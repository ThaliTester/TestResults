#### Test 6391070405f2a33_thali08_samsung-SM-N910C Logs


```
--------- beginning of system
03-24 15:29:10.625  3390  3429 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:29:10.625  3390  3429 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:29:10.625  3390  3429 D BatteryService: online:4, current avg:49, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:59
,03-24 15:29:10.625  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-24 15:29:10.635  3390  3390 I MotionRecognitionService: Plugged
03-24 15:29:10.635  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:29:10.635  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-24 15:29:10.635  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
--------- beginning of main
03-24 15:29:10.645  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:29:10.635  3390  3429 D BatteryService: stay LED for fully charged
03-24 15:29:10.645  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:29:10.645  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
03-24 15:29:10.655  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-24 15:29:10.655  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
03-24 15:29:10.670  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:29:10.670  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:29:10.670  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:29:10.670  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:29:11.090 11123 11123 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
03-24 15:29:11.100 11123 11123 D AndroidRuntime: CheckJNI is OFF
03-24 15:29:11.100 11123 11123 D AndroidRuntime: readGMSProperty: start
03-24 15:29:11.100 11123 11123 D AndroidRuntime: readGMSProperty: already setted!!
03-24 15:29:11.100 11123 11123 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-24 15:29:11.100 11123 11123 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-24 15:29:11.100 11123 11123 D AndroidRuntime: readGMSProperty: end
03-24 15:29:11.100 11123 11123 D AndroidRuntime: addProductProperty: start
03-24 15:29:11.265  3390  3620 V AlarmManager: waitForAlarm result :4
03-24 15:29:11.275 11123 11123 E AffinityControl: AffinityControl: registerfunction enter
03-24 15:29:11.300 11123 11123 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-24 15:29:11.315  3390  3853 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
03-24 15:29:11.320  3390  3853 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-24 15:29:11.350  3390  3853 W ActivityManager: mDVFSHelper.acquire()
03-24 15:29:11.355  3390  3853 V WindowManager: addAppToken: AppWindowToken{2d14f0f1 token=Token{2b10f098 ActivityRecord{34da1a7b u0 com.test.thalitest/.MainActivity t42}}} to stack=1 task=42 at 0
03-24 15:29:11.360  3390  3853 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-24 15:29:11.360  3390  3853 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-24 15:29:11.360  3390  3853 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-24 15:29:11.360  3390  3853 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-24 15:29:11.365  3390  3581 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-24 15:29:11.365  3390  3581 D PhoneWindow: *FMB* installDecor flags : -2122120936
03-24 15:29:11.365  3390  3581 D SecWifiDisplayUtil: Metadata value : none
03-24 15:29:11.370  3390  3581 V WindowManager: Adding window Window{37193ab0 u0 d0 Starting com.test.thalitest} at 3 of 7 (after Window{27c075d2 u0 d0 com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity})
03-24 15:29:11.380 11146 11146 E Zygote  : MountEmulatedStorage()
03-24 15:29:11.380 11146 11146 E Zygote  : v2
03-24 15:29:11.380 11146 11146 I libpersona: KNOX_SDCARD checking this for 10011
03-24 15:29:11.380 11146 11146 I libpersona: KNOX_SDCARD not a persona
03-24 15:29:11.385  3390  3853 I ActivityManager: Start proc 11146:com.test.thalitest/u0a11 for activity com.test.thalitest/.MainActivity
03-24 15:29:11.385  3390  3853 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
03-24 15:29:11.385  3390  3581 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-24 15:29:11.385  3390  3581 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
03-24 15:29:11.385  3390  3853 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-24 15:29:11.385  3390  3853 D InputDispatcher: Focused application set to: xxxx
03-24 15:29:11.385  3390  3853 D MultiWindowConverter: dismissGuide() : Before attaching the guide view, mForceDismissGuide : false
03-24 15:29:11.385  3390  3853 D InputDispatcher: Focus left window: 6544
03-24 15:29:11.390 11123 11123 D AndroidRuntime: Shutting down VM
03-24 15:29:11.390  2862  2862 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=404, uhalitest
03-24 15:29:11.395 11146 11146 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
03-24 15:29:11.395 11146 11146 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
03-24 15:29:11.400 11146 11146 E Zygote  : accessInfo : 0
03-24 15:29:11.400 11146 11146 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-24 15:29:11.410  3390  3581 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3390 uid:1000
03-24 15:29:11.410  3390  3581 D PointerIcon: setMouseCustomIcon IconType is same.101
03-24 15:29:11.410  3390  3581 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3390 uid:1000
03-24 15:29:11.410  3390  3581 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
03-24 15:29:11.430 11146 11146 D TimaKeyStoreProvider: TimaSignature is unavailable
03-24 15:29:11.430 11146 11146 D ActivityThread: Added TimaKeyStore provider
03-24 15:29:11.435  3390  4268 D PowerManagerService: setKeyboardVisibility: false
03-24 15:29:11.440  3390  3579 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{37193ab0 u0 d0 Starting com.test.thalitest}
03-24 15:29:11.440  3390  4268 D ActivityManager:  Launching com.test.thalitest, updated priority
03-24 15:29:11.455  3390  4268 I ActivityManager: Skip updateThumbnail for r=ActivityRecord{34da1a7b u0 com.test.thalitest/.MainActivity t42}
03-24 15:29:11.475  2862 10867 I SurfaceFlinger: id=12 Removed YUIInstallC (5/9)
03-24 15:29:11.475  2862  4525 I SurfaceFlinger: id=12 Removed YUIInstallC (-2/9)
03-24 15:29:11.480  6544  6544 V ActivityThread: updateVisibility : ActivityRecord{130e6c3 token=android.os.BinderProxy@16baa8c1 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
,03-24 15:29:11.630  3390  6051 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
03-24 15:29:11.665 11146 11146 D SecWifiDisplayUtil: Metadata value : none
03-24 15:29:11.670  3390  6051 D SSRM:n  : SIOP:: AP = 280, PST = 287 (W:14), CUR = 49, LCD = 0
03-24 15:29:11.715 11146 11146 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
03-24 15:29:11.730 11146 11146 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 6049-6051)
03-24 15:29:11.730 11146 11146 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-24 15:29:11.750 11146 11174 W System.err: remove failed: ENOENT (No such file or directory) : /data/data/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
03-24 15:29:11.750 11146 11146 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {201846a0}
03-24 15:29:11.750 11146 11146 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-24 15:29:11.750 11146 11146 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
03-24 15:29:11.775 11146 11146 I BrowserStartupController: Initializing chromium process, singleProcess=true
03-24 15:29:11.775 11146 11146 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-24 15:29:11.780 11146 11146 E SysUtils: ApplicationContext is null in ApplicationStatus
03-24 15:29:11.805 11146 11146 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
03-24 15:29:11.805 11146 11146 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=37 off=50556 len=3379
03-24 15:29:11.805 11146 11146 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:38 off:7638088 len:1165478
03-24 15:29:11.885 11146 11201 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
03-24 15:29:11.920 11146 11146 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-24 15:29:11.935 11146 11146 W AwContents: onDetachedFromWindow called when already detached. Ignoring
03-24 15:29:11.950 11146 11146 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-24 15:29:11.950 11146 11146 D PhoneWindow: *FMB* installDecor flags : -2139027200
03-24 15:29:11.955 11146 11146 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
03-24 15:29:11.960 11146 11146 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-24 15:29:11.960 11146 11146 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-24 15:29:12.010 11146 11214 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
03-24 15:29:12.015  3390  3965 V WindowManager: Adding window Window{24d9bbd1 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity} at 3 of 8 (before Window{37193ab0 u0 d0 Starting com.test.thalitest})
03-24 15:29:12.020  3390  4707 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-24 15:29:12.020  3390  4707 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-24 15:29:12.020  3390  4707 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-24 15:29:12.020  3390  3390 D KnoxTimeoutHandler: handleActiveUserChange for user 0
03-24 15:29:12.020  3390  3390 E EnterpriseSharedDevicePolicy: isSharedDeviceEnabled
03-24 15:29:12.020  3390  3390 I EnterpriseSharedDevicePolicy: isSharedDeviceEnabled in Service
03-24 15:29:12.025  3390  3390 I EnterpriseSharedDevicePolicy: Get Result: -1
03-24 15:29:12.025  3390  3390 I EnterpriseSharedDevicePolicy: status: false
03-24 15:29:12.025  3390  3390 D PersonaManagerService: getPersonasForUser(): returning null!
03-24 15:29:12.025  3390  3390 I KnoxTimeoutHandler: Shared devices show user statefalse
03-24 15:29:12.035 11146 11146 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-24 15:29:12.035 11146 11146 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
03-24 15:29:12.040 11146 11146 D SecWifiDisplayUtil: Metadata value : none
03-24 15:29:12.050  2862  2862 I SurfaceFlinger: id=15 createSurf (1x1),1 flag=404, NainActivit
03-24 15:29:12.050  3390  3652 D MultiWindowConverter: dismissGuide() : Before attaching the guide view, mForceDismissGuide : false
03-24 15:29:12.055  3390  3652 D InputDispatcher: Focus entered window: 11146
03-24 15:29:12.060  3390  3581 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3390 uid:1000
03-24 15:29:12.060  3390  3581 D PointerIcon: setMouseCustomIcon IconType is same.101
03-24 15:29:12.060  3390  3581 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3390 uid:1000
03-24 15:29:12.060  3390  3581 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
03-24 15:29:12.060 11146 11146 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
03-24 15:29:12.060 11146 11214 I OpenGLRenderer: Initialized EGL, version 1.4
03-24 15:29:12.065 11146 11214 I OpenGLRenderer: HWUI protection enabled for context ,  &this =0xae5b7b50 ,&mEglDisplay = 1 , &mEglConfig = -1267793648 
03-24 15:29:12.065 11146 11214 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
03-24 15:29:12.065 11146 11214 D OpenGLRenderer: Enabling debug mode 0
03-24 15:29:12.070 11146 11214 D mali_winsys: new_window_surface returns 0x3000,  [1440x2560]-format:1
03-24 15:29:12.070 11146 11146 V ActivityThread: updateVisibility : ActivityRecord{28d990e8 token=android.os.BinderProxy@fd475da {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
03-24 15:29:12.145  3390  3965 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
03-24 15:29:12.150  3390  3581 I ActivityManager: Displayed Component not be shown by security: +557ms (total +1m27s901ms)
03-24 15:29:12.150  3727  3727 D PanelView: There is/are notification(s) 
03-24 15:29:12.150  3390  3581 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{34da1a7b u0 com.test.thalitest/.MainActivity t42} time:186474
03-24 15:29:12.150  3390  3581 W ActivityManager: mDVFSHelper.release()
03-24 15:29:12.155  2862  3035 I SurfaceFlinger: id=14 Removed uhalitest (7/9)
03-24 15:29:12.155  2862  3231 I SurfaceFlinger: id=14 Removed uhalitest (-2/9)
03-24 15:29:12.180 11146 11146 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
03-24 15:29:12.180 11146 11146 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@fd475da time:186501
03-24 15:29:12.205 11146 11146 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 11146
,03-24 15:29:12.330 11146 11146 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-24 15:29:12.390 11146 11219 D jxcore_app_log: JniHelper::setJavaVM(0xb449d200), pthread_self() = -1623034368
,03-24 15:29:12.395 11146 11219 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-24 15:29:12.395 11146 11219 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-24 15:29:12.395 11146 11219 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-24 15:29:12.395 11146 11219 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-24 15:29:12.395 11146 11219 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-24 15:29:12.395 11146 11219 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15cc3e71 added. We now have 1 listener(s)
,03-24 15:29:12.400 11146 11219 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: E0:DB:10:14:E2:C0
,03-24 15:29:12.400 11146 11219 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
,03-24 15:29:12.405 11146 11219 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
03-24 15:29:12.405 11146 11219 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,03-24 15:29:12.405 11146 11174 W System.err: remove failed: ENOENT (No such file or directory) : /data/data/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,03-24 15:29:12.405 11146 11219 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-24 15:29:12.405 11146 11219 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-24 15:29:12.405 11146 11219 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-24 15:29:12.405 11146 11219 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: E0:DB:10:14:E2:C0
03-24 15:29:12.405 11146 11219 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-24 15:29:12.405 11146 11219 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-24 15:29:12.405 11146 11219 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
03-24 15:29:12.405 11146 11219 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-24 15:29:12.405 11146 11219 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-24 15:29:12.405 11146 11219 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-24 15:29:12.405 11146 11219 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-24 15:29:12.405 11146 11219 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b7449c4 added. We now have 1 listener(s)
03-24 15:29:12.405 11146 11219 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-24 15:29:12.410 11146 11219 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,03-24 15:29:12.415 11146 11219 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
03-24 15:29:12.415 11146 11219 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
,03-24 15:29:12.415 11146 11219 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-24 15:29:12.415 11146 11219 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,03-24 15:29:12.415 11146 11219 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-24 15:29:12.420 11146 11219 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is E0:DB:10:14:E2:C0
,03-24 15:29:12.425 11146 11219 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 15:29:12.425 11146 11219 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 15:29:12.425 11146 11219 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 15:29:12.425 11146 11219 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 15:29:12.425 11146 11219 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 15:29:12.425 11146 11219 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 15:29:12.425 11146 11219 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 15:29:12.425 11146 11219 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-24 15:29:12.425 11146 11219 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-24 15:29:12.425 11146 11219 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-24 15:29:12.425 11146 11219 I io.jxcore.node.LifeCycleMonitor: start: OK
,03-24 15:29:12.425 11146 11146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-24 15:29:12.430 11146 11146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-24 15:29:12.450 11146 11146 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-24 15:29:12.830 11146 11225 W jxcore-log: Initializing JXcore engine
03-24 15:29:12.830 11146 11225 W jxcore-log: JXcore engine is ready
,03-24 15:29:12.860  4701  4701 E auditd  : In denial and Property audit_ondenial is set to 1 
,03-24 15:29:12.860  4701  4701 E audit   : type=1400 msg=audit(1458829752.855:196): avc:  denied  { ioctl } for  pid=11225 comm="Thread-1539" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2210 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
03-24 15:29:12.860  3390  3577 D SecurityLogAgent:SEDenialService: Got Modify Event and sending Denial Intent foraudit.log
03-24 15:29:12.860  4701  4701 E audit   :  SEPF_SM-N910C_5.1.1_0038
03-24 15:29:12.860  3390  3577 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.android.server.SEDenialService$AuditFileObserver.onEvent:80 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
03-24 15:29:12.860  4701  4701 E audit   : type=1300 msg=audit(1458829752.855:196): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=2 a3=95f008d8 items=0 ppid=2902 ppcomm=main pid=11225 auid=4294967295 uid=10011 gid=10011 euid=10011 suid=10011 fsuid=10011 egid=10011 sgid=10011 fsgid=10011 ses=4294967295 tty=(none) comm="Thread-1539" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
03-24 15:29:12.860  4701  4701 E audit   : type=1320 msg=audit(1458829752.855:196): 
,03-24 15:29:12.860  3390  3577 D SecurityLogAgent:SEDenialService: audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,03-24 15:29:12.860  3390  3572 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-24 15:29:12.860  3390  3572 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-24 15:29:12.860  3390  3572 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-24 15:29:12.860  3390  3572 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-24 15:29:12.865 11146 11225 W jxcore-log: Starting JXcore engine
,03-24 15:29:12.875 11226 11226 E Zygote  : MountEmulatedStorage()
03-24 15:29:12.875 11226 11226 I libpersona: KNOX_SDCARD checking this for 1000
03-24 15:29:12.875 11226 11226 E Zygote  : v2
03-24 15:29:12.875 11226 11226 I libpersona: KNOX_SDCARD not a persona
,03-24 15:29:12.875 11226 11226 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
,03-24 15:29:12.880  3390  3572 I ActivityManager: Start proc 11226:com.samsung.android.securitylogagent/1000 for broadcast-3 com.samsung.android.securitylogagent/.receivers.SeDenialReceiver
,03-24 15:29:12.880 11226 11226 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
,03-24 15:29:12.880 11226 11226 E Zygote  : accessInfo : 0
,03-24 15:29:12.880 11226 11226 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-24 15:29:12.900 11226 11226 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-24 15:29:12.900 11226 11226 D ActivityThread: Added TimaKeyStore provider
,03-24 15:29:12.905  3390  3429 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3d33e7c5 u0 samsung.intent.action.knox.DENIAL_NOTIFICATION} DELIVERED for app ProcessRecord{2715e51a 11226:com.samsung.android.securitylogagent/1000}
,03-24 15:29:12.910 11146 11225 W jxcore-log: Platform android
03-24 15:29:12.910 11146 11225 W jxcore-log: 
03-24 15:29:12.910 11146 11225 W jxcore-log: Process ARCH arm
03-24 15:29:12.910 11146 11225 W jxcore-log: 
,03-24 15:29:12.925 11226 11226 D SecurityLogAgent:  SeDenialReceiver : Intent received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,03-24 15:29:12.925 11226 11226 D SecurityLogAgent:  SeDenialReceiver : File path = null
,03-24 15:29:12.930  3390  4257 I ActivityManager: Killing 10129:com.sec.spp.push:RemoteNotiProcess/u0a39 (adj 15): emptyCount ##31
,03-24 15:29:13.005 11146 11225 I jxcore-log: JXcore Cordova bridge is ready!
03-24 15:29:13.005 11146 11225 I jxcore-log: 
03-24 15:29:13.005 11146 11225 W jxcore-log: JXcore engine is started
,03-24 15:29:13.015 11146 11219 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-24 15:29:13.015 11146 11146 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-24 15:29:14.365  3390  3693 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/42_task.xml.bak
,03-24 15:29:15.470  3390  6082 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-24 15:29:18.335  3390  3864 E Watchdog: !@Sync 6 [03-24 15:29:18.341]
,03-24 15:29:18.740 11146 11225 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 15:29:18.740 11146 11225 I jxcore-log: 
,03-24 15:29:18.740 11146 11225 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 15:29:18.740 11146 11225 I jxcore-log: 
,03-24 15:29:18.740 11146 11225 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 15:29:18.740 11146 11225 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 15:29:18.740 11146 11225 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 15:29:18.740 11146 11225 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 15:29:18.740 11146 11225 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 15:29:18.740 11146 11225 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 15:29:18.740 11146 11225 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 15:29:18.740 11146 11225 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 15:29:18.745 11146 11225 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 15:29:18.745 11146 11225 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 15:29:18.745 11146 11225 I jxcore-log: 
,03-24 15:29:18.745 11146 11225 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 15:29:18.745 11146 11225 I jxcore-log: 
,03-24 15:29:19.070 11146 11225 I jxcore-log: Unit Test app is loaded
03-24 15:29:19.070 11146 11225 I jxcore-log: 
,03-24 15:29:19.075 11146 11225 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 15:29:19.075 11146 11225 I jxcore-log: 
,03-24 15:29:19.080 11146 11146 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,03-24 15:29:19.080 11146 11225 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,03-24 15:29:19.080 11146 11225 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
03-24 15:29:19.080 11146 11225 I jxcore-log: 
,03-24 15:29:19.080 11146 11225 I jxcore-log: My device name is: samsung-SM-N910C
03-24 15:29:19.080 11146 11225 I jxcore-log: 
,03-24 15:29:20.740  3390  3853 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:29:20.740  3390  3853 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:29:20.740  3390  3853 D BatteryService: online:4, current avg:-79, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-202
03-24 15:29:20.740  3390  3853 D BatteryService: stay LED for fully charged
03-24 15:29:20.740  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-24 15:29:20.740  3390  3390 I MotionRecognitionService: Plugged
03-24 15:29:20.740  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:29:20.740  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-24 15:29:20.740  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:29:20.745  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:29:20.745  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:29:20.745  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:29:20.750  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-24 15:29:20.750  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:29:20.765  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:29:20.765  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:29:20.765  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:29:20.765  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:29:21.405  3390  3593 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,03-24 15:29:21.415  3390  3593 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,03-24 15:29:21.465 11146 11225 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
03-24 15:29:21.465 11146 11225 I jxcore-log: 
,03-24 15:29:21.575  2892  4752 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-24 15:29:21.675 11146 11225 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
03-24 15:29:21.675 11146 11225 I jxcore-log: 
,03-24 15:29:21.680  3390  6051 D SSRM:n  : SIOP:: AP = 310, PST = 287 (W:10), CUR = -79, LCD = 0
,03-24 15:29:21.680 11146 11225 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
03-24 15:29:21.680 11146 11225 I jxcore-log: 
,03-24 15:29:21.680 11146 11225 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
03-24 15:29:21.680 11146 11225 I jxcore-log: 
,03-24 15:29:21.705 11146 11225 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
03-24 15:29:21.705 11146 11225 I jxcore-log: 
,03-24 15:29:21.715 11146 11225 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
03-24 15:29:21.715 11146 11225 I jxcore-log: 
,03-24 15:29:21.715 11146 11225 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
03-24 15:29:21.715 11146 11225 I jxcore-log: 
,03-24 15:29:22.930 11146 11225 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
03-24 15:29:22.930 11146 11225 I jxcore-log: 
,03-24 15:29:22.940 11146 11225 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
03-24 15:29:22.940 11146 11225 I jxcore-log: 
,03-24 15:29:22.945 11146 11225 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
03-24 15:29:22.945 11146 11225 I jxcore-log: 
,03-24 15:29:23.020 11146 11225 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
03-24 15:29:23.020 11146 11225 I jxcore-log: 
,03-24 15:29:23.050 11146 11225 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
03-24 15:29:23.050 11146 11225 I jxcore-log: 
,03-24 15:29:23.080 11146 11225 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
03-24 15:29:23.080 11146 11225 I jxcore-log: 
,03-24 15:29:23.160 11146 11225 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
03-24 15:29:23.160 11146 11225 I jxcore-log: 
,03-24 15:29:23.165 11146 11225 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
03-24 15:29:23.165 11146 11225 I jxcore-log: 
,03-24 15:29:23.165 11146 11225 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
03-24 15:29:23.165 11146 11225 I jxcore-log: 
,03-24 15:29:23.175 11146 11225 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
03-24 15:29:23.175 11146 11225 I jxcore-log: 
,03-24 15:29:23.185 11146 11225 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
03-24 15:29:23.185 11146 11225 I jxcore-log: 
,03-24 15:29:23.245 11146 11225 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
03-24 15:29:23.245 11146 11225 I jxcore-log: 
,03-24 15:29:23.250 11146 11225 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
03-24 15:29:23.250 11146 11225 I jxcore-log: 
,03-24 15:29:23.265 11146 11225 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
03-24 15:29:23.265 11146 11225 I jxcore-log: 
,03-24 15:29:30.880  3390  4710 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:29:30.880  3390  4710 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:29:30.880  3390  4710 D BatteryService: online:4, current avg:-23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:48
,03-24 15:29:30.885  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-24 15:29:30.885  3390  4710 D BatteryService: stay LED for fully charged
,03-24 15:29:30.895  3390  3390 I MotionRecognitionService: Plugged,
,03-24 15:29:30.895  3390  3390 D MotionRecognitionService:   cableConnection= 1
,03-24 15:29:30.895  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
,03-24 15:29:30.895  3390  3390 D MotionRecognitionService: skip setTransmitPower. ,
03-24 15:29:30.905  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:29:30.905  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,03-24 15:29:30.905  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-24 15:29:30.925  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-24 15:29:30.925  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:29:30.940  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:29:30.940  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:29:30.940  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:29:30.940  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:29:31.400  3390  3587 I PowerManagerService: [PWL] Off : 140s ago
,03-24 15:29:31.705  3390  6051 D SSRM:n  : SIOP:: AP = 300, PST = 285 (W:10), CUR = -23, LCD = 0
,03-24 15:29:33.235 11146 11225 I jxcore-log: TAP version 13
03-24 15:29:33.235 11146 11225 I jxcore-log: 
,03-24 15:29:33.235 11146 11225 I jxcore-log: # setup
03-24 15:29:33.235 11146 11225 I jxcore-log: 
,03-24 15:29:33.355 11146 11225 I jxcore-log: # 1. calling createNativeListener directly rejects
03-24 15:29:33.355 11146 11225 I jxcore-log: 
,03-24 15:29:33.930 11146 11225 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 15:29:33.930 11146 11225 I jxcore-log: 
,03-24 15:29:33.940 11146 11225 I jxcore-log: DEBUG createNativeListener: listening 60894
03-24 15:29:33.940 11146 11225 I jxcore-log: 
,03-24 15:29:33.950 11146 11225 I jxcore-log: ok 1 Should throw
03-24 15:29:33.950 11146 11225 I jxcore-log: 
,03-24 15:29:33.955 11146 11225 I jxcore-log: # teardown
03-24 15:29:33.955 11146 11225 I jxcore-log: 
,03-24 15:29:34.045 11146 11225 I jxcore-log: # setup
03-24 15:29:34.045 11146 11225 I jxcore-log: 
,03-24 15:29:34.640 11146 11225 I jxcore-log: # 2. emits incomingConnectionState
03-24 15:29:34.640 11146 11225 I jxcore-log: 
,03-24 15:29:34.840 11146 11225 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 15:29:34.840 11146 11225 I jxcore-log: 
,03-24 15:29:34.850 11146 11225 I jxcore-log: DEBUG createNativeListener: listening 51971
03-24 15:29:34.850 11146 11225 I jxcore-log: 
,03-24 15:29:34.860 11146 11225 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 15:29:34.860 11146 11225 I jxcore-log: 
,03-24 15:29:34.865 11146 11225 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 15:29:34.865 11146 11225 I jxcore-log: 
,03-24 15:29:34.880 11146 11225 I jxcore-log: DEBUG createNativeListener: new mux
03-24 15:29:34.880 11146 11225 I jxcore-log: 
,03-24 15:29:34.885 11146 11225 I jxcore-log: ok 2 initial connection state should be CONNECTED
03-24 15:29:34.885 11146 11225 I jxcore-log: 
,03-24 15:29:34.910 11146 11225 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 15:29:34.910 11146 11225 I jxcore-log: 
,03-24 15:29:34.915 11146 11225 I jxcore-log: ok 3 final connection state should be DISCONNECTED
03-24 15:29:34.915 11146 11225 I jxcore-log: 
,03-24 15:29:34.925 11146 11225 I jxcore-log: # teardown
03-24 15:29:34.925 11146 11225 I jxcore-log: 
,03-24 15:29:35.015 11146 11225 I jxcore-log: # setup
03-24 15:29:35.015 11146 11225 I jxcore-log: 
,03-24 15:29:35.105 11146 11225 I jxcore-log: # 3. emits routerPortConnectionFailed
03-24 15:29:35.105 11146 11225 I jxcore-log: 
,03-24 15:29:35.255 11146 11225 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 15:29:35.255 11146 11225 I jxcore-log: 
,03-24 15:29:35.255 11146 11225 I jxcore-log: DEBUG createNativeListener: listening 48429
03-24 15:29:35.255 11146 11225 I jxcore-log: 
,03-24 15:29:35.265 11146 11225 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 15:29:35.265 11146 11225 I jxcore-log: 
,03-24 15:29:35.265 11146 11225 I jxcore-log: DEBUG createNativeListener: creating incoming mux
,03-24 15:29:35.265 11146 11225 I jxcore-log: 
,03-24 15:29:35.270 11146 11225 I jxcore-log: DEBUG createNativeListener: new mux
03-24 15:29:35.270 11146 11225 I jxcore-log: 
,03-24 15:29:35.305 11146 11225 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:35.305 11146 11225 I jxcore-log: 
,03-24 15:29:35.310 11146 11225 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:35.310 11146 11225 I jxcore-log: 
,03-24 15:29:35.315 11146 11225 I jxcore-log: DEBUG createNativeListener: 
03-24 15:29:35.315 11146 11225 I jxcore-log: 
,03-24 15:29:35.320 11146 11225 I jxcore-log: ok 4 tried to connect to right port
03-24 15:29:35.320 11146 11225 I jxcore-log: 
,03-24 15:29:35.320 11146 11225 I jxcore-log: ok 5 failed due to refused connection
03-24 15:29:35.320 11146 11225 I jxcore-log: 
,03-24 15:29:35.320 11146 11225 I jxcore-log: ok 6 routerPortConnectionFailed is emitted
03-24 15:29:35.320 11146 11225 I jxcore-log: 
,03-24 15:29:35.330 11146 11225 I jxcore-log: # teardown
03-24 15:29:35.330 11146 11225 I jxcore-log: 
,03-24 15:29:35.335 11146 11225 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:35.335 11146 11225 I jxcore-log: 
,03-24 15:29:35.475  3390  6082 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-24 15:29:35.485 11146 11225 I jxcore-log: DEBUG createNativeListener: mux close
03-24 15:29:35.485 11146 11225 I jxcore-log: 
,03-24 15:29:35.495 11146 11225 I jxcore-log: # setup
03-24 15:29:35.495 11146 11225 I jxcore-log: 
,03-24 15:29:35.500 11146 11225 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 15:29:35.500 11146 11225 I jxcore-log: 
,03-24 15:29:35.715 11146 11225 I jxcore-log: # 4. native server connections all up
03-24 15:29:35.715 11146 11225 I jxcore-log: 
,03-24 15:29:35.830 11146 11225 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 15:29:35.830 11146 11225 I jxcore-log: 
,03-24 15:29:35.840 11146 11225 I jxcore-log: DEBUG createNativeListener: listening 39021
03-24 15:29:35.840 11146 11225 I jxcore-log: 
,03-24 15:29:35.850 11146 11225 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 15:29:35.850 11146 11225 I jxcore-log: 
,03-24 15:29:35.855 11146 11225 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 15:29:35.855 11146 11225 I jxcore-log: 
,03-24 15:29:35.855 11146 11225 I jxcore-log: DEBUG createNativeListener: new mux
03-24 15:29:35.855 11146 11225 I jxcore-log: 
,03-24 15:29:35.890 11146 11225 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:35.890 11146 11225 I jxcore-log: 
,03-24 15:29:35.895 11146 11225 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:35.895 11146 11225 I jxcore-log: 
,03-24 15:29:35.900 11146 11225 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:35.900 11146 11225 I jxcore-log: 
,03-24 15:29:35.900 11146 11225 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:35.900 11146 11225 I jxcore-log: 
,03-24 15:29:35.935 11146 11225 I jxcore-log: ok 7 Send/recvd #1 should be equal length
03-24 15:29:35.935 11146 11225 I jxcore-log: 
,03-24 15:29:35.935 11146 11225 I jxcore-log: ok 8 Send/recvd #1 should be same
03-24 15:29:35.935 11146 11225 I jxcore-log: 
,03-24 15:29:35.940 11146 11225 I jxcore-log: ok 9 Send/recvd #2 should be equal length
03-24 15:29:35.940 11146 11225 I jxcore-log: 
,03-24 15:29:35.940 11146 11225 I jxcore-log: ok 10 Send/recvd #2 should be same
03-24 15:29:35.940 11146 11225 I jxcore-log: 
,03-24 15:29:35.945 11146 11225 I jxcore-log: ok 11 Should be exactly 2 client sockets
03-24 15:29:35.945 11146 11225 I jxcore-log: 
,03-24 15:29:35.965 11146 11225 I jxcore-log: # teardown
03-24 15:29:35.965 11146 11225 I jxcore-log: 
,03-24 15:29:36.060 11146 11225 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:36.060 11146 11225 I jxcore-log: 
,03-24 15:29:36.070 11146 11225 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:36.070 11146 11225 I jxcore-log: 
,03-24 15:29:36.075 11146 11225 I jxcore-log: DEBUG createNativeListener: mux close
03-24 15:29:36.075 11146 11225 I jxcore-log: 
,03-24 15:29:36.080 11146 11225 I jxcore-log: # setup
03-24 15:29:36.080 11146 11225 I jxcore-log: 
,03-24 15:29:36.080 11146 11225 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 15:29:36.080 11146 11225 I jxcore-log: 
,03-24 15:29:36.200 11146 11225 I jxcore-log: # 5. native server - closing incoming stream cleans outgoing socket
03-24 15:29:36.200 11146 11225 I jxcore-log: 
,03-24 15:29:36.340 11146 11225 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 15:29:36.340 11146 11225 I jxcore-log: 
,03-24 15:29:36.345 11146 11225 I jxcore-log: DEBUG createNativeListener: listening 45535
03-24 15:29:36.345 11146 11225 I jxcore-log: 
,03-24 15:29:36.355 11146 11225 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 15:29:36.355 11146 11225 I jxcore-log: 
,03-24 15:29:36.360 11146 11225 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 15:29:36.360 11146 11225 I jxcore-log: 
,03-24 15:29:36.365 11146 11225 I jxcore-log: DEBUG createNativeListener: new mux
03-24 15:29:36.365 11146 11225 I jxcore-log: 
,03-24 15:29:36.390 11146 11225 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:36.390 11146 11225 I jxcore-log: 
,03-24 15:29:36.400 11146 11225 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:36.400 11146 11225 I jxcore-log: 
,03-24 15:29:36.420 11146 11225 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:36.420 11146 11225 I jxcore-log: 
,03-24 15:29:36.440 11146 11225 I jxcore-log: ok 12 socket shouldn't close until after stream
03-24 15:29:36.440 11146 11225 I jxcore-log: 
,03-24 15:29:36.440 11146 11225 I jxcore-log: ok 13 incoming remains open
03-24 15:29:36.440 11146 11225 I jxcore-log: 
,03-24 15:29:36.450 11146 11225 I jxcore-log: # teardown
03-24 15:29:36.450 11146 11225 I jxcore-log: 
,03-24 15:29:36.535 11146 11225 I jxcore-log: DEBUG createNativeListener: mux close
03-24 15:29:36.535 11146 11225 I jxcore-log: 
,03-24 15:29:36.540 11146 11225 I jxcore-log: # setup
03-24 15:29:36.540 11146 11225 I jxcore-log: 
,03-24 15:29:36.540 11146 11225 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 15:29:36.540 11146 11225 I jxcore-log: 
,03-24 15:29:36.635 11146 11225 I jxcore-log: # 6. native server - closing incoming connection cleans outgoing socket
03-24 15:29:36.635 11146 11225 I jxcore-log: 
,03-24 15:29:36.745 11146 11225 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 15:29:36.745 11146 11225 I jxcore-log: 
,03-24 15:29:36.750 11146 11225 I jxcore-log: DEBUG createNativeListener: listening 36734
03-24 15:29:36.750 11146 11225 I jxcore-log: 
,03-24 15:29:36.760 11146 11225 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 15:29:36.760 11146 11225 I jxcore-log: 
,03-24 15:29:36.760 11146 11225 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 15:29:36.760 11146 11225 I jxcore-log: 
,03-24 15:29:36.765 11146 11225 I jxcore-log: DEBUG createNativeListener: new mux
03-24 15:29:36.765 11146 11225 I jxcore-log: 
,03-24 15:29:36.775 11146 11225 I jxcore-log: ok 14 we should not have gotten an error
03-24 15:29:36.775 11146 11225 I jxcore-log: 
,03-24 15:29:36.780 11146 11225 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:36.780 11146 11225 I jxcore-log: 
,03-24 15:29:36.790 11146 11225 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:36.790 11146 11225 I jxcore-log: 
,03-24 15:29:36.800 11146 11225 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:36.800 11146 11225 I jxcore-log: 
,03-24 15:29:36.805 11146 11225 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 15:29:36.805 11146 11225 I jxcore-log: 
,03-24 15:29:36.815 11146 11225 I jxcore-log: ok 15 socket shouldn't close until after incoming
03-24 15:29:36.815 11146 11225 I jxcore-log: 
,03-24 15:29:36.815 11146 11225 I jxcore-log: ok 16 incoming is cleaned up
03-24 15:29:36.815 11146 11225 I jxcore-log: 
,03-24 15:29:36.820 11146 11225 I jxcore-log: # teardown
03-24 15:29:36.820 11146 11225 I jxcore-log: 
,03-24 15:29:37.530 11146 11225 I jxcore-log: # setup
03-24 15:29:37.530 11146 11225 I jxcore-log: 
,03-24 15:29:37.615 11146 11225 I jxcore-log: # 7. native server - closing outgoing socket cleans associated mux stream
03-24 15:29:37.615 11146 11225 I jxcore-log: 
,03-24 15:29:39.255 11146 11225 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 15:29:39.255 11146 11225 I jxcore-log: 
,03-24 15:29:39.260 11146 11225 I jxcore-log: DEBUG createNativeListener: listening 39895
03-24 15:29:39.260 11146 11225 I jxcore-log: 
,03-24 15:29:39.270 11146 11225 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 15:29:39.270 11146 11225 I jxcore-log: 
,03-24 15:29:39.275 11146 11225 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 15:29:39.275 11146 11225 I jxcore-log: 
,03-24 15:29:39.280 11146 11225 I jxcore-log: DEBUG createNativeListener: new mux
03-24 15:29:39.280 11146 11225 I jxcore-log: 
,03-24 15:29:39.295 11146 11225 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:39.295 11146 11225 I jxcore-log: 
,03-24 15:29:39.300 11146 11225 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:39.300 11146 11225 I jxcore-log: 
,03-24 15:29:39.315 11146 11225 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:39.315 11146 11225 I jxcore-log: 
,03-24 15:29:39.330 11146 11225 I jxcore-log: ok 17 stream was closed
03-24 15:29:39.330 11146 11225 I jxcore-log: 
,03-24 15:29:39.330 11146 11225 I jxcore-log: ok 18 incoming should survive
03-24 15:29:39.330 11146 11225 I jxcore-log: 
,03-24 15:29:39.330 11146 11225 I jxcore-log: ok 19 mux should have no streams
03-24 15:29:39.330 11146 11225 I jxcore-log: 
,03-24 15:29:39.340 11146 11225 I jxcore-log: # teardown
03-24 15:29:39.340 11146 11225 I jxcore-log: 
,03-24 15:29:39.790 11146 11225 I jxcore-log: DEBUG createNativeListener: mux close
03-24 15:29:39.790 11146 11225 I jxcore-log: 
,03-24 15:29:39.800 11146 11225 I jxcore-log: # setup
03-24 15:29:39.800 11146 11225 I jxcore-log: 
,03-24 15:29:39.805 11146 11225 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 15:29:39.805 11146 11225 I jxcore-log: 
,03-24 15:29:41.020  3390  4045 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:29:41.020  3390  4045 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:29:41.020  3390  4045 D BatteryService: online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:50
,03-24 15:29:41.025  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-24 15:29:41.025  3390  4045 D BatteryService: stay LED for fully charged
,03-24 15:29:41.030  3390  3390 I MotionRecognitionService: Plugged,
03-24 15:29:41.035  3390  3390 D MotionRecognitionService:   cableConnection= 1
,03-24 15:29:41.035  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
03-24 15:29:41.035  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:29:41.045  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:29:41.045  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:29:41.045  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-24 15:29:41.055  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-24 15:29:41.055  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:29:41.070  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:29:41.070  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:29:41.070  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:29:41.070  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:29:41.730  3390  6051 D SSRM:n  : SIOP:: AP = 290, PST = 286 (W:10), CUR = 26, LCD = 0,
,03-24 15:29:42.935 11146 11225 I jxcore-log: # 8. native server - closing the whole server cleans everything up
03-24 15:29:42.935 11146 11225 I jxcore-log: 
,03-24 15:29:44.635 11146 11225 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 15:29:44.635 11146 11225 I jxcore-log: 
,03-24 15:29:44.640 11146 11225 I jxcore-log: DEBUG createNativeListener: listening 53757
03-24 15:29:44.640 11146 11225 I jxcore-log: 
,03-24 15:29:44.655 11146 11225 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 15:29:44.655 11146 11225 I jxcore-log: 
,03-24 15:29:44.655 11146 11225 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 15:29:44.655 11146 11225 I jxcore-log: 
,03-24 15:29:44.660 11146 11225 I jxcore-log: DEBUG createNativeListener: new mux
03-24 15:29:44.660 11146 11225 I jxcore-log: 
,03-24 15:29:44.670 11146 11225 I jxcore-log: ok 20 we should not have gotten an error
03-24 15:29:44.670 11146 11225 I jxcore-log: 
,03-24 15:29:44.680 11146 11225 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:44.680 11146 11225 I jxcore-log: 
,03-24 15:29:44.685 11146 11225 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:44.685 11146 11225 I jxcore-log: 
,03-24 15:29:44.695 11146 11225 I jxcore-log: ok 21 Buffers are identical
03-24 15:29:44.695 11146 11225 I jxcore-log: 
,03-24 15:29:44.700 11146 11225 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:44.700 11146 11225 I jxcore-log: 
,03-24 15:29:44.710 11146 11225 I jxcore-log: DEBUG createNativeListener: mux close
03-24 15:29:44.710 11146 11225 I jxcore-log: 
,03-24 15:29:44.715 11146 11225 I jxcore-log: ok 22 native server is nulled out
03-24 15:29:44.715 11146 11225 I jxcore-log: 
,03-24 15:29:44.715 11146 11225 I jxcore-log: ok 23 native server should be closed
03-24 15:29:44.715 11146 11225 I jxcore-log: 
,03-24 15:29:44.715 11146 11225 I jxcore-log: ok 24 incoming has been removed
03-24 15:29:44.715 11146 11225 I jxcore-log: 
03-24 15:29:44.715 11146 11225 I jxcore-log: ok 25 Incoming should be done
03-24 15:29:44.715 11146 11225 I jxcore-log: 
,03-24 15:29:44.715 11146 11225 I jxcore-log: ok 26 The mux object should be closed
03-24 15:29:44.715 11146 11225 I jxcore-log: 
,03-24 15:29:44.715 11146 11225 I jxcore-log: ok 27 The mux stream should be closed
03-24 15:29:44.715 11146 11225 I jxcore-log: 
,03-24 15:29:44.720 11146 11225 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 15:29:44.720 11146 11225 I jxcore-log: 
,03-24 15:29:44.740 11146 11225 I jxcore-log: # teardown
03-24 15:29:44.740 11146 11225 I jxcore-log: 
,03-24 15:29:47.815 11146 11225 I jxcore-log: # setup
03-24 15:29:47.815 11146 11225 I jxcore-log: 
,03-24 15:29:48.340  3390  3864 E Watchdog: !@Sync 7 [03-24 15:29:48.342]
,03-24 15:29:49.085 11146 11225 I jxcore-log: # 9. native server - we can get a ton of connections and data through and still clean up the server completely
03-24 15:29:49.085 11146 11225 I jxcore-log: 
,03-24 15:29:51.160  3390  3425 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:29:51.160  3390  3425 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:29:51.160  3390  3425 D BatteryService: online:4, current avg:44, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:62
,03-24 15:29:51.160  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-24 15:29:51.165  3390  3425 D BatteryService: stay LED for fully charged
,03-24 15:29:51.170  3390  3390 I MotionRecognitionService: Plugged,
,03-24 15:29:51.170  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:29:51.170  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
03-24 15:29:51.170  3390  3390 D MotionRecognitionService: skip setTransmitPower. ,
,03-24 15:29:51.185  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:29:51.185  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:29:51.185  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:29:51.195  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-24 15:29:51.195  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:29:51.210  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:29:51.210  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:29:51.210  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:29:51.210  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:29:51.760  3390  6051 D SSRM:n  : SIOP:: AP = 290, PST = 287 (W:10), CUR = 44, LCD = 0
,03-24 15:29:53.745 11146 11225 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 15:29:53.745 11146 11225 I jxcore-log: 
,03-24 15:29:53.760 11146 11225 I jxcore-log: DEBUG createNativeListener: listening 49583
03-24 15:29:53.760 11146 11225 I jxcore-log: 
,03-24 15:29:53.790 11146 11225 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 15:29:53.790 11146 11225 I jxcore-log: 
,03-24 15:29:53.795 11146 11225 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 15:29:53.795 11146 11225 I jxcore-log: 
,03-24 15:29:53.795 11146 11225 I jxcore-log: DEBUG createNativeListener: new mux
03-24 15:29:53.795 11146 11225 I jxcore-log: 
,03-24 15:29:53.810 11146 11225 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 15:29:53.810 11146 11225 I jxcore-log: 
,03-24 15:29:53.810 11146 11225 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 15:29:53.810 11146 11225 I jxcore-log: 
,03-24 15:29:53.810 11146 11225 I jxcore-log: DEBUG createNativeListener: new mux
03-24 15:29:53.810 11146 11225 I jxcore-log: 
,03-24 15:29:53.815 11146 11225 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 15:29:53.815 11146 11225 I jxcore-log: 
,03-24 15:29:53.815 11146 11225 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 15:29:53.815 11146 11225 I jxcore-log: 
,03-24 15:29:53.820 11146 11225 I jxcore-log: DEBUG createNativeListener: new mux
03-24 15:29:53.820 11146 11225 I jxcore-log: 
,03-24 15:29:53.825 11146 11225 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 15:29:53.825 11146 11225 I jxcore-log: 
,03-24 15:29:53.825 11146 11225 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 15:29:53.825 11146 11225 I jxcore-log: 
,03-24 15:29:53.825 11146 11225 I jxcore-log: DEBUG createNativeListener: new mux
03-24 15:29:53.825 11146 11225 I jxcore-log: 
,03-24 15:29:53.830 11146 11225 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 15:29:53.830 11146 11225 I jxcore-log: 
,03-24 15:29:53.830 11146 11225 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 15:29:53.830 11146 11225 I jxcore-log: 
,03-24 15:29:53.835 11146 11225 I jxcore-log: DEBUG createNativeListener: new mux
03-24 15:29:53.835 11146 11225 I jxcore-log: 
,03-24 15:29:53.835 11146 11225 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 15:29:53.835 11146 11225 I jxcore-log: 
,03-24 15:29:53.835 11146 11225 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 15:29:53.835 11146 11225 I jxcore-log: 
,03-24 15:29:53.840 11146 11225 I jxcore-log: DEBUG createNativeListener: new mux
03-24 15:29:53.840 11146 11225 I jxcore-log: 
,03-24 15:29:53.840 11146 11225 I jxcore-log: DEBUG createNativeListener: new incoming socket,
03-24 15:29:53.840 11146 11225 I jxcore-log: 
03-24 15:29:53.845 11146 11225 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 15:29:53.845 11146 11225 I jxcore-log: 
,03-24 15:29:53.845 11146 11225 I jxcore-log: DEBUG createNativeListener: new mux
03-24 15:29:53.845 11146 11225 I jxcore-log: 
,03-24 15:29:53.850 11146 11225 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 15:29:53.850 11146 11225 I jxcore-log: 
,03-24 15:29:53.850 11146 11225 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 15:29:53.850 11146 11225 I jxcore-log: 
,03-24 15:29:53.850 11146 11225 I jxcore-log: DEBUG createNativeListener: new mux
03-24 15:29:53.850 11146 11225 I jxcore-log: 
,03-24 15:29:53.855 11146 11225 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 15:29:53.855 11146 11225 I jxcore-log: 
,03-24 15:29:53.855 11146 11225 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 15:29:53.855 11146 11225 I jxcore-log: 
,03-24 15:29:53.855 11146 11225 I jxcore-log: DEBUG createNativeListener: new mux
03-24 15:29:53.855 11146 11225 I jxcore-log: 
,03-24 15:29:53.860 11146 11225 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 15:29:53.860 11146 11225 I jxcore-log: 
,03-24 15:29:53.860 11146 11225 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 15:29:53.860 11146 11225 I jxcore-log: 
,03-24 15:29:53.865 11146 11225 I jxcore-log: DEBUG createNativeListener: new mux
03-24 15:29:53.865 11146 11225 I jxcore-log: 
,03-24 15:29:53.970 11146 11225 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:53.970 11146 11225 I jxcore-log: 
,03-24 15:29:53.975 11146 11225 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:53.975 11146 11225 I jxcore-log: 
,03-24 15:29:53.975 11146 11225 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:53.975 11146 11225 I jxcore-log: 
,03-24 15:29:53.980 11146 11225 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:53.980 11146 11225 I jxcore-log: 
,03-24 15:29:53.980 11146 11225 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:53.980 11146 11225 I jxcore-log: 
,03-24 15:29:53.980 11146 11225 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:53.980 11146 11225 I jxcore-log: 
,03-24 15:29:53.985 11146 11225 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:53.985 11146 11225 I jxcore-log: 
,03-24 15:29:53.985 11146 11225 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:53.985 11146 11225 I jxcore-log: 
,03-24 15:29:53.990 11146 11225 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:53.990 11146 11225 I jxcore-log: 
,03-24 15:29:53.990 11146 11225 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:53.990 11146 11225 I jxcore-log: 
,03-24 15:29:53.990 11146 11225 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:53.990 11146 11225 I jxcore-log: 
,03-24 15:29:53.995 11146 11225 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:53.995 11146 11225 I jxcore-log: 
,03-24 15:29:53.995 11146 11225 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:53.995 11146 11225 I jxcore-log: 
,03-24 15:29:53.995 11146 11225 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:53.995 11146 11225 I jxcore-log: 
,03-24 15:29:53.995 11146 11225 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:53.995 11146 11225 I jxcore-log: 
,03-24 15:29:54.000 11146 11225 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:54.000 11146 11225 I jxcore-log: 
,03-24 15:29:54.000 11146 11225 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:54.000 11146 11225 I jxcore-log: 
,03-24 15:29:54.000 11146 11225 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:54.000 11146 11225 I jxcore-log: 
,03-24 15:29:54.000 11146 11225 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:54.000 11146 11225 I jxcore-log: 
,03-24 15:29:54.005 11146 11225 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:54.005 11146 11225 I jxcore-log: 
,03-24 15:29:54.005 11146 11225 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:54.005 11146 11225 I jxcore-log: 
,03-24 15:29:54.010 11146 11225 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:54.010 11146 11225 I jxcore-log: 
,03-24 15:29:54.010 11146 11225 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:54.010 11146 11225 I jxcore-log: 
,03-24 15:29:54.010 11146 11225 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:54.010 11146 11225 I jxcore-log: 
,03-24 15:29:54.010 11146 11225 I jxcore-log: DEBUG createNativeListener: new stream: 
,03-24 15:29:54.010 11146 11225 I jxcore-log: 
,03-24 15:29:54.015 11146 11225 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:54.015 11146 11225 I jxcore-log: 
,03-24 15:29:54.015 11146 11225 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:54.015 11146 11225 I jxcore-log: 
,03-24 15:29:54.015 11146 11225 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:54.015 11146 11225 I jxcore-log: 
,03-24 15:29:54.020 11146 11225 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:54.020 11146 11225 I jxcore-log: 
,03-24 15:29:54.020 11146 11225 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:54.020 11146 11225 I jxcore-log: 
,03-24 15:29:54.020 11146 11225 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:54.020 11146 11225 I jxcore-log: 
,03-24 15:29:54.020 11146 11225 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:54.020 11146 11225 I jxcore-log: 
,03-24 15:29:54.025 11146 11225 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:54.025 11146 11225 I jxcore-log: 
,03-24 15:29:54.025 11146 11225 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:54.025 11146 11225 I jxcore-log: 
,03-24 15:29:54.025 11146 11225 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:54.025 11146 11225 I jxcore-log: 
,03-24 15:29:54.030 11146 11225 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:54.030 11146 11225 I jxcore-log: 
,03-24 15:29:54.030 11146 11225 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:54.030 11146 11225 I jxcore-log: 
,03-24 15:29:54.030 11146 11225 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:54.030 11146 11225 I jxcore-log: 
,03-24 15:29:54.030 11146 11225 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:54.030 11146 11225 I jxcore-log: 
,03-24 15:29:54.035 11146 11225 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:54.035 11146 11225 I jxcore-log: 
03-24 15:29:54.035 11146 11225 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:54.035 11146 11225 I jxcore-log: 
03-24 15:29:54.035 11146 11225 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:54.035 11146 11225 I jxcore-log: 
,03-24 15:29:54.035 11146 11225 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:54.035 11146 11225 I jxcore-log: 
,03-24 15:29:54.035 11146 11225 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:54.035 11146 11225 I jxcore-log: 
,03-24 15:29:54.040 11146 11225 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:54.040 11146 11225 I jxcore-log: 
,03-24 15:29:54.040 11146 11225 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:54.040 11146 11225 I jxcore-log: 
,03-24 15:29:54.050 11146 11225 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:54.050 11146 11225 I jxcore-log: 
,03-24 15:29:54.050 11146 11225 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:54.050 11146 11225 I jxcore-log: 
,03-24 15:29:54.055 11146 11225 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:54.055 11146 11225 I jxcore-log: 
,03-24 15:29:54.055 11146 11225 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:54.055 11146 11225 I jxcore-log: 
,03-24 15:29:54.055 11146 11225 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:54.055 11146 11225 I jxcore-log: 
,03-24 15:29:54.060 11146 11225 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:54.060 11146 11225 I jxcore-log: 
,03-24 15:29:54.060 11146 11225 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:54.060 11146 11225 I jxcore-log: 
,03-24 15:29:54.060 11146 11225 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:54.060 11146 11225 I jxcore-log: 
,03-24 15:29:54.060 11146 11225 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:54.060 11146 11225 I jxcore-log: 
,03-24 15:29:54.060 11146 11225 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:54.060 11146 11225 I jxcore-log: 
,03-24 15:29:54.065 11146 11225 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:54.065 11146 11225 I jxcore-log: 
,03-24 15:29:54.065 11146 11225 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:54.065 11146 11225 I jxcore-log: 
,03-24 15:29:54.065 11146 11225 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:54.065 11146 11225 I jxcore-log: 
,03-24 15:29:54.070 11146 11225 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:54.070 11146 11225 I jxcore-log: 
,03-24 15:29:54.070 11146 11225 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:54.070 11146 11225 I jxcore-log: 
,03-24 15:29:54.070 11146 11225 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:54.070 11146 11225 I jxcore-log: 
,03-24 15:29:54.070 11146 11225 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:54.070 11146 11225 I jxcore-log: 
,03-24 15:29:54.070 11146 11225 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:54.070 11146 11225 I jxcore-log: 
,03-24 15:29:54.075 11146 11225 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:54.075 11146 11225 I jxcore-log: 
,03-24 15:29:54.075 11146 11225 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:54.075 11146 11225 I jxcore-log: 
,03-24 15:29:54.075 11146 11225 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:54.075 11146 11225 I jxcore-log: 
,03-24 15:29:54.075 11146 11225 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:54.075 11146 11225 I jxcore-log: 
,03-24 15:29:54.075 11146 11225 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:54.075 11146 11225 I jxcore-log: 
,03-24 15:29:54.080 11146 11225 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:54.080 11146 11225 I jxcore-log: 
,03-24 15:29:54.080 11146 11225 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:54.080 11146 11225 I jxcore-log: 
,03-24 15:29:54.080 11146 11225 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:54.080 11146 11225 I jxcore-log: 
,03-24 15:29:54.085 11146 11225 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:54.085 11146 11225 I jxcore-log: 
,03-24 15:29:54.085 11146 11225 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:54.085 11146 11225 I jxcore-log: 
,03-24 15:29:54.085 11146 11225 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:54.085 11146 11225 I jxcore-log: 
,03-24 15:29:54.085 11146 11225 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:54.085 11146 11225 I jxcore-log: 
,03-24 15:29:54.085 11146 11225 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:54.085 11146 11225 I jxcore-log: 
,03-24 15:29:54.090 11146 11225 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:54.090 11146 11225 I jxcore-log: 
,03-24 15:29:54.090 11146 11225 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:54.090 11146 11225 I jxcore-log: 
,03-24 15:29:54.090 11146 11225 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:54.090 11146 11225 I jxcore-log: 
,03-24 15:29:54.150 11146 11225 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:54.150 11146 11225 I jxcore-log: 
,03-24 15:29:54.150 11146 11225 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:54.150 11146 11225 I jxcore-log: 
,03-24 15:29:54.150 11146 11225 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:54.150 11146 11225 I jxcore-log: 
,03-24 15:29:54.150 11146 11225 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:54.150 11146 11225 I jxcore-log: 
,03-24 15:29:54.155 11146 11225 I jxcore-log: DEBUG createNativeListener: mux close
03-24 15:29:54.155 11146 11225 I jxcore-log: 
,03-24 15:29:54.155 11146 11225 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:54.155 11146 11225 I jxcore-log: 
03-24 15:29:54.155 11146 11225 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:54.155 11146 11225 I jxcore-log: 
,03-24 15:29:54.155 11146 11225 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:54.155 11146 11225 I jxcore-log: 
03-24 15:29:54.155 11146 11225 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:54.155 11146 11225 I jxcore-log: 
,03-24 15:29:54.155 11146 11225 I jxcore-log: DEBUG createNativeListener: mux close
03-24 15:29:54.155 11146 11225 I jxcore-log: 
,03-24 15:29:54.160 11146 11225 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:54.160 11146 11225 I jxcore-log: 
,03-24 15:29:54.160 11146 11225 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:54.160 11146 11225 I jxcore-log: 
,03-24 15:29:54.160 11146 11225 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:54.160 11146 11225 I jxcore-log: 
03-24 15:29:54.160 11146 11225 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:54.160 11146 11225 I jxcore-log: 
,03-24 15:29:54.160 11146 11225 I jxcore-log: DEBUG createNativeListener: mux close
03-24 15:29:54.160 11146 11225 I jxcore-log: 
,03-24 15:29:54.160 11146 11225 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:54.160 11146 11225 I jxcore-log: 
,03-24 15:29:54.165 11146 11225 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:54.165 11146 11225 I jxcore-log: 
03-24 15:29:54.165 11146 11225 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:54.165 11146 11225 I jxcore-log: 
,03-24 15:29:54.165 11146 11225 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:54.165 11146 11225 I jxcore-log: 
03-24 15:29:54.165 11146 11225 I jxcore-log: DEBUG createNativeListener: mux close
03-24 15:29:54.165 11146 11225 I jxcore-log: 
,03-24 15:29:54.165 11146 11225 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:54.165 11146 11225 I jxcore-log: 
03-24 15:29:54.165 11146 11225 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:54.165 11146 11225 I jxcore-log: 
,03-24 15:29:54.165 11146 11225 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:54.165 11146 11225 I jxcore-log: 
03-24 15:29:54.165 11146 11225 I jxcore-log: DEBUG createNativeListener: stream close:
,03-24 15:29:54.165 11146 11225 I jxcore-log: 
03-24 15:29:54.165 11146 11225 I jxcore-log: DEBUG createNativeListener: mux close
03-24 15:29:54.165 11146 11225 I jxcore-log: 
,03-24 15:29:54.170 11146 11225 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:54.170 11146 11225 I jxcore-log: 
,03-24 15:29:54.170 11146 11225 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:54.170 11146 11225 I jxcore-log: 
03-24 15:29:54.170 11146 11225 I jxcore-log: DEBUG createNativeListener: stream close:
,03-24 15:29:54.170 11146 11225 I jxcore-log: 
03-24 15:29:54.170 11146 11225 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:54.170 11146 11225 I jxcore-log: 
,03-24 15:29:54.170 11146 11225 I jxcore-log: DEBUG createNativeListener: mux close
03-24 15:29:54.170 11146 11225 I jxcore-log: 
03-24 15:29:54.170 11146 11225 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:54.170 11146 11225 I jxcore-log: 
,03-24 15:29:54.170 11146 11225 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:54.170 11146 11225 I jxcore-log: 
03-24 15:29:54.170 11146 11225 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:54.170 11146 11225 I jxcore-log: 
,03-24 15:29:54.170 11146 11225 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:54.170 11146 11225 I jxcore-log: 
,03-24 15:29:54.175 11146 11225 I jxcore-log: DEBUG createNativeListener: mux close
03-24 15:29:54.175 11146 11225 I jxcore-log: 
03-24 15:29:54.175 11146 11225 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:54.175 11146 11225 I jxcore-log: 
,03-24 15:29:54.175 11146 11225 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:54.175 11146 11225 I jxcore-log: 
,03-24 15:29:54.175 11146 11225 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:54.175 11146 11225 I jxcore-log: 
03-24 15:29:54.175 11146 11225 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:54.175 11146 11225 I jxcore-log: 
,03-24 15:29:54.175 11146 11225 I jxcore-log: DEBUG createNativeListener: mux close
03-24 15:29:54.175 11146 11225 I jxcore-log: 
03-24 15:29:54.175 11146 11225 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:54.175 11146 11225 I jxcore-log: 
,03-24 15:29:54.175 11146 11225 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:54.175 11146 11225 I jxcore-log: 
03-24 15:29:54.175 11146 11225 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:54.175 11146 11225 I jxcore-log: 
,03-24 15:29:54.180 11146 11225 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:54.180 11146 11225 I jxcore-log: 
03-24 15:29:54.180 11146 11225 I jxcore-log: DEBUG createNativeListener: mux close
03-24 15:29:54.180 11146 11225 I jxcore-log: 
,03-24 15:29:54.180 11146 11225 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:54.180 11146 11225 I jxcore-log: 
,03-24 15:29:54.180 11146 11225 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:54.180 11146 11225 I jxcore-log: 
03-24 15:29:54.180 11146 11225 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:54.180 11146 11225 I jxcore-log: 
,03-24 15:29:54.180 11146 11225 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:54.180 11146 11225 I jxcore-log: 
03-24 15:29:54.180 11146 11225 I jxcore-log: DEBUG createNativeListener: mux close
,03-24 15:29:54.180 11146 11225 I jxcore-log: 
,03-24 15:29:54.185 11146 11225 I jxcore-log: ok 28 native server is nulled out
03-24 15:29:54.185 11146 11225 I jxcore-log: 
,03-24 15:29:54.185 11146 11225 I jxcore-log: ok 29 native server should be closed
03-24 15:29:54.185 11146 11225 I jxcore-log: 
03-24 15:29:54.185 11146 11225 I jxcore-log: ok 30 incoming has been removed
03-24 15:29:54.185 11146 11225 I jxcore-log: 
03-24 15:29:54.185 11146 11225 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 15:29:54.185 11146 11225 I jxcore-log: 
,03-24 15:29:54.185 11146 11225 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 15:29:54.185 11146 11225 I jxcore-log: 
03-24 15:29:54.185 11146 11225 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 15:29:54.185 11146 11225 I jxcore-log: 
03-24 15:29:54.185 11146 11225 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 15:29:54.185 11146 11225 I jxcore-log: 
,03-24 15:29:54.185 11146 11225 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 15:29:54.185 11146 11225 I jxcore-log: 
03-24 15:29:54.185 11146 11225 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 15:29:54.185 11146 11225 I jxcore-log: 
03-24 15:29:54.185 11146 11225 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 15:29:54.185 11146 11225 I jxcore-log: 
,03-24 15:29:54.185 11146 11225 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 15:29:54.185 11146 11225 I jxcore-log: 
03-24 15:29:54.185 11146 11225 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 15:29:54.185 11146 11225 I jxcore-log: 
03-24 15:29:54.185 11146 11225 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 15:29:54.185 11146 11225 I jxcore-log: 
,03-24 15:29:54.275 11146 11225 I jxcore-log: # teardown
03-24 15:29:54.275 11146 11225 I jxcore-log: 
,03-24 15:29:55.480  3390  6082 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-24 15:29:59.995  3390  3620 V AlarmManager: waitForAlarm result :8
,03-24 15:30:01.295  3390  4707 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:30:01.295  3390  4707 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:30:01.295  3390  4707 D BatteryService: online:4, current avg:49, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:47
,03-24 15:30:01.295  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-24 15:30:01.300  3390  4707 D BatteryService: stay LED for fully charged
,03-24 15:30:01.310  3390  3390 I MotionRecognitionService: Plugged
03-24 15:30:01.310  3390  3390 D MotionRecognitionService:   cableConnection= 1,
03-24 15:30:01.310  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-24 15:30:01.310  3390  3390 D MotionRecognitionService: skip setTransmitPower. ,
,03-24 15:30:01.320  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:30:01.320  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:30:01.320  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-24 15:30:01.340  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-24 15:30:01.340  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:30:01.350  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:30:01.350  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:30:01.350  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:30:01.350  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:30:01.790  3390  6051 D SSRM:n  : SIOP:: AP = 280, PST = 287 (W:12), CUR = 49, LCD = 0
,03-24 15:30:02.915 11146 11225 I jxcore-log: # setup
03-24 15:30:02.915 11146 11225 I jxcore-log: 
,03-24 15:30:05.255 11146 11225 I jxcore-log: # 10. native server - simulate mux failure, make sure everything is cleaned up
03-24 15:30:05.255 11146 11225 I jxcore-log: 
,03-24 15:30:11.410  3390  3587 I PowerManagerService: [PWL] Off : 180s ago
,03-24 15:30:11.435  3390  3652 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:30:11.435  3390  3652 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:30:11.435  3390  3652 D BatteryService: online:4, current avg:48, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:43
,03-24 15:30:11.435  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-24 15:30:11.435  3390  3652 D BatteryService: stay LED for fully charged
,03-24 15:30:11.445  3390  3390 I MotionRecognitionService: Plugged
03-24 15:30:11.445  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:30:11.445  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-24 15:30:11.445  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:30:11.450  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:30:11.450  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:30:11.450  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:30:11.470  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-24 15:30:11.470  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:30:11.485  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:30:11.485  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:30:11.485  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:30:11.485  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:30:11.820  3390  6051 D SSRM:n  : SIOP:: AP = 280, PST = 285 (W:12), CUR = 48, LCD = 0
,03-24 15:30:13.215 11146 11225 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 15:30:13.215 11146 11225 I jxcore-log: 
,03-24 15:30:13.220 11146 11225 I jxcore-log: DEBUG createNativeListener: listening 47527
03-24 15:30:13.220 11146 11225 I jxcore-log: 
,03-24 15:30:13.235 11146 11225 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 15:30:13.235 11146 11225 I jxcore-log: 
,03-24 15:30:13.235 11146 11225 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 15:30:13.235 11146 11225 I jxcore-log: 
,03-24 15:30:13.240 11146 11225 I jxcore-log: DEBUG createNativeListener: new mux
03-24 15:30:13.240 11146 11225 I jxcore-log: 
,03-24 15:30:13.255 11146 11225 I jxcore-log: ok 31 we should not have gotten an error
03-24 15:30:13.255 11146 11225 I jxcore-log: 
,03-24 15:30:13.260 11146 11225 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:30:13.260 11146 11225 I jxcore-log: 
,03-24 15:30:13.265 11146 11225 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:30:13.265 11146 11225 I jxcore-log: 
,03-24 15:30:13.270 11146 11225 I jxcore-log: ok 32 Buffers are identical
03-24 15:30:13.270 11146 11225 I jxcore-log: 
,03-24 15:30:13.275 11146 11225 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:30:13.275 11146 11225 I jxcore-log: 
,03-24 15:30:13.275 11146 11225 I jxcore-log: DEBUG createNativeListener: mux close
03-24 15:30:13.275 11146 11225 I jxcore-log: 
,03-24 15:30:13.290 11146 11225 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 15:30:13.290 11146 11225 I jxcore-log: 
,03-24 15:30:13.290 11146 11225 I jxcore-log: ok 33 server should be fine
03-24 15:30:13.290 11146 11225 I jxcore-log: 
,03-24 15:30:13.295 11146 11225 I jxcore-log: ok 34 server should be open
03-24 15:30:13.295 11146 11225 I jxcore-log: 
,03-24 15:30:13.295 11146 11225 I jxcore-log: ok 35 incoming has been removed
03-24 15:30:13.295 11146 11225 I jxcore-log: 
03-24 15:30:13.295 11146 11225 I jxcore-log: ok 36 The mux object should be closed
03-24 15:30:13.295 11146 11225 I jxcore-log: 
,03-24 15:30:13.295 11146 11225 I jxcore-log: ok 37 The mux stream should be closed
03-24 15:30:13.295 11146 11225 I jxcore-log: 
,03-24 15:30:13.305 11146 11225 I jxcore-log: # teardown
03-24 15:30:13.305 11146 11225 I jxcore-log: 
,03-24 15:30:15.485  3390  6082 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-24 15:30:17.025 11146 11225 I jxcore-log: # setup
03-24 15:30:17.025 11146 11225 I jxcore-log: 
,03-24 15:30:18.345  3390  3864 E Watchdog: !@Sync 8 [03-24 15:30:18.350]
,03-24 15:30:18.515 11146 11225 I jxcore-log: # 11. native server - timing out the incoming connection cleans everything up
03-24 15:30:18.515 11146 11225 I jxcore-log: 
,03-24 15:30:18.790 11146 11225 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 15:30:18.790 11146 11225 I jxcore-log: 
,03-24 15:30:18.820 11146 11225 I jxcore-log: DEBUG createNativeListener: listening 41928
03-24 15:30:18.820 11146 11225 I jxcore-log: 
,03-24 15:30:18.825 11146 11225 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 15:30:18.825 11146 11225 I jxcore-log: 
,03-24 15:30:18.825 11146 11225 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 15:30:18.825 11146 11225 I jxcore-log: 
,03-24 15:30:18.830 11146 11225 I jxcore-log: DEBUG createNativeListener: new mux
03-24 15:30:18.830 11146 11225 I jxcore-log: 
,03-24 15:30:18.840 11146 11225 I jxcore-log: ok 38 we should not have gotten an error
03-24 15:30:18.840 11146 11225 I jxcore-log: 
,03-24 15:30:18.840 11146 11225 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:30:18.840 11146 11225 I jxcore-log: 
,03-24 15:30:18.845 11146 11225 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:30:18.845 11146 11225 I jxcore-log: 
,03-24 15:30:18.850 11146 11225 I jxcore-log: ok 39 Buffers are identical
03-24 15:30:18.850 11146 11225 I jxcore-log: 
,03-24 15:30:18.860 11146 11225 I jxcore-log: DEBUG createNativeListener: incoming socket timeout
03-24 15:30:18.860 11146 11225 I jxcore-log: 
,03-24 15:30:18.860 11146 11225 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:30:18.860 11146 11225 I jxcore-log: 
,03-24 15:30:18.860 11146 11225 I jxcore-log: DEBUG createNativeListener: mux close
03-24 15:30:18.860 11146 11225 I jxcore-log: 
,03-24 15:30:18.870 11146 11225 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 15:30:18.870 11146 11225 I jxcore-log: 
,03-24 15:30:18.870 11146 11225 I jxcore-log: ok 40 server should be fine
03-24 15:30:18.870 11146 11225 I jxcore-log: 
03-24 15:30:18.870 11146 11225 I jxcore-log: ok 41 server should be open
03-24 15:30:18.870 11146 11225 I jxcore-log: 
,03-24 15:30:18.870 11146 11225 I jxcore-log: ok 42 incoming has been removed
03-24 15:30:18.870 11146 11225 I jxcore-log: 
03-24 15:30:18.870 11146 11225 I jxcore-log: ok 43 The mux object should be closed
03-24 15:30:18.870 11146 11225 I jxcore-log: 
,03-24 15:30:18.870 11146 11225 I jxcore-log: ok 44 The mux stream should be closed
03-24 15:30:18.870 11146 11225 I jxcore-log: 
,03-24 15:30:18.880 11146 11225 I jxcore-log: # teardown
03-24 15:30:18.880 11146 11225 I jxcore-log: 
,03-24 15:30:19.005 11146 11225 I jxcore-log: # setup
03-24 15:30:19.005 11146 11225 I jxcore-log: 
,03-24 15:30:19.185 11146 11225 I jxcore-log: # 12. closeAll can close even when connections open
03-24 15:30:19.185 11146 11225 I jxcore-log: 
,03-24 15:30:19.455 11146 11225 I jxcore-log: ok 45 not possible to connect to the server anymore
03-24 15:30:19.455 11146 11225 I jxcore-log: 
,03-24 15:30:19.465 11146 11225 I jxcore-log: # teardown
03-24 15:30:19.465 11146 11225 I jxcore-log: 
,03-24 15:30:19.625 11146 11225 I jxcore-log: # setup
03-24 15:30:19.625 11146 11225 I jxcore-log: 
,03-24 15:30:19.770 11146 11225 I jxcore-log: # 13. closeAll with promise
03-24 15:30:19.770 11146 11225 I jxcore-log: 
,03-24 15:30:19.935 11146 11225 I jxcore-log: ok 46 not possible to connect to the server anymore
03-24 15:30:19.935 11146 11225 I jxcore-log: 
,03-24 15:30:19.940 11146 11225 I jxcore-log: # teardown
03-24 15:30:19.940 11146 11225 I jxcore-log: 
,03-24 15:30:20.070 11146 11225 I jxcore-log: # setup
03-24 15:30:20.070 11146 11225 I jxcore-log: 
,03-24 15:30:20.185 11146 11225 I jxcore-log: # 14. multiplex can send data
03-24 15:30:20.185 11146 11225 I jxcore-log: 
,03-24 15:30:20.395 11146 11225 I jxcore-log: ok 47 String should be length:200
03-24 15:30:20.395 11146 11225 I jxcore-log: 
,03-24 15:30:20.410 11146 11225 I jxcore-log: # teardown
03-24 15:30:20.410 11146 11225 I jxcore-log: 
,03-24 15:30:20.495 11146 11225 I jxcore-log: # setup
03-24 15:30:20.495 11146 11225 I jxcore-log: 
,03-24 15:30:20.670 11146 11225 I jxcore-log: # 15. enqueue and run in order
03-24 15:30:20.670 11146 11225 I jxcore-log: 
,03-24 15:30:20.880 11146 11225 I jxcore-log: ok 48 firstPromise setTimeout
03-24 15:30:20.880 11146 11225 I jxcore-log: 
,03-24 15:30:20.890 11146 11225 I jxcore-log: ok 49 firstPromise result
03-24 15:30:20.890 11146 11225 I jxcore-log: 
,03-24 15:30:20.895 11146 11225 I jxcore-log: ok 50 firstPromise testValue
03-24 15:30:20.895 11146 11225 I jxcore-log: 
,03-24 15:30:21.005 11146 11225 I jxcore-log: ok 51 secondPromise setTimeout
03-24 15:30:21.005 11146 11225 I jxcore-log: 
,03-24 15:30:21.015 11146 11225 I jxcore-log: ok 52 secondPromise result
03-24 15:30:21.015 11146 11225 I jxcore-log: 
,03-24 15:30:21.025 11146 11225 I jxcore-log: ok 53 secondPromise testValue
03-24 15:30:21.025 11146 11225 I jxcore-log: 
,03-24 15:30:21.030 11146 11225 I jxcore-log: ok 54 thirdPromise in promise
03-24 15:30:21.030 11146 11225 I jxcore-log: 
,03-24 15:30:21.035 11146 11225 I jxcore-log: ok 55 thirdPromise result
03-24 15:30:21.035 11146 11225 I jxcore-log: 
,03-24 15:30:21.035 11146 11225 I jxcore-log: ok 56 thirdPromise testValue
03-24 15:30:21.035 11146 11225 I jxcore-log: 
,03-24 15:30:21.045 11146 11225 I jxcore-log: # teardown
03-24 15:30:21.045 11146 11225 I jxcore-log: 
,03-24 15:30:21.175 11146 11225 I jxcore-log: # setup
03-24 15:30:21.175 11146 11225 I jxcore-log: 
,03-24 15:30:21.445 11146 11225 I jxcore-log: # 16. enqueueAtTop and run backwards
03-24 15:30:21.445 11146 11225 I jxcore-log: 
,03-24 15:30:21.545  3390  4044 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-24 15:30:21.545  3390  4044 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:30:21.545  3390  4044 D BatteryService: online:4, current avg:47, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:51
03-24 15:30:21.545  3390  4044 D BatteryService: stay LED for fully charged
03-24 15:30:21.545  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-24 15:30:21.550  3390  3390 I MotionRecognitionService: Plugged
03-24 15:30:21.550  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:30:21.550  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-24 15:30:21.550  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:30:21.555  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:30:21.555  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:30:21.555  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:30:21.565  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-24 15:30:21.565  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
03-24 15:30:21.565 11146 11225 I jxcore-log: ok 57 thirdPromise - first to run
03-24 15:30:21.565 11146 11225 I jxcore-log: 
,03-24 15:30:21.565 11146 11225 I jxcore-log: ok 58 thirdPromise - in resolve
03-24 15:30:21.565 11146 11225 I jxcore-log: 
,03-24 15:30:21.570 11146 11225 I jxcore-log: ok 59 secondPromise - second to run
03-24 15:30:21.570 11146 11225 I jxcore-log: 
,03-24 15:30:21.570 11146 11225 I jxcore-log: ok 60 secondPromise - in catch
03-24 15:30:21.570 11146 11225 I jxcore-log: 
,03-24 15:30:21.570 11146 11225 I jxcore-log: ok 61 firstPromise - third to run
03-24 15:30:21.570 11146 11225 I jxcore-log: 
,03-24 15:30:21.575 11146 11225 I jxcore-log: ok 62 firstPromise - in then
03-24 15:30:21.575 11146 11225 I jxcore-log: 
,03-24 15:30:21.575 11146 11225 I jxcore-log: ok 63 testing promises
03-24 15:30:21.575 11146 11225 I jxcore-log: 
,03-24 15:30:21.575  2892  4752 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-24 15:30:21.575  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:30:21.575  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:30:21.580  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:30:21.580  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:30:21.580 11146 11225 I jxcore-log: # teardown
03-24 15:30:21.580 11146 11225 I jxcore-log: 
,03-24 15:30:21.735 11146 11225 I jxcore-log: # setup
03-24 15:30:21.735 11146 11225 I jxcore-log: 
,03-24 15:30:21.835  3390  6051 D SSRM:n  : SIOP:: AP = 280, PST = 285 (W:12), CUR = 47, LCD = 0
,03-24 15:30:21.865 11146 11225 I jxcore-log: # 17. mix enqueue and enqueueAtTop
03-24 15:30:21.865 11146 11225 I jxcore-log: 
,03-24 15:30:22.035 11146 11225 I jxcore-log: ok 64 fourth
03-24 15:30:22.035 11146 11225 I jxcore-log: 
,03-24 15:30:22.040 11146 11225 I jxcore-log: ok 65 fourth
03-24 15:30:22.040 11146 11225 I jxcore-log: 
,03-24 15:30:22.040 11146 11225 I jxcore-log: ok 66 second
03-24 15:30:22.040 11146 11225 I jxcore-log: 
,03-24 15:30:22.045 11146 11225 I jxcore-log: ok 67 secondPromise - in then
03-24 15:30:22.045 11146 11225 I jxcore-log: 
,03-24 15:30:22.150 11146 11225 I jxcore-log: ok 68 first
03-24 15:30:22.150 11146 11225 I jxcore-log: 
,03-24 15:30:22.150 11146 11225 I jxcore-log: ok 69 firstPromise - in catch
03-24 15:30:22.150 11146 11225 I jxcore-log: 
,03-24 15:30:22.155 11146 11225 I jxcore-log: ok 70 third
03-24 15:30:22.155 11146 11225 I jxcore-log: 
,03-24 15:30:22.155 11146 11225 I jxcore-log: ok 71 thirdPromise - in then
03-24 15:30:22.155 11146 11225 I jxcore-log: 
03-24 15:30:22.155 11146 11225 I jxcore-log: ok 72 testingPromises
03-24 15:30:22.155 11146 11225 I jxcore-log: 
,03-24 15:30:22.170 11146 11225 I jxcore-log: # teardown
03-24 15:30:22.170 11146 11225 I jxcore-log: 
,03-24 15:30:22.240 11146 11225 I jxcore-log: # setup
03-24 15:30:22.240 11146 11225 I jxcore-log: 
,03-24 15:30:22.415 11146 11225 I jxcore-log: # 18. queues handled independently
03-24 15:30:22.415 11146 11225 I jxcore-log: 
,03-24 15:30:22.605 11146 11225 I jxcore-log: ok 73 all short operations completed before the long resolves
03-24 15:30:22.605 11146 11225 I jxcore-log: 
,03-24 15:30:22.620 11146 11225 I jxcore-log: # teardown
03-24 15:30:22.620 11146 11225 I jxcore-log: 
,03-24 15:30:22.735 11146 11225 I jxcore-log: # setup
03-24 15:30:22.735 11146 11225 I jxcore-log: 
,03-24 15:30:22.850 11146 11225 I jxcore-log: # 19. basic
03-24 15:30:22.850 11146 11225 I jxcore-log: 
,03-24 15:30:22.970 11146 11225 I jxcore-log: ok 74 sane
03-24 15:30:22.970 11146 11225 I jxcore-log: 
,03-24 15:30:22.975 11146 11225 I jxcore-log: # teardown
03-24 15:30:22.975 11146 11225 I jxcore-log: 
,03-24 15:30:23.070 11146 11225 I jxcore-log: # setup
03-24 15:30:23.070 11146 11225 I jxcore-log: 
,03-24 15:30:23.210 11146 11225 I jxcore-log: # 20. another
03-24 15:30:23.210 11146 11225 I jxcore-log: 
,03-24 15:30:23.400 11146 11225 I jxcore-log: ok 75 sane
03-24 15:30:23.400 11146 11225 I jxcore-log: 
,03-24 15:30:23.415 11146 11225 I jxcore-log: # teardown
03-24 15:30:23.415 11146 11225 I jxcore-log: 
,03-24 15:30:23.565 11146 11225 I jxcore-log: # setup,
03-24 15:30:23.565 11146 11225 I jxcore-log: 
,03-24 15:30:23.775 11146 11225 I jxcore-log: # 21. can pass data in setup
03-24 15:30:23.775 11146 11225 I jxcore-log: 
,03-24 15:30:23.935 11146 11225 I jxcore-log: ok 76 test participant has uuid
03-24 15:30:23.935 11146 11225 I jxcore-log: 
,03-24 15:30:23.940 11146 11225 I jxcore-log: ok 77 participant data matches
03-24 15:30:23.940 11146 11225 I jxcore-log: 
,03-24 15:30:23.940 11146 11225 I jxcore-log: ok 78 test participant has uuid
03-24 15:30:23.940 11146 11225 I jxcore-log: 
,03-24 15:30:23.940 11146 11225 I jxcore-log: ok 79 participant data matches
03-24 15:30:23.940 11146 11225 I jxcore-log: 
,03-24 15:30:23.945 11146 11225 I jxcore-log: ok 80 test participant has uuid
03-24 15:30:23.945 11146 11225 I jxcore-log: 
,03-24 15:30:23.945 11146 11225 I jxcore-log: ok 81 participant data matches
03-24 15:30:23.945 11146 11225 I jxcore-log: 
,03-24 15:30:23.950 11146 11225 I jxcore-log: # teardown
03-24 15:30:23.950 11146 11225 I jxcore-log: 
,03-24 15:30:24.115 11146 11225 I jxcore-log: # setup
03-24 15:30:24.115 11146 11225 I jxcore-log: 
,03-24 15:30:24.235 11146 11225 I jxcore-log: # 22. #startListeningForAdvertisements should fail if start not called
03-24 15:30:24.235 11146 11225 I jxcore-log: 
,03-24 15:30:24.355 11146 11225 I jxcore-log: ok 82 specific error should be returned
03-24 15:30:24.355 11146 11225 I jxcore-log: 
,03-24 15:30:24.360 11146 11225 I jxcore-log: # teardown
03-24 15:30:24.360 11146 11225 I jxcore-log: 
,03-24 15:30:24.495 11146 11225 I jxcore-log: ok 83 error should be null
03-24 15:30:24.495 11146 11225 I jxcore-log: 
,03-24 15:30:24.495 11146 11225 I jxcore-log: ok 84 error should be null
03-24 15:30:24.495 11146 11225 I jxcore-log: 
,03-24 15:30:24.500 11146 11225 I jxcore-log: # setup
03-24 15:30:24.500 11146 11225 I jxcore-log: 
,03-24 15:30:24.650 11146 11225 I jxcore-log: # 23. #startUpdateAdvertisingAndListening should fail if start not called
03-24 15:30:24.650 11146 11225 I jxcore-log: 
,03-24 15:30:24.890 11146 11225 I jxcore-log: ok 85 specific error should be returned
03-24 15:30:24.890 11146 11225 I jxcore-log: 
,03-24 15:30:24.895 11146 11225 I jxcore-log: # teardown
03-24 15:30:24.895 11146 11225 I jxcore-log: 
,03-24 15:30:25.015 11146 11225 I jxcore-log: ok 86 error should be null
03-24 15:30:25.015 11146 11225 I jxcore-log: 
,03-24 15:30:25.015 11146 11225 I jxcore-log: ok 87 error should be null
03-24 15:30:25.015 11146 11225 I jxcore-log: 
,03-24 15:30:25.020 11146 11225 I jxcore-log: # setup
03-24 15:30:25.020 11146 11225 I jxcore-log: 
,03-24 15:30:25.130 11146 11225 I jxcore-log: # 24. should be able to call #stopListeningForAdvertisements many times
03-24 15:30:25.130 11146 11225 I jxcore-log: 
,03-24 15:30:25.340 11146 11225 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 15:30:25.340 11146 11225 I jxcore-log: 
,03-24 15:30:25.350 11146 11225 I jxcore-log: DEBUG createNativeListener: listening 51124
03-24 15:30:25.350 11146 11225 I jxcore-log: 
,03-24 15:30:25.355 11146 11225 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 15:30:25.355 11146 11225 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 15:30:25.355 11146 11225 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 15:30:25.360 11146 11225 I jxcore-log: ok 88 error should be null
03-24 15:30:25.360 11146 11225 I jxcore-log: 
,03-24 15:30:25.365 11146 11225 I jxcore-log: ok 89 error should be null
03-24 15:30:25.365 11146 11225 I jxcore-log: 
,03-24 15:30:25.365 11146 11225 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 15:30:25.365 11146 11225 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 15:30:25.365 11146 11225 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 15:30:25.370 11146 11225 I jxcore-log: ok 90 error should be null
03-24 15:30:25.370 11146 11225 I jxcore-log: 
,03-24 15:30:25.370 11146 11225 I jxcore-log: ok 91 error should be null
03-24 15:30:25.370 11146 11225 I jxcore-log: 
,03-24 15:30:25.375 11146 11225 I jxcore-log: # teardown
03-24 15:30:25.375 11146 11225 I jxcore-log: 
,03-24 15:30:25.555 11146 11225 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections,
,03-24 15:30:25.555 11146 11225 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
,03-24 15:30:25.555 11146 11225 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 15:30:25.565 11146 11225 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 15:30:25.565 11146 11225 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-24 15:30:25.565 11146 11225 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 15:30:25.575 11146 11225 I jxcore-log: ok 92 error should be null
03-24 15:30:25.575 11146 11225 I jxcore-log: 
,03-24 15:30:25.580 11146 11225 I jxcore-log: ok 93 error should be null
03-24 15:30:25.580 11146 11225 I jxcore-log: 
,03-24 15:30:25.585 11146 11225 I jxcore-log: # setup
03-24 15:30:25.585 11146 11225 I jxcore-log: 
,03-24 15:30:25.720 11146 11225 I jxcore-log: # 25. should be able to call #startListeningForAdvertisements many times
03-24 15:30:25.720 11146 11225 I jxcore-log: 
,03-24 15:30:25.895 11146 11225 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 15:30:25.895 11146 11225 I jxcore-log: 
,03-24 15:30:25.900 11146 11225 I jxcore-log: DEBUG createNativeListener: listening 58700
03-24 15:30:25.900 11146 11225 I jxcore-log: 
,03-24 15:30:25.915 11146 11225 I io.jxcore.node.ConnectionHelper: start: Port number: 0, start advertisements: false
03-24 15:30:25.915 11146 11225 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 15:30:25.915 11146 11225 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 15:30:25.915 11146 11225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
03-24 15:30:25.915 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 15:30:25.915 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-24 15:30:25.920 11146 11225 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-24 15:30:25.930 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-24 15:30:25.935 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 15:30:25.935 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 15:30:25.935 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 15:30:25.935 11146 11225 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 15:30:25.945  5836  5849 D BtGatt.GattService: registerClient() - UUID=6a5ba5e9-00a7-48f0-82ed-77ded57c9f25
,03-24 15:30:25.985  5836  5906 D BtGatt.GattService: onClientRegistered() - UUID=6a5ba5e9-00a7-48f0-82ed-77ded57c9f25, clientIf=6
,03-24 15:30:25.995 11146 11158 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-24 15:30:25.995  5836  9528 D BtGatt.GattService: start scan with filters
,03-24 15:30:26.060  5836  9528 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 54
,03-24 15:30:26.070  5836  5926 D BtGatt.ScanManager: handling starting scan
03-24 15:30:26.070  5836  5926 D BtGatt.ScanManager: isFilteringSupported
03-24 15:30:26.070  5836  5926 D BluetoothAdapter: setting StandAloneBleMode
,03-24 15:30:26.075  5836  5926 D BtGatt.ScanManager: isFilteringSupported
,03-24 15:30:26.075  5836  5926 D BluetoothAdapter: setting StandAloneBleMode
,03-24 15:30:26.080  5836  5926 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@201846a0
,03-24 15:30:26.085 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 15:30:26.085 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 15:30:26.085 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 15:30:26.085 11146 11225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 15:30:26.085 11146 11225 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 15:30:26.085 11146 11225 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 15:30:26.085 11146 11146 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 15:30:26.090 11146 11225 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 15:30:26.090 11146 11225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 15:30:26.090  5836  5906 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-24 15:30:26.090  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-24 15:30:26.090  5836  5926 D BtGatt.ScanManager: allow scan with filters,
03-24 15:30:26.095  5836  5926 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,03-24 15:30:26.095  5836  5926 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,03-24 15:30:26.100  5836  5906 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-24 15:30:26.100  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-24 15:30:26.100 11146 11146 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 15:30:26.100 11146 11146 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 15:30:26.100 11146 11146 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 15:30:26.100 11146 11225 I io.jxcore.node.ConnectionHelper: start: OK,
,03-24 15:30:26.105  5836  5926 D BtGatt.ScanManager: Starting BLE batch scan
,03-24 15:30:26.105  5836  5926 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-24 15:30:26.110  5836  5906 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-24 15:30:26.110  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-24 15:30:26.110  5836  5906 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-24 15:30:26.110  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-24 15:30:26.120 11146 11225 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 15:30:26.120 11146 11225 I jxcore-log: 
,03-24 15:30:26.125 11146 11225 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 15:30:26.125 11146 11225 I jxcore-log: 
,03-24 15:30:26.125 11146 11225 I jxcore-log: ok 94 error should be null
03-24 15:30:26.125 11146 11225 I jxcore-log: 
,03-24 15:30:26.130 11146 11225 I jxcore-log: ok 95 error should be null
03-24 15:30:26.130 11146 11225 I jxcore-log: 
,03-24 15:30:26.135 11146 11225 I io.jxcore.node.ConnectionHelper: start: Port number: 0, start advertisements: false
,03-24 15:30:26.135 11146 11225 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-24 15:30:26.135 11146 11225 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 15:30:26.135 11146 11225 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 15:30:26.140 11146 11225 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 15:30:26.145 11146 11225 I jxcore-log: ok 96 error should be null
03-24 15:30:26.145 11146 11225 I jxcore-log: 
,03-24 15:30:26.145 11146 11225 I jxcore-log: ok 97 error should be null
03-24 15:30:26.145 11146 11225 I jxcore-log: 
,03-24 15:30:26.150 11146 11225 I jxcore-log: # teardown
03-24 15:30:26.150 11146 11225 I jxcore-log: 
,03-24 15:30:26.365 11146 11225 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 15:30:26.370 11146 11225 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,03-24 15:30:26.370 11146 11225 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,03-24 15:30:26.370 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-24 15:30:26.370 11146 11225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-24 15:30:26.370 11146 11225 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-24 15:30:26.370 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-24 15:30:26.375 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-24 15:30:26.375 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-24 15:30:26.380  5836  5846 D BtGatt.GattService: stopScan() - queue size =1
03-24 15:30:26.380  5836  5926 D BtGatt.ScanManager: filter size is 1
03-24 15:30:26.380  5836  5926 D BtGatt.ScanManager: delete FilterIndex - 3
03-24 15:30:26.380  5836  5906 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-24 15:30:26.380  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-24 15:30:26.385  5836  5926 D BtGatt.ScanManager: stopping BLe Batch
,03-24 15:30:26.385  5836  5849 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 15:30:26.385  5836  5906 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,03-24 15:30:26.385  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-24 15:30:26.385  5836  5926 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-24 15:30:26.390  5836  5906 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0,
03-24 15:30:26.390  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-24 15:30:26.395 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
03-24 15:30:26.395 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-24 15:30:26.395 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 15:30:26.395 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-24 15:30:26.395 11146 11225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,03-24 15:30:26.395 11146 11225 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-24 15:30:26.400 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
03-24 15:30:26.400 11146 11225 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 15:30:26.400 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-24 15:30:26.400 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
03-24 15:30:26.400 11146 11225 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false,
,03-24 15:30:26.400 11146 11146 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
03-24 15:30:26.400 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-24 15:30:26.400 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-24 15:30:26.410 11146 11146 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-24 15:30:26.420 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
,03-24 15:30:26.420 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
03-24 15:30:26.420 11146 11146 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
,03-24 15:30:26.425 11146 11225 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).,
03-24 15:30:26.425 11146 11225 I jxcore-log: 
,03-24 15:30:26.430 11146 11146 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false,
03-24 15:30:26.430 11146 11146 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-24 15:30:26.430 11146 11146 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed,
03-24 15:30:26.430 11146 11146 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 15:30:26.435 11146 11225 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 15:30:26.435 11146 11225 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-24 15:30:26.435 11146 11225 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 15:30:26.440 11146 11225 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 15:30:26.440 11146 11225 I jxcore-log: 
,03-24 15:30:26.440 11146 11225 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 15:30:26.440 11146 11225 I jxcore-log: 
,03-24 15:30:26.445 11146 11225 I jxcore-log: ok 98 error should be null
03-24 15:30:26.445 11146 11225 I jxcore-log: 
,03-24 15:30:26.445 11146 11225 I jxcore-log: ok 99 error should be null
03-24 15:30:26.445 11146 11225 I jxcore-log: 
,03-24 15:30:26.455 11146 11225 I jxcore-log: # setup
03-24 15:30:26.455 11146 11225 I jxcore-log: 
,03-24 15:30:28.185 11146 11225 I jxcore-log: # 26. should be able to call #startUpdateAdvertisingAndListening many times
03-24 15:30:28.185 11146 11225 I jxcore-log: 
,03-24 15:30:28.470 11146 11225 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 15:30:28.470 11146 11225 I jxcore-log: 
,03-24 15:30:28.475 11146 11225 I jxcore-log: DEBUG createNativeListener: listening 58115
03-24 15:30:28.475 11146 11225 I jxcore-log: 
,03-24 15:30:28.490 11146 11225 I io.jxcore.node.ConnectionHelper: start: Port number: 58115, start advertisements: true
,03-24 15:30:28.490 11146 11225 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-24 15:30:28.495 11146 11225 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-24 15:30:28.495 11146 11225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 15:30:28.495 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-24 15:30:28.500 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 15:30:28.500 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 15:30:28.500 11146 11225 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 15:30:28.505  5836  5935 D BtGatt.GattService: registerClient() - UUID=892d1f57-c887-4022-b34c-0faf9fd71ed1
,03-24 15:30:28.545  5836  5906 D BtGatt.GattService: onClientRegistered() - UUID=892d1f57-c887-4022-b34c-0faf9fd71ed1, clientIf=6
,03-24 15:30:28.545 11146 11158 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-24 15:30:28.545  5836  9528 D BtGatt.GattService: start scan with filters
,03-24 15:30:28.560  5836  9528 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 55
,03-24 15:30:28.560 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 15:30:28.560 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 15:30:28.560 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 15:30:28.560 11146 11225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 15:30:28.560  5836  5926 D BtGatt.ScanManager: handling starting scan
03-24 15:30:28.560 11146 11225 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 15:30:28.560  5836  5926 D BtGatt.ScanManager: isFilteringSupported
03-24 15:30:28.560  5836  5926 D BluetoothAdapter: setting StandAloneBleMode
03-24 15:30:28.560 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 15:30:28.560 11146 11146 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 15:30:28.560 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-24 15:30:28.560 11146 11225 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-24 15:30:28.560 11146 11225 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 15:30:28.560 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 15:30:28.560 11146 11225 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 15:30:28.565  5836  9528 D BtGatt.GattService: registerClient() - UUID=b1ad7254-5df1-4390-bd7b-f744d77926d5
,03-24 15:30:28.565  5836  5906 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-24 15:30:28.565  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-24 15:30:28.565  5836  5926 D BtGatt.ScanManager: allow scan with filters
,03-24 15:30:28.565  5836  5926 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-24 15:30:28.565  5836  5926 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,03-24 15:30:28.570  5836  5906 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,03-24 15:30:28.570  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-24 15:30:28.570  5836  5926 D BtGatt.ScanManager: Starting BLE batch scan
03-24 15:30:28.570  5836  5926 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-24 15:30:28.570  5836  5906 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,03-24 15:30:28.570  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-24 15:30:28.575  5836  5906 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,03-24 15:30:28.575  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-24 15:30:28.605  5836  5906 D BtGatt.GattService: onClientRegistered() - UUID=b1ad7254-5df1-4390-bd7b-f744d77926d5, clientIf=7
,03-24 15:30:28.610 11146 11160 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-24 15:30:28.635  5836  5846 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 44
,03-24 15:30:28.640  5836  5917 D BtGatt.AdvertiseManager: message : 0
,03-24 15:30:28.645  5836  5917 D BtGatt.AdvertiseManager: number of adv instance running0
03-24 15:30:28.645  5836  5917 D BtGatt.AdvertiseManager: size of list is =0
,03-24 15:30:28.650  5836  5917 D BtGatt.AdvertiseManager: starting advertising
,03-24 15:30:28.650  5836  5917 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-24 15:30:28.655  5836  5906 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-24 15:30:28.660  5836  5917 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 15:30:28.660  5836  5906 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-24 15:30:28.660  5836  5917 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,03-24 15:30:28.660  5836  5917 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,03-24 15:30:28.665 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-24 15:30:28.665 11146 11225 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-24 15:30:28.670 11146 11225 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 15:30:28.670 11146 11225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-24 15:30:28.670 11146 11225 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,03-24 15:30:28.670 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-24 15:30:28.670 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-24 15:30:28.675 11146 11225 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,03-24 15:30:28.675 11146 11225 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,03-24 15:30:28.675 11146 11225 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-24 15:30:28.675 11146 11146 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-24 15:30:28.675 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 15:30:28.675 11146 11146 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 15:30:28.675 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 15:30:28.675 11146 11146 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-24 15:30:28.675 11146 11146 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-24 15:30:28.675 11146 11146 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 15:30:28.675 11146 11146 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 15:30:28.675 11146 11146 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 15:30:28.675 11146 11146 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 15:30:28.675 11146 11146 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-24 15:30:28.675 11146 11146 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-24 15:30:28.680 11146 11225 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 15:30:28.690 11146 11533 D BluetoothSocket: bindListen(): myUserId = 0
,03-24 15:30:28.695 11146 11533 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-24 15:30:28.700 11146 11533 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[114]}
,03-24 15:30:28.700 11146 11533 D BluetoothSocket: bindListen(), new LocalSocket 
03-24 15:30:28.700 11146 11533 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,03-24 15:30:28.700 11146 11533 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@b060f02
,03-24 15:30:28.700 11146 11533 D BluetoothSocket: channel: 6
03-24 15:30:28.700 11146 11533 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-24 15:30:28.705 11146 11225 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 15:30:28.705 11146 11225 I jxcore-log: 
,03-24 15:30:28.710 11146 11225 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 15:30:28.710 11146 11225 I jxcore-log: 
,03-24 15:30:28.710 11146 11225 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 15:30:28.710 11146 11225 I jxcore-log: 
,03-24 15:30:28.715 11146 11225 I jxcore-log: ok 100 error should be null
03-24 15:30:28.715 11146 11225 I jxcore-log: 
,03-24 15:30:28.715 11146 11225 I jxcore-log: ok 101 error should be null
03-24 15:30:28.715 11146 11225 I jxcore-log: 
,03-24 15:30:28.725 11146 11225 I io.jxcore.node.ConnectionHelper: start: Port number: 58115, start advertisements: true
03-24 15:30:28.725 11146 11225 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 15:30:28.725 11146 11225 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 15:30:28.725 11146 11225 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 15:30:28.725 11146 11225 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 15:30:28.735 11146 11225 I jxcore-log: ok 102 error should be null
03-24 15:30:28.735 11146 11225 I jxcore-log: 
,03-24 15:30:28.740 11146 11225 I jxcore-log: ok 103 error should be null
03-24 15:30:28.740 11146 11225 I jxcore-log: 
,03-24 15:30:28.745 11146 11225 I jxcore-log: # teardown
03-24 15:30:28.745 11146 11225 I jxcore-log: 
,03-24 15:30:29.575  3390  3620 V AlarmManager: waitForAlarm result :4
,03-24 15:30:29.590  5836  5836 D BtGatt.ScanManager: awakened up at time 263912
,03-24 15:30:29.600  5836  5926 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-24 15:30:29.605  5836  5906 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
03-24 15:30:29.605  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-24 15:30:29.605  5836  5906 D BtGatt.GattService: current time is 263928116780
03-24 15:30:29.605  5836  5906 D BtGatt.GattService: Batch record : [21, -77, -72, 111, -120, 91, 1, -128, -71, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,03-24 15:30:29.615  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
03-24 15:30:29.615  3727  3727 I PERF    : received broadcast android.intent.action.TIME_TICK
03-24 15:30:29.615  3727  3727 D KeyguardUpdateMonitor: handleTimeUpdate
,03-24 15:30:29.625  5836  5906 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 15:30:29.625  5836  5906 D ScanRecord: parseFromBytes,
,03-24 15:30:29.630  3727  3727 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,03-24 15:30:29.640  5836  5906 D BtGatt.GattService: result: ScanResult{mDevice=5B:88:6F:B8:B3:15, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-71, mTimestampNanos=263828415072},
03-24 15:30:29.640  5836  5906 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 15:30:29.640 11146 11160 D ScanRecord: parseFromBytes
03-24 15:30:29.645 11146 11146 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 1
03-24 15:30:29.645 11146 11146 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
,03-24 15:30:29.650 11146 11225 I jxcore-log: DEBUG createPeerListener: createPeerListener
03-24 15:30:29.650 11146 11225 I jxcore-log: 
,03-24 15:30:29.655  3727  3727 D SecKeyguardClockView: HomeTimezone(): 1
,03-24 15:30:29.660 11146 11225 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false
03-24 15:30:29.660 11146 11225 I jxcore-log: 
,03-24 15:30:29.665  3727  3727 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-24 15:30:29.665  3727  3727 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,03-24 15:30:29.675  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,03-24 15:30:29.705  3727  3727 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-24 15:30:29.710  3727  3727 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-24 15:30:29.715  3727  3727 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-24 15:30:29.715  3727  3727 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-24 15:30:29.720  3727  3727 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-24 15:30:29.720  3727  3727 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-24 15:30:29.735  3727  3727 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-24 15:30:29.945 11146 11225 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 15:30:29.945 11146 11225 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
,03-24 15:30:29.950 11146 11225 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,03-24 15:30:29.950 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,03-24 15:30:29.950 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,03-24 15:30:29.955 11146 11225 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1a37250, channel: 6, state: LISTENING
,03-24 15:30:29.955 11146 11225 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1a37250, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@b060f02, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@394c3c49mSocket: android.net.LocalSocket@94a194e impl:android.net.LocalSocketImpl@2896ba6f fd:FileDescriptor[114]
,03-24 15:30:29.960 11146 11225 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@94a194e impl:android.net.LocalSocketImpl@2896ba6f fd:FileDescriptor[114]
,03-24 15:30:29.960 11146 11225 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-24 15:30:29.960 11146 11533 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-24 15:30:29.960 11146 11533 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-24 15:30:29.960 11146 11533 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-24 15:30:29.960 11146 11146 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-24 15:30:29.960 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-24 15:30:29.965 11146 11146 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-24 15:30:29.965 11146 11146 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-24 15:30:29.965 11146 11225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 15:30:29.965 11146 11225 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 15:30:29.965 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 15:30:29.965 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 15:30:29.965 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-24 15:30:29.970  5836  5935 D BtGatt.GattService: stopScan() - queue size =1,
03-24 15:30:29.970  5836  5926 D BtGatt.ScanManager: filter size is 1
03-24 15:30:29.970  5836  5926 D BtGatt.ScanManager: delete FilterIndex - 4
03-24 15:30:29.970  5836  5906 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-24 15:30:29.970  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-24 15:30:29.970  5836  5926 D BtGatt.ScanManager: stopping BLe Batch
,03-24 15:30:29.975  5836  5906 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0,
,03-24 15:30:29.975  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
03-24 15:30:29.975  5836  5926 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-24 15:30:29.975  5836  5906 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=4,
,03-24 15:30:29.975  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-24 15:30:29.975  5836  5906 D BtGatt.GattService: current time is 264299366447
03-24 15:30:29.975  5836  5906 D BtGatt.GattService: Batch record : [21, -77, -72, 111, -120, 91, 1, -128, -86, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -49, 10, -91, -100, 76, 108, 1, -128, -56, 6, 0, 0, 0, -28, -44, -106, -22, -38, 116, 0, -128, -96, 6, 0, 23, 2, 1, 6, 3, 2, 5, 24, 15, 9, 90, 101, 70, 105, 116, 50, 32, 35, 54, 54, 48, 55, 53, 0, 16, 15, 9, 90, 101, 70, 105, 116, 50, 32, 35, 54, 54, 48, 55, 53, 0, -49, 10, -91, -100, 76, 108, 1, -128, -65, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0],
03-24 15:30:29.975  5836  5906 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81],
,03-24 15:30:29.975  5836  5906 D ScanRecord: parseFromBytes,
03-24 15:30:29.980  5836  5906 D BtGatt.GattService: ScanRecord : []
03-24 15:30:29.980  5836  5906 D ScanRecord: parseFromBytes,
,03-24 15:30:29.980  5836  5906 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 5, 24, 15, 9, 90, 101, 70, 105, 116, 50, 32, 35, 54, 54, 48, 55, 53, 0, 15, 9, 90, 101, 70, 105, 116, 50, 32, 35, 54, 54, 48, 55, 53, 0]
03-24 15:30:29.980  5836  5906 D ScanRecord: parseFromBytes,
,03-24 15:30:29.980  5836  5906 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
,03-24 15:30:29.980  5836  5906 D ScanRecord: parseFromBytes
03-24 15:30:29.980  5836  9528 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 15:30:29.985 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 15:30:29.985 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 15:30:29.985 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,03-24 15:30:29.985 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-24 15:30:29.985 11146 11225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-24 15:30:29.985 11146 11225 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 15:30:29.985 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-24 15:30:29.990  5836  5917 D BtGatt.AdvertiseManager: message : 1
03-24 15:30:29.990  5836  5917 D BtGatt.AdvertiseManager: stop advertise for client 7
,03-24 15:30:29.990  5836  5917 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-24 15:30:29.990  5836  5917 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-24 15:30:29.990  5836  5906 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-24 15:30:29.990  5836  5906 D BtGatt.GattService: Client app is not null!
03-24 15:30:29.995  5836  5935 D BtGatt.GattService: unregisterClient() - clientIf=7
03-24 15:30:29.995 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
03-24 15:30:29.995 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 15:30:29.995 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-24 15:30:29.995 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-24 15:30:29.995 11146 11225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED],
,03-24 15:30:29.995 11146 11225 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false,
03-24 15:30:29.995 11146 11225 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped,
03-24 15:30:29.995 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-24 15:30:30.000 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
,03-24 15:30:30.000 11146 11225 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-24 15:30:30.000 11146 11225 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 15:30:30.000 11146 11146 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
03-24 15:30:30.000 11146 11146 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed,
,03-24 15:30:30.000 11146 11146 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 15:30:30.000 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 15:30:30.000 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-24 15:30:30.005 11146 11146 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-24 15:30:30.010 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-24 15:30:30.010 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 15:30:30.010 11146 11146 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 15:30:30.020 11146 11146 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 15:30:30.020 11146 11146 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false,
03-24 15:30:30.020 11146 11146 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 15:30:30.020 11146 11225 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 15:30:30.020 11146 11225 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 15:30:30.020 11146 11225 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 15:30:30.030 11146 11225 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-24 15:30:30.030 11146 11225 I jxcore-log: 
,03-24 15:30:30.030 11146 11225 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-24 15:30:30.030 11146 11225 I jxcore-log: 
03-24 15:30:30.030 11146 11225 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 15:30:30.030 11146 11225 I jxcore-log: 
03-24 15:30:30.035 11146 11225 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 15:30:30.035 11146 11225 I jxcore-log: 
,03-24 15:30:30.040 11146 11225 I jxcore-log: ok 104 error should be null
03-24 15:30:30.040 11146 11225 I jxcore-log: 
,03-24 15:30:30.040 11146 11225 I jxcore-log: ok 105 error should be null
03-24 15:30:30.040 11146 11225 I jxcore-log: 
,03-24 15:30:30.045 11146 11225 I jxcore-log: # setup
03-24 15:30:30.045 11146 11225 I jxcore-log: 
,03-24 15:30:30.350 11146 11225 I jxcore-log: # 27. should be able to call #stopAdvertisingAndListening many times
03-24 15:30:30.350 11146 11225 I jxcore-log: 
,03-24 15:30:30.525 11146 11225 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 15:30:30.525 11146 11225 I jxcore-log: 
,03-24 15:30:30.530 11146 11225 I jxcore-log: DEBUG createNativeListener: listening 50989
03-24 15:30:30.530 11146 11225 I jxcore-log: 
,03-24 15:30:30.535 11146 11225 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 15:30:30.540 11146 11225 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-24 15:30:30.540 11146 11225 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 15:30:30.545 11146 11225 I jxcore-log: ok 106 error should be null
03-24 15:30:30.545 11146 11225 I jxcore-log: 
,03-24 15:30:30.545 11146 11225 I jxcore-log: ok 107 error should be null
03-24 15:30:30.545 11146 11225 I jxcore-log: 
,03-24 15:30:30.550 11146 11225 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 15:30:30.550 11146 11225 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-24 15:30:30.550 11146 11225 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 15:30:30.555 11146 11225 I jxcore-log: ok 108 error should be null
03-24 15:30:30.555 11146 11225 I jxcore-log: 
,03-24 15:30:30.555 11146 11225 I jxcore-log: ok 109 error should be null
03-24 15:30:30.555 11146 11225 I jxcore-log: 
,03-24 15:30:30.565 11146 11225 I jxcore-log: # teardown
03-24 15:30:30.565 11146 11225 I jxcore-log: 
,03-24 15:30:30.710 11146 11225 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 15:30:30.710 11146 11225 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-24 15:30:30.710 11146 11225 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 15:30:30.715 11146 11225 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 15:30:30.715 11146 11225 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-24 15:30:30.715 11146 11225 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 15:30:30.725 11146 11225 I jxcore-log: ok 110 error should be null
03-24 15:30:30.725 11146 11225 I jxcore-log: 
,03-24 15:30:30.730 11146 11225 I jxcore-log: ok 111 error should be null
03-24 15:30:30.730 11146 11225 I jxcore-log: 
,03-24 15:30:30.735 11146 11225 I jxcore-log: # setup
03-24 15:30:30.735 11146 11225 I jxcore-log: 
,03-24 15:30:30.885 11146 11225 I jxcore-log: # 28. #start should fail if called twice in a row
03-24 15:30:30.885 11146 11225 I jxcore-log: 
,03-24 15:30:31.040 11146 11225 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 15:30:31.040 11146 11225 I jxcore-log: 
,03-24 15:30:31.045 11146 11225 I jxcore-log: DEBUG createNativeListener: listening 55499
03-24 15:30:31.045 11146 11225 I jxcore-log: 
,03-24 15:30:31.050 11146 11225 I jxcore-log: ok 112 first call should succeed
03-24 15:30:31.050 11146 11225 I jxcore-log: 
,03-24 15:30:31.050 11146 11225 I jxcore-log: ok 113 first call should succeed
03-24 15:30:31.050 11146 11225 I jxcore-log: 
,03-24 15:30:31.055 11146 11225 I jxcore-log: ok 114 specific error should be returned
03-24 15:30:31.055 11146 11225 I jxcore-log: 
,03-24 15:30:31.060 11146 11225 I jxcore-log: # teardown
03-24 15:30:31.060 11146 11225 I jxcore-log: 
,03-24 15:30:31.110  3390  3572 W ProcessCpuTracker: Skipping unknown process pid 11565
,03-24 15:30:31.185 11146 11225 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections,
03-24 15:30:31.185 11146 11225 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 15:30:31.185 11146 11225 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 15:30:31.185 11146 11225 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 15:30:31.185 11146 11225 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 15:30:31.185 11146 11225 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 15:30:31.195 11146 11225 I jxcore-log: ok 115 error should be null
03-24 15:30:31.195 11146 11225 I jxcore-log: 
,03-24 15:30:31.200 11146 11225 I jxcore-log: ok 116 error should be null
03-24 15:30:31.200 11146 11225 I jxcore-log: 
,03-24 15:30:31.215 11146 11225 I jxcore-log: # setup
03-24 15:30:31.215 11146 11225 I jxcore-log: 
,03-24 15:30:31.315 11146 11225 I jxcore-log: # 29. does not emit duplicate discoveryAdvertisingStateUpdate
03-24 15:30:31.315 11146 11225 I jxcore-log: 
,03-24 15:30:31.470 11146 11225 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 15:30:31.470 11146 11225 I jxcore-log: 
,03-24 15:30:31.475 11146 11225 I jxcore-log: DEBUG createNativeListener: listening 45901
03-24 15:30:31.475 11146 11225 I jxcore-log: 
,03-24 15:30:31.485 11146 11225 I io.jxcore.node.ConnectionHelper: start: Port number: 58115, start advertisements: false
,03-24 15:30:31.485 11146 11225 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 15:30:31.485 11146 11225 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,03-24 15:30:31.485 11146 11225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-24 15:30:31.490 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-24 15:30:31.490 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 15:30:31.490 11146 11225 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 15:30:31.495  5836  5935 D BtGatt.GattService: registerClient() - UUID=c4c912c3-3f1c-4005-9ce7-2e506c98e95a
,03-24 15:30:31.535  5836  5906 D BtGatt.GattService: onClientRegistered() - UUID=c4c912c3-3f1c-4005-9ce7-2e506c98e95a, clientIf=6
,03-24 15:30:31.535 11146 11158 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-24 15:30:31.540  5836  9528 D BtGatt.GattService: start scan with filters
,03-24 15:30:31.550  5836  9528 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 56
,03-24 15:30:31.550 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 15:30:31.550 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 15:30:31.550 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 15:30:31.550 11146 11225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 15:30:31.550 11146 11225 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 15:30:31.550  5836  5926 D BtGatt.ScanManager: handling starting scan
03-24 15:30:31.550 11146 11225 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 15:30:31.550  5836  5926 D BtGatt.ScanManager: isFilteringSupported
03-24 15:30:31.550  5836  5926 D BluetoothAdapter: setting StandAloneBleMode
03-24 15:30:31.550 11146 11146 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-24 15:30:31.555 11146 11225 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 15:30:31.555 11146 11225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 15:30:31.555 11146 11225 I io.jxcore.node.ConnectionHelper: start: OK
03-24 15:30:31.555 11146 11146 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 15:30:31.555 11146 11146 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 15:30:31.555 11146 11146 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 15:30:31.555  5836  5906 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-24 15:30:31.555  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-24 15:30:31.555  5836  5926 D BtGatt.ScanManager: allow scan with filters
03-24 15:30:31.555  5836  5926 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-24 15:30:31.555  5836  5926 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,03-24 15:30:31.555  5836  5906 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-24 15:30:31.555  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-24 15:30:31.555  5836  5926 D BtGatt.ScanManager: Starting BLE batch scan
03-24 15:30:31.555  5836  5926 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-24 15:30:31.560  5836  5906 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0,
03-24 15:30:31.560  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-24 15:30:31.560 11146 11225 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 15:30:31.560 11146 11225 I jxcore-log: 
,03-24 15:30:31.560  5836  5906 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-24 15:30:31.560  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-24 15:30:31.560 11146 11225 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 15:30:31.560 11146 11225 I jxcore-log: 
,03-24 15:30:31.575 11146 11225 I io.jxcore.node.ConnectionHelper: start: Port number: 45901, start advertisements: true
,03-24 15:30:31.575 11146 11225 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 15:30:31.575 11146 11225 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-24 15:30:31.575 11146 11225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 15:30:31.575 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-24 15:30:31.575 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
03-24 15:30:31.575 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 15:30:31.575 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-24 15:30:31.575 11146 11225 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-24 15:30:31.575 11146 11225 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 15:30:31.575 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-24 15:30:31.575 11146 11225 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 15:30:31.580  5836  9528 D BtGatt.GattService: registerClient() - UUID=51cf518e-8244-4c2a-809a-f5cb23204c57
,03-24 15:30:31.620  5836  5906 D BtGatt.GattService: onClientRegistered() - UUID=51cf518e-8244-4c2a-809a-f5cb23204c57, clientIf=7
,03-24 15:30:31.620 11146 11160 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-24 15:30:31.635  5836  5846 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 45
,03-24 15:30:31.635  5836  5917 D BtGatt.AdvertiseManager: message : 0
03-24 15:30:31.635  5836  5917 D BtGatt.AdvertiseManager: number of adv instance running0
03-24 15:30:31.635  5836  5917 D BtGatt.AdvertiseManager: size of list is =0
,03-24 15:30:31.635  5836  5917 D BtGatt.AdvertiseManager: starting advertising
03-24 15:30:31.635  5836  5917 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-24 15:30:31.640  5836  5906 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-24 15:30:31.640  5836  5917 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 15:30:31.640  5836  5906 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
03-24 15:30:31.640  5836  5917 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-24 15:30:31.640  5836  5917 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,03-24 15:30:31.640 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 15:30:31.640 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-24 15:30:31.640 11146 11225 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-24 15:30:31.640 11146 11146 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 15:30:31.640 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 15:30:31.640 11146 11146 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-24 15:30:31.640 11146 11146 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
,03-24 15:30:31.645 11146 11225 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 15:30:31.645 11146 11225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 15:30:31.645 11146 11225 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-24 15:30:31.645 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 15:30:31.645 11146 11146 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-24 15:30:31.645 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-24 15:30:31.645 11146 11225 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-24 15:30:31.645 11146 11225 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-24 15:30:31.645 11146 11225 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-24 15:30:31.645 11146 11225 I io.jxcore.node.ConnectionHelper: start: OK
03-24 15:30:31.645 11146 11146 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,03-24 15:30:31.645 11146 11146 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 15:30:31.645 11146 11146 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,03-24 15:30:31.655 11146 11582 D BluetoothSocket: bindListen(): myUserId = 0
03-24 15:30:31.655 11146 11582 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-24 15:30:31.655 11146 11225 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 15:30:31.655 11146 11225 I jxcore-log: 
,03-24 15:30:31.660 11146 11582 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[115]}
03-24 15:30:31.660 11146 11582 D BluetoothSocket: bindListen(), new LocalSocket 
03-24 15:30:31.660 11146 11582 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-24 15:30:31.660 11146 11582 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1f7e8e8b
03-24 15:30:31.660 11146 11582 D BluetoothSocket: channel: 6
03-24 15:30:31.660 11146 11582 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-24 15:30:31.660  3390  4028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:30:31.660  3390  4028 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:30:31.660  3390  4028 D BatteryService: online:4, current avg:46, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:31
,03-24 15:30:31.660  3390  4028 D BatteryService: stay LED for fully charged
03-24 15:30:31.660  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-24 15:30:31.660  3390  3390 I MotionRecognitionService: Plugged
,03-24 15:30:31.660  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:30:31.660  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-24 15:30:31.660  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
03-24 15:30:31.665 11146 11225 I jxcore-log: ok 117 called only once
03-24 15:30:31.665 11146 11225 I jxcore-log: 
,03-24 15:30:31.665 11146 11225 I jxcore-log: ok 118 discovery state matches
03-24 15:30:31.665 11146 11225 I jxcore-log: 
,03-24 15:30:31.665 11146 11225 I jxcore-log: ok 119 advertising state matches
03-24 15:30:31.665 11146 11225 I jxcore-log: 
,03-24 15:30:31.665  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:30:31.665  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:30:31.665  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:30:31.675  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-24 15:30:31.675  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:30:31.675 11146 11225 I jxcore-log: # teardown
03-24 15:30:31.675 11146 11225 I jxcore-log: 
,03-24 15:30:31.685  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:30:31.690  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:30:31.690  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:30:31.690  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:30:31.855  3390  6051 D SSRM:n  : SIOP:: AP = 280, PST = 285 (W:12), CUR = 46, LCD = 0
,03-24 15:30:31.990 11146 11225 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 15:30:31.990 11146 11225 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
,03-24 15:30:31.990 11146 11225 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-24 15:30:31.990 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,03-24 15:30:31.995 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-24 15:30:31.995 11146 11225 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2d33b68, channel: 6, state: LISTENING
,03-24 15:30:31.995 11146 11225 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2d33b68, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1f7e8e8b, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2a7a2b81mSocket: android.net.LocalSocket@360c0426 impl:android.net.LocalSocketImpl@7c58867 fd:FileDescriptor[115]
,03-24 15:30:31.995 11146 11225 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@360c0426 impl:android.net.LocalSocketImpl@7c58867 fd:FileDescriptor[115]
,03-24 15:30:31.995 11146 11225 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-24 15:30:31.995 11146 11582 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-24 15:30:31.995 11146 11582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-24 15:30:31.995 11146 11582 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-24 15:30:32.000 11146 11146 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-24 15:30:32.000 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-24 15:30:32.000 11146 11146 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-24 15:30:32.000 11146 11146 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-24 15:30:32.000 11146 11225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-24 15:30:32.000 11146 11225 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 15:30:32.000 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 15:30:32.000 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-24 15:30:32.000 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-24 15:30:32.005  5836  9528 D BtGatt.GattService: stopScan() - queue size =1,
03-24 15:30:32.005  5836  5926 D BtGatt.ScanManager: filter size is 1
03-24 15:30:32.005  5836  5926 D BtGatt.ScanManager: delete FilterIndex - 5
,03-24 15:30:32.005  5836  5906 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16,
,03-24 15:30:32.005  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
03-24 15:30:32.005  5836  5926 D BtGatt.ScanManager: stopping BLe Batch,
,03-24 15:30:32.010  5836  5906 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-24 15:30:32.010  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-24 15:30:32.010  5836  5926 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6,
,03-24 15:30:32.010  5836  5906 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2,
,03-24 15:30:32.010  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-24 15:30:32.010  5836  5906 D BtGatt.GattService: current time is 266334278739,
,03-24 15:30:32.010  5836  5906 D BtGatt.GattService: Batch record : [71, -128, 19, 2, 85, 67, 1, -128, -75, 5, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, 33, 127, -114, -125, -112, 82, 1, -128, -61, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0],
,03-24 15:30:32.010  5836  5906 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81],
,03-24 15:30:32.010  5836  5906 D ScanRecord: parseFromBytes
,03-24 15:30:32.010  5836  5906 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-24 15:30:32.010  5836  5906 D ScanRecord: parseFromBytes
03-24 15:30:32.015  5836  5846 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-24 15:30:32.020 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 15:30:32.020 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 15:30:32.020 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,03-24 15:30:32.020 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-24 15:30:32.020 11146 11225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-24 15:30:32.020 11146 11225 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 15:30:32.020 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-24 15:30:32.020  5836  5917 D BtGatt.AdvertiseManager: message : 1
,03-24 15:30:32.020  5836  5917 D BtGatt.AdvertiseManager: stop advertise for client 7
03-24 15:30:32.020  5836  5917 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-24 15:30:32.025  5836  5917 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-24 15:30:32.025  5836  5906 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-24 15:30:32.025  5836  5906 D BtGatt.GattService: Client app is not null!
,03-24 15:30:32.025  5836  9528 D BtGatt.GattService: unregisterClient() - clientIf=7
03-24 15:30:32.030 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 15:30:32.030 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED,
,03-24 15:30:32.030 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-24 15:30:32.030 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,03-24 15:30:32.030 11146 11225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-24 15:30:32.030 11146 11225 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 15:30:32.030 11146 11225 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 15:30:32.030 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-24 15:30:32.035 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 15:30:32.035 11146 11225 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 15:30:32.035 11146 11146 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-24 15:30:32.035 11146 11146 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 15:30:32.035 11146 11146 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 15:30:32.035 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 15:30:32.035 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-24 15:30:32.040 11146 11146 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-24 15:30:32.045 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-24 15:30:32.045 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 15:30:32.045 11146 11146 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 15:30:32.045 11146 11225 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 15:30:32.045 11146 11225 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 15:30:32.045 11146 11225 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 15:30:32.060 11146 11225 I jxcore-log: INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
03-24 15:30:32.060 11146 11225 I jxcore-log: 
03-24 15:30:32.060 11146 11146 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 15:30:32.060 11146 11146 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 15:30:32.060 11146 11146 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 15:30:32.060 11146 11225 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-24 15:30:32.060 11146 11225 I jxcore-log: 
,03-24 15:30:32.065 11146 11225 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-24 15:30:32.065 11146 11225 I jxcore-log: 
,03-24 15:30:32.065 11146 11225 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-24 15:30:32.065 11146 11225 I jxcore-log: 
,03-24 15:30:32.065 11146 11225 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 15:30:32.065 11146 11225 I jxcore-log: 
,03-24 15:30:32.070 11146 11225 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 15:30:32.070 11146 11225 I jxcore-log: 
,03-24 15:30:32.075 11146 11225 I jxcore-log: ok 120 error should be null
03-24 15:30:32.075 11146 11225 I jxcore-log: 
,03-24 15:30:32.075 11146 11225 I jxcore-log: ok 121 error should be null
03-24 15:30:32.075 11146 11225 I jxcore-log: 
,03-24 15:30:32.080 11146 11225 I jxcore-log: # setup
03-24 15:30:32.080 11146 11225 I jxcore-log: 
,03-24 15:30:32.410 11146 11225 I jxcore-log: # 30. does not send duplicate availability changes
03-24 15:30:32.410 11146 11225 I jxcore-log: 
,03-24 15:30:32.605 11146 11225 I jxcore-log: ok 122 should be called once
03-24 15:30:32.605 11146 11225 I jxcore-log: 
,03-24 15:30:32.605 11146 11225 I jxcore-log: ok 123 should not have been called more than once
03-24 15:30:32.605 11146 11225 I jxcore-log: 
,03-24 15:30:32.610 11146 11225 I jxcore-log: # teardown
03-24 15:30:32.610 11146 11225 I jxcore-log: 
,03-24 15:30:32.720 11146 11225 I jxcore-log: ok 124 error should be null
03-24 15:30:32.720 11146 11225 I jxcore-log: 
,03-24 15:30:32.725 11146 11225 I jxcore-log: ok 125 error should be null
03-24 15:30:32.725 11146 11225 I jxcore-log: 
,03-24 15:30:32.730 11146 11225 I jxcore-log: # setup
03-24 15:30:32.730 11146 11225 I jxcore-log: 
,03-24 15:30:32.890 11146 11225 I jxcore-log: # 31. can get the network status
03-24 15:30:32.890 11146 11225 I jxcore-log: 
,03-24 15:30:32.990 11146 11225 I jxcore-log: ok 126 network status should have certain non-empty properties
03-24 15:30:32.990 11146 11225 I jxcore-log: 
,03-24 15:30:32.995 11146 11225 I jxcore-log: # teardown
03-24 15:30:32.995 11146 11225 I jxcore-log: 
,03-24 15:30:33.165 11146 11225 I jxcore-log: ok 127 error should be null
03-24 15:30:33.165 11146 11225 I jxcore-log: 
,03-24 15:30:33.165 11146 11225 I jxcore-log: ok 128 error should be null
03-24 15:30:33.165 11146 11225 I jxcore-log: 
,03-24 15:30:33.170 11146 11225 I jxcore-log: # setup
03-24 15:30:33.170 11146 11225 I jxcore-log: 
,03-24 15:30:33.275 11146 11225 I jxcore-log: # 32. wifi peer is marked unavailable if announcements stop
03-24 15:30:33.275 11146 11225 I jxcore-log: 
,03-24 15:30:33.440 11146 11225 I jxcore-log: ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
03-24 15:30:33.440 11146 11225 I jxcore-log: 
,03-24 15:30:33.470 11146 11225 I jxcore-log: ok 129 host address should match
03-24 15:30:33.470 11146 11225 I jxcore-log: 
,03-24 15:30:33.475 11146 11225 I jxcore-log: ok 130 port should match
03-24 15:30:33.475 11146 11225 I jxcore-log: 
,03-24 15:30:35.455 11146 11225 I jxcore-log: ok 131 host address should be null
03-24 15:30:35.455 11146 11225 I jxcore-log: 
,03-24 15:30:35.465 11146 11225 I jxcore-log: ok 132 port should should be null
03-24 15:30:35.465 11146 11225 I jxcore-log: 
,03-24 15:30:35.485  3390  6082 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-24 15:30:35.490 11146 11225 I jxcore-log: # teardown
03-24 15:30:35.490 11146 11225 I jxcore-log: 
,03-24 15:30:35.565 11146 11225 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-24 15:30:35.565 11146 11225 I jxcore-log: 
,03-24 15:30:35.570 11146 11225 I jxcore-log: ok 133 error should be null
03-24 15:30:35.570 11146 11225 I jxcore-log: 
,03-24 15:30:35.570 11146 11225 I jxcore-log: ok 134 error should be null
03-24 15:30:35.570 11146 11225 I jxcore-log: 
,03-24 15:30:35.575 11146 11225 I jxcore-log: # setup
03-24 15:30:35.575 11146 11225 I jxcore-log: 
,03-24 15:30:35.675 11146 11225 I jxcore-log: # 33. Can call start/stopListeningForAdvertisements
03-24 15:30:35.675 11146 11225 I jxcore-log: 
,03-24 15:30:35.810 11146 11225 I io.jxcore.node.ConnectionHelper: start: Port number: 45901, start advertisements: false
,03-24 15:30:35.810 11146 11225 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-24 15:30:35.810 11146 11225 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,03-24 15:30:35.810 11146 11225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-24 15:30:35.815 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-24 15:30:35.815 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-24 15:30:35.815 11146 11225 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 15:30:35.825  5836  9528 D BtGatt.GattService: registerClient() - UUID=6d1ab980-f9a2-4bb0-9679-0ded0ce48644
,03-24 15:30:35.865  5836  5906 D BtGatt.GattService: onClientRegistered() - UUID=6d1ab980-f9a2-4bb0-9679-0ded0ce48644, clientIf=6
,03-24 15:30:35.865 11146 11160 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-24 15:30:35.865  5836  5846 D BtGatt.GattService: start scan with filters
,03-24 15:30:35.880  5836  5846 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 57
,03-24 15:30:35.880 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 15:30:35.880 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 15:30:35.880 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 15:30:35.880 11146 11225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 15:30:35.880 11146 11225 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 15:30:35.880  5836  5926 D BtGatt.ScanManager: handling starting scan
03-24 15:30:35.880  5836  5926 D BtGatt.ScanManager: isFilteringSupported
03-24 15:30:35.880  5836  5926 D BluetoothAdapter: setting StandAloneBleMode
03-24 15:30:35.880 11146 11225 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 15:30:35.880 11146 11146 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-24 15:30:35.880 11146 11225 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
03-24 15:30:35.885 11146 11225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 15:30:35.885 11146 11146 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 15:30:35.885 11146 11146 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 15:30:35.885 11146 11146 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 15:30:35.885 11146 11225 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 15:30:35.885  5836  5906 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-24 15:30:35.885  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-24 15:30:35.885  5836  5926 D BtGatt.ScanManager: allow scan with filters
,03-24 15:30:35.885  5836  5926 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-24 15:30:35.885  5836  5926 D BtGatt.ScanManager: set filter index= 6 for clientIf= 6
,03-24 15:30:35.885 11146 11225 I jxcore-log: ok 135 Can call startListeningForAdvertisements without error
03-24 15:30:35.885 11146 11225 I jxcore-log: 
03-24 15:30:35.885  5836  5906 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-24 15:30:35.885  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-24 15:30:35.885  5836  5926 D BtGatt.ScanManager: Starting BLE batch scan
03-24 15:30:35.885  5836  5926 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-24 15:30:35.885 11146 11225 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 15:30:35.885 11146 11225 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only,
,03-24 15:30:35.885 11146 11225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-24 15:30:35.885 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-24 15:30:35.890  5836  5906 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-24 15:30:35.890  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-24 15:30:35.890  5836  5846 D BtGatt.GattService: stopScan() - queue size =1
,03-24 15:30:35.890  5836  5935 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-24 15:30:35.890  5836  5906 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-24 15:30:35.890  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-24 15:30:35.890 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 15:30:35.890 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 15:30:35.890 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,03-24 15:30:35.890 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-24 15:30:35.890 11146 11225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-24 15:30:35.890 11146 11225 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 15:30:35.890 11146 11146 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 15:30:35.890 11146 11146 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 15:30:35.890 11146 11146 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 15:30:35.895 11146 11225 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 15:30:35.895 11146 11225 I jxcore-log: 
03-24 15:30:35.895 11146 11225 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 15:30:35.895 11146 11225 I jxcore-log: 
03-24 15:30:35.895  5836  5926 D BtGatt.ScanManager: filter size is 1
03-24 15:30:35.895  5836  5926 D BtGatt.ScanManager: delete FilterIndex - 6
,03-24 15:30:35.895  5836  5906 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-24 15:30:35.895 11146 11225 I jxcore-log: ok 136 Can call stopListeningForAdvertisements without error
03-24 15:30:35.895 11146 11225 I jxcore-log: 
03-24 15:30:35.895  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-24 15:30:35.895  5836  5926 D BtGatt.ScanManager: stopping BLe Batch
,03-24 15:30:35.900  5836  5906 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0,
03-24 15:30:35.900  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-24 15:30:35.900  5836  5926 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-24 15:30:35.900  5836  5906 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-24 15:30:35.900  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-24 15:30:35.905 11146 11225 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 15:30:35.905 11146 11225 I jxcore-log: 
,03-24 15:30:35.905 11146 11225 I jxcore-log: # teardown
03-24 15:30:35.905 11146 11225 I jxcore-log: 
,03-24 15:30:35.965 11146 11225 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 15:30:35.965 11146 11225 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 15:30:35.965 11146 11225 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 15:30:35.970 11146 11225 I jxcore-log: ok 137 Should be able to call stopListeningForAdvertisments in teardown
03-24 15:30:35.970 11146 11225 I jxcore-log: 
,03-24 15:30:35.970 11146 11225 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 15:30:35.970 11146 11225 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 15:30:35.970 11146 11225 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-24 15:30:35.975 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 15:30:35.975 11146 11225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 15:30:35.975 11146 11225 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 15:30:35.975 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 15:30:35.975 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-24 15:30:35.975 11146 11225 D BluetoothLeScanner: could not find callback wrapper
,03-24 15:30:35.975 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-24 15:30:35.975 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 15:30:35.975 11146 11225 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 15:30:35.975 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-24 15:30:35.975 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-24 15:30:35.975 11146 11225 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 15:30:35.975 11146 11146 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 15:30:35.975 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 15:30:35.975 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-24 15:30:35.985 11146 11146 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-24 15:30:35.990 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-24 15:30:35.990 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-24 15:30:35.990 11146 11146 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 15:30:35.995 11146 11146 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 15:30:35.995 11146 11146 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 15:30:35.995 11146 11146 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 15:30:36.000 11146 11225 I jxcore-log: ok 138 Should be able to call stopAdvertisingAndListening in teardown
03-24 15:30:36.000 11146 11225 I jxcore-log: 
,03-24 15:30:36.015 11146 11225 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 15:30:36.015 11146 11225 I jxcore-log: 
,03-24 15:30:36.015 11146 11225 I jxcore-log: # setup
03-24 15:30:36.015 11146 11225 I jxcore-log: 
,03-24 15:30:36.145 11146 11225 I jxcore-log: # 34. Calling startListeningForAdvertisements twice is NOT an error,
03-24 15:30:36.145 11146 11225 I jxcore-log: 
,03-24 15:30:36.265 11146 11225 I io.jxcore.node.ConnectionHelper: start: Port number: 45901, start advertisements: false
,03-24 15:30:36.270 11146 11225 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-24 15:30:36.270 11146 11225 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,03-24 15:30:36.270 11146 11225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-24 15:30:36.280 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-24 15:30:36.280 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-24 15:30:36.280 11146 11225 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 15:30:36.285  5836  9528 D BtGatt.GattService: registerClient() - UUID=c8ff4835-56f7-4869-8c28-6a4759b98ee3
,03-24 15:30:36.325  5836  5906 D BtGatt.GattService: onClientRegistered() - UUID=c8ff4835-56f7-4869-8c28-6a4759b98ee3, clientIf=6
,03-24 15:30:36.325 11146 11160 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-24 15:30:36.325  5836  5846 D BtGatt.GattService: start scan with filters
,03-24 15:30:36.340  5836  5846 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 58
,03-24 15:30:36.340 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 15:30:36.340 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 15:30:36.340 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 15:30:36.340 11146 11225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 15:30:36.340 11146 11225 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 15:30:36.340 11146 11225 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 15:30:36.340 11146 11146 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 15:30:36.340  5836  5926 D BtGatt.ScanManager: handling starting scan
03-24 15:30:36.340  5836  5926 D BtGatt.ScanManager: isFilteringSupported
03-24 15:30:36.340  5836  5926 D BluetoothAdapter: setting StandAloneBleMode
,03-24 15:30:36.340  5836  5906 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-24 15:30:36.340  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-24 15:30:36.345  5836  5926 D BtGatt.ScanManager: allow scan with filters
03-24 15:30:36.345  5836  5926 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-24 15:30:36.345  5836  5926 D BtGatt.ScanManager: set filter index= 7 for clientIf= 6
,03-24 15:30:36.345 11146 11225 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 15:30:36.345 11146 11225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 15:30:36.345 11146 11225 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 15:30:36.345 11146 11146 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 15:30:36.345 11146 11146 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 15:30:36.345 11146 11146 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 15:30:36.345  5836  5906 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,03-24 15:30:36.345  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-24 15:30:36.345  5836  5926 D BtGatt.ScanManager: Starting BLE batch scan
03-24 15:30:36.345  5836  5926 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-24 15:30:36.345  5836  5906 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,03-24 15:30:36.345 11146 11225 I jxcore-log: ok 139 Can call startListeningForAdvertisements without error
03-24 15:30:36.345 11146 11225 I jxcore-log: 
03-24 15:30:36.345  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-24 15:30:36.350  5836  5906 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-24 15:30:36.350  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-24 15:30:36.350 11146 11225 I io.jxcore.node.ConnectionHelper: start: Port number: 45901, start advertisements: false
,03-24 15:30:36.350 11146 11225 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 15:30:36.350 11146 11225 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 15:30:36.350 11146 11225 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 15:30:36.350 11146 11225 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 15:30:36.355 11146 11225 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 15:30:36.355 11146 11225 I jxcore-log: 
,03-24 15:30:36.355 11146 11225 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 15:30:36.355 11146 11225 I jxcore-log: ,
,03-24 15:30:36.355 11146 11225 I jxcore-log: ok 140 Can call startListeningForAdvertisements twice without error
03-24 15:30:36.355 11146 11225 I jxcore-log: 
,03-24 15:30:36.365 11146 11225 I jxcore-log: # teardown
03-24 15:30:36.365 11146 11225 I jxcore-log: 
,03-24 15:30:36.580 11146 11225 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 15:30:36.580 11146 11225 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 15:30:36.580 11146 11225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-24 15:30:36.580 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-24 15:30:36.585  5836  5849 D BtGatt.GattService: stopScan() - queue size =1
,03-24 15:30:36.590  5836  5926 D BtGatt.ScanManager: filter size is 1
03-24 15:30:36.590  5836  5926 D BtGatt.ScanManager: delete FilterIndex - 7
03-24 15:30:36.590  5836  9528 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-24 15:30:36.590  5836  5906 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16,
,03-24 15:30:36.590  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-24 15:30:36.595  5836  5926 D BtGatt.ScanManager: stopping BLe Batch,
,03-24 15:30:36.595 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 15:30:36.595 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED,
,03-24 15:30:36.595 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false,
,03-24 15:30:36.595 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,03-24 15:30:36.595 11146 11225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,03-24 15:30:36.595 11146 11225 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 15:30:36.595 11146 11146 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 15:30:36.595 11146 11146 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only,
,03-24 15:30:36.595 11146 11146 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 15:30:36.595  5836  5906 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-24 15:30:36.595  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-24 15:30:36.595  5836  5926 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-24 15:30:36.600  5836  5906 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-24 15:30:36.600  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-24 15:30:36.605 11146 11225 I jxcore-log: ok 141 Should be able to call stopListeningForAdvertisments in teardown
03-24 15:30:36.605 11146 11225 I jxcore-log: 
03-24 15:30:36.605 11146 11225 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections,
03-24 15:30:36.605 11146 11225 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-24 15:30:36.605 11146 11225 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-24 15:30:36.605 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-24 15:30:36.605 11146 11225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-24 15:30:36.605 11146 11225 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart,
,03-24 15:30:36.605 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode,
,03-24 15:30:36.605 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-24 15:30:36.605 11146 11225 D BluetoothLeScanner: could not find callback wrapper
,03-24 15:30:36.605 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 15:30:36.610 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-24 15:30:36.610 11146 11225 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 15:30:36.610 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-24 15:30:36.610 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 15:30:36.610 11146 11225 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 15:30:36.610 11146 11146 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 15:30:36.610 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 15:30:36.610 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-24 15:30:36.620 11146 11146 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-24 15:30:36.625 11146 11225 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 15:30:36.625 11146 11225 I jxcore-log: 
,03-24 15:30:36.625 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-24 15:30:36.630 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 15:30:36.630 11146 11146 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 15:30:36.630 11146 11146 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 15:30:36.630 11146 11146 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 15:30:36.630 11146 11146 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 15:30:36.630 11146 11225 I jxcore-log: ok 142 Should be able to call stopAdvertisingAndListening in teardown
03-24 15:30:36.630 11146 11225 I jxcore-log: 
,03-24 15:30:36.640 11146 11225 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 15:30:36.640 11146 11225 I jxcore-log: 
,03-24 15:30:36.640 11146 11225 I jxcore-log: # setup
03-24 15:30:36.640 11146 11225 I jxcore-log: 
,03-24 15:30:36.720 11146 11225 I jxcore-log: # 35. Can call start/stopUpdateAdvertisingAndListening
03-24 15:30:36.720 11146 11225 I jxcore-log: 
,03-24 15:30:36.890 11146 11225 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true
,03-24 15:30:36.890 11146 11225 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-24 15:30:36.890 11146 11225 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,03-24 15:30:36.890 11146 11225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 15:30:36.895 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-24 15:30:36.895 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-24 15:30:36.900 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-24 15:30:36.900 11146 11225 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 15:30:36.905  5836  5849 D BtGatt.GattService: registerClient() - UUID=efac376a-99c3-4049-baf8-91f2fb2c5e4d
,03-24 15:30:36.950  5836  5906 D BtGatt.GattService: onClientRegistered() - UUID=efac376a-99c3-4049-baf8-91f2fb2c5e4d, clientIf=6
,03-24 15:30:36.950 11146 11160 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-24 15:30:36.950  5836  5846 D BtGatt.GattService: start scan with filters
,03-24 15:30:36.960  5836  5846 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 59
,03-24 15:30:36.960 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 15:30:36.960 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 15:30:36.960 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 15:30:36.960 11146 11225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,03-24 15:30:36.960  5836  5926 D BtGatt.ScanManager: handling starting scan
03-24 15:30:36.960 11146 11225 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 15:30:36.960  5836  5926 D BtGatt.ScanManager: isFilteringSupported
03-24 15:30:36.960  5836  5926 D BluetoothAdapter: setting StandAloneBleMode
03-24 15:30:36.960 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 15:30:36.960 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-24 15:30:36.960 11146 11146 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 15:30:36.960 11146 11225 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-24 15:30:36.960 11146 11225 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 15:30:36.960 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 15:30:36.960 11146 11225 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 15:30:36.965  5836  5906 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,03-24 15:30:36.965  5836  5846 D BtGatt.GattService: registerClient() - UUID=7c409068-68c0-4332-b957-0ef8ebcd174e
03-24 15:30:36.965  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-24 15:30:36.965  5836  5926 D BtGatt.ScanManager: allow scan with filters
03-24 15:30:36.965  5836  5926 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-24 15:30:36.965  5836  5926 D BtGatt.ScanManager: set filter index= 8 for clientIf= 6
,03-24 15:30:36.965  5836  5906 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-24 15:30:36.965  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-24 15:30:36.965  5836  5926 D BtGatt.ScanManager: Starting BLE batch scan
03-24 15:30:36.965  5836  5926 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-24 15:30:36.970  5836  5906 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0,
03-24 15:30:36.970  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-24 15:30:36.970  5836  5906 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,03-24 15:30:36.970  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-24 15:30:37.005  5836  5906 D BtGatt.GattService: onClientRegistered() - UUID=7c409068-68c0-4332-b957-0ef8ebcd174e, clientIf=7
,03-24 15:30:37.005 11146 11158 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-24 15:30:37.050  5836  9528 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 46
,03-24 15:30:37.060  5836  5917 D BtGatt.AdvertiseManager: message : 0
,03-24 15:30:37.065  5836  5917 D BtGatt.AdvertiseManager: number of adv instance running0
03-24 15:30:37.065  5836  5917 D BtGatt.AdvertiseManager: size of list is =0
,03-24 15:30:37.075  5836  5917 D BtGatt.AdvertiseManager: starting advertising,
,03-24 15:30:37.080  5836  5917 D BtGatt.AdvertiseManager: isStandardAdvfalse,
,03-24 15:30:37.095  5836  5906 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-24 15:30:37.100  5836  5917 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 15:30:37.105  5836  5906 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-24 15:30:37.105  5836  5917 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,03-24 15:30:37.105  5836  5917 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0,
,03-24 15:30:37.110 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-24 15:30:37.110 11146 11225 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK,
,03-24 15:30:37.115 11146 11225 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 15:30:37.120 11146 11225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-24 15:30:37.120 11146 11225 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,03-24 15:30:37.120 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-24 15:30:37.120 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-24 15:30:37.125 11146 11225 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,03-24 15:30:37.125 11146 11225 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,03-24 15:30:37.125 11146 11225 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-24 15:30:37.125 11146 11146 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,03-24 15:30:37.125 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 15:30:37.125 11146 11146 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,03-24 15:30:37.125 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 15:30:37.125 11146 11146 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
,03-24 15:30:37.125 11146 11146 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-24 15:30:37.125 11146 11146 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 15:30:37.125 11146 11146 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 15:30:37.125 11146 11146 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 15:30:37.125 11146 11146 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 15:30:37.125 11146 11146 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING,
03-24 15:30:37.125 11146 11146 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-24 15:30:37.130 11146 11225 I io.jxcore.node.ConnectionHelper: start: OK,
03-24 15:30:37.135 11146 11225 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 15:30:37.135 11146 11225 I jxcore-log: 
,03-24 15:30:37.135 11146 11225 I jxcore-log: ok 143 Can call startUpdateAdvertisingAndListening without error
03-24 15:30:37.135 11146 11225 I jxcore-log: 
,03-24 15:30:37.145 11146 11647 D BluetoothSocket: bindListen(): myUserId = 0
,03-24 15:30:37.145 11146 11647 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-24 15:30:37.145 11146 11647 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[92]}
,03-24 15:30:37.150 11146 11647 D BluetoothSocket: bindListen(), new LocalSocket 
,03-24 15:30:37.150 11146 11647 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-24 15:30:37.150 11146 11647 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@25ea4875
,03-24 15:30:37.150 11146 11647 D BluetoothSocket: channel: 6
,03-24 15:30:37.150 11146 11647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-24 15:30:37.150 11146 11225 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 15:30:37.150 11146 11225 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-24 15:30:37.150 11146 11225 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,03-24 15:30:37.150 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-24 15:30:37.150 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,03-24 15:30:37.155 11146 11225 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@652b00a, channel: 6, state: LISTENING
03-24 15:30:37.155 11146 11225 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@652b00a, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@25ea4875, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1494307bmSocket: android.net.LocalSocket@24004e98 impl:android.net.LocalSocketImpl@da3f6f1 fd:FileDescriptor[92]
,03-24 15:30:37.155 11146 11225 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@24004e98 impl:android.net.LocalSocketImpl@da3f6f1 fd:FileDescriptor[92]
,03-24 15:30:37.155 11146 11225 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-24 15:30:37.155 11146 11647 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-24 15:30:37.155 11146 11647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-24 15:30:37.155 11146 11647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-24 15:30:37.155 11146 11146 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-24 15:30:37.155 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-24 15:30:37.160 11146 11146 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-24 15:30:37.160 11146 11146 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-24 15:30:37.160 11146 11225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 15:30:37.160 11146 11225 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 15:30:37.160 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 15:30:37.160 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 15:30:37.160 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-24 15:30:37.165  5836  5849 D BtGatt.GattService: stopScan() - queue size =1
,03-24 15:30:37.165  5836  5926 D BtGatt.ScanManager: filter size is 1
03-24 15:30:37.165  5836  5846 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 15:30:37.165  5836  5926 D BtGatt.ScanManager: delete FilterIndex - 8
,03-24 15:30:37.165  5836  5906 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-24 15:30:37.165 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 15:30:37.165 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 15:30:37.165 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 15:30:37.165  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-24 15:30:37.165 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-24 15:30:37.165 11146 11225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-24 15:30:37.165  5836  5926 D BtGatt.ScanManager: stopping BLe Batch
03-24 15:30:37.165 11146 11225 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 15:30:37.165 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-24 15:30:37.170  5836  5917 D BtGatt.AdvertiseManager: message : 1
,03-24 15:30:37.170  5836  5906 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-24 15:30:37.170  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-24 15:30:37.170  5836  5917 D BtGatt.AdvertiseManager: stop advertise for client 7
,03-24 15:30:37.170  5836  5917 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-24 15:30:37.170  5836  5926 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-24 15:30:37.170  5836  5917 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,03-24 15:30:37.170  5836  5906 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-24 15:30:37.170  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-24 15:30:37.170  5836  5906 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
,03-24 15:30:37.170  5836  5906 D BtGatt.GattService: Client app is not null!
,03-24 15:30:37.175  5836  5849 D BtGatt.GattService: unregisterClient() - clientIf=7
,03-24 15:30:37.175 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 15:30:37.175 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 15:30:37.175 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,03-24 15:30:37.175 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-24 15:30:37.175 11146 11225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-24 15:30:37.175 11146 11225 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 15:30:37.175 11146 11225 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 15:30:37.175 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-24 15:30:37.175 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-24 15:30:37.175 11146 11225 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 15:30:37.175 11146 11146 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 15:30:37.175 11146 11146 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 15:30:37.175 11146 11146 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 15:30:37.175 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 15:30:37.175 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-24 15:30:37.175 11146 11225 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 15:30:37.175 11146 11225 I jxcore-log: 
,03-24 15:30:37.180 11146 11225 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 15:30:37.180 11146 11225 I jxcore-log: 
,03-24 15:30:37.180 11146 11146 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-24 15:30:37.180 11146 11225 I jxcore-log: ok 144 Can call stopAdvertisingAndListening without error
03-24 15:30:37.180 11146 11225 I jxcore-log: 
,03-24 15:30:37.185 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-24 15:30:37.185 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-24 15:30:37.185 11146 11146 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 15:30:37.185 11146 11225 I jxcore-log: # teardown
03-24 15:30:37.185 11146 11225 I jxcore-log: 
,03-24 15:30:37.190 11146 11146 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-24 15:30:37.190 11146 11146 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 15:30:37.190 11146 11146 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 15:30:37.190 11146 11225 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-24 15:30:37.190 11146 11225 I jxcore-log: 
,03-24 15:30:37.195 11146 11225 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 15:30:37.195 11146 11225 I jxcore-log: 
,03-24 15:30:37.195 11146 11225 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 15:30:37.195 11146 11225 I jxcore-log: 
,03-24 15:30:37.265 11146 11225 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 15:30:37.265 11146 11225 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 15:30:37.265 11146 11225 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 15:30:37.270 11146 11225 I jxcore-log: ok 145 Should be able to call stopListeningForAdvertisments in teardown
03-24 15:30:37.270 11146 11225 I jxcore-log: 
,03-24 15:30:37.275 11146 11225 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 15:30:37.275 11146 11225 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 15:30:37.275 11146 11225 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 15:30:37.280 11146 11225 I jxcore-log: ok 146 Should be able to call stopAdvertisingAndListening in teardown
03-24 15:30:37.280 11146 11225 I jxcore-log: 
,03-24 15:30:37.290 11146 11225 I jxcore-log: # setup
03-24 15:30:37.290 11146 11225 I jxcore-log: 
,03-24 15:30:38.120 11146 11225 I jxcore-log: # 36. Calling startUpdateAdvertisingAndListening twice is NOT an error
03-24 15:30:38.120 11146 11225 I jxcore-log: 
,03-24 15:30:38.260 11146 11225 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true
,03-24 15:30:38.260 11146 11225 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-24 15:30:38.260 11146 11225 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,03-24 15:30:38.260 11146 11225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 15:30:38.265 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-24 15:30:38.270 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-24 15:30:38.270 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-24 15:30:38.270 11146 11225 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 15:30:38.275  5836  5849 D BtGatt.GattService: registerClient() - UUID=afb8bbc8-0923-492e-9c79-1fa95f12c3b4
,03-24 15:30:38.315  5836  5906 D BtGatt.GattService: onClientRegistered() - UUID=afb8bbc8-0923-492e-9c79-1fa95f12c3b4, clientIf=6
,03-24 15:30:38.320 11146 11158 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-24 15:30:38.320  5836  5846 D BtGatt.GattService: start scan with filters
,03-24 15:30:38.330  5836  5846 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 60
,03-24 15:30:38.330 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-24 15:30:38.330 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 15:30:38.330  5836  5926 D BtGatt.ScanManager: handling starting scan
03-24 15:30:38.330  5836  5926 D BtGatt.ScanManager: isFilteringSupported
,03-24 15:30:38.330 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 15:30:38.330  5836  5926 D BluetoothAdapter: setting StandAloneBleMode
03-24 15:30:38.330 11146 11225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 15:30:38.330 11146 11225 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 15:30:38.330 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...,
,03-24 15:30:38.330 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-24 15:30:38.330 11146 11146 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-24 15:30:38.330 11146 11225 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-24 15:30:38.330 11146 11225 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 15:30:38.330 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 15:30:38.330 11146 11225 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 15:30:38.335  5836  5906 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-24 15:30:38.335  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-24 15:30:38.335  5836  5926 D BtGatt.ScanManager: allow scan with filters
03-24 15:30:38.335  5836  5926 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-24 15:30:38.335  5836  5926 D BtGatt.ScanManager: set filter index= 9 for clientIf= 6
03-24 15:30:38.335  5836  5846 D BtGatt.GattService: registerClient() - UUID=f10c86ac-7fab-40d2-9904-35d8572f8f64
,03-24 15:30:38.335  5836  5906 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-24 15:30:38.335  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-24 15:30:38.335  5836  5926 D BtGatt.ScanManager: Starting BLE batch scan
03-24 15:30:38.335  5836  5926 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-24 15:30:38.340  5836  5906 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,03-24 15:30:38.340  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-24 15:30:38.340  5836  5906 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-24 15:30:38.340  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-24 15:30:38.375  5836  5906 D BtGatt.GattService: onClientRegistered() - UUID=f10c86ac-7fab-40d2-9904-35d8572f8f64, clientIf=7
,03-24 15:30:38.375 11146 11160 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-24 15:30:38.390  5836  9528 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 47,
03-24 15:30:38.390  5836  5917 D BtGatt.AdvertiseManager: message : 0
03-24 15:30:38.390  5836  5917 D BtGatt.AdvertiseManager: number of adv instance running0
,03-24 15:30:38.390  5836  5917 D BtGatt.AdvertiseManager: size of list is =0
,03-24 15:30:38.390  5836  5917 D BtGatt.AdvertiseManager: starting advertising
,03-24 15:30:38.390  5836  5917 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-24 15:30:38.395  5836  5906 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-24 15:30:38.395  5836  5917 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 15:30:38.395  5836  5906 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-24 15:30:38.395  5836  5917 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-24 15:30:38.395  5836  5917 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
03-24 15:30:38.395 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-24 15:30:38.395 11146 11225 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-24 15:30:38.400 11146 11225 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 15:30:38.400 11146 11225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 15:30:38.400 11146 11225 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-24 15:30:38.400 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 15:30:38.400 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-24 15:30:38.400 11146 11225 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-24 15:30:38.400 11146 11225 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-24 15:30:38.400 11146 11225 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-24 15:30:38.400 11146 11225 I io.jxcore.node.ConnectionHelper: start: OK
03-24 15:30:38.400 11146 11146 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-24 15:30:38.400 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 15:30:38.400 11146 11146 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 15:30:38.400 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 15:30:38.400 11146 11146 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-24 15:30:38.400 11146 11146 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-24 15:30:38.400 11146 11146 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 15:30:38.400 11146 11146 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 15:30:38.400 11146 11146 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 15:30:38.400 11146 11146 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 15:30:38.400 11146 11146 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-24 15:30:38.400 11146 11146 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-24 15:30:38.405 11146 11225 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 15:30:38.405 11146 11225 I jxcore-log: 
,03-24 15:30:38.405 11146 11663 D BluetoothSocket: bindListen(): myUserId = 0
03-24 15:30:38.405 11146 11663 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-24 15:30:38.405 11146 11225 I jxcore-log: ok 147 Can call startUpdateAdvertisingAndListening without error
03-24 15:30:38.405 11146 11225 I jxcore-log: 
,03-24 15:30:38.405 11146 11663 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[92]}
,03-24 15:30:38.405 11146 11663 D BluetoothSocket: bindListen(), new LocalSocket 
03-24 15:30:38.405 11146 11663 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-24 15:30:38.405 11146 11663 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2d70112d
03-24 15:30:38.405 11146 11663 D BluetoothSocket: channel: 6
03-24 15:30:38.405 11146 11663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-24 15:30:38.410 11146 11225 I io.jxcore.node.ConnectionHelper: start: Port number: 4243, start advertisements: true
03-24 15:30:38.410 11146 11225 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 15:30:38.410 11146 11225 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 15:30:38.410 11146 11225 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 15:30:38.410 11146 11225 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 15:30:38.410 11146 11225 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 15:30:38.410 11146 11225 I jxcore-log: 
,03-24 15:30:38.410 11146 11225 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 15:30:38.410 11146 11225 I jxcore-log: 
,03-24 15:30:38.415 11146 11225 I jxcore-log: ok 148 Can call startUpdateAdvertisingAndListening twice without error
03-24 15:30:38.415 11146 11225 I jxcore-log: 
,03-24 15:30:38.420 11146 11225 I jxcore-log: # teardown
03-24 15:30:38.420 11146 11225 I jxcore-log: 
,03-24 15:30:38.625 11146 11225 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 15:30:38.625 11146 11225 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
,03-24 15:30:38.630 11146 11225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-24 15:30:38.630 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-24 15:30:38.630  5836  5935 D BtGatt.GattService: stopScan() - queue size =1
03-24 15:30:38.635  5836  5926 D BtGatt.ScanManager: filter size is 1
03-24 15:30:38.635  5836  5926 D BtGatt.ScanManager: delete FilterIndex - 9
,03-24 15:30:38.635  5836  5906 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16,
,03-24 15:30:38.635  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-24 15:30:38.635  5836  5926 D BtGatt.ScanManager: stopping BLe Batch
,03-24 15:30:38.640  5836  5906 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-24 15:30:38.640  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-24 15:30:38.640  5836  5926 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-24 15:30:38.645  5836  5906 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
03-24 15:30:38.645  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-24 15:30:38.645  5836  5906 D BtGatt.GattService: current time is 272967331198
03-24 15:30:38.645  5836  5906 D BtGatt.GattService: Batch record : [-65, 4, 114, -96, 51, 124, 1, -128, -60, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0, 99, 110, -100, -53, 77, 88, 1, -128, -76, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,03-24 15:30:38.645  5836  5906 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
,03-24 15:30:38.645  5836  5906 D ScanRecord: parseFromBytes,
03-24 15:30:38.645  5836  5906 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 15:30:38.645  5836  5906 D ScanRecord: parseFromBytes
,03-24 15:30:38.650  5836  5849 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-24 15:30:38.650 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 15:30:38.650 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 15:30:38.650 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 15:30:38.650 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING],
03-24 15:30:38.650 11146 11225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-24 15:30:38.650 11146 11225 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-24 15:30:38.650 11146 11146 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 15:30:38.655 11146 11146 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-24 15:30:38.655 11146 11146 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 15:30:38.655 11146 11225 I jxcore-log: ok 149 Should be able to call stopListeningForAdvertisments in teardown
03-24 15:30:38.655 11146 11225 I jxcore-log: 
03-24 15:30:38.655 11146 11225 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 15:30:38.655 11146 11225 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,03-24 15:30:38.655 11146 11225 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-24 15:30:38.655 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-24 15:30:38.655 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,03-24 15:30:38.655 11146 11225 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@33c13662, channel: 6, state: LISTENING
03-24 15:30:38.660 11146 11225 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@33c13662, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2d70112d, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@19a233f3mSocket: android.net.LocalSocket@36d658b0 impl:android.net.LocalSocketImpl@30699329 fd:FileDescriptor[92]
03-24 15:30:38.660 11146 11225 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@36d658b0 impl:android.net.LocalSocketImpl@30699329 fd:FileDescriptor[92]
03-24 15:30:38.660 11146 11225 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-24 15:30:38.660 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 15:30:38.660 11146 11225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 15:30:38.660 11146 11225 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 15:30:38.660 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 15:30:38.660 11146 11663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-24 15:30:38.660 11146 11663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-24 15:30:38.660 11146 11663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-24 15:30:38.660 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-24 15:30:38.660 11146 11225 D BluetoothLeScanner: could not find callback wrapper
03-24 15:30:38.660 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-24 15:30:38.660 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-24 15:30:38.660  5836  5917 D BtGatt.AdvertiseManager: message : 1
03-24 15:30:38.665  5836  5917 D BtGatt.AdvertiseManager: stop advertise for client 7
03-24 15:30:38.665  5836  5917 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
,03-24 15:30:38.665  5836  5917 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-24 15:30:38.665  5836  5906 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-24 15:30:38.665  5836  5906 D BtGatt.GattService: Client app is not null!
03-24 15:30:38.665  5836  5849 D BtGatt.GattService: unregisterClient() - clientIf=7
03-24 15:30:38.670 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-24 15:30:38.670 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 15:30:38.670 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-24 15:30:38.670 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-24 15:30:38.670 11146 11225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED],
,03-24 15:30:38.670 11146 11225 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 15:30:38.670 11146 11225 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 15:30:38.670 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-24 15:30:38.670 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-24 15:30:38.670 11146 11225 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false,
,03-24 15:30:38.670 11146 11146 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 15:30:38.670 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-24 15:30:38.670 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-24 15:30:38.675 11146 11225 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-24 15:30:38.675 11146 11225 I jxcore-log: 
03-24 15:30:38.680 11146 11146 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-24 15:30:38.685 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-24 15:30:38.685 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 15:30:38.685 11146 11146 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 15:30:38.690 11146 11146 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-24 15:30:38.690 11146 11146 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-24 15:30:38.690 11146 11146 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 15:30:38.690 11146 11146 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 15:30:38.690 11146 11146 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 15:30:38.690 11146 11146 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 15:30:38.690 11146 11146 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-24 15:30:38.690 11146 11225 I jxcore-log: ok 150 Should be able to call stopAdvertisingAndListening in teardown
03-24 15:30:38.690 11146 11225 I jxcore-log: 
,03-24 15:30:38.695 11146 11225 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 15:30:38.695 11146 11225 I jxcore-log: 
,03-24 15:30:38.700 11146 11225 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 15:30:38.700 11146 11225 I jxcore-log: 
,03-24 15:30:38.700 11146 11225 I jxcore-log: # setup
03-24 15:30:38.700 11146 11225 I jxcore-log: 
,03-24 15:30:38.835 11146 11225 I jxcore-log: # 37. peerAvailabilityChange is called
03-24 15:30:38.835 11146 11225 I jxcore-log: 
,03-24 15:30:38.930 11146 11225 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true
03-24 15:30:38.930 11146 11225 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 15:30:38.930 11146 11225 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-24 15:30:38.930 11146 11225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 15:30:38.930 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-24 15:30:38.930 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 15:30:38.930 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 15:30:38.930 11146 11225 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 15:30:38.935  5836  5849 D BtGatt.GattService: registerClient() - UUID=0200a211-d247-42b8-a3a3-8f72c01eec61
,03-24 15:30:38.980  5836  5906 D BtGatt.GattService: onClientRegistered() - UUID=0200a211-d247-42b8-a3a3-8f72c01eec61, clientIf=6
,03-24 15:30:38.980 11146 11160 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-24 15:30:38.980  5836  5846 D BtGatt.GattService: start scan with filters
,03-24 15:30:39.005  5836  5846 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 61
,03-24 15:30:39.005  5836  5926 D BtGatt.ScanManager: handling starting scan
,03-24 15:30:39.005  5836  5926 D BtGatt.ScanManager: isFilteringSupported
03-24 15:30:39.005  5836  5926 D BluetoothAdapter: setting StandAloneBleMode
,03-24 15:30:39.010  5836  5906 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-24 15:30:39.015  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-24 15:30:39.015  5836  5926 D BtGatt.ScanManager: allow scan with filters
03-24 15:30:39.015  5836  5926 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-24 15:30:39.015  5836  5926 D BtGatt.ScanManager: set filter index= 10 for clientIf= 6
03-24 15:30:39.015  5836  5906 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,03-24 15:30:39.015  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-24 15:30:39.020  5836  5926 D BtGatt.ScanManager: Starting BLE batch scan,
,03-24 15:30:39.020  5836  5926 D BtGatt.ScanManager: configuring batch scan storage, appIf 6,
03-24 15:30:39.020  5836  5906 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,03-24 15:30:39.020  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-24 15:30:39.025  5836  5906 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1,
03-24 15:30:39.025  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-24 15:30:39.025 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 15:30:39.025 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 15:30:39.025 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 15:30:39.025 11146 11225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 15:30:39.025 11146 11225 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 15:30:39.025 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 15:30:39.025 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0",
03-24 15:30:39.030 11146 11146 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-24 15:30:39.030 11146 11225 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-24 15:30:39.030 11146 11225 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 15:30:39.030 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 15:30:39.030 11146 11225 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-24 15:30:39.035  5836  9528 D BtGatt.GattService: registerClient() - UUID=3c5ee91b-5b3c-4258-8003-653412f673f4
,03-24 15:30:39.075  5836  5906 D BtGatt.GattService: onClientRegistered() - UUID=3c5ee91b-5b3c-4258-8003-653412f673f4, clientIf=7,
03-24 15:30:39.075 11146 11158 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-24 15:30:39.105  5836  5935 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 48
,03-24 15:30:39.105  5836  5917 D BtGatt.AdvertiseManager: message : 0
,03-24 15:30:39.105  5836  5917 D BtGatt.AdvertiseManager: number of adv instance running0
03-24 15:30:39.105  5836  5917 D BtGatt.AdvertiseManager: size of list is =0
,03-24 15:30:39.110  5836  5917 D BtGatt.AdvertiseManager: starting advertising
03-24 15:30:39.110  5836  5917 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-24 15:30:39.115  5836  5906 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-24 15:30:39.120  5836  5917 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 15:30:39.125  5836  5906 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-24 15:30:39.125  5836  5917 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-24 15:30:39.125  5836  5917 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,03-24 15:30:39.125 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING,
03-24 15:30:39.125 11146 11225 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 15:30:39.130 11146 11225 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 15:30:39.130 11146 11225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 15:30:39.130 11146 11225 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-24 15:30:39.130 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-24 15:30:39.135 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...,
03-24 15:30:39.135 11146 11225 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-24 15:30:39.135 11146 11225 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-24 15:30:39.135 11146 11225 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-24 15:30:39.135 11146 11146 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,03-24 15:30:39.135 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 15:30:39.135 11146 11146 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 15:30:39.135 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 15:30:39.135 11146 11146 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-24 15:30:39.135 11146 11146 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-24 15:30:39.135 11146 11146 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 15:30:39.135 11146 11146 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 15:30:39.135 11146 11146 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 15:30:39.135 11146 11146 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 15:30:39.135 11146 11146 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-24 15:30:39.135 11146 11146 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 15:30:39.135 11146 11225 I io.jxcore.node.ConnectionHelper: start: OK
03-24 15:30:39.135 11146 11225 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 15:30:39.135 11146 11225 I jxcore-log: 
,03-24 15:30:39.145 11146 11682 D BluetoothSocket: bindListen(): myUserId = 0,
03-24 15:30:39.145 11146 11682 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-24 15:30:39.145 11146 11682 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[92]}
03-24 15:30:39.145 11146 11682 D BluetoothSocket: bindListen(), new LocalSocket 
03-24 15:30:39.145 11146 11682 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-24 15:30:39.145 11146 11682 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3e5f38e5
03-24 15:30:39.145 11146 11682 D BluetoothSocket: channel: 6
,03-24 15:30:39.145 11146 11682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-24 15:30:39.150 11146 11225 I jxcore-log: ok 151 Can call startUpdateAdvertisingAndListeningwithout error
03-24 15:30:39.150 11146 11225 I jxcore-log: 
,03-24 15:30:39.155 11146 11225 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: false
,03-24 15:30:39.155 11146 11225 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 15:30:39.155 11146 11225 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
,03-24 15:30:39.155 11146 11225 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 15:30:39.155 11146 11225 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 15:30:39.160 11146 11225 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 15:30:39.160 11146 11225 I jxcore-log: 
,03-24 15:30:39.170 11146 11225 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 15:30:39.170 11146 11225 I jxcore-log: 
,03-24 15:30:39.175 11146 11225 I jxcore-log: ok 152 Can call startListeningForAdvertisements without error
03-24 15:30:39.175 11146 11225 I jxcore-log: 
,03-24 15:30:40.035  3390  3620 V AlarmManager: waitForAlarm result :4
,03-24 15:30:40.045  5836  5836 D BtGatt.ScanManager: awakened up at time 274368
,03-24 15:30:40.050  5836  5926 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-24 15:30:40.060  5836  5906 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
03-24 15:30:40.060  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
03-24 15:30:40.060  5836  5906 D BtGatt.GattService: current time is 274383431115
,03-24 15:30:40.060  5836  5906 D BtGatt.GattService: Batch record : [0, 18, -103, 31, -124, 86, 1, -128, -72, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-24 15:30:40.060  5836  5906 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 15:30:40.060  5836  5906 D ScanRecord: parseFromBytes,
,03-24 15:30:40.060  5836  5906 D BtGatt.GattService: result: ScanResult{mDevice=56:84:1F:99:12:00, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-72, mTimestampNanos=274283568490}
,03-24 15:30:40.060  5836  5906 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-24 15:30:40.065 11146 11158 D ScanRecord: parseFromBytes
03-24 15:30:40.065 11146 11146 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 1
,03-24 15:30:40.065 11146 11146 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
03-24 15:30:40.075 11146 11225 I jxcore-log: ok 153 peers must be an array
03-24 15:30:40.075 11146 11225 I jxcore-log: 
03-24 15:30:40.075 11146 11225 I jxcore-log: ok 154 peers must not be zero-length,
,03-24 15:30:40.075 11146 11225 I jxcore-log: 
03-24 15:30:40.075 11146 11225 I jxcore-log: ok 155 peer must have peerIdentifier
03-24 15:30:40.075 11146 11225 I jxcore-log: 
,03-24 15:30:40.085 11146 11225 I jxcore-log: ok 156 peerIdentifier must be a string
03-24 15:30:40.085 11146 11225 I jxcore-log: 
,03-24 15:30:40.090 11146 11225 I jxcore-log: ok 157 peer must have peerAvailable
03-24 15:30:40.090 11146 11225 I jxcore-log: 
,03-24 15:30:40.090 11146 11225 I jxcore-log: ok 158 peer must have pleaseConnect
03-24 15:30:40.090 11146 11225 I jxcore-log: 
,03-24 15:30:40.100 11146 11225 I jxcore-log: # teardown
03-24 15:30:40.100 11146 11225 I jxcore-log: 
,03-24 15:30:40.270 11146 11225 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 15:30:40.270 11146 11225 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
,03-24 15:30:40.275 11146 11225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,03-24 15:30:40.275 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-24 15:30:40.275  5836  5846 D BtGatt.GattService: stopScan() - queue size =1
03-24 15:30:40.280  5836  5926 D BtGatt.ScanManager: filter size is 1
03-24 15:30:40.280  5836  5926 D BtGatt.ScanManager: delete FilterIndex - 10
03-24 15:30:40.280  5836  5906 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-24 15:30:40.280  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-24 15:30:40.280  5836  5926 D BtGatt.ScanManager: stopping BLe Batch,
,03-24 15:30:40.285  5836  5906 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0,
03-24 15:30:40.285  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-24 15:30:40.285  5836  5926 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6,
03-24 15:30:40.285  5836  5906 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
03-24 15:30:40.285  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-24 15:30:40.285  5836  5906 D BtGatt.GattService: current time is 274609545156
,03-24 15:30:40.285  5836  5906 D BtGatt.GattService: Batch record : [0, 18, -103, 31, -124, 86, 1, -128, -77, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-24 15:30:40.285  5836  5906 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-24 15:30:40.285  5836  5906 D ScanRecord: parseFromBytes,
,03-24 15:30:40.290  5836  9528 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 15:30:40.295 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 15:30:40.295 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED,
03-24 15:30:40.295 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false,
,03-24 15:30:40.295 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING],
,03-24 15:30:40.295 11146 11225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-24 15:30:40.295 11146 11225 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-24 15:30:40.295 11146 11146 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true,
03-24 15:30:40.300 11146 11146 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-24 15:30:40.300 11146 11146 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 15:30:40.305 11146 11225 I jxcore-log: ok 159 Should be able to call stopListeningForAdvertisments in teardown
03-24 15:30:40.305 11146 11225 I jxcore-log: 
,03-24 15:30:40.305 11146 11225 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 15:30:40.305 11146 11225 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-24 15:30:40.305 11146 11225 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,03-24 15:30:40.305 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-24 15:30:40.305 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,03-24 15:30:40.310 11146 11225 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3c0e2e6b, channel: 6, state: LISTENING
,03-24 15:30:40.310 11146 11225 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3c0e2e6b, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3e5f38e5, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@35f08dc8mSocket: android.net.LocalSocket@334f7e61 impl:android.net.LocalSocketImpl@31608d86 fd:FileDescriptor[92]
03-24 15:30:40.310 11146 11225 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@334f7e61 impl:android.net.LocalSocketImpl@31608d86 fd:FileDescriptor[92]
,03-24 15:30:40.310 11146 11225 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-24 15:30:40.310 11146 11682 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-24 15:30:40.310 11146 11682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-24 15:30:40.310 11146 11682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-24 15:30:40.310 11146 11146 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-24 15:30:40.310 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-24 15:30:40.315 11146 11146 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-24 15:30:40.315 11146 11146 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-24 15:30:40.315 11146 11225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-24 15:30:40.315 11146 11225 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 15:30:40.315 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-24 15:30:40.315 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-24 15:30:40.315 11146 11225 D BluetoothLeScanner: could not find callback wrapper,
03-24 15:30:40.315 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-24 15:30:40.315 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-24 15:30:40.320  5836  5917 D BtGatt.AdvertiseManager: message : 1,
,03-24 15:30:40.320  5836  5917 D BtGatt.AdvertiseManager: stop advertise for client 7
03-24 15:30:40.320  5836  5917 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
,03-24 15:30:40.320  5836  5917 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-24 15:30:40.320  5836  5906 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-24 15:30:40.320  5836  5906 D BtGatt.GattService: Client app is not null!
,03-24 15:30:40.325  5836  9528 D BtGatt.GattService: unregisterClient() - clientIf=7,
,03-24 15:30:40.330 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 15:30:40.330 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,03-24 15:30:40.330 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false,
03-24 15:30:40.330 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-24 15:30:40.330 11146 11225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,03-24 15:30:40.330 11146 11225 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false,
03-24 15:30:40.330 11146 11225 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 15:30:40.330 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...,
,03-24 15:30:40.330 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-24 15:30:40.330 11146 11225 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-24 15:30:40.330 11146 11225 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 15:30:40.335 11146 11146 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-24 15:30:40.335 11146 11146 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 15:30:40.335 11146 11146 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 15:30:40.335 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 15:30:40.335 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-24 15:30:40.340 11146 11146 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-24 15:30:40.345 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-24 15:30:40.345 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 15:30:40.345 11146 11146 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 15:30:40.345 11146 11225 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-24 15:30:40.345 11146 11225 I jxcore-log: 
03-24 15:30:40.345 11146 11225 I jxcore-log: ok 160 Should be able to call stopAdvertisingAndListening in teardown
,03-24 15:30:40.345 11146 11225 I jxcore-log: 
,03-24 15:30:40.355 11146 11146 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false,
03-24 15:30:40.355 11146 11146 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 15:30:40.365 11146 11225 I jxcore-log: # setup
03-24 15:30:40.365 11146 11225 I jxcore-log: 
,03-24 15:30:40.365 11146 11225 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 15:30:40.365 11146 11225 I jxcore-log: 
,03-24 15:30:40.370 11146 11225 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 15:30:40.370 11146 11225 I jxcore-log: 
,03-24 15:30:40.690 11146 11225 I jxcore-log: # 38. Can connect to a remote peer
03-24 15:30:40.690 11146 11225 I jxcore-log: 
,03-24 15:30:40.795 11146 11225 I io.jxcore.node.ConnectionHelper: start: Port number: 48179, start advertisements: true
,03-24 15:30:40.795 11146 11225 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 15:30:40.800 11146 11225 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,03-24 15:30:40.800 11146 11225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 15:30:40.805 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-24 15:30:40.805 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 15:30:40.805 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 15:30:40.805 11146 11225 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 15:30:40.810  5836  9528 D BtGatt.GattService: registerClient() - UUID=b4900b26-61a6-47dd-8705-6bb16ee5b143
,03-24 15:30:40.850  5836  5906 D BtGatt.GattService: onClientRegistered() - UUID=b4900b26-61a6-47dd-8705-6bb16ee5b143, clientIf=6
03-24 15:30:40.855 11146 11160 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-24 15:30:40.860  5836  5935 D BtGatt.GattService: start scan with filters
,03-24 15:30:40.885  5836  5935 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 62
,03-24 15:30:40.885  5836  5926 D BtGatt.ScanManager: handling starting scan
03-24 15:30:40.885  5836  5926 D BtGatt.ScanManager: isFilteringSupported
03-24 15:30:40.885  5836  5926 D BluetoothAdapter: setting StandAloneBleMode
,03-24 15:30:40.890  5836  5906 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-24 15:30:40.890  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-24 15:30:40.895  5836  5926 D BtGatt.ScanManager: allow scan with filters
03-24 15:30:40.895  5836  5926 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-24 15:30:40.895  5836  5926 D BtGatt.ScanManager: set filter index= 11 for clientIf= 6
03-24 15:30:40.895  5836  5906 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-24 15:30:40.895  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-24 15:30:40.900  5836  5926 D BtGatt.ScanManager: Starting BLE batch scan
,03-24 15:30:40.900  5836  5926 D BtGatt.ScanManager: configuring batch scan storage, appIf 6,
,03-24 15:30:40.900  5836  5906 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,03-24 15:30:40.900  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-24 15:30:40.905  5836  5906 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,03-24 15:30:40.905  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,03-24 15:30:40.910 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 15:30:40.910 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-24 15:30:40.910 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 15:30:40.910 11146 11225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING],
,03-24 15:30:40.910 11146 11225 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false,
03-24 15:30:40.910 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...,
03-24 15:30:40.910 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
,03-24 15:30:40.910 11146 11225 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-24 15:30:40.910 11146 11225 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 15:30:40.910 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false],
03-24 15:30:40.910 11146 11225 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-24 15:30:40.910 11146 11146 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-24 15:30:40.915  5836  5849 D BtGatt.GattService: registerClient() - UUID=2af9281c-d90f-48b8-a9dc-a1d3eed46ff9
,03-24 15:30:40.955  5836  5906 D BtGatt.GattService: onClientRegistered() - UUID=2af9281c-d90f-48b8-a9dc-a1d3eed46ff9, clientIf=7,
03-24 15:30:40.955 11146 11158 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-24 15:30:40.970  5836  5846 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 49,
,03-24 15:30:40.970  5836  5917 D BtGatt.AdvertiseManager: message : 0,
03-24 15:30:40.970  5836  5917 D BtGatt.AdvertiseManager: number of adv instance running0
03-24 15:30:40.970  5836  5917 D BtGatt.AdvertiseManager: size of list is =0
03-24 15:30:40.970  5836  5917 D BtGatt.AdvertiseManager: starting advertising
03-24 15:30:40.970  5836  5917 D BtGatt.AdvertiseManager: isStandardAdvfalse
03-24 15:30:40.975  5836  5906 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
03-24 15:30:40.975  5836  5917 D BtGatt.AdvertiseManager: starting multi advertising
03-24 15:30:40.975  5836  5906 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
03-24 15:30:40.980  5836  5917 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-24 15:30:40.980  5836  5917 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,03-24 15:30:40.980 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 15:30:40.980 11146 11225 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 15:30:40.985 11146 11225 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 15:30:40.985 11146 11225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-24 15:30:40.985 11146 11225 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,03-24 15:30:40.985 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 15:30:40.985 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-24 15:30:40.985 11146 11225 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-24 15:30:40.985 11146 11225 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-24 15:30:40.985 11146 11225 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-24 15:30:40.985 11146 11146 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-24 15:30:40.985 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 15:30:40.985 11146 11146 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 15:30:40.985 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 15:30:40.985 11146 11146 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-24 15:30:40.985 11146 11146 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-24 15:30:40.985 11146 11146 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 15:30:40.985 11146 11146 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 15:30:40.985 11146 11146 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,03-24 15:30:40.985 11146 11146 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 15:30:40.985 11146 11146 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-24 15:30:40.985 11146 11146 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 15:30:40.985 11146 11225 I io.jxcore.node.ConnectionHelper: start: OK
03-24 15:30:40.990 11146 11703 D BluetoothSocket: bindListen(): myUserId = 0
03-24 15:30:40.990 11146 11703 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-24 15:30:40.995 11146 11703 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[93]}
03-24 15:30:40.995 11146 11703 D BluetoothSocket: bindListen(), new LocalSocket 
03-24 15:30:40.995 11146 11703 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,03-24 15:30:40.995 11146 11703 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2927fc12
03-24 15:30:40.995 11146 11703 D BluetoothSocket: channel: 6
03-24 15:30:40.995 11146 11703 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-24 15:30:41.005 11146 11225 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 15:30:41.005 11146 11225 I jxcore-log: 
,03-24 15:30:41.005 11146 11225 I jxcore-log: ok 161 Can call startUpdateAdvertisingAndListening without error
03-24 15:30:41.005 11146 11225 I jxcore-log: 
,03-24 15:30:41.010 11146 11225 I io.jxcore.node.ConnectionHelper: start: Port number: 48179, start advertisements: false
,03-24 15:30:41.010 11146 11225 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 15:30:41.010 11146 11225 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
03-24 15:30:41.010 11146 11225 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 15:30:41.010 11146 11225 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 15:30:41.010 11146 11225 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 15:30:41.010 11146 11225 I jxcore-log: 
,03-24 15:30:41.015 11146 11225 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 15:30:41.015 11146 11225 I jxcore-log: 
,03-24 15:30:41.015 11146 11225 I jxcore-log: ok 162 Can call startListeningForAdvertisements without error
03-24 15:30:41.015 11146 11225 I jxcore-log: 
,03-24 15:30:41.800  3390  4259 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:30:41.805  3390  4259 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:30:41.805  3390  4259 D BatteryService: online:4, current avg:45, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:50
,03-24 15:30:41.805  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-24 15:30:41.810  3390  4259 D BatteryService: stay LED for fully charged
,03-24 15:30:41.815  3390  3390 I MotionRecognitionService: Plugged,
03-24 15:30:41.815  3390  3390 D MotionRecognitionService:   cableConnection= 1
,03-24 15:30:41.815  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
,03-24 15:30:41.815  3390  3390 D MotionRecognitionService: skip setTransmitPower. ,
,03-24 15:30:41.830  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:30:41.830  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:30:41.830  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:30:41.840  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-24 15:30:41.840  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:30:41.855  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:30:41.855  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:30:41.855  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:30:41.855  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:30:41.865  3390  6051 D SSRM:n  : SIOP:: AP = 280, PST = 285 (W:14), CUR = 45, LCD = 0
,03-24 15:30:41.915  3390  3620 V AlarmManager: waitForAlarm result :4
,03-24 15:30:41.935  5836  5836 D BtGatt.ScanManager: awakened up at time 276258
,03-24 15:30:41.940  5836  5926 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-24 15:30:41.945  5836  5906 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=3
03-24 15:30:41.945  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-24 15:30:41.945  5836  5906 D BtGatt.GattService: current time is 276266618865
03-24 15:30:41.945  5836  5906 D BtGatt.GattService: Batch record : [-121, -19, 4, -125, -7, 78, 1, -128, -70, 4, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -4, -24, -59, 113, 10, 80, 1, -128, -56, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0, -28, -44, -106, -22, -38, 116, 0, -128, -98, 4, 0, 23, 2, 1, 6, 3, 2, 5, 24, 15, 9, 90, 101, 70, 105, 116, 50, 32, 35, 54, 54, 48, 55, 53, 0, 16, 15, 9, 90, 101, 70, 105, 116, 50, 32, 35, 54, 54, 48, 55, 53, 0]
03-24 15:30:41.945  5836  5906 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 15:30:41.945  5836  5906 D ScanRecord: parseFromBytes
03-24 15:30:41.945  5836  5906 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-24 15:30:41.945  5836  5906 D ScanRecord: parseFromBytes
03-24 15:30:41.945  5836  5906 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 5, 24, 15, 9, 90, 101, 70, 105, 116, 50, 32, 35, 54, 54, 48, 55, 53, 0, 15, 9, 90, 101, 70, 105, 116, 50, 32, 35, 54, 54, 48, 55, 53, 0]
03-24 15:30:41.945  5836  5906 D ScanRecord: parseFromBytes
03-24 15:30:41.945  5836  5906 D BtGatt.GattService: result: ScanResult{mDevice=74:DA:EA:96:D4:E4, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[00001805-0000-1000-8000-00805f9b34fb], mManufacturerSpecificData={}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=ZeFit2 #66075��], mRssi=-98, mTimestampNanos=276066814615}
03-24 15:30:41.945  5836  5906 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-24 15:30:41.945  5836  5906 D BtGatt.GattService: result: ScanResult{mDevice=4E:F9:83:04:ED:87, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-70, mTimestampNanos=276066814615}
03-24 15:30:41.945  5836  5906 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-24 15:30:41.945  5836  5906 D BtGatt.GattService: result: ScanResult{mDevice=50:0A:71:C5:E8:FC, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-56, mTimestampNanos=276216814615}
03-24 15:30:41.945  5836  5906 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-24 15:30:41.945 11146 11160 D ScanRecord: parseFromBytes
03-24 15:30:41.945 11146 11160 D ScanRecord: parseFromBytes
03-24 15:30:41.945 11146 11160 D ScanRecord: parseFromBytes
03-24 15:30:41.945 11146 11146 V org.thaliproject.p2p.btc,onnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 1
03-24 15:30:41.945 11146 11146 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:CF:C5:D9:E5:61], added - the peer count is 2
03-24 15:30:41.945 11146 11146 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
03-24 15:30:41.950 11146 11146 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:CF:C5:D9:E5:61], Bluetooth address: F8:CF:C5:D9:E5:61, device name: , device address: 
,03-24 15:30:41.950 11146 11225 I jxcore-log: INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"pleaseConnect":false}],
03-24 15:30:41.950 11146 11225 I jxcore-log: 
,03-24 15:30:41.965 11146 11225 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID F8:95:C7:87:3C:51
,03-24 15:30:41.970 11146 11225 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> F8:95:C7:87:3C:51]
,03-24 15:30:41.970 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address F8:95:C7:87:3C:51
,03-24 15:30:41.975 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,03-24 15:30:41.975 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,03-24 15:30:41.975 11146 11225 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null F8:95:C7:87:3C:51
,03-24 15:30:41.975 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address F8:95:C7:87:3C:51
03-24 15:30:41.975 11146 11225 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: F8:95:C7:87:3C:51)
,03-24 15:30:41.980 11146 11225 I jxcore-log: INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"F8:CF:C5:D9:E5:61","peerAvailable":true,"pleaseConnect":false}]
03-24 15:30:41.980 11146 11225 I jxcore-log: 
,03-24 15:30:41.980 11146 11715 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address F8:95:C7:87:3C:51 (thread ID: 1546)
,03-24 15:30:41.990 11146 11715 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
,03-24 15:30:41.990 11146 11715 D BluetoothSocket: connect(): myUserId = 0
,03-24 15:30:41.990 11146 11715 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-24 15:30:41.995  5836  5935 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
03-24 15:30:41.995  5836  5999 D IOP_DB_BT: db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-24 15:30:41.995  5836  5999 D IOP_DB_BT: db_query_add_key: key KEY_LMP_MFCT, value 15
03-24 15:30:41.995  5836  5999 D IOP_DB_BT: db_query_add_key: key KEY_LMP_VER, value 7:8975
03-24 15:30:41.995  5836  5999 D IOP_DB_BT: db_query_add_key: key KEY_DIR_ALL, value 1
03-24 15:30:41.995  5836  5999 D IOP_DB_BT: db_query_execute: result 1
03-24 15:30:41.995  5836  5999 W bt-btif : bta_dm_acl_change(), event : 2
,03-24 15:30:42.000 11146 11715 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[112]}
,03-24 15:30:42.955  3390  3620 V AlarmManager: waitForAlarm result :4
,03-24 15:30:42.965  5836  5836 D BtGatt.ScanManager: awakened up at time 277288
03-24 15:30:42.970  5836  5926 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-24 15:30:42.975  5836  5906 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
03-24 15:30:42.975  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-24 15:30:42.975  5836  5906 D BtGatt.GattService: current time is 277298515948
03-24 15:30:42.975  5836  5906 D BtGatt.GattService: Batch record : [-121, -19, 4, -125, -7, 78, 1, -128, -71, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -4, -24, -59, 113, 10, 80, 1, -128, -55, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0]
03-24 15:30:42.975  5836  5906 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 15:30:42.975  5836  5906 D ScanRecord: parseFromBytes
,03-24 15:30:42.975  5836  5906 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97],
03-24 15:30:42.975  5836  5906 D ScanRecord: parseFromBytes
,03-24 15:30:42.980  5836  5906 D BtGatt.GattService: result: ScanResult{mDevice=50:0A:71:C5:E8:FC, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-55, mTimestampNanos=277298810282}
03-24 15:30:42.980  5836  5906 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 15:30:42.980  5836  5906 D BtGatt.GattService: result: ScanResult{mDevice=4E:F9:83:04:ED:87, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-71, mTimestampNanos=277298810282}
03-24 15:30:42.980  5836  5906 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null],
,03-24 15:30:42.980 11146 11158 D ScanRecord: parseFromBytes
,03-24 15:30:42.980 11146 11158 D ScanRecord: parseFromBytes
,03-24 15:30:42.980 11146 11146 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:CF:C5:D9:E5:61] updated - the peer count is 2
03-24 15:30:42.980 11146 11146 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2,
,03-24 15:30:43.995  3390  3620 V AlarmManager: waitForAlarm result :4
,03-24 15:30:44.005  5836  5836 D BtGatt.ScanManager: awakened up at time 278329
03-24 15:30:44.010  5836  5999 D IOP_DB_BT: db_query: id SkipSdpInfo :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-24 15:30:44.015  5836  5999 D IOP_DB_BT: db_query: result 1
03-24 15:30:44.015  5836  5999 W bt-btif : bta_dm_acl_change(), event : 2
,03-24 15:30:44.030  5836  5999 D IOP_DB_BT: db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-24 15:30:44.030  5836  5999 D IOP_DB_BT: db_query_add_key: key KEY_LMP_MFCT, value 15
03-24 15:30:44.030  5836  5999 D IOP_DB_BT: db_query_add_key: key KEY_LMP_VER, value 7:24841
03-24 15:30:44.030  5836  5999 D IOP_DB_BT: db_query_add_key: key KEY_DIR_ALL, value *
03-24 15:30:44.030  5836  5999 D IOP_DB_BT: db_query_execute: result 1
03-24 15:30:44.030  5836  5999 W bt-btif : bta_dm_acl_change(), event : 0
03-24 15:30:44.030  5836  5999 W bt-btif : info:x10
03-24 15:30:44.030  5836  5906 D         : remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
03-24 15:30:44.030  5836  5906 E BluetoothRemoteDevices: aclStateChangeCallback: Device is NULL
03-24 15:30:44.035  5836  5999 W bt-btif : bta_dm_acl_change(), event : 2
03-24 15:30:44.035  5836  5926 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-24 15:30:44.045  5836  5906 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
03-24 15:30:44.050  5836  5906 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
03-24 15:30:44.050  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-24 15:30:44.050  5836  5906 D BtGatt.GattService: current time is 278372537907
03-24 15:30:44.050  5836  5906 D BtGatt.GattService: Batch record : [-4, -24, -59, 113, 10, 80, 1, -128, -55, 9, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0, -121, -19, 4, -125, -7, 78, 1, -128, -72, 11, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-24 15:30:44.050  5836  5906 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-24 15:30:44.050  5836  5906 D ScanRecord: parseFromBytes
03-24 15:30:44.050  5836  5906 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 15:30:44.050  5836  5906 D ScanRecord: parseFromBytes
03-24 15:30:44.050  5836  5906 D BtGatt.GattService: result: ScanResult{mDevice=50:0A:71:C5:E8:FC, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-55, mTimestampNanos=277922687282}
03-24 15:30:44.050  5836  5906 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-24 15:30:44.050  5836  5906 D BtGatt.GattService: result: ScanResult{mDevice=4E:F9:83:04:ED:87, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-72, mTimestampNanos=277822687282}
03-24 15:30:44.050  5836  5906 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-24 15:30:44.050 11146 11160 D ScanRecord: parseFromBytes
03-24 15:30:44.050 11146 11160 D ScanRecord: parseFromBytes
03-24 15:30:44.050 11146 11146 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:CF:C5:D9:E5:61] updated - the peer count is 2
03-24 15:30:44.055 11146 11146 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
,03-24 15:30:44.060  5836  5999 W bt-sdp  : process_service_search_attr_rsp,
,03-24 15:30:44.225  5836  5906 W bt-btif : btif_dm_ssp_cfm_req_evt
,03-24 15:30:44.235  5836  5906 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,03-24 15:30:44.250  5836  5906 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
03-24 15:30:44.255  5836  5906 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
03-24 15:30:44.255  3390  3429 D SecContentProvider: query(), uri = 4 selection = bluetoothLogForRemote
03-24 15:30:44.260  5836  5906 E bt-btif : check_cod: remote_cod = 0x5a020c
03-24 15:30:44.260  5836  5906 W bt-btif : btif_dm_ssp_reply: accept=1
03-24 15:30:44.270  3390  3390 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
03-24 15:30:44.270  3390  3390 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.device.action.BOND_STATE_CHANGED
,03-24 15:30:44.275  5836  5908 I BluetoothBondStateMachine: Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
,03-24 15:30:44.285  3390  3572 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2cab2246 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{234f3170 10147:com.android.settings/1000}
,03-24 15:30:44.290  5836  5908 D BtConfig.SecureMode: isSecureModeOn:false
03-24 15:30:44.290  5836  5908 I BluetoothBondStateMachine: Entering PendingCommandState State
,03-24 15:30:44.290  3390  3390 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED
03-24 15:30:44.290  3390  3390 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 10
03-24 15:30:44.290  3390  3390 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 11
03-24 15:30:44.290  3390  3390 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
,03-24 15:30:44.295  3727  3727 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,03-24 15:30:44.300  3390  3965 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
,03-24 15:30:44.305 10147 10147 D BluetoothNotiBroadcastReceiver: onReceive
,03-24 15:30:44.310 10341 11730 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
03-24 15:30:44.310  3727  4695 D BluetoothTile:  handleUpdatestate:false name:null
03-24 15:30:44.310 10341 10341 D [CarModeFW]: ConnectivityManager-handleMessage PAIRING_DEVICES
,03-24 15:30:44.315  3390  3853 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2cab2246 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{1c707cd7 10341:com.sec.android.automotive.drivelink/u0a102}
,03-24 15:30:44.315 10341 10341 D [CarMode]: [AutoLaunchReceiver]-action: android.bluetooth.device.action.BOND_STATE_CHANGED
,03-24 15:30:44.315 10341 10341 D [CarMode]: [AutoLaunchReceiver]-ACTION_BOND_STATE_CHANGED G4-1 state is 11
,03-24 15:30:44.320  3390  3425 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2cab2246 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{1c707cd7 10341:com.sec.android.automotive.drivelink/u0a102}
,03-24 15:30:44.325  3390  4259 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
,03-24 15:30:44.330 10341 11732 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,03-24 15:30:44.330 10341 10341 D [CarModeFW]: ConnectivityManager-handleMessage PAIRING_DEVICES
,03-24 15:30:44.330  3390  4268 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2cab2246 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{1961ff11 10498:com.samsung.android.app.watchmanagerstub/u0a121}
,03-24 15:30:44.345 10498 10498 E BluetoothHeadset: BTStateChangeCB is registed
,03-24 15:30:44.345 10498 10498 D GMHFPReceiver: android.bluetooth.device.action.BOND_STATE_CHANGED
03-24 15:30:44.345 10498 10498 D GMHFPReceiver: jangil::setProperties()
,03-24 15:30:44.350 10498 10498 D GMHFPReceiver: jangil::printBTStatus()
,03-24 15:30:44.350  3390  3429 D SettingsProvider: name = Wearable0001
03-24 15:30:44.350  3390  3429 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-24 15:30:44.350  3390  3429 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-24 15:30:44.350  3390  3429 D SettingsProvider: selectionArgs: false
03-24 15:30:44.350  3390  3429 D SettingsProvider: selectionArgs: 10121
03-24 15:30:44.350  3390  3429 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,03-24 15:30:44.350  3390  3429 D SettingsProvider: ret = -1
,03-24 15:30:44.355  3390  3429 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10121
,03-24 15:30:44.360 10498 10498 D GMHFPReceiver: ::::::::Wearable0001::false
,03-24 15:30:44.360  3390  3425 D SettingsProvider: name = Wearable0002
03-24 15:30:44.360  3390  3425 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-24 15:30:44.360  3390  3425 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-24 15:30:44.360  3390  3425 D SettingsProvider: selectionArgs: false
03-24 15:30:44.360  3390  3425 D SettingsProvider: selectionArgs: 10121
03-24 15:30:44.360  3390  3425 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,03-24 15:30:44.360  3390  3425 D SettingsProvider: ret = -1
,03-24 15:30:44.365  3390  3425 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10121
,03-24 15:30:44.365 10498 10498 D GMHFPReceiver: ::::::::Wearable0002::false
,03-24 15:30:44.370  3727  3727 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-24 15:30:44.370  3390  4257 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2cab2246 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{3363faf0 4351:com.google.android.gms.persistent/u0a14}
,03-24 15:30:44.385  3727  3727 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-24 15:30:44.445 10498 10498 D GMHFPReceiver: onServiceConnected() : 1
03-24 15:30:44.445 10498 10498 D GMHFPReceiver: mBluetoothHeadset = true
,03-24 15:30:44.555  5836  5906 W bt-btif : btif_dm_auth_cmpl_evt
,03-24 15:30:44.570  5836  5906 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,03-24 15:30:44.600  5836  5906 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,03-24 15:30:44.605  5836  5908 D BluetoothAdapterProperties: Failed to remove device: F8:95:C7:87:3C:51
,03-24 15:30:44.610  3390  3652 D SecContentProvider: query(), uri = 4 selection = bluetoothLogForRemote
,03-24 15:30:44.615  3727  3727 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,03-24 15:30:44.620  3390  3390 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
03-24 15:30:44.620  3390  3390 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.device.action.BOND_STATE_CHANGED
03-24 15:30:44.620  3390  3390 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED
03-24 15:30:44.620  3390  3390 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 11
03-24 15:30:44.620  3390  3390 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 10
03-24 15:30:44.620  3390  3390 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
,03-24 15:30:44.620  5836  5908 I BluetoothBondStateMachine: Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,03-24 15:30:44.635  3390  3572 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{149fc059 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{234f3170 10147:com.android.settings/1000}
,03-24 15:30:44.635 10147 10147 D BluetoothNotiBroadcastReceiver: onReceive
03-24 15:30:44.635  3390  3853 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
03-24 15:30:44.640  5836  5908 D BtConfig.SecureMode: isSecureModeOn:false
,03-24 15:30:44.645  3727  4695 D BluetoothTile:  handleUpdatestate:false name:null
,03-24 15:30:44.650  5836  5908 D HidService: getHidService(): returning com.android.bluetooth.hid.HidService@31faf1af
,03-24 15:30:44.650 10341 11741 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,03-24 15:30:44.650  3390  4028 D SettingsProvider: name = bluetooth_input_device_priority_F8:95:C7:87:3C:51
03-24 15:30:44.650  3390  4028 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-24 15:30:44.650  3390  4028 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-24 15:30:44.650  3390  4028 D SettingsProvider: selectionArgs: false
03-24 15:30:44.650  3390  4028 D SettingsProvider: selectionArgs: 1002
03-24 15:30:44.650  3390  4028 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,03-24 15:30:44.650  3390  4028 D SettingsProvider: ret = -1
03-24 15:30:44.655  5836  5908 D HidService: Saved priority F8:95:C7:87:3C:51 = -1
03-24 15:30:44.655  3390  4710 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{149fc059 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{1c707cd7 10341:com.sec.android.automotive.drivelink/u0a102}
03-24 15:30:44.655  3390  3425 D SettingsProvider: name = bluetooth_a2dp_sink_priority_F8:95:C7:87:3C:51
03-24 15:30:44.655 10341 10341 D [CarMode]: [AutoLaunchReceiver]-action: android.bluetooth.device.action.BOND_STATE_CHANGED
03-24 15:30:44.655  3390  3425 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3,
03-24 15:30:44.655  3390  3425 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-24 15:30:44.655  3390  3425 D SettingsProvider: selectionArgs: false
03-24 15:30:44.655  3390  3425 D SettingsProvider: selectionArgs: 1002
03-24 15:30:44.655  3390  3425 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
03-24 15:30:44.655  3390  3425 D SettingsProvider: ret = -1
,03-24 15:30:44.655 10341 10341 D [CarMode]: [AutoLaunchReceiver]-ACTION_BOND_STATE_CHANGED G4-1 state is 10
03-24 15:30:44.655  3390  4257 D SettingsProvider: name = bluetooth_headset_priority_F8:95:C7:87:3C:51
,03-24 15:30:44.655  3390  4257 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-24 15:30:44.655  3390  4257 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-24 15:30:44.655  3390  4257 D SettingsProvider: selectionArgs: false
03-24 15:30:44.655  3390  4257 D SettingsProvider: selectionArgs: 1002
,03-24 15:30:44.655  3390  4257 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
03-24 15:30:44.660  3390  4257 D SettingsProvider: ret = -1
03-24 15:30:44.660  5836  5908 I BluetoothBondStateMachine: StableState(): Entering Off State
,03-24 15:30:44.660  3390  4268 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{149fc059 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{1c707cd7 10341:com.sec.android.automotive.drivelink/u0a102},
,03-24 15:30:44.665  3390  3652 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
,03-24 15:30:44.670 10341 11743 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,03-24 15:30:44.675  3390  3853 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{149fc059 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{1961ff11 10498:com.samsung.android.app.watchmanagerstub/u0a121}
,03-24 15:30:44.675 10498 10498 E BluetoothHeadset: BTStateChangeCB is registed
,03-24 15:30:44.675 10498 10498 D GMHFPReceiver: android.bluetooth.device.action.BOND_STATE_CHANGED
03-24 15:30:44.675 10498 10498 D GMHFPReceiver: jangil::setProperties()
,03-24 15:30:44.680 10498 10498 D GMHFPReceiver: jangil::printBTStatus()
,03-24 15:30:44.680  3390  4044 D SettingsProvider: name = Wearable0001
03-24 15:30:44.680  3390  4044 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-24 15:30:44.680  3390  4044 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-24 15:30:44.680  3390  4044 D SettingsProvider: selectionArgs: false
03-24 15:30:44.680  3390  4044 D SettingsProvider: selectionArgs: 10121
03-24 15:30:44.680  3390  4044 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,03-24 15:30:44.680  3390  4044 D SettingsProvider: ret = -1
03-24 15:30:44.680 10498 10498 D GMHFPReceiver: ::::::::Wearable0001::false
03-24 15:30:44.680  3390  4709 D SettingsProvider: name = Wearable0002
,03-24 15:30:44.680  3390  4709 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-24 15:30:44.680  3390  4709 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-24 15:30:44.680  3390  4709 D SettingsProvider: selectionArgs: false
03-24 15:30:44.680  3390  4709 D SettingsProvider: selectionArgs: 10121
03-24 15:30:44.680  3390  4709 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
03-24 15:30:44.680  3390  4709 D SettingsProvider: ret = -1
03-24 15:30:44.680 10498 10498 D GMHFPReceiver: ::::::::Wearable0002::false
,03-24 15:30:44.685  3390  4710 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{149fc059 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{3363faf0 4351:com.google.android.gms.persistent/u0a14}
,03-24 15:30:44.775 10498 10498 D GMHFPReceiver: onServiceConnected() : 1
03-24 15:30:44.775 10498 10498 D GMHFPReceiver: mBluetoothHeadset = true
,03-24 15:30:45.060  3390  3620 V AlarmManager: waitForAlarm result :4
,03-24 15:30:45.075  5836  5836 D BtGatt.ScanManager: awakened up at time 279396
,03-24 15:30:45.080  5836  5926 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-24 15:30:45.085  5836  5906 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-24 15:30:45.085  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-24 15:30:45.185  5836  5999 D IOP_DB_BT: db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-24 15:30:45.185  5836  5999 D IOP_DB_BT: db_query_add_key: key KEY_LMP_MFCT, value 15
03-24 15:30:45.185  5836  5999 D IOP_DB_BT: db_query_add_key: key KEY_LMP_VER, value 7:24841
03-24 15:30:45.185  5836  5999 D IOP_DB_BT: db_query_add_key: key KEY_DIR_ALL, value *
03-24 15:30:45.185  5836  5999 D IOP_DB_BT: db_query_execute: result 1
03-24 15:30:45.190  5836  5999 D IOP_DB_BT: db_query_create: id EnforceSlaveRole :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-24 15:30:45.190  5836  5999 D IOP_DB_BT: db_query_add_key: key KEY_LMP_MFCT, value 15
03-24 15:30:45.190  5836  5999 D IOP_DB_BT: db_query_add_key: key KEY_LMP_VER, value 7:24841
03-24 15:30:45.190  5836  5999 D IOP_DB_BT: db_query_add_key: key KEY_DIR_ALL, value *
03-24 15:30:45.190  5836  5999 D IOP_DB_BT: db_query_execute: result 1
,03-24 15:30:45.395  5836  5999 D IOP_DB_BT: db_query: id SkipSdpInfo :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-24 15:30:45.395  5836  5999 D IOP_DB_BT: db_query: result 1
03-24 15:30:45.415  5836  5999 D IOP_DB_BT: db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-24 15:30:45.415  5836  5999 D IOP_DB_BT: db_query_add_key: key KEY_LMP_MFCT, value 15
03-24 15:30:45.415  5836  5999 D IOP_DB_BT: db_query_add_key: key KEY_LMP_VER, value 7:8975
03-24 15:30:45.415  5836  5999 D IOP_DB_BT: db_query_add_key: key KEY_DIR_ALL, value *
03-24 15:30:45.420  5836  5999 D IOP_DB_BT: db_query_execute: result 1
,03-24 15:30:45.420  5836  5999 W bt-btif : bta_dm_acl_change(), event : 0
03-24 15:30:45.420  5836  5999 W bt-btif : info:x10
,03-24 15:30:45.420  5836  5906 D         : remote version info [f8:cf:c5:d9:e5:61]: 7, f, 230f
03-24 15:30:45.420  5836  5906 E BluetoothRemoteDevices: aclStateChangeCallback: Device is NULL
03-24 15:30:45.420  5836  5999 W bt-btif : bta_dm_acl_change(), event : 2,
,03-24 15:30:45.425  5836  5906 D BluetoothUtils: getBtEnabledContainers(): btContainers = [],
,03-24 15:30:45.585  5836  5906 W bt-btif : btif_dm_ssp_cfm_req_evt
03-24 15:30:45.590  5836  5906 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
03-24 15:30:45.595  5836  5906 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
03-24 15:30:45.595  5836  5906 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:CF:C5:D9:E5:61 newState: 1
03-24 15:30:45.600  3390  4710 D SecContentProvider: query(), uri = 4 selection = bluetoothLogForRemote
,03-24 15:30:45.605  5836  5906 E bt-btif : check_cod: remote_cod = 0x5a020c
03-24 15:30:45.615  3727  3727 D BluetoothTile:  onBluetoothPairedDevicesChanged:
03-24 15:30:45.605  5836  5906 W bt-btif : btif_dm_ssp_reply: accept=1
03-24 15:30:45.610  5836  5908 I BluetoothBondStateMachine: Bond State Change Intent:F8:CF:C5:D9:E5:61 OldState: 10 NewState: 11
03-24 15:30:45.610  5836  5908 D BtConfig.SecureMode: isSecureModeOn:false
03-24 15:30:45.610  5836  5908 I BluetoothBondStateMachine: Entering PendingCommandState State
,03-24 15:30:45.620  3390  3390 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive,
03-24 15:30:45.620  3390  3390 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.device.action.BOND_STATE_CHANGED
03-24 15:30:45.620  3390  3390 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED
,03-24 15:30:45.620  3390  3390 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 10,
03-24 15:30:45.620  3390  3390 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 11
03-24 15:30:45.620  3390  3390 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit,
,03-24 15:30:45.635  5836  5906 W bt-btif : btif_dm_auth_cmpl_evt,
,03-24 15:30:45.635  5836  5906 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,03-24 15:30:45.645  5836  5906 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:CF:C5:D9:E5:61 newState: 0,
03-24 15:30:45.645  5836  5908 D BluetoothAdapterProperties: Failed to remove device: F8:CF:C5:D9:E5:61
,03-24 15:30:45.650  3390  3572 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{35b721b u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{234f3170 10147:com.android.settings/1000}
,03-24 15:30:45.655  3390  4044 D SecContentProvider: query(), uri = 4 selection = bluetoothLogForRemote
,03-24 15:30:45.655  3390  3943 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
,03-24 15:30:45.665 10147 10147 D BluetoothNotiBroadcastReceiver: onReceive
,03-24 15:30:45.670  3390  3390 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
03-24 15:30:45.670  3390  3390 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.device.action.BOND_STATE_CHANGED
03-24 15:30:45.670  3390  3390 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED
03-24 15:30:45.670  3390  3390 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 11
03-24 15:30:45.670  3390  3390 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 10
03-24 15:30:45.670  3390  3390 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
,03-24 15:30:45.680  5836  5908 I BluetoothBondStateMachine: Bond State Change Intent:F8:CF:C5:D9:E5:61 OldState: 11 NewState: 10
,03-24 15:30:45.685  5836  5908 D BtConfig.SecureMode: isSecureModeOn:false
03-24 15:30:45.685  5836  5908 D HidService: getHidService(): returning com.android.bluetooth.hid.HidService@31faf1af
,03-24 15:30:45.685  3390  4259 D SettingsProvider: name = bluetooth_input_device_priority_F8:CF:C5:D9:E5:61
03-24 15:30:45.685  3390  4259 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-24 15:30:45.685  3390  4259 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-24 15:30:45.685  3390  4259 D SettingsProvider: selectionArgs: false
03-24 15:30:45.685  3390  4259 D SettingsProvider: selectionArgs: 1002
03-24 15:30:45.685  3390  4259 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,03-24 15:30:45.690  3390  4259 D SettingsProvider: ret = -1
03-24 15:30:45.690  5836  5908 D HidService: Saved priority F8:CF:C5:D9:E5:61 = -1
,03-24 15:30:45.690  3390  3832 D SettingsProvider: name = bluetooth_a2dp_sink_priority_F8:CF:C5:D9:E5:61
03-24 15:30:45.690  3390  3832 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-24 15:30:45.690  3390  3832 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-24 15:30:45.690  3390  3832 D SettingsProvider: selectionArgs: false
03-24 15:30:45.690  3390  3832 D SettingsProvider: selectionArgs: 1002
03-24 15:30:45.690  3390  3832 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
03-24 15:30:45.690  3390  3832 D SettingsProvider: ret = -1
,03-24 15:30:45.695  3390  3425 D SettingsProvider: name = bluetooth_headset_priority_F8:CF:C5:D9:E5:61
03-24 15:30:45.695  3390  3425 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-24 15:30:45.695  3390  3425 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-24 15:30:45.695  3390  3425 D SettingsProvider: selectionArgs: false
03-24 15:30:45.695  3390  3425 D SettingsProvider: selectionArgs: 1002
03-24 15:30:45.695  3390  3425 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,03-24 15:30:45.695  3390  3425 D SettingsProvider: ret = -1
,03-24 15:30:45.695  5836  5908 I BluetoothBondStateMachine: StableState(): Entering Off State
,03-24 15:30:45.705  3390  4707 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{35b721b u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{1c707cd7 10341:com.sec.android.automotive.drivelink/u0a102}
,03-24 15:30:45.705  3727  3727 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,03-24 15:30:45.705  3727  4695 D BluetoothTile:  handleUpdatestate:false name:null
,03-24 15:30:45.705 10341 11770 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,03-24 15:30:45.710  3390  3652 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
,03-24 15:30:45.710  3727  4695 D BluetoothTile:  handleUpdatestate:false name:null
,03-24 15:30:45.710 10341 10341 D [CarMode]: [AutoLaunchReceiver]-action: android.bluetooth.device.action.BOND_STATE_CHANGED
,03-24 15:30:45.710  5836  5999 W bt-btif : new conn_srvc id:26, app_id:255
03-24 15:30:45.710  5836  5999 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
,03-24 15:30:45.710 10341 10341 D [CarMode]: [AutoLaunchReceiver]-ACTION_BOND_STATE_CHANGED Nexus 6 state is 11
03-24 15:30:45.710  5836  5999 W bt-btif : bta_dm_pm_ssr:2, lat:1200
03-24 15:30:45.710 11146 11703 D BluetoothSocket: socket fd passed by stack  fds: [Ljava.io.FileDescriptor;@18e92555
03-24 15:30:45.715  5836  9528 E BluetoothRemoteDevices: setRfcommConnected true
03-24 15:30:45.715 11146 11703 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection accepted
03-24 15:30:45.715 10341 10341 D [CarModeFW]: ConnectivityManager-handleMessage PAIRING_DEVICES
03-24 15:30:45.715 10341 11770 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,03-24 15:30:45.715  3390  3425 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{35b721b u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{1c707cd7 10341:com.sec.android.automotive.drivelink/u0a102}
,03-24 15:30:45.720  3390  4707 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
,03-24 15:30:45.720 11146 11703 D BluetoothSocket: getInputStream(): myUserId = 0
,03-24 15:30:45.720  5836  5999 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-24 15:30:45.720  5836  5999 D IOP_DB_BT: db_query: result 1
03-24 15:30:45.720  5836  5999 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
,03-24 15:30:45.720  5836  5999 D IOP_DB_BT: db_query: result 1
,03-24 15:30:45.725 11146 11703 D BluetoothSocket: getOutputStream(): myUserId = 0
03-24 15:30:45.725 11146 11703 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection initialized (thread ID: 1547)
03-24 15:30:45.725 11146 11703 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1962fb6a, channel: 6, state: LISTENING
,03-24 15:30:45.725 11146 11703 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1962fb6a, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2927fc12, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@15bb885bmSocket: android.net.LocalSocket@35c6f8f8 impl:android.net.LocalSocketImpl@d63c1d1 fd:FileDescriptor[93]
03-24 15:30:45.725 11146 11703 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@35c6f8f8 impl:android.net.LocalSocketImpl@d63c1d1 fd:FileDescriptor[93]
03-24 15:30:45.725 11146 11703 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-24 15:30:45.725 11146 11772 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 1547)
03-24 15:30:45.725 11146 11772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesRead: Read 15 bytes successfully (thread ID: 1547)
,03-24 15:30:45.730 11146 11772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Got valid identity from [<no peer name> F8:CF:C5:D9:E5:61]
03-24 15:30:45.730 11146 11772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesWritten: 15 bytes successfully written (thread ID: 1547)
03-24 15:30:45.730 11146 11772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: removeThreadFromList: Removing thread with ID 1547
03-24 15:30:45.730  3390  3943 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{35b721b u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{1961ff11 10498:com.samsung.android.app.watchmanagerstub/u0a121}
03-24 15:30:45.730 11146 11772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Handshake thread disposed (thread ID: 1547)
03-24 15:30:45.730 11146 11772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onIncomingConnectionConnected: [<no peer name> F8:CF:C5:D9:E5:61]
,03-24 15:30:45.730  5836  5999 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
,03-24 15:30:45.730 11146 11772 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 1547)
03-24 15:30:45.730 11146 11146 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:CF:C5:D9:E5:61]
03-24 15:30:45.730  5836  5999 D IOP_DB_BT: db_query: result 1
03-24 15:30:45.730  5836  5999 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-24 15:30:45.730  5836  5999 D IOP_DB_BT: db_query: result 1
03-24 15:30:45.730 11146 11146 I io.jxcore.node.ConnectionHelper: onConnected: Incoming connection to peer [<no peer name> F8:CF:C5:D9:E5:61]
,03-24 15:30:45.730 11146 11146 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:CF:C5:D9:E5:61] updated - the peer count is 2
03-24 15:30:45.730 10498 10498 E BluetoothHeadset: BTStateChangeCB is registed
03-24 15:30:45.735 10498 10498 D GMHFPReceiver: android.bluetooth.device.action.BOND_STATE_CHANGED
03-24 15:30:45.735 10498 10498 D GMHFPReceiver: jangil::setProperties()
03-24 15:30:45.735 11146 11703 D BluetoothSocket: bindListen(): myUserId = 0
03-24 15:30:45.735 11146 11703 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-24 15:30:45.735 11146 11146 D BluetoothSocket: getInputStream(): myUserId = 0
03-24 15:30:45.735 11146 11703 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[113]}
03-24 15:30:45.735 11146 11703 D BluetoothSocket: bindListen(), new LocalSocket 
,03-24 15:30:45.735 11146 11703 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-24 15:30:45.735 11146 11703 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1ca04f37
03-24 15:30:45.735 11146 11703 D BluetoothSocket: channel: 6
03-24 15:30:45.735 11146 11703 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-24 15:30:45.740 10498 10498 D GMHFPReceiver: jangil::printBTStatus()
,03-24 15:30:45.740  3390  4259 D SettingsProvider: name = Wearable0001
03-24 15:30:45.740  3390  4259 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-24 15:30:45.740  3390  4259 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-24 15:30:45.740  3390  4259 D SettingsProvider: selectionArgs: false
03-24 15:30:45.740  3390  4259 D SettingsProvider: selectionArgs: 10121
03-24 15:30:45.740  3390  4259 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
03-24 15:30:45.740 10341 11771 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
03-24 15:30:45.740  3390  4259 D SettingsProvider: ret = -1
03-24 15:30:45.740 11146 11146 D BluetoothSocket: getOutputStream(): myUserId = 0
03-24 15:30:45.740 11146 11146 I io.jxcore.node.ConnectionHelper: lowerBleDiscoveryPowerAndStartResetTimer: Lowering the power settings
03-24 15:30:45.740 10498 10498 D GMHFPReceiver: ::::::::Wearable0001::false
03-24 15:30:45.740 10341 10341 D [CarModeFW]: ConnectivityManager-handleMessage PAIRING_DEVICES
03-24 15:30:45.740 11146 11146 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 2 -> 0
,03-24 15:30:45.740 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 15:30:45.740 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 15:30:45.740 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-24 15:30:45.740 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-24 15:30:45.740 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-24 15:30:45.740 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 15:30:45.740  3390  4044 D SettingsProvider: name = Wearable0002
03-24 15:30:45.740  3390  4044 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-24 15:30:45.740  3390  4044 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-24 15:30:45.740  3390  4044 D SettingsProvider: selectionArgs: false
03-24 15:30:45.740  3390  4044 D SettingsProvider: selectionArgs: 10121
03-24 15:30:45.740  3390  4044 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,03-24 15:30:45.740  3390  4044 D SettingsProvider: ret = -1,
,03-24 15:30:45.745 10498 10498 D GMHFPReceiver: ::::::::Wearable0002::false
03-24 15:30:45.745  5836  5917 D BtGatt.AdvertiseManager: message : 1
03-24 15:30:45.745  5836  5917 D BtGatt.AdvertiseManager: stop advertise for client 7
03-24 15:30:45.745  5836  5917 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
,03-24 15:30:45.745  5836  5917 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,03-24 15:30:45.750  5836  5906 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
,03-24 15:30:45.750  5836  5906 D BtGatt.GattService: Client app is not null!
03-24 15:30:45.750  5836  9528 D BtGatt.GattService: unregisterClient() - clientIf=7
,03-24 15:30:45.750  3390  3853 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{35b721b u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{3363faf0 4351:com.google.android.gms.persistent/u0a14}
,03-24 15:30:45.755 11146 11146 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-24 15:30:45.755 11146 11146 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 15:30:45.755 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 3, timeout: 0, is connectable: false
03-24 15:30:45.755 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 15:30:45.755 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-24 15:30:45.755 11146 11146 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
,03-24 15:30:45.755 11146 11146 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 15:30:45.755 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 15:30:45.755 11146 11146 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 15:30:45.755  5836  9528 D BtGatt.GattService: registerClient() - UUID=f8f6b206-7f1d-45a9-a96c-8ddcc82174e2,
,03-24 15:30:45.760  3390  3853 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{33b514f7 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{234f3170 10147:com.android.settings/1000}
,03-24 15:30:45.760 10147 10147 D BluetoothNotiBroadcastReceiver: onReceive
,03-24 15:30:45.770  3390  3853 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{33b514f7 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{1c707cd7 10341:com.sec.android.automotive.drivelink/u0a102}
,03-24 15:30:45.770 10341 10341 D [CarMode]: [AutoLaunchReceiver]-action: android.bluetooth.device.action.BOND_STATE_CHANGED
,03-24 15:30:45.770 10341 10341 D [CarMode]: [AutoLaunchReceiver]-ACTION_BOND_STATE_CHANGED Nexus 6 state is 10
,03-24 15:30:45.775  3390  4268 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{33b514f7 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{1c707cd7 10341:com.sec.android.automotive.drivelink/u0a102}
,03-24 15:30:45.775  3390  4709 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
,03-24 15:30:45.780 10341 11774 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,03-24 15:30:45.785  3390  4257 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{33b514f7 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{1961ff11 10498:com.samsung.android.app.watchmanagerstub/u0a121}
,03-24 15:30:45.785 10498 10498 E BluetoothHeadset: BTStateChangeCB is registed
,03-24 15:30:45.785 10498 10498 D GMHFPReceiver: android.bluetooth.device.action.BOND_STATE_CHANGED
03-24 15:30:45.785 10498 10498 D GMHFPReceiver: jangil::setProperties()
,03-24 15:30:45.790 10498 10498 D GMHFPReceiver: jangil::printBTStatus()
,03-24 15:30:45.790  3390  4259 D SettingsProvider: name = Wearable0001
03-24 15:30:45.790  3390  4259 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-24 15:30:45.790  3390  4259 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-24 15:30:45.790  3390  4259 D SettingsProvider: selectionArgs: false
03-24 15:30:45.790  3390  4259 D SettingsProvider: selectionArgs: 10121
03-24 15:30:45.790  3390  4259 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,03-24 15:30:45.790  3390  4259 D SettingsProvider: ret = -1
03-24 15:30:45.790 10498 10498 D GMHFPReceiver: ::::::::Wearable0001::false
,03-24 15:30:45.790  3390  4044 D SettingsProvider: name = Wearable0002
03-24 15:30:45.790  3390  4044 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-24 15:30:45.790  3390  4044 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-24 15:30:45.790  3390  4044 D SettingsProvider: selectionArgs: false
03-24 15:30:45.790  3390  4044 D SettingsProvider: selectionArgs: 10121
03-24 15:30:45.790  3390  4044 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,03-24 15:30:45.795  3390  4044 D SettingsProvider: ret = -1
03-24 15:30:45.795 10498 10498 D GMHFPReceiver: ::::::::Wearable0002::false
,03-24 15:30:45.800  3390  3853 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{33b514f7 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{3363faf0 4351:com.google.android.gms.persistent/u0a14}
03-24 15:30:45.800  5836  5906 D BtGatt.GattService: onClientRegistered() - UUID=f8f6b206-7f1d-45a9-a96c-8ddcc82174e2, clientIf=7
,03-24 15:30:45.800 11146 11158 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-24 15:30:45.815  5836  5935 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 50
,03-24 15:30:45.815  5836  5917 D BtGatt.AdvertiseManager: message : 0
03-24 15:30:45.815  5836  5917 D BtGatt.AdvertiseManager: number of adv instance running0
03-24 15:30:45.815  5836  5917 D BtGatt.AdvertiseManager: size of list is =0
,03-24 15:30:45.815  5836  5917 D BtGatt.AdvertiseManager: starting advertising
03-24 15:30:45.815  5836  5917 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-24 15:30:45.820  5836  5906 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-24 15:30:45.820  5836  5917 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 15:30:45.820  5836  5906 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
03-24 15:30:45.820  5836  5917 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-24 15:30:45.820  5836  5917 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 0, TxPowerLevel: 3, isConnectable: false, Timeout: 0
03-24 15:30:45.820 11146 11146 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 15:30:45.820  5836  5849 D BtGatt.GattService: stopScan() - queue size =1
03-24 15:30:45.825  5836  5926 D BtGatt.ScanManager: filter size is 1
03-24 15:30:45.825  5836  5926 D BtGatt.ScanManager: delete FilterIndex - 11
,03-24 15:30:45.825  5836  9528 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 15:30:45.825 11146 11146 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 15:30:45.825 11146 11146 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 15:30:45.825 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 15:30:45.825 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 15:30:45.825  5836  5906 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-24 15:30:45.825 11146 11146 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 15:30:45.825  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-24 15:30:45.825 11146 11146 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-24 15:30:45.825  5836  5926 D BtGatt.ScanManager: stopping BLe Batch
,03-24 15:30:45.825  5836  5906 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,03-24 15:30:45.825  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-24 15:30:45.825  5836  5926 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-24 15:30:45.830  5836  5906 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-24 15:30:45.830  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-24 15:30:45.830  5836  9528 D BtGatt.GattService: registerClient() - UUID=c94b7f2b-6e5e-468f-ae06-c50e46c49e7b
,03-24 15:30:45.835 10498 10498 D GMHFPReceiver: onServiceConnected() : 1
,03-24 15:30:45.835 10498 10498 D GMHFPReceiver: mBluetoothHeadset = true
,03-24 15:30:45.870  5836  5906 D BtGatt.GattService: onClientRegistered() - UUID=c94b7f2b-6e5e-468f-ae06-c50e46c49e7b, clientIf=6
,03-24 15:30:45.870 11146 11158 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-24 15:30:45.870  5836  5846 D BtGatt.GattService: start scan with filters
,03-24 15:30:45.890 10498 10498 D GMHFPReceiver: onServiceConnected() : 1
,03-24 15:30:45.890 10498 10498 D GMHFPReceiver: mBluetoothHeadset = true
03-24 15:30:45.890  5836  5846 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 63
,03-24 15:30:45.890 11146 11146 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-24 15:30:45.890 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 15:30:45.890  5836  5926 D BtGatt.ScanManager: handling starting scan
03-24 15:30:45.890 11146 11146 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 3 -> 1
03-24 15:30:45.890  5836  5926 D BtGatt.ScanManager: isFilteringSupported
03-24 15:30:45.890  5836  5926 D BluetoothAdapter: setting StandAloneBleMode
03-24 15:30:45.890 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 15:30:45.890 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 15:30:45.890 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-24 15:30:45.890 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-24 15:30:45.890 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-24 15:30:45.890 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-24 15:30:45.895  5836  5906 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1,
03-24 15:30:45.895  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-24 15:30:45.895  5836  5926 D BtGatt.ScanManager: allow scan with filters
03-24 15:30:45.895  5836  5926 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,03-24 15:30:45.895  5836  5926 D BtGatt.ScanManager: set filter index= 12 for clientIf= 6
03-24 15:30:45.895  5836  5917 D BtGatt.AdvertiseManager: message : 1
03-24 15:30:45.895  5836  5906 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,03-24 15:30:45.895  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-24 15:30:45.895  5836  5926 D BtGatt.ScanManager: Starting BLE batch scan
03-24 15:30:45.895  5836  5926 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-24 15:30:45.895  5836  5917 D BtGatt.AdvertiseManager: stop advertise for client 7
,03-24 15:30:45.895  5836  5917 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-24 15:30:45.900  5836  5917 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-24 15:30:45.900  5836  5906 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-24 15:30:45.900  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-24 15:30:45.900  5836  5906 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
,03-24 15:30:45.900  5836  5906 D BtGatt.GattService: Client app is not null!
,03-24 15:30:45.905  5836  9528 D BtGatt.GattService: unregisterClient() - clientIf=7
,03-24 15:30:45.905 11146 11146 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 15:30:45.905 11146 11146 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-24 15:30:45.905 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
,03-24 15:30:45.905 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 15:30:45.905 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-24 15:30:45.905  5836  5906 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,03-24 15:30:45.905  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-24 15:30:45.905 11146 11146 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-24 15:30:45.905 11146 11146 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 15:30:45.905 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 15:30:45.905 11146 11146 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 15:30:45.910  5836  9528 D BtGatt.GattService: registerClient() - UUID=376782d6-b08c-4fac-a4e2-3a9c276fd4e1
,03-24 15:30:45.950  5836  5906 D BtGatt.GattService: onClientRegistered() - UUID=376782d6-b08c-4fac-a4e2-3a9c276fd4e1, clientIf=7
03-24 15:30:45.955 11146 11158 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-24 15:30:45.970  5836  5846 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 51
,03-24 15:30:45.970  5836  5917 D BtGatt.AdvertiseManager: message : 0
,03-24 15:30:45.975  5836  5917 D BtGatt.AdvertiseManager: number of adv instance running0
03-24 15:30:45.975  5836  5917 D BtGatt.AdvertiseManager: size of list is =0
,03-24 15:30:45.975  5836  5917 D BtGatt.AdvertiseManager: starting advertising
03-24 15:30:45.975  5836  5917 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-24 15:30:45.985  5836  5906 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-24 15:30:45.985  5836  5917 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 15:30:45.990  5836  5906 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-24 15:30:45.990  5836  5917 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,03-24 15:30:45.990  5836  5917 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 0, TxPowerLevel: 1, isConnectable: false, Timeout: 0
,03-24 15:30:45.990 11146 11146 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-24 15:30:45.995  5836  5935 D BtGatt.GattService: stopScan() - queue size =1
03-24 15:30:45.995  5836  5926 D BtGatt.ScanManager: filter size is 1
03-24 15:30:45.995  5836  5926 D BtGatt.ScanManager: delete FilterIndex - 12
03-24 15:30:45.995  5836  9528 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 15:30:45.995 11146 11146 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 15:30:45.995 11146 11146 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 15:30:45.995 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 15:30:45.995 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 15:30:45.995 11146 11146 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 15:30:45.995 11146 11146 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-24 15:30:45.995  5836  5906 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-24 15:30:45.995  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-24 15:30:46.000  5836  5926 D BtGatt.ScanManager: stopping BLe Batch
,03-24 15:30:46.000  5836  5906 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0,
03-24 15:30:46.000  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-24 15:30:46.005  5836  5926 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-24 15:30:46.005  5836  5906 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,03-24 15:30:46.005  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-24 15:30:46.010  5836  9528 D BtGatt.GattService: registerClient() - UUID=bd47bd8e-e55e-465c-bee5-3cd9ccdbaa27,
,03-24 15:30:46.050  5836  5906 D BtGatt.GattService: onClientRegistered() - UUID=bd47bd8e-e55e-465c-bee5-3cd9ccdbaa27, clientIf=6
,03-24 15:30:46.050 11146 11158 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-24 15:30:46.050  5836  5849 D BtGatt.GattService: start scan with filters
,03-24 15:30:46.065  5836  5849 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 64
,03-24 15:30:46.065  5836  5926 D BtGatt.ScanManager: handling starting scan
03-24 15:30:46.065 11146 11146 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 15:30:46.065  5836  5926 D BtGatt.ScanManager: isFilteringSupported
03-24 15:30:46.065 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 15:30:46.065  5836  5926 D BluetoothAdapter: setting StandAloneBleMode
03-24 15:30:46.065 11146 11146 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 2 -> 0
03-24 15:30:46.065 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 15:30:46.065 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 15:30:46.065 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-24 15:30:46.065 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-24 15:30:46.065 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-24 15:30:46.065 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-24 15:30:46.065  5836  5917 D BtGatt.AdvertiseManager: message : 1
,03-24 15:30:46.065  5836  5917 D BtGatt.AdvertiseManager: stop advertise for client 7
03-24 15:30:46.065  5836  5917 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
,03-24 15:30:46.070  5836  5917 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-24 15:30:46.070  5836  5906 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-24 15:30:46.070  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-24 15:30:46.070  5836  5926 D BtGatt.ScanManager: allow scan with filters
03-24 15:30:46.070  5836  5926 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-24 15:30:46.070  5836  5926 D BtGatt.ScanManager: set filter index= 13 for clientIf= 6
,03-24 15:30:46.070  5836  5906 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-24 15:30:46.070  5836  5906 D BtGatt.GattService: Client app is not null!
,03-24 15:30:46.070  5836  9528 D BtGatt.GattService: unregisterClient() - clientIf=7
,03-24 15:30:46.070 11146 11146 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 15:30:46.070 11146 11146 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-24 15:30:46.070 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-24 15:30:46.070 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 15:30:46.070 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0",
03-24 15:30:46.070  5836  5906 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-24 15:30:46.070  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-24 15:30:46.070 11146 11146 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-24 15:30:46.070  5836  5926 D BtGatt.ScanManager: Starting BLE batch scan
03-24 15:30:46.070 11146 11146 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 15:30:46.070  5836  5926 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-24 15:30:46.070 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 15:30:46.070 11146 11146 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 15:30:46.075  5836  5906 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,03-24 15:30:46.075  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-24 15:30:46.075  5836  5906 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-24 15:30:46.075  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-24 15:30:46.075  5836  9528 D BtGatt.GattService: registerClient() - UUID=3e5c91ae-7d21-4dbe-b718-43ce69128ef1
,03-24 15:30:46.120  5836  5906 D BtGatt.GattService: onClientRegistered() - UUID=3e5c91ae-7d21-4dbe-b718-43ce69128ef1, clientIf=7
,03-24 15:30:46.120 11146 11158 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-24 15:30:46.170  5836  5849 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 52
,03-24 15:30:46.180  5836  5917 D BtGatt.AdvertiseManager: message : 0
,03-24 15:30:46.180  5836  5917 D BtGatt.AdvertiseManager: number of adv instance running0
03-24 15:30:46.180  5836  5917 D BtGatt.AdvertiseManager: size of list is =0
,03-24 15:30:46.185  5836  5917 D BtGatt.AdvertiseManager: starting advertising
,03-24 15:30:46.190  5836  5917 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-24 15:30:46.195  5836  5906 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-24 15:30:46.195  5836  5917 D BtGatt.AdvertiseManager: starting multi advertising,
,03-24 15:30:46.200  5836  5906 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-24 15:30:46.200  5836  5917 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,03-24 15:30:46.205  5836  5917 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 0, TxPowerLevel: 1, isConnectable: false, Timeout: 0
,03-24 15:30:46.205 11146 11146 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-24 15:30:46.205  5836  5846 D BtGatt.GattService: stopScan() - queue size =1
03-24 15:30:46.205  5836  5926 D BtGatt.ScanManager: filter size is 1
03-24 15:30:46.205  5836  5926 D BtGatt.ScanManager: delete FilterIndex - 13
03-24 15:30:46.205  5836  5906 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-24 15:30:46.205  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-24 15:30:46.205  5836  5926 D BtGatt.ScanManager: stopping BLe Batch
03-24 15:30:46.210  5836  9528 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 15:30:46.210  5836  5906 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-24 15:30:46.210  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-24 15:30:46.210  5836  5926 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-24 15:30:46.210 11146 11146 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 15:30:46.210 11146 11146 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 15:30:46.210 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 15:30:46.210  5836  5906 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,03-24 15:30:46.210  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
03-24 15:30:46.215 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 15:30:46.215 11146 11146 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-24 15:30:46.215 11146 11146 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-24 15:30:46.225  5836  5846 D BtGatt.GattService: registerClient() - UUID=10bc4bfa-43bb-4ca8-bf0a-dcddff849f0b
,03-24 15:30:46.265  5836  5906 D BtGatt.GattService: onClientRegistered() - UUID=10bc4bfa-43bb-4ca8-bf0a-dcddff849f0b, clientIf=6
,03-24 15:30:46.265 11146 11158 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-24 15:30:46.265  5836  9528 D BtGatt.GattService: start scan with filters
,03-24 15:30:46.285  5836  9528 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 65
,03-24 15:30:46.285 11146 11146 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 15:30:46.285 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 15:30:46.285  5836  5926 D BtGatt.ScanManager: handling starting scan
03-24 15:30:46.285  5836  5926 D BtGatt.ScanManager: isFilteringSupported
03-24 15:30:46.285  5836  5926 D BluetoothAdapter: setting StandAloneBleMode
03-24 15:30:46.285 11146 11146 I io.jxcore.node.ConnectionHelper: onConnected: Incoming socket thread, for peer [<no peer name> F8:CF:C5:D9:E5:61], created successfully
03-24 15:30:46.285 11146 11146 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 1
03-24 15:30:46.285 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 15:30:46.285 11146 11146 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 15:30:46.285 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 15:30:46.285 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 15:30:46.285 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 15:30:46.285 11146 11799 D io.jxcore.node.IncomingSocketThread: Entering thread (ID: 1548)
,03-24 15:30:46.285  2874  3384 D EnterpriseController: netId is 0
03-24 15:30:46.285  2874  3384 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,03-24 15:30:46.285  5836  5906 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-24 15:30:46.285  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-24 15:30:46.285  5836  5926 D BtGatt.ScanManager: allow scan with filters
03-24 15:30:46.285  5836  5926 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-24 15:30:46.285  5836  5926 D BtGatt.ScanManager: set filter index= 14 for clientIf= 6
,03-24 15:30:46.290  5836  5906 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,03-24 15:30:46.290  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-24 15:30:46.290  5836  5926 D BtGatt.ScanManager: Starting BLE batch scan
03-24 15:30:46.290  5836  5926 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-24 15:30:46.290 11146 11799 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 48179
03-24 15:30:46.290 11146 11799 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,03-24 15:30:46.290  5836  5906 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-24 15:30:46.290  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-24 15:30:46.290 11146 11799 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-24 15:30:46.290 11146 11799 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-24 15:30:46.290 11146 11799 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 1548)
,03-24 15:30:46.290 11146 11799 D io.jxcore.node.IncomingSocketThread: Exiting thread (ID: 1548)
03-24 15:30:46.290  5836  5906 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-24 15:30:46.290  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-24 15:30:46.295 11146 11802 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1550, name: Receiver)
,03-24 15:30:46.295 11146 11801 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1549, name: Sender)
,03-24 15:30:47.295  3390  3620 V AlarmManager: waitForAlarm result :4
,03-24 15:30:47.305  5836  5836 D BtGatt.ScanManager: awakened up at time 281628
,03-24 15:30:47.315  5836  5926 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-24 15:30:47.320  5836  5906 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-24 15:30:47.320  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,03-24 15:30:47.910  5836  5999 W bt-btif : new conn_srvc id:26, app_id:255
03-24 15:30:47.910  5836  5999 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
03-24 15:30:47.915  5836  5999 W bt-btif : bta_dm_pm_ssr:2, lat:1200
,03-24 15:30:47.915 11146 11703 D BluetoothSocket: socket fd passed by stack  fds: [Ljava.io.FileDescriptor;@3eeaca4,
,03-24 15:30:47.925  5836  5849 E BluetoothRemoteDevices: setRfcommConnected true,
03-24 15:30:47.925 11146 11703 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection accepted
,03-24 15:30:47.935 11146 11703 D BluetoothSocket: getInputStream(): myUserId = 0,
,03-24 15:30:47.945 11146 11703 D BluetoothSocket: getOutputStream(): myUserId = 0,
,03-24 15:30:47.945 11146 11703 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection initialized (thread ID: 1551)
03-24 15:30:47.945 11146 11703 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1011aa0d, channel: 6, state: LISTENING
,03-24 15:30:47.945 11146 11703 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1011aa0d, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1ca04f37, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@c638dc2mSocket: android.net.LocalSocket@1a0a7d3 impl:android.net.LocalSocketImpl@4bbef10 fd:FileDescriptor[113]
,03-24 15:30:47.950 11146 11703 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1a0a7d3 impl:android.net.LocalSocketImpl@4bbef10 fd:FileDescriptor[113]
,03-24 15:30:47.950 11146 11703 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-24 15:30:47.955 11146 11810 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 1551)
03-24 15:30:47.955 11146 11703 D BluetoothSocket: bindListen(): myUserId = 0
03-24 15:30:47.955 11146 11703 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-24 15:30:47.960 11146 11703 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[116]}
,03-24 15:30:47.960 11146 11703 D BluetoothSocket: bindListen(), new LocalSocket 
03-24 15:30:47.960 11146 11703 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-24 15:30:47.960 11146 11703 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3d3bda09
03-24 15:30:47.960 11146 11703 D BluetoothSocket: channel: 6
03-24 15:30:47.960 11146 11703 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-24 15:30:47.995  5836  5999 W bt-btif : new conn_srvc id:26, app_id:1
03-24 15:30:47.995  5836  5999 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
,03-24 15:30:47.995  5836  5999 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:1
03-24 15:30:47.995  5836  5999 W bt-btif : bta_dm_pm_ssr:2, lat:1200
03-24 15:30:47.995  5836  5846 E BluetoothRemoteDevices: setRfcommConnected true
,03-24 15:30:48.000 11146 11715 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onSocketConnected: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 1546)
03-24 15:30:48.000 11146 11715 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 1546)
,03-24 15:30:48.005 11146 11715 D BluetoothSocket: getInputStream(): myUserId = 0
,03-24 15:30:48.010 11146 11810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesRead: Read 15 bytes successfully (thread ID: 1551)
,03-24 15:30:48.010 11146 11810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Got valid identity from [<no peer name> F8:95:C7:87:3C:51],
03-24 15:30:48.010 11146 11810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesWritten: 15 bytes successfully written (thread ID: 1551)
03-24 15:30:48.010 11146 11810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: removeThreadFromList: Removing thread with ID 1551
03-24 15:30:48.015 11146 11810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Handshake thread disposed (thread ID: 1551)
03-24 15:30:48.015 11146 11810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onIncomingConnectionConnected: [<no peer name> F8:95:C7:87:3C:51]
03-24 15:30:48.015 11146 11810 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 1551)
,03-24 15:30:48.015 11146 11146 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:95:C7:87:3C:51]
03-24 15:30:48.015 11146 11146 I io.jxcore.node.ConnectionHelper: onConnected: Incoming connection to peer [<no peer name> F8:95:C7:87:3C:51]
03-24 15:30:48.015 11146 11146 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
03-24 15:30:48.015 11146 11715 D BluetoothSocket: getOutputStream(): myUserId = 0
03-24 15:30:48.015 11146 11715 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesWritten: 15 bytes successfully written (thread ID: 1552)
03-24 15:30:48.015  5836  5999 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-24 15:30:48.015  5836  5999 D IOP_DB_BT: db_query: result 1
03-24 15:30:48.015  5836  5999 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-24 15:30:48.015 11146 11715 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Outgoing connection initialized (*handshake* thread ID: 1552)
03-24 15:30:48.015  5836  5999 D IOP_DB_BT: db_query: result 1
03-24 15:30:48.015 11146 11715 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1546)
,03-24 15:30:48.020 11146 11813 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 1552)
03-24 15:30:48.020 11146 11146 D BluetoothSocket: getInputStream(): myUserId = 0
,03-24 15:30:48.020 11146 11146 D BluetoothSocket: getOutputStream(): myUserId = 0
,03-24 15:30:48.025 11146 11146 I io.jxcore.node.ConnectionHelper: onConnected: Incoming socket thread, for peer [<no peer name> F8:95:C7:87:3C:51], created successfully
03-24 15:30:48.025 11146 11146 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 2
03-24 15:30:48.025 11146 11814 D io.jxcore.node.IncomingSocketThread: Entering thread (ID: 1553)
,03-24 15:30:48.025 11146 11814 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 48179
,03-24 15:30:48.025 11146 11814 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
03-24 15:30:48.025 11146 11814 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-24 15:30:48.025 11146 11814 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-24 15:30:48.025 11146 11814 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 1553)
03-24 15:30:48.025 11146 11814 D io.jxcore.node.IncomingSocketThread: Exiting thread (ID: 1553)
,03-24 15:30:48.030 11146 11815 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1554, name: Sender)
,03-24 15:30:48.030 11146 11816 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1555, name: Receiver)
,03-24 15:30:48.050  5836  5999 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51,
03-24 15:30:48.050 11146 11813 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesRead: Read 15 bytes successfully (thread ID: 1552)
03-24 15:30:48.050  5836  5999 D IOP_DB_BT: db_query: result 1
03-24 15:30:48.050  5836  5999 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-24 15:30:48.055  5836  5999 D IOP_DB_BT: db_query: result 1
,03-24 15:30:48.055 11146 11813 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Handshake succeeded with [<no peer name> F8:95:C7:87:3C:51]
03-24 15:30:48.055 11146 11813 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onHandshakeSucceeded: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 1546)
03-24 15:30:48.055 11146 11813 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: handleSuccessfulClientThread: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 1546)
03-24 15:30:48.055 11146 11813 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 1552)
03-24 15:30:48.055 11146 11146 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:95:C7:87:3C:51]
03-24 15:30:48.055 11146 11146 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing connection to peer [<no peer name> F8:95:C7:87:3C:51]
03-24 15:30:48.055 11146 11146 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
,03-24 15:30:48.060 11146 11146 D BluetoothSocket: getInputStream(): myUserId = 0
,03-24 15:30:48.065 11146 11146 D BluetoothSocket: getOutputStream(): myUserId = 0
,03-24 15:30:48.065 11146 11146 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing socket thread, for peer [<no peer name> F8:95:C7:87:3C:51], created successfully
03-24 15:30:48.065 11146 11146 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 3
,03-24 15:30:48.070 11146 11819 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1556)
,03-24 15:30:48.075 11146 11819 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 42214
03-24 15:30:48.075 11146 11819 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
03-24 15:30:48.075 11146 11819 I io.jxcore.node.ConnectionHelper: onListeningForIncomingConnections: Outgoing connection is using port 42214 (peer ID: F8:95:C7:87:3C:51)
,03-24 15:30:48.075 11146 11819 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "F8:95:C7:87:3C:51" removed
,03-24 15:30:48.080 11146 11225 I jxcore-log: INFO testThaliMobileNative: 
03-24 15:30:48.080 11146 11225 I jxcore-log: 
,03-24 15:30:48.080 11146 11225 I jxcore-log: ok 163 Must have listeningPort
03-24 15:30:48.080 11146 11225 I jxcore-log: 
,03-24 15:30:48.080 11146 11225 I jxcore-log: ok 164 listeningPort must be a number
03-24 15:30:48.080 11146 11225 I jxcore-log: 
,03-24 15:30:48.080 11146 11225 I jxcore-log: ok 165 Connection must have clientPort
03-24 15:30:48.080 11146 11225 I jxcore-log: 
,03-24 15:30:48.085 11146 11225 I jxcore-log: ok 166 clientPort must be a number
03-24 15:30:48.085 11146 11225 I jxcore-log: 
,03-24 15:30:48.085 11146 11225 I jxcore-log: ok 167 Connection must have serverPort
03-24 15:30:48.085 11146 11225 I jxcore-log: 
,03-24 15:30:48.085 11146 11225 I jxcore-log: ok 168 serverPort must be a number
03-24 15:30:48.085 11146 11225 I jxcore-log: 
,03-24 15:30:48.085 11146 11225 I jxcore-log: ok 169 forward connection must have clientPort == 0
03-24 15:30:48.085 11146 11225 I jxcore-log: 
,03-24 15:30:48.090 11146 11225 I jxcore-log: ok 170 forward connection must have serverPort == 0
03-24 15:30:48.090 11146 11225 I jxcore-log: 
,03-24 15:30:48.100 11146 11225 I jxcore-log: # teardown
03-24 15:30:48.100 11146 11225 I jxcore-log: 
,03-24 15:30:48.310 11146 11801 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 1549, thread name: Sender),
03-24 15:30:48.310 11146 11801 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Input stream got -1 on read
03-24 15:30:48.310 11146 11801 W io.jxcore.node.ConnectionHelper: onDisconnected: Incoming connection, peer [<no peer name> F8:CF:C5:D9:E5:61] disconnected: Input stream got -1 on read
03-24 15:30:48.310 11146 11801 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1548
03-24 15:30:48.310 11146 11801 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 1548),
03-24 15:30:48.310 11146 11801 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1cd8ec3c, channel: 6, state: CONNECTED
03-24 15:30:48.310 11146 11801 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1cd8ec3c, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@12bf0dc5, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1ce9131amSocket: android.net.LocalSocket@332b3e4b impl:android.net.LocalSocketImpl@2f669028 fd:FileDescriptor[92]
03-24 15:30:48.310 11146 11801 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@332b3e4b impl:android.net.LocalSocketImpl@2f669028 fd:FileDescriptor[92]
03-24 15:30:48.310 11146 11802 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 1550, thread name: Receiver): bt socket closed, read return: -1
03-24 15:30:48.310 11146 11802 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1550, name: Receiver)
,03-24 15:30:48.315 11146 11801 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1cd8ec3c, channel: 6, state: CLOSED
03-24 15:30:48.315 11146 11801 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1cd8ec3c, channel: 6, state: CLOSED
03-24 15:30:48.315 11146 11801 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-24 15:30:48.315 11146 11801 D io.jxcore.node.IncomingSocketThread: close: Stopping receiving thread...
03-24 15:30:48.315 11146 11801 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 1550
03-24 15:30:48.315 11146 11801 D io.jxcore.node.IncomingSocketThread: close: Stopping sending thread...
03-24 15:30:48.315 11146 11801 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 1549
,03-24 15:30:48.315 11146 11801 D io.jxcore.node.IncomingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 1548)
03-24 15:30:48.315 11146 11801 I io.jxcore.node.IncomingSocketThread: close: Complete (thread ID: 1548),
,03-24 15:30:48.315 11146 11801 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left,
03-24 15:30:48.320 11146 11815 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 1554, thread name: Sender)
03-24 15:30:48.320 11146 11815 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Input stream got -1 on read,
03-24 15:30:48.325 11146 11815 W io.jxcore.node.ConnectionHelper: onDisconnected: Incoming connection, peer [<no peer name> F8:95:C7:87:3C:51] disconnected: Input stream got -1 on read
03-24 15:30:48.325 11146 11815 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1553
03-24 15:30:48.325 11146 11815 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 1553)
03-24 15:30:48.325 11146 11815 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1587c141, channel: 6, state: CONNECTED,
03-24 15:30:48.325 11146 11815 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1587c141, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@f546e6, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1fed7427mSocket: android.net.LocalSocket@2ea886d4 impl:android.net.LocalSocketImpl@12ce307d fd:FileDescriptor[115]
03-24 15:30:48.325 11146 11815 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2ea886d4 impl:android.net.LocalSocketImpl@12ce307d fd:FileDescriptor[115]
03-24 15:30:48.325 11146 11815 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1587c141, channel: 6, state: CLOSED,
03-24 15:30:48.325 11146 11815 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1587c141, channel: 6, state: CLOSED
03-24 15:30:48.325 11146 11815 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-24 15:30:48.325 11146 11815 D io.jxcore.node.IncomingSocketThread: close: Stopping receiving thread...
03-24 15:30:48.325 11146 11815 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 1555,
03-24 15:30:48.325 11146 11815 D io.jxcore.node.IncomingSocketThread: close: Stopping sending thread...
03-24 15:30:48.325 11146 11815 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 1554
03-24 15:30:48.325 11146 11815 D io.jxcore.node.IncomingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 1553),
,03-24 15:30:48.325 11146 11815 I io.jxcore.node.IncomingSocketThread: close: Complete (thread ID: 1553)
03-24 15:30:48.335  3390  3620 V AlarmManager: waitForAlarm result :4
03-24 15:30:48.325 11146 11815 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
03-24 15:30:48.325 11146 11815 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1554, name: Sender)
03-24 15:30:48.325 11146 11816 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 1555, thread name: Receiver): bt socket closed, read return: -1
,03-24 15:30:48.325 11146 11816 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1555, name: Receiver)
03-24 15:30:48.325 11146 11801 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1549, name: Sender)
03-24 15:30:48.340  5836  5836 D BtGatt.ScanManager: awakened up at time 282660
,03-24 15:30:48.345 11146 11225 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements,
,03-24 15:30:48.345 11146 11225 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only,
,03-24 15:30:48.350  3390  3864 E Watchdog: !@Sync 9 [03-24 15:30:48.356],
,03-24 15:30:48.345 11146 11225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-24 15:30:48.345 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...,
03-24 15:30:48.345  5836  5926 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6,
,03-24 15:30:48.350  5836  5906 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0,
03-24 15:30:48.350  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
03-24 15:30:48.355  5836  9528 D BtGatt.GattService: stopScan() - queue size =1
03-24 15:30:48.360  5836  5999 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-24 15:30:48.360  5836  5999 D IOP_DB_BT: db_query: result 1
,03-24 15:30:48.360  5836  5999 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-24 15:30:48.360  5836  5999 D IOP_DB_BT: db_query: result 1
03-24 15:30:48.360  5836  6154 W bt-btif : invalid rfc slot id: 10,
03-24 15:30:48.360  5836  5926 D BtGatt.ScanManager: filter size is 1
03-24 15:30:48.360  5836  5926 D BtGatt.ScanManager: delete FilterIndex - 14
03-24 15:30:48.360  5836  5935 D BtGatt.GattService: unregisterClient() - clientIf=6,
03-24 15:30:48.365 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 15:30:48.365 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 15:30:48.365 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false,
03-24 15:30:48.365 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-24 15:30:48.365 11146 11225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-24 15:30:48.365 11146 11225 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 15:30:48.365 11146 11146 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true,
03-24 15:30:48.365  5836  5906 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-24 15:30:48.365  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
03-24 15:30:48.365 11146 11146 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-24 15:30:48.365 11146 11146 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 15:30:48.365  5836  5926 D BtGatt.ScanManager: stopping BLe Batch
03-24 15:30:48.370  5836  5906 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-24 15:30:48.370  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-24 15:30:48.370  5836  5926 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6,
03-24 15:30:48.370  5836  5906 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0,
03-24 15:30:48.370  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-24 15:30:48.385 11146 11225 I jxcore-log: INFO thaliMobileNativeWrapper: incomingConnectionToPortNumberFailed: %s
03-24 15:30:48.385 11146 11225 I jxcore-log: 
,03-24 15:30:48.385 11146 11225 I jxcore-log: INFO thaliMobileNativeWrapper: got incomingConnectionToPortNumberFailed while not in start
03-24 15:30:48.385 11146 11225 I jxcore-log: 
,03-24 15:30:48.390 11146 11225 I jxcore-log: ok 171 Should be able to call stopListeningForAdvertisments in teardown
03-24 15:30:48.390 11146 11225 I jxcore-log: 
,03-24 15:30:48.390 11146 11225 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 15:30:48.390 11146 11225 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> F8:95:C7:87:3C:51]
03-24 15:30:48.390 11146 11225 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1556)
03-24 15:30:48.390 11146 11225 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 1556)
,03-24 15:30:48.390 11146 11225 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@123eeb72, channel: 7, state: CONNECTED
03-24 15:30:48.390 11146 11225 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@123eeb72, channel: 7, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3cb32bc3, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@b713c40mSocket: android.net.LocalSocket@39125779 impl:android.net.LocalSocketImpl@40c4cbe fd:FileDescriptor[112]
03-24 15:30:48.390 11146 11225 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@39125779 impl:android.net.LocalSocketImpl@40c4cbe fd:FileDescriptor[112]
,03-24 15:30:48.395 11146 11225 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@123eeb72, channel: 7, state: CLOSED
03-24 15:30:48.395 11146 11225 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@123eeb72, channel: 7, state: CLOSED
03-24 15:30:48.395 11146 11225 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
,03-24 15:30:48.395 11146 11225 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Nothing to close (thread ID: 1556)
03-24 15:30:48.395 11146 11225 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1556)
,03-24 15:30:48.395 11146 11819 D io.jxcore.node.OutgoingSocketThread: Exiting thread (ID: 1556)
03-24 15:30:48.395 11146 11225 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-24 15:30:48.395 11146 11225 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,03-24 15:30:48.395 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-24 15:30:48.395 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-24 15:30:48.395 11146 11225 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1192c11f, channel: 6, state: LISTENING
03-24 15:30:48.395 11146 11225 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1192c11f, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3d3bda09, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2f4ddc6cmSocket: android.net.LocalSocket@4d7f235 impl:android.net.LocalSocketImpl@25bc76ca fd:FileDescriptor[116]
,03-24 15:30:48.400 11146 11225 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@4d7f235 impl:android.net.LocalSocketImpl@25bc76ca fd:FileDescriptor[116]
,03-24 15:30:48.400 11146 11225 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-24 15:30:48.400 11146 11703 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close,
03-24 15:30:48.400 11146 11703 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-24 15:30:48.400 11146 11703 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-24 15:30:48.400 11146 11146 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-24 15:30:48.400 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
,03-24 15:30:48.405 11146 11146 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,03-24 15:30:48.405 11146 11146 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-24 15:30:48.405 11146 11225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 15:30:48.405 11146 11225 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 15:30:48.405 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 15:30:48.405 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-24 15:30:48.405 11146 11225 D BluetoothLeScanner: could not find callback wrapper,
03-24 15:30:48.405 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-24 15:30:48.405 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-24 15:30:48.410  5836  5999 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0xf):jv handle:0x0 not FOUND,
03-24 15:30:48.410  5836  5999 E bt-btif : bta_jv_port_mgmt_sr_cback, p_cb:0x0, p_cb->p_cback0x0,
,03-24 15:30:48.410  5836  5917 D BtGatt.AdvertiseManager: message : 1
03-24 15:30:48.410  5836  5917 D BtGatt.AdvertiseManager: stop advertise for client 7
03-24 15:30:48.410  5836  5917 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-24 15:30:48.415  5836  5917 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-24 15:30:48.415  5836  5906 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-24 15:30:48.415  5836  5906 D BtGatt.GattService: Client app is not null!
,03-24 15:30:48.420  5836  5935 D BtGatt.GattService: unregisterClient() - clientIf=7
,03-24 15:30:48.420 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 15:30:48.420 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 15:30:48.420 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-24 15:30:48.420 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-24 15:30:48.420 11146 11225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,03-24 15:30:48.420 11146 11225 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 15:30:48.420 11146 11225 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 15:30:48.420 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-24 15:30:48.425 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-24 15:30:48.425 11146 11225 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-24 15:30:48.425 11146 11225 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 15:30:48.425 11146 11146 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 15:30:48.425 11146 11146 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 15:30:48.425 11146 11146 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 15:30:48.425 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-24 15:30:48.425 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-24 15:30:48.425 11146 11225 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true},
03-24 15:30:48.425 11146 11225 I jxcore-log: 
,03-24 15:30:48.430 11146 11225 I jxcore-log: ok 172 Should be able to call stopAdvertisingAndListening in teardown
03-24 15:30:48.430 11146 11225 I jxcore-log: 
,03-24 15:30:48.430 11146 11146 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
,03-24 15:30:48.435 11146 11225 I jxcore-log: # setup
03-24 15:30:48.435 11146 11225 I jxcore-log: 
,03-24 15:30:48.435 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
,03-24 15:30:48.440 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
,03-24 15:30:48.440 11146 11146 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 15:30:48.440 11146 11146 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-24 15:30:48.440 11146 11146 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 15:30:48.440 11146 11225 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 15:30:48.440 11146 11225 I jxcore-log: 
,03-24 15:30:48.445 11146 11225 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 15:30:48.445 11146 11225 I jxcore-log: 
,03-24 15:30:48.620  5836  5999 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0x12):jv handle:0x0 not FOUND,
,03-24 15:30:48.620  5836  5999 E bt-btif : bta_jv_port_mgmt_sr_cback, p_cb:0x0, p_cb->p_cback0x0,
,03-24 15:30:51.120  5836  5999 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-24 15:30:51.120  5836  5999 D IOP_DB_BT: db_query: result 1
03-24 15:30:51.120  5836  5999 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-24 15:30:51.120  5836  5999 D IOP_DB_BT: db_query: result 1
,03-24 15:30:51.785  5836  5999 E bt-btm  : Reset sec_bd_name and name flag. (BR/EDR link)
03-24 15:30:51.785  5836  5999 E bt-btm  : btm_sec_disconnected - Clearing Pending flag
03-24 15:30:51.785  5836  5999 W bt-btif : bta_dm_acl_change(), event : 1
03-24 15:30:51.785  5836  5999 W bt-btif : bta_dm_acl_change(), event : 2
,03-24 15:30:51.790  5836  5906 E BluetoothRemoteDevices: aclStateChangeCallback: State:DisConnected to Device:F8:CF:C5:D9:E5:XX
03-24 15:30:51.810  5836  5906 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,03-24 15:30:51.815  3727  3727 D KeyguardViewMediator: Received android.bluetooth.device.action.ACL_DISCONNECTED
,03-24 15:30:51.825  3390  3390 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive,
03-24 15:30:51.825  3390  3390 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.device.action.ACL_DISCONNECTED
03-24 15:30:51.825  3390  3390 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_ACL_DISCONNECTED
,03-24 15:30:51.850  3390  3572 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{37433bda u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{15b2ca6 5836:com.android.bluetooth/1002}
,03-24 15:30:51.855  5836  5836 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@201846a0
03-24 15:30:51.865  3390  4257 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
03-24 15:30:51.855  5836  5836 D BtConfig.SecureMode: isSecureModeOn:false
03-24 15:30:51.860  3390  4707 D SecContentProvider: query(), uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,03-24 15:30:51.865  5836  5836 I BluetoothPbapService: action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
03-24 15:30:51.870  3727  3727 D KeyguardViewMediator: isGear1: device is not B1!
,03-24 15:30:51.875  3390  3965 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-24 15:30:51.875  3390  3965 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-24 15:30:51.875  3390  3965 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-24 15:30:51.875  3390  3965 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-24 15:30:51.880  3390  6051 D SSRM:n  : SIOP:: AP = 280, PST = 285 (W:14), CUR = 45, LCD = 0
,03-24 15:30:51.885 11146 11225 I jxcore-log: # 39. Can shift large amounts of data
03-24 15:30:51.885 11146 11225 I jxcore-log: 
,03-24 15:30:51.890 11836 11836 E Zygote  : MountEmulatedStorage()
03-24 15:30:51.890 11836 11836 E Zygote  : v2
03-24 15:30:51.890 11836 11836 I libpersona: KNOX_SDCARD checking this for 10036
03-24 15:30:51.890 11836 11836 I libpersona: KNOX_SDCARD not a persona
,03-24 15:30:51.895 11836 11836 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
,03-24 15:30:51.895  3390  3965 I ActivityManager: Start proc 11836:com.sec.android.app.shealth/u0a36 for broadcast-3 com.sec.android.app.shealth/com.samsung.android.app.shealth.tracker.weight.receiver.TrackerWeightReceiver
03-24 15:30:51.895 11836 11836 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
,03-24 15:30:51.895 11836 11836 E Zygote  : accessInfo : 0
,03-24 15:30:51.900 11836 11836 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-24 15:30:51.900  3390  4709 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
,03-24 15:30:51.910 10341 11845 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.ACL_DISCONNECTED State = -2147483648 Previous = -2147483648
,03-24 15:30:51.910 10341 10341 D [CarModeFW]: ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED
03-24 15:30:51.915 10341 10341 D [CarModeFW]: ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED onNotifyBluetoothDeviceDisconnected
,03-24 15:30:51.920 10341 10341 D [CarModeFW]: ConnectivityManager-Paired Devices list is empty
,03-24 15:30:51.920 10341 10341 E [CarMode]: [BluetoothConnectivityListener]-onNotifyBluetoothProfileDisconnected: Unexpected error: Invalid device
,03-24 15:30:51.925 11836 11836 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-24 15:30:51.925 11836 11836 D ActivityThread: Added TimaKeyStore provider
,03-24 15:30:51.935  3390  4045 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{37433bda u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{464c6e8 11836:com.sec.android.app.shealth/u0a36}
,03-24 15:30:51.945 11836 11836 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-24 15:30:52.000  3390  4707 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-24 15:30:52.000  3390  4707 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:30:52.000  3390  4707 D BatteryService: online:4, current avg:43, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:51
03-24 15:30:52.000  3390  4707 D BatteryService: stay LED for fully charged
03-24 15:30:52.000  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-24 15:30:52.005  3390  3390 I MotionRecognitionService: Plugged
03-24 15:30:52.005  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:30:52.005  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-24 15:30:52.005  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:30:52.005  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:30:52.005  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:30:52.005  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:30:52.010  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-24 15:30:52.010  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:30:52.025  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:30:52.030  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:30:52.030  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:30:52.030  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:30:52.040 11836 11836 D HealthConsole: Service for HealthDataConsole is connected
,03-24 15:30:52.045  3390  4709 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{37433bda u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{464c6e8 11836:com.sec.android.app.shealth/u0a36}
,03-24 15:30:52.060 11836 11836 D HealthConsole: Service for HealthDataConsole is connected
,03-24 15:30:52.065  3390  3429 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{37433bda u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{464c6e8 11836:com.sec.android.app.shealth/u0a36}
,03-24 15:30:52.080  3390  3832 I ActivityManager: Killing 10218:com.facebook.system/u0a10 (adj 15): emptyCount ##31
,03-24 15:30:52.085  3390  3832 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{37433bda u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{2fc8d8b1 4128:com.google.android.googlequicksearchbox:search/u0a64}
,03-24 15:30:52.115  4128  4128 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,03-24 15:30:52.120  4128  4128 I BluetoothClassifier: Bluetooth Device Name: Nexus 6
,03-24 15:30:53.470 11146 11225 I io.jxcore.node.ConnectionHelper: start: Port number: 54065, start advertisements: true
03-24 15:30:53.470 11146 11225 I io.jxcore.node.ConnectionHelper: restoreDefaultBleDiscoverySettings: Powering the BLE discovery back up
03-24 15:30:53.470 11146 11225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 0 -> 2
03-24 15:30:53.470 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 15:30:53.470 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 15:30:53.470 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-24 15:30:53.470 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-24 15:30:53.470 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-24 15:30:53.470 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 15:30:53.470 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 1, timeout: 0, is connectable: false
03-24 15:30:53.470 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 15:30:53.470 11146 11225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 1 -> 3
03-24 15:30:53.470 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 15:30:53.470 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 15:30:53.470 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-24 15:30:53.470 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-24 15:30:53.470 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-24 15:30:53.470 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 15:30:53.470 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-24 15:30:53.470 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 15:30:53.470 11146 11225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 0 -> 2
03-24 15:30:53.470 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 15:30:53.470 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 15:30:53.470 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-24 15:30:53.470 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-24 15:30:53.470 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-24 15:30:53.470 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 15:30:53.470 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectabl,e: false
03-24 15:30:53.470 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 15:30:53.470 11146 11225 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 15:30:53.470 11146 11225 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-24 15:30:53.470 11146 11225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 15:30:53.475 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-24 15:30:53.475 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 15:30:53.475 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 15:30:53.475 11146 11225 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 15:30:53.480  5836  5935 D BtGatt.GattService: registerClient() - UUID=e2c6e374-548a-41b8-90ee-e8ee9e6a29d5
,03-24 15:30:53.520  5836  5906 D BtGatt.GattService: onClientRegistered() - UUID=e2c6e374-548a-41b8-90ee-e8ee9e6a29d5, clientIf=6
,03-24 15:30:53.520 11146 11160 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-24 15:30:53.520  5836  5846 D BtGatt.GattService: start scan with filters
,03-24 15:30:53.535  5836  5846 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 66
,03-24 15:30:53.535 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 15:30:53.535 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-24 15:30:53.535 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 15:30:53.535  5836  5926 D BtGatt.ScanManager: handling starting scan
03-24 15:30:53.535 11146 11225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 15:30:53.535  5836  5926 D BtGatt.ScanManager: isFilteringSupported
,03-24 15:30:53.535  5836  5926 D BluetoothAdapter: setting StandAloneBleMode
03-24 15:30:53.535 11146 11225 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 15:30:53.540 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 15:30:53.540 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-24 15:30:53.540 11146 11146 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 15:30:53.540 11146 11225 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-24 15:30:53.540 11146 11225 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-24 15:30:53.540 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 15:30:53.540 11146 11225 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-24 15:30:53.540  5836  5906 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-24 15:30:53.540  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-24 15:30:53.540  5836  5926 D BtGatt.ScanManager: allow scan with filters
03-24 15:30:53.540  5836  5926 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-24 15:30:53.540  5836  5926 D BtGatt.ScanManager: set filter index= 15 for clientIf= 6
,03-24 15:30:53.545  5836  5906 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-24 15:30:53.545  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-24 15:30:53.545  5836  5926 D BtGatt.ScanManager: Starting BLE batch scan
03-24 15:30:53.545  5836  5926 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-24 15:30:53.545  5836  5906 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,03-24 15:30:53.545  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-24 15:30:53.545  5836  5846 D BtGatt.GattService: registerClient() - UUID=9edb1e95-d324-4aef-af93-6529be279966
,03-24 15:30:53.550  5836  5906 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,03-24 15:30:53.550  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-24 15:30:53.590  5836  5906 D BtGatt.GattService: onClientRegistered() - UUID=9edb1e95-d324-4aef-af93-6529be279966, clientIf=7
,03-24 15:30:53.590 11146 11158 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-24 15:30:53.605  5836  9528 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 53
,03-24 15:30:53.605  5836  5917 D BtGatt.AdvertiseManager: message : 0
,03-24 15:30:53.605  5836  5917 D BtGatt.AdvertiseManager: number of adv instance running0
03-24 15:30:53.605  5836  5917 D BtGatt.AdvertiseManager: size of list is =0
,03-24 15:30:53.610  5836  5917 D BtGatt.AdvertiseManager: starting advertising
03-24 15:30:53.610  5836  5917 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-24 15:30:53.615  5836  5906 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-24 15:30:53.620  5836  5917 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 15:30:53.620  5836  5906 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-24 15:30:53.625  5836  5917 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-24 15:30:53.625  5836  5917 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,03-24 15:30:53.625 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-24 15:30:53.625 11146 11225 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 15:30:53.625 11146 11225 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 15:30:53.625 11146 11225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 15:30:53.625 11146 11225 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-24 15:30:53.625 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 15:30:53.630 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-24 15:30:53.630 11146 11225 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-24 15:30:53.630 11146 11225 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-24 15:30:53.630 11146 11225 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-24 15:30:53.630 11146 11146 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything,
03-24 15:30:53.630 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 15:30:53.630 11146 11146 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 15:30:53.630 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,03-24 15:30:53.630 11146 11146 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-24 15:30:53.630 11146 11146 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-24 15:30:53.630 11146 11146 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 15:30:53.630 11146 11146 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 15:30:53.630 11146 11146 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,03-24 15:30:53.630 11146 11146 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 15:30:53.630 11146 11146 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-24 15:30:53.630 11146 11146 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 15:30:53.630 11146 11225 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 15:30:53.635 11146 11225 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false},
03-24 15:30:53.635 11146 11225 I jxcore-log: 
,03-24 15:30:53.640 11146 11887 D BluetoothSocket: bindListen(): myUserId = 0,
,03-24 15:30:53.645 11146 11887 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-24 15:30:53.645 11146 11887 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[93]},
,03-24 15:30:53.645 11146 11887 D BluetoothSocket: bindListen(), new LocalSocket 
03-24 15:30:53.645 11146 11887 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-24 15:30:53.645 11146 11887 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2b933596
03-24 15:30:53.645 11146 11887 D BluetoothSocket: channel: 6
,03-24 15:30:53.645 11146 11887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-24 15:30:53.650 11146 11225 I jxcore-log: ok 173 Can call startUpdateAdvertisingAndListening without error
03-24 15:30:53.650 11146 11225 I jxcore-log: 
,03-24 15:30:53.655 11146 11225 I io.jxcore.node.ConnectionHelper: start: Port number: 54065, start advertisements: false
,03-24 15:30:53.655 11146 11225 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 15:30:53.655 11146 11225 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
,03-24 15:30:53.655 11146 11225 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 15:30:53.655 11146 11225 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 15:30:53.660 11146 11225 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 15:30:53.660 11146 11225 I jxcore-log: 
,03-24 15:30:53.660 11146 11225 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 15:30:53.660 11146 11225 I jxcore-log: 
,03-24 15:30:53.665 11146 11225 I jxcore-log: ok 174 Can call startListeningForAdvertisements without error
03-24 15:30:53.665 11146 11225 I jxcore-log: 
,03-24 15:30:54.485  5836  5999 E bt-btm  : Reset sec_bd_name and name flag. (BR/EDR link)
03-24 15:30:54.485  5836  5999 E bt-btm  : btm_sec_disconnected - Clearing Pending flag
03-24 15:30:54.485  5836  5999 W bt-btif : bta_dm_acl_change(), event : 1
03-24 15:30:54.485  5836  5999 W bt-btif : bta_dm_acl_change(), event : 2
,03-24 15:30:54.490  5836  5906 E BluetoothRemoteDevices: aclStateChangeCallback: State:DisConnected to Device:F8:95:C7:87:3C:XX
03-24 15:30:54.510  5836  5906 D BluetoothUtils: getBtEnabledContainers(): btContainers = [],
03-24 15:30:54.510  3727  3727 D KeyguardViewMediator: Received android.bluetooth.device.action.ACL_DISCONNECTED
,03-24 15:30:54.525  3390  3390 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive,
03-24 15:30:54.525  3390  3390 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.device.action.ACL_DISCONNECTED
03-24 15:30:54.525  3390  3390 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_ACL_DISCONNECTED
,03-24 15:30:54.535  3390  3572 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{20aeb5f5 u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{15b2ca6 5836:com.android.bluetooth/1002}
03-24 15:30:54.540  3390  4044 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
,03-24 15:30:54.540  3727  3727 D KeyguardViewMediator: isGear1: device is not B1!
,03-24 15:30:54.550  3390  3620 V AlarmManager: waitForAlarm result :4
,03-24 15:30:54.550  5836  5836 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@201846a0
03-24 15:30:54.550  5836  5836 D BtConfig.SecureMode: isSecureModeOn:false
,03-24 15:30:54.550  3390  4257 D SecContentProvider: query(), uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,03-24 15:30:54.555 10341 11897 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.ACL_DISCONNECTED State = -2147483648 Previous = -2147483648
,03-24 15:30:54.560 10341 10341 D [CarModeFW]: ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED
,03-24 15:30:54.560 10341 10341 D [CarModeFW]: ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED onNotifyBluetoothDeviceDisconnected
03-24 15:30:54.560  3390  4045 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,03-24 15:30:54.560  5836  5836 I BluetoothPbapService: action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,03-24 15:30:54.565 10341 10341 D [CarModeFW]: ConnectivityManager-Paired Devices list is empty
03-24 15:30:54.565 10341 10341 E [CarMode]: [BluetoothConnectivityListener]-onNotifyBluetoothProfileDisconnected: Unexpected error: Invalid device
,03-24 15:30:54.565  3390  3429 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{20aeb5f5 u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{464c6e8 11836:com.sec.android.app.shealth/u0a36}
,03-24 15:30:54.580  3390  3853 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{20aeb5f5 u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{464c6e8 11836:com.sec.android.app.shealth/u0a36}
,03-24 15:30:54.590  3390  4709 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{20aeb5f5 u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{464c6e8 11836:com.sec.android.app.shealth/u0a36}
,03-24 15:30:54.600  3390  4045 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{20aeb5f5 u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{2fc8d8b1 4128:com.google.android.googlequicksearchbox:search/u0a64}
,03-24 15:30:54.605  4128  4128 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,03-24 15:30:54.605  4128  4128 I BluetoothClassifier: Bluetooth Device Name: G4-1
,03-24 15:30:54.615  5836  5836 D BtGatt.ScanManager: awakened up at time 288936
,03-24 15:30:54.615  5836  5926 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-24 15:30:54.615  5836  5906 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
03-24 15:30:54.615  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-24 15:30:54.620  5836  5906 D BtGatt.GattService: current time is 288940083658
03-24 15:30:54.620  5836  5906 D BtGatt.GattService: Batch record : [17, -94, 76, -115, 109, 94, 1, -128, -70, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, 121, 28, 84, 124, 93, 126, 1, -128, -56, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0]
03-24 15:30:54.620  5836  5906 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 15:30:54.620  5836  5906 D ScanRecord: parseFromBytes
03-24 15:30:54.620  5836  5906 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-24 15:30:54.620  5836  5906 D ScanRecord: parseFromBytes
,03-24 15:30:54.620  5836  5906 D BtGatt.GattService: result: ScanResult{mDevice=7E:5D:7C:54:1C:79, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-56, mTimestampNanos=288890255825}
03-24 15:30:54.620  5836  5906 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-24 15:30:54.620  5836  5906 D BtGatt.GattService: result: ScanResult{mDevice=5E:6D:8D:4C:A2:11, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-70, mTimestampNanos=288840255825}
03-24 15:30:54.620  5836  5906 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-24 15:30:54.620 11146 11158 D ScanRecord: parseFromBytes
03-24 15:30:54.620 11146 11158 D ScanRecord: parseFromBytes
03-24 15:30:54.620 11146 11146 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:CF:C5:D9:E5:61], added - the peer count is 1
,03-24 15:30:54.620 11146 11146 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 2
03-24 15:30:54.620 11146 11146 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:CF:C5:D9:E5:61], Bluetooth address: F8:CF:C5:D9:E5:61, device name: , device address: 
03-24 15:30:54.620 11146 11146 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
,03-24 15:30:54.625 11146 11225 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID F8:CF:C5:D9:E5:61
03-24 15:30:54.625 11146 11225 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> F8:CF:C5:D9:E5:61]
,03-24 15:30:54.625 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to Nexus 6 in address F8:CF:C5:D9:E5:61
,03-24 15:30:54.625 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
03-24 15:30:54.630 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
03-24 15:30:54.630 11146 11225 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: Nexus 6 F8:CF:C5:D9:E5:61
03-24 15:30:54.630 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to Nexus 6 in address F8:CF:C5:D9:E5:61
,03-24 15:30:54.630 11146 11225 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: F8:CF:C5:D9:E5:61)
03-24 15:30:54.630 11146 11898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address F8:CF:C5:D9:E5:61 (thread ID: 1558)
,03-24 15:30:54.640 11146 11898 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null,
03-24 15:30:54.640 11146 11898 D BluetoothSocket: connect(): myUserId = 0
03-24 15:30:54.640 11146 11898 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-24 15:30:54.640  5836  5849 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
03-24 15:30:54.640  5836  5999 D IOP_DB_BT: db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-24 15:30:54.640  5836  5999 D IOP_DB_BT: db_query_add_key: key KEY_LMP_MFCT, value 15
03-24 15:30:54.640  5836  5999 D IOP_DB_BT: db_query_add_key: key KEY_LMP_VER, value 7:8975
03-24 15:30:54.640  5836  5999 D IOP_DB_BT: db_query_add_key: key KEY_DIR_ALL, value 1
03-24 15:30:54.640  5836  5999 D IOP_DB_BT: db_query_execute: result 1
03-24 15:30:54.640  5836  5999 W bt-btif : bta_dm_acl_change(), event : 2
03-24 15:30:54.645 11146 11898 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[112]}
,03-24 15:30:55.490  3390  6082 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-24 15:30:55.620  3390  3620 V AlarmManager: waitForAlarm result :4
,03-24 15:30:55.630  5836  5836 D BtGatt.ScanManager: awakened up at time 289953
,03-24 15:30:55.635  5836  5926 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-24 15:30:55.645  5836  5906 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
03-24 15:30:55.645  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-24 15:30:55.645  5836  5906 D BtGatt.GattService: current time is 289965333408
03-24 15:30:55.645  5836  5906 D BtGatt.GattService: Batch record : [17, -94, 76, -115, 109, 94, 1, -128, -71, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, 121, 28, 84, 124, 93, 126, 1, -128, -56, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0]
03-24 15:30:55.645  5836  5906 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 15:30:55.645  5836  5906 D ScanRecord: parseFromBytes
03-24 15:30:55.645  5836  5906 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-24 15:30:55.645  5836  5906 D ScanRecord: parseFromBytes
03-24 15:30:55.645  5836  5906 D BtGatt.GattService: result: ScanResult{mDevice=7E:5D:7C:54:1C:79, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-56, mTimestampNanos=289915511991}
03-24 15:30:55.645  5836  5906 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 15:30:55.645  5836  5906 D BtGatt.GattService: result: ScanResult{mDevice=5E:6D:8D:4C:A2:11, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-71, mTimestampNanos=289915511991},
03-24 15:30:55.645  5836  5906 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-24 15:30:55.645 11146 11160 D ScanRecord: parseFromBytes
,03-24 15:30:55.645 11146 11160 D ScanRecord: parseFromBytes
03-24 15:30:55.645 11146 11146 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:CF:C5:D9:E5:61] updated - the peer count is 2
03-24 15:30:55.645 11146 11146 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
,03-24 15:30:56.040  5836  5999 W bt-btif : bta_dm_acl_change(), event : 2
03-24 15:30:56.040  5836  5999 W bt-btif : bta_dm_acl_change(), event : 4
03-24 15:30:56.040  5836  5999 W bt-btif : scb return value : 1
,03-24 15:30:56.055  5836  5999 D IOP_DB_BT: db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-24 15:30:56.055  5836  5999 D IOP_DB_BT: db_query_add_key: key KEY_LMP_MFCT, value 15
03-24 15:30:56.055  5836  5999 D IOP_DB_BT: db_query_add_key: key KEY_LMP_VER, value 7:24841
03-24 15:30:56.055  5836  5999 D IOP_DB_BT: db_query_add_key: key KEY_DIR_ALL, value *
03-24 15:30:56.060  5836  5999 D IOP_DB_BT: db_query_execute: result 1
03-24 15:30:56.060  5836  5999 D IOP_DB_BT: db_query: id SkipSdpInfo :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-24 15:30:56.060  5836  5999 D IOP_DB_BT: db_query: result 1
03-24 15:30:56.060  5836  5999 W bt-btif : bta_dm_acl_change(), event : 0
03-24 15:30:56.060  5836  5999 W bt-btif : info:x10
03-24 15:30:56.060  5836  5906 D         : remote version info [f8:cf:c5:d9:e5:61]: 7, f, 6109
03-24 15:30:56.060  5836  5906 E BluetoothRemoteDevices: aclStateChangeCallback: State:Connected to Device:F8:CF:C5:D9:E5:XX
03-24 15:30:56.065  5836  5999 W bt-btif : bta_dm_acl_change(), event : 2
03-24 15:30:56.095  5836  5906 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
03-24 15:30:56.095  3727  3727 D KeyguardViewMediator: Received android.bluetooth.device.action.ACL_CONNECTED
,03-24 15:30:56.110  3390  3390 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive,
,03-24 15:30:56.110  3390  3390 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.device.action.ACL_CONNECTED
03-24 15:30:56.110  3390  3390 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_ACL_CONNECTED
,03-24 15:30:56.120  3390  3572 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3801bc71 u0 android.bluetooth.device.action.ACL_CONNECTED} DELIVERED for app ProcessRecord{464c6e8 11836:com.sec.android.app.shealth/u0a36},
03-24 15:30:56.120  3390  4710 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
,03-24 15:30:56.130  5836  5906 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,03-24 15:30:56.130  3727  3727 D KeyguardViewMediator: isGear1: device is not B1!
,03-24 15:30:56.135 10341 11915 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.ACL_CONNECTED State = -2147483648 Previous = -2147483648
,03-24 15:30:56.140  3390  4709 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3801bc71 u0 android.bluetooth.device.action.ACL_CONNECTED} DELIVERED for app ProcessRecord{464c6e8 11836:com.sec.android.app.shealth/u0a36}
,03-24 15:30:56.140 10341 10341 D [CarModeFW]: ConnectivityManager-handleMessage BLUETOOTH_ACL_CONNECTED
,03-24 15:30:56.145  5836  5999 W bt-sdp  : process_service_search_attr_rsp
,03-24 15:30:56.150 10341 10341 D [CarModeFW]: ConnectivityManager-handleMessage BLUETOOTH_ACL_CONNECTED onNotifyBluetoothDeviceConnected
03-24 15:30:56.150 10341 10341 D [CarModeFW]: ConnectivityManager-handleMessage CONNECTION_COMPLETE
,03-24 15:30:56.150  3390  3832 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3801bc71 u0 android.bluetooth.device.action.ACL_CONNECTED} DELIVERED for app ProcessRecord{464c6e8 11836:com.sec.android.app.shealth/u0a36}
,03-24 15:30:56.165  3390  3652 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3801bc71 u0 android.bluetooth.device.action.ACL_CONNECTED} DELIVERED for app ProcessRecord{234f3170 10147:com.android.settings/1000}
,03-24 15:30:56.165 10147 10147 D BluetoothNotiBroadcastReceiver: onReceive
,03-24 15:30:56.175  3390  3652 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3801bc71 u0 android.bluetooth.device.action.ACL_CONNECTED} DELIVERED for app ProcessRecord{2fc8d8b1 4128:com.google.android.googlequicksearchbox:search/u0a64}
,03-24 15:30:56.190  4128  4128 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,03-24 15:30:56.195  4128  4128 I BluetoothClassifier: Bluetooth Device Name: Nexus 6
,03-24 15:30:56.410  3390  3587 I PowerManagerService: [PWL] Off : 225s ago
03-24 15:30:56.410  3390  3587 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
03-24 15:30:56.410  3390  3587 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
03-24 15:30:56.410  3390  3587 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'bluedroid_timer' (uid=1002, pid=5836, ws=null) (elapsedTime=14470)
,03-24 15:30:56.655  3390  3620 V AlarmManager: waitForAlarm result :4
,03-24 15:30:56.670  5836  5836 D BtGatt.ScanManager: awakened up at time 290990
,03-24 15:30:56.675  5836  5926 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-24 15:30:56.680  5836  5906 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
03-24 15:30:56.680  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-24 15:30:56.680  5836  5906 D BtGatt.GattService: current time is 291003920117
03-24 15:30:56.680  5836  5906 D BtGatt.GattService: Batch record : [17, -94, 76, -115, 109, 94, 1, -128, -65, 15, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, 121, 28, 84, 124, 93, 126, 1, -128, -53, 15, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0]
03-24 15:30:56.685  5836  5906 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 15:30:56.685  5836  5906 D ScanRecord: parseFromBytes
03-24 15:30:56.685  5836  5906 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-24 15:30:56.685  5836  5906 D ScanRecord: parseFromBytes
03-24 15:30:56.685  5836  5906 D BtGatt.GattService: result: ScanResult{mDevice=7E:5D:7C:54:1C:79, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-53, mTimestampNanos=290254343617}
03-24 15:30:56.685  5836  5906 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-24 15:30:56.685  5836  5906 D BtGatt.GattService: result: ScanResult{mDevice=5E:6D:8D:4C:A2:11, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-65, mTimestampNanos=290254343617}
03-24 15:30:56.685  5836  5906 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-24 15:30:56.685 11146 11158 D ScanRecord: parseFromBytes
03-24 15:30:56.685 11146 11158 D ScanRecord: parseFromBytes
,03-24 15:30:56.695 11146 11146 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:CF:C5:D9:E5:61] updated - the peer count is 2,
03-24 15:30:56.695 11146 11146 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
,03-24 15:30:57.705  3390  3620 V AlarmManager: waitForAlarm result :4
,03-24 15:30:57.720  5836  5836 D BtGatt.ScanManager: awakened up at time 292042
03-24 15:30:57.725  5836  5926 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-24 15:30:57.730  5836  5906 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-24 15:30:57.730  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-24 15:30:58.120  5836  5999 W bt-btif : dm_pm_timer expires
03-24 15:30:58.120  5836  5999 W bt-btif : dm_pm_timer expires 0
03-24 15:30:58.120  5836  5999 W bt-btif : proc dm_pm_timer expires
,03-24 15:30:58.745  3390  3620 V AlarmManager: waitForAlarm result :4
,03-24 15:30:58.760  5836  5836 D BtGatt.ScanManager: awakened up at time 293081
,03-24 15:30:58.765  5836  5926 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-24 15:30:58.770  5836  5906 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-24 15:30:58.770  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,03-24 15:30:59.780  3390  3620 V AlarmManager: waitForAlarm result :4
,03-24 15:30:59.795  5836  5836 D BtGatt.ScanManager: awakened up at time 294115
,03-24 15:30:59.800  5836  5926 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-24 15:30:59.800  5836  5906 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-24 15:30:59.800  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-24 15:31:00.000  3390  3620 V AlarmManager: waitForAlarm result :8,
,03-24 15:31:00.810  3390  3620 V AlarmManager: waitForAlarm result :4
,03-24 15:31:00.835  5836  5836 D BtGatt.ScanManager: awakened up at time 295155
,03-24 15:31:00.840  5836  5926 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-24 15:31:00.840  5836  5906 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-24 15:31:00.840  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-24 15:31:00.855  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
03-24 15:31:00.855  3727  3727 I PERF    : received broadcast android.intent.action.TIME_TICK
03-24 15:31:00.855  3727  3727 D KeyguardUpdateMonitor: handleTimeUpdate
,03-24 15:31:00.865  3727  3727 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,03-24 15:31:00.875  3727  3727 D SecKeyguardClockView: HomeTimezone(): 1
,03-24 15:31:00.880  3727  3727 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-24 15:31:00.880  3727  3727 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,03-24 15:31:00.890  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,03-24 15:31:00.935  3727  3727 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-24 15:31:00.935  3727  3727 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-24 15:31:00.940  3727  3727 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-24 15:31:00.940  3727  3727 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-24 15:31:00.945  3727  3727 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-24 15:31:00.950  3727  3727 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-24 15:31:00.965  3727  3727 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-24 15:31:01.845  3390  3620 V AlarmManager: waitForAlarm result :4
,03-24 15:31:01.860  5836  5836 D BtGatt.ScanManager: awakened up at time 296181
,03-24 15:31:01.865  5836  5926 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-24 15:31:01.870  5836  5906 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=3,
03-24 15:31:01.870  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-24 15:31:01.870  5836  5906 D BtGatt.GattService: current time is 296191833284
,03-24 15:31:01.870  5836  5906 D BtGatt.GattService: Batch record : [51, 74, 69, 91, 51, 110, 1, -128, -77, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -28, -44, -106, -22, -38, 116, 0, -128, -92, 20, 0, 23, 2, 1, 6, 3, 2, 5, 24, 15, 9, 90, 101, 70, 105, 116, 50, 32, 35, 54, 54, 48, 55, 53, 0, 16, 15, 9, 90, 101, 70, 105, 116, 50, 32, 35, 54, 54, 48, 55, 53, 0, 62, 23, 49, 75, 90, 110, 1, -128, -65, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0],
,03-24 15:31:01.870  5836  5906 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 15:31:01.870  5836  5906 D ScanRecord: parseFromBytes
,03-24 15:31:01.870  5836  5906 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 5, 24, 15, 9, 90, 101, 70, 105, 116, 50, 32, 35, 54, 54, 48, 55, 53, 0, 15, 9, 90, 101, 70, 105, 116, 50, 32, 35, 54, 54, 48, 55, 53, 0]
03-24 15:31:01.870  5836  5906 D ScanRecord: parseFromBytes
03-24 15:31:01.870  5836  5906 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
,03-24 15:31:01.870  5836  5906 D ScanRecord: parseFromBytes,
,03-24 15:31:01.870  5836  5906 D BtGatt.GattService: result: ScanResult{mDevice=6E:5A:4B:31:17:3E, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-65, mTimestampNanos=296192053117}
,03-24 15:31:01.870  5836  5906 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-24 15:31:01.870  5836  5906 D BtGatt.GattService: result: ScanResult{mDevice=74:DA:EA:96:D4:E4, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[00001805-0000-1000-8000-00805f9b34fb], mManufacturerSpecificData={}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=ZeFit2 #66075��], mRssi=-92, mTimestampNanos=295192053117}
03-24 15:31:01.870  5836  5906 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 15:31:01.870  5836  5906 D BtGatt.GattService: result: ScanResult{mDevice=6E:33:5B:45:4A:33, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-77, mTimestampNanos=296192053117}
03-24 15:31:01.870  5836  5906 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-24 15:31:01.870 11146 11160 D ScanRecord: parseFromBytes,
03-24 15:31:01.870 11146 11160 D ScanRecord: parseFromBytes
03-24 15:31:01.870 11146 11160 D ScanRecord: parseFromBytes
03-24 15:31:01.875 11146 11146 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:CF:C5:D9:E5:61] updated - the peer count is 2
03-24 15:31:01.875 11146 11146 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2,
,03-24 15:31:01.900  3390  6051 D SSRM:n  : SIOP:: AP = 280, PST = 282 (W:14), CUR = 43, LCD = 0
,03-24 15:31:02.065  5836  5903 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,03-24 15:31:02.130  3390  4707 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:31:02.130  3390  4707 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:31:02.130  3390  4707 D BatteryService: online:4, current avg:41, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:50
03-24 15:31:02.130  3390  4707 D BatteryService: stay LED for fully charged
03-24 15:31:02.130  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-24 15:31:02.135  3390  3390 I MotionRecognitionService: Plugged
03-24 15:31:02.135  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:31:02.135  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-24 15:31:02.135  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:31:02.140  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:31:02.140  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:31:02.140  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:31:02.155  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-24 15:31:02.155  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:31:02.165  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:31:02.165  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:31:02.165  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:31:02.165  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:31:02.890  3390  3620 V AlarmManager: waitForAlarm result :4
,03-24 15:31:02.900  5836  5836 D BtGatt.ScanManager: awakened up at time 297223,
,03-24 15:31:02.905  5836  5926 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-24 15:31:02.915  5836  5906 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-24 15:31:02.915  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,03-24 15:31:03.145  5836  5999 W bt-l2cap: L2CAP - no CCB for conn rsp, LCID: 72 RCID: 69
,03-24 15:31:03.170  5836  5999 W bt-btif : new conn_srvc id:26, app_id:255
03-24 15:31:03.170  5836  5999 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
03-24 15:31:03.170  5836  5999 W bt-btif : bta_dm_pm_ssr:2, lat:1200
,03-24 15:31:03.175  5836  5999 W bt-btif : new conn_srvc id:26, app_id:1
03-24 15:31:03.175  5836  5999 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
03-24 15:31:03.175  5836  5999 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:1
03-24 15:31:03.175  5836  5999 W bt-btif : bta_dm_pm_ssr:2, lat:1200
03-24 15:31:03.180  5836  5935 E BluetoothRemoteDevices: setRfcommConnected true
,03-24 15:31:03.190 11146 11887 D BluetoothSocket: socket fd passed by stack  fds: [Ljava.io.FileDescriptor;@2474300f,
03-24 15:31:03.190  5836  9528 E BluetoothRemoteDevices: setRfcommConnected true
03-24 15:31:03.190 11146 11898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onSocketConnected: [<no peer name> F8:CF:C5:D9:E5:61] (thread ID: 1558)
03-24 15:31:03.190 11146 11898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 1558)
,03-24 15:31:03.195 11146 11887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection accepted
,03-24 15:31:03.200 11146 11898 D BluetoothSocket: getInputStream(): myUserId = 0
,03-24 15:31:03.205 11146 11898 D BluetoothSocket: getOutputStream(): myUserId = 0,
,03-24 15:31:03.205 11146 11898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesWritten: 15 bytes successfully written (thread ID: 1559)
03-24 15:31:03.205 11146 11898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Outgoing connection initialized (*handshake* thread ID: 1559)
03-24 15:31:03.205 11146 11975 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 1559)
03-24 15:31:03.205 11146 11898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1558)
,03-24 15:31:03.205 11146 11887 D BluetoothSocket: getInputStream(): myUserId = 0
,03-24 15:31:03.210 11146 11887 D BluetoothSocket: getOutputStream(): myUserId = 0
,03-24 15:31:03.210 11146 11887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection initialized (thread ID: 1560)
03-24 15:31:03.210 11146 11887 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@26b7389c, channel: 6, state: LISTENING
03-24 15:31:03.210 11146 11887 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@26b7389c, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2b933596, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@33ead2a5mSocket: android.net.LocalSocket@37c8267a impl:android.net.LocalSocketImpl@384dbe2b fd:FileDescriptor[93]
03-24 15:31:03.210 11146 11887 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@37c8267a impl:android.net.LocalSocketImpl@384dbe2b fd:FileDescriptor[93]
03-24 15:31:03.210 11146 11887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-24 15:31:03.215 11146 11977 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 1560)
03-24 15:31:03.215 11146 11887 D BluetoothSocket: bindListen(): myUserId = 0
03-24 15:31:03.215 11146 11887 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-24 15:31:03.215  5836  5999 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
,03-24 15:31:03.215  5836  5999 D IOP_DB_BT: db_query: result 1
03-24 15:31:03.215  5836  5999 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-24 15:31:03.215 11146 11887 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[113]}
03-24 15:31:03.215 11146 11887 D BluetoothSocket: bindListen(), new LocalSocket 
03-24 15:31:03.215 11146 11887 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-24 15:31:03.215 11146 11887 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@294d4288
,03-24 15:31:03.215  5836  5999 D IOP_DB_BT: db_query: result 1
03-24 15:31:03.215 11146 11887 D BluetoothSocket: channel: 6,
03-24 15:31:03.215 11146 11887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-24 15:31:03.220 11146 11977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesRead: Read 15 bytes successfully (thread ID: 1560)
,03-24 15:31:03.220 11146 11977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Got valid identity from [<no peer name> F8:CF:C5:D9:E5:61]
,03-24 15:31:03.220  5836  5999 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-24 15:31:03.220  5836  5999 D IOP_DB_BT: db_query: result 1
03-24 15:31:03.220  5836  5999 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-24 15:31:03.220  5836  5999 D IOP_DB_BT: db_query: result 1
03-24 15:31:03.225 11146 11977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesWritten: 15 bytes successfully written (thread ID: 1560)
03-24 15:31:03.225 11146 11977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: removeThreadFromList: Removing thread with ID 1560
03-24 15:31:03.225 11146 11977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Handshake thread disposed (thread ID: 1560)
03-24 15:31:03.225 11146 11977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onIncomingConnectionConnected: [<no peer name> F8:CF:C5:D9:E5:61]
,03-24 15:31:03.225 11146 11146 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:CF:C5:D9:E5:61]
03-24 15:31:03.225 11146 11146 I io.jxcore.node.ConnectionHelper: onConnected: Incoming connection to peer [<no peer name> F8:CF:C5:D9:E5:61]
,03-24 15:31:03.225 11146 11146 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:CF:C5:D9:E5:61] updated - the peer count is 2
,03-24 15:31:03.225 11146 11977 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 1560)
03-24 15:31:03.225  5836  5999 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-24 15:31:03.225  5836  5999 D IOP_DB_BT: db_query: result 1
03-24 15:31:03.225  5836  5999 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-24 15:31:03.225  5836  5999 D IOP_DB_BT: db_query: result 1
03-24 15:31:03.230 11146 11975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesRead: Read 15 bytes successfully (thread ID: 1559)
,03-24 15:31:03.230 11146 11975 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Handshake succeeded with [<no peer name> F8:CF:C5:D9:E5:61]
03-24 15:31:03.230 11146 11975 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onHandshakeSucceeded: [<no peer name> F8:CF:C5:D9:E5:61] (thread ID: 1558)
03-24 15:31:03.230 11146 11975 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: handleSuccessfulClientThread: [<no peer name> F8:CF:C5:D9:E5:61] (thread ID: 1558)
03-24 15:31:03.230 11146 11975 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 1559)
,03-24 15:31:03.230 11146 11156 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1192c11f, channel: 6, state: CLOSED
03-24 15:31:03.230 11146 11156 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1587c141, channel: 6, state: CLOSED
03-24 15:31:03.230 11146 11146 D BluetoothSocket: getInputStream(): myUserId = 0
03-24 15:31:03.230 11146 11156 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1011aa0d, channel: 6, state: CLOSED
03-24 15:31:03.230 11146 11156 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1cd8ec3c, channel: 6, state: CLOSED
03-24 15:31:03.230 11146 11156 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@123eeb72, channel: 7, state: CLOSED
,03-24 15:31:03.230 11146 11156 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1962fb6a, channel: 6, state: CLOSED
03-24 15:31:03.230 11146 11156 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3c0e2e6b, channel: 6, state: CLOSED
,03-24 15:31:03.235 11146 11146 D BluetoothSocket: getOutputStream(): myUserId = 0,
,03-24 15:31:03.235 11146 11146 I io.jxcore.node.ConnectionHelper: lowerBleDiscoveryPowerAndStartResetTimer: Lowering the power settings
03-24 15:31:03.235 11146 11146 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 2 -> 0
03-24 15:31:03.235 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 15:31:03.235 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 15:31:03.235 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-24 15:31:03.235 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-24 15:31:03.235 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-24 15:31:03.235 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-24 15:31:03.235 11146 11156 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@33c13662, channel: 6, state: CLOSED
03-24 15:31:03.235 11146 11156 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@652b00a, channel: 6, state: CLOSED
03-24 15:31:03.235 11146 11156 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1a37250, channel: 6, state: CLOSED
,03-24 15:31:03.235  5836  5917 D BtGatt.AdvertiseManager: message : 1
03-24 15:31:03.240  5836  5917 D BtGatt.AdvertiseManager: stop advertise for client 7
03-24 15:31:03.240  5836  5917 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-24 15:31:03.240  5836  5917 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-24 15:31:03.240  5836  5906 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
,03-24 15:31:03.240  5836  5906 D BtGatt.GattService: Client app is not null!
03-24 15:31:03.240 11146 11156 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2d33b68, channel: 6, state: CLOSED
03-24 15:31:03.240  5836  5846 D BtGatt.GattService: unregisterClient() - clientIf=7
,03-24 15:31:03.240 11146 11146 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 15:31:03.240 11146 11146 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 15:31:03.240 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 3, timeout: 0, is connectable: false
03-24 15:31:03.240 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 15:31:03.240 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-24 15:31:03.240 11146 11146 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-24 15:31:03.240 11146 11146 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-24 15:31:03.240 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 15:31:03.240 11146 11146 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 15:31:03.245  5836 11894 D BtGatt.GattService: registerClient() - UUID=c4b544ab-6425-468e-ac13-8402f159af6e
,03-24 15:31:03.285  5836  5999 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
,03-24 15:31:03.285  5836  5999 D IOP_DB_BT: db_query: result 1
,03-24 15:31:03.285  5836  5999 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-24 15:31:03.290  5836  5999 D IOP_DB_BT: db_query: result 1
03-24 15:31:03.290  5836  5906 D BtGatt.GattService: onClientRegistered() - UUID=c4b544ab-6425-468e-ac13-8402f159af6e, clientIf=7
03-24 15:31:03.290 11146 11158 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-24 15:31:03.305  5836  5999 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
,03-24 15:31:03.305  5836  5999 D IOP_DB_BT: db_query: result 1
03-24 15:31:03.305  5836  5999 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
,03-24 15:31:03.305  5836  5999 D IOP_DB_BT: db_query: result 1
,03-24 15:31:03.305  5836  5999 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-24 15:31:03.310  5836  5999 D IOP_DB_BT: db_query: result 1
03-24 15:31:03.310  5836  5999 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
,03-24 15:31:03.310  5836  5999 D IOP_DB_BT: db_query: result 1
03-24 15:31:03.310  5836  5999 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-24 15:31:03.310  5836  5999 D IOP_DB_BT: db_query: result 1
03-24 15:31:03.310  5836  5999 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
,03-24 15:31:03.310  5836  5999 D IOP_DB_BT: db_query: result 1
03-24 15:31:03.310  5836  5999 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
,03-24 15:31:03.310  5836  5999 D IOP_DB_BT: db_query: result 1
,03-24 15:31:03.310  5836  5999 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-24 15:31:03.310  5836  5999 D IOP_DB_BT: db_query: result 1
,03-24 15:31:03.315  5836  5846 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 54
,03-24 15:31:03.315  5836  5917 D BtGatt.AdvertiseManager: message : 0
03-24 15:31:03.315  5836  5917 D BtGatt.AdvertiseManager: number of adv instance running0
03-24 15:31:03.315  5836  5917 D BtGatt.AdvertiseManager: size of list is =0
,03-24 15:31:03.320  5836  5917 D BtGatt.AdvertiseManager: starting advertising
,03-24 15:31:03.320  5836  5917 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-24 15:31:03.320  5836  5906 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0,
,03-24 15:31:03.325  5836  5917 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 15:31:03.325  5836  5906 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
03-24 15:31:03.325  5836  5917 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-24 15:31:03.325  5836  5917 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 0, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,03-24 15:31:03.325 11146 11146 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 15:31:03.325  5836  9528 D BtGatt.GattService: stopScan() - queue size =1
,03-24 15:31:03.330  5836  5926 D BtGatt.ScanManager: filter size is 1
03-24 15:31:03.330  5836  5926 D BtGatt.ScanManager: delete FilterIndex - 15
03-24 15:31:03.330  5836  5935 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-24 15:31:03.330  5836  5906 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-24 15:31:03.330  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-24 15:31:03.330  5836  5926 D BtGatt.ScanManager: stopping BLe Batch
03-24 15:31:03.330 11146 11146 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 15:31:03.330 11146 11146 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 15:31:03.330 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 15:31:03.330 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-24 15:31:03.330 11146 11146 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 15:31:03.330 11146 11146 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-24 15:31:03.330  5836  5906 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-24 15:31:03.330  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-24 15:31:03.335  5836  5926 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-24 15:31:03.335  5836  5906 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-24 15:31:03.335  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-24 15:31:03.335  5836  9528 D BtGatt.GattService: registerClient() - UUID=3794c7b5-9d52-4a5c-b5e4-d029fc313a18
,03-24 15:31:03.380  5836  5906 D BtGatt.GattService: onClientRegistered() - UUID=3794c7b5-9d52-4a5c-b5e4-d029fc313a18, clientIf=6,
03-24 15:31:03.380 11146 11158 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-24 15:31:03.380  5836  5935 D BtGatt.GattService: start scan with filters
,03-24 15:31:03.395  5836  5935 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 67,
03-24 15:31:03.395 11146 11146 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 15:31:03.395 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 15:31:03.395 11146 11146 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 3 -> 1
,03-24 15:31:03.395 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 15:31:03.395 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 15:31:03.395 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-24 15:31:03.395 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-24 15:31:03.395 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-24 15:31:03.395 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500,
03-24 15:31:03.395  5836  5926 D BtGatt.ScanManager: handling starting scan
,03-24 15:31:03.395  5836  5926 D BtGatt.ScanManager: isFilteringSupported
,03-24 15:31:03.395  5836  5926 D BluetoothAdapter: setting StandAloneBleMode
03-24 15:31:03.400  5836  5906 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-24 15:31:03.400  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-24 15:31:03.400  5836  5917 D BtGatt.AdvertiseManager: message : 1
03-24 15:31:03.400  5836  5926 D BtGatt.ScanManager: allow scan with filters
03-24 15:31:03.400  5836  5926 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,03-24 15:31:03.400  5836  5926 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
03-24 15:31:03.405  5836  5917 D BtGatt.AdvertiseManager: stop advertise for client 7
03-24 15:31:03.405  5836  5917 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-24 15:31:03.405  5836  5906 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-24 15:31:03.405  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-24 15:31:03.405  5836  5926 D BtGatt.ScanManager: Starting BLE batch scan
03-24 15:31:03.405  5836  5926 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-24 15:31:03.405  5836  5917 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,03-24 15:31:03.410  5836  5906 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-24 15:31:03.410  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-24 15:31:03.410  5836  5906 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-24 15:31:03.410  5836  5906 D BtGatt.GattService: Client app is not null!
,03-24 15:31:03.410  5836  9528 D BtGatt.GattService: unregisterClient() - clientIf=7
03-24 15:31:03.410  5836  5906 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-24 15:31:03.410  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-24 15:31:03.415 11146 11146 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 15:31:03.415 11146 11146 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-24 15:31:03.415 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
,03-24 15:31:03.415 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 15:31:03.415 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-24 15:31:03.415 11146 11146 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-24 15:31:03.415 11146 11146 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 15:31:03.415 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-24 15:31:03.415 11146 11146 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-24 15:31:03.420  5836  5849 D BtGatt.GattService: registerClient() - UUID=680d8450-eefa-48b5-80e4-23dbf949bc64
,03-24 15:31:03.465  5836  5906 D BtGatt.GattService: onClientRegistered() - UUID=680d8450-eefa-48b5-80e4-23dbf949bc64, clientIf=7
,03-24 15:31:03.465 11146 11158 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-24 15:31:03.490  5836  9528 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 55
,03-24 15:31:03.490  5836  5917 D BtGatt.AdvertiseManager: message : 0
03-24 15:31:03.490  5836  5917 D BtGatt.AdvertiseManager: number of adv instance running0
,03-24 15:31:03.490  5836  5917 D BtGatt.AdvertiseManager: size of list is =0
,03-24 15:31:03.495  5836  5917 D BtGatt.AdvertiseManager: starting advertising
,03-24 15:31:03.495  5836  5917 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-24 15:31:03.500  5836  5906 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-24 15:31:03.500  5836  5917 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 15:31:03.505  5836  5906 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-24 15:31:03.505  5836  5917 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-24 15:31:03.505  5836  5917 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 0, TxPowerLevel: 1, isConnectable: false, Timeout: 0
03-24 15:31:03.505 11146 11146 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 15:31:03.510  5836 11894 D BtGatt.GattService: stopScan() - queue size =1
,03-24 15:31:03.510  5836  5926 D BtGatt.ScanManager: filter size is 1
03-24 15:31:03.510  5836  5926 D BtGatt.ScanManager: delete FilterIndex - 3
03-24 15:31:03.510  5836  5846 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 15:31:03.510  5836  5906 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,03-24 15:31:03.510  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-24 15:31:03.510  5836  5926 D BtGatt.ScanManager: stopping BLe Batch
03-24 15:31:03.515 11146 11146 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 15:31:03.515 11146 11146 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 15:31:03.515 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 15:31:03.515 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 15:31:03.515 11146 11146 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 15:31:03.515 11146 11146 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 15:31:03.515  5836  5906 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-24 15:31:03.515  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-24 15:31:03.515  5836  5926 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-24 15:31:03.520  5836  5906 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-24 15:31:03.520  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-24 15:31:03.520  5836  5846 D BtGatt.GattService: registerClient() - UUID=3786977b-62b5-48b4-8cc4-2a4093ff811a
,03-24 15:31:03.560  5836  5906 D BtGatt.GattService: onClientRegistered() - UUID=3786977b-62b5-48b4-8cc4-2a4093ff811a, clientIf=6
,03-24 15:31:03.560 11146 11158 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-24 15:31:03.560  5836  5849 D BtGatt.GattService: start scan with filters
,03-24 15:31:03.575  5836  5849 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 68
,03-24 15:31:03.575 11146 11146 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 15:31:03.575 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 15:31:03.575 11146 11146 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 2 -> 0
03-24 15:31:03.575 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 15:31:03.575 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 15:31:03.575 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-24 15:31:03.575 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-24 15:31:03.575 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-24 15:31:03.575 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 15:31:03.575  5836  5926 D BtGatt.ScanManager: handling starting scan
03-24 15:31:03.575  5836  5926 D BtGatt.ScanManager: isFilteringSupported
03-24 15:31:03.575  5836  5926 D BluetoothAdapter: setting StandAloneBleMode
,03-24 15:31:03.580  5836  5906 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-24 15:31:03.580  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-24 15:31:03.580  5836  5917 D BtGatt.AdvertiseManager: message : 1
03-24 15:31:03.580  5836  5917 D BtGatt.AdvertiseManager: stop advertise for client 7
,03-24 15:31:03.580  5836  5917 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-24 15:31:03.580  5836  5926 D BtGatt.ScanManager: allow scan with filters
03-24 15:31:03.580  5836  5926 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-24 15:31:03.580  5836  5926 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
03-24 15:31:03.580  5836  5917 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-24 15:31:03.585  5836  5906 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,03-24 15:31:03.585  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-24 15:31:03.585  5836  5926 D BtGatt.ScanManager: Starting BLE batch scan
03-24 15:31:03.585  5836  5926 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-24 15:31:03.585  5836  5906 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-24 15:31:03.585  5836  5906 D BtGatt.GattService: Client app is not null!
,03-24 15:31:03.585  5836  5849 D BtGatt.GattService: unregisterClient() - clientIf=7
,03-24 15:31:03.590 11146 11146 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-24 15:31:03.590 11146 11146 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-24 15:31:03.590 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-24 15:31:03.590 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 15:31:03.590 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-24 15:31:03.590 11146 11146 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-24 15:31:03.590 11146 11146 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 15:31:03.590  5836  5906 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-24 15:31:03.590  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-24 15:31:03.590 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 15:31:03.590 11146 11146 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 15:31:03.590  5836  5906 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-24 15:31:03.590  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-24 15:31:03.600  5836  5846 D BtGatt.GattService: registerClient() - UUID=118e62ce-34ed-4384-a62c-07ea5967dbcc
,03-24 15:31:03.640  5836  5906 D BtGatt.GattService: onClientRegistered() - UUID=118e62ce-34ed-4384-a62c-07ea5967dbcc, clientIf=7
03-24 15:31:03.640 11146 11158 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-24 15:31:03.655  5836  5849 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 56
,03-24 15:31:03.655  5836  5917 D BtGatt.AdvertiseManager: message : 0
,03-24 15:31:03.655  5836  5917 D BtGatt.AdvertiseManager: number of adv instance running0
03-24 15:31:03.655  5836  5917 D BtGatt.AdvertiseManager: size of list is =0
,03-24 15:31:03.660  5836  5917 D BtGatt.AdvertiseManager: starting advertising
03-24 15:31:03.660  5836  5917 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-24 15:31:03.665  5836  5906 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-24 15:31:03.665  5836  5917 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 15:31:03.670  5836  5906 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-24 15:31:03.670  5836  5917 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,03-24 15:31:03.670  5836  5917 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 0, TxPowerLevel: 1, isConnectable: false, Timeout: 0
,03-24 15:31:03.670 11146 11146 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-24 15:31:03.675  5836  9528 D BtGatt.GattService: stopScan() - queue size =1
03-24 15:31:03.675  5836  5926 D BtGatt.ScanManager: filter size is 1
03-24 15:31:03.675  5836  5926 D BtGatt.ScanManager: delete FilterIndex - 4
03-24 15:31:03.675  5836 11894 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-24 15:31:03.675 11146 11146 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 15:31:03.675 11146 11146 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 15:31:03.675 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 15:31:03.675 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-24 15:31:03.675 11146 11146 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true,
03-24 15:31:03.675 11146 11146 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-24 15:31:03.680  5836  5906 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-24 15:31:03.680  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-24 15:31:03.680  5836  5926 D BtGatt.ScanManager: stopping BLe Batch
03-24 15:31:03.680  5836  5906 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,03-24 15:31:03.680  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-24 15:31:03.680  5836  5926 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-24 15:31:03.685  5836  5906 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-24 15:31:03.685  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-24 15:31:03.685  5836 11894 D BtGatt.GattService: registerClient() - UUID=91d36204-7375-4746-ba33-5b453038506b
,03-24 15:31:03.730  5836  5906 D BtGatt.GattService: onClientRegistered() - UUID=91d36204-7375-4746-ba33-5b453038506b, clientIf=6
,03-24 15:31:03.730 11146 11158 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-24 15:31:03.730  5836  5846 D BtGatt.GattService: start scan with filters
,03-24 15:31:03.740  5836  5846 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 69
,03-24 15:31:03.740 11146 11146 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 15:31:03.740 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 15:31:03.740  5836  5926 D BtGatt.ScanManager: handling starting scan
03-24 15:31:03.740  5836  5926 D BtGatt.ScanManager: isFilteringSupported
03-24 15:31:03.740  5836  5926 D BluetoothAdapter: setting StandAloneBleMode
03-24 15:31:03.740 11146 11146 I io.jxcore.node.ConnectionHelper: onConnected: Incoming socket thread, for peer [<no peer name> F8:CF:C5:D9:E5:61], created successfully
03-24 15:31:03.740 11146 11146 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 1
03-24 15:31:03.740 11146 11146 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:CF:C5:D9:E5:61]
03-24 15:31:03.740 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 15:31:03.740 11146 11146 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,03-24 15:31:03.740 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 15:31:03.740 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 15:31:03.740 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 15:31:03.740 11146 11146 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing connection to peer [<no peer name> F8:CF:C5:D9:E5:61]
03-24 15:31:03.740 11146 11146 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:CF:C5:D9:E5:61] updated - the peer count is 2
03-24 15:31:03.740 11146 11989 D io.jxcore.node.IncomingSocketThread: Entering thread (ID: 1561)
,03-24 15:31:03.740  5836  5906 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-24 15:31:03.740  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-24 15:31:03.740  5836  5926 D BtGatt.ScanManager: allow scan with filters
03-24 15:31:03.740  5836  5926 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-24 15:31:03.740  5836  5926 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,03-24 15:31:03.745  5836  5906 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-24 15:31:03.745  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-24 15:31:03.745  2874  3384 D EnterpriseController: netId is 0
03-24 15:31:03.745  2874  3384 D Netd    : getNetworkForDns: using netid 502 for uid 10011
03-24 15:31:03.745  5836  5926 D BtGatt.ScanManager: Starting BLE batch scan
,03-24 15:31:03.745  5836  5926 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-24 15:31:03.745 11146 11146 D BluetoothSocket: getInputStream(): myUserId = 0
03-24 15:31:03.745  5836  5906 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-24 15:31:03.745  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-24 15:31:03.745 11146 11989 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 54065
,03-24 15:31:03.745 11146 11989 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...,
03-24 15:31:03.745 11146 11989 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-24 15:31:03.745 11146 11989 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-24 15:31:03.745 11146 11989 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 1561)
03-24 15:31:03.745 11146 11989 D io.jxcore.node.IncomingSocketThread: Exiting thread (ID: 1561)
03-24 15:31:03.745  5836  5906 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-24 15:31:03.745  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-24 15:31:03.750 11146 11992 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1564, name: Receiver)
03-24 15:31:03.750 11146 11991 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1563, name: Sender)
,03-24 15:31:03.750 11146 11146 D BluetoothSocket: getOutputStream(): myUserId = 0
03-24 15:31:03.750 11146 11146 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing socket thread, for peer [<no peer name> F8:CF:C5:D9:E5:61], created successfully
03-24 15:31:03.750 11146 11146 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 2
,03-24 15:31:03.755 11146 11993 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1562)
03-24 15:31:03.755 11146 11993 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47015
03-24 15:31:03.755 11146 11993 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
03-24 15:31:03.755 11146 11993 I io.jxcore.node.ConnectionHelper: onListeningForIncomingConnections: Outgoing connection is using port 47015 (peer ID: F8:CF:C5:D9:E5:61)
03-24 15:31:03.755 11146 11993 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "F8:CF:C5:D9:E5:61" removed
03-24 15:31:03.755  5836  5999 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
,03-24 15:31:03.755  5836  5999 D IOP_DB_BT: db_query: result 1
03-24 15:31:03.755  5836  5999 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-24 15:31:03.755  5836  5999 D IOP_DB_BT: db_query: result 1
,03-24 15:31:03.755 11146 11225 I jxcore-log: INFO testThaliMobileNative: 
03-24 15:31:03.755 11146 11225 I jxcore-log: 
,03-24 15:31:03.760 11146 11225 I jxcore-log: INFO testThaliMobileNative: Forward connection
03-24 15:31:03.760 11146 11225 I jxcore-log: 
,03-24 15:31:03.760 11146 11993 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47015
,03-24 15:31:03.760 11146 11993 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
03-24 15:31:03.760 11146 11993 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-24 15:31:03.760 11146 11993 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-24 15:31:03.760 11146 11993 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1562)
03-24 15:31:03.760 11146 11993 D io.jxcore.node.OutgoingSocketThread: Exiting thread (ID: 1562)
,03-24 15:31:03.760 11146 11994 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1565, name: Sender)
03-24 15:31:03.765 11146 11995 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1566, name: Receiver)
03-24 15:31:03.765 11146 11225 I jxcore-log: INFO testThaliMobileNative: forwardSend
03-24 15:31:03.765 11146 11225 I jxcore-log: 
,03-24 15:31:03.765  5836  5999 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
,03-24 15:31:03.765  5836  5999 D IOP_DB_BT: db_query: result 1
03-24 15:31:03.765  5836  5999 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-24 15:31:03.765  5836  5999 D IOP_DB_BT: db_query: result 1
,03-24 15:31:04.305  5836  5999 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61,
,03-24 15:31:04.305  5836  5999 D IOP_DB_BT: db_query: result 1
,03-24 15:31:04.305  5836  5999 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
,03-24 15:31:04.310  5836  5999 D IOP_DB_BT: db_query: result 1,
,03-24 15:31:04.335 11146 11225 I jxcore-log: INFO testThaliMobileNative: forwardData
03-24 15:31:04.335 11146 11225 I jxcore-log: 
,03-24 15:31:04.380  5836  5999 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-24 15:31:04.380  5836  5999 D IOP_DB_BT: db_query: result 1
03-24 15:31:04.380  5836  5999 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-24 15:31:04.380  5836  5999 D IOP_DB_BT: db_query: result 1
,03-24 15:31:04.385 11146 11225 I jxcore-log: INFO testThaliMobileNative: forwardData
03-24 15:31:04.385 11146 11225 I jxcore-log: 
,03-24 15:31:04.455  5836  5999 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-24 15:31:04.455  5836  5999 D IOP_DB_BT: db_query: result 1
03-24 15:31:04.455  5836  5999 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-24 15:31:04.455  5836  5999 D IOP_DB_BT: db_query: result 1
,03-24 15:31:04.470 11146 11225 I jxcore-log: INFO testThaliMobileNative: forwardData
03-24 15:31:04.470 11146 11225 I jxcore-log: 
,03-24 15:31:04.550  5836  5999 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-24 15:31:04.555  5836  5999 D IOP_DB_BT: db_query: result 1
,03-24 15:31:04.555  5836  5999 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61,
,03-24 15:31:04.555  5836  5999 D IOP_DB_BT: db_query: result 1,
,03-24 15:31:04.575 11146 11225 I jxcore-log: INFO testThaliMobileNative: forwardData
03-24 15:31:04.575 11146 11225 I jxcore-log: 
,03-24 15:31:04.620  5836  5999 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
,03-24 15:31:04.625  5836  5999 D IOP_DB_BT: db_query: result 1
03-24 15:31:04.625  5836  5999 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-24 15:31:04.625  5836  5999 D IOP_DB_BT: db_query: result 1
,03-24 15:31:04.640 11146 11225 I jxcore-log: INFO testThaliMobileNative: forwardData
03-24 15:31:04.640 11146 11225 I jxcore-log: 
,03-24 15:31:04.640 11146 11225 I jxcore-log: ok 175 received should match sent forward
03-24 15:31:04.640 11146 11225 I jxcore-log: 
,03-24 15:31:04.655 11146 11225 I jxcore-log: # teardown
03-24 15:31:04.655 11146 11225 I jxcore-log: 
,03-24 15:31:04.750  3390  3620 V AlarmManager: waitForAlarm result :4
,03-24 15:31:04.765  5836  5836 D BtGatt.ScanManager: awakened up at time 299085
,03-24 15:31:04.770  5836  5926 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-24 15:31:04.775  5836  5906 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
03-24 15:31:04.775  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-24 15:31:04.775  5836  5906 D BtGatt.GattService: current time is 299098647992
03-24 15:31:04.775  5836  5906 D BtGatt.GattService: Batch record : [51, 74, 69, 91, 51, 110, 1, -128, -82, 12, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, 62, 23, 49, 75, 90, 110, 1, -128, -68, 11, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0],
03-24 15:31:04.775  5836  5906 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-24 15:31:04.775  5836  5906 D ScanRecord: parseFromBytes,
03-24 15:31:04.775  5836  5906 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97],
03-24 15:31:04.775  5836  5906 D ScanRecord: parseFromBytes
,03-24 15:31:04.775  5836  5906 D BtGatt.GattService: result: ScanResult{mDevice=6E:33:5B:45:4A:33, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-82, mTimestampNanos=298498833784}
03-24 15:31:04.775  5836  5906 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 15:31:04.780  5836  5906 D BtGatt.GattService: result: ScanResult{mDevice=6E:5A:4B:31:17:3E, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-68, mTimestampNanos=298548833784},
03-24 15:31:04.780  5836  5906 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 15:31:04.780 11146 11160 D ScanRecord: parseFromBytes
03-24 15:31:04.780 11146 11160 D ScanRecord: parseFromBytes
03-24 15:31:04.780 11146 11146 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
,03-24 15:31:04.780 11146 11146 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:CF:C5:D9:E5:61] updated - the peer count is 2
,03-24 15:31:05.460 11146 11991 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 1563, thread name: Sender)
03-24 15:31:05.460 11146 11991 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Input stream got -1 on read
03-24 15:31:05.460 11146 11991 W io.jxcore.node.ConnectionHelper: onDisconnected: Incoming connection, peer [<no peer name> F8:CF:C5:D9:E5:61] disconnected: Input stream got -1 on read
03-24 15:31:05.460 11146 11991 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1561
03-24 15:31:05.460 11146 11991 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 1561)
03-24 15:31:05.460 11146 11991 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@f51b15d, channel: 6, state: CONNECTED
03-24 15:31:05.460 11146 11991 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@f51b15d, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@34c10ad2, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@37e9c7a3mSocket: android.net.LocalSocket@146fdaa0 impl:android.net.LocalSocketImpl@3ffd0659 fd:FileDescriptor[92]
03-24 15:31:05.460 11146 11991 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@146fdaa0 impl:android.net.LocalSocketImpl@3ffd0659 fd:FileDescriptor[92]
03-24 15:31:05.460 11146 11992 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 1564, thread name: Receiver): bt socket closed, read return: -1
,03-24 15:31:05.465 11146 11992 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1564, name: Receiver),
,03-24 15:31:05.470 11146 11991 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@f51b15d, channel: 6, state: CLOSED,
,03-24 15:31:05.470 11146 11991 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@f51b15d, channel: 6, state: CLOSED,
,03-24 15:31:05.475 11146 11991 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
,03-24 15:31:05.475 11146 11991 D io.jxcore.node.IncomingSocketThread: close: Stopping receiving thread...
,03-24 15:31:05.475 11146 11991 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 1564
03-24 15:31:05.475 11146 11991 D io.jxcore.node.IncomingSocketThread: close: Stopping sending thread...
03-24 15:31:05.475 11146 11991 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 1563
03-24 15:31:05.475 11146 11991 D io.jxcore.node.IncomingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 1561)
,03-24 15:31:05.480 11146 11991 I io.jxcore.node.IncomingSocketThread: close: Complete (thread ID: 1561)
,03-24 15:31:05.480 11146 11991 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
03-24 15:31:05.480 11146 11991 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1563, name: Sender)
,03-24 15:31:05.485 11146 11225 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 15:31:05.485 11146 11225 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
03-24 15:31:05.485 11146 11225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-24 15:31:05.485 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-24 15:31:05.485  5836  5846 D BtGatt.GattService: stopScan() - queue size =1
,03-24 15:31:05.485  5836  5926 D BtGatt.ScanManager: filter size is 1
,03-24 15:31:05.485  5836  5926 D BtGatt.ScanManager: delete FilterIndex - 5
,03-24 15:31:05.490  5836  5935 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 15:31:05.490  5836  5906 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-24 15:31:05.490  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-24 15:31:05.490 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-24 15:31:05.490 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 15:31:05.490 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 15:31:05.490  5836  5926 D BtGatt.ScanManager: stopping BLe Batch
03-24 15:31:05.490 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-24 15:31:05.490 11146 11225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-24 15:31:05.490 11146 11225 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 15:31:05.490 11146 11146 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-24 15:31:05.490 11146 11146 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-24 15:31:05.490 11146 11146 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 15:31:05.495  5836  5906 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-24 15:31:05.495  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-24 15:31:05.495  5836  5926 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-24 15:31:05.495 11146 11225 I jxcore-log: INFO thaliMobileNativeWrapper: incomingConnectionToPortNumberFailed: %s
03-24 15:31:05.495 11146 11225 I jxcore-log: 
03-24 15:31:05.495 11146 11225 I jxcore-log: INFO thaliMobileNativeWrapper: got incomingConnectionToPortNumberFailed while not in start
03-24 15:31:05.495 11146 11225 I jxcore-log: 
,03-24 15:31:05.495  5836  5906 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
,03-24 15:31:05.495  5836  5906 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-24 15:31:05.495  5836  5906 D BtGatt.GattService: current time is 299819553909
03-24 15:31:05.495  5836  5906 D BtGatt.GattService: Batch record : [62, 23, 49, 75, 90, 110, 1, -128, -71, 6, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0]
03-24 15:31:05.500  5836  5906 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-24 15:31:05.500  5836  5906 D ScanRecord: parseFromBytes
03-24 15:31:05.500 11146 11225 I jxcore-log: ok 176 Should be able to call stopListeningForAdvertisments in teardown
03-24 15:31:05.500 11146 11225 I jxcore-log: 
,03-24 15:31:05.500 11146 11225 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 15:31:05.500 11146 11225 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> F8:CF:C5:D9:E5:61]
03-24 15:31:05.500 11146 11225 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1562)
,03-24 15:31:05.500 11146 11225 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 1562)
03-24 15:31:05.500 11146 11225 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1881021e, channel: 5, state: CONNECTED
,03-24 15:31:05.500 11146 11225 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1881021e, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3ec73aff, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@f0800ccmSocket: android.net.LocalSocket@6eaf15 impl:android.net.LocalSocketImpl@27b7222a fd:FileDescriptor[112]
03-24 15:31:05.500 11146 11225 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@6eaf15 impl:android.net.LocalSocketImpl@27b7222a fd:FileDescriptor[112]
03-24 15:31:05.500 11146 11225 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1881021e, channel: 5, state: CLOSED
03-24 15:31:05.500 11146 11225 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1881021e, channel: 5, state: CLOSED
03-24 15:31:05.500 11146 11225 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
,03-24 15:31:05.500 11146 11995 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 1566, thread name: Receiver): bt socket closed, read return: -1
03-24 15:31:05.500 11146 11225 D io.jxcore.node.OutgoingSocketThread: close: Stopping receiving thread...
03-24 15:31:05.500 11146 11225 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 1566
,03-24 15:31:05.500 11146 11225 D io.jxcore.node.OutgoingSocketThread: close: Stopping sending thread...
03-24 15:31:05.500 11146 11995 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1566, name: Receiver)
03-24 15:31:05.500 11146 11225 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 1565,
03-24 15:31:05.500 11146 11225 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 1562)
03-24 15:31:05.500  5836  5999 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
,03-24 15:31:05.500 11146 11994 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 1565, thread name: Sender): Socket closed
03-24 15:31:05.500 11146 11994 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1565, name: Sender)
03-24 15:31:05.500  5836  5999 D IOP_DB_BT: db_query: result 1
03-24 15:31:05.500  5836  5999 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-24 15:31:05.500  5836  5999 D IOP_DB_BT: db_query: result 1
03-24 15:31:05.505 11146 11225 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1562)
03-24 15:31:05.505 11146 11225 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-24 15:31:05.505 11146 11225 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,03-24 15:31:05.505 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-24 15:31:05.505 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,03-24 15:31:05.505 11146 11225 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@bde881b, channel: 6, state: LISTENING
03-24 15:31:05.505 11146 11225 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@bde881b, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@294d4288, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3b1a5db8mSocket: android.net.LocalSocket@27182791 impl:android.net.LocalSocketImpl@2c7d36f6 fd:FileDescriptor[113]
03-24 15:31:05.505 11146 11225 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@27182791 impl:android.net.LocalSocketImpl@2c7d36f6 fd:FileDescriptor[113]
03-24 15:31:05.505 11146 11225 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-24 15:31:05.505 11146 11887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
,03-24 15:31:05.505 11146 11887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-24 15:31:05.505 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 15:31:05.505 11146 11225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 15:31:05.505 11146 11887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,03-24 15:31:05.505 11146 11225 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 15:31:05.505 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 15:31:05.505 11146 11146 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-24 15:31:05.505 11146 11146 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-24 15:31:05.505 11146 11146 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-24 15:31:05.505 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 15:31:05.505 11146 11225 D BluetoothLeScanner: could not find callback wrapper
03-24 15:31:05.505 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 15:31:05.505 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-24 15:31:05.510  5836  5917 D BtGatt.AdvertiseManager: message : 1
03-24 15:31:05.510  5836  5917 D BtGatt.AdvertiseManager: stop advertise for client 7
03-24 15:31:05.510  5836  5917 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-24 15:31:05.510  5836  5917 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-24 15:31:05.510  5836  5906 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-24 15:31:05.510  5836  5906 D BtGatt.GattService: Client app is not null!
03-24 15:31:05.515  5836  5846 D BtGatt.GattService: unregisterClient() - clientIf=7
03-24 15:31:05.515 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-24 15:31:05.515 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 15:31:05.515 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-24 15:31:05.515 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-24 15:31:05.515 11146 11225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-24 15:31:05.515 11146 11225 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 15:31:05.515 11146 11225 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 15:31:05.515 11146 11225 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-24 15:31:05.515 11146 11225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 15:31:05.515 11146 11225 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-24 15:31:05.515 11146 11225 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 15:31:05.515 11146 11146 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-24 15:31:05.515 11146 11146 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 15:31:05.520 11146 11146 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 15:31:05.520 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-24 15:31:05.520 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-24 15:31:05.520 11146 11225 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-24 15:31:05.520 11146 11225 I jxcore-log: 
,03-24 15:31:05.525 11146 11146 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-24 15:31:05.530 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false,
,03-24 15:31:05.535 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0,
03-24 15:31:05.535 11146 11146 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 15:31:05.535 11146 11146 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false,
03-24 15:31:05.535 11146 11146 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 15:31:05.540 11146 11225 I jxcore-log: ok 177 Should be able to call stopAdvertisingAndListening in teardown
03-24 15:31:05.540 11146 11225 I jxcore-log: 
,03-24 15:31:05.545 11146 11225 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 15:31:05.545 11146 11225 I jxcore-log: 
,03-24 15:31:05.545 11146 11225 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 15:31:05.545 11146 11225 I jxcore-log: 
,03-24 15:31:05.550 11146 11225 I jxcore-log: # setup
03-24 15:31:05.550 11146 11225 I jxcore-log: 
,03-24 15:31:05.835  5836  5999 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0x15):jv handle:0x0 not FOUND
03-24 15:31:05.835  5836  5999 E bt-btif : bta_jv_port_mgmt_sr_cback, p_cb:0x0, p_cb->p_cback0x0
,03-24 15:31:05.840  5836  5999 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0x16):jv handle:0x0 not FOUND,
,03-24 15:31:07.450  5836  5999 W bt-rfcomm: rfc_find_lcid_mcb LCID reused LCID:0x49 current:0x0
,03-24 15:31:07.450  5836  5999 W bt-rfcomm: RFCOMM_DisconnectInd LCID:0x49,
,03-24 15:31:08.510 11146 11225 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 15:31:08.510 11146 11225 I jxcore-log: 
,03-24 15:31:08.515 11146 11225 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 15:31:08.515 11146 11225 I jxcore-log: 
,03-24 15:31:08.525 11146 11225 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 15:31:08.525 11146 11225 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 15:31:08.525 11146 11225 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 15:31:08.525 11146 11225 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 15:31:08.525 11146 11225 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 15:31:08.525 11146 11225 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 15:31:08.525 11146 11225 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 15:31:08.525 11146 11225 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 15:31:08.530 11146 11225 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 15:31:08.535 11146 11225 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 15:31:08.535 11146 11225 I jxcore-log: 
,03-24 15:31:08.535 11146 11225 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 15:31:08.535 11146 11225 I jxcore-log: 
,03-24 15:31:08.545 11146 11225 I jxcore-log: # 40. #startListeningForAdvertisements should fail if start not called
03-24 15:31:08.545 11146 11225 I jxcore-log: 
,03-24 15:31:08.550 11146 11225 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 15:31:08.550 11146 11225 I jxcore-log: 
,03-24 15:31:09.395 11146 11225 I jxcore-log: ok 178 specific error should be returned
03-24 15:31:09.395 11146 11225 I jxcore-log: 
,03-24 15:31:09.400 11146 11225 I jxcore-log: # teardown
03-24 15:31:09.400 11146 11225 I jxcore-log: 
,03-24 15:31:11.500  5836  5999 E bt-btm  : Reset sec_bd_name and name flag. (BR/EDR link)
03-24 15:31:11.500  5836  5999 E bt-btm  : btm_sec_disconnected - Clearing Pending flag
03-24 15:31:11.500  5836  5999 W bt-btif : bta_dm_acl_change(), event : 1
03-24 15:31:11.500  5836  5999 W bt-btif : bta_dm_acl_change(), event : 2
,03-24 15:31:11.500  5836  5906 E BluetoothRemoteDevices: aclStateChangeCallback: State:DisConnected to Device:F8:CF:C5:D9:E5:XX
03-24 15:31:11.525  5836  5906 D BluetoothUtils: getBtEnabledContainers(): btContainers = [],
03-24 15:31:11.525  3727  3727 D KeyguardViewMediator: Received android.bluetooth.device.action.ACL_DISCONNECTED
,03-24 15:31:11.535  3390  3390 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive,
03-24 15:31:11.535  3390  3390 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.device.action.ACL_DISCONNECTED
03-24 15:31:11.535  3390  3390 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_ACL_DISCONNECTED
,03-24 15:31:11.545  3390  3572 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a0b77eb u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{15b2ca6 5836:com.android.bluetooth/1002}
,03-24 15:31:11.550  3390  4257 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
,03-24 15:31:11.555  5836  5836 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@201846a0
03-24 15:31:11.555  5836  5836 D BtConfig.SecureMode: isSecureModeOn:false
03-24 15:31:11.555  3390  3832 D SecContentProvider: query(), uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,03-24 15:31:11.555  3727  3727 D KeyguardViewMediator: isGear1: device is not B1!
,03-24 15:31:11.560  3390  4028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,03-24 15:31:11.565  5836  5836 I BluetoothPbapService: action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,03-24 15:31:11.570 10341 12022 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.ACL_DISCONNECTED State = -2147483648 Previous = -2147483648
,03-24 15:31:11.575  3390  4045 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a0b77eb u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{464c6e8 11836:com.sec.android.app.shealth/u0a36}
,03-24 15:31:11.585 10341 10341 D [CarModeFW]: ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED
03-24 15:31:11.585 10341 10341 D [CarModeFW]: ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED onNotifyBluetoothDeviceDisconnected
,03-24 15:31:11.585 10341 10341 D [CarModeFW]: ConnectivityManager-Paired Devices list is empty
03-24 15:31:11.585 10341 10341 E [CarMode]: [BluetoothConnectivityListener]-onNotifyBluetoothProfileDisconnected: Unexpected error: Invalid device
,03-24 15:31:11.590  3390  4257 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a0b77eb u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{464c6e8 11836:com.sec.android.app.shealth/u0a36}
,03-24 15:31:11.600  3390  3832 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a0b77eb u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{464c6e8 11836:com.sec.android.app.shealth/u0a36}
,03-24 15:31:11.610  3390  4710 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a0b77eb u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{2fc8d8b1 4128:com.google.android.googlequicksearchbox:search/u0a64}
,03-24 15:31:11.615  4128  4128 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,03-24 15:31:11.620  4128  4128 I BluetoothClassifier: Bluetooth Device Name: Nexus 6
,03-24 15:31:11.930  3390  6051 D SSRM:n  : SIOP:: AP = 280, PST = 281 (W:14), CUR = 41, LCD = 0
,03-24 15:31:12.270  3390  4268 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:31:12.275  3390  4268 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:31:12.275  3390  4268 D BatteryService: online:4, current avg:40, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:35
,03-24 15:31:12.275  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-24 15:31:12.275  3390  4268 D BatteryService: stay LED for fully charged
,03-24 15:31:12.285  3390  3390 I MotionRecognitionService: Plugged
03-24 15:31:12.285  3390  3390 D MotionRecognitionService:   cableConnection= 1,
03-24 15:31:12.285  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-24 15:31:12.285  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:31:12.295  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:31:12.295  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:31:12.295  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:31:12.305  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-24 15:31:12.305  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:31:12.320  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:31:12.320  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:31:12.320  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:31:12.320  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:31:12.420  5836  5999 W bt-btif : dm_pm_timer expires
03-24 15:31:12.420  5836  5999 W bt-btif : dm_pm_timer expires 0
03-24 15:31:12.420  5836  5999 W bt-btif : proc dm_pm_timer expires
,03-24 15:31:15.495  3390  6082 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-24 15:31:15.990  3390  3609 D TimaService: TIMA: TimaService scheduler is intialized. 
03-24 15:31:15.990  3390  3609 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,03-24 15:31:15.995  3390  3608 D TimaService: TimaServiceHandler.handleMessage what =1
,03-24 15:31:15.995  3390  3609 I TLC_TIMA_PKM_initialize: initializing...
,03-24 15:31:16.000  3390  3609 I TLC_TIMA_PKM_initialize: root = 0, root_strlen = 1
03-24 15:31:16.000  3390  3609 I TLC_TIMA_PKM_initialize: process = ffffffff00000000000000000000000a, process_strlen = 32
03-24 15:31:16.000  3390  3609 I TZ: mc_tlc_communication: input max_sendmsg_size = 262196
03-24 15:31:16.000  3390  3609 I TZ: mc_tlc_communication: input max_recvmsg_size = 262196
03-24 15:31:16.000  3390  3609 I TZ: mc_tlc_communication: root = 0, root_len = 1
,03-24 15:31:16.000  3390  3609 I TZ: mc_tlc_communication: process = ffffffff00000000000000000000000a, process_strlen = 32
,03-24 15:31:16.000  3390  3609 I TZ: mc_tlc_communication: aligned max_sendmsg_size = 262208,
,03-24 15:31:16.000  3390  3609 I TZ: mc_tlc_communication: aligned max_recvmsg_size = 262208
03-24 15:31:16.000  3390  3609 I TZ: mc_tlc_communication: device_id = 0x0
03-24 15:31:16.000  3390  3609 I TZ: mc_tlc_communication: tlc_open() was called
03-24 15:31:16.000  3390  3609 I TZ: mc_tlc_communication: Opening MobiCore device
,03-24 15:31:16.010  3390  3609 I TZ: mc_tlc_communication: Allocating message buffer for TCI,
,03-24 15:31:16.015  3390  3609 I TZ: mc_tlc_communication: Opening the session
,03-24 15:31:16.030 11146 11225 I jxcore-log: # setup
03-24 15:31:16.030 11146 11225 I jxcore-log: 
,03-24 15:31:16.035  3390  3609 I TZ: mc_tlc_communication: tlc_open() succeeded
,03-24 15:31:16.040  3390  3609 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,03-24 15:31:18.355  3390  3864 E Watchdog: !@Sync 10 [03-24 15:31:18.358]
,03-24 15:31:19.645 11146 11146 I io.jxcore.node.ConnectionHelper: restoreDefaultBleDiscoverySettings: Powering the BLE discovery back up
03-24 15:31:19.645 11146 11146 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 0 -> 2
,03-24 15:31:19.650 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:,
03-24 15:31:19.650 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 15:31:19.650 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-24 15:31:19.650 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-24 15:31:19.650 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-24 15:31:19.650 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-24 15:31:19.650 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 1, timeout: 0, is connectable: false,
03-24 15:31:19.650 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 15:31:19.650 11146 11146 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 1 -> 3
,03-24 15:31:19.650 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:,
,03-24 15:31:19.650 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 15:31:19.650 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-24 15:31:19.650 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-24 15:31:19.650 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-24 15:31:19.650 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-24 15:31:19.650 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-24 15:31:19.650 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 15:31:19.650 11146 11146 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 0 -> 2
03-24 15:31:19.665 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 15:31:19.665 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE,
03-24 15:31:19.665 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-24 15:31:19.665 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-24 15:31:19.665 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2,
03-24 15:31:19.665 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500,
,03-24 15:31:19.665 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
,03-24 15:31:19.665 11146 11146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-24 15:31:20.905  3390  3609 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
03-24 15:31:20.905  3390  3609 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,03-24 15:31:20.925  3390  3609 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;,
03-24 15:31:20.925  3390  3609 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,03-24 15:31:21.575  2892  4752 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-24 15:31:21.960  3390  6051 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:16), CUR = 40, LCD = 0
,03-24 15:31:22.410  3390  3425 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:31:22.410  3390  3425 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:31:22.410  3390  3425 D BatteryService: online:4, current avg:41, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:40
,03-24 15:31:22.415  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-24 15:31:22.415  3390  3425 D BatteryService: stay LED for fully charged,
,03-24 15:31:22.430  3390  3390 I MotionRecognitionService: Plugged,
03-24 15:31:22.430  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:31:22.430  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-24 15:31:22.430  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:31:22.440  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:31:22.440  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:31:22.440  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:31:22.445  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:31:22.450  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-24 15:31:22.450  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:31:22.465  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:31:22.465  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:31:22.465  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:31:31.985  3390  6051 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:16), CUR = 41, LCD = 0
,03-24 15:31:32.560  3390  4257 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:31:32.565  3390  4257 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:31:32.565  3390  4257 D BatteryService: online:4, current avg:39, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:54
,03-24 15:31:32.565  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-24 15:31:32.565  3390  4257 D BatteryService: stay LED for fully charged
,03-24 15:31:32.575  3390  3390 I MotionRecognitionService: Plugged
03-24 15:31:32.575  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:31:32.575  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
03-24 15:31:32.575  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:31:32.580  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:31:32.580  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:31:32.580  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:31:32.600  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-24 15:31:32.600  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:31:32.610  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:31:32.610  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:31:32.610  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:31:32.610  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:31:34.040 11146 11225 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 15:31:34.040 11146 11225 I jxcore-log: 
,03-24 15:31:34.045 11146 11225 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 15:31:34.045 11146 11225 I jxcore-log: 
,03-24 15:31:34.055 11146 11225 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 15:31:34.055 11146 11225 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 15:31:34.055 11146 11225 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 15:31:34.055 11146 11225 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 15:31:34.055 11146 11225 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 15:31:34.055 11146 11225 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 15:31:34.055 11146 11225 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 15:31:34.055 11146 11225 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 15:31:34.055 11146 11225 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 15:31:34.060 11146 11225 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 15:31:34.060 11146 11225 I jxcore-log: 
,03-24 15:31:34.065 11146 11225 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 15:31:34.065 11146 11225 I jxcore-log: 
,03-24 15:31:34.065 11146 11225 I jxcore-log: # 41. #startUpdateAdvertisingAndListening should fail if start not called
03-24 15:31:34.065 11146 11225 I jxcore-log: 
,03-24 15:31:34.070 11146 11225 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 15:31:34.070 11146 11225 I jxcore-log: 
,03-24 15:31:35.500  3390  6082 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-24 15:31:42.015  3390  6051 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:16), CUR = 39, LCD = 0
,03-24 15:31:42.700  3390  4045 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:31:42.700  3390  4045 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:31:42.700  3390  4045 D BatteryService: online:4, current avg:37, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:33
,03-24 15:31:42.705  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-24 15:31:42.715  3390  3390 I MotionRecognitionService: Plugged
03-24 15:31:42.715  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:31:42.720  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-24 15:31:42.720  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
03-24 15:31:42.720  3390  4045 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 17ms
03-24 15:31:42.720  3390  4045 D BatteryService: stay LED for fully charged
,03-24 15:31:42.730  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:31:42.730  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:31:42.730  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:31:42.740  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-24 15:31:42.740  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:31:42.755  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:31:42.755  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:31:42.755  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:31:42.755  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:31:46.410  3390  3587 I PowerManagerService: [PWL] Off : 275s ago
,03-24 15:31:48.360  3390  3864 E Watchdog: !@Sync 11 [03-24 15:31:48.365]
,03-24 15:31:52.040  3390  6051 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:16), CUR = 37, LCD = 0
,03-24 15:31:52.835  3390  3853 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-24 15:31:52.840  3390  3853 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:31:52.840  3390  3853 D BatteryService: online:4, current avg:38, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
03-24 15:31:52.840  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-24 15:31:52.845  3390  3853 D BatteryService: stay LED for fully charged
,03-24 15:31:52.850  3390  3390 I MotionRecognitionService: Plugged
03-24 15:31:52.850  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:31:52.850  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-24 15:31:52.850  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:31:52.860  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:31:52.860  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:31:52.860  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:31:52.870  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-24 15:31:52.870  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:31:52.885  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:31:52.885  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:31:52.885  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:31:52.885  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:31:55.505  3390  6082 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-24 15:31:59.995  3390  3620 V AlarmManager: waitForAlarm result :8
,03-24 15:32:02.065  3390  6051 D SSRM:n  : SIOP:: AP = 270, PST = 279 (W:18), CUR = 38, LCD = 0
,03-24 15:32:02.980  3390  4268 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-24 15:32:02.980  3390  4268 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:32:02.980  3390  4268 D BatteryService: online:4, current avg:35, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:47
03-24 15:32:02.980  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-24 15:32:02.980  3390  4268 D BatteryService: stay LED for fully charged
,03-24 15:32:02.990  3390  3390 I MotionRecognitionService: Plugged,
03-24 15:32:02.990  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:32:02.990  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-24 15:32:02.990  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:32:02.995  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:32:02.995  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:32:02.995  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:32:03.010  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-24 15:32:03.010  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:32:03.020  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:32:03.020  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:32:03.020  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:32:03.025  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:32:12.095  3390  6051 D SSRM:n  : SIOP:: AP = 270, PST = 277 (W:18), CUR = 35, LCD = 0
,03-24 15:32:13.115  3390  3965 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:32:13.115  3390  3965 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:32:13.115  3390  3965 D BatteryService: online:4, current avg:36, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:33
,03-24 15:32:13.115  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-24 15:32:13.120  3390  3965 D BatteryService: stay LED for fully charged,
,03-24 15:32:13.130  3390  3390 I MotionRecognitionService: Plugged
03-24 15:32:13.130  3390  3390 D MotionRecognitionService:   cableConnection= 1,
03-24 15:32:13.130  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-24 15:32:13.130  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:32:13.140  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:32:13.140  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:32:13.140  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:32:13.160  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-24 15:32:13.160  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:32:13.170  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:32:13.170  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:32:13.170  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:32:13.170  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:32:15.515  3390  6082 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-24 15:32:18.370  3390  3864 E Watchdog: !@Sync 12 [03-24 15:32:18.374]
,03-24 15:32:21.575  2892  4752 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-24 15:32:22.140  3390  6051 D SSRM:n  : SIOP:: AP = 270, PST = 277 (W:18), CUR = 36, LCD = 0
,03-24 15:32:22.225  3390  3413 I art     : Background sticky concurrent mark sweep GC freed 76470(6MB) AllocSpace objects, 153(2MB) LOS objects, 19% free, 32MB/40MB, paused 2.987ms total 108.346ms
,03-24 15:32:23.250  3390  3652 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-24 15:32:23.250  3390  3652 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:32:23.250  3390  3652 D BatteryService: online:4, current avg:34, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,03-24 15:32:23.255  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-24 15:32:23.265  3390  3390 I MotionRecognitionService: Plugged
,03-24 15:32:23.265  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:32:23.265  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
,03-24 15:32:23.265  3390  3390 D MotionRecognitionService: skip setTransmitPower. ,
,03-24 15:32:23.265  3390  3652 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 15ms
03-24 15:32:23.265  3390  3652 D BatteryService: stay LED for fully charged
,03-24 15:32:23.280  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:32:23.280  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:32:23.280  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:32:23.290  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-24 15:32:23.290  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:32:23.305  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:32:23.305  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:32:23.305  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:32:23.305  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:32:32.165  3390  6051 D SSRM:n  : SIOP:: AP = 270, PST = 276 (W:18), CUR = 34, LCD = 0
,03-24 15:32:33.390  3390  4044 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:32:33.390  3390  4044 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:32:33.390  3390  4044 D BatteryService: online:4, current avg:33, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:40
,03-24 15:32:33.390  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-24 15:32:33.405  3390  4044 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 14ms
03-24 15:32:33.405  3390  4044 D BatteryService: stay LED for fully charged,
,03-24 15:32:33.405  3390  3390 I MotionRecognitionService: Plugged
03-24 15:32:33.405  3390  3390 D MotionRecognitionService:   cableConnection= 1,
03-24 15:32:33.405  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-24 15:32:33.405  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:32:33.415  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:32:33.415  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:32:33.415  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:32:33.425  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-24 15:32:33.425  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:32:33.430  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:32:33.430  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:32:33.440  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:32:33.440  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:32:35.520  3390  6082 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-24 15:32:41.415  3390  3587 I PowerManagerService: [PWL] Off : 330s ago
,03-24 15:32:42.195  3390  6051 D SSRM:n  : SIOP:: AP = 270, PST = 276 (W:20), CUR = 33, LCD = 0
,03-24 15:32:43.525  3390  3429 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:32:43.525  3390  3429 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:32:43.525  3390  3429 D BatteryService: online:4, current avg:32, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
,03-24 15:32:43.530  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-24 15:32:43.530  3390  3429 D BatteryService: stay LED for fully charged
,03-24 15:32:43.535  3390  3390 I MotionRecognitionService: Plugged,
03-24 15:32:43.540  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:32:43.540  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-24 15:32:43.540  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:32:43.550  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:32:43.550  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:32:43.550  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:32:43.560  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-24 15:32:43.560  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:32:43.575  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:32:43.575  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:32:43.575  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:32:43.575  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:32:48.380  3390  3864 E Watchdog: !@Sync 13 [03-24 15:32:48.381]
,03-24 15:32:52.220  3390  6051 D SSRM:n  : SIOP:: AP = 270, PST = 275 (W:20), CUR = 32, LCD = 0
,03-24 15:32:53.670  3390  4709 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:32:53.670  3390  4709 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:32:53.670  3390  4709 D BatteryService: online:4, current avg:33, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:28
03-24 15:32:53.670  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-24 15:32:53.670  3390  4709 D BatteryService: stay LED for fully charged
,03-24 15:32:53.680  3390  3390 I MotionRecognitionService: Plugged
03-24 15:32:53.680  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:32:53.680  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-24 15:32:53.680  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:32:53.685  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:32:53.685  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:32:53.685  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:32:53.695  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-24 15:32:53.700  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:32:53.710  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:32:53.710  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:32:53.710  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:32:53.710  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:32:55.525  3390  6082 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-24 15:33:02.245  3390  6051 D SSRM:n  : SIOP:: AP = 270, PST = 274 (W:20), CUR = 33, LCD = 0
,03-24 15:33:03.805  3390  4259 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:33:03.805  3390  4259 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:33:03.805  3390  4259 D BatteryService: online:4, current avg:32, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,03-24 15:33:03.810  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-24 15:33:03.820  3390  4259 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 11ms
03-24 15:33:03.820  3390  4259 D BatteryService: stay LED for fully charged,
,03-24 15:33:03.820  3390  3390 I MotionRecognitionService: Plugged
03-24 15:33:03.820  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:33:03.820  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
03-24 15:33:03.820  3390  3390 D MotionRecognitionService: skip setTransmitPower. ,
,03-24 15:33:03.835  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:33:03.835  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:33:03.835  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:33:03.855  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-24 15:33:03.855  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:33:03.865  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:33:03.865  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:33:03.865  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:33:03.865  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:33:04.375 11146 11225 I jxcore-log: Disconnected from the test server
03-24 15:33:04.375 11146 11225 I jxcore-log: 
,03-24 15:33:05.535 11146 11225 I jxcore-log: Reconnected to the test server
03-24 15:33:05.535 11146 11225 I jxcore-log: 
,03-24 15:33:12.275  3390  6051 D SSRM:n  : SIOP:: AP = 270, PST = 274 (W:20), CUR = 32, LCD = 0
,03-24 15:33:13.935  3390  4045 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:33:13.940  3390  4045 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:33:13.940  3390  4045 D BatteryService: online:4, current avg:32, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:36
,03-24 15:33:13.940  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-24 15:33:13.940  3390  4045 D BatteryService: stay LED for fully charged
,03-24 15:33:13.945  3390  3390 I MotionRecognitionService: Plugged
03-24 15:33:13.945  3390  3390 D MotionRecognitionService:   cableConnection= 1,
03-24 15:33:13.945  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-24 15:33:13.945  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:33:13.955  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:33:13.955  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:33:13.960  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:33:13.980  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-24 15:33:13.980  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:33:13.990  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:33:13.990  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:33:13.990  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:33:13.990  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:33:15.530  3390  6082 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-24 15:33:18.385  3390  3864 E Watchdog: !@Sync 14 [03-24 15:33:18.389]
,03-24 15:33:21.575  2892  4752 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-24 15:33:22.305  3390  6051 D SSRM:n  : SIOP:: AP = 270, PST = 273 (W:22), CUR = 32, LCD = 0
,03-24 15:33:24.080  3390  4259 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:33:24.080  3390  4259 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:33:24.080  3390  4259 D BatteryService: online:4, current avg:32, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
,03-24 15:33:24.080  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-24 15:33:24.090  3390  3390 I MotionRecognitionService: Plugged
03-24 15:33:24.090  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:33:24.090  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-24 15:33:24.090  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:33:24.090  3390  4259 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 13ms,
03-24 15:33:24.090  3390  4259 D BatteryService: stay LED for fully charged
,03-24 15:33:24.100  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:33:24.100  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:33:24.100  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:33:24.120  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-24 15:33:24.120  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:33:24.130  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:33:24.130  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:33:24.130  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:33:24.130  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:33:32.335  3390  6051 D SSRM:n  : SIOP:: AP = 270, PST = 272 (W:22), CUR = 32, LCD = 0
,03-24 15:33:34.215  3390  4045 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:33:34.215  3390  4045 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
,03-24 15:33:34.220  3390  4045 D BatteryService: online:4, current avg:30, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
03-24 15:33:34.220  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-24 15:33:34.225  3390  4045 D BatteryService: stay LED for fully charged
,03-24 15:33:34.230  3390  3390 I MotionRecognitionService: Plugged,
03-24 15:33:34.230  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:33:34.230  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
03-24 15:33:34.230  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:33:34.240  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:33:34.240  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:33:34.240  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:33:34.260  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-24 15:33:34.260  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:33:34.270  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:33:34.275  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:33:34.275  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:33:34.275  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:33:35.535  3390  6082 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,03-24 15:33:41.415  3390  3587 I PowerManagerService: [PWL] Off : 390s ago
,03-24 15:33:42.365  3390  6051 D SSRM:n  : SIOP:: AP = 270, PST = 272 (W:22), CUR = 30, LCD = 0,
,03-24 15:33:44.360  3390  3853 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:33:44.360  3390  3853 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:33:44.360  3390  3853 D BatteryService: online:4, current avg:30, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
,03-24 15:33:44.360  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-24 15:33:44.370  3390  3390 I MotionRecognitionService: Plugged
03-24 15:33:44.370  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:33:44.370  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-24 15:33:44.370  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:33:44.375  3390  3853 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 16ms,
03-24 15:33:44.375  3390  3853 D BatteryService: stay LED for fully charged
,03-24 15:33:44.385  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:33:44.385  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:33:44.385  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:33:44.395  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-24 15:33:44.395  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:33:44.410  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:33:44.410  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:33:44.410  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:33:44.410  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:33:48.395  3390  3864 E Watchdog: !@Sync 15 [03-24 15:33:48.397]
,03-24 15:33:52.395  3390  6051 D SSRM:n  : SIOP:: AP = 270, PST = 271 (W:22), CUR = 30, LCD = 0
,03-24 15:33:54.500  3390  4268 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:33:54.500  3390  4268 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:33:54.500  3390  4268 D BatteryService: online:4, current avg:29, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:28
,03-24 15:33:54.500  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-24 15:33:54.510  3390  3390 I MotionRecognitionService: Plugged
03-24 15:33:54.510  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:33:54.510  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-24 15:33:54.510  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:33:54.515  3390  4268 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 16ms,
03-24 15:33:54.515  3390  4268 D BatteryService: stay LED for fully charged
,03-24 15:33:54.520  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:33:54.520  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:33:54.520  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:33:54.535  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-24 15:33:54.535  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:33:54.545  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:33:54.545  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:33:54.545  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:33:54.545  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:33:55.540  3390  6082 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-24 15:34:02.425  3390  6051 D SSRM:n  : SIOP:: AP = 270, PST = 271 (W:24), CUR = 29, LCD = 0
,03-24 15:34:04.635  3390  3965 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:34:04.635  3390  3965 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:34:04.635  3390  3965 D BatteryService: online:4, current avg:29, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,03-24 15:34:04.640  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-24 15:34:04.650  3390  3390 I MotionRecognitionService: Plugged
03-24 15:34:04.650  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:34:04.650  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
03-24 15:34:04.650  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:34:04.650  3390  3965 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 16ms,
03-24 15:34:04.650  3390  3965 D BatteryService: stay LED for fully charged
,03-24 15:34:04.660  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:34:04.660  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:34:04.660  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:34:04.670  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-24 15:34:04.670  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:34:04.685  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:34:04.685  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:34:04.685  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:34:04.685  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:34:09.745  2908  2908 I bootchecker: bootchecker wake up!!,
,03-24 15:34:12.460  3390  6051 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:24), CUR = 29, LCD = 0
,03-24 15:34:14.780  3390  3652 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:34:14.780  3390  3652 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:34:14.780  3390  3652 D BatteryService: online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:2
03-24 15:34:14.780  3390  3652 D BatteryService: stay LED for fully charged
03-24 15:34:14.780  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-24 15:34:14.785  3390  3390 I MotionRecognitionService: Plugged
,03-24 15:34:14.785  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:34:14.785  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-24 15:34:14.785  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:34:14.795  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:34:14.795  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:34:14.795  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:34:14.805  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-24 15:34:14.805  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:34:14.820  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:34:14.820  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:34:14.820  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:34:14.820  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:34:15.545  3390  6082 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-24 15:34:18.400  3390  3864 E Watchdog: !@Sync 16 [03-24 15:34:18.404]
,03-24 15:34:21.575  2892  4752 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-24 15:34:22.490  3390  6051 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:24), CUR = 28, LCD = 0
,03-24 15:34:24.910  3390  4044 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:34:24.910  3390  4044 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:34:24.910  3390  4044 D BatteryService: online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:32
,03-24 15:34:24.915  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-24 15:34:24.915  3390  4044 D BatteryService: stay LED for fully charged
,03-24 15:34:24.920  3390  3390 I MotionRecognitionService: Plugged,
03-24 15:34:24.920  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:34:24.920  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
03-24 15:34:24.920  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:34:24.930  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:34:24.930  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:34:24.930  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:34:24.955  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-24 15:34:24.955  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:34:24.965  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:34:24.965  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:34:24.965  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:34:24.965  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:34:32.520  3390  6051 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:24), CUR = 28, LCD = 0
,03-24 15:34:35.050  3390  3429 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:34:35.050  3390  3429 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:34:35.050  3390  3429 D BatteryService: online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:28
,03-24 15:34:35.050  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-24 15:34:35.055  3390  3429 D BatteryService: stay LED for fully charged
,03-24 15:34:35.060  3390  3390 I MotionRecognitionService: Plugged
03-24 15:34:35.060  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:34:35.060  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-24 15:34:35.060  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:34:35.070  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:34:35.070  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:34:35.070  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:34:35.085  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-24 15:34:35.090  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:34:35.100  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:34:35.100  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:34:35.100  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:34:35.100  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:34:35.550  3390  6082 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-24 15:34:42.545  3390  6051 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:26), CUR = 28, LCD = 0,
,03-24 15:34:45.185  3390  4028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:34:45.185  3390  4028 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
,03-24 15:34:45.190  3390  4028 D BatteryService: online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:47
03-24 15:34:45.190  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-24 15:34:45.190  3390  4028 D BatteryService: stay LED for fully charged
,03-24 15:34:45.200  3390  3390 I MotionRecognitionService: Plugged
03-24 15:34:45.200  3390  3390 D MotionRecognitionService:   cableConnection= 1,
03-24 15:34:45.200  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-24 15:34:45.200  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:34:45.205  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:34:45.205  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:34:45.205  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:34:45.225  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-24 15:34:45.225  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:34:45.235  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:34:45.235  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:34:45.235  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:34:45.235  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:34:46.415  3390  3587 I PowerManagerService: [PWL] Off : 455s ago
,03-24 15:34:48.410  3390  3864 E Watchdog: !@Sync 17 [03-24 15:34:48.413]
,03-24 15:34:52.580  3390  6051 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:26), CUR = 28, LCD = 0,
,03-24 15:34:55.325  3390  4707 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:34:55.325  3390  4707 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:34:55.325  3390  4707 D BatteryService: online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-2
,03-24 15:34:55.330  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-24 15:34:55.330  3390  4707 D BatteryService: stay LED for fully charged
,03-24 15:34:55.335  3390  3390 I MotionRecognitionService: Plugged
03-24 15:34:55.335  3390  3390 D MotionRecognitionService:   cableConnection= 1,
03-24 15:34:55.335  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-24 15:34:55.335  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:34:55.345  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:34:55.345  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:34:55.345  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:34:55.370  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-24 15:34:55.370  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:34:55.380  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:34:55.380  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:34:55.380  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:34:55.380  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:34:55.555  3390  6082 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-24 15:34:59.995  3390  3620 V AlarmManager: waitForAlarm result :8
03-24 15:34:59.995  3390  3620 V AlarmManager: No more alarm at this time.nowELAPSED=534317 batch.start=795417
,03-24 15:35:00.025  3390  3620 V AlarmManager: waitForAlarm result :8
,03-24 15:35:00.030  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
03-24 15:35:00.030  3727  3727 I PERF    : received broadcast android.intent.action.TIME_TICK
03-24 15:35:00.030  3727  3727 D KeyguardUpdateMonitor: handleTimeUpdate
,03-24 15:35:00.040  3390  3620 V AlarmManager: No more alarm at this time.nowELAPSED=534361 batch.start=594317,
,03-24 15:35:00.045  3727  3727 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,03-24 15:35:00.055  3727  3727 D SecKeyguardClockView: HomeTimezone(): 1
,03-24 15:35:00.065  3727  3727 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-24 15:35:00.065  3727  3727 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,03-24 15:35:00.070  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,03-24 15:35:00.110  3727  3727 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-24 15:35:00.115  3727  3727 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-24 15:35:00.120  3727  3727 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-24 15:35:00.120  3727  3727 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-24 15:35:00.125  3727  3727 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-24 15:35:00.125  3727  3727 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
,03-24 15:35:00.145  3727  3727 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-24 15:35:02.610  3390  6051 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:26), CUR = 27, LCD = 0
,03-24 15:35:05.460  3390  3943 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:35:05.460  3390  3943 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:35:05.460  3390  3943 D BatteryService: online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:21
,03-24 15:35:05.465  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.,
03-24 15:35:05.465  3390  3943 D BatteryService: stay LED for fully charged
03-24 15:35:05.470  3390  3390 I MotionRecognitionService: Plugged,
,03-24 15:35:05.470  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:35:05.470  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-24 15:35:05.470  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:35:05.485  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:35:05.485  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:35:05.485  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:35:05.505  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-24 15:35:05.510  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:35:05.515  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:35:05.515  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:35:05.515  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:35:05.515  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:35:12.635  3390  6051 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:26), CUR = 28, LCD = 0
,03-24 15:35:15.560  3390  6082 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-24 15:35:15.605  3390  3832 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:35:15.605  3390  3832 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:35:15.605  3390  3832 D BatteryService: online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
,03-24 15:35:15.605  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-24 15:35:15.610  3390  3832 D BatteryService: stay LED for fully charged
,03-24 15:35:15.615  3390  3390 I MotionRecognitionService: Plugged,
03-24 15:35:15.615  3390  3390 D MotionRecognitionService:   cableConnection= 1
,03-24 15:35:15.615  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-24 15:35:15.615  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:35:15.625  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:35:15.625  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:35:15.630  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:35:15.640  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:35:15.645  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-24 15:35:15.645  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:35:15.660  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:35:15.660  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:35:15.660  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:35:18.415  3390  3864 E Watchdog: !@Sync 18 [03-24 15:35:18.420]
,03-24 15:35:21.575  2892  4752 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-24 15:35:22.670  3390  6051 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:28), CUR = 27, LCD = 0
,03-24 15:35:25.745  3390  3652 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-24 15:35:25.750  3390  3652 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:35:25.750  3390  3652 D BatteryService: online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:29
03-24 15:35:25.750  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-24 15:35:25.755  3390  3652 D BatteryService: stay LED for fully charged
,03-24 15:35:25.765  3390  3390 I MotionRecognitionService: Plugged
03-24 15:35:25.765  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:35:25.765  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-24 15:35:25.765  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:35:25.775  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:35:25.775  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:35:25.775  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:35:25.785  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-24 15:35:25.785  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:35:25.795  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:35:25.800  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:35:25.800  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:35:25.800  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:35:32.700  3390  6051 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:28), CUR = 27, LCD = 0
,03-24 15:35:35.565  3390  6082 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-24 15:35:35.890  3390  4044 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-24 15:35:35.890  3390  4044 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:35:35.890  3390  4044 D BatteryService: online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
03-24 15:35:35.890  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-24 15:35:35.895  3390  4044 D BatteryService: stay LED for fully charged
,03-24 15:35:35.900  3390  3390 I MotionRecognitionService: Plugged
03-24 15:35:35.900  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:35:35.900  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-24 15:35:35.900  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:35:35.905  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:35:35.905  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:35:35.905  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:35:35.920  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-24 15:35:35.920  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:35:35.930  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:35:35.935  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:35:35.935  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:35:35.935  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:35:42.725  3390  6051 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:28), CUR = 27, LCD = 0
,03-24 15:35:46.025  3390  3429 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:35:46.025  3390  3429 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:35:46.025  3390  3429 D BatteryService: online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
,03-24 15:35:46.030  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-24 15:35:46.030  3390  3429 D BatteryService: stay LED for fully charged,
,03-24 15:35:46.035  3390  3390 I MotionRecognitionService: Plugged
03-24 15:35:46.035  3390  3390 D MotionRecognitionService:   cableConnection= 1,
03-24 15:35:46.035  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-24 15:35:46.035  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:35:46.050  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:35:46.050  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:35:46.050  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:35:46.070  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-24 15:35:46.070  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:35:46.080  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:35:46.080  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:35:46.080  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:35:46.080  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:35:48.425  3390  3864 E Watchdog: !@Sync 19 [03-24 15:35:48.427]
,03-24 15:35:52.755  3390  6051 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:28), CUR = 27, LCD = 0
,03-24 15:35:55.565  3390  6082 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-24 15:35:56.165  3390  4028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:35:56.165  3390  4028 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:35:56.165  3390  4028 D BatteryService: online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
,03-24 15:35:56.165  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-24 15:35:56.165  3390  4028 D BatteryService: stay LED for fully charged
,03-24 15:35:56.175  3390  3390 I MotionRecognitionService: Plugged,
03-24 15:35:56.175  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:35:56.175  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
03-24 15:35:56.175  3390  3390 D MotionRecognitionService: skip setTransmitPower. ,
,03-24 15:35:56.185  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-24 15:35:56.185  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:35:56.185  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:35:56.205  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-24 15:35:56.205  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:35:56.220  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:35:56.220  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:35:56.220  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:35:56.220  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:35:56.415  3390  3587 I PowerManagerService: [PWL] Off : 525s ago
,03-24 15:35:59.995  3390  3620 V AlarmManager: waitForAlarm result :8
,03-24 15:36:02.785  3390  6051 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CUR = 24, LCD = 0
,03-24 15:36:06.300  3390  3853 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:36:06.300  3390  3853 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:36:06.300  3390  3853 D BatteryService: online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:39
,03-24 15:36:06.305  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-24 15:36:06.305  3390  3853 D BatteryService: stay LED for fully charged
,03-24 15:36:06.315  3390  3390 I MotionRecognitionService: Plugged,
03-24 15:36:06.315  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:36:06.315  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-24 15:36:06.315  3390  3390 D MotionRecognitionService: skip setTransmitPower. ,
,03-24 15:36:06.325  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:36:06.325  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:36:06.325  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:36:06.345  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-24 15:36:06.350  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:36:06.355  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:36:06.355  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:36:06.355  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:36:06.355  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:36:12.815  3390  6051 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CUR = 23, LCD = 0
,03-24 15:36:15.570  3390  6082 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-24 15:36:15.990  3390  3609 D TimaService: TIMA: TimaService scheduler is intialized. 
03-24 15:36:15.990  3390  3609 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,03-24 15:36:15.995  3390  3608 D TimaService: TimaServiceHandler.handleMessage what =1
,03-24 15:36:16.450  3390  4257 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:36:16.450  3390  4257 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
,03-24 15:36:16.450  3390  4257 D BatteryService: online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:32
,03-24 15:36:16.455  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-24 15:36:16.465  3390  3390 I MotionRecognitionService: Plugged
03-24 15:36:16.465  3390  3390 D MotionRecognitionService:   cableConnection= 1,
03-24 15:36:16.465  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-24 15:36:16.465  3390  3390 D MotionRecognitionService: skip setTransmitPower. ,
,03-24 15:36:16.465  3390  4257 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 14ms
03-24 15:36:16.480  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:36:16.465  3390  4257 D BatteryService: stay LED for fully charged
03-24 15:36:16.480  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:36:16.480  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:36:16.500  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,03-24 15:36:16.505  5836  5927 D HeadsetStateMachine: Disconnected process message: 10,
,03-24 15:36:16.515  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:36:16.515  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:36:16.515  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:36:16.515  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:36:18.430  3390  3864 E Watchdog: !@Sync 20 [03-24 15:36:18.435]
,03-24 15:36:18.520  3390  3609 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
03-24 15:36:18.520  3390  3609 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,03-24 15:36:18.535  3390  3609 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,03-24 15:36:18.540  3390  3609 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,03-24 15:36:21.575  2892  4752 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-24 15:36:21.600  3390  3581 I ActivityManager: setMaxStartingBackgroundTimer onfinish
03-24 15:36:21.600  3390  3581 I ActivityManager: MaxStartingBackground is set. ( current : 8 )
,03-24 15:36:22.845  3390  6051 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CUR = 24, LCD = 0
,03-24 15:36:26.585  3390  3965 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:36:26.585  3390  3965 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:36:26.585  3390  3965 D BatteryService: online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:34
,03-24 15:36:26.585  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-24 15:36:26.595  3390  3965 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 11ms
03-24 15:36:26.595  3390  3965 D BatteryService: stay LED for fully charged,
03-24 15:36:26.595  3390  3390 I MotionRecognitionService: Plugged
03-24 15:36:26.595  3390  3390 D MotionRecognitionService:   cableConnection= 1
,03-24 15:36:26.595  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
,03-24 15:36:26.595  3390  3390 D MotionRecognitionService: skip setTransmitPower. ,
,03-24 15:36:26.610  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:36:26.610  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:36:26.610  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:36:26.615  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:36:26.620  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-24 15:36:26.620  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:36:26.635  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:36:26.635  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:36:26.635  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:36:32.880  3390  6051 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CUR = 24, LCD = 0
,03-24 15:36:35.580  3390  6082 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-24 15:36:36.720  3390  4259 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:36:36.725  3390  4259 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:36:36.725  3390  4259 D BatteryService: online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
,03-24 15:36:36.725  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-24 15:36:36.735  3390  3390 I MotionRecognitionService: Plugged
03-24 15:36:36.735  3390  3390 D MotionRecognitionService:   cableConnection= 1,
03-24 15:36:36.735  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-24 15:36:36.735  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:36:36.740  3390  4259 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 16ms,
03-24 15:36:36.740  3390  4259 D BatteryService: stay LED for fully charged
,03-24 15:36:36.745  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:36:36.745  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:36:36.745  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:36:36.755  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:36:36.760  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-24 15:36:36.760  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:36:36.770  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:36:36.770  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:36:36.770  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:36:37.005  3390  4045 I ActivityManager: Killing 10201:com.sec.android.app.soundalive/u0a59 (adj 15): emptyCount ##31
,03-24 15:36:42.905  3390  6051 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CUR = 24, LCD = 0
,03-24 15:36:46.860  3390  4707 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:36:46.860  3390  4707 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:36:46.860  3390  4707 D BatteryService: online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
,03-24 15:36:46.865  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-24 15:36:46.875  3390  4707 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 11ms
03-24 15:36:46.875  3390  4707 D BatteryService: stay LED for fully charged
,03-24 15:36:46.875  3390  3390 I MotionRecognitionService: Plugged,
03-24 15:36:46.875  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:36:46.875  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-24 15:36:46.875  3390  3390 D MotionRecognitionService: skip setTransmitPower. ,
,03-24 15:36:46.890  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:36:46.890  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:36:46.890  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:36:46.895  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:36:46.900  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-24 15:36:46.900  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:36:46.915  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:36:46.915  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:36:46.915  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:36:48.445  3390  3864 E Watchdog: !@Sync 21 [03-24 15:36:48.450]
,03-24 15:36:52.930  3390  6051 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CUR = 24, LCD = 0,
,03-24 15:36:57.010  3390  4045 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-24 15:36:57.010  3390  4045 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:36:57.010  3390  4045 D BatteryService: online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:36
03-24 15:36:57.010  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-24 15:36:57.010  3390  4045 D BatteryService: stay LED for fully charged
,03-24 15:36:57.015  3390  3390 I MotionRecognitionService: Plugged,
03-24 15:36:57.015  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:36:57.015  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-24 15:36:57.015  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:36:57.020  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:36:57.020  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:36:57.020  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:36:57.035  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-24 15:36:57.035  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:36:57.045  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:36:57.045  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:36:57.045  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:36:57.045  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:37:02.965  3390  6051 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CUR = 23, LCD = 0
,03-24 15:37:07.135  3390  3429 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:37:07.140  3390  3429 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:37:07.140  3390  3429 D BatteryService: online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
,03-24 15:37:07.140  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-24 15:37:07.140  3390  3429 D BatteryService: stay LED for fully charged
,03-24 15:37:07.145  3390  3390 I MotionRecognitionService: Plugged
03-24 15:37:07.145  3390  3390 D MotionRecognitionService:   cableConnection= 1,
03-24 15:37:07.150  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-24 15:37:07.150  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:37:07.160  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:37:07.160  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:37:07.160  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:37:07.170  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-24 15:37:07.170  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:37:07.185  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:37:07.185  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:37:07.185  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:37:07.185  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:37:11.420  3390  3587 I PowerManagerService: [PWL] Off : 600s ago
,03-24 15:37:12.995  3390  6051 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CUR = 23, LCD = 0,
,03-24 15:37:17.280  3390  4709 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:37:17.280  3390  4709 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:37:17.280  3390  4709 D BatteryService: online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
03-24 15:37:17.280  3390  4709 D BatteryService: stay LED for fully charged
03-24 15:37:17.280  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-24 15:37:17.285  3390  3390 I MotionRecognitionService: Plugged
,03-24 15:37:17.285  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:37:17.285  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-24 15:37:17.285  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:37:17.295  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:37:17.295  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:37:17.295  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:37:17.310  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-24 15:37:17.310  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:37:17.320  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:37:17.320  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:37:17.320  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:37:17.320  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:37:18.455  3390  3864 E Watchdog: !@Sync 22 [03-24 15:37:18.457]
,03-24 15:37:21.575  2892  4752 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-24 15:37:23.030  3390  6051 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CUR = 23, LCD = 0
,03-24 15:37:27.415  3390  3853 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:37:27.415  3390  3853 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:37:27.415  3390  3853 D BatteryService: online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
,03-24 15:37:27.420  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-24 15:37:27.420  3390  3853 D BatteryService: stay LED for fully charged
,03-24 15:37:27.430  3390  3390 I MotionRecognitionService: Plugged,
03-24 15:37:27.430  3390  3390 D MotionRecognitionService:   cableConnection= 1,
,03-24 15:37:27.430  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-24 15:37:27.430  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:37:27.440  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:37:27.440  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:37:27.440  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:37:27.460  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-24 15:37:27.460  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:37:27.470  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:37:27.470  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:37:27.470  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:37:27.470  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:37:33.060  3390  6051 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CUR = 24, LCD = 0
,03-24 15:37:37.550  3390  4257 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-24 15:37:37.555  3390  4257 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:37:37.555  3390  4257 D BatteryService: online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
03-24 15:37:37.555  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-24 15:37:37.560  3390  4257 D BatteryService: stay LED for fully charged
,03-24 15:37:37.565  3390  3390 I MotionRecognitionService: Plugged,
03-24 15:37:37.565  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:37:37.565  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
03-24 15:37:37.565  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:37:37.575  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:37:37.575  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:37:37.575  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-24 15:37:37.600  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-24 15:37:37.600  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:37:37.610  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:37:37.610  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:37:37.610  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:37:37.610  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:37:43.085  3390  6051 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CUR = 23, LCD = 0
,03-24 15:37:47.695  3390  3965 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:37:47.695  3390  3965 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:37:47.695  3390  3965 D BatteryService: online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
,03-24 15:37:47.695  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-24 15:37:47.695  3390  3965 D BatteryService: stay LED for fully charged
,03-24 15:37:47.705  3390  3390 I MotionRecognitionService: Plugged,
03-24 15:37:47.705  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:37:47.705  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-24 15:37:47.705  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:37:47.710  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:37:47.710  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:37:47.710  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:37:47.730  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-24 15:37:47.730  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:37:47.740  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:37:47.740  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:37:47.740  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:37:47.740  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:37:48.460  3390  3864 E Watchdog: !@Sync 23 [03-24 15:37:48.465],
,03-24 15:37:53.110  3390  6051 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CUR = 22, LCD = 0
,03-24 15:37:57.830  3390  4259 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:37:57.835  3390  4259 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:37:57.835  3390  4259 D BatteryService: online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,03-24 15:37:57.835  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-24 15:37:57.840  3390  4259 D BatteryService: stay LED for fully charged
,03-24 15:37:57.845  3390  3390 I MotionRecognitionService: Plugged,
03-24 15:37:57.845  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:37:57.845  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-24 15:37:57.845  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:37:57.855  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:37:57.855  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:37:57.855  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:37:57.875  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-24 15:37:57.875  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:37:57.885  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:37:57.885  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:37:57.885  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:37:57.885  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:38:03.135  3390  6051 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CUR = 22, LCD = 0
,03-24 15:38:07.970  3390  4028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-24 15:38:07.970  3390  4028 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:38:07.970  3390  4028 D BatteryService: online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:28
03-24 15:38:07.975  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-24 15:38:07.975  3390  4028 D BatteryService: stay LED for fully charged
,03-24 15:38:07.985  3390  3390 I MotionRecognitionService: Plugged
03-24 15:38:07.985  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:38:07.985  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-24 15:38:07.985  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:38:07.995  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:38:07.995  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:38:07.995  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:38:08.015  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-24 15:38:08.015  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:38:08.025  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:38:08.025  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:38:08.025  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:38:08.025  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:38:13.165  3390  6051 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CUR = 22, LCD = 0
,03-24 15:38:18.110  3390  4710 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:38:18.110  3390  4710 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:38:18.110  3390  4710 D BatteryService: online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,03-24 15:38:18.115  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-24 15:38:18.120  3390  4710 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 10ms
03-24 15:38:18.120  3390  4710 D BatteryService: stay LED for fully charged,
03-24 15:38:18.125  3390  3390 I MotionRecognitionService: Plugged
03-24 15:38:18.125  3390  3390 D MotionRecognitionService:   cableConnection= 1,
,03-24 15:38:18.125  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-24 15:38:18.125  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:38:18.135  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:38:18.135  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:38:18.135  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-24 15:38:18.155  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-24 15:38:18.155  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:38:18.165  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:38:18.170  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:38:18.170  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:38:18.170  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:38:18.470  3390  3864 E Watchdog: !@Sync 24 [03-24 15:38:18.473]
,03-24 15:38:21.575  2892  4752 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-24 15:38:23.190  3390  6051 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CUR = 22, LCD = 0
,03-24 15:38:28.250  3390  4268 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:38:28.250  3390  4268 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:38:28.250  3390  4268 D BatteryService: online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
,03-24 15:38:28.255  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-24 15:38:28.260  3390  3390 I MotionRecognitionService: Plugged
03-24 15:38:28.260  3390  3390 D MotionRecognitionService:   cableConnection= 1,
03-24 15:38:28.260  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
,03-24 15:38:28.260  3390  3390 D MotionRecognitionService: skip setTransmitPower. ,
03-24 15:38:28.265  3390  4268 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 13ms,
03-24 15:38:28.265  3390  4268 D BatteryService: stay LED for fully charged,
,03-24 15:38:28.275  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:38:28.275  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,03-24 15:38:28.275  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-24 15:38:28.295  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-24 15:38:28.295  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:38:28.305  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:38:28.305  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:38:28.305  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:38:28.305  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:38:31.420  3390  3587 I PowerManagerService: [PWL] Off : 680s ago
,03-24 15:38:33.215  3390  6051 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CUR = 19, LCD = 0
,03-24 15:38:38.390  3390  4707 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:38:38.390  3390  4707 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:38:38.390  3390  4707 D BatteryService: online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,03-24 15:38:38.395  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-24 15:38:38.395  3390  4707 D BatteryService: stay LED for fully charged,
,03-24 15:38:38.400  3390  3390 I MotionRecognitionService: Plugged
03-24 15:38:38.400  3390  3390 D MotionRecognitionService:   cableConnection= 1,
03-24 15:38:38.400  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
03-24 15:38:38.400  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:38:38.415  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:38:38.415  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:38:38.415  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:38:38.425  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-24 15:38:38.425  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:38:38.440  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:38:38.440  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:38:38.440  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:38:38.440  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:38:43.240  3390  6051 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CUR = 21, LCD = 0
,03-24 15:38:48.475  3390  3864 E Watchdog: !@Sync 25 [03-24 15:38:48.480]
,03-24 15:38:48.540  3390  4045 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:38:48.540  3390  4045 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:38:48.540  3390  4045 D BatteryService: online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:7
,03-24 15:38:48.545  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-24 15:38:48.545  3390  4045 D BatteryService: stay LED for fully charged,
,03-24 15:38:48.550  3390  3390 I MotionRecognitionService: Plugged,
03-24 15:38:48.550  3390  3390 D MotionRecognitionService:   cableConnection= 1,
03-24 15:38:48.550  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-24 15:38:48.550  3390  3390 D MotionRecognitionService: skip setTransmitPower. ,
03-24 15:38:48.560  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:38:48.560  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:38:48.560  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:38:48.585  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-24 15:38:48.585  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:38:48.595  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:38:48.595  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:38:48.595  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:38:48.595  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:38:53.270  3390  6051 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CUR = 20, LCD = 0
,03-24 15:38:58.675  3390  3425 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:38:58.675  3390  3425 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:38:58.675  3390  3425 D BatteryService: online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
,03-24 15:38:58.680  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-24 15:38:58.680  3390  3425 D BatteryService: stay LED for fully charged
,03-24 15:38:58.685  3390  3390 I MotionRecognitionService: Plugged
03-24 15:38:58.690  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:38:58.690  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-24 15:38:58.690  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:38:58.695  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:38:58.695  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:38:58.695  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:38:58.715  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-24 15:38:58.715  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:38:58.730  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:38:58.730  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:38:58.730  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:38:58.730  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:39:03.300  3390  6051 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CUR = 19, LCD = 0
,03-24 15:39:08.815  3390  3943 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:39:08.815  3390  3943 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:39:08.815  3390  3943 D BatteryService: online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
,03-24 15:39:08.820  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-24 15:39:08.830  3390  3390 I MotionRecognitionService: Plugged,
03-24 15:39:08.830  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:39:08.830  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
,03-24 15:39:08.830  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:39:08.830  3390  3943 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 12ms,
03-24 15:39:08.830  3390  3943 D BatteryService: stay LED for fully charged,
03-24 15:39:08.840  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:39:08.840  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:39:08.840  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:39:08.865  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-24 15:39:08.865  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:39:08.875  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:39:08.875  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:39:08.875  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:39:08.875  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:39:13.325  3390  6051 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CUR = 20, LCD = 0,
,03-24 15:39:18.480  3390  3864 E Watchdog: !@Sync 26 [03-24 15:39:18.483]
,03-24 15:39:18.955  3390  3832 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:39:18.960  3390  3832 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:39:18.965  3390  3832 D BatteryService: online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:36
,03-24 15:39:18.965  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.,
,03-24 15:39:18.965  3390  3832 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 10ms
,03-24 15:39:18.970  3390  3832 D BatteryService: stay LED for fully charged
,03-24 15:39:18.980  3390  3390 I MotionRecognitionService: Plugged
03-24 15:39:18.980  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:39:18.985  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-24 15:39:18.985  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:39:18.990  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:39:18.990  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:39:18.990  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:39:19.010  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-24 15:39:19.010  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:39:19.020  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:39:19.020  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:39:19.020  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:39:19.020  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:39:19.170  3390  3413 I art     : Background partial concurrent mark sweep GC freed 50217(5MB) AllocSpace objects, 207(3MB) LOS objects, 33% free, 31MB/47MB, paused 2.323ms total 210.244ms
,03-24 15:39:21.095  3390  3620 V AlarmManager: waitForAlarm result :8
,03-24 15:39:21.575  2892  4752 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-24 15:39:23.355  3390  6051 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CUR = 21, LCD = 0
,03-24 15:39:29.095  3390  3652 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:39:29.095  3390  3652 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:39:29.095  3390  3652 D BatteryService: online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
,03-24 15:39:29.100  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-24 15:39:29.105  3390  3390 I MotionRecognitionService: Plugged
03-24 15:39:29.105  3390  3390 D MotionRecognitionService:   cableConnection= 1,
03-24 15:39:29.105  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-24 15:39:29.105  3390  3390 D MotionRecognitionService: skip setTransmitPower. ,
,03-24 15:39:29.110  3390  3652 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 15ms,
03-24 15:39:29.110  3390  3652 D BatteryService: stay LED for fully charged
,03-24 15:39:29.120  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:39:29.120  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:39:29.120  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:39:29.145  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-24 15:39:29.145  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:39:29.150  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:39:29.155  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:39:29.155  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:39:29.155  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:39:33.385  3390  6051 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CUR = 21, LCD = 0
,03-24 15:39:39.235  3390  4044 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:39:39.235  3390  4044 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:39:39.235  3390  4044 D BatteryService: online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:28
,03-24 15:39:39.240  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-24 15:39:39.240  3390  4044 D BatteryService: stay LED for fully charged,
,03-24 15:39:39.250  3390  3390 I MotionRecognitionService: Plugged
03-24 15:39:39.250  3390  3390 D MotionRecognitionService:   cableConnection= 1,
03-24 15:39:39.250  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-24 15:39:39.250  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:39:39.260  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:39:39.260  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:39:39.260  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:39:39.275  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-24 15:39:39.275  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:39:39.290  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:39:39.290  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:39:39.290  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:39:39.290  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:39:43.415  3390  6051 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CUR = 21, LCD = 0
,03-24 15:39:48.490  3390  3864 E Watchdog: !@Sync 27 [03-24 15:39:48.490]
,03-24 15:39:49.370  3390  3429 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-24 15:39:49.370  3390  3429 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:39:49.370  3390  3429 D BatteryService: online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:34
,03-24 15:39:49.375  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-24 15:39:49.380  3390  3429 D BatteryService: stay LED for fully charged
,03-24 15:39:49.385  3390  3390 I MotionRecognitionService: Plugged,
03-24 15:39:49.385  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:39:49.385  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
03-24 15:39:49.385  3390  3390 D MotionRecognitionService: skip setTransmitPower. ,
,03-24 15:39:49.395  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:39:49.395  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:39:49.395  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-24 15:39:49.420  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-24 15:39:49.420  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:39:49.430  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:39:49.430  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:39:49.430  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:39:49.430  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:39:53.440  3390  6051 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CUR = 20, LCD = 0
,03-24 15:39:56.425  3390  3587 I PowerManagerService: [PWL] Off : 765s ago
,03-24 15:39:59.515  3390  4044 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:39:59.515  3390  4044 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:39:59.515  3390  4044 D BatteryService: online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
,03-24 15:39:59.515  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-24 15:39:59.525  3390  3390 I MotionRecognitionService: Plugged
03-24 15:39:59.525  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:39:59.525  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-24 15:39:59.525  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:39:59.525  3390  4044 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 13ms,
03-24 15:39:59.525  3390  4044 D BatteryService: stay LED for fully charged
,03-24 15:39:59.535  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:39:59.535  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:39:59.535  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:39:59.550  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-24 15:39:59.550  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:39:59.565  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:39:59.565  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:39:59.565  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:39:59.570  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:40:03.470  3390  6051 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CUR = 19, LCD = 0
,03-24 15:40:09.650  3390  3429 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:40:09.650  3390  3429 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:40:09.650  3390  3429 D BatteryService: online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
,03-24 15:40:09.655  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-24 15:40:09.655  3390  3429 D BatteryService: stay LED for fully charged,
,03-24 15:40:09.665  3390  3390 I MotionRecognitionService: Plugged
03-24 15:40:09.665  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:40:09.665  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
03-24 15:40:09.665  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:40:09.675  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:40:09.675  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:40:09.675  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:40:09.695  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-24 15:40:09.695  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:40:09.705  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:40:09.705  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:40:09.705  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:40:09.705  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:40:13.495  3390  6051 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CUR = 21, LCD = 0
,03-24 15:40:18.495  3390  3864 E Watchdog: !@Sync 28 [03-24 15:40:18.499]
,03-24 15:40:19.785  3390  4709 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:40:19.790  3390  4709 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:40:19.790  3390  4709 D BatteryService: online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
,03-24 15:40:19.790  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-24 15:40:19.800  3390  3390 I MotionRecognitionService: Plugged
03-24 15:40:19.800  3390  3390 D MotionRecognitionService:   cableConnection= 1
,03-24 15:40:19.800  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-24 15:40:19.800  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:40:19.805  3390  4709 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 18ms,
03-24 15:40:19.805  3390  4709 D BatteryService: stay LED for fully charged,
,03-24 15:40:19.815  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:40:19.815  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:40:19.815  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:40:19.825  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-24 15:40:19.825  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:40:19.840  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:40:19.840  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:40:19.840  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:40:19.840  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:40:21.575  2892  4752 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-24 15:40:23.520  3390  6051 D SSRM:n  : SIOP:: AP = 260, PST = 269 (W:30), CUR = 21, LCD = 0
,03-24 15:40:29.925  3390  3853 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:40:29.925  3390  3853 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:40:29.925  3390  3853 D BatteryService: online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-3
,03-24 15:40:29.925  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-24 15:40:29.935  3390  3853 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 11ms
03-24 15:40:29.935  3390  3853 D BatteryService: stay LED for fully charged
,03-24 15:40:29.940  3390  3390 I MotionRecognitionService: Plugged
03-24 15:40:29.940  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:40:29.940  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-24 15:40:29.940  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:40:29.945  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:40:29.945  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,03-24 15:40:29.945  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:40:29.970  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-24 15:40:29.970  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:40:29.980  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:40:29.980  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:40:29.980  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:40:29.980  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:40:33.550  3390  6051 D SSRM:n  : SIOP:: AP = 260, PST = 269 (W:30), CUR = 17, LCD = 0
,03-24 15:40:40.060  3390  4257 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:40:40.065  3390  4257 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:40:40.065  3390  4257 D BatteryService: online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
,03-24 15:40:40.065  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-24 15:40:40.075  3390  3390 I MotionRecognitionService: Plugged
03-24 15:40:40.075  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:40:40.075  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-24 15:40:40.075  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:40:40.075  3390  4257 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 14ms,
03-24 15:40:40.075  3390  4257 D BatteryService: stay LED for fully charged
,03-24 15:40:40.085  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:40:40.085  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:40:40.085  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-24 15:40:40.100  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-24 15:40:40.100  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:40:40.115  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:40:40.115  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:40:40.115  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:40:40.115  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:40:43.580  3390  6051 D SSRM:n  : SIOP:: AP = 260, PST = 269 (W:30), CUR = 18, LCD = 0
,03-24 15:40:48.505  3390  3864 E Watchdog: !@Sync 29 [03-24 15:40:48.506]
,03-24 15:40:50.200  3390  3965 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:40:50.200  3390  3965 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:40:50.200  3390  3965 D BatteryService: online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:36
,03-24 15:40:50.205  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-24 15:40:50.205  3390  3965 D BatteryService: stay LED for fully charged
,03-24 15:40:50.215  3390  3390 I MotionRecognitionService: Plugged,
,03-24 15:40:50.215  3390  3390 D MotionRecognitionService:   cableConnection= 1
,03-24 15:40:50.215  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
,03-24 15:40:50.215  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:40:50.225  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:40:50.225  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,03-24 15:40:50.225  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-24 15:40:50.245  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-24 15:40:50.245  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:40:50.260  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:40:50.260  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:40:50.260  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:40:50.260  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:40:53.605  3390  6051 D SSRM:n  : SIOP:: AP = 260, PST = 268 (W:30), CUR = 18, LCD = 0
,03-24 15:41:00.345  3390  4259 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:41:00.345  3390  4259 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:41:00.345  3390  4259 D BatteryService: online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
,03-24 15:41:00.345  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-24 15:41:00.355  3390  3390 I MotionRecognitionService: Plugged
03-24 15:41:00.355  3390  3390 D MotionRecognitionService:   cableConnection= 1,
03-24 15:41:00.355  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
03-24 15:41:00.355  3390  3390 D MotionRecognitionService: skip setTransmitPower. ,
03-24 15:41:00.360  3390  4259 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 14ms,
,03-24 15:41:00.360  3390  4259 D BatteryService: stay LED for fully charged
,03-24 15:41:00.365  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:41:00.365  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:41:00.365  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:41:00.385  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-24 15:41:00.385  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:41:00.395  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:41:00.395  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:41:00.395  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:41:00.395  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:41:03.640  3390  6051 D SSRM:n  : SIOP:: AP = 260, PST = 268 (W:30), CUR = 18, LCD = 0
,03-24 15:41:10.480  3390  4028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:41:10.485  3390  4028 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:41:10.485  3390  4028 D BatteryService: online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:36
,03-24 15:41:10.485  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-24 15:41:10.495  3390  3390 I MotionRecognitionService: Plugged
03-24 15:41:10.495  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:41:10.495  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-24 15:41:10.495  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:41:10.495  3390  4028 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 14ms,
03-24 15:41:10.495  3390  4028 D BatteryService: stay LED for fully charged
,03-24 15:41:10.505  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-24 15:41:10.505  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,03-24 15:41:10.505  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:41:10.525  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-24 15:41:10.525  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:41:10.535  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:41:10.535  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:41:10.535  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:41:10.535  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:41:13.665  3390  6051 D SSRM:n  : SIOP:: AP = 260, PST = 268 (W:30), CUR = 18, LCD = 0
,03-24 15:41:15.990  3390  3609 D TimaService: TIMA: TimaService scheduler is intialized. 
03-24 15:41:15.990  3390  3609 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,03-24 15:41:15.995  3390  3608 D TimaService: TimaServiceHandler.handleMessage what =1,
,03-24 15:41:18.510  3390  3864 E Watchdog: !@Sync 30 [03-24 15:41:18.514]
,03-24 15:41:20.640  3390  4710 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:41:20.640  3390  4710 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:41:20.640  3390  4710 D BatteryService: online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
,03-24 15:41:20.640  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-24 15:41:20.640  3390  4710 D BatteryService: stay LED for fully charged
,03-24 15:41:20.650  3390  3390 I MotionRecognitionService: Plugged
03-24 15:41:20.650  3390  3390 D MotionRecognitionService:   cableConnection= 1,
03-24 15:41:20.650  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-24 15:41:20.650  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:41:20.660  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:41:20.660  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:41:20.660  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-24 15:41:20.675  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-24 15:41:20.675  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:41:20.675  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:41:20.695  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:41:20.695  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:41:20.695  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:41:20.860  3390  3609 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
03-24 15:41:20.860  3390  3609 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,03-24 15:41:20.875  3390  3609 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
03-24 15:41:20.875  3390  3609 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,03-24 15:41:21.575  2892  4752 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-24 15:41:23.690  3390  6051 D SSRM:n  : SIOP:: AP = 260, PST = 267 (W:30), CUR = 17, LCD = 0
,03-24 15:41:26.425  3390  3587 I PowerManagerService: [PWL] Off : 855s ago
,03-24 15:41:30.775  3390  4268 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:41:30.775  3390  4268 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
,03-24 15:41:30.780  3390  4268 D BatteryService: online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
03-24 15:41:30.780  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.,
03-24 15:41:30.780  3390  4268 D BatteryService: stay LED for fully charged,
,03-24 15:41:30.790  3390  3390 I MotionRecognitionService: Plugged,
03-24 15:41:30.790  3390  3390 D MotionRecognitionService:   cableConnection= 1,
03-24 15:41:30.790  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-24 15:41:30.790  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:41:30.800  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:41:30.800  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:41:30.800  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-24 15:41:30.820  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-24 15:41:30.820  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:41:30.830  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:41:30.830  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:41:30.830  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:41:30.830  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:41:33.720  3390  6051 D SSRM:n  : SIOP:: AP = 260, PST = 267 (W:30), CUR = 17, LCD = 0
,03-24 15:41:40.915  3390  4707 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:41:40.915  3390  4707 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:41:40.915  3390  4707 D BatteryService: online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
,03-24 15:41:40.920  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-24 15:41:40.920  3390  4707 D BatteryService: stay LED for fully charged,
,03-24 15:41:40.930  3390  3390 I MotionRecognitionService: Plugged
03-24 15:41:40.930  3390  3390 D MotionRecognitionService:   cableConnection= 1,
03-24 15:41:40.930  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-24 15:41:40.930  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:41:40.940  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:41:40.940  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:41:40.940  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:41:40.960  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-24 15:41:40.960  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:41:40.970  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:41:40.970  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:41:40.970  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:41:40.970  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:41:43.750  3390  6051 D SSRM:n  : SIOP:: AP = 260, PST = 267 (W:30), CUR = 16, LCD = 0
,03-24 15:41:48.520  3390  3864 E Watchdog: !@Sync 31 [03-24 15:41:48.525]
,03-24 15:41:51.055  3390  4045 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:41:51.055  3390  4045 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:41:51.055  3390  4045 D BatteryService: online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,03-24 15:41:51.060  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-24 15:41:51.065  3390  4045 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 11ms
,03-24 15:41:51.065  3390  4045 D BatteryService: stay LED for fully charged
03-24 15:41:51.070  3390  3390 I MotionRecognitionService: Plugged,
03-24 15:41:51.070  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:41:51.070  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-24 15:41:51.070  3390  3390 D MotionRecognitionService: skip setTransmitPower. ,
,03-24 15:41:51.080  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-24 15:41:51.080  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,03-24 15:41:51.080  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-24 15:41:51.105  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-24 15:41:51.105  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:41:51.110  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:41:51.115  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:41:51.115  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:41:51.115  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:41:53.775  3390  6051 D SSRM:n  : SIOP:: AP = 260, PST = 266 (W:30), CUR = 16, LCD = 0
,03-24 15:42:01.195  3390  3425 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:42:01.195  3390  3425 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4400, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:42:01.195  3390  3425 D BatteryService: online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:40
,03-24 15:42:01.195  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-24 15:42:01.200  3390  3425 D BatteryService: stay LED for fully charged
,03-24 15:42:01.205  3390  3390 I MotionRecognitionService: Plugged
03-24 15:42:01.205  3390  3390 D MotionRecognitionService:   cableConnection= 1,
03-24 15:42:01.205  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-24 15:42:01.205  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:42:01.215  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:42:01.215  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:42:01.215  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:42:01.230  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:42:01.230  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-24 15:42:01.230  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:42:01.230  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:42:01.235  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:42:01.245  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:42:03.810  3390  6051 D SSRM:n  : SIOP:: AP = 260, PST = 266 (W:30), CUR = 16, LCD = 0
,03-24 15:42:11.330  3390  3943 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:42:11.330  3390  3943 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:42:11.330  3390  3943 D BatteryService: online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
03-24 15:42:11.330  3390  3943 D BatteryService: stay LED for fully charged
,03-24 15:42:11.330  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-24 15:42:11.340  3390  3390 I MotionRecognitionService: Plugged
03-24 15:42:11.340  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:42:11.340  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-24 15:42:11.340  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:42:11.345  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:42:11.345  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:42:11.345  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:42:11.360  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-24 15:42:11.360  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:42:11.370  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:42:11.370  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:42:11.370  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:42:11.370  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:42:13.835  3390  6051 D SSRM:n  : SIOP:: AP = 260, PST = 266 (W:30), CUR = 16, LCD = 0
,03-24 15:42:18.530  3390  3864 E Watchdog: !@Sync 32 [03-24 15:42:18.532]
,03-24 15:42:21.475  3390  3832 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:42:21.475  3390  3832 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:42:21.475  3390  3832 D BatteryService: online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,03-24 15:42:21.475  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-24 15:42:21.475  3390  3832 D BatteryService: stay LED for fully charged
,03-24 15:42:21.485  3390  3390 I MotionRecognitionService: Plugged,
03-24 15:42:21.485  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:42:21.485  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
03-24 15:42:21.485  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:42:21.495  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:42:21.495  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:42:21.495  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:42:21.505  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-24 15:42:21.505  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:42:21.520  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:42:21.520  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:42:21.520  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:42:21.520  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:42:21.575  2892  4752 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-24 15:42:23.865  3390  6051 D SSRM:n  : SIOP:: AP = 260, PST = 265 (W:30), CUR = 16, LCD = 0
,03-24 15:42:31.610  3390  3652 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:42:31.610  3390  3652 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:42:31.610  3390  3652 D BatteryService: online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:21
,03-24 15:42:31.610  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-24 15:42:31.625  3390  3390 I MotionRecognitionService: Plugged
03-24 15:42:31.625  3390  3390 D MotionRecognitionService:   cableConnection= 1
,03-24 15:42:31.625  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-24 15:42:31.625  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:42:31.625  3390  3652 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 16ms,
03-24 15:42:31.625  3390  3652 D BatteryService: stay LED for fully charged
,03-24 15:42:31.635  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:42:31.635  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:42:31.635  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:42:31.645  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-24 15:42:31.645  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:42:31.660  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:42:31.660  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:42:31.660  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:42:31.660  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:42:33.895  3390  6051 D SSRM:n  : SIOP:: AP = 260, PST = 265 (W:30), CUR = 15, LCD = 0
,03-24 15:42:41.750  3390  4044 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:42:41.750  3390  4044 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:42:41.750  3390  4044 D BatteryService: online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
,03-24 15:42:41.750  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-24 15:42:41.755  3390  4044 D BatteryService: stay LED for fully charged
,03-24 15:42:41.760  3390  3390 I MotionRecognitionService: Plugged,
03-24 15:42:41.760  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:42:41.760  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-24 15:42:41.760  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:42:41.770  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:42:41.770  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:42:41.770  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:42:41.790  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-24 15:42:41.790  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:42:41.805  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:42:41.805  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:42:41.805  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:42:41.805  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:42:43.930  3390  6051 D SSRM:n  : SIOP:: AP = 260, PST = 265 (W:30), CUR = 16, LCD = 0
,03-24 15:42:48.535  3390  3864 E Watchdog: !@Sync 33 [03-24 15:42:48.540]
,03-24 15:42:51.885  3390  3429 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:42:51.885  3390  3429 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:42:51.885  3390  3429 D BatteryService: online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,03-24 15:42:51.890  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-24 15:42:51.890  3390  3429 D BatteryService: stay LED for fully charged
,03-24 15:42:51.895  3390  3390 I MotionRecognitionService: Plugged,
03-24 15:42:51.895  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:42:51.895  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-24 15:42:51.895  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:42:51.905  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:42:51.905  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:42:51.905  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:42:51.925  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-24 15:42:51.925  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:42:51.935  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:42:51.935  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:42:51.935  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:42:51.935  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:42:53.955  3390  6051 D SSRM:n  : SIOP:: AP = 260, PST = 264 (W:30), CUR = 15, LCD = 0
,03-24 15:43:01.435  3390  3587 I PowerManagerService: [PWL] Off : 950s ago
,03-24 15:43:02.025  3390  4709 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:43:02.025  3390  4709 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:43:02.025  3390  4709 D BatteryService: online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:36
,03-24 15:43:02.030  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-24 15:43:02.035  3390  4709 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 11ms
03-24 15:43:02.035  3390  4709 D BatteryService: stay LED for fully charged
,03-24 15:43:02.040  3390  3390 I MotionRecognitionService: Plugged
03-24 15:43:02.040  3390  3390 D MotionRecognitionService:   cableConnection= 1,
03-24 15:43:02.040  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-24 15:43:02.040  3390  3390 D MotionRecognitionService: skip setTransmitPower. ,
,03-24 15:43:02.050  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-24 15:43:02.050  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:43:02.050  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-24 15:43:02.070  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-24 15:43:02.070  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:43:02.080  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:43:02.080  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:43:02.080  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:43:02.080  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:43:03.985  3390  6051 D SSRM:n  : SIOP:: AP = 260, PST = 264 (W:30), CUR = 15, LCD = 0
,03-24 15:43:12.165  3390  3853 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:43:12.165  3390  3853 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:43:12.165  3390  3853 D BatteryService: online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,03-24 15:43:12.165  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-24 15:43:12.175  3390  3390 I MotionRecognitionService: Plugged
03-24 15:43:12.175  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:43:12.175  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-24 15:43:12.175  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:43:12.180  3390  3853 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 14ms,
03-24 15:43:12.180  3390  3853 D BatteryService: stay LED for fully charged
,03-24 15:43:12.185  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:43:12.185  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:43:12.185  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:43:12.210  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-24 15:43:12.210  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:43:12.220  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:43:12.220  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:43:12.220  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:43:12.220  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:43:14.010  3390  6051 D SSRM:n  : SIOP:: AP = 260, PST = 264 (W:30), CUR = 15, LCD = 0
,03-24 15:43:18.545  3390  3864 E Watchdog: !@Sync 34 [03-24 15:43:18.548]
,03-24 15:43:21.575  2892  4752 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-24 15:43:22.300  3390  4257 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:43:22.300  3390  4257 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:43:22.300  3390  4257 D BatteryService: online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
,03-24 15:43:22.305  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-24 15:43:22.305  3390  4257 D BatteryService: stay LED for fully charged
,03-24 15:43:22.310  3390  3390 I MotionRecognitionService: Plugged
03-24 15:43:22.310  3390  3390 D MotionRecognitionService:   cableConnection= 1,
03-24 15:43:22.310  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-24 15:43:22.310  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:43:22.320  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:43:22.320  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:43:22.320  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:43:22.340  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-24 15:43:22.340  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:43:22.350  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:43:22.350  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:43:22.350  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:43:22.350  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:43:24.035  3390  6051 D SSRM:n  : SIOP:: AP = 260, PST = 263 (W:30), CUR = 16, LCD = 0
,03-24 15:43:32.440  3390  3965 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:43:32.440  3390  3965 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:43:32.440  3390  3965 D BatteryService: online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:6
,03-24 15:43:32.440  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-24 15:43:32.450  3390  3965 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 11ms,
03-24 15:43:32.450  3390  3965 D BatteryService: stay LED for fully charged
03-24 15:43:32.450  3390  3390 I MotionRecognitionService: Plugged
,03-24 15:43:32.450  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:43:32.450  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
,03-24 15:43:32.450  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:43:32.465  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-24 15:43:32.465  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:43:32.465  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-24 15:43:32.490  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-24 15:43:32.490  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:43:32.495  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:43:32.500  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:43:32.500  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:43:32.500  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:43:34.065  3390  6051 D SSRM:n  : SIOP:: AP = 260, PST = 263 (W:30), CUR = 15, LCD = 0
,03-24 15:43:42.580  3390  4259 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:43:42.580  3390  4259 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:43:42.580  3390  4259 D BatteryService: online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
,03-24 15:43:42.580  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-24 15:43:42.590  3390  3390 I MotionRecognitionService: Plugged
03-24 15:43:42.590  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:43:42.590  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-24 15:43:42.590  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:43:42.590  3390  4259 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 12ms,
03-24 15:43:42.590  3390  4259 D BatteryService: stay LED for fully charged
,03-24 15:43:42.600  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:43:42.600  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:43:42.600  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:43:42.620  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-24 15:43:42.620  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:43:42.630  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:43:42.630  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:43:42.630  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:43:42.630  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:43:44.095  3390  6051 D SSRM:n  : SIOP:: AP = 260, PST = 263 (W:30), CUR = 15, LCD = 0,
,03-24 15:43:48.550  3390  3864 E Watchdog: !@Sync 35 [03-24 15:43:48.555]
,03-24 15:43:52.720  3390  4028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:43:52.720  3390  4028 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:43:52.720  3390  4028 D BatteryService: online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,03-24 15:43:52.720  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-24 15:43:52.725  3390  4028 D BatteryService: stay LED for fully charged
,03-24 15:43:52.730  3390  3390 I MotionRecognitionService: Plugged
03-24 15:43:52.730  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:43:52.730  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-24 15:43:52.730  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:43:52.740  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:43:52.740  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:43:52.740  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:43:52.760  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-24 15:43:52.760  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:43:52.770  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:43:52.770  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:43:52.770  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:43:52.770  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:43:54.125  3390  6051 D SSRM:n  : SIOP:: AP = 260, PST = 262 (W:30), CUR = 14, LCD = 0
,03-24 15:44:02.860  3390  4710 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:44:02.860  3390  4710 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:44:02.860  3390  4710 D BatteryService: online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
,03-24 15:44:02.860  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-24 15:44:02.865  3390  4710 D BatteryService: stay LED for fully charged
,03-24 15:44:02.870  3390  3390 I MotionRecognitionService: Plugged,
03-24 15:44:02.870  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:44:02.870  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-24 15:44:02.870  3390  3390 D MotionRecognitionService: skip setTransmitPower. ,
,03-24 15:44:02.880  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:44:02.880  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:44:02.880  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:44:02.905  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-24 15:44:02.905  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:44:02.910  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:44:02.910  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:44:02.910  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:44:02.910  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:44:04.155  3390  6051 D SSRM:n  : SIOP:: AP = 260, PST = 262 (W:30), CUR = 14, LCD = 0
,03-24 15:44:12.995  3390  4268 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:44:12.995  3390  4268 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:44:12.995  3390  4268 D BatteryService: online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
,03-24 15:44:13.000  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-24 15:44:13.000  3390  4268 D BatteryService: stay LED for fully charged,
,03-24 15:44:13.010  3390  3390 I MotionRecognitionService: Plugged
03-24 15:44:13.010  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:44:13.010  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
03-24 15:44:13.010  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:44:13.020  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:44:13.020  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:44:13.020  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:44:13.035  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-24 15:44:13.040  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:44:13.050  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:44:13.050  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:44:13.050  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:44:13.050  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:44:14.180  3390  6051 D SSRM:n  : SIOP:: AP = 260, PST = 262 (W:30), CUR = 16, LCD = 0
,03-24 15:44:18.560  3390  3864 E Watchdog: !@Sync 36 [03-24 15:44:18.562]
,03-24 15:44:21.575  2892  4752 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-24 15:44:23.135  3390  4707 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:44:23.135  3390  4707 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:44:23.135  3390  4707 D BatteryService: online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:7
,03-24 15:44:23.135  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-24 15:44:23.140  3390  4707 D BatteryService: stay LED for fully charged
,03-24 15:44:23.145  3390  3390 I MotionRecognitionService: Plugged
03-24 15:44:23.145  3390  3390 D MotionRecognitionService:   cableConnection= 1,
03-24 15:44:23.145  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-24 15:44:23.145  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:44:23.155  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:44:23.155  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:44:23.155  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-24 15:44:23.180  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-24 15:44:23.180  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:44:23.185  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:44:23.190  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:44:23.190  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:44:23.190  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:44:24.205  3390  6051 D SSRM:n  : SIOP:: AP = 260, PST = 261 (W:30), CUR = 15, LCD = 0
,03-24 15:44:33.270  3390  4045 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:44:33.270  3390  4045 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:44:33.270  3390  4045 D BatteryService: online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:3
,03-24 15:44:33.275  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-24 15:44:33.275  3390  4045 D BatteryService: stay LED for fully charged,
,03-24 15:44:33.285  3390  3390 I MotionRecognitionService: Plugged
03-24 15:44:33.285  3390  3390 D MotionRecognitionService:   cableConnection= 1,
03-24 15:44:33.285  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-24 15:44:33.285  3390  3390 D MotionRecognitionService: skip setTransmitPower. ,
,03-24 15:44:33.295  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:44:33.295  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:44:33.295  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:44:33.315  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-24 15:44:33.315  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:44:33.325  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:44:33.330  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:44:33.330  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:44:33.330  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:44:34.240  3390  6051 D SSRM:n  : SIOP:: AP = 260, PST = 261 (W:30), CUR = 15, LCD = 0
,03-24 15:44:41.435  3390  3587 I PowerManagerService: [PWL] Off : 1050s ago
,03-24 15:44:43.410  3390  3425 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:44:43.410  3390  3425 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:44:43.410  3390  3425 D BatteryService: online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
,03-24 15:44:43.415  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-24 15:44:43.420  3390  3390 I MotionRecognitionService: Plugged
03-24 15:44:43.420  3390  3390 D MotionRecognitionService:   cableConnection= 1,
03-24 15:44:43.420  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-24 15:44:43.420  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
03-24 15:44:43.425  3390  3425 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 11ms
,03-24 15:44:43.425  3390  3425 D BatteryService: stay LED for fully charged,
,03-24 15:44:43.435  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:44:43.435  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:44:43.435  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:44:43.450  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-24 15:44:43.450  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:44:43.460  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:44:43.465  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:44:43.465  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:44:43.465  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:44:44.265  3390  6051 D SSRM:n  : SIOP:: AP = 260, PST = 261 (W:30), CUR = 14, LCD = 0
,03-24 15:44:48.565  3390  3864 E Watchdog: !@Sync 37 [03-24 15:44:48.570]
,03-24 15:44:53.550  3390  3943 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:44:53.550  3390  3943 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:44:53.550  3390  3943 D BatteryService: online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-3
,03-24 15:44:53.555  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-24 15:44:53.555  3390  3943 D BatteryService: stay LED for fully charged,
,03-24 15:44:53.565  3390  3390 I MotionRecognitionService: Plugged
03-24 15:44:53.565  3390  3390 D MotionRecognitionService:   cableConnection= 1,
03-24 15:44:53.565  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-24 15:44:53.565  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:44:53.575  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:44:53.575  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:44:53.575  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:44:53.590  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-24 15:44:53.590  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:44:53.605  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:44:53.605  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:44:53.605  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:44:53.605  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:44:54.295  3390  6051 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 14, LCD = 0
,03-24 15:45:03.690  3390  4707 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:45:03.690  3390  4707 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:45:03.690  3390  4707 D BatteryService: online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
,03-24 15:45:03.690  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-24 15:45:03.700  3390  3390 I MotionRecognitionService: Plugged
03-24 15:45:03.700  3390  3390 D MotionRecognitionService:   cableConnection= 1,
03-24 15:45:03.700  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-24 15:45:03.700  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
03-24 15:45:03.700  3390  4707 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 11ms
,03-24 15:45:03.700  3390  4707 D BatteryService: stay LED for fully charged
,03-24 15:45:03.710  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-24 15:45:03.710  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,03-24 15:45:03.710  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-24 15:45:03.730  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-24 15:45:03.730  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:45:03.745  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:45:03.750  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:45:03.750  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:45:03.750  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:45:04.325  3390  6051 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 13, LCD = 0
,03-24 15:45:13.825  3390  4045 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:45:13.825  3390  4045 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:45:13.825  3390  4045 D BatteryService: online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
,03-24 15:45:13.825  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-24 15:45:13.840  3390  4045 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 13ms
03-24 15:45:13.840  3390  4045 D BatteryService: stay LED for fully charged,
,03-24 15:45:13.845  3390  3390 I MotionRecognitionService: Plugged,
03-24 15:45:13.845  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:45:13.845  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
03-24 15:45:13.845  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:45:13.855  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:45:13.855  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:45:13.855  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:45:13.870  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-24 15:45:13.870  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:45:13.880  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:45:13.885  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:45:13.885  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:45:13.885  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:45:14.350  3390  6051 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 15, LCD = 0
,03-24 15:45:18.575  3390  3864 E Watchdog: !@Sync 38 [03-24 15:45:18.577]
,03-24 15:45:21.575  2892  4752 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-24 15:45:23.965  3390  3425 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:45:23.965  3390  3425 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:45:23.965  3390  3425 D BatteryService: online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
,03-24 15:45:23.965  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-24 15:45:23.970  3390  3425 D BatteryService: stay LED for fully charged
,03-24 15:45:23.975  3390  3390 I MotionRecognitionService: Plugged
03-24 15:45:23.975  3390  3390 D MotionRecognitionService:   cableConnection= 1,
03-24 15:45:23.980  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-24 15:45:23.980  3390  3390 D MotionRecognitionService: skip setTransmitPower. ,
,03-24 15:45:23.985  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:45:23.985  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:45:23.985  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:45:24.000  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-24 15:45:24.000  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:45:24.010  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:45:24.015  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:45:24.015  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:45:24.015  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:45:24.375  3390  6051 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 14, LCD = 0
,03-24 15:45:34.110  3390  3943 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-24 15:45:34.110  3390  3943 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:45:34.110  3390  3943 D BatteryService: online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-3
03-24 15:45:34.110  3390  3943 D BatteryService: stay LED for fully charged
03-24 15:45:34.110  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-24 15:45:34.115  3390  3390 I MotionRecognitionService: Plugged,
03-24 15:45:34.115  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:45:34.115  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-24 15:45:34.115  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:45:34.120  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:45:34.120  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:45:34.120  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:45:34.135  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-24 15:45:34.135  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:45:34.150  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:45:34.150  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:45:34.150  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:45:34.150  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:45:34.405  3390  6051 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 15, LCD = 0
,03-24 15:45:44.250  3390  3832 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:45:44.250  3390  3832 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:45:44.250  3390  3832 D BatteryService: online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,03-24 15:45:44.250  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-24 15:45:44.260  3390  3832 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 11ms
03-24 15:45:44.260  3390  3832 D BatteryService: stay LED for fully charged
,03-24 15:45:44.265  3390  3390 I MotionRecognitionService: Plugged,
03-24 15:45:44.265  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:45:44.265  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-24 15:45:44.265  3390  3390 D MotionRecognitionService: skip setTransmitPower. ,
03-24 15:45:44.275  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:45:44.275  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:45:44.275  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:45:44.290  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-24 15:45:44.295  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:45:44.305  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:45:44.305  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:45:44.305  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:45:44.305  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:45:44.415  3390  6051 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 15, LCD = 0
,03-24 15:45:48.580  3390  3864 E Watchdog: !@Sync 39 [03-24 15:45:48.584]
,03-24 15:45:54.385  3390  3652 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:45:54.385  3390  3652 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:45:54.385  3390  3652 D BatteryService: online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:4
,03-24 15:45:54.390  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-24 15:45:54.390  3390  3652 D BatteryService: stay LED for fully charged,
,03-24 15:45:54.395  3390  3390 I MotionRecognitionService: Plugged,
03-24 15:45:54.395  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:45:54.395  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
,03-24 15:45:54.395  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:45:54.410  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:45:54.410  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:45:54.410  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:45:54.435  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-24 15:45:54.435  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:45:54.445  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:45:54.445  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:45:54.445  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:45:54.445  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:45:54.450  3390  6051 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 14, LCD = 0
,03-24 15:46:04.470  3390  6051 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 14, LCD = 0
,03-24 15:46:04.520  3390  4044 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:46:04.520  3390  4044 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:46:04.520  3390  4044 D BatteryService: online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
03-24 15:46:04.520  3390  4044 D BatteryService: stay LED for fully charged
,03-24 15:46:04.520  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-24 15:46:04.525  3390  3390 I MotionRecognitionService: Plugged
03-24 15:46:04.525  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:46:04.525  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-24 15:46:04.525  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:46:04.530  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:46:04.530  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:46:04.530  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:46:04.545  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-24 15:46:04.545  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:46:04.560  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:46:04.560  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:46:04.560  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:46:04.560  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:46:14.500  3390  6051 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 14, LCD = 0
,03-24 15:46:14.640  3390  3429 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:46:14.640  3390  3429 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:46:14.640  3390  3429 D BatteryService: online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-4
,03-24 15:46:14.640  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-24 15:46:14.645  3390  3429 D BatteryService: stay LED for fully charged
,03-24 15:46:14.650  3390  3390 I MotionRecognitionService: Plugged
03-24 15:46:14.650  3390  3390 D MotionRecognitionService:   cableConnection= 1,
03-24 15:46:14.650  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-24 15:46:14.650  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:46:14.660  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:46:14.660  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,03-24 15:46:14.660  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:46:14.685  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-24 15:46:14.685  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:46:14.695  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:46:14.695  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:46:14.695  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:46:14.695  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:46:15.995  3390  3609 D TimaService: TIMA: TimaService scheduler is intialized. 
03-24 15:46:15.995  3390  3609 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,03-24 15:46:15.995  3390  3608 D TimaService: TimaServiceHandler.handleMessage what =1,
,03-24 15:46:16.630  3390  3569 I UsageStatsService: User[0] Flushing usage stats to disk
,03-24 15:46:18.525  3390  3609 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
03-24 15:46:18.525  3390  3609 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,03-24 15:46:18.545  3390  3609 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;,
,03-24 15:46:18.555  3390  3609 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,03-24 15:46:18.585  3390  3864 E Watchdog: !@Sync 40 [03-24 15:46:18.591]
,03-24 15:46:21.575  2892  4752 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-24 15:46:24.525  3390  6051 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 12, LCD = 0
,03-24 15:46:24.780  3390  4709 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:46:24.780  3390  4709 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:46:24.780  3390  4709 D BatteryService: online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:3
,03-24 15:46:24.780  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-24 15:46:24.790  3390  3390 I MotionRecognitionService: Plugged
03-24 15:46:24.790  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:46:24.790  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-24 15:46:24.790  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:46:24.790  3390  4709 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 12ms,
03-24 15:46:24.790  3390  4709 D BatteryService: stay LED for fully charged
,03-24 15:46:24.800  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:46:24.800  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:46:24.800  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:46:24.820  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-24 15:46:24.820  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:46:24.830  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:46:24.830  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:46:24.830  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:46:24.830  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:46:26.435  3390  3587 I PowerManagerService: [PWL] Off : 1155s ago
,03-24 15:46:34.555  3390  6051 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 10, LCD = 0
,03-24 15:46:34.915  3390  3429 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-24 15:46:34.920  3390  3429 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:46:34.920  3390  3429 D BatteryService: online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-3
03-24 15:46:34.920  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-24 15:46:34.925  3390  3429 D BatteryService: stay LED for fully charged
,03-24 15:46:34.930  3390  3390 I MotionRecognitionService: Plugged,
03-24 15:46:34.930  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:46:34.930  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-24 15:46:34.930  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:46:34.945  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:46:34.945  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:46:34.945  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:46:34.965  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-24 15:46:34.965  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:46:34.975  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:46:34.975  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:46:34.975  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:46:34.975  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:46:44.585  3390  6051 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 13, LCD = 0
,03-24 15:46:45.055  3390  4709 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:46:45.055  3390  4709 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:46:45.055  3390  4709 D BatteryService: online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
,03-24 15:46:45.060  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-24 15:46:45.060  3390  4709 D BatteryService: stay LED for fully charged
,03-24 15:46:45.065  3390  3390 I MotionRecognitionService: Plugged
03-24 15:46:45.065  3390  3390 D MotionRecognitionService:   cableConnection= 1,
03-24 15:46:45.065  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-24 15:46:45.065  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:46:45.075  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:46:45.075  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:46:45.075  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-24 15:46:45.095  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-24 15:46:45.095  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:46:45.110  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:46:45.110  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:46:45.110  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:46:45.110  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:46:48.590  3390  3864 E Watchdog: !@Sync 41 [03-24 15:46:48.593]
,03-24 15:46:54.620  3390  6051 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 12, LCD = 0
,03-24 15:46:55.195  3390  3853 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:46:55.195  3390  3853 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:46:55.195  3390  3853 D BatteryService: online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
,03-24 15:46:55.195  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-24 15:46:55.205  3390  3853 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 12ms
03-24 15:46:55.205  3390  3853 D BatteryService: stay LED for fully charged
,03-24 15:46:55.210  3390  3390 I MotionRecognitionService: Plugged,
03-24 15:46:55.210  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:46:55.210  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-24 15:46:55.210  3390  3390 D MotionRecognitionService: skip setTransmitPower. ,
,03-24 15:46:55.220  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:46:55.220  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:46:55.220  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:46:55.235  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-24 15:46:55.235  5836  5927 D HeadsetStateMachine: Disconnected process message: 10,
,03-24 15:46:55.245  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:46:55.245  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:46:55.250  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:46:55.250  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:47:04.650  3390  6051 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 13, LCD = 0
,03-24 15:47:05.330  3390  4257 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:47:05.330  3390  4257 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:47:05.335  3390  4257 D BatteryService: online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,03-24 15:47:05.335  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-24 15:47:05.335  3390  4257 D BatteryService: stay LED for fully charged
,03-24 15:47:05.340  3390  3390 I MotionRecognitionService: Plugged
,03-24 15:47:05.345  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:47:05.345  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-24 15:47:05.345  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:47:05.350  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:47:05.350  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:47:05.350  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:47:05.370  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-24 15:47:05.370  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:47:05.385  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:47:05.385  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:47:05.385  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:47:05.385  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:47:14.685  3390  6051 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 12, LCD = 0
,03-24 15:47:15.470  3390  3965 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:47:15.470  3390  3965 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:47:15.470  3390  3965 D BatteryService: online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
,03-24 15:47:15.475  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-24 15:47:15.475  3390  3965 D BatteryService: stay LED for fully charged
,03-24 15:47:15.480  3390  3390 I MotionRecognitionService: Plugged
03-24 15:47:15.480  3390  3390 D MotionRecognitionService:   cableConnection= 1,
03-24 15:47:15.480  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-24 15:47:15.480  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:47:15.490  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-24 15:47:15.490  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:47:15.490  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:47:15.515  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-24 15:47:15.515  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:47:15.525  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:47:15.530  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:47:15.530  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:47:15.530  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:47:18.595  3390  3864 E Watchdog: !@Sync 42 [03-24 15:47:18.600]
,03-24 15:47:21.575  2892  4752 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-24 15:47:24.715  3390  6051 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 12, LCD = 0
,03-24 15:47:25.610  3390  4259 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:47:25.610  3390  4259 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:47:25.610  3390  4259 D BatteryService: online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,03-24 15:47:25.610  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-24 15:47:25.615  3390  4259 D BatteryService: stay LED for fully charged
,03-24 15:47:25.620  3390  3390 I MotionRecognitionService: Plugged,
03-24 15:47:25.620  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:47:25.620  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
,03-24 15:47:25.620  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:47:25.635  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:47:25.635  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:47:25.635  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:47:25.645  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-24 15:47:25.645  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:47:25.660  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:47:25.660  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:47:25.660  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:47:25.660  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:47:34.740  3390  6051 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 12, LCD = 0
,03-24 15:47:35.745  3390  4028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:47:35.745  3390  4028 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:47:35.745  3390  4028 D BatteryService: online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
,03-24 15:47:35.745  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-24 15:47:35.755  3390  3390 I MotionRecognitionService: Plugged
03-24 15:47:35.755  3390  3390 D MotionRecognitionService:   cableConnection= 1,
03-24 15:47:35.755  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-24 15:47:35.755  3390  3390 D MotionRecognitionService: skip setTransmitPower. ,
03-24 15:47:35.755  3390  4028 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 13ms,
,03-24 15:47:35.755  3390  4028 D BatteryService: stay LED for fully charged
,03-24 15:47:35.770  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-24 15:47:35.770  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:47:35.770  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-24 15:47:35.780  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-24 15:47:35.785  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:47:35.795  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:47:35.795  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:47:35.795  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:47:35.795  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:47:44.770  3390  6051 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 12, LCD = 0,
,03-24 15:47:45.880  3390  3652 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:47:45.880  3390  3652 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:47:45.880  3390  3652 D BatteryService: online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,03-24 15:47:45.885  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-24 15:47:45.885  3390  3652 D BatteryService: stay LED for fully charged,
,03-24 15:47:45.895  3390  3390 I MotionRecognitionService: Plugged
,03-24 15:47:45.895  3390  3390 D MotionRecognitionService:   cableConnection= 1
,03-24 15:47:45.895  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
03-24 15:47:45.900  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:47:45.895  3390  3390 D MotionRecognitionService: skip setTransmitPower. ,
03-24 15:47:45.900  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,03-24 15:47:45.900  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-24 15:47:45.920  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-24 15:47:45.920  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:47:45.930  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:47:45.930  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:47:45.930  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:47:45.930  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:47:48.605  3390  3864 E Watchdog: !@Sync 43 [03-24 15:47:48.608],
,03-24 15:47:54.800  3390  6051 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 12, LCD = 0
,03-24 15:47:56.020  3390  4044 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:47:56.020  3390  4044 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:47:56.020  3390  4044 D BatteryService: online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:6
,03-24 15:47:56.025  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-24 15:47:56.025  3390  4044 D BatteryService: stay LED for fully charged,
,03-24 15:47:56.035  3390  3390 I MotionRecognitionService: Plugged
03-24 15:47:56.035  3390  3390 D MotionRecognitionService:   cableConnection= 1,
03-24 15:47:56.035  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-24 15:47:56.035  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:47:56.045  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:47:56.045  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:47:56.045  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:47:56.060  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-24 15:47:56.060  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:47:56.075  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:47:56.075  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:47:56.075  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:47:56.075  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:48:04.830  3390  6051 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 10, LCD = 0
,03-24 15:48:06.160  3390  3429 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:48:06.160  3390  3429 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:48:06.160  3390  3429 D BatteryService: online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-3
,03-24 15:48:06.160  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-24 15:48:06.160  3390  3429 D BatteryService: stay LED for fully charged
,03-24 15:48:06.170  3390  3390 I MotionRecognitionService: Plugged,
03-24 15:48:06.170  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:48:06.170  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-24 15:48:06.170  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:48:06.180  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:48:06.180  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:48:06.180  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:48:06.195  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-24 15:48:06.195  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:48:06.205  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:48:06.205  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:48:06.205  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:48:06.205  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:48:14.860  3390  6051 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 11, LCD = 0
,03-24 15:48:16.300  3390  4709 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-24 15:48:16.300  3390  4709 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:48:16.300  3390  4709 D BatteryService: online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:43
03-24 15:48:16.300  3390  4709 D BatteryService: stay LED for fully charged
,03-24 15:48:16.300  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-24 15:48:16.310  3390  3390 I MotionRecognitionService: Plugged,
,03-24 15:48:16.310  3390  3390 D MotionRecognitionService:   cableConnection= 1
,03-24 15:48:16.310  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-24 15:48:16.310  3390  3390 D MotionRecognitionService: skip setTransmitPower. ,
03-24 15:48:16.315  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:48:16.315  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:48:16.315  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:48:16.330  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-24 15:48:16.330  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:48:16.340  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:48:16.340  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:48:16.340  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:48:16.340  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:48:16.435  3390  3587 I PowerManagerService: [PWL] Off : 1265s ago,
,03-24 15:48:18.615  3390  3864 E Watchdog: !@Sync 44 [03-24 15:48:18.617]
,03-24 15:48:21.575  2892  4752 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-24 15:48:24.890  3390  6051 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 12, LCD = 0
,03-24 15:48:26.440  3390  3853 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-24 15:48:26.440  3390  3853 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:48:26.440  3390  3853 D BatteryService: online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
03-24 15:48:26.440  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-24 15:48:26.440  3390  3853 D BatteryService: stay LED for fully charged
,03-24 15:48:26.445  3390  3390 I MotionRecognitionService: Plugged
03-24 15:48:26.445  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:48:26.445  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-24 15:48:26.445  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:48:26.455  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:48:26.455  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:48:26.455  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:48:26.470  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-24 15:48:26.470  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:48:26.480  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:48:26.480  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:48:26.480  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:48:26.480  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:48:34.915  3390  6051 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 12, LCD = 0
,03-24 15:48:36.575  3390  4257 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:48:36.580  3390  4257 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:48:36.580  3390  4257 D BatteryService: online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:2
,03-24 15:48:36.580  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-24 15:48:36.585  3390  4257 D BatteryService: stay LED for fully charged
,03-24 15:48:36.590  3390  3390 I MotionRecognitionService: Plugged,
,03-24 15:48:36.590  3390  3390 D MotionRecognitionService:   cableConnection= 1,
03-24 15:48:36.590  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-24 15:48:36.590  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:48:36.600  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:48:36.600  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:48:36.605  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:48:36.620  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-24 15:48:36.620  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:48:36.635  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:48:36.635  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:48:36.635  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:48:36.635  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:48:44.945  3390  6051 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 11, LCD = 0
,03-24 15:48:46.715  3390  3965 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:48:46.715  3390  3965 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:48:46.715  3390  3965 D BatteryService: online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
,03-24 15:48:46.715  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-24 15:48:46.720  3390  3965 D BatteryService: stay LED for fully charged
,03-24 15:48:46.725  3390  3390 I MotionRecognitionService: Plugged
03-24 15:48:46.725  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:48:46.725  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
03-24 15:48:46.725  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:48:46.735  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:48:46.735  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:48:46.735  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:48:46.755  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-24 15:48:46.755  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:48:46.765  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:48:46.765  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:48:46.765  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:48:46.765  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:48:48.620  3390  3864 E Watchdog: !@Sync 45 [03-24 15:48:48.624]
,03-24 15:48:54.975  3390  6051 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 10, LCD = 0
,03-24 15:48:56.855  3390  4259 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:48:56.855  3390  4259 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:48:56.855  3390  4259 D BatteryService: online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-10
,03-24 15:48:56.855  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-24 15:48:56.865  3390  3390 I MotionRecognitionService: Plugged
03-24 15:48:56.865  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:48:56.865  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-24 15:48:56.865  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:48:56.865  3390  4259 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 12ms,
,03-24 15:48:56.865  3390  4259 D BatteryService: stay LED for fully charged,
03-24 15:48:56.875  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:48:56.875  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:48:56.880  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:48:56.900  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-24 15:48:56.900  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:48:56.910  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:48:56.910  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:48:56.910  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:48:56.910  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:49:05.000  3390  6051 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 12, LCD = 0
,03-24 15:49:06.995  3390  4028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:49:06.995  3390  4028 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:49:06.995  3390  4028 D BatteryService: online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,03-24 15:49:06.995  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-24 15:49:07.005  3390  4028 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 11ms
,03-24 15:49:07.005  3390  4028 D BatteryService: stay LED for fully charged
03-24 15:49:07.005  3390  3390 I MotionRecognitionService: Plugged
03-24 15:49:07.005  3390  3390 D MotionRecognitionService:   cableConnection= 1
,03-24 15:49:07.005  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-24 15:49:07.005  3390  3390 D MotionRecognitionService: skip setTransmitPower. ,
,03-24 15:49:07.015  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:49:07.015  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:49:07.015  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:49:07.035  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-24 15:49:07.035  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:49:07.045  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:49:07.045  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:49:07.045  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:49:07.045  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:49:15.035  3390  6051 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 10, LCD = 0
,03-24 15:49:17.135  3390  4710 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:49:17.135  3390  4710 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:49:17.135  3390  4710 D BatteryService: online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
,03-24 15:49:17.140  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-24 15:49:17.140  3390  4710 D BatteryService: stay LED for fully charged
,03-24 15:49:17.150  3390  3390 I MotionRecognitionService: Plugged,
03-24 15:49:17.150  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:49:17.150  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-24 15:49:17.150  3390  3390 D MotionRecognitionService: skip setTransmitPower. ,
,03-24 15:49:17.160  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:49:17.160  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:49:17.160  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:49:17.180  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-24 15:49:17.180  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:49:17.190  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:49:17.190  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:49:17.190  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:49:17.190  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:49:18.630  3390  3864 E Watchdog: !@Sync 46 [03-24 15:49:18.632]
,03-24 15:49:21.575  2892  4752 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-24 15:49:25.060  3390  6051 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 11, LCD = 0
,03-24 15:49:27.275  3390  4268 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:49:27.275  3390  4268 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:49:27.275  3390  4268 D BatteryService: online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
,03-24 15:49:27.275  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-24 15:49:27.285  3390  3390 I MotionRecognitionService: Plugged
03-24 15:49:27.285  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:49:27.285  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-24 15:49:27.285  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:49:27.285  3390  4268 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 12ms,
03-24 15:49:27.285  3390  4268 D BatteryService: stay LED for fully charged
,03-24 15:49:27.295  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:49:27.295  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:49:27.295  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-24 15:49:27.315  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-24 15:49:27.315  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:49:27.325  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:49:27.325  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:49:27.330  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:49:27.330  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:49:35.095  3390  6051 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 12, LCD = 0
,03-24 15:49:37.410  3390  4707 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-24 15:49:37.410  3390  4707 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:49:37.410  3390  4707 D BatteryService: online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-4
,03-24 15:49:37.415  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-24 15:49:37.420  3390  4707 D BatteryService: stay LED for fully charged
,03-24 15:49:37.425  3390  3390 I MotionRecognitionService: Plugged,
03-24 15:49:37.425  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:49:37.425  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-24 15:49:37.425  3390  3390 D MotionRecognitionService: skip setTransmitPower. ,
03-24 15:49:37.435  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:49:37.435  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:49:37.435  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:49:37.450  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:49:37.450  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-24 15:49:37.450  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:49:37.465  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:49:37.465  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:49:37.465  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:49:45.125  3390  6051 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 10, LCD = 0
,03-24 15:49:47.550  3390  4045 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:49:47.550  3390  4045 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:49:47.550  3390  4045 D BatteryService: online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:4
,03-24 15:49:47.555  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-24 15:49:47.555  3390  4045 D BatteryService: stay LED for fully charged,
,03-24 15:49:47.565  3390  3390 I MotionRecognitionService: Plugged
03-24 15:49:47.565  3390  3390 D MotionRecognitionService:   cableConnection= 1,
03-24 15:49:47.565  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-24 15:49:47.565  3390  3390 D MotionRecognitionService: skip setTransmitPower. ,
,03-24 15:49:47.575  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-24 15:49:47.575  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,03-24 15:49:47.575  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
03-24 15:49:47.585  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-24 15:49:47.585  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:49:47.600  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:49:47.600  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:49:47.600  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:49:47.600  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:49:48.635  3390  3864 E Watchdog: !@Sync 47 [03-24 15:49:48.640]
,03-24 15:49:55.155  3390  6051 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 11, LCD = 0
,03-24 15:49:57.685  3390  3853 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-24 15:49:57.685  3390  3853 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:49:57.685  3390  3853 D BatteryService: online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,03-24 15:49:57.690  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-24 15:49:57.700  3390  3390 I MotionRecognitionService: Plugged
03-24 15:49:57.700  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:49:57.700  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-24 15:49:57.700  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
03-24 15:49:57.700  3390  3853 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 15ms
03-24 15:49:57.700  3390  3853 D BatteryService: stay LED for fully charged
,03-24 15:49:57.710  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:49:57.710  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:49:57.710  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:49:57.725  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-24 15:49:57.725  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:49:57.735  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:49:57.735  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:49:57.735  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:49:57.740  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:50:05.180  3390  6051 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 11, LCD = 0,
,03-24 15:50:07.825  3390  4257 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:50:07.825  3390  4257 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:50:07.825  3390  4257 D BatteryService: online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
,03-24 15:50:07.830  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-24 15:50:07.835  3390  4257 D BatteryService: stay LED for fully charged,
,03-24 15:50:07.840  3390  3390 I MotionRecognitionService: Plugged,
03-24 15:50:07.840  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:50:07.840  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-24 15:50:07.840  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:50:07.845  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:50:07.845  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:50:07.845  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:50:07.855  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-24 15:50:07.855  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:50:07.870  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:50:07.870  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:50:07.870  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:50:07.870  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:50:11.440  3390  3587 I PowerManagerService: [PWL] Off : 1380s ago
,03-24 15:50:15.210  3390  6051 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 11, LCD = 0
,03-24 15:50:17.965  3390  3965 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:50:17.965  3390  3965 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:50:17.965  3390  3965 D BatteryService: online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-4
,03-24 15:50:17.970  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-24 15:50:17.970  3390  3965 D BatteryService: stay LED for fully charged
,03-24 15:50:17.980  3390  3390 I MotionRecognitionService: Plugged
03-24 15:50:17.980  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:50:17.980  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-24 15:50:17.980  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:50:17.990  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:50:17.990  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:50:17.990  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:50:18.010  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-24 15:50:18.010  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:50:18.020  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:50:18.020  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:50:18.020  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:50:18.020  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:50:18.645  3390  3864 E Watchdog: !@Sync 48 [03-24 15:50:18.648]
,03-24 15:50:21.575  2892  4752 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-24 15:50:25.235  3390  6051 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 10, LCD = 0
,03-24 15:50:28.105  3390  4259 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:50:28.105  3390  4259 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:50:28.105  3390  4259 D BatteryService: online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
,03-24 15:50:28.110  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-24 15:50:28.110  3390  4259 D BatteryService: stay LED for fully charged
,03-24 15:50:28.115  3390  3390 I MotionRecognitionService: Plugged
03-24 15:50:28.115  3390  3390 D MotionRecognitionService:   cableConnection= 1,
03-24 15:50:28.115  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-24 15:50:28.115  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:50:28.130  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:50:28.130  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:50:28.130  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:50:28.150  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-24 15:50:28.150  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:50:28.160  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:50:28.160  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:50:28.160  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:50:28.160  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:50:35.265  3390  6051 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 10, LCD = 0
,03-24 15:50:38.245  3390  4028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:50:38.245  3390  4028 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:50:38.245  3390  4028 D BatteryService: online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
,03-24 15:50:38.250  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-24 15:50:38.255  3390  3390 I MotionRecognitionService: Plugged
03-24 15:50:38.260  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:50:38.260  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-24 15:50:38.260  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:50:38.260  3390  4028 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 13ms,
03-24 15:50:38.260  3390  4028 D BatteryService: stay LED for fully charged
,03-24 15:50:38.270  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:50:38.270  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:50:38.270  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:50:38.285  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-24 15:50:38.285  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:50:38.295  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:50:38.300  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:50:38.300  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:50:38.300  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:50:45.300  3390  6051 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 10, LCD = 0
,03-24 15:50:48.390  3390  4710 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:50:48.390  3390  4710 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:50:48.390  3390  4710 D BatteryService: online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,03-24 15:50:48.390  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-24 15:50:48.400  3390  4710 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 11ms
03-24 15:50:48.400  3390  4710 D BatteryService: stay LED for fully charged,
,03-24 15:50:48.400  3390  3390 I MotionRecognitionService: Plugged,
03-24 15:50:48.400  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:50:48.400  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-24 15:50:48.400  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:50:48.410  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:50:48.410  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:50:48.410  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:50:48.430  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-24 15:50:48.430  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:50:48.440  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:50:48.440  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:50:48.440  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:50:48.440  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:50:48.655  3390  3864 E Watchdog: !@Sync 49 [03-24 15:50:48.656]
,03-24 15:50:55.325  3390  6051 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 11, LCD = 0
,03-24 15:50:58.530  3390  4709 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:50:58.530  3390  4709 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:50:58.530  3390  4709 D BatteryService: online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
,03-24 15:50:58.535  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-24 15:50:58.540  3390  4709 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 11ms
03-24 15:50:58.540  3390  4709 D BatteryService: stay LED for fully charged
03-24 15:50:58.545  3390  3390 I MotionRecognitionService: Plugged
03-24 15:50:58.545  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:50:58.545  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-24 15:50:58.545  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:50:58.550  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:50:58.550  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:50:58.550  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:50:58.570  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-24 15:50:58.570  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:50:58.585  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:50:58.585  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:50:58.585  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:50:58.585  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:51:05.355  3390  6051 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 11, LCD = 0
,03-24 15:51:08.670  3390  4707 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:51:08.670  3390  4707 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:51:08.670  3390  4707 D BatteryService: online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,03-24 15:51:08.675  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-24 15:51:08.675  3390  4707 D BatteryService: stay LED for fully charged
,03-24 15:51:08.685  3390  3390 I MotionRecognitionService: Plugged
03-24 15:51:08.685  3390  3390 D MotionRecognitionService:   cableConnection= 1,
03-24 15:51:08.685  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-24 15:51:08.685  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:51:08.695  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:51:08.695  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:51:08.695  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:51:08.715  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-24 15:51:08.715  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:51:08.725  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:51:08.725  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:51:08.725  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:51:08.725  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:51:15.380  3390  6051 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 10, LCD = 0
,03-24 15:51:15.995  3390  3609 D TimaService: TIMA: TimaService scheduler is intialized. 
03-24 15:51:15.995  3390  3609 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,03-24 15:51:16.000  3390  3608 D TimaService: TimaServiceHandler.handleMessage what =1
,03-24 15:51:18.660  3390  3864 E Watchdog: !@Sync 50 [03-24 15:51:18.664]
,03-24 15:51:18.815  3390  4045 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:51:18.815  3390  4045 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:51:18.815  3390  4045 D BatteryService: online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
,03-24 15:51:18.815  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-24 15:51:18.820  3390  4045 D BatteryService: stay LED for fully charged
,03-24 15:51:18.830  3390  3390 I MotionRecognitionService: Plugged
,03-24 15:51:18.830  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:51:18.830  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-24 15:51:18.830  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:51:18.835  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:51:18.835  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:51:18.840  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:51:18.860  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-24 15:51:18.860  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:51:18.870  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:51:18.870  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:51:18.870  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:51:18.870  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:51:20.840  3390  3609 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,03-24 15:51:20.840  3390  3609 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,03-24 15:51:20.860  3390  3609 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;,
03-24 15:51:20.860  3390  3609 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,03-24 15:51:21.575  2892  4752 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-24 15:51:25.405  3390  6051 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 10, LCD = 0
,03-24 15:51:28.955  3390  3425 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:51:28.955  3390  3425 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:51:28.955  3390  3425 D BatteryService: online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
,03-24 15:51:28.960  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-24 15:51:28.960  3390  3425 D BatteryService: stay LED for fully charged
,03-24 15:51:28.965  3390  3390 I MotionRecognitionService: Plugged
03-24 15:51:28.965  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:51:28.965  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-24 15:51:28.965  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:51:28.975  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:51:28.975  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:51:28.975  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:51:28.995  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-24 15:51:28.995  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:51:29.005  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:51:29.005  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:51:29.005  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:51:29.005  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:51:35.435  3390  6051 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 10, LCD = 0
,03-24 15:51:39.095  3390  3943 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:51:39.095  3390  3943 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:51:39.095  3390  3943 D BatteryService: online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
,03-24 15:51:39.095  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-24 15:51:39.105  3390  3943 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 10ms
03-24 15:51:39.105  3390  3943 D BatteryService: stay LED for fully charged,
,03-24 15:51:39.110  3390  3390 I MotionRecognitionService: Plugged
03-24 15:51:39.110  3390  3390 D MotionRecognitionService:   cableConnection= 1,
03-24 15:51:39.110  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
03-24 15:51:39.110  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:51:39.120  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:51:39.120  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,03-24 15:51:39.120  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-24 15:51:39.140  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-24 15:51:39.140  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:51:39.155  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:51:39.155  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:51:39.155  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:51:39.155  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:51:45.460  3390  6051 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 10, LCD = 0
,03-24 15:51:48.675  3390  3864 E Watchdog: !@Sync 51 [03-24 15:51:48.680]
,03-24 15:51:49.230  3390  3832 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:51:49.230  3390  3832 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:51:49.230  3390  3832 D BatteryService: online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,03-24 15:51:49.235  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-24 15:51:49.235  3390  3832 D BatteryService: stay LED for fully charged
,03-24 15:51:49.245  3390  3390 I MotionRecognitionService: Plugged,
03-24 15:51:49.245  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:51:49.245  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-24 15:51:49.245  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:51:49.250  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:51:49.250  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:51:49.250  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-24 15:51:49.270  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-24 15:51:49.270  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:51:49.280  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:51:49.280  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:51:49.280  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:51:49.280  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:51:55.495  3390  6051 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 11, LCD = 0
,03-24 15:51:59.365  3390  3652 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-24 15:51:59.370  3390  3652 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:51:59.370  3390  3652 D BatteryService: online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-9
03-24 15:51:59.370  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-24 15:51:59.375  3390  3652 D BatteryService: stay LED for fully charged
,03-24 15:51:59.380  3390  3390 I MotionRecognitionService: Plugged
03-24 15:51:59.380  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:51:59.380  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-24 15:51:59.380  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:51:59.390  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:51:59.390  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:51:59.390  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:51:59.410  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-24 15:51:59.410  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:51:59.420  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:51:59.420  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:51:59.420  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:51:59.420  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:52:05.525  3390  6051 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 11, LCD = 0
,03-24 15:52:09.505  3390  4044 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:52:09.505  3390  4044 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:52:09.505  3390  4044 D BatteryService: online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:21
,03-24 15:52:09.510  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-24 15:52:09.510  3390  4044 D BatteryService: stay LED for fully charged
,03-24 15:52:09.515  3390  3390 I MotionRecognitionService: Plugged,
03-24 15:52:09.515  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:52:09.515  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
,03-24 15:52:09.515  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-24 15:52:09.530  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:52:09.530  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:52:09.530  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:52:09.550  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-24 15:52:09.550  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:52:09.560  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:52:09.560  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:52:09.560  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:52:09.560  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:52:11.440  3390  3587 I PowerManagerService: [PWL] Off : 1500s ago
,03-24 15:52:15.550  3390  6051 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 9, LCD = 0
,03-24 15:52:18.685  3390  3864 E Watchdog: !@Sync 52 [03-24 15:52:18.689]
,03-24 15:52:19.640  3390  3429 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-24 15:52:19.645  3390  3429 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:52:19.645  3390  3429 D BatteryService: online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:6
03-24 15:52:19.645  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-24 15:52:19.650  3390  3429 D BatteryService: stay LED for fully charged
,03-24 15:52:19.655  3390  3390 I MotionRecognitionService: Plugged,
03-24 15:52:19.655  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:52:19.655  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-24 15:52:19.655  3390  3390 D MotionRecognitionService: skip setTransmitPower. ,
03-24 15:52:19.665  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:52:19.665  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:52:19.665  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
03-24 15:52:19.685  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-24 15:52:19.690  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
03-24 15:52:19.695  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:52:19.695  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:52:19.695  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:52:19.695  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:52:21.575  2892  4752 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-24 15:52:25.575  3390  6051 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 7, LCD = 0
,03-24 15:52:29.785  3390  4268 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:52:29.785  3390  4268 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:52:29.785  3390  4268 D BatteryService: online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
,03-24 15:52:29.785  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-24 15:52:29.795  3390  3390 I MotionRecognitionService: Plugged
03-24 15:52:29.795  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-24 15:52:29.795  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-24 15:52:29.795  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
03-24 15:52:29.795  3390  4268 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 10ms
03-24 15:52:29.795  3390  4268 D BatteryService: stay LED for fully charged
,03-24 15:52:29.805  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-24 15:52:29.805  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,03-24 15:52:29.805  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:52:29.825  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-24 15:52:29.825  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:52:29.835  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:52:29.835  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:52:29.835  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:52:29.835  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-24 15:52:35.610  3390  6051 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 10, LCD = 0
,03-24 15:52:39.925  3390  3853 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-24 15:52:39.925  3390  3853 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-24 15:52:39.925  3390  3853 D BatteryService: online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:2
,03-24 15:52:39.930  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-24 15:52:39.935  3390  3853 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 10ms
03-24 15:52:39.935  3390  3853 D BatteryService: stay LED for fully charged
,03-24 15:52:39.940  3390  3390 I MotionRecognitionService: Plugged,
03-24 15:52:39.940  3390  3390 D MotionRecognitionService:   cableConnection= 1,
03-24 15:52:39.940  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
,03-24 15:52:39.940  3390  3390 D MotionRecognitionService: skip setTransmitPower. ,
,03-24 15:52:39.950  3727  3727 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:52:39.950  3727  3727 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-24 15:52:39.950  3727  3727 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-24 15:52:39.965  5836  5836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-24 15:52:39.965  5836  5927 D HeadsetStateMachine: Disconnected process message: 10
,03-24 15:52:39.980  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-24 15:52:39.980  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:52:39.980  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-24 15:52:39.980  3727  3727 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,TIME-OUT KILL (timeout was 1400000ms),03-24 15:52:43.035 12918 12918 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
03-24 15:52:43.040 12918 12918 D AndroidRuntime: CheckJNI is OFF
03-24 15:52:43.040 12918 12918 D AndroidRuntime: readGMSProperty: start
03-24 15:52:43.040 12918 12918 D AndroidRuntime: readGMSProperty: already setted!!
03-24 15:52:43.040 12918 12918 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-24 15:52:43.040 12918 12918 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-24 15:52:43.040 12918 12918 D AndroidRuntime: readGMSProperty: end
03-24 15:52:43.040 12918 12918 D AndroidRuntime: addProductProperty: start
03-24 15:52:43.135 12918 12918 E AffinityControl: AffinityControl: registerfunction enter
03-24 15:52:43.155 12918 12918 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
03-24 15:52:43.165  3390  3943 D PackageManager: START PACKAGE DELETE: observer{988775686}
03-24 15:52:43.165  3390  3943 D PackageManager: pkg{<packageName>}
03-24 15:52:43.165  3390  3943 D PackageManager: user{0}
03-24 15:52:43.165  3390  3943 D PackageManager: caller{2000}
03-24 15:52:43.165  3390  3943 D PackageManager: flags{2}
03-24 15:52:43.165  3390  3943 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
03-24 15:52:43.165  3390  3943 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
03-24 15:52:43.165  3390  3593 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
03-24 15:52:43.165  3390  3943 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
03-24 15:52:43.165  3390  3943 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
03-24 15:52:43.165  3390  3943 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
03-24 15:52:43.165  3390  3593 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
03-24 15:52:43.165  3390  3593 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
03-24 15:52:43.170  3390  3593 D PackageManager: !@killApplicatoin: 10011, uninstall pkg
03-24 15:52:43.165  3390  3593 D ApplicationPolicy: getApplicationUninstallationEnabled
03-24 15:52:43.165  3390  3593 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
03-24 15:52:43.170  3390  3572 I ActivityManager: Force stopping com.test.thalitest appid=10011 user=-1: uninstall pkg
03-24 15:52:43.175  3390  3572 I ActivityManager: Killing 11146:com.test.thalitest/u0a11 (adj 0): stop com.test.thalitest cause uninstall pkg
03-24 15:52:43.200  3390  3572 I ActivityManager:   Force finishing activity 3 ActivityRecord{34da1a7b u0 com.test.thalitest/.MainActivity t42}
03-24 15:52:43.200  3390  3572 W ActivityManager: mDVFSHelper.acquire()
03-24 15:52:43.285  3390  3593 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
03-24 15:52:43.290  3390  3593 W PackageSettings: Skipping PackageSetting{4168691 com.example.hello/10691} due to missing metadata
03-24 15:52:43.320  3390  3593 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
03-24 15:52:43.335  3390  3965 I WindowState: WIN DEATH: Window{24d9bbd1 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}
03-24 15:52:43.335  2862  4525 I SurfaceFlinger: id=15 Removed NainActivit (6/8)
03-24 15:52:43.340  2862  3035 I SurfaceFlinger: id=15 Removed NainActivit (-2/8)
03-24 15:52:43.350  3390  3965 D InputDispatcher: Focus left window: 11146
03-24 15:52:43.355  3390  3965 D MultiWindowConverter: dismissGuide() : Before attaching the guide view, mForceDismissGuide : false
03-24 15:52:43.355  3390  3572 D PowerManagerService: setKeyboardVisibility: false
03-24 15:52:43.355  3390  3572 I ActivityManager: Skip updateThumbnail for r=ActivityRecord{21ea0dab u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t40}
03-24 15:52:43.370  3390  3581 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3390 uid:1000
03-24 15:52:43.370  3390  3581 D PointerIcon: setMouseCustomIcon IconType is same.101
03-24 15:52:43.370  3390  3581 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3390 uid:1000
03-24 15:52:43.370  3390  3581 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
03-24 15:52:43.375  3390  3593 I ActivityManager: Force stopping com.test.thalitest appid=10011 user=0: pkg removed
03-24 15:52:43.380  3390  3593 I ActivityManager:   Force finishing activity 3 ActivityRecord{34da1a7b u0 com.test.thalitest/.MainActivity t42 f}
03-24 15:52:43.380  3390  3593 W ActivityManager: Duplicate finish request for ActivityRecord{34da1a7b u0 com.test.thalitest/.MainActivity t42 f}
03-24 15:52:43.395  3390  3413 I art     : Background sticky concurrent mark sweep GC freed 67596(9MB) AllocSpace objects, 406(6MB) LOS objects, 19% free, 32MB/40MB, paused 10.437ms total 102.418ms
03-24 15:52:43.425  3390  3593 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-24 15:52:43.430  6544  6544 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(433/onResume)] 
03-24 15:52:43.435  3390  3572 D InputDispatcher: Focused application released
03-24 15:52:43.435  9170  9170 I art     : Explicit concurrent mark sweep GC freed 2670(151KB) AllocSpace objects, 0(0B) LOS objects, 69% free, 1770KB/5MB, paused 720us total 21.513ms
03-24 15:52:43.435  3922  3922 I art     : Explicit concurrent mark sweep GC freed 1664(87KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 714us total 17.797ms
03-24 15:52:43.445  6544  6544 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5412/IlIlllIlllllIlIllllI)] Get Postpone Count : 0
03-24 15:52:43.450  4128  4128 I art     : Explicit concurrent mark sweep GC freed 22443(1288KB) AllocSpace objects, 2(32KB) LOS objects, 26% free, 5MB/7MB, paused 845us total 53.964ms
03-24 15:52:43.455  4626  4626 I art     : Explicit concurrent mark sweep GC freed 3085(189KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 8MB/11MB, paused 784us total 68.757ms
03-24 15:52:43.460  6544  6544 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5134/lIIIIIIIlllllllIIlll)] Get Priority : 0
03-24 15:52:43.470  6544  6544 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5434/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
03-24 15:52:43.475  6544  6544 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(443/onResume)] Postpone Count : 0
03-24 15:52:43.475  4626  4635 W SQLiteConnectionPool: A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
03-24 15:52:43.485  4029  4029 I art     : Explicit concurrent mark sweep GC freed 16135(925KB) AllocSpace objects, 10(1506KB) LOS objects, 12% free, 56MB/64MB, paused 4.379ms total 51.057ms
03-24 15:52:43.485  6544  6544 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5475/llIlIIIIlllIlllllIll)] Download Postpone status : 0
03-24 15:52:43.490  3390  3633 I InputReader: Reconfiguring input devices.  changes=0x00000010
03-24 15:52:43.490  3727  3727 D CoverUpdateMonitor: received broadcast android.intent.action.PACKAGE_REMOVED
03-24 15:52:43.490  4509  4509 E SamsungIME: mOCRHelper is null
03-24 15:52:43.495  4351  4785 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
03-24 15:52:43.500 10674 10674 D LWLocationManager: getDeviceLocationId :  id = -100
03-24 15:52:43.500 10674 10674 D LocationWidgetApplication: getLastUiLocationId() : mLastUiLocationId = -100
03-24 15:52:43.510  3390  3654 V NetworkStats: removeUidsLocked() for UIDs [10011]
03-24 15:52:43.510  3390  3654 D NtpTrustedTime: currentTimeMillis() cache hit
03-24 15:52:43.510  3390  3654 V NetworkStats: performPollLocked(flags=0x3)
03-24 15:52:43.515  3390  3654 V NetworkStats: performPollLocked() took 8ms
03-24 15:52:43.515  3390  3654 D NtpTrustedTime: currentTimeMillis() cache hit
03-24 15:52:43.520  3390  3572 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-24 15:52:43.520  3390  3572 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-24 15:52:43.520  3390  3572 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-24 15:52:43.520  3390  3572 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-24 15:52:43.520  5602  5620 W ResourceType: For resource 0x7f020570, entry index(1392) is beyond type entryCount(787)
03-24 15:52:43.520  5602  5620 W ResourceType: Failure getting entry for 0x7f020570 (t=1 e=1392) (error -75)
03-24 15:52:43.535 12937 12937 E Zygote  : MountEmulatedStorage()
03-24 15:52:43.535 12937 12937 E Zygote  : v2
03-24 15:52:43.535 12937 12937 I libpersona: KNOX_SDCARD checking this for 10063
03-24 15:52:43.535 12937 12937 I libpersona: KNOX_SDCARD not a persona
03-24 15:52:43.540 12937 12937 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
03-24 15:52:43.540  3390  3572 I ActivityManager: Start proc 12937:com.samsung.android.app.vrsetupwizardstub/u0a63 for broadcast-3 com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver
03-24 15:52:43.540  3390  3693 D TaskPersister: removeObsoleteFile: deleting file=42_task.xml
03-24 15:52:43.540  3390  3693 D TaskPersister: removeObsoleteFile: deleting file=42_task_thumbnail.png
03-24 15:52:43.540  6544  6544 I DBG_DM  : [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
03-24 15:52:43.545  6544  6544 I DBG_DM  : [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(327/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
03-24 15:52:43.545  3390  3593 I art     : Explicit concurrent mark sweep GC freed 12461(884KB) AllocSpace objects, 3(2MB) LOS objects, 33% free, 29MB/44MB, paused 2.314ms total 113.307ms
03-24 15:52:43.545 12937 12937 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
03-24 15:52:43.545 12937 12937 E Zygote  : accessInfo : 0
03-24 15:52:43.550 12937 12937 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-24 15:52:43.555  6544  6544 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5134/lIIIIIIIlllllllIIlll)] Get Priority : 0
03-24 15:52:43.565  3998  3998 D RegisteredServicesCache: empty dynamic service
03-24 15:52:43.575  3390  3853 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
03-24 15:52:43.575  3390  3853 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
03-24 15:52:43.575  3998  3998 D RegisteredComponentCache: Collect Tech packages for Knox
03-24 15:52:43.580  6544  6544 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5412/IlIlllIlllllIlIllllI)] Get Postpone Count : 0
03-24 15:52:43.585 12937 12937 D TimaKeyStoreProvider: TimaSignature is unavailable
03-24 15:52:43.585  6544  6544 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5054/IIlllIlIIlIllIlllIll)] Get Force status : 0
03-24 15:52:43.585 12937 12937 D ActivityThread: Added TimaKeyStore provider
03-24 15:52:43.590  6544  6544 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5434/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
03-24 15:52:43.590  6544  6544 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(537/llIIIIlllllIIllIIllI)] Check Force Install : false
03-24 15:52:43.590  6544  6544 I DBG_DM  : [llIIlIIlIllIllIlllII(337/IllIlIIIIlIIlIIIllIl)] 
03-24 15:52:43.595  6544  6544 I DBG_DM  : [llIIlIIlIllIllIlllII(343/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
03-24 15:52:43.600  3390  3832 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{15dd1024 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{9e3078d 12937:com.samsung.android.app.vrsetupwizardstub/u0a63}
03-24 15:52:43.600  3390  3652 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-24 15:52:43.600  3390  3652 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-24 15:52:43.600  3390  3652 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-24 15:52:43.605  3390  3655 D NtpTrustedTime: currentTimeMillis() cache hit
03-24 15:52:43.605  3390  3655 D NtpTrustedTime: currentTimeMillis() cache hit
03-24 15:52:43.610  2862  2862 I SurfaceFlinger: id=16 createSurf (1440x2560),1 flag=404, YUIInstallC
03-24 15:52:43.610  3390  3652 D SecContentProvider2: query(), uri = 11 selection = getMyKnoxAdmin
03-24 15:52:43.610  3390  4028 D MultiWindowConverter: dismissGuide() : Before attaching the guide view, mForceDismissGuide : false
03-24 15:52:43.610  3390  3579 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{27c075d2 u0 d0 com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}
03-24 15:52:43.615  3390  4028 D InputDispatcher: Focus entered window: 6544
03-24 15:52:43.615  3390  3581 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3390 uid:1000
03-24 15:52:43.615  3390  3581 D PointerIcon: setMouseCustomIcon IconType is same.101
03-24 15:52:43.615  3390  3581 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3390 uid:1000
03-24 15:52:43.615  3390  3581 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
03-24 15:52:43.615  6544  6544 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
03-24 15:52:43.620  6544  9187 D mali_winsys: new_window_surface returns 0x3000,  [1440x2560]-format:1
03-24 15:52:43.620  6544  6544 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(425/onPause)] 
03-24 15:52:43.620  3390  4045 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
03-24 15:52:43.625  3390  4045 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 11146 uid 10011
03-24 15:52:43.635  4509  4509 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
03-24 15:52:43.640 12937 12937 D VRSetupWizardStub/PackageIntentReceiver: onReceive()
03-24 15:52:43.640 12937 12937 D VRSetupWizardStub/PackageIntentReceiver: Action Package Remove
03-24 15:52:43.640 12937 12937 D VRSetupWizardStub/PackageIntentReceiver: packagename:com.test.thalitest
03-24 15:52:43.645  3390  4044 I ActivityManager: Killing 10174:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): emptyCount ##31
03-24 15:52:43.650  3390  4044 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{15dd1024 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{24306e87 7138:com.samsung.klmsagent/u0a21}
03-24 15:52:43.650  7138  7138 I KLMS-2.5.262: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Mar 24 15:52:43 GMT+01:00 2016
03-24 15:52:43.650  6544  6544 V ActivityThread: updateVisibility : ActivityRecord{130e6c3 token=android.os.BinderProxy@16baa8c1 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
03-24 15:52:43.655  6544  6544 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@16baa8c1 time:1597975
03-24 15:52:43.655  3390  3853 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
03-24 15:52:43.660  7138  7138 I KLMS-2.5.262: : KLMSAbstractReciever(): onReceive().END.
03-24 15:52:43.660  7138  7138 I KLMS-2.5.262: : KLMSIntentService(): onCreate()
03-24 15:52:43.660  7138  7138 I KLMS-2.5.262: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
03-24 15:52:43.660  7138  7138 I KLMS-2.5.262: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
03-24 15:52:43.665  7138 12955 I KLMS-2.5.262: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.service.KLMSIntentService (has extras) }
03-24 15:52:43.665  7138 12955 D KLMS-2.5.262: : KLMSIntentService(): PACKAGE_REMOVED
03-24 15:52:43.665  7138 12955 I KLMS-2.5.262: : Systemprocess(): listeningToPackageRemoved().START
03-24 15:52:43.665  7138 12955 I KLMS-2.5.262: : Systemprocess(): listeningToPackageRemoved().packageName: com.test.thalitest
03-24 15:52:43.665  7138 12955 I KLMS-2.5.262: : listeningToPackageRemovedforELM().START
03-24 15:52:43.665  7138 12955 I KLMS-2.5.262: : MDMBridge.getInstance()
03-24 15:52:43.665  7138 12955 I KLMS-2.5.262: : MDMBridge.getAllLicenseInfoFromSDK()
03-24 15:52:43.665  7138 12955 I KLMS-2.5.262: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
03-24 15:52:43.665  3390  3581 W ActivityManager: mDVFSHelper.release()
03-24 15:52:43.665  3390  3581 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{21ea0dab u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t40} time:1597988
03-24 15:52:43.670  3390  4044 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=14, mSplitNum[1]=26, mSplitNum[2]=38, mBgSplitQueueNum=3 divideNum= 12 r.nextReceiver= 2 receivers.size=50
03-24 15:52:43.670  3390  4044 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
03-24 15:52:43.670  3390  3593 D PackageManager: Resopt: Clean up res: /data/app/com.test.thalitest-1/base.apk
03-24 15:52:43.670  3390  3593 D PackageManager: delete codoeFile: 
03-24 15:52:43.675  7138 12955 I KLMS-2.5.262: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
03-24 15:52:43.675  7138 12955 I KLMS-2.5.262: : MDMBridge.getAllLicenseInfoFromSDK()
03-24 15:52:43.675  3390  3593 D AASAuninstall: userId = 0, info.removedAppID = 10011, info.uid = 10011, packageName = com.test.thalitest
03-24 15:52:43.680  3390  3593 I AASA_removePackage: UID=10011 Target=com.test.thalitest
03-24 15:52:43.680  7138 12955 E KLMS-2.5.262: : arr si null
03-24 15:52:43.680  3390  3593 D PackageManager: result of delete: 1{988775686}
03-24 15:52:43.680  3390  4044 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{15dd1024 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{1483c585 6825:com.samsung.aasaservice/1000}
03-24 15:52:43.680  6825  6825 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
03-24 15:52:43.680  6825  6825 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
03-24 15:52:43.680 12918 12918 I art     : System.exit called, status: 0
03-24 15:52:43.680 12918 12918 I AndroidRuntime: VM exiting with result code 0.
03-24 15:52:43.680  6825  6825 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:334)
03-24 15:52:43.680  6825  6825 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
03-24 15:52:43.680  6825  6825 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3509)
03-24 15:52:43.680  6825  6825 W System.err: 	at android.app.ActivityThread.access$1900(ActivityThread.java:197)
03-24 15:52:43.680  6825  6825 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1758)
03-24 15:52:43.680  6825  6825 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-24 15:52:43.680  6825  6825 W System.err: 	at android.os.Looper.loop(Looper.java:145)
03-24 15:52:43.680  6825  6825 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6872)
03-24 15:52:43.680  6825  6825 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
03-24 15:52:43.680  6825  6825 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-24 15:52:43.680  6825  6825 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
03-24 15:52:43.680  6825  6825 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
03-24 15:52:43.685  3390  3572 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
03-24 15:52:43.685  3390  3593 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
03-24 15:52:43.685  3390  3593 D PackageManager: userId{-1}
03-24 15:52:43.685  3390  3593 D PackageManager: andCode{true}
03-24 15:52:43.685  3390  3390 D RCPManagerService: PackageReceiver onReceive()
03-24 15:52:43.685  3390  3390 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
03-24 15:52:43.690  3390  3390 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
03-24 15:52:43.690  3390  3390 I OTPFW   : PackageRemovalReceiver::onReceive Enter
03-24 15:52:43.690  3390  3390 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10011 container id = 0
03-24 15:52:43.690  7138 12955 D KLMS-2.5.262: : DataSource(): Fetched Data from data base count : 0
03-24 15:52:43.690  7138 12955 I KLMS-2.5.262: : listeningToPackageRemovedforELM().END
03-24 15:52:43.690  7138 12955 I KLMS-2.5.262: : Systemprocess(): listeningToPackageRemovedforKLM().START
03-24 15:52:43.690  7138 12955 I KLMS-2.5.262: : Systemprocess(): .pkgName: com.test.thalitest
03-24 15:52:43.690  3390  3572 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver}
03-24 15:52:43.690  3390  3572 W BroadcastQueue: android.os.TransactionTooLargeException
03-24 15:52:43.690  3390  3572 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
03-24 15:52:43.690  3390  3572 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:511)
03-24 15:52:43.690  3390  3572 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:1109)
03-24 15:52:43.690  3390  3572 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:404)
03-24 15:52:43.690  3390  3572 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1510)
03-24 15:52:43.690  3390  3572 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue$BroadcastHandler.handleMessage(BroadcastQueue.java:221)
03-24 15:52:43.690  3390  3572 W BroadcastQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-24 15:52:43.690  3390  3572 W BroadcastQueue: 	at android.os.Looper.loop(Looper.java:145)
03-24 15:52:43.690  3390  3572 W BroadcastQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-24 15:52:43.690  3390  3572 W BroadcastQueue: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
03-24 15:52:43.695  3390  3390 I OTPFW   : ProvisionData::getAllEntries Enter
03-24 15:52:43.695  3390  3390 E OTPFW   : ProvisionData::getAllEntries Table is empty
03-24 15:52:43.695  3390  3390 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
03-24 15:52:43.695  3390  3390 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
03-24 15:52:43.700  3390  3572 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-24 15:52:43.700  3390  3572 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-24 15:52:43.700  3390  3572 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-24 15:52:43.700  3390  3572 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-24 15:52:43.710 12957 12957 E Zygote  : MountEmulatedStorage()
03-24 15:52:43.710 12957 12957 I libpersona: KNOX_SDCARD checking this for 10042
03-24 15:52:43.710 12957 12957 E Zygote  : v2
03-24 15:52:43.710 12957 12957 I libpersona: KNOX_SDCARD not a persona
03-24 15:52:43.715 12957 12957 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
03-24 15:52:43.715  3390  3572 I ActivityManager: Start proc 12957:com.samsung.android.sdk.samsunglink/u0a42 for broadcast-4 com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver
03-24 15:52:43.715 12957 12957 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
03-24 15:52:43.715 12957 12957 E Zygote  : accessInfo : 0
03-24 15:52:43.720 12957 12957 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
03-24 15:52:43.720  3390  3572 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-24 15:52:43.720  3390  3572 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-24 15:52:43.720  3390  3572 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-24 15:52:43.720  3390  3572 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-24 15:52:43.725 10674 12943 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
03-24 15:52:43.740 12971 12971 E Zygote  : MountEmulatedStorage()
03-24 15:52:43.740 12971 12971 E Zygote  : v2
03-24 15:52:43.740 12971 12971 I libpersona: KNOX_SDCARD checking this for 1000
03-24 15:52:43.740 12971 12971 I libpersona: KNOX_SDCARD not a persona
03-24 15:52:43.740 12971 12971 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
03-24 15:52:43.745 12971 12971 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
03-24 15:52:43.745 12971 12971 E Zygote  : accessInfo : 0
03-24 15:52:43.745 12971 12971 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-24 15:52:43.750  3390  3572 I ActivityManager: Start proc 12971:com.samsung.android.sm/1000 for broadcast-4 com.samsung.android.sm/.ui.security.MonitorReceiver
03-24 15:52:43.755  3390  3390 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
03-24 15:52:43.755  3390  3390 V EnterpriseBillingPolicy: uID is 10011
03-24 15:52:43.755  3390  3390 V EnterpriseBillingPolicy: Removed Packageuid is0
03-24 15:52:43.755  3390  3390 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
03-24 15:52:43.755  3390  3390 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
03-24 15:52:43.755  3390  3390 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
03-24 15:52:43.755  3390  3390 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
03-24 15:52:43.755  3390  3390 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
03-24 15:52:43.755  3390  3390 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
03-24 15:52:43.755  3390  3390 D SdpManagerService:  ActionReceiver::onReceive() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
03-24 15:52:43.760  3390  3390 D SdpManagerService: ACTION_PACKAGE_REMOVED Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) } DATA= package:com.test.thalitest UID 1000 userId 0
03-24 15:52:43.760  3390  3390 D SdpManagerService: ACTION_PACKAGE_REMOVED packageName:: com.test.thalitest
03-24 15:52:43.765  9682 12982 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.test.thalitest
03-24 15:52:43.765  3390  3572 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-24 15:52:43.765  9682 12982 W System.err: remove failed: EACCES (Permission denied) : /storage/extSdCard/Android/data/com.test.thalitest
03-24 15:52:43.765  3390  3572 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-24 15:52:43.765  3390  3572 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-24 15:52:43.765  9682 12982 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.test.thalitest
03-24 15:52:43.765  3390  3572 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-24 15:52:43.765  9682 12982 W System.err: remove failed: EACCES (Permission denied) : /storage/extSdCard/Android/media/com.test.thalitest
03-24 15:52:43.765  9682 12982 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/obb/com.test.thalitest
03-24 15:52:43.765  9682 12982 W System.err: remove failed: EACCES (Permission denied) : /storage/extSdCard/Android/obb/com.test.thalitest
03-24 15:52:43.765 10674 12943 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-24 15:52:43.765 10674 12943 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-24 15:52:43.765 10674 12943 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-24 15:52:43.765 10674 12943 W ResourcesManager: Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
03-24 15:52:43.770 12957 12957 D TimaKeyStoreProvider: TimaSignature is unavailable
03-24 15:52:43.770  3390  3390 D EnterprisePartitionManager: SND -> {secure_fs remove_enc_dir}
03-24 15:52:43.770  3390  3595 D EnterprisePartitionManager: RCV <-
03-24 15:52:43.770  3390  3390 D EnterprisePartitionManager: RMV <-
03-24 15:52:43.770 12957 12957 D ActivityThread: Added TimaKeyStore provider
03-24 15:52:43.780 12971 12971 D TimaKeyStoreProvider: TimaSignature is unavailable
03-24 15:52:43.780 12971 12971 D ActivityThread: Added TimaKeyStore provider
03-24 15:52:43.785 12989 12989 E Zygote  : MountEmulatedStorage()
03-24 15:52:43.785 12989 12989 I libpersona: KNOX_SDCARD checking this for 1000
03-24 15:52:43.785 12989 12989 E Zygote  : v2
03-24 15:52:43.785 12989 12989 I libpersona: KNOX_SDCARD not a persona
03-24 15:52:43.785  7138 12955 D KLMS-2.5.262: : KLMSUtility(): IsPackageExistInDevice().mAppInfoList: 322
03-24 15:52:43.790  3390  3572 I ActivityManager: Start proc 12989:com.sec.android.app.popupuireceiver/1000 for broadcast-4 com.sec.android.app.popupuireceiver/.PopupuiReceiver
03-24 15:52:43.785  7138 12955 D KLMS-2.5.262: : KLMSSharedPreferences(): deleteNotificationAppList().pkgName: com.test.thalitest
03-24 15:52:43.795  3390  4044 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{15dd1024 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{816d256 3390:system/1000}
03-24 15:52:43.785  7138 12955 I KLMS-2.5.262: : KLMSSharedPreferences(): getNotificationAppList(): null
03-24 15:52:43.795  3390  6051 D SSRM:bd : MSG_TYPE_APP_REMOVED::
03-24 15:52:43.785  7138 12955 I KLMS-2.5.262: : Systemprocess(): Notification App List is Null. Remove Notification.
03-24 15:52:43.785 12989 12989 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
03-24 15:52:43.790 12989 12989 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
03-24 15:52:43.790 12989 12989 E Zygote  : accessInfo : 0
03-24 15:52:43.790 12989 12989 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-24 15:52:43.790  7138 12955 D KLMS-2.5.262: : DataSource(): Fetched Data from data base count : 0
03-24 15:52:43.790  7138 12955 I KLMS-2.5.262: : Systemprocess(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
03-24 15:52:43.795  7138 12955 I KLMS-2.5.262: : Systemprocess(): listeningToPackageRemovedforKLM().END
03-24 15:52:43.795  7138 12955 I KLMS-2.5.262: : Systemprocess(): listeningToPackageRemoved().END
03-24 15:52:43.795  3390  3390 E EnterprisePartitionManager: Failed to send commandcom.sec.knox.container.util.DaemonConnector$DaemonArgumentException: command 'secure_fs' failed with '500 3 Command not recognized'
03-24 15:52:43.795  3390  3390 W System.err: java.io.FileNotFoundException: /data/system/users/sdp_engine_list.xml: open failed: ENOENT (No such file or directory)
03-24 15:52:43.795  3390  3390 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-24 15:52:43.795  3390  3390 W System.err: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
03-24 15:52:43.795  3390  3390 W System.err: 	at com.android.server.SdpManagerService$SdpEngineDatabase$EngineListHandler.getEngineListLocked(SdpManagerService.java:1514)
03-24 15:52:43.795  3390  3390 W System.err: 	at com.android.server.SdpManagerService$SdpEngineDatabase$EngineListHandler.access$1100(SdpManagerService.java:1434)
03-24 15:52:43.795  3390  3390 W System.err: 	at com.android.server.SdpManagerService$SdpEngineDatabase.getEngineListLocked(SdpManagerService.java:1418)
03-24 15:52:43.795  3390  3390 W System.err: 	at com.android.server.SdpManagerService$SdpEngineDatabase.access$2200(SdpManagerService.java:1393)
03-24 15:52:43.795  3390  3390 W System.err: 	at com.android.server.SdpManagerService.handlePkgRemoved(SdpManagerService.java:2647)
03-24 15:52:43.795  3390  3390 W System.err: 	at com.android.server.SdpManagerService.access$2500(SdpManagerService.java:137)
03-24 15:52:43.795  3390  3390 W System.err: 	at com.android.server.SdpManagerService$ActionReceiver.onReceive(SdpManagerService.java:2719)
03-24 15:52:43.795  3390  3390 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:972)
03-24 15:52:43.795  3390  3390 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
03-24 15:52:43.795  3390  3390 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-24 15:52:43.795  3390  3390 W System.err: 	at android.os.Looper.loop(Looper.java:145)
03-24 15:52:43.795  3390  3390 W System.err: 	at com.android.server.SystemServer.run(SystemServer.java:469)
03-24 15:52:43.795  3390  3390 W System.err: 	at com.android.server.SystemServer.main(SystemServer.java:353)
03-24 15:52:43.795  3390  3390 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
03-24 15:52:43.795  3390  3390 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-24 15:52:43.795  3390  3390 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
03-24 15:52:43.795  3390  3390 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
03-24 15:52:43.795  3390  3390 W System.err: Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
03-24 15:52:43.795  3390  3390 W System.err: 	at libcore.io.Posix.open(Native Method)
03-24 15:52:43.795  3390  3390 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-24 15:52:43.795  3390  3390 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-24 15:52:43.795  3390  3390 W System.err: 	... 18 more
03-24 15:52:43.795  3390  3390 E SdpManagerService: failed to get engine list
03-24 15:52:43.795  3390  3390 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
03-24 15:52:43.795  3390  3390 V EnterpriseBillingPolicy: uID is 10011
03-24 15:52:43.795  3390  3390 V EnterpriseBillingPolicy: Removed Packageuid is0
03-24 15:52:43.795  3390  3390 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
03-24 15:52:43.800  3390  3390 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
03-24 15:52:43.800  3390  3390 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
03-24 15:52:43.800  3390  3390 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
03-24 15:52:43.800  3390  3390 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
03-24 15:52:43.800  3390  3390 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
03-24 15:52:43.805  2902  2902 I art     : Explicit concurrent mark sweep GC freed 8754(372KB) AllocSpace objects, 0(0B) LOS objects, 72% free, 1529KB/5MB, paused 437us total 17.494ms
03-24 15:52:43.815  2902  2902 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 72% free, 1529KB/5MB, paused 306us total 10.079ms
03-24 15:52:43.820  3390  3429 V BroadcastQueue: [backgroundsplit_0] Process cur broadcast BroadcastRecord{e3d7c81 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{2870aa2b 12957:com.samsung.android.sdk.samsunglink/u0a42}
03-24 15:52:43.820  7138  7138 I KLMS-2.5.262: : KLMSIntentService(): onDestroy()
03-24 15:52:43.820 12989 12989 D TimaKeyStoreProvider: TimaSignature is unavailable
03-24 15:52:43.820 12989 12989 D ActivityThread: Added TimaKeyStore provider
03-24 15:52:43.830  2902  2902 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 72% free, 1529KB/5MB, paused 301us total 9.286ms
03-24 15:52:43.835  3390  4268 V BroadcastQueue: [backgroundsplit_1] Process cur broadcast BroadcastRecord{2ae8eb14 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{22445fbd 12971:com.samsung.android.sm/1000}
03-24 15:52:43.835  3390  3390 D KnoxTimeoutHandler: handleActiveUserChange for user 0
03-24 15:52:43.835  3390  3390 E EnterpriseSharedDevicePolicy: isSharedDeviceEnabled
03-24 15:52:43.835  3390  3390 I EnterpriseSharedDevicePolicy: isSharedDeviceEnabled in Service
03-24 15:52:43.835 12957 12957 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-24 15:52:43.835 12957 12957 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
03-24 15:52:43.840  3390  3390 I EnterpriseSharedDevicePolicy: Get Result: -1
03-24 15:52:43.840  3390  3390 I EnterpriseSharedDevicePolicy: status: false
03-24 15:52:43.840  3390  3390 I KnoxTimeoutHandler: Shared devices show user statefalse
03-24 15:52:43.840  3390  3390 D PersonaManagerService: getPersonasForUser(): returning null!
03-24 15:52:43.840  3390  3390 V AlarmManagerEXT: com.test.thalitest(10011) is removed.
03-24 15:52:43.845  3727  3727 D PanelView: There is/are notification(s) 
03-24 15:52:43.845  3390  3943 V BroadcastQueue: [backgroundsplit_2] Process cur broadcast BroadcastRecord{357689b2 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{13190d03 12989:com.sec.android.app.popupuireceiver/1000}
03-24 15:52:43.860 12971 12971 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-24 15:52:43.875  3390  3390 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{15dd1024 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{225e9812 6117:com.sec.android.service.health/u0a19}
03-24 15:52:43.875  6117  6117 D com.sec.android.service.health.upgrade.UninstallReceiver: onReceive()
03-24 15:52:43.875  6117  6117 I com.sec.android.service.health.upgrade.UninstallReceiver: onReceive called  PACKAGE_REMOVED package:com.test.thalitest
03-24 15:52:43.875  6117  6117 D com.sec.android.service.health.upgrade.UninstallReceiver: onReceive() : package name is not s health. Return !!!
03-24 15:52:43.875 12989 12989 D PopupuiReceiver: onReceive() getAction : android.intent.action.PACKAGE_REMOVED
03-24 15:52:43.880  3727  3727 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
03-24 15:52:43.880  3390  4044 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{15dd1024 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{af20ae3 10674:com.sec.android.widgetapp.locationwidget/u0a22}
03-24 15:52:43.885 10674 10674 D LocationWidgetApplication: getLastUiLocationId() : mLastUiLocationId = -100
03-24 15:52:43.885 12971 12971 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.sm/databases/lowpowercontext-system-db" with flag (131138) and mode_t (0) due to error (30)
03-24 15:52:43.885  3727  3727 D PanelView: There is/are notification(s) 
03-24 15:52:43.885  3727  3727 D PanelView: kidsfalse mQsExpansionEnabled:true
03-24 15:52:43.885  3390  3853 D SecContentProvider2: query(), uri = -1 selection = getSealedState
03-24 15:52:43.885 12971 12971 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.sm/databases/lowpowercontext-system-db'.
03-24 15:52:43.885 12971 12971 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-24 15:52:43.885 12971 12971 E SQLiteDatabase: #################################################################
03-24 15:52:43.885 12971 12971 E SQLiteDatabase: Error Code : 0 (SQLITE_OK)
03-24 15:52:43.885 12971 12971 E SQLiteDatabase: Caused By : not an error (code 0): Could not open the database in read/write mode.
03-24 15:52:43.885 12971 12971 E SQLiteDatabase: #################################################################
03-24 15:52:43.885 12971 12971 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-24 15:52:43.885 12971 12971 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-24 15:52:43.885 12971 12971 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-24 15:52:43.885 12971 12971 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-24 15:52:43.885 12971 12971 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-24 15:52:43.885 12971 12971 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-24 15:52:43.885 12971 12971 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-24 15:52:43.885 12971 12971 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-24 15:52:43.885 12971 12971 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-24 15:52:43.885 12971 12971 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1585)
03-24 15:52:43.885 12971 12971 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
03-24 15:52:43.885 12971 12971 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-24 15:52:43.885 12971 12971 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-24 15:52:43.885 12971 12971 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2441)
03-24 15:52:43.885 12971 12971 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.a(DataStore.java:86)
03-24 15:52:43.885 12971 12971 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextProvider.onCreate(LowpowerContextProvider.java:302)
03-24 15:52:43.885 12971 12971 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1737)
03-24 15:52:43.885 12971 12971 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
03-24 15:52:43.885 12971 12971 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:6413)
03-24 15:52:43.885 12971 12971 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:6008)
03-24 15:52:43.885 12971 12971 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5948)
03-24 15:52:43.885 12971 12971 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:197)
03-24 15:52:43.885 12971 12971 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1742)
03-24 15:52:43.885 12971 12971 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-24 15:52:43.885 12971 12971 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-24 15:52:43.885 12971 12971 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6872)
03-24 15:52:43.885 12971 12971 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
03-24 15:52:43.885 12971 12971 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-24 15:52:43.885 12971 12971 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
03-24 15:52:43.885 12971 12971 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
03-24 15:52:43.890  3390  4257 D SecContentProvider2: query(), uri = 15 selection = getSealedHideNotificationMessages
03-24 15:52:43.890  3727  3727 D PanelView: There is/are notification(s) 
03-24 15:52:43.890  3727  3727 D PanelView: kidsfalse mQsExpansionEnabled:true
03-24 15:52:43.890 12989 12989 I PopupuiReceiver_KNOX: getSealedHideNotificationMessages : 0
03-24 15:52:43.890 12971 12971 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.sm/databases/sm.db" with flag (131138) and mode_t (0) due to error (30)
03-24 15:52:43.890  3390  3425 D SecContentProvider2: query(), uri = 15 selection = getCheckCoverPopupState
03-24 15:52:43.890 12971 12971 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.sm/databases/sm.db'.
03-24 15:52:43.890 12971 12971 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-24 15:52:43.890 12971 12971 E SQLiteDatabase: #################################################################
03-24 15:52:43.890 12971 12971 E SQLiteDatabase: Error Code : 0 (SQLITE_OK)
03-24 15:52:43.890 12971 12971 E SQLiteDatabase: Caused By : not an error (code 0): Could not open the database in read/write mode.
03-24 15:52:43.890 12971 12971 E SQLiteDatabase: #################################################################
03-24 15:52:43.890 12971 12971 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-24 15:52:43.890 12971 12971 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-24 15:52:43.890 12971 12971 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-24 15:52:43.890 12971 12971 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-24 15:52:43.890 12971 12971 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-24 15:52:43.890 12971 12971 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-24 15:52:43.890 12971 12971 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-24 15:52:43.890 12971 12971 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-24 15:52:43.890 12971 12971 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-24 15:52:43.890 12971 12971 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1585)
03-24 15:52:43.890 12971 12971 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
03-24 15:52:43.890 12971 12971 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-24 15:52:43.890 12971 12971 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-24 15:52:43.890 12971 12971 E SQLiteDatabase: 	at com.samsung.android.sm.database.b.<init>(SmDatabaseHelper.java:55)
03-24 15:52:43.890 12971 12971 E SQLiteDatabase: 	at com.samsung.android.sm.database.b.a(SmDatabaseHelper.java:44)
03-24 15:52:43.890 12971 12971 E SQLiteDatabase: 	at com.samsung.android.sm.database.SmProvider.onCreate(SmProvider.java:78)
03-24 15:52:43.890 12971 12971 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1737)
03-24 15:52:43.890 12971 12971 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
03-24 15:52:43.890 12971 12971 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:6413)
03-24 15:52:43.890 12971 12971 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:6008)
03-24 15:52:43.890 12971 12971 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5948)
03-24 15:52:43.890 12971 12971 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:197)
03-24 15:52:43.890 12971 12971 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1742)
03-24 15:52:43.890 12971 12971 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-24 15:52:43.890 12971 12971 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-24 15:52:43.890 12971 12971 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6872)
03-24 15:52:43.890 12971 12971 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
03-24 15:52:43.890 12971 12971 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-24 15:52:43.890 12971 12971 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
03-24 15:52:43.890 12971 12971 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
03-24 15:52:43.890 12971 12971 D AndroidRuntime: Shutting down VM
03-24 15:52:43.890 12989 12989 I PopupuiReceiver_KNOX: getCheckCoverPopupState : false
03-24 15:52:43.890 12989 12989 D PopupuiReceiver: Action package removed
03-24 15:52:43.890 12971 12971 E AndroidRuntime: FATAL EXCEPTION: main
03-24 15:52:43.890 12971 12971 E AndroidRuntime: Process: com.samsung.android.sm, PID: 12971
03-24 15:52:43.890 12971 12971 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.samsung.android.sm.database.SmProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-24 15:52:43.890 12971 12971 E AndroidRuntime: #################################################################
03-24 15:52:43.890 12971 12971 E AndroidRuntime: Error Code : 0 (SQLITE_OK)
03-24 15:52:43.890 12971 12971 E AndroidRuntime: Caused By : not an error (code 0): Could not open the database in read/write mode.
03-24 15:52:43.890 12971 12971 E AndroidRuntime: #################################################################
03-24 15:52:43.890 12971 12971 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:6416)
03-24 15:52:43.890 12971 12971 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:6008)
03-24 15:52:43.890 12971 12971 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5948)
03-24 15:52:43.890 12971 12971 E AndroidRuntime: 	at android.app.ActivityThread.access$1700(ActivityThread.java:197)
03-24 15:52:43.890 12971 12971 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1742)
03-24 15:52:43.890 12971 12971 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-24 15:52:43.890 12971 12971 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
03-24 15:52:43.890 12971 12971 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6872)
03-24 15:52:43.890 12971 12971 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
03-24 15:52:43.890 12971 12971 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-24 15:52:43.890 12971 12971 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
03-24 15:52:43.890 12971 12971 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
03-24 15:52:43.890 12971 12971 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-24 15:52:43.890 12971 12971 E AndroidRuntime: #################################################################
03-24 15:52:43.890 12971 12971 E AndroidRuntime: Error Code : 0 (SQLITE_OK)
03-24 15:52:43.890 12971 12971 E AndroidRuntime: Caused By : not an error (code 0): Could not open the database in read/write mode.
03-24 15:52:43.890 12971 12971 E AndroidRuntime: #################################################################
03-24 15:52:43.890 12971 12971 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-24 15:52:43.890 12971 12971 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-24 15:52:43.890 12971 12971 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-24 15:52:43.890 12971 12971 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-24 15:52:43.890 12971 12971 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-24 15:52:43.890 12971 12971 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-24 15:52:43.890 12971 12971 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-24 15:52:43.890 12971 12971 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-24 15:52:43.890 12971 12971 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-24 15:52:43.890 12971 12971 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1585)
03-24 15:52:43.890 12971 12971 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
03-24 15:52:43.890 12971 12971 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-24 15:52:43.890 12971 12971 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-24 15:52:43.890 12971 12971 E AndroidRuntime: 	at com.samsung.android.sm.database.b.<init>(SmDatabaseHelper.java:55)
03-24 15:52:43.890 12971 12971 E AndroidRuntime: 	at com.samsung.android.sm.database.b.a(SmDatabaseHelper.java:44)
03-24 15:52:43.890 12971 12971 E AndroidRuntime: 	at com.samsung.android.sm.database.SmProvider.onCreate(SmProvider.java:78)
03-24 15:52:43.890 12971 12971 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1737)
03-24 15:52:43.890 12971 12971 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
03-24 15:52:43.890 12971 12971 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:6413)
03-24 15:52:43.890 12971 12971 E AndroidRuntime: 	... 11 more
03-24 15:52:43.895  3390  3429 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-24 15:52:43.895  3390  3429 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-24 15:52:43.895  3390  3429 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-24 15:52:43.895  3390  3429 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-24 15:52:43.910 13004 13004 E Zygote  : MountEmulatedStorage()
03-24 15:52:43.910 13004 13004 E Zygote  : v2
03-24 15:52:43.910 13004 13004 I libpersona: KNOX_SDCARD checking this for 1000
03-24 15:52:43.910 13004 13004 I libpersona: KNOX_SDCARD not a persona
03-24 15:52:43.915 13004 13004 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
03-24 15:52:43.915  3390  3429 I ActivityManager: Start proc 13004:com.sec.pcw.device/1000 for broadcast-3 com.sec.pcw.device/.receiver.SYSTEMReceiver
03-24 15:52:43.920 13004 13004 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
03-24 15:52:43.920 13004 13004 E Zygote  : accessInfo : 0
03-24 15:52:43.920 13004 13004 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-24 15:52:43.920 12957 12957 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.sdk.samsunglink/databases/asp.db" with flag (131138) and mode_t (0) due to error (30)
03-24 15:52:43.925 12957 12957 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.sdk.samsunglink/databases/asp.db'.
03-24 15:52:43.925 12957 12957 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-24 15:52:43.925 12957 12957 E SQLiteDatabase: #################################################################
03-24 15:52:43.925 12957 12957 E SQLiteDatabase: Error Code : 0 (SQLITE_OK)
03-24 15:52:43.925 12957 12957 E SQLiteDatabase: Caused By : not an error (code 0): Could not open the database in read/write mode.
03-24 15:52:43.925 12957 12957 E SQLiteDatabase: #################################################################
03-24 15:52:43.925 12957 12957 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-24 15:52:43.925 12957 12957 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-24 15:52:43.925 12957 12957 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-24 15:52:43.925 12957 12957 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-24 15:52:43.925 12957 12957 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-24 15:52:43.925 12957 12957 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-24 15:52:43.925 12957 12957 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-24 15:52:43.925 12957 12957 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-24 15:52:43.925 12957 12957 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-24 15:52:43.925 12957 12957 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1585)
03-24 15:52:43.925 12957 12957 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
03-24 15:52:43.925 12957 12957 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-24 15:52:43.925 12957 12957 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-24 15:52:43.925 12957 12957 E SQLiteDatabase: 	at com.mfluent.asp.datamodel.ASPMediaStoreProvider.onCreate(SourceFile:471)
03-24 15:52:43.925 12957 12957 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1737)
03-24 15:52:43.925 12957 12957 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
03-24 15:52:43.925 12957 12957 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:6413)
03-24 15:52:43.925 12957 12957 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:6008)
03-24 15:52:43.925 12957 12957 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5948)
03-24 15:52:43.925 12957 12957 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:197)
03-24 15:52:43.925 12957 12957 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1742)
03-24 15:52:43.925 12957 12957 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-24 15:52:43.925 12957 12957 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-24 15:52:43.925 12957 12957 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6872)
03-24 15:52:43.925 12957 12957 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
03-24 15:52:43.925 12957 12957 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-24 15:52:43.925 12957 12957 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
03-24 15:52:43.925 12957 12957 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
03-24 15:52:43.925 12957 12957 D AndroidRuntime: Shutting down VM
03-24 15:52:43.925 12957 12957 E AndroidRuntime: FATAL EXCEPTION: main
03-24 15:52:43.925 12957 12957 E AndroidRuntime: Process: com.samsung.android.sdk.samsunglink, PID: 12957
03-24 15:52:43.925 12957 12957 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.mfluent.asp.datamodel.ASPMediaStoreProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-24 15:52:43.925 12957 12957 E AndroidRuntime: #################################################################
03-24 15:52:43.925 12957 12957 E AndroidRuntime: Error Code : 0 (SQLITE_OK)
03-24 15:52:43.925 12957 12957 E AndroidRuntime: Caused By : not an error (code 0): Could not open the database in read/write mode.
03-24 15:52:43.925 12957 12957 E AndroidRuntime: #################################################################
03-24 15:52:43.925 12957 12957 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:6416)
03-24 15:52:43.925 12957 12957 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:6008)
03-24 15:52:43.925 12957 12957 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5948)
03-24 15:52:43.925 12957 12957 E AndroidRuntime: 	at android.app.ActivityThread.access$1700(ActivityThread.java:197)
03-24 15:52:43.925 12957 12957 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1742)
03-24 15:52:43.925 12957 12957 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-24 15:52:43.925 12957 12957 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
03-24 15:52:43.925 12957 12957 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6872)
03-24 15:52:43.925 12957 12957 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
03-24 15:52:43.925 12957 12957 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-24 15:52:43.925 12957 12957 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
03-24 15:52:43.925 12957 12957 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
03-24 15:52:43.925 12957 12957 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-24 15:52:43.925 12957 12957 E AndroidRuntime: #################################################################
03-24 15:52:43.925 12957 12957 E AndroidRuntime: Error Code : 0 (SQLITE_OK)
03-24 15:52:43.925 12957 12957 E AndroidRuntime: Caused By : not an error (code 0): Could not open the database in read/write mode.
03-24 15:52:43.925 12957 12957 E AndroidRuntime: #################################################################
03-24 15:52:43.925 12957 12957 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-24 15:52:43.925 12957 12957 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-24 15:52:43.925 12957 12957 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-24 15:52:43.925 12957 12957 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-24 15:52:43.925 12957 12957 E AndroidRuntime: 	at andro,id.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-24 15:52:43.925 12957 12957 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-24 15:52:43.925 12957 12957 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-24 15:52:43.925 12957 12957 E AndroidRuntime: 	at android.database.sqlite.SQLiteDat
```
