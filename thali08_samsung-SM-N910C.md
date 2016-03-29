#### Test 63998117de3e24f_thali08_samsung-SM-N910C Logs


```
--------- beginning of system
03-29 16:22:29.199  3452  3491 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-29 16:22:29.199  3452  3491 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-29 16:22:29.199  3452  3491 D BatteryService: online:4, current avg:45, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:33
,03-29 16:22:29.204  3452  3452 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-29 16:22:29.214  3452  3452 I MotionRecognitionService: Plugged
03-29 16:22:29.214  3452  3452 D MotionRecognitionService:   cableConnection= 1
03-29 16:22:29.214  3452  3452 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-29 16:22:29.214  3452  3452 D MotionRecognitionService: skip setTransmitPower. 
--------- beginning of main
03-29 16:22:29.224  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-29 16:22:29.214  3452  3491 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 14ms
03-29 16:22:29.224  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-29 16:22:29.214  3452  3491 D BatteryService: stay LED for fully charged
03-29 16:22:29.224  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
03-29 16:22:29.249  5848  5848 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-29 16:22:29.249  5848  5945 D HeadsetStateMachine: Disconnected process message: 10
03-29 16:22:29.259  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-29 16:22:29.259  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-29 16:22:29.259  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-29 16:22:29.259  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-29 16:22:29.594 11165 11165 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
03-29 16:22:29.599 11165 11165 D AndroidRuntime: CheckJNI is OFF
03-29 16:22:29.599 11165 11165 D AndroidRuntime: readGMSProperty: start
03-29 16:22:29.599 11165 11165 D AndroidRuntime: readGMSProperty: already setted!!
03-29 16:22:29.599 11165 11165 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-29 16:22:29.599 11165 11165 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-29 16:22:29.599 11165 11165 D AndroidRuntime: readGMSProperty: end
03-29 16:22:29.599 11165 11165 D AndroidRuntime: addProductProperty: start
03-29 16:22:29.774 11165 11165 E AffinityControl: AffinityControl: registerfunction enter
03-29 16:22:29.804 11165 11165 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-29 16:22:29.819  3452  4010 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
03-29 16:22:29.824  3452  4010 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-29 16:22:29.849  3452  4010 W ActivityManager: mDVFSHelper.acquire()
03-29 16:22:29.854  3452  4010 V WindowManager: addAppToken: AppWindowToken{1f3cc731 token=Token{1ab537d8 ActivityRecord{b51f6bb u0 com.test.thalitest/.MainActivity t42}}} to stack=1 task=42 at 0
03-29 16:22:29.859  3452  4010 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-29 16:22:29.859  3452  4010 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-29 16:22:29.859  3452  4010 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-29 16:22:29.859  3452  4010 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-29 16:22:29.869  3452  3583 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-29 16:22:29.869  3452  3583 D PhoneWindow: *FMB* installDecor flags : -2122120936
03-29 16:22:29.869  3452  3583 D SecWifiDisplayUtil: Metadata value : none
03-29 16:22:29.869  3452  3583 V WindowManager: Adding window Window{379729f0 u0 d0 Starting com.test.thalitest} at 3 of 7 (after Window{bab2242 u0 d0 com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity})
03-29 16:22:29.874 11183 11183 E Zygote  : MountEmulatedStorage()
03-29 16:22:29.874 11183 11183 E Zygote  : v2
03-29 16:22:29.874 11183 11183 I libpersona: KNOX_SDCARD checking this for 10011
03-29 16:22:29.874 11183 11183 I libpersona: KNOX_SDCARD not a persona
03-29 16:22:29.879 11183 11183 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
03-29 16:22:29.879  3452  4010 I ActivityManager: Start proc 11183:com.test.thalitest/u0a11 for activity com.test.thalitest/.MainActivity
03-29 16:22:29.879  3452  4010 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
03-29 16:22:29.879  3452  4010 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-29 16:22:29.879  3452  4010 D InputDispatcher: Focused application set to: xxxx
03-29 16:22:29.879  3452  4010 D MultiWindowConverter: dismissGuide() : Before attaching the guide view, mForceDismissGuide : false
03-29 16:22:29.879  3452  4010 D InputDispatcher: Focus left window: 6467
03-29 16:22:29.879 11165 11165 D AndroidRuntime: Shutting down VM
03-29 16:22:29.884 11183 11183 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
03-29 16:22:29.884 11183 11183 E Zygote  : accessInfo : 0
03-29 16:22:29.884 11183 11183 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-29 16:22:29.884  3452  3583 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-29 16:22:29.884  3452  3583 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
03-29 16:22:29.889  2859  2859 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=404, uhalitest
03-29 16:22:29.904  3452  3583 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3452 uid:1000
03-29 16:22:29.904  3452  3583 D PointerIcon: setMouseCustomIcon IconType is same.101
03-29 16:22:29.904  3452  3583 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3452 uid:1000
03-29 16:22:29.904  3452  3583 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
03-29 16:22:29.904 11183 11183 D TimaKeyStoreProvider: TimaSignature is unavailable
03-29 16:22:29.904 11183 11183 D ActivityThread: Added TimaKeyStore provider
03-29 16:22:29.909  3452  3836 D PowerManagerService: setKeyboardVisibility: false
03-29 16:22:29.909  3452  3581 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{379729f0 u0 d0 Starting com.test.thalitest}
03-29 16:22:29.914  3452  3836 D ActivityManager:  Launching com.test.thalitest, updated priority
03-29 16:22:29.924  3452  3836 I ActivityManager: Skip updateThumbnail for r=ActivityRecord{b51f6bb u0 com.test.thalitest/.MainActivity t42}
03-29 16:22:29.939  2859  3009 I SurfaceFlinger: id=12 Removed YUIInstallC (5/9)
03-29 16:22:29.939  2859  4021 I SurfaceFlinger: id=12 Removed YUIInstallC (-2/9)
03-29 16:22:29.949  6467  6467 V ActivityThread: updateVisibility : ActivityRecord{fb44e6d token=android.os.BinderProxy@1558a83b {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
,03-29 16:22:30.094  3452  6034 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,03-29 16:22:30.134 11183 11183 D SecWifiDisplayUtil: Metadata value : none
,03-29 16:22:30.179 11183 11183 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,03-29 16:22:30.189 11183 11183 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 5864-5865)
03-29 16:22:30.189 11183 11183 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-29 16:22:30.204 11183 11199 W System.err: remove failed: ENOENT (No such file or directory) : /data/data/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
,03-29 16:22:30.204 11183 11183 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3c37c702}
,03-29 16:22:30.204 11183 11183 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-29 16:22:30.204 11183 11183 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,03-29 16:22:30.224 11183 11183 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-29 16:22:30.224 11183 11183 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-29 16:22:30.224 11183 11183 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-29 16:22:30.244 11183 11183 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,03-29 16:22:30.244 11183 11183 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=37 off=50556 len=3379
03-29 16:22:30.244 11183 11183 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:38 off:7638088 len:1165478
,03-29 16:22:30.309 11183 11222 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,03-29 16:22:30.334 11183 11183 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-29 16:22:30.349 11183 11183 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-29 16:22:30.359 11183 11183 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-29 16:22:30.359 11183 11183 D PhoneWindow: *FMB* installDecor flags : -2139027200
,03-29 16:22:30.364 11183 11183 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,03-29 16:22:30.369 11183 11183 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-29 16:22:30.369 11183 11183 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-29 16:22:30.434 11183 11235 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,03-29 16:22:30.439  3452  4020 V WindowManager: Adding window Window{729b211 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity} at 3 of 8 (before Window{379729f0 u0 d0 Starting com.test.thalitest})
,03-29 16:22:30.444  3452  3491 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-29 16:22:30.444  3452  3491 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-29 16:22:30.444  3452  3491 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-29 16:22:30.444  3452  3452 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,03-29 16:22:30.444  3452  3452 E EnterpriseSharedDevicePolicy: isSharedDeviceEnabled
,03-29 16:22:30.444  3452  3452 I EnterpriseSharedDevicePolicy: isSharedDeviceEnabled in Service
03-29 16:22:30.444  3452  3452 I EnterpriseSharedDevicePolicy: Get Result: -1
03-29 16:22:30.444  3452  3452 I EnterpriseSharedDevicePolicy: status: false
03-29 16:22:30.444  3452  3452 I KnoxTimeoutHandler: Shared devices show user statefalse
,03-29 16:22:30.449  3452  3452 D PersonaManagerService: getPersonasForUser(): returning null!
,03-29 16:22:30.459 11183 11183 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-29 16:22:30.459 11183 11183 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,03-29 16:22:30.459 11183 11183 D SecWifiDisplayUtil: Metadata value : none
,03-29 16:22:30.469  2859  2859 I SurfaceFlinger: id=15 createSurf (1x1),1 flag=404, NainActivit
,03-29 16:22:30.469  3452  4010 D MultiWindowConverter: dismissGuide() : Before attaching the guide view, mForceDismissGuide : false
,03-29 16:22:30.479  3452  4010 D InputDispatcher: Focus entered window: 11183
,03-29 16:22:30.484  3452  3583 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3452 uid:1000
03-29 16:22:30.484  3452  3583 D PointerIcon: setMouseCustomIcon IconType is same.101
03-29 16:22:30.484  3452  3583 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3452 uid:1000
03-29 16:22:30.484  3452  3583 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
03-29 16:22:30.484 11183 11183 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
03-29 16:22:30.484 11183 11235 I OpenGLRenderer: Initialized EGL, version 1.4
,03-29 16:22:30.489 11183 11235 I OpenGLRenderer: HWUI protection enabled for context ,  &this =0xae4e1e80 ,&mEglDisplay = 1 , &mEglConfig = -1267396336 
,03-29 16:22:30.489 11183 11235 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
03-29 16:22:30.489 11183 11235 D OpenGLRenderer: Enabling debug mode 0
,03-29 16:22:30.489 11183 11235 D mali_winsys: new_window_surface returns 0x3000,  [1440x2560]-format:1
,03-29 16:22:30.494 11183 11183 V ActivityThread: updateVisibility : ActivityRecord{ea1680a token=android.os.BinderProxy@20c89bac {com.test.thalitest/com.test.thalitest.MainActivity}} show : true,
,03-29 16:22:30.574  3452  3836 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-29 16:22:30.579  3726  3726 D PanelView: There is/are notification(s) 
,03-29 16:22:30.579  3452  3583 I ActivityManager: Displayed Component not be shown by security: +518ms (total +1m17s748ms)
,03-29 16:22:30.579  3452  3583 W ActivityManager: mDVFSHelper.release()
03-29 16:22:30.579  3452  3583 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{b51f6bb u0 com.test.thalitest/.MainActivity t42} time:176259
,03-29 16:22:30.584  2859  3006 I SurfaceFlinger: id=14 Removed uhalitest (7/9)
03-29 16:22:30.584  2859  4021 I SurfaceFlinger: id=14 Removed uhalitest (-2/9)
,03-29 16:22:30.609 11183 11183 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,03-29 16:22:30.609 11183 11183 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@20c89bac time:176289
,03-29 16:22:30.639 11183 11183 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 11183
,03-29 16:22:30.684  3452  6034 D SSRM:n  : SIOP:: AP = 280, PST = 290 (W:14), CUR = 45, LCD = 0
,03-29 16:22:30.754 11183 11183 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-29 16:22:30.824 11183 11239 D jxcore_app_log: JniHelper::setJavaVM(0xb449d200), pthread_self() = -1626760192
,03-29 16:22:30.829 11183 11239 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-29 16:22:30.829 11183 11239 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-29 16:22:30.829 11183 11239 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-29 16:22:30.829 11183 11239 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-29 16:22:30.829 11183 11239 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-29 16:22:30.834 11183 11239 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b68866b added. We now have 1 listener(s)
,03-29 16:22:30.834 11183 11239 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: E0:DB:10:14:E2:C0
,03-29 16:22:30.839 11183 11239 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
,03-29 16:22:30.839 11183 11239 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
03-29 16:22:30.839 11183 11239 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
03-29 16:22:30.839 11183 11199 W System.err: remove failed: ENOENT (No such file or directory) : /data/data/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,03-29 16:22:30.844 11183 11239 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-29 16:22:30.844 11183 11239 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-29 16:22:30.844 11183 11239 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-29 16:22:30.844 11183 11239 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: E0:DB:10:14:E2:C0
03-29 16:22:30.844 11183 11239 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-29 16:22:30.844 11183 11239 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-29 16:22:30.844 11183 11239 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
03-29 16:22:30.844 11183 11239 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-29 16:22:30.844 11183 11239 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-29 16:22:30.844 11183 11239 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-29 16:22:30.844 11183 11239 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-29 16:22:30.844 11183 11239 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ce0c586 added. We now have 1 listener(s)
03-29 16:22:30.844 11183 11239 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-29 16:22:30.849 11183 11239 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,03-29 16:22:30.849 11183 11239 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
03-29 16:22:30.849 11183 11239 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
03-29 16:22:30.849 11183 11239 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-29 16:22:30.849 11183 11239 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,03-29 16:22:30.854 11183 11239 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-29 16:22:30.854 11183 11239 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is E0:DB:10:14:E2:C0
,03-29 16:22:30.859 11183 11239 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-29 16:22:30.859 11183 11239 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-29 16:22:30.859 11183 11239 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-29 16:22:30.859 11183 11239 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-29 16:22:30.859 11183 11239 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-29 16:22:30.859 11183 11239 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-29 16:22:30.859 11183 11239 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-29 16:22:30.859 11183 11239 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-29 16:22:30.859 11183 11239 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-29 16:22:30.859 11183 11239 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-29 16:22:30.859 11183 11239 I io.jxcore.node.LifeCycleMonitor: start: OK
,03-29 16:22:30.859 11183 11183 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-29 16:22:30.864 11183 11183 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-29 16:22:30.914 11183 11183 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-29 16:22:31.274 11183 11246 W jxcore-log: Initializing JXcore engine
03-29 16:22:31.274 11183 11246 W jxcore-log: JXcore engine is ready
,03-29 16:22:31.299  4766  4766 E auditd  : In denial and Property audit_ondenial is set to 1 
,03-29 16:22:31.299  4766  4766 E audit   : type=1400 msg=audit(1459261351.299:196): avc:  denied  { ioctl } for  pid=11246 comm="Thread-1539" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3090 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
03-29 16:22:31.299  3452  3579 D SecurityLogAgent:SEDenialService: Got Modify Event and sending Denial Intent foraudit.log
03-29 16:22:31.299  4766  4766 E audit   :  SEPF_SM-N910C_5.1.1_0038
03-29 16:22:31.304  4766  4766 E audit   : type=1300 msg=audit(1459261351.299:196): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=2 a3=974008d8 items=0 ppid=2900 ppcomm=main pid=11246 auid=4294967295 uid=10011 gid=10011 euid=10011 suid=10011 fsuid=10011 egid=10011 sgid=10011 fsgid=10011 ses=4294967295 tty=(none) comm="Thread-1539" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
03-29 16:22:31.304  3452  3579 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.android.server.SEDenialService$AuditFileObserver.onEvent:80 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
03-29 16:22:31.304  4766  4766 E audit   : type=1320 msg=audit(1459261351.299:196): 
,03-29 16:22:31.304  3452  3579 D SecurityLogAgent:SEDenialService: audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,03-29 16:22:31.304  3452  3572 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-29 16:22:31.304  3452  3572 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-29 16:22:31.304 11183 11246 W jxcore-log: Starting JXcore engine
03-29 16:22:31.304  3452  3572 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-29 16:22:31.304  3452  3572 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-29 16:22:31.314 11247 11247 E Zygote  : MountEmulatedStorage()
03-29 16:22:31.314 11247 11247 E Zygote  : v2
03-29 16:22:31.314 11247 11247 I libpersona: KNOX_SDCARD checking this for 1000
03-29 16:22:31.314 11247 11247 I libpersona: KNOX_SDCARD not a persona
,03-29 16:22:31.319 11247 11247 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
,03-29 16:22:31.319  3452  3572 I ActivityManager: Start proc 11247:com.samsung.android.securitylogagent/1000 for broadcast-3 com.samsung.android.securitylogagent/.receivers.SeDenialReceiver
,03-29 16:22:31.319 11247 11247 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
,03-29 16:22:31.324 11247 11247 E Zygote  : accessInfo : 0
,03-29 16:22:31.324 11247 11247 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-29 16:22:31.339 11247 11247 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-29 16:22:31.339 11247 11247 D ActivityThread: Added TimaKeyStore provider
,03-29 16:22:31.349  3452  3492 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1b6e0a05 u0 samsung.intent.action.knox.DENIAL_NOTIFICATION} DELIVERED for app ProcessRecord{39c5fa5a 11247:com.samsung.android.securitylogagent/1000}
,03-29 16:22:31.354 11183 11246 W jxcore-log: Platform android
03-29 16:22:31.354 11183 11246 W jxcore-log: 
03-29 16:22:31.354 11183 11246 W jxcore-log: Process ARCH arm
03-29 16:22:31.354 11183 11246 W jxcore-log: 
,03-29 16:22:31.364 11247 11247 D SecurityLogAgent:  SeDenialReceiver : Intent received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,03-29 16:22:31.369 11247 11247 D SecurityLogAgent:  SeDenialReceiver : File path = null
,03-29 16:22:31.369  3452  3651 I ActivityManager: Killing 9782:com.android.mms/u0a52 (adj 15): emptyCount ##31
,03-29 16:22:31.429  3452  3914 D CountryDetector: No listener is left
,03-29 16:22:31.454 11183 11246 I jxcore-log: JXcore Cordova bridge is ready!
03-29 16:22:31.454 11183 11246 I jxcore-log: 
03-29 16:22:31.454 11183 11246 W jxcore-log: JXcore engine is started
,03-29 16:22:31.459 11183 11239 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-29 16:22:31.464 11183 11183 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-29 16:22:31.959  3452  3619 V AlarmManager: waitForAlarm result :4
,03-29 16:22:31.964  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
03-29 16:22:31.964  3726  3726 I PERF    : received broadcast android.intent.action.TIME_TICK
03-29 16:22:31.964  3726  3726 D KeyguardUpdateMonitor: handleTimeUpdate
,03-29 16:22:31.969  3726  3726 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,03-29 16:22:31.969  3726  3726 D SecKeyguardClockView: HomeTimezone(): 1
,03-29 16:22:31.974  3726  3726 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
03-29 16:22:31.974  3726  3726 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,03-29 16:22:31.974  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,03-29 16:22:31.999  3726  3726 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-29 16:22:31.999  3726  3726 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
03-29 16:22:31.999  3726  3726 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
03-29 16:22:31.999  3726  3726 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-29 16:22:32.004  3726  3726 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-29 16:22:32.004  3726  3726 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-29 16:22:32.009  3726  3726 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-29 16:22:32.869  3452  3692 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/42_task.xml.bak
,03-29 16:22:35.574  4462  5736 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,03-29 16:22:37.284 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-29 16:22:37.284 11183 11246 I jxcore-log: 
,03-29 16:22:37.284 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-29 16:22:37.284 11183 11246 I jxcore-log: 
,03-29 16:22:37.289 11183 11246 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-29 16:22:37.289 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-29 16:22:37.289 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-29 16:22:37.289 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-29 16:22:37.289 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-29 16:22:37.289 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-29 16:22:37.289 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-29 16:22:37.289 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-29 16:22:37.289 11183 11246 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-29 16:22:37.289 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-29 16:22:37.289 11183 11246 I jxcore-log: 
,03-29 16:22:37.289 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-29 16:22:37.289 11183 11246 I jxcore-log: 
,03-29 16:22:37.619 11183 11246 I jxcore-log: Unit Test app is loaded
03-29 16:22:37.619 11183 11246 I jxcore-log: 
,03-29 16:22:37.624 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-29 16:22:37.624 11183 11246 I jxcore-log: 
,03-29 16:22:37.624 11183 11183 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
03-29 16:22:37.629 11183 11246 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,03-29 16:22:37.629 11183 11246 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
03-29 16:22:37.629 11183 11246 I jxcore-log: 
,03-29 16:22:37.629 11183 11246 I jxcore-log: My device name is: samsung-SM-N910C
03-29 16:22:37.629 11183 11246 I jxcore-log: 
,03-29 16:22:39.319  3452  4028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-29 16:22:39.319  3452  4028 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-29 16:22:39.319  3452  4028 D BatteryService: online:4, current avg:-82, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-195
03-29 16:22:39.319  3452  4028 D BatteryService: stay LED for fully charged
03-29 16:22:39.319  3452  3452 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-29 16:22:39.319  3452  3452 I MotionRecognitionService: Plugged
03-29 16:22:39.319  3452  3452 D MotionRecognitionService:   cableConnection= 1
03-29 16:22:39.319  3452  3452 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-29 16:22:39.319  3452  3452 D MotionRecognitionService: skip setTransmitPower. 
,03-29 16:22:39.324  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-29 16:22:39.324  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-29 16:22:39.324  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-29 16:22:39.324  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-29 16:22:39.329  5848  5848 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-29 16:22:39.329  5848  5945 D HeadsetStateMachine: Disconnected process message: 10
,03-29 16:22:39.344  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-29 16:22:39.344  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-29 16:22:39.344  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-29 16:22:39.904  3452  3591 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,03-29 16:22:39.914  3452  3591 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,03-29 16:22:40.039 11183 11246 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
03-29 16:22:40.039 11183 11246 I jxcore-log: 
,03-29 16:22:40.209  3452  3619 V AlarmManager: waitForAlarm result :4
,03-29 16:22:40.254 11183 11246 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
03-29 16:22:40.254 11183 11246 I jxcore-log: 
,03-29 16:22:40.259 11183 11246 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
03-29 16:22:40.259 11183 11246 I jxcore-log: 
,03-29 16:22:40.264 11183 11246 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
03-29 16:22:40.264 11183 11246 I jxcore-log: 
,03-29 16:22:40.284 11183 11246 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
03-29 16:22:40.284 11183 11246 I jxcore-log: 
,03-29 16:22:40.294 11183 11246 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
03-29 16:22:40.294 11183 11246 I jxcore-log: 
,03-29 16:22:40.294 11183 11246 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
03-29 16:22:40.294 11183 11246 I jxcore-log: 
,03-29 16:22:40.689  3452  6034 D SSRM:n  : SIOP:: AP = 310, PST = 287 (W:10), CUR = -82, LCD = 0
,03-29 16:22:41.529 11183 11246 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
03-29 16:22:41.529 11183 11246 I jxcore-log: 
,03-29 16:22:41.539 11183 11246 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
03-29 16:22:41.539 11183 11246 I jxcore-log: 
,03-29 16:22:41.544 11183 11246 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
03-29 16:22:41.544 11183 11246 I jxcore-log: 
,03-29 16:22:41.694 11183 11246 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
03-29 16:22:41.694 11183 11246 I jxcore-log: 
,03-29 16:22:41.734 11183 11246 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
03-29 16:22:41.734 11183 11246 I jxcore-log: 
,03-29 16:22:41.769 11183 11246 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
03-29 16:22:41.769 11183 11246 I jxcore-log: 
,03-29 16:22:41.774 11183 11246 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
03-29 16:22:41.774 11183 11246 I jxcore-log: 
,03-29 16:22:41.779 11183 11246 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
03-29 16:22:41.779 11183 11246 I jxcore-log: 
,03-29 16:22:41.779 11183 11246 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
03-29 16:22:41.779 11183 11246 I jxcore-log: 
,03-29 16:22:41.784 11183 11246 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
03-29 16:22:41.784 11183 11246 I jxcore-log: 
,03-29 16:22:41.794 11183 11246 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
03-29 16:22:41.794 11183 11246 I jxcore-log: 
,03-29 16:22:41.804 11183 11246 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
03-29 16:22:41.804 11183 11246 I jxcore-log: 
,03-29 16:22:41.854 11183 11246 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
03-29 16:22:41.854 11183 11246 I jxcore-log: 
,03-29 16:22:41.854 11183 11246 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
03-29 16:22:41.854 11183 11246 I jxcore-log: 
,03-29 16:22:41.869 11183 11246 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
03-29 16:22:41.869 11183 11246 I jxcore-log: 
,03-29 16:22:44.049  3452  6065 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-29 16:22:46.829  3452  3861 E Watchdog: !@Sync 6 [03-29 16:22:46.830]
,03-29 16:22:49.464  3452  3914 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-29 16:22:49.464  3452  3914 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-29 16:22:49.464  3452  3914 D BatteryService: online:4, current avg:-29, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:57
,03-29 16:22:49.464  3452  3452 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-29 16:22:49.474  3452  3452 I MotionRecognitionService: Plugged
03-29 16:22:49.474  3452  3452 D MotionRecognitionService:   cableConnection= 1,
03-29 16:22:49.474  3452  3452 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
,03-29 16:22:49.474  3452  3452 D MotionRecognitionService: skip setTransmitPower. ,
,03-29 16:22:49.479  3452  3914 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 16ms,
03-29 16:22:49.479  3452  3914 D BatteryService: stay LED for fully charged,
03-29 16:22:49.489  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-29 16:22:49.489  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
03-29 16:22:49.489  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-29 16:22:49.509  5848  5848 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-29 16:22:49.509  5848  5945 D HeadsetStateMachine: Disconnected process message: 10
,03-29 16:22:49.519  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-29 16:22:49.519  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-29 16:22:49.519  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-29 16:22:49.519  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-29 16:22:50.224  2892  4828 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-29 16:22:50.714  3452  6034 D SSRM:n  : SIOP:: AP = 300, PST = 285 (W:10), CUR = -29, LCD = 0,
,03-29 16:22:58.289 11183 11246 I jxcore-log: TAP version 13
03-29 16:22:58.289 11183 11246 I jxcore-log: 
,03-29 16:22:58.289 11183 11246 I jxcore-log: # setup
03-29 16:22:58.289 11183 11246 I jxcore-log: 
,03-29 16:22:58.544 11183 11246 I jxcore-log: # 1. calling createNativeListener directly rejects
03-29 16:22:58.544 11183 11246 I jxcore-log: 
,03-29 16:22:59.124 11183 11246 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 16:22:59.124 11183 11246 I jxcore-log: 
,03-29 16:22:59.134 11183 11246 I jxcore-log: DEBUG createNativeListener: listening 50471
03-29 16:22:59.134 11183 11246 I jxcore-log: 
,03-29 16:22:59.144 11183 11246 I jxcore-log: ok 1 Should throw
03-29 16:22:59.144 11183 11246 I jxcore-log: 
,03-29 16:22:59.144 11183 11246 I jxcore-log: # teardown
03-29 16:22:59.144 11183 11246 I jxcore-log: 
,03-29 16:22:59.324 11183 11246 I jxcore-log: # setup
03-29 16:22:59.324 11183 11246 I jxcore-log: 
,03-29 16:22:59.604  3452  4020 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-29 16:22:59.604  3452  4020 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-29 16:22:59.604  3452  4020 D BatteryService: online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:59
,03-29 16:22:59.604  3452  3452 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-29 16:22:59.609  3452  4020 D BatteryService: stay LED for fully charged
,03-29 16:22:59.614  3452  3452 I MotionRecognitionService: Plugged,
03-29 16:22:59.614  3452  3452 D MotionRecognitionService:   cableConnection= 1,
,03-29 16:22:59.614  3452  3452 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-29 16:22:59.614  3452  3452 D MotionRecognitionService: skip setTransmitPower. 
,03-29 16:22:59.624  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-29 16:22:59.624  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-29 16:22:59.624  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-29 16:22:59.644  5848  5848 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-29 16:22:59.644  5848  5945 D HeadsetStateMachine: Disconnected process message: 10
,03-29 16:22:59.654  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-29 16:22:59.654  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-29 16:22:59.654  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-29 16:22:59.654  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-29 16:22:59.939 11183 11246 I jxcore-log: # 2. emits incomingConnectionState
03-29 16:22:59.939 11183 11246 I jxcore-log: 
,03-29 16:22:59.999  3452  3619 V AlarmManager: waitForAlarm result :8
,03-29 16:23:00.049 11183 11246 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 16:23:00.049 11183 11246 I jxcore-log: 
,03-29 16:23:00.054 11183 11246 I jxcore-log: DEBUG createNativeListener: listening 46907
03-29 16:23:00.054 11183 11246 I jxcore-log: 
,03-29 16:23:00.064 11183 11246 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 16:23:00.064 11183 11246 I jxcore-log: 
,03-29 16:23:00.069 11183 11246 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 16:23:00.069 11183 11246 I jxcore-log: 
,03-29 16:23:00.079 11183 11246 I jxcore-log: DEBUG createNativeListener: new mux
03-29 16:23:00.079 11183 11246 I jxcore-log: 
,03-29 16:23:00.089 11183 11246 I jxcore-log: ok 2 initial connection state should be CONNECTED
03-29 16:23:00.089 11183 11246 I jxcore-log: 
,03-29 16:23:00.114 11183 11246 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 16:23:00.114 11183 11246 I jxcore-log: 
,03-29 16:23:00.114 11183 11246 I jxcore-log: ok 3 final connection state should be DISCONNECTED
03-29 16:23:00.114 11183 11246 I jxcore-log: 
,03-29 16:23:00.119 11183 11246 I jxcore-log: # teardown
03-29 16:23:00.119 11183 11246 I jxcore-log: 
,03-29 16:23:00.464  3452  3585 I PowerManagerService: [PWL] Off : 140s ago
,03-29 16:23:00.749  3452  6034 D SSRM:n  : SIOP:: AP = 290, PST = 286 (W:10), CUR = 20, LCD = 0
,03-29 16:23:02.214 11183 11246 I jxcore-log: # setup
03-29 16:23:02.214 11183 11246 I jxcore-log: 
,03-29 16:23:02.924 11183 11246 I jxcore-log: # 3. emits routerPortConnectionFailed
03-29 16:23:02.924 11183 11246 I jxcore-log: 
,03-29 16:23:03.144 11183 11246 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 16:23:03.144 11183 11246 I jxcore-log: 
,03-29 16:23:03.149 11183 11246 I jxcore-log: DEBUG createNativeListener: listening 32966
03-29 16:23:03.149 11183 11246 I jxcore-log: 
,03-29 16:23:03.154 11183 11246 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 16:23:03.154 11183 11246 I jxcore-log: 
,03-29 16:23:03.159 11183 11246 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 16:23:03.159 11183 11246 I jxcore-log: 
,03-29 16:23:03.159 11183 11246 I jxcore-log: DEBUG createNativeListener: new mux
03-29 16:23:03.159 11183 11246 I jxcore-log: 
,03-29 16:23:03.199 11183 11246 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:03.199 11183 11246 I jxcore-log: 
,03-29 16:23:03.204 11183 11246 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:03.204 11183 11246 I jxcore-log: 
,03-29 16:23:03.209 11183 11246 I jxcore-log: DEBUG createNativeListener: 
03-29 16:23:03.209 11183 11246 I jxcore-log: 
,03-29 16:23:03.209 11183 11246 I jxcore-log: ok 4 tried to connect to right port
03-29 16:23:03.209 11183 11246 I jxcore-log: 
,03-29 16:23:03.214 11183 11246 I jxcore-log: ok 5 failed due to refused connection
03-29 16:23:03.214 11183 11246 I jxcore-log: 
,03-29 16:23:03.214 11183 11246 I jxcore-log: ok 6 routerPortConnectionFailed is emitted
03-29 16:23:03.214 11183 11246 I jxcore-log: 
,03-29 16:23:03.219 11183 11246 I jxcore-log: # teardown
03-29 16:23:03.219 11183 11246 I jxcore-log: 
,03-29 16:23:03.219 11183 11246 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:03.219 11183 11246 I jxcore-log: 
,03-29 16:23:03.464 11183 11246 I jxcore-log: DEBUG createNativeListener: mux close
03-29 16:23:03.464 11183 11246 I jxcore-log: 
,03-29 16:23:03.474 11183 11246 I jxcore-log: # setup
03-29 16:23:03.474 11183 11246 I jxcore-log: 
,03-29 16:23:03.479 11183 11246 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 16:23:03.479 11183 11246 I jxcore-log: 
,03-29 16:23:03.619 11183 11246 I jxcore-log: # 4. native server connections all up
03-29 16:23:03.619 11183 11246 I jxcore-log: 
,03-29 16:23:03.764 11183 11246 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 16:23:03.764 11183 11246 I jxcore-log: 
,03-29 16:23:03.769 11183 11246 I jxcore-log: DEBUG createNativeListener: listening 54852
03-29 16:23:03.769 11183 11246 I jxcore-log: 
,03-29 16:23:03.784 11183 11246 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 16:23:03.784 11183 11246 I jxcore-log: 
,03-29 16:23:03.784 11183 11246 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 16:23:03.784 11183 11246 I jxcore-log: 
,03-29 16:23:03.789 11183 11246 I jxcore-log: DEBUG createNativeListener: new mux
03-29 16:23:03.789 11183 11246 I jxcore-log: 
,03-29 16:23:03.819 11183 11246 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:03.819 11183 11246 I jxcore-log: 
,03-29 16:23:03.824 11183 11246 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:03.824 11183 11246 I jxcore-log: 
,03-29 16:23:03.829 11183 11246 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:03.829 11183 11246 I jxcore-log: 
,03-29 16:23:03.834 11183 11246 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:03.834 11183 11246 I jxcore-log: 
,03-29 16:23:03.884 11183 11246 I jxcore-log: ok 7 Send/recvd #1 should be equal length
03-29 16:23:03.884 11183 11246 I jxcore-log: 
,03-29 16:23:03.884 11183 11246 I jxcore-log: ok 8 Send/recvd #1 should be same
03-29 16:23:03.884 11183 11246 I jxcore-log: 
03-29 16:23:03.889 11183 11246 I jxcore-log: ok 9 Send/recvd #2 should be equal length
03-29 16:23:03.889 11183 11246 I jxcore-log: 
03-29 16:23:03.889 11183 11246 I jxcore-log: ok 10 Send/recvd #2 should be same
03-29 16:23:03.889 11183 11246 I jxcore-log: 
,03-29 16:23:03.894 11183 11246 I jxcore-log: ok 11 Should be exactly 2 client sockets
03-29 16:23:03.894 11183 11246 I jxcore-log: 
,03-29 16:23:03.904 11183 11246 I jxcore-log: # teardown
03-29 16:23:03.904 11183 11246 I jxcore-log: 
,03-29 16:23:04.054  3452  6065 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-29 16:23:04.064 11183 11246 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:04.064 11183 11246 I jxcore-log: 
,03-29 16:23:04.069 11183 11246 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:04.069 11183 11246 I jxcore-log: 
,03-29 16:23:04.074 11183 11246 I jxcore-log: DEBUG createNativeListener: mux close
03-29 16:23:04.074 11183 11246 I jxcore-log: 
,03-29 16:23:04.084 11183 11246 I jxcore-log: # setup
03-29 16:23:04.084 11183 11246 I jxcore-log: 
,03-29 16:23:04.084 11183 11246 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 16:23:04.084 11183 11246 I jxcore-log: 
,03-29 16:23:04.234 11183 11246 I jxcore-log: # 5. native server - closing incoming stream cleans outgoing socket
03-29 16:23:04.234 11183 11246 I jxcore-log: 
,03-29 16:23:04.464 11183 11246 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 16:23:04.464 11183 11246 I jxcore-log: 
,03-29 16:23:04.469 11183 11246 I jxcore-log: DEBUG createNativeListener: listening 60765
03-29 16:23:04.469 11183 11246 I jxcore-log: 
,03-29 16:23:04.479 11183 11246 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 16:23:04.479 11183 11246 I jxcore-log: 
,03-29 16:23:04.484 11183 11246 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 16:23:04.484 11183 11246 I jxcore-log: 
,03-29 16:23:04.489 11183 11246 I jxcore-log: DEBUG createNativeListener: new mux
03-29 16:23:04.489 11183 11246 I jxcore-log: 
,03-29 16:23:04.504 11183 11246 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:04.504 11183 11246 I jxcore-log: 
,03-29 16:23:04.509 11183 11246 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:04.509 11183 11246 I jxcore-log: 
,03-29 16:23:04.529 11183 11246 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:04.529 11183 11246 I jxcore-log: 
,03-29 16:23:04.544 11183 11246 I jxcore-log: ok 12 socket shouldn't close until after stream
03-29 16:23:04.544 11183 11246 I jxcore-log: 
,03-29 16:23:04.544 11183 11246 I jxcore-log: ok 13 incoming remains open
03-29 16:23:04.544 11183 11246 I jxcore-log: 
,03-29 16:23:04.549 11183 11246 I jxcore-log: # teardown
03-29 16:23:04.549 11183 11246 I jxcore-log: 
,03-29 16:23:04.669 11183 11246 I jxcore-log: DEBUG createNativeListener: mux close
03-29 16:23:04.669 11183 11246 I jxcore-log: 
,03-29 16:23:04.679 11183 11246 I jxcore-log: # setup
03-29 16:23:04.679 11183 11246 I jxcore-log: 
,03-29 16:23:04.684 11183 11246 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 16:23:04.684 11183 11246 I jxcore-log: 
,03-29 16:23:04.774 11183 11246 I jxcore-log: # 6. native server - closing incoming connection cleans outgoing socket
03-29 16:23:04.774 11183 11246 I jxcore-log: 
,03-29 16:23:04.929 11183 11246 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 16:23:04.929 11183 11246 I jxcore-log: 
,03-29 16:23:04.934 11183 11246 I jxcore-log: DEBUG createNativeListener: listening 47021
03-29 16:23:04.934 11183 11246 I jxcore-log: 
,03-29 16:23:04.944 11183 11246 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 16:23:04.944 11183 11246 I jxcore-log: 
,03-29 16:23:04.949 11183 11246 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 16:23:04.949 11183 11246 I jxcore-log: 
,03-29 16:23:04.949 11183 11246 I jxcore-log: DEBUG createNativeListener: new mux
03-29 16:23:04.949 11183 11246 I jxcore-log: 
,03-29 16:23:04.964 11183 11246 I jxcore-log: ok 14 we should not have gotten an error
03-29 16:23:04.964 11183 11246 I jxcore-log: 
,03-29 16:23:04.969 11183 11246 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:04.969 11183 11246 I jxcore-log: 
,03-29 16:23:04.979 11183 11246 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:04.979 11183 11246 I jxcore-log: 
,03-29 16:23:04.989 11183 11246 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:04.989 11183 11246 I jxcore-log: 
,03-29 16:23:04.994 11183 11246 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 16:23:04.994 11183 11246 I jxcore-log: 
,03-29 16:23:05.004 11183 11246 I jxcore-log: ok 15 socket shouldn't close until after incoming
03-29 16:23:05.004 11183 11246 I jxcore-log: 
,03-29 16:23:05.004 11183 11246 I jxcore-log: ok 16 incoming is cleaned up
03-29 16:23:05.004 11183 11246 I jxcore-log: 
,03-29 16:23:05.014 11183 11246 I jxcore-log: # teardown
03-29 16:23:05.014 11183 11246 I jxcore-log: 
,03-29 16:23:05.099 11183 11246 I jxcore-log: # setup
03-29 16:23:05.099 11183 11246 I jxcore-log: 
,03-29 16:23:05.254 11183 11246 I jxcore-log: # 7. native server - closing outgoing socket cleans associated mux stream
03-29 16:23:05.254 11183 11246 I jxcore-log: 
,03-29 16:23:05.394 11183 11246 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 16:23:05.394 11183 11246 I jxcore-log: 
,03-29 16:23:05.404 11183 11246 I jxcore-log: DEBUG createNativeListener: listening 36622
03-29 16:23:05.404 11183 11246 I jxcore-log: 
,03-29 16:23:05.414 11183 11246 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 16:23:05.414 11183 11246 I jxcore-log: 
,03-29 16:23:05.414 11183 11246 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 16:23:05.414 11183 11246 I jxcore-log: 
,03-29 16:23:05.419 11183 11246 I jxcore-log: DEBUG createNativeListener: new mux
03-29 16:23:05.419 11183 11246 I jxcore-log: 
,03-29 16:23:05.434 11183 11246 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:05.434 11183 11246 I jxcore-log: 
,03-29 16:23:05.439 11183 11246 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:05.439 11183 11246 I jxcore-log: 
,03-29 16:23:05.459 11183 11246 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:05.459 11183 11246 I jxcore-log: 
,03-29 16:23:05.469 11183 11246 I jxcore-log: ok 17 stream was closed
03-29 16:23:05.469 11183 11246 I jxcore-log: 
,03-29 16:23:05.469 11183 11246 I jxcore-log: ok 18 incoming should survive
03-29 16:23:05.469 11183 11246 I jxcore-log: 
,03-29 16:23:05.474 11183 11246 I jxcore-log: ok 19 mux should have no streams
03-29 16:23:05.474 11183 11246 I jxcore-log: 
,03-29 16:23:05.479 11183 11246 I jxcore-log: # teardown
03-29 16:23:05.479 11183 11246 I jxcore-log: 
,03-29 16:23:05.894 11183 11246 I jxcore-log: DEBUG createNativeListener: mux close
03-29 16:23:05.894 11183 11246 I jxcore-log: 
,03-29 16:23:05.904 11183 11246 I jxcore-log: # setup
03-29 16:23:05.904 11183 11246 I jxcore-log: 
,03-29 16:23:05.909 11183 11246 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 16:23:05.909 11183 11246 I jxcore-log: 
,03-29 16:23:09.739  3452  3651 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-29 16:23:09.739  3452  3651 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-29 16:23:09.739  3452  3651 D BatteryService: online:4, current avg:37, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:49
,03-29 16:23:09.744  3452  3452 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-29 16:23:09.754  3452  3452 I MotionRecognitionService: Plugged
03-29 16:23:09.754  3452  3452 D MotionRecognitionService:   cableConnection= 1,
03-29 16:23:09.754  3452  3452 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
03-29 16:23:09.754  3452  3452 D MotionRecognitionService: skip setTransmitPower. ,
,03-29 16:23:09.754  3452  3651 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 12ms
,03-29 16:23:09.754  3452  3651 D BatteryService: stay LED for fully charged
,03-29 16:23:09.764  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-29 16:23:09.764  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,03-29 16:23:09.764  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-29 16:23:09.784  5848  5848 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-29 16:23:09.784  5848  5945 D HeadsetStateMachine: Disconnected process message: 10
,03-29 16:23:09.794  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-29 16:23:09.794  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-29 16:23:09.794  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-29 16:23:09.794  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-29 16:23:10.779  3452  6034 D SSRM:n  : SIOP:: AP = 280, PST = 286 (W:10), CUR = 37, LCD = 0
,03-29 16:23:14.874 11183 11246 I jxcore-log: # 8. native server - closing the whole server cleans everything up
03-29 16:23:14.874 11183 11246 I jxcore-log: 
,03-29 16:23:16.834  3452  3861 E Watchdog: !@Sync 7 [03-29 16:23:16.838]
,03-29 16:23:18.789 11183 11246 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 16:23:18.789 11183 11246 I jxcore-log: 
,03-29 16:23:18.799 11183 11246 I jxcore-log: DEBUG createNativeListener: listening 44172
03-29 16:23:18.799 11183 11246 I jxcore-log: 
,03-29 16:23:18.809 11183 11246 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 16:23:18.809 11183 11246 I jxcore-log: 
,03-29 16:23:18.809 11183 11246 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 16:23:18.809 11183 11246 I jxcore-log: 
,03-29 16:23:18.814 11183 11246 I jxcore-log: DEBUG createNativeListener: new mux
03-29 16:23:18.814 11183 11246 I jxcore-log: 
,03-29 16:23:18.824 11183 11246 I jxcore-log: ok 20 we should not have gotten an error
03-29 16:23:18.824 11183 11246 I jxcore-log: 
,03-29 16:23:18.834 11183 11246 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:18.834 11183 11246 I jxcore-log: 
,03-29 16:23:18.839 11183 11246 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:18.839 11183 11246 I jxcore-log: 
,03-29 16:23:18.849 11183 11246 I jxcore-log: ok 21 Buffers are identical
03-29 16:23:18.849 11183 11246 I jxcore-log: 
,03-29 16:23:18.854 11183 11246 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:18.854 11183 11246 I jxcore-log: 
,03-29 16:23:18.859 11183 11246 I jxcore-log: DEBUG createNativeListener: mux close
03-29 16:23:18.859 11183 11246 I jxcore-log: 
,03-29 16:23:18.864 11183 11246 I jxcore-log: ok 22 native server is nulled out
03-29 16:23:18.864 11183 11246 I jxcore-log: 
,03-29 16:23:18.864 11183 11246 I jxcore-log: ok 23 native server should be closed
03-29 16:23:18.864 11183 11246 I jxcore-log: 
,03-29 16:23:18.864 11183 11246 I jxcore-log: ok 24 incoming has been removed
03-29 16:23:18.864 11183 11246 I jxcore-log: 
03-29 16:23:18.864 11183 11246 I jxcore-log: ok 25 Incoming should be done
03-29 16:23:18.864 11183 11246 I jxcore-log: 
,03-29 16:23:18.864 11183 11246 I jxcore-log: ok 26 The mux object should be closed
03-29 16:23:18.864 11183 11246 I jxcore-log: 
,03-29 16:23:18.869 11183 11246 I jxcore-log: ok 27 The mux stream should be closed
03-29 16:23:18.869 11183 11246 I jxcore-log: 
,03-29 16:23:18.869 11183 11246 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 16:23:18.869 11183 11246 I jxcore-log: 
,03-29 16:23:18.889 11183 11246 I jxcore-log: # teardown
03-29 16:23:18.889 11183 11246 I jxcore-log: 
,03-29 16:23:19.884  3452  3836 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-29 16:23:19.884  3452  3836 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0,
,03-29 16:23:19.884  3452  3836 D BatteryService: online:4, current avg:41, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,03-29 16:23:19.884  3452  3836 D BatteryService: stay LED for fully charged
03-29 16:23:19.884  3452  3452 D BatteryService: Sending ACTION_BATTERY_CHANGED.,
,03-29 16:23:19.894  3452  3452 I MotionRecognitionService: Plugged
,03-29 16:23:19.894  3452  3452 D MotionRecognitionService:   cableConnection= 1
03-29 16:23:19.894  3452  3452 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-29 16:23:19.894  3452  3452 D MotionRecognitionService: skip setTransmitPower. 
,03-29 16:23:19.899  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-29 16:23:19.899  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-29 16:23:19.899  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-29 16:23:19.914  5848  5848 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-29 16:23:19.914  5848  5945 D HeadsetStateMachine: Disconnected process message: 10
,03-29 16:23:19.924  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-29 16:23:19.929  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-29 16:23:19.929  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-29 16:23:19.929  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-29 16:23:20.809  3452  6034 D SSRM:n  : SIOP:: AP = 280, PST = 286 (W:12), CUR = 41, LCD = 0
,03-29 16:23:21.584 11183 11246 I jxcore-log: # setup
03-29 16:23:21.584 11183 11246 I jxcore-log: 
,03-29 16:23:23.494 11183 11246 I jxcore-log: # 9. native server - we can get a ton of connections and data through and still clean up the server completely
03-29 16:23:23.494 11183 11246 I jxcore-log: 
,03-29 16:23:23.774 11183 11246 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 16:23:23.774 11183 11246 I jxcore-log: 
,03-29 16:23:23.784 11183 11246 I jxcore-log: DEBUG createNativeListener: listening 35936
03-29 16:23:23.784 11183 11246 I jxcore-log: 
,03-29 16:23:23.819 11183 11246 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 16:23:23.819 11183 11246 I jxcore-log: 
,03-29 16:23:23.819 11183 11246 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 16:23:23.819 11183 11246 I jxcore-log: 
,03-29 16:23:23.824 11183 11246 I jxcore-log: DEBUG createNativeListener: new mux
03-29 16:23:23.824 11183 11246 I jxcore-log: 
,03-29 16:23:23.829 11183 11246 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 16:23:23.829 11183 11246 I jxcore-log: 
,03-29 16:23:23.829 11183 11246 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 16:23:23.829 11183 11246 I jxcore-log: 
,03-29 16:23:23.834 11183 11246 I jxcore-log: DEBUG createNativeListener: new mux
03-29 16:23:23.834 11183 11246 I jxcore-log: 
,03-29 16:23:23.839 11183 11246 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 16:23:23.839 11183 11246 I jxcore-log: 
,03-29 16:23:23.839 11183 11246 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 16:23:23.839 11183 11246 I jxcore-log: 
,03-29 16:23:23.839 11183 11246 I jxcore-log: DEBUG createNativeListener: new mux
03-29 16:23:23.839 11183 11246 I jxcore-log: 
,03-29 16:23:23.849 11183 11246 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 16:23:23.849 11183 11246 I jxcore-log: 
,03-29 16:23:23.849 11183 11246 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 16:23:23.849 11183 11246 I jxcore-log: 
,03-29 16:23:23.854 11183 11246 I jxcore-log: DEBUG createNativeListener: new mux
03-29 16:23:23.854 11183 11246 I jxcore-log: 
,03-29 16:23:23.854 11183 11246 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 16:23:23.854 11183 11246 I jxcore-log: 
,03-29 16:23:23.859 11183 11246 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 16:23:23.859 11183 11246 I jxcore-log: 
,03-29 16:23:23.859 11183 11246 I jxcore-log: DEBUG createNativeListener: new mux
03-29 16:23:23.859 11183 11246 I jxcore-log: 
,03-29 16:23:23.864 11183 11246 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 16:23:23.864 11183 11246 I jxcore-log: 
,03-29 16:23:23.864 11183 11246 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 16:23:23.864 11183 11246 I jxcore-log: 
,03-29 16:23:23.864 11183 11246 I jxcore-log: DEBUG createNativeListener: new mux
03-29 16:23:23.864 11183 11246 I jxcore-log: 
,03-29 16:23:23.869 11183 11246 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 16:23:23.869 11183 11246 I jxcore-log: 
,03-29 16:23:23.869 11183 11246 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 16:23:23.869 11183 11246 I jxcore-log: 
,03-29 16:23:23.869 11183 11246 I jxcore-log: DEBUG createNativeListener: new mux
03-29 16:23:23.869 11183 11246 I jxcore-log: 
,03-29 16:23:23.874 11183 11246 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 16:23:23.874 11183 11246 I jxcore-log: 
,03-29 16:23:23.874 11183 11246 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 16:23:23.874 11183 11246 I jxcore-log: 
,03-29 16:23:23.879 11183 11246 I jxcore-log: DEBUG createNativeListener: new mux
03-29 16:23:23.879 11183 11246 I jxcore-log: 
,03-29 16:23:23.879 11183 11246 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 16:23:23.879 11183 11246 I jxcore-log: 
,03-29 16:23:23.879 11183 11246 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 16:23:23.879 11183 11246 I jxcore-log: 
,03-29 16:23:23.884 11183 11246 I jxcore-log: DEBUG createNativeListener: new mux
03-29 16:23:23.884 11183 11246 I jxcore-log: 
,03-29 16:23:23.884 11183 11246 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 16:23:23.884 11183 11246 I jxcore-log: 
,03-29 16:23:23.889 11183 11246 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 16:23:23.889 11183 11246 I jxcore-log: 
,03-29 16:23:23.889 11183 11246 I jxcore-log: DEBUG createNativeListener: new mux
03-29 16:23:23.889 11183 11246 I jxcore-log: 
,03-29 16:23:24.009 11183 11246 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:24.009 11183 11246 I jxcore-log: 
,03-29 16:23:24.014 11183 11246 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:24.014 11183 11246 I jxcore-log: 
,03-29 16:23:24.014 11183 11246 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:24.014 11183 11246 I jxcore-log: 
,03-29 16:23:24.019 11183 11246 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:24.019 11183 11246 I jxcore-log: 
,03-29 16:23:24.019 11183 11246 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:24.019 11183 11246 I jxcore-log: 
,03-29 16:23:24.024 11183 11246 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:24.024 11183 11246 I jxcore-log: 
,03-29 16:23:24.024 11183 11246 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:24.024 11183 11246 I jxcore-log: 
,03-29 16:23:24.024 11183 11246 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:24.024 11183 11246 I jxcore-log: 
,03-29 16:23:24.024 11183 11246 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:24.024 11183 11246 I jxcore-log: 
,03-29 16:23:24.029 11183 11246 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:24.029 11183 11246 I jxcore-log: 
,03-29 16:23:24.029 11183 11246 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:24.029 11183 11246 I jxcore-log: 
,03-29 16:23:24.029 11183 11246 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:24.029 11183 11246 I jxcore-log: 
,03-29 16:23:24.034 11183 11246 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:24.034 11183 11246 I jxcore-log: 
,03-29 16:23:24.034 11183 11246 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:24.034 11183 11246 I jxcore-log: 
,03-29 16:23:24.034 11183 11246 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:24.034 11183 11246 I jxcore-log: 
,03-29 16:23:24.039 11183 11246 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:24.039 11183 11246 I jxcore-log: 
,03-29 16:23:24.039 11183 11246 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:24.039 11183 11246 I jxcore-log: 
,03-29 16:23:24.039 11183 11246 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:24.039 11183 11246 I jxcore-log: 
03-29 16:23:24.039 11183 11246 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:24.039 11183 11246 I jxcore-log: 
03-29 16:23:24.044 11183 11246 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:24.044 11183 11246 I jxcore-log: 
,03-29 16:23:24.049 11183 11246 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:24.049 11183 11246 I jxcore-log: 
,03-29 16:23:24.049 11183 11246 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:24.049 11183 11246 I jxcore-log: 
,03-29 16:23:24.049 11183 11246 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:24.049 11183 11246 I jxcore-log: 
,03-29 16:23:24.049 11183 11246 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:24.049 11183 11246 I jxcore-log: 
,03-29 16:23:24.054 11183 11246 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:24.054 11183 11246 I jxcore-log: 
,03-29 16:23:24.054 11183 11246 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:24.054 11183 11246 I jxcore-log: 
,03-29 16:23:24.054 11183 11246 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:24.054 11183 11246 I jxcore-log: 
,03-29 16:23:24.059  3452  6065 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-29 16:23:24.059 11183 11246 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:24.059 11183 11246 I jxcore-log: 
,03-29 16:23:24.059 11183 11246 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:24.059 11183 11246 I jxcore-log: 
,03-29 16:23:24.059 11183 11246 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:24.059 11183 11246 I jxcore-log: 
,03-29 16:23:24.059 11183 11246 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:24.059 11183 11246 I jxcore-log: 
,03-29 16:23:24.064 11183 11246 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:24.064 11183 11246 I jxcore-log: 
,03-29 16:23:24.064 11183 11246 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:24.064 11183 11246 I jxcore-log: 
,03-29 16:23:24.064 11183 11246 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:24.064 11183 11246 I jxcore-log: 
,03-29 16:23:24.069 11183 11246 I jxcore-log: DEBUG createNativeListener: new stream: ,
03-29 16:23:24.069 11183 11246 I jxcore-log: 
,03-29 16:23:24.069 11183 11246 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:24.069 11183 11246 I jxcore-log: 
,03-29 16:23:24.069 11183 11246 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:24.069 11183 11246 I jxcore-log: 
,03-29 16:23:24.069 11183 11246 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:24.069 11183 11246 I jxcore-log: 
,03-29 16:23:24.074 11183 11246 I jxcore-log: DEBUG createNativeListener: new stream: ,
03-29 16:23:24.074 11183 11246 I jxcore-log: 
,03-29 16:23:24.074 11183 11246 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:24.074 11183 11246 I jxcore-log: 
,03-29 16:23:24.074 11183 11246 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:24.074 11183 11246 I jxcore-log: 
,03-29 16:23:24.079 11183 11246 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:24.079 11183 11246 I jxcore-log: 
,03-29 16:23:24.079 11183 11246 I jxcore-log: DEBUG createNativeListener: new stream: ,
03-29 16:23:24.079 11183 11246 I jxcore-log: 
,03-29 16:23:24.079 11183 11246 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:24.079 11183 11246 I jxcore-log: 
,03-29 16:23:24.079 11183 11246 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:24.079 11183 11246 I jxcore-log: 
,03-29 16:23:24.089 11183 11246 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:24.089 11183 11246 I jxcore-log: 
,03-29 16:23:24.089 11183 11246 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:24.089 11183 11246 I jxcore-log: 
,03-29 16:23:24.094 11183 11246 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:24.094 11183 11246 I jxcore-log: 
,03-29 16:23:24.094 11183 11246 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:24.094 11183 11246 I jxcore-log: 
,03-29 16:23:24.099 11183 11246 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:24.099 11183 11246 I jxcore-log: 
,03-29 16:23:24.099 11183 11246 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:24.099 11183 11246 I jxcore-log: 
,03-29 16:23:24.099 11183 11246 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:24.099 11183 11246 I jxcore-log: 
,03-29 16:23:24.099 11183 11246 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:24.099 11183 11246 I jxcore-log: 
,03-29 16:23:24.104 11183 11246 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:24.104 11183 11246 I jxcore-log: 
,03-29 16:23:24.104 11183 11246 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:24.104 11183 11246 I jxcore-log: 
,03-29 16:23:24.104 11183 11246 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:24.104 11183 11246 I jxcore-log: 
,03-29 16:23:24.109 11183 11246 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:24.109 11183 11246 I jxcore-log: 
,03-29 16:23:24.109 11183 11246 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:24.109 11183 11246 I jxcore-log: 
,03-29 16:23:24.109 11183 11246 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:24.109 11183 11246 I jxcore-log: 
,03-29 16:23:24.114 11183 11246 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:24.114 11183 11246 I jxcore-log: 
,03-29 16:23:24.114 11183 11246 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:24.114 11183 11246 I jxcore-log: 
,03-29 16:23:24.114 11183 11246 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:24.114 11183 11246 I jxcore-log: 
,03-29 16:23:24.114 11183 11246 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:24.114 11183 11246 I jxcore-log: 
,03-29 16:23:24.114 11183 11246 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:24.114 11183 11246 I jxcore-log: 
,03-29 16:23:24.119 11183 11246 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:24.119 11183 11246 I jxcore-log: 
,03-29 16:23:24.119 11183 11246 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:24.119 11183 11246 I jxcore-log: 
,03-29 16:23:24.119 11183 11246 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:24.119 11183 11246 I jxcore-log: 
,03-29 16:23:24.119 11183 11246 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:24.119 11183 11246 I jxcore-log: 
,03-29 16:23:24.124 11183 11246 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:24.124 11183 11246 I jxcore-log: 
,03-29 16:23:24.124 11183 11246 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:24.124 11183 11246 I jxcore-log: 
,03-29 16:23:24.124 11183 11246 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:24.124 11183 11246 I jxcore-log: 
,03-29 16:23:24.124 11183 11246 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:24.124 11183 11246 I jxcore-log: 
,03-29 16:23:24.129 11183 11246 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:24.129 11183 11246 I jxcore-log: ,
,03-29 16:23:24.129 11183 11246 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:24.129 11183 11246 I jxcore-log: 
,03-29 16:23:24.129 11183 11246 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:24.129 11183 11246 I jxcore-log: 
,03-29 16:23:24.129 11183 11246 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:24.129 11183 11246 I jxcore-log: 
,03-29 16:23:24.129 11183 11246 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:24.129 11183 11246 I jxcore-log: 
,03-29 16:23:24.134 11183 11246 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:24.134 11183 11246 I jxcore-log: 
03-29 16:23:24.134 11183 11246 I jxcore-log: DEBUG createNativeListener: new stream: 
,03-29 16:23:24.134 11183 11246 I jxcore-log: 
,03-29 16:23:24.134 11183 11246 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:24.134 11183 11246 I jxcore-log: 
,03-29 16:23:24.194 11183 11246 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.194 11183 11246 I jxcore-log: 
,03-29 16:23:24.194 11183 11246 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.194 11183 11246 I jxcore-log: 
,03-29 16:23:24.194 11183 11246 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.194 11183 11246 I jxcore-log: 
,03-29 16:23:24.194 11183 11246 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.194 11183 11246 I jxcore-log: 
03-29 16:23:24.194 11183 11246 I jxcore-log: DEBUG createNativeListener: mux close
03-29 16:23:24.194 11183 11246 I jxcore-log: 
,03-29 16:23:24.199 11183 11246 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.199 11183 11246 I jxcore-log: 
,03-29 16:23:24.199 11183 11246 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.199 11183 11246 I jxcore-log: 
03-29 16:23:24.199 11183 11246 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.199 11183 11246 I jxcore-log: 
,03-29 16:23:24.199 11183 11246 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.199 11183 11246 I jxcore-log: 
03-29 16:23:24.199 11183 11246 I jxcore-log: DEBUG createNativeListener: mux close
03-29 16:23:24.199 11183 11246 I jxcore-log: 
,03-29 16:23:24.199 11183 11246 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.199 11183 11246 I jxcore-log: 
,03-29 16:23:24.204 11183 11246 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.204 11183 11246 I jxcore-log: 
03-29 16:23:24.204 11183 11246 I jxcore-log: DEBUG createNativeListener: stream close:
,03-29 16:23:24.204 11183 11246 I jxcore-log: 
03-29 16:23:24.204 11183 11246 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.204 11183 11246 I jxcore-log: 
,03-29 16:23:24.204 11183 11246 I jxcore-log: DEBUG createNativeListener: mux close
03-29 16:23:24.204 11183 11246 I jxcore-log: 
,03-29 16:23:24.204 11183 11246 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.204 11183 11246 I jxcore-log: 
03-29 16:23:24.204 11183 11246 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.204 11183 11246 I jxcore-log: 
,03-29 16:23:24.204 11183 11246 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.204 11183 11246 I jxcore-log: 
03-29 16:23:24.209 11183 11246 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.209 11183 11246 I jxcore-log: 
,03-29 16:23:24.209 11183 11246 I jxcore-log: DEBUG createNativeListener: mux close
03-29 16:23:24.209 11183 11246 I jxcore-log: 
03-29 16:23:24.209 11183 11246 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.209 11183 11246 I jxcore-log: 
,03-29 16:23:24.209 11183 11246 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.209 11183 11246 I jxcore-log: 
03-29 16:23:24.209 11183 11246 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.209 11183 11246 I jxcore-log: 
,03-29 16:23:24.209 11183 11246 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.209 11183 11246 I jxcore-log: 
,03-29 16:23:24.209 11183 11246 I jxcore-log: DEBUG createNativeListener: mux close
03-29 16:23:24.209 11183 11246 I jxcore-log: 
03-29 16:23:24.209 11183 11246 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.209 11183 11246 I jxcore-log: 
,03-29 16:23:24.214 11183 11246 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.214 11183 11246 I jxcore-log: 
,03-29 16:23:24.214 11183 11246 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.214 11183 11246 I jxcore-log: 
03-29 16:23:24.214 11183 11246 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.214 11183 11246 I jxcore-log: 
,03-29 16:23:24.214 11183 11246 I jxcore-log: DEBUG createNativeListener: mux close
03-29 16:23:24.214 11183 11246 I jxcore-log: 
,03-29 16:23:24.214 11183 11246 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.214 11183 11246 I jxcore-log: 
03-29 16:23:24.214 11183 11246 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.214 11183 11246 I jxcore-log: 
,03-29 16:23:24.214 11183 11246 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.214 11183 11246 I jxcore-log: 
,03-29 16:23:24.214 11183 11246 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.214 11183 11246 I jxcore-log: 
03-29 16:23:24.214 11183 11246 I jxcore-log: DEBUG createNativeListener: mux close
03-29 16:23:24.214 11183 11246 I jxcore-log: 
,03-29 16:23:24.214 11183 11246 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.214 11183 11246 I jxcore-log: 
03-29 16:23:24.219 11183 11246 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.219 11183 11246 I jxcore-log: 
,03-29 16:23:24.219 11183 11246 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.219 11183 11246 I jxcore-log: 
03-29 16:23:24.219 11183 11246 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.219 11183 11246 I jxcore-log: 
,03-29 16:23:24.219 11183 11246 I jxcore-log: DEBUG createNativeListener: mux close
03-29 16:23:24.219 11183 11246 I jxcore-log: 
03-29 16:23:24.219 11183 11246 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.219 11183 11246 I jxcore-log: 
,03-29 16:23:24.219 11183 11246 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.219 11183 11246 I jxcore-log: 
03-29 16:23:24.219 11183 11246 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.219 11183 11246 I jxcore-log: 
,03-29 16:23:24.219 11183 11246 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.219 11183 11246 I jxcore-log: 
03-29 16:23:24.219 11183 11246 I jxcore-log: DEBUG createNativeListener: mux close
,03-29 16:23:24.219 11183 11246 I jxcore-log: 
03-29 16:23:24.219 11183 11246 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.219 11183 11246 I jxcore-log: 
,03-29 16:23:24.224 11183 11246 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.224 11183 11246 I jxcore-log: 
,03-29 16:23:24.224 11183 11246 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.224 11183 11246 I jxcore-log: 
03-29 16:23:24.224 11183 11246 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.224 11183 11246 I jxcore-log: 
,03-29 16:23:24.224 11183 11246 I jxcore-log: DEBUG createNativeListener: mux close
03-29 16:23:24.224 11183 11246 I jxcore-log: 
,03-29 16:23:24.224 11183 11246 I jxcore-log: ok 28 native server is nulled out
03-29 16:23:24.224 11183 11246 I jxcore-log: 
,03-29 16:23:24.229 11183 11246 I jxcore-log: ok 29 native server should be closed
03-29 16:23:24.229 11183 11246 I jxcore-log: 
03-29 16:23:24.229 11183 11246 I jxcore-log: ok 30 incoming has been removed
03-29 16:23:24.229 11183 11246 I jxcore-log: 
03-29 16:23:24.229 11183 11246 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 16:23:24.229 11183 11246 I jxcore-log: 
,03-29 16:23:24.229 11183 11246 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 16:23:24.229 11183 11246 I jxcore-log: 
03-29 16:23:24.229 11183 11246 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 16:23:24.229 11183 11246 I jxcore-log: 
03-29 16:23:24.229 11183 11246 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 16:23:24.229 11183 11246 I jxcore-log: 
,03-29 16:23:24.229 11183 11246 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 16:23:24.229 11183 11246 I jxcore-log: 
03-29 16:23:24.229 11183 11246 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 16:23:24.229 11183 11246 I jxcore-log: 
03-29 16:23:24.229 11183 11246 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 16:23:24.229 11183 11246 I jxcore-log: 
,03-29 16:23:24.229 11183 11246 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 16:23:24.229 11183 11246 I jxcore-log: 
03-29 16:23:24.229 11183 11246 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 16:23:24.229 11183 11246 I jxcore-log: 
03-29 16:23:24.229 11183 11246 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 16:23:24.229 11183 11246 I jxcore-log: 
,03-29 16:23:24.314 11183 11246 I jxcore-log: # teardown
03-29 16:23:24.314 11183 11246 I jxcore-log: 
,03-29 16:23:24.469 11183 11246 I jxcore-log: # setup
03-29 16:23:24.469 11183 11246 I jxcore-log: 
,03-29 16:23:24.634 11183 11246 I jxcore-log: # 10. native server - simulate mux failure, make sure everything is cleaned up
03-29 16:23:24.634 11183 11246 I jxcore-log: 
,03-29 16:23:24.869 11183 11246 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 16:23:24.869 11183 11246 I jxcore-log: 
,03-29 16:23:24.874 11183 11246 I jxcore-log: DEBUG createNativeListener: listening 49590
03-29 16:23:24.874 11183 11246 I jxcore-log: 
,03-29 16:23:24.884 11183 11246 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 16:23:24.884 11183 11246 I jxcore-log: 
,03-29 16:23:24.889 11183 11246 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 16:23:24.889 11183 11246 I jxcore-log: 
,03-29 16:23:24.894 11183 11246 I jxcore-log: DEBUG createNativeListener: new mux
03-29 16:23:24.894 11183 11246 I jxcore-log: 
,03-29 16:23:24.904 11183 11246 I jxcore-log: ok 31 we should not have gotten an error
03-29 16:23:24.904 11183 11246 I jxcore-log: 
,03-29 16:23:24.909 11183 11246 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:24.909 11183 11246 I jxcore-log: 
,03-29 16:23:24.914 11183 11246 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:24.914 11183 11246 I jxcore-log: 
,03-29 16:23:24.924 11183 11246 I jxcore-log: ok 32 Buffers are identical
03-29 16:23:24.924 11183 11246 I jxcore-log: 
,03-29 16:23:24.924 11183 11246 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.924 11183 11246 I jxcore-log: 
,03-29 16:23:24.929 11183 11246 I jxcore-log: DEBUG createNativeListener: mux close
03-29 16:23:24.929 11183 11246 I jxcore-log: 
,03-29 16:23:24.944 11183 11246 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 16:23:24.944 11183 11246 I jxcore-log: 
,03-29 16:23:24.944 11183 11246 I jxcore-log: ok 33 server should be fine
03-29 16:23:24.944 11183 11246 I jxcore-log: 
,03-29 16:23:24.944 11183 11246 I jxcore-log: ok 34 server should be open
03-29 16:23:24.944 11183 11246 I jxcore-log: 
,03-29 16:23:24.944 11183 11246 I jxcore-log: ok 35 incoming has been removed
03-29 16:23:24.944 11183 11246 I jxcore-log: 
,03-29 16:23:24.944 11183 11246 I jxcore-log: ok 36 The mux object should be closed
03-29 16:23:24.944 11183 11246 I jxcore-log: 
,03-29 16:23:24.949 11183 11246 I jxcore-log: ok 37 The mux stream should be closed
03-29 16:23:24.949 11183 11246 I jxcore-log: 
,03-29 16:23:24.954 11183 11246 I jxcore-log: # teardown
03-29 16:23:24.954 11183 11246 I jxcore-log: 
,03-29 16:23:25.019 11183 11246 I jxcore-log: # setup
03-29 16:23:25.019 11183 11246 I jxcore-log: 
,03-29 16:23:25.189 11183 11246 I jxcore-log: # 11. native server - timing out the incoming connection cleans everything up
03-29 16:23:25.189 11183 11246 I jxcore-log: 
,03-29 16:23:25.369 11183 11246 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 16:23:25.369 11183 11246 I jxcore-log: 
,03-29 16:23:25.379 11183 11246 I jxcore-log: DEBUG createNativeListener: listening 55515
03-29 16:23:25.379 11183 11246 I jxcore-log: 
,03-29 16:23:25.389 11183 11246 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 16:23:25.389 11183 11246 I jxcore-log: 
,03-29 16:23:25.389 11183 11246 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 16:23:25.389 11183 11246 I jxcore-log: 
,03-29 16:23:25.394 11183 11246 I jxcore-log: DEBUG createNativeListener: new mux
03-29 16:23:25.394 11183 11246 I jxcore-log: 
,03-29 16:23:25.404 11183 11246 I jxcore-log: ok 38 we should not have gotten an error
03-29 16:23:25.404 11183 11246 I jxcore-log: 
,03-29 16:23:25.409 11183 11246 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:25.409 11183 11246 I jxcore-log: 
,03-29 16:23:25.414 11183 11246 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:25.414 11183 11246 I jxcore-log: 
,03-29 16:23:25.419 11183 11246 I jxcore-log: ok 39 Buffers are identical
03-29 16:23:25.419 11183 11246 I jxcore-log: 
,03-29 16:23:25.429 11183 11246 I jxcore-log: DEBUG createNativeListener: incoming socket timeout
03-29 16:23:25.429 11183 11246 I jxcore-log: 
,03-29 16:23:25.429 11183 11246 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:25.429 11183 11246 I jxcore-log: 
,03-29 16:23:25.434 11183 11246 I jxcore-log: DEBUG createNativeListener: mux close
03-29 16:23:25.434 11183 11246 I jxcore-log: 
,03-29 16:23:25.439 11183 11246 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 16:23:25.439 11183 11246 I jxcore-log: 
,03-29 16:23:25.444 11183 11246 I jxcore-log: ok 40 server should be fine
03-29 16:23:25.444 11183 11246 I jxcore-log: 
,03-29 16:23:25.444 11183 11246 I jxcore-log: ok 41 server should be open
03-29 16:23:25.444 11183 11246 I jxcore-log: 
,03-29 16:23:25.444 11183 11246 I jxcore-log: ok 42 incoming has been removed
03-29 16:23:25.444 11183 11246 I jxcore-log: 
,03-29 16:23:25.444 11183 11246 I jxcore-log: ok 43 The mux object should be closed
03-29 16:23:25.444 11183 11246 I jxcore-log: 
,03-29 16:23:25.449 11183 11246 I jxcore-log: ok 44 The mux stream should be closed
03-29 16:23:25.449 11183 11246 I jxcore-log: 
,03-29 16:23:25.459 11183 11246 I jxcore-log: # teardown
03-29 16:23:25.459 11183 11246 I jxcore-log: 
,03-29 16:23:25.569 11183 11246 I jxcore-log: # setup
03-29 16:23:25.569 11183 11246 I jxcore-log: 
,03-29 16:23:25.794 11183 11246 I jxcore-log: # 12. closeAll can close even when connections open
03-29 16:23:25.794 11183 11246 I jxcore-log: 
,03-29 16:23:25.994 11183 11246 I jxcore-log: ok 45 not possible to connect to the server anymore
03-29 16:23:25.994 11183 11246 I jxcore-log: 
,03-29 16:23:26.004 11183 11246 I jxcore-log: # teardown
03-29 16:23:26.004 11183 11246 I jxcore-log: 
,03-29 16:23:26.134 11183 11246 I jxcore-log: # setup
03-29 16:23:26.134 11183 11246 I jxcore-log: 
,03-29 16:23:26.429 11183 11246 I jxcore-log: # 13. closeAll with promise
03-29 16:23:26.429 11183 11246 I jxcore-log: 
,03-29 16:23:26.669 11183 11246 I jxcore-log: ok 46 not possible to connect to the server anymore
03-29 16:23:26.669 11183 11246 I jxcore-log: 
,03-29 16:23:26.679 11183 11246 I jxcore-log: # teardown
03-29 16:23:26.679 11183 11246 I jxcore-log: 
,03-29 16:23:26.879 11183 11246 I jxcore-log: # setup
03-29 16:23:26.879 11183 11246 I jxcore-log: 
,03-29 16:23:27.414 11183 11246 I jxcore-log: # 14. closeAll properly throws when closing a non open server with eatNotRunning set to false
03-29 16:23:27.414 11183 11246 I jxcore-log: 
,03-29 16:23:27.624 11183 11246 I jxcore-log: ok 47 Got the right error
03-29 16:23:27.624 11183 11246 I jxcore-log: 
,03-29 16:23:27.629 11183 11246 I jxcore-log: # teardown
03-29 16:23:27.629 11183 11246 I jxcore-log: 
,03-29 16:23:27.829 11183 11246 I jxcore-log: # setup
03-29 16:23:27.829 11183 11246 I jxcore-log: 
,03-29 16:23:27.974 11183 11246 I jxcore-log: # 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true
03-29 16:23:27.974 11183 11246 I jxcore-log: 
,03-29 16:23:28.099 11183 11246 I jxcore-log: # teardown
03-29 16:23:28.099 11183 11246 I jxcore-log: 
,03-29 16:23:28.214 11183 11246 I jxcore-log: # setup
03-29 16:23:28.214 11183 11246 I jxcore-log: 
,03-29 16:23:28.329 11183 11246 I jxcore-log: # 16. multiplex can send data
03-29 16:23:28.329 11183 11246 I jxcore-log: 
,03-29 16:23:28.524 11183 11246 I jxcore-log: ok 48 String should be length:200
03-29 16:23:28.524 11183 11246 I jxcore-log: 
,03-29 16:23:28.539 11183 11246 I jxcore-log: # teardown
03-29 16:23:28.539 11183 11246 I jxcore-log: 
,03-29 16:23:28.619 11183 11246 I jxcore-log: # setup
03-29 16:23:28.619 11183 11246 I jxcore-log: 
,03-29 16:23:28.779 11183 11246 I jxcore-log: # 17. enqueue and run in order
03-29 16:23:28.779 11183 11246 I jxcore-log: 
,03-29 16:23:29.119 11183 11246 I jxcore-log: ok 49 firstPromise setTimeout
03-29 16:23:29.119 11183 11246 I jxcore-log: 
,03-29 16:23:29.129 11183 11246 I jxcore-log: ok 50 firstPromise result
03-29 16:23:29.129 11183 11246 I jxcore-log: 
,03-29 16:23:29.134 11183 11246 I jxcore-log: ok 51 firstPromise testValue,
03-29 16:23:29.134 11183 11246 I jxcore-log: 
,03-29 16:23:29.249 11183 11246 I jxcore-log: ok 52 secondPromise setTimeout
03-29 16:23:29.249 11183 11246 I jxcore-log: 
,03-29 16:23:29.259 11183 11246 I jxcore-log: ok 53 secondPromise result
03-29 16:23:29.259 11183 11246 I jxcore-log: 
,03-29 16:23:29.264 11183 11246 I jxcore-log: ok 54 secondPromise testValue
03-29 16:23:29.264 11183 11246 I jxcore-log: 
,03-29 16:23:29.269 11183 11246 I jxcore-log: ok 55 thirdPromise in promise
03-29 16:23:29.269 11183 11246 I jxcore-log: 
,03-29 16:23:29.274 11183 11246 I jxcore-log: ok 56 thirdPromise result
03-29 16:23:29.274 11183 11246 I jxcore-log: 
,03-29 16:23:29.279 11183 11246 I jxcore-log: ok 57 thirdPromise testValue
03-29 16:23:29.279 11183 11246 I jxcore-log: 
,03-29 16:23:29.284 11183 11246 I jxcore-log: # teardown
03-29 16:23:29.284 11183 11246 I jxcore-log: 
,03-29 16:23:29.459 11183 11246 I jxcore-log: # setup
03-29 16:23:29.459 11183 11246 I jxcore-log: 
,03-29 16:23:30.039  3452  4028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-29 16:23:30.039  3452  4028 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-29 16:23:30.039  3452  4028 D BatteryService: online:4, current avg:41, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:37
,03-29 16:23:30.039  3452  3452 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-29 16:23:30.039  3452  4028 D BatteryService: stay LED for fully charged
,03-29 16:23:30.044  3452  3452 I MotionRecognitionService: Plugged
03-29 16:23:30.044  3452  3452 D MotionRecognitionService:   cableConnection= 1,
03-29 16:23:30.044  3452  3452 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-29 16:23:30.044  3452  3452 D MotionRecognitionService: skip setTransmitPower. 
,03-29 16:23:30.054  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-29 16:23:30.054  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-29 16:23:30.054  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-29 16:23:30.069  5848  5848 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-29 16:23:30.069  5848  5945 D HeadsetStateMachine: Disconnected process message: 10
,03-29 16:23:30.079 11183 11246 I jxcore-log: # 18. enqueueAtTop and run backwards
03-29 16:23:30.079 11183 11246 I jxcore-log: 
,03-29 16:23:30.079  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-29 16:23:30.079  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-29 16:23:30.079  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-29 16:23:30.079  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-29 16:23:30.274 11183 11246 I jxcore-log: ok 58 thirdPromise - first to run
03-29 16:23:30.274 11183 11246 I jxcore-log: 
,03-29 16:23:30.279 11183 11246 I jxcore-log: ok 59 thirdPromise - in resolve
03-29 16:23:30.279 11183 11246 I jxcore-log: 
,03-29 16:23:30.279 11183 11246 I jxcore-log: ok 60 secondPromise - second to run
03-29 16:23:30.279 11183 11246 I jxcore-log: 
,03-29 16:23:30.284 11183 11246 I jxcore-log: ok 61 secondPromise - in catch
03-29 16:23:30.284 11183 11246 I jxcore-log: 
,03-29 16:23:30.289 11183 11246 I jxcore-log: ok 62 firstPromise - third to run
03-29 16:23:30.289 11183 11246 I jxcore-log: 
,03-29 16:23:30.289 11183 11246 I jxcore-log: ok 63 firstPromise - in then
03-29 16:23:30.289 11183 11246 I jxcore-log: 
,03-29 16:23:30.289 11183 11246 I jxcore-log: ok 64 testing promises
03-29 16:23:30.289 11183 11246 I jxcore-log: 
,03-29 16:23:30.294 11183 11246 I jxcore-log: # teardown
03-29 16:23:30.294 11183 11246 I jxcore-log: 
,03-29 16:23:30.639 11183 11246 I jxcore-log: # setup
03-29 16:23:30.639 11183 11246 I jxcore-log: 
,03-29 16:23:30.769 11183 11246 I jxcore-log: # 19. mix enqueue and enqueueAtTop
03-29 16:23:30.769 11183 11246 I jxcore-log: 
,03-29 16:23:30.819  3452  6034 D SSRM:n  : SIOP:: AP = 280, PST = 285 (W:12), CUR = 41, LCD = 0
,03-29 16:23:30.889 11183 11246 I jxcore-log: ok 65 fourth
03-29 16:23:30.889 11183 11246 I jxcore-log: 
,03-29 16:23:30.889 11183 11246 I jxcore-log: ok 66 fourth
03-29 16:23:30.889 11183 11246 I jxcore-log: 
,03-29 16:23:30.894 11183 11246 I jxcore-log: ok 67 second
03-29 16:23:30.894 11183 11246 I jxcore-log: 
,03-29 16:23:30.899 11183 11246 I jxcore-log: ok 68 secondPromise - in then
03-29 16:23:30.899 11183 11246 I jxcore-log: 
,03-29 16:23:31.004 11183 11246 I jxcore-log: ok 69 first
03-29 16:23:31.004 11183 11246 I jxcore-log: 
,03-29 16:23:31.004 11183 11246 I jxcore-log: ok 70 firstPromise - in catch
03-29 16:23:31.004 11183 11246 I jxcore-log: 
,03-29 16:23:31.004 11183 11246 I jxcore-log: ok 71 third
03-29 16:23:31.004 11183 11246 I jxcore-log: 
,03-29 16:23:31.004 11183 11246 I jxcore-log: ok 72 thirdPromise - in then
03-29 16:23:31.004 11183 11246 I jxcore-log: 
,03-29 16:23:31.009 11183 11246 I jxcore-log: ok 73 testingPromises
03-29 16:23:31.009 11183 11246 I jxcore-log: 
,03-29 16:23:31.014 11183 11246 I jxcore-log: # teardown
03-29 16:23:31.014 11183 11246 I jxcore-log: 
,03-29 16:23:31.104 11183 11246 I jxcore-log: # setup
03-29 16:23:31.104 11183 11246 I jxcore-log: 
,03-29 16:23:31.234 11183 11246 I jxcore-log: # 20. queues handled independently
03-29 16:23:31.234 11183 11246 I jxcore-log: 
,03-29 16:23:31.424 11183 11246 I jxcore-log: ok 74 all short operations completed before the long resolves
03-29 16:23:31.424 11183 11246 I jxcore-log: 
,03-29 16:23:31.434 11183 11246 I jxcore-log: # teardown
03-29 16:23:31.434 11183 11246 I jxcore-log: 
,03-29 16:23:31.579 11183 11246 I jxcore-log: # setup
03-29 16:23:31.579 11183 11246 I jxcore-log: 
,03-29 16:23:31.714 11183 11246 I jxcore-log: # 21. basic
03-29 16:23:31.714 11183 11246 I jxcore-log: 
,03-29 16:23:31.949 11183 11246 I jxcore-log: ok 75 sane
03-29 16:23:31.949 11183 11246 I jxcore-log: 
,03-29 16:23:31.959 11183 11246 I jxcore-log: # teardown
03-29 16:23:31.959 11183 11246 I jxcore-log: 
,03-29 16:23:32.044 11183 11246 I jxcore-log: # setup
03-29 16:23:32.044 11183 11246 I jxcore-log: 
,03-29 16:23:32.204 11183 11246 I jxcore-log: # 22. another
03-29 16:23:32.204 11183 11246 I jxcore-log: 
,03-29 16:23:32.359 11183 11246 I jxcore-log: ok 76 sane
03-29 16:23:32.359 11183 11246 I jxcore-log: 
,03-29 16:23:32.369 11183 11246 I jxcore-log: # teardown
03-29 16:23:32.369 11183 11246 I jxcore-log: 
,03-29 16:23:32.509 11183 11246 I jxcore-log: # setup
03-29 16:23:32.509 11183 11246 I jxcore-log: 
,03-29 16:23:32.624 11183 11246 I jxcore-log: # 23. can pass data in setup
03-29 16:23:32.624 11183 11246 I jxcore-log: 
,03-29 16:23:32.744 11183 11246 I jxcore-log: ok 77 test participant has uuid
03-29 16:23:32.744 11183 11246 I jxcore-log: 
,03-29 16:23:32.749 11183 11246 I jxcore-log: ok 78 participant data matches
03-29 16:23:32.749 11183 11246 I jxcore-log: 
,03-29 16:23:32.749 11183 11246 I jxcore-log: ok 79 test participant has uuid
03-29 16:23:32.749 11183 11246 I jxcore-log: 
,03-29 16:23:32.749 11183 11246 I jxcore-log: ok 80 participant data matches
03-29 16:23:32.749 11183 11246 I jxcore-log: 
,03-29 16:23:32.754 11183 11246 I jxcore-log: ok 81 test participant has uuid
03-29 16:23:32.754 11183 11246 I jxcore-log: 
,03-29 16:23:32.754 11183 11246 I jxcore-log: ok 82 participant data matches
03-29 16:23:32.754 11183 11246 I jxcore-log: 
,03-29 16:23:32.759 11183 11246 I jxcore-log: ok 83 own UUID is found from the participants list
03-29 16:23:32.759 11183 11246 I jxcore-log: 
,03-29 16:23:32.764 11183 11246 I jxcore-log: # teardown
03-29 16:23:32.764 11183 11246 I jxcore-log: 
,03-29 16:23:32.864 11183 11246 I jxcore-log: # setup
03-29 16:23:32.864 11183 11246 I jxcore-log: 
,03-29 16:23:33.034 11183 11246 I jxcore-log: # 24. #startListeningForAdvertisements should fail if start not called
03-29 16:23:33.034 11183 11246 I jxcore-log: 
,03-29 16:23:33.259 11183 11246 I jxcore-log: ok 84 specific error should be returned
03-29 16:23:33.259 11183 11246 I jxcore-log: 
,03-29 16:23:33.264 11183 11246 I jxcore-log: # teardown
03-29 16:23:33.264 11183 11246 I jxcore-log: 
,03-29 16:23:33.454 11183 11246 I jxcore-log: ok 85 error should be null
03-29 16:23:33.454 11183 11246 I jxcore-log: 
,03-29 16:23:33.454 11183 11246 I jxcore-log: ok 86 error should be null
03-29 16:23:33.454 11183 11246 I jxcore-log: 
,03-29 16:23:33.459 11183 11246 I jxcore-log: # setup
03-29 16:23:33.459 11183 11246 I jxcore-log: 
,03-29 16:23:33.589 11183 11246 I jxcore-log: # 25. #startUpdateAdvertisingAndListening should fail if start not called
03-29 16:23:33.589 11183 11246 I jxcore-log: 
,03-29 16:23:33.689 11183 11246 I jxcore-log: ok 87 specific error should be returned
03-29 16:23:33.689 11183 11246 I jxcore-log: 
,03-29 16:23:33.694 11183 11246 I jxcore-log: # teardown
03-29 16:23:33.694 11183 11246 I jxcore-log: 
,03-29 16:23:33.789 11183 11246 I jxcore-log: ok 88 error should be null
03-29 16:23:33.789 11183 11246 I jxcore-log: 
,03-29 16:23:33.789 11183 11246 I jxcore-log: ok 89 error should be null
03-29 16:23:33.789 11183 11246 I jxcore-log: 
,03-29 16:23:33.794 11183 11246 I jxcore-log: # setup
03-29 16:23:33.794 11183 11246 I jxcore-log: 
,03-29 16:23:33.989 11183 11246 I jxcore-log: # 26. should be able to call #stopListeningForAdvertisements many times
03-29 16:23:33.989 11183 11246 I jxcore-log: 
,03-29 16:23:34.204 11183 11246 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 16:23:34.204 11183 11246 I jxcore-log: 
,03-29 16:23:34.204 11183 11246 I jxcore-log: DEBUG createNativeListener: listening 55843
03-29 16:23:34.204 11183 11246 I jxcore-log: 
,03-29 16:23:34.209 11183 11246 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-29 16:23:34.209 11183 11246 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-29 16:23:34.209 11183 11246 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 16:23:34.214 11183 11246 I jxcore-log: ok 90 error should be null
03-29 16:23:34.214 11183 11246 I jxcore-log: 
,03-29 16:23:34.214 11183 11246 I jxcore-log: ok 91 error should be null
03-29 16:23:34.214 11183 11246 I jxcore-log: 
03-29 16:23:34.214 11183 11246 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-29 16:23:34.214 11183 11246 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-29 16:23:34.214 11183 11246 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 16:23:34.219 11183 11246 I jxcore-log: ok 92 error should be null
03-29 16:23:34.219 11183 11246 I jxcore-log: 
03-29 16:23:34.219 11183 11246 I jxcore-log: ok 93 error should be null
03-29 16:23:34.219 11183 11246 I jxcore-log: 
,03-29 16:23:34.219 11183 11246 I jxcore-log: # teardown
03-29 16:23:34.219 11183 11246 I jxcore-log: 
,03-29 16:23:34.404 11183 11246 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-29 16:23:34.404 11183 11246 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 16:23:34.404 11183 11246 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 16:23:34.424 11183 11246 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-29 16:23:34.429 11183 11246 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-29 16:23:34.429 11183 11246 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 16:23:34.439 11183 11246 I jxcore-log: ok 94 error should be null
03-29 16:23:34.439 11183 11246 I jxcore-log: 
,03-29 16:23:34.444 11183 11246 I jxcore-log: ok 95 error should be null
03-29 16:23:34.444 11183 11246 I jxcore-log: 
,03-29 16:23:34.449 11183 11246 I jxcore-log: # setup
03-29 16:23:34.449 11183 11246 I jxcore-log: 
,03-29 16:23:34.569 11183 11246 I jxcore-log: # 27. should be able to call #startListeningForAdvertisements many times
03-29 16:23:34.569 11183 11246 I jxcore-log: 
,03-29 16:23:34.689 11183 11246 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 16:23:34.689 11183 11246 I jxcore-log: 
,03-29 16:23:34.694 11183 11246 I jxcore-log: DEBUG createNativeListener: listening 35815
03-29 16:23:34.694 11183 11246 I jxcore-log: 
,03-29 16:23:34.704 11183 11246 I io.jxcore.node.ConnectionHelper: start: Port number: 0, start advertisements: false
03-29 16:23:34.704 11183 11246 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-29 16:23:34.704 11183 11246 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,03-29 16:23:34.704 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
03-29 16:23:34.704 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-29 16:23:34.704 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-29 16:23:34.714 11183 11246 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-29 16:23:34.729 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-29 16:23:34.734 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-29 16:23:34.734 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-29 16:23:34.734 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-29 16:23:34.734 11183 11246 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-29 16:23:34.739  5848  5938 D BtGatt.GattService: registerClient() - UUID=53eec2d2-5260-4ab3-8458-2510963071b9
,03-29 16:23:34.784  5848  5919 D BtGatt.GattService: onClientRegistered() - UUID=53eec2d2-5260-4ab3-8458-2510963071b9, clientIf=6
,03-29 16:23:34.789 11183 11193 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-29 16:23:34.794  5848  8884 D BtGatt.GattService: start scan with filters
,03-29 16:23:34.819  5848  8884 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 69
,03-29 16:23:34.839  5848  5944 D BtGatt.ScanManager: handling starting scan
03-29 16:23:34.839  5848  5944 D BtGatt.ScanManager: isFilteringSupported
03-29 16:23:34.839  5848  5944 D BluetoothAdapter: setting StandAloneBleMode
03-29 16:23:34.839  5848  5944 D BtGatt.ScanManager: isFilteringSupported
03-29 16:23:34.839  5848  5944 D BluetoothAdapter: setting StandAloneBleMode
03-29 16:23:34.839  5848  5944 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c37c702
,03-29 16:23:34.844 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-29 16:23:34.844 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-29 16:23:34.844 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-29 16:23:34.844 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-29 16:23:34.844 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 16:23:34.844 11183 11183 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 16:23:34.849 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-29 16:23:34.849 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-29 16:23:34.849 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-29 16:23:34.859 11183 11183 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-29 16:23:34.859 11183 11183 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-29 16:23:34.864 11183 11183 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false,
03-29 16:23:34.864 11183 11246 I io.jxcore.node.ConnectionHelper: start: OK
,03-29 16:23:34.864  5848  5919 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1,
03-29 16:23:34.864  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:23:34.869  5848  5944 D BtGatt.ScanManager: allow scan with filters
03-29 16:23:34.869  5848  5944 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,03-29 16:23:34.869  5848  5944 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
03-29 16:23:34.869  5848  5919 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-29 16:23:34.869  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 16:23:34.874  5848  5944 D BtGatt.ScanManager: Starting BLE batch scan,
,03-29 16:23:34.879  5848  5944 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-29 16:23:34.879  5848  5919 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-29 16:23:34.879  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 16:23:34.884  5848  5919 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-29 16:23:34.884  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 16:23:34.894 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 16:23:34.894 11183 11246 I jxcore-log: 
,03-29 16:23:34.894 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 16:23:34.894 11183 11246 I jxcore-log: 
,03-29 16:23:34.899 11183 11246 I jxcore-log: ok 96 error should be null
03-29 16:23:34.899 11183 11246 I jxcore-log: 
,03-29 16:23:34.899 11183 11246 I jxcore-log: ok 97 error should be null
03-29 16:23:34.899 11183 11246 I jxcore-log: 
,03-29 16:23:34.904 11183 11246 I io.jxcore.node.ConnectionHelper: start: Port number: 0, start advertisements: false
,03-29 16:23:34.904 11183 11246 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-29 16:23:34.909 11183 11246 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,03-29 16:23:34.909 11183 11246 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 16:23:34.909 11183 11246 I io.jxcore.node.ConnectionHelper: start: OK
,03-29 16:23:34.914 11183 11246 I jxcore-log: ok 98 error should be null
03-29 16:23:34.914 11183 11246 I jxcore-log: 
,03-29 16:23:34.914 11183 11246 I jxcore-log: ok 99 error should be null
03-29 16:23:34.914 11183 11246 I jxcore-log: 
,03-29 16:23:34.919 11183 11246 I jxcore-log: # teardown
03-29 16:23:34.919 11183 11246 I jxcore-log: 
,03-29 16:23:35.084 11183 11246 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-29 16:23:35.089 11183 11246 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,03-29 16:23:35.089 11183 11246 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,03-29 16:23:35.089 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-29 16:23:35.089 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-29 16:23:35.089 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-29 16:23:35.089 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-29 16:23:35.094 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-29 16:23:35.094 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-29 16:23:35.099  5848  5857 D BtGatt.GattService: stopScan() - queue size =1
,03-29 16:23:35.099  5848  5944 D BtGatt.ScanManager: filter size is 1
03-29 16:23:35.099  5848  5944 D BtGatt.ScanManager: delete FilterIndex - 3
03-29 16:23:35.099  5848  5919 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-29 16:23:35.099  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 16:23:35.104  5848  5944 D BtGatt.ScanManager: stopping BLe Batch
,03-29 16:23:35.104  5848  5919 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-29 16:23:35.104  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:23:35.104  5848  5938 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-29 16:23:35.109  5848  5944 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-29 16:23:35.109 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-29 16:23:35.109 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED,
03-29 16:23:35.109  5848  5919 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-29 16:23:35.109  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 16:23:35.114 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,03-29 16:23:35.114 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-29 16:23:35.114 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,03-29 16:23:35.114 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-29 16:23:35.119 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-29 16:23:35.119 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped,
03-29 16:23:35.119 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-29 16:23:35.124 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
03-29 16:23:35.124 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-29 16:23:35.124 11183 11183 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
03-29 16:23:35.124 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-29 16:23:35.124 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-29 16:23:35.129 11183 11183 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-29 16:23:35.139 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
,03-29 16:23:35.139 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
03-29 16:23:35.139 11183 11183 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-29 16:23:35.144 11183 11183 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false,
,03-29 16:23:35.144 11183 11183 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-29 16:23:35.144 11183 11183 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-29 16:23:35.149 11183 11183 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-29 16:23:35.149 11183 11246 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-29 16:23:35.149 11183 11246 I jxcore-log: 
,03-29 16:23:35.154 11183 11246 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-29 16:23:35.154 11183 11246 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-29 16:23:35.154 11183 11246 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 16:23:35.154 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 16:23:35.154 11183 11246 I jxcore-log: 
,03-29 16:23:35.159 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 16:23:35.159 11183 11246 I jxcore-log: 
,03-29 16:23:35.164 11183 11246 I jxcore-log: ok 100 error should be null
03-29 16:23:35.164 11183 11246 I jxcore-log: 
,03-29 16:23:35.164 11183 11246 I jxcore-log: ok 101 error should be null
03-29 16:23:35.164 11183 11246 I jxcore-log: 
,03-29 16:23:35.174 11183 11246 I jxcore-log: # setup
03-29 16:23:35.174 11183 11246 I jxcore-log: 
,03-29 16:23:35.319 11183 11246 I jxcore-log: # 28. should be able to call #startUpdateAdvertisingAndListening many times
03-29 16:23:35.319 11183 11246 I jxcore-log: 
,03-29 16:23:35.489 11183 11246 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 16:23:35.489 11183 11246 I jxcore-log: 
,03-29 16:23:35.494 11183 11246 I jxcore-log: DEBUG createNativeListener: listening 54870
03-29 16:23:35.494 11183 11246 I jxcore-log: 
,03-29 16:23:35.514 11183 11246 I io.jxcore.node.ConnectionHelper: start: Port number: 54870, start advertisements: true
03-29 16:23:35.514 11183 11246 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-29 16:23:35.514 11183 11246 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-29 16:23:35.514 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-29 16:23:35.519 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-29 16:23:35.519 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-29 16:23:35.519 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-29 16:23:35.519 11183 11246 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-29 16:23:35.524  5848  5860 D BtGatt.GattService: registerClient() - UUID=7e6843c3-53ea-437e-94a6-89e93a2833f4
,03-29 16:23:35.564  5848  5919 D BtGatt.GattService: onClientRegistered() - UUID=7e6843c3-53ea-437e-94a6-89e93a2833f4, clientIf=6
,03-29 16:23:35.564 11183 11193 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-29 16:23:35.564  5848  8884 D BtGatt.GattService: start scan with filters
,03-29 16:23:35.589  5848  8884 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 70
,03-29 16:23:35.589 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-29 16:23:35.594 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-29 16:23:35.594 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-29 16:23:35.594 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-29 16:23:35.594 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 16:23:35.594  5848  5944 D BtGatt.ScanManager: handling starting scan
03-29 16:23:35.594  5848  5944 D BtGatt.ScanManager: isFilteringSupported
,03-29 16:23:35.594 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-29 16:23:35.594  5848  5944 D BluetoothAdapter: setting StandAloneBleMode
03-29 16:23:35.594 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
,03-29 16:23:35.594 11183 11183 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 16:23:35.594 11183 11246 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-29 16:23:35.594 11183 11246 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 16:23:35.594 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 16:23:35.594 11183 11246 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-29 16:23:35.604  5848  5919 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-29 16:23:35.604  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:23:35.604  5848  5944 D BtGatt.ScanManager: allow scan with filters
03-29 16:23:35.604  5848  5944 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-29 16:23:35.604  5848  5944 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,03-29 16:23:35.609  5848  5919 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,03-29 16:23:35.609  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:23:35.609  5848  5944 D BtGatt.ScanManager: Starting BLE batch scan
03-29 16:23:35.609  5848  5944 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-29 16:23:35.609  5848  8884 D BtGatt.GattService: registerClient() - UUID=7d765b5b-e412-4324-ab6d-d50cdc490aaf
,03-29 16:23:35.614  5848  5919 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-29 16:23:35.614  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 16:23:35.614  5848  5919 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-29 16:23:35.614  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 16:23:35.654  5848  5919 D BtGatt.GattService: onClientRegistered() - UUID=7d765b5b-e412-4324-ab6d-d50cdc490aaf, clientIf=7
,03-29 16:23:35.654 11183 11195 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-29 16:23:35.674  5848  5857 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 56
,03-29 16:23:35.679  5848  5941 D BtGatt.AdvertiseManager: message : 0
,03-29 16:23:35.684  5848  5941 D BtGatt.AdvertiseManager: number of adv instance running0
03-29 16:23:35.684  5848  5941 D BtGatt.AdvertiseManager: size of list is =0
,03-29 16:23:35.684  5848  5941 D BtGatt.AdvertiseManager: starting advertising
03-29 16:23:35.684  5848  5941 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-29 16:23:35.689  5848  5919 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-29 16:23:35.694  5848  5941 D BtGatt.AdvertiseManager: starting multi advertising
,03-29 16:23:35.694  5848  5919 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-29 16:23:35.694  5848  5941 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,03-29 16:23:35.699  5848  5941 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,03-29 16:23:35.699 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-29 16:23:35.699 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-29 16:23:35.704 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-29 16:23:35.704 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-29 16:23:35.704 11183 11246 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,03-29 16:23:35.704 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,03-29 16:23:35.709 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...,
,03-29 16:23:35.709 11183 11246 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,03-29 16:23:35.709 11183 11246 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,03-29 16:23:35.709 11183 11246 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-29 16:23:35.714 11183 11183 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-29 16:23:35.714 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-29 16:23:35.714 11183 11183 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-29 16:23:35.714 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-29 16:23:35.714 11183 11183 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-29 16:23:35.714 11183 11183 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-29 16:23:35.714 11183 11183 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-29 16:23:35.714 11183 11183 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-29 16:23:35.714 11183 11183 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-29 16:23:35.714 11183 11183 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 16:23:35.714 11183 11183 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-29 16:23:35.714 11183 11183 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-29 16:23:35.714 11183 11246 I io.jxcore.node.ConnectionHelper: start: OK
03-29 16:23:35.724 11183 11565 D BluetoothSocket: bindListen(): myUserId = 0
03-29 16:23:35.724 11183 11565 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-29 16:23:35.729 11183 11565 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[114]}
03-29 16:23:35.729 11183 11565 D BluetoothSocket: bindListen(), new LocalSocket 
03-29 16:23:35.729 11183 11565 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-29 16:23:35.729 11183 11565 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2682fc85
03-29 16:23:35.729 11183 11565 D BluetoothSocket: channel: 6
03-29 16:23:35.729 11183 11565 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-29 16:23:35.744 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 16:23:35.744 11183 11246 I jxcore-log: 
03-29 16:23:35.749 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 16:23:35.749 11183 11246 I jxcore-log: 
03-29 16:23:35.749 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-29 16:23:35.749 11183 11246 I jxcore-log: 
03-29 16:23:35.749 11183 11246 I jxcore-log: ok 102 error should be null
03-29 16:23:35.749 11183 11246 I jxcore-log: 
,03-29 16:23:35.754 11183 11246 I jxcore-log: ok 103 error should be null
03-29 16:23:35.754 11183 11246 I jxcore-log: 
,03-29 16:23:35.759 11183 11246 I io.jxcore.node.ConnectionHelper: start: Port number: 54870, start advertisements: true
,03-29 16:23:35.759 11183 11246 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-29 16:23:35.759 11183 11246 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-29 16:23:35.759 11183 11246 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-29 16:23:35.759 11183 11246 I io.jxcore.node.ConnectionHelper: start: OK
,03-29 16:23:35.774 11183 11246 I jxcore-log: ok 104 error should be null
03-29 16:23:35.774 11183 11246 I jxcore-log: 
,03-29 16:23:35.774 11183 11246 I jxcore-log: ok 105 error should be null
03-29 16:23:35.774 11183 11246 I jxcore-log: 
,03-29 16:23:35.779 11183 11246 I jxcore-log: # teardown
03-29 16:23:35.779 11183 11246 I jxcore-log: 
,03-29 16:23:36.619  3452  3619 V AlarmManager: waitForAlarm result :4,
,03-29 16:23:36.644  5848  5848 D BtGatt.ScanManager: awakened up at time 242322
,03-29 16:23:36.649  5848  5944 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-29 16:23:36.659  5848  5919 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
03-29 16:23:36.659  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,03-29 16:23:36.659  5848  5919 D BtGatt.GattService: current time is 242337181027
,03-29 16:23:36.659  5848  5919 D BtGatt.GattService: Batch record : [116, 121, 15, 101, -55, 78, 1, -128, -76, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -25, 31, -61, -3, -4, 116, 1, -128, -61, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0],
,03-29 16:23:36.684  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
03-29 16:23:36.684  3726  3726 I PERF    : received broadcast android.intent.action.TIME_TICK
,03-29 16:23:36.684  3726  3726 D KeyguardUpdateMonitor: handleTimeUpdate
,03-29 16:23:36.689  5848  5919 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81],
03-29 16:23:36.689  5848  5919 D ScanRecord: parseFromBytes
,03-29 16:23:36.694  5848  5919 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97],
03-29 16:23:36.694  5848  5919 D ScanRecord: parseFromBytes
03-29 16:23:36.694  5848  5919 D BtGatt.GattService: result: ScanResult{mDevice=74:FC:FD:C3:1F:E7, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-61, mTimestampNanos=242187641652}
,03-29 16:23:36.694  5848  5919 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-29 16:23:36.694  5848  5919 D BtGatt.GattService: result: ScanResult{mDevice=4E:C9:65:0F:79:74, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-76, mTimestampNanos=242337641652}
,03-29 16:23:36.694  5848  5919 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-29 16:23:36.694 11183 11195 D ScanRecord: parseFromBytes
,03-29 16:23:36.694 11183 11195 D ScanRecord: parseFromBytes
,03-29 16:23:36.699 11183 11183 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:CF:C5:D9:E5:61], added - the peer count is 1
,03-29 16:23:36.699 11183 11183 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 2
03-29 16:23:36.704 11183 11183 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:CF:C5:D9:E5:61], Bluetooth address: F8:CF:C5:D9:E5:61, device name: , device address: 
03-29 16:23:36.704  3726  3726 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
03-29 16:23:36.704 11183 11183 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
,03-29 16:23:36.709 11183 11246 I jxcore-log: DEBUG createPeerListener: createPeerListener,
03-29 16:23:36.709 11183 11246 I jxcore-log: 
,03-29 16:23:36.709  3726  3726 D SecKeyguardClockView: HomeTimezone(): 1,
,03-29 16:23:36.714 11183 11246 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false
03-29 16:23:36.714 11183 11246 I jxcore-log: 
,03-29 16:23:36.719  3726  3726 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-29 16:23:36.719  3726  3726 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
03-29 16:23:36.719 11183 11246 I jxcore-log: DEBUG createPeerListener: createPeerListener,
03-29 16:23:36.719 11183 11246 I jxcore-log: 
,03-29 16:23:36.724 11183 11246 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false
03-29 16:23:36.724 11183 11246 I jxcore-log: 
,03-29 16:23:36.724  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,03-29 16:23:36.759  3726  3726 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-29 16:23:36.759  3726  3726 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-29 16:23:36.764  3726  3726 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-29 16:23:36.769  3726  3726 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-29 16:23:36.769  3726  3726 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-29 16:23:36.774  3726  3726 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-29 16:23:36.789  3726  3726 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-29 16:23:37.404 11183 11246 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-29 16:23:37.409 11183 11246 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
,03-29 16:23:37.409 11183 11246 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,03-29 16:23:37.409 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,03-29 16:23:37.409 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,03-29 16:23:37.409 11183 11246 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@20035de8, channel: 6, state: LISTENING
,03-29 16:23:37.414 11183 11246 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@20035de8, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2682fc85, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@317bdc01mSocket: android.net.LocalSocket@388b2aa6 impl:android.net.LocalSocketImpl@1ca3ece7 fd:FileDescriptor[114]
,03-29 16:23:37.414 11183 11246 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@388b2aa6 impl:android.net.LocalSocketImpl@1ca3ece7 fd:FileDescriptor[114]
,03-29 16:23:37.419 11183 11246 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-29 16:23:37.419 11183 11565 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-29 16:23:37.419 11183 11565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-29 16:23:37.419 11183 11565 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-29 16:23:37.419 11183 11183 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-29 16:23:37.424 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-29 16:23:37.424 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-29 16:23:37.424 11183 11183 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-29 16:23:37.424 11183 11183 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-29 16:23:37.424 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-29 16:23:37.424 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-29 16:23:37.424 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-29 16:23:37.424 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-29 16:23:37.429  5848  5860 D BtGatt.GattService: stopScan() - queue size =1
,03-29 16:23:37.429  5848  5944 D BtGatt.ScanManager: filter size is 1
03-29 16:23:37.429  5848  5944 D BtGatt.ScanManager: delete FilterIndex - 4
,03-29 16:23:37.429  5848  8884 D BtGatt.GattService: unregisterClient() - clientIf=6
03-29 16:23:37.429 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-29 16:23:37.429 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-29 16:23:37.429  5848  5919 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-29 16:23:37.429  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:23:37.429  5848  5944 D BtGatt.ScanManager: stopping BLe Batch
03-29 16:23:37.429 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,03-29 16:23:37.429 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
,03-29 16:23:37.429 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-29 16:23:37.429 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-29 16:23:37.434 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-29 16:23:37.434  5848  5919 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-29 16:23:37.434  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:23:37.434  5848  5944 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-29 16:23:37.434  5848  5941 D BtGatt.AdvertiseManager: message : 1
03-29 16:23:37.434  5848  5941 D BtGatt.AdvertiseManager: stop advertise for client 7
03-29 16:23:37.434  5848  5941 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-29 16:23:37.434  5848  5919 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
03-29 16:23:37.434  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:23:37.434  5848  5919 D BtGatt.GattService: current time is 243114908361
03-29 16:23:37.439  5848  5919 D BtGatt.GattService: Batch record : [-25, 31, -61, -3, -4, 116, 1, -128, -61, 6, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0, 116, 121, 15, 101, -55, 78, 1, -128, -76, 6, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-29 16:23:37.439  5848  5919 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-29 16:23:37.439  5848  5919 D ScanRecord: parseFromBytes
03-29 16:23:37.439  5848  5919 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-29 16:23:37.439  5848  5919 D ScanRecord: parseFromBytes
,03-29 16:23:37.439  5848  5941 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-29 16:23:37.439  5848  5919 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-29 16:23:37.439  5848  5919 D BtGatt.GattService: Client app is not null!
03-29 16:23:37.439  5848  5860 D BtGatt.GattService: unregisterClient() - clientIf=7
03-29 16:23:37.444 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-29 16:23:37.444 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-29 16:23:37.444 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-29 16:23:37.444 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-29 16:23:37.444 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-29 16:23:37.444 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-29 16:23:37.444 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-29 16:23:37.444 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-29 16:23:37.444 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-29 16:23:37.444 11183 11246 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-29 16:23:37.444 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-29 16:23:37.444 11183 11183 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 16:23:37.444 11183 11183 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 16:23:37.444 11183 11183 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-29 16:23:37.444 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-29 16:23:37.444 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-29 16:23:37.444 11183 11246 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-29 16:23:37.444 11183 11246 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-29 16:23:37.444 11183 11246 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-29 16:23:37.449 11183 11183 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-29 16:23:37.454 11183 11246 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-29 16:23:37.454 11183 11246 I jxcore-log: 
03-29 16:23:37.454 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-29 16:23:37.454 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-29 16:23:37.454 11183 11183 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-29 16:23:37.459 11183 11183 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-29 16:23:37.459 11183 11183 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-29 16:23:37.459 11183 11183 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-29 16:23:37.459 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-29 16:23:37.459 11183 11246 I jxcore-log: 
03-29 16:23:37.459 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 16:23:37.459 11183 11246 I jxcore-log: 
03-29 16:23:37.459 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 16:23:37.459 11183 11246 I jxcore-log: 
03-29 16:23:37.469 11183 11246 I jxcore-log: ok 106 error should be null
03-29 16:23:37.469 11183 11246 I jxcore-log: 
03-29 16:23:37.469 11183 11246 I jxcore-log: ok 107 error should be null
03-29 16:23:37.469 11183 11246 I jxcore-log: 
,03-29 16:23:37.474 11183 11246 I jxcore-log: # setup
03-29 16:23:37.474 11183 11246 I jxcore-log: 
,03-29 16:23:37.724 11183 11246 I jxcore-log: # 29. should be able to call #stopAdvertisingAndListening many times
03-29 16:23:37.724 11183 11246 I jxcore-log: 
,03-29 16:23:37.914 11183 11246 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 16:23:37.914 11183 11246 I jxcore-log: 
,03-29 16:23:37.919 11183 11246 I jxcore-log: DEBUG createNativeListener: listening 58517
03-29 16:23:37.919 11183 11246 I jxcore-log: 
,03-29 16:23:37.924 11183 11246 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-29 16:23:37.929 11183 11246 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-29 16:23:37.929 11183 11246 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 16:23:37.934 11183 11246 I jxcore-log: ok 108 error should be null
03-29 16:23:37.934 11183 11246 I jxcore-log: 
,03-29 16:23:37.934 11183 11246 I jxcore-log: ok 109 error should be null
03-29 16:23:37.934 11183 11246 I jxcore-log: 
,03-29 16:23:37.939 11183 11246 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-29 16:23:37.939 11183 11246 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-29 16:23:37.939 11183 11246 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 16:23:37.944 11183 11246 I jxcore-log: ok 110 error should be null
03-29 16:23:37.944 11183 11246 I jxcore-log: 
,03-29 16:23:37.944 11183 11246 I jxcore-log: ok 111 error should be null
03-29 16:23:37.944 11183 11246 I jxcore-log: 
,03-29 16:23:37.954 11183 11246 I jxcore-log: # teardown
03-29 16:23:37.954 11183 11246 I jxcore-log: 
,03-29 16:23:38.029 11183 11246 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-29 16:23:38.029 11183 11246 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 16:23:38.029 11183 11246 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 16:23:38.034 11183 11246 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-29 16:23:38.034 11183 11246 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-29 16:23:38.034 11183 11246 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 16:23:38.039 11183 11246 I jxcore-log: ok 112 error should be null
03-29 16:23:38.039 11183 11246 I jxcore-log: 
,03-29 16:23:38.039 11183 11246 I jxcore-log: ok 113 error should be null
03-29 16:23:38.039 11183 11246 I jxcore-log: 
,03-29 16:23:38.049 11183 11246 I jxcore-log: # setup
03-29 16:23:38.049 11183 11246 I jxcore-log: 
,03-29 16:23:38.174 11183 11246 I jxcore-log: # 30. #start should fail if called twice in a row
03-29 16:23:38.174 11183 11246 I jxcore-log: 
,03-29 16:23:38.334 11183 11246 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 16:23:38.334 11183 11246 I jxcore-log: 
,03-29 16:23:38.339 11183 11246 I jxcore-log: DEBUG createNativeListener: listening 50872
03-29 16:23:38.339 11183 11246 I jxcore-log: 
,03-29 16:23:38.344 11183 11246 I jxcore-log: ok 114 first call should succeed
03-29 16:23:38.344 11183 11246 I jxcore-log: 
,03-29 16:23:38.344 11183 11246 I jxcore-log: ok 115 first call should succeed
03-29 16:23:38.344 11183 11246 I jxcore-log: 
,03-29 16:23:38.349 11183 11246 I jxcore-log: ok 116 specific error should be returned
03-29 16:23:38.349 11183 11246 I jxcore-log: 
,03-29 16:23:38.354 11183 11246 I jxcore-log: # teardown
03-29 16:23:38.354 11183 11246 I jxcore-log: 
,03-29 16:23:38.499 11183 11246 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-29 16:23:38.499 11183 11246 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-29 16:23:38.499 11183 11246 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 16:23:38.504 11183 11246 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-29 16:23:38.509 11183 11246 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-29 16:23:38.509 11183 11246 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 16:23:38.519 11183 11246 I jxcore-log: ok 117 error should be null
03-29 16:23:38.519 11183 11246 I jxcore-log: 
,03-29 16:23:38.519 11183 11246 I jxcore-log: ok 118 error should be null
03-29 16:23:38.519 11183 11246 I jxcore-log: 
,03-29 16:23:38.524 11183 11246 I jxcore-log: # setup
03-29 16:23:38.524 11183 11246 I jxcore-log: 
,03-29 16:23:38.674 11183 11246 I jxcore-log: # 31. does not emit duplicate discoveryAdvertisingStateUpdate
03-29 16:23:38.674 11183 11246 I jxcore-log: 
,03-29 16:23:38.874 11183 11246 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 16:23:38.874 11183 11246 I jxcore-log: 
,03-29 16:23:38.879 11183 11246 I jxcore-log: DEBUG createNativeListener: listening 36320
03-29 16:23:38.879 11183 11246 I jxcore-log: 
,03-29 16:23:38.889 11183 11246 I io.jxcore.node.ConnectionHelper: start: Port number: 54870, start advertisements: false
,03-29 16:23:38.889 11183 11246 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-29 16:23:38.889 11183 11246 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-29 16:23:38.889 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-29 16:23:38.894 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-29 16:23:38.894 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-29 16:23:38.894 11183 11246 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-29 16:23:38.904  5848  5860 D BtGatt.GattService: registerClient() - UUID=8f7fbd91-b860-4caf-9264-9983975d2921
,03-29 16:23:38.944  5848  5919 D BtGatt.GattService: onClientRegistered() - UUID=8f7fbd91-b860-4caf-9264-9983975d2921, clientIf=6
,03-29 16:23:38.944 11183 11195 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-29 16:23:38.944  5848  8884 D BtGatt.GattService: start scan with filters
,03-29 16:23:38.954  5848  8884 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 71
,03-29 16:23:38.954 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-29 16:23:38.954 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-29 16:23:38.954 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-29 16:23:38.954  5848  5944 D BtGatt.ScanManager: handling starting scan
03-29 16:23:38.954 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-29 16:23:38.954  5848  5944 D BtGatt.ScanManager: isFilteringSupported
03-29 16:23:38.954 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 16:23:38.954  5848  5944 D BluetoothAdapter: setting StandAloneBleMode
03-29 16:23:38.954 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-29 16:23:38.954 11183 11183 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-29 16:23:38.959 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-29 16:23:38.959 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-29 16:23:38.959 11183 11246 I io.jxcore.node.ConnectionHelper: start: OK
03-29 16:23:38.959 11183 11183 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-29 16:23:38.959 11183 11183 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 16:23:38.959  5848  5919 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-29 16:23:38.959  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:23:38.959  5848  5944 D BtGatt.ScanManager: allow scan with filters
03-29 16:23:38.959 11183 11183 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-29 16:23:38.959  5848  5944 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-29 16:23:38.959  5848  5944 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
03-29 16:23:38.959  5848  5919 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-29 16:23:38.959  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:23:38.959  5848  5944 D BtGatt.ScanManager: Starting BLE batch scan
03-29 16:23:38.959  5848  5944 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-29 16:23:38.964  5848  5919 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-29 16:23:38.964  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 16:23:38.964  5848  5919 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1,
03-29 16:23:38.964  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:23:38.964 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 16:23:38.964 11183 11246 I jxcore-log: 
,03-29 16:23:38.964 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 16:23:38.964 11183 11246 I jxcore-log: 
,03-29 16:23:38.979 11183 11246 I io.jxcore.node.ConnectionHelper: start: Port number: 36320, start advertisements: true
,03-29 16:23:38.979 11183 11246 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-29 16:23:38.979 11183 11246 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-29 16:23:38.979 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-29 16:23:38.984 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-29 16:23:38.984 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
03-29 16:23:38.984 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-29 16:23:38.984 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-29 16:23:38.984 11183 11246 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-29 16:23:38.984 11183 11246 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-29 16:23:38.984 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 16:23:38.984 11183 11246 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-29 16:23:38.989  5848  5938 D BtGatt.GattService: registerClient() - UUID=244df624-f2fc-4fd3-867a-1db7f821cb81
,03-29 16:23:39.029  5848  5919 D BtGatt.GattService: onClientRegistered() - UUID=244df624-f2fc-4fd3-867a-1db7f821cb81, clientIf=7,
,03-29 16:23:39.029 11183 11193 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7,
,03-29 16:23:39.049  5848  5857 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 57
,03-29 16:23:39.049  5848  5941 D BtGatt.AdvertiseManager: message : 0
,03-29 16:23:39.049  5848  5941 D BtGatt.AdvertiseManager: number of adv instance running0
03-29 16:23:39.049  5848  5941 D BtGatt.AdvertiseManager: size of list is =0
,03-29 16:23:39.054  5848  5941 D BtGatt.AdvertiseManager: starting advertising
,03-29 16:23:39.054  5848  5941 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-29 16:23:39.059  5848  5919 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-29 16:23:39.064  5848  5941 D BtGatt.AdvertiseManager: starting multi advertising
,03-29 16:23:39.064  5848  5919 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-29 16:23:39.064  5848  5941 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,03-29 16:23:39.064  5848  5941 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,03-29 16:23:39.069 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-29 16:23:39.069 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-29 16:23:39.069 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-29 16:23:39.069 11183 11183 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING,
03-29 16:23:39.069 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-29 16:23:39.069 11183 11183 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-29 16:23:39.069 11183 11183 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
,03-29 16:23:39.074 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-29 16:23:39.074 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-29 16:23:39.074 11183 11183 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-29 16:23:39.074 11183 11246 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,03-29 16:23:39.074 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-29 16:23:39.074 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...,
03-29 16:23:39.074 11183 11246 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-29 16:23:39.074 11183 11246 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,03-29 16:23:39.074 11183 11246 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-29 16:23:39.079 11183 11183 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-29 16:23:39.079 11183 11183 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-29 16:23:39.079 11183 11183 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-29 16:23:39.079 11183 11246 I io.jxcore.node.ConnectionHelper: start: OK
,03-29 16:23:39.089 11183 11610 D BluetoothSocket: bindListen(): myUserId = 0
,03-29 16:23:39.089 11183 11610 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-29 16:23:39.089 11183 11610 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[115]}
,03-29 16:23:39.089 11183 11610 D BluetoothSocket: bindListen(), new LocalSocket 
,03-29 16:23:39.094 11183 11610 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,03-29 16:23:39.094 11183 11610 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1f387083
03-29 16:23:39.094 11183 11610 D BluetoothSocket: channel: 6
,03-29 16:23:39.094 11183 11610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-29 16:23:39.099 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-29 16:23:39.099 11183 11246 I jxcore-log: 
,03-29 16:23:39.104 11183 11246 I jxcore-log: ok 119 called only once
03-29 16:23:39.104 11183 11246 I jxcore-log: 
,03-29 16:23:39.104 11183 11246 I jxcore-log: ok 120 discovery state matches
03-29 16:23:39.104 11183 11246 I jxcore-log: 
,03-29 16:23:39.109 11183 11246 I jxcore-log: ok 121 advertising state matches
03-29 16:23:39.109 11183 11246 I jxcore-log: 
,03-29 16:23:39.119 11183 11246 I jxcore-log: # teardown
03-29 16:23:39.119 11183 11246 I jxcore-log: 
,03-29 16:23:39.384 11183 11246 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-29 16:23:39.384 11183 11246 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
,03-29 16:23:39.384 11183 11246 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,03-29 16:23:39.384 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-29 16:23:39.384 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,03-29 16:23:39.389 11183 11246 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@5a20200, channel: 6, state: LISTENING,
03-29 16:23:39.389 11183 11246 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@5a20200, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1f387083, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@e970a39mSocket: android.net.LocalSocket@1c82e87e impl:android.net.LocalSocketImpl@160791df fd:FileDescriptor[115]
,03-29 16:23:39.389 11183 11246 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1c82e87e impl:android.net.LocalSocketImpl@160791df fd:FileDescriptor[115],
,03-29 16:23:39.389 11183 11246 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-29 16:23:39.394 11183 11610 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close,
03-29 16:23:39.394 11183 11610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-29 16:23:39.394 11183 11610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,03-29 16:23:39.394 11183 11183 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-29 16:23:39.394 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-29 16:23:39.394 11183 11183 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-29 16:23:39.394 11183 11183 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-29 16:23:39.394 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-29 16:23:39.394 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-29 16:23:39.394 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-29 16:23:39.399 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-29 16:23:39.399 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-29 16:23:39.399  5848  8884 D BtGatt.GattService: stopScan() - queue size =1,
,03-29 16:23:39.399  5848  5944 D BtGatt.ScanManager: filter size is 1,
,03-29 16:23:39.399  5848  5944 D BtGatt.ScanManager: delete FilterIndex - 5,
,03-29 16:23:39.404  5848  5919 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16,
03-29 16:23:39.404  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:23:39.404  5848  5944 D BtGatt.ScanManager: stopping BLe Batch,
03-29 16:23:39.404  5848  5919 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0,
03-29 16:23:39.404  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,03-29 16:23:39.404  5848  5944 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6,
,03-29 16:23:39.409  5848  5919 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
,03-29 16:23:39.409  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
03-29 16:23:39.409  5848  5919 D BtGatt.GattService: current time is 245086264069,
,03-29 16:23:39.409  5848  5919 D BtGatt.GattService: Batch record : [92, -55, -80, 74, 71, 70, 1, -128, -76, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, 4, -31, 22, -121, 127, 105, 1, -128, -61, 7, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0]
,03-29 16:23:39.409  5848  5919 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-29 16:23:39.409  5848  5919 D ScanRecord: parseFromBytes,
,03-29 16:23:39.409  5848  5919 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-29 16:23:39.409  5848  5919 D ScanRecord: parseFromBytes
03-29 16:23:39.409  5848  5857 D BtGatt.GattService: unregisterClient() - clientIf=6
03-29 16:23:39.414 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-29 16:23:39.414 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-29 16:23:39.414 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-29 16:23:39.414 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-29 16:23:39.414 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING],
03-29 16:23:39.414 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-29 16:23:39.414 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-29 16:23:39.419  5848  5941 D BtGatt.AdvertiseManager: message : 1
03-29 16:23:39.419  5848  5941 D BtGatt.AdvertiseManager: stop advertise for client 7
,03-29 16:23:39.419  5848  5941 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-29 16:23:39.419  5848  5941 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-29 16:23:39.424  5848  5919 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-29 16:23:39.424  5848  5919 D BtGatt.GattService: Client app is not null!
03-29 16:23:39.424  5848  8884 D BtGatt.GattService: unregisterClient() - clientIf=7
03-29 16:23:39.424 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-29 16:23:39.424 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-29 16:23:39.424 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,03-29 16:23:39.424 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-29 16:23:39.424 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-29 16:23:39.424 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-29 16:23:39.424 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-29 16:23:39.424 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-29 16:23:39.429 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-29 16:23:39.429 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-29 16:23:39.429 11183 11183 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 16:23:39.429 11183 11183 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 16:23:39.429 11183 11183 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-29 16:23:39.429 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-29 16:23:39.429 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-29 16:23:39.434 11183 11183 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-29 16:23:39.439 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-29 16:23:39.439 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-29 16:23:39.439 11183 11183 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-29 16:23:39.444 11183 11246 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-29 16:23:39.444 11183 11246 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-29 16:23:39.444 11183 11246 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-29 16:23:39.449 11183 11246 I jxcore-log: INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
03-29 16:23:39.449 11183 11246 I jxcore-log: 
03-29 16:23:39.454 11183 11246 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-29 16:23:39.454 11183 11246 I jxcore-log: 
03-29 16:23:39.454 11183 11183 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-29 16:23:39.454 11183 11183 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-29 16:23:39.454 11183 11183 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-29 16:23:39.454 11183 11246 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-29 16:23:39.454 11183 11246 I jxcore-log: 
03-29 16:23:39.459 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-29 16:23:39.459 11183 11246 I jxcore-log: 
03-29 16:23:39.459 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 16:23:39.459 11183 11246 I jxcore-log: 
03-29 16:23:39.459 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 16:23:39.459 11183 11246 I jxcore-log: 
,03-29 16:23:39.464 11183 11246 I jxcore-log: ok 122 error should be null
03-29 16:23:39.464 11183 11246 I jxcore-log: 
,03-29 16:23:39.464 11183 11246 I jxcore-log: ok 123 error should be null
03-29 16:23:39.464 11183 11246 I jxcore-log: 
,03-29 16:23:39.474 11183 11246 I jxcore-log: # setup
03-29 16:23:39.474 11183 11246 I jxcore-log: 
,03-29 16:23:39.729 11183 11246 I jxcore-log: # 32. does not send duplicate availability changes
03-29 16:23:39.729 11183 11246 I jxcore-log: 
,03-29 16:23:39.844 11183 11246 I jxcore-log: ok 124 should be called once
03-29 16:23:39.844 11183 11246 I jxcore-log: 
,03-29 16:23:39.849 11183 11246 I jxcore-log: ok 125 should not have been called more than once
03-29 16:23:39.849 11183 11246 I jxcore-log: 
,03-29 16:23:39.859 11183 11246 I jxcore-log: # teardown
03-29 16:23:39.859 11183 11246 I jxcore-log: 
,03-29 16:23:39.894  3452  3572 W ProcessCpuTracker: Skipping unknown process pid 11622
,03-29 16:23:39.994 11183 11246 I jxcore-log: ok 126 error should be null
03-29 16:23:39.994 11183 11246 I jxcore-log: 
,03-29 16:23:39.994 11183 11246 I jxcore-log: ok 127 error should be null
03-29 16:23:39.994 11183 11246 I jxcore-log: 
,03-29 16:23:40.004 11183 11246 I jxcore-log: # setup
03-29 16:23:40.004 11183 11246 I jxcore-log: 
,03-29 16:23:40.104 11183 11246 I jxcore-log: # 33. can get the network status
03-29 16:23:40.104 11183 11246 I jxcore-log: 
,03-29 16:23:40.154  3452  4028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-29 16:23:40.154  3452  4028 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-29 16:23:40.154  3452  4028 D BatteryService: online:4, current avg:40, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:40
03-29 16:23:40.154  3452  4028 D BatteryService: stay LED for fully charged
,03-29 16:23:40.154  3452  3452 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-29 16:23:40.159  3452  3452 I MotionRecognitionService: Plugged
03-29 16:23:40.159  3452  3452 D MotionRecognitionService:   cableConnection= 1
03-29 16:23:40.159  3452  3452 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-29 16:23:40.159  3452  3452 D MotionRecognitionService: skip setTransmitPower. 
,03-29 16:23:40.164  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-29 16:23:40.164  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
03-29 16:23:40.164  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-29 16:23:40.179  5848  5848 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-29 16:23:40.179  5848  5945 D HeadsetStateMachine: Disconnected process message: 10
,03-29 16:23:40.189  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-29 16:23:40.189  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-29 16:23:40.189  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-29 16:23:40.189  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-29 16:23:40.214 11183 11246 I jxcore-log: ok 128 network status should have certain non-empty properties
03-29 16:23:40.214 11183 11246 I jxcore-log: 
,03-29 16:23:40.219 11183 11246 I jxcore-log: # teardown
03-29 16:23:40.219 11183 11246 I jxcore-log: 
,03-29 16:23:40.354 11183 11246 I jxcore-log: ok 129 error should be null
03-29 16:23:40.354 11183 11246 I jxcore-log: 
,03-29 16:23:40.354 11183 11246 I jxcore-log: ok 130 error should be null
03-29 16:23:40.354 11183 11246 I jxcore-log: 
,03-29 16:23:40.369 11183 11246 I jxcore-log: # setup
03-29 16:23:40.369 11183 11246 I jxcore-log: 
,03-29 16:23:40.464  3452  3585 I PowerManagerService: [PWL] Off : 180s ago
,03-29 16:23:40.509 11183 11246 I jxcore-log: # 34. wifi peer is marked unavailable if announcements stop
03-29 16:23:40.509 11183 11246 I jxcore-log: 
,03-29 16:23:40.629 11183 11246 I jxcore-log: ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
03-29 16:23:40.629 11183 11246 I jxcore-log: 
,03-29 16:23:40.664 11183 11246 I jxcore-log: ok 131 host address should match
03-29 16:23:40.664 11183 11246 I jxcore-log: 
,03-29 16:23:40.664 11183 11246 I jxcore-log: ok 132 port should match
03-29 16:23:40.664 11183 11246 I jxcore-log: 
,03-29 16:23:40.849  3452  6034 D SSRM:n  : SIOP:: AP = 280, PST = 285 (W:12), CUR = 40, LCD = 0
,03-29 16:23:42.159  3452  3619 V AlarmManager: waitForAlarm result :8
,03-29 16:23:42.649 11183 11246 I jxcore-log: ok 133 host address should be null
03-29 16:23:42.649 11183 11246 I jxcore-log: 
,03-29 16:23:42.654 11183 11246 I jxcore-log: ok 134 port should should be null
03-29 16:23:42.654 11183 11246 I jxcore-log: 
,03-29 16:23:42.684 11183 11246 I jxcore-log: # teardown
03-29 16:23:42.684 11183 11246 I jxcore-log: 
,03-29 16:23:42.839 11183 11246 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-29 16:23:42.839 11183 11246 I jxcore-log: 
,03-29 16:23:42.844 11183 11246 I jxcore-log: ok 135 error should be null
03-29 16:23:42.844 11183 11246 I jxcore-log: 
,03-29 16:23:42.849 11183 11246 I jxcore-log: ok 136 error should be null
03-29 16:23:42.849 11183 11246 I jxcore-log: 
,03-29 16:23:42.854 11183 11246 I jxcore-log: # setup
03-29 16:23:42.854 11183 11246 I jxcore-log: 
,03-29 16:23:42.934 11183 11246 I jxcore-log: # 35. Can call start/stopListeningForAdvertisements
03-29 16:23:42.934 11183 11246 I jxcore-log: 
,03-29 16:23:43.124 11183 11246 I io.jxcore.node.ConnectionHelper: start: Port number: 36320, start advertisements: false
,03-29 16:23:43.124 11183 11246 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-29 16:23:43.124 11183 11246 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,03-29 16:23:43.124 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-29 16:23:43.129 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-29 16:23:43.129 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-29 16:23:43.134 11183 11246 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-29 16:23:43.139  5848  5857 D BtGatt.GattService: registerClient() - UUID=5b6a45f0-5b58-4fd6-b859-ffee22419716
,03-29 16:23:43.184  5848  5919 D BtGatt.GattService: onClientRegistered() - UUID=5b6a45f0-5b58-4fd6-b859-ffee22419716, clientIf=6
03-29 16:23:43.184 11183 11193 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-29 16:23:43.189  5848  5860 D BtGatt.GattService: start scan with filters
,03-29 16:23:43.214  5848  5860 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 72
,03-29 16:23:43.214  5848  5944 D BtGatt.ScanManager: handling starting scan
03-29 16:23:43.214  5848  5944 D BtGatt.ScanManager: isFilteringSupported
03-29 16:23:43.214  5848  5944 D BluetoothAdapter: setting StandAloneBleMode
,03-29 16:23:43.224  5848  5919 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-29 16:23:43.224  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 16:23:43.224  5848  5944 D BtGatt.ScanManager: allow scan with filters
03-29 16:23:43.224  5848  5944 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-29 16:23:43.224  5848  5944 D BtGatt.ScanManager: set filter index= 6 for clientIf= 6
03-29 16:23:43.229  5848  5919 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-29 16:23:43.229  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 16:23:43.229  5848  5944 D BtGatt.ScanManager: Starting BLE batch scan
03-29 16:23:43.229  5848  5944 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-29 16:23:43.229  5848  5919 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0,
03-29 16:23:43.229  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:23:43.234  5848  5919 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-29 16:23:43.234  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 16:23:43.239 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
03-29 16:23:43.239 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-29 16:23:43.239 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-29 16:23:43.239 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-29 16:23:43.239 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,03-29 16:23:43.239 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-29 16:23:43.239 11183 11183 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 16:23:43.244 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-29 16:23:43.244 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-29 16:23:43.244 11183 11183 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-29 16:23:43.244 11183 11183 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 16:23:43.244 11183 11183 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-29 16:23:43.244 11183 11246 I io.jxcore.node.ConnectionHelper: start: OK
03-29 16:23:43.244 11183 11246 I jxcore-log: ok 137 Can call startListeningForAdvertisements without error,
03-29 16:23:43.244 11183 11246 I jxcore-log: 
03-29 16:23:43.249 11183 11246 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-29 16:23:43.249 11183 11246 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
03-29 16:23:43.249 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,03-29 16:23:43.249 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-29 16:23:43.254  5848  5857 D BtGatt.GattService: stopScan() - queue size =1,
03-29 16:23:43.254  5848  5944 D BtGatt.ScanManager: filter size is 1
,03-29 16:23:43.254  5848  5944 D BtGatt.ScanManager: delete FilterIndex - 6
03-29 16:23:43.254  5848  5919 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,03-29 16:23:43.254  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,03-29 16:23:43.254  5848  5944 D BtGatt.ScanManager: stopping BLe Batch
03-29 16:23:43.259  5848  5919 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0,
03-29 16:23:43.259  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,03-29 16:23:43.259  5848  5944 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6,
03-29 16:23:43.259  5848  5919 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0,
03-29 16:23:43.259  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,03-29 16:23:43.264  5848  5938 D BtGatt.GattService: unregisterClient() - clientIf=6
03-29 16:23:43.264 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-29 16:23:43.264 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED,
03-29 16:23:43.264 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-29 16:23:43.264 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-29 16:23:43.264 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED],
,03-29 16:23:43.264 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-29 16:23:43.269 11183 11183 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-29 16:23:43.269 11183 11183 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only,
03-29 16:23:43.269 11183 11183 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-29 16:23:43.274 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false},
03-29 16:23:43.274 11183 11246 I jxcore-log: 
,03-29 16:23:43.279 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 16:23:43.279 11183 11246 I jxcore-log: 
,03-29 16:23:43.279 11183 11246 I jxcore-log: ok 138 Can call stopListeningForAdvertisements without error
03-29 16:23:43.279 11183 11246 I jxcore-log: 
,03-29 16:23:43.284 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 16:23:43.284 11183 11246 I jxcore-log: 
,03-29 16:23:43.289 11183 11246 I jxcore-log: # teardown
03-29 16:23:43.289 11183 11246 I jxcore-log: 
,03-29 16:23:43.444 11183 11246 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements,
,03-29 16:23:43.454 11183 11246 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-29 16:23:43.454 11183 11246 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
,03-29 16:23:43.464 11183 11246 I jxcore-log: ok 139 Should be able to call stopListeningForAdvertisments in teardown
03-29 16:23:43.464 11183 11246 I jxcore-log: 
,03-29 16:23:43.464 11183 11246 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-29 16:23:43.464 11183 11246 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-29 16:23:43.469 11183 11246 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-29 16:23:43.469 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-29 16:23:43.469 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-29 16:23:43.469 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-29 16:23:43.469 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-29 16:23:43.469 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser,
,03-29 16:23:43.474 11183 11246 D BluetoothLeScanner: could not find callback wrapper,
03-29 16:23:43.474 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-29 16:23:43.474 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
,03-29 16:23:43.479 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,03-29 16:23:43.479 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-29 16:23:43.479 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
03-29 16:23:43.479 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-29 16:23:43.484 11183 11183 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
03-29 16:23:43.484 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-29 16:23:43.484 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-29 16:23:43.489 11183 11183 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-29 16:23:43.494 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
,03-29 16:23:43.499 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
03-29 16:23:43.499 11183 11183 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
,03-29 16:23:43.504 11183 11183 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-29 16:23:43.504 11183 11183 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
03-29 16:23:43.504 11183 11183 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-29 16:23:43.509 11183 11246 I jxcore-log: ok 140 Should be able to call stopAdvertisingAndListening in teardown
03-29 16:23:43.509 11183 11246 I jxcore-log: 
,03-29 16:23:43.514 11183 11246 I jxcore-log: # setup
03-29 16:23:43.514 11183 11246 I jxcore-log: 
,03-29 16:23:43.519 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 16:23:43.519 11183 11246 I jxcore-log: 
,03-29 16:23:43.614 11183 11246 I jxcore-log: # 36. Calling startListeningForAdvertisements twice is NOT an error
03-29 16:23:43.614 11183 11246 I jxcore-log: 
,03-29 16:23:43.864 11183 11246 I io.jxcore.node.ConnectionHelper: start: Port number: 36320, start advertisements: false
,03-29 16:23:43.864 11183 11246 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-29 16:23:43.864 11183 11246 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,03-29 16:23:43.864 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-29 16:23:43.869 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-29 16:23:43.874 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-29 16:23:43.874 11183 11246 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-29 16:23:43.879  5848  8884 D BtGatt.GattService: registerClient() - UUID=1d2a7113-24d0-432c-9ab5-ef5e9a12e0b1
,03-29 16:23:43.919  5848  5919 D BtGatt.GattService: onClientRegistered() - UUID=1d2a7113-24d0-432c-9ab5-ef5e9a12e0b1, clientIf=6
03-29 16:23:43.919 11183 11193 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-29 16:23:43.924  5848  5857 D BtGatt.GattService: start scan with filters
,03-29 16:23:43.954  5848  5857 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 73
,03-29 16:23:43.954  5848  5944 D BtGatt.ScanManager: handling starting scan
03-29 16:23:43.954  5848  5944 D BtGatt.ScanManager: isFilteringSupported
03-29 16:23:43.954  5848  5944 D BluetoothAdapter: setting StandAloneBleMode
,03-29 16:23:43.959  5848  5919 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-29 16:23:43.959  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 16:23:43.959  5848  5944 D BtGatt.ScanManager: allow scan with filters
03-29 16:23:43.959  5848  5944 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-29 16:23:43.959  5848  5944 D BtGatt.ScanManager: set filter index= 7 for clientIf= 6
03-29 16:23:43.964  5848  5919 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-29 16:23:43.964  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 16:23:43.964  5848  5944 D BtGatt.ScanManager: Starting BLE batch scan
03-29 16:23:43.964  5848  5944 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-29 16:23:43.969  5848  5919 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-29 16:23:43.969  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 16:23:43.969  5848  5919 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1,
03-29 16:23:43.969  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 16:23:43.974 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
03-29 16:23:43.974 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-29 16:23:43.974 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,03-29 16:23:43.974 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-29 16:23:43.974 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 16:23:43.974 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-29 16:23:43.974 11183 11183 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 16:23:43.974 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-29 16:23:43.974 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-29 16:23:43.979 11183 11183 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-29 16:23:43.979 11183 11183 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-29 16:23:43.979 11183 11183 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-29 16:23:43.979 11183 11246 I io.jxcore.node.ConnectionHelper: start: OK
03-29 16:23:43.979 11183 11246 I jxcore-log: ok 141 Can call startListeningForAdvertisements without error
03-29 16:23:43.979 11183 11246 I jxcore-log: 
,03-29 16:23:43.994 11183 11246 I io.jxcore.node.ConnectionHelper: start: Port number: 36320, start advertisements: false
,03-29 16:23:43.994 11183 11246 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-29 16:23:43.994 11183 11246 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-29 16:23:43.994 11183 11246 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 16:23:43.994 11183 11246 I io.jxcore.node.ConnectionHelper: start: OK
,03-29 16:23:43.999 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 16:23:43.999 11183 11246 I jxcore-log: 
,03-29 16:23:43.999 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 16:23:43.999 11183 11246 I jxcore-log: 
,03-29 16:23:44.004 11183 11246 I jxcore-log: ok 142 Can call startListeningForAdvertisements twice without error
03-29 16:23:44.004 11183 11246 I jxcore-log: 
,03-29 16:23:44.009 11183 11246 I jxcore-log: # teardown
03-29 16:23:44.009 11183 11246 I jxcore-log: 
,03-29 16:23:44.059  3452  6065 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-29 16:23:44.114 11183 11246 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-29 16:23:44.114 11183 11246 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
03-29 16:23:44.114 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-29 16:23:44.114 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-29 16:23:44.119  5848  5860 D BtGatt.GattService: stopScan() - queue size =1
,03-29 16:23:44.119  5848  5944 D BtGatt.ScanManager: filter size is 1
03-29 16:23:44.119  5848  5944 D BtGatt.ScanManager: delete FilterIndex - 7
03-29 16:23:44.119  5848  5938 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-29 16:23:44.119  5848  5919 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-29 16:23:44.119  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 16:23:44.119  5848  5944 D BtGatt.ScanManager: stopping BLe Batch
03-29 16:23:44.119 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-29 16:23:44.119 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-29 16:23:44.119 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-29 16:23:44.119 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-29 16:23:44.119 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-29 16:23:44.119 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false,
,03-29 16:23:44.119 11183 11183 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-29 16:23:44.119 11183 11183 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-29 16:23:44.119 11183 11183 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 16:23:44.124  5848  5919 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,03-29 16:23:44.124  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:23:44.124  5848  5944 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-29 16:23:44.124 11183 11246 I jxcore-log: ok 143 Should be able to call stopListeningForAdvertisments in teardown
03-29 16:23:44.124 11183 11246 I jxcore-log: 
,03-29 16:23:44.124  5848  5919 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,03-29 16:23:44.124  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:23:44.124 11183 11246 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections,
03-29 16:23:44.124 11183 11246 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 16:23:44.124 11183 11246 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,03-29 16:23:44.124 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-29 16:23:44.124 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-29 16:23:44.124 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-29 16:23:44.124 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-29 16:23:44.124 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-29 16:23:44.124 11183 11246 D BluetoothLeScanner: could not find callback wrapper
03-29 16:23:44.124 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-29 16:23:44.129 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-29 16:23:44.129 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,03-29 16:23:44.129 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-29 16:23:44.129 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-29 16:23:44.129 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-29 16:23:44.129 11183 11183 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-29 16:23:44.129 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-29 16:23:44.129 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-29 16:23:44.129 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 16:23:44.129 11183 11246 I jxcore-log: 
,03-29 16:23:44.134 11183 11183 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-29 16:23:44.139 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-29 16:23:44.139 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-29 16:23:44.139 11183 11183 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-29 16:23:44.144 11183 11183 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-29 16:23:44.144 11183 11183 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 16:23:44.144 11183 11183 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-29 16:23:44.144 11183 11246 I jxcore-log: ok 144 Should be able to call stopAdvertisingAndListening in teardown
03-29 16:23:44.144 11183 11246 I jxcore-log: 
,03-29 16:23:44.149 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 16:23:44.149 11183 11246 I jxcore-log: 
,03-29 16:23:44.154 11183 11246 I jxcore-log: # setup
03-29 16:23:44.154 11183 11246 I jxcore-log: 
,03-29 16:23:44.339 11183 11246 I jxcore-log: # 37. Can call start/stopUpdateAdvertisingAndListening
03-29 16:23:44.339 11183 11246 I jxcore-log: 
,03-29 16:23:44.504 11183 11246 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true
,03-29 16:23:44.504 11183 11246 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-29 16:23:44.504 11183 11246 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,03-29 16:23:44.509 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-29 16:23:44.514 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-29 16:23:44.514 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-29 16:23:44.514 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-29 16:23:44.514 11183 11246 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-29 16:23:44.519  5848  5860 D BtGatt.GattService: registerClient() - UUID=51a3c40d-44c6-46cd-b8ae-d749c10c0fd6
,03-29 16:23:44.564  5848  5919 D BtGatt.GattService: onClientRegistered() - UUID=51a3c40d-44c6-46cd-b8ae-d749c10c0fd6, clientIf=6
03-29 16:23:44.564 11183 11193 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-29 16:23:44.569  5848  5938 D BtGatt.GattService: start scan with filters,
,03-29 16:23:44.594  5848  5938 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 74
,03-29 16:23:44.594 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-29 16:23:44.594 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-29 16:23:44.594  5848  5944 D BtGatt.ScanManager: handling starting scan
03-29 16:23:44.594  5848  5944 D BtGatt.ScanManager: isFilteringSupported
03-29 16:23:44.594  5848  5944 D BluetoothAdapter: setting StandAloneBleMode
03-29 16:23:44.594 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-29 16:23:44.594 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-29 16:23:44.594 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 16:23:44.594 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-29 16:23:44.594 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-29 16:23:44.594 11183 11246 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-29 16:23:44.594 11183 11246 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 16:23:44.594 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 16:23:44.594 11183 11246 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-29 16:23:44.594 11183 11183 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-29 16:23:44.599  5848  5919 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1,
03-29 16:23:44.599  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:23:44.604  5848  5857 D BtGatt.GattService: registerClient() - UUID=87415412-c144-4dd1-9b2f-d8ca5703fa77
03-29 16:23:44.604  5848  5944 D BtGatt.ScanManager: allow scan with filters
03-29 16:23:44.604  5848  5944 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,03-29 16:23:44.604  5848  5944 D BtGatt.ScanManager: set filter index= 8 for clientIf= 6
,03-29 16:23:44.604  5848  5919 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-29 16:23:44.604  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:23:44.604  5848  5944 D BtGatt.ScanManager: Starting BLE batch scan
03-29 16:23:44.604  5848  5944 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-29 16:23:44.609  5848  5919 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-29 16:23:44.609  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 16:23:44.609  5848  5919 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-29 16:23:44.609  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 16:23:44.644  5848  5919 D BtGatt.GattService: onClientRegistered() - UUID=87415412-c144-4dd1-9b2f-d8ca5703fa77, clientIf=7
,03-29 16:23:44.644 11183 11195 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-29 16:23:44.664  5848  5860 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 58,
03-29 16:23:44.664  5848  5941 D BtGatt.AdvertiseManager: message : 0
03-29 16:23:44.669  5848  5941 D BtGatt.AdvertiseManager: number of adv instance running0
03-29 16:23:44.669  5848  5941 D BtGatt.AdvertiseManager: size of list is =0
,03-29 16:23:44.669  5848  5941 D BtGatt.AdvertiseManager: starting advertising
,03-29 16:23:44.669  5848  5941 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-29 16:23:44.674  5848  5919 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-29 16:23:44.674  5848  5941 D BtGatt.AdvertiseManager: starting multi advertising
,03-29 16:23:44.679  5848  5919 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-29 16:23:44.679  5848  5941 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-29 16:23:44.679  5848  5941 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,03-29 16:23:44.679 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-29 16:23:44.679 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-29 16:23:44.684 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
03-29 16:23:44.684 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-29 16:23:44.684 11183 11246 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-29 16:23:44.684 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-29 16:23:44.684 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-29 16:23:44.684 11183 11246 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,03-29 16:23:44.684 11183 11246 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,03-29 16:23:44.684 11183 11246 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-29 16:23:44.684 11183 11246 I io.jxcore.node.ConnectionHelper: start: OK
03-29 16:23:44.684 11183 11183 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-29 16:23:44.684 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-29 16:23:44.684 11183 11183 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-29 16:23:44.684 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,03-29 16:23:44.684 11183 11183 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-29 16:23:44.684 11183 11183 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-29 16:23:44.684 11183 11183 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-29 16:23:44.684 11183 11183 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-29 16:23:44.684 11183 11183 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-29 16:23:44.684 11183 11183 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-29 16:23:44.689 11183 11183 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-29 16:23:44.689 11183 11183 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-29 16:23:44.689 11183 11672 D BluetoothSocket: bindListen(): myUserId = 0
03-29 16:23:44.689 11183 11672 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-29 16:23:44.689 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false},
03-29 16:23:44.689 11183 11246 I jxcore-log: 
,03-29 16:23:44.694 11183 11246 I jxcore-log: ok 145 Can call startUpdateAdvertisingAndListening without error
03-29 16:23:44.694 11183 11246 I jxcore-log: 
,03-29 16:23:44.694 11183 11672 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[92]}
03-29 16:23:44.694 11183 11672 D BluetoothSocket: bindListen(), new LocalSocket 
03-29 16:23:44.694 11183 11672 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-29 16:23:44.694 11183 11672 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@17db69ad
03-29 16:23:44.694 11183 11672 D BluetoothSocket: channel: 6
03-29 16:23:44.694 11183 11672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-29 16:23:44.694 11183 11246 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-29 16:23:44.694 11183 11246 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-29 16:23:44.694 11183 11246 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,03-29 16:23:44.694 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-29 16:23:44.694 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-29 16:23:44.694 11183 11246 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2b6ce4e2, channel: 6, state: LISTENING
,03-29 16:23:44.699 11183 11246 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2b6ce4e2, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@17db69ad, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@13e68073mSocket: android.net.LocalSocket@39eb30 impl:android.net.LocalSocketImpl@1571f3a9 fd:FileDescriptor[92]
03-29 16:23:44.699 11183 11246 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@39eb30 impl:android.net.LocalSocketImpl@1571f3a9 fd:FileDescriptor[92]
03-29 16:23:44.699 11183 11246 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-29 16:23:44.699 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-29 16:23:44.699 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...,
,03-29 16:23:44.699 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-29 16:23:44.699 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-29 16:23:44.699 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-29 16:23:44.699 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-29 16:23:44.699 11183 11672 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-29 16:23:44.699 11183 11672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-29 16:23:44.699 11183 11672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-29 16:23:44.699  5848  5938 D BtGatt.GattService: stopScan() - queue size =1
03-29 16:23:44.699  5848  5944 D BtGatt.ScanManager: filter size is 1
,03-29 16:23:44.699  5848  5944 D BtGatt.ScanManager: delete FilterIndex - 8
03-29 16:23:44.699  5848  5857 D BtGatt.GattService: unregisterClient() - clientIf=6
03-29 16:23:44.704  5848  5919 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-29 16:23:44.704  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:23:44.704 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-29 16:23:44.704 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-29 16:23:44.704  5848  5944 D BtGatt.ScanManager: stopping BLe Batch
,03-29 16:23:44.704 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-29 16:23:44.704 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-29 16:23:44.704 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-29 16:23:44.704 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-29 16:23:44.704 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-29 16:23:44.704  5848  5919 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-29 16:23:44.704  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:23:44.704  5848  5944 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-29 16:23:44.709  5848  5941 D BtGatt.AdvertiseManager: message : 1
03-29 16:23:44.709  5848  5941 D BtGatt.AdvertiseManager: stop advertise for client 7
03-29 16:23:44.709  5848  5941 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
,03-29 16:23:44.709  5848  5941 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-29 16:23:44.709  5848  5919 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-29 16:23:44.709  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 16:23:44.709  5848  5919 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
,03-29 16:23:44.709  5848  5919 D BtGatt.GattService: Client app is not null!
,03-29 16:23:44.709  5848  5938 D BtGatt.GattService: unregisterClient() - clientIf=7
03-29 16:23:44.714 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-29 16:23:44.714 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED,
,03-29 16:23:44.714 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-29 16:23:44.714 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-29 16:23:44.714 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-29 16:23:44.714 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-29 16:23:44.714 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,03-29 16:23:44.714 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-29 16:23:44.714 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-29 16:23:44.714 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-29 16:23:44.714 11183 11183 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-29 16:23:44.714 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-29 16:23:44.714 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-29 16:23:44.714 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 16:23:44.714 11183 11246 I jxcore-log: 
,03-29 16:23:44.719 11183 11183 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-29 16:23:44.719 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-29 16:23:44.719 11183 11246 I jxcore-log: 
,03-29 16:23:44.724 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-29 16:23:44.724 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-29 16:23:44.724 11183 11183 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-29 16:23:44.729 11183 11183 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-29 16:23:44.729 11183 11183 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-29 16:23:44.729 11183 11183 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-29 16:23:44.729 11183 11183 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 16:23:44.729 11183 11183 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 16:23:44.729 11183 11183 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-29 16:23:44.729 11183 11183 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-29 16:23:44.729 11183 11183 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-29 16:23:44.729 11183 11246 I jxcore-log: ok 146 Can call stopAdvertisingAndListening without error
03-29 16:23:44.729 11183 11246 I jxcore-log: 
,03-29 16:23:44.734 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-29 16:23:44.734 11183 11246 I jxcore-log: 
,03-29 16:23:44.739 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 16:23:44.739 11183 11246 I jxcore-log: 
,03-29 16:23:44.739 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 16:23:44.739 11183 11246 I jxcore-log: 
,03-29 16:23:44.739 11183 11246 I jxcore-log: # teardown
03-29 16:23:44.739 11183 11246 I jxcore-log: 
,03-29 16:23:44.849 11183 11246 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-29 16:23:44.849 11183 11246 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-29 16:23:44.849 11183 11246 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 16:23:44.854 11183 11246 I jxcore-log: ok 147 Should be able to call stopListeningForAdvertisments in teardown
03-29 16:23:44.854 11183 11246 I jxcore-log: 
,03-29 16:23:44.854 11183 11246 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-29 16:23:44.854 11183 11246 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 16:23:44.854 11183 11246 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 16:23:44.859 11183 11246 I jxcore-log: ok 148 Should be able to call stopAdvertisingAndListening in teardown
03-29 16:23:44.859 11183 11246 I jxcore-log: 
,03-29 16:23:44.864 11183 11246 I jxcore-log: # setup,
03-29 16:23:44.864 11183 11246 I jxcore-log: 
,03-29 16:23:45.399 11183 11246 I jxcore-log: # 38. Calling startUpdateAdvertisingAndListening twice is NOT an error
03-29 16:23:45.399 11183 11246 I jxcore-log: 
,03-29 16:23:45.534 11183 11246 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true
,03-29 16:23:45.534 11183 11246 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-29 16:23:45.534 11183 11246 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,03-29 16:23:45.534 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-29 16:23:45.539 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-29 16:23:45.539 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-29 16:23:45.544 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-29 16:23:45.544 11183 11246 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-29 16:23:45.549  5848  5938 D BtGatt.GattService: registerClient() - UUID=6c07536f-33e7-42b5-9d36-333120ca00d3
,03-29 16:23:45.594  5848  5919 D BtGatt.GattService: onClientRegistered() - UUID=6c07536f-33e7-42b5-9d36-333120ca00d3, clientIf=6
03-29 16:23:45.594 11183 11195 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-29 16:23:45.609  5848  5857 D BtGatt.GattService: start scan with filters
,03-29 16:23:45.634  5848  5857 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 75
,03-29 16:23:45.639 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-29 16:23:45.639 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-29 16:23:45.639 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-29 16:23:45.639 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-29 16:23:45.639 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 16:23:45.639 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-29 16:23:45.639 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-29 16:23:45.639  5848  5944 D BtGatt.ScanManager: handling starting scan
,03-29 16:23:45.639  5848  5944 D BtGatt.ScanManager: isFilteringSupported
,03-29 16:23:45.639 11183 11246 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0,
03-29 16:23:45.639  5848  5944 D BluetoothAdapter: setting StandAloneBleMode
03-29 16:23:45.639 11183 11246 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 16:23:45.639 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-29 16:23:45.639 11183 11246 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-29 16:23:45.639 11183 11183 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-29 16:23:45.644  5848  5919 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,03-29 16:23:45.644  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:23:45.644  5848  5944 D BtGatt.ScanManager: allow scan with filters
03-29 16:23:45.644  5848  5944 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,03-29 16:23:45.644  5848  5944 D BtGatt.ScanManager: set filter index= 9 for clientIf= 6
,03-29 16:23:45.644  5848  5919 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-29 16:23:45.649  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:23:45.649  5848  5944 D BtGatt.ScanManager: Starting BLE batch scan
03-29 16:23:45.649  5848  5944 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-29 16:23:45.649  5848  5860 D BtGatt.GattService: registerClient() - UUID=0986bfc1-5ac9-4e4e-a8d3-9cc274468bad
03-29 16:23:45.649  5848  5919 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-29 16:23:45.649  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 16:23:45.654  5848  5919 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-29 16:23:45.654  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 16:23:45.689  5848  5919 D BtGatt.GattService: onClientRegistered() - UUID=0986bfc1-5ac9-4e4e-a8d3-9cc274468bad, clientIf=7
,03-29 16:23:45.689 11183 11193 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-29 16:23:45.714  5848  8884 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 59
,03-29 16:23:45.714  5848  5941 D BtGatt.AdvertiseManager: message : 0
,03-29 16:23:45.714  5848  5941 D BtGatt.AdvertiseManager: number of adv instance running0
03-29 16:23:45.714  5848  5941 D BtGatt.AdvertiseManager: size of list is =0
,03-29 16:23:45.719  5848  5941 D BtGatt.AdvertiseManager: starting advertising
,03-29 16:23:45.719  5848  5941 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-29 16:23:45.719  5848  5919 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-29 16:23:45.729  5848  5941 D BtGatt.AdvertiseManager: starting multi advertising
,03-29 16:23:45.729  5848  5919 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-29 16:23:45.729  5848  5941 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-29 16:23:45.729  5848  5941 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,03-29 16:23:45.729 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-29 16:23:45.729 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-29 16:23:45.739 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
,03-29 16:23:45.739 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-29 16:23:45.739 11183 11246 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,03-29 16:23:45.739 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-29 16:23:45.749 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...,
,03-29 16:23:45.749 11183 11246 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true,
,03-29 16:23:45.749 11183 11246 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,03-29 16:23:45.749 11183 11246 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-29 16:23:45.754 11183 11183 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything,
03-29 16:23:45.754 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-29 16:23:45.754 11183 11183 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-29 16:23:45.754 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,03-29 16:23:45.754 11183 11183 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
,03-29 16:23:45.754 11183 11183 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-29 16:23:45.754 11183 11183 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-29 16:23:45.754 11183 11183 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false,
03-29 16:23:45.754 11183 11183 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-29 16:23:45.754 11183 11183 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 16:23:45.754 11183 11183 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING,
,03-29 16:23:45.754 11183 11183 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true,
03-29 16:23:45.759 11183 11246 I io.jxcore.node.ConnectionHelper: start: OK
,03-29 16:23:45.764 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false},
03-29 16:23:45.764 11183 11246 I jxcore-log: 
,03-29 16:23:45.769 11183 11687 D BluetoothSocket: bindListen(): myUserId = 0,
,03-29 16:23:45.774 11183 11687 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback,
,03-29 16:23:45.779 11183 11687 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[92]},
,03-29 16:23:45.779 11183 11687 D BluetoothSocket: bindListen(), new LocalSocket 
,03-29 16:23:45.779 11183 11687 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-29 16:23:45.779 11183 11687 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1ecd2165,
03-29 16:23:45.779 11183 11687 D BluetoothSocket: channel: 6
,03-29 16:23:45.779 11183 11687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...,
,03-29 16:23:45.784 11183 11246 I jxcore-log: ok 149 Can call startUpdateAdvertisingAndListening without error
03-29 16:23:45.784 11183 11246 I jxcore-log: 
,03-29 16:23:45.789 11183 11246 I io.jxcore.node.ConnectionHelper: start: Port number: 4243, start advertisements: true
,03-29 16:23:45.789 11183 11246 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-29 16:23:45.789 11183 11246 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,03-29 16:23:45.789 11183 11246 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 16:23:45.789 11183 11246 I io.jxcore.node.ConnectionHelper: start: OK
,03-29 16:23:45.794 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 16:23:45.794 11183 11246 I jxcore-log: 
,03-29 16:23:45.794 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-29 16:23:45.794 11183 11246 I jxcore-log: 
,03-29 16:23:45.799 11183 11246 I jxcore-log: ok 150 Can call startUpdateAdvertisingAndListening twice without error
03-29 16:23:45.799 11183 11246 I jxcore-log: 
,03-29 16:23:45.804 11183 11246 I jxcore-log: # teardown
03-29 16:23:45.804 11183 11246 I jxcore-log: 
,03-29 16:23:46.654  3452  3619 V AlarmManager: waitForAlarm result :4
,03-29 16:23:46.664  5848  5848 D BtGatt.ScanManager: awakened up at time 252344
,03-29 16:23:46.674  5848  5944 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-29 16:23:46.684  5848  5919 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
03-29 16:23:46.684  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:23:46.684  5848  5919 D BtGatt.GattService: current time is 252361381028
03-29 16:23:46.684  5848  5919 D BtGatt.GattService: Batch record : [117, 97, 39, -43, 54, 110, 1, -128, -74, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, 114, -55, 67, 93, -62, 77, 1, -128, -57, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0]
03-29 16:23:46.684  5848  5919 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-29 16:23:46.684  5848  5919 D ScanRecord: parseFromBytes
03-29 16:23:46.684  5848  5919 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-29 16:23:46.684  5848  5919 D ScanRecord: parseFromBytes
03-29 16:23:46.684  5848  5919 D BtGatt.GattService: result: ScanResult{mDevice=4D:C2:5D:43:C9:72, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-57, mTimestampNanos=252311588778}
03-29 16:23:46.684  5848  5919 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-29 16:23:46.684  5848  5919 D BtGatt.GattService: result: ScanResult{mDevice=6E:36:D5:27:61:75, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-74, mTimestampNanos=252311588778}
03-29 16:23:46.684  5848  5919 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
,03-29 16:23:46.684 11183 11193 D ScanRecord: parseFromBytes
03-29 16:23:46.684 11183 11193 D ScanRecord: parseFromBytes
,03-29 16:23:46.684 11183 11183 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:CF:C5:D9:E5:61], added - the peer count is 1
03-29 16:23:46.689 11183 11183 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 2
,03-29 16:23:46.689 11183 11183 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:CF:C5:D9:E5:61], Bluetooth address: F8:CF:C5:D9:E5:61, device name: , device address: ,
03-29 16:23:46.689 11183 11183 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
03-29 16:23:46.689 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
03-29 16:23:46.689 11183 11246 I jxcore-log: 
,03-29 16:23:46.694 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
03-29 16:23:46.694 11183 11246 I jxcore-log: 
,03-29 16:23:46.704  3452  4020 D ActivityManager: startService callerProcessName:com.facebook.appmanager, calleePkgName: com.facebook.appmanager
,03-29 16:23:46.814 10280 11698 W appmanager(:<default>):QuickExperimentControllerImpl: Exposure of experiment com.facebook.imagepipeline.m.d@114e7c4e occurred when no user was logged in
,03-29 16:23:46.829 10280 11698 W appmanager(:<default>):aa: Requested time interval of 300000 ms should be increased to at least 900000 ms for a
03-29 16:23:46.829 10280 11698 W appmanager(:<default>):aa: Requested time interval of 300000 ms should be increased to at least 900000 ms for a
,03-29 16:23:46.834 10280 11698 V analytics4a: JNI_OnLoad called
03-29 16:23:46.834 10280 11698 V analytics4a: JNI_OnLoad complete
,03-29 16:23:46.844  3452  3861 E Watchdog: !@Sync 8 [03-29 16:23:46.845]
,03-29 16:23:46.859 10280 11698 I art     : WaitForGcToComplete blocked for 13.366ms for cause Explicit
,03-29 16:23:46.899 10280 11698 I art     : Explicit concurrent mark sweep GC freed 2462(296KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/8MB, paused 1.398ms total 40.144ms
,03-29 16:23:46.924 10280 11698 W appmanager(:<default>):m: No feature status reporters found; is this dead code?
,03-29 16:23:47.004  3452  3491 D ActivityManager: bindService callerProcessName:com.facebook.appmanager, calleePkgName: com.facebook.appmanager, action: null
,03-29 16:23:47.019  3452  4399 D ActivityManager: startService callerProcessName:com.facebook.appmanager, calleePkgName: com.facebook.appmanager
,03-29 16:23:47.109  3452  4020 D ActivityManager: bindService callerProcessName:com.facebook.appmanager, calleePkgName: com.facebook.appmanager, action: null
,03-29 16:23:47.244 10280 11721 I System.out: Thread-1464(ApacheHTTPLog):isSBSettingEnabled false
03-29 16:23:47.244 10280 11721 I System.out: Thread-1464(ApacheHTTPLog):isShipBuild true
03-29 16:23:47.244 10280 11721 I System.out: Thread-1464(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-29 16:23:47.244 10280 11721 I System.out: Thread-1464(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-29 16:23:47.244  2872  3506 D EnterpriseController: netId is 0
03-29 16:23:47.244  2872  3506 D Netd    : getNetworkForDns: using netid 502 for uid 10110
,03-29 16:23:47.339 10280 11723 I System.out: Thread-1465(ApacheHTTPLog):isSBSettingEnabled false
03-29 16:23:47.339 10280 11723 I System.out: Thread-1465(ApacheHTTPLog):isShipBuild true
03-29 16:23:47.339 10280 11723 I System.out: Thread-1465(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-29 16:23:47.339 10280 11723 I System.out: Thread-1465(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-29 16:23:47.339  2872  3506 D EnterpriseController: netId is 0
03-29 16:23:47.339  2872  3506 D Netd    : getNetworkForDns: using netid 502 for uid 10110
,03-29 16:23:47.539 11183 11246 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-29 16:23:47.539 11183 11246 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
,03-29 16:23:47.539 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-29 16:23:47.539 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-29 16:23:47.544  5848  5857 D BtGatt.GattService: stopScan() - queue size =1,
03-29 16:23:47.544  5848  5944 D BtGatt.ScanManager: filter size is 1
03-29 16:23:47.544  5848  5944 D BtGatt.ScanManager: delete FilterIndex - 9
03-29 16:23:47.544  5848  5919 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-29 16:23:47.544  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:23:47.544  5848  5944 D BtGatt.ScanManager: stopping BLe Batch,
,03-29 16:23:47.549  5848  5919 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0,
,03-29 16:23:47.549  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:23:47.549  5848  5944 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-29 16:23:47.549  5848  5919 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
03-29 16:23:47.549  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:23:47.549  5848  5919 D BtGatt.GattService: current time is 253229818528
,03-29 16:23:47.549  5848  5919 D BtGatt.GattService: Batch record : [114, -55, 67, 93, -62, 77, 1, -128, -61, 6, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0, 117, 97, 39, -43, 54, 110, 1, -128, -70, 9, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-29 16:23:47.554  5848  5919 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-29 16:23:47.554  5848  5919 D ScanRecord: parseFromBytes
03-29 16:23:47.554  5848  5919 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81],
03-29 16:23:47.554  5848  5919 D ScanRecord: parseFromBytes
,03-29 16:23:47.559  5848  5860 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-29 16:23:47.564 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
03-29 16:23:47.564 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-29 16:23:47.564 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-29 16:23:47.564 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-29 16:23:47.564 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
,03-29 16:23:47.564 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-29 16:23:47.564 11183 11183 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-29 16:23:47.564 11183 11183 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-29 16:23:47.564 11183 11183 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-29 16:23:47.569 11183 11246 I jxcore-log: ok 151 Should be able to call stopListeningForAdvertisments in teardown
03-29 16:23:47.569 11183 11246 I jxcore-log: 
,03-29 16:23:47.574 11183 11246 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-29 16:23:47.574 11183 11246 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,03-29 16:23:47.574 11183 11246 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-29 16:23:47.574 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,03-29 16:23:47.574 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-29 16:23:47.574 11183 11246 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@20e3f048, channel: 6, state: LISTENING
,03-29 16:23:47.574 11183 11246 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@20e3f048, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1ecd2165, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@13f36ee1mSocket: android.net.LocalSocket@d74f406 impl:android.net.LocalSocketImpl@1fc9eac7 fd:FileDescriptor[92]
,03-29 16:23:47.574 11183 11246 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@d74f406 impl:android.net.LocalSocketImpl@1fc9eac7 fd:FileDescriptor[92]
,03-29 16:23:47.579 11183 11246 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-29 16:23:47.579 11183 11687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-29 16:23:47.579 11183 11687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-29 16:23:47.579 11183 11687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-29 16:23:47.579 11183 11183 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-29 16:23:47.579 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-29 16:23:47.579 11183 11183 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-29 16:23:47.579 11183 11183 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-29 16:23:47.579 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-29 16:23:47.579 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-29 16:23:47.579 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-29 16:23:47.584 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-29 16:23:47.584 11183 11246 D BluetoothLeScanner: could not find callback wrapper,
03-29 16:23:47.584 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-29 16:23:47.584 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-29 16:23:47.589  5848  5941 D BtGatt.AdvertiseManager: message : 1,
,03-29 16:23:47.589  5848  5941 D BtGatt.AdvertiseManager: stop advertise for client 7
03-29 16:23:47.589  5848  5941 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-29 16:23:47.589  5848  5941 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,03-29 16:23:47.589  5848  5919 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-29 16:23:47.589  5848  5919 D BtGatt.GattService: Client app is not null!
,03-29 16:23:47.594  5848  5860 D BtGatt.GattService: unregisterClient() - clientIf=7,
,03-29 16:23:47.594 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-29 16:23:47.594 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-29 16:23:47.594 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false,
03-29 16:23:47.594 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,03-29 16:23:47.599 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-29 16:23:47.599 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-29 16:23:47.599 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,03-29 16:23:47.599 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-29 16:23:47.599 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
03-29 16:23:47.599 11183 11246 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-29 16:23:47.599 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false,
,03-29 16:23:47.599 11183 11183 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 16:23:47.599 11183 11183 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-29 16:23:47.599 11183 11183 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-29 16:23:47.599 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-29 16:23:47.599 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-29 16:23:47.604 11183 11183 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-29 16:23:47.614 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true},
03-29 16:23:47.614 11183 11246 I jxcore-log: 
,03-29 16:23:47.614 11183 11246 I jxcore-log: ok 152 Should be able to call stopAdvertisingAndListening in teardown
03-29 16:23:47.614 11183 11246 I jxcore-log: 
,03-29 16:23:47.619 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-29 16:23:47.619 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-29 16:23:47.619 11183 11183 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-29 16:23:47.624 11183 11183 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-29 16:23:47.624 11183 11183 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-29 16:23:47.624 11183 11246 I jxcore-log: # setup
03-29 16:23:47.624 11183 11246 I jxcore-log: 
,03-29 16:23:47.629 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 16:23:47.629 11183 11246 I jxcore-log: 
,03-29 16:23:47.629 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 16:23:47.629 11183 11246 I jxcore-log: 
,03-29 16:23:47.899 11183 11246 I jxcore-log: # 39. peerAvailabilityChange is called
03-29 16:23:47.899 11183 11246 I jxcore-log: 
,03-29 16:23:48.204 10280 11721 I System.out: P[5]_NetworkDispatch4 calls detatch()
,03-29 16:23:48.214 11183 11246 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true
03-29 16:23:48.214 11183 11246 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-29 16:23:48.214 11183 11246 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-29 16:23:48.214 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-29 16:23:48.219 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-29 16:23:48.219 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-29 16:23:48.219 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-29 16:23:48.219 11183 11246 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-29 16:23:48.224  5848  5860 D BtGatt.GattService: registerClient() - UUID=09dc80d9-7a82-41a5-ba76-ce966e587e3e
,03-29 16:23:48.264  5848  5919 D BtGatt.GattService: onClientRegistered() - UUID=09dc80d9-7a82-41a5-ba76-ce966e587e3e, clientIf=6
,03-29 16:23:48.264 11183 11195 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-29 16:23:48.264  5848  8884 D BtGatt.GattService: start scan with filters
,03-29 16:23:48.274 10280 11751 I System.out: Thread-1466(ApacheHTTPLog):isSBSettingEnabled false
03-29 16:23:48.274 10280 11751 I System.out: Thread-1466(ApacheHTTPLog):isShipBuild true
03-29 16:23:48.274 10280 11751 I System.out: Thread-1466(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-29 16:23:48.274 10280 11751 I System.out: Thread-1466(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-29 16:23:48.279  5848  8884 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 76
,03-29 16:23:48.279 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
03-29 16:23:48.279 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-29 16:23:48.279 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-29 16:23:48.279 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-29 16:23:48.279 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,03-29 16:23:48.279 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-29 16:23:48.279 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-29 16:23:48.279 11183 11246 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
,03-29 16:23:48.284 11183 11183 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-29 16:23:48.284  5848  5944 D BtGatt.ScanManager: handling starting scan
03-29 16:23:48.284  5848  5944 D BtGatt.ScanManager: isFilteringSupported
,03-29 16:23:48.284  5848  5944 D BluetoothAdapter: setting StandAloneBleMode
03-29 16:23:48.284 11183 11246 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-29 16:23:48.284 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 16:23:48.284 11183 11246 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-29 16:23:48.289  5848  5919 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,03-29 16:23:48.289  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:23:48.289  5848  5944 D BtGatt.ScanManager: allow scan with filters
03-29 16:23:48.289  5848  5944 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-29 16:23:48.289  5848  5944 D BtGatt.ScanManager: set filter index= 10 for clientIf= 6
,03-29 16:23:48.294  5848  8884 D BtGatt.GattService: registerClient() - UUID=549ee3f3-6b5b-4cc8-b260-3c50cb2d8f31,
,03-29 16:23:48.294  5848  5919 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,03-29 16:23:48.294  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:23:48.294  5848  5944 D BtGatt.ScanManager: Starting BLE batch scan
03-29 16:23:48.294  5848  5944 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-29 16:23:48.299  5848  5919 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,03-29 16:23:48.299  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 16:23:48.299  5848  5919 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,03-29 16:23:48.299  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 16:23:48.314 10280 11723 I System.out: P[5]_NetworkDispatch5 calls detatch()
,03-29 16:23:48.334  5848  5919 D BtGatt.GattService: onClientRegistered() - UUID=549ee3f3-6b5b-4cc8-b260-3c50cb2d8f31, clientIf=7
,03-29 16:23:48.334 11183 11193 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-29 16:23:48.349  5848  5938 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 60
,03-29 16:23:48.349  5848  5941 D BtGatt.AdvertiseManager: message : 0
,03-29 16:23:48.349  5848  5941 D BtGatt.AdvertiseManager: number of adv instance running0
03-29 16:23:48.349  5848  5941 D BtGatt.AdvertiseManager: size of list is =0
,03-29 16:23:48.359  5848  5941 D BtGatt.AdvertiseManager: starting advertising
03-29 16:23:48.359  5848  5941 D BtGatt.AdvertiseManager: isStandardAdvfalse
03-29 16:23:48.359  5848  5919 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-29 16:23:48.364  5848  5941 D BtGatt.AdvertiseManager: starting multi advertising
,03-29 16:23:48.364  5848  5919 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-29 16:23:48.364  5848  5941 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-29 16:23:48.364  5848  5941 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,03-29 16:23:48.364 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-29 16:23:48.364 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-29 16:23:48.369 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-29 16:23:48.369 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-29 16:23:48.369 11183 11246 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-29 16:23:48.369 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-29 16:23:48.369 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-29 16:23:48.369 11183 11246 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-29 16:23:48.369 11183 11246 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-29 16:23:48.369 11183 11246 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-29 16:23:48.369 11183 11183 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-29 16:23:48.369 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-29 16:23:48.369 11183 11183 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-29 16:23:48.369 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-29 16:23:48.369 11183 11183 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-29 16:23:48.369 11183 11183 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-29 16:23:48.369 11183 11183 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-29 16:23:48.369 11183 11183 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-29 16:23:48.369 11183 11183 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-29 16:23:48.369 11183 11183 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 16:23:48.369 11183 11183 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-29 16:23:48.369 11183 11183 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-29 16:23:48.369 11183 11246 I io.jxcore.node.ConnectionHelper: start: OK
,03-29 16:23:48.374 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false},
03-29 16:23:48.374 11183 11246 I jxcore-log: 
,03-29 16:23:48.379 11183 11755 D BluetoothSocket: bindListen(): myUserId = 0,
,03-29 16:23:48.384 11183 11246 I jxcore-log: ok 153 Can call startUpdateAdvertisingAndListeningwithout error
03-29 16:23:48.384 11183 11246 I jxcore-log: 
,03-29 16:23:48.384 11183 11755 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-29 16:23:48.384 11183 11755 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[92]}
,03-29 16:23:48.389 11183 11755 D BluetoothSocket: bindListen(), new LocalSocket 
,03-29 16:23:48.389 11183 11755 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-29 16:23:48.389 11183 11755 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@20f06c63
,03-29 16:23:48.389 11183 11755 D BluetoothSocket: channel: 6
,03-29 16:23:48.389 11183 11755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-29 16:23:48.394 11183 11246 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: false
,03-29 16:23:48.394 11183 11246 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-29 16:23:48.394 11183 11246 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
03-29 16:23:48.394 11183 11246 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 16:23:48.394 11183 11246 I io.jxcore.node.ConnectionHelper: start: OK
,03-29 16:23:48.399 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 16:23:48.399 11183 11246 I jxcore-log: 
,03-29 16:23:48.404 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-29 16:23:48.404 11183 11246 I jxcore-log: 
,03-29 16:23:48.409 11183 11246 I jxcore-log: ok 154 Can call startListeningForAdvertisements without error
03-29 16:23:48.409 11183 11246 I jxcore-log: 
,03-29 16:23:48.504  2857  3081 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/Download/
03-29 16:23:48.504  2857  3081 W Vold    : Returning OperationFailed - no handler for errno 0
,03-29 16:23:48.504 10280 11697 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files/Download
,03-29 16:23:48.514  3753  6005 D DownloadManager: checkFileUriDestination : valid path 
,03-29 16:23:48.519  3452  3836 D SecContentProvider2: query(), uri = 15 selection = getAppBlockDownloadState
,03-29 16:23:48.564  3452  4028 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
,03-29 16:23:48.574 10280 11751 I System.out: P[5]_NetworkDispatch6 calls detatch()
,03-29 16:23:48.584  3452  3836 D SecContentProvider2: query(), uri = 15 selection = getAppBlockDownloadState
,03-29 16:23:48.604  3452  4399 D SecContentProvider2: query(), uri = 15 selection = getAppBlockDownloadState
,03-29 16:23:48.624  3753 11763 V DownloadManager: 1 items are running
,03-29 16:23:48.629 10280 11765 I System.out: Thread-1467(ApacheHTTPLog):isSBSettingEnabled false
03-29 16:23:48.629 10280 11765 I System.out: Thread-1467(ApacheHTTPLog):isShipBuild true
03-29 16:23:48.629 10280 11765 I System.out: Thread-1467(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-29 16:23:48.629 10280 11765 I System.out: Thread-1467(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-29 16:23:48.639  3753 11764 D DownloadManager: [118] Starting com.facebook.appmanager
,03-29 16:23:48.644  3753 11764 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,03-29 16:23:48.644  3452  4028 D SecContentProvider2: query(), uri = 15 selection = getAppBlockDownloadState
,03-29 16:23:48.649  3753 11763 V DownloadManager: 1 items are running
,03-29 16:23:48.654 10280 11770 I System.out: Thread-1471(ApacheHTTPLog):isSBSettingEnabled false
03-29 16:23:48.654 10280 11770 I System.out: Thread-1471(ApacheHTTPLog):isShipBuild true
03-29 16:23:48.654 10280 11770 I System.out: Thread-1471(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-29 16:23:48.659 10280 11770 I System.out: Thread-1471(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-29 16:23:48.664  3753 11764 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,03-29 16:23:48.669  3753 11764 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
03-29 16:23:48.669  3753 11764 I System.out: (HTTPLog)-Static: isShipBuild true
03-29 16:23:48.669  3753 11764 I System.out: (HTTPLog)-Thread-59-218613216: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
03-29 16:23:48.669  3753 11764 I System.out: (HTTPLog)-Thread-59-218613216: SMARTBONDING_FEATURE_ENABLED is true
03-29 16:23:48.669  3753 11764 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,03-29 16:23:48.674  2872  3506 D EnterpriseController: netId is 0
03-29 16:23:48.674  2872  3506 D Netd    : getNetworkForDns: using netid 502 for uid 10048
,03-29 16:23:48.799  3753 11764 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,03-29 16:23:48.799  3753 11764 I qtaguid : Tagging socket 58 with tag ffffff0100000000{4294967041,0} uid 10110, pid: 3753, getuid(): 10048
,03-29 16:23:48.924 10280 11770 I System.out: P[5]_NetworkDispatch8 calls detatch()
,03-29 16:23:48.939 10280 11765 I System.out: P[5]_NetworkDispatch7 calls detatch()
,03-29 16:23:49.004 10280 11784 I System.out: Thread-1474(ApacheHTTPLog):isSBSettingEnabled false
03-29 16:23:49.004 10280 11784 I System.out: Thread-1474(ApacheHTTPLog):isShipBuild true
03-29 16:23:49.004 10280 11784 I System.out: Thread-1474(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-29 16:23:49.004 10280 11784 I System.out: Thread-1474(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-29 16:23:49.299  3452  3619 V AlarmManager: waitForAlarm result :4
,03-29 16:23:49.314  5848  5848 D BtGatt.ScanManager: awakened up at time 254991
,03-29 16:23:49.319  5848  5944 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-29 16:23:49.324  5848  5919 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
03-29 16:23:49.324  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:23:49.324  5848  5919 D BtGatt.GattService: current time is 255004684487
03-29 16:23:49.324  5848  5919 D BtGatt.GattService: Batch record : [109, -112, -67, 74, 77, 73, 1, -128, -63, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0, -67, -13, -48, -10, 91, 116, 1, -128, -64, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-29 16:23:49.329  5848  5919 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-29 16:23:49.329  5848  5919 D ScanRecord: parseFromBytes
03-29 16:23:49.329  5848  5919 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-29 16:23:49.329  5848  5919 D ScanRecord: parseFromBytes
03-29 16:23:49.329  5848  5919 D BtGatt.GattService: result: ScanResult{mDevice=49:4D:4A:BD:90:6D, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-63, mTimestampNanos=255004941570}
03-29 16:23:49.329  5848  5919 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-29 16:23:49.329  5848  5919 D BtGatt.GattService: result: ScanResult{mDevice=74:5B:F6:D0:F3:BD, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-64, mTimestampNanos=254954941570}
03-29 16:23:49.329  5848  5919 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-29 16:23:49.329 11183 11193 D ScanRecord: parseFromBytes
03-29 16:23:49.329 11183 11193 D ScanRecord: parseFromBytes
03-29 16:23:49.329 11183 11183 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:CF:C5:D9:E5:61], added - the peer count is 1
03-29 16:23:49.329 11183 11183 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 2
03-29 16:23:49.329 11183 11183 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:CF:C5:D9:E5:61], Bluetooth address: F8:CF:C5:D9:E5:61, device name: , device address: 
03-29 16:23:49.329 11183 11183 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
,03-29 16:23:49.349 11183 11246 I jxcore-log: ok 155 peers must be an array,
03-29 16:23:49.349 11183 11246 I jxcore-log: 
03-29 16:23:49.349 11183 11246 I jxcore-log: ok 156 peers must not be zero-length
03-29 16:23:49.349 11183 11246 I jxcore-log: 
,03-29 16:23:49.349 11183 11246 I jxcore-log: ok 157 peer must have peerIdentifier
03-29 16:23:49.349 11183 11246 I jxcore-log: 
03-29 16:23:49.349 11183 11246 I jxcore-log: ok 158 peerIdentifier must be a string
03-29 16:23:49.349 11183 11246 I jxcore-log: 
03-29 16:23:49.349 11183 11246 I jxcore-log: ok 159 peer must have peerAvailable
03-29 16:23:49.349 11183 11246 I jxcore-log: 
,03-29 16:23:49.359 11183 11246 I jxcore-log: ok 160 peer must have pleaseConnect
03-29 16:23:49.359 11183 11246 I jxcore-log: 
,03-29 16:23:49.369 11183 11246 I jxcore-log: # teardown
03-29 16:23:49.369 11183 11246 I jxcore-log: 
,03-29 16:23:49.369 10280 11784 I System.out: P[5]_NetworkDispatch9 calls detatch()
,03-29 16:23:49.434 10280 11791 I System.out: Thread-1475(ApacheHTTPLog):isSBSettingEnabled false
03-29 16:23:49.434 10280 11791 I System.out: Thread-1475(ApacheHTTPLog):isShipBuild true
03-29 16:23:49.434 10280 11791 I System.out: Thread-1475(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-29 16:23:49.434 10280 11791 I System.out: Thread-1475(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-29 16:23:49.949 10280 11791 I System.out: P[5]_NetworkDispatch10 calls detatch()
,03-29 16:23:49.979 11183 11246 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-29 16:23:49.984 11183 11246 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
,03-29 16:23:49.984 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-29 16:23:49.984 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-29 16:23:49.984  5848  5860 D BtGatt.GattService: stopScan() - queue size =1
,03-29 16:23:49.989  5848  5944 D BtGatt.ScanManager: filter size is 1
03-29 16:23:49.989  5848  5944 D BtGatt.ScanManager: delete FilterIndex - 10
03-29 16:23:49.989  5848  5919 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-29 16:23:49.989  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 16:23:49.989  5848  5944 D BtGatt.ScanManager: stopping BLe Batch
,03-29 16:23:49.989  5848  8884 D BtGatt.GattService: unregisterClient() - clientIf=6
03-29 16:23:49.994  5848  5919 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,03-29 16:23:49.994  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 16:23:49.994  5848  5944 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-29 16:23:49.994  5848  5919 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
03-29 16:23:49.994  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
03-29 16:23:49.994  5848  5919 D BtGatt.GattService: current time is 255674931320
03-29 16:23:49.999  5848  5919 D BtGatt.GattService: Batch record : [-67, -13, -48, -10, 91, 116, 1, -128, -64, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, 109, -112, -67, 74, 77, 73, 1, -128, -63, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0]
03-29 16:23:49.999  5848  5919 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-29 16:23:49.999  5848  5919 D ScanRecord: parseFromBytes
03-29 16:23:49.999  5848  5919 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-29 16:23:49.999  5848  5919 D ScanRecord: parseFromBytes
,03-29 16:23:49.999 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
03-29 16:23:49.999 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-29 16:23:49.999 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,03-29 16:23:49.999 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-29 16:23:49.999 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-29 16:23:49.999 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-29 16:23:50.004 11183 11183 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-29 16:23:50.004 11183 11183 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-29 16:23:50.004 11183 11183 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 16:23:50.004 11183 11246 I jxcore-log: ok 161 Should be able to call stopListeningForAdvertisments in teardown
03-29 16:23:50.004 11183 11246 I jxcore-log: 
03-29 16:23:50.004 11183 11246 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-29 16:23:50.004 11183 11246 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,03-29 16:23:50.004 11183 11246 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-29 16:23:50.004 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-29 16:23:50.004 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-29 16:23:50.004 11183 11246 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2cf07dde, channel: 6, state: LISTENING
03-29 16:23:50.004 11183 11246 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2cf07dde, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@20f06c63, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@20736bbfmSocket: android.net.LocalSocket@10b3428c impl:android.net.LocalSocketImpl@3ee22dd5 fd:FileDescriptor[92]
03-29 16:23:50.004 11183 11246 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@10b3428c impl:android.net.LocalSocketImpl@3ee22dd5 fd:FileDescriptor[92]
,03-29 16:23:50.009 11183 11246 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-29 16:23:50.009 11183 11755 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-29 16:23:50.009 11183 11755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-29 16:23:50.009 11183 11755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-29 16:23:50.014 11183 11183 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-29 16:23:50.014 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-29 16:23:50.014 11183 11183 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-29 16:23:50.014 11183 11183 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-29 16:23:50.014 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-29 16:23:50.014 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-29 16:23:50.014 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-29 16:23:50.014 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-29 16:23:50.014 11183 11246 D BluetoothLeScanner: could not find callback wrapper,
03-29 16:23:50.019 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-29 16:23:50.019 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-29 16:23:50.019  5848  5941 D BtGatt.AdvertiseManager: message : 1,
,03-29 16:23:50.019  5848  5941 D BtGatt.AdvertiseManager: stop advertise for client 7
03-29 16:23:50.019  5848  5941 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-29 16:23:50.019  5848  5941 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,03-29 16:23:50.024  5848  5919 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-29 16:23:50.024  5848  5919 D BtGatt.GattService: Client app is not null!
,03-29 16:23:50.024  5848  8884 D BtGatt.GattService: unregisterClient() - clientIf=7,
,03-29 16:23:50.029 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-29 16:23:50.029 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-29 16:23:50.029 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-29 16:23:50.029 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-29 16:23:50.029 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-29 16:23:50.029 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-29 16:23:50.029 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,03-29 16:23:50.029 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-29 16:23:50.034 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
03-29 16:23:50.034 11183 11246 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-29 16:23:50.034 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-29 16:23:50.034 11183 11183 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 16:23:50.034 11183 11183 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 16:23:50.034 11183 11183 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-29 16:23:50.034 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-29 16:23:50.034 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-29 16:23:50.034 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-29 16:23:50.034 11183 11246 I jxcore-log: 
,03-29 16:23:50.039 11183 11246 I jxcore-log: ok 162 Should be able to call stopAdvertisingAndListening in teardown
03-29 16:23:50.039 11183 11246 I jxcore-log: 
,03-29 16:23:50.044 11183 11183 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-29 16:23:50.049 11183 11246 I jxcore-log: # setup
03-29 16:23:50.049 11183 11246 I jxcore-log: 
,03-29 16:23:50.049 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-29 16:23:50.054 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-29 16:23:50.054 11183 11183 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-29 16:23:50.054 11183 11183 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-29 16:23:50.054 11183 11183 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-29 16:23:50.059 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 16:23:50.059 11183 11246 I jxcore-log: 
,03-29 16:23:50.064 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 16:23:50.064 11183 11246 I jxcore-log: 
,03-29 16:23:50.074 10280 11798 I System.out: Thread-1476(ApacheHTTPLog):isSBSettingEnabled false
03-29 16:23:50.074 10280 11798 I System.out: Thread-1476(ApacheHTTPLog):isShipBuild true
03-29 16:23:50.074 10280 11798 I System.out: Thread-1476(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-29 16:23:50.074 10280 11798 I System.out: Thread-1476(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-29 16:23:50.224  2892  4828 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-29 16:23:50.289  3753 11764 I qtaguid : Tagging socket 64 with tag ffffff0100000000{4294967041,0} uid 10110, pid: 3753, getuid(): 10048
,03-29 16:23:50.289  3753 11764 I qtaguid : Tagging socket 65 with tag ffffff0100000000{4294967041,0} uid 10110, pid: 3753, getuid(): 10048
,03-29 16:23:50.294  3753 11764 W DownloadManager: fallocate() said ENOTSUP; falling back to ftruncate()
,03-29 16:23:50.299  3452  3914 D SecContentProvider2: query(), uri = 15 selection = getAppBlockDownloadState
,03-29 16:23:50.299  3753 11763 V DownloadManager: 1 items are running
,03-29 16:23:50.304 10280 11798 I System.out: P[5]_NetworkDispatch11 calls detatch()
,03-29 16:23:50.314  3452  3836 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-29 16:23:50.314  3452  3836 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-29 16:23:50.314  3452  3836 D BatteryService: online:4, current avg:40, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:44
03-29 16:23:50.314  3452  3836 D BatteryService: stay LED for fully charged
03-29 16:23:50.314  3452  3452 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-29 16:23:50.319  3452  3452 I MotionRecognitionService: Plugged
03-29 16:23:50.319  3452  3452 D MotionRecognitionService:   cableConnection= 1
03-29 16:23:50.319  3452  3452 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-29 16:23:50.319  3452  3452 D MotionRecognitionService: skip setTransmitPower. 
,03-29 16:23:50.319  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-29 16:23:50.319  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-29 16:23:50.319  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-29 16:23:50.329  5848  5848 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-29 16:23:50.329  5848  5945 D HeadsetStateMachine: Disconnected process message: 10
,03-29 16:23:50.339  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-29 16:23:50.344  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-29 16:23:50.344  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-29 16:23:50.344  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-29 16:23:50.354 10280 11807 I System.out: Thread-1477(ApacheHTTPLog):isSBSettingEnabled false
03-29 16:23:50.354 10280 11807 I System.out: Thread-1477(ApacheHTTPLog):isShipBuild true
03-29 16:23:50.354 10280 11807 I System.out: Thread-1477(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-29 16:23:50.354 10280 11807 I System.out: Thread-1477(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-29 16:23:50.434 10280 10681 W IdleConnectionHandler: Removing a connection that never existed!
,03-29 16:23:50.574  3452  3653 V NetworkStats: performPollLocked(flags=0x1)
,03-29 16:23:50.574  3452  3653 D NtpTrustedTime: currentTimeMillis() cache hit
,03-29 16:23:50.594  3452  3653 V NetworkStats: performPollLocked() took 21ms
,03-29 16:23:50.599  3452  3653 D NtpTrustedTime: currentTimeMillis() cache hit
,03-29 16:23:50.599  3452  3654 D NtpTrustedTime: currentTimeMillis() cache hit
03-29 16:23:50.599  3452  3654 D NtpTrustedTime: currentTimeMillis() cache hit
,03-29 16:23:50.614 10280 11807 I System.out: P[5]_NetworkDispatch12 calls detatch()
,03-29 16:23:50.639  3452  3572 W ProcessCpuTracker: Skipping unknown process pid 11810
,03-29 16:23:50.669 10280 11814 I System.out: Thread-1478(ApacheHTTPLog):isSBSettingEnabled false
03-29 16:23:50.669 10280 11814 I System.out: Thread-1478(ApacheHTTPLog):isShipBuild true
03-29 16:23:50.669 10280 11814 I System.out: Thread-1478(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-29 16:23:50.669 10280 11814 I System.out: Thread-1478(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-29 16:23:50.694 11183 11246 I jxcore-log: # 40. Can connect to a remote peer
03-29 16:23:50.694 11183 11246 I jxcore-log: 
,03-29 16:23:50.739  3452  3599 D SecContentProvider2: query(), uri = 15 selection = getAppBlockDownloadState
,03-29 16:23:50.744  3753 11763 V DownloadManager: 1 items are running
,03-29 16:23:50.884  3452  6034 D SSRM:n  : SIOP:: AP = 280, PST = 285 (W:12), CUR = 40, LCD = 0
,03-29 16:23:51.254 11183 11246 I io.jxcore.node.ConnectionHelper: start: Port number: 39804, start advertisements: true
,03-29 16:23:51.254 11183 11246 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-29 16:23:51.254 11183 11246 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-29 16:23:51.254 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-29 16:23:51.259 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-29 16:23:51.259 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-29 16:23:51.259 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-29 16:23:51.259 11183 11246 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-29 16:23:51.264  5848  5938 D BtGatt.GattService: registerClient() - UUID=432cbb93-e04c-4b21-bf09-c2ca01bf556f
,03-29 16:23:51.264 10280 11814 I System.out: P[5]_NetworkDispatch13 calls detatch()
,03-29 16:23:51.304  5848  5919 D BtGatt.GattService: onClientRegistered() - UUID=432cbb93-e04c-4b21-bf09-c2ca01bf556f, clientIf=6
,03-29 16:23:51.304 11183 11195 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-29 16:23:51.304  5848  5857 D BtGatt.GattService: start scan with filters
,03-29 16:23:51.314  5848  5857 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 77
,03-29 16:23:51.314 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-29 16:23:51.314 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-29 16:23:51.314 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-29 16:23:51.314  5848  5944 D BtGatt.ScanManager: handling starting scan
03-29 16:23:51.314  5848  5944 D BtGatt.ScanManager: isFilteringSupported
03-29 16:23:51.314 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-29 16:23:51.314  5848  5944 D BluetoothAdapter: setting StandAloneBleMode
03-29 16:23:51.314 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 16:23:51.314 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-29 16:23:51.314 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-29 16:23:51.314 11183 11246 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-29 16:23:51.314 11183 11246 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 16:23:51.314 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 16:23:51.314 11183 11246 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-29 16:23:51.314 11183 11183 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-29 16:23:51.319  5848  5919 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,03-29 16:23:51.319  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:23:51.319  5848  5944 D BtGatt.ScanManager: allow scan with filters
03-29 16:23:51.319  5848  5944 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-29 16:23:51.319  5848  5944 D BtGatt.ScanManager: set filter index= 11 for clientIf= 6
,03-29 16:23:51.319  5848  5919 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,03-29 16:23:51.319  5848  5857 D BtGatt.GattService: registerClient() - UUID=d88aa51c-ef4e-437b-928c-fc9501aa2a13
,03-29 16:23:51.319  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:23:51.319  5848  5944 D BtGatt.ScanManager: Starting BLE batch scan
03-29 16:23:51.319  5848  5944 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-29 16:23:51.324  5848  5919 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,03-29 16:23:51.324  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 16:23:51.324  5848  5919 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-29 16:23:51.324  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 16:23:51.329 10280 11829 I System.out: Thread-1479(ApacheHTTPLog):isSBSettingEnabled false
03-29 16:23:51.329 10280 11829 I System.out: Thread-1479(ApacheHTTPLog):isShipBuild true
03-29 16:23:51.329 10280 11829 I System.out: Thread-1479(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-29 16:23:51.329 10280 11829 I System.out: Thread-1479(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-29 16:23:51.364  5848  5919 D BtGatt.GattService: onClientRegistered() - UUID=d88aa51c-ef4e-437b-928c-fc9501aa2a13, clientIf=7
,03-29 16:23:51.364 11183 11193 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-29 16:23:51.384  5848  5860 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 61
,03-29 16:23:51.384  5848  5941 D BtGatt.AdvertiseManager: message : 0
03-29 16:23:51.384  5848  5941 D BtGatt.AdvertiseManager: number of adv instance running0
,03-29 16:23:51.384  5848  5941 D BtGatt.AdvertiseManager: size of list is =0
,03-29 16:23:51.384  5848  5941 D BtGatt.AdvertiseManager: starting advertising
,03-29 16:23:51.384  5848  5941 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-29 16:23:51.389  5848  5919 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-29 16:23:51.389  5848  5941 D BtGatt.AdvertiseManager: starting multi advertising
,03-29 16:23:51.389  5848  5919 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-29 16:23:51.389  5848  5941 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,03-29 16:23:51.394  5848  5941 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
03-29 16:23:51.394 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-29 16:23:51.394 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-29 16:23:51.394 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-29 16:23:51.394 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-29 16:23:51.394 11183 11246 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-29 16:23:51.394 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-29 16:23:51.394 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-29 16:23:51.399 11183 11246 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-29 16:23:51.399 11183 11246 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-29 16:23:51.399 11183 11246 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-29 16:23:51.399 11183 11246 I io.jxcore.node.ConnectionHelper: start: OK
03-29 16:23:51.399 11183 11183 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-29 16:23:51.399 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-29 16:23:51.399 11183 11183 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-29 16:23:51.399 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-29 16:23:51.399 11183 11183 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
,03-29 16:23:51.399 11183 11183 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-29 16:23:51.399 11183 11183 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-29 16:23:51.399 11183 11183 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-29 16:23:51.399 11183 11183 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-29 16:23:51.399 11183 11183 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-29 16:23:51.399 11183 11183 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-29 16:23:51.399 11183 11183 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-29 16:23:51.399 11183 11830 D BluetoothSocket: bindListen(): myUserId = 0
03-29 16:23:51.399 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 16:23:51.399 11183 11246 I jxcore-log: 
,03-29 16:23:51.399 11183 11830 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-29 16:23:51.404 11183 11830 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[93]}
,03-29 16:23:51.404 11183 11246 I jxcore-log: ok 163 Can call startUpdateAdvertisingAndListening without error
03-29 16:23:51.404 11183 11246 I jxcore-log: 
03-29 16:23:51.404 11183 11830 D BluetoothSocket: bindListen(), new LocalSocket 
03-29 16:23:51.404 11183 11830 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-29 16:23:51.404 11183 11830 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1124d251
,03-29 16:23:51.404 11183 11830 D BluetoothSocket: channel: 6
03-29 16:23:51.404 11183 11830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-29 16:23:51.409 11183 11246 I io.jxcore.node.ConnectionHelper: start: Port number: 39804, start advertisements: false
,03-29 16:23:51.409 11183 11246 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-29 16:23:51.409 11183 11246 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
03-29 16:23:51.409 11183 11246 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 16:23:51.409 11183 11246 I io.jxcore.node.ConnectionHelper: start: OK
,03-29 16:23:51.409 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 16:23:51.409 11183 11246 I jxcore-log: 
,03-29 16:23:51.414 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-29 16:23:51.414 11183 11246 I jxcore-log: 
,03-29 16:23:51.414 11183 11246 I jxcore-log: ok 164 Can call startListeningForAdvertisements without error
03-29 16:23:51.414 11183 11246 I jxcore-log: 
,03-29 16:23:51.699 10280 11829 I System.out: P[5]_NetworkDispatch14 calls detatch()
,03-29 16:23:51.754 10280 11837 I System.out: Thread-1480(ApacheHTTPLog):isSBSettingEnabled false
03-29 16:23:51.754 10280 11837 I System.out: Thread-1480(ApacheHTTPLog):isShipBuild true
03-29 16:23:51.754 10280 11837 I System.out: Thread-1480(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-29 16:23:51.754 10280 11837 I System.out: Thread-1480(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-29 16:23:52.014  3452  3492 D ActivityManager: bindService callerProcessName:com.facebook.appmanager, calleePkgName: com.facebook.appmanager, action: null
,03-29 16:23:52.124 10280 11837 I System.out: P[5]_NetworkDispatch15 calls detatch()
,03-29 16:23:52.184 10280 11850 I System.out: Thread-1481(ApacheHTTPLog):isSBSettingEnabled false
03-29 16:23:52.184 10280 11850 I System.out: Thread-1481(ApacheHTTPLog):isShipBuild true
03-29 16:23:52.184 10280 11850 I System.out: Thread-1481(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-29 16:23:52.184 10280 11850 I System.out: Thread-1481(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-29 16:23:52.329  3452  3619 V AlarmManager: waitForAlarm result :4
,03-29 16:23:52.349  5848  5848 D BtGatt.ScanManager: awakened up at time 258026
03-29 16:23:52.354  5848  5944 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-29 16:23:52.364  5848  5919 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=3
03-29 16:23:52.364  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:23:52.364  5848  5919 D BtGatt.GattService: current time is 258042163821
03-29 16:23:52.364  5848  5919 D BtGatt.GattService: Batch record : [4, -43, 6, -91, 34, 116, 1, -128, -77, 4, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, 105, 13, 48, -123, -100, 92, 1, -128, -65, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0, 4, -43, 6, -91, 34, 116, 1, -128, -85, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-29 16:23:52.364  5848  5919 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-29 16:23:52.364  5848  5919 D ScanRecord: parseFromBytes
03-29 16:23:52.364  5848  5919 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-29 16:23:52.364  5848  5919 D ScanRecord: parseFromBytes
03-29 16:23:52.364  5848  5919 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-29 16:23:52.364  5848  5919 D ScanRecord: parseFromBytes
03-29 16:23:52.364  5848  5919 D BtGatt.GattService: result: ScanResult{mDevice=5C:9C:85:30:0D:69, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-65, mTimestampNanos=258042342154}
03-29 16:23:52.364  5848  5919 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-29 16:23:52.364  5848  5919 D BtGatt.GattService: result: ScanResult{mDevice=74:22:A5:06:D5:04, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-77, mTimestampNanos=257842342154}
03-29 16:23:52.364  5848  5919 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-29 16:23:52.364  5848  5919 D BtGatt.GattService: result: ScanResult{mDevice=74:22:A5:06:D5:04, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-85, mTimestampNanos=258042342154}
03-29 16:23:52.364  5848  5919 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-29 16:23:52.364 11183 11193 D ScanRecord: parseFromBytes
03-29 16:23:52.364 11183 11193 D ScanRecord: parseFromBytes
03-29 16:23:52.364 11183 11193 D ScanRecord: parseFromBytes
03-29 16:23:52.364 11183 11183 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:CF,:C5:D9:E5:61], added - the peer count is 1
03-29 16:23:52.369 11183 11183 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 2
03-29 16:23:52.369 11183 11183 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
03-29 16:23:52.369 11183 11183 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:CF:C5:D9:E5:61], Bluetooth address: F8:CF:C5:D9:E5:61, device name: , device address: 
03-29 16:23:52.369 11183 11183 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
,03-29 16:23:52.374 11183 11246 I jxcore-log: INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"F8:CF:C5:D9:E5:61","peerAvailable":true,"pleaseConnect":false}],
03-29 16:23:52.374 11183 11246 I jxcore-log: 
,03-29 16:23:52.384 11183 11246 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID F8:CF:C5:D9:E5:61
,03-29 16:23:52.389 11183 11246 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> F8:CF:C5:D9:E5:61]
,03-29 16:23:52.389 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address F8:CF:C5:D9:E5:61
,03-29 16:23:52.394 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
03-29 16:23:52.394 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
03-29 16:23:52.394 11183 11246 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null F8:CF:C5:D9:E5:61
03-29 16:23:52.394 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address F8:CF:C5:D9:E5:61
03-29 16:23:52.394 11183 11246 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: F8:CF:C5:D9:E5:61)
,03-29 16:23:52.394 11183 11246 I jxcore-log: INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"pleaseConnect":false}]
03-29 16:23:52.394 11183 11246 I jxcore-log: 
,03-29 16:23:52.399 11183 11855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address F8:CF:C5:D9:E5:61 (thread ID: 1546),
,03-29 16:23:52.409 11183 11855 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
03-29 16:23:52.409 11183 11855 D BluetoothSocket: connect(): myUserId = 0
03-29 16:23:52.409 11183 11855 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-29 16:23:52.409  5848  5860 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-29 16:23:52.409  5848  5997 D IOP_DB_BT: db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-29 16:23:52.409  5848  5997 D IOP_DB_BT: db_query_add_key: key KEY_LMP_MFCT, value 15
03-29 16:23:52.409  5848  5997 D IOP_DB_BT: db_query_add_key: key KEY_LMP_VER, value 7:8975
03-29 16:23:52.409  5848  5997 D IOP_DB_BT: db_query_add_key: key KEY_DIR_ALL, value 1
03-29 16:23:52.409  5848  5997 D IOP_DB_BT: db_query_execute: result 1
,03-29 16:23:52.409  5848  5997 W bt-btif : bta_dm_acl_change(), event : 2
,03-29 16:23:52.414 11183 11855 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[112]}
,03-29 16:23:52.424  3452  3492 D SecContentProvider2: query(), uri = 15 selection = getAppBlockDownloadState
,03-29 16:23:52.424  3753 11763 V DownloadManager: 1 items are running
,03-29 16:23:52.919 10280 11850 I System.out: P[5]_NetworkDispatch16 calls detatch()
,03-29 16:23:52.984 10280 11861 I System.out: Thread-1482(ApacheHTTPLog):isSBSettingEnabled false
,03-29 16:23:52.984 10280 11861 I System.out: Thread-1482(ApacheHTTPLog):isShipBuild true
,03-29 16:23:52.984 10280 11861 I System.out: Thread-1482(ApacheHTTPLog):SMARTBONDING_ENABLED is false
,03-29 16:23:52.984 10280 11861 I System.out: Thread-1482(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-29 16:23:53.379  3452  3619 V AlarmManager: waitForAlarm result :4
,03-29 16:23:53.384  5848  5848 D BtGatt.ScanManager: awakened up at time 259062
03-29 16:23:53.389  5848  5944 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-29 16:23:53.389  5848  5919 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
03-29 16:23:53.389  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:23:53.389  5848  5919 D BtGatt.GattService: current time is 259069419571
03-29 16:23:53.389  5848  5919 D BtGatt.GattService: Batch record : [105, 13, 48, -123, -100, 92, 1, -128, -60, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0, 4, -43, 6, -91, 34, 116, 1, -128, -74, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-29 16:23:53.389  5848  5919 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-29 16:23:53.394  5848  5919 D ScanRecord: parseFromBytes
,03-29 16:23:53.394  5848  5919 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81],
03-29 16:23:53.394  5848  5919 D ScanRecord: parseFromBytes,
,03-29 16:23:53.394  5848  5919 D BtGatt.GattService: result: ScanResult{mDevice=74:22:A5:06:D5:04, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-74, mTimestampNanos=259019624987},
03-29 16:23:53.394  5848  5919 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null],
,03-29 16:23:53.394  5848  5919 D BtGatt.GattService: result: ScanResult{mDevice=5C:9C:85:30:0D:69, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-60, mTimestampNanos=259019624987},
,03-29 16:23:53.394  5848  5919 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-29 16:23:53.394 11183 11195 D ScanRecord: parseFromBytes
,03-29 16:23:53.394 11183 11195 D ScanRecord: parseFromBytes,
,03-29 16:23:53.394 11183 11183 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
,03-29 16:23:53.394 11183 11183 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:CF:C5:D9:E5:61] updated - the peer count is 2
03-29 16:23:53.419 10280 11861 I System.out: P[5]_NetworkDispatch17 calls detatch()
,03-29 16:23:53.439  5848  5997 W bt-btif : bta_dm_acl_change(), event : 2
03-29 16:23:53.439  5848  5997 W bt-btif : bta_dm_acl_change(), event : 4
03-29 16:23:53.439  5848  5997 W bt-btif : scb return value : 1
,03-29 16:23:53.484 10280 11861 I System.out: Thread-1482(ApacheHTTPLog):isSBSettingEnabled false
03-29 16:23:53.484 10280 11861 I System.out: Thread-1482(ApacheHTTPLog):isShipBuild true
03-29 16:23:53.484 10280 11861 I System.out: Thread-1482(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-29 16:23:53.484 10280 11861 I System.out: Thread-1482(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-29 16:23:53.804 10280 11861 I System.out: P[5]_NetworkDispatch17 calls detatch()
,03-29 16:23:53.824  5848  5997 D IOP_DB_BT: db_query: id SkipSdpInfo :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-29 16:23:53.824  5848  5997 D IOP_DB_BT: db_query: result 1
,03-29 16:23:53.829  5848  5997 D IOP_DB_BT: db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-29 16:23:53.829  5848  5997 D IOP_DB_BT: db_query_add_key: key KEY_LMP_MFCT, value 15
03-29 16:23:53.829  5848  5997 D IOP_DB_BT: db_query_add_key: key KEY_LMP_VER, value 7:8975
03-29 16:23:53.829  5848  5997 D IOP_DB_BT: db_query_add_key: key KEY_DIR_ALL, value *
03-29 16:23:53.829  5848  5997 D IOP_DB_BT: db_query_execute: result 1
03-29 16:23:53.829  5848  5997 W bt-btif : bta_dm_acl_change(), event : 0
03-29 16:23:53.829  5848  5997 W bt-btif : info:x10
03-29 16:23:53.829  5848  5997 W bt-btif : bta_dm_acl_change(), event : 2
,03-29 16:23:53.829  5848  5919 D         : remote version info [f8:cf:c5:d9:e5:61]: 7, f, 230f
03-29 16:23:53.834  5848  5919 E BluetoothRemoteDevices: aclStateChangeCallback: Device is NULL
,03-29 16:23:54.009  3452  4020 D SecContentProvider2: query(), uri = 15 selection = getAppBlockDownloadState
,03-29 16:23:54.014  3753 11763 V DownloadManager: 1 items are running
,03-29 16:23:54.329  5848  5919 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,03-29 16:23:54.404  3452  3619 V AlarmManager: waitForAlarm result :4
,03-29 16:23:54.409  5848  5848 D BtGatt.ScanManager: awakened up at time 260087
03-29 16:23:54.414  5848  5944 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-29 16:23:54.414  5848  5919 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
,03-29 16:23:54.414  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:23:54.419  5848  5919 D BtGatt.GattService: current time is 260096320113
,03-29 16:23:54.419  5848  5919 D BtGatt.GattService: Batch record : [105, 13, 48, -123, -100, 92, 1, -128, -61, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0, 4, -43, 6, -91, 34, 116, 1, -128, -75, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,03-29 16:23:54.419  5848  5919 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-29 16:23:54.419  5848  5919 D ScanRecord: parseFromBytes,
,03-29 16:23:54.419  5848  5919 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81],
03-29 16:23:54.419  5848  5919 D ScanRecord: parseFromBytes
,03-29 16:23:54.419  5848  5919 D BtGatt.GattService: result: ScanResult{mDevice=74:22:A5:06:D5:04, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-75, mTimestampNanos=260046642779},
,03-29 16:23:54.419  5848  5919 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
,03-29 16:23:54.419  5848  5919 D BtGatt.GattService: result: ScanResult{mDevice=5C:9C:85:30:0D:69, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-61, mTimestampNanos=259996642779}
,03-29 16:23:54.419  5848  5919 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
,03-29 16:23:54.439 11183 11193 D ScanRecord: parseFromBytes
03-29 16:23:54.439 11183 11193 D ScanRecord: parseFromBytes
,03-29 16:23:54.439 11183 11183 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
03-29 16:23:54.439 11183 11183 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:CF:C5:D9:E5:61] updated - the peer count is 2
,03-29 16:23:55.019  5848  5997 W bt-sdp  : process_service_search_attr_rsp
,03-29 16:23:55.289  5848  5919 W bt-btif : btif_dm_ssp_cfm_req_evt
,03-29 16:23:55.294  5848  5919 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,03-29 16:23:55.309  5848  5919 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
03-29 16:23:55.309  5848  5919 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:CF:C5:D9:E5:61 newState: 1
,03-29 16:23:55.314  3452  3492 D SecContentProvider: query(), uri = 4 selection = bluetoothLogForRemote
03-29 16:23:55.319  5848  5919 E bt-btif : check_cod: remote_cod = 0x5a020c
03-29 16:23:55.319  5848  5919 W bt-btif : btif_dm_ssp_reply: accept=1
,03-29 16:23:55.334  5848  5924 I BluetoothBondStateMachine: Bond State Change Intent:F8:CF:C5:D9:E5:61 OldState: 10 NewState: 11
03-29 16:23:55.339  3452  3452 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
03-29 16:23:55.339  3452  3452 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.device.action.BOND_STATE_CHANGED
,03-29 16:23:55.344  3452  3452 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED
03-29 16:23:55.344  3452  3452 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 10
03-29 16:23:55.344  3452  3452 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 11
03-29 16:23:55.344  3452  3452 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
,03-29 16:23:55.349 10280 10680 W IdleConnectionHandler: Removing a connection that never existed!
,03-29 16:23:55.354  3726  3726 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,03-29 16:23:55.359  3726  4745 D BluetoothTile:  handleUpdatestate:false name:null
03-29 16:23:55.359  3452  3572 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7bdd537 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{1e4b0d55 10251:com.android.settings/1000}
,03-29 16:23:55.359  3452  3492 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
,03-29 16:23:55.359  5848  5924 D BtConfig.SecureMode: isSecureModeOn:false
03-29 16:23:55.359  5848  5924 I BluetoothBondStateMachine: Entering PendingCommandState State
,03-29 16:23:55.364 10251 10251 D BluetoothNotiBroadcastReceiver: onReceive
,03-29 16:23:55.374  3452  4399 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7bdd537 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{3f3c0ed4 10322:com.sec.android.automotive.drivelink/u0a102}
,03-29 16:23:55.374 10322 10322 D [CarMode]: [AutoLaunchReceiver]-action: android.bluetooth.device.action.BOND_STATE_CHANGED
,03-29 16:23:55.379 10322 11889 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,03-29 16:23:55.379 10322 10322 D [CarMode]: [AutoLaunchReceiver]-ACTION_BOND_STATE_CHANGED Nexus 6 state is 11
03-29 16:23:55.379 10322 10322 D [CarModeFW]: ConnectivityManager-handleMessage PAIRING_DEVICES
,03-29 16:23:55.384  3452  3599 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7bdd537 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{3f3c0ed4 10322:com.sec.android.automotive.drivelink/u0a102}
,03-29 16:23:55.389  3452  3491 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
,03-29 16:23:55.394 10322 11890 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,03-29 16:23:55.394 10322 10322 D [CarModeFW]: ConnectivityManager-handleMessage PAIRING_DEVICES
,03-29 16:23:55.399  3452  4028 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7bdd537 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{2d500a3d 10477:com.samsung.android.app.watchmanagerstub/u0a121}
,03-29 16:23:55.414 10477 10477 E BluetoothHeadset: BTStateChangeCB is registed
,03-29 16:23:55.414 10477 10477 D GMHFPReceiver: android.bluetooth.device.action.BOND_STATE_CHANGED
,03-29 16:23:55.414 10477 10477 D GMHFPReceiver: jangil::setProperties()
,03-29 16:23:55.419 10477 10477 D GMHFPReceiver: jangil::printBTStatus()
,03-29 16:23:55.419  3452  4010 D SettingsProvider: name = Wearable0001
,03-29 16:23:55.419  3452  4010 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-29 16:23:55.419  3452  4010 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-29 16:23:55.419  3452  4010 D SettingsProvider: selectionArgs: false
03-29 16:23:55.419  3452  4010 D SettingsProvider: selectionArgs: 10121
03-29 16:23:55.419  3452  4010 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,03-29 16:23:55.424  3452  4010 D SettingsProvider: ret = -1
,03-29 16:23:55.424  3452  4010 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10121
,03-29 16:23:55.429 10477 10477 D GMHFPReceiver: ::::::::Wearable0001::false
,03-29 16:23:55.429  3452  4020 D SettingsProvider: name = Wearable0002
03-29 16:23:55.429  3452  4020 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,03-29 16:23:55.429  3452  4020 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-29 16:23:55.429  3452  4020 D SettingsProvider: selectionArgs: false
03-29 16:23:55.429  3452  4020 D SettingsProvider: selectionArgs: 10121
03-29 16:23:55.429  3452  4020 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
03-29 16:23:55.429  3452  4020 D SettingsProvider: ret = -1
,03-29 16:23:55.439  3452  4020 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10121
,03-29 16:23:55.439  3726  3726 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-29 16:23:55.439 10477 10477 D GMHFPReceiver: ::::::::Wearable0002::false
,03-29 16:23:55.444  5848  5919 W bt-btif : btif_dm_auth_cmpl_evt
,03-29 16:23:55.444  3452  3619 V AlarmManager: waitForAlarm result :4
03-29 16:23:55.444  5848  5919 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,03-29 16:23:55.449  3452  3914 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7bdd537 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{15b9f192 4462:com.google.android.gms.persistent/u0a14}
,03-29 16:23:55.454  5848  5848 D BtGatt.ScanManager: awakened up at time 261134
,03-29 16:23:55.459  5848  5944 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-29 16:23:55.464  3726  3726 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-29 16:23:55.464  5848  5919 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:CF:C5:D9:E5:61 newState: 0
,03-29 16:23:55.464  5848  5924 D BluetoothAdapterProperties: Failed to remove device: F8:CF:C5:D9:E5:61
,03-29 16:23:55.469  3452  4020 D SecContentProvider: query(), uri = 4 selection = bluetoothLogForRemote
,03-29 16:23:55.469  5848  5919 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
03-29 16:23:55.469  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:23:55.469  5848  5919 D BtGatt.GattService: current time is 261145700488
03-29 16:23:55.469  5848  5919 D BtGatt.GattService: Batch record : [4, -43, 6, -91, 34, 116, 1, -128, -78, 9, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, 105, 13, 48, -123, -100, 92, 1, -128, -60, 10, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0]
03-29 16:23:55.469  5848  5919 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-29 16:23:55.469  5848  5919 D ScanRecord: parseFromBytes
,03-29 16:23:55.469  5848  5919 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-29 16:23:55.469  5848  5919 D ScanRecord: parseFromBytes
03-29 16:23:55.469  5848  5919 D BtGatt.GattService: result: ScanResult{mDevice=5C:9C:85:30:0D:69, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-60, mTimestampNanos=260645842071}
03-29 16:23:55.469  5848  5919 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-29 16:23:55.469  5848  5919 D BtGatt.GattService: result: ScanResult{mDevice=74:22:A5:06:D5:04, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-78, mTimestampNanos=260695842071}
03-29 16:23:55.469  5848  5919 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-29 16:23:55.469 11183 11195 D ScanRecord: parseFromBytes
03-29 16:23:55.469 11183 11195 D ScanRecord: parseFromBytes
,03-29 16:23:55.469 11183 11183 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:CF:C5:D9:E5:61] updated - the peer count is 2
03-29 16:23:55.469 11183 11183 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
,03-29 16:23:55.474  5848  5924 I BluetoothBondStateMachine: Bond State Change Intent:F8:CF:C5:D9:E5:61 OldState: 11 NewState: 10
,03-29 16:23:55.474  3452  3452 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
03-29 16:23:55.474  3452  3452 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.device.action.BOND_STATE_CHANGED
03-29 16:23:55.474  3452  3452 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED,
03-29 16:23:55.474  3452  3452 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 11
03-29 16:23:55.474  3452  3452 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 10
03-29 16:23:55.474  3452  3452 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
,03-29 16:23:55.479  3726  3726 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,03-29 16:23:55.479  3726  4745 D BluetoothTile:  handleUpdatestate:false name:null
,03-29 16:23:55.484  3452  3572 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{22e6620e u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{1e4b0d55 10251:com.android.settings/1000},
03-29 16:23:55.484  5848  5924 D BtConfig.SecureMode: isSecureModeOn:false
03-29 16:23:55.484  3452  3998 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
03-29 16:23:55.484 10251 10251 D BluetoothNotiBroadcastReceiver: onReceive
,03-29 16:23:55.489 10322 11894 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,03-29 16:23:55.494  5848  5924 D HidService: getHidService(): returning com.android.bluetooth.hid.HidService@1558a83b
,03-29 16:23:55.494  3452  4399 D SettingsProvider: name = bluetooth_input_device_priority_F8:CF:C5:D9:E5:61
03-29 16:23:55.494  3452  4399 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-29 16:23:55.494  3452  4399 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-29 16:23:55.494  3452  3651 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{22e6620e u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{3f3c0ed4 10322:com.sec.android.automotive.drivelink/u0a102}
03-29 16:23:55.494  3452  4399 D SettingsProvider: selectionArgs: false
03-29 16:23:55.494  3452  4399 D SettingsProvider: selectionArgs: 1002
03-29 16:23:55.494  3452  4399 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,03-29 16:23:55.494 10322 10322 D [CarMode]: [AutoLaunchReceiver]-action: android.bluetooth.device.action.BOND_STATE_CHANGED
03-29 16:23:55.494  3452  4399 D SettingsProvider: ret = -1
03-29 16:23:55.494  5848  5924 D HidService: Saved priority F8:CF:C5:D9:E5:61 = -1
,03-29 16:23:55.499  3452  3491 D SettingsProvider: name = bluetooth_a2dp_sink_priority_F8:CF:C5:D9:E5:61
03-29 16:23:55.499  3452  3491 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-29 16:23:55.499  3452  3491 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-29 16:23:55.499  3452  3491 D SettingsProvider: selectionArgs: false
03-29 16:23:55.499  3452  3491 D SettingsProvider: selectionArgs: 1002
03-29 16:23:55.499  3452  3491 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,03-29 16:23:55.499  3452  3491 D SettingsProvider: ret = -1
,03-29 16:23:55.499 10322 10322 D [CarMode]: [AutoLaunchReceiver]-ACTION_BOND_STATE_CHANGED Nexus 6 state is 10
03-29 16:23:55.499  3452  3914 D SettingsProvider: name = bluetooth_headset_priority_F8:CF:C5:D9:E5:61
03-29 16:23:55.499  3452  3914 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-29 16:23:55.499  3452  3914 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-29 16:23:55.499  3452  3914 D SettingsProvider: selectionArgs: false
03-29 16:23:55.499  3452  3914 D SettingsProvider: selectionArgs: 1002
03-29 16:23:55.499  3452  3914 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,03-29 16:23:55.499  3452  3914 D SettingsProvider: ret = -1
03-29 16:23:55.499  5848  5924 I BluetoothBondStateMachine: StableState(): Entering Off State
,03-29 16:23:55.504  3452  3836 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{22e6620e u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{3f3c0ed4 10322:com.sec.android.automotive.drivelink/u0a102}
,03-29 16:23:55.504  3452  4399 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
,03-29 16:23:55.514 10322 11895 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,03-29 16:23:55.514  3452  3836 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{22e6620e u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{2d500a3d 10477:com.samsung.android.app.watchmanagerstub/u0a121}
,03-29 16:23:55.519 10477 10477 E BluetoothHeadset: BTStateChangeCB is registed
,03-29 16:23:55.519 10477 10477 D GMHFPReceiver: android.bluetooth.device.action.BOND_STATE_CHANGED
03-29 16:23:55.524 10477 10477 D GMHFPReceiver: jangil::setProperties()
,03-29 16:23:55.524 10477 10477 D GMHFPReceiver: jangil::printBTStatus()
,03-29 16:23:55.524  3452  3651 D SettingsProvider: name = Wearable0001
03-29 16:23:55.524  3452  3651 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-29 16:23:55.524  3452  3651 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-29 16:23:55.524  3452  3651 D SettingsProvider: selectionArgs: false
03-29 16:23:55.524  3452  3651 D SettingsProvider: selectionArgs: 10121
03-29 16:23:55.524  3452  3651 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,03-29 16:23:55.524  3452  3651 D SettingsProvider: ret = -1
03-29 16:23:55.524 10477 10477 D GMHFPReceiver: ::::::::Wearable0001::false
,03-29 16:23:55.524  3452  3998 D SettingsProvider: name = Wearable0002
,03-29 16:23:55.524  3452  3998 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-29 16:23:55.524  3452  3998 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-29 16:23:55.524  3452  3998 D SettingsProvider: selectionArgs: false
03-29 16:23:55.524  3452  3998 D SettingsProvider: selectionArgs: 10121
03-29 16:23:55.524  3452  3998 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,03-29 16:23:55.529  3452  3998 D SettingsProvider: ret = -1
03-29 16:23:55.529 10477 10477 D GMHFPReceiver: ::::::::Wearable0002::false
,03-29 16:23:55.529 10477 10477 D GMHFPReceiver: onServiceConnected() : 1
03-29 16:23:55.529 10477 10477 D GMHFPReceiver: mBluetoothHeadset = true
,03-29 16:23:55.534  3452  3914 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{22e6620e u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{15b9f192 4462:com.google.android.gms.persistent/u0a14}
,03-29 16:23:55.624 10477 10477 D GMHFPReceiver: onServiceConnected() : 1
,03-29 16:23:55.624 10477 10477 D GMHFPReceiver: mBluetoothHeadset = true
,03-29 16:23:55.899  3452  3492 I art     : Explicit concurrent mark sweep GC freed 47949(3MB) AllocSpace objects, 52(3MB) LOS objects, 33% free, 29MB/44MB, paused 2.860ms total 182.540ms
,03-29 16:23:55.909  3452  3914 D SecContentProvider2: query(), uri = 15 selection = getAppBlockDownloadState
,03-29 16:23:55.909  3753 11763 V DownloadManager: 1 items are running
,03-29 16:23:56.354  3452  3572 W ProcessCpuTracker: Skipping unknown process pid 11913
,03-29 16:23:56.469  3452  3619 V AlarmManager: waitForAlarm result :4
,03-29 16:23:56.484  5848  5848 D BtGatt.ScanManager: awakened up at time 262160
,03-29 16:23:56.494  5848  5944 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6,
,03-29 16:23:56.499  5848  5919 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2,
,03-29 16:23:56.499  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,03-29 16:23:56.499  5848  5919 D BtGatt.GattService: current time is 262179595404,
,03-29 16:23:56.499  5848  5919 D BtGatt.GattService: Batch record : [4, -43, 6, -91, 34, 116, 1, -128, -64, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, 105, 13, 48, -123, -100, 92, 1, -128, -62, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0],
,03-29 16:23:56.504  5848  5919 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-29 16:23:56.504  5848  5919 D ScanRecord: parseFromBytes,
03-29 16:23:56.504  5848  5919 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
,03-29 16:23:56.504  5848  5919 D ScanRecord: parseFromBytes
,03-29 16:23:56.504  5848  5919 D BtGatt.GattService: result: ScanResult{mDevice=5C:9C:85:30:0D:69, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-62, mTimestampNanos=262080455779}
,03-29 16:23:56.504  5848  5919 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
,03-29 16:23:56.504  5848  5919 D BtGatt.GattService: result: ScanResult{mDevice=74:22:A5:06:D5:04, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-64, mTimestampNanos=262080455779}
,03-29 16:23:56.504  5848  5919 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
,03-29 16:23:56.509 11183 11193 D ScanRecord: parseFromBytes
03-29 16:23:56.509 11183 11193 D ScanRecord: parseFromBytes
,03-29 16:23:56.509 11183 11183 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:CF:C5:D9:E5:61] updated - the peer count is 2
,03-29 16:23:56.509 11183 11183 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
,03-29 16:23:57.514  3452  3619 V AlarmManager: waitForAlarm result :4
,03-29 16:23:57.529  5848  5848 D BtGatt.ScanManager: awakened up at time 263207
,03-29 16:23:57.534  5848  5944 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-29 16:23:57.544  5848  5919 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=8
03-29 16:23:57.544  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:23:57.544  5848  5919 D BtGatt.GattService: current time is 263222299780
03-29 16:23:57.544  5848  5919 D BtGatt.GattService: Batch record : [4, -43, 6, -91, 34, 116, 1, -128, -65, 12, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, 105, 13, 48, -123, -100, 92, 1, -128, -63, 14, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0, -43, 57, -50, 16, 56, 71, 1, -128, -53, 12, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0, -22, -37, -37, 8, 35, 84, 1, -128, -66, 11, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0, -108, 120, 21, 91, -93, 119, 1, -128, -65, 11, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, 98, 120, 115, -83, -114, 124, 1, -128, -66, 10, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0, -52, -9, 125, 34, 27, 92, 1, -128, -76, 10, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, 0, -117, -16, 115, -72, 77, 1, -128, -76, 9, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-29 16:23:57.544  5848  5919 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-29 16:23:57.544  5848  5919 D ScanRecord: parseFromBytes
03-29 16:23:57.544  5848  5919 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-29 16:23:57.544  5848  5919 D ScanRecord: parseFromBytes
03-29 16:23:57.544  5848  5919 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-29 16:23:57.544  5848  5919 D ScanRecord: parseFromBytes
03-29 16:23:57.544  5848  5919 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-29 16:23:57.544  5848  5919 D ScanRecord: parseFromBytes
03-29 16:23:57.544  5848  5919 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-29 16:23:57.544  5848  5919 D ScanRecord: parseFromBytes
03-29 16:23:57.544  5848  5919 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-29 16:23:57.544  5848  5919 D ScanRecord: parseFromBytes
03-29 16:23:57.544  5848  5919 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-29 16:23:57.544  5848  5919 D ScanRecord: parseFromBytes
03-29 16:23:57.544  5848  5919 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-29 16:23:57.544  5848  5919 D ScanRecord: parseFromBytes
03-29 16:23:57.544  5848  5919 D BtGatt.GattService: result: ScanResult{mDevice=7,C:8E:AD:73:78:62, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-66, mTimestampNanos=262722813071}
03-29 16:23:57.549  5848  5919 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-29 16:23:57.549  5848  5919 D BtGatt.GattService: result: ScanResult{mDevice=74:22:A5:06:D5:04, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-65, mTimestampNanos=262622813071}
03-29 16:23:57.549  5848  5919 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-29 16:23:57.549  5848  5919 D BtGatt.GattService: result: ScanResult{mDevice=4D:B8:73:F0:8B:00, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-76, mTimestampNanos=262772813071},
,03-29 16:23:57.549  5848  5919 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null],
03-29 16:23:57.549  5848  5919 D BtGatt.GattService: result: ScanResult{mDevice=47:38:10:CE:39:D5, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-53, mTimestampNanos=262622813071}
03-29 16:23:57.549  5848  5919 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null],
03-29 16:23:57.549  5848  5919 D BtGatt.GattService: result: ScanResult{mDevice=54:23:08:DB:DB:EA, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-66, mTimestampNanos=262672813071}
03-29 16:23:57.549  5848  5919 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-29 16:23:57.549  5848  5919 D BtGatt.GattService: result: ScanResult{mDevice=77:A3:5B:15:78:94, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-65, mTimestampNanos=262672813071}
03-29 16:23:57.549  5848  5919 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
,03-29 16:23:57.549  5848  5919 D BtGatt.GattService: result: ScanResult{mDevice=5C:1B:22:7D:F7:CC, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-76, mTimestampNanos=262722813071}
03-29 16:23:57.549  5848  5919 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-29 16:23:57.549  5848  5919 D BtGatt.GattService: result: ScanResult{mDevice=5C:9C:85:30:0D:69, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-63, mTimestampNanos=262522813071}
03-29 16:23:57.549  5848  5919 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-29 16:23:57.549 11183 11195 D ScanRecord: parseFromBytes
03-29 16:23:57.549 11183 11195 D ScanRecord: parseFromBytes,
03-29 16:23:57.549 11183 11195 D ScanRecord: parseFromBytes
03-29 16:23:57.549 11183 11195 D ScanRecord: parseFromBytes
03-29 16:23:57.549 11183 11195 D ScanRecord: parseFromBytes
03-29 16:23:57.549 11183 11195 D ScanRecord: parseFromBytes
03-29 16:23:57.549 11183 11195 D ScanRecord: parseFromBytes
03-29 16:23:57.549 11183 11195 D ScanRecord: parseFromBytes
03-29 16:23:57.549 11183 11183 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:CF:C5:D9:E5:61] updated - the peer count is 2
03-29 16:23:57.549 11183 11183 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
03-29 16:23:57.549 11183 11183 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
,03-29 16:23:57.549 11183 11183 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:CF:C5:D9:E5:61] updated - the peer count is 2
03-29 16:23:57.549 11183 11183 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:CF:C5:D9:E5:61] updated - the peer count is 2
03-29 16:23:57.549 11183 11183 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
03-29 16:23:57.549 11183 11183 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
03-29 16:23:57.549 11183 11183 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:CF:C5:D9:E5:61] updated - the peer count is 2
,03-29 16:23:58.264  5848  5997 W bt-btif : new conn_srvc id:26, app_id:255
03-29 16:23:58.264  5848  5997 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
03-29 16:23:58.264  5848  5997 W bt-btif : bta_dm_pm_ssr:2, lat:1200
,03-29 16:23:58.264 11183 11830 D BluetoothSocket: socket fd passed by stack  fds: [Ljava.io.FileDescriptor;@26a6e8fd
,03-29 16:23:58.274  5848  5938 E BluetoothRemoteDevices: setRfcommConnected true,
,03-29 16:23:58.279 11183 11830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection accepted
,03-29 16:23:58.289 11183 11830 D BluetoothSocket: getInputStream(): myUserId = 0
,03-29 16:23:58.294 11183 11830 D BluetoothSocket: getOutputStream(): myUserId = 0
,03-29 16:23:58.294 11183 11830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection initialized (thread ID: 1547)
,03-29 16:23:58.294 11183 11830 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@bc79f2, channel: 6, state: LISTENING
03-29 16:23:58.294 11183 11830 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@bc79f2, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1124d251, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@93d843mSocket: android.net.LocalSocket@11a9aec0 impl:android.net.LocalSocketImpl@20fe17f9 fd:FileDescriptor[93]
,03-29 16:23:58.294 11183 11830 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@11a9aec0 impl:android.net.LocalSocketImpl@20fe17f9 fd:FileDescriptor[93]
,03-29 16:23:58.299 11183 11830 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-29 16:23:58.304 11183 11830 D BluetoothSocket: bindListen(): myUserId = 0
,03-29 16:23:58.304 11183 11830 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-29 16:23:58.304 11183 11830 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[113]}
,03-29 16:23:58.309 11183 11830 D BluetoothSocket: bindListen(), new LocalSocket 
03-29 16:23:58.309 11183 11830 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-29 16:23:58.309 11183 11830 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3b14433e
,03-29 16:23:58.309 11183 11830 D BluetoothSocket: channel: 6
03-29 16:23:58.309 11183 11830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-29 16:23:58.309 11183 11920 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 1547)
,03-29 16:23:58.389  5848  5997 W bt-btif : new conn_srvc id:26, app_id:1
03-29 16:23:58.389  5848  5997 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
03-29 16:23:58.389  5848  5997 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:1
03-29 16:23:58.389  5848  5997 W bt-btif : bta_dm_pm_ssr:2, lat:1200
,03-29 16:23:58.394  5848  5860 E BluetoothRemoteDevices: setRfcommConnected true,
,03-29 16:23:58.414 11183 11855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onSocketConnected: [<no peer name> F8:CF:C5:D9:E5:61] (thread ID: 1546)
03-29 16:23:58.414 11183 11855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 1546)
,03-29 16:23:58.414 11183 11855 D BluetoothSocket: getInputStream(): myUserId = 0
,03-29 16:23:58.419 11183 11855 D BluetoothSocket: getOutputStream(): myUserId = 0
,03-29 16:23:58.419 11183 11855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesWritten: 15 bytes successfully written (thread ID: 1548)
03-29 16:23:58.419 11183 11855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Outgoing connection initialized (*handshake* thread ID: 1548)
03-29 16:23:58.419 11183 11855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1546)
03-29 16:23:58.419 11183 11924 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 1548)
,03-29 16:23:58.564  3452  3619 V AlarmManager: waitForAlarm result :4
,03-29 16:23:58.574  5848  5848 D BtGatt.ScanManager: awakened up at time 264254
,03-29 16:23:58.584  5848  5944 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-29 16:23:58.584  5848  5919 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0,
,03-29 16:23:58.584  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,03-29 16:23:58.604  5848  5997 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61,
03-29 16:23:58.604  5848  5997 D IOP_DB_BT: db_query: result 1
03-29 16:23:58.604  5848  5997 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-29 16:23:58.604  5848  5997 D IOP_DB_BT: db_query: result 1
03-29 16:23:58.604 11183 11920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesRead: Read 15 bytes successfully (thread ID: 1547)
03-29 16:23:58.604 11183 11920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Got valid identity from [<no peer name> F8:CF:C5:D9:E5:61]
03-29 16:23:58.604  5848  5997 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-29 16:23:58.604  5848  5997 D IOP_DB_BT: db_query: result 1
03-29 16:23:58.604  5848  5997 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61,
03-29 16:23:58.604  5848  5997 D IOP_DB_BT: db_query: result 1
03-29 16:23:58.609 11183 11920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesWritten: 15 bytes successfully written (thread ID: 1547)
03-29 16:23:58.609 11183 11920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: removeThreadFromList: Removing thread with ID 1547
03-29 16:23:58.609 11183 11920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Handshake thread disposed (thread ID: 1547)
03-29 16:23:58.609 11183 11920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onIncomingConnectionConnected: [<no peer name> F8:CF:C5:D9:E5:61]
03-29 16:23:58.609 11183 11183 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:CF:C5:D9:E5:61]
,03-29 16:23:58.609 11183 11183 I io.jxcore.node.ConnectionHelper: onConnected: Incoming connection to peer [<no peer name> F8:CF:C5:D9:E5:61]
03-29 16:23:58.609 11183 11183 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:CF:C5:D9:E5:61] updated - the peer count is 2
03-29 16:23:58.624 11183 11920 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 1547)
,03-29 16:23:58.629 11183 11183 D BluetoothSocket: getInputStream(): myUserId = 0,
,03-29 16:23:58.634 11183 11183 D BluetoothSocket: getOutputStream(): myUserId = 0,
03-29 16:23:58.634 11183 11183 I io.jxcore.node.ConnectionHelper: lowerBleDiscoveryPowerAndStartResetTimer: Lowering the power settings
03-29 16:23:58.634 11183 11183 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 2 -> 0
03-29 16:23:58.639 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-29 16:23:58.639 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-29 16:23:58.639 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-29 16:23:58.639 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-29 16:23:58.639 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-29 16:23:58.639 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-29 16:23:58.644  5848  5941 D BtGatt.AdvertiseManager: message : 1
03-29 16:23:58.644  5848  5941 D BtGatt.AdvertiseManager: stop advertise for client 7
03-29 16:23:58.644  5848  5941 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-29 16:23:58.644  5848  5941 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,03-29 16:23:58.644  5848  5919 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-29 16:23:58.644  5848  5919 D BtGatt.GattService: Client app is not null!
03-29 16:23:58.644  5848  5938 D BtGatt.GattService: unregisterClient() - clientIf=7
,03-29 16:23:58.649 11183 11183 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-29 16:23:58.649 11183 11183 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,03-29 16:23:58.649 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 3, timeout: 0, is connectable: false
03-29 16:23:58.649 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-29 16:23:58.649 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-29 16:23:58.649 11183 11183 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-29 16:23:58.649 11183 11183 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 16:23:58.649 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 16:23:58.649 11183 11183 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-29 16:23:58.654  5848  5938 D BtGatt.GattService: registerClient() - UUID=f10255e2-8d68-4028-a33c-b3307b2e2bbb,
,03-29 16:23:58.674  5848  5997 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
,03-29 16:23:58.674 11183 11924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesRead: Read 15 bytes successfully (thread ID: 1548)
03-29 16:23:58.674  5848  5997 D IOP_DB_BT: db_query: result 1
03-29 16:23:58.674  5848  5997 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-29 16:23:58.674  5848  5997 D IOP_DB_BT: db_query: result 1
03-29 16:23:58.674 11183 11924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Handshake succeeded with [<no peer name> F8:CF:C5:D9:E5:61]
03-29 16:23:58.674 11183 11924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onHandshakeSucceeded: [<no peer name> F8:CF:C5:D9:E5:61] (thread ID: 1546)
03-29 16:23:58.674 11183 11924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: handleSuccessfulClientThread: [<no peer name> F8:CF:C5:D9:E5:61] (thread ID: 1546)
,03-29 16:23:58.679 11183 11924 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 1548)
,03-29 16:23:58.694  5848  5919 D BtGatt.GattService: onClientRegistered() - UUID=f10255e2-8d68-4028-a33c-b3307b2e2bbb, clientIf=7
,03-29 16:23:58.694 11183 11193 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-29 16:23:58.709  5848  5860 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 62
,03-29 16:23:58.709  5848  5941 D BtGatt.AdvertiseManager: message : 0
03-29 16:23:58.709  5848  5941 D BtGatt.AdvertiseManager: number of adv instance running0
03-29 16:23:58.709  5848  5941 D BtGatt.AdvertiseManager: size of list is =0
,03-29 16:23:58.709  5848  5941 D BtGatt.AdvertiseManager: starting advertising
03-29 16:23:58.709  5848  5941 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-29 16:23:58.714  5848  5919 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-29 16:23:58.714  5848  5941 D BtGatt.AdvertiseManager: starting multi advertising
,03-29 16:23:58.719  5848  5919 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-29 16:23:58.719  5848  5941 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-29 16:23:58.719  5848  5941 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 0, TxPowerLevel: 3, isConnectable: false, Timeout: 0
03-29 16:23:58.719 11183 11183 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-29 16:23:58.719  5848  5857 D BtGatt.GattService: stopScan() - queue size =1
,03-29 16:23:58.724  5848  5944 D BtGatt.ScanManager: filter size is 1
,03-29 16:23:58.724  5848  5944 D BtGatt.ScanManager: delete FilterIndex - 11
03-29 16:23:58.724  5848  5938 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-29 16:23:58.724 11183 11183 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-29 16:23:58.724 11183 11183 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-29 16:23:58.724 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-29 16:23:58.724 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-29 16:23:58.724  5848  5919 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-29 16:23:58.724  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:23:58.724 11183 11183 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-29 16:23:58.724  5848  5944 D BtGatt.ScanManager: stopping BLe Batch
03-29 16:23:58.724 11183 11183 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-29 16:23:58.729  5848  5919 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,03-29 16:23:58.729  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:23:58.729  5848  5944 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-29 16:23:58.729  5848  5919 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,03-29 16:23:58.729  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:23:58.729  5848  5938 D BtGatt.GattService: registerClient() - UUID=3bf9d50a-4599-4925-96d3-98623069c550
,03-29 16:23:58.774  5848  5919 D BtGatt.GattService: onClientRegistered() - UUID=3bf9d50a-4599-4925-96d3-98623069c550, clientIf=6
03-29 16:23:58.774 11183 11193 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-29 16:23:58.774  5848  5860 D BtGatt.GattService: start scan with filters
,03-29 16:23:58.799  5848  5860 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 78
,03-29 16:23:58.799  5848  5944 D BtGatt.ScanManager: handling starting scan
03-29 16:23:58.799  5848  5944 D BtGatt.ScanManager: isFilteringSupported
03-29 16:23:58.799  5848  5944 D BluetoothAdapter: setting StandAloneBleMode
,03-29 16:23:58.804  5848  5919 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-29 16:23:58.804  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 16:23:58.804  5848  5944 D BtGatt.ScanManager: allow scan with filters
03-29 16:23:58.804  5848  5944 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-29 16:23:58.804  5848  5944 D BtGatt.ScanManager: set filter index= 12 for clientIf= 6
03-29 16:23:58.804  5848  5919 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-29 16:23:58.804  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 16:23:58.809  5848  5944 D BtGatt.ScanManager: Starting BLE batch scan
03-29 16:23:58.809  5848  5944 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-29 16:23:58.809  5848  5919 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-29 16:23:58.809  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 16:23:58.814  5848  5919 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-29 16:23:58.814  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:23:58.814 11183 11183 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-29 16:23:58.814 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-29 16:23:58.814 11183 11183 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 3 -> 1
03-29 16:23:58.814 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-29 16:23:58.814 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-29 16:23:58.814 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-29 16:23:58.814 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-29 16:23:58.814 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-29 16:23:58.814 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-29 16:23:58.819  5848  5941 D BtGatt.AdvertiseManager: message : 1
03-29 16:23:58.819  5848  5941 D BtGatt.AdvertiseManager: stop advertise for client 7
03-29 16:23:58.819  5848  5941 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-29 16:23:58.819  5848  5941 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-29 16:23:58.819  5848  5919 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-29 16:23:58.819  5848  5919 D BtGatt.GattService: Client app is not null!
03-29 16:23:58.824  5848  5938 D BtGatt.GattService: unregisterClient() - clientIf=7
03-29 16:23:58.824 11183 11183 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-29 16:23:58.824 11183 11183 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-29 16:23:58.824 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-29 16:23:58.824 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-29 16:23:58.824 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-29 16:23:58.824 11183 11183 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-29 16:23:58.824 11183 11183 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 16:23:58.824 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 16:23:58.824 11183 11183 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-29 16:23:58.829  5848  8884 ,D BtGatt.GattService: registerClient() - UUID=df0767cb-011a-4237-9d17-e1ccbd430fd6
,03-29 16:23:58.869  5848  5919 D BtGatt.GattService: onClientRegistered() - UUID=df0767cb-011a-4237-9d17-e1ccbd430fd6, clientIf=7
,03-29 16:23:58.874 11183 11195 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-29 16:23:58.884  5848  5857 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 63
,03-29 16:23:58.884  5848  5941 D BtGatt.AdvertiseManager: message : 0
03-29 16:23:58.884  5848  5941 D BtGatt.AdvertiseManager: number of adv instance running0
03-29 16:23:58.884  5848  5941 D BtGatt.AdvertiseManager: size of list is =0
,03-29 16:23:58.884  5848  5941 D BtGatt.AdvertiseManager: starting advertising
03-29 16:23:58.884  5848  5941 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-29 16:23:58.889  5848  5919 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-29 16:23:58.889  5848  5941 D BtGatt.AdvertiseManager: starting multi advertising
,03-29 16:23:58.889  5848  5919 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-29 16:23:58.889  5848  5941 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-29 16:23:58.889  5848  5941 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 0, TxPowerLevel: 1, isConnectable: false, Timeout: 0
03-29 16:23:58.889 11183 11183 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-29 16:23:58.894  5848  5860 D BtGatt.GattService: stopScan() - queue size =1
,03-29 16:23:58.894  5848  5944 D BtGatt.ScanManager: filter size is 1
03-29 16:23:58.894  5848  5944 D BtGatt.ScanManager: delete FilterIndex - 12
03-29 16:23:58.894  5848  8884 D BtGatt.GattService: unregisterClient() - clientIf=6
03-29 16:23:58.894 11183 11183 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-29 16:23:58.894 11183 11183 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-29 16:23:58.894  5848  5919 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,03-29 16:23:58.894  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:23:58.894  5848  5944 D BtGatt.ScanManager: stopping BLe Batch
03-29 16:23:58.894 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-29 16:23:58.894 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-29 16:23:58.894 11183 11183 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-29 16:23:58.894 11183 11183 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-29 16:23:58.899  5848  5919 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-29 16:23:58.899  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:23:58.899  5848  5944 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-29 16:23:58.899  5848  5919 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,03-29 16:23:58.899  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:23:58.899  5848  8884 D BtGatt.GattService: registerClient() - UUID=6a4b23c4-450e-425b-a2d3-928eb78225df
,03-29 16:23:58.939  5848  5919 D BtGatt.GattService: onClientRegistered() - UUID=6a4b23c4-450e-425b-a2d3-928eb78225df, clientIf=6
,03-29 16:23:58.939 11183 11939 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-29 16:23:58.944  5848  5857 D BtGatt.GattService: start scan with filters
,03-29 16:23:58.964  5848  5857 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 79
,03-29 16:23:58.969 11183 11183 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-29 16:23:58.969 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-29 16:23:58.969 11183 11183 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 2 -> 0
03-29 16:23:58.969  5848  5944 D BtGatt.ScanManager: handling starting scan
03-29 16:23:58.969  5848  5944 D BtGatt.ScanManager: isFilteringSupported
03-29 16:23:58.969  5848  5944 D BluetoothAdapter: setting StandAloneBleMode
03-29 16:23:58.969 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-29 16:23:58.969 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-29 16:23:58.969 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-29 16:23:58.969 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-29 16:23:58.969 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-29 16:23:58.969 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-29 16:23:58.984  5848  5941 D BtGatt.AdvertiseManager: message : 1
03-29 16:23:58.984  5848  5941 D BtGatt.AdvertiseManager: stop advertise for client 7
03-29 16:23:58.984  5848  5941 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-29 16:23:58.984  5848  5919 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-29 16:23:58.984  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
03-29 16:23:58.989  5848  5944 D BtGatt.ScanManager: allow scan with filters
,03-29 16:23:58.989  5848  5944 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-29 16:23:58.989  5848  5944 D BtGatt.ScanManager: set filter index= 13 for clientIf= 6
,03-29 16:23:58.989  5848  5941 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-29 16:23:58.989  5848  5919 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-29 16:23:58.989  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 16:23:58.994  5848  5944 D BtGatt.ScanManager: Starting BLE batch scan
,03-29 16:23:58.994  5848  5944 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-29 16:23:58.994  5848  5919 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-29 16:23:58.994  5848  5919 D BtGatt.GattService: Client app is not null!
03-29 16:23:58.999  5848  8884 D BtGatt.GattService: unregisterClient() - clientIf=7
03-29 16:23:59.004 11183 11183 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-29 16:23:59.004 11183 11183 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-29 16:23:59.004 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-29 16:23:59.004 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-29 16:23:59.004 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-29 16:23:59.004  5848  5919 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-29 16:23:59.004  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:23:59.004 11183 11183 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-29 16:23:59.009 11183 11183 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-29 16:23:59.009 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 16:23:59.009 11183 11183 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-29 16:23:59.014  5848  5919 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-29 16:23:59.014  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 16:23:59.029  5848  5938 D BtGatt.GattService: registerClient() - UUID=511f06e6-ab98-493c-aff6-60bd7074e715,
,03-29 16:23:59.074  5848  5919 D BtGatt.GattService: onClientRegistered() - UUID=511f06e6-ab98-493c-aff6-60bd7074e715, clientIf=7
,03-29 16:23:59.074 11183 11193 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-29 16:23:59.114  5848  5857 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 64,
03-29 16:23:59.119  5848  5941 D BtGatt.AdvertiseManager: message : 0
,03-29 16:23:59.129  5848  5941 D BtGatt.AdvertiseManager: number of adv instance running0
,03-29 16:23:59.129  5848  5941 D BtGatt.AdvertiseManager: size of list is =0
,03-29 16:23:59.144  5848  5941 D BtGatt.AdvertiseManager: starting advertising,
03-29 16:23:59.144  5848  5941 D BtGatt.AdvertiseManager: isStandardAdvfalse
03-29 16:23:59.149  5848  5919 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-29 16:23:59.154  5848  5941 D BtGatt.AdvertiseManager: starting multi advertising,
03-29 16:23:59.154  5848  5919 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-29 16:23:59.159  5848  5941 D BtGatt.AdvertiseManager: logClientsSet() - status: 0,
03-29 16:23:59.159  5848  5941 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 0, TxPowerLevel: 1, isConnectable: false, Timeout: 0
,03-29 16:23:59.164 11183 11183 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING,
,03-29 16:23:59.164  5848  8884 D BtGatt.GattService: stopScan() - queue size =1
03-29 16:23:59.164  5848  5944 D BtGatt.ScanManager: filter size is 1
,03-29 16:23:59.164  5848  5944 D BtGatt.ScanManager: delete FilterIndex - 13
03-29 16:23:59.169  5848  5938 D BtGatt.GattService: unregisterClient() - clientIf=6
03-29 16:23:59.169 11183 11183 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-29 16:23:59.169 11183 11183 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-29 16:23:59.169 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-29 16:23:59.169 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-29 16:23:59.169 11183 11183 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-29 16:23:59.169 11183 11183 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null],
03-29 16:23:59.174  5848  5938 D BtGatt.GattService: registerClient() - UUID=9ae5540e-9c0e-48fe-a29a-491485e381ca
03-29 16:23:59.174  5848  5919 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-29 16:23:59.174  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
03-29 16:23:59.174  5848  5944 D BtGatt.ScanManager: stopping BLe Batch
03-29 16:23:59.179  5848  5919 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-29 16:23:59.179  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:23:59.179  5848  5944 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-29 16:23:59.179  5848  5919 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2,
03-29 16:23:59.179  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:23:59.179  5848  5919 D BtGatt.GattService: current time is 264858780446,
03-29 16:23:59.179  5848  5919 D BtGatt.GattService: Batch record : [98, 120, 115, -83, -114, 124, 1, -128, -68, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0, 0, -117, -16, 115, -72, 77, 1, -128, -84, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-29 16:23:59.179  5848  5919 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-29 16:23:59.179  5848  5919 D ScanRecord: parseFromBytes
,03-29 16:23:59.179  5848  5919 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-29 16:23:59.179  5848  5919 D ScanRecord: parseFromBytes
,03-29 16:23:59.214  5848  5919 D BtGatt.GattService: onClientRegistered() - UUID=9ae5540e-9c0e-48fe-a29a-491485e381ca, clientIf=6
03-29 16:23:59.214 11183 11195 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-29 16:23:59.214  5848  5857 D BtGatt.GattService: start scan with filters
,03-29 16:23:59.229  5848  5857 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 80
,03-29 16:23:59.229  5848  5944 D BtGatt.ScanManager: handling starting scan
03-29 16:23:59.229  5848  5944 D BtGatt.ScanManager: isFilteringSupported
03-29 16:23:59.229  5848  5944 D BluetoothAdapter: setting StandAloneBleMode
,03-29 16:23:59.234  5848  5919 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-29 16:23:59.234  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 16:23:59.234  5848  5944 D BtGatt.ScanManager: allow scan with filters
03-29 16:23:59.234  5848  5944 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-29 16:23:59.234  5848  5944 D BtGatt.ScanManager: set filter index= 14 for clientIf= 6
03-29 16:23:59.234  5848  5919 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-29 16:23:59.234  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 16:23:59.239  5848  5944 D BtGatt.ScanManager: Starting BLE batch scan
03-29 16:23:59.239  5848  5944 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-29 16:23:59.239  5848  5919 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-29 16:23:59.239  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 16:23:59.244  5848  5919 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-29 16:23:59.244  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 16:23:59.244 11183 11183 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-29 16:23:59.244 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-29 16:23:59.244 11183 11183 I io.jxcore.node.ConnectionHelper: onConnected: Incoming socket thread, for peer [<no peer name> F8:CF:C5:D9:E5:61], created successfully
03-29 16:23:59.244 11183 11183 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 1
03-29 16:23:59.244 11183 11183 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:CF:C5:D9:E5:61]
03-29 16:23:59.244 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-29 16:23:59.244 11183 11183 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-29 16:23:59.244 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-29 16:23:59.244 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-29 16:23:59.244 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-29 16:23:59.244 11183 11183 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing connection to peer [<no peer name> F8:CF:C5:D9:E5:61]
03-29 16:23:59.249 11183 11183 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:CF:C5:D9:E5:61] updated - the peer count is 2
,03-29 16:23:59.249 11183 11948 D io.jxcore.node.IncomingSocketThread: Entering thread (ID: 1549)
03-29 16:23:59.249  2872  3506 D EnterpriseController: netId is 0
03-29 16:23:59.249  2872  3506 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,03-29 16:23:59.254 11183 11183 D BluetoothSocket: getInputStream(): myUserId = 0
,03-29 16:23:59.254 11183 11948 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 39804
,03-29 16:23:59.254 11183 11948 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,03-29 16:23:59.254 11183 11948 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
,03-29 16:23:59.259 11183 11948 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-29 16:23:59.259 11183 11948 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 1549)
03-29 16:23:59.259 11183 11948 D io.jxcore.node.IncomingSocketThread: Exiting thread (ID: 1549)
,03-29 16:23:59.259 11183 11952 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1553, name: Receiver)
,03-29 16:23:59.259 11183 11183 D BluetoothSocket: getOutputStream(): myUserId = 0
,03-29 16:23:59.259 11183 11951 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1552, name: Sender)
03-29 16:23:59.259 11183 11183 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing socket thread, for peer [<no peer name> F8:CF:C5:D9:E5:61], created successfully
,03-29 16:23:59.259 11183 11183 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 2
03-29 16:23:59.264 11183 11954 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1551)
,03-29 16:23:59.264 11183 11954 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 44721
,03-29 16:23:59.264 11183 11954 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
03-29 16:23:59.264 11183 11954 I io.jxcore.node.ConnectionHelper: onListeningForIncomingConnections: Outgoing connection is using port 44721 (peer ID: F8:CF:C5:D9:E5:61)
03-29 16:23:59.264 11183 11954 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "F8:CF:C5:D9:E5:61" removed
,03-29 16:23:59.269 11183 11246 I jxcore-log: INFO testThaliMobileNative: 
03-29 16:23:59.269 11183 11246 I jxcore-log: 
,03-29 16:23:59.269 11183 11246 I jxcore-log: ok 165 Must have listeningPort
03-29 16:23:59.269 11183 11246 I jxcore-log: 
,03-29 16:23:59.269 11183 11246 I jxcore-log: ok 166 listeningPort must be a number
03-29 16:23:59.269 11183 11246 I jxcore-log: 
,03-29 16:23:59.269 11183 11246 I jxcore-log: ok 167 Connection must have clientPort
03-29 16:23:59.269 11183 11246 I jxcore-log: 
,03-29 16:23:59.274 11183 11246 I jxcore-log: ok 168 clientPort must be a number
03-29 16:23:59.274 11183 11246 I jxcore-log: 
,03-29 16:23:59.274 11183 11246 I jxcore-log: ok 169 Connection must have serverPort
03-29 16:23:59.274 11183 11246 I jxcore-log: 
,03-29 16:23:59.274 11183 11246 I jxcore-log: ok 170 serverPort must be a number
03-29 16:23:59.274 11183 11246 I jxcore-log: 
,03-29 16:23:59.274 11183 11246 I jxcore-log: ok 171 forward connection must have clientPort == 0
03-29 16:23:59.274 11183 11246 I jxcore-log: 
,03-29 16:23:59.274 11183 11246 I jxcore-log: ok 172 forward connection must have serverPort == 0
03-29 16:23:59.274 11183 11246 I jxcore-log: 
,03-29 16:23:59.284 11183 11246 I jxcore-log: # teardown
03-29 16:23:59.284 11183 11246 I jxcore-log: 
,03-29 16:23:59.474 11183 11951 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 1552, thread name: Sender)
03-29 16:23:59.474 11183 11951 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Input stream got -1 on read
03-29 16:23:59.474 11183 11951 W io.jxcore.node.ConnectionHelper: onDisconnected: Incoming connection, peer [<no peer name> F8:CF:C5:D9:E5:61] disconnected: Input stream got -1 on read
03-29 16:23:59.474 11183 11951 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1549
03-29 16:23:59.474 11183 11951 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 1549)
03-29 16:23:59.474 11183 11951 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@22ff3ab5, channel: 6, state: CONNECTED
03-29 16:23:59.474 11183 11951 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@22ff3ab5, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@78d554a, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@8660cbbmSocket: android.net.LocalSocket@3ef695d8 impl:android.net.LocalSocketImpl@2db5cd31 fd:FileDescriptor[92]
03-29 16:23:59.474 11183 11951 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3ef695d8 impl:android.net.LocalSocketImpl@2db5cd31 fd:FileDescriptor[92]
03-29 16:23:59.474 11183 11952 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 1553, thread name: Receiver): bt socket closed, read return: -1
03-29 16:23:59.474 11183 11952 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1553, name: Receiver)
,03-29 16:23:59.479  5848  5997 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61,
03-29 16:23:59.484  5848  5997 D IOP_DB_BT: db_query: result 1,
03-29 16:23:59.484  5848  5997 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
,03-29 16:23:59.484  5848  5997 D IOP_DB_BT: db_query: result 1
03-29 16:23:59.484 11183 11951 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@22ff3ab5, channel: 6, state: CLOSED
03-29 16:23:59.484 11183 11951 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@22ff3ab5, channel: 6, state: CLOSED
,03-29 16:23:59.484 11183 11951 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed,
,03-29 16:23:59.484 11183 11951 D io.jxcore.node.IncomingSocketThread: close: Stopping receiving thread...
,03-29 16:23:59.484 11183 11951 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 1553
03-29 16:23:59.484 11183 11951 D io.jxcore.node.IncomingSocketThread: close: Stopping sending thread...
,03-29 16:23:59.484 11183 11951 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 1552
03-29 16:23:59.484 11183 11951 D io.jxcore.node.IncomingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 1549)
,03-29 16:23:59.484 11183 11951 I io.jxcore.node.IncomingSocketThread: close: Complete (thread ID: 1549)
03-29 16:23:59.484 11183 11951 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
03-29 16:23:59.494 11183 11951 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1552, name: Sender)
,03-29 16:23:59.499 11183 11246 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements,
,03-29 16:23:59.499 11183 11246 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
,03-29 16:23:59.499 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-29 16:23:59.499 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-29 16:23:59.504  5848  5857 D BtGatt.GattService: stopScan() - queue size =1,
03-29 16:23:59.504  5848  5944 D BtGatt.ScanManager: filter size is 1
03-29 16:23:59.504  5848  5944 D BtGatt.ScanManager: delete FilterIndex - 14
,03-29 16:23:59.504  5848  5919 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-29 16:23:59.504  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:23:59.504  5848  5944 D BtGatt.ScanManager: stopping BLe Batch
,03-29 16:23:59.509  5848  5919 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0,
03-29 16:23:59.509  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:23:59.509  5848  5860 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-29 16:23:59.509  5848  5944 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-29 16:23:59.514  5848  5919 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,03-29 16:23:59.514  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 16:23:59.519 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
03-29 16:23:59.519 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-29 16:23:59.519 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,03-29 16:23:59.519 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-29 16:23:59.519 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-29 16:23:59.519 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-29 16:23:59.519 11183 11183 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-29 16:23:59.519 11183 11183 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-29 16:23:59.519 11183 11183 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-29 16:23:59.524 11183 11246 I jxcore-log: INFO thaliMobileNativeWrapper: incomingConnectionToPortNumberFailed: %s
03-29 16:23:59.524 11183 11246 I jxcore-log: 
,03-29 16:23:59.529 11183 11246 I jxcore-log: INFO thaliMobileNativeWrapper: got incomingConnectionToPortNumberFailed while not in start
03-29 16:23:59.529 11183 11246 I jxcore-log: 
,03-29 16:23:59.529 11183 11246 I jxcore-log: ok 173 Should be able to call stopListeningForAdvertisments in teardown
03-29 16:23:59.529 11183 11246 I jxcore-log: 
,03-29 16:23:59.534 11183 11246 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-29 16:23:59.534 11183 11246 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> F8:CF:C5:D9:E5:61]
03-29 16:23:59.534 11183 11246 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1551)
,03-29 16:23:59.534 11183 11246 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 1551)
03-29 16:23:59.534 11183 11246 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3fd37c16, channel: 5, state: CONNECTED
,03-29 16:23:59.534 11183 11246 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3fd37c16, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2bdeb997, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2c2b3784mSocket: android.net.LocalSocket@2d690b6d impl:android.net.LocalSocketImpl@1a8343a2 fd:FileDescriptor[112]
03-29 16:23:59.534 11183 11246 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2d690b6d impl:android.net.LocalSocketImpl@1a8343a2 fd:FileDescriptor[112]
,03-29 16:23:59.534 11183 11246 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3fd37c16, channel: 5, state: CLOSED
,03-29 16:23:59.534 11183 11246 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3fd37c16, channel: 5, state: CLOSED
03-29 16:23:59.534 11183 11246 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
,03-29 16:23:59.539 11183 11246 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Nothing to close (thread ID: 1551)
03-29 16:23:59.539 11183 11246 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1551)
,03-29 16:23:59.539 11183 11954 D io.jxcore.node.OutgoingSocketThread: Exiting thread (ID: 1551)
03-29 16:23:59.539 11183 11246 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,03-29 16:23:59.539 11183 11246 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-29 16:23:59.539 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-29 16:23:59.539 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-29 16:23:59.539 11183 11246 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@39cb5833, channel: 6, state: LISTENING
03-29 16:23:59.539 11183 11246 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@39cb5833, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3b14433e, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3ae647f0mSocket: android.net.LocalSocket@1197f169 impl:android.net.LocalSocketImpl@2975f7ee fd:FileDescriptor[113]
,03-29 16:23:59.539 11183 11246 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1197f169 impl:android.net.LocalSocketImpl@2975f7ee fd:FileDescriptor[113]
,03-29 16:23:59.544 11183 11246 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-29 16:23:59.544 11183 11830 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-29 16:23:59.544 11183 11830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-29 16:23:59.544 11183 11830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-29 16:23:59.544 11183 11183 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-29 16:23:59.544 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-29 16:23:59.544 11183 11183 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-29 16:23:59.544 11183 11183 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-29 16:23:59.544 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-29 16:23:59.544 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-29 16:23:59.544 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-29 16:23:59.544 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-29 16:23:59.549 11183 11246 D BluetoothLeScanner: could not find callback wrapper
,03-29 16:23:59.549 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-29 16:23:59.549 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-29 16:23:59.549  5848  5941 D BtGatt.AdvertiseManager: message : 1,
03-29 16:23:59.554  5848  5941 D BtGatt.AdvertiseManager: stop advertise for client 7,
03-29 16:23:59.554  5848  5941 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-29 16:23:59.554  5848  5941 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-29 16:23:59.554  5848  5919 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-29 16:23:59.554  5848  5919 D BtGatt.GattService: Client app is not null!
,03-29 16:23:59.559  5848  5860 D BtGatt.GattService: unregisterClient() - clientIf=7,
,03-29 16:23:59.559 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
03-29 16:23:59.559 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-29 16:23:59.559 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-29 16:23:59.559 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,03-29 16:23:59.559 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED],
03-29 16:23:59.559 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-29 16:23:59.559 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-29 16:23:59.559 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-29 16:23:59.564  5848  5997 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0xf):jv handle:0x0 not FOUND,
03-29 16:23:59.564  5848  5997 E bt-btif : bta_jv_port_mgmt_sr_cback, p_cb:0x0, p_cb->p_cback0x0
03-29 16:23:59.564 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-29 16:23:59.564 11183 11246 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-29 16:23:59.564 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-29 16:23:59.564 11183 11183 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 16:23:59.564 11183 11183 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 16:23:59.564 11183 11183 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
03-29 16:23:59.564 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-29 16:23:59.564 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-29 16:23:59.574 11183 11183 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-29 16:23:59.574  5848  5997 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0x10):jv handle:0x0 not FOUND
,03-29 16:23:59.579 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-29 16:23:59.579 11183 11246 I jxcore-log: 
,03-29 16:23:59.579 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
,03-29 16:23:59.584 11183 11246 I jxcore-log: ok 174 Should be able to call stopAdvertisingAndListening in teardown
03-29 16:23:59.584 11183 11246 I jxcore-log: 
,03-29 16:23:59.584 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-29 16:23:59.584 11183 11183 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-29 16:23:59.584 11183 11183 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-29 16:23:59.589 11183 11183 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-29 16:23:59.589 11183 11246 I jxcore-log: # setup
03-29 16:23:59.589 11183 11246 I jxcore-log: 
,03-29 16:23:59.589 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 16:23:59.589 11183 11246 I jxcore-log: 
,03-29 16:23:59.594 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 16:23:59.594 11183 11246 I jxcore-log: 
,03-29 16:23:59.604  3452  3492 D SecContentProvider2: query(), uri = 15 selection = getAppBlockDownloadState
,03-29 16:23:59.609  3753 11763 V DownloadManager: 1 items are running
,03-29 16:23:59.999  3452  3619 V AlarmManager: waitForAlarm result :8
,03-29 16:24:00.459  3452  4020 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-29 16:24:00.459  3452  4020 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-29 16:24:00.459  3452  4020 D BatteryService: online:4, current avg:39, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:33
,03-29 16:24:00.464  3452  3452 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-29 16:24:00.464  3452  4020 D BatteryService: stay LED for fully charged
,03-29 16:24:00.469  3452  3452 I MotionRecognitionService: Plugged,
,03-29 16:24:00.469  3452  3452 D MotionRecognitionService:   cableConnection= 1
03-29 16:24:00.469  3452  3452 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-29 16:24:00.469  3452  3452 D MotionRecognitionService: skip setTransmitPower. ,
,03-29 16:24:00.484  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-29 16:24:00.484  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-29 16:24:00.484  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-29 16:24:00.504  5848  5848 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-29 16:24:00.504  5848  5945 D HeadsetStateMachine: Disconnected process message: 10
,03-29 16:24:00.514  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-29 16:24:00.514  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-29 16:24:00.514  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-29 16:24:00.514  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-29 16:24:00.919  3452  6034 D SSRM:n  : SIOP:: AP = 280, PST = 285 (W:14), CUR = 39, LCD = 0
,03-29 16:24:00.979 11183 11246 I jxcore-log: # 41. Can shift large amounts of data
03-29 16:24:00.979 11183 11246 I jxcore-log: 
,03-29 16:24:01.299 11183 11246 I io.jxcore.node.ConnectionHelper: start: Port number: 40475, start advertisements: true
03-29 16:24:01.299 11183 11246 I io.jxcore.node.ConnectionHelper: restoreDefaultBleDiscoverySettings: Powering the BLE discovery back up
,03-29 16:24:01.299 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 0 -> 2
03-29 16:24:01.299 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-29 16:24:01.299 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-29 16:24:01.299 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-29 16:24:01.299 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-29 16:24:01.299 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-29 16:24:01.299 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-29 16:24:01.299 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 1, timeout: 0, is connectable: false
03-29 16:24:01.304 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-29 16:24:01.304 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 1 -> 3
03-29 16:24:01.304 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-29 16:24:01.304 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-29 16:24:01.304 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-29 16:24:01.304 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-29 16:24:01.304 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-29 16:24:01.304 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-29 16:24:01.304 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-29 16:24:01.304 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-29 16:24:01.304 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 0 -> 2
03-29 16:24:01.304 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-29 16:24:01.304 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-29 16:24:01.304 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-29 16:24:01.304 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-29 16:24:01.304 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-29 16:24:01.304 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-29 16:24:01.304 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-29 16:24:01.304 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-29 16:24:01.304 11183 11246 V io.jxcore.node.ConnectivityMoni,tor: start: Already started
03-29 16:24:01.304 11183 11246 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-29 16:24:01.304 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-29 16:24:01.304 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-29 16:24:01.304 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-29 16:24:01.304 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-29 16:24:01.309 11183 11246 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-29 16:24:01.309  5848  8884 D BtGatt.GattService: registerClient() - UUID=5bf2d058-26cd-45d5-b0bf-03ba7d81ce3b
,03-29 16:24:01.349  5848  5919 D BtGatt.GattService: onClientRegistered() - UUID=5bf2d058-26cd-45d5-b0bf-03ba7d81ce3b, clientIf=6
,03-29 16:24:01.349 11183 11195 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-29 16:24:01.354  5848  5938 D BtGatt.GattService: start scan with filters
,03-29 16:24:01.369  5848  5938 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 81
,03-29 16:24:01.369  5848  5944 D BtGatt.ScanManager: handling starting scan
03-29 16:24:01.369  5848  5944 D BtGatt.ScanManager: isFilteringSupported
03-29 16:24:01.369  5848  5944 D BluetoothAdapter: setting StandAloneBleMode
03-29 16:24:01.369 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-29 16:24:01.369 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-29 16:24:01.369 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,03-29 16:24:01.369 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-29 16:24:01.369 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 16:24:01.369 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-29 16:24:01.369 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-29 16:24:01.369 11183 11246 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-29 16:24:01.369 11183 11246 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 16:24:01.369 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 16:24:01.369 11183 11246 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-29 16:24:01.374 11183 11183 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-29 16:24:01.379  5848  5919 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1,
,03-29 16:24:01.379  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:24:01.379  5848  5944 D BtGatt.ScanManager: allow scan with filters
03-29 16:24:01.379  5848  5944 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-29 16:24:01.379  5848  5944 D BtGatt.ScanManager: set filter index= 15 for clientIf= 6
03-29 16:24:01.384  5848  5919 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,03-29 16:24:01.384  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:24:01.384  5848  5944 D BtGatt.ScanManager: Starting BLE batch scan
03-29 16:24:01.384  5848  5944 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-29 16:24:01.384  5848  5919 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,03-29 16:24:01.384  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:24:01.389  5848  5919 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1,
03-29 16:24:01.389  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 16:24:01.404  5848  5938 D BtGatt.GattService: registerClient() - UUID=98ff329f-f089-48b9-8f54-3c6bbf24afdc,
,03-29 16:24:01.449  5848  5919 D BtGatt.GattService: onClientRegistered() - UUID=98ff329f-f089-48b9-8f54-3c6bbf24afdc, clientIf=7
03-29 16:24:01.449 11183 11193 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-29 16:24:01.464  5848  5857 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 65
,03-29 16:24:01.464  5848  5941 D BtGatt.AdvertiseManager: message : 0
,03-29 16:24:01.469  5848  5941 D BtGatt.AdvertiseManager: number of adv instance running0
03-29 16:24:01.469  5848  5941 D BtGatt.AdvertiseManager: size of list is =0
,03-29 16:24:01.469  5848  5941 D BtGatt.AdvertiseManager: starting advertising
03-29 16:24:01.469  5848  5941 D BtGatt.AdvertiseManager: isStandardAdvfalse
03-29 16:24:01.474  5848  5919 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-29 16:24:01.474  5848  5941 D BtGatt.AdvertiseManager: starting multi advertising
03-29 16:24:01.479  5848  5919 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-29 16:24:01.479  5848  5941 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-29 16:24:01.479  5848  5941 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,03-29 16:24:01.479 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-29 16:24:01.479 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-29 16:24:01.484 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-29 16:24:01.484 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-29 16:24:01.484 11183 11246 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-29 16:24:01.484 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-29 16:24:01.484 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-29 16:24:01.484 11183 11246 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-29 16:24:01.484 11183 11246 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-29 16:24:01.484 11183 11246 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-29 16:24:01.484 11183 11183 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-29 16:24:01.484 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-29 16:24:01.484 11183 11183 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING,
03-29 16:24:01.484 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-29 16:24:01.484 11183 11183 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
,03-29 16:24:01.484 11183 11183 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-29 16:24:01.484 11183 11183 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-29 16:24:01.484 11183 11183 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-29 16:24:01.484 11183 11183 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-29 16:24:01.484 11183 11183 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 16:24:01.484 11183 11183 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,03-29 16:24:01.484 11183 11183 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-29 16:24:01.494 11183 11246 I io.jxcore.node.ConnectionHelper: start: OK
03-29 16:24:01.494 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 16:24:01.494 11183 11246 I jxcore-log: 
03-29 16:24:01.494 11183 11246 I jxcore-log: ok 175 Can call startUpdateAdvertisingAndListening without error
,03-29 16:24:01.494 11183 11246 I jxcore-log: 
,03-29 16:24:01.509 11183 11985 D BluetoothSocket: bindListen(): myUserId = 0
03-29 16:24:01.509 11183 11985 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-29 16:24:01.514 11183 11985 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[93]},
03-29 16:24:01.514 11183 11985 D BluetoothSocket: bindListen(), new LocalSocket 
03-29 16:24:01.514 11183 11985 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-29 16:24:01.514 11183 11985 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@30cda4fa
03-29 16:24:01.514 11183 11985 D BluetoothSocket: channel: 6
,03-29 16:24:01.514 11183 11985 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-29 16:24:01.514 11183 11246 I io.jxcore.node.ConnectionHelper: start: Port number: 40475, start advertisements: false
03-29 16:24:01.514 11183 11246 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-29 16:24:01.514 11183 11246 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
,03-29 16:24:01.514 11183 11246 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-29 16:24:01.514 11183 11246 I io.jxcore.node.ConnectionHelper: start: OK
,03-29 16:24:01.519  3452  3572 W ProcessCpuTracker: Skipping unknown process pid 11983
,03-29 16:24:01.519 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 16:24:01.519 11183 11246 I jxcore-log: 
,03-29 16:24:01.519 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-29 16:24:01.519 11183 11246 I jxcore-log: 
,03-29 16:24:01.524 11183 11246 I jxcore-log: ok 176 Can call startListeningForAdvertisements without error
03-29 16:24:01.524 11183 11246 I jxcore-log: 
,03-29 16:24:01.534  3452  3914 D SecContentProvider2: query(), uri = 15 selection = getAppBlockDownloadState
,03-29 16:24:01.539  3753 11763 V DownloadManager: 1 items are running
,03-29 16:24:02.389  3452  3619 V AlarmManager: waitForAlarm result :4
,03-29 16:24:02.414  5848  5848 D BtGatt.ScanManager: awakened up at time 268092
,03-29 16:24:02.424  5848  5944 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-29 16:24:02.429  5848  5919 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
03-29 16:24:02.429  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:24:02.429  5848  5919 D BtGatt.GattService: current time is 268105563655
03-29 16:24:02.429  5848  5919 D BtGatt.GattService: Batch record : [88, -66, -25, 96, 65, 82, 1, -128, -71, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, 60, -64, -109, -67, -72, 65, 1, -128, -56, 4, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0]
03-29 16:24:02.429  5848  5919 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-29 16:24:02.429  5848  5919 D ScanRecord: parseFromBytes
03-29 16:24:02.429  5848  5919 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-29 16:24:02.429  5848  5919 D ScanRecord: parseFromBytes
03-29 16:24:02.429  5848  5919 D BtGatt.GattService: result: ScanResult{mDevice=41:B8:BD:93:C0:3C, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-56, mTimestampNanos=267905750739}
03-29 16:24:02.429  5848  5919 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-29 16:24:02.429  5848  5919 D BtGatt.GattService: result: ScanResult{mDevice=52:41:60:E7:BE:58, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-71, mTimestampNanos=268005750739}
03-29 16:24:02.429  5848  5919 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-29 16:24:02.429 11183 11195 D ScanRecord: parseFromBytes
03-29 16:24:02.429 11183 11195 D ScanRecord: parseFromBytes
03-29 16:24:02.429 11183 11183 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:CF:C5:D9:E5:61], added - the peer count is 1
03-29 16:24:02.429 11183 11183 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 2
03-29 16:24:02.429 11183 11183 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:CF:C5:D9:E5:61], Bluetooth address: F8:CF:C5:D9:E5:61, device name: , device address: 
03-29 16:24:02.429 11183 11183 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
,03-29 16:24:02.454  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
03-29 16:24:02.454  3726  3726 I PERF    : received broadcast android.intent.action.TIME_TICK
03-29 16:24:02.454  3726  3726 D KeyguardUpdateMonitor: handleTimeUpdate
,03-29 16:24:02.459 11183 11246 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID F8:CF:C5:D9:E5:61
03-29 16:24:02.459 11183 11246 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> F8:CF:C5:D9:E5:61]
,03-29 16:24:02.459 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to Nexus 6 in address F8:CF:C5:D9:E5:61
03-29 16:24:02.459 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
03-29 16:24:02.459 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
03-29 16:24:02.459 11183 11246 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: Nexus 6 F8:CF:C5:D9:E5:61
03-29 16:24:02.459 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to Nexus 6 in address F8:CF:C5:D9:E5:61
03-29 16:24:02.459 11183 11246 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: F8:CF:C5:D9:E5:61)
,03-29 16:24:02.459 11183 11995 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address F8:CF:C5:D9:E5:61 (thread ID: 1555)
,03-29 16:24:02.459  3726  3726 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,03-29 16:24:02.464  3726  3726 D SecKeyguardClockView: HomeTimezone(): 1
,03-29 16:24:02.469 11183 11995 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
,03-29 16:24:02.469 11183 11995 D BluetoothSocket: connect(): myUserId = 0
03-29 16:24:02.469 11183 11995 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-29 16:24:02.469  5848  5857 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-29 16:24:02.469 11183 11995 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[112]}
,03-29 16:24:02.474  3726  3726 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-29 16:24:02.474  3726  3726 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,03-29 16:24:02.479  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,03-29 16:24:02.514  3726  3726 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-29 16:24:02.514  3726  3726 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-29 16:24:02.519  3726  3726 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-29 16:24:02.524  3726  3726 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-29 16:24:02.529  3726  3726 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-29 16:24:02.529  3726  3726 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-29 16:24:02.554  3726  3726 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-29 16:24:02.989  5848  5997 W bt-sdp  : process_service_search_attr_rsp
,03-29 16:24:03.444  3452  3619 V AlarmManager: waitForAlarm result :4
,03-29 16:24:03.459  5848  5848 D BtGatt.ScanManager: awakened up at time 269135
,03-29 16:24:03.464  5848  5944 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-29 16:24:03.479  5848  5919 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
03-29 16:24:03.479  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:24:03.479  5848  5919 D BtGatt.GattService: current time is 269155626655
03-29 16:24:03.479  5848  5919 D BtGatt.GattService: Batch record : [60, -64, -109, -67, -72, 65, 1, -128, -60, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0, 88, -66, -25, 96, 65, 82, 1, -128, -76, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-29 16:24:03.479  5848  5919 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-29 16:24:03.479  5848  5919 D ScanRecord: parseFromBytes
03-29 16:24:03.479  5848  5919 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-29 16:24:03.479  5848  5919 D ScanRecord: parseFromBytes
03-29 16:24:03.479  5848  5919 D BtGatt.GattService: result: ScanResult{mDevice=52:41:60:E7:BE:58, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-76, mTimestampNanos=269155810697}
03-29 16:24:03.479  5848  5919 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-29 16:24:03.479  5848  5919 D BtGatt.GattService: result: ScanResult{mDevice=41:B8:BD:93:C0:3C, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-60, mTimestampNanos=269005810697}
03-29 16:24:03.479  5848  5919 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-29 16:24:03.479 11183 11193 D ScanRecord: parseFromBytes
03-29 16:24:03.479 11183 11193 D ScanRecord: parseFromBytes
03-29 16:24:03.479 11183 11183 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
03-29 16:24:03.479 11183 11183 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:CF:C5:D9:E5:61] updated - the peer count is 2
,03-29 16:24:03.569  3452  3572 I ActivityManager: Waited long enough for: ServiceRecord{20ca65e3 u0 com.android.providers.downloads/.DownloadService}
,03-29 16:24:03.749  5848  5997 W bt-btif : new conn_srvc id:26, app_id:1
03-29 16:24:03.749  5848  5997 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:1
03-29 16:24:03.749  5848  5997 W bt-btif : bta_dm_pm_ssr:2, lat:1200
,03-29 16:24:03.754  5848  8884 E BluetoothRemoteDevices: setRfcommConnected true
,03-29 16:24:03.764 11183 11995 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onSocketConnected: [<no peer name> F8:CF:C5:D9:E5:61] (thread ID: 1555)
03-29 16:24:03.764 11183 11995 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 1555)
,03-29 16:24:03.764 11183 11995 D BluetoothSocket: getInputStream(): myUserId = 0
,03-29 16:24:03.774 11183 11995 D BluetoothSocket: getOutputStream(): myUserId = 0
,03-29 16:24:03.774  5848  5997 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-29 16:24:03.774  5848  5997 D IOP_DB_BT: db_query: result 1
03-29 16:24:03.774  5848  5997 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-29 16:24:03.774  5848  5997 D IOP_DB_BT: db_query: result 1
,03-29 16:24:03.774 11183 11995 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesWritten: 15 bytes successfully written (thread ID: 1556)
03-29 16:24:03.774 11183 11995 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Outgoing connection initialized (*handshake* thread ID: 1556)
,03-29 16:24:03.779 11183 11995 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1555)
,03-29 16:24:03.779 11183 12004 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 1556)
,03-29 16:24:03.794  3452  3491 D SecContentProvider2: query(), uri = 15 selection = getAppBlockDownloadState
,03-29 16:24:03.799  3753 11763 V DownloadManager: 1 items are running
,03-29 16:24:03.824  5848  5997 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-29 16:24:03.824 11183 12004 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesRead: Read 15 bytes successfully (thread ID: 1556)
03-29 16:24:03.824  5848  5997 D IOP_DB_BT: db_query: result 1
03-29 16:24:03.824  5848  5997 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
,03-29 16:24:03.824  5848  5997 D IOP_DB_BT: db_query: result 1
03-29 16:24:03.824 11183 12004 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Handshake succeeded with [<no peer name> F8:CF:C5:D9:E5:61]
03-29 16:24:03.829 11183 12004 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onHandshakeSucceeded: [<no peer name> F8:CF:C5:D9:E5:61] (thread ID: 1555)
03-29 16:24:03.829 11183 12004 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: handleSuccessfulClientThread: [<no peer name> F8:CF:C5:D9:E5:61] (thread ID: 1555)
03-29 16:24:03.829 11183 12004 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 1556)
03-29 16:24:03.829 11183 11183 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:CF:C5:D9:E5:61]
,03-29 16:24:03.829 11183 11183 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing connection to peer [<no peer name> F8:CF:C5:D9:E5:61]
03-29 16:24:03.829 11183 11183 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:CF:C5:D9:E5:61] updated - the peer count is 2
,03-29 16:24:03.829 11183 11183 D BluetoothSocket: getInputStream(): myUserId = 0
,03-29 16:24:03.834 11183 11183 D BluetoothSocket: getOutputStream(): myUserId = 0
03-29 16:24:03.834 11183 11183 I io.jxcore.node.ConnectionHelper: lowerBleDiscoveryPowerAndStartResetTimer: Lowering the power settings
03-29 16:24:03.834 11183 11183 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 2 -> 0
03-29 16:24:03.834 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-29 16:24:03.834 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-29 16:24:03.834 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-29 16:24:03.834 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-29 16:24:03.834 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-29 16:24:03.834 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-29 16:24:03.834  5848  5941 D BtGatt.AdvertiseManager: message : 1
,03-29 16:24:03.839  5848  5941 D BtGatt.AdvertiseManager: stop advertise for client 7
03-29 16:24:03.839  5848  5941 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
,03-29 16:24:03.839  5848  5941 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,03-29 16:24:03.839  5848  5919 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-29 16:24:03.839  5848  5919 D BtGatt.GattService: Client app is not null!
,03-29 16:24:03.844  5848  5857 D BtGatt.GattService: unregisterClient() - clientIf=7
,03-29 16:24:03.844 11183 11183 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-29 16:24:03.844 11183 11183 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-29 16:24:03.844 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 3, timeout: 0, is connectable: false
03-29 16:24:03.844 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-29 16:24:03.844 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
,03-29 16:24:03.844 11183 11183 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-29 16:24:03.844 11183 11183 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 16:24:03.844 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 16:24:03.844 11183 11183 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-29 16:24:03.849  5848  5857 D BtGatt.GattService: registerClient() - UUID=5e5775ac-6cff-49c0-8b4e-926deb0abd08
,03-29 16:24:03.849 11183 11192 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@39cb5833, channel: 6, state: CLOSED
03-29 16:24:03.849 11183 11192 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@22ff3ab5, channel: 6, state: CLOSED
03-29 16:24:03.849 11183 11192 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3fd37c16, channel: 5, state: CLOSED
03-29 16:24:03.849 11183 11192 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@bc79f2, channel: 6, state: CLOSED
,03-29 16:24:03.854 11183 11192 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2cf07dde, channel: 6, state: CLOSED
,03-29 16:24:03.854 11183 11192 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@20035de8, channel: 6, state: CLOSED
,03-29 16:24:03.854 11183 11192 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@20e3f048, channel: 6, state: CLOSED
,03-29 16:24:03.859 11183 11192 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2b6ce4e2, channel: 6, state: CLOSED
,03-29 16:24:03.859 11183 11192 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@5a20200, channel: 6, state: CLOSED
,03-29 16:24:03.889  5848  5919 D BtGatt.GattService: onClientRegistered() - UUID=5e5775ac-6cff-49c0-8b4e-926deb0abd08, clientIf=7
,03-29 16:24:03.889 11183 11195 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-29 16:24:03.914  5848  5860 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 66
,03-29 16:24:03.919  5848  5941 D BtGatt.AdvertiseManager: message : 0
,03-29 16:24:03.924  5848  5941 D BtGatt.AdvertiseManager: number of adv instance running0
03-29 16:24:03.924  5848  5941 D BtGatt.AdvertiseManager: size of list is =0
,03-29 16:24:03.929  5848  5941 D BtGatt.AdvertiseManager: starting advertising
03-29 16:24:03.929  5848  5941 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-29 16:24:03.934  5848  5919 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-29 16:24:03.934  5848  5941 D BtGatt.AdvertiseManager: starting multi advertising
,03-29 16:24:03.939  5848  5919 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-29 16:24:03.939  5848  5941 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,03-29 16:24:03.939  5848  5941 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 0, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,03-29 16:24:03.944 11183 11183 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-29 16:24:03.944  5848  5938 D BtGatt.GattService: stopScan() - queue size =1
03-29 16:24:03.944  5848  5944 D BtGatt.ScanManager: filter size is 1
03-29 16:24:03.944  5848  5944 D BtGatt.ScanManager: delete FilterIndex - 15
03-29 16:24:03.949  5848  5857 D BtGatt.GattService: unregisterClient() - clientIf=6
03-29 16:24:03.949  5848  5919 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-29 16:24:03.949  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:24:03.949  5848  5944 D BtGatt.ScanManager: stopping BLe Batch
03-29 16:24:03.954 11183 11183 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-29 16:24:03.954 11183 11183 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-29 16:24:03.954 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-29 16:24:03.954 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-29 16:24:03.954 11183 11183 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-29 16:24:03.954 11183 11183 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-29 16:24:03.954  5848  5919 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-29 16:24:03.954  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:24:03.954  5848  5944 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-29 16:24:03.959  5848  5919 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
03-29 16:24:03.959  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:24:03.959  5848  5919 D BtGatt.GattService: current time is 269635599405
03-29 16:24:03.959  5848  5919 D BtGatt.GattService: Batch record : [60, -64, -109, -67, -72, 65, 1, -128, -65, 5, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0, 88, -66, -25, 96, 65, 82, 1, -128, -76, 5, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-29 16:24:03.959  5848  5919 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-29 16:24:03.959  5848  5919 D ScanRecord: parseFromBytes
03-29 16:24:03.959  5848  5919 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-29 16:24:03.959  5848  5919 D ScanRecord: parseFromBytes
03-29 16:24:03.964  5848  8884 D BtGatt.GattService: registerClient() - UUID=87a1c9ca-9d75-453c-878b-23e978a09c1d
,03-29 16:24:04.009  5848  5919 D BtGatt.GattService: onClientRegistered() - UUID=87a1c9ca-9d75-453c-878b-23e978a09c1d, clientIf=6,
,03-29 16:24:04.009 11183 11939 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6,
,03-29 16:24:04.024  5848  5857 D BtGatt.GattService: start scan with filters,
,03-29 16:24:04.044  5848  5857 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 82
,03-29 16:24:04.044 11183 11183 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-29 16:24:04.044 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-29 16:24:04.044 11183 11183 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 3 -> 1
03-29 16:24:04.044 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-29 16:24:04.044 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-29 16:24:04.044 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-29 16:24:04.044 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-29 16:24:04.044 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-29 16:24:04.044 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-29 16:24:04.049  5848  5944 D BtGatt.ScanManager: handling starting scan
03-29 16:24:04.049  5848  5944 D BtGatt.ScanManager: isFilteringSupported
03-29 16:24:04.049  5848  5944 D BluetoothAdapter: setting StandAloneBleMode
,03-29 16:24:04.054  5848  5941 D BtGatt.AdvertiseManager: message : 1
03-29 16:24:04.059  3452  6065 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
03-29 16:24:04.054  5848  5941 D BtGatt.AdvertiseManager: stop advertise for client 7
03-29 16:24:04.054  5848  5941 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-29 16:24:04.054  5848  5941 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-29 16:24:04.059  5848  5919 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-29 16:24:04.059  5848  5919 D BtGatt.GattService: Client app is not null!
03-29 16:24:04.059  5848  5919 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-29 16:24:04.059  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:24:04.059  5848  8884 D BtGatt.GattService: unregisterClient() - clientIf=7
03-29 16:24:04.064 11183 11183 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-29 16:24:04.064 11183 11183 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-29 16:24:04.064 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-29 16:24:04.064 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-29 16:24:04.064 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-29 16:24:04.064 11183 11183 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-29 16:24:04.064 11183 11183 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 16:24:04.064 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 16:24:04.064 11183 11183 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-29 16:24:04.064  5848  5944 D BtGatt.ScanManager: allow scan with filters
03-29 16:24:04.064  5848  5944 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-29 16:24:04.064  5848  5944 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
03-29 16:24:04.069  5848  5919 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-29 16:24:04.069  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 16:24:04.069  5848  5944 D BtGatt.ScanManager: Starting BLE batch scan,
03-29 16:24:04.069  5848  5944 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-29 16:24:04.074  5848  5919 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,03-29 16:24:04.074  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:24:04.074  5848  5919 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-29 16:24:04.074  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:24:04.079  5848  5938 D BtGatt.GattService: registerClient() - UUID=37a14d44-6dae-4607-91c3-953ac8c39dbe
,03-29 16:24:04.124  5848  5919 D BtGatt.GattService: onClientRegistered() - UUID=37a14d44-6dae-4607-91c3-953ac8c39dbe, clientIf=7,
,03-29 16:24:04.124 11183 11193 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7,
,03-29 16:24:04.159  5848  5857 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 67
,03-29 16:24:04.159  5848  5941 D BtGatt.AdvertiseManager: message : 0
03-29 16:24:04.159  5848  5941 D BtGatt.AdvertiseManager: number of adv instance running0
03-29 16:24:04.159  5848  5941 D BtGatt.AdvertiseManager: size of list is =0
,03-29 16:24:04.159  5848  5941 D BtGatt.AdvertiseManager: starting advertising
,03-29 16:24:04.159  5848  5941 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-29 16:24:04.164  5848  5919 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-29 16:24:04.164  5848  5941 D BtGatt.AdvertiseManager: starting multi advertising
,03-29 16:24:04.169  5848  5919 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0,
03-29 16:24:04.169  5848  5941 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-29 16:24:04.169  5848  5941 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 0, TxPowerLevel: 1, isConnectable: false, Timeout: 0
,03-29 16:24:04.169 11183 11183 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-29 16:24:04.169  5848  8884 D BtGatt.GattService: stopScan() - queue size =1
,03-29 16:24:04.174  5848  5944 D BtGatt.ScanManager: filter size is 1,
03-29 16:24:04.174  5848  5944 D BtGatt.ScanManager: delete FilterIndex - 3
03-29 16:24:04.174  5848  5938 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-29 16:24:04.174  5848  5919 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-29 16:24:04.174  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:24:04.174  5848  5944 D BtGatt.ScanManager: stopping BLe Batch
03-29 16:24:04.174 11183 11183 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-29 16:24:04.174 11183 11183 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-29 16:24:04.174 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-29 16:24:04.174 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-29 16:24:04.174 11183 11183 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-29 16:24:04.174 11183 11183 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-29 16:24:04.179  5848  5919 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,03-29 16:24:04.179  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 16:24:04.179  5848  5944 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-29 16:24:04.179  5848  5919 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-29 16:24:04.179  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:24:04.184  5848  5857 D BtGatt.GattService: registerClient() - UUID=d3470340-cbb0-4988-bfaf-1e6894135a54
,03-29 16:24:04.224  5848  5919 D BtGatt.GattService: onClientRegistered() - UUID=d3470340-cbb0-4988-bfaf-1e6894135a54, clientIf=6
,03-29 16:24:04.224 11183 11195 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-29 16:24:04.229  5848  5860 D BtGatt.GattService: start scan with filters
,03-29 16:24:04.264  5848  5860 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 83
,03-29 16:24:04.269  5848  5944 D BtGatt.ScanManager: handling starting scan
,03-29 16:24:04.269  5848  5944 D BtGatt.ScanManager: isFilteringSupported
03-29 16:24:04.269  5848  5944 D BluetoothAdapter: setting StandAloneBleMode
,03-29 16:24:04.279 11183 11183 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-29 16:24:04.279 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-29 16:24:04.279 11183 11183 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 2 -> 0
03-29 16:24:04.279  5848  5919 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,03-29 16:24:04.279  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:24:04.284  5848  5944 D BtGatt.ScanManager: allow scan with filters
03-29 16:24:04.284  5848  5944 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-29 16:24:04.284  5848  5944 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
03-29 16:24:04.289  5848  5919 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-29 16:24:04.289  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 16:24:04.289  5848  5944 D BtGatt.ScanManager: Starting BLE batch scan,
03-29 16:24:04.289  5848  5944 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-29 16:24:04.294  5848  5919 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-29 16:24:04.294  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:24:04.299  5848  5919 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-29 16:24:04.299  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:24:04.299 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-29 16:24:04.299 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-29 16:24:04.299 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-29 16:24:04.299 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-29 16:24:04.299 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-29 16:24:04.299 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-29 16:24:04.314  5848  5941 D BtGatt.AdvertiseManager: message : 1
03-29 16:24:04.319  5848  5941 D BtGatt.AdvertiseManager: stop advertise for client 7
03-29 16:24:04.319  5848  5941 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-29 16:24:04.324  5848  5919 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
,03-29 16:24:04.324  5848  5919 D BtGatt.GattService: Client app is not null!,
03-29 16:24:04.324  5848  5941 D BtGatt.AdvertiseManager: logClientsSet() - status: -1,
,03-29 16:24:04.344  5848  5857 D BtGatt.GattService: unregisterClient() - clientIf=7
,03-29 16:24:04.359 11183 11183 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-29 16:24:04.359 11183 11183 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
,03-29 16:24:04.359 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false,
,03-29 16:24:04.359 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...,
,03-29 16:24:04.359 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-29 16:24:04.359 11183 11183 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
,03-29 16:24:04.359 11183 11183 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-29 16:24:04.359 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false],
03-29 16:24:04.359 11183 11183 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...,
,03-29 16:24:04.399  5848  5857 D BtGatt.GattService: registerClient() - UUID=f9b29a03-86ae-4e21-8daa-116f06c81d75,
,03-29 16:24:04.439  5848  5919 D BtGatt.GattService: onClientRegistered() - UUID=f9b29a03-86ae-4e21-8daa-116f06c81d75, clientIf=7,
,03-29 16:24:04.439 11183 11939 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-29 16:24:04.529  5848  5860 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 68
,03-29 16:24:04.529  5848  5941 D BtGatt.AdvertiseManager: message : 0
03-29 16:24:04.529  5848  5941 D BtGatt.AdvertiseManager: number of adv instance running0
03-29 16:24:04.529  5848  5941 D BtGatt.AdvertiseManager: size of list is =0
,03-29 16:24:04.529  5848  5941 D BtGatt.AdvertiseManager: starting advertising
03-29 16:24:04.529  5848  5941 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-29 16:24:04.534  5848  5919 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-29 16:24:04.534  5848  5941 D BtGatt.AdvertiseManager: starting multi advertising
,03-29 16:24:04.534  5848  5919 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-29 16:24:04.534  5848  5941 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-29 16:24:04.534  5848  5941 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 0, TxPowerLevel: 1, isConnectable: false, Timeout: 0
03-29 16:24:04.534 11183 11183 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-29 16:24:04.539  5848  5938 D BtGatt.GattService: stopScan() - queue size =1,
03-29 16:24:04.539  5848  5944 D BtGatt.ScanManager: filter size is 1
03-29 16:24:04.539  5848  5944 D BtGatt.ScanManager: delete FilterIndex - 4
03-29 16:24:04.539  5848  5857 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-29 16:24:04.539 11183 11183 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-29 16:24:04.539 11183 11183 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-29 16:24:04.539 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-29 16:24:04.539 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-29 16:24:04.539 11183 11183 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-29 16:24:04.539 11183 11183 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-29 16:24:04.539  5848  5919 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-29 16:24:04.539  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 16:24:04.539  5848  5944 D BtGatt.ScanManager: stopping BLe Batch
,03-29 16:24:04.544  5848  5919 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-29 16:24:04.544  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:24:04.544  5848  5944 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-29 16:24:04.544  5848  5857 D BtGatt.GattService: registerClient() - UUID=363e659b-c486-4575-8a3c-1ec05034b527
,03-29 16:24:04.544  5848  5919 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
,03-29 16:24:04.544  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:24:04.544  5848  5919 D BtGatt.GattService: current time is 270224367364
03-29 16:24:04.544  5848  5919 D BtGatt.GattService: Batch record : [88, -66, -25, 96, 65, 82, 1, -128, -75, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-29 16:24:04.544  5848  5919 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-29 16:24:04.544  5848  5919 D ScanRecord: parseFromBytes
,03-29 16:24:04.584  5848  5919 D BtGatt.GattService: onClientRegistered() - UUID=363e659b-c486-4575-8a3c-1ec05034b527, clientIf=6
,03-29 16:24:04.584 11183 11193 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-29 16:24:04.584  5848  5860 D BtGatt.GattService: start scan with filters
,03-29 16:24:04.659  5848  5860 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 84
,03-29 16:24:04.659 11183 11183 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-29 16:24:04.659 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-29 16:24:04.659  5848  5944 D BtGatt.ScanManager: handling starting scan
03-29 16:24:04.659  5848  5944 D BtGatt.ScanManager: isFilteringSupported
03-29 16:24:04.659  5848  5944 D BluetoothAdapter: setting StandAloneBleMode
03-29 16:24:04.659 11183 11183 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing socket thread, for peer [<no peer name> F8:CF:C5:D9:E5:61], created successfully
03-29 16:24:04.659 11183 11183 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 1
03-29 16:24:04.659 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-29 16:24:04.659 11183 11183 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-29 16:24:04.659 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-29 16:24:04.659 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-29 16:24:04.659 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-29 16:24:04.664 11183 12024 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1557)
,03-29 16:24:04.664 11183 12024 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 43415
03-29 16:24:04.664 11183 12024 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
03-29 16:24:04.664 11183 12024 I io.jxcore.node.ConnectionHelper: onListeningForIncomingConnections: Outgoing connection is using port 43415 (peer ID: F8:CF:C5:D9:E5:61)
03-29 16:24:04.664 11183 12024 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "F8:CF:C5:D9:E5:61" removed
03-29 16:24:04.664  5848  5919 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-29 16:24:04.664  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:24:04.664  5848  5944 D BtGatt.ScanManager: allow scan with filters
,03-29 16:24:04.664  5848  5944 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-29 16:24:04.664  5848  5944 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
03-29 16:24:04.664  5848  5997 W bt-btif : new conn_srvc id:26, app_id:255
,03-29 16:24:04.664  5848  5997 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:1,
03-29 16:24:04.664  5848  5997 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
,03-29 16:24:04.664  5848  5997 W bt-btif : bta_dm_pm_ssr:2, lat:1200
03-29 16:24:04.664 11183 11985 D BluetoothSocket: socket fd passed by stack  fds: [Ljava.io.FileDescriptor;@320d89b4
03-29 16:24:04.664  5848  5919 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-29 16:24:04.664  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:24:04.669  5848  5944 D BtGatt.ScanManager: Starting BLE batch scan
03-29 16:24:04.669  5848  5944 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-29 16:24:04.669  5848  8884 E BluetoothRemoteDevices: setRfcommConnected true
03-29 16:24:04.669 11183 11985 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection accepted
03-29 16:24:04.669 11183 11246 I jxcore-log: INFO testThaliMobileNative: 
03-29 16:24:04.669 11183 11246 I jxcore-log: 
03-29 16:24:04.669  5848  5919 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-29 16:24:04.669  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 16:24:04.674 11183 11246 I jxcore-log: INFO testThaliMobileNative: Forward connection
03-29 16:24:04.674 11183 11246 I jxcore-log: 
03-29 16:24:04.674  5848  5919 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,03-29 16:24:04.674  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:24:04.674 11183 11985 D BluetoothSocket: getInputStream(): myUserId = 0
,03-29 16:24:04.679 11183 12024 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 43415
03-29 16:24:04.679 11183 12024 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
03-29 16:24:04.679 11183 12024 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-29 16:24:04.679 11183 12024 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
,03-29 16:24:04.679 11183 12024 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1557)
03-29 16:24:04.679 11183 12024 D io.jxcore.node.OutgoingSocketThread: Exiting thread (ID: 1557)
03-29 16:24:04.679 11183 11985 D BluetoothSocket: getOutputStream(): myUserId = 0
,03-29 16:24:04.684 11183 11246 I jxcore-log: INFO testThaliMobileNative: forwardSend
03-29 16:24:04.684 11183 11246 I jxcore-log: 
,03-29 16:24:04.684 11183 12025 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1559, name: Sender),
03-29 16:24:04.684 11183 11985 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection initialized (thread ID: 1558)
03-29 16:24:04.684 11183 11985 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@24f0a9dd, channel: 6, state: LISTENING
03-29 16:24:04.684 11183 11985 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@24f0a9dd, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@30cda4fa, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@c27d952mSocket: android.net.LocalSocket@389ab423 impl:android.net.LocalSocketImpl@32d38d20 fd:FileDescriptor[93]
03-29 16:24:04.684 11183 11985 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@389ab423 impl:android.net.LocalSocketImpl@32d38d20 fd:FileDescriptor[93]
03-29 16:24:04.684 11183 11985 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-29 16:24:04.689 11183 12026 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1560, name: Receiver)
03-29 16:24:04.689 11183 12027 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 1558)
,03-29 16:24:04.694 11183 11985 D BluetoothSocket: bindListen(): myUserId = 0
03-29 16:24:04.694 11183 11985 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-29 16:24:04.694 11183 11985 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[116]}
,03-29 16:24:04.694 11183 11985 D BluetoothSocket: bindListen(), new LocalSocket 
03-29 16:24:04.694 11183 11985 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-29 16:24:04.694 11183 11985 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1fd306d9
03-29 16:24:04.694 11183 11985 D BluetoothSocket: channel: 6
,03-29 16:24:04.694 11183 11985 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-29 16:24:04.889 11183 11246 I jxcore-log: INFO testThaliMobileNative: forwardData
03-29 16:24:04.889 11183 11246 I jxcore-log: 
,03-29 16:24:04.964 11183 11246 I jxcore-log: INFO testThaliMobileNative: forwardData
03-29 16:24:04.964 11183 11246 I jxcore-log: 
,03-29 16:24:05.089 11183 11246 I jxcore-log: INFO testThaliMobileNative: forwardData
03-29 16:24:05.089 11183 11246 I jxcore-log: 
,03-29 16:24:05.229 11183 11246 I jxcore-log: INFO testThaliMobileNative: forwardData
03-29 16:24:05.229 11183 11246 I jxcore-log: 
,03-29 16:24:05.294 11183 11246 I jxcore-log: INFO testThaliMobileNative: forwardData
03-29 16:24:05.294 11183 11246 I jxcore-log: 
,03-29 16:24:05.304 11183 11246 I jxcore-log: ok 177 received should match sent forward
03-29 16:24:05.304 11183 11246 I jxcore-log: 
,03-29 16:24:05.319 11183 11246 I jxcore-log: # teardown
03-29 16:24:05.319 11183 11246 I jxcore-log: 
,03-29 16:24:05.524  5848  5997 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-29 16:24:05.524  5848  5997 D IOP_DB_BT: db_query: result 1
03-29 16:24:05.524  5848  5997 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-29 16:24:05.524  5848  5997 D IOP_DB_BT: db_query: result 1
,03-29 16:24:05.534 11183 12027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesRead: Read 15 bytes successfully (thread ID: 1558),
,03-29 16:24:05.539 11183 12027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Got valid identity from [<no peer name> F8:CF:C5:D9:E5:61]
03-29 16:24:05.539  5848  5997 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-29 16:24:05.539  5848  5997 D IOP_DB_BT: db_query: result 1
03-29 16:24:05.539  5848  5997 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-29 16:24:05.539  5848  5997 D IOP_DB_BT: db_query: result 1
03-29 16:24:05.544 11183 12027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesWritten: 15 bytes successfully written (thread ID: 1558)
03-29 16:24:05.544 11183 12027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: removeThreadFromList: Removing thread with ID 1558
03-29 16:24:05.544 11183 12027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Handshake thread disposed (thread ID: 1558)
03-29 16:24:05.544 11183 12027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onIncomingConnectionConnected: [<no peer name> F8:CF:C5:D9:E5:61]
,03-29 16:24:05.544 11183 11183 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:CF:C5:D9:E5:61],
03-29 16:24:05.544 11183 11183 I io.jxcore.node.ConnectionHelper: onConnected: Incoming connection to peer [<no peer name> F8:CF:C5:D9:E5:61]
,03-29 16:24:05.544 11183 11183 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:CF:C5:D9:E5:61] updated - the peer count is 2
,03-29 16:24:05.554 11183 11183 D BluetoothSocket: getInputStream(): myUserId = 0,
,03-29 16:24:05.559 11183 11183 D BluetoothSocket: getOutputStream(): myUserId = 0,
03-29 16:24:05.559 11183 11183 I io.jxcore.node.ConnectionHelper: onConnected: Incoming socket thread, for peer [<no peer name> F8:CF:C5:D9:E5:61], created successfully
,03-29 16:24:05.559 11183 11183 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 2
,03-29 16:24:05.559 11183 12027 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 1558),
,03-29 16:24:05.564 11183 12035 D io.jxcore.node.IncomingSocketThread: Entering thread (ID: 1561)
,03-29 16:24:05.564  2872  3506 D EnterpriseController: netId is 0
03-29 16:24:05.564  2872  3506 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,03-29 16:24:05.569 11183 12035 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 40475
,03-29 16:24:05.574 11183 12035 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,03-29 16:24:05.574 11183 12035 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
,03-29 16:24:05.574 11183 12035 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
,03-29 16:24:05.574 11183 12035 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 1561)
,03-29 16:24:05.574 11183 12035 D io.jxcore.node.IncomingSocketThread: Exiting thread (ID: 1561)
,03-29 16:24:05.579 11183 12038 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1563, name: Receiver)
,03-29 16:24:05.579 11183 12037 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1562, name: Sender)
,03-29 16:24:05.604  3452  4399 D SecContentProvider2: query(), uri = 15 selection = getAppBlockDownloadState
,03-29 16:24:05.609  3753 11763 V DownloadManager: 1 items are running
,03-29 16:24:05.674  3452  3619 V AlarmManager: waitForAlarm result :4
,03-29 16:24:05.674  5848  5848 D BtGatt.ScanManager: awakened up at time 271354
,03-29 16:24:05.679  5848  5944 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-29 16:24:05.679  5848  5919 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
03-29 16:24:05.679  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:24:05.679  5848  5919 D BtGatt.GattService: current time is 271357946072
03-29 16:24:05.679  5848  5919 D BtGatt.GattService: Batch record : [88, -66, -25, 96, 65, 82, 1, -128, -77, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-29 16:24:05.679  5848  5919 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-29 16:24:05.679  5848  5919 D ScanRecord: parseFromBytes
,03-29 16:24:05.679  5848  5919 D BtGatt.GattService: result: ScanResult{mDevice=52:41:60:E7:BE:58, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-77, mTimestampNanos=271258065822}
03-29 16:24:05.679  5848  5919 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-29 16:24:05.679 11183 11939 D ScanRecord: parseFromBytes
,03-29 16:24:05.679 11183 11183 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
,03-29 16:24:05.694  5848  5997 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61,
,03-29 16:24:05.694  5848  5997 D IOP_DB_BT: db_query: result 1
03-29 16:24:05.694  5848  5997 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
,03-29 16:24:05.694  5848  5997 D IOP_DB_BT: db_query: result 1
,03-29 16:24:05.699  5848  5997 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
,03-29 16:24:05.699  5848  5997 D IOP_DB_BT: db_query: result 1
03-29 16:24:05.699  5848  5997 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-29 16:24:05.699  5848  5997 D IOP_DB_BT: db_query: result 1
,03-29 16:24:05.709  5848  5997 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
,03-29 16:24:05.709  5848  5997 D IOP_DB_BT: db_query: result 1
03-29 16:24:05.709  5848  5997 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-29 16:24:05.709  5848  5997 D IOP_DB_BT: db_query: result 1
,03-29 16:24:05.714  5848  5997 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
,03-29 16:24:05.714  5848  5997 D IOP_DB_BT: db_query: result 1
03-29 16:24:05.714  5848  5997 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
,03-29 16:24:05.714  5848  5997 D IOP_DB_BT: db_query: result 1
,03-29 16:24:05.839  5848  5997 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-29 16:24:05.844  5848  5997 D IOP_DB_BT: db_query: result 1
03-29 16:24:05.844  5848  5997 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-29 16:24:05.844  5848  5997 D IOP_DB_BT: db_query: result 1
,03-29 16:24:05.854  5848  5997 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-29 16:24:05.854  5848  5997 D IOP_DB_BT: db_query: result 1
,03-29 16:24:05.854  5848  5997 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-29 16:24:05.859  5848  5997 D IOP_DB_BT: db_query: result 1
,03-29 16:24:05.954  5848  5997 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-29 16:24:05.954  5848  5997 D IOP_DB_BT: db_query: result 1
03-29 16:24:05.954  5848  5997 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-29 16:24:05.954  5848  5997 D IOP_DB_BT: db_query: result 1
,03-29 16:24:05.969  5848  5997 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-29 16:24:05.974  5848  5997 D IOP_DB_BT: db_query: result 1
03-29 16:24:05.974  5848  5997 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-29 16:24:05.974  5848  5997 D IOP_DB_BT: db_query: result 1
,03-29 16:24:06.019  5848  5997 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-29 16:24:06.019  5848  5997 D IOP_DB_BT: db_query: result 1
03-29 16:24:06.019  5848  5997 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-29 16:24:06.019  5848  5997 D IOP_DB_BT: db_query: result 1
,03-29 16:24:06.024  5848  5997 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-29 16:24:06.024  5848  5997 D IOP_DB_BT: db_query: result 1
03-29 16:24:06.024  5848  5997 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-29 16:24:06.024  5848  5997 D IOP_DB_BT: db_query: result 1
,03-29 16:24:06.679  3452  3619 V AlarmManager: waitForAlarm result :4
,03-29 16:24:06.694  5848  5848 D BtGatt.ScanManager: awakened up at time 272373
,03-29 16:24:06.699  5848  5944 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-29 16:24:06.699  5848  5919 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
03-29 16:24:06.699  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:24:06.699  5848  5919 D BtGatt.GattService: current time is 272378966739
03-29 16:24:06.699  5848  5919 D BtGatt.GattService: Batch record : [88, -66, -25, 96, 65, 82, 1, -128, -77, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, 40, 36, 100, 44, -42, 101, 1, -128, -68, 15, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0]
03-29 16:24:06.699  5848  5919 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-29 16:24:06.699  5848  5919 D ScanRecord: parseFromBytes
03-29 16:24:06.699  5848  5919 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-29 16:24:06.699  5848  5919 D ScanRecord: parseFromBytes
03-29 16:24:06.704  5848  5919 D BtGatt.GattService: result: ScanResult{mDevice=52:41:60:E7:BE:58, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-77, mTimestampNanos=272379203406}
03-29 16:24:06.704  5848  5919 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-29 16:24:06.704  5848  5919 D BtGatt.GattService: result: ScanResult{mDevice=65:D6:2C:64:24:28, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-68, mTimestampNanos=271629203406}
03-29 16:24:06.704  5848  5919 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-29 16:24:06.704 11183 11195 D ScanRecord: parseFromBytes
03-29 16:24:06.704 11183 11195 D ScanRecord: parseFromBytes
03-29 16:24:06.704 11183 11183 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
03-29 16:24:06.704 11183 11183 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:CF:C5:D9:E5:61] updated - the peer count is 2
,03-29 16:24:07.194  3452  3491 D SecContentProvider2: query(), uri = 15 selection = getAppBlockDownloadState
,03-29 16:24:07.199  3753 11763 V DownloadManager: 1 items are running
,03-29 16:24:07.374  3452  3653 V NetworkStats: performPollLocked(flags=0x1)
,03-29 16:24:07.379  3452  3653 D NtpTrustedTime: currentTimeMillis() cache hit
,03-29 16:24:07.414  3452  3653 V NetworkStats: performPollLocked() took 33ms
03-29 16:24:07.414  3452  3653 D NtpTrustedTime: currentTimeMillis() cache hit
,03-29 16:24:07.439  3452  3654 D NtpTrustedTime: currentTimeMillis() cache hit
03-29 16:24:07.439  3452  3654 D NtpTrustedTime: currentTimeMillis() cache hit
,03-29 16:24:07.714  3452  3619 V AlarmManager: waitForAlarm result :4
,03-29 16:24:07.729  5848  5848 D BtGatt.ScanManager: awakened up at time 273405
,03-29 16:24:07.734  5848  5944 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6,
03-29 16:24:07.744  5848  5919 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
,03-29 16:24:07.744  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,03-29 16:24:07.744  5848  5919 D BtGatt.GattService: current time is 273422483156
03-29 16:24:07.744  5848  5919 D BtGatt.GattService: Batch record : [88, -66, -25, 96, 65, 82, 1, -128, -77, 17, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, 40, 36, 100, 44, -42, 101, 1, -128, -73, 15, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0]
,03-29 16:24:07.744  5848  5919 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-29 16:24:07.744  5848  5919 D ScanRecord: parseFromBytes
03-29 16:24:07.744  5848  5919 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97],
,03-29 16:24:07.744  5848  5919 D ScanRecord: parseFromBytes
03-29 16:24:07.744  5848  5919 D BtGatt.GattService: result: ScanResult{mDevice=65:D6:2C:64:24:28, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-73, mTimestampNanos=272672704197}
,03-29 16:24:07.744  5848  5919 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-29 16:24:07.744  5848  5919 D BtGatt.GattService: result: ScanResult{mDevice=52:41:60:E7:BE:58, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-77, mTimestampNanos=272572704197}
,03-29 16:24:07.744  5848  5919 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-29 16:24:07.744 11183 11193 D ScanRecord: parseFromBytes
03-29 16:24:07.744 11183 11193 D ScanRecord: parseFromBytes,
,03-29 16:24:07.749 11183 11183 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:CF:C5:D9:E5:61] updated - the peer count is 2
03-29 16:24:07.749 11183 11183 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
,03-29 16:24:08.759  3452  3619 V AlarmManager: waitForAlarm result :4
,03-29 16:24:08.764  5848  5848 D BtGatt.ScanManager: awakened up at time 274442
03-29 16:24:08.769  5848  5944 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-29 16:24:08.769  5848  5919 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-29 16:24:08.769  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 16:24:08.824  3452  3914 D SecContentProvider2: query(), uri = 15 selection = getAppBlockDownloadState
,03-29 16:24:08.824  3753 11763 V DownloadManager: 1 items are running
,03-29 16:24:09.419 11183 12037 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 1562, thread name: Sender)
03-29 16:24:09.419 11183 12037 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Input stream got -1 on read
03-29 16:24:09.419 11183 12037 W io.jxcore.node.ConnectionHelper: onDisconnected: Incoming connection, peer [<no peer name> F8:CF:C5:D9:E5:61] disconnected: Input stream got -1 on read
03-29 16:24:09.419 11183 12037 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1561
03-29 16:24:09.419 11183 12037 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 1561)
03-29 16:24:09.419 11183 12037 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@16f1e038, channel: 6, state: CONNECTED
03-29 16:24:09.419 11183 12037 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@16f1e038, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1a9db811, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1162bd76mSocket: android.net.LocalSocket@3c08cf77 impl:android.net.LocalSocketImpl@2c00c7e4 fd:FileDescriptor[114]
03-29 16:24:09.419 11183 12037 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3c08cf77 impl:android.net.LocalSocketImpl@2c00c7e4 fd:FileDescriptor[114]
03-29 16:24:09.419 11183 12037 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@16f1e038, channel: 6, state: CLOSED
03-29 16:24:09.419 11183 12037 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@16f1e038, channel: 6, state: CLOSED
03-29 16:24:09.419 11183 12037 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-29 16:24:09.419 11183 12037 D io.jxcore.node.IncomingSocketThread: close: Stopping receiving thread...
03-29 16:24:09.419 11183 12037 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 1563
03-29 16:24:09.419 11183 12037 D io.jxcore.node.IncomingSocketThread: close: Stopping sending thread...
,03-29 16:24:09.424 11183 12038 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 1563, thread name: Receiver): bt socket closed, read return: -1,
03-29 16:24:09.424 11183 12038 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1563, name: Receiver)
03-29 16:24:09.424  5848  5997 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-29 16:24:09.424  5848  5997 D IOP_DB_BT: db_query: result 1
03-29 16:24:09.424  5848  5997 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61,
,03-29 16:24:09.424  5848  5997 D IOP_DB_BT: db_query: result 1
03-29 16:24:09.424 11183 12037 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 1562
03-29 16:24:09.424 11183 12037 D io.jxcore.node.IncomingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 1561)
,03-29 16:24:09.429 11183 12037 I io.jxcore.node.IncomingSocketThread: close: Complete (thread ID: 1561)
03-29 16:24:09.429 11183 12037 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
03-29 16:24:09.429 11183 12037 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1562, name: Sender),
,03-29 16:24:09.439 11183 11246 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-29 16:24:09.439 11183 11246 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
03-29 16:24:09.439 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,03-29 16:24:09.439 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-29 16:24:09.444  5848  8884 D BtGatt.GattService: stopScan() - queue size =1
03-29 16:24:09.444  5848  5944 D BtGatt.ScanManager: filter size is 1
03-29 16:24:09.444  5848  5944 D BtGatt.ScanManager: delete FilterIndex - 5
03-29 16:24:09.444  5848  5919 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-29 16:24:09.444  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 16:24:09.449  5848  5944 D BtGatt.ScanManager: stopping BLe Batch
,03-29 16:24:09.449  5848  5919 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0,
03-29 16:24:09.449  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:24:09.449  5848  5944 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-29 16:24:09.449  5848  5919 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-29 16:24:09.449  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 16:24:09.454  5848  5938 D BtGatt.GattService: unregisterClient() - clientIf=6,
03-29 16:24:09.454 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-29 16:24:09.454 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-29 16:24:09.454 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-29 16:24:09.454 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-29 16:24:09.454 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-29 16:24:09.454 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-29 16:24:09.459 11183 11183 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-29 16:24:09.459 11183 11183 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-29 16:24:09.459 11183 11183 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-29 16:24:09.459 11183 11246 I jxcore-log: INFO thaliMobileNativeWrapper: incomingConnectionToPortNumberFailed: %s
03-29 16:24:09.459 11183 11246 I jxcore-log: 
,03-29 16:24:09.464 11183 11246 I jxcore-log: INFO thaliMobileNativeWrapper: got incomingConnectionToPortNumberFailed while not in start
03-29 16:24:09.464 11183 11246 I jxcore-log: 
,03-29 16:24:09.464 11183 11246 I jxcore-log: ok 178 Should be able to call stopListeningForAdvertisments in teardown
03-29 16:24:09.464 11183 11246 I jxcore-log: 
,03-29 16:24:09.469 11183 11246 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-29 16:24:09.469 11183 11246 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> F8:CF:C5:D9:E5:61]
03-29 16:24:09.469 11183 11246 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1557)
03-29 16:24:09.469 11183 11246 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 1557)
,03-29 16:24:09.469 11183 11246 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3794c44d, channel: 5, state: CONNECTED
03-29 16:24:09.469 11183 11246 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3794c44d, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1eb53b02, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@30b0ec13mSocket: android.net.LocalSocket@cf47e50 impl:android.net.LocalSocketImpl@4765849 fd:FileDescriptor[112]
03-29 16:24:09.469 11183 11246 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@cf47e50 impl:android.net.LocalSocketImpl@4765849 fd:FileDescriptor[112]
,03-29 16:24:09.469 11183 12026 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 1560, thread name: Receiver): bt socket closed, read return: -1
03-29 16:24:09.469 11183 12026 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1560, name: Receiver)
,03-29 16:24:09.474 11183 11246 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3794c44d, channel: 5, state: CLOSED
03-29 16:24:09.474 11183 11246 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3794c44d, channel: 5, state: CLOSED
,03-29 16:24:09.474 11183 11246 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-29 16:24:09.474 11183 11246 D io.jxcore.node.OutgoingSocketThread: close: Stopping receiving thread...
03-29 16:24:09.474 11183 11246 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 1560
03-29 16:24:09.474 11183 11246 D io.jxcore.node.OutgoingSocketThread: close: Stopping sending thread...
03-29 16:24:09.474 11183 11246 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 1559
03-29 16:24:09.474 11183 11246 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 1557)
03-29 16:24:09.474 11183 11246 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1557)
03-29 16:24:09.474 11183 11246 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-29 16:24:09.474 11183 11246 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-29 16:24:09.474 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-29 16:24:09.479 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-29 16:24:09.479 11183 11246 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@6c0054e, channel: 6, state: LISTENING
03-29 16:24:09.479 11183 12025 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 1559, thread name: Sender): Socket closed
03-29 16:24:09.479 11183 12025 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1559, name: Sender)
,03-29 16:24:09.479 11183 11246 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@6c0054e, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1fd306d9, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@9b4366fmSocket: android.net.LocalSocket@132b2f7c impl:android.net.LocalSocketImpl@7c33005 fd:FileDescriptor[116]
03-29 16:24:09.479 11183 11246 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@132b2f7c impl:android.net.LocalSocketImpl@7c33005 fd:FileDescriptor[116]
03-29 16:24:09.479  5848  5997 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0x13):jv handle:0x0 not FOUND
03-29 16:24:09.479  5848  5997 E bt-btif : bta_jv_port_mgmt_sr_cback, p_cb:0x0, p_cb->p_cback0x0
03-29 16:24:09.479 11183 11246 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-29 16:24:09.479 11183 11985 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-29 16:24:09.479 11183 11985 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,03-29 16:24:09.479 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-29 16:24:09.479 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-29 16:24:09.479 11183 11985 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-29 16:24:09.479 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-29 16:24:09.479 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-29 16:24:09.479 11183 11183 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-29 16:24:09.479 11183 11183 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-29 16:24:09.479 11183 11183 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-29 16:24:09.479 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-29 16:24:09.479 11183 11246 D BluetoothLeScanner: could not find callback wrapper
03-29 16:24:09.479 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-29 16:24:09.479 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-29 16:24:09.479  5848  5997 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0x14):jv handle:0x0 not FOUND
,03-29 16:24:09.484  5848  5941 D BtGatt.AdvertiseManager: message : 1
,03-29 16:24:09.484  5848  5941 D BtGatt.AdvertiseManager: stop advertise for client 7
03-29 16:24:09.484  5848  5941 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-29 16:24:09.484  5848  5941 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,03-29 16:24:09.484  5848  5919 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
,03-29 16:24:09.484  5848  5919 D BtGatt.GattService: Client app is not null!
03-29 16:24:09.489  5848  5938 D BtGatt.GattService: unregisterClient() - clientIf=7
,03-29 16:24:09.489 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-29 16:24:09.489 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-29 16:24:09.489 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-29 16:24:09.489 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-29 16:24:09.489 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-29 16:24:09.489 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-29 16:24:09.489 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-29 16:24:09.489 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-29 16:24:09.489 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-29 16:24:09.489 11183 11246 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-29 16:24:09.489 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-29 16:24:09.489 11183 11183 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 16:24:09.489 11183 11183 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-29 16:24:09.489 11183 11183 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-29 16:24:09.489 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-29 16:24:09.489 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-29 16:24:09.494 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-29 16:24:09.494 11183 11246 I jxcore-log: 
,03-29 16:24:09.494 11183 11183 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-29 16:24:09.499 11183 11246 I jxcore-log: ok 179 Should be able to call stopAdvertisingAndListening in teardown
03-29 16:24:09.499 11183 11246 I jxcore-log: 
,03-29 16:24:09.499 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
,03-29 16:24:09.504 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-29 16:24:09.504 11183 11183 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-29 16:24:09.504 11183 11183 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-29 16:24:09.504 11183 11183 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-29 16:24:09.509 11183 11246 I jxcore-log: # setup
03-29 16:24:09.509 11183 11246 I jxcore-log: 
,03-29 16:24:09.509 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 16:24:09.509 11183 11246 I jxcore-log: 
,03-29 16:24:09.509 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 16:24:09.509 11183 11246 I jxcore-log: 
,03-29 16:24:10.049 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-29 16:24:10.049 11183 11246 I jxcore-log: 
,03-29 16:24:10.054 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-29 16:24:10.054 11183 11246 I jxcore-log: 
,03-29 16:24:10.059 11183 11246 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-29 16:24:10.059 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-29 16:24:10.059 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-29 16:24:10.059 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-29 16:24:10.059 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-29 16:24:10.059 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-29 16:24:10.059 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-29 16:24:10.059 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-29 16:24:10.064 11183 11246 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-29 16:24:10.069 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-29 16:24:10.069 11183 11246 I jxcore-log: 
,03-29 16:24:10.074 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-29 16:24:10.074 11183 11246 I jxcore-log: 
,03-29 16:24:10.074 11183 11246 I jxcore-log: # 42. #startListeningForAdvertisements should fail if start not called
03-29 16:24:10.074 11183 11246 I jxcore-log: 
,03-29 16:24:10.079 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-29 16:24:10.079 11183 11246 I jxcore-log: 
,03-29 16:24:10.534  3452  3651 D SecContentProvider2: query(), uri = 15 selection = getAppBlockDownloadState
,03-29 16:24:10.534  3753 11763 V DownloadManager: 1 items are running
,03-29 16:24:10.594  3452  3836 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-29 16:24:10.594  3452  3836 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-29 16:24:10.594  3452  3836 D BatteryService: online:4, current avg:36, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:31
03-29 16:24:10.594  3452  3836 D BatteryService: stay LED for fully charged
03-29 16:24:10.594  3452  3452 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-29 16:24:10.594  3452  3452 I MotionRecognitionService: Plugged
03-29 16:24:10.594  3452  3452 D MotionRecognitionService:   cableConnection= 1
03-29 16:24:10.594  3452  3452 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-29 16:24:10.594  3452  3452 D MotionRecognitionService: skip setTransmitPower. 
,03-29 16:24:10.599  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-29 16:24:10.599  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-29 16:24:10.599  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-29 16:24:10.604  5848  5848 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-29 16:24:10.604  5848  5945 D HeadsetStateMachine: Disconnected process message: 10
,03-29 16:24:10.619  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-29 16:24:10.619  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-29 16:24:10.619  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-29 16:24:10.624  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-29 16:24:10.949  3452  6034 D SSRM:n  : SIOP:: AP = 280, PST = 284 (W:14), CUR = 36, LCD = 0,
,03-29 16:24:11.014 11183 11246 I jxcore-log: ok 180 specific error should be returned
03-29 16:24:11.014 11183 11246 I jxcore-log: 
,03-29 16:24:11.019 11183 11246 I jxcore-log: # teardown
03-29 16:24:11.019 11183 11246 I jxcore-log: 
,03-29 16:24:11.459 11183 11246 I jxcore-log: ok 181 must be stopped
03-29 16:24:11.459 11183 11246 I jxcore-log: 
,03-29 16:24:11.464 11183 11246 I jxcore-log: # setup
03-29 16:24:11.464 11183 11246 I jxcore-log: 
,03-29 16:24:12.204 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-29 16:24:12.204 11183 11246 I jxcore-log: 
,03-29 16:24:12.209 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-29 16:24:12.209 11183 11246 I jxcore-log: 
,03-29 16:24:12.219 11183 11246 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-29 16:24:12.219 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-29 16:24:12.219 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-29 16:24:12.219 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-29 16:24:12.219 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-29 16:24:12.219 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-29 16:24:12.219 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-29 16:24:12.219 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-29 16:24:12.224 11183 11246 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-29 16:24:12.224 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-29 16:24:12.224 11183 11246 I jxcore-log: 
,03-29 16:24:12.229 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-29 16:24:12.229 11183 11246 I jxcore-log: 
,03-29 16:24:12.234 11183 11246 I jxcore-log: # 43. #startUpdateAdvertisingAndListening should fail if start not called
03-29 16:24:12.234 11183 11246 I jxcore-log: 
,03-29 16:24:12.234 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-29 16:24:12.234 11183 11246 I jxcore-log: 
,03-29 16:24:12.269  3452  3836 D SecContentProvider2: query(), uri = 15 selection = getAppBlockDownloadState
,03-29 16:24:12.274  3753 11763 V DownloadManager: 1 items are running
,03-29 16:24:12.519 11183 11246 I jxcore-log: ok 182 specific error should be returned
03-29 16:24:12.519 11183 11246 I jxcore-log: 
,03-29 16:24:12.519 11183 11246 I jxcore-log: # teardown
03-29 16:24:12.519 11183 11246 I jxcore-log: 
,03-29 16:24:12.724 11183 11246 I jxcore-log: ok 183 must be stopped
03-29 16:24:12.724 11183 11246 I jxcore-log: 
,03-29 16:24:12.729 11183 11246 I jxcore-log: # setup
03-29 16:24:12.729 11183 11246 I jxcore-log: 
,03-29 16:24:12.884 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-29 16:24:12.884 11183 11246 I jxcore-log: 
,03-29 16:24:12.889 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-29 16:24:12.889 11183 11246 I jxcore-log: 
,03-29 16:24:12.899 11183 11246 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-29 16:24:12.899 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-29 16:24:12.899 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-29 16:24:12.899 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-29 16:24:12.899 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-29 16:24:12.899 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-29 16:24:12.899 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-29 16:24:12.899 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-29 16:24:12.899 11183 11246 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-29 16:24:12.904 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-29 16:24:12.904 11183 11246 I jxcore-log: 
,03-29 16:24:12.904 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-29 16:24:12.904 11183 11246 I jxcore-log: 
,03-29 16:24:12.909 11183 11246 I jxcore-log: # 44. should be able to call #stopListeningForAdvertisements many times
03-29 16:24:12.909 11183 11246 I jxcore-log: 
,03-29 16:24:12.914 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-29 16:24:12.914 11183 11246 I jxcore-log: 
,03-29 16:24:13.059 11183 11246 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 16:24:13.059 11183 11246 I jxcore-log: 
,03-29 16:24:13.064 11183 11246 I jxcore-log: DEBUG createNativeListener: listening 38809
03-29 16:24:13.064 11183 11246 I jxcore-log: 
,03-29 16:24:13.064 11183 11246 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-29 16:24:13.064 11183 11246 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-29 16:24:13.064 11183 11246 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 16:24:13.069 11183 11246 I jxcore-log: ok 184 no errors
03-29 16:24:13.069 11183 11246 I jxcore-log: 
,03-29 16:24:13.074 11183 11246 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-29 16:24:13.074 11183 11246 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-29 16:24:13.074 11183 11246 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 16:24:13.079 11183 11246 I jxcore-log: ok 185 still no errors
03-29 16:24:13.079 11183 11246 I jxcore-log: 
,03-29 16:24:13.089 11183 11246 I jxcore-log: # teardown
03-29 16:24:13.089 11183 11246 I jxcore-log: 
,03-29 16:24:13.194 11183 11246 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-29 16:24:13.194 11183 11246 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 16:24:13.194 11183 11246 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 16:24:13.199 11183 11246 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-29 16:24:13.199 11183 11246 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-29 16:24:13.199 11183 11246 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 16:24:13.214 11183 11246 I jxcore-log: ok 186 must be stopped
03-29 16:24:13.214 11183 11246 I jxcore-log: 
,03-29 16:24:13.224 11183 11246 I jxcore-log: # setup
03-29 16:24:13.224 11183 11246 I jxcore-log: 
,03-29 16:24:13.359 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-29 16:24:13.359 11183 11246 I jxcore-log: 
,03-29 16:24:13.364 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-29 16:24:13.364 11183 11246 I jxcore-log: 
,03-29 16:24:13.369 11183 11246 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-29 16:24:13.369 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-29 16:24:13.369 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-29 16:24:13.369 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-29 16:24:13.369 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-29 16:24:13.369 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-29 16:24:13.369 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-29 16:24:13.369 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-29 16:24:13.374 11183 11246 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-29 16:24:13.379 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-29 16:24:13.379 11183 11246 I jxcore-log: 
,03-29 16:24:13.379 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-29 16:24:13.379 11183 11246 I jxcore-log: 
,03-29 16:24:13.384 11183 11246 I jxcore-log: # 45. should be able to call #startListeningForAdvertisements many times
03-29 16:24:13.384 11183 11246 I jxcore-log: 
,03-29 16:24:13.389 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-29 16:24:13.389 11183 11246 I jxcore-log: 
,03-29 16:24:13.524  5848  5997 E bt-btm  : Reset sec_bd_name and name flag. (BR/EDR link)
,03-29 16:24:13.529  5848  5997 E bt-btm  : btm_sec_disconnected - Clearing Pending flag,
03-29 16:24:13.529  5848  5997 W bt-btif : bta_dm_acl_change(), event : 1
03-29 16:24:13.534  5848  5997 W bt-btif : bta_dm_acl_change(), event : 2
03-29 16:24:13.539  5848  5919 E BluetoothRemoteDevices: aclStateChangeCallback: State:DisConnected to Device:F8:CF:C5:D9:E5:XX
,03-29 16:24:13.559  5848  5919 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
03-29 16:24:13.559  3726  3726 D KeyguardViewMediator: Received android.bluetooth.device.action.ACL_DISCONNECTED
,03-29 16:24:13.569  3452  3452 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
03-29 16:24:13.569  3452  3452 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.device.action.ACL_DISCONNECTED
03-29 16:24:13.569  3452  3452 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_ACL_DISCONNECTED
,03-29 16:24:13.589  3452  3572 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{122a12b1 u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{21c88728 5848:com.android.bluetooth/1002}
,03-29 16:24:13.599  5848  5848 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c37c702
03-29 16:24:13.599  5848  5848 D BtConfig.SecureMode: isSecureModeOn:false
03-29 16:24:13.599  3452  3491 D SecContentProvider: query(), uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,03-29 16:24:13.604  5848  5848 I BluetoothPbapService: action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
03-29 16:24:13.604  3452  4020 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
03-29 16:24:13.609  3726  3726 D KeyguardViewMediator: isGear1: device is not B1!
,03-29 16:24:13.609  3452  3599 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-29 16:24:13.609  3452  3599 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-29 16:24:13.609  3452  3599 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-29 16:24:13.609  3452  3599 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-29 16:24:13.634 12126 12126 E Zygote  : MountEmulatedStorage()
,03-29 16:24:13.634 11183 11246 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 16:24:13.634 11183 11246 I jxcore-log: 
,03-29 16:24:13.634 12126 12126 E Zygote  : v2
03-29 16:24:13.634 12126 12126 I libpersona: KNOX_SDCARD checking this for 10036
,03-29 16:24:13.639 12126 12126 I libpersona: KNOX_SDCARD not a persona
,03-29 16:24:13.644 12126 12126 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
,03-29 16:24:13.649 11183 11246 I jxcore-log: DEBUG createNativeListener: listening 60284
03-29 16:24:13.649 11183 11246 I jxcore-log: 
,03-29 16:24:13.654  3452  3599 I ActivityManager: Start proc 12126:com.sec.android.app.shealth/u0a36 for broadcast-3 com.sec.android.app.shealth/com.samsung.android.app.shealth.tracker.weight.receiver.TrackerWeightReceiver
,03-29 16:24:13.659 12126 12126 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
,03-29 16:24:13.664 12126 12126 E Zygote  : accessInfo : 0
,03-29 16:24:13.664 12126 12126 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-29 16:24:13.679 11183 11246 I io.jxcore.node.ConnectionHelper: start: Port number: 40475, start advertisements: false
03-29 16:24:13.679 11183 11246 I io.jxcore.node.ConnectionHelper: restoreDefaultBleDiscoverySettings: Powering the BLE discovery back up
03-29 16:24:13.679 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 0 -> 2
03-29 16:24:13.679 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-29 16:24:13.679 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-29 16:24:13.679 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-29 16:24:13.679 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-29 16:24:13.679 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-29 16:24:13.679 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-29 16:24:13.679 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 1, timeout: 0, is connectable: false
03-29 16:24:13.679 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-29 16:24:13.679 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 1 -> 3
03-29 16:24:13.679 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-29 16:24:13.679 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-29 16:24:13.679 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-29 16:24:13.679 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-29 16:24:13.679 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-29 16:24:13.679 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-29 16:24:13.679 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-29 16:24:13.679 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-29 16:24:13.679 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 0 -> 2
03-29 16:24:13.679 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-29 16:24:13.679 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-29 16:24:13.679 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-29 16:24:13.679 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-29 16:24:13.679 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-29 16:24:13.679 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-29 16:24:13.679 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectab,le: false
03-29 16:24:13.679 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-29 16:24:13.679 11183 11246 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-29 16:24:13.679 11183 11246 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-29 16:24:13.679 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-29 16:24:13.694 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-29 16:24:13.694  3452  3998 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
03-29 16:24:13.694 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-29 16:24:13.694 11183 11246 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-29 16:24:13.699  5848  8884 D BtGatt.GattService: registerClient() - UUID=acb7ebda-b741-46e1-b6e2-9b08df7dfb4d
,03-29 16:24:13.714 10322 12145 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.ACL_DISCONNECTED State = -2147483648 Previous = -2147483648
,03-29 16:24:13.719 10322 10322 D [CarModeFW]: ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED
03-29 16:24:13.719 10322 10322 D [CarModeFW]: ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED onNotifyBluetoothDeviceDisconnected
,03-29 16:24:13.719 12126 12126 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-29 16:24:13.724 10322 10322 D [CarModeFW]: ConnectivityManager-Paired Devices list is empty
03-29 16:24:13.724 10322 10322 E [CarMode]: [BluetoothConnectivityListener]-onNotifyBluetoothProfileDisconnected: Unexpected error: Invalid device
,03-29 16:24:13.724 12126 12126 D ActivityThread: Added TimaKeyStore provider
,03-29 16:24:13.734  3452  3998 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{122a12b1 u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{c5e3b17 12126:com.sec.android.app.shealth/u0a36}
,03-29 16:24:13.739  5848  5919 D BtGatt.GattService: onClientRegistered() - UUID=acb7ebda-b741-46e1-b6e2-9b08df7dfb4d, clientIf=6
03-29 16:24:13.739 11183 11939 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-29 16:24:13.739  5848  8884 D BtGatt.GattService: start scan with filters
,03-29 16:24:13.744 12126 12126 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-29 16:24:13.754  5848  8884 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 85
,03-29 16:24:13.754 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-29 16:24:13.754 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-29 16:24:13.754 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-29 16:24:13.754 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-29 16:24:13.754  5848  5944 D BtGatt.ScanManager: handling starting scan
03-29 16:24:13.754 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 16:24:13.754  5848  5944 D BtGatt.ScanManager: isFilteringSupported
03-29 16:24:13.754  5848  5944 D BluetoothAdapter: setting StandAloneBleMode
03-29 16:24:13.754 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-29 16:24:13.754 11183 11183 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-29 16:24:13.759 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-29 16:24:13.759 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-29 16:24:13.759 11183 11246 I io.jxcore.node.ConnectionHelper: start: OK
03-29 16:24:13.759  5848  5919 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-29 16:24:13.759 11183 11183 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-29 16:24:13.759  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:24:13.759 11183 11183 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 16:24:13.759  5848  5944 D BtGatt.ScanManager: allow scan with filters
,03-29 16:24:13.759  5848  5944 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-29 16:24:13.759  5848  5944 D BtGatt.ScanManager: set filter index= 6 for clientIf= 6
03-29 16:24:13.759 11183 11183 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-29 16:24:13.759  5848  5919 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-29 16:24:13.759  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:24:13.759  5848  5944 D BtGatt.ScanManager: Starting BLE batch scan,
03-29 16:24:13.759  5848  5944 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-29 16:24:13.764 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 16:24:13.764 11183 11246 I jxcore-log: 
03-29 16:24:13.764  5848  5919 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,03-29 16:24:13.764  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 16:24:13.764 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 16:24:13.764 11183 11246 I jxcore-log: 
03-29 16:24:13.764  5848  5919 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-29 16:24:13.764  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 16:24:13.769 11183 11246 I jxcore-log: ok 187 no errors
03-29 16:24:13.769 11183 11246 I jxcore-log: 
,03-29 16:24:13.774 11183 11246 I io.jxcore.node.ConnectionHelper: start: Port number: 40475, start advertisements: false,
03-29 16:24:13.774 11183 11246 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-29 16:24:13.774 11183 11246 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-29 16:24:13.774 11183 11246 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-29 16:24:13.774 11183 11246 I io.jxcore.node.ConnectionHelper: start: OK
,03-29 16:24:13.779 11183 11246 I jxcore-log: ok 188 still no errors
03-29 16:24:13.779 11183 11246 I jxcore-log: 
,03-29 16:24:13.784 11183 11246 I jxcore-log: # teardown
03-29 16:24:13.784 11183 11246 I jxcore-log: 
,03-29 16:24:13.844 12126 12126 D HealthConsole: Service for HealthDataConsole is connected
,03-29 16:24:13.849  3452  3914 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{122a12b1 u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{c5e3b17 12126:com.sec.android.app.shealth/u0a36}
,03-29 16:24:13.869 12126 12126 D HealthConsole: Service for HealthDataConsole is connected
,03-29 16:24:13.874  3452  3651 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{122a12b1 u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{c5e3b17 12126:com.sec.android.app.shealth/u0a36}
,03-29 16:24:13.879  3452  3914 D SecContentProvider2: query(), uri = 15 selection = getAppBlockDownloadState
,03-29 16:24:13.879  3753 11763 V DownloadManager: 1 items are running
,03-29 16:24:13.884  3452  4020 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{122a12b1 u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{28507108 4113:com.google.android.googlequicksearchbox:search/u0a64}
,03-29 16:24:13.904  4113  4113 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,03-29 16:24:13.904  4113  4113 I BluetoothClassifier: Bluetooth Device Name: Nexus 6
,03-29 16:24:13.939 11183 11246 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-29 16:24:13.939 11183 11246 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
03-29 16:24:13.939 11183 11246 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-29 16:24:13.939 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-29 16:24:13.939 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-29 16:24:13.939 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-29 16:24:13.939 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-29 16:24:13.939 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-29 16:24:13.939 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-29 16:24:13.939  5848  5860 D BtGatt.GattService: stopScan() - queue size =1
,03-29 16:24:13.939  5848  5944 D BtGatt.ScanManager: filter size is 1
03-29 16:24:13.939  5848  5944 D BtGatt.ScanManager: delete FilterIndex - 6
,03-29 16:24:13.939  5848  5938 D BtGatt.GattService: unregisterClient() - clientIf=6
03-29 16:24:13.939  5848  5919 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-29 16:24:13.939  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:24:13.939 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
03-29 16:24:13.939  5848  5944 D BtGatt.ScanManager: stopping BLe Batch
03-29 16:24:13.939 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-29 16:24:13.939 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-29 16:24:13.939 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-29 16:24:13.939 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-29 16:24:13.944 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-29 16:24:13.944 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-29 16:24:13.944 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-29 16:24:13.944 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-29 16:24:13.944 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-29 16:24:13.944 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-29 16:24:13.944 11183 11183 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-29 16:24:13.944 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-29 16:24:13.944 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-29 16:24:13.944  5848  5919 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-29 16:24:13.944  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:24:13.944  5848  5944 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-29 16:24:13.944  5848  5919 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,03-29 16:24:13.944  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 16:24:13.949 11183 11183 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-29 16:24:13.954 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-29 16:24:13.954 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-29 16:24:13.954 11183 11183 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-29 16:24:13.954 11183 11183 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-29 16:24:13.954 11183 11183 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 16:24:13.954 11183 11183 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 16:24:13.959 11183 11183 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-29 16:24:13.959 11183 11246 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-29 16:24:13.959 11183 11246 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-29 16:24:13.959 11183 11246 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 16:24:13.959 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 16:24:13.959 11183 11246 I jxcore-log: 
,03-29 16:24:13.959 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 16:24:13.959 11183 11246 I jxcore-log: 
,03-29 16:24:13.964 11183 11246 I jxcore-log: ok 189 must be stopped
03-29 16:24:13.964 11183 11246 I jxcore-log: 
,03-29 16:24:13.969 11183 11246 I jxcore-log: # setup
03-29 16:24:13.969 11183 11246 I jxcore-log: 
,03-29 16:24:14.189 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-29 16:24:14.189 11183 11246 I jxcore-log: 
,03-29 16:24:14.194 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-29 16:24:14.194 11183 11246 I jxcore-log: 
,03-29 16:24:14.204 11183 11246 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-29 16:24:14.204 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-29 16:24:14.204 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-29 16:24:14.204 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-29 16:24:14.204 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-29 16:24:14.204 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-29 16:24:14.204 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-29 16:24:14.204 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-29 16:24:14.209 11183 11246 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-29 16:24:14.214 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-29 16:24:14.214 11183 11246 I jxcore-log: 
,03-29 16:24:14.219 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-29 16:24:14.219 11183 11246 I jxcore-log: 
,03-29 16:24:14.224 11183 11246 I jxcore-log: # 46. should be able to call #startUpdateAdvertisingAndListening many times
03-29 16:24:14.224 11183 11246 I jxcore-log: 
,03-29 16:24:14.229 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-29 16:24:14.229 11183 11246 I jxcore-log: 
,03-29 16:24:14.454 11183 11246 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 16:24:14.454 11183 11246 I jxcore-log: 
,03-29 16:24:14.459 11183 11246 I jxcore-log: DEBUG createNativeListener: listening 52967
03-29 16:24:14.459 11183 11246 I jxcore-log: 
,03-29 16:24:14.469 11183 11246 I io.jxcore.node.ConnectionHelper: start: Port number: 52967, start advertisements: true
,03-29 16:24:14.469 11183 11246 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-29 16:24:14.469 11183 11246 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,03-29 16:24:14.474 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-29 16:24:14.474 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-29 16:24:14.474 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-29 16:24:14.474 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-29 16:24:14.479 11183 11246 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-29 16:24:14.479  5848  5938 D BtGatt.GattService: registerClient() - UUID=df88aa0a-65dc-48e6-a123-ec8937e0a28f
,03-29 16:24:14.524  5848  5919 D BtGatt.GattService: onClientRegistered() - UUID=df88aa0a-65dc-48e6-a123-ec8937e0a28f, clientIf=6
,03-29 16:24:14.524 11183 11193 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-29 16:24:14.524  5848  5857 D BtGatt.GattService: start scan with filters
,03-29 16:24:14.534  5848  5857 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 86
,03-29 16:24:14.534 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-29 16:24:14.534 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-29 16:24:14.534  5848  5944 D BtGatt.ScanManager: handling starting scan
03-29 16:24:14.534 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-29 16:24:14.534  5848  5944 D BtGatt.ScanManager: isFilteringSupported
03-29 16:24:14.534 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-29 16:24:14.534  5848  5944 D BluetoothAdapter: setting StandAloneBleMode
03-29 16:24:14.534 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 16:24:14.534 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-29 16:24:14.534 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-29 16:24:14.534 11183 11183 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 16:24:14.534 11183 11246 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-29 16:24:14.534 11183 11246 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 16:24:14.534 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 16:24:14.534 11183 11246 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-29 16:24:14.534  5848  5919 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,03-29 16:24:14.539  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:24:14.539  5848  5944 D BtGatt.ScanManager: allow scan with filters
03-29 16:24:14.539  5848  5944 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-29 16:24:14.539  5848  5944 D BtGatt.ScanManager: set filter index= 7 for clientIf= 6
,03-29 16:24:14.539  5848  5919 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,03-29 16:24:14.539  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:24:14.539  5848  5944 D BtGatt.ScanManager: Starting BLE batch scan
03-29 16:24:14.539  5848  5944 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-29 16:24:14.539  5848  5860 D BtGatt.GattService: registerClient() - UUID=51d6b05d-9c4f-4295-bd7f-a50cd6d43b7a
,03-29 16:24:14.539  5848  5919 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0,
03-29 16:24:14.539  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 16:24:14.544  5848  5919 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,03-29 16:24:14.544  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 16:24:14.579  5848  5919 D BtGatt.GattService: onClientRegistered() - UUID=51d6b05d-9c4f-4295-bd7f-a50cd6d43b7a, clientIf=7
,03-29 16:24:14.579 11183 11939 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-29 16:24:14.594  5848  8884 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 69,
03-29 16:24:14.594  5848  5941 D BtGatt.AdvertiseManager: message : 0
03-29 16:24:14.599  5848  5941 D BtGatt.AdvertiseManager: number of adv instance running0
03-29 16:24:14.599  5848  5941 D BtGatt.AdvertiseManager: size of list is =0
,03-29 16:24:14.604  5848  5941 D BtGatt.AdvertiseManager: starting advertising,
03-29 16:24:14.604  5848  5941 D BtGatt.AdvertiseManager: isStandardAdvfalse,
,03-29 16:24:14.604  5848  5919 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
03-29 16:24:14.609  5848  5941 D BtGatt.AdvertiseManager: starting multi advertising
03-29 16:24:14.609  5848  5919 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
03-29 16:24:14.609  5848  5941 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-29 16:24:14.609  5848  5941 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
03-29 16:24:14.614 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-29 16:24:14.614 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-29 16:24:14.614 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-29 16:24:14.614 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-29 16:24:14.614 11183 11246 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-29 16:24:14.614 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-29 16:24:14.619 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...,
03-29 16:24:14.619 11183 11246 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,03-29 16:24:14.619 11183 11246 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-29 16:24:14.619 11183 11246 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK,
03-29 16:24:14.619 11183 11183 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-29 16:24:14.619 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-29 16:24:14.619 11183 11183 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-29 16:24:14.619 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,03-29 16:24:14.619 11183 11183 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-29 16:24:14.619 11183 11183 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-29 16:24:14.619 11183 11183 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true,
,03-29 16:24:14.619 11183 11183 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-29 16:24:14.619 11183 11183 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,03-29 16:24:14.619 11183 11183 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 16:24:14.619 11183 11183 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,03-29 16:24:14.619 11183 11183 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true,
03-29 16:24:14.619 11183 11246 I io.jxcore.node.ConnectionHelper: start: OK
,03-29 16:24:14.639 11183 12180 D BluetoothSocket: bindListen(): myUserId = 0
03-29 16:24:14.639 11183 12180 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback,
03-29 16:24:14.639 11183 12180 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[112]}
,03-29 16:24:14.639 11183 12180 D BluetoothSocket: bindListen(), new LocalSocket 
03-29 16:24:14.639 11183 12180 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() ,
03-29 16:24:14.639 11183 12180 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2617f214,
03-29 16:24:14.639 11183 12180 D BluetoothSocket: channel: 6
03-29 16:24:14.639 11183 12180 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...,
03-29 16:24:14.644 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false},
03-29 16:24:14.644 11183 11246 I jxcore-log: 
,03-29 16:24:14.649 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false},
03-29 16:24:14.649 11183 11246 I jxcore-log: 
,03-29 16:24:14.654 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-29 16:24:14.654 11183 11246 I jxcore-log: 
,03-29 16:24:14.654 11183 11246 I jxcore-log: ok 190 no errors
03-29 16:24:14.654 11183 11246 I jxcore-log: 
,03-29 16:24:14.659 11183 11246 I io.jxcore.node.ConnectionHelper: start: Port number: 52967, start advertisements: true
,03-29 16:24:14.659 11183 11246 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-29 16:24:14.659 11183 11246 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-29 16:24:14.659 11183 11246 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 16:24:14.664 11183 11246 I io.jxcore.node.ConnectionHelper: start: OK
,03-29 16:24:14.664 11183 11246 I jxcore-log: ok 191 still no errors
03-29 16:24:14.664 11183 11246 I jxcore-log: 
,03-29 16:24:14.674 11183 11246 I jxcore-log: # teardown
03-29 16:24:14.674 11183 11246 I jxcore-log: 
,03-29 16:24:14.754  3452  3653 V NetworkStats: performPollLocked(flags=0x1)
,03-29 16:24:14.754  3452  3653 D NtpTrustedTime: currentTimeMillis() cache hit
,03-29 16:24:14.799  3452  3653 D NtpTrustedTime: currentTimeMillis() cache hit
03-29 16:24:14.799  3452  3653 V NetworkStats: performPollLocked() took 43ms
,03-29 16:24:14.799  3452  3654 D NtpTrustedTime: currentTimeMillis() cache hit
03-29 16:24:14.799  3452  3654 D NtpTrustedTime: currentTimeMillis() cache hit
,03-29 16:24:15.074 11183 11246 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-29 16:24:15.074 11183 11246 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
,03-29 16:24:15.074 11183 11246 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,03-29 16:24:15.074 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...,
03-29 16:24:15.079 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,03-29 16:24:15.079 11183 11246 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@136c5abd, channel: 6, state: LISTENING
,03-29 16:24:15.079 11183 11246 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@136c5abd, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2617f214, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@33f668b2mSocket: android.net.LocalSocket@1f7d0003 impl:android.net.LocalSocketImpl@38c1b80 fd:FileDescriptor[112],
03-29 16:24:15.079 11183 11246 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1f7d0003 impl:android.net.LocalSocketImpl@38c1b80 fd:FileDescriptor[112]
,03-29 16:24:15.084 11183 11246 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed,
,03-29 16:24:15.084 11183 12180 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-29 16:24:15.084 11183 12180 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,03-29 16:24:15.084 11183 12180 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-29 16:24:15.084 11183 11183 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-29 16:24:15.089 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-29 16:24:15.089 11183 11183 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-29 16:24:15.089 11183 11183 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-29 16:24:15.089 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-29 16:24:15.089 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-29 16:24:15.089 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode,
,03-29 16:24:15.089 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser,
,03-29 16:24:15.089 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...,
03-29 16:24:15.094  5848  5938 D BtGatt.GattService: stopScan() - queue size =1
,03-29 16:24:15.094  5848  5944 D BtGatt.ScanManager: filter size is 1
03-29 16:24:15.094  5848  5944 D BtGatt.ScanManager: delete FilterIndex - 7
03-29 16:24:15.094  5848  5919 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,03-29 16:24:15.094  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:24:15.094  5848  5944 D BtGatt.ScanManager: stopping BLe Batch,
,03-29 16:24:15.099  5848  5857 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-29 16:24:15.099  5848  5919 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0,
03-29 16:24:15.099  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 16:24:15.099  5848  5944 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-29 16:24:15.104  5848  5919 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
03-29 16:24:15.104  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:24:15.104  5848  5919 D BtGatt.GattService: current time is 280781256407,
03-29 16:24:15.104  5848  5919 D BtGatt.GattService: Batch record : [-66, -94, -84, 82, -79, 89, 1, -128, -76, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -116, -108, -38, 63, -109, 69, 1, -128, -60, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0]
03-29 16:24:15.104  5848  5919 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-29 16:24:15.104  5848  5919 D ScanRecord: parseFromBytes
03-29 16:24:15.104  5848  5919 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97],
,03-29 16:24:15.104  5848  5919 D ScanRecord: parseFromBytes
,03-29 16:24:15.109 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-29 16:24:15.109 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-29 16:24:15.109 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,03-29 16:24:15.109 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-29 16:24:15.109 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-29 16:24:15.109 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-29 16:24:15.109 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-29 16:24:15.114  5848  5941 D BtGatt.AdvertiseManager: message : 1
03-29 16:24:15.114  5848  5941 D BtGatt.AdvertiseManager: stop advertise for client 7
03-29 16:24:15.114  5848  5941 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-29 16:24:15.114  5848  5941 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-29 16:24:15.114  5848  5919 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
,03-29 16:24:15.114  5848  5919 D BtGatt.GattService: Client app is not null!
03-29 16:24:15.119  5848  5938 D BtGatt.GattService: unregisterClient() - clientIf=7
03-29 16:24:15.119 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-29 16:24:15.119 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-29 16:24:15.119 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,03-29 16:24:15.119 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED],
,03-29 16:24:15.119 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED],
03-29 16:24:15.119 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-29 16:24:15.119 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,03-29 16:24:15.119 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-29 16:24:15.119 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-29 16:24:15.119 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-29 16:24:15.119 11183 11183 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-29 16:24:15.119 11183 11183 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 16:24:15.119 11183 11183 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-29 16:24:15.119 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-29 16:24:15.119 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-29 16:24:15.124 11183 11183 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-29 16:24:15.129 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-29 16:24:15.129 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-29 16:24:15.129 11183 11183 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-29 16:24:15.134 11183 11246 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-29 16:24:15.134 11183 11246 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-29 16:24:15.134 11183 11246 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-29 16:24:15.139 11183 11183 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-29 16:24:15.139 11183 11183 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-29 16:24:15.139 11183 11183 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-29 16:24:15.144 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
,03-29 16:24:15.144 11183 11246 I jxcore-log: ,
03-29 16:24:15.154 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 16:24:15.154 11183 11246 I jxcore-log: 
,03-29 16:24:15.154 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 16:24:15.154 11183 11246 I jxcore-log: 
,03-29 16:24:15.159 11183 11246 I jxcore-log: ok 192 must be stopped
03-29 16:24:15.159 11183 11246 I jxcore-log: 
,03-29 16:24:15.169 11183 11246 I jxcore-log: # setup
03-29 16:24:15.169 11183 11246 I jxcore-log: 
,03-29 16:24:15.454  3452  3491 D SecContentProvider2: query(), uri = 15 selection = getAppBlockDownloadState
,03-29 16:24:15.459  3753 11763 V DownloadManager: 1 items are running
,03-29 16:24:15.594 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-29 16:24:15.594 11183 11246 I jxcore-log: 
,03-29 16:24:15.599 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-29 16:24:15.599 11183 11246 I jxcore-log: 
,03-29 16:24:15.614 11183 11246 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-29 16:24:15.614 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-29 16:24:15.614 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-29 16:24:15.614 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-29 16:24:15.614 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-29 16:24:15.614 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-29 16:24:15.614 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-29 16:24:15.614 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-29 16:24:15.619 11183 11246 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
03-29 16:24:15.619 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-29 16:24:15.619 11183 11246 I jxcore-log: 
,03-29 16:24:15.629 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-29 16:24:15.629 11183 11246 I jxcore-log: 
,03-29 16:24:15.634 11183 11246 I jxcore-log: # 47. should be able to call #stopAdvertisingAndListening many times
03-29 16:24:15.634 11183 11246 I jxcore-log: 
,03-29 16:24:15.639 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-29 16:24:15.639 11183 11246 I jxcore-log: 
,03-29 16:24:16.089 11183 11246 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 16:24:16.089 11183 11246 I jxcore-log: 
,03-29 16:24:16.094 11183 11246 I jxcore-log: DEBUG createNativeListener: listening 47472
03-29 16:24:16.094 11183 11246 I jxcore-log: 
,03-29 16:24:16.099 11183 11246 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-29 16:24:16.099 11183 11246 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-29 16:24:16.104 11183 11246 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 16:24:16.109 11183 11246 I jxcore-log: ok 193 no errors
03-29 16:24:16.109 11183 11246 I jxcore-log: 
,03-29 16:24:16.109 11183 11246 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-29 16:24:16.109 11183 11246 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-29 16:24:16.109 11183 11246 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 16:24:16.114 11183 11246 I jxcore-log: ok 194 still no errors
03-29 16:24:16.114 11183 11246 I jxcore-log: 
,03-29 16:24:16.124 11183 11246 I jxcore-log: # teardown
03-29 16:24:16.124 11183 11246 I jxcore-log: 
,03-29 16:24:16.394 11183 11246 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-29 16:24:16.394 11183 11246 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-29 16:24:16.394 11183 11246 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 16:24:16.399 11183 11246 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-29 16:24:16.399 11183 11246 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-29 16:24:16.399 11183 11246 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 16:24:16.414 11183 11246 I jxcore-log: ok 195 must be stopped
03-29 16:24:16.414 11183 11246 I jxcore-log: 
,03-29 16:24:16.419 11183 11246 I jxcore-log: # setup
03-29 16:24:16.419 11183 11246 I jxcore-log: 
,03-29 16:24:16.539 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-29 16:24:16.539 11183 11246 I jxcore-log: 
,03-29 16:24:16.539 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-29 16:24:16.539 11183 11246 I jxcore-log: 
,03-29 16:24:16.549 11183 11246 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-29 16:24:16.549 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-29 16:24:16.549 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-29 16:24:16.549 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-29 16:24:16.549 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-29 16:24:16.549 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-29 16:24:16.549 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-29 16:24:16.549 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-29 16:24:16.554 11183 11246 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-29 16:24:16.554 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-29 16:24:16.554 11183 11246 I jxcore-log: 
,03-29 16:24:16.564 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-29 16:24:16.564 11183 11246 I jxcore-log: 
,03-29 16:24:16.574 11183 11246 I jxcore-log: # 48. can get the network status before starting
03-29 16:24:16.574 11183 11246 I jxcore-log: 
,03-29 16:24:16.574 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-29 16:24:16.574 11183 11246 I jxcore-log: 
,03-29 16:24:16.759 11183 11246 I jxcore-log: ok 196 network status should have certain non-empty properties
03-29 16:24:16.759 11183 11246 I jxcore-log: 
,03-29 16:24:16.764 11183 11246 I jxcore-log: # teardown
03-29 16:24:16.764 11183 11246 I jxcore-log: 
,03-29 16:24:16.844  3452  3861 E Watchdog: !@Sync 9 [03-29 16:24:16.846]
,03-29 16:24:16.934 11183 11246 I jxcore-log: ok 197 must be stopped
03-29 16:24:16.934 11183 11246 I jxcore-log: 
,03-29 16:24:16.939 11183 11246 I jxcore-log: # setup
03-29 16:24:16.939 11183 11246 I jxcore-log: 
,03-29 16:24:17.039 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-29 16:24:17.039 11183 11246 I jxcore-log: 
,03-29 16:24:17.039 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-29 16:24:17.039 11183 11246 I jxcore-log: 
,03-29 16:24:17.054 11183 11246 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-29 16:24:17.054 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-29 16:24:17.054 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-29 16:24:17.054 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-29 16:24:17.054 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-29 16:24:17.054 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-29 16:24:17.054 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-29 16:24:17.054 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-29 16:24:17.064 11183 11246 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-29 16:24:17.064 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-29 16:24:17.064 11183 11246 I jxcore-log: 
,03-29 16:24:17.069 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-29 16:24:17.069 11183 11246 I jxcore-log: 
,03-29 16:24:17.079 11183 11246 I jxcore-log: # 49. error returned with bad router,
,03-29 16:24:17.079 11183 11246 I jxcore-log: 
,03-29 16:24:17.089 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-29 16:24:17.089 11183 11246 I jxcore-log: 
,03-29 16:24:17.149  3452  3651 D SecContentProvider2: query(), uri = 15 selection = getAppBlockDownloadState
,03-29 16:24:17.149  3753 11763 V DownloadManager: 1 items are running
,03-29 16:24:17.234 11183 11246 I jxcore-log: ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
03-29 16:24:17.234 11183 11246 I jxcore-log: 
,03-29 16:24:17.239 11183 11246 I jxcore-log: ok 198 specific error expected
03-29 16:24:17.239 11183 11246 I jxcore-log: 
,03-29 16:24:17.239 11183 11246 I jxcore-log: # teardown
03-29 16:24:17.239 11183 11246 I jxcore-log: 
,03-29 16:24:17.404 11183 11246 I jxcore-log: ok 199 must be stopped
03-29 16:24:17.404 11183 11246 I jxcore-log: 
,03-29 16:24:17.409 11183 11246 I jxcore-log: # setup
03-29 16:24:17.409 11183 11246 I jxcore-log: 
,03-29 16:24:17.559 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-29 16:24:17.559 11183 11246 I jxcore-log: 
,03-29 16:24:17.564 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-29 16:24:17.564 11183 11246 I jxcore-log: 
,03-29 16:24:17.574 11183 11246 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-29 16:24:17.574 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-29 16:24:17.574 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-29 16:24:17.574 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-29 16:24:17.574 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-29 16:24:17.574 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-29 16:24:17.574 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-29 16:24:17.574 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-29 16:24:17.579 11183 11246 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-29 16:24:17.579 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-29 16:24:17.579 11183 11246 I jxcore-log: 
,03-29 16:24:17.584 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-29 16:24:17.584 11183 11246 I jxcore-log: 
,03-29 16:24:17.589 11183 11246 I jxcore-log: # 50. all services are stopped when we call stop
03-29 16:24:17.589 11183 11246 I jxcore-log: 
,03-29 16:24:17.594 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-29 16:24:17.594 11183 11246 I jxcore-log: 
,03-29 16:24:17.769 11183 11246 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 16:24:17.769 11183 11246 I jxcore-log: 
,03-29 16:24:17.769 11183 11246 I jxcore-log: DEBUG createNativeListener: listening 42490
03-29 16:24:17.769 11183 11246 I jxcore-log: 
,03-29 16:24:17.779 11183 11246 I io.jxcore.node.ConnectionHelper: start: Port number: 52967, start advertisements: false
,03-29 16:24:17.779 11183 11246 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-29 16:24:17.779 11183 11246 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,03-29 16:24:17.779 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-29 16:24:17.784 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-29 16:24:17.784 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-29 16:24:17.784 11183 11246 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-29 16:24:17.789  5848  5938 D BtGatt.GattService: registerClient() - UUID=2a0bbeb4-f80b-42b1-b820-810095b6ee5c
,03-29 16:24:17.829  5848  5919 D BtGatt.GattService: onClientRegistered() - UUID=2a0bbeb4-f80b-42b1-b820-810095b6ee5c, clientIf=6
03-29 16:24:17.834 11183 11195 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-29 16:24:17.839  5848  5857 D BtGatt.GattService: start scan with filters
,03-29 16:24:17.859  5848  5857 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 87
,03-29 16:24:17.859  5848  5944 D BtGatt.ScanManager: handling starting scan
03-29 16:24:17.859  5848  5944 D BtGatt.ScanManager: isFilteringSupported
03-29 16:24:17.859  5848  5944 D BluetoothAdapter: setting StandAloneBleMode
,03-29 16:24:17.869  5848  5919 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-29 16:24:17.869  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 16:24:17.869  5848  5944 D BtGatt.ScanManager: allow scan with filters
03-29 16:24:17.869  5848  5944 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-29 16:24:17.869  5848  5944 D BtGatt.ScanManager: set filter index= 8 for clientIf= 6
03-29 16:24:17.869  5848  5919 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-29 16:24:17.869  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 16:24:17.874  5848  5944 D BtGatt.ScanManager: Starting BLE batch scan
03-29 16:24:17.874  5848  5944 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-29 16:24:17.874 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-29 16:24:17.874 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-29 16:24:17.874 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-29 16:24:17.874 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-29 16:24:17.874 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 16:24:17.874 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-29 16:24:17.874 11183 11183 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 16:24:17.874 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-29 16:24:17.874 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-29 16:24:17.874 11183 11183 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-29 16:24:17.874 11183 11183 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 16:24:17.874 11183 11183 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-29 16:24:17.879 11183 11246 I io.jxcore.node.ConnectionHelper: start: OK
03-29 16:24:17.879 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 16:24:17.879 11183 11246 I jxcore-log: 
03-29 16:24:17.879 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 16:24:17.879 11183 11246 I jxcore-log: 
03-29 16:24:17.884  5848  5919 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-29 16:24:17.884  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:24:17.884  5848  5919 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-29 16:24:17.884  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 16:24:17.894 11183 11246 I io.jxcore.node.ConnectionHelper: start: Port number: 42490, start advertisements: true
,03-29 16:24:17.894 11183 11246 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-29 16:24:17.894 11183 11246 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,03-29 16:24:17.894 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-29 16:24:17.899 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-29 16:24:17.899 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
03-29 16:24:17.899 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-29 16:24:17.899 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
,03-29 16:24:17.899 11183 11246 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-29 16:24:17.899 11183 11246 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-29 16:24:17.899 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 16:24:17.904 11183 11246 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-29 16:24:17.904  5848  5860 D BtGatt.GattService: registerClient() - UUID=4192a5b5-8055-4d87-8891-d3d1fb5709b5
,03-29 16:24:17.949  5848  5919 D BtGatt.GattService: onClientRegistered() - UUID=4192a5b5-8055-4d87-8891-d3d1fb5709b5, clientIf=7
,03-29 16:24:17.949 11183 11193 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-29 16:24:17.959  5848  5857 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 70
,03-29 16:24:17.959  5848  5941 D BtGatt.AdvertiseManager: message : 0
,03-29 16:24:17.959  5848  5941 D BtGatt.AdvertiseManager: number of adv instance running0
03-29 16:24:17.959  5848  5941 D BtGatt.AdvertiseManager: size of list is =0
,03-29 16:24:17.959  5848  5941 D BtGatt.AdvertiseManager: starting advertising
03-29 16:24:17.959  5848  5941 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-29 16:24:17.964  5848  5919 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-29 16:24:17.964  5848  5941 D BtGatt.AdvertiseManager: starting multi advertising
,03-29 16:24:17.964  5848  5919 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-29 16:24:17.964  5848  5941 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-29 16:24:17.964  5848  5941 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
03-29 16:24:17.969 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-29 16:24:17.969 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-29 16:24:17.969 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-29 16:24:17.969 11183 11183 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-29 16:24:17.969 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-29 16:24:17.969 11183 11183 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-29 16:24:17.969 11183 11183 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
,03-29 16:24:17.969 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-29 16:24:17.969 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-29 16:24:17.969 11183 11246 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-29 16:24:17.969 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-29 16:24:17.969 11183 11183 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-29 16:24:17.974 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-29 16:24:17.974 11183 11246 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-29 16:24:17.974 11183 11246 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-29 16:24:17.974 11183 11246 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-29 16:24:17.974 11183 11246 I io.jxcore.node.ConnectionHelper: start: OK
03-29 16:24:17.974 11183 11183 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,03-29 16:24:17.974 11183 11183 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 16:24:17.974 11183 11183 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,03-29 16:24:17.979 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-29 16:24:17.979 11183 11246 I jxcore-log: 
03-29 16:24:17.979 11183 12234 D BluetoothSocket: bindListen(): myUserId = 0
03-29 16:24:17.979 11183 12234 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-29 16:24:17.979 11183 12234 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[112]}
,03-29 16:24:17.979 11183 12234 D BluetoothSocket: bindListen(), new LocalSocket 
03-29 16:24:17.979 11183 12234 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-29 16:24:17.979 11183 12234 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@39576fac
03-29 16:24:17.979 11183 12234 D BluetoothSocket: channel: 6
03-29 16:24:17.979 11183 12234 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-29 16:24:17.984 11183 11246 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 16:24:17.984 11183 11246 I jxcore-log: 
,03-29 16:24:17.984 11183 11246 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 16:24:17.984 11183 11246 I jxcore-log: 
,03-29 16:24:17.989 11183 11246 I jxcore-log: DEBUG createNativeListener: new mux
03-29 16:24:17.989 11183 11246 I jxcore-log: 
,03-29 16:24:17.989 11183 11246 I jxcore-log: ok 200 connection to servers manager should succeed after starting
03-29 16:24:17.989 11183 11246 I jxcore-log: 
,03-29 16:24:18.014 11183 11246 I jxcore-log: ok 201 connection to router server should succeed after starting
03-29 16:24:18.014 11183 11246 I jxcore-log: 
,03-29 16:24:18.019 11183 11246 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-29 16:24:18.019 11183 11246 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-29 16:24:18.019 11183 11246 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-29 16:24:18.019 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-29 16:24:18.019 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-29 16:24:18.019 11183 11246 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@19492475, channel: 6, state: LISTENING
,03-29 16:24:18.019 11183 11246 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@19492475, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@39576fac, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@34be5c0amSocket: android.net.LocalSocket@2ed46c7b impl:android.net.LocalSocketImpl@ba1da98 fd:FileDescriptor[112]
03-29 16:24:18.019 11183 11246 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2ed46c7b impl:android.net.LocalSocketImpl@ba1da98 fd:FileDescriptor[112]
03-29 16:24:18.019 11183 11246 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-29 16:24:18.019 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-29 16:24:18.019 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-29 16:24:18.019 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-29 16:24:18.019 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-29 16:24:18.019 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-29 16:24:18.019 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-29 16:24:18.019 11183 12234 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-29 16:24:18.019 11183 12234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-29 16:24:18.019 11183 12234 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-29 16:24:18.019  5848  5938 D BtGatt.GattService: stopScan() - queue size =1
03-29 16:24:18.019  5848  5944 D BtGatt.ScanManager: filter size is 1,
03-29 16:24:18.019  5848  5944 D BtGatt.ScanManager: delete FilterIndex - 8
,03-29 16:24:18.024  5848  5860 D BtGatt.GattService: unregisterClient() - clientIf=6
03-29 16:24:18.024  5848  5919 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-29 16:24:18.024  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:24:18.024  5848  5944 D BtGatt.ScanManager: stopping BLe Batch
03-29 16:24:18.024 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-29 16:24:18.024 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-29 16:24:18.024 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-29 16:24:18.024 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-29 16:24:18.024 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-29 16:24:18.024 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-29 16:24:18.024 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-29 16:24:18.024  5848  5941 D BtGatt.AdvertiseManager: message : 1
03-29 16:24:18.024  5848  5919 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,03-29 16:24:18.024  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:24:18.024  5848  5941 D BtGatt.AdvertiseManager: stop advertise for client 7
03-29 16:24:18.024  5848  5941 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-29 16:24:18.024  5848  5944 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-29 16:24:18.029  5848  5941 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-29 16:24:18.029  5848  5919 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,03-29 16:24:18.029  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 16:24:18.029  5848  5919 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-29 16:24:18.029  5848  5919 D BtGatt.GattService: Client app is not null!
,03-29 16:24:18.029  5848  5857 D BtGatt.GattService: unregisterClient() - clientIf=7
,03-29 16:24:18.029 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-29 16:24:18.029 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,03-29 16:24:18.029 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-29 16:24:18.029 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-29 16:24:18.029 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-29 16:24:18.029 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-29 16:24:18.029 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-29 16:24:18.029 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-29 16:24:18.034 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-29 16:24:18.034 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-29 16:24:18.034 11183 11183 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-29 16:24:18.034 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-29 16:24:18.034 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-29 16:24:18.034 11183 11246 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 16:24:18.034 11183 11246 I jxcore-log: 
,03-29 16:24:18.039 11183 11183 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-29 16:24:18.044 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
03-29 16:24:18.044 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-29 16:24:18.044 11183 11183 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-29 16:24:18.049 11183 11183 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-29 16:24:18.049 11183 11183 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-29 16:24:18.049 11183 11183 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-29 16:24:18.049 11183 11183 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 16:24:18.049 11183 11183 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 16:24:18.049 11183 11183 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-29 16:24:18.049 11183 11183 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-29 16:24:18.049 11183 11183 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-29 16:24:18.054 11183 11246 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-29 16:24:18.054 11183 11246 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-29 16:24:18.054 11183 11246 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 16:24:18.054 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-29 16:24:18.054 11183 11246 I jxcore-log: 
,03-29 16:24:18.054 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 16:24:18.054 11183 11246 I jxcore-log: 
,03-29 16:24:18.059 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 16:24:18.059 11183 11246 I jxcore-log: 
,03-29 16:24:18.064 11183 11246 I jxcore-log: ok 202 is stopped after calling stop
03-29 16:24:18.064 11183 11246 I jxcore-log: 
,03-29 16:24:18.069 11183 11246 I jxcore-log: ok 203 connection to servers manager should fail after stopping
03-29 16:24:18.069 11183 11246 I jxcore-log: 
,03-29 16:24:18.074 11183 11246 I jxcore-log: ok 204 connection to router server should fail after stopping
03-29 16:24:18.074 11183 11246 I jxcore-log: 
,03-29 16:24:18.079 11183 11246 I jxcore-log: # teardown
03-29 16:24:18.079 11183 11246 I jxcore-log: 
,03-29 16:24:18.459 11183 11246 I jxcore-log: ok 205 must be stopped
03-29 16:24:18.459 11183 11246 I jxcore-log: 
,03-29 16:24:18.469 11183 11246 I jxcore-log: # setup
03-29 16:24:18.469 11183 11246 I jxcore-log: 
,03-29 16:24:18.659 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-29 16:24:18.659 11183 11246 I jxcore-log: 
,03-29 16:24:18.659 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-29 16:24:18.659 11183 11246 I jxcore-log: 
,03-29 16:24:18.669 11183 11246 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-29 16:24:18.669 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-29 16:24:18.669 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-29 16:24:18.669 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-29 16:24:18.669 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-29 16:24:18.669 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-29 16:24:18.669 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-29 16:24:18.669 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-29 16:24:18.674  3452  3599 D SecContentProvider2: query(), uri = 15 selection = getAppBlockDownloadState
03-29 16:24:18.674 11183 11246 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-29 16:24:18.679 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-29 16:24:18.679 11183 11246 I jxcore-log: 
,03-29 16:24:18.679  3753 11763 V DownloadManager: 1 items are running
,03-29 16:24:18.679 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-29 16:24:18.679 11183 11246 I jxcore-log: 
,03-29 16:24:18.689 11183 11246 I jxcore-log: # 51. make sure terminateConnection is properly hooked up
03-29 16:24:18.689 11183 11246 I jxcore-log: 
,03-29 16:24:18.689 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-29 16:24:18.689 11183 11246 I jxcore-log: 
,03-29 16:24:19.109 11183 11246 I jxcore-log: ok 206 called with right arguments,
03-29 16:24:19.109 11183 11246 I jxcore-log: 
03-29 16:24:19.109 11183 11246 I jxcore-log: # teardown
03-29 16:24:19.109 11183 11246 I jxcore-log: 
,03-29 16:24:19.609 11183 11246 I jxcore-log: ok 207 must be stopped
03-29 16:24:19.609 11183 11246 I jxcore-log: 
,03-29 16:24:19.619 11183 11246 I jxcore-log: # setup
03-29 16:24:19.619 11183 11246 I jxcore-log: 
,03-29 16:24:19.839 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-29 16:24:19.839 11183 11246 I jxcore-log: 
,03-29 16:24:19.844 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-29 16:24:19.844 11183 11246 I jxcore-log: 
,03-29 16:24:19.854 11183 11246 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-29 16:24:19.854 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-29 16:24:19.854 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-29 16:24:19.854 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-29 16:24:19.854 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-29 16:24:19.854 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-29 16:24:19.854 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-29 16:24:19.854 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-29 16:24:19.854 11183 11246 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-29 16:24:19.859 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-29 16:24:19.859 11183 11246 I jxcore-log: 
,03-29 16:24:19.859 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-29 16:24:19.859 11183 11246 I jxcore-log: 
,03-29 16:24:19.864 11183 11246 I jxcore-log: # 52. make sure terminateListener is properly hooked up
03-29 16:24:19.864 11183 11246 I jxcore-log: 
,03-29 16:24:19.869 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-29 16:24:19.869 11183 11246 I jxcore-log: 
,03-29 16:24:20.064 11183 11246 I jxcore-log: ok 208 called with right arguments
03-29 16:24:20.064 11183 11246 I jxcore-log: 
,03-29 16:24:20.074 11183 11246 I jxcore-log: # teardown
03-29 16:24:20.074 11183 11246 I jxcore-log: 
,03-29 16:24:20.219 11183 11246 I jxcore-log: ok 209 must be stopped
03-29 16:24:20.219 11183 11246 I jxcore-log: 
,03-29 16:24:20.224 11183 11246 I jxcore-log: # setup
03-29 16:24:20.224 11183 11246 I jxcore-log: 
,03-29 16:24:20.364 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-29 16:24:20.364 11183 11246 I jxcore-log: 
,03-29 16:24:20.364 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-29 16:24:20.364 11183 11246 I jxcore-log: 
,03-29 16:24:20.374 11183 11246 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-29 16:24:20.374 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-29 16:24:20.374 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-29 16:24:20.374 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-29 16:24:20.374 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-29 16:24:20.374 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-29 16:24:20.374 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-29 16:24:20.374 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-29 16:24:20.379 11183 11246 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-29 16:24:20.379 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-29 16:24:20.379 11183 11246 I jxcore-log: 
,03-29 16:24:20.384 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-29 16:24:20.384 11183 11246 I jxcore-log: 
,03-29 16:24:20.389 11183 11246 I jxcore-log: # 53. make sure we actually call kill connections properly
03-29 16:24:20.389 11183 11246 I jxcore-log: 
,03-29 16:24:20.389 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-29 16:24:20.389 11183 11246 I jxcore-log: 
,03-29 16:24:20.564 11183 11246 I jxcore-log: ok 210 specific error expected
03-29 16:24:20.564 11183 11246 I jxcore-log: 
,03-29 16:24:20.569 11183 11246 I jxcore-log: # teardown
03-29 16:24:20.569 11183 11246 I jxcore-log: 
,03-29 16:24:20.664  3452  3651 D SecContentProvider2: query(), uri = 15 selection = getAppBlockDownloadState
,03-29 16:24:20.669  3753 11763 V DownloadManager: 1 items are running
,03-29 16:24:20.704  3452  4010 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-29 16:24:20.704  3452  4010 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-29 16:24:20.704  3452  4010 D BatteryService: online:4, current avg:37, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:32
03-29 16:24:20.704  3452  4010 D BatteryService: stay LED for fully charged
03-29 16:24:20.704  3452  3452 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-29 16:24:20.709  3452  3452 I MotionRecognitionService: Plugged
03-29 16:24:20.709  3452  3452 D MotionRecognitionService:   cableConnection= 1
03-29 16:24:20.709  3452  3452 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-29 16:24:20.709  3452  3452 D MotionRecognitionService: skip setTransmitPower. 
,03-29 16:24:20.709  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-29 16:24:20.709  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-29 16:24:20.709  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-29 16:24:20.714  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-29 16:24:20.719  5848  5848 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-29 16:24:20.719  5848  5945 D HeadsetStateMachine: Disconnected process message: 10
,03-29 16:24:20.734  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-29 16:24:20.734  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-29 16:24:20.734  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-29 16:24:20.739 11183 11246 I jxcore-log: ok 211 must be stopped
03-29 16:24:20.739 11183 11246 I jxcore-log: 
,03-29 16:24:20.744 11183 11246 I jxcore-log: # setup
03-29 16:24:20.744 11183 11246 I jxcore-log: 
,03-29 16:24:20.884 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-29 16:24:20.884 11183 11246 I jxcore-log: 
,03-29 16:24:20.889 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-29 16:24:20.889 11183 11246 I jxcore-log: 
,03-29 16:24:20.894 11183 11246 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-29 16:24:20.894 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-29 16:24:20.894 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-29 16:24:20.894 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-29 16:24:20.894 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-29 16:24:20.894 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-29 16:24:20.894 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-29 16:24:20.894 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-29 16:24:20.899 11183 11246 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-29 16:24:20.904 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-29 16:24:20.904 11183 11246 I jxcore-log: 
,03-29 16:24:20.904 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-29 16:24:20.904 11183 11246 I jxcore-log: 
,03-29 16:24:20.909 11183 11246 I jxcore-log: # 54. thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
03-29 16:24:20.909 11183 11246 I jxcore-log: 
,03-29 16:24:20.914 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-29 16:24:20.914 11183 11246 I jxcore-log: 
,03-29 16:24:20.984  3452  6034 D SSRM:n  : SIOP:: AP = 280, PST = 282 (W:14), CUR = 37, LCD = 0
,03-29 16:24:21.104 11183 11246 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 16:24:21.104 11183 11246 I jxcore-log: 
,03-29 16:24:21.109 11183 11246 I jxcore-log: DEBUG createNativeListener: listening 46702
03-29 16:24:21.109 11183 11246 I jxcore-log: 
,03-29 16:24:21.119 11183 11246 I jxcore-log: INFO thaliMobileNativeWrapper: routerPortConnectionFailed - {"routerPort":32906,"error":{}}
03-29 16:24:21.119 11183 11246 I jxcore-log: 
,03-29 16:24:21.124 11183 11246 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-29 16:24:21.124 11183 11246 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 16:24:21.124 11183 11246 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 16:24:21.124 11183 11246 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-29 16:24:21.129 11183 11246 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-29 16:24:21.129 11183 11246 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 16:24:21.144 11183 11246 I jxcore-log: ok 212 failure reason is as expected
03-29 16:24:21.144 11183 11246 I jxcore-log: 
,03-29 16:24:21.144 11183 11246 I jxcore-log: ok 213 error description is as expected
03-29 16:24:21.144 11183 11246 I jxcore-log: 
,03-29 16:24:21.144 11183 11246 I jxcore-log: ok 214 must be stopped
03-29 16:24:21.144 11183 11246 I jxcore-log: 
,03-29 16:24:21.154 11183 11246 I jxcore-log: # teardown
03-29 16:24:21.154 11183 11246 I jxcore-log: 
,03-29 16:24:21.329 11183 11246 I jxcore-log: ok 215 must be stopped
03-29 16:24:21.329 11183 11246 I jxcore-log: 
,03-29 16:24:21.334 11183 11246 I jxcore-log: # setup
03-29 16:24:21.334 11183 11246 I jxcore-log: 
,03-29 16:24:21.489 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-29 16:24:21.489 11183 11246 I jxcore-log: 
,03-29 16:24:21.494 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-29 16:24:21.494 11183 11246 I jxcore-log: 
,03-29 16:24:21.504 11183 11246 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-29 16:24:21.504 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-29 16:24:21.504 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-29 16:24:21.504 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-29 16:24:21.504 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-29 16:24:21.504 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-29 16:24:21.504 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-29 16:24:21.504 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-29 16:24:21.504 11183 11246 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-29 16:24:21.509 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-29 16:24:21.509 11183 11246 I jxcore-log: 
,03-29 16:24:21.514 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-29 16:24:21.514 11183 11246 I jxcore-log: 
,03-29 16:24:21.519 11183 11246 I jxcore-log: # 55. We repeat failedConnection event when we get it from thaliTcpServersManager
03-29 16:24:21.519 11183 11246 I jxcore-log: 
,03-29 16:24:21.524 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-29 16:24:21.524 11183 11246 I jxcore-log: 
,03-29 16:24:21.694 11183 11246 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 16:24:21.694 11183 11246 I jxcore-log: 
,03-29 16:24:21.699 11183 11246 I jxcore-log: DEBUG createNativeListener: listening 51938
03-29 16:24:21.699 11183 11246 I jxcore-log: 
,03-29 16:24:21.704 11183 11246 I jxcore-log: ok 216 peerIdentifier matches
03-29 16:24:21.704 11183 11246 I jxcore-log: 
,03-29 16:24:21.704 11183 11246 I jxcore-log: ok 217 error description matches
03-29 16:24:21.704 11183 11246 I jxcore-log: 
,03-29 16:24:21.709 11183 11246 I jxcore-log: # teardown
03-29 16:24:21.709 11183 11246 I jxcore-log: 
,03-29 16:24:21.869 11183 11246 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-29 16:24:21.869 11183 11246 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-29 16:24:21.869 11183 11246 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 16:24:21.874 11183 11246 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-29 16:24:21.874 11183 11246 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-29 16:24:21.874 11183 11246 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 16:24:21.884 11183 11246 I jxcore-log: ok 218 must be stopped
03-29 16:24:21.884 11183 11246 I jxcore-log: 
,03-29 16:24:21.889 11183 11246 I jxcore-log: # setup
03-29 16:24:21.889 11183 11246 I jxcore-log: 
,03-29 16:24:21.984 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-29 16:24:21.984 11183 11246 I jxcore-log: 
,03-29 16:24:21.984 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-29 16:24:21.984 11183 11246 I jxcore-log: 
,03-29 16:24:21.994 11183 11246 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-29 16:24:21.994 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-29 16:24:21.994 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-29 16:24:21.994 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-29 16:24:21.994 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-29 16:24:21.994 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-29 16:24:21.994 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-29 16:24:21.994 11183 11246 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-29 16:24:21.999 11183 11246 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-29 16:24:22.004 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-29 16:24:22.004 11183 11246 I jxcore-log: 
,03-29 16:24:22.004 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-29 16:24:22.004 11183 11246 I jxcore-log: 
,03-29 16:24:22.019 11183 11246 I jxcore-log: # 56. we successfully receive and replay discoveryAdvertisingStateUpdate
03-29 16:24:22.019 11183 11246 I jxcore-log: 
,03-29 16:24:22.019 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-29 16:24:22.019 11183 11246 I jxcore-log: 
,03-29 16:24:22.129  3452  4028 I ActivityManager: Killing 10214:com.sec.android.app.myfiles/u0a53 (adj 15): emptyCount ##31
,03-29 16:24:22.189 11183 11246 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 16:24:22.189 11183 11246 I jxcore-log: 
,03-29 16:24:22.194 11183 11246 I jxcore-log: DEBUG createNativeListener: listening 58653
03-29 16:24:22.194 11183 11246 I jxcore-log: 
,03-29 16:24:22.204 11183 11246 I io.jxcore.node.ConnectionHelper: start: Port number: 42490, start advertisements: false
,03-29 16:24:22.204 11183 11246 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-29 16:24:22.204 11183 11246 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,03-29 16:24:22.209 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-29 16:24:22.209 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-29 16:24:22.214 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-29 16:24:22.214 11183 11246 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-29 16:24:22.214  5848  5938 D BtGatt.GattService: registerClient() - UUID=57484a28-733a-4649-aba6-76489d61070b
,03-29 16:24:22.259  5848  5919 D BtGatt.GattService: onClientRegistered() - UUID=57484a28-733a-4649-aba6-76489d61070b, clientIf=6
,03-29 16:24:22.259 11183 11195 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-29 16:24:22.259  5848  5857 D BtGatt.GattService: start scan with filters
,03-29 16:24:22.274  5848  5857 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 88
,03-29 16:24:22.274  5848  5944 D BtGatt.ScanManager: handling starting scan
03-29 16:24:22.274  5848  5944 D BtGatt.ScanManager: isFilteringSupported
03-29 16:24:22.274  5848  5944 D BluetoothAdapter: setting StandAloneBleMode
,03-29 16:24:22.284  5848  5919 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-29 16:24:22.284  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 16:24:22.284  5848  5944 D BtGatt.ScanManager: allow scan with filters
03-29 16:24:22.284  5848  5944 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-29 16:24:22.284  5848  5944 D BtGatt.ScanManager: set filter index= 9 for clientIf= 6
03-29 16:24:22.289  5848  5919 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-29 16:24:22.289  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 16:24:22.289  5848  5944 D BtGatt.ScanManager: Starting BLE batch scan
,03-29 16:24:22.289  5848  5944 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-29 16:24:22.289 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-29 16:24:22.289 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-29 16:24:22.289 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-29 16:24:22.289 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-29 16:24:22.289 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 16:24:22.289 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-29 16:24:22.289 11183 11183 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 16:24:22.294 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-29 16:24:22.294 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-29 16:24:22.294 11183 11183 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-29 16:24:22.294 11183 11183 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 16:24:22.294 11183 11183 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-29 16:24:22.294 11183 11246 I io.jxcore.node.ConnectionHelper: start: OK
03-29 16:24:22.299  5848  5919 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-29 16:24:22.299  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:24:22.299  5848  5919 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-29 16:24:22.299  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 16:24:22.304 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false},
03-29 16:24:22.304 11183 11246 I jxcore-log: 
,03-29 16:24:22.309 11183 11246 I jxcore-log: ok 219 discoveryActive matches
03-29 16:24:22.309 11183 11246 I jxcore-log: 
,03-29 16:24:22.314 11183 11246 I jxcore-log: ok 220 advertisingActive matches
03-29 16:24:22.314 11183 11246 I jxcore-log: 
,03-29 16:24:22.314 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 16:24:22.314 11183 11246 I jxcore-log: 
,03-29 16:24:22.314 11183 11246 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-29 16:24:22.319 11183 11246 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
03-29 16:24:22.319 11183 11246 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,03-29 16:24:22.319 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-29 16:24:22.319 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-29 16:24:22.319 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-29 16:24:22.319 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-29 16:24:22.319 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-29 16:24:22.319 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-29 16:24:22.319  5848  5938 D BtGatt.GattService: stopScan() - queue size =1
03-29 16:24:22.324  5848  5944 D BtGatt.ScanManager: filter size is 1
03-29 16:24:22.324  5848  5944 D BtGatt.ScanManager: delete FilterIndex - 9
03-29 16:24:22.324  5848  5919 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-29 16:24:22.324  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:24:22.324  5848  5944 D BtGatt.ScanManager: stopping BLe Batch
,03-29 16:24:22.329  5848  5919 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-29 16:24:22.329  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:24:22.329  5848  5860 D BtGatt.GattService: unregisterClient() - clientIf=6
03-29 16:24:22.329  5848  5944 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-29 16:24:22.329  5848  5919 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-29 16:24:22.329  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 16:24:22.334 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-29 16:24:22.334 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-29 16:24:22.334 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,03-29 16:24:22.334 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-29 16:24:22.334 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-29 16:24:22.334 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-29 16:24:22.334 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
03-29 16:24:22.334 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-29 16:24:22.334 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-29 16:24:22.339 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
03-29 16:24:22.339 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-29 16:24:22.339 11183 11183 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-29 16:24:22.339 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-29 16:24:22.339 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-29 16:24:22.344 11183 11183 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-29 16:24:22.349 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
03-29 16:24:22.354 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-29 16:24:22.354 11183 11183 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-29 16:24:22.354 11183 11183 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false,
03-29 16:24:22.354 11183 11183 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-29 16:24:22.359 11183 11183 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-29 16:24:22.359 11183 11183 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-29 16:24:22.359 11183 11246 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements,
03-29 16:24:22.359 11183 11246 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-29 16:24:22.364 11183 11246 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
,03-29 16:24:22.364 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 16:24:22.364 11183 11246 I jxcore-log: 
,03-29 16:24:22.369 11183 11246 I jxcore-log: ok 221 discoveryActive matches
03-29 16:24:22.369 11183 11246 I jxcore-log: 
,03-29 16:24:22.369 11183 11246 I jxcore-log: ok 222 advertisingActive matches
03-29 16:24:22.369 11183 11246 I jxcore-log: 
,03-29 16:24:22.374 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 16:24:22.374 11183 11246 I jxcore-log: 
,03-29 16:24:22.389 11183 11246 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 16:24:22.389 11183 11246 I jxcore-log: 
,03-29 16:24:22.394 11183 11246 I jxcore-log: DEBUG createNativeListener: listening 57726
03-29 16:24:22.394 11183 11246 I jxcore-log: 
,03-29 16:24:22.399 11183 11246 I io.jxcore.node.ConnectionHelper: start: Port number: 57726, start advertisements: true
,03-29 16:24:22.399 11183 11246 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-29 16:24:22.399 11183 11246 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-29 16:24:22.399 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-29 16:24:22.399 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-29 16:24:22.399 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-29 16:24:22.399 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-29 16:24:22.399 11183 11246 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-29 16:24:22.404  5848  5857 D BtGatt.GattService: registerClient() - UUID=79707709-8c6b-450d-b84a-367a7d982d12
,03-29 16:24:22.429  3452  3651 D SecContentProvider2: query(), uri = 15 selection = getAppBlockDownloadState
,03-29 16:24:22.434  3753 11763 V DownloadManager: 1 items are running
,03-29 16:24:22.444  5848  5919 D BtGatt.GattService: onClientRegistered() - UUID=79707709-8c6b-450d-b84a-367a7d982d12, clientIf=6
03-29 16:24:22.444 11183 11193 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-29 16:24:22.444  5848  8884 D BtGatt.GattService: start scan with filters
03-29 16:24:22.454  5848  8884 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 89
03-29 16:24:22.454 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-29 16:24:22.454 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-29 16:24:22.454 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-29 16:24:22.454 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-29 16:24:22.454  5848  5944 D BtGatt.ScanManager: handling starting scan
03-29 16:24:22.454 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 16:24:22.454  5848  5944 D BtGatt.ScanManager: isFilteringSupported
03-29 16:24:22.454  5848  5944 D BluetoothAdapter: setting StandAloneBleMode
03-29 16:24:22.454 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-29 16:24:22.454 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-29 16:24:22.454 11183 11183 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 16:24:22.454 11183 11246 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-29 16:24:22.454 11183 11246 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 16:24:22.454 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 16:24:22.454 11183 11246 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-29 16:24:22.459  5848  5919 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-29 16:24:22.459  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:24:22.459  5848  5944 D BtGatt.ScanManager: allow scan with filters
03-29 16:24:22.459  5848  5944 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-29 16:24:22.459  5848  5944 D BtGatt.ScanManager: set filter index= 10 for clientIf= 6
03-29 16:24:22.459  5848  5919 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-29 16:24:22.459  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:24:22.459  5848  5944 D BtGatt.ScanManager: Starting BLE batch scan
03-29 16:24:22.459  5848  5944 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-29 16:24:22.459  5848  8884 D BtGatt.GattService: registerClient() - UUID=e8c40727-5a4a-4d3c-98ba-65fe2a8b38ed
03-29 16:24:22.464  5848  5919 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-29 16:24:22.464  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:24:22.464  5848  5919 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-29 16:24:22.464  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 16:24:22.504  5848  5919 D BtGatt.GattService: onClientRegistered() - UUID=e8c40727-5a4a-4d3c-98ba-65fe2a8b38ed, clientIf=7
,03-29 16:24:22.504 11183 11195 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-29 16:24:22.524  5848  5938 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 71
,03-29 16:24:22.524  5848  5941 D BtGatt.AdvertiseManager: message : 0
,03-29 16:24:22.524  5848  5941 D BtGatt.AdvertiseManager: number of adv instance running0
03-29 16:24:22.524  5848  5941 D BtGatt.AdvertiseManager: size of list is =0
,03-29 16:24:22.529  5848  5941 D BtGatt.AdvertiseManager: starting advertising
,03-29 16:24:22.529  5848  5941 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-29 16:24:22.529  5848  5919 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-29 16:24:22.534  5848  5941 D BtGatt.AdvertiseManager: starting multi advertising
,03-29 16:24:22.534  5848  5919 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-29 16:24:22.534  5848  5941 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-29 16:24:22.534  5848  5941 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
03-29 16:24:22.534 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-29 16:24:22.534 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-29 16:24:22.539 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-29 16:24:22.539 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-29 16:24:22.539 11183 11246 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-29 16:24:22.539 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-29 16:24:22.539 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-29 16:24:22.539 11183 11246 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-29 16:24:22.539 11183 11246 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-29 16:24:22.539 11183 11246 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-29 16:24:22.539 11183 11246 I io.jxcore.node.ConnectionHelper: start: OK
03-29 16:24:22.539 11183 11183 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-29 16:24:22.539 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-29 16:24:22.539 11183 11183 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-29 16:24:22.539 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-29 16:24:22.539 11183 11183 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-29 16:24:22.539 11183 11183 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
,03-29 16:24:22.539 11183 11183 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-29 16:24:22.539 11183 11183 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-29 16:24:22.539 11183 11183 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-29 16:24:22.539 11183 11183 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 16:24:22.539 11183 11183 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-29 16:24:22.544 11183 11183 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-29 16:24:22.544 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 16:24:22.544 11183 11246 I jxcore-log: 
,03-29 16:24:22.544 11183 12306 D BluetoothSocket: bindListen(): myUserId = 0,
03-29 16:24:22.544 11183 12306 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-29 16:24:22.549 11183 12306 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[112]}
03-29 16:24:22.549 11183 12306 D BluetoothSocket: bindListen(), new LocalSocket 
03-29 16:24:22.549 11183 12306 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-29 16:24:22.549 11183 12306 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3c2deff3
03-29 16:24:22.549 11183 12306 D BluetoothSocket: channel: 6
03-29 16:24:22.549 11183 12306 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-29 16:24:22.554 11183 11246 I jxcore-log: not ok 223 discoveryActive matches
03-29 16:24:22.554 11183 11246 I jxcore-log: 
,03-29 16:24:22.559 11183 11246 I jxcore-log:   ---
03-29 16:24:22.559 11183 11246 I jxcore-log: 
03-29 16:24:22.559 11183 11246 I jxcore-log:     operator: equal
03-29 16:24:22.559 11183 11246 I jxcore-log: 
03-29 16:24:22.559 11183 11246 I jxcore-log:     expected: false
03-29 16:24:22.559 11183 11246 I jxcore-log: 
03-29 16:24:22.559 11183 11246 I jxcore-log:     actual:   true
03-29 16:24:22.559 11183 11246 I jxcore-log: 
03-29 16:24:22.559 11183 11246 I jxcore-log:   ...
03-29 16:24:22.559 11183 11246 I jxcore-log: 
,03-29 16:24:22.564 11183 11246 I jxcore-log: not ok 224 advertisingActive matches
03-29 16:24:22.564 11183 11246 I jxcore-log: 
,03-29 16:24:22.564 11183 11246 I jxcore-log:   ---
03-29 16:24:22.564 11183 11246 I jxcore-log: 
03-29 16:24:22.564 11183 11246 I jxcore-log:     operator: equal
03-29 16:24:22.564 11183 11246 I jxcore-log: 
03-29 16:24:22.564 11183 11246 I jxcore-log:     expected: true
03-29 16:24:22.564 11183 11246 I jxcore-log: 
03-29 16:24:22.564 11183 11246 I jxcore-log:     actual:   false
03-29 16:24:22.564 11183 11246 I jxcore-log: 
03-29 16:24:22.564 11183 11246 I jxcore-log:   ...
03-29 16:24:22.564 11183 11246 I jxcore-log: 
,03-29 16:24:22.564 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 16:24:22.564 11183 11246 I jxcore-log: 
,03-29 16:24:22.569 11183 11246 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-29 16:24:22.569 11183 11246 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-29 16:24:22.569 11183 11246 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-29 16:24:22.569 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-29 16:24:22.569 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-29 16:24:22.569 11183 11246 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@279d64b0, channel: 6, state: LISTENING
,03-29 16:24:22.569 11183 11246 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@279d64b0, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3c2deff3, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@22d1af29mSocket: android.net.LocalSocket@195c42ae impl:android.net.LocalSocketImpl@292d984f fd:FileDescriptor[112]
03-29 16:24:22.569 11183 11246 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@195c42ae impl:android.net.LocalSocketImpl@292d984f fd:FileDescriptor[112]
03-29 16:24:22.569 11183 11246 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-29 16:24:22.569 11183 12306 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-29 16:24:22.569 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-29 16:24:22.569 11183 12306 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-29 16:24:22.569 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-29 16:24:22.569 11183 12306 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-29 16:24:22.569 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-29 16:24:22.569 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-29 16:24:22.569 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-29 16:24:22.569 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-29 16:24:22.569 11183 11183 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-29 16:24:22.569 11183 11183 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-29 16:24:22.569  5848  5857 D BtGatt.GattService: stopScan() - queue size =1
03-29 16:24:22.569  5848  5938 D BtGatt.GattService: unregisterClient() - clientIf=6
03-29 16:24:22.569  5848  5944 D BtGatt.ScanManager: filter size is 1
,03-29 16:24:22.569  5848  5944 D BtGatt.ScanManager: delete FilterIndex - 10
03-29 16:24:22.569 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-29 16:24:22.574 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-29 16:24:22.574 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-29 16:24:22.574 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-29 16:24:22.574 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
,03-29 16:24:22.574 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-29 16:24:22.574  5848  5919 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-29 16:24:22.574  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:24:22.574 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-29 16:24:22.574  5848  5944 D BtGatt.ScanManager: stopping BLe Batch
,03-29 16:24:22.574  5848  5941 D BtGatt.AdvertiseManager: message : 1
03-29 16:24:22.574  5848  5941 D BtGatt.AdvertiseManager: stop advertise for client 7
03-29 16:24:22.574  5848  5941 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
,03-29 16:24:22.574  5848  5919 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-29 16:24:22.574  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 16:24:22.574  5848  5944 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-29 16:24:22.574  5848  5941 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-29 16:24:22.574  5848  5919 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-29 16:24:22.574  5848  5919 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 16:24:22.579  5848  5919 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
,03-29 16:24:22.579  5848  5919 D BtGatt.GattService: Client app is not null!
03-29 16:24:22.579  5848  8884 D BtGatt.GattService: unregisterClient() - clientIf=7
,03-29 16:24:22.579 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-29 16:24:22.579 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-29 16:24:22.579 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-29 16:24:22.579 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-29 16:24:22.579 11183 11246 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,03-29 16:24:22.579 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-29 16:24:22.579 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-29 16:24:22.579 11183 11246 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-29 16:24:22.579 11183 11246 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-29 16:24:22.579 11183 11246 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-29 16:24:22.579 11183 11183 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-29 16:24:22.579 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-29 16:24:22.579 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-29 16:24:22.584 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-29 16:24:22.584 11183 11246 I jxcore-log: 
,03-29 16:24:22.584 11183 11183 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-29 16:24:22.589 11183 11246 I jxcore-log: not ok 225 discoveryActive matches
03-29 16:24:22.589 11183 11246 I jxcore-log: 
,03-29 16:24:22.589 11183 11246 I jxcore-log:   ---
03-29 16:24:22.589 11183 11246 I jxcore-log: 
03-29 16:24:22.589 11183 11246 I jxcore-log:     operator: equal
03-29 16:24:22.589 11183 11246 I jxcore-log: 
03-29 16:24:22.589 11183 11246 I jxcore-log:     expected: false
03-29 16:24:22.589 11183 11246 I jxcore-log: 
03-29 16:24:22.589 11183 11246 I jxcore-log:     actual:   true
03-29 16:24:22.589 11183 11246 I jxcore-log: 
,03-29 16:24:22.589 11183 11246 I jxcore-log:   ...
03-29 16:24:22.589 11183 11246 I jxcore-log: 
,03-29 16:24:22.589 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-29 16:24:22.594 11183 11183 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-29 16:24:22.594 11183 11183 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-29 16:24:22.594 11183 11246 I jxcore-log: not ok 226 advertisingActive matches
03-29 16:24:22.594 11183 11246 I jxcore-log: 
03-29 16:24:22.594 11183 11246 I jxcore-log:   ---
03-29 16:24:22.594 11183 11246 I jxcore-log: 
03-29 16:24:22.594 11183 11246 I jxcore-log:     operator: equal
03-29 16:24:22.594 11183 11246 I jxcore-log: 
03-29 16:24:22.594 11183 11246 I jxcore-log:     expected: false
03-29 16:24:22.594 11183 11246 I jxcore-log: 
03-29 16:24:22.594 11183 11246 I jxcore-log:     actual:   true
03-29 16:24:22.594 11183 11246 I jxcore-log: 
,03-29 16:24:22.594 11183 11246 I jxcore-log:   ...
03-29 16:24:22.594 11183 11246 I jxcore-log: 
,03-29 16:24:22.594 11183 11183 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-29 16:24:22.594 11183 11183 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 16:24:22.594 11183 11183 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 16:24:22.594 11183 11183 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-29 16:24:22.594 11183 11183 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-29 16:24:22.594 11183 11183 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-29 16:24:22.599 11183 11246 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-29 16:24:22.599 11183 11246 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-29 16:24:22.599 11183 11246 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 16:24:22.599 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-29 16:24:22.599 11183 11246 I jxcore-log: 
,03-29 16:24:22.599 11183 11246 I jxcore-log: ok 227 discoveryActive matches
03-29 16:24:22.599 11183 11246 I jxcore-log: 
,03-29 16:24:22.604 11183 11246 I jxcore-log: not ok 228 advertisingActive matches
03-29 16:24:22.604 11183 11246 I jxcore-log: 
,03-29 16:24:22.604 11183 11246 I jxcore-log:   ---
03-29 16:24:22.604 11183 11246 I jxcore-log: 
03-29 16:24:22.604 11183 11246 I jxcore-log:     operator: equal
03-29 16:24:22.604 11183 11246 I jxcore-log: 
03-29 16:24:22.604 11183 11246 I jxcore-log:     expected: false
03-29 16:24:22.604 11183 11246 I jxcore-log: 
03-29 16:24:22.604 11183 11246 I jxcore-log:     actual:   true
03-29 16:24:22.604 11183 11246 I jxcore-log: 
03-29 16:24:22.604 11183 11246 I jxcore-log:   ...
03-29 16:24:22.604 11183 11246 I jxcore-log: 
,03-29 16:24:22.609 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 16:24:22.609 11183 11246 I jxcore-log: 
,03-29 16:24:22.609 11183 11246 I jxcore-log: ok 229 discoveryActive matches
03-29 16:24:22.609 11183 11246 I jxcore-log: 
,03-29 16:24:22.609 11183 11246 I jxcore-log: ok 230 advertisingActive matches
03-29 16:24:22.609 11183 11246 I jxcore-log: 
,03-29 16:24:22.614 11183 11246 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 16:24:22.614 11183 11246 I jxcore-log: 
,03-29 16:24:22.624 11183 11246 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 16:24:22.624 11183 11246 I jxcore-log: 
,03-29 16:24:22.629 11183 11246 I jxcore-log: DEBUG createNativeListener: listening 48600
03-29 16:24:22.629 11183 11246 I jxcore-log: 
,03-29 16:24:22.639 11183 11246 I jxcore-log: Uncaught Promise Rejection: {}
03-29 16:24:22.639 11183 11246 I jxcore-log: 
,03-29 16:24:22.649 11183 11246 E jxcore-log: Trace: [Error: Call Stop!]
03-29 16:24:22.649 11183 11246 E jxcore-log:     at $3.prototype.trace@console.js:139:8
03-29 16:24:22.649 11183 11246 E jxcore-log:     at @/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:38:3
03-29 16:24:22.649 11183 11246 E jxcore-log:     at emit@events.js:98:1
03-29 16:24:22.649 11183 11246 E jxcore-log:     at handlers.reject/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/thali/node_modules/lie/lib/index.js:128:11
03-29 16:24:22.649 11183 11246 E jxcore-log:     at nextTick@/data/data/com.test.thalitest/files/www/jxcore/node_modules/immediate/lib/index.js:61:7
03-29 16:24:22.649 11183 11246 E jxcore-log:     at $0a@node.js:917:1
03-29 16:24:22.649 11183 11246 E jxcore-log: 
,03-29 16:24:22.649 11183 11246 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
03-29 16:24:22.649 11183 11246 I jxcore-log: 
,03-29 16:24:22.654 11183 11246 I jxcore-log: # teardown
03-29 16:24:22.654 11183 11246 I jxcore-log: 
,03-29 16:24:23.064 12310 12310 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,03-29 16:24:23.069 12310 12310 D AndroidRuntime: CheckJNI is OFF
,03-29 16:24:23.069 12310 12310 D AndroidRuntime: readGMSProperty: start
03-29 16:24:23.069 12310 12310 D AndroidRuntime: readGMSProperty: already setted!!
03-29 16:24:23.069 12310 12310 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-29 16:24:23.069 12310 12310 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-29 16:24:23.069 12310 12310 D AndroidRuntime: readGMSProperty: end
03-29 16:24:23.069 12310 12310 D AndroidRuntime: addProductProperty: start
,03-29 16:24:23.164 12310 12310 E AffinityControl: AffinityControl: registerfunction enter
,03-29 16:24:23.184 12310 12310 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,03-29 16:24:23.194  3452  3491 D PackageManager: START PACKAGE DELETE: observer{916827675}
03-29 16:24:23.194  3452  3491 D PackageManager: pkg{<packageName>}
03-29 16:24:23.194  3452  3491 D PackageManager: user{0}
03-29 16:24:23.194  3452  3491 D PackageManager: caller{2000}
03-29 16:24:23.194  3452  3491 D PackageManager: flags{2}
03-29 16:24:23.194  3452  3491 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
03-29 16:24:23.194  3452  3491 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
03-29 16:24:23.194  3452  3491 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
03-29 16:24:23.194  3452  3491 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
03-29 16:24:23.194  3452  3491 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
03-29 16:24:23.199  3452  3591 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
03-29 16:24:23.199  3452  3591 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
03-29 16:24:23.199  3452  3591 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
03-29 16:24:23.199  3452  3591 D ApplicationPolicy: getApplicationUninstallationEnabled
03-29 16:24:23.199  3452  3591 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,03-29 16:24:23.199  3452  3591 D PackageManager: !@killApplicatoin: 10011, uninstall pkg
,03-29 16:24:23.204  3452  3572 I ActivityManager: Force stopping com.test.thalitest appid=10011 user=-1: uninstall pkg
,03-29 16:24:23.204  3452  3572 I ActivityManager: Killing 11183:com.test.thalitest/u0a11 (adj 0): stop com.test.thalitest cause uninstall pkg
,03-29 16:24:23.214  3452  3572 I ActivityManager:   Force finishing activity 3 ActivityRecord{b51f6bb u0 com.test.thalitest/.MainActivity t42},
,03-29 16:24:23.219  3452  3572 W ActivityManager: mDVFSHelper.acquire()
,03-29 16:24:23.319  3452  3591 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
,03-29 16:24:23.319  3452  3591 W PackageSettings: Skipping PackageSetting{38bb2b5a com.example.hello/10691} due to missing metadata
,03-29 16:24:23.339  3452  3591 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,03-29 16:24:23.339  3452  3572 D PowerManagerService: setKeyboardVisibility: false
03-29 16:24:23.339  3452  3572 I ActivityManager: Skip updateThumbnail for r=ActivityRecord{2ec579bf u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t40}
,03-29 16:24:23.349  3452  4010 I WindowState: WIN DEATH: Window{729b211 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}
,03-29 16:24:23.349  2859  3006 I SurfaceFlinger: id=15 Removed NainActivit (6/8)
03-29 16:24:23.349  2859 10889 I SurfaceFlinger: id=15 Removed NainActivit (-2/8)
,03-29 16:24:23.349  3452  4010 D InputDispatcher: Focus left window: 11183
,03-29 16:24:23.354  3452  4010 D MultiWindowConverter: dismissGuide() : Before attaching the guide view, mForceDismissGuide : false
,03-29 16:24:23.364  3452  3583 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3452 uid:1000
03-29 16:24:23.364  3452  3583 D PointerIcon: setMouseCustomIcon IconType is same.101
03-29 16:24:23.364  3452  3583 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3452 uid:1000
03-29 16:24:23.364  3452  3583 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,03-29 16:24:23.364  3452  3591 I ActivityManager: Force stopping com.test.thalitest appid=10011 user=0: pkg removed
,03-29 16:24:23.369  3452  3591 I ActivityManager:   Force finishing activity 3 ActivityRecord{b51f6bb u0 com.test.thalitest/.MainActivity t42 f}
03-29 16:24:23.369  3452  3591 W ActivityManager: Duplicate finish request for ActivityRecord{b51f6bb u0 com.test.thalitest/.MainActivity t42 f}
,03-29 16:24:23.404  9087  9087 I art     : Explicit concurrent mark sweep GC freed 2670(151KB) AllocSpace objects, 0(0B) LOS objects, 69% free, 1770KB/5MB, paused 664us total 20.680ms
,03-29 16:24:23.409  3939  3939 I art     : Explicit concurrent mark sweep GC freed 1664(87KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 487us total 18.756ms
,03-29 16:24:23.414  3452  3591 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,03-29 16:24:23.424  6467  6467 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(433/onResume)] 
,03-29 16:24:23.424  3452  3692 D TaskPersister: removeObsoleteFile: deleting file=42_task.xml
03-29 16:24:23.424  3452  3692 D TaskPersister: removeObsoleteFile: deleting file=42_task_thumbnail.png
03-29 16:24:23.429  3452  3572 D InputDispatcher: Focused application released
03-29 16:24:23.434  4113  4113 I art     : Explicit concurrent mark sweep GC freed 18176(1117KB) AllocSpace objects, 1(16KB) LOS objects, 25% free, 6MB/8MB, paused 992us total 58.359ms
,03-29 16:24:23.434  4681  4681 I art     : Explicit concurrent mark sweep GC freed 3007(186KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 8MB/11MB, paused 1.122ms total 60.148ms
,03-29 16:24:23.439  6467  6467 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5412/IlIlllIlllllIlIllllI)] Get Postpone Count : 0
,03-29 16:24:23.454  6467  6467 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5134/lIIIIIIIlllllllIIlll)] Get Priority : 0
,03-29 16:24:23.469  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.PACKAGE_REMOVED
,03-29 16:24:23.469  6467  6467 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5434/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,03-29 16:24:23.469  6467  6467 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(443/onResume)] Postpone Count : 0
,03-29 16:24:23.474  4529  4529 E SamsungIME: mOCRHelper is null
,03-29 16:24:23.479  3452  3632 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-29 16:24:23.479  4462  4795 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,03-29 16:24:23.479  6467  6467 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5475/llIlIIIIlllIlllllIll)] Download Postpone status : 0
03-29 16:24:23.479  4011  4011 I art     : Explicit concurrent mark sweep GC freed 16043(921KB) AllocSpace objects, 9(1362KB) LOS objects, 12% free, 56MB/64MB, paused 521us total 70.099ms
,03-29 16:24:23.484 10686 10686 D LWLocationManager: getDeviceLocationId :  id = -100
,03-29 16:24:23.484 10686 10686 D LocationWidgetApplication: getLastUiLocationId() : mLastUiLocationId = -100
,03-29 16:24:23.494  3452  3653 V NetworkStats: removeUidsLocked() for UIDs [10011]
03-29 16:24:23.494  3452  3653 D NtpTrustedTime: currentTimeMillis() cache hit
03-29 16:24:23.494  3452  3653 V NetworkStats: performPollLocked(flags=0x3)
,03-29 16:24:23.494  3452  3571 D EnterpriseDeviceManagerService: Package has changed for user 0
03-29 16:24:23.494  3452  3571 W TextServicesManagerService: no available spell checker services found
03-29 16:24:23.494  3452  3571 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,03-29 16:24:23.499  3452  3572 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-29 16:24:23.499  3452  3572 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-29 16:24:23.499  3452  3572 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-29 16:24:23.499  3452  3572 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-29 16:24:23.519 12329 12329 E Zygote  : MountEmulatedStorage()
03-29 16:24:23.519 12329 12329 E Zygote  : v2
03-29 16:24:23.519 12329 12329 I libpersona: KNOX_SDCARD checking this for 10063
03-29 16:24:23.519 12329 12329 I libpersona: KNOX_SDCARD not a persona
03-29 16:24:23.519  5574  5592 W ResourceType: For resource 0x7f020570, entry index(1392) is beyond type entryCount(787)
03-29 16:24:23.519  5574  5592 W ResourceType: Failure getting entry for 0x7f020570 (t=1 e=1392) (error -75)
,03-29 16:24:23.519 12329 12329 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
,03-29 16:24:23.524 12329 12329 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
,03-29 16:24:23.524  3452  3572 I ActivityManager: Start proc 12329:com.samsung.android.app.vrsetupwizardstub/u0a63 for broadcast-3 com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver
03-29 16:24:23.524 12329 12329 E Zygote  : accessInfo : 0
,03-29 16:24:23.524  6467  6467 I DBG_DM  : [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,03-29 16:24:23.529 12329 12329 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-29 16:24:23.529  6467  6467 I DBG_DM  : [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(327/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,03-29 16:24:23.529  3452  3653 V NetworkStats: performPollLocked() took 35ms
,03-29 16:24:23.529  3452  3653 D NtpTrustedTime: currentTimeMillis() cache hit
,03-29 16:24:23.539  3977  3977 D RegisteredServicesCache: empty dynamic service
,03-29 16:24:23.549  3977  3977 D RegisteredComponentCache: Collect Tech packages for Knox
,03-29 16:24:23.549  6467  6467 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5134/lIIIIIIIlllllllIIlll)] Get Priority : 0
,03-29 16:24:23.569 12329 12329 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-29 16:24:23.569 12329 12329 D ActivityThread: Added TimaKeyStore provider
,03-29 16:24:23.574  3452  3599 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
03-29 16:24:23.574  3452  3599 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,03-29 16:24:23.579  3452  3452 I art     : Explicit concurrent mark sweep GC freed 48849(3MB) AllocSpace objects, 19(304KB) LOS objects, 33% free, 30MB/45MB, paused 7.286ms total 166.059ms
,03-29 16:24:23.579  3452  3591 I art     : WaitForGcToComplete blocked for 155.058ms for cause Explicit
03-29 16:24:23.579  6467  6467 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5412/IlIlllIlllllIlIllllI)] Get Postpone Count : 0
,03-29 16:24:23.584  3452  4028 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{33cb02fc u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{33413d85 12329:com.samsung.android.app.vrsetupwizardstub/u0a63}
,03-29 16:24:23.584  6467  6467 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5054/IIlllIlIIlIllIlllIll)] Get Force status : 0
,03-29 16:24:23.599  6467  6467 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5434/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,03-29 16:24:23.599  6467  6467 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(537/llIIIIlllllIIllIIllI)] Check Force Install : false
,03-29 16:24:23.599  6467  6467 I DBG_DM  : [llIIlIIlIllIllIlllII(337/IllIlIIIIlIIlIIIllIl)] 
,03-29 16:24:23.604  6467  6467 I DBG_DM  : [llIIlIIlIllIllIlllII(343/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
,03-29 16:24:23.604  3452  3651 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-29 16:24:23.604  3452  3651 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-29 16:24:23.604  3452  3651 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,03-29 16:24:23.604  3452  3654 D NtpTrustedTime: currentTimeMillis() cache hit
03-29 16:24:23.604  3452  3654 D NtpTrustedTime: currentTimeMillis() cache hit
,03-29 16:24:23.609  2859  2859 I SurfaceFlinger: id=16 createSurf (1440x2560),1 flag=404, YUIInstallC
,03-29 16:24:23.609  3452  3998 D MultiWindowConverter: dismissGuide() : Before attaching the guide view, mForceDismissGuide : false
03-29 16:24:23.609  3452  3581 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{bab2242 u0 d0 com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}
,03-29 16:24:23.609  3452  3998 D InputDispatcher: Focus entered window: 6467
,03-29 16:24:23.614  3452  3583 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3452 uid:1000
03-29 16:24:23.614  3452  3583 D PointerIcon: setMouseCustomIcon IconType is same.101
03-29 16:24:23.614  3452  3583 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3452 uid:1000
03-29 16:24:23.614  3452  3583 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,03-29 16:24:23.614  6467  6467 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-29 16:24:23.614  6467  9191 D mali_winsys: new_window_surface returns 0x3000,  [1440x2560]-format:1
,03-29 16:24:23.614  6467  6467 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(425/onPause)] 
,03-29 16:24:23.619 12329 12329 D VRSetupWizardStub/PackageIntentReceiver: onReceive(),
03-29 16:24:23.619 12329 12329 D VRSetupWizardStub/PackageIntentReceiver: Action Package Remove
03-29 16:24:23.619 12329 12329 D VRSetupWizardStub/PackageIntentReceiver: packagename:com.test.thalitest
03-29 16:24:23.619  3452  4010 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-29 16:24:23.624  3452  4028 D SecContentProvider2: query(), uri = 11 selection = getMyKnoxAdmin
03-29 16:24:23.624  3452  4010 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 11183 uid 10011
,03-29 16:24:23.629  3452  3651 I ActivityManager: Killing 10132:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): emptyCount ##31
,03-29 16:24:23.634  4529  4529 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,03-29 16:24:23.634  3452  3651 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{33cb02fc u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{3fe445df 7080:com.samsung.klmsagent/u0a21}
,03-29 16:24:23.634  7080  7080 I KLMS-2.5.262: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Mar 29 16:24:23 GMT+02:00 2016
,03-29 16:24:23.639  3452  3599 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,03-29 16:24:23.644  7080  7080 I KLMS-2.5.262: : KLMSAbstractReciever(): onReceive().END.
,03-29 16:24:23.649  3452  3994 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=14, mSplitNum[1]=26, mSplitNum[2]=38, mBgSplitQueueNum=3 divideNum= 12 r.nextReceiver= 2 receivers.size=50
03-29 16:24:23.649  3452  3994 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
03-29 16:24:23.649  7080  7080 I KLMS-2.5.262: : KLMSIntentService(): onCreate()
03-29 16:24:23.649  7080  7080 I KLMS-2.5.262: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,03-29 16:24:23.649  6467  6467 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1558a83b time:289329
03-29 16:24:23.649  6467  6467 V ActivityThread: updateVisibility : ActivityRecord{fb44e6d token=android.os.BinderProxy@1558a83b {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
03-29 16:24:23.649  7080  7080 I KLMS-2.5.262: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
03-29 16:24:23.654  7080 12347 I KLMS-2.5.262: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.service.KLMSIntentService (has extras) }
03-29 16:24:23.654  7080 12347 D KLMS-2.5.262: : KLMSIntentService(): PACKAGE_REMOVED
03-29 16:24:23.654  7080 12347 I KLMS-2.5.262: : Systemprocess(): listeningToPackageRemoved().START
03-29 16:24:23.654  7080 12347 I KLMS-2.5.262: : Systemprocess(): listeningToPackageRemoved().packageName: com.test.thalitest
03-29 16:24:23.654  7080 12347 I KLMS-2.5.262: : listeningToPackageRemovedforELM().START
03-29 16:24:23.654  7080 12347 I KLMS-2.5.262: : MDMBridge.getInstance()
03-29 16:24:23.654  7080 12347 I KLMS-2.5.262: : MDMBridge.getAllLicenseInfoFromSDK()
,03-29 16:24:23.654  3452  3571 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75),
03-29 16:24:23.659  3452  3994 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{33cb02fc u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{e3ed86b 6818:com.samsung.aasaservice/1000}
03-29 16:24:23.654  7080 12347 I KLMS-2.5.262: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
03-29 16:24:23.659  7080 12347 I KLMS-2.5.262: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,03-29 16:24:23.659  6818  6818 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
03-29 16:24:23.659  7080 12347 I KLMS-2.5.262: : MDMBridge.getAllLicenseInfoFromSDK()
,03-29 16:24:23.664  6818  6818 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,03-29 16:24:23.664  6818  6818 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:334)
03-29 16:24:23.664  6818  6818 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
03-29 16:24:23.664  6818  6818 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3509)
03-29 16:24:23.664  6818  6818 W System.err: 	at android.app.ActivityThread.access$1900(ActivityThread.java:197)
03-29 16:24:23.664  6818  6818 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1758)
03-29 16:24:23.664  6818  6818 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-29 16:24:23.664  6818  6818 W System.err: 	at android.os.Looper.loop(Looper.java:145)
03-29 16:24:23.664  6818  6818 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6872)
03-29 16:24:23.664  6818  6818 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
03-29 16:24:23.664  6818  6818 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-29 16:24:23.664  6818  6818 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
03-29 16:24:23.664  6818  6818 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
,03-29 16:24:23.664  7080 12347 E KLMS-2.5.262: : arr si null
,03-29 16:24:23.669  7080 12347 D KLMS-2.5.262: : DataSource(): Fetched Data from data base count : 0
,03-29 16:24:23.669  7080 12347 I KLMS-2.5.262: : listeningToPackageRemovedforELM().END
03-29 16:24:23.669  7080 12347 I KLMS-2.5.262: : Systemprocess(): listeningToPackageRemovedforKLM().START
03-29 16:24:23.669  7080 12347 I KLMS-2.5.262: : Systemprocess(): .pkgName: com.test.thalitest
,03-29 16:24:23.674  3452  3572 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-29 16:24:23.674  3452  3572 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-29 16:24:23.674  3452  3572 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-29 16:24:23.674  3452  3572 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-29 16:24:23.694  3452  3591 I art     : Explicit concurrent mark sweep GC freed 10128(802KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 29MB/44MB, paused 1.916ms total 115.439ms
,03-29 16:24:23.704 12349 12349 E Zygote  : MountEmulatedStorage()
,03-29 16:24:23.704 12349 12349 I libpersona: KNOX_SDCARD checking this for 10042
03-29 16:24:23.704 12349 12349 E Zygote  : v2
03-29 16:24:23.704 12349 12349 I libpersona: KNOX_SDCARD not a persona
03-29 16:24:23.704 12349 12349 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
,03-29 16:24:23.709 12349 12349 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038,
,03-29 16:24:23.709 12349 12349 E Zygote  : accessInfo : 0
03-29 16:24:23.709  3452  3572 I ActivityManager: Start proc 12349:com.samsung.android.sdk.samsunglink/u0a42 for broadcast-4 com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver
03-29 16:24:23.709 12349 12349 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
03-29 16:24:23.709  3452  3583 W ActivityManager: mDVFSHelper.release()
,03-29 16:24:23.709  3452  3583 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2ec579bf u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t40} time:289388,
,03-29 16:24:23.714  3452  3572 E ActivityManager: checkUser: useridlist=null, currentuser=0,
03-29 16:24:23.714  3452  3572 E ActivityManager: checkUser: useridlist=null, currentuser=0,
03-29 16:24:23.714  3452  3572 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-29 16:24:23.714  3452  3572 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-29 16:24:23.729 12364 12364 E Zygote  : MountEmulatedStorage()
03-29 16:24:23.729 12364 12364 I libpersona: KNOX_SDCARD checking this for 1000
03-29 16:24:23.729 12364 12364 E Zygote  : v2
03-29 16:24:23.729 12364 12364 I libpersona: KNOX_SDCARD not a persona
,03-29 16:24:23.729 12364 12364 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
,03-29 16:24:23.729 12364 12364 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
,03-29 16:24:23.729 12364 12364 E Zygote  : accessInfo : 0
03-29 16:24:23.729  3452  3572 I ActivityManager: Start proc 12364:com.samsung.android.sm/1000 for broadcast-4 com.samsung.android.sm/.ui.security.MonitorReceiver
03-29 16:24:23.734 12364 12364 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-29 16:24:23.739  3452  3572 E ActivityManager: checkUser: useridlist=null, currentuser=0,
03-29 16:24:23.739  3452  3572 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-29 16:24:23.739  3452  3572 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-29 16:24:23.739  3452  3572 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-29 16:24:23.744 12349 12349 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-29 16:24:23.744 12349 12349 D ActivityThread: Added TimaKeyStore provider
,03-29 16:24:23.744  7080 12347 D KLMS-2.5.262: : KLMSUtility(): IsPackageExistInDevice().mAppInfoList: 322
,03-29 16:24:23.744  7080 12347 D KLMS-2.5.262: : KLMSSharedPreferences(): deleteNotificationAppList().pkgName: com.test.thalitest
03-29 16:24:23.744  7080 12347 I KLMS-2.5.262: : KLMSSharedPreferences(): getNotificationAppList(): null
03-29 16:24:23.744  7080 12347 I KLMS-2.5.262: : Systemprocess(): Notification App List is Null. Remove Notification.
,03-29 16:24:23.749 12379 12379 E Zygote  : MountEmulatedStorage()
,03-29 16:24:23.749 12379 12379 I libpersona: KNOX_SDCARD checking this for 1000
03-29 16:24:23.749 12379 12379 E Zygote  : v2
03-29 16:24:23.749 12379 12379 I libpersona: KNOX_SDCARD not a persona
03-29 16:24:23.749 12379 12379 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
03-29 16:24:23.749 12364 12364 D TimaKeyStoreProvider: TimaSignature is unavailable
03-29 16:24:23.749 12364 12364 D ActivityThread: Added TimaKeyStore provider
,03-29 16:24:23.749 12379 12379 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038,
03-29 16:24:23.754 12379 12379 E Zygote  : accessInfo : 0
03-29 16:24:23.754 12379 12379 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-29 16:24:23.754  7080 12347 D KLMS-2.5.262: : DataSource(): Fetched Data from data base count : 0
,03-29 16:24:23.754  7080 12347 I KLMS-2.5.262: : Systemprocess(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
03-29 16:24:23.754  7080 12347 I KLMS-2.5.262: : Systemprocess(): listeningToPackageRemovedforKLM().END
03-29 16:24:23.754  7080 12347 I KLMS-2.5.262: : Systemprocess(): listeningToPackageRemoved().END
,03-29 16:24:23.754  3452  3572 I ActivityManager: Start proc 12379:com.sec.android.app.popupuireceiver/1000 for broadcast-4 com.sec.android.app.popupuireceiver/.PopupuiReceiver
,03-29 16:24:23.759  7080  7080 I KLMS-2.5.262: : KLMSIntentService(): onDestroy()
,03-29 16:24:23.764 12379 12379 D TimaKeyStoreProvider: TimaSignature is unavailable
03-29 16:24:23.764  2900  2900 I art     : Explicit concurrent mark sweep GC freed 8747(372KB) AllocSpace objects, 0(0B) LOS objects, 72% free, 1529KB/5MB, paused 205us total 10.244ms
03-29 16:24:23.764  3452  3492 V BroadcastQueue: [backgroundsplit_0] Process cur broadcast BroadcastRecord{2f69ca2e u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{393949cf 12349:com.samsung.android.sdk.samsunglink/u0a42}
,03-29 16:24:23.769 12379 12379 D ActivityThread: Added TimaKeyStore provider
,03-29 16:24:23.769 10686 12335 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-29 16:24:23.774  2900  2900 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 72% free, 1529KB/5MB, paused 212us total 6.515ms
,03-29 16:24:23.774  3452  3599 V BroadcastQueue: [backgroundsplit_1] Process cur broadcast BroadcastRecord{36fbaf5c u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{15bfe265 12364:com.samsung.android.sm/1000}
,03-29 16:24:23.774 12349 12349 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-29 16:24:23.774 12349 12349 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,03-29 16:24:23.779  2900  2900 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 72% free, 1529KB/5MB, paused 440us total 6.782ms
,03-29 16:24:23.784  3452  3591 D PackageManager: Resopt: Clean up res: /data/app/com.test.thalitest-1/base.apk
03-29 16:24:23.784  3452  3591 D PackageManager: delete codoeFile: 
,03-29 16:24:23.789  3452  3914 V BroadcastQueue: [backgroundsplit_2] Process cur broadcast BroadcastRecord{38cc5b3a u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{3baab3eb 12379:com.sec.android.app.popupuireceiver/1000}
,03-29 16:24:23.789 12364 12364 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-29 16:24:23.789  3452  3591 D AASAuninstall: userId = 0, info.removedAppID = 10011, info.uid = 10011, packageName = com.test.thalitest
,03-29 16:24:23.794  3452  3591 I AASA_removePackage: UID=10011 Target=com.test.thalitest
,03-29 16:24:23.794  3452  3591 D PackageManager: result of delete: 1{916827675}
,03-29 16:24:23.794  3452  3994 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{33cb02fc u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{72746e5 3452:system/1000}
,03-29 16:24:23.804 12379 12379 D PopupuiReceiver: onReceive() getAction : android.intent.action.PACKAGE_REMOVED
,03-29 16:24:23.804 12310 12310 I art     : System.exit called, status: 0
03-29 16:24:23.804 12310 12310 I AndroidRuntime: VM exiting with result code 0.
,03-29 16:24:23.809  3452  3994 D SecContentProvider2: query(), uri = -1 selection = getSealedState
,03-29 16:24:23.809  3452  3591 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
03-29 16:24:23.809  3452  3591 D PackageManager: userId{-1}
03-29 16:24:23.809  3452  3591 D PackageManager: andCode{true}
,03-29 16:24:23.809  3452  3651 D SecContentProvider2: query(), uri = 15 selection = getSealedHideNotificationMessages
,03-29 16:24:23.814 12379 12379 I PopupuiReceiver_KNOX: getSealedHideNotificationMessages : 0
,03-29 16:24:23.814  3452  3599 D SecContentProvider2: query(), uri = 15 selection = getCheckCoverPopupState
,03-29 16:24:23.819 12379 12379 I PopupuiReceiver_KNOX: getCheckCoverPopupState : false
03-29 16:24:23.819 12379 12379 D PopupuiReceiver: Action package removed
,03-29 16:24:23.824  3452  3571 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-29 16:24:23.824  3452  3571 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-29 16:24:23.824  3452  3571 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-29 16:24:23.824  3452  3571 W ResourcesManager: Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,03-29 16:24:23.824  9645 12395 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.test.thalitest
,03-29 16:24:23.829  9645 12395 W System.err: remove failed: EACCES (Permission denied) : /storage/extSdCard/Android/data/com.test.thalitest
,03-29 16:24:23.829  9645 12395 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.test.thalitest
03-29 16:24:23.829  9645 12395 W System.err: remove failed: EACCES (Permission denied) : /storage/extSdCard/Android/media/com.test.thalitest
,03-29 16:24:23.829  9645 12395 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/obb/com.test.thalitest
03-29 16:24:23.829  9645 12395 W System.err: remove failed: EACCES (Permission denied) : /storage/extSdCard/Android/obb/com.test.thalitest
,03-29 16:24:23.829 10686 12335 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-29 16:24:23.829 10686 12335 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-29 16:24:23.829 10686 12335 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-29 16:24:23.829 10686 12335 W ResourcesManager: Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,03-29 16:24:23.829  3452  3836 V BroadcastQueue: [backgroundsplit_2] Process cur broadcast BroadcastRecord{38cc5b3a u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{129d50f2 10622:com.samsung.android.snote/u0a160}
,03-29 16:24:23.839  3452  3836 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-29 16:24:23.839  3452  3836 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-29 16:24:23.839  3452  3836 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-29 16:24:23.839  3452  3836 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-29 16:24:23.849 12397 12397 E Zygote  : MountEmulatedStorage()
03-29 16:24:23.849 12397 12397 E Zygote  : v2
03-29 16:24:23.849 12397 12397 I libpersona: KNOX_SDCARD checking this for 10183
03-29 16:24:23.849 12397 12397 I libpersona: KNOX_SDCARD not a persona
,03-29 16:24:23.854 12397 12397 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
,03-29 16:24:23.854  3452  3836 I ActivityManager: Start proc 12397:com.samsung.android.provider.shootingmodeprovider/u0a183 for broadcast-4 com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver
,03-29 16:24:23.859 12397 12397 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
,03-29 16:24:23.859 12397 12397 E Zygote  : accessInfo : 0
,03-29 16:24:23.864 12397 12397 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-29 16:24:23.864  3452  3836 I ActivityManager: Killing 10056:com.google.android.apps.docs/u0a101 (adj 15): emptyCount ##31
,03-29 16:24:23.869 12349 12349 I SL_DEBUG: isLoggable:: isProductShip = 1
,03-29 16:24:23.869 12349 12349 I SL_DEBUG: isLoggable:: SL_DEBUG_EXIST = false
,03-29 16:24:23.874 12364 12364 I art     : Explicit concurrent mark sweep GC freed 9203(426KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 1733KB/3MB, paused 242us total 25.004ms
,03-29 16:24:23.879  3452  3452 D RCPManagerService: PackageReceiver onReceive()
03-29 16:24:23.879  3452  3452 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,03-29 16:24:23.884  3452  3452 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
03-29 16:24:23.884  3452  3452 I OTPFW   : PackageRemovalReceiver::onReceive Enter
03-29 16:24:23.884  3452  3452 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10011 container id = 0
,03-29 16:24:23.889  3452  3571 D UsbSettingsManager: clearDefaults: com.test.thalitest
03-29 16:24:23.889  3452  3571 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,03-29 16:24:23.894  4011  4011 E Launcher.Model: onPackageRemoved :com.test.thalitest
,03-29 16:24:23.894  3452  3452 I OTPFW   : ProvisionData::getAllEntries Enter
,03-29 16:24:23.894 12397 12397 D TimaKeyStoreProvider: TimaSignature is unavailable
03-29 16:24:23.899  3452  3452 E OTPFW   : ProvisionData::getAllEntries Table is empty
03-29 16:24:23.899 12397 12397 D ActivityThread: Added TimaKeyStore provider
,03-29 16:24:23.899  3452  3994 V BroadcastQueue: [backgroundsplit_1] Process cur broadcast BroadcastRecord{36fbaf5c u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{15bfe265 12364:com.samsung.android.sm/1000}
,03-29 16:24:23.904  3452  3994 V BroadcastQueue: [backgroundsplit_1] Process cur broadcast BroadcastRecord{36fbaf5c u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{15bfe265 12364:com.samsung.android.sm/1000}
,03-29 16:24:23.909  3452  3452 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
03-29 16:24:23.909  3452  3452 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,03-29 16:24:23.914  3452  3492 V BroadcastQueue: [backgroundsplit_2] Process cur broadcast BroadcastRecord{38cc5b3a u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{498d350 12397:com.samsung.android.provider.shootingmodeprovider/u0a183}
,03-29 16:24:23.914  3452  3452 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
03-29 16:24:23.914  3452  3452 V EnterpriseBillingPolicy: uID is 10011
03-29 16:24:23.914  3452  3452 V EnterpriseBillingPolicy: Removed Packageuid is0
03-29 16:24:23.914  3452  3452 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,03-29 16:24:23.914  3452  3452 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
03-29 16:24:23.914  3452  3452 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
03-29 16:24:23.914  3452  3452 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
03-29 16:24:23.914  3452  3452 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
03-29 16:24:23.914  3452  3452 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,03-29 16:24:23.914  3452  3452 D SdpManagerService:  ActionReceiver::onReceive() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
03-29 16:24:23.919  3452  3452 D SdpManagerService: ACTION_PACKAGE_REMOVED Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) } DATA= package:com.test.thalitest UID 1000 userId 0
03-29 16:24:23.919  3452  3452 D SdpManagerService: ACTION_PACKAGE_REMOVED packageName:: com.test.thalitest
,03-29 16:24:23.919  3452  3994 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-29 16:24:23.919  3452  3994 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-29 16:24:23.919  3452  3994 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-29 16:24:23.919  3452  3994 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-29 16:24:23.924 12364 12417 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
,03-29 16:24:23.929  3452  3452 D EnterprisePartitionManager: SND -> {secure_fs remove_enc_dir}
,03-29 16:24:23.929  3452  3593 D EnterprisePartitionManager: RCV <-
03-29 16:24:23.929  3452  3452 D EnterprisePartitionManager: RMV <-
,03-29 16:24:23.934 12420 12420 E Zygote  : MountEmulatedStorage()
03-29 16:24:23.934 12420 12420 I libpersona: KNOX_SDCARD checking this for 1000
03-29 16:24:23.934 12420 12420 E Zygote  : v2
03-29 16:24:23.934 12420 12420 I libpersona: KNOX_SDCARD not a persona
03-29 16:24:23.939 12420 12420 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
03-29 16:24:23.939  3452  3452 E EnterprisePartitionManager: Failed to send commandcom.sec.knox.container.util.DaemonConnector$DaemonArgumentException: command 'secure_fs' failed with '500 3 Command not recognized'
03-29 16:24:23.939  3452  3452 W System.err: java.io.FileNotFoundException: /data/system/users/sdp_engine_list.xml: open failed: ENOENT (No such file or directory)
03-29 16:24:23.939 12420 12420 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
03-29 16:24:23.939  3452  3452 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-29 16:24:23.939  3452  3452 W System.err: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
03-29 16:24:23.939  3452  3452 W System.err: 	at com.android.server.SdpManagerService$SdpEngineDatabase$EngineListHandler.getEngineListLocked(SdpManagerService.java:1514)
03-29 16:24:23.939  3452  3452 W System.err: 	at com.android.server.SdpManagerService$SdpEngineDatabase$EngineListHandler.access$1100(SdpManagerService.java:1434)
03-29 16:24:23.939  3452  3452 W System.err: 	at com.android.server.SdpManagerService$SdpEngineDatabase.getEngineListLocked(SdpManagerService.java:1418)
03-29 16:24:23.939  3452  3452 W System.err: 	at com.android.server.SdpManagerService$SdpEngineDatabase.access$2200(SdpManagerService.java:1393)
03-29 16:24:23.939  3452  3452 W System.err: 	at com.android.server.SdpManagerService.handlePkgRemoved(SdpManagerService.java:2647)
03-29 16:24:23.939  3452  3452 W System.err: 	at com.android.server.SdpManagerService.access$2500(SdpManagerService.java:137)
03-29 16:24:23.939  3452  3452 W System.err: 	at com.android.server.SdpManagerService$ActionReceiver.onReceive(SdpManagerService.java:2719)
03-29 16:24:23.939  3452  3452 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:972)
03-29 16:24:23.939  3452  3452 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
03-29 16:24:23.939  3452  3452 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-29 16:24:23.939  3452  3452 W System.err: 	at android.os.Looper.loop(Looper.java:145)
03-29 16:24:23.939  3452  3452 W System.err: 	at com.android.server.SystemServer.run(SystemServer.java:469)
03-29 16:24:23.939  3452  3452 W System.err: 	at com.android.server.SystemServer.main(SystemServer.java:353)
03-29 16:24:23.939  3452  3452 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
03-29 16:24:23.939  3452  3452 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-29 16:24:23.939  3452  3452 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
03-29 16:24:23.939  3452  3452 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
03-29 16:24:23.939  3452  3452 W System.err: Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
03-29 16:24:23.944  3452  3452 W System.err: 	at libcore.io.Posix.open(Native Method)
03-29 16:24:23.944  3452  3452 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-29 16:24:23.944  3452  3452 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-29 16:24:23.944  3452  3452 W System.err: 	... 18 more
03-29 16:24:23.944  3452  3452 E SdpManagerService: failed to get engine list
03-29 16:24:23.944 12420 12420 E Zygote  : accessInfo : 0
03-29 16:24:23.944 12420 12420 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-29 16:24:23.944  3452  3452 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.i,ntent.action.PACKAGE_FULLY_REMOVED
03-29 16:24:23.944  3452  3452 V EnterpriseBillingPolicy: uID is 10011
03-29 16:24:23.944  3452  3452 V EnterpriseBillingPolicy: Removed Packageuid is0
03-29 16:24:23.944  3452  3452 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
03-29 16:24:23.944  3452  3452 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
03-29 16:24:23.944  3452  3452 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
03-29 16:24:23.944  3452  3452 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
03-29 16:24:23.944  3452  3452 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
03-29 16:24:23.944  3452  3452 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
03-29 16:24:23.949  3452  3994 I ActivityManager: Start proc 12420:com.samsung.android.app.assistantmenu/1000 for broadcast-4 com.samsung.android.app.assistantmenu/.AssistantMenuReceiver
03-29 16:24:23.949  3452  6034 D SSRM:bd : MSG_TYPE_APP_REMOVED::
03-29 16:24:23.949  3452  3994 I ActivityManager: Killing 10300:com.sec.android.app.soundalive/u0a59 (adj 15): emptyCount ##31
,03-29 16:24:23.954 12397 12397 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
,03-29 16:24:23.969  3452  3452 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,03-29 16:24:23.969  3452  3452 E EnterpriseSharedDevicePolicy: isSharedDeviceEnabled
03-29 16:24:23.969  3452  4020 D ActivityManager: startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
,03-29 16:24:23.974  3452  3452 I EnterpriseSharedDevicePolicy: isSharedDeviceEnabled in Service
,03-29 16:24:23.974  3452  3452 I EnterpriseSharedDevicePolicy: Get Result: -1
03-29 16:24:23.974  3452  3452 D PersonaManagerService: getPersonasForUser(): returning null!
03-29 16:24:23.974  3452  3452 I EnterpriseSharedDevicePolicy: status: false
03-29 16:24:23.974  3452  3452 I KnoxTimeoutHandler: Shared devices show user statefalse
,03-29 16:24:23.979  3726  3726 D PanelView: There is/are notification(s) 
,03-29 16:24:23.979 10778 10789 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
03-29 16:24:23.979 10778 10789 D BadgeProvider: sendNotify, [notify] : null
03-29 16:24:23.979 10778 10789 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
03-29 16:24:23.979 10778 10789 D BadgeProvider: update, [uri.query] : null
03-29 16:24:23.979 10778 10789 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-29 16:24:23.979 10778 10789 D BadgeProvider: update, [UpdateCount] : 1
,03-29 16:24:23.984 12420 12420 D TimaKeyStoreProvider: TimaSignature is unavailable
03-29 16:24:23.984  3452  3452 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{33cb02fc u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{9a2e19f 6101:com.sec.android.service.health/u0a19}
03-29 16:24:23.984 12420 12420 D ActivityThread: Added TimaKeyStore provider
,03-29 16:24:23.984  6101  6101 D com.sec.android.service.health.upgrade.UninstallReceiver: onReceive()
,03-29 16:24:23.984  3452  3452 V AlarmManagerEXT: com.test.thalitest(10011) is removed.
,03-29 16:24:23.989  6101  6101 I com.sec.android.service.health.upgrade.UninstallReceiver: onReceive called  PACKAGE_REMOVED package:com.test.thalitest
03-29 16:24:23.989  6101  6101 D com.sec.android.service.health.upgrade.UninstallReceiver: onReceive() : package name is not s health. Return !!!
,03-29 16:24:23.989  3452  3491 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-29 16:24:23.989  3452  3491 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-29 16:24:23.989  3452  3491 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-29 16:24:23.989  3452  3491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-29 16:24:24.009 12436 12436 E Zygote  : MountEmulatedStorage()
03-29 16:24:24.009 12436 12436 E Zygote  : v2
03-29 16:24:24.009 12436 12436 I libpersona: KNOX_SDCARD checking this for 10190
03-29 16:24:24.009 12436 12436 I libpersona: KNOX_SDCARD not a persona
,03-29 16:24:24.014  3452  3491 I ActivityManager: Start proc 12436:com.sec.android.widgetapp.tapandpay/u0a190 for broadcast-4 com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider
,03-29 16:24:24.019 12436 12436 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
,03-29 16:24:24.024  3452  4020 V BroadcastQueue: [backgroundsplit_1] Process cur broadcast BroadcastRecord{36fbaf5c u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{3354d55a 12420:com.samsung.android.app.assistantmenu/1000}
,03-29 16:24:24.029 12436 12436 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
,03-29 16:24:24.029 12436 12436 E Zygote  : accessInfo : 0
03-29 16:24:24.029 12436 12436 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-29 16:24:24.039  3452  3491 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{33cb02fc u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{2de36f0 10686:com.sec.android.widgetapp.locationwidget/u0a22}
,03-29 16:24:24.044  3726  3726 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,03-29 16:24:24.049 10686 10686 D LocationWidgetApplication: getLastUiLocationId() : mLastUiLocationId = -100
03-29 16:24:24.049  3726  3726 D PanelView: There is/are notification(s) 
,03-29 16:24:24.049  3726  3726 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-29 16:24:24.054  3726  3726 D PanelView: There is/are notification(s) 
,03-29 16:24:24.054  3726  3726 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-29 16:24:24.059  3452  6065 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-29 16:24:24.064  3452  3491 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-29 16:24:24.064  3452  3491 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-29 16:24:24.064  3452  3491 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-29 16:24:24.064  3452  3491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-29 16:24:24.064 12436 12436 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-29 16:24:24.064 12436 12436 D ActivityThread: Added TimaKeyStore provider
,03-29 16:24:24.079  2857  3081 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
03-29 16:24:24.079  2857  3081 W Vold    : Returning OperationFailed - no handler for errno 0
,03-29 16:24:24.079 12452 12452 E Zygote  : MountEmulatedStorage()
03-29 16:24:24.079 12452 12452 E Zygote  : v2
03-29 16:24:24.079 12349 12349 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
,03-29 16:24:24.079 12452 12452 I libpersona: KNOX_SDCARD checking this for 1000
03-29 16:24:24.079 12452 12452 I libpersona: KNOX_SDCARD not a persona
,03-29 16:24:24.084 12364 12418 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
,03-29 16:24:24.084 12349 12349 D SecWifiDisplayUtil: Metadata value : none
03-29 16:24:24.084 12364 12418 E SQLiteLog: (6922) statement aborts at 21: [DELETE FROM usage_log WHERE strftime('%s','now', '-40 days')*1000 - start_time >= 0] disk I/O error
03-29 16:24:24.084 12452 12452 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
,03-29 16:24:24.084  3452  3491 I ActivityManager: Start proc 12452:com.sec.pcw.device/1000 for broadcast-3 com.sec.pcw.device/.receiver.SYSTEMReceiver
,03-29 16:24:24.089  3452  3491 I ActivityManager: Killing 10362:com.vlingo.midas/u0a34 (adj 15): emptyCount ##31
,03-29 16:24:24.094 12452 12452 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
03-29 16:24:24.094 12364 12418 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-29 16:24:24.094 12364 12418 E SQLiteLog: (6922) statement aborts at 17: [DELETE FROM running_service_log WHERE strftime('%s','now', '-40 days')*1000 - captured_time >= 0] disk I/O error
,03-29 16:24:24.099 12452 12452 E Zygote  : accessInfo : 0
,03-29 16:24:24.099 12452 12452 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-29 16:24:24.099  3452  3914 V BroadcastQueue: [backgroundsplit_2] Process cur broadcast BroadcastRecord{38cc5b3a u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{b7c3714 12436:com.sec.android.widgetapp.tapandpay/u0a190}
,03-29 16:24:24.099 12364 12418 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
,03-29 16:24:24.099 12364 12418 E SQLiteLog: (6922) statement aborts at 17: [DELETE FROM noti_info WHERE strftime('%s','now', '-40 days')*1000 - posted_date >= 0] disk I/O error
,03-29 16:24:24.104  3452  3604 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/2/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.0
03-29 16:24:24.104  3452  3604 D UsbHostManager: displayNotification : [02h,02h,01h]
,03-29 16:24:24.104  3452  3604 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.1
03-29 16:24:24.104  3452  3604 D UsbHostManager: displayNotification : [0ah,00h,00h]
,03-29 16:24:24.104  3452  3604 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/13/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.2
03-29 16:24:24.104  3452  3604 D UsbHostManager: displayNotification : [02h,0dh,00h]
,03-29 16:24:24.109  3452  3604 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.3
03-29 16:24:24.109  3452  3604 D UsbHostManager: displayNotification : [0ah,00h,01h]
,03-29 16:24:24.109 12420 12420 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2129 android.content.ContextWrapper.startService:534 android.content.ContextWrapper.startService:534 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3509 
,03-29 16:24:24.109  3452  4028 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
,03-29 16:24:24.114  3452  3604 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 1d6b/2/310, type = 9/0/0, interface = 9/0/0, devpath = /devices/15510000.usb/usb1/1-0:1.0
03-29 16:24:24.114  3452  3604 D UsbHostManager: displayNotification : [09h,00h,00h]
03-29 16:24:24.114 12364 12418 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-29 16:24:24.114  3452  3694 D UsbHostManager: usbDeviceRemoved : /dev/bus/usb/001/003
03-29 16:24:24.114  3452  3694 E UsbHostManager: usbDeviceRemoved :: deviceName = /dev/bus/usb/001/003
03-29 16:24:24.114  3452  3694 D UsbSettingsManager: usbDeviceRemoved, sending Intent { act=android.hardware.usb.action.USB_DEVICE_DETACHED (has extras) }
03-29 16:24:24.119 12364 12418 E SQLiteLog: (6922) statement aborts at 17: [DELETE FROM screen_state_log WHERE strftime('%s','now', '-40 days')*1000 - time >= 0] disk I/O error
,03-29 16:24:24.119 12364 12418 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-29 16:24:24.119 12364 12418 E SQLiteLog: (6922) statement aborts at 17: [DELETE FROM debug_log_info WHERE strftime('%s','now', '-20 days')*1000 - created_At >= 0] disk I/O error
,03-29 16:24:24.119 12364 12418 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-29 16:24:24.119 12364 12418 E SQLiteLog: (6922) statement aborts at 3: [DELETE FROM system_env_info] disk I/O error
03-29 16:24:24.119  3726  3726 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,03-29 16:24:24.119 12364 12418 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-29 16:24:24.119 12364 12418 E SQLiteLog: (6922) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
,03-29 16:24:24.124 12364 12418 E SQLiteDatabase: Error inserting name=this value=SmartManager LowpowerContextEngine
03-29 16:24:24.124 12364 12418 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 6922)
03-29 16:24:24.124 12364 12418 E SQLiteDatabase: #################################################################
03-29 16:24:24.124 12364 12418 E SQLiteDatabase: Error Code : 6922 (SQLITE_IOERR_LOCK_EBADF)
03-29 16:24:24.124 12364 12418 E SQLiteDatabase: Caused By : I/O error happened due to bad file descriptor. There is possibility the partition changed to read-only.
03-29 16:24:24.124 12364 12418 E SQLiteDatabase: 	(disk I/O error (code 6922))
03-29 16:24:24.124 12364 12418 E SQLiteDatabase: #################################################################
03-29 16:24:24.124 12364 12418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
03-29 16:24:24.124 12364 12418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
03-29 16:24:24.124 12364 12418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
03-29 16:24:24.124 12364 12418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
03-29 16:24:24.124 12364 12418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
03-29 16:24:24.124 12364 12418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
03-29 16:24:24.124 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
03-29 16:24:24.124 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
03-29 16:24:24.124 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:183)
03-29 16:24:24.124 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
03-29 16:24:24.124 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
03-29 16:24:24.124 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
03-29 16:24:24.124 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
03-29 16:24:24.124 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
03-29 16:24:24.124 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
03-29 16:24:24.124 12364 12418 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-29 16:24:24.124 12364 12418 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-29 16:24:24.124 12364 12418 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-29 16:24:24.124 12364 12418 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-29 16:24:24.129 12420 12473 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu" with flag (131138) and mode_t (0) due to error (30)
03-29 16:24:24.129 12364 12418 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-29 16:24:24.129  3452  3914 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-29 16:24:24.129 12364 12418 E SQLiteLog: (6922) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
03-29 16:24:24.129  3452  3914 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-29 16:24:24.129  3452  3914 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-29 16:24:24.129  3452  3914 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-29 16:24:24.129 12364 12418 E SQLiteDatabase: Error inserting name=now value=Tue Mar 29 16:24:24 GMT+02:00 2016
03-29 16:24:24.129 12364 12418 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 6922)
03-29 16:24:24.129 12364 12418 E SQLiteDatabase: #################################################################
03-29 16:24:24.129 12364 12418 E SQLiteDatabase: Error Code : 6922 (SQLITE_IOERR_LOCK_EBADF)
03-29 16:24:24.129 12364 12418 E SQLiteDatabase: Caused By : I/O error happened due to bad file descriptor. There is possibility the partition changed to read-only.
03-29 16:24:24.129 12364 12418 E SQLiteDatabase: 	(disk I/O error (code 6922))
03-29 16:24:24.129 12364 12418 E SQLiteDatabase: #################################################################
03-29 16:24:24.129 12364 12418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
03-29 16:24:24.129 12364 12418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
03-29 16:24:24.129 12364 12418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
03-29 16:24:24.129 12364 12418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
03-29 16:24:24.129 12364 12418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
03-29 16:24:24.129 12364 12418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
03-29 16:24:24.129 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
03-29 16:24:24.129 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
03-29 16:24:24.129 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:184)
03-29 16:24:24.129 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
03-29 16:24:24.129 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
03-29 16:24:24.129 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
03-29 16:24:24.129 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
03-29 16:24:24.129 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
03-29 16:24:24.129 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
03-29 16:24:24.129 12364 12418 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-29 16:24:24.129 12364 12418 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-29 16:24:24.129 12364 12418 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-29 16:24:24.129 12364 12418 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-29 16:24:24.129 12364 12418 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-29 16:24:24.129 12364 12418 E SQLiteLog: (6922) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
03-29 16:24:24.129 12452 12452 D TimaKeyStoreProvider: TimaSignature is unavailable
03-29 16:24:24.129 12364 12418 E SQLiteDatabase: Error inserting name=isSystemBuild value=false
03-29 16:24:24.129 12364 12418 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 6922)
03-29 16:24:24.129 12364 12418 E SQLiteDatabase: #################################################################
03-29 16:24:24.129 12364 12418 E SQLiteDatabase: Error Code : 6922 (SQLITE_IOERR_LOCK_EBADF)
03-29 16:24:24.129 12364 12418 E SQLiteDatabase: Caused By : I/O error happened due to bad file descriptor. There is possibility the partition changed to read-only.
03-29 16:24:24.129 12364 12418 E SQLiteDatabase: 	(disk I/O error (code 6922))
03-29 16:24:24.129 12364 12418 E SQLiteDatabase: #################################################################
03-29 16:24:24.129 12364 12418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
03-29 16:24:24.129 12364 12418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
03-29 16:24:24.129 12364 12418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
03-29 16:24:24.129 12364 12418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
03-29 16:24:24.129 12364 12418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
03-29 16:24:24.129 12364 12418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
03-29 16:24:24.129 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
03-29 16:24:24.129 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
03-29 16:24:24.129 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:185)
03-29 16:24:24.129 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
03-29 16:24:24.129 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
03-29 16:24:24.129 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
03-29 16:24:24.129 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
03-29 16:24:24.129 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
03-29 16:24:24.129 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
03-29 16:24:24.129 12364 12418 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-29 16:24:24.129 12364 12418 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-29 16:24:24.129 12364 12418 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-29 16:24:24.129 12364 12418 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-29 16:24:24.129 12420 12473 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu'.
03-29 16:24:24.129 12420 12473 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-29 16:24:24.129 12420 12473 E SQLiteDatabase: #################################################################
03-29 16:24:24.129 12420 12473 E S,QLiteDatabase: Error Code : 0 (SQLITE_OK)
03-29 16:24:24.129 12420 12473 E SQLiteDatabase: Caused By : not an error (code 0): Could not open the database in read/write mode.
03-29 16:24:24.129 12420 12473 E SQLiteDatabase: #################################################################
03-29 16:24:24.129 12420 12473 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-29 16:24:24.129 12420 12473 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-29 16:24:24.129 12420 12473 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-29 16:24:24.129 12420 12473 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-29 16:24:24.129 12420 12473 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-29 16:24:24.129 12420 12473 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-29 16:24:24.129 12420 12473 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-29 16:24:24.129 12420 12473 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-29 16:24:24.129 12420 12473 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-29 16:24:24.129 12420 12473 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1585)
03-29 16:24:24.129 12420 12473 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
03-29 16:24:24.129 12420 12473 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-29 16:24:24.129 12420 12473 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-29 16:24:24.129 12420 12473 E SQLiteDatabase: 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
03-29 16:24:24.129 12420 12473 E SQLiteDatabase: 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:109)
03-29 16:24:24.129 12420 12473 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-29 16:24:24.129 12420 12473 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-29 16:24:24.129 12420 12473 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-29 16:24:24.129 12420 12473 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-29 16:24:24.129 12420 12473 W System.err: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-29 16:24:24.129 12420 12473 W System.err: #################################################################
03-29 16:24:24.129 12420 12473 W System.err: Error Code : 0 (SQLITE_OK)
03-29 16:24:24.129 12420 12473 W System.err: Caused By : not an error (code 0): Could not open the database in read/write mode.
,03-29 16:24:24.129 12420 12473 W System.err: #################################################################
03-29 16:24:24.129 12420 12473 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-29 16:24:24.129 12364 12418 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-29 16:24:24.129 12420 12473 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-29 16:24:24.129 12364 12418 E SQLiteLog: (6922) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
03-29 16:24:24.129 12420 12473 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-29 16:24:24.129 12420 12473 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
,03-29 16:24:24.129 12420 12473 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-29 16:24:24.129 12420 12473 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-29 16:24:24.129 12420 12473 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-29 16:24:24.129 12420 12473 W System.err: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
,03-29 16:24:24.129 12420 12473 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-29 16:24:24.129 12420 12473 W System.err: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1585)
03-29 16:24:24.129 12420 12473 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
03-29 16:24:24.129 12420 12473 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-29 16:24:24.129 12420 12473 W System.err: ,	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-29 16:24:24.129 12420 12473 W System.err: 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
,03-29 16:24:24.129 12420 12473 W System.err: 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:109)
03-29 16:24:24.129 12420 12473 W System.err: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-29 16:24:24.129 12420 12473 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-29 16:24:24.129 12420 12473 W System.err: 	at android.os.Looper.loop(Looper.java:145)
03-29 16:24:24.129 12420 12473 W System.err: 	,at android.os.HandlerThread.run(HandlerThread.java:61)
03-29 16:24:24.134 12364 12418 E SQLiteDatabase: Error inserting name=isDevelopVersion value=false
03-29 16:24:24.134 12364 12418 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 6922)
03-29 16:24:24.134 12364 12418 E SQLiteDatabase: #################################################################
03-29 16:24:24.134 12364 12418 E SQLiteDatabase: Error Code : 6922 (SQLITE_IOERR_LOCK_EBADF)
03-29 16:24:24.134 12364 12418 E SQLiteDatabase: Caused By : I/O error happened due to bad file descriptor. There is possibility the partition changed to read-only.
03-29 16:24:24.134 12364 12418 E SQLiteDatabase: 	(disk I/O error (code 6922))
03-29 16:24:24.134 12364 12418 E SQLiteDatabase: #################################################################
03-29 16:24:24.134 12364 12418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
03-29 16:24:24.134 12364 12418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
03-29 16:24:24.134 12364 12418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
03-29 16:24:24.134 12364 12418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
03-29 16:24:24.134 12364 12418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
03-29 16:24:24.134 12364 12418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
03-29 16:24:24.134 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
03-29 16:24:24.134 12364 12418 E SQLiteDatabase: 	,at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
03-29 16:24:24.134 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:186)
03-29 16:24:24.134 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
03-29 16:24:24.134 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
03-29 16:24:24.134 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
03-29 16:24:24.134 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
03-29 16:24:24.134 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
03-29 16:24:24.134 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
03-29 16:24:24.134 12364 12418 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-29 16:24:24.134 12364 12418 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-29 16:24:24.134 12364 12418 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-29 16:24:24.134 12364 12418 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-29 16:24:24.134 12452 12452 D ActivityThread: Added TimaKeyStore provider
,03-29 16:24:24.134 12364 12418 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-29 16:24:24.134 12364 12418 E SQLiteLog: (6922) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
03-29 16:24:24.144 12476 12476 I libpersona: KNOX_SDCARD checking this for 1000
,03-29 16:24:24.134 12364 12418 E SQLiteDatabase: Error inserting name=DBVersion value=2003
03-29 16:24:24.134 12364 12418 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 6922)
03-29 16:24:24.134 12364 12418 E SQLiteDatabase: #################################################################
03-29 16:24:24.134 12364 12418 E SQLiteDatabase: Error Code : 6922 (SQLITE_IOERR_LOCK_EBADF)
03-29 16:24:24.134 12364 12418 E SQLiteDatabase: Caused By : I/O error happened due to bad file descriptor. There is possibility the partition changed to read-only.
03-29 16:24:24.134 12364 12418 E SQLiteDatabase: 	(disk I/O error (code 6922))
03-29 16:24:24.134 12364 12418 E SQLiteDatabase: #################################################################
03-29 16:24:24.134 12364 12418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
03-29 16:24:24.134 12364 12418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
03-29 16:24:24.134 12364 12418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
03-29 16:24:24.134 12364 12418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
03-29 16:24:24.134 12364 12418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
03-29 16:24:24.134 12364 12418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
03-29 16:24:24.134 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
03-29 16:24:24.134 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
03-29 16:24:24.134 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:187)
03-29 16:24:24.134 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
03-29 16:24:24.134 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
03-29 16:24:24.134 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
03-29 16:24:24.134 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
03-29 16:24:24.134 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
03-29 16:24:24.134 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
03-29 16:24:24.134 12364 12418 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-29 16:24:24.134 12364 12418 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
,03-29 16:24:24.134 12364 12418 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-29 16:24:24.134 12364 12418 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-29 16:24:24.144 12476 12476 I libpersona: KNOX_SDCARD not a persona
03-29 16:24:24.134 12364 12418 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-29 16:24:24.134 12364 12418 E SQLiteLog: (6922) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
03-29 16:24:24.134 12364 12418 E SQLiteDatabase: Error inserting name=LPCSystemVersion value=1.0.0
03-29 16:24:24.134 12364 12418 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 6922)
03-29 16:24:24.134 12364 12418 E SQLiteDatabase: #################################################################
03-29 16:24:24.134 12364 12418 E SQLiteDatabase: Error Code : 6922 (SQLITE_IOERR_LOCK_EBADF)
03-29 16:24:24.134 12364 12418 E SQLiteDatabase: Caused By : I/O error happened due to bad file descriptor. There is possibility the partition changed to read-only.
03-29 16:24:24.134 12364 12418 E SQLiteDatabase: 	(disk I/O error (code 6922))
03-29 16:24:24.134 12364 12418 E SQLiteDatabase: #################################################################
03-29 16:24:24.134 12364 12418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
03-29 16:24:24.134 12364 12418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
03-29 16:24:24.134 12364 12418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
03-29 16:24:24.134 12364 12418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
03-29 16:24:24.134 12364 12418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
03-29 16:24:24.134 12364 12418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
03-29 16:24:24.134 12364 12418 E SQLiteDatabase: ,	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
03-29 16:24:24.134 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
,03-29 16:24:24.134 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:188)
03-29 16:24:24.134 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
03-29 16:24:24.134 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
03-29 16:24:24.134 12364 12418 E SQLiteDatabase: 	,at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
03-29 16:24:24.134 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
03-29 16:24:24.134 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
03-29 16:24:24.134 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
03-29 16:24:24.134 12364 12418 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-29 16:24:24.134 12364 12418 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-29 16:24:24.134 12364 12418 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-29 16:24:24.134 12364 12418 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-29 16:24:24.144 12364 12418 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-29 16:24:24.149  3452  3914 I ActivityManager: Start proc 12476:com.sec.knox.bridge/1000 for broadcast-4 com.sec.knox.bridge/.PersonaShortcutReceiver
03-29 16:24:24.144 12364 12418 E SQLiteLog: (6922) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
,03-29 16:24:24.144 12364 12418 E SQLiteDatabase: Error inserting name=UT enabled value=false
03-29 16:24:24.144 12364 12418 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 6922)
03-29 16:24:24.144 12364 12418 E SQLiteDatabase: #################################################################
03-29 16:24:24.144 12364 12418 E SQLiteDatabase: Error Code : 6922 (SQLITE_IOERR_LOCK_EBADF)
03-29 16:24:24.144 12364 12418 E SQLiteDatabase: Caused By : I/O error happened due to bad file descriptor. There is possibility the partition changed to read-only.
03-29 16:24:24.144 12364 12418 E SQLiteDatabase: 	(disk I/O error (code 6922))
03-29 16:24:24.144 12364 12418 E SQLiteDatabase: #################################################################
03-29 16:24:24.144 12364 12418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
03-29 16:24:24.144 12364 12418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
03-29 16:24:24.144 12364 12418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
03-29 16:24:24.144 12364 12418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
03-29 16:24:24.144 12364 12418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
03-29 16:24:24.144 12364 12418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
03-29 16:24:24.144 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
03-29 16:24:24.144 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
03-29 16:24:24.144 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:189)
03-29 16:24:24.144 12364 12418 E SQLiteDatabase: ,	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
03-29 16:24:24.144 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
03-29 16:24:24.144 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
03-29 16:24:24.144 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
03-29 16:24:24.144 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
03-29 16:24:24.144 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
03-29 16:24:24.144 12364 12418 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-29 16:24:24.144 12364 12418 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-29 16:24:24.144 12364 12418 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-29 16:24:24.144 12364 12418 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-29 16:24:24.144 12364 12418 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-29 16:24:24.144 12364 12418 E SQLiteLog: (6922) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
03-29 16:24:24.144 12476 12476 E Zygote  : MountEmulatedStorage()
03-29 16:24:24.144 12476 12476 E Zygote  : v2
,03-29 16:24:24.144 12364 12418 E SQLiteDatabase: Error inserting name=AFP Enabled value=true
,03-29 16:24:24.144 12364 12418 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 6922)
03-29 16:24:24.144 12364 12418 E SQLiteDatabase: #################################################################
03-29 16:24:24.144 12364 12418 E SQLiteDatabase: Error Code : 6922 (SQLITE_IOERR_LOCK_EBADF)
03-29 16:24:24.144 12364 12418 E SQLiteDatabase: Caused By : I/O error happened due to bad file descriptor. There is possibility the partition changed to read-only.
03-29 16:24:24.144 12364 12418 E SQLiteDatabase: 	(disk I/O error (code 6922))
03-29 16:24:24.144 12364 12418 E SQLiteDatabase: #################################################################
03-29 16:24:24.144 12364 12418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
03-29 16:24:24.144 12364 12418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
03-29 16:24:24.144 12364 12418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
,03-29 16:24:24.144 12364 12418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
03-29 16:24:24.144 12364 12418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
03-29 16:24:24.144 12364 12418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
03-29 16:24:24.144 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
03-29 16:24:24.144 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
03-29 16:24:24.144 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:190)
03-29 16:24:24.144 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
03-29 16:24:24.144 12364 12418 E SQLiteDatabase: 	,at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
03-29 16:24:24.144 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
03-29 16:24:24.144 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
03-29 16:24:24.144 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
03-29 16:24:24.144 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
,03-29 16:24:24.144 12364 12418 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-29 16:24:24.144 12364 12418 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-29 16:24:24.144 12364 12418 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-29 16:24:24.144 12364 12418 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-29 16:24:24.144 12364 12418 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-29 16:24:24.144 12364 12418 E SQLiteLog: (6922) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
03-29 16:24:24.144 12364 12418 E SQLiteDatabase: Error inserting name=SleepDetection Enabled value=false
03-29 16:24:24.144 12364 12418 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 6922)
03-29 16:24:24.144 12364 12418 E SQLiteDatabase: #################################################################
03-29 16:24:24.144 12364 12418 E SQLiteDatabase: Error Code : 6922 (SQLITE_IOERR_LOCK_EBADF)
03-29 16:24:24.144 12364 12418 E SQLiteDatabase: Caused By : I/O error happened due to bad file descriptor. There is possibility the partition changed to read-only.
03-29 16:24:24.144 12364 12418 E SQLiteDatabase: 	(disk I/O error (code 6922))
03-29 16:24:24.144 12364 12418 E SQLiteDatabase: #################################################################
03-29 16:24:24.144 12364 12418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
03-29 16:24:24.144 12364 12418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
03-29 16:24:24.144 12364 12418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
03-29 16:24:24.144 12364 12418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
03-29 16:24:24.144 12364 12418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
03-29 16:24:24.144 12364 12418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
03-29 16:24:24.144 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
,03-29 16:24:24.144 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
03-29 16:24:24.144 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:191)
03-29 16:24:24.144 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
03-29 16:24:24.144 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
03-29 16:24:24.144 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
03-29 16:24:24.144 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
03-29 16:24:24.144 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
03-29 16:24:24.144 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
03-29 16:24:24.144 12364 12418 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-29 16:24:24.144 12364 12418 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-29 16:24:24.144 12364 12418 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-29 16:24:24.144 12364 12418 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-29 16:24:24.159  3452  3694 D UsbHostManager: usbDeviceRemoved : /dev/bus/usb/001/001
03-29 16:24:24.144 12364 12418 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-29 16:24:24.159  3452  3694 E UsbHostManager: usbDeviceRemoved :: deviceName = /dev/bus/usb/001/001
,03-29 16:24:24.144 12364 12418 E SQLiteLog: (6922) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
03-29 16:24:24.149 12364 12418 E SQLiteDatabase: Error inserting name=System Build Version Release value=5.1.1
03-29 16:24:24.149 12364 12418 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 6922)
03-29 16:24:24.149 12364 12418 E SQLiteDatabase: #################################################################
03-29 16:24:24.149 12364 12418 E SQLiteDatabase: Error Code : 6922 (SQLITE_IOERR_LOCK_EBADF)
03-29 16:24:24.149 12364 12418 E SQLiteDatabase: Caused By : I/O error happened due to bad file descriptor. There is possibility the partition changed to read-only.
03-29 16:24:24.149 12364 12418 E SQLiteDatabase: 	(disk I/O error (code 6922))
03-29 16:24:24.149 12364 12418 E SQLiteDatabase: #################################################################
03-29 16:24:24.149 12364 12418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
03-29 16:24:24.149 12364 12418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
03-29 16:24:24.149 12364 12418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
03-29 16:24:24.149 12364 12418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
03-29 16:24:24.149 12364 12418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
03-29 16:24:24.149 12364 12418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
03-29 16:24:24.149 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
03-29 16:24:24.149 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
03-29 16:24:24.149 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:192)
03-29 16:24:24.149 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
03-29 16:24:24.149 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
,03-29 16:24:24.149 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
03-29 16:24:24.149 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
03-29 16:24:24.149 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
03-29 16:24:24.149 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
03-29 16:24:24.149 12364 12418 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-29 16:24:24.149 12364 12418 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-29 16:24:24.149 12364 12418 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-29 16:24:24.149 12364 12418 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-29 16:24:24.149 12364 12418 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-29 16:24:24.159  3452  4020 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{33cb02fc u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{598b5b2 12452:com.sec.pcw.device/1000}
03-29 16:24:24.149 12364 12418 E SQLiteLog: (6922) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
,03-29 16:24:24.149 12476 12476 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
03-29 16:24:24.164  3452  4399 D ActivityManager: startService callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
03-29 16:24:24.149 12364 12418 E SQLiteDatabase: Error inserting name=status value=successfully initialized
03-29 16:24:24.149 12364 12418 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 6922)
03-29 16:24:24.149 12364 12418 E SQLiteDatabase: #################################################################
03-29 16:24:24.149 12364 12418 E SQLiteDatabase: Error Code : 6922 (SQLITE_IOERR_LOCK_EBADF)
03-29 16:24:24.149 12364 12418 E SQLiteDatabase: Caused By : I/O error happened due to bad file descriptor. There is possibility the partition changed to read-only.
03-29 16:24:24.149 12364 12418 E SQLiteDatabase: 	(disk I/O error (code 6922))
03-29 16:24:24.149 12364 12418 E SQLiteDatabase: #################################################################
03-29 16:24:24.149 12364 12418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
03-29 16:24:24.149 12364 12418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
03-29 16:24:24.149 12364 12418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
03-29 16:24:24.149 12364 12418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
03-29 16:24:24.149 12364 12418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
03-29 16:24:24.149 12364 12418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
03-29 16:24:24.149 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
03-29 16:24:24.149 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
03-29 16:24:24.149 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:193)
03-29 16:24:24.149 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
03-29 16:24:24.149 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
03-29 16:24:24.149 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
03-29 16:24:24.149 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
03-29 16:24:24.149 12364 12418 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
03-29 16:24:24.149 12364 12418 E SQLiteDatabase: 	,at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
03-29 16:24:24.149 12364 12418 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-29 16:24:24.149 12364 12418 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-29 16:24:24.149 12364 12418 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-29 16:24:24.149 12364 12418 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-29 16:24:24.154 12436 12436 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
03-29 16:24:24.159 12436 12436 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
03-29 16:24:24.164 12476 12476 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
03-29 16:24:24.164 12476 12476 E Zygote  : accessInfo : 0
,03-29 16:24:24.169 12476 12476 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-29 16:24:24.174  3753 11764 I qtaguid : Tagging socket 62 with tag ffffff0100000000{4294967041,0} uid 10110, pid: 3753, getuid(): 10048
,03-29 16:24:24.189 12436 12436 I TapandpayWidget:Utils: Clear T&P info.
,03-29 16:24:24.199 12436 12436 D TapandpayWidget:TapandpayAppWidgetProvider: Widget is not attached.
,03-29 16:24:24.199  3452  3914 I ActivityManager: Killing 10454:com.samsung.android.app.filterinstaller/1000 (adj 15): emptyCount ##31
,03-29 16:24:24.224  2857  3081 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
03-29 16:24:24.224  2857  3081 W Vold    : Returning OperationFailed - no handler for errno 0
,03-29 16:24:24.229 12476 12476 D TimaKeyStoreProvider: TimaSignature is unavailable
03-29 16:24:24.229  3452  3632 I EventHub: Removing device '/dev/input/event10' due to inotify event
03-29 16:24:24.229 12349 12349 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
,03-29 16:24:24.234 12476 12476 D ActivityThread: Added TimaKeyStore provider
,03-29 16:24:24.234  3452  3914 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-29 16:24:24.234  3452  3914 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-29 16:24:24.234  3452  3914 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-29 16:24:24.234  3452  3914 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-29 16:24:24.249 12452 12452 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true,
03-29 16:24:24.249 12452 12452 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
03-29 16:24:24.249 12452 12452 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
03-29 16:24:24.254  3452  3632 I EventHub: Removing device '/dev/input/event7' due to inotify event
03-29 16:24:24.254 12452 12452 E SQLiteLog: (28) failed to open "/data/data/com.sec.pcw.device/databases/value.db" with flag (131138) and mode_t (0) due to error (30)
,03-29 16:24:24.254 12452 12452 E SQLiteDatabase: Failed to open database '/data/data/com.sec.pcw.device/databases/value.db'.,
03-29 16:24:24.254 12452 12452 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-29 16:24:24.254 12452 12452 E SQLiteDatabase: #################################################################
03-29 16:24:24.254 12452 12452 E SQLiteDatabase: Error Code : 0 (SQLITE_OK)
03-29 16:24:24.254 12452 12452 E SQLiteDatabase: Caused By : not an error (code 0): Could not open the database in read/write mode.
03-29 16:24:24.254 12452 12452 E SQLiteDatabase: #################################################################
03-29 16:24:24.254 12452 12452 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
,03-29 16:24:24.254 12452 12452 E SQLiteDatabase: ,	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-29 16:24:24.254 12452 12452 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-29 16:24:24.254 12452 12452 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-29 16:24:24.254 12452 12452 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-29 16:24:24.254 12452 12452 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-29 16:24:24.254 12452 12452 E SQLiteDatabase: ,	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-29 16:24:24.254 12452 12452 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-29 16:24:24.254 12452 12452 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-29 16:24:24.254 12452 12452 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1585)
03-29 16:24:24.254 12452 12452 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
03-29 16:24:24.254 12452 12452 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-29 16:24:24.254 12452 12452 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-29 16:24:24.254 12452 12452 E SQLiteDatabase: ,	at com.sec.pcw.device.contentprovider.DMProvider.onCreate(DMProvider.java:32)
03-29 16:24:24.254 12452 12452 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1737)
03-29 16:24:24.254 12452 12452 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
03-29 16:24:24.254 12452 12452 E SQLiteDatabase: 	,at android.app.ActivityThread.installProvider(ActivityThread.java:6413)
03-29 16:24:24.254 12452 12452 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:6008)
03-29 16:24:24.254 12452 12452 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5948)
03-29 16:24:24.254 12452 12452 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:197)
03-29 16:24:24.254 12452 12452 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1742)
03-29 16:24:24.254 12452 12452 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-29 16:24:24.254 12452 12452 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-29 16:24:24.254 12452 12452 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6872)
03-29 16:24:24.254 12452 12452 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method),
03-29 16:24:24.254 12452 12452 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-29 16:24:24.254 12452 12452 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
03-29 16:24:24.254 12452 12452 E SQLiteDatabase: 	,at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
03-29 16:24:24.259 12452 12452 D AndroidRuntime: Shutting down VM
03-29 16:24:24.289 12493 12493 I libpersona: KNOX_SDCARD checking this for 10193
03-29 16:24:24.259 12452 12452 E AndroidRuntime: FATAL EXCEPTION: main
03-29 16:24:24.259 12452 12452 E AndroidRuntime: Process: com.sec.pcw.device, PID: 12452
03-29 16:24:24.259 12452 12452 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.sec.pcw.device.contentprovider.DMProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-29 16:24:24.259 12452 12452 E AndroidRuntime: #################################################################
03-29 16:24:24.259 12452 12452 E AndroidRuntime: Error Code : 0 (SQLITE_OK)
03-29 16:24:24.259 12452 12452 E AndroidRuntime: Caused By : not an error (code 0): Could not open the database in read/write mode.
03-29 16:24:24.259 12452 12452 E AndroidRuntime: #################################################################
03-29 16:24:24.259 12452 12452 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:6416)
03-29 16:24:24.259 12452 12452 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:6008)
03-29 16:24:24.259 12452 12452 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5948)
03-29 16:24:24.259 12452 12452 E AndroidRuntime: 	at android.app.ActivityThread.access$1700(ActivityThread.java:197)
03-29 16:24:24.259 12452 12452 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1742)
03-29 16:24:24.259 12452 12452 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-29 16:24:24.259 12452 12452 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
03-29 16:24:24.259 12452 12452 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6872)
03-29 16:24:24.259 12452 12452 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
03-29 16:24:24.259 12452 12452 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-29 16:24:24.259 12452 12452 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
03-29 16:24:24.259 12452 12452 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
03-29 16:24:24.259 12452 12452 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-29 16:24:24.259 12452 12452 E AndroidRuntime: #################################################################
03-29 16:24:24.259 12452 12452 E AndroidRuntime: Error Code : 0 (SQLITE_OK)
03-29 16:24:24.259 12452 12452 E AndroidRuntime: Caused By : not an error (code 0): Could not open the database in read/write mode.
03-29 16:24:24.259 12452 12452 E AndroidRuntime: #################################################################
03-29 16:24:24.259 12452 12452 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-29 16:24:24.259 12452 12452 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-29 16:24:24.259 12452 12452 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-29 16:24:24.259 12452 12452 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-29 16:24:24.259 12452 12452 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-29 16:24:24.259 12452 12452 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-29 16:24:24.259 12452 12452 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-29 16:24:24.259 12452 12452 E AndroidRuntime: 	at android.database.sqlite.SQLiteDat,abase.open(SQLiteDatabase.java:878)
03-29 16:24:24.259 12452 12452 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-29 16:24:24.259 12452 12452 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1585)
03-29 16:24:24.259 12452 12452 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
03-29 16:24:24.259 12452 12452 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-29 16:24:24.259 12452 12452 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-29 16:24:24.259 12452 12452 E AndroidRuntime: 	at com.sec.pcw.device.contentprovider.DMProvider.onCreate(DMProvider.java:32)
03-29 16:24:24.259 12452 12452 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1737)
03-29 16:24:24.259 12452 12452 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
03-29 16:24:24.259 12452 12452 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:6413)
03-29 16:24:24.259 12452 12452 E AndroidRuntime: 	... 11 more
03-29 16:24:24.289 12493 12493 I libpersona: KNOX_SDCARD not a persona
03-29 16:24:24.279  3753 11764 I qtaguid : Untagging socket 58
03-29 16:24:24.284  3753 11764 I qtaguid : Untagging socket 64
03-29 16:24:24.284  3753 11764 W DownloadManager: [118] Stop requested with status FILE_ERROR: write failed: EBADF (Bad file number)
,03-29 16:24:24.284  3753 11764 D DownloadManager: [118] Finished with status FILE_ERROR
03-29 16:24:24.289 12493 12493 E Zygote  : MountEmulatedStorage()
03-29 16:24:24.289 12493 12493 E Zygote  : v2
03-29 16:24:24.289  3452  3632 I EventHub: Removing device '/dev/input/event8' due to inotify event
03-29 16:24:24.289 12493 12493 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
03-29 16:24:24.299 12493 12493 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
03-29 16:24:24.299 12493 12493 E Zygote  : accessInfo : 0
,03-29 16:24:24.304 12493 12493 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-29 16:24:24.304  3452  3914 I ActivityManager: Start proc 12493:com.sec.enterprise.knox.cloudmdm.smdms/u0a193 for broadcast-4 com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver
,03-29 16:24:24.324  3452  3914 I ActivityManager: Killing 10496:com.samsung.helphub/1000 (adj 15): emptyCount ##31
,03-29 16:24:24.329  3753  3753 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
,03-29 16:24:24.329  3753  3753 E SQLiteLog: (6922) statement aborts at 77: [UPDATE downloads SET lastmod=?,total_bytes=? WHERE (_id = ?)] disk I/O error
03-29 16:24:24.329  3452  3998 D ActivityManager: startService callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
,03-29 16:24:24.339  3452  3632 I EventHub: Removing device '/dev/input/event9' due to inotify event
,03-29 16:24:24.339  3452  4399 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.pcw.device
,03-29 16:24:24.349  3753  3753 D AndroidRuntime: Shutting down VM
,03-29 16:24:24.359  3753  3753 E AndroidRuntime: FATAL EXCEPTION: main
03-29 16:24:24.359  3753  3753 E AndroidRuntime: Process: android.process.media, PID: 3753
03-29 16:24:24.359  3753  3753 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 6922)
03-29 16:24:24.359  3753  3753 E AndroidRuntime: #################################################################
03-29 16:24:24.359  3753  3753 E AndroidRuntime: Error Code : 6922 (SQLITE_IOERR_LOCK_EBADF)
03-29 16:24:24.359  3753  3753 E AndroidRuntime: Caused By : I/O error happened due to bad file descriptor. There is possibility the partition changed to read-only.
03-29 16:24:24.359  3753  3753 E AndroidRuntime: 	(disk I/O error (code 6922))
03-29 16:24:24.359  3753  3753 E AndroidRuntime: #################################################################
03-29 16:24:24.359  3753  3753 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
03-29 16:24:24.359  3753  3753 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
03-29 16:24:24.359  3753  3753 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
03-29 16:24:24.359  3753  3753 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
03-29 16:24:24.359  3753  3753 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1714)
03-29 16:24:24.359  3753  3753 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1660)
03-29 16:24:24.359  3753  3753 E AndroidRuntime: 	at com.android.providers.downloads.DownloadProvider.update(DownloadProvider.java:1314)
03-29 16:24:24.359  3753  3753 E AndroidRuntime: 	at com.android.providers.downloads.DownloadProvider$1.onClose(DownloadProvider.java:1485)
03-29 16:24:24.359  3753  3753 E AndroidRuntime: 	at android.os.ParcelFileDescriptor$ListenerBridge$1.handleMessage(ParcelFileDescriptor.java:1021)
03-29 16:24:24.359  3753  3753 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-29 16:24:24.359  3753  3753 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
03-29 16:24:24.359  3753  3753 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6872)
03-29 16:24:24.359  3753  3753 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
03-29 16:24:24.359  3753  3753 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-29 16:24:24.359  3753  3753 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
03-29 16:24:24.359  3753  3753 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
,03-29 16:24:24.369  3452  3632 I EventHub: Removing device '/dev/input/event11' due to inotify event
,03-29 16:24:24.374  3452  3994 V BroadcastQueue: [backgroundsplit_1] Process cur broadcast BroadcastRecord{36fbaf5c u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{395556b9 12476:com.sec.knox.bridge/1000}
,03-29 16:24:24.379 12493 12493 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-29 16:24:24.384 12493 12493 D ActivityThread: Added TimaKeyStore provider
,03-29 16:24:24.404  3452 12509 W System.err: remove failed: EROFS (Read-only file system) : /data/system/dropbox/event_data@1459002262616.txt
,03-29 16:24:24.409  3452  3914 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname android.process.media
,03-29 16:24:24.409  3452 12509 E DropBoxManagerService: Can't write: system_app_crash
03-29 16:24:24.409  3452 12509 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop224.tmp: open failed: EROFS (Read-only file system)
03-29 16:24:24.409  3452 12509 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-29 16:24:24.409  3452 12509 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-29 16:24:24.409  3452 12509 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-29 16:24:24.409  3452 12509 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-29 16:24:24.409  3452 12509 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-29 16:24:24.409  3452 12509 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$23.run(ActivityManagerService.java:16408)
03-29 16:24:24.409  3452 12509 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-29 16:24:24.409  3452 12509 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-29 16:24:24.409  3452 12509 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-29 16:24:24.409  3452 12509 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-29 16:24:24.409  3452 12509 E DropBoxManagerService: 	... 5 more
,03-29 16:24:24.414  3452  3632 I EventHub: Removing device '/dev/input/event12' due to inotify event
,03-29 16:24:24.419  3452 12509 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/dropbox/drop224.tmp
,03-29 16:24:24.434  3452  3599 V BroadcastQueue: [backgroundsplit_2] Process cur broadcast BroadcastRecord{38cc5b3a u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{35d87afe 12493:com.sec.enterprise.knox.cloudmdm.smdms/u0a193}
,03-29 16:24:24.444  3452 12511 E DropBoxManagerService: Can't write: system_app_crash
03-29 16:24:24.444  3452 12511 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop225.tmp: open failed: EROFS (Read-only file system)
03-29 16:24:24.444  3452 12511 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-29 16:24:24.444  3452 12511 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-29 16:24:24.444  3452 12511 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-29 16:24:24.444  3452 12511 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-29 16:24:24.444  3452 12511 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-29 16:24:24.444  3452 12511 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$23.run(ActivityManagerService.java:16408)
03-29 16:24:24.444  3452 12511 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-29 16:24:24.444  3452 12511 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-29 16:24:24.444  3452 12511 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-29 16:24:24.444  3452 12511 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-29 16:24:24.444  3452 12511 E DropBoxManagerService: 	... 5 more
03-29 16:24:24.444  3452 12511 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/dropbox/drop225.tmp
,03-29 16:24:24.449 12476 12476 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-29 16:24:24.454  3452  3491 I ActivityManager: Killing 10437:com.android.providers.calendar/u0a47 (adj 15): emptyCount ##31
,03-29 16:24:24.459  3753 11764 W System.err: remove failed: EROFS (Read-only file system) : /storage/emulated/0/Android/data/com.facebook.appmanager/files/Download/fileDownloader/18.com.facebook.katana.25391168.apkdiff
03-29 16:24:24.459  3753 11764 V DownloadManager: MIME Type = application/vnd.android.package-archive
,03-29 16:24:24.459  3753 11764 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-29 16:24:24.459  3753 11764 E SQLiteLog: (6922) statement aborts at 77: [UPDATE downloads SET etag=?,method=?,lastmod=?,state=?,current_bytes=?,range_end=?,range_start=?,mimetype=?,numfailed=?,errorMsg=?,_data=?,status=?,total_bytes=?,uri=?,range_first_end=
03-29 16:24:24.459  3452  3632 I EventHub: Removing device '/dev/input/event13' due to inotify event
,03-29 16:24:24.469  3452  3572 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-29 16:24:24.469  3452  3572 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-29 16:24:24.469  3452  3572 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-29 16:24:24.469  3452  3572 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-29 16:24:24.479  3753 11764 W DownloadManager: Uncaught exception
03-29 16:24:24.479  3753 11764 W DownloadManager: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 6922)
03-29 16:24:24.479  3753 11764 W DownloadManager: #################################################################
03-29 16:24:24.479  3753 11764 W DownloadManager: Error Code : 6922 (SQLITE_IOERR_LOCK_EBADF)
03-29 16:24:24.479  3753 11764 W DownloadManager: Caused By : I/O error happened due to bad file descriptor. There is possibility the partition changed to read-only.
03-29 16:24:24.479  3753 11764 W DownloadManager: 	(disk I/O error (code 6922))
03-29 16:24:24.479  3753 11764 W DownloadManager: #################################################################
03-29 16:24:24.479  3753 11764 W DownloadManager: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
03-29 16:24:24.479  3753 11764 W DownloadManager: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
03-29 16:24:24.479  3753 11764 W DownloadManager: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
03-29 16:24:24.479  3753 11764 W DownloadManager: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
03-29 16:24:24.479  3753 11764 W DownloadManager: 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1714)
03-29 16:24:24.479  3753 11764 W DownloadManager: 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1660)
03-29 16:24:24.479  3753 11764 W DownloadManager: 	at com.android.providers.downloads.DownloadProvider.update(DownloadProvider.java:1314)
03-29 16:24:24.479  3753 11764 W DownloadManager: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:341)
03-29 16:24:24.479  3753 11764 W DownloadManager: 	at android.content.ContentResolver.update(ContentResolver.java:1386)
03-29 16:24:24.479  3753 11764 W DownloadManager: 	at com.android.providers.downloads.DownloadThread$DownloadInfoDelta.writeToDatabase(DownloadThread.java:365)
03-29 16:24:24.479  3753 11764 W DownloadManager: 	at com.android.providers.downloads.DownloadThread.run(DownloadThread.java:676)
03-29 16:24:24.479  3753 11764 W DownloadManager: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-29 16:24:24.479  3753 11764 W DownloadManager: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-29 16:24:24.479  3753 11764 W DownloadManager: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 16:24:24.479  3753 11764 W DownloadManager: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 16:24:24.479  3753 11764 W DownloadManager: 	at java.lang.Thread.run(Thread.java:818)
,03-29 16:24:24.499 12476 12476 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
03-29 16:24:24.499 12493 12493 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-29 16:24:24.514 12513 12513 E Zygote  : MountEmulatedStorage()
03-29 16:24:24.514 12513 12513 E Zygote  : v2
03-29 16:24:24.514 12513 12513 I libpersona: KNOX_SDCARD checking this for 10035
03-29 16:24:24.514 12513 12513 I libpersona: KNOX_SDCARD not a persona
,03-29 16:24:24.519 12364 12364 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
03-29 16:24:24.519 12513 12513 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
,03-29 16:24:24.529 12513 12513 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
03-29 16:24:24.529  3452  3632 I EventHub: Removing device '/dev/input/event14' due to inotify event
03-29 16:24:24.529 12513 12513 E Zygote  : accessInfo : 0
,03-29 16:24:24.529 12513 12513 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-29 16:24:24.534  3452  3491 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
03-29 16:24:24.534  3452  3491 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
,03-29 16:24:24.534 12493 12493 D [0]UMC:UMCContentProvider: @onCreate
,03-29 16:24:24.539  3452  3572 I ActivityManager: Start proc 12513:com.samsung.android.app.galaxyfinder/u0a35 for broadcast-3 com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver
,03-29 16:24:24.549  3452  4028 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-29 16:24:24.549  3452  4028 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-29 16:24:24.549  3452  4028 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-29 16:24:24.549  3452  4028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-29 16:24:24.579 12513 12513 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-29 16:24:24.584 12528 12528 E Zygote  : MountEmulatedStorage()
03-29 16:24:24.584 12528 12528 E Zygote  : v2
03-29 16:24:24.584 12528 12528 I libpersona: KNOX_SDCARD checking this for 10045
03-29 16:24:24.584 12528 12528 I libpersona: KNOX_SDCARD not a persona
03-29 16:24:24.584  3452  4028 I ActivityManager: Start proc 12528:com.osp.app.signin/u0a45 for broadcast-4 com.osp.app.signin/com.msc.sa.selfupdate.SelfUpgradeReceiver
,03-29 16:24:24.584 12528 12528 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
03-29 16:24:24.584 12513 12513 D ActivityThread: Added TimaKeyStore provider
,03-29 16:24:24.589 12528 12528 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
,03-29 16:24:24.589 12528 12528 E Zygote  : accessInfo : 0
,03-29 16:24:24.594 12528 12528 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL,
,03-29 16:24:24.609 12452 12452 I Process : Sending signal. PID: 12452 SIG: 9
03-29 16:24:24.609  3452  3994 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,03-29 16:24:24.629 10778 10787 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-29 16:24:24.629 10778 10787 E SQLiteLog: (6922) statement aborts at 27: [UPDATE apps SET badgecount=? WHERE package=? AND class=?] disk I/O error
,03-29 16:24:24.639  3452  4010 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{33cb02fc u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{895557b 12513:com.samsung.android.app.galaxyfinder/u0a35}
,03-29 16:24:24.644 10778 10787 E DatabaseUtils: Writing exception to parcel
03-29 16:24:24.644 10778 10787 E DatabaseUtils: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 6922)
03-29 16:24:24.644 10778 10787 E DatabaseUtils: #################################################################
03-29 16:24:24.644 10778 10787 E DatabaseUtils: Error Code : 6922 (SQLITE_IOERR_LOCK_EBADF)
03-29 16:24:24.644 10778 10787 E DatabaseUtils: Caused By : I/O error happened due to bad file descriptor. There is possibility the partition changed to read-only.
03-29 16:24:24.644 10778 10787 E DatabaseUtils: 	(disk I/O error (code 6922))
03-29 16:24:24.644 10778 10787 E DatabaseUtils: #################################################################
03-29 16:24:24.644 10778 10787 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
03-29 16:24:24.644 10778 10787 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
03-29 16:24:24.644 10778 10787 E DatabaseUtils: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
03-29 16:24:24.644 10778 10787 E DatabaseUtils: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
03-29 16:24:24.644 10778 10787 E DatabaseUtils: 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1714)
03-29 16:24:24.644 10778 10787 E DatabaseUtils: 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1660)
03-29 16:24:24.644 10778 10787 E DatabaseUtils: 	at com.sec.android.provider.badge.BadgeProvider.update(BadgeProvider.java:176)
03-29 16:24:24.644 10778 10787 E DatabaseUtils: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:341)
03-29 16:24:24.644 10778 10787 E DatabaseUtils: 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:222)
03-29 16:24:24.644 10778 10787 E DatabaseUtils: 	at android.os.Binder.execTransact(Binder.java:461)
,03-29 16:24:24.654  3452  4028 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-29 16:24:24.654  3452  4028 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-29 16:24:24.654  3452  4028 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-29 16:24:24.654  3452  4028 E ActivityManager: checkUser: useridlist=null, currentuser=0

```
