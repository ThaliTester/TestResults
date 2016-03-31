#### Test 646138038d447f5_thali08_samsung-SM-N910C Logs


```
--------- beginning of system
03-31 09:43:45.632  3424  3938 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-31 09:43:45.637  3424  3938 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
--------- beginning of main
03-31 09:43:45.652  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:43:45.637  3424  3938 D BatteryService: online:4, current avg:37, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
03-31 09:43:45.652  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:43:45.637  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 09:43:45.652  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
03-31 09:43:45.642  3424  3938 D BatteryService: stay LED for fully charged
03-31 09:43:45.642  3424  3424 I MotionRecognitionService: Plugged
03-31 09:43:45.642  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 09:43:45.667  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 09:43:45.642  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 09:43:45.667  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
03-31 09:43:45.642  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
03-31 09:43:45.662  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:43:45.677  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:43:45.677  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:43:45.677  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:43:46.087 11101 11101 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
03-31 09:43:46.097 11101 11101 D AndroidRuntime: CheckJNI is OFF
03-31 09:43:46.097 11101 11101 D AndroidRuntime: readGMSProperty: start
03-31 09:43:46.097 11101 11101 D AndroidRuntime: readGMSProperty: already setted!!
03-31 09:43:46.097 11101 11101 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-31 09:43:46.097 11101 11101 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-31 09:43:46.097 11101 11101 D AndroidRuntime: readGMSProperty: end
03-31 09:43:46.097 11101 11101 D AndroidRuntime: addProductProperty: start
03-31 09:43:46.312 11101 11101 E AffinityControl: AffinityControl: registerfunction enter
03-31 09:43:46.337 11101 11101 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-31 09:43:46.357  3424  3451 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
03-31 09:43:46.372  3424  3451 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-31 09:43:46.402  3424  3451 W ActivityManager: mDVFSHelper.acquire()
03-31 09:43:46.402  3424  3451 V WindowManager: addAppToken: AppWindowToken{9ebd599 token=Token{3d275ee0 ActivityRecord{10f7b4e3 u0 com.test.thalitest/.MainActivity t42}}} to stack=1 task=42 at 0
03-31 09:43:46.407  3424  3451 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 09:43:46.407  3424  3451 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 09:43:46.407  3424  3451 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 09:43:46.407  3424  3451 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 09:43:46.422  3424  3582 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-31 09:43:46.422  3424  3582 D PhoneWindow: *FMB* installDecor flags : -2122120936
03-31 09:43:46.427  3424  3582 D SecWifiDisplayUtil: Metadata value : none
03-31 09:43:46.437  3424  3582 V WindowManager: Adding window Window{23629f8 u0 d0 Starting com.test.thalitest} at 3 of 7 (after Window{e54828f u0 d0 com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity})
03-31 09:43:46.442  3424  3582 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-31 09:43:46.442  3424  3582 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
03-31 09:43:46.447  2861  2861 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=404, uhalitest
03-31 09:43:46.452  3424  3451 I ActivityManager: Start proc 11127:com.test.thalitest/u0a11 for activity com.test.thalitest/.MainActivity
03-31 09:43:46.457  3424  3451 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
03-31 09:43:46.457  3424  3451 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-31 09:43:46.457 11127 11127 E Zygote  : MountEmulatedStorage()
03-31 09:43:46.462  2891  4701 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
03-31 09:43:46.467  3424  3451 D InputDispatcher: Focused application set to: xxxx
03-31 09:43:46.467  3424  3451 D MultiWindowConverter: dismissGuide() : Before attaching the guide view, mForceDismissGuide : false
03-31 09:43:46.472 11127 11127 E Zygote  : v2
03-31 09:43:46.472 11127 11127 I libpersona: KNOX_SDCARD checking this for 10011
03-31 09:43:46.472 11127 11127 I libpersona: KNOX_SDCARD not a persona
03-31 09:43:46.477  3424  3451 D InputDispatcher: Focus left window: 6557
03-31 09:43:46.492 11101 11101 D AndroidRuntime: Shutting down VM
03-31 09:43:46.492 11127 11127 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
03-31 09:43:46.497 11127 11127 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
03-31 09:43:46.512 11127 11127 E Zygote  : accessInfo : 0
03-31 09:43:46.512 11127 11127 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-31 09:43:46.527  3424  3582 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3424 uid:1000
03-31 09:43:46.527  3424  3582 D PointerIcon: setMouseCustomIcon IconType is same.101
03-31 09:43:46.527  3424  3582 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3424 uid:1000
03-31 09:43:46.527  3424  3582 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
03-31 09:43:46.547 11127 11127 D TimaKeyStoreProvider: TimaSignature is unavailable
03-31 09:43:46.547 11127 11127 D ActivityThread: Added TimaKeyStore provider
03-31 09:43:46.552  3424  3837 D PowerManagerService: setKeyboardVisibility: false
03-31 09:43:46.552  3424  3580 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{23629f8 u0 d0 Starting com.test.thalitest}
03-31 09:43:46.557  3424  3837 D ActivityManager:  Launching com.test.thalitest, updated priority
03-31 09:43:46.567  3424  3837 I ActivityManager: Skip updateThumbnail for r=ActivityRecord{10f7b4e3 u0 com.test.thalitest/.MainActivity t42}
03-31 09:43:46.587  2861  3011 I SurfaceFlinger: id=12 Removed YUIInstallC (5/9)
03-31 09:43:46.587  2861 10836 I SurfaceFlinger: id=12 Removed YUIInstallC (-2/9)
03-31 09:43:46.592  6557  6557 V ActivityThread: updateVisibility : ActivityRecord{16558a6c token=android.os.BinderProxy@1af6ebf2 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
03-31 09:43:46.607  3424  6055 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
03-31 09:43:46.647 11127 11127 D SecWifiDisplayUtil: Metadata value : none
03-31 09:43:46.687 11127 11127 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
03-31 09:43:46.697 11127 11127 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 6194-6196)
03-31 09:43:46.697 11127 11127 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-31 09:43:46.717 11127 11127 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {294b1e15}
03-31 09:43:46.717 11127 11150 W System.err: remove failed: ENOENT (No such file or directory) : /data/data/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
03-31 09:43:46.717 11127 11127 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-31 09:43:46.717 11127 11127 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,03-31 09:43:46.737 11127 11127 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-31 09:43:46.737 11127 11127 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-31 09:43:46.737 11127 11127 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-31 09:43:46.762 11127 11127 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,03-31 09:43:46.762 11127 11127 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=37 off=50556 len=3379
03-31 09:43:46.762 11127 11127 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:38 off:7638088 len:1165478
,03-31 09:43:46.837 11127 11173 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,03-31 09:43:46.877 11127 11127 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-31 09:43:46.897 11127 11127 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-31 09:43:46.912 11127 11127 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-31 09:43:46.912 11127 11127 D PhoneWindow: *FMB* installDecor flags : -2139027200
,03-31 09:43:46.922 11127 11127 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,03-31 09:43:46.932 11127 11127 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-31 09:43:46.932 11127 11127 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-31 09:43:47.017 11127 11186 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,03-31 09:43:47.022  3424  4420 V WindowManager: Adding window Window{5301479 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity} at 3 of 8 (before Window{23629f8 u0 d0 Starting com.test.thalitest})
,03-31 09:43:47.022  3424  3837 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-31 09:43:47.022  3424  3837 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-31 09:43:47.022  3424  3837 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-31 09:43:47.022  3424  3424 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,03-31 09:43:47.027  3424  3424 E EnterpriseSharedDevicePolicy: isSharedDeviceEnabled
,03-31 09:43:47.027  3424  3424 I EnterpriseSharedDevicePolicy: isSharedDeviceEnabled in Service
,03-31 09:43:47.027  3424  3424 I EnterpriseSharedDevicePolicy: Get Result: -1
03-31 09:43:47.027  3424  3424 I EnterpriseSharedDevicePolicy: status: false
03-31 09:43:47.027  3424  3424 D PersonaManagerService: getPersonasForUser(): returning null!
03-31 09:43:47.027  3424  3424 I KnoxTimeoutHandler: Shared devices show user statefalse
,03-31 09:43:47.037 11127 11127 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-31 09:43:47.037 11127 11127 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,03-31 09:43:47.042 11127 11127 D SecWifiDisplayUtil: Metadata value : none
,03-31 09:43:47.052  2861  2861 I SurfaceFlinger: id=15 createSurf (1x1),1 flag=404, NainActivit
,03-31 09:43:47.052  3424  3732 D MultiWindowConverter: dismissGuide() : Before attaching the guide view, mForceDismissGuide : false
,03-31 09:43:47.062  3424  3732 D InputDispatcher: Focus entered window: 11127
,03-31 09:43:47.067  3424  3582 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3424 uid:1000
03-31 09:43:47.067  3424  3582 D PointerIcon: setMouseCustomIcon IconType is same.101
03-31 09:43:47.067  3424  3582 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3424 uid:1000
03-31 09:43:47.067  3424  3582 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
03-31 09:43:47.067 11127 11127 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
03-31 09:43:47.067 11127 11186 I OpenGLRenderer: Initialized EGL, version 1.4
,03-31 09:43:47.072 11127 11186 I OpenGLRenderer: HWUI protection enabled for context ,  &this =0xae42fb50 ,&mEglDisplay = 1 , &mEglConfig = -1266798320 
,03-31 09:43:47.072 11127 11186 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
03-31 09:43:47.072 11127 11186 D OpenGLRenderer: Enabling debug mode 0
,03-31 09:43:47.072 11127 11186 D mali_winsys: new_window_surface returns 0x3000,  [1440x2560]-format:1
,03-31 09:43:47.077 11127 11127 V ActivityThread: updateVisibility : ActivityRecord{28f4313d token=android.os.BinderProxy@1593d6e7 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,03-31 09:43:47.132  3424  3816 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-31 09:43:47.137  3424  3582 I ActivityManager: Displayed Component not be shown by security: +555ms (total +1m37s603ms)
,03-31 09:43:47.137  3723  3723 D PanelView: There is/are notification(s) 
,03-31 09:43:47.142  3424  3582 W ActivityManager: mDVFSHelper.release()
,03-31 09:43:47.142  3424  3582 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{10f7b4e3 u0 com.test.thalitest/.MainActivity t42} time:196642
03-31 09:43:47.142  2861  3011 I SurfaceFlinger: id=14 Removed uhalitest (7/9)
,03-31 09:43:47.142  2861 10836 I SurfaceFlinger: id=14 Removed uhalitest (-2/9)
,03-31 09:43:47.167 11127 11127 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,03-31 09:43:47.167 11127 11127 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1593d6e7 time:196667
,03-31 09:43:47.192 11127 11127 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 11127
,03-31 09:43:47.202  3424  6055 D SSRM:n  : SIOP:: AP = 260, PST = 267 (W:14), CUR = 37, LCD = 0
,03-31 09:43:47.292 11127 11127 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-31 09:43:47.367 11127 11191 D jxcore_app_log: JniHelper::setJavaVM(0xb449d200), pthread_self() = -1626310528
,03-31 09:43:47.377 11127 11191 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-31 09:43:47.377 11127 11191 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-31 09:43:47.377 11127 11191 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-31 09:43:47.377 11127 11191 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-31 09:43:47.377 11127 11191 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-31 09:43:47.377 11127 11191 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ee5d6e2 added. We now have 1 listener(s)
,03-31 09:43:47.377 11127 11191 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: E0:DB:10:14:E2:C0
,03-31 09:43:47.382 11127 11191 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
,03-31 09:43:47.382 11127 11191 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
03-31 09:43:47.382 11127 11191 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
03-31 09:43:47.382 11127 11150 W System.err: remove failed: ENOENT (No such file or directory) : /data/data/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,03-31 09:43:47.387 11127 11191 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-31 09:43:47.387 11127 11191 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-31 09:43:47.387 11127 11191 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-31 09:43:47.387 11127 11191 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: E0:DB:10:14:E2:C0
03-31 09:43:47.387 11127 11191 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-31 09:43:47.387 11127 11191 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-31 09:43:47.387 11127 11191 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
03-31 09:43:47.387 11127 11191 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-31 09:43:47.387 11127 11191 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-31 09:43:47.387 11127 11191 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-31 09:43:47.387 11127 11191 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-31 09:43:47.387 11127 11191 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25ad0da9 added. We now have 1 listener(s)
03-31 09:43:47.387 11127 11191 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-31 09:43:47.387 11127 11191 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,03-31 09:43:47.392 11127 11191 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
03-31 09:43:47.392 11127 11191 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
03-31 09:43:47.392 11127 11191 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-31 09:43:47.392 11127 11191 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,03-31 09:43:47.392 11127 11191 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-31 09:43:47.397 11127 11191 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is E0:DB:10:14:E2:C0
,03-31 09:43:47.402 11127 11191 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 09:43:47.402 11127 11191 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 09:43:47.402 11127 11191 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 09:43:47.402 11127 11191 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 09:43:47.402 11127 11191 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 09:43:47.402 11127 11191 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 09:43:47.402 11127 11191 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 09:43:47.402 11127 11191 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-31 09:43:47.402 11127 11191 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-31 09:43:47.402 11127 11191 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-31 09:43:47.402 11127 11191 I io.jxcore.node.LifeCycleMonitor: start: OK
,03-31 09:43:47.402 11127 11127 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-31 09:43:47.407 11127 11127 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-31 09:43:47.452 11127 11127 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-31 09:43:47.817 11127 11197 W jxcore-log: Initializing JXcore engine
03-31 09:43:47.817 11127 11197 W jxcore-log: JXcore engine is ready
,03-31 09:43:47.847  4800  4800 E auditd  : In denial and Property audit_ondenial is set to 1 
03-31 09:43:47.847  4800  4800 E audit   : type=1400 msg=audit(1459410227.842:196): avc:  denied  { ioctl } for  pid=11197 comm="Thread-1524" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3227 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
03-31 09:43:47.847  3424  3578 D SecurityLogAgent:SEDenialService: Got Modify Event and sending Denial Intent foraudit.log
,03-31 09:43:47.847  4800  4800 E audit   :  SEPF_SM-N910C_5.1.1_0038
03-31 09:43:47.847  4800  4800 E audit   : type=1300 msg=audit(1459410227.842:196): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=2 a3=970008d8 items=0 ppid=2899 ppcomm=main pid=11197 auid=4294967295 uid=10011 gid=10011 euid=10011 suid=10011 fsuid=10011 egid=10011 sgid=10011 fsgid=10011 ses=4294967295 tty=(none) comm="Thread-1524" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
03-31 09:43:47.847  4800  4800 E audit   : type=1320 msg=audit(1459410227.842:196): 
,03-31 09:43:47.847  3424  3578 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.android.server.SEDenialService$AuditFileObserver.onEvent:80 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,03-31 09:43:47.847  3424  3578 D SecurityLogAgent:SEDenialService: audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,03-31 09:43:47.852  3424  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 09:43:47.852  3424  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 09:43:47.852 11127 11197 W jxcore-log: Starting JXcore engine
03-31 09:43:47.852  3424  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 09:43:47.852  3424  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-31 09:43:47.862 11198 11198 E Zygote  : MountEmulatedStorage()
03-31 09:43:47.862 11198 11198 E Zygote  : v2
03-31 09:43:47.862 11198 11198 I libpersona: KNOX_SDCARD checking this for 1000
03-31 09:43:47.862 11198 11198 I libpersona: KNOX_SDCARD not a persona
,03-31 09:43:47.862 11198 11198 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
,03-31 09:43:47.862  3424  3574 I ActivityManager: Start proc 11198:com.samsung.android.securitylogagent/1000 for broadcast-3 com.samsung.android.securitylogagent/.receivers.SeDenialReceiver
,03-31 09:43:47.867 11198 11198 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
03-31 09:43:47.867 11198 11198 E Zygote  : accessInfo : 0
03-31 09:43:47.867 11198 11198 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-31 09:43:47.882 11198 11198 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-31 09:43:47.882 11198 11198 D ActivityThread: Added TimaKeyStore provider
,03-31 09:43:47.892  3424  3938 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7d25fed u0 samsung.intent.action.knox.DENIAL_NOTIFICATION} DELIVERED for app ProcessRecord{c1b3e22 11198:com.samsung.android.securitylogagent/1000}
,03-31 09:43:47.902 11127 11197 W jxcore-log: Platform android
03-31 09:43:47.902 11127 11197 W jxcore-log: 
03-31 09:43:47.902 11127 11197 W jxcore-log: Process ARCH arm
03-31 09:43:47.902 11127 11197 W jxcore-log: 
,03-31 09:43:47.907 11198 11198 D SecurityLogAgent:  SeDenialReceiver : Intent received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,03-31 09:43:47.912 11198 11198 D SecurityLogAgent:  SeDenialReceiver : File path = null
,03-31 09:43:47.912  3424  3453 I ActivityManager: Killing 10117:com.sec.android.app.myfiles/u0a53 (adj 15): emptyCount ##31
,03-31 09:43:47.997 11127 11197 I jxcore-log: JXcore Cordova bridge is ready!
03-31 09:43:47.997 11127 11197 I jxcore-log: 
03-31 09:43:47.997 11127 11197 W jxcore-log: JXcore engine is started
,03-31 09:43:48.002 11127 11191 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-31 09:43:48.002 11127 11127 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-31 09:43:49.417  3424  3689 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/42_task.xml.bak
,03-31 09:43:49.852  3424  3617 V AlarmManager: waitForAlarm result :4
,03-31 09:43:49.857  3424  3574 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e820de9 u0 null} DELIVERED for app ProcessRecord{2e3370c7 4616:com.google.android.gms/u0a14}
,03-31 09:43:49.862  3424  4027 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-31 09:43:49.877  4616 11214 I EventLogService: Aggregate from 1459408429795 (log), 1459408429795 (data)
,03-31 09:43:49.932  3424  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 09:43:49.932  3424  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 09:43:49.932  3424  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 09:43:49.932  3424  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-31 09:43:49.942 11215 11215 E Zygote  : MountEmulatedStorage()
03-31 09:43:49.942 11215 11215 I libpersona: KNOX_SDCARD checking this for 1000
03-31 09:43:49.942 11215 11215 E Zygote  : v2
03-31 09:43:49.942 11215 11215 I libpersona: KNOX_SDCARD not a persona
03-31 09:43:49.947 11215 11215 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
,03-31 09:43:49.947 11215 11215 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
03-31 09:43:49.947 11215 11215 E Zygote  : accessInfo : 0
03-31 09:43:49.947 11215 11215 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-31 09:43:49.947  3424  3574 I ActivityManager: Start proc 11215:com.samsung.android.sm/1000 for broadcast-3 com.samsung.android.sm/.common.SmartManagerReceiver
,03-31 09:43:49.967 11215 11215 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-31 09:43:49.967 11215 11215 D ActivityThread: Added TimaKeyStore provider
03-31 09:43:49.972  3424  4420 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{391a6f7a u0 android.intent.action.DROPBOX_ENTRY_ADDED} DELIVERED for app ProcessRecord{1094d32b 11215:com.samsung.android.sm/1000}
03-31 09:43:49.977 11215 11215 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-31 09:43:49.997  3424  3837 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{25f73388 u0 android.intent.action.DROPBOX_ENTRY_ADDED} DELIVERED for app ProcessRecord{1094d32b 11215:com.samsung.android.sm/1000}
,03-31 09:43:49.997  3424  3837 I ActivityManager: Killing 10190:com.sec.android.app.soundalive/u0a59 (adj 15): emptyCount ##31
,03-31 09:43:53.812 11127 11197 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 09:43:53.812 11127 11197 I jxcore-log: 
,03-31 09:43:53.812 11127 11197 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 09:43:53.812 11127 11197 I jxcore-log: 
,03-31 09:43:53.817 11127 11197 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 09:43:53.817 11127 11197 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 09:43:53.817 11127 11197 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 09:43:53.817 11127 11197 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 09:43:53.817 11127 11197 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 09:43:53.817 11127 11197 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 09:43:53.817 11127 11197 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 09:43:53.817 11127 11197 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 09:43:53.817 11127 11197 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 09:43:53.822 11127 11197 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 09:43:53.822 11127 11197 I jxcore-log: 
,03-31 09:43:53.822 11127 11197 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 09:43:53.822 11127 11197 I jxcore-log: 
,03-31 09:43:54.142 11127 11197 I jxcore-log: Unit Test app is loaded
03-31 09:43:54.142 11127 11197 I jxcore-log: 
,03-31 09:43:54.147 11127 11197 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 09:43:54.147 11127 11197 I jxcore-log: 
,03-31 09:43:54.152 11127 11127 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,03-31 09:43:54.152 11127 11197 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,03-31 09:43:54.152 11127 11197 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
03-31 09:43:54.152 11127 11197 I jxcore-log: 
,03-31 09:43:54.152 11127 11197 I jxcore-log: My device name is: samsung-SM-N910C
03-31 09:43:54.152 11127 11197 I jxcore-log: 
,03-31 09:43:55.737  3424  4025 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-31 09:43:55.742  3424  4025 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:43:55.742  3424  4025 D BatteryService: online:4, current avg:-94, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-207
03-31 09:43:55.742  3424  4025 D BatteryService: stay LED for fully charged
03-31 09:43:55.742  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 09:43:55.742  3424  3424 I MotionRecognitionService: Plugged
03-31 09:43:55.742  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 09:43:55.742  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 09:43:55.742  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 09:43:55.742  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:43:55.742  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-31 09:43:55.742  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:43:55.747  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 09:43:55.747  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:43:55.762  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:43:55.762  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:43:55.762  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:43:55.762  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:43:56.457  3424  3590 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,03-31 09:43:56.462 11127 11197 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
03-31 09:43:56.462 11127 11197 I jxcore-log: 
,03-31 09:43:56.467  3424  3590 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,03-31 09:43:56.667 11127 11197 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
03-31 09:43:56.667 11127 11197 I jxcore-log: 
,03-31 09:43:56.672 11127 11197 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
03-31 09:43:56.672 11127 11197 I jxcore-log: 
,03-31 09:43:56.677 11127 11197 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
03-31 09:43:56.677 11127 11197 I jxcore-log: 
,03-31 09:43:56.697 11127 11197 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
03-31 09:43:56.697 11127 11197 I jxcore-log: 
,03-31 09:43:56.707 11127 11197 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
03-31 09:43:56.707 11127 11197 I jxcore-log: 
,03-31 09:43:56.707 11127 11197 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
03-31 09:43:56.707 11127 11197 I jxcore-log: 
,03-31 09:43:56.912  3424  3584 I PowerManagerService: [PWL] Off : 140s ago
,03-31 09:43:57.207  3424  6055 D SSRM:n  : SIOP:: AP = 290, PST = 267 (W:10), CUR = -94, LCD = 0
,03-31 09:43:57.917 11127 11197 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
03-31 09:43:57.917 11127 11197 I jxcore-log: 
,03-31 09:43:57.927 11127 11197 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
03-31 09:43:57.927 11127 11197 I jxcore-log: 
,03-31 09:43:57.932 11127 11197 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
03-31 09:43:57.932 11127 11197 I jxcore-log: 
,03-31 09:43:58.082 11127 11197 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
03-31 09:43:58.082 11127 11197 I jxcore-log: 
,03-31 09:43:58.122 11127 11197 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
03-31 09:43:58.122 11127 11197 I jxcore-log: 
,03-31 09:43:58.152 11127 11197 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
03-31 09:43:58.152 11127 11197 I jxcore-log: 
,03-31 09:43:58.157 11127 11197 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
03-31 09:43:58.157 11127 11197 I jxcore-log: 
,03-31 09:43:58.162 11127 11197 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
03-31 09:43:58.162 11127 11197 I jxcore-log: 
,03-31 09:43:58.167 11127 11197 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
03-31 09:43:58.167 11127 11197 I jxcore-log: 
,03-31 09:43:58.167 11127 11197 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
03-31 09:43:58.167 11127 11197 I jxcore-log: 
,03-31 09:43:58.177 11127 11197 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
03-31 09:43:58.177 11127 11197 I jxcore-log: 
,03-31 09:43:58.187 11127 11197 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
03-31 09:43:58.187 11127 11197 I jxcore-log: 
,03-31 09:43:58.237 11127 11197 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
03-31 09:43:58.237 11127 11197 I jxcore-log: 
,03-31 09:43:58.242 11127 11197 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
03-31 09:43:58.242 11127 11197 I jxcore-log: 
,03-31 09:43:58.252 11127 11197 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
03-31 09:43:58.252 11127 11197 I jxcore-log: 
,03-31 09:43:58.657 11127 11197 I jxcore-log: Connected to the test server
03-31 09:43:58.657 11127 11197 I jxcore-log: 
,03-31 09:43:59.992  3424  3617 V AlarmManager: waitForAlarm result :8
,03-31 09:44:00.547  3424  6086 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-31 09:44:05.882  3424  3965 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:44:05.882  3424  3965 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:44:05.882  3424  3965 D BatteryService: online:4, current avg:-35, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:56
,03-31 09:44:05.887  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 09:44:05.887  3424  3965 D BatteryService: stay LED for fully charged
,03-31 09:44:05.897  3424  3424 I MotionRecognitionService: Plugged
03-31 09:44:05.897  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 09:44:05.897  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 09:44:05.897  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 09:44:05.902  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 09:44:05.902  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-31 09:44:05.902  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:44:05.927  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 09:44:05.927  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:44:05.937  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 09:44:05.937  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:44:05.937  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:44:05.937  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:44:07.232  3424  6055 D SSRM:n  : SIOP:: AP = 280, PST = 265 (W:10), CUR = -35, LCD = 0
,03-31 09:44:13.412  3424  3861 E Watchdog: !@Sync 7 [03-31 09:44:13.416]
,03-31 09:44:16.022  3424  3837 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:44:16.022  3424  3837 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:44:16.022  3424  3837 D BatteryService: online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:61
,03-31 09:44:16.022  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 09:44:16.027  3424  3837 D BatteryService: stay LED for fully charged
,03-31 09:44:16.032  3424  3424 I MotionRecognitionService: Plugged
03-31 09:44:16.032  3424  3424 D MotionRecognitionService:   cableConnection= 1,
03-31 09:44:16.032  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-31 09:44:16.032  3424  3424 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 09:44:16.042  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 09:44:16.042  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:44:16.042  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
03-31 09:44:16.067  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 09:44:16.067  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
03-31 09:44:16.077  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:44:16.077  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:44:16.077  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:44:16.077  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:44:17.267  3424  6055 D SSRM:n  : SIOP:: AP = 270, PST = 266 (W:10), CUR = 15, LCD = 0
,03-31 09:44:20.552  3424  6086 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-31 09:44:26.157  3424  4045 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:44:26.157  3424  4045 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:44:26.157  3424  4045 D BatteryService: online:4, current avg:32, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
,03-31 09:44:26.157  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 09:44:26.167  3424  3424 I MotionRecognitionService: Plugged
03-31 09:44:26.167  3424  3424 D MotionRecognitionService:   cableConnection= 1,
,03-31 09:44:26.167  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 09:44:26.167  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 09:44:26.172  3424  4045 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 14ms,
,03-31 09:44:26.172  3424  4045 D BatteryService: stay LED for fully charged
,03-31 09:44:26.182  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-31 09:44:26.182  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
03-31 09:44:26.182  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:44:26.202  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 09:44:26.202  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:44:26.212  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:44:26.212  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:44:26.212  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:44:26.212  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:44:27.297  3424  6055 D SSRM:n  : SIOP:: AP = 270, PST = 267 (W:10), CUR = 32, LCD = 0
,03-31 09:44:36.297  3424  3451 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:44:36.297  3424  3451 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:44:36.297  3424  3451 D BatteryService: online:4, current avg:37, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:47
,03-31 09:44:36.297  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 09:44:36.302  3424  3451 D BatteryService: stay LED for fully charged
,03-31 09:44:36.307  3424  3424 I MotionRecognitionService: Plugged
03-31 09:44:36.307  3424  3424 D MotionRecognitionService:   cableConnection= 1,
03-31 09:44:36.307  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 09:44:36.307  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 09:44:36.317  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 09:44:36.317  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:44:36.317  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:44:36.337  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 09:44:36.337  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:44:36.347  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:44:36.347  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:44:36.347  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:44:36.347  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:44:36.912  3424  3584 I PowerManagerService: [PWL] Off : 180s ago
,03-31 09:44:37.327  3424  6055 D SSRM:n  : SIOP:: AP = 260, PST = 267 (W:12), CUR = 37, LCD = 0
,03-31 09:44:40.557  3424  6086 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-31 09:44:43.417  3424  3861 E Watchdog: !@Sync 8 [03-31 09:44:43.424]
,03-31 09:44:46.432  3424  3938 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-31 09:44:46.432  3424  3938 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:44:46.432  3424  3938 D BatteryService: online:4, current avg:37, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:54
,03-31 09:44:46.437  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 09:44:46.447  3424  3424 I MotionRecognitionService: Plugged
03-31 09:44:46.447  3424  3424 D MotionRecognitionService:   cableConnection= 1,
03-31 09:44:46.447  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
03-31 09:44:46.447  3424  3424 D MotionRecognitionService: skip setTransmitPower. ,
03-31 09:44:46.447  3424  3938 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 13ms
,03-31 09:44:46.447  3424  3938 D BatteryService: stay LED for fully charged
,03-31 09:44:46.462  2891  4701 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 ,
,03-31 09:44:46.462  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-31 09:44:46.462  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,03-31 09:44:46.462  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-31 09:44:46.482  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 09:44:46.482  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:44:46.497  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 09:44:46.497  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:44:46.497  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:44:46.497  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:44:47.357  3424  6055 D SSRM:n  : SIOP:: AP = 260, PST = 265 (W:12), CUR = 37, LCD = 0
,03-31 09:44:56.572  3424  3816 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:44:56.572  3424  3816 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:44:56.572  3424  3816 D BatteryService: online:4, current avg:35, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:32
,03-31 09:44:56.572  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 09:44:56.572  3424  3816 D BatteryService: stay LED for fully charged
,03-31 09:44:56.582  3424  3424 I MotionRecognitionService: Plugged,
03-31 09:44:56.582  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 09:44:56.582  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 09:44:56.582  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 09:44:56.592  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:44:56.592  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:44:56.592  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:44:56.602  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 09:44:56.602  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:44:56.617  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 09:44:56.617  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:44:56.617  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:44:56.617  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:44:57.382  3424  6055 D SSRM:n  : SIOP:: AP = 260, PST = 265 (W:12), CUR = 35, LCD = 0
,03-31 09:45:00.562  3424  6086 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-31 09:45:06.712  3424  3732 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:45:06.712  3424  3732 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:45:06.712  3424  3732 D BatteryService: online:4, current avg:34, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:32
,03-31 09:45:06.712  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 09:45:06.717  3424  3732 D BatteryService: stay LED for fully charged
,03-31 09:45:06.722  3424  3424 I MotionRecognitionService: Plugged,
03-31 09:45:06.722  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 09:45:06.722  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 09:45:06.722  3424  3424 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 09:45:06.732  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 09:45:06.732  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:45:06.732  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:45:06.752  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 09:45:06.752  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:45:06.762  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:45:06.762  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:45:06.762  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:45:06.762  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:45:07.407  3424  6055 D SSRM:n  : SIOP:: AP = 260, PST = 265 (W:12), CUR = 34, LCD = 0
,03-31 09:45:13.427  3424  3861 E Watchdog: !@Sync 9 [03-31 09:45:13.431]
,03-31 09:45:16.847  3424  3453 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:45:16.847  3424  3453 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:45:16.847  3424  3453 D BatteryService: online:4, current avg:32, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:44
,03-31 09:45:16.852  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 09:45:16.852  3424  3453 D BatteryService: stay LED for fully charged
,03-31 09:45:16.862  3424  3424 I MotionRecognitionService: Plugged,
03-31 09:45:16.862  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 09:45:16.862  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
,03-31 09:45:16.862  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 09:45:16.872  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 09:45:16.872  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-31 09:45:16.872  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:45:16.892  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 09:45:16.892  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:45:16.902  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 09:45:16.907  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:45:16.907  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:45:16.907  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:45:17.437  3424  6055 D SSRM:n  : SIOP:: AP = 260, PST = 265 (W:14), CUR = 32, LCD = 0
,03-31 09:45:20.567  3424  6086 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-31 09:45:21.917  3424  3584 I PowerManagerService: [PWL] Off : 225s ago
,03-31 09:45:26.987  3424  4025 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:45:26.987  3424  4025 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:45:26.987  3424  4025 D BatteryService: online:4, current avg:33, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
03-31 09:45:26.987  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 09:45:26.992  3424  4025 D BatteryService: stay LED for fully charged
,03-31 09:45:26.997  3424  3424 I MotionRecognitionService: Plugged
03-31 09:45:26.997  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 09:45:26.997  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 09:45:26.997  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 09:45:27.007  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 09:45:27.007  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:45:27.007  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:45:27.022  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 09:45:27.022  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:45:27.037  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:45:27.037  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:45:27.037  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:45:27.037  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:45:27.467  3424  6055 D SSRM:n  : SIOP:: AP = 260, PST = 265 (W:14), CUR = 33, LCD = 0
,03-31 09:45:37.122  3424  4027 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:45:37.127  3424  4027 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:45:37.127  3424  4027 D BatteryService: online:4, current avg:31, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
,03-31 09:45:37.127  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 09:45:37.127  3424  4027 D BatteryService: stay LED for fully charged
,03-31 09:45:37.137  3424  3424 I MotionRecognitionService: Plugged,
03-31 09:45:37.137  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 09:45:37.137  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 09:45:37.137  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 09:45:37.142  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 09:45:37.142  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:45:37.142  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:45:37.162  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 09:45:37.162  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:45:37.172  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:45:37.172  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:45:37.172  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:45:37.172  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:45:37.502  3424  6055 D SSRM:n  : SIOP:: AP = 260, PST = 262 (W:14), CUR = 31, LCD = 0
,03-31 09:45:40.572  3424  6086 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-31 09:45:41.022  3424  3606 D TimaService: TIMA: TimaService scheduler is intialized. 
,03-31 09:45:41.027  3424  3605 D TimaService: TimaServiceHandler.handleMessage what =1
,03-31 09:45:41.032  3424  3606 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000,
,03-31 09:45:41.047  3424  3606 I TLC_TIMA_PKM_initialize: initializing...
03-31 09:45:41.047  3424  3606 I TLC_TIMA_PKM_initialize: root = 0, root_strlen = 1
03-31 09:45:41.047  3424  3606 I TLC_TIMA_PKM_initialize: process = ffffffff00000000000000000000000a, process_strlen = 32
03-31 09:45:41.047  3424  3606 I TZ: mc_tlc_communication: input max_sendmsg_size = 262196
03-31 09:45:41.047  3424  3606 I TZ: mc_tlc_communication: input max_recvmsg_size = 262196
03-31 09:45:41.047  3424  3606 I TZ: mc_tlc_communication: root = 0, root_len = 1
03-31 09:45:41.047  3424  3606 I TZ: mc_tlc_communication: process = ffffffff00000000000000000000000a, process_strlen = 32
03-31 09:45:41.047  3424  3606 I TZ: mc_tlc_communication: aligned max_sendmsg_size = 262208
03-31 09:45:41.047  3424  3606 I TZ: mc_tlc_communication: aligned max_recvmsg_size = 262208
03-31 09:45:41.047  3424  3606 I TZ: mc_tlc_communication: device_id = 0x0
03-31 09:45:41.047  3424  3606 I TZ: mc_tlc_communication: tlc_open() was called
03-31 09:45:41.047  3424  3606 I TZ: mc_tlc_communication: Opening MobiCore device
,03-31 09:45:41.052  3424  3606 I TZ: mc_tlc_communication: Allocating message buffer for TCI,
,03-31 09:45:41.057  3424  3606 I TZ: mc_tlc_communication: Opening the session
,03-31 09:45:41.082  3424  3606 I TZ: mc_tlc_communication: tlc_open() succeeded
,03-31 09:45:41.092  3424  3606 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,03-31 09:45:43.437  3424  3861 E Watchdog: !@Sync 10 [03-31 09:45:43.439],
,03-31 09:45:45.932  3424  3606 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
03-31 09:45:45.932  3424  3606 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,03-31 09:45:45.947  3424  3606 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
03-31 09:45:45.947  3424  3606 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,03-31 09:45:46.462  2891  4701 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-31 09:45:47.267  3424  4420 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:45:47.267  3424  4420 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:45:47.267  3424  4420 D BatteryService: online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:35
,03-31 09:45:47.267  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.,
03-31 09:45:47.277  3424  3424 I MotionRecognitionService: Plugged
03-31 09:45:47.277  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 09:45:47.277  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 09:45:47.277  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 09:45:47.282  3424  4420 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 14ms,
03-31 09:45:47.287  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:45:47.282  3424  4420 D BatteryService: stay LED for fully charged
03-31 09:45:47.287  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-31 09:45:47.287  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:45:47.307  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 09:45:47.307  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:45:47.317  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:45:47.317  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:45:47.317  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:45:47.317  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:45:47.537  3424  6055 D SSRM:n  : SIOP:: AP = 260, PST = 261 (W:14), CUR = 28, LCD = 0
,03-31 09:45:57.392  3424  3965 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:45:57.392  3424  3965 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:45:57.392  3424  3965 D BatteryService: online:4, current avg:29, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:35
,03-31 09:45:57.397  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 09:45:57.397  3424  3965 D BatteryService: stay LED for fully charged
,03-31 09:45:57.402  3424  3424 I MotionRecognitionService: Plugged
03-31 09:45:57.402  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 09:45:57.402  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 09:45:57.402  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 09:45:57.412  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 09:45:57.412  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-31 09:45:57.412  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:45:57.432  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 09:45:57.432  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:45:57.442  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:45:57.442  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:45:57.442  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:45:57.442  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:45:57.557  3424  6055 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:16), CUR = 29, LCD = 0
,03-31 09:45:57.737  3424  3440 I art     : Background partial concurrent mark sweep GC freed 41674(3MB) AllocSpace objects, 91(3MB) LOS objects, 33% free, 29MB/44MB, paused 2.791ms total 193.022ms
,03-31 09:46:00.582  3424  6086 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-31 09:46:07.532  3424  3837 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:46:07.532  3424  3837 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:46:07.532  3424  3837 D BatteryService: online:4, current avg:29, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:31
,03-31 09:46:07.537  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 09:46:07.547  3424  3424 I MotionRecognitionService: Plugged
03-31 09:46:07.547  3424  3424 D MotionRecognitionService:   cableConnection= 1,
03-31 09:46:07.547  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-31 09:46:07.547  3424  3424 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 09:46:07.552  3424  3837 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 18ms
,03-31 09:46:07.552  3424  3837 D BatteryService: stay LED for fully charged
,03-31 09:46:07.562  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:46:07.562  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:46:07.562  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:46:07.572  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 09:46:07.572  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:46:07.577  3424  6055 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:16), CUR = 29, LCD = 0
,03-31 09:46:07.587  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 09:46:07.587  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:46:07.587  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:46:07.587  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:46:11.922  3424  3584 I PowerManagerService: [PWL] Off : 275s ago,
,03-31 09:46:13.447  3424  3861 E Watchdog: !@Sync 11 [03-31 09:46:13.451]
,03-31 09:46:17.597  3424  6055 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:16), CUR = 29, LCD = 0
,03-31 09:46:17.667  3424  4045 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:46:17.667  3424  4045 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:46:17.667  3424  4045 D BatteryService: online:4, current avg:29, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
,03-31 09:46:17.672  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 09:46:17.672  3424  4045 D BatteryService: stay LED for fully charged
,03-31 09:46:17.677  3424  3424 I MotionRecognitionService: Plugged
03-31 09:46:17.677  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 09:46:17.677  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 09:46:17.677  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 09:46:17.687  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:46:17.687  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:46:17.687  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:46:17.697  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 09:46:17.697  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:46:17.712  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 09:46:17.712  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:46:17.712  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:46:17.712  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:46:20.592  3424  6086 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-31 09:46:27.632  3424  6055 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:16), CUR = 29, LCD = 0
,03-31 09:46:27.792  3424  3451 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:46:27.792  3424  3451 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:46:27.792  3424  3451 D BatteryService: online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:31
,03-31 09:46:27.792  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 09:46:27.792  3424  3451 D BatteryService: stay LED for fully charged
,03-31 09:46:27.802  3424  3424 I MotionRecognitionService: Plugged
03-31 09:46:27.802  3424  3424 D MotionRecognitionService:   cableConnection= 1,
03-31 09:46:27.802  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
03-31 09:46:27.802  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 09:46:27.812  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 09:46:27.812  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:46:27.812  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:46:27.822  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 09:46:27.827  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 09:46:27.827  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:46:27.837  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:46:27.837  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:46:27.837  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:46:37.662  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 259 (W:18), CUR = 28, LCD = 0
,03-31 09:46:37.932  3424  3938 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:46:37.932  3424  3938 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:46:37.932  3424  3938 D BatteryService: online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
,03-31 09:46:37.932  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 09:46:37.942  3424  3424 I MotionRecognitionService: Plugged
03-31 09:46:37.942  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 09:46:37.942  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
03-31 09:46:37.942  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 09:46:37.947  3424  3938 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 15ms,
,03-31 09:46:37.947  3424  3938 D BatteryService: stay LED for fully charged
,03-31 09:46:37.957  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-31 09:46:37.957  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,03-31 09:46:37.957  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-31 09:46:37.977  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 09:46:37.977  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:46:37.987  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:46:37.987  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:46:37.987  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:46:37.987  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:46:40.597  3424  6086 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-31 09:46:43.457  3424  3861 E Watchdog: !@Sync 12 [03-31 09:46:43.459]
,03-31 09:46:46.462  2891  4701 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-31 09:46:47.692  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 257 (W:18), CUR = 27, LCD = 0
,03-31 09:46:48.072  3424  3816 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:46:48.072  3424  3816 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:46:48.072  3424  3816 D BatteryService: online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:33
,03-31 09:46:48.072  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 09:46:48.077  3424  3816 D BatteryService: stay LED for fully charged
,03-31 09:46:48.082  3424  3424 I MotionRecognitionService: Plugged,
03-31 09:46:48.082  3424  3424 D MotionRecognitionService:   cableConnection= 1
,03-31 09:46:48.082  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
,03-31 09:46:48.082  3424  3424 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 09:46:48.092  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 09:46:48.092  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
03-31 09:46:48.092  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:46:48.112  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 09:46:48.112  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:46:48.122  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:46:48.122  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:46:48.122  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:46:48.122  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:46:57.727  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 257 (W:18), CUR = 28, LCD = 0
,03-31 09:46:58.207  3424  4419 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:46:58.207  3424  4419 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:46:58.207  3424  4419 D BatteryService: online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:34
,03-31 09:46:58.212  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 09:46:58.217  3424  4419 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 11ms
03-31 09:46:58.217  3424  4419 D BatteryService: stay LED for fully charged
,03-31 09:46:58.222  3424  3424 I MotionRecognitionService: Plugged,
,03-31 09:46:58.222  3424  3424 D MotionRecognitionService:   cableConnection= 1
,03-31 09:46:58.222  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
,03-31 09:46:58.222  3424  3424 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 09:46:58.237  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-31 09:46:58.237  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,03-31 09:46:58.237  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-31 09:46:58.257  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 09:46:58.257  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:46:58.267  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 09:46:58.267  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:46:58.267  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:46:58.267  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:46:59.992  3424  3617 V AlarmManager: waitForAlarm result :8
03-31 09:46:59.992  3424  3617 V AlarmManager: No more alarm at this time.nowELAPSED=389494 batch.start=546066
,03-31 09:47:00.017  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
03-31 09:47:00.017  3723  3723 I PERF    : received broadcast android.intent.action.TIME_TICK
03-31 09:47:00.022  3723  3723 D KeyguardUpdateMonitor: handleTimeUpdate
,03-31 09:47:00.042  3723  3723 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,03-31 09:47:00.042  3424  3617 V AlarmManager: waitForAlarm result :8
03-31 09:47:00.042  3424  3617 V AlarmManager: No more alarm at this time.nowELAPSED=389543 batch.start=449495
,03-31 09:47:00.047  3723  3723 D SecKeyguardClockView: HomeTimezone(): 1
,03-31 09:47:00.057  3723  3723 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 09:47:00.057  3723  3723 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,03-31 09:47:00.067  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,03-31 09:47:00.112  3723  3723 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 09:47:00.117  3723  3723 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 09:47:00.122  3723  3723 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 09:47:00.122  3723  3723 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 09:47:00.127  3723  3723 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 09:47:00.127  3723  3723 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 09:47:00.142  3723  3723 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 09:47:00.602  3424  6086 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-31 09:47:06.922  3424  3584 I PowerManagerService: [PWL] Off : 330s ago
,03-31 09:47:07.757  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 256 (W:18), CUR = 27, LCD = 0
,03-31 09:47:08.352  3424  3965 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-31 09:47:08.352  3424  3965 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:47:08.352  3424  3965 D BatteryService: online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:29
03-31 09:47:08.352  3424  3965 D BatteryService: stay LED for fully charged
03-31 09:47:08.352  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 09:47:08.357  3424  3424 I MotionRecognitionService: Plugged
,03-31 09:47:08.357  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 09:47:08.357  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 09:47:08.357  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 09:47:08.362  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 09:47:08.362  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:47:08.362  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:47:08.377  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 09:47:08.377  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:47:08.387  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 09:47:08.387  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:47:08.387  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:47:08.387  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:47:13.462  3424  3861 E Watchdog: !@Sync 13 [03-31 09:47:13.467],
,03-31 09:47:17.787  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 256 (W:20), CUR = 27, LCD = 0
,03-31 09:47:18.492  3424  4420 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:47:18.492  3424  4420 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:47:18.492  3424  4420 D BatteryService: online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
,03-31 09:47:18.492  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 09:47:18.497  3424  4420 D BatteryService: stay LED for fully charged
,03-31 09:47:18.502  3424  3424 I MotionRecognitionService: Plugged,
03-31 09:47:18.502  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 09:47:18.502  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 09:47:18.502  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 09:47:18.512  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 09:47:18.512  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:47:18.512  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:47:18.527  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 09:47:18.532  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:47:18.542  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:47:18.542  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:47:18.542  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:47:18.542  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:47:20.607  3424  6086 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-31 09:47:27.812  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 255 (W:20), CUR = 25, LCD = 0
,03-31 09:47:28.627  3424  4045 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:47:28.627  3424  4045 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:47:28.627  3424  4045 D BatteryService: online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,03-31 09:47:28.632  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 09:47:28.637  3424  4045 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 10ms
03-31 09:47:28.637  3424  4045 D BatteryService: stay LED for fully charged,
03-31 09:47:28.642  3424  3424 I MotionRecognitionService: Plugged,
,03-31 09:47:28.642  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 09:47:28.642  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-31 09:47:28.642  3424  3424 D MotionRecognitionService: skip setTransmitPower. ,
03-31 09:47:28.652  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 09:47:28.652  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,03-31 09:47:28.652  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-31 09:47:28.677  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 09:47:28.677  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:47:28.687  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:47:28.687  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:47:28.687  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:47:28.687  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:47:37.842  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 254 (W:20), CUR = 24, LCD = 0
,03-31 09:47:38.767  3424  3816 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:47:38.767  3424  3816 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:47:38.767  3424  3816 D BatteryService: online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
,03-31 09:47:38.772  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 09:47:38.777  3424  3816 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 10ms
03-31 09:47:38.777  3424  3816 D BatteryService: stay LED for fully charged,
,03-31 09:47:38.782  3424  3424 I MotionRecognitionService: Plugged,
03-31 09:47:38.782  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 09:47:38.782  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 09:47:38.782  3424  3424 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 09:47:38.797  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 09:47:38.797  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-31 09:47:38.797  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:47:38.812  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 09:47:38.812  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:47:38.827  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 09:47:38.827  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:47:38.827  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:47:38.827  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:47:40.612  3424  6086 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-31 09:47:43.472  3424  3861 E Watchdog: !@Sync 14 [03-31 09:47:43.475]
,03-31 09:47:46.462  2891  4701 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-31 09:47:47.872  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 254 (W:20), CUR = 24, LCD = 0
,03-31 09:47:48.907  3424  3938 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:47:48.907  3424  3938 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:47:48.907  3424  3938 D BatteryService: online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:29
,03-31 09:47:48.912  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 09:47:48.917  3424  3424 I MotionRecognitionService: Plugged,
03-31 09:47:48.917  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 09:47:48.922  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-31 09:47:48.922  3424  3424 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 09:47:48.922  3424  3938 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 12ms
03-31 09:47:48.922  3424  3938 D BatteryService: stay LED for fully charged,
,03-31 09:47:48.937  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 09:47:48.937  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:47:48.937  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:47:48.957  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 09:47:48.957  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:47:48.967  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 09:47:48.967  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:47:48.967  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:47:48.967  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:47:57.902  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 253 (W:22), CUR = 23, LCD = 0
,03-31 09:47:59.047  3424  3837 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:47:59.047  3424  3837 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:47:59.047  3424  3837 D BatteryService: online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,03-31 09:47:59.047  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 09:47:59.047  3424  3837 D BatteryService: stay LED for fully charged
,03-31 09:47:59.057  3424  3424 I MotionRecognitionService: Plugged,
03-31 09:47:59.057  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 09:47:59.057  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-31 09:47:59.057  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 09:47:59.067  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 09:47:59.067  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-31 09:47:59.067  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:47:59.087  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 09:47:59.087  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:47:59.102  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 09:47:59.102  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:47:59.102  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:47:59.102  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:47:59.997  3424  3617 V AlarmManager: waitForAlarm result :8
,03-31 09:48:00.617  3424  6086 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,03-31 09:48:06.932  3424  3584 I PowerManagerService: [PWL] Off : 390s ago
,03-31 09:48:07.932  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 252 (W:22), CUR = 24, LCD = 0
,03-31 09:48:09.187  3424  3732 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:48:09.187  3424  3732 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:48:09.187  3424  3732 D BatteryService: online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
,03-31 09:48:09.192  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 09:48:09.197  3424  3424 I MotionRecognitionService: Plugged
03-31 09:48:09.197  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 09:48:09.197  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 09:48:09.197  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 09:48:09.202  3424  3732 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 13ms,
03-31 09:48:09.202  3424  3732 D BatteryService: stay LED for fully charged
,03-31 09:48:09.212  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 09:48:09.212  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
03-31 09:48:09.212  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-31 09:48:09.227  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 09:48:09.227  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:48:09.242  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:48:09.242  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:48:09.242  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:48:09.242  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:48:13.477  3424  3861 E Watchdog: !@Sync 15 [03-31 09:48:13.483]
,03-31 09:48:17.967  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 252 (W:22), CUR = 23, LCD = 0
,03-31 09:48:19.327  3424  4027 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:48:19.327  3424  4027 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:48:19.327  3424  4027 D BatteryService: online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:40
,03-31 09:48:19.332  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 09:48:19.337  3424  3424 I MotionRecognitionService: Plugged,
03-31 09:48:19.337  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 09:48:19.337  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
03-31 09:48:19.337  3424  3424 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 09:48:19.337  3424  4027 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 11ms
,03-31 09:48:19.352  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-31 09:48:19.337  3424  4027 D BatteryService: stay LED for fully charged,
03-31 09:48:19.352  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,03-31 09:48:19.352  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-31 09:48:19.372  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 09:48:19.377  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:48:19.387  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 09:48:19.387  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:48:19.387  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:48:19.387  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:48:20.627  3424  6086 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-31 09:48:27.997  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 251 (W:22), CUR = 24, LCD = 0
,03-31 09:48:29.467  3424  4025 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:48:29.467  3424  4025 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:48:29.467  3424  4025 D BatteryService: online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:3
,03-31 09:48:29.467  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 09:48:29.477  3424  3424 I MotionRecognitionService: Plugged
03-31 09:48:29.477  3424  3424 D MotionRecognitionService:   cableConnection= 1,
03-31 09:48:29.477  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 09:48:29.477  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 09:48:29.477  3424  4025 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 14ms,
03-31 09:48:29.477  3424  4025 D BatteryService: stay LED for fully charged
,03-31 09:48:29.487  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 09:48:29.487  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-31 09:48:29.487  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-31 09:48:29.507  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 09:48:29.512  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:48:29.517  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 09:48:29.522  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:48:29.522  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:48:29.522  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:48:34.647  2903  2903 I bootchecker: bootchecker wake up!!,
,03-31 09:48:38.027  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 251 (W:24), CUR = 22, LCD = 0
,03-31 09:48:39.602  3424  3965 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:48:39.602  3424  3965 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:48:39.602  3424  3965 D BatteryService: online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,03-31 09:48:39.607  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 09:48:39.617  3424  3424 I MotionRecognitionService: Plugged
03-31 09:48:39.617  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 09:48:39.617  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 09:48:39.617  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
03-31 09:48:39.617  3424  3965 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 13ms
03-31 09:48:39.617  3424  3965 D BatteryService: stay LED for fully charged
,03-31 09:48:39.622  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 09:48:39.622  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:48:39.622  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:48:39.642  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 09:48:39.647  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:48:39.652  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 09:48:39.652  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:48:39.652  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:48:39.657  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:48:40.632  3424  6086 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-31 09:48:43.487  3424  3861 E Watchdog: !@Sync 16 [03-31 09:48:43.490]
,03-31 09:48:46.462  2891  4701 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-31 09:48:48.057  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:24), CUR = 22, LCD = 0
,03-31 09:48:49.742  3424  4420 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:48:49.742  3424  4420 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:48:49.742  3424  4420 D BatteryService: online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,03-31 09:48:49.747  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 09:48:49.747  3424  4420 D BatteryService: stay LED for fully charged
,03-31 09:48:49.752  3424  3424 I MotionRecognitionService: Plugged,
03-31 09:48:49.752  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 09:48:49.752  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-31 09:48:49.752  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 09:48:49.767  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 09:48:49.767  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:48:49.767  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:48:49.787  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 09:48:49.787  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:48:49.797  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 09:48:49.797  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:48:49.797  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:48:49.797  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:48:58.092  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:24), CUR = 21, LCD = 0
,03-31 09:48:59.887  3424  4045 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:48:59.887  3424  4045 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:48:59.887  3424  4045 D BatteryService: online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
03-31 09:48:59.887  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 09:48:59.887  3424  4045 D BatteryService: stay LED for fully charged
,03-31 09:48:59.892  3424  3424 I MotionRecognitionService: Plugged
03-31 09:48:59.892  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 09:48:59.892  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 09:48:59.892  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 09:48:59.897  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 09:48:59.902  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:48:59.902  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:48:59.917  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 09:48:59.917  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:48:59.927  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:48:59.927  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:48:59.927  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:48:59.927  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:49:00.637  3424  6086 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-31 09:49:08.127  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:24), CUR = 21, LCD = 0
,03-31 09:49:10.027  3424  3816 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:49:10.027  3424  3816 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:49:10.027  3424  3816 D BatteryService: online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
,03-31 09:49:10.027  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 09:49:10.037  3424  3424 I MotionRecognitionService: Plugged
03-31 09:49:10.037  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 09:49:10.037  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
03-31 09:49:10.037  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 09:49:10.037  3424  3816 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 13ms,
03-31 09:49:10.042  3424  3816 D BatteryService: stay LED for fully charged
,03-31 09:49:10.047  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-31 09:49:10.047  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:49:10.047  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:49:10.067  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 09:49:10.067  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:49:10.077  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:49:10.077  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:49:10.077  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:49:10.077  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:49:11.932  3424  3584 I PowerManagerService: [PWL] Off : 455s ago
,03-31 09:49:13.492  3424  3861 E Watchdog: !@Sync 17 [03-31 09:49:13.497]
,03-31 09:49:18.157  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:26), CUR = 20, LCD = 0
,03-31 09:49:20.162  3424  3938 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:49:20.162  3424  3938 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:49:20.162  3424  3938 D BatteryService: online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,03-31 09:49:20.167  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 09:49:20.167  3424  3938 D BatteryService: stay LED for fully charged
,03-31 09:49:20.177  3424  3424 I MotionRecognitionService: Plugged
03-31 09:49:20.177  3424  3424 D MotionRecognitionService:   cableConnection= 1,
03-31 09:49:20.177  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 09:49:20.177  3424  3424 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 09:49:20.187  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 09:49:20.187  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:49:20.187  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:49:20.207  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 09:49:20.207  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:49:20.217  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:49:20.217  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:49:20.217  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:49:20.217  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:49:20.647  3424  6086 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-31 09:49:28.187  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:26), CUR = 20, LCD = 0
,03-31 09:49:30.302  3424  4035 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:49:30.302  3424  4035 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:49:30.302  3424  4035 D BatteryService: online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
,03-31 09:49:30.302  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 09:49:30.307  3424  4035 D BatteryService: stay LED for fully charged
,03-31 09:49:30.312  3424  3424 I MotionRecognitionService: Plugged
03-31 09:49:30.312  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 09:49:30.312  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 09:49:30.312  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 09:49:30.322  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 09:49:30.322  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:49:30.322  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:49:30.337  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 09:49:30.337  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:49:30.347  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 09:49:30.352  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:49:30.352  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:49:30.352  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:49:36.567  3424  3617 V AlarmManager: waitForAlarm result :4
,03-31 09:49:36.612  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
03-31 09:49:36.612  3723  3723 I PERF    : received broadcast android.intent.action.TIME_TICK
03-31 09:49:36.612  3723  3723 D KeyguardUpdateMonitor: handleTimeUpdate
,03-31 09:49:36.622  3723  3723 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,03-31 09:49:36.632  3723  3723 D SecKeyguardClockView: HomeTimezone(): 1
,03-31 09:49:36.642  3723  3723 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 09:49:36.642  3723  3723 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,03-31 09:49:36.652  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,03-31 09:49:36.702  3723  3723 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 09:49:36.702  3723  3723 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 09:49:36.707  3723  3723 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 09:49:36.707  3723  3723 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 09:49:36.712  3723  3723 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 09:49:36.717  3723  3723 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 09:49:36.732  3723  3723 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 09:49:38.212  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:26), CUR = 19, LCD = 0
,03-31 09:49:40.442  3424  3938 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:49:40.442  3424  3938 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:49:40.442  3424  3938 D BatteryService: online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
,03-31 09:49:40.442  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 09:49:40.442  3424  3938 D BatteryService: stay LED for fully charged
,03-31 09:49:40.452  3424  3424 I MotionRecognitionService: Plugged
03-31 09:49:40.452  3424  3424 D MotionRecognitionService:   cableConnection= 1,
03-31 09:49:40.452  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 09:49:40.452  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 09:49:40.467  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 09:49:40.467  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:49:40.467  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:49:40.487  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 09:49:40.492  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:49:40.497  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:49:40.497  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:49:40.497  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:49:40.497  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:49:40.652  3424  6086 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-31 09:49:43.502  3424  3861 E Watchdog: !@Sync 18 [03-31 09:49:43.505]
,03-31 09:49:46.462  2891  4701 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-31 09:49:48.242  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:26), CUR = 19, LCD = 0
,03-31 09:49:50.582  3424  3732 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:49:50.582  3424  3732 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:49:50.582  3424  3732 D BatteryService: online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,03-31 09:49:50.587  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 09:49:50.587  3424  3732 D BatteryService: stay LED for fully charged
,03-31 09:49:50.592  3424  3424 I MotionRecognitionService: Plugged
03-31 09:49:50.592  3424  3424 D MotionRecognitionService:   cableConnection= 1,
03-31 09:49:50.592  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-31 09:49:50.592  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 09:49:50.607  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:49:50.607  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:49:50.607  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:49:50.617  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 09:49:50.617  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:49:50.632  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 09:49:50.632  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:49:50.632  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:49:50.632  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:49:58.272  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:28), CUR = 20, LCD = 0,
,03-31 09:49:59.997  3424  3617 V AlarmManager: waitForAlarm result :8
,03-31 09:50:00.652  3424  6086 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-31 09:50:00.727  3424  3453 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:50:00.727  3424  3453 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:50:00.727  3424  3453 D BatteryService: online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:28
,03-31 09:50:00.727  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 09:50:00.727  3424  3453 D BatteryService: stay LED for fully charged
,03-31 09:50:00.737  3424  3424 I MotionRecognitionService: Plugged,
03-31 09:50:00.737  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 09:50:00.737  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 09:50:00.737  3424  3424 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 09:50:00.747  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 09:50:00.747  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:50:00.747  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:50:00.767  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 09:50:00.767  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:50:00.777  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:50:00.777  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:50:00.777  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:50:00.777  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:50:08.302  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:28), CUR = 18, LCD = 0
,03-31 09:50:10.862  3424  4025 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:50:10.862  3424  4025 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:50:10.862  3424  4025 D BatteryService: online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
,03-31 09:50:10.867  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 09:50:10.867  3424  4025 D BatteryService: stay LED for fully charged
,03-31 09:50:10.872  3424  3424 I MotionRecognitionService: Plugged
03-31 09:50:10.872  3424  3424 D MotionRecognitionService:   cableConnection= 1,
03-31 09:50:10.872  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
,03-31 09:50:10.872  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 09:50:10.887  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 09:50:10.887  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:50:10.887  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:50:10.907  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 09:50:10.907  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:50:10.917  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 09:50:10.917  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:50:10.917  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:50:10.917  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:50:13.507  3424  3861 E Watchdog: !@Sync 19 [03-31 09:50:13.513]
,03-31 09:50:18.332  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:28), CUR = 19, LCD = 0
,03-31 09:50:20.657  3424  6086 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-31 09:50:20.997  3424  4035 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:50:20.997  3424  4035 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:50:20.997  3424  4035 D BatteryService: online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:42
,03-31 09:50:21.002  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 09:50:21.002  3424  4035 D BatteryService: stay LED for fully charged
,03-31 09:50:21.012  3424  3424 I MotionRecognitionService: Plugged,
03-31 09:50:21.012  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 09:50:21.012  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 09:50:21.012  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 09:50:21.022  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 09:50:21.022  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:50:21.022  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:50:21.037  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 09:50:21.037  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:50:21.052  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:50:21.052  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:50:21.052  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:50:21.052  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:50:21.932  3424  3584 I PowerManagerService: [PWL] Off : 525s ago
,03-31 09:50:28.357  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:28), CUR = 18, LCD = 0
,03-31 09:50:31.137  3424  4420 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:50:31.137  3424  4420 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:50:31.137  3424  4420 D BatteryService: online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
,03-31 09:50:31.142  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 09:50:31.142  3424  4420 D BatteryService: stay LED for fully charged,
,03-31 09:50:31.152  3424  3424 I MotionRecognitionService: Plugged
03-31 09:50:31.152  3424  3424 D MotionRecognitionService:   cableConnection= 1,
03-31 09:50:31.152  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-31 09:50:31.152  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 09:50:31.162  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 09:50:31.162  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:50:31.162  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:50:31.182  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 09:50:31.182  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:50:31.192  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:50:31.192  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:50:31.192  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:50:31.192  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:50:38.387  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 18, LCD = 0
,03-31 09:50:40.662  3424  6086 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-31 09:50:41.022  3424  3606 D TimaService: TIMA: TimaService scheduler is intialized. 
03-31 09:50:41.022  3424  3606 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,03-31 09:50:41.027  3424  3605 D TimaService: TimaServiceHandler.handleMessage what =1
,03-31 09:50:41.287  3424  4027 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:50:41.287  3424  4027 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:50:41.287  3424  4027 D BatteryService: online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
03-31 09:50:41.287  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 09:50:41.287  3424  4027 D BatteryService: stay LED for fully charged
,03-31 09:50:41.297  3424  3424 I MotionRecognitionService: Plugged
03-31 09:50:41.297  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 09:50:41.297  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 09:50:41.297  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 09:50:41.302  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 09:50:41.302  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:50:41.302  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:50:41.322  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 09:50:41.322  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:50:41.332  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:50:41.332  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:50:41.332  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:50:41.332  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:50:43.517  3424  3861 E Watchdog: !@Sync 20 [03-31 09:50:43.521]
,03-31 09:50:43.552  3424  3606 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
03-31 09:50:43.552  3424  3606 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,03-31 09:50:43.567  3424  3606 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;,
,03-31 09:50:43.577  3424  3606 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,03-31 09:50:46.462  2891  4701 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-31 09:50:46.947  3424  3582 I ActivityManager: setMaxStartingBackgroundTimer onfinish
03-31 09:50:46.947  3424  3582 I ActivityManager: MaxStartingBackground is set. ( current : 8 )
,03-31 09:50:48.412  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 19, LCD = 0
,03-31 09:50:51.427  3424  3451 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:50:51.427  3424  3451 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:50:51.427  3424  3451 D BatteryService: online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:3
,03-31 09:50:51.432  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 09:50:51.432  3424  3451 D BatteryService: stay LED for fully charged
,03-31 09:50:51.442  3424  3424 I MotionRecognitionService: Plugged
03-31 09:50:51.442  3424  3424 D MotionRecognitionService:   cableConnection= 1,
03-31 09:50:51.442  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 09:50:51.442  3424  3424 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 09:50:51.452  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:50:51.452  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:50:51.452  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:50:51.462  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 09:50:51.462  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:50:51.477  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 09:50:51.477  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:50:51.477  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:50:51.477  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:50:58.437  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 18, LCD = 0
,03-31 09:51:00.667  3424  6086 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-31 09:51:01.562  3424  3837 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:51:01.562  3424  3837 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:51:01.562  3424  3837 D BatteryService: online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
,03-31 09:51:01.567  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 09:51:01.567  3424  3837 D BatteryService: stay LED for fully charged
,03-31 09:51:01.577  3424  3424 I MotionRecognitionService: Plugged,
03-31 09:51:01.577  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 09:51:01.577  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-31 09:51:01.577  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 09:51:01.587  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 09:51:01.587  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:51:01.587  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:51:01.602  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 09:51:01.607  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:51:01.617  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:51:01.617  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:51:01.617  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:51:01.617  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:51:02.197  3424  3732 I ActivityManager: Killing 10089:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): emptyCount ##31
,03-31 09:51:08.462  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 17, LCD = 0
,03-31 09:51:11.702  3424  4027 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:51:11.702  3424  4027 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:51:11.702  3424  4027 D BatteryService: online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:34
,03-31 09:51:11.707  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 09:51:11.707  3424  4027 D BatteryService: stay LED for fully charged
,03-31 09:51:11.712  3424  3424 I MotionRecognitionService: Plugged,
03-31 09:51:11.712  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 09:51:11.712  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-31 09:51:11.712  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 09:51:11.727  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 09:51:11.727  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:51:11.727  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:51:11.747  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 09:51:11.747  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:51:11.757  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 09:51:11.757  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:51:11.757  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:51:11.757  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:51:13.527  3424  3861 E Watchdog: !@Sync 21 [03-31 09:51:13.532]
,03-31 09:51:18.492  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 18, LCD = 0
,03-31 09:51:21.837  3424  3816 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:51:21.842  3424  3816 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:51:21.842  3424  3816 D BatteryService: online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:3
,03-31 09:51:21.842  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 09:51:21.842  3424  3816 D BatteryService: stay LED for fully charged
,03-31 09:51:21.852  3424  3424 I MotionRecognitionService: Plugged,
03-31 09:51:21.852  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 09:51:21.852  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 09:51:21.852  3424  3424 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 09:51:21.862  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 09:51:21.862  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:51:21.862  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-31 09:51:21.882  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 09:51:21.882  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:51:21.892  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:51:21.892  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:51:21.892  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:51:21.892  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:51:28.522  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 18, LCD = 0
,03-31 09:51:31.982  3424  3732 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:51:31.982  3424  3732 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:51:31.982  3424  3732 D BatteryService: online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,03-31 09:51:31.982  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 09:51:31.987  3424  3732 D BatteryService: stay LED for fully charged
,03-31 09:51:31.992  3424  3424 I MotionRecognitionService: Plugged
03-31 09:51:31.992  3424  3424 D MotionRecognitionService:   cableConnection= 1,
03-31 09:51:31.992  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 09:51:31.992  3424  3424 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 09:51:32.002  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 09:51:32.002  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-31 09:51:32.002  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:51:32.027  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 09:51:32.027  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:51:32.037  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 09:51:32.037  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:51:32.037  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:51:32.037  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:51:36.937  3424  3584 I PowerManagerService: [PWL] Off : 600s ago
,03-31 09:51:38.547  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 18, LCD = 0
,03-31 09:51:42.117  3424  3453 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:51:42.122  3424  3453 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:51:42.122  3424  3453 D BatteryService: online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
,03-31 09:51:42.122  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 09:51:42.122  3424  3453 D BatteryService: stay LED for fully charged
,03-31 09:51:42.132  3424  3424 I MotionRecognitionService: Plugged
03-31 09:51:42.132  3424  3424 D MotionRecognitionService:   cableConnection= 1,
03-31 09:51:42.132  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 09:51:42.132  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 09:51:42.137  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 09:51:42.137  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:51:42.137  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:51:42.157  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 09:51:42.157  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:51:42.172  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 09:51:42.172  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:51:42.172  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:51:42.172  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:51:43.537  3424  3861 E Watchdog: !@Sync 22 [03-31 09:51:43.539]
,03-31 09:51:46.462  2891  4701 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-31 09:51:48.577  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 18, LCD = 0
,03-31 09:51:52.257  3424  4420 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:51:52.257  3424  4420 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:51:52.257  3424  4420 D BatteryService: online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,03-31 09:51:52.262  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 09:51:52.262  3424  4420 D BatteryService: stay LED for fully charged
,03-31 09:51:52.267  3424  3424 I MotionRecognitionService: Plugged
03-31 09:51:52.267  3424  3424 D MotionRecognitionService:   cableConnection= 1,
03-31 09:51:52.267  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 09:51:52.267  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 09:51:52.277  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 09:51:52.277  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:51:52.282  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:51:52.302  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 09:51:52.302  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:51:52.312  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:51:52.312  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:51:52.312  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:51:52.312  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:51:58.612  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 19, LCD = 0
,03-31 09:52:02.397  3424  4035 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:52:02.397  3424  4035 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:52:02.397  3424  4035 D BatteryService: online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,03-31 09:52:02.397  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 09:52:02.402  3424  4035 D BatteryService: stay LED for fully charged
,03-31 09:52:02.407  3424  3424 I MotionRecognitionService: Plugged,
03-31 09:52:02.407  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 09:52:02.407  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-31 09:52:02.407  3424  3424 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 09:52:02.417  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 09:52:02.417  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:52:02.417  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:52:02.442  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 09:52:02.442  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:52:02.452  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 09:52:02.452  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:52:02.452  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:52:02.452  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:52:08.642  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 18, LCD = 0
,03-31 09:52:12.532  3424  3451 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:52:12.532  3424  3451 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:52:12.532  3424  3451 D BatteryService: online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,03-31 09:52:12.537  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 09:52:12.537  3424  3451 D BatteryService: stay LED for fully charged
,03-31 09:52:12.547  3424  3424 I MotionRecognitionService: Plugged
03-31 09:52:12.547  3424  3424 D MotionRecognitionService:   cableConnection= 1,
03-31 09:52:12.547  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 09:52:12.547  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 09:52:12.552  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 09:52:12.552  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:52:12.552  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:52:12.572  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 09:52:12.572  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:52:12.582  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 09:52:12.582  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:52:12.582  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:52:12.582  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:52:13.542  3424  3861 E Watchdog: !@Sync 23 [03-31 09:52:13.547]
,03-31 09:52:18.672  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 16, LCD = 0
,03-31 09:52:22.672  3424  4027 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:52:22.672  3424  4027 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:52:22.672  3424  4027 D BatteryService: online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
,03-31 09:52:22.677  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 09:52:22.677  3424  4027 D BatteryService: stay LED for fully charged
,03-31 09:52:22.682  3424  3424 I MotionRecognitionService: Plugged
,03-31 09:52:22.682  3424  3424 D MotionRecognitionService:   cableConnection= 1
,03-31 09:52:22.682  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-31 09:52:22.682  3424  3424 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 09:52:22.697  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 09:52:22.697  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:52:22.697  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:52:22.717  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 09:52:22.717  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:52:22.727  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:52:22.727  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:52:22.727  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:52:22.727  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:52:28.702  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 16, LCD = 0
,03-31 09:52:32.807  3424  3816 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:52:32.807  3424  3816 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:52:32.807  3424  3816 D BatteryService: online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,03-31 09:52:32.812  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 09:52:32.812  3424  3816 D BatteryService: stay LED for fully charged
,03-31 09:52:32.822  3424  3424 I MotionRecognitionService: Plugged
03-31 09:52:32.822  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 09:52:32.822  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 09:52:32.822  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 09:52:32.832  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 09:52:32.832  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:52:32.832  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:52:32.847  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 09:52:32.852  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:52:32.862  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:52:32.862  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:52:32.862  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:52:32.862  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:52:38.732  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 16, LCD = 0
,03-31 09:52:42.947  3424  3837 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:52:42.947  3424  3837 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:52:42.947  3424  3837 D BatteryService: online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
,03-31 09:52:42.952  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 09:52:42.952  3424  3837 D BatteryService: stay LED for fully charged,
,03-31 09:52:42.957  3424  3424 I MotionRecognitionService: Plugged
03-31 09:52:42.957  3424  3424 D MotionRecognitionService:   cableConnection= 1,
03-31 09:52:42.962  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 09:52:42.962  3424  3424 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 09:52:42.972  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 09:52:42.972  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:52:42.972  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:52:42.992  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 09:52:42.992  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:52:43.002  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:52:43.002  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:52:43.002  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:52:43.002  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:52:43.552  3424  3861 E Watchdog: !@Sync 24 [03-31 09:52:43.554]
,03-31 09:52:46.462  2891  4701 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-31 09:52:48.762  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 15, LCD = 0
,03-31 09:52:53.082  3424  4025 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:52:53.087  3424  4025 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:52:53.087  3424  4025 D BatteryService: online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:35
,03-31 09:52:53.087  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 09:52:53.087  3424  4025 D BatteryService: stay LED for fully charged
,03-31 09:52:53.097  3424  3424 I MotionRecognitionService: Plugged,
03-31 09:52:53.097  3424  3424 D MotionRecognitionService:   cableConnection= 1
,03-31 09:52:53.097  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
03-31 09:52:53.097  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 09:52:53.107  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-31 09:52:53.107  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-31 09:52:53.107  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:52:53.127  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 09:52:53.127  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:52:53.142  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 09:52:53.142  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:52:53.142  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:52:53.142  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:52:56.937  3424  3584 I PowerManagerService: [PWL] Off : 680s ago
,03-31 09:52:58.792  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 14, LCD = 0
,03-31 09:53:03.222  3424  3965 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:53:03.222  3424  3965 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:53:03.222  3424  3965 D BatteryService: online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:39
03-31 09:53:03.227  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 09:53:03.227  3424  3965 D BatteryService: stay LED for fully charged
,03-31 09:53:03.232  3424  3424 I MotionRecognitionService: Plugged
03-31 09:53:03.232  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 09:53:03.232  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-31 09:53:03.232  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 09:53:03.242  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 09:53:03.242  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:53:03.242  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:53:03.267  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 09:53:03.267  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:53:03.272  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 09:53:03.272  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:53:03.272  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:53:03.272  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:53:08.827  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 15, LCD = 0
,03-31 09:53:13.367  3424  4045 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:53:13.367  3424  4045 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:53:13.367  3424  4045 D BatteryService: online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:39
,03-31 09:53:13.367  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 09:53:13.377  3424  3424 I MotionRecognitionService: Plugged
03-31 09:53:13.377  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 09:53:13.377  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 09:53:13.377  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 09:53:13.377  3424  4045 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 13ms,
03-31 09:53:13.377  3424  4045 D BatteryService: stay LED for fully charged
,03-31 09:53:13.387  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:53:13.387  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:53:13.387  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:53:13.397  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 09:53:13.397  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:53:13.412  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 09:53:13.412  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:53:13.412  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:53:13.412  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:53:13.557  3424  3861 E Watchdog: !@Sync 25 [03-31 09:53:13.561]
,03-31 09:53:18.862  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 16, LCD = 0
,03-31 09:53:23.502  3424  4419 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:53:23.502  3424  4419 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:53:23.502  3424  4419 D BatteryService: online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:38
,03-31 09:53:23.502  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 09:53:23.512  3424  3424 I MotionRecognitionService: Plugged
03-31 09:53:23.512  3424  3424 D MotionRecognitionService:   cableConnection= 1,
03-31 09:53:23.512  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-31 09:53:23.512  3424  3424 D MotionRecognitionService: skip setTransmitPower. ,
03-31 09:53:23.517  3424  4419 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 15ms
,03-31 09:53:23.517  3424  4419 D BatteryService: stay LED for fully charged
,03-31 09:53:23.527  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:53:23.527  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:53:23.527  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:53:23.542  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 09:53:23.542  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:53:23.552  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 09:53:23.552  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:53:23.552  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:53:23.552  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:53:28.892  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 17, LCD = 0
,03-31 09:53:33.667  3424  3938 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:53:33.667  3424  3938 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:53:33.667  3424  3938 D BatteryService: online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
,03-31 09:53:33.667  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 09:53:33.677  3424  3938 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 10ms
03-31 09:53:33.677  3424  3938 D BatteryService: stay LED for fully charged
,03-31 09:53:33.677  3424  3424 I MotionRecognitionService: Plugged
03-31 09:53:33.677  3424  3424 D MotionRecognitionService:   cableConnection= 1,
03-31 09:53:33.677  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 09:53:33.677  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 09:53:33.687  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 09:53:33.687  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:53:33.687  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:53:33.712  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 09:53:33.712  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:53:33.722  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 09:53:33.722  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:53:33.722  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:53:33.722  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:53:38.922  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 15, LCD = 0
,03-31 09:53:43.562  3424  3861 E Watchdog: !@Sync 26 [03-31 09:53:43.568]
,03-31 09:53:43.807  3424  3732 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:53:43.807  3424  3732 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
,03-31 09:53:43.812  3424  3732 D BatteryService: online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
03-31 09:53:43.812  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 09:53:43.812  3424  3732 D BatteryService: stay LED for fully charged
,03-31 09:53:43.822  3424  3424 I MotionRecognitionService: Plugged
03-31 09:53:43.822  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 09:53:43.822  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 09:53:43.822  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 09:53:43.827  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 09:53:43.827  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:53:43.827  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:53:43.847  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 09:53:43.847  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:53:43.862  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 09:53:43.862  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:53:43.862  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:53:43.862  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:53:46.462  2891  4701 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-31 09:53:46.602  3424  3617 V AlarmManager: waitForAlarm result :8
,03-31 09:53:48.952  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 15, LCD = 0
,03-31 09:53:53.947  3424  3453 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:53:53.947  3424  3453 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:53:53.947  3424  3453 D BatteryService: online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,03-31 09:53:53.947  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 09:53:53.952  3424  3453 D BatteryService: stay LED for fully charged
,03-31 09:53:53.957  3424  3424 I MotionRecognitionService: Plugged,
03-31 09:53:53.957  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 09:53:53.957  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 09:53:53.957  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 09:53:53.967  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 09:53:53.967  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:53:53.967  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:53:53.982  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 09:53:53.982  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:53:53.992  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 09:53:53.997  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:53:53.997  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:53:53.997  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:53:58.982  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 16, LCD = 0
,03-31 09:54:04.087  3424  4420 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:54:04.087  3424  4420 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:54:04.087  3424  4420 D BatteryService: online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:6
,03-31 09:54:04.087  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 09:54:04.087  3424  4420 D BatteryService: stay LED for fully charged
,03-31 09:54:04.097  3424  3424 I MotionRecognitionService: Plugged,
03-31 09:54:04.097  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 09:54:04.097  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
,03-31 09:54:04.097  3424  3424 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 09:54:04.107  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 09:54:04.107  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:54:04.107  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:54:04.127  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 09:54:04.127  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:54:04.142  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 09:54:04.142  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:54:04.142  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:54:04.142  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:54:09.012  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 15, LCD = 0
,03-31 09:54:13.572  3424  3861 E Watchdog: !@Sync 27 [03-31 09:54:13.575]
,03-31 09:54:14.222  3424  4035 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:54:14.222  3424  4035 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:54:14.222  3424  4035 D BatteryService: online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
,03-31 09:54:14.227  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 09:54:14.227  3424  4035 D BatteryService: stay LED for fully charged
,03-31 09:54:14.237  3424  3424 I MotionRecognitionService: Plugged
03-31 09:54:14.237  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 09:54:14.237  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 09:54:14.237  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 09:54:14.242  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 09:54:14.242  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:54:14.242  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:54:14.262  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 09:54:14.262  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:54:14.272  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 09:54:14.272  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:54:14.272  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:54:14.272  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:54:19.042  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 14, LCD = 0
,03-31 09:54:21.947  3424  3584 I PowerManagerService: [PWL] Off : 765s ago
,03-31 09:54:24.362  3424  4025 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:54:24.362  3424  4025 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:54:24.362  3424  4025 D BatteryService: online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
,03-31 09:54:24.367  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 09:54:24.367  3424  4025 D BatteryService: stay LED for fully charged
,03-31 09:54:24.372  3424  3424 I MotionRecognitionService: Plugged
03-31 09:54:24.372  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 09:54:24.372  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 09:54:24.372  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 09:54:24.382  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 09:54:24.382  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-31 09:54:24.382  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:54:24.397  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 09:54:24.402  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 09:54:24.402  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:54:24.402  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:54:24.417  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:54:24.417  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:54:29.067  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 15, LCD = 0
,03-31 09:54:34.502  3424  4419 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:54:34.502  3424  4419 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:54:34.502  3424  4419 D BatteryService: online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,03-31 09:54:34.502  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 09:54:34.502  3424  4419 D BatteryService: stay LED for fully charged
,03-31 09:54:34.512  3424  3424 I MotionRecognitionService: Plugged,
03-31 09:54:34.512  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 09:54:34.512  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 09:54:34.512  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 09:54:34.522  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 09:54:34.522  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:54:34.522  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:54:34.532  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 09:54:34.532  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:54:34.547  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 09:54:34.547  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:54:34.547  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:54:34.547  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:54:39.097  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 15, LCD = 0
,03-31 09:54:43.577  3424  3861 E Watchdog: !@Sync 28 [03-31 09:54:43.584]
,03-31 09:54:44.637  3424  4045 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:54:44.637  3424  4045 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:54:44.637  3424  4045 D BatteryService: online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
,03-31 09:54:44.642  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 09:54:44.642  3424  4045 D BatteryService: stay LED for fully charged
,03-31 09:54:44.652  3424  3424 I MotionRecognitionService: Plugged
03-31 09:54:44.652  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 09:54:44.652  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 09:54:44.652  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 09:54:44.657  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 09:54:44.657  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:54:44.657  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:54:44.667  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-31 09:54:44.667  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:54:44.682  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 09:54:44.682  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:54:44.682  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:54:44.682  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:54:46.462  2891  4701 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 ,
,03-31 09:54:49.122  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 14, LCD = 0
,03-31 09:54:54.777  3424  3732 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:54:54.777  3424  3732 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:54:54.777  3424  3732 D BatteryService: online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
,03-31 09:54:54.782  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 09:54:54.787  3424  3424 I MotionRecognitionService: Plugged
03-31 09:54:54.787  3424  3424 D MotionRecognitionService:   cableConnection= 1,
03-31 09:54:54.787  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 09:54:54.787  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 09:54:54.792  3424  3732 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 14ms,
03-31 09:54:54.792  3424  3732 D BatteryService: stay LED for fully charged
,03-31 09:54:54.802  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 09:54:54.802  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:54:54.802  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:54:54.817  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 09:54:54.817  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:54:54.832  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 09:54:54.832  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:54:54.832  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:54:54.832  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:54:59.152  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 14, LCD = 0
,03-31 09:55:04.917  3424  3453 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:55:04.917  3424  3453 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:55:04.917  3424  3453 D BatteryService: online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-1
,03-31 09:55:04.917  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 09:55:04.927  3424  3424 I MotionRecognitionService: Plugged
,03-31 09:55:04.927  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 09:55:04.927  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 09:55:04.927  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 09:55:04.927  3424  3453 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 12ms,
03-31 09:55:04.927  3424  3453 D BatteryService: stay LED for fully charged,
,03-31 09:55:04.942  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 09:55:04.942  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:55:04.942  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:55:04.957  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 09:55:04.957  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:55:04.967  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 09:55:04.972  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:55:04.972  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:55:04.972  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:55:09.177  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 12, LCD = 0
,03-31 09:55:13.587  3424  3861 E Watchdog: !@Sync 29 [03-31 09:55:13.591]
,03-31 09:55:15.052  3424  4420 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:55:15.052  3424  4420 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:55:15.052  3424  4420 D BatteryService: online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,03-31 09:55:15.057  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 09:55:15.062  3424  4420 D BatteryService: stay LED for fully charged
,03-31 09:55:15.067  3424  3424 I MotionRecognitionService: Plugged,
03-31 09:55:15.067  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 09:55:15.067  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-31 09:55:15.067  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 09:55:15.077  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 09:55:15.077  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:55:15.077  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:55:15.097  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 09:55:15.097  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:55:15.107  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 09:55:15.107  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:55:15.107  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:55:15.107  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:55:19.207  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 12, LCD = 0
,03-31 09:55:25.192  3424  4035 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:55:25.192  3424  4035 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:55:25.192  3424  4035 D BatteryService: online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
,03-31 09:55:25.197  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 09:55:25.197  3424  4035 D BatteryService: stay LED for fully charged
,03-31 09:55:25.207  3424  3424 I MotionRecognitionService: Plugged,
03-31 09:55:25.207  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 09:55:25.207  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-31 09:55:25.207  3424  3424 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 09:55:25.217  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 09:55:25.217  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,03-31 09:55:25.217  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-31 09:55:25.237  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 09:55:25.242  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:55:25.247  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 09:55:25.247  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:55:25.252  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:55:25.252  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:55:29.232  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 12, LCD = 0
,03-31 09:55:35.332  3424  3451 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:55:35.332  3424  3451 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:55:35.332  3424  3451 D BatteryService: online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
,03-31 09:55:35.332  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 09:55:35.332  3424  3451 D BatteryService: stay LED for fully charged
,03-31 09:55:35.342  3424  3424 I MotionRecognitionService: Plugged
03-31 09:55:35.342  3424  3424 D MotionRecognitionService:   cableConnection= 1,
03-31 09:55:35.342  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 09:55:35.342  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 09:55:35.352  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 09:55:35.352  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:55:35.352  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:55:35.372  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 09:55:35.372  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:55:35.382  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:55:35.382  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:55:35.382  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:55:35.382  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:55:39.262  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 12, LCD = 0
,03-31 09:55:41.022  3424  3606 D TimaService: TIMA: TimaService scheduler is intialized. 
03-31 09:55:41.022  3424  3606 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,03-31 09:55:41.027  3424  3605 D TimaService: TimaServiceHandler.handleMessage what =1
,03-31 09:55:43.592  3424  3861 E Watchdog: !@Sync 30 [03-31 09:55:43.598]
,03-31 09:55:45.482  3424  4027 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:55:45.482  3424  4027 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:55:45.482  3424  4027 D BatteryService: online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
,03-31 09:55:45.482  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 09:55:45.487  3424  4027 D BatteryService: stay LED for fully charged
,03-31 09:55:45.497  3424  3424 I MotionRecognitionService: Plugged,
03-31 09:55:45.497  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 09:55:45.497  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-31 09:55:45.497  3424  3424 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 09:55:45.507  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:55:45.507  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:55:45.507  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:55:45.522  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 09:55:45.522  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:55:45.532  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 09:55:45.532  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:55:45.537  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:55:45.537  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:55:45.897  3424  3606 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
03-31 09:55:45.897  3424  3606 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,03-31 09:55:45.912  3424  3606 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;,
,03-31 09:55:45.922  3424  3606 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,03-31 09:55:46.462  2891  4701 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-31 09:55:49.292  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 13, LCD = 0
,03-31 09:55:51.947  3424  3584 I PowerManagerService: [PWL] Off : 855s ago
,03-31 09:55:55.622  3424  3816 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:55:55.622  3424  3816 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:55:55.622  3424  3816 D BatteryService: online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-3
,03-31 09:55:55.627  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 09:55:55.627  3424  3816 D BatteryService: stay LED for fully charged
,03-31 09:55:55.637  3424  3424 I MotionRecognitionService: Plugged,
03-31 09:55:55.637  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 09:55:55.637  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-31 09:55:55.637  3424  3424 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 09:55:55.647  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:55:55.647  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:55:55.647  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:55:55.657  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 09:55:55.657  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:55:55.672  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 09:55:55.672  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:55:55.672  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:55:55.672  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:55:59.322  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 12, LCD = 0
,03-31 09:56:05.757  3424  3837 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:56:05.757  3424  3837 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4400, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:56:05.757  3424  3837 D BatteryService: online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:2
,03-31 09:56:05.762  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 09:56:05.762  3424  3837 D BatteryService: stay LED for fully charged
,03-31 09:56:05.772  3424  3424 I MotionRecognitionService: Plugged
03-31 09:56:05.772  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 09:56:05.772  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 09:56:05.772  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 09:56:05.777  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:56:05.777  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:56:05.777  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:56:05.792  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 09:56:05.792  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:56:05.807  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 09:56:05.807  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:56:05.807  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:56:05.807  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:56:09.347  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 13, LCD = 0
,03-31 09:56:13.602  3424  3861 E Watchdog: !@Sync 31 [03-31 09:56:13.605]
,03-31 09:56:15.897  3424  4025 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:56:15.897  3424  4025 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:56:15.897  3424  4025 D BatteryService: online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:3
,03-31 09:56:15.897  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 09:56:15.897  3424  4025 D BatteryService: stay LED for fully charged
,03-31 09:56:15.907  3424  3424 I MotionRecognitionService: Plugged,
03-31 09:56:15.907  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 09:56:15.907  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 09:56:15.907  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 09:56:15.912  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 09:56:15.912  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:56:15.917  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:56:15.932  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 09:56:15.932  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:56:15.942  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 09:56:15.947  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:56:15.947  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:56:15.947  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:56:19.377  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 15, LCD = 0
,03-31 09:56:26.032  3424  3965 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:56:26.032  3424  3965 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:56:26.032  3424  3965 D BatteryService: online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:4
,03-31 09:56:26.037  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 09:56:26.042  3424  3965 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 11ms
03-31 09:56:26.042  3424  3965 D BatteryService: stay LED for fully charged,
03-31 09:56:26.047  3424  3424 I MotionRecognitionService: Plugged
,03-31 09:56:26.047  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 09:56:26.047  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
,03-31 09:56:26.047  3424  3424 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 09:56:26.057  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-31 09:56:26.057  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
03-31 09:56:26.057  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-31 09:56:26.077  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 09:56:26.077  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:56:26.087  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:56:26.087  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:56:26.087  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:56:26.087  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:56:29.412  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 13, LCD = 0
,03-31 09:56:36.172  3424  3938 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:56:36.177  3424  3938 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:56:36.177  3424  3938 D BatteryService: online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,03-31 09:56:36.177  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 09:56:36.177  3424  3938 D BatteryService: stay LED for fully charged
,03-31 09:56:36.187  3424  3424 I MotionRecognitionService: Plugged,
03-31 09:56:36.187  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 09:56:36.187  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-31 09:56:36.187  3424  3424 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 09:56:36.197  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 09:56:36.197  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:56:36.197  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:56:36.217  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 09:56:36.217  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:56:36.227  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 09:56:36.227  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:56:36.227  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:56:36.227  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:56:39.442  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 12, LCD = 0
,03-31 09:56:43.607  3424  3861 E Watchdog: !@Sync 32 [03-31 09:56:43.613]
,03-31 09:56:46.317  3424  4419 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:56:46.317  3424  4419 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:56:46.317  3424  4419 D BatteryService: online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,03-31 09:56:46.322  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 09:56:46.322  3424  4419 D BatteryService: stay LED for fully charged,
,03-31 09:56:46.332  3424  3424 I MotionRecognitionService: Plugged
03-31 09:56:46.332  3424  3424 D MotionRecognitionService:   cableConnection= 1,
03-31 09:56:46.332  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 09:56:46.332  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 09:56:46.342  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 09:56:46.342  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:56:46.342  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:56:46.362  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 09:56:46.362  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:56:46.372  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:56:46.372  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:56:46.372  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:56:46.372  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:56:46.462  2891  4701 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-31 09:56:49.467  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 13, LCD = 0
,03-31 09:56:56.457  3424  4045 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:56:56.457  3424  4045 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:56:56.457  3424  4045 D BatteryService: online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
,03-31 09:56:56.457  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 09:56:56.457  3424  4045 D BatteryService: stay LED for fully charged
,03-31 09:56:56.467  3424  3424 I MotionRecognitionService: Plugged,
03-31 09:56:56.467  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 09:56:56.467  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 09:56:56.467  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 09:56:56.477  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 09:56:56.477  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:56:56.477  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:56:56.492  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 09:56:56.492  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:56:56.502  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:56:56.502  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:56:56.507  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:56:56.507  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:56:59.497  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 12, LCD = 0
,03-31 09:57:06.592  3424  3732 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:57:06.592  3424  3732 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:57:06.592  3424  3732 D BatteryService: online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,03-31 09:57:06.597  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 09:57:06.602  3424  3732 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 10ms
03-31 09:57:06.602  3424  3732 D BatteryService: stay LED for fully charged,
03-31 09:57:06.607  3424  3424 I MotionRecognitionService: Plugged
03-31 09:57:06.607  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 09:57:06.607  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 09:57:06.607  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 09:57:06.617  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-31 09:57:06.617  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,03-31 09:57:06.617  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-31 09:57:06.642  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 09:57:06.642  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:57:06.652  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:57:06.652  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:57:06.652  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:57:06.652  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:57:09.532  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 11, LCD = 0
,03-31 09:57:13.617  3424  3861 E Watchdog: !@Sync 33 [03-31 09:57:13.620]
,03-31 09:57:16.732  3424  3453 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:57:16.732  3424  3453 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:57:16.732  3424  3453 D BatteryService: online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,03-31 09:57:16.732  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 09:57:16.742  3424  3453 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 10ms
03-31 09:57:16.742  3424  3453 D BatteryService: stay LED for fully charged,
03-31 09:57:16.742  3424  3424 I MotionRecognitionService: Plugged
,03-31 09:57:16.742  3424  3424 D MotionRecognitionService:   cableConnection= 1,
03-31 09:57:16.742  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
03-31 09:57:16.742  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 09:57:16.757  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:57:16.757  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:57:16.757  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:57:16.767  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 09:57:16.767  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:57:16.782  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 09:57:16.782  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:57:16.782  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:57:16.782  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:57:19.557  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 11, LCD = 0
,03-31 09:57:26.877  3424  4420 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:57:26.877  3424  4420 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:57:26.877  3424  4420 D BatteryService: online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
03-31 09:57:26.877  3424  4420 D BatteryService: stay LED for fully charged
03-31 09:57:26.877  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 09:57:26.882  3424  3424 I MotionRecognitionService: Plugged,
03-31 09:57:26.882  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 09:57:26.882  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-31 09:57:26.882  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 09:57:26.887  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 09:57:26.887  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:57:26.887  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:57:26.902  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 09:57:26.902  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:57:26.912  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 09:57:26.912  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:57:26.912  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:57:26.912  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:57:26.947  3424  3584 I PowerManagerService: [PWL] Off : 950s ago
,03-31 09:57:29.587  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 10, LCD = 0
,03-31 09:57:37.007  3424  4035 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:57:37.007  3424  4035 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:57:37.007  3424  4035 D BatteryService: online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
,03-31 09:57:37.012  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 09:57:37.017  3424  3424 I MotionRecognitionService: Plugged
03-31 09:57:37.022  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 09:57:37.022  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 09:57:37.022  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 09:57:37.022  3424  4035 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 13ms,
03-31 09:57:37.022  3424  4035 D BatteryService: stay LED for fully charged
,03-31 09:57:37.032  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 09:57:37.032  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:57:37.032  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:57:37.052  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 09:57:37.052  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:57:37.062  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:57:37.062  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:57:37.062  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:57:37.067  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:57:39.617  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 12, LCD = 0
,03-31 09:57:43.627  3424  3861 E Watchdog: !@Sync 34 [03-31 09:57:43.633]
,03-31 09:57:46.462  2891  4701 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-31 09:57:47.147  3424  3451 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-31 09:57:47.147  3424  3451 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:57:47.147  3424  3451 D BatteryService: online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-10
,03-31 09:57:47.152  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 09:57:47.162  3424  3424 I MotionRecognitionService: Plugged
03-31 09:57:47.162  3424  3424 D MotionRecognitionService:   cableConnection= 1,
03-31 09:57:47.162  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 09:57:47.162  3424  3424 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 09:57:47.162  3424  3451 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 13ms
03-31 09:57:47.162  3424  3451 D BatteryService: stay LED for fully charged
,03-31 09:57:47.172  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 09:57:47.172  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:57:47.172  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:57:47.197  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 09:57:47.197  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:57:47.202  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:57:47.202  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:57:47.207  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:57:47.207  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:57:49.642  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 11, LCD = 0
,03-31 09:57:57.287  3424  4027 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:57:57.287  3424  4027 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:57:57.287  3424  4027 D BatteryService: online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,03-31 09:57:57.292  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 09:57:57.297  3424  3424 I MotionRecognitionService: Plugged
03-31 09:57:57.297  3424  3424 D MotionRecognitionService:   cableConnection= 1
,03-31 09:57:57.297  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
03-31 09:57:57.297  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
03-31 09:57:57.302  3424  4027 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 14ms,
,03-31 09:57:57.302  3424  4027 D BatteryService: stay LED for fully charged
03-31 09:57:57.312  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 09:57:57.312  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:57:57.312  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:57:57.332  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 09:57:57.332  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:57:57.342  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:57:57.342  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:57:57.342  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:57:57.342  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:57:59.667  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 13, LCD = 0
,03-31 09:58:07.427  3424  3816 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:58:07.427  3424  3816 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:58:07.427  3424  3816 D BatteryService: online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
03-31 09:58:07.427  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 09:58:07.432  3424  3816 D BatteryService: stay LED for fully charged
,03-31 09:58:07.437  3424  3424 I MotionRecognitionService: Plugged
03-31 09:58:07.437  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 09:58:07.437  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 09:58:07.437  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 09:58:07.442  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 09:58:07.447  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:58:07.447  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:58:07.467  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 09:58:07.467  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:58:07.477  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:58:07.477  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:58:07.477  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:58:07.477  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:58:09.697  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 12, LCD = 0
,03-31 09:58:13.637  3424  3861 E Watchdog: !@Sync 35 [03-31 09:58:13.640]
,03-31 09:58:17.567  3424  3837 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:58:17.567  3424  3837 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:58:17.567  3424  3837 D BatteryService: online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
,03-31 09:58:17.567  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 09:58:17.567  3424  3837 D BatteryService: stay LED for fully charged
,03-31 09:58:17.577  3424  3424 I MotionRecognitionService: Plugged
03-31 09:58:17.577  3424  3424 D MotionRecognitionService:   cableConnection= 1,
03-31 09:58:17.577  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 09:58:17.577  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 09:58:17.587  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 09:58:17.587  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:58:17.587  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:58:17.612  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 09:58:17.612  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:58:17.617  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 09:58:17.617  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:58:17.617  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:58:17.617  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:58:19.732  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 12, LCD = 0
,03-31 09:58:27.702  3424  4025 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:58:27.702  3424  4025 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:58:27.702  3424  4025 D BatteryService: online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
,03-31 09:58:27.707  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 09:58:27.707  3424  4025 D BatteryService: stay LED for fully charged,
,03-31 09:58:27.717  3424  3424 I MotionRecognitionService: Plugged,
03-31 09:58:27.717  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 09:58:27.717  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
03-31 09:58:27.717  3424  3424 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 09:58:27.727  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-31 09:58:27.727  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,03-31 09:58:27.732  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:58:27.747  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 09:58:27.747  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:58:27.747  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 09:58:27.747  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:58:27.762  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:58:27.762  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:58:29.757  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 12, LCD = 0
,03-31 09:58:37.842  3424  3965 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:58:37.842  3424  3965 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:58:37.842  3424  3965 D BatteryService: online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,03-31 09:58:37.842  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 09:58:37.852  3424  3965 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 11ms
03-31 09:58:37.852  3424  3965 D BatteryService: stay LED for fully charged,
,03-31 09:58:37.857  3424  3424 I MotionRecognitionService: Plugged,
03-31 09:58:37.857  3424  3424 D MotionRecognitionService:   cableConnection= 1
,03-31 09:58:37.857  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
03-31 09:58:37.857  3424  3424 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 09:58:37.867  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-31 09:58:37.867  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:58:37.867  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:58:37.877  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 09:58:37.877  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:58:37.892  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 09:58:37.892  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:58:37.892  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:58:37.892  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:58:39.787  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 11, LCD = 0
,03-31 09:58:43.642  3424  3861 E Watchdog: !@Sync 36 [03-31 09:58:43.648]
,03-31 09:58:46.462  2891  4701 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-31 09:58:47.977  3424  3938 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:58:47.982  3424  3938 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:58:47.982  3424  3938 D BatteryService: online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:4
,03-31 09:58:47.982  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 09:58:47.982  3424  3938 D BatteryService: stay LED for fully charged
,03-31 09:58:47.992  3424  3424 I MotionRecognitionService: Plugged
03-31 09:58:47.992  3424  3424 D MotionRecognitionService:   cableConnection= 1,
03-31 09:58:47.992  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 09:58:47.992  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 09:58:48.002  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 09:58:48.002  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:58:48.002  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:58:48.012  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 09:58:48.012  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:58:48.027  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 09:58:48.027  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:58:48.027  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:58:48.027  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:58:49.812  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 11, LCD = 0
,03-31 09:58:58.122  3424  4419 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:58:58.122  3424  4419 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:58:58.122  3424  4419 D BatteryService: online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
03-31 09:58:58.122  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 09:58:58.122  3424  4419 D BatteryService: stay LED for fully charged
,03-31 09:58:58.132  3424  3424 I MotionRecognitionService: Plugged
03-31 09:58:58.132  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 09:58:58.132  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 09:58:58.132  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 09:58:58.142  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:58:58.142  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:58:58.142  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:58:58.152  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 09:58:58.152  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:58:58.167  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 09:58:58.167  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:58:58.167  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:58:58.167  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:58:59.862  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 10, LCD = 0
,03-31 09:58:59.937  3424  3440 I art     : Background sticky concurrent mark sweep GC freed 59285(8MB) AllocSpace objects, 390(6MB) LOS objects, 21% free, 29MB/37MB, paused 2.985ms total 102.536ms
,03-31 09:59:06.957  3424  3584 I PowerManagerService: [PWL] Off : 1050s ago
,03-31 09:59:08.257  3424  4045 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-31 09:59:08.262  3424  4045 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:59:08.262  3424  4045 D BatteryService: online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
03-31 09:59:08.262  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 09:59:08.272  3424  3424 I MotionRecognitionService: Plugged
03-31 09:59:08.272  3424  3424 D MotionRecognitionService:   cableConnection= 1,
03-31 09:59:08.272  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 09:59:08.272  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 09:59:08.277  3424  4045 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 16ms,
,03-31 09:59:08.277  3424  4045 D BatteryService: stay LED for fully charged
,03-31 09:59:08.287  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 09:59:08.287  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:59:08.287  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:59:08.302  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 09:59:08.302  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:59:08.317  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 09:59:08.317  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:59:08.317  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:59:08.317  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:59:09.887  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 11, LCD = 0
,03-31 09:59:13.652  3424  3861 E Watchdog: !@Sync 37 [03-31 09:59:13.655]
,03-31 09:59:18.397  3424  3732 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-31 09:59:18.402  3424  3732 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:59:18.402  3424  3732 D BatteryService: online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
03-31 09:59:18.402  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 09:59:18.407  3424  3732 D BatteryService: stay LED for fully charged
,03-31 09:59:18.412  3424  3424 I MotionRecognitionService: Plugged,
03-31 09:59:18.412  3424  3424 D MotionRecognitionService:   cableConnection= 1,
,03-31 09:59:18.412  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 09:59:18.412  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 09:59:18.427  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 09:59:18.427  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:59:18.427  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:59:18.437  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-31 09:59:18.437  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:59:18.452  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 09:59:18.452  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:59:18.452  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:59:18.452  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:59:19.912  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 11, LCD = 0,
,03-31 09:59:28.532  3424  3453 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-31 09:59:28.537  3424  3453 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:59:28.537  3424  3453 D BatteryService: online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:2
03-31 09:59:28.537  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 09:59:28.542  3424  3453 D BatteryService: stay LED for fully charged
,03-31 09:59:28.547  3424  3424 I MotionRecognitionService: Plugged
03-31 09:59:28.547  3424  3424 D MotionRecognitionService:   cableConnection= 1
,03-31 09:59:28.547  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 09:59:28.547  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 09:59:28.557  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:59:28.557  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:59:28.557  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:59:28.567  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 09:59:28.567  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:59:28.582  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 09:59:28.582  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:59:28.582  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:59:28.582  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:59:29.947  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 11, LCD = 0
,03-31 09:59:38.677  3424  4420 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-31 09:59:38.677  3424  4420 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:59:38.677  3424  4420 D BatteryService: online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,03-31 09:59:38.677  3424  4420 D BatteryService: stay LED for fully charged
03-31 09:59:38.677  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 09:59:38.682  3424  3424 I MotionRecognitionService: Plugged
,03-31 09:59:38.687  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 09:59:38.687  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 09:59:38.687  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 09:59:38.692  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-31 09:59:38.692  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:59:38.692  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-31 09:59:38.702  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 09:59:38.702  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 09:59:38.707  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:59:38.722  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:59:38.722  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:59:38.722  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:59:39.972  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 10, LCD = 0
,03-31 09:59:43.657  3424  3861 E Watchdog: !@Sync 38 [03-31 09:59:43.663]
,03-31 09:59:46.462  2891  4701 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-31 09:59:48.812  3424  4419 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:59:48.812  3424  4419 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:59:48.812  3424  4419 D BatteryService: online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
,03-31 09:59:48.812  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 09:59:48.822  3424  3424 I MotionRecognitionService: Plugged
03-31 09:59:48.822  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 09:59:48.822  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 09:59:48.822  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 09:59:48.827  3424  4419 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 15ms,
03-31 09:59:48.827  3424  4419 D BatteryService: stay LED for fully charged
,03-31 09:59:48.837  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:59:48.837  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 09:59:48.837  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:59:48.847  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 09:59:48.852  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 09:59:48.862  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 09:59:48.862  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:59:48.862  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:59:48.862  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:59:50.002  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 9, LCD = 0
,03-31 09:59:58.947  3424  4045 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 09:59:58.947  3424  4045 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 09:59:58.947  3424  4045 D BatteryService: online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
,03-31 09:59:58.952  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 09:59:58.952  3424  4045 D BatteryService: stay LED for fully charged,
,03-31 09:59:58.962  3424  3424 I MotionRecognitionService: Plugged,
03-31 09:59:58.962  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 09:59:58.962  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-31 09:59:58.962  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 09:59:58.967  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 09:59:58.967  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-31 09:59:58.972  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 09:59:58.977  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 09:59:58.982  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
03-31 09:59:58.982  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 09:59:58.982  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 09:59:58.982  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 09:59:58.982  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 10:00:00.032  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 9, LCD = 0
,03-31 10:00:09.087  3424  3732 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 10:00:09.087  3424  3732 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 10:00:09.087  3424  3732 D BatteryService: online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:21
,03-31 10:00:09.092  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 10:00:09.102  3424  3424 I MotionRecognitionService: Plugged
03-31 10:00:09.102  3424  3424 D MotionRecognitionService:   cableConnection= 1,
03-31 10:00:09.102  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 10:00:09.102  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 10:00:09.102  3424  3732 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 15ms,
03-31 10:00:09.102  3424  3732 D BatteryService: stay LED for fully charged
,03-31 10:00:09.112  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 10:00:09.112  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 10:00:09.112  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 10:00:09.127  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 10:00:09.127  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 10:00:09.137  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 10:00:09.137  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:00:09.142  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:00:09.142  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 10:00:10.062  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 11, LCD = 0,
,03-31 10:00:13.667  3424  3861 E Watchdog: !@Sync 39 [03-31 10:00:13.671]
,03-31 10:00:19.227  3424  3453 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 10:00:19.227  3424  3453 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 10:00:19.227  3424  3453 D BatteryService: online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:4
,03-31 10:00:19.232  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 10:00:19.242  3424  3424 I MotionRecognitionService: Plugged
03-31 10:00:19.242  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 10:00:19.242  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 10:00:19.242  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 10:00:19.242  3424  3453 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 14ms,
03-31 10:00:19.242  3424  3453 D BatteryService: stay LED for fully charged
,03-31 10:00:19.252  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 10:00:19.252  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 10:00:19.252  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 10:00:19.262  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 10:00:19.262  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 10:00:19.277  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 10:00:19.277  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:00:19.277  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:00:19.277  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 10:00:20.092  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 11, LCD = 0
,03-31 10:00:29.362  3424  4420 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 10:00:29.362  3424  4420 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 10:00:29.362  3424  4420 D BatteryService: online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
,03-31 10:00:29.367  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 10:00:29.372  3424  4420 D BatteryService: stay LED for fully charged
,03-31 10:00:29.377  3424  3424 I MotionRecognitionService: Plugged
03-31 10:00:29.377  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 10:00:29.377  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 10:00:29.377  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 10:00:29.382  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 10:00:29.382  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 10:00:29.382  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 10:00:29.397  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 10:00:29.397  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 10:00:29.407  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 10:00:29.407  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:00:29.412  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:00:29.412  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 10:00:30.112  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 9, LCD = 0
,03-31 10:00:39.502  3424  4035 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 10:00:39.502  3424  4035 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 10:00:39.502  3424  4035 D BatteryService: online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
03-31 10:00:39.502  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 10:00:39.502  3424  4035 D BatteryService: stay LED for fully charged
,03-31 10:00:39.507  3424  3424 I MotionRecognitionService: Plugged
,03-31 10:00:39.507  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 10:00:39.507  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 10:00:39.507  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 10:00:39.517  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 10:00:39.517  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 10:00:39.517  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 10:00:39.532  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 10:00:39.532  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 10:00:39.542  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 10:00:39.542  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:00:39.542  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:00:39.542  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 10:00:40.142  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 10, LCD = 0
,03-31 10:00:41.022  3424  3606 D TimaService: TIMA: TimaService scheduler is intialized. 
03-31 10:00:41.022  3424  3606 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,03-31 10:00:41.027  3424  3605 D TimaService: TimaServiceHandler.handleMessage what =1
,03-31 10:00:41.687  3424  3571 I UsageStatsService: User[0] Flushing usage stats to disk
,03-31 10:00:43.557  3424  3606 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
03-31 10:00:43.557  3424  3606 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,03-31 10:00:43.577  3424  3606 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;,
,03-31 10:00:43.587  3424  3606 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,03-31 10:00:43.672  3424  3861 E Watchdog: !@Sync 40 [03-31 10:00:43.678]
,03-31 10:00:46.462  2891  4701 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-31 10:00:49.637  3424  3451 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 10:00:49.637  3424  3451 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 10:00:49.637  3424  3451 D BatteryService: online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
,03-31 10:00:49.642  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 10:00:49.652  3424  3424 I MotionRecognitionService: Plugged
03-31 10:00:49.652  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 10:00:49.652  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 10:00:49.652  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
03-31 10:00:49.652  3424  3451 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 15ms
03-31 10:00:49.652  3424  3451 D BatteryService: stay LED for fully charged
,03-31 10:00:49.662  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 10:00:49.662  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 10:00:49.662  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 10:00:49.677  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 10:00:49.677  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 10:00:49.687  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 10:00:49.687  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:00:49.687  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:00:49.687  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 10:00:50.167  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 10, LCD = 0
,03-31 10:00:51.957  3424  3584 I PowerManagerService: [PWL] Off : 1155s ago
,03-31 10:00:59.777  3424  3965 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 10:00:59.782  3424  3965 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 10:00:59.782  3424  3965 D BatteryService: online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
,03-31 10:00:59.782  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 10:00:59.787  3424  3965 D BatteryService: stay LED for fully charged
,03-31 10:00:59.792  3424  3424 I MotionRecognitionService: Plugged,
03-31 10:00:59.792  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 10:00:59.792  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 10:00:59.792  3424  3424 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 10:00:59.802  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 10:00:59.802  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 10:00:59.802  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 10:00:59.812  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 10:00:59.812  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 10:00:59.827  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 10:00:59.827  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:00:59.827  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:00:59.827  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 10:01:00.197  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 10, LCD = 0,
,03-31 10:01:09.917  3424  3938 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 10:01:09.917  3424  3938 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 10:01:09.917  3424  3938 D BatteryService: online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-3
,03-31 10:01:09.922  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 10:01:09.927  3424  3938 D BatteryService: stay LED for fully charged
,03-31 10:01:09.932  3424  3424 I MotionRecognitionService: Plugged,
03-31 10:01:09.932  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 10:01:09.932  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 10:01:09.932  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 10:01:09.937  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 10:01:09.937  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 10:01:09.937  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 10:01:09.952  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 10:01:09.952  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 10:01:09.967  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 10:01:09.967  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:01:09.967  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:01:09.967  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 10:01:10.232  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 10, LCD = 0
,03-31 10:01:13.682  3424  3861 E Watchdog: !@Sync 41 [03-31 10:01:13.686]
,03-31 10:01:20.057  3424  4419 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 10:01:20.062  3424  4419 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 10:01:20.062  3424  4419 D BatteryService: online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
,03-31 10:01:20.062  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 10:01:20.067  3424  4419 D BatteryService: stay LED for fully charged
,03-31 10:01:20.072  3424  3424 I MotionRecognitionService: Plugged
03-31 10:01:20.072  3424  3424 D MotionRecognitionService:   cableConnection= 1,
03-31 10:01:20.072  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 10:01:20.072  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 10:01:20.082  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 10:01:20.082  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 10:01:20.082  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 10:01:20.097  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 10:01:20.102  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 10:01:20.112  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 10:01:20.112  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:01:20.112  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:01:20.112  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 10:01:20.252  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 10, LCD = 0
,03-31 10:01:30.202  3424  4045 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 10:01:30.202  3424  4045 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 10:01:30.202  3424  4045 D BatteryService: online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
,03-31 10:01:30.207  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 10:01:30.207  3424  4045 D BatteryService: stay LED for fully charged
,03-31 10:01:30.212  3424  3424 I MotionRecognitionService: Plugged,
03-31 10:01:30.212  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 10:01:30.212  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 10:01:30.212  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 10:01:30.222  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-31 10:01:30.222  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 10:01:30.222  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 10:01:30.242  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 10:01:30.242  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 10:01:30.252  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 10:01:30.252  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:01:30.252  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:01:30.252  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 10:01:30.262  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 10, LCD = 0
,03-31 10:01:40.282  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 10, LCD = 0
,03-31 10:01:40.337  3424  3732 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-31 10:01:40.337  3424  3732 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 10:01:40.337  3424  3732 D BatteryService: online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
03-31 10:01:40.337  3424  3732 D BatteryService: stay LED for fully charged
03-31 10:01:40.337  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 10:01:40.337  3424  3424 I MotionRecognitionService: Plugged
03-31 10:01:40.342  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 10:01:40.342  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 10:01:40.342  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 10:01:40.342  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 10:01:40.342  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 10:01:40.342  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 10:01:40.347  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 10:01:40.347  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 10:01:40.362  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 10:01:40.362  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:01:40.367  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:01:40.367  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 10:01:43.687  3424  3861 E Watchdog: !@Sync 42 [03-31 10:01:43.694]
,03-31 10:01:46.462  2891  4701 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-31 10:01:50.307  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 10, LCD = 0
,03-31 10:01:50.462  3424  3453 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 10:01:50.462  3424  3453 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 10:01:50.462  3424  3453 D BatteryService: online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
03-31 10:01:50.462  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 10:01:50.462  3424  3453 D BatteryService: stay LED for fully charged
,03-31 10:01:50.472  3424  3424 I MotionRecognitionService: Plugged
03-31 10:01:50.472  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 10:01:50.472  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 10:01:50.472  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 10:01:50.482  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 10:01:50.482  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-31 10:01:50.482  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 10:01:50.502  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 10:01:50.502  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 10:01:50.512  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 10:01:50.512  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 10:01:50.512  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:01:50.512  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 10:02:00.337  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 9, LCD = 0
,03-31 10:02:00.597  3424  4420 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 10:02:00.602  3424  4420 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 10:02:00.602  3424  4420 D BatteryService: online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,03-31 10:02:00.602  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 10:02:00.612  3424  3424 I MotionRecognitionService: Plugged
03-31 10:02:00.612  3424  3424 D MotionRecognitionService:   cableConnection= 1,
03-31 10:02:00.612  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-31 10:02:00.612  3424  3424 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 10:02:00.612  3424  4420 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 14ms
03-31 10:02:00.612  3424  4420 D BatteryService: stay LED for fully charged,
,03-31 10:02:00.622  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 10:02:00.627  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 10:02:00.627  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 10:02:00.642  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 10:02:00.647  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 10:02:00.657  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 10:02:00.657  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:02:00.657  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:02:00.657  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 10:02:10.367  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 9, LCD = 0
,03-31 10:02:10.737  3424  4035 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 10:02:10.737  3424  4035 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 10:02:10.737  3424  4035 D BatteryService: online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,03-31 10:02:10.742  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 10:02:10.747  3424  3424 I MotionRecognitionService: Plugged
03-31 10:02:10.747  3424  3424 D MotionRecognitionService:   cableConnection= 1,
03-31 10:02:10.747  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 10:02:10.747  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
03-31 10:02:10.752  3424  4035 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 12ms
,03-31 10:02:10.752  3424  4035 D BatteryService: stay LED for fully charged,
,03-31 10:02:10.757  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 10:02:10.762  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-31 10:02:10.762  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 10:02:10.777  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 10:02:10.777  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 10:02:10.787  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 10:02:10.792  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:02:10.792  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 10:02:10.792  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 10:02:13.697  3424  3861 E Watchdog: !@Sync 43 [03-31 10:02:13.701]
,03-31 10:02:20.397  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 9, LCD = 0
,03-31 10:02:20.877  3424  3451 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 10:02:20.877  3424  3451 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 10:02:20.877  3424  3451 D BatteryService: online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
,03-31 10:02:20.882  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 10:02:20.887  3424  3424 I MotionRecognitionService: Plugged
03-31 10:02:20.887  3424  3424 D MotionRecognitionService:   cableConnection= 1,
03-31 10:02:20.887  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 10:02:20.887  3424  3424 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 10:02:20.892  3424  3451 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 14ms
,03-31 10:02:20.892  3424  3451 D BatteryService: stay LED for fully charged,
,03-31 10:02:20.902  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-31 10:02:20.902  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-31 10:02:20.902  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-31 10:02:20.927  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 10:02:20.927  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 10:02:20.937  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 10:02:20.937  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:02:20.937  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:02:20.937  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 10:02:30.427  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 9, LCD = 0
,03-31 10:02:31.012  3424  4027 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 10:02:31.012  3424  4027 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 10:02:31.012  3424  4027 D BatteryService: online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-10
,03-31 10:02:31.017  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 10:02:31.017  3424  4027 D BatteryService: stay LED for fully charged
,03-31 10:02:31.027  3424  3424 I MotionRecognitionService: Plugged,
03-31 10:02:31.027  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 10:02:31.027  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-31 10:02:31.027  3424  3424 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 10:02:31.037  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 10:02:31.037  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 10:02:31.037  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 10:02:31.057  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 10:02:31.057  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 10:02:31.067  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 10:02:31.067  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:02:31.067  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:02:31.067  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 10:02:40.462  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 9, LCD = 0
,03-31 10:02:41.152  3424  3816 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 10:02:41.157  3424  3816 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 10:02:41.157  3424  3816 D BatteryService: online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,03-31 10:02:41.157  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 10:02:41.167  3424  3424 I MotionRecognitionService: Plugged
03-31 10:02:41.167  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 10:02:41.167  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 10:02:41.167  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 10:02:41.167  3424  3816 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 13ms,
03-31 10:02:41.167  3424  3816 D BatteryService: stay LED for fully charged
,03-31 10:02:41.177  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 10:02:41.177  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 10:02:41.177  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 10:02:41.192  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 10:02:41.197  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 10:02:41.207  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 10:02:41.207  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:02:41.207  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:02:41.207  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 10:02:41.957  3424  3584 I PowerManagerService: [PWL] Off : 1265s ago
,03-31 10:02:43.707  3424  3861 E Watchdog: !@Sync 44 [03-31 10:02:43.710]
,03-31 10:02:46.462  2891  4701 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-31 10:02:50.492  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 9, LCD = 0
,03-31 10:02:51.292  3424  3837 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 10:02:51.292  3424  3837 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 10:02:51.292  3424  3837 D BatteryService: online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
,03-31 10:02:51.297  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 10:02:51.297  3424  3837 D BatteryService: stay LED for fully charged
,03-31 10:02:51.302  3424  3424 I MotionRecognitionService: Plugged
03-31 10:02:51.302  3424  3424 D MotionRecognitionService:   cableConnection= 1,
03-31 10:02:51.302  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-31 10:02:51.302  3424  3424 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 10:02:51.317  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 10:02:51.317  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 10:02:51.317  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 10:02:51.337  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 10:02:51.337  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 10:02:51.347  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 10:02:51.347  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 10:02:51.347  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 10:02:51.347  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 10:03:00.522  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 9, LCD = 0
,03-31 10:03:01.427  3424  4025 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 10:03:01.427  3424  4025 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
,03-31 10:03:01.427  3424  4025 D BatteryService: online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
03-31 10:03:01.432  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 10:03:01.432  3424  4025 D BatteryService: stay LED for fully charged
,03-31 10:03:01.442  3424  3424 I MotionRecognitionService: Plugged,
03-31 10:03:01.442  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 10:03:01.442  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-31 10:03:01.442  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 10:03:01.452  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 10:03:01.452  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 10:03:01.452  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 10:03:01.472  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 10:03:01.472  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 10:03:01.482  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 10:03:01.482  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:03:01.482  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:03:01.482  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 10:03:10.552  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 8, LCD = 0
,03-31 10:03:11.562  3424  3965 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-31 10:03:13.712  3424  3861 E Watchdog: !@Sync 45 [03-31 10:03:13.718]
,03-31 10:03:20.582  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 8, LCD = 0
,03-31 10:03:21.702  3424  3816 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-31 10:03:21.707  3424  3816 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 10:03:21.707  3424  3816 D BatteryService: online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
03-31 10:03:21.707  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 10:03:21.712  3424  3816 D BatteryService: stay LED for fully charged
,03-31 10:03:21.717  3424  3424 I MotionRecognitionService: Plugged,
03-31 10:03:21.717  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 10:03:21.717  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-31 10:03:21.717  3424  3424 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 10:03:21.727  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-31 10:03:21.727  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 10:03:21.727  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 10:03:21.752  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 10:03:21.757  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 10:03:21.762  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 10:03:21.762  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:03:21.762  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:03:21.762  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 10:03:30.612  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 7, LCD = 0
,03-31 10:03:31.852  3424  3837 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 10:03:31.852  3424  3837 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 10:03:31.852  3424  3837 D BatteryService: online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-3
03-31 10:03:31.852  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 10:03:31.852  3424  3837 D BatteryService: stay LED for fully charged
,03-31 10:03:31.862  3424  3424 I MotionRecognitionService: Plugged
03-31 10:03:31.862  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 10:03:31.862  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 10:03:31.862  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 10:03:31.867  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 10:03:31.867  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 10:03:31.867  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 10:03:31.887  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 10:03:31.892  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 10:03:31.897  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 10:03:31.897  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:03:31.897  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:03:31.897  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 10:03:40.642  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 6, LCD = 0,
,03-31 10:03:41.977  3424  4025 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 10:03:41.977  3424  4025 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 10:03:41.977  3424  4025 D BatteryService: online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,03-31 10:03:41.977  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 10:03:41.977  3424  4025 D BatteryService: stay LED for fully charged
,03-31 10:03:41.987  3424  3424 I MotionRecognitionService: Plugged
03-31 10:03:41.987  3424  3424 D MotionRecognitionService:   cableConnection= 1,
03-31 10:03:41.987  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 10:03:41.987  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 10:03:41.992  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 10:03:41.992  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 10:03:41.997  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 10:03:42.017  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 10:03:42.017  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 10:03:42.027  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 10:03:42.027  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:03:42.027  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:03:42.027  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 10:03:43.722  3424  3861 E Watchdog: !@Sync 46 [03-31 10:03:43.725]
,03-31 10:03:46.462  2891  4701 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-31 10:03:50.672  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 8, LCD = 0
,03-31 10:03:52.117  3424  3965 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 10:03:52.117  3424  3965 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 10:03:52.117  3424  3965 D BatteryService: online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:2
,03-31 10:03:52.117  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 10:03:52.122  3424  3965 D BatteryService: stay LED for fully charged
,03-31 10:03:52.127  3424  3424 I MotionRecognitionService: Plugged
03-31 10:03:52.127  3424  3424 D MotionRecognitionService:   cableConnection= 1,
,03-31 10:03:52.127  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 10:03:52.127  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 10:03:52.137  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-31 10:03:52.137  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
03-31 10:03:52.137  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 10:03:52.152  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 10:03:52.157  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 10:03:52.157  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 10:03:52.167  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:03:52.167  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:03:52.167  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 10:04:00.702  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 7, LCD = 0
,03-31 10:04:02.252  3424  3938 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-31 10:04:02.257  3424  3938 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 10:04:02.257  3424  3938 D BatteryService: online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-2
03-31 10:04:02.257  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 10:04:02.262  3424  3938 D BatteryService: stay LED for fully charged
,03-31 10:04:02.267  3424  3424 I MotionRecognitionService: Plugged,
03-31 10:04:02.267  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 10:04:02.267  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-31 10:04:02.267  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 10:04:02.277  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 10:04:02.277  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 10:04:02.277  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 10:04:02.292  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 10:04:02.292  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 10:04:02.302  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 10:04:02.302  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:04:02.302  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:04:02.302  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 10:04:10.722  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 6, LCD = 0
,03-31 10:04:12.387  3424  4419 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 10:04:12.387  3424  4419 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 10:04:12.387  3424  4419 D BatteryService: online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:4
,03-31 10:04:12.392  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 10:04:12.392  3424  4419 D BatteryService: stay LED for fully charged
,03-31 10:04:12.402  3424  3424 I MotionRecognitionService: Plugged
03-31 10:04:12.402  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 10:04:12.402  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 10:04:12.402  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 10:04:12.412  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 10:04:12.412  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 10:04:12.412  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 10:04:12.417  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 10:04:12.422  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 10:04:12.432  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 10:04:12.432  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:04:12.432  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:04:12.432  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 10:04:13.732  3424  3861 E Watchdog: !@Sync 47 [03-31 10:04:13.732]
,03-31 10:04:20.752  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 6, LCD = 0,
,03-31 10:04:22.527  3424  4045 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 10:04:22.527  3424  4045 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 10:04:22.527  3424  4045 D BatteryService: online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
,03-31 10:04:22.532  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 10:04:22.532  3424  4045 D BatteryService: stay LED for fully charged
,03-31 10:04:22.542  3424  3424 I MotionRecognitionService: Plugged
03-31 10:04:22.542  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 10:04:22.542  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 10:04:22.542  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 10:04:22.547  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-31 10:04:22.547  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 10:04:22.547  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 10:04:22.567  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 10:04:22.567  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 10:04:22.577  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 10:04:22.577  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:04:22.577  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:04:22.577  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 10:04:30.782  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 6, LCD = 0
,03-31 10:04:32.667  3424  3732 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 10:04:32.667  3424  3732 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 10:04:32.667  3424  3732 D BatteryService: online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
,03-31 10:04:32.672  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 10:04:32.672  3424  3732 D BatteryService: stay LED for fully charged
,03-31 10:04:32.677  3424  3424 I MotionRecognitionService: Plugged,
03-31 10:04:32.677  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 10:04:32.677  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 10:04:32.677  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 10:04:32.687  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-31 10:04:32.687  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 10:04:32.687  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 10:04:32.707  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 10:04:32.707  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 10:04:32.722  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 10:04:32.722  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 10:04:32.722  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:04:32.722  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 10:04:36.962  3424  3584 I PowerManagerService: [PWL] Off : 1380s ago
,03-31 10:04:40.812  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 5, LCD = 0
,03-31 10:04:42.807  3424  3453 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 10:04:42.807  3424  3453 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 10:04:42.807  3424  3453 D BatteryService: online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
,03-31 10:04:42.807  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 10:04:42.817  3424  3424 I MotionRecognitionService: Plugged,
03-31 10:04:42.817  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 10:04:42.817  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
03-31 10:04:42.817  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
03-31 10:04:42.817  3424  3453 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 12ms,
,03-31 10:04:42.817  3424  3453 D BatteryService: stay LED for fully charged,
,03-31 10:04:42.832  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-31 10:04:42.832  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,03-31 10:04:42.832  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-31 10:04:42.857  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 10:04:42.857  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 10:04:42.867  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 10:04:42.867  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:04:42.867  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:04:42.867  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 10:04:43.737  3424  3861 E Watchdog: !@Sync 48 [03-31 10:04:43.742]
,03-31 10:04:46.462  2891  4701 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-31 10:04:50.842  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 5, LCD = 0
,03-31 10:04:52.942  3424  4420 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 10:04:52.942  3424  4420 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
,03-31 10:04:52.947  3424  4420 D BatteryService: online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
03-31 10:04:52.947  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 10:04:52.952  3424  4420 D BatteryService: stay LED for fully charged
,03-31 10:04:52.957  3424  3424 I MotionRecognitionService: Plugged,
03-31 10:04:52.957  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 10:04:52.957  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
03-31 10:04:52.957  3424  3424 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 10:04:52.967  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 10:04:52.967  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 10:04:52.967  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-31 10:04:52.987  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 10:04:52.987  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 10:04:52.997  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 10:04:52.997  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:04:52.997  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:04:52.997  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 10:05:00.872  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 6, LCD = 0
,03-31 10:05:03.082  3424  4035 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 10:05:03.082  3424  4035 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 10:05:03.082  3424  4035 D BatteryService: online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-5
,03-31 10:05:03.087  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 10:05:03.097  3424  3424 I MotionRecognitionService: Plugged
03-31 10:05:03.097  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 10:05:03.097  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 10:05:03.097  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 10:05:03.097  3424  4035 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 13ms,
03-31 10:05:03.097  3424  4035 D BatteryService: stay LED for fully charged
,03-31 10:05:03.107  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 10:05:03.107  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 10:05:03.107  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 10:05:03.127  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 10:05:03.127  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 10:05:03.137  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 10:05:03.137  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:05:03.137  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:05:03.137  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 10:05:10.907  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 6, LCD = 0
,03-31 10:05:13.227  3424  3451 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 10:05:13.227  3424  3451 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 10:05:13.227  3424  3451 D BatteryService: online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
,03-31 10:05:13.227  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 10:05:13.232  3424  3451 D BatteryService: stay LED for fully charged
,03-31 10:05:13.237  3424  3424 I MotionRecognitionService: Plugged
03-31 10:05:13.237  3424  3424 D MotionRecognitionService:   cableConnection= 1,
03-31 10:05:13.237  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 10:05:13.237  3424  3424 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 10:05:13.247  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-31 10:05:13.247  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 10:05:13.247  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 10:05:13.272  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 10:05:13.272  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 10:05:13.282  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 10:05:13.282  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:05:13.282  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:05:13.282  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 10:05:13.747  3424  3861 E Watchdog: !@Sync 49 [03-31 10:05:13.750]
,03-31 10:05:20.937  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 6, LCD = 0
,03-31 10:05:23.367  3424  4027 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 10:05:23.367  3424  4027 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 10:05:23.367  3424  4027 D BatteryService: online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
,03-31 10:05:23.372  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 10:05:23.372  3424  4027 D BatteryService: stay LED for fully charged
,03-31 10:05:23.377  3424  3424 I MotionRecognitionService: Plugged,
03-31 10:05:23.377  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 10:05:23.377  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 10:05:23.377  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 10:05:23.387  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 10:05:23.387  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 10:05:23.387  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 10:05:23.407  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 10:05:23.412  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 10:05:23.417  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 10:05:23.417  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:05:23.417  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:05:23.417  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 10:05:30.967  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 8, LCD = 0
,03-31 10:05:33.502  3424  3816 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 10:05:33.502  3424  3816 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
,03-31 10:05:33.507  3424  3816 D BatteryService: online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:36
03-31 10:05:33.507  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 10:05:33.512  3424  3816 D BatteryService: stay LED for fully charged
,03-31 10:05:33.517  3424  3424 I MotionRecognitionService: Plugged,
03-31 10:05:33.517  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 10:05:33.517  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-31 10:05:33.517  3424  3424 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 10:05:33.527  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 10:05:33.527  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
03-31 10:05:33.527  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 10:05:33.542  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 10:05:33.547  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 10:05:33.547  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 10:05:33.562  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:05:33.562  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:05:33.562  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 10:05:40.992  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 8, LCD = 0
,03-31 10:05:41.022  3424  3606 D TimaService: TIMA: TimaService scheduler is intialized. 
03-31 10:05:41.022  3424  3606 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,03-31 10:05:41.027  3424  3605 D TimaService: TimaServiceHandler.handleMessage what =1
,03-31 10:05:43.662  3424  3837 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 10:05:43.662  3424  3837 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 10:05:43.662  3424  3837 D BatteryService: online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,03-31 10:05:43.662  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 10:05:43.667  3424  3837 D BatteryService: stay LED for fully charged
,03-31 10:05:43.672  3424  3424 I MotionRecognitionService: Plugged
03-31 10:05:43.672  3424  3424 D MotionRecognitionService:   cableConnection= 1,
03-31 10:05:43.672  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 10:05:43.672  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 10:05:43.682  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 10:05:43.682  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 10:05:43.682  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 10:05:43.702  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 10:05:43.702  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 10:05:43.712  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 10:05:43.712  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:05:43.712  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:05:43.712  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 10:05:43.752  3424  3861 E Watchdog: !@Sync 50 [03-31 10:05:43.759]
,03-31 10:05:45.857  3424  3606 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
03-31 10:05:45.857  3424  3606 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,03-31 10:05:45.877  3424  3606 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
03-31 10:05:45.877  3424  3606 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,03-31 10:05:46.462  2891  4701 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-31 10:05:51.022  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 9, LCD = 0
,03-31 10:05:53.802  3424  4025 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 10:05:53.802  3424  4025 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 10:05:53.802  3424  4025 D BatteryService: online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
,03-31 10:05:53.802  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 10:05:53.812  3424  4025 D BatteryService: stay LED for fully charged
03-31 10:05:53.812  3424  3424 I MotionRecognitionService: Plugged,
03-31 10:05:53.812  3424  3424 D MotionRecognitionService:   cableConnection= 1
,03-31 10:05:53.812  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 10:05:53.812  3424  3424 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 10:05:53.827  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 10:05:53.827  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 10:05:53.827  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 10:05:53.847  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 10:05:53.847  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 10:05:53.857  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 10:05:53.857  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 10:05:53.857  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 10:05:53.857  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 10:06:01.047  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 7, LCD = 0
,03-31 10:06:03.937  3424  3965 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-31 10:06:03.937  3424  3965 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 10:06:03.937  3424  3965 D BatteryService: online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
,03-31 10:06:03.942  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 10:06:03.952  3424  3424 I MotionRecognitionService: Plugged
03-31 10:06:03.952  3424  3424 D MotionRecognitionService:   cableConnection= 1,
03-31 10:06:03.952  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 10:06:03.952  3424  3424 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 10:06:03.952  3424  3965 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 13ms,
,03-31 10:06:03.952  3424  3965 D BatteryService: stay LED for fully charged
,03-31 10:06:03.962  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 10:06:03.962  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 10:06:03.962  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-31 10:06:03.987  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 10:06:03.987  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 10:06:03.997  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 10:06:03.997  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:06:03.997  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:06:03.997  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 10:06:11.082  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 6, LCD = 0
,03-31 10:06:13.757  3424  3861 E Watchdog: !@Sync 51 [03-31 10:06:13.761]
,03-31 10:06:14.077  3424  3938 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 10:06:14.077  3424  3938 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
,03-31 10:06:14.082  3424  3938 D BatteryService: online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
03-31 10:06:14.082  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 10:06:14.087  3424  3938 D BatteryService: stay LED for fully charged
,03-31 10:06:14.092  3424  3424 I MotionRecognitionService: Plugged
03-31 10:06:14.092  3424  3424 D MotionRecognitionService:   cableConnection= 1,
03-31 10:06:14.092  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-31 10:06:14.092  3424  3424 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 10:06:14.102  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 10:06:14.102  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 10:06:14.102  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 10:06:14.117  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 10:06:14.117  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 10:06:14.127  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 10:06:14.127  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:06:14.127  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:06:14.132  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 10:06:21.112  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 6, LCD = 0
,03-31 10:06:24.217  3424  4419 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 10:06:24.217  3424  4419 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 10:06:24.217  3424  4419 D BatteryService: online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
,03-31 10:06:24.222  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 10:06:24.227  3424  4419 D BatteryService: stay LED for fully charged,
,03-31 10:06:24.232  3424  3424 I MotionRecognitionService: Plugged,
03-31 10:06:24.232  3424  3424 D MotionRecognitionService:   cableConnection= 1,
03-31 10:06:24.232  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
03-31 10:06:24.232  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 10:06:24.237  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 10:06:24.237  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 10:06:24.237  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 10:06:24.252  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 10:06:24.252  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 10:06:24.262  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 10:06:24.262  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:06:24.262  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:06:24.262  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 10:06:31.137  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 7, LCD = 0
,03-31 10:06:34.357  3424  4045 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 10:06:34.357  3424  4045 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 10:06:34.357  3424  4045 D BatteryService: online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:3
03-31 10:06:34.357  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 10:06:34.362  3424  4045 D BatteryService: stay LED for fully charged,
,03-31 10:06:34.367  3424  3424 I MotionRecognitionService: Plugged
03-31 10:06:34.367  3424  3424 D MotionRecognitionService:   cableConnection= 1
,03-31 10:06:34.367  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 10:06:34.367  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 10:06:34.372  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 10:06:34.372  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 10:06:34.372  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 10:06:34.382  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 10:06:34.382  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 10:06:34.387  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 10:06:34.397  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:06:34.397  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 10:06:34.397  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 10:06:36.962  3424  3584 I PowerManagerService: [PWL] Off : 1500s ago,
,03-31 10:06:41.172  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 8, LCD = 0
,03-31 10:06:43.767  3424  3861 E Watchdog: !@Sync 52 [03-31 10:06:43.769]
,03-31 10:06:44.492  3424  3732 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 10:06:44.492  3424  3732 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 10:06:44.492  3424  3732 D BatteryService: online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
,03-31 10:06:44.497  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 10:06:44.497  3424  3732 D BatteryService: stay LED for fully charged
,03-31 10:06:44.502  3424  3424 I MotionRecognitionService: Plugged,
03-31 10:06:44.502  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 10:06:44.502  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-31 10:06:44.502  3424  3424 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 10:06:44.512  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 10:06:44.512  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 10:06:44.517  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 10:06:44.537  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 10:06:44.537  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 10:06:44.547  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 10:06:44.547  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:06:44.547  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:06:44.547  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 10:06:46.462  2891  4701 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-31 10:06:51.202  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 6, LCD = 0
,03-31 10:06:54.627  3424  3453 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 10:06:54.632  3424  3453 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4400, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 10:06:54.632  3424  3453 D BatteryService: online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,03-31 10:06:54.632  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 10:06:54.642  3424  3424 I MotionRecognitionService: Plugged
03-31 10:06:54.642  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 10:06:54.642  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
03-31 10:06:54.642  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 10:06:54.647  3424  3453 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 16ms,
03-31 10:06:54.647  3424  3453 D BatteryService: stay LED for fully charged
,03-31 10:06:54.657  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 10:06:54.657  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 10:06:54.657  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 10:06:54.672  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 10:06:54.672  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 10:06:54.682  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 10:06:54.687  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:06:54.687  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 10:06:54.687  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 10:07:01.227  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 8, LCD = 0
,03-31 10:07:04.767  3424  4420 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 10:07:04.767  3424  4420 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 10:07:04.767  3424  4420 D BatteryService: online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,03-31 10:07:04.767  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 10:07:04.777  3424  4420 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 11ms
03-31 10:07:04.777  3424  4420 D BatteryService: stay LED for fully charged
,03-31 10:07:04.782  3424  3424 I MotionRecognitionService: Plugged,
03-31 10:07:04.782  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 10:07:04.782  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 10:07:04.782  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 10:07:04.792  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 10:07:04.792  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 10:07:04.792  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 10:07:04.812  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 10:07:04.817  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 10:07:04.822  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 10:07:04.822  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:07:04.822  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:07:04.822  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 10:07:11.257  3424  6055 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 7, LCD = 0
,03-31 10:07:13.772  3424  3861 E Watchdog: !@Sync 53 [03-31 10:07:13.777]
,03-31 10:07:14.907  3424  4035 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 10:07:14.912  3424  4035 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 10:07:14.912  3424  4035 D BatteryService: online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-19
,03-31 10:07:14.912  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 10:07:14.922  3424  3424 I MotionRecognitionService: Plugged
03-31 10:07:14.922  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-31 10:07:14.922  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 10:07:14.922  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-31 10:07:14.922  3424  4035 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 13ms,
03-31 10:07:14.922  3424  4035 D BatteryService: stay LED for fully charged
,03-31 10:07:14.932  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 10:07:14.932  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 10:07:14.932  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-31 10:07:14.947  5874  5874 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 10:07:14.947  5874  5948 D HeadsetStateMachine: Disconnected process message: 10
,03-31 10:07:14.962  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 10:07:14.962  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:07:14.962  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:07:14.962  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,TIME-OUT KILL (timeout was 1400000ms),03-31 10:07:17.147 12194 12194 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
03-31 10:07:17.152 12194 12194 D AndroidRuntime: CheckJNI is OFF
03-31 10:07:17.152 12194 12194 D AndroidRuntime: readGMSProperty: start
03-31 10:07:17.152 12194 12194 D AndroidRuntime: readGMSProperty: already setted!!
03-31 10:07:17.152 12194 12194 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-31 10:07:17.152 12194 12194 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-31 10:07:17.152 12194 12194 D AndroidRuntime: readGMSProperty: end
03-31 10:07:17.152 12194 12194 D AndroidRuntime: addProductProperty: start
03-31 10:07:17.247 12194 12194 E AffinityControl: AffinityControl: registerfunction enter
03-31 10:07:17.262 12194 12194 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
03-31 10:07:17.272  3424  4420 D PackageManager: START PACKAGE DELETE: observer{596639796}
03-31 10:07:17.272  3424  4420 D PackageManager: pkg{<packageName>}
03-31 10:07:17.272  3424  4420 D PackageManager: user{0}
03-31 10:07:17.272  3424  4420 D PackageManager: caller{2000}
03-31 10:07:17.272  3424  4420 D PackageManager: flags{2}
03-31 10:07:17.272  3424  4420 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
03-31 10:07:17.272  3424  4420 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
03-31 10:07:17.272  3424  3590 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
03-31 10:07:17.272  3424  4420 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
03-31 10:07:17.272  3424  4420 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
03-31 10:07:17.272  3424  4420 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
03-31 10:07:17.272  3424  3590 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
03-31 10:07:17.277  3424  3590 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
03-31 10:07:17.277  3424  3590 D ApplicationPolicy: getApplicationUninstallationEnabled
03-31 10:07:17.277  3424  3590 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
03-31 10:07:17.277  3424  3590 D PackageManager: !@killApplicatoin: 10011, uninstall pkg
03-31 10:07:17.282  3424  3574 I ActivityManager: Force stopping com.test.thalitest appid=10011 user=-1: uninstall pkg
03-31 10:07:17.282  3424  3574 I ActivityManager: Killing 11127:com.test.thalitest/u0a11 (adj 0): stop com.test.thalitest cause uninstall pkg
03-31 10:07:17.307  3424  3574 I ActivityManager:   Force finishing activity 3 ActivityRecord{10f7b4e3 u0 com.test.thalitest/.MainActivity t42}
03-31 10:07:17.307  3424  3574 W ActivityManager: mDVFSHelper.acquire()
03-31 10:07:17.382  3424  3590 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
03-31 10:07:17.387  3424  3590 W PackageSettings: Skipping PackageSetting{a6bd115 com.example.hello/10691} due to missing metadata
03-31 10:07:17.402  3424  3590 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
03-31 10:07:17.412  3424  3574 D PowerManagerService: setKeyboardVisibility: false
03-31 10:07:17.412  3424  3574 I ActivityManager: Skip updateThumbnail for r=ActivityRecord{26fc9258 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t40}
03-31 10:07:17.417  3424  3837 I WindowState: WIN DEATH: Window{5301479 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}
03-31 10:07:17.417  2861  3014 I SurfaceFlinger: id=15 Removed NainActivit (6/8)
03-31 10:07:17.417  2861  4065 I SurfaceFlinger: id=15 Removed NainActivit (-2/8)
03-31 10:07:17.422  2861  9074 I SurfaceFlinger: id=15 Removed NainActivit (-2/8)
03-31 10:07:17.422  3424  3837 D InputDispatcher: Focus left window: 11127
03-31 10:07:17.422  3424  3837 D MultiWindowConverter: dismissGuide() : Before attaching the guide view, mForceDismissGuide : false
03-31 10:07:17.432  3424  3590 I ActivityManager: Force stopping com.test.thalitest appid=10011 user=0: pkg removed
03-31 10:07:17.437  3424  3590 I ActivityManager:   Force finishing activity 3 ActivityRecord{10f7b4e3 u0 com.test.thalitest/.MainActivity t42 f}
03-31 10:07:17.437  3424  3582 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3424 uid:1000
03-31 10:07:17.437  3424  3582 D PointerIcon: setMouseCustomIcon IconType is same.101
03-31 10:07:17.437  3424  3582 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3424 uid:1000
03-31 10:07:17.437  3424  3582 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
03-31 10:07:17.437  3424  3590 W ActivityManager: Duplicate finish request for ActivityRecord{10f7b4e3 u0 com.test.thalitest/.MainActivity t42 f}
03-31 10:07:17.477  3424  3590 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-31 10:07:17.477  9056  9056 I art     : Explicit concurrent mark sweep GC freed 2670(151KB) AllocSpace objects, 0(0B) LOS objects, 69% free, 1770KB/5MB, paused 1.351ms total 19.727ms
03-31 10:07:17.482  3920  3920 I art     : Explicit concurrent mark sweep GC freed 1697(88KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 522us total 17.777ms
03-31 10:07:17.487  6557  6557 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(433/onResume)] 
03-31 10:07:17.487  3424  3689 D TaskPersister: removeObsoleteFile: deleting file=42_task.xml
03-31 10:07:17.487  3424  3689 D TaskPersister: removeObsoleteFile: deleting file=42_task_thumbnail.png
03-31 10:07:17.492  3424  3574 D InputDispatcher: Focused application released
03-31 10:07:17.497  6557  6557 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5412/IlIlllIlllllIlIllllI)] Get Postpone Count : 0
03-31 10:07:17.512  4129  4129 I art     : Explicit concurrent mark sweep GC freed 15398(967KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/8MB, paused 782us total 43.651ms
03-31 10:07:17.517  6557  6557 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5134/lIIIIIIIlllllllIIlll)] Get Priority : 0
03-31 10:07:17.522  3424  3630 I InputReader: Reconfiguring input devices.  changes=0x00000010
03-31 10:07:17.522  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.PACKAGE_REMOVED
03-31 10:07:17.532  4351  4768 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
03-31 10:07:17.532  6557  6557 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5434/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
03-31 10:07:17.532  4616  4616 I art     : Explicit concurrent mark sweep GC freed 4707(321KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 8MB/11MB, paused 707us total 94.577ms
03-31 10:07:17.537  6557  6557 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(443/onResume)] Postpone Count : 0
03-31 10:07:17.537  4515  4515 E SamsungIME: mOCRHelper is null
03-31 10:07:17.542 10635 10635 D LWLocationManager: getDeviceLocationId :  id = -100
03-31 10:07:17.542 10635 10635 D LocationWidgetApplication: getLastUiLocationId() : mLastUiLocationId = -100
03-31 10:07:17.547  6557  6557 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5475/llIlIIIIlllIlllllIll)] Download Postpone status : 0
03-31 10:07:17.552  3424  3650 D NtpTrustedTime: currentTimeMillis() cache hit
03-31 10:07:17.552  3424  3650 V NetworkStats: removeUidsLocked() for UIDs [10011]
03-31 10:07:17.552  3424  3650 V NetworkStats: performPollLocked(flags=0x3)
03-31 10:07:17.557  3424  3650 V NetworkStats: performPollLocked() took 7ms
03-31 10:07:17.557  3424  3650 D NtpTrustedTime: currentTimeMillis() cache hit
03-31 10:07:17.562  4029  4029 I art     : Explicit concurrent mark sweep GC freed 16037(920KB) AllocSpace objects, 9(1362KB) LOS objects, 12% free, 56MB/64MB, paused 400us total 86.905ms
03-31 10:07:17.562  3424  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 10:07:17.562  3424  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 10:07:17.562  3424  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 10:07:17.562  3424  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 10:07:17.562  5616  5649 W ResourceType: For resource 0x7f020570, entry index(1392) is beyond type entryCount(787)
03-31 10:07:17.562  5616  5649 W ResourceType: Failure getting entry for 0x7f020570 (t=1 e=1392) (error -75)
03-31 10:07:17.577 12214 12214 E Zygote  : MountEmulatedStorage()
03-31 10:07:17.577 12214 12214 E Zygote  : v2
03-31 10:07:17.577 12214 12214 I libpersona: KNOX_SDCARD checking this for 10063
03-31 10:07:17.577 12214 12214 I libpersona: KNOX_SDCARD not a persona
03-31 10:07:17.582 12214 12214 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
03-31 10:07:17.582  3424  3574 I ActivityManager: Start proc 12214:com.samsung.android.app.vrsetupwizardstub/u0a63 for broadcast-3 com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver
03-31 10:07:17.582 12214 12214 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
03-31 10:07:17.587  6557  6557 I DBG_DM  : [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
03-31 10:07:17.587 12214 12214 E Zygote  : accessInfo : 0
03-31 10:07:17.587 12214 12214 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-31 10:07:17.587  6557  6557 I DBG_DM  : [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(327/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
03-31 10:07:17.597  3997  3997 D RegisteredServicesCache: empty dynamic service
03-31 10:07:17.602  6557  6557 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5134/lIIIIIIIlllllllIIlll)] Get Priority : 0
03-31 10:07:17.617  3997  3997 D RegisteredComponentCache: Collect Tech packages for Knox
03-31 10:07:17.627 12214 12214 D TimaKeyStoreProvider: TimaSignature is unavailable
03-31 10:07:17.632 12214 12214 D ActivityThread: Added TimaKeyStore provider
03-31 10:07:17.632  3424  3837 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
03-31 10:07:17.632  3424  3837 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
03-31 10:07:17.632  3424  3424 I art     : Explicit concurrent mark sweep GC freed 31616(2MB) AllocSpace objects, 35(560KB) LOS objects, 33% free, 30MB/45MB, paused 2.512ms total 156.101ms
03-31 10:07:17.637  3424  3590 I art     : WaitForGcToComplete blocked for 150.210ms for cause Explicit
03-31 10:07:17.637  6557  6557 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5412/IlIlllIlllllIlIllllI)] Get Postpone Count : 0
03-31 10:07:17.642  3424  4419 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{12f373d2 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{255e7ca3 12214:com.samsung.android.app.vrsetupwizardstub/u0a63}
03-31 10:07:17.642  6557  6557 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5054/IIlllIlIIlIllIlllIll)] Get Force status : 0
03-31 10:07:17.647  6557  6557 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5434/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
03-31 10:07:17.647  6557  6557 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(537/llIIIIlllllIIllIIllI)] Check Force Install : false
03-31 10:07:17.647  6557  6557 I DBG_DM  : [llIIlIIlIllIllIlllII(337/IllIlIIIIlIIlIIIllIl)] 
03-31 10:07:17.647  6557  6557 I DBG_DM  : [llIIlIIlIllIllIlllII(343/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
03-31 10:07:17.647  3424  3816 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-31 10:07:17.647  3424  3816 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-31 10:07:17.647  3424  3816 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-31 10:07:17.652  6557  6557 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(425/onPause)] 
03-31 10:07:17.652  2861  2861 I SurfaceFlinger: id=16 createSurf (1440x2560),1 flag=404, YUIInstallC
03-31 10:07:17.657  3424  3837 D MultiWindowConverter: dismissGuide() : Before attaching the guide view, mForceDismissGuide : false
03-31 10:07:17.657  3424  3580 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{e54828f u0 d0 com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}
03-31 10:07:17.657  3424  3837 D InputDispatcher: Focus entered window: 6557
03-31 10:07:17.662  3424  3582 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3424 uid:1000
03-31 10:07:17.662  3424  3582 D PointerIcon: setMouseCustomIcon IconType is same.101
03-31 10:07:17.662  3424  3582 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3424 uid:1000
03-31 10:07:17.662  3424  3582 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
03-31 10:07:17.662  6557  6557 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
03-31 10:07:17.667  6557  9073 D mali_winsys: new_window_surface returns 0x3000,  [1440x2560]-format:1
03-31 10:07:17.667  3424  3451 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
03-31 10:07:17.672  3424  3451 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 11127 uid 10011
03-31 10:07:17.672  3424  4027 D SecContentProvider2: query(), uri = 11 selection = getMyKnoxAdmin
03-31 10:07:17.682  4515  4515 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
03-31 10:07:17.687  3424  3651 D NtpTrustedTime: currentTimeMillis() cache hit
03-31 10:07:17.687  3424  3651 D NtpTrustedTime: currentTimeMillis() cache hit
03-31 10:07:17.702  6557  6557 V ActivityThread: updateVisibility : ActivityRecord{16558a6c token=android.os.BinderProxy@1af6ebf2 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
03-31 10:07:17.702  6557  6557 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1af6ebf2 time:1607202
03-31 10:07:17.707 12214 12214 D VRSetupWizardStub/PackageIntentReceiver: onReceive()
03-31 10:07:17.707 12214 12214 D VRSetupWizardStub/PackageIntentReceiver: Action Package Remove
03-31 10:07:17.707 12214 12214 D VRSetupWizardStub/PackageIntentReceiver: packagename:com.test.thalitest
03-31 10:07:17.707  3424  3837 I ActivityManager: Killing 10010:com.google.android.apps.docs/u0a101 (adj 15): emptyCount ##31
03-31 10:07:17.712  3424  3837 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{12f373d2 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{36bb9767 7140:com.samsung.klmsagent/u0a21}
03-31 10:07:17.717  3424  3582 W ActivityManager: mDVFSHelper.release()
03-31 10:07:17.717  3424  3582 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{26fc9258 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t40} time:1607216
03-31 10:07:17.717  7140  7140 I KLMS-2.5.262: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Mar 31 10:07:17 GMT+02:00 2016
03-31 10:07:17.717  3424  4025 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
03-31 10:07:17.727  7140  7140 I KLMS-2.5.262: : KLMSAbstractReciever(): onReceive().END.
03-31 10:07:17.727  3424  4420 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=14, mSplitNum[1]=26, mSplitNum[2]=38, mBgSplitQueueNum=3 divideNum= 12 r.nextReceiver= 2 receivers.size=50
03-31 10:07:17.727  3424  4420 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
03-31 10:07:17.732  3424  4420 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{12f373d2 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{17d88639 6792:com.samsung.aasaservice/1000}
03-31 10:07:17.737  7140  7140 I KLMS-2.5.262: : KLMSIntentService(): onCreate()
03-31 10:07:17.737  6792  6792 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
03-31 10:07:17.737  3424  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 10:07:17.737  3424  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 10:07:17.737  3424  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 10:07:17.737  7140  7140 I KLMS-2.5.262: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
03-31 10:07:17.737  3424  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 10:07:17.737  6792  6792 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
03-31 10:07:17.737  7140  7140 I KLMS-2.5.262: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
03-31 10:07:17.737  6792  6792 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:334)
03-31 10:07:17.742  6792  6792 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
03-31 10:07:17.742  7140 12232 I KLMS-2.5.262: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.service.KLMSIntentService (has extras) }
03-31 10:07:17.742  7140 12232 D KLMS-2.5.262: : KLMSIntentService(): PACKAGE_REMOVED
03-31 10:07:17.742  7140 12232 I KLMS-2.5.262: : Systemprocess(): listeningToPackageRemoved().START
03-31 10:07:17.742  7140 12232 I KLMS-2.5.262: : Systemprocess(): listeningToPackageRemoved().packageName: com.test.thalitest
03-31 10:07:17.742  7140 12232 I KLMS-2.5.262: : listeningToPackageRemovedforELM().START
03-31 10:07:17.742  7140 12232 I KLMS-2.5.262: : MDMBridge.getInstance()
03-31 10:07:17.742  7140 12232 I KLMS-2.5.262: : MDMBridge.getAllLicenseInfoFromSDK()
03-31 10:07:17.742  6792  6792 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3509)
03-31 10:07:17.742  6792  6792 W System.err: 	at android.app.ActivityThread.access$1900(ActivityThread.java:197)
03-31 10:07:17.742  6792  6792 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1758)
03-31 10:07:17.742  6792  6792 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-31 10:07:17.742  6792  6792 W System.err: 	at android.os.Looper.loop(Looper.java:145)
03-31 10:07:17.742  6792  6792 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6872)
03-31 10:07:17.742  6792  6792 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
03-31 10:07:17.742  6792  6792 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-31 10:07:17.742  6792  6792 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
03-31 10:07:17.742  6792  6792 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
03-31 10:07:17.742  7140 12232 I KLMS-2.5.262: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
03-31 10:07:17.747  7140 12232 I KLMS-2.5.262: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
03-31 10:07:17.747  7140 12232 I KLMS-2.5.262: : MDMBridge.getAllLicenseInfoFromSDK()
03-31 10:07:17.747  7140 12232 E KLMS-2.5.262: : arr si null
03-31 10:07:17.752 12233 12233 E Zygote  : MountEmulatedStorage()
03-31 10:07:17.752 12233 12233 E Zygote  : v2
03-31 10:07:17.752 12233 12233 I libpersona: KNOX_SDCARD checking this for 10042
03-31 10:07:17.752 12233 12233 I libpersona: KNOX_SDCARD not a persona
03-31 10:07:17.752 12233 12233 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
03-31 10:07:17.757  3424  3574 I ActivityManager: Start proc 12233:com.samsung.android.sdk.samsunglink/u0a42 for broadcast-4 com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver
03-31 10:07:17.757  7140 12232 D KLMS-2.5.262: : DataSource(): Fetched Data from data base count : 0
03-31 10:07:17.757 12233 12233 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
03-31 10:07:17.757  3424  3574 V BroadcastQueue: [backgroundsplit_1] Process cur broadcast BroadcastRecord{1fa8b4c9 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{1094d32b 11215:com.samsung.android.sm/1000}
03-31 10:07:17.762  7140 12232 I KLMS-2.5.262: : listeningToPackageRemovedforELM().END
03-31 10:07:17.762  7140 12232 I KLMS-2.5.262: : Systemprocess(): listeningToPackageRemovedforKLM().START
03-31 10:07:17.762  7140 12232 I KLMS-2.5.262: : Systemprocess(): .pkgName: com.test.thalitest
03-31 10:07:17.762 12233 12233 E Zygote  : accessInfo : 0
03-31 10:07:17.762 12233 12233 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
03-31 10:07:17.767  3424  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 10:07:17.767  3424  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 10:07:17.767  3424  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 10:07:17.767  3424  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 10:07:17.787 12244 12244 E Zygote  : MountEmulatedStorage()
03-31 10:07:17.787 12244 12244 I libpersona: KNOX_SDCARD checking this for 1000
03-31 10:07:17.787 12244 12244 E Zygote  : v2
03-31 10:07:17.787 12244 12244 I libpersona: KNOX_SDCARD not a persona
03-31 10:07:17.787 12244 12244 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
03-31 10:07:17.792  3424  3574 I ActivityManager: Start proc 12244:com.sec.android.app.popupuireceiver/1000 for broadcast-4 com.sec.android.app.popupuireceiver/.PopupuiReceiver
03-31 10:07:17.792 12244 12244 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
03-31 10:07:17.792  3424  3590 I art     : Explicit concurrent mark sweep GC freed 9406(816KB) AllocSpace objects, 2(2MB) LOS objects, 33% free, 27MB/41MB, paused 1.795ms total 154.884ms
03-31 10:07:17.792 12244 12244 E Zygote  : accessInfo : 0
03-31 10:07:17.792 12244 12244 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-31 10:07:17.807 12233 12233 D TimaKeyStoreProvider: TimaSignature is unavailable
03-31 10:07:17.812 12233 12233 D ActivityThread: Added TimaKeyStore provider
03-31 10:07:17.812  3424  4420 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{12f373d2 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{1a662e2c 3424:system/1000}
03-31 10:07:17.822 11215 11215 I art     : Explicit concurrent mark sweep GC freed 150(20KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 1735KB/3MB, paused 3.707ms total 40.950ms
03-31 10:07:17.822  3424  3837 V BroadcastQueue: [backgroundsplit_0] Process cur broadcast BroadcastRecord{101a1f71 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{131a0156 12233:com.samsung.android.sdk.samsunglink/u0a42}
03-31 10:07:17.832 12244 12244 D TimaKeyStoreProvider: TimaSignature is unavailable
03-31 10:07:17.832 12244 12244 D ActivityThread: Added TimaKeyStore provider
03-31 10:07:17.832 10635 12221 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
03-31 10:07:17.837  3424  4420 V BroadcastQueue: [backgroundsplit_1] Process cur broadcast BroadcastRecord{1fa8b4c9 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{1094d32b 11215:com.samsung.android.sm/1000}
03-31 10:07:17.842 12233 12233 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-31 10:07:17.842  3424  4035 V BroadcastQueue: [backgroundsplit_2] Process cur broadcast BroadcastRecord{15aac25c u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{3014f965 12244:com.sec.android.app.popupuireceiver/1000}
03-31 10:07:17.842 12233 12233 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
03-31 10:07:17.847  3424  4420 V BroadcastQueue: [backgroundsplit_1] Process cur broadcast BroadcastRecord{1fa8b4c9 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{1094d32b 11215:com.samsung.android.sm/1000}
03-31 10:07:17.852  3424  3590 D PackageManager: delete codoeFile: 
03-31 10:07:17.852  3424  3590 D PackageManager: Resopt: Clean up res: /data/app/com.test.thalitest-1/base.apk
03-31 10:07:17.852  7140 12232 D KLMS-2.5.262: : KLMSUtility(): IsPackageExistInDevice().mAppInfoList: 322
03-31 10:07:17.852  7140 12232 D KLMS-2.5.262: : KLMSSharedPreferences(): deleteNotificationAppList().pkgName: com.test.thalitest
03-31 10:07:17.852  7140 12232 I KLMS-2.5.262: : KLMSSharedPreferences(): getNotificationAppList(): null
03-31 10:07:17.852  7140 12232 I KLMS-2.5.262: : Systemprocess(): Notification App List is Null. Remove Notification.
03-31 10:07:17.857  3424  3590 D AASAuninstall: userId = 0, info.removedAppID = 10011, info.uid = 10011, packageName = com.test.thalitest
03-31 10:07:17.862 11215 12263 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
03-31 10:07:17.862  3424  4420 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 10:07:17.862  3424  4420 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 10:07:17.862  3424  3590 I AASA_removePackage: UID=10011 Target=com.test.thalitest
03-31 10:07:17.862  3424  4420 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 10:07:17.862  3424  4420 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 10:07:17.862  3424  3590 D PackageManager: result of delete: 1{596639796}
03-31 10:07:17.867 12194 12194 I art     : System.exit called, status: 0
03-31 10:07:17.867 12194 12194 I AndroidRuntime: VM exiting with result code 0.
03-31 10:07:17.867  3424  3590 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
03-31 10:07:17.867  3424  3590 D PackageManager: userId{-1}
03-31 10:07:17.867  3424  3590 D PackageManager: andCode{true}
03-31 10:07:17.872  7140 12232 D KLMS-2.5.262: : DataSource(): Fetched Data from data base count : 0
03-31 10:07:17.872  7140 12232 I KLMS-2.5.262: : Systemprocess(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
03-31 10:07:17.872  7140 12232 I KLMS-2.5.262: : Systemprocess(): listeningToPackageRemovedforKLM().END
03-31 10:07:17.872  7140 12232 I KLMS-2.5.262: : Systemprocess(): listeningToPackageRemoved().END
03-31 10:07:17.877 12267 12267 E Zygote  : MountEmulatedStorage()
03-31 10:07:17.877 12267 12267 E Zygote  : v2
03-31 10:07:17.877 12267 12267 I libpersona: KNOX_SDCARD checking this for 1000
03-31 10:07:17.877 12267 12267 I libpersona: KNOX_SDCARD not a persona
03-31 10:07:17.882 12267 12267 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
03-31 10:07:17.882  3424  4420 I ActivityManager: Start proc 12267:com.samsung.android.app.assistantmenu/1000 for broadcast-4 com.samsung.android.app.assistantmenu/.AssistantMenuReceiver
03-31 10:07:17.887 12267 12267 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
03-31 10:07:17.887 12267 12267 E Zygote  : accessInfo : 0
03-31 10:07:17.887  3424  3424 D RCPManagerService: PackageReceiver onReceive()
03-31 10:07:17.887  3424  3424 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
03-31 10:07:17.887 12267 12267 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-31 10:07:17.887  3424  3424 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
03-31 10:07:17.887  3424  3424 I OTPFW   : PackageRemovalReceiver::onReceive Enter
03-31 10:07:17.887  3424  3424 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10011 container id = 0
03-31 10:07:17.887 12244 12244 D PopupuiReceiver: onReceive() getAction : android.intent.action.PACKAGE_REMOVED
03-31 10:07:17.892  3424  3424 I OTPFW   : ProvisionData::getAllEntries Enter
03-31 10:07:17.892  3424  3424 E OTPFW   : ProvisionData::getAllEntries Table is empty
03-31 10:07:17.892  7140  7140 I KLMS-2.5.262: : KLMSIntentService(): onDestroy()
03-31 10:07:17.892  3424  3424 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
03-31 10:07:17.897  3424  4045 D SecContentProvider2: query(), uri = -1 selection = getSealedState
03-31 10:07:17.892  3424  3424 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
03-31 10:07:17.897  3424  3965 D SecContentProvider2: query(), uri = 15 selection = getSealedHideNotificationMessages
03-31 10:07:17.897  9635 12276 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.test.thalitest
03-31 10:07:17.897  3424  3424 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
03-31 10:07:17.897  3424  3424 V EnterpriseBillingPolicy: uID is 10011
03-31 10:07:17.897  3424  3424 V EnterpriseBillingPolicy: Removed Packageuid is0
03-31 10:07:17.897  3424  3424 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
03-31 10:07:17.897  9635 12276 W System.err: remove failed: EACCES (Permission denied) : /storage/extSdCard/Android/data/com.test.thalitest
03-31 10:07:17.897 12244 12244 I PopupuiReceiver_KNOX: getSealedHideNotificationMessages : 0
03-31 10:07:17.897  3424  3424 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
03-31 10:07:17.897  3424  3424 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
03-31 10:07:17.897  3424  3424 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
03-31 10:07:17.897  3424  3424 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
03-31 10:07:17.897  3424  3424 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
03-31 10:07:17.897  3424  3451 D SecContentProvider2: query(), uri = 15 selection = getCheckCoverPopupState
03-31 10:07:17.897  3424  3424 D SdpManagerService:  ActionReceiver::onReceive() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
03-31 10:07:17.897  3424  3424 D SdpManagerService: ACTION_PACKAGE_REMOVED Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) } DATA= package:com.test.thalitest UID 1000 userId 0
03-31 10:07:17.897  3424  3424 D SdpManagerService: ACTION_PACKAGE_REMOVED packageName:: com.test.thalitest
03-31 10:07:17.902 12244 12244 I PopupuiReceiver_KNOX: getCheckCoverPopupState : false
03-31 10:07:17.902 12244 12244 D PopupuiReceiver: Action package removed
03-31 10:07:17.902  3424  3424 D EnterprisePartitionManager: SND -> {secure_fs remove_enc_dir}
03-31 10:07:17.902  3424  3592 D EnterprisePartitionManager: RCV <-
03-31 10:07:17.902  3424  3424 D EnterprisePartitionManager: RMV <-
03-31 10:07:17.907  9635 12276 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.test.thalitest
03-31 10:07:17.907  9635 12276 W System.err: remove failed: EACCES (Permission denied) : /storage/extSdCard/Android/media/com.test.thalitest
03-31 10:07:17.912  3424  3424 E EnterprisePartitionManager: Failed to send commandcom.sec.knox.container.util.DaemonConnector$DaemonArgumentException: command 'secure_fs' failed with '500 3 Command not recognized'
03-31 10:07:17.912  3424  3424 W System.err: java.io.FileNotFoundException: /data/system/users/sdp_engine_list.xml: open failed: ENOENT (No such file or directory)
03-31 10:07:17.912  3424  3424 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-31 10:07:17.912  3424  3424 W System.err: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
03-31 10:07:17.912  3424  3424 W System.err: 	at com.android.server.SdpManagerService$SdpEngineDatabase$EngineListHandler.getEngineListLocked(SdpManagerService.java:1514)
03-31 10:07:17.912  3424  3424 W System.err: 	at com.android.server.SdpManagerService$SdpEngineDatabase$EngineListHandler.access$1100(SdpManagerService.java:1434)
03-31 10:07:17.912  3424  3424 W System.err: 	at com.android.server.SdpManagerService$SdpEngineDatabase.getEngineListLocked(SdpManagerService.java:1418)
03-31 10:07:17.912  3424  3424 W System.err: 	at com.android.server.SdpManagerService$SdpEngineDatabase.access$2200(SdpManagerService.java:1393)
03-31 10:07:17.912  3424  3424 W System.err: 	at com.android.server.SdpManagerService.handlePkgRemoved(SdpManagerService.java:2647)
03-31 10:07:17.912  3424  3424 W System.err: 	at com.android.server.SdpManagerService.access$2500(SdpManagerService.java:137)
03-31 10:07:17.912  3424  3424 W System.err: 	at com.android.server.SdpManagerService$ActionReceiver.onReceive(SdpManagerService.java:2719)
03-31 10:07:17.912  3424  3424 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:972)
03-31 10:07:17.912  3424  3424 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
03-31 10:07:17.912  3424  3424 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-31 10:07:17.912  3424  3424 W System.err: 	at android.os.Looper.loop(Looper.java:145)
03-31 10:07:17.912  3424  3424 W System.err: 	at com.android.server.SystemServer.run(SystemServer.java:469)
03-31 10:07:17.912  3424  3424 W System.err: 	at com.android.server.SystemServer.main(SystemServer.java:353)
03-31 10:07:17.912  3424  3424 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
03-31 10:07:17.912  3424  3424 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-31 10:07:17.912  3424  3424 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
03-31 10:07:17.912  3424  3424 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
03-31 10:07:17.912  3424  3424 W System.err: Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
03-31 10:07:17.912  3424  3424 W System.err: 	at libcore.io.Posix.open(Native Method)
03-31 10:07:17.912  3424  3424 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-31 10:07:17.912  3424  3424 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-31 10:07:17.912  3424  3424 W System.err: 	... 18 more
03-31 10:07:17.912  3424  3424 E SdpManagerService: failed to get engine list
03-31 10:07:17.912  9635 12276 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/obb/com.test.thalitest
03-31 10:07:17.912  9635 12276 W System.err: remove failed: EACCES (Permission denied) : /storage/extSdCard/Android/obb/com.test.thalitest
03-31 10:07:17.912 12267 12267 D TimaKeyStoreProvider: TimaSignature is unavailable
03-31 10:07:17.917  3424  6055 D SSRM:bd : MSG_TYPE_APP_REMOVED::
03-31 10:07:17.912  3424  3424 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
03-31 10:07:17.912 12267 12267 D ActivityThread: Added TimaKeyStore provider
03-31 10:07:17.912  3424  3424 V EnterpriseBillingPolicy: uID is 10011
03-31 10:07:17.912  3424  3424 V EnterpriseBillingPolicy: Removed Packageuid is0
03-31 10:07:17.912  3424  3424 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
03-31 10:07:17.917  3424  3424 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
03-31 10:07:17.917  3424  3424 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
03-31 10:07:17.917  3424  3424 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
03-31 10:07:17.917  3424  3424 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
03-31 10:07:17.917  3424  3424 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
03-31 10:07:17.922  3424  4419 V BroadcastQueue: [backgroundsplit_2] Process cur broadcast BroadcastRecord{15aac25c u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{28a4bd 10552:com.samsung.android.snote/u0a160}
03-31 10:07:17.927 10635 12221 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-31 10:07:17.927 10635 12221 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-31 10:07:17.927 10635 12221 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-31 10:07:17.927 10635 12221 W ResourcesManager: Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
03-31 10:07:17.932  4029  4029 D Launcher.Model: reloadBadges entered.
03-31 10:07:17.932 10737 10754 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
03-31 10:07:17.932 10737 10754 D BadgeProvider: sendNotify, [notify] : null
03-31 10:07:17.932 10737 10754 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
03-31 10:07:17.932 10737 10754 D BadgeProvider: update, [uri.query] : null
03-31 10:07:17.932 10737 10754 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-31 10:07:17.932 10737 10754 D BadgeProvider: update, [UpdateCount] : 1
03-31 10:07:17.932  3424  3816 V BroadcastQueue: [backgroundsplit_1] Process cur broadcast BroadcastRecord{1fa8b4c9 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{156671f2 12267:com.samsung.android.app.assistantmenu/1000}
03-31 10:07:17.932  3424  3424 D KnoxTimeoutHandler: handleActiveUserChange for user 0
03-31 10:07:17.937  3424  3424 E EnterpriseSharedDevicePolicy: isSharedDeviceEnabled
03-31 10:07:17.937  3424  3424 I EnterpriseSharedDevicePolicy: isSharedDeviceEnabled in Service
03-31 10:07:17.937  3424  3424 I EnterpriseSharedDevicePolicy: Get Result: -1
03-31 10:07:17.937  3424  3424 I EnterpriseSharedDevicePolicy: status: false
03-31 10:07:17.937  3424  3424 D PersonaManagerService: getPersonasForUser(): returning null!
03-31 10:07:17.937  3424  3424 I KnoxTimeoutHandler: Shared devices show user statefalse
03-31 10:07:17.937  3424  3424 V AlarmManagerEXT: com.test.thalitest(10011) is removed.
03-31 10:07:17.937  3723  3723 D PanelView: There is/are notification(s) 
03-31 10:07:17.937  3424  4027 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 10:07:17.937  3424  4027 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 10:07:17.937  3424  4027 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 10:07:17.937  3424  4027 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 10:07:17.942 12233 12233 I SL_DEBUG: isLoggable:: isProductShip = 1
03-31 10:07:17.942 12233 12233 I SL_DEBUG: isLoggable:: SL_DEBUG_EXIST = false
03-31 10:07:17.952 10737 10747 D BadgeProvider: query, [selection] : null
03-31 10:07:17.952 12288 12288 I libpersona: KNOX_SDCARD checking this for 10183
03-31 10:07:17.952 12288 12288 E Zygote  : MountEmulatedStorage()
03-31 10:07:17.952 12288 12288 I libpersona: KNOX_SDCARD not a persona
03-31 10:07:17.952 12288 12288 E Zygote  : v2
03-31 10:07:17.957 12288 12288 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
03-31 10:07:17.957  3424  4027 I ActivityManager: Start proc 12288:com.samsung.android.provider.shootingmodeprovider/u0a183 for broadcast-4 com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver
03-31 10:07:17.962 12288 12288 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
03-31 10:07:17.962 12288 12288 E Zygote  : accessInfo : 0
03-31 10:07:17.962 12288 12288 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-31 10:07:17.967  6120  6120 D com.sec.android.service.health.upgrade.UninstallReceiver: onReceive()
03-31 10:07:17.967  3424  3424 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{12f373d2 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{a135086 6120:com.sec.android.service.health/u0a19}
03-31 10:07:17.967  6120  6120 I com.sec.android.service.health.upgrade.UninstallReceiver: onReceive called  PACKAGE_REMOVED package:com.test.thalitest
03-31 10:07:17.967  6120  6120 D com.sec.android.service.health.upgrade.UninstallReceiver: onReceive() : package name is not s health. Return !!!
03-31 10:07:17.982  3424  4025 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{12f373d2 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{248e5e5b 10635:com.sec.android.widgetapp.locationwidget/u0a22}
03-31 10:07:17.982 10635 10635 D LocationWidgetApplication: getLastUiLocationId() : mLastUiLocationId = -100
03-31 10:07:17.997 12288 12288 D TimaKeyStoreProvider: TimaSignature is unavailable
03-31 10:07:17.997 12288 12288 D ActivityThread: Added TimaKeyStore provider
03-31 10:07:18.007  3424  4025 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 10:07:18.007  3424  4025 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 10:07:18.007  3424  4025 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 10:07:18.007  3424  4025 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 10:07:18.017  3723  3723 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
03-31 10:07:18.022  3723  3723 D PanelView: There is/are notification(s) 
03-31 10:07:18.022  3723  3723 D PanelView: kidsfalse mQsExpansionEnabled:true
03-31 10:07:18.022 12267 12267 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2129 android.content.ContextWrapper.startService:534 android.content.ContextWrapper.startService:534 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3509 
03-31 10:07:18.022  3723  3723 D PanelView: There is/are notification(s) 
03-31 10:07:18.022  3723  3723 D PanelView: kidsfalse mQsExpansionEnabled:true
03-31 10:07:18.027 12305 12305 E Zygote  : MountEmulatedStorage()
03-31 10:07:18.027 12305 12305 E Zygote  : v2
03-31 10:07:18.027 12305 12305 I libpersona: KNOX_SDCARD checking this for 1000
03-31 10:07:18.027 12305 12305 I libpersona: KNOX_SDCARD not a persona
03-31 10:07:18.027 12305 12305 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
03-31 10:07:18.032  3424  4025 I ActivityManager: Start proc 12305:com.sec.pcw.device/1000 for broadcast-3 com.sec.pcw.device/.receiver.SYSTEMReceiver
03-31 10:07:18.032 12305 12305 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
03-31 10:07:18.032  3424  4025 I ActivityManager: Killing 10296:com.facebook.system/u0a10 (adj 15): emptyCount ##31
03-31 10:07:18.037 12305 12305 E Zygote  : accessInfo : 0
03-31 10:07:18.037  3424  3732 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
03-31 10:07:18.042 12305 12305 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-31 10:07:18.047  3424  4419 V BroadcastQueue: [backgroundsplit_2] Process cur broadcast BroadcastRecord{15aac25c u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{36352531 12288:com.samsung.android.provider.shootingmodeprovider/u0a183}
03-31 10:07:18.052  3424  3451 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 10:07:18.052  3424  3451 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 10:07:18.052 11215 12264 E SQLiteLog: (10) unixWrite() File Descriptor : 35 gets errno : 30
03-31 10:07:18.052  3424  3451 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 10:07:18.052  3424  3451 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 10:07:18.062 12305 12305 D TimaKeyStoreProvider: TimaSignature is unavailable
03-31 10:07:18.062 12305 12305 D ActivityThread: Added TimaKeyStore provider
03-31 10:07:18.072 11215 12264 E SQLiteDatabase: Error inserting name=isDevelopVersion value=false
03-31 10:07:18.072 11215 12264 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
03-31 10:07:18.072 11215 12264 E SQLiteDatabase: #################################################################
03-31 10:07:18.072 11215 12264 E SQLiteDatabase: Error Code : 778 (SQLITE_IOERR_WRITE)
03-31 10:07:18.072 11215 12264 E SQLiteDatabase: Caused By : Disk I/O error occurred during 'write' operation.
03-31 10:07:18.072 11215 12264 E SQLiteDatabase: 	(disk I/O error (code 778))
03-31 10:07:18.072 11215 12264 E SQLiteDatabase: #################################################################
03-31 10:07:18.072 11215 12264 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
03-31 10:07:18.072 11215 12264 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
03-31 10:07:18.072 11215 12264 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
03-31 10:07:18.072 11215 12264 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
03-31 10:07:18.072 11215 12264 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
03-31 10:07:18.072 11215 12264 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
03-31 10:07:18.072 11215 12264 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
03-31 10:07:18.072 11215 12264 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
03-31 10:07:18.072 11215 12264 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:186)
03-31 10:07:18.072 11215 12264 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
03-31 10:07:18.072 11215 12264 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
03-31 10:07:18.072 11215 12264 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
03-31 10:07:18.072 11215 12264 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
03-31 10:07:18.072 11215 12264 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
03-31 10:07:18.072 11215 12264 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
03-31 10:07:18.072 11215 12264 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-31 10:07:18.072 11215 12264 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-31 10:07:18.072 11215 12264 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-31 10:07:18.072 11215 12264 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-31 10:07:18.077 12321 12321 E Zygote  : MountEmulatedStorage()
03-31 10:07:18.077 12321 12321 E Zygote  : v2
03-31 10:07:18.077 12321 12321 I libpersona: KNOX_SDCARD checking this for 1000
03-31 10:07:18.077 12321 12321 I libpersona: KNOX_SDCARD not a persona
03-31 10:07:18.077 11215 12264 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-31 10:07:18.077 11215 12264 E SQLiteLog: (6922) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
03-31 10:07:18.077 11215 12264 E SQLiteDatabase: Error inserting name=DBVersion value=2003
03-31 10:07:18.077 11215 12264 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 6922)
03-31 10:07:18.077 11215 12264 E SQLiteDatabase: #################################################################
03-31 10:07:18.077 11215 12264 E SQLiteDatabase: Error Code : 6922 (SQLITE_IOERR_LOCK_EBADF)
03-31 10:07:18.077 11215 12264 E SQLiteDatabase: Caused By : I/O error happened due to bad file descriptor. There is possibility the partition changed to read-only.
03-31 10:07:18.077 11215 12264 E SQLiteDatabase: 	(disk I/O error (code 6922))
03-31 10:07:18.077 11215 12264 E SQLiteDatabase: #################################################################
03-31 10:07:18.077 11215 12264 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
03-31 10:07:18.077 11215 12264 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
03-31 10:07:18.077 11215 12264 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
03-31 10:07:18.077 11215 12264 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
03-31 10:07:18.077 11215 12264 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
03-31 10:07:18.077 11215 12264 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
03-31 10:07:18.077 11215 12264 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
03-31 10:07:18.077 11215 12264 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
03-31 10:07:18.077 11215 12264 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:187)
03-31 10:07:18.077 11215 12264 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
03-31 10:07:18.077 11215 12264 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
03-31 10:07:18.077 11215 12264 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
03-31 10:07:18.077 11215 12264 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
03-31 10:07:18.077 11215 12264 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
03-31 10:07:18.077 11215 12264 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
03-31 10:07:18.077 11215 12264 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-31 10:07:18.077 11215 12264 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-31 10:07:18.077 11215 12264 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-31 10:07:18.077 11215 12264 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-31 10:07:18.077 12321 12321 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
03-31 10:07:18.082 11215 12264 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-31 10:07:18.082  3424  3451 I ActivityManager: Start proc 12321:com.sec.knox.bridge/1000 for broadcast-4 com.sec.knox.bridge/.PersonaShortcutReceiver
03-31 10:07:18.082 11215 12264 E SQLiteLog: (6922) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
03-31 10:07:18.082 11215 12264 E SQLiteDatabase: Error inserting name=LPCSystemVersion value=1.0.0
03-31 10:07:18.082 11215 12264 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 6922)
03-31 10:07:18.082 11215 12264 E SQLiteDatabase: #################################################################
03-31 10:07:18.082 11215 12264 E SQLiteDatabase: Error Code : 6922 (SQLITE_IOERR_LOCK_EBADF)
03-31 10:07:18.082 11215 12264 E SQLiteDatabase: Caused By : I/O error happened due to bad file descriptor. There is possibility the partition changed to read-only.
03-31 10:07:18.082 11215 12264 E SQLiteDatabase: 	(disk I/O error (code 6922))
03-31 10:07:18.082 11215 12264 E SQLiteDatabase: #################################################################
03-31 10:07:18.082 11215 12264 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
03-31 10:07:18.082 11215 12264 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
03-31 10:07:18.082 11215 12264 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
03-31 10:07:18.082 11215 12264 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
03-31 10:07:18.082 11215 12264 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
03-31 10:07:18.082 11215 12264 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
03-31 10:07:18.082 11215 12264 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
03-31 10:07:18.082 11215 12264 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
03-31 10:07:18.082 11215 12264 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:188)
03-31 10:07:18.082 11215 12264 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
03-31 10:07:18.082 11215 12264 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
03-31 10:07:18.082 11215 12264 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
03-31 10:07:18.082 11215 12264 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
03-31 10:07:18.082 11215 12264 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
03-31 10:07:18.082 11215 12264 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
03-31 10:07:18.082 11215 12264 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-31 10:07:18.082 11215 12264 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-31 10:07:18.082 11215 12264 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-31 10:07:18.082 11215 12264 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-31 10:07:18.082 12267 12320 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu" with flag (131138) and mode_t (0) due to error (30)
03-31 10:07:18.087 12321 12321 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
03-31 10:07:18.087 12321 12321 E Zygote  : accessInfo : 0
03-31 10:07:18.087 12321 12321 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-31 10:07:18.092 12267 12320 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu'.
03-31 10:07:18.092 12267 12320 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (co
```
