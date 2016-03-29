#### Test 63998117d1f6a2b_thali08_samsung-SM-N910C Logs


```
--------- beginning of system
,03-29 13:29:32.162  3481  4438 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-29 13:29:32.172  3481  4438 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
--------- beginning of main
03-29 13:29:32.187  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-29 13:29:32.172  3481  4438 D BatteryService: online:4, current avg:39, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:45
03-29 13:29:32.187  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-29 13:29:32.172  3481  3481 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-29 13:29:32.187  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
03-29 13:29:32.182  3481  3481 I MotionRecognitionService: Plugged
03-29 13:29:32.182  3481  3481 D MotionRecognitionService:   cableConnection= 1
03-29 13:29:32.182  3481  3481 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-29 13:29:32.182  3481  3481 D MotionRecognitionService: skip setTransmitPower. 
03-29 13:29:32.187  3481  4438 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 23ms
03-29 13:29:32.187  3481  4438 D BatteryService: stay LED for fully charged
03-29 13:29:32.207  5947  5947 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-29 13:29:32.207  5947  6065 D HeadsetStateMachine: Disconnected process message: 10
03-29 13:29:32.217  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-29 13:29:32.222  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-29 13:29:32.222  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-29 13:29:32.222  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-29 13:29:32.612 11182 11182 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
03-29 13:29:32.617 11182 11182 D AndroidRuntime: CheckJNI is OFF
03-29 13:29:32.617 11182 11182 D AndroidRuntime: readGMSProperty: start
03-29 13:29:32.617 11182 11182 D AndroidRuntime: readGMSProperty: already setted!!
03-29 13:29:32.617 11182 11182 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-29 13:29:32.617 11182 11182 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-29 13:29:32.617 11182 11182 D AndroidRuntime: readGMSProperty: end
03-29 13:29:32.617 11182 11182 D AndroidRuntime: addProductProperty: start
03-29 13:29:32.822 11182 11182 E AffinityControl: AffinityControl: registerfunction enter
03-29 13:29:32.847 11182 11182 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-29 13:29:32.862  3481  4718 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
03-29 13:29:32.867  3481  4718 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-29 13:29:32.902  3481  4718 W ActivityManager: mDVFSHelper.acquire()
03-29 13:29:32.902  3481  4718 V WindowManager: addAppToken: AppWindowToken{330810e9 token=Token{1c8d3570 ActivityRecord{1e2b8bb3 u0 com.test.thalitest/.MainActivity t42}}} to stack=1 task=42 at 0
03-29 13:29:32.907  3481  4718 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-29 13:29:32.907  3481  4718 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-29 13:29:32.907  3481  4718 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-29 13:29:32.907  3481  4718 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-29 13:29:32.917  3481  3584 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-29 13:29:32.917  3481  3584 D PhoneWindow: *FMB* installDecor flags : -2122120936
03-29 13:29:32.917  3481  3584 D SecWifiDisplayUtil: Metadata value : none
03-29 13:29:32.917  3481  3584 V WindowManager: Adding window Window{2e8e4288 u0 d0 Starting com.test.thalitest} at 3 of 7 (after Window{1fb2a860 u0 d0 com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity})
03-29 13:29:32.927 11202 11202 E Zygote  : MountEmulatedStorage()
03-29 13:29:32.927 11202 11202 E Zygote  : v2
03-29 13:29:32.927 11202 11202 I libpersona: KNOX_SDCARD checking this for 10011
03-29 13:29:32.927 11202 11202 I libpersona: KNOX_SDCARD not a persona
03-29 13:29:32.932 11202 11202 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
03-29 13:29:32.932  3481  4718 I ActivityManager: Start proc 11202:com.test.thalitest/u0a11 for activity com.test.thalitest/.MainActivity
03-29 13:29:32.932  3481  4718 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
03-29 13:29:32.932  3481  4718 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-29 13:29:32.932  3481  4718 D InputDispatcher: Focused application set to: xxxx
03-29 13:29:32.932  3481  4718 D MultiWindowConverter: dismissGuide() : Before attaching the guide view, mForceDismissGuide : false
03-29 13:29:32.932  3481  4718 D InputDispatcher: Focus left window: 6713
03-29 13:29:32.932 11182 11182 D AndroidRuntime: Shutting down VM
03-29 13:29:32.932  3481  3584 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-29 13:29:32.932  3481  3584 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
03-29 13:29:32.932 11202 11202 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
03-29 13:29:32.937 11202 11202 E Zygote  : accessInfo : 0
03-29 13:29:32.937 11202 11202 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-29 13:29:32.937  2860  2860 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=404, uhalitest
03-29 13:29:32.952 11202 11202 D TimaKeyStoreProvider: TimaSignature is unavailable
03-29 13:29:32.952 11202 11202 D ActivityThread: Added TimaKeyStore provider
03-29 13:29:32.962  3481  3511 D PowerManagerService: setKeyboardVisibility: false
03-29 13:29:32.962  3481  3584 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3481 uid:1000
03-29 13:29:32.962  3481  3584 D PointerIcon: setMouseCustomIcon IconType is same.101
03-29 13:29:32.962  3481  3584 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3481 uid:1000
03-29 13:29:32.962  3481  3584 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
03-29 13:29:32.962  3481  3582 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{2e8e4288 u0 d0 Starting com.test.thalitest}
03-29 13:29:32.962  3481  3511 D ActivityManager:  Launching com.test.thalitest, updated priority
03-29 13:29:32.977  3481  3511 I ActivityManager: Skip updateThumbnail for r=ActivityRecord{1e2b8bb3 u0 com.test.thalitest/.MainActivity t42}
03-29 13:29:32.992  2860  9330 I SurfaceFlinger: id=12 Removed YUIInstallC (5/9)
03-29 13:29:32.997  2860  3018 I SurfaceFlinger: id=12 Removed YUIInstallC (-2/9)
03-29 13:29:32.997  6713  6713 V ActivityThread: updateVisibility : ActivityRecord{2b930f32 token=android.os.BinderProxy@27aad868 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
03-29 13:29:33.137  3481  6174 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,03-29 13:29:33.182 11202 11202 D SecWifiDisplayUtil: Metadata value : none
03-29 13:29:33.232 11202 11202 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
03-29 13:29:33.242 11202 11202 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 6225-6227)
03-29 13:29:33.242 11202 11202 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-29 13:29:33.257 11202 11202 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {d3d4163}
03-29 13:29:33.257 11202 11202 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-29 13:29:33.257 11202 11202 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
03-29 13:29:33.267 11202 11219 W System.err: remove failed: ENOENT (No such file or directory) : /data/data/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
03-29 13:29:33.277 11202 11202 I BrowserStartupController: Initializing chromium process, singleProcess=true
03-29 13:29:33.277 11202 11202 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-29 13:29:33.277 11202 11202 E SysUtils: ApplicationContext is null in ApplicationStatus
03-29 13:29:33.302 11202 11202 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
03-29 13:29:33.307 11202 11202 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=37 off=50556 len=3379
03-29 13:29:33.307 11202 11202 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:38 off:7638088 len:1165478
03-29 13:29:33.387 11202 11242 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
03-29 13:29:33.427 11202 11202 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-29 13:29:33.447 11202 11202 W AwContents: onDetachedFromWindow called when already detached. Ignoring
03-29 13:29:33.462 11202 11202 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-29 13:29:33.462 11202 11202 D PhoneWindow: *FMB* installDecor flags : -2139027200
03-29 13:29:33.472 11202 11202 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
03-29 13:29:33.477 11202 11202 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-29 13:29:33.477 11202 11202 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-29 13:29:33.552 11202 11255 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
03-29 13:29:33.557  3481  4417 V WindowManager: Adding window Window{96c37c9 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity} at 3 of 8 (before Window{2e8e4288 u0 d0 Starting com.test.thalitest})
03-29 13:29:33.562  3481  3745 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-29 13:29:33.562  3481  3745 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-29 13:29:33.562  3481  3745 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-29 13:29:33.562  3481  3481 D KnoxTimeoutHandler: handleActiveUserChange for user 0
03-29 13:29:33.562  3481  3481 E EnterpriseSharedDevicePolicy: isSharedDeviceEnabled
03-29 13:29:33.562  3481  3481 I EnterpriseSharedDevicePolicy: isSharedDeviceEnabled in Service
03-29 13:29:33.562  3481  3481 I EnterpriseSharedDevicePolicy: Get Result: -1
03-29 13:29:33.562  3481  3481 I EnterpriseSharedDevicePolicy: status: false
03-29 13:29:33.562  3481  3481 D PersonaManagerService: getPersonasForUser(): returning null!
03-29 13:29:33.562  3481  3481 I KnoxTimeoutHandler: Shared devices show user statefalse
03-29 13:29:33.577 11202 11202 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-29 13:29:33.577 11202 11202 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
03-29 13:29:33.577 11202 11202 D SecWifiDisplayUtil: Metadata value : none
03-29 13:29:33.587  2860  2860 I SurfaceFlinger: id=15 createSurf (1x1),1 flag=404, NainActivit
03-29 13:29:33.587  3481  4029 D MultiWindowConverter: dismissGuide() : Before attaching the guide view, mForceDismissGuide : false
03-29 13:29:33.592  3481  4029 D InputDispatcher: Focus entered window: 11202
03-29 13:29:33.597  3481  3584 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3481 uid:1000
03-29 13:29:33.597  3481  3584 D PointerIcon: setMouseCustomIcon IconType is same.101
03-29 13:29:33.597  3481  3584 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3481 uid:1000
03-29 13:29:33.597  3481  3584 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
03-29 13:29:33.597 11202 11202 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
03-29 13:29:33.597 11202 11255 I OpenGLRenderer: Initialized EGL, version 1.4
03-29 13:29:33.597 11202 11255 I OpenGLRenderer: HWUI protection enabled for context ,  &this =0xae430910 ,&mEglDisplay = 1 , &mEglConfig = -1266757360 
03-29 13:29:33.597 11202 11255 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
03-29 13:29:33.597 11202 11255 D OpenGLRenderer: Enabling debug mode 0
03-29 13:29:33.602 11202 11255 D mali_winsys: new_window_surface returns 0x3000,  [1440x2560]-format:1
03-29 13:29:33.602 11202 11202 V ActivityThread: updateVisibility : ActivityRecord{367e8fcb token=android.os.BinderProxy@4cea345 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
03-29 13:29:33.642  3481  3745 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
03-29 13:29:33.647  3481  3584 I ActivityManager: Displayed Component not be shown by security: +534ms (total +1m27s151ms)
03-29 13:29:33.647  3481  3584 W ActivityManager: mDVFSHelper.release()
03-29 13:29:33.647  3726  3726 D PanelView: There is/are notification(s) 
03-29 13:29:33.647  3481  3584 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1e2b8bb3 u0 com.test.thalitest/.MainActivity t42} time:186634
03-29 13:29:33.652  2860  3018 I SurfaceFlinger: id=14 Removed uhalitest (7/9)
03-29 13:29:33.652  2860  3688 I SurfaceFlinger: id=14 Removed uhalitest (-2/9)
03-29 13:29:33.677 11202 11202 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
03-29 13:29:33.677 11202 11202 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@4cea345 time:186664
03-29 13:29:33.702 11202 11202 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 11202
03-29 13:29:33.827 11202 11202 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-29 13:29:33.892 11202 11259 D jxcore_app_log: JniHelper::setJavaVM(0xb449d200), pthread_self() = -1626208128
,03-29 13:29:33.897 11202 11259 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-29 13:29:33.897 11202 11259 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-29 13:29:33.897 11202 11259 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-29 13:29:33.897 11202 11259 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-29 13:29:33.897 11202 11259 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-29 13:29:33.897 11202 11259 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2494e6d8 added. We now have 1 listener(s)
,03-29 13:29:33.902 11202 11259 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: E0:DB:10:14:E2:C0
,03-29 13:29:33.902 11202 11259 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
,03-29 13:29:33.902 11202 11259 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-29 13:29:33.902 11202 11259 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,03-29 13:29:33.902 11202 11219 W System.err: remove failed: ENOENT (No such file or directory) : /data/data/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,03-29 13:29:33.907 11202 11259 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-29 13:29:33.907 11202 11259 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-29 13:29:33.907 11202 11259 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-29 13:29:33.907 11202 11259 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: E0:DB:10:14:E2:C0
03-29 13:29:33.907 11202 11259 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-29 13:29:33.907 11202 11259 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-29 13:29:33.907 11202 11259 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
03-29 13:29:33.907 11202 11259 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-29 13:29:33.907 11202 11259 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-29 13:29:33.907 11202 11259 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-29 13:29:33.907 11202 11259 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-29 13:29:33.907 11202 11259 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1549fe97 added. We now have 1 listener(s)
03-29 13:29:33.907 11202 11259 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-29 13:29:33.912 11202 11259 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,03-29 13:29:33.912 11202 11259 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
03-29 13:29:33.912 11202 11259 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
03-29 13:29:33.912 11202 11259 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-29 13:29:33.912 11202 11259 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,03-29 13:29:33.917 11202 11259 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-29 13:29:33.917 11202 11259 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is E0:DB:10:14:E2:C0
,03-29 13:29:33.922 11202 11259 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-29 13:29:33.922 11202 11259 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-29 13:29:33.922 11202 11259 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-29 13:29:33.922 11202 11259 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-29 13:29:33.922 11202 11259 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-29 13:29:33.922 11202 11259 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-29 13:29:33.922 11202 11259 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-29 13:29:33.922 11202 11259 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-29 13:29:33.922 11202 11259 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-29 13:29:33.922 11202 11259 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-29 13:29:33.922 11202 11259 I io.jxcore.node.LifeCycleMonitor: start: OK
,03-29 13:29:33.922 11202 11202 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-29 13:29:33.927 11202 11202 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,03-29 13:29:33.952 11202 11202 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-29 13:29:34.062  3481  6174 D SSRM:n  : SIOP:: AP = 270, PST = 280 (W:14), CUR = 39, LCD = 0
,03-29 13:29:34.372 11202 11266 W jxcore-log: Initializing JXcore engine
03-29 13:29:34.372 11202 11266 W jxcore-log: JXcore engine is ready
,03-29 13:29:34.397  4798  4798 E auditd  : In denial and Property audit_ondenial is set to 1 
,03-29 13:29:34.397  4798  4798 E audit   : type=1400 msg=audit(1459250974.397:196): avc:  denied  { ioctl } for  pid=11266 comm="Thread-1544" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2213 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
03-29 13:29:34.402  3481  3580 D SecurityLogAgent:SEDenialService: Got Modify Event and sending Denial Intent foraudit.log
03-29 13:29:34.402  4798  4798 E audit   :  SEPF_SM-N910C_5.1.1_0038
03-29 13:29:34.402  4798  4798 E audit   : type=1300 msg=audit(1459250974.397:196): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=2 a3=962008d8 items=0 ppid=2902 ppcomm=main pid=11266 auid=4294967295 uid=10011 gid=10011 euid=10011 suid=10011 fsuid=10011 egid=10011 sgid=10011 fsgid=10011 ses=4294967295 tty=(none) comm="Thread-1544" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
,03-29 13:29:34.402  4798  4798 E audit   : type=1320 msg=audit(1459250974.397:196): 
,03-29 13:29:34.402  3481  3580 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.android.server.SEDenialService$AuditFileObserver.onEvent:80 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,03-29 13:29:34.402  3481  3580 D SecurityLogAgent:SEDenialService: audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,03-29 13:29:34.402  3481  3575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-29 13:29:34.402  3481  3575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-29 13:29:34.402 11202 11266 W jxcore-log: Starting JXcore engine
03-29 13:29:34.402  3481  3575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-29 13:29:34.402  3481  3575 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-29 13:29:34.417 11267 11267 E Zygote  : MountEmulatedStorage()
,03-29 13:29:34.417 11267 11267 E Zygote  : v2
03-29 13:29:34.417 11267 11267 I libpersona: KNOX_SDCARD checking this for 1000
03-29 13:29:34.417 11267 11267 I libpersona: KNOX_SDCARD not a persona
03-29 13:29:34.417 11267 11267 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
,03-29 13:29:34.417  3481  3575 I ActivityManager: Start proc 11267:com.samsung.android.securitylogagent/1000 for broadcast-3 com.samsung.android.securitylogagent/.receivers.SeDenialReceiver
,03-29 13:29:34.422 11267 11267 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
,03-29 13:29:34.422 11267 11267 E Zygote  : accessInfo : 0
,03-29 13:29:34.422 11267 11267 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-29 13:29:34.437 11267 11267 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-29 13:29:34.442 11267 11267 D ActivityThread: Added TimaKeyStore provider
,03-29 13:29:34.447  3481  4438 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{26e4223d u0 samsung.intent.action.knox.DENIAL_NOTIFICATION} DELIVERED for app ProcessRecord{9bf5a32 11267:com.samsung.android.securitylogagent/1000}
,03-29 13:29:34.457 11202 11266 W jxcore-log: Platform android
03-29 13:29:34.457 11202 11266 W jxcore-log: 
03-29 13:29:34.457 11202 11266 W jxcore-log: Process ARCH arm
03-29 13:29:34.457 11202 11266 W jxcore-log: 
,03-29 13:29:34.462 11267 11267 D SecurityLogAgent:  SeDenialReceiver : Intent received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,03-29 13:29:34.467 11267 11267 D SecurityLogAgent:  SeDenialReceiver : File path = null
,03-29 13:29:34.467  3481  4718 I ActivityManager: Killing 10173:com.sec.android.app.myfiles/u0a53 (adj 15): emptyCount ##31
,03-29 13:29:34.552 11202 11266 I jxcore-log: JXcore Cordova bridge is ready!
03-29 13:29:34.552 11202 11266 I jxcore-log: 
03-29 13:29:34.552 11202 11266 W jxcore-log: JXcore engine is started
,03-29 13:29:34.557 11202 11259 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-29 13:29:34.562 11202 11202 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-29 13:29:35.917  3481  3693 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/42_task.xml.bak
,03-29 13:29:37.597  3481  6205 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-29 13:29:39.852  3481  3863 E Watchdog: !@Sync 6 [03-29 13:29:39.860]
,03-29 13:29:40.332 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-29 13:29:40.332 11202 11266 I jxcore-log: 
,03-29 13:29:40.337 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-29 13:29:40.337 11202 11266 I jxcore-log: 
,03-29 13:29:40.337 11202 11266 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-29 13:29:40.337 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-29 13:29:40.337 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-29 13:29:40.337 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-29 13:29:40.337 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-29 13:29:40.337 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-29 13:29:40.337 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-29 13:29:40.337 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-29 13:29:40.337 11202 11266 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-29 13:29:40.342 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-29 13:29:40.342 11202 11266 I jxcore-log: 
,03-29 13:29:40.342 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-29 13:29:40.342 11202 11266 I jxcore-log: 
,03-29 13:29:40.662 11202 11266 I jxcore-log: Unit Test app is loaded
03-29 13:29:40.662 11202 11266 I jxcore-log: 
,03-29 13:29:40.667 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-29 13:29:40.667 11202 11266 I jxcore-log: 
,03-29 13:29:40.667 11202 11202 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,03-29 13:29:40.672 11202 11266 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,03-29 13:29:40.672 11202 11266 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
03-29 13:29:40.672 11202 11266 I jxcore-log: 
,03-29 13:29:40.672 11202 11266 I jxcore-log: My device name is: samsung-SM-N910C
03-29 13:29:40.672 11202 11266 I jxcore-log: 
,03-29 13:29:42.272  3481  3511 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-29 13:29:42.272  3481  3511 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-29 13:29:42.272  3481  3511 D BatteryService: online:4, current avg:-94, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-215
03-29 13:29:42.272  3481  3511 D BatteryService: stay LED for fully charged
03-29 13:29:42.272  3481  3481 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-29 13:29:42.272  3481  3481 I MotionRecognitionService: Plugged
03-29 13:29:42.272  3481  3481 D MotionRecognitionService:   cableConnection= 1
03-29 13:29:42.272  3481  3481 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-29 13:29:42.272  3481  3481 D MotionRecognitionService: skip setTransmitPower. 
,03-29 13:29:42.277  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-29 13:29:42.277  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-29 13:29:42.277  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-29 13:29:42.277  5947  5947 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-29 13:29:42.282  5947  6065 D HeadsetStateMachine: Disconnected process message: 10
,03-29 13:29:42.297  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-29 13:29:42.297  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-29 13:29:42.297  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-29 13:29:42.297  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-29 13:29:42.957  3481  3592 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,03-29 13:29:42.962  3481  3592 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,03-29 13:29:42.992  2895  4777 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-29 13:29:43.027 11202 11266 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
03-29 13:29:43.027 11202 11266 I jxcore-log: 
,03-29 13:29:43.232 11202 11266 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
03-29 13:29:43.232 11202 11266 I jxcore-log: 
,03-29 13:29:43.242 11202 11266 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
03-29 13:29:43.242 11202 11266 I jxcore-log: 
,03-29 13:29:43.242 11202 11266 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
03-29 13:29:43.242 11202 11266 I jxcore-log: 
,03-29 13:29:43.262 11202 11266 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
03-29 13:29:43.262 11202 11266 I jxcore-log: 
,03-29 13:29:43.272 11202 11266 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
03-29 13:29:43.272 11202 11266 I jxcore-log: 
,03-29 13:29:43.272 11202 11266 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
03-29 13:29:43.272 11202 11266 I jxcore-log: 
,03-29 13:29:43.792  3481  3586 I PowerManagerService: [PWL] Off : 140s ago
,03-29 13:29:44.067  3481  6174 D SSRM:n  : SIOP:: AP = 310, PST = 280 (W:10), CUR = -94, LCD = 0
,03-29 13:29:44.482 11202 11266 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
03-29 13:29:44.482 11202 11266 I jxcore-log: 
,03-29 13:29:44.492 11202 11266 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
03-29 13:29:44.492 11202 11266 I jxcore-log: 
,03-29 13:29:44.497 11202 11266 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
03-29 13:29:44.497 11202 11266 I jxcore-log: 
,03-29 13:29:44.647 11202 11266 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
03-29 13:29:44.647 11202 11266 I jxcore-log: 
,03-29 13:29:44.687 11202 11266 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
03-29 13:29:44.687 11202 11266 I jxcore-log: 
,03-29 13:29:44.717 11202 11266 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
03-29 13:29:44.717 11202 11266 I jxcore-log: 
,03-29 13:29:44.722 11202 11266 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
03-29 13:29:44.722 11202 11266 I jxcore-log: 
,03-29 13:29:44.727 11202 11266 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
03-29 13:29:44.727 11202 11266 I jxcore-log: 
,03-29 13:29:44.732 11202 11266 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
03-29 13:29:44.732 11202 11266 I jxcore-log: 
,03-29 13:29:44.732 11202 11266 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
03-29 13:29:44.732 11202 11266 I jxcore-log: 
,03-29 13:29:44.742 11202 11266 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
03-29 13:29:44.742 11202 11266 I jxcore-log: 
,03-29 13:29:44.752 11202 11266 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
03-29 13:29:44.752 11202 11266 I jxcore-log: 
,03-29 13:29:44.802 11202 11266 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
03-29 13:29:44.802 11202 11266 I jxcore-log: 
,03-29 13:29:44.807 11202 11266 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
03-29 13:29:44.807 11202 11266 I jxcore-log: 
,03-29 13:29:44.817 11202 11266 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
03-29 13:29:44.817 11202 11266 I jxcore-log: 
,03-29 13:29:52.417  3481  3745 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-29 13:29:52.417  3481  3745 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-29 13:29:52.417  3481  3745 D BatteryService: online:4, current avg:-34, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:51
,03-29 13:29:52.422  3481  3481 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-29 13:29:52.427  3481  3481 I MotionRecognitionService: Plugged
03-29 13:29:52.427  3481  3481 D MotionRecognitionService:   cableConnection= 1,
03-29 13:29:52.427  3481  3481 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
03-29 13:29:52.427  3481  3481 D MotionRecognitionService: skip setTransmitPower. 
,03-29 13:29:52.432  3481  3745 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 12ms,
03-29 13:29:52.432  3481  3745 D BatteryService: stay LED for fully charged,
,03-29 13:29:52.442  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-29 13:29:52.442  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,03-29 13:29:52.442  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-29 13:29:52.462  5947  5947 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-29 13:29:52.467  5947  6065 D HeadsetStateMachine: Disconnected process message: 10
,03-29 13:29:52.477  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-29 13:29:52.477  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-29 13:29:52.477  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-29 13:29:52.477  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-29 13:29:54.087  3481  6174 D SSRM:n  : SIOP:: AP = 290, PST = 278 (W:14), CUR = -34, LCD = 0
,03-29 13:29:54.862 11202 11266 I jxcore-log: TAP version 13
03-29 13:29:54.862 11202 11266 I jxcore-log: 
,03-29 13:29:54.862 11202 11266 I jxcore-log: # setup
03-29 13:29:54.862 11202 11266 I jxcore-log: 
,03-29 13:29:55.147 11202 11266 I jxcore-log: # 1. calling createNativeListener directly rejects
03-29 13:29:55.147 11202 11266 I jxcore-log: 
,03-29 13:29:55.322 11202 11266 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 13:29:55.322 11202 11266 I jxcore-log: 
,03-29 13:29:55.332 11202 11266 I jxcore-log: DEBUG createNativeListener: listening 34933
03-29 13:29:55.332 11202 11266 I jxcore-log: 
,03-29 13:29:55.337 11202 11266 I jxcore-log: ok 1 Should throw
03-29 13:29:55.337 11202 11266 I jxcore-log: 
,03-29 13:29:55.342 11202 11266 I jxcore-log: # teardown
03-29 13:29:55.342 11202 11266 I jxcore-log: 
,03-29 13:29:55.472 11202 11266 I jxcore-log: # setup
03-29 13:29:55.472 11202 11266 I jxcore-log: 
,03-29 13:29:55.647 11202 11266 I jxcore-log: # 2. emits incomingConnectionState
03-29 13:29:55.647 11202 11266 I jxcore-log: 
,03-29 13:29:55.792 11202 11266 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 13:29:55.792 11202 11266 I jxcore-log: 
,03-29 13:29:55.797 11202 11266 I jxcore-log: DEBUG createNativeListener: listening 46931
03-29 13:29:55.797 11202 11266 I jxcore-log: 
,03-29 13:29:55.812 11202 11266 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 13:29:55.812 11202 11266 I jxcore-log: 
,03-29 13:29:55.817 11202 11266 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 13:29:55.817 11202 11266 I jxcore-log: 
,03-29 13:29:55.837 11202 11266 I jxcore-log: DEBUG createNativeListener: new mux
03-29 13:29:55.837 11202 11266 I jxcore-log: 
,03-29 13:29:55.842 11202 11266 I jxcore-log: ok 2 initial connection state should be CONNECTED
03-29 13:29:55.842 11202 11266 I jxcore-log: 
,03-29 13:29:55.862 11202 11266 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 13:29:55.862 11202 11266 I jxcore-log: 
,03-29 13:29:55.867 11202 11266 I jxcore-log: ok 3 final connection state should be DISCONNECTED
03-29 13:29:55.867 11202 11266 I jxcore-log: 
,03-29 13:29:55.877 11202 11266 I jxcore-log: # teardown
03-29 13:29:55.877 11202 11266 I jxcore-log: 
,03-29 13:29:56.002 11202 11266 I jxcore-log: # setup
03-29 13:29:56.002 11202 11266 I jxcore-log: 
,03-29 13:29:56.147 11202 11266 I jxcore-log: # 3. emits routerPortConnectionFailed
03-29 13:29:56.147 11202 11266 I jxcore-log: 
,03-29 13:29:56.227 11202 11266 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 13:29:56.227 11202 11266 I jxcore-log: 
,03-29 13:29:56.232 11202 11266 I jxcore-log: DEBUG createNativeListener: listening 46533
03-29 13:29:56.232 11202 11266 I jxcore-log: 
,03-29 13:29:56.237 11202 11266 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 13:29:56.237 11202 11266 I jxcore-log: 
,03-29 13:29:56.242 11202 11266 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 13:29:56.242 11202 11266 I jxcore-log: 
,03-29 13:29:56.242 11202 11266 I jxcore-log: DEBUG createNativeListener: new mux
03-29 13:29:56.242 11202 11266 I jxcore-log: 
,03-29 13:29:56.277 11202 11266 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:56.277 11202 11266 I jxcore-log: 
,03-29 13:29:56.282 11202 11266 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:56.282 11202 11266 I jxcore-log: 
,03-29 13:29:56.282 11202 11266 I jxcore-log: DEBUG createNativeListener: 
03-29 13:29:56.282 11202 11266 I jxcore-log: 
,03-29 13:29:56.287 11202 11266 I jxcore-log: ok 4 tried to connect to right port
03-29 13:29:56.287 11202 11266 I jxcore-log: 
,03-29 13:29:56.287 11202 11266 I jxcore-log: ok 5 failed due to refused connection
03-29 13:29:56.287 11202 11266 I jxcore-log: 
,03-29 13:29:56.287 11202 11266 I jxcore-log: ok 6 routerPortConnectionFailed is emitted
03-29 13:29:56.287 11202 11266 I jxcore-log: 
,03-29 13:29:56.292 11202 11266 I jxcore-log: # teardown
03-29 13:29:56.292 11202 11266 I jxcore-log: 
,03-29 13:29:56.292 11202 11266 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:56.292 11202 11266 I jxcore-log: 
,03-29 13:29:56.447 11202 11266 I jxcore-log: DEBUG createNativeListener: mux close
03-29 13:29:56.447 11202 11266 I jxcore-log: 
,03-29 13:29:56.457 11202 11266 I jxcore-log: # setup
03-29 13:29:56.457 11202 11266 I jxcore-log: 
,03-29 13:29:56.462 11202 11266 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 13:29:56.462 11202 11266 I jxcore-log: 
,03-29 13:29:56.607 11202 11266 I jxcore-log: # 4. native server connections all up
03-29 13:29:56.607 11202 11266 I jxcore-log: 
,03-29 13:29:56.697 11202 11266 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 13:29:56.697 11202 11266 I jxcore-log: 
,03-29 13:29:56.702 11202 11266 I jxcore-log: DEBUG createNativeListener: listening 56624
03-29 13:29:56.702 11202 11266 I jxcore-log: 
,03-29 13:29:56.717 11202 11266 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 13:29:56.717 11202 11266 I jxcore-log: 
,03-29 13:29:56.717 11202 11266 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 13:29:56.717 11202 11266 I jxcore-log: 
,03-29 13:29:56.722 11202 11266 I jxcore-log: DEBUG createNativeListener: new mux
03-29 13:29:56.722 11202 11266 I jxcore-log: 
,03-29 13:29:56.772 11202 11266 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:56.772 11202 11266 I jxcore-log: 
,03-29 13:29:56.777 11202 11266 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:56.777 11202 11266 I jxcore-log: 
,03-29 13:29:56.787 11202 11266 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:56.787 11202 11266 I jxcore-log: 
,03-29 13:29:56.792 11202 11266 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:56.792 11202 11266 I jxcore-log: 
,03-29 13:29:56.832 11202 11266 I jxcore-log: ok 7 Send/recvd #1 should be equal length
03-29 13:29:56.832 11202 11266 I jxcore-log: 
,03-29 13:29:56.837 11202 11266 I jxcore-log: ok 8 Send/recvd #1 should be same
03-29 13:29:56.837 11202 11266 I jxcore-log: 
,03-29 13:29:56.837 11202 11266 I jxcore-log: ok 9 Send/recvd #2 should be equal length
03-29 13:29:56.837 11202 11266 I jxcore-log: 
,03-29 13:29:56.842 11202 11266 I jxcore-log: ok 10 Send/recvd #2 should be same
03-29 13:29:56.842 11202 11266 I jxcore-log: 
,03-29 13:29:56.852 11202 11266 I jxcore-log: ok 11 Should be exactly 2 client sockets
03-29 13:29:56.852 11202 11266 I jxcore-log: 
,03-29 13:29:56.862 11202 11266 I jxcore-log: # teardown
03-29 13:29:56.862 11202 11266 I jxcore-log: 
,03-29 13:29:56.997 11202 11266 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:56.997 11202 11266 I jxcore-log: 
,03-29 13:29:57.002 11202 11266 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:57.002 11202 11266 I jxcore-log: 
,03-29 13:29:57.012 11202 11266 I jxcore-log: DEBUG createNativeListener: mux close
03-29 13:29:57.012 11202 11266 I jxcore-log: 
,03-29 13:29:57.017 11202 11266 I jxcore-log: # setup
03-29 13:29:57.017 11202 11266 I jxcore-log: 
,03-29 13:29:57.017 11202 11266 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 13:29:57.017 11202 11266 I jxcore-log: 
,03-29 13:29:57.112 11202 11266 I jxcore-log: # 5. native server - closing incoming stream cleans outgoing socket
03-29 13:29:57.112 11202 11266 I jxcore-log: 
,03-29 13:29:57.262 11202 11266 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 13:29:57.262 11202 11266 I jxcore-log: 
,03-29 13:29:57.267 11202 11266 I jxcore-log: DEBUG createNativeListener: listening 46244
03-29 13:29:57.267 11202 11266 I jxcore-log: 
,03-29 13:29:57.277 11202 11266 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 13:29:57.277 11202 11266 I jxcore-log: 
,03-29 13:29:57.282 11202 11266 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 13:29:57.282 11202 11266 I jxcore-log: 
,03-29 13:29:57.282 11202 11266 I jxcore-log: DEBUG createNativeListener: new mux
03-29 13:29:57.282 11202 11266 I jxcore-log: 
,03-29 13:29:57.297 11202 11266 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:57.297 11202 11266 I jxcore-log: 
,03-29 13:29:57.302 11202 11266 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:57.302 11202 11266 I jxcore-log: 
,03-29 13:29:57.322 11202 11266 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:57.322 11202 11266 I jxcore-log: 
,03-29 13:29:57.337 11202 11266 I jxcore-log: ok 12 socket shouldn't close until after stream
03-29 13:29:57.337 11202 11266 I jxcore-log: 
,03-29 13:29:57.337 11202 11266 I jxcore-log: ok 13 incoming remains open
03-29 13:29:57.337 11202 11266 I jxcore-log: 
,03-29 13:29:57.347 11202 11266 I jxcore-log: # teardown
03-29 13:29:57.347 11202 11266 I jxcore-log: 
,03-29 13:29:57.512 11202 11266 I jxcore-log: DEBUG createNativeListener: mux close
03-29 13:29:57.512 11202 11266 I jxcore-log: 
,03-29 13:29:57.522 11202 11266 I jxcore-log: # setup
03-29 13:29:57.522 11202 11266 I jxcore-log: 
,03-29 13:29:57.527 11202 11266 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 13:29:57.527 11202 11266 I jxcore-log: 
,03-29 13:29:57.597  3481  6205 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-29 13:29:57.702 11202 11266 I jxcore-log: # 6. native server - closing incoming connection cleans outgoing socket
03-29 13:29:57.702 11202 11266 I jxcore-log: 
,03-29 13:29:57.832 11202 11266 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 13:29:57.832 11202 11266 I jxcore-log: 
,03-29 13:29:57.837 11202 11266 I jxcore-log: DEBUG createNativeListener: listening 34473
03-29 13:29:57.837 11202 11266 I jxcore-log: 
,03-29 13:29:57.847 11202 11266 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 13:29:57.847 11202 11266 I jxcore-log: 
,03-29 13:29:57.852 11202 11266 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 13:29:57.852 11202 11266 I jxcore-log: 
,03-29 13:29:57.852 11202 11266 I jxcore-log: DEBUG createNativeListener: new mux
03-29 13:29:57.852 11202 11266 I jxcore-log: 
,03-29 13:29:57.867 11202 11266 I jxcore-log: ok 14 we should not have gotten an error
03-29 13:29:57.867 11202 11266 I jxcore-log: 
,03-29 13:29:57.872 11202 11266 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:57.872 11202 11266 I jxcore-log: 
,03-29 13:29:57.877 11202 11266 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:57.877 11202 11266 I jxcore-log: 
,03-29 13:29:57.897 11202 11266 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:57.897 11202 11266 I jxcore-log: 
,03-29 13:29:57.897 11202 11266 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 13:29:57.897 11202 11266 I jxcore-log: 
,03-29 13:29:57.907 11202 11266 I jxcore-log: ok 15 socket shouldn't close until after incoming
03-29 13:29:57.907 11202 11266 I jxcore-log: 
,03-29 13:29:57.907 11202 11266 I jxcore-log: ok 16 incoming is cleaned up
03-29 13:29:57.907 11202 11266 I jxcore-log: 
,03-29 13:29:57.917 11202 11266 I jxcore-log: # teardown
03-29 13:29:57.917 11202 11266 I jxcore-log: 
,03-29 13:29:58.037 11202 11266 I jxcore-log: # setup,
03-29 13:29:58.037 11202 11266 I jxcore-log: 
,03-29 13:29:58.212 11202 11266 I jxcore-log: # 7. native server - closing outgoing socket cleans associated mux stream
03-29 13:29:58.212 11202 11266 I jxcore-log: 
,03-29 13:29:58.327 11202 11266 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 13:29:58.327 11202 11266 I jxcore-log: 
,03-29 13:29:58.332 11202 11266 I jxcore-log: DEBUG createNativeListener: listening 60035
03-29 13:29:58.332 11202 11266 I jxcore-log: 
,03-29 13:29:58.342 11202 11266 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 13:29:58.342 11202 11266 I jxcore-log: 
,03-29 13:29:58.347 11202 11266 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 13:29:58.347 11202 11266 I jxcore-log: 
,03-29 13:29:58.347 11202 11266 I jxcore-log: DEBUG createNativeListener: new mux
03-29 13:29:58.347 11202 11266 I jxcore-log: 
,03-29 13:29:58.367 11202 11266 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:58.367 11202 11266 I jxcore-log: 
,03-29 13:29:58.367 11202 11266 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:58.367 11202 11266 I jxcore-log: 
,03-29 13:29:58.387 11202 11266 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:58.387 11202 11266 I jxcore-log: 
,03-29 13:29:58.397 11202 11266 I jxcore-log: ok 17 stream was closed
03-29 13:29:58.397 11202 11266 I jxcore-log: 
,03-29 13:29:58.402 11202 11266 I jxcore-log: ok 18 incoming should survive
03-29 13:29:58.402 11202 11266 I jxcore-log: 
,03-29 13:29:58.402 11202 11266 I jxcore-log: ok 19 mux should have no streams
03-29 13:29:58.402 11202 11266 I jxcore-log: 
,03-29 13:29:58.412 11202 11266 I jxcore-log: # teardown
03-29 13:29:58.412 11202 11266 I jxcore-log: 
,03-29 13:29:58.477 11202 11266 I jxcore-log: DEBUG createNativeListener: mux close
03-29 13:29:58.477 11202 11266 I jxcore-log: 
,03-29 13:29:58.482 11202 11266 I jxcore-log: # setup
03-29 13:29:58.482 11202 11266 I jxcore-log: 
,03-29 13:29:58.482 11202 11266 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 13:29:58.482 11202 11266 I jxcore-log: 
,03-29 13:29:58.687 11202 11266 I jxcore-log: # 8. native server - closing the whole server cleans everything up
03-29 13:29:58.687 11202 11266 I jxcore-log: 
,03-29 13:29:58.852 11202 11266 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 13:29:58.852 11202 11266 I jxcore-log: 
,03-29 13:29:58.857 11202 11266 I jxcore-log: DEBUG createNativeListener: listening 55563
03-29 13:29:58.857 11202 11266 I jxcore-log: 
,03-29 13:29:58.867 11202 11266 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 13:29:58.867 11202 11266 I jxcore-log: 
,03-29 13:29:58.872 11202 11266 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 13:29:58.872 11202 11266 I jxcore-log: 
,03-29 13:29:58.872 11202 11266 I jxcore-log: DEBUG createNativeListener: new mux
03-29 13:29:58.872 11202 11266 I jxcore-log: 
,03-29 13:29:58.887 11202 11266 I jxcore-log: ok 20 we should not have gotten an error
03-29 13:29:58.887 11202 11266 I jxcore-log: 
,03-29 13:29:58.892 11202 11266 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:58.892 11202 11266 I jxcore-log: 
,03-29 13:29:58.897 11202 11266 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:58.897 11202 11266 I jxcore-log: 
,03-29 13:29:58.912 11202 11266 I jxcore-log: ok 21 Buffers are identical
03-29 13:29:58.912 11202 11266 I jxcore-log: 
,03-29 13:29:58.912 11202 11266 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:58.912 11202 11266 I jxcore-log: 
,03-29 13:29:58.917 11202 11266 I jxcore-log: DEBUG createNativeListener: mux close
03-29 13:29:58.917 11202 11266 I jxcore-log: 
,03-29 13:29:58.922 11202 11266 I jxcore-log: ok 22 native server is nulled out
03-29 13:29:58.922 11202 11266 I jxcore-log: 
,03-29 13:29:58.922 11202 11266 I jxcore-log: ok 23 native server should be closed
03-29 13:29:58.922 11202 11266 I jxcore-log: 
,03-29 13:29:58.927 11202 11266 I jxcore-log: ok 24 incoming has been removed
03-29 13:29:58.927 11202 11266 I jxcore-log: 
03-29 13:29:58.927 11202 11266 I jxcore-log: ok 25 Incoming should be done
03-29 13:29:58.927 11202 11266 I jxcore-log: 
,03-29 13:29:58.927 11202 11266 I jxcore-log: ok 26 The mux object should be closed
03-29 13:29:58.927 11202 11266 I jxcore-log: 
,03-29 13:29:58.927 11202 11266 I jxcore-log: ok 27 The mux stream should be closed
03-29 13:29:58.927 11202 11266 I jxcore-log: 
,03-29 13:29:58.927 11202 11266 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 13:29:58.927 11202 11266 I jxcore-log: 
,03-29 13:29:58.947 11202 11266 I jxcore-log: # teardown
03-29 13:29:58.947 11202 11266 I jxcore-log: 
,03-29 13:29:59.107 11202 11266 I jxcore-log: # setup,
03-29 13:29:59.107 11202 11266 I jxcore-log: 
,03-29 13:29:59.272 11202 11266 I jxcore-log: # 9. native server - we can get a ton of connections and data through and still clean up the server completely
03-29 13:29:59.272 11202 11266 I jxcore-log: 
,03-29 13:29:59.492 11202 11266 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 13:29:59.492 11202 11266 I jxcore-log: 
,03-29 13:29:59.497 11202 11266 I jxcore-log: DEBUG createNativeListener: listening 51972
03-29 13:29:59.497 11202 11266 I jxcore-log: 
,03-29 13:29:59.527 11202 11266 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 13:29:59.527 11202 11266 I jxcore-log: 
,03-29 13:29:59.527 11202 11266 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 13:29:59.527 11202 11266 I jxcore-log: 
,03-29 13:29:59.532 11202 11266 I jxcore-log: DEBUG createNativeListener: new mux
03-29 13:29:59.532 11202 11266 I jxcore-log: 
,03-29 13:29:59.532 11202 11266 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 13:29:59.532 11202 11266 I jxcore-log: 
,03-29 13:29:59.537 11202 11266 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 13:29:59.537 11202 11266 I jxcore-log: 
,03-29 13:29:59.537 11202 11266 I jxcore-log: DEBUG createNativeListener: new mux
03-29 13:29:59.537 11202 11266 I jxcore-log: 
,03-29 13:29:59.542 11202 11266 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 13:29:59.542 11202 11266 I jxcore-log: 
,03-29 13:29:59.547 11202 11266 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 13:29:59.547 11202 11266 I jxcore-log: 
,03-29 13:29:59.547 11202 11266 I jxcore-log: DEBUG createNativeListener: new mux
03-29 13:29:59.547 11202 11266 I jxcore-log: 
,03-29 13:29:59.552 11202 11266 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 13:29:59.552 11202 11266 I jxcore-log: 
,03-29 13:29:59.557 11202 11266 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 13:29:59.557 11202 11266 I jxcore-log: 
,03-29 13:29:59.557 11202 11266 I jxcore-log: DEBUG createNativeListener: new mux
03-29 13:29:59.557 11202 11266 I jxcore-log: 
,03-29 13:29:59.567 11202 11266 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 13:29:59.567 11202 11266 I jxcore-log: 
,03-29 13:29:59.572 11202 11266 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 13:29:59.572 11202 11266 I jxcore-log: 
,03-29 13:29:59.572 11202 11266 I jxcore-log: DEBUG createNativeListener: new mux
03-29 13:29:59.572 11202 11266 I jxcore-log: 
,03-29 13:29:59.577 11202 11266 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 13:29:59.577 11202 11266 I jxcore-log: 
,03-29 13:29:59.577 11202 11266 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 13:29:59.577 11202 11266 I jxcore-log: 
,03-29 13:29:59.577 11202 11266 I jxcore-log: DEBUG createNativeListener: new mux
03-29 13:29:59.577 11202 11266 I jxcore-log: 
,03-29 13:29:59.582 11202 11266 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 13:29:59.582 11202 11266 I jxcore-log: 
,03-29 13:29:59.582 11202 11266 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 13:29:59.582 11202 11266 I jxcore-log: 
,03-29 13:29:59.587 11202 11266 I jxcore-log: DEBUG createNativeListener: new mux
03-29 13:29:59.587 11202 11266 I jxcore-log: 
,03-29 13:29:59.587 11202 11266 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 13:29:59.587 11202 11266 I jxcore-log: 
,03-29 13:29:59.587 11202 11266 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 13:29:59.587 11202 11266 I jxcore-log: 
,03-29 13:29:59.592 11202 11266 I jxcore-log: DEBUG createNativeListener: new mux
03-29 13:29:59.592 11202 11266 I jxcore-log: 
,03-29 13:29:59.592 11202 11266 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 13:29:59.592 11202 11266 I jxcore-log: 
,03-29 13:29:59.597 11202 11266 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 13:29:59.597 11202 11266 I jxcore-log: 
,03-29 13:29:59.597 11202 11266 I jxcore-log: DEBUG createNativeListener: new mux
03-29 13:29:59.597 11202 11266 I jxcore-log: 
,03-29 13:29:59.602 11202 11266 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 13:29:59.602 11202 11266 I jxcore-log: 
,03-29 13:29:59.602 11202 11266 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 13:29:59.602 11202 11266 I jxcore-log: 
,03-29 13:29:59.602 11202 11266 I jxcore-log: DEBUG createNativeListener: new mux
03-29 13:29:59.602 11202 11266 I jxcore-log: 
,03-29 13:29:59.727 11202 11266 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:59.727 11202 11266 I jxcore-log: 
,03-29 13:29:59.727 11202 11266 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:59.727 11202 11266 I jxcore-log: 
,03-29 13:29:59.732 11202 11266 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:59.732 11202 11266 I jxcore-log: 
,03-29 13:29:59.732 11202 11266 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:59.732 11202 11266 I jxcore-log: 
,03-29 13:29:59.732 11202 11266 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:59.732 11202 11266 I jxcore-log: 
,03-29 13:29:59.737 11202 11266 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:59.737 11202 11266 I jxcore-log: 
,03-29 13:29:59.737 11202 11266 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:59.737 11202 11266 I jxcore-log: 
,03-29 13:29:59.742 11202 11266 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:59.742 11202 11266 I jxcore-log: 
,03-29 13:29:59.742 11202 11266 I jxcore-log: DEBUG createNativeListener: new stream: 
,03-29 13:29:59.742 11202 11266 I jxcore-log: 
03-29 13:29:59.742 11202 11266 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:59.742 11202 11266 I jxcore-log: 
,03-29 13:29:59.742 11202 11266 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:59.742 11202 11266 I jxcore-log: 
,03-29 13:29:59.747 11202 11266 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:59.747 11202 11266 I jxcore-log: 
,03-29 13:29:59.747 11202 11266 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:59.747 11202 11266 I jxcore-log: 
,03-29 13:29:59.747 11202 11266 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:59.747 11202 11266 I jxcore-log: 
,03-29 13:29:59.747 11202 11266 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:59.747 11202 11266 I jxcore-log: 
,03-29 13:29:59.752 11202 11266 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:59.752 11202 11266 I jxcore-log: 
,03-29 13:29:59.752 11202 11266 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:59.752 11202 11266 I jxcore-log: 
,03-29 13:29:59.757 11202 11266 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:59.757 11202 11266 I jxcore-log: 
,03-29 13:29:59.757 11202 11266 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:59.757 11202 11266 I jxcore-log: ,
,03-29 13:29:59.757 11202 11266 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:59.757 11202 11266 I jxcore-log: 
,03-29 13:29:59.762 11202 11266 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:59.762 11202 11266 I jxcore-log: 
,03-29 13:29:59.762 11202 11266 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:59.762 11202 11266 I jxcore-log: 
,03-29 13:29:59.767 11202 11266 I jxcore-log: DEBUG createNativeListener: new stream: 
,03-29 13:29:59.767 11202 11266 I jxcore-log: 
,03-29 13:29:59.767 11202 11266 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:59.767 11202 11266 I jxcore-log: 
,03-29 13:29:59.767 11202 11266 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:59.767 11202 11266 I jxcore-log: 
,03-29 13:29:59.772 11202 11266 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:59.772 11202 11266 I jxcore-log: 
,03-29 13:29:59.772 11202 11266 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:59.772 11202 11266 I jxcore-log: 
,03-29 13:29:59.772 11202 11266 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:59.772 11202 11266 I jxcore-log: 
,03-29 13:29:59.772 11202 11266 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:59.772 11202 11266 I jxcore-log: 
,03-29 13:29:59.777 11202 11266 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:59.777 11202 11266 I jxcore-log: 
,03-29 13:29:59.777 11202 11266 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:59.777 11202 11266 I jxcore-log: 
,03-29 13:29:59.777 11202 11266 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:59.777 11202 11266 I jxcore-log: 
,03-29 13:29:59.782 11202 11266 I jxcore-log: DEBUG createNativeListener: new stream: ,
03-29 13:29:59.782 11202 11266 I jxcore-log: 
,03-29 13:29:59.782 11202 11266 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:59.782 11202 11266 I jxcore-log: 
,03-29 13:29:59.782 11202 11266 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:59.782 11202 11266 I jxcore-log: 
,03-29 13:29:59.782 11202 11266 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:59.782 11202 11266 I jxcore-log: 
,03-29 13:29:59.787 11202 11266 I jxcore-log: DEBUG createNativeListener: new stream: ,
03-29 13:29:59.787 11202 11266 I jxcore-log: 
,03-29 13:29:59.787 11202 11266 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:59.787 11202 11266 I jxcore-log: 
,03-29 13:29:59.787 11202 11266 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:59.787 11202 11266 I jxcore-log: 
,03-29 13:29:59.787 11202 11266 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:59.787 11202 11266 I jxcore-log: 
,03-29 13:29:59.792 11202 11266 I jxcore-log: DEBUG createNativeListener: new stream: ,
03-29 13:29:59.792 11202 11266 I jxcore-log: 
,03-29 13:29:59.792 11202 11266 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:59.792 11202 11266 I jxcore-log: 
,03-29 13:29:59.792 11202 11266 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:59.792 11202 11266 I jxcore-log: 
,03-29 13:29:59.797 11202 11266 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:59.797 11202 11266 I jxcore-log: 
,03-29 13:29:59.797 11202 11266 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:59.797 11202 11266 I jxcore-log: 
,03-29 13:29:59.797 11202 11266 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:59.797 11202 11266 I jxcore-log: 
,03-29 13:29:59.797 11202 11266 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:59.797 11202 11266 I jxcore-log: 
,03-29 13:29:59.802 11202 11266 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:59.802 11202 11266 I jxcore-log: 
,03-29 13:29:59.812 11202 11266 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:59.812 11202 11266 I jxcore-log: 
,03-29 13:29:59.812 11202 11266 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:59.812 11202 11266 I jxcore-log: 
,03-29 13:29:59.812 11202 11266 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:59.812 11202 11266 I jxcore-log: 
,03-29 13:29:59.817 11202 11266 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:59.817 11202 11266 I jxcore-log: 
,03-29 13:29:59.817 11202 11266 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:59.817 11202 11266 I jxcore-log: 
,03-29 13:29:59.817 11202 11266 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:59.817 11202 11266 I jxcore-log: 
,03-29 13:29:59.817 11202 11266 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:59.817 11202 11266 I jxcore-log: 
,03-29 13:29:59.822 11202 11266 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:59.822 11202 11266 I jxcore-log: 
,03-29 13:29:59.822 11202 11266 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:59.822 11202 11266 I jxcore-log: 
,03-29 13:29:59.827 11202 11266 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:59.827 11202 11266 I jxcore-log: 
,03-29 13:29:59.827 11202 11266 I jxcore-log: DEBUG createNativeListener: new stream: 
,03-29 13:29:59.827 11202 11266 I jxcore-log: 
03-29 13:29:59.827 11202 11266 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:59.827 11202 11266 I jxcore-log: 
,03-29 13:29:59.827 11202 11266 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:59.827 11202 11266 I jxcore-log: 
,03-29 13:29:59.827 11202 11266 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:59.827 11202 11266 I jxcore-log: 
,03-29 13:29:59.832 11202 11266 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:59.832 11202 11266 I jxcore-log: 
,03-29 13:29:59.832 11202 11266 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:59.832 11202 11266 I jxcore-log: 
,03-29 13:29:59.832 11202 11266 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:59.832 11202 11266 I jxcore-log: 
,03-29 13:29:59.832 11202 11266 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:59.832 11202 11266 I jxcore-log: 
,03-29 13:29:59.837 11202 11266 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:59.837 11202 11266 I jxcore-log: 
,03-29 13:29:59.837 11202 11266 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:59.837 11202 11266 I jxcore-log: 
,03-29 13:29:59.837 11202 11266 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:59.837 11202 11266 I jxcore-log: 
,03-29 13:29:59.837 11202 11266 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:59.837 11202 11266 I jxcore-log: 
,03-29 13:29:59.837 11202 11266 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:59.837 11202 11266 I jxcore-log: ,
,03-29 13:29:59.842 11202 11266 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:59.842 11202 11266 I jxcore-log: 
,03-29 13:29:59.842 11202 11266 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:59.842 11202 11266 I jxcore-log: 
,03-29 13:29:59.842 11202 11266 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:59.842 11202 11266 I jxcore-log: 
,03-29 13:29:59.842 11202 11266 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:59.842 11202 11266 I jxcore-log: 
,03-29 13:29:59.847 11202 11266 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:59.847 11202 11266 I jxcore-log: 
,03-29 13:29:59.847 11202 11266 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:59.847 11202 11266 I jxcore-log: 
,03-29 13:29:59.847 11202 11266 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:59.847 11202 11266 I jxcore-log: 
,03-29 13:29:59.847 11202 11266 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:59.847 11202 11266 I jxcore-log: 
,03-29 13:29:59.847 11202 11266 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:59.847 11202 11266 I jxcore-log: 
,03-29 13:29:59.907 11202 11266 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:59.907 11202 11266 I jxcore-log: 
,03-29 13:29:59.907 11202 11266 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:59.907 11202 11266 I jxcore-log: 
,03-29 13:29:59.907 11202 11266 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:59.907 11202 11266 I jxcore-log: 
,03-29 13:29:59.912 11202 11266 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:59.912 11202 11266 I jxcore-log: 
,03-29 13:29:59.912 11202 11266 I jxcore-log: DEBUG createNativeListener: mux close
03-29 13:29:59.912 11202 11266 I jxcore-log: 
,03-29 13:29:59.912 11202 11266 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:59.912 11202 11266 I jxcore-log: 
03-29 13:29:59.912 11202 11266 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:59.912 11202 11266 I jxcore-log: 
,03-29 13:29:59.912 11202 11266 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:59.912 11202 11266 I jxcore-log: 
03-29 13:29:59.912 11202 11266 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:59.912 11202 11266 I jxcore-log: 
,03-29 13:29:59.917 11202 11266 I jxcore-log: DEBUG createNativeListener: mux close
03-29 13:29:59.917 11202 11266 I jxcore-log: 
,03-29 13:29:59.917 11202 11266 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:59.917 11202 11266 I jxcore-log: 
,03-29 13:29:59.917 11202 11266 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:59.917 11202 11266 I jxcore-log: 
,03-29 13:29:59.917 11202 11266 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:59.917 11202 11266 I jxcore-log: 
03-29 13:29:59.917 11202 11266 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:59.917 11202 11266 I jxcore-log: 
,03-29 13:29:59.917 11202 11266 I jxcore-log: DEBUG createNativeListener: mux close
03-29 13:29:59.917 11202 11266 I jxcore-log: 
,03-29 13:29:59.922 11202 11266 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:59.922 11202 11266 I jxcore-log: 
,03-29 13:29:59.922 11202 11266 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:59.922 11202 11266 I jxcore-log: 
03-29 13:29:59.922 11202 11266 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:59.922 11202 11266 I jxcore-log: 
,03-29 13:29:59.922 11202 11266 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:59.922 11202 11266 I jxcore-log: 
,03-29 13:29:59.922 11202 11266 I jxcore-log: DEBUG createNativeListener: mux close
03-29 13:29:59.922 11202 11266 I jxcore-log: 
03-29 13:29:59.922 11202 11266 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:59.922 11202 11266 I jxcore-log: 
,03-29 13:29:59.922 11202 11266 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:59.922 11202 11266 I jxcore-log: 
03-29 13:29:59.922 11202 11266 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:59.922 11202 11266 I jxcore-log: 
,03-29 13:29:59.922 11202 11266 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:59.922 11202 11266 I jxcore-log: 
,03-29 13:29:59.927 11202 11266 I jxcore-log: DEBUG createNativeListener: mux close
03-29 13:29:59.927 11202 11266 I jxcore-log: 
03-29 13:29:59.927 11202 11266 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:59.927 11202 11266 I jxcore-log: 
,03-29 13:29:59.927 11202 11266 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:59.927 11202 11266 I jxcore-log: 
03-29 13:29:59.927 11202 11266 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:59.927 11202 11266 I jxcore-log: 
,03-29 13:29:59.927 11202 11266 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:59.927 11202 11266 I jxcore-log: 
,03-29 13:29:59.927 11202 11266 I jxcore-log: DEBUG createNativeListener: mux close
03-29 13:29:59.927 11202 11266 I jxcore-log: 
,03-29 13:29:59.927 11202 11266 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:59.927 11202 11266 I jxcore-log: 
03-29 13:29:59.927 11202 11266 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:59.927 11202 11266 I jxcore-log: 
,03-29 13:29:59.932 11202 11266 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:59.932 11202 11266 I jxcore-log: 
03-29 13:29:59.932 11202 11266 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:59.932 11202 11266 I jxcore-log: 
,03-29 13:29:59.932 11202 11266 I jxcore-log: DEBUG createNativeListener: mux close
03-29 13:29:59.932 11202 11266 I jxcore-log: 
,03-29 13:29:59.932 11202 11266 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:59.932 11202 11266 I jxcore-log: 
03-29 13:29:59.932 11202 11266 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:59.932 11202 11266 I jxcore-log: 
,03-29 13:29:59.932 11202 11266 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:59.932 11202 11266 I jxcore-log: 
,03-29 13:29:59.932 11202 11266 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:59.932 11202 11266 I jxcore-log: 
03-29 13:29:59.932 11202 11266 I jxcore-log: DEBUG createNativeListener: mux close
03-29 13:29:59.932 11202 11266 I jxcore-log: 
,03-29 13:29:59.932 11202 11266 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:59.932 11202 11266 I jxcore-log: 
,03-29 13:29:59.932 11202 11266 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:59.932 11202 11266 I jxcore-log: 
03-29 13:29:59.937 11202 11266 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:59.937 11202 11266 I jxcore-log: 
,03-29 13:29:59.937 11202 11266 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:59.937 11202 11266 I jxcore-log: 
03-29 13:29:59.937 11202 11266 I jxcore-log: DEBUG createNativeListener: mux close
03-29 13:29:59.937 11202 11266 I jxcore-log: 
,03-29 13:29:59.937 11202 11266 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:59.937 11202 11266 I jxcore-log: 
03-29 13:29:59.937 11202 11266 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:59.937 11202 11266 I jxcore-log: 
,03-29 13:29:59.937 11202 11266 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:59.937 11202 11266 I jxcore-log: 
03-29 13:29:59.937 11202 11266 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:59.937 11202 11266 I jxcore-log: 
,03-29 13:29:59.937 11202 11266 I jxcore-log: DEBUG createNativeListener: mux close
03-29 13:29:59.937 11202 11266 I jxcore-log: 
,03-29 13:29:59.942 11202 11266 I jxcore-log: ok 28 native server is nulled out
03-29 13:29:59.942 11202 11266 I jxcore-log: 
,03-29 13:29:59.942 11202 11266 I jxcore-log: ok 29 native server should be closed
03-29 13:29:59.942 11202 11266 I jxcore-log: 
03-29 13:29:59.942 11202 11266 I jxcore-log: ok 30 incoming has been removed
03-29 13:29:59.942 11202 11266 I jxcore-log: 
03-29 13:29:59.942 11202 11266 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 13:29:59.942 11202 11266 I jxcore-log: 
,03-29 13:29:59.942 11202 11266 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 13:29:59.942 11202 11266 I jxcore-log: 
03-29 13:29:59.942 11202 11266 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 13:29:59.942 11202 11266 I jxcore-log: 
,03-29 13:29:59.942 11202 11266 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 13:29:59.942 11202 11266 I jxcore-log: 
03-29 13:29:59.942 11202 11266 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 13:29:59.942 11202 11266 I jxcore-log: 
03-29 13:29:59.942 11202 11266 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 13:29:59.942 11202 11266 I jxcore-log: 
,03-29 13:29:59.942 11202 11266 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 13:29:59.942 11202 11266 I jxcore-log: 
03-29 13:29:59.947 11202 11266 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 13:29:59.947 11202 11266 I jxcore-log: 
03-29 13:29:59.947 11202 11266 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 13:29:59.947 11202 11266 I jxcore-log: 
,03-29 13:29:59.947 11202 11266 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 13:29:59.947 11202 11266 I jxcore-log: 
,03-29 13:29:59.992  3481  3619 V AlarmManager: waitForAlarm result :8
,03-29 13:30:00.027 11202 11266 I jxcore-log: # teardown
03-29 13:30:00.027 11202 11266 I jxcore-log: 
,03-29 13:30:00.142 11202 11266 I jxcore-log: # setup
03-29 13:30:00.142 11202 11266 I jxcore-log: 
,03-29 13:30:02.552  3481  4438 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-29 13:30:02.552  3481  4438 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-29 13:30:02.552  3481  4438 D BatteryService: online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:53
,03-29 13:30:02.557  3481  3481 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-29 13:30:02.557  3481  4438 D BatteryService: stay LED for fully charged,
,03-29 13:30:02.567  3481  3481 I MotionRecognitionService: Plugged
03-29 13:30:02.567  3481  3481 D MotionRecognitionService:   cableConnection= 1,
,03-29 13:30:02.567  3481  3481 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
03-29 13:30:02.567  3481  3481 D MotionRecognitionService: skip setTransmitPower. 
,03-29 13:30:02.577  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-29 13:30:02.577  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,03-29 13:30:02.577  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-29 13:30:02.602  5947  5947 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-29 13:30:02.602  5947  6065 D HeadsetStateMachine: Disconnected process message: 10
,03-29 13:30:02.612  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-29 13:30:02.612  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-29 13:30:02.612  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-29 13:30:02.612  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-29 13:30:03.487 11202 11266 I jxcore-log: # 10. native server - simulate mux failure, make sure everything is cleaned up
03-29 13:30:03.487 11202 11266 I jxcore-log: 
,03-29 13:30:03.662 11202 11266 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 13:30:03.662 11202 11266 I jxcore-log: 
,03-29 13:30:03.677 11202 11266 I jxcore-log: DEBUG createNativeListener: listening 34830
03-29 13:30:03.677 11202 11266 I jxcore-log: 
,03-29 13:30:03.687 11202 11266 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 13:30:03.687 11202 11266 I jxcore-log: 
,03-29 13:30:03.692 11202 11266 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 13:30:03.692 11202 11266 I jxcore-log: 
,03-29 13:30:03.692 11202 11266 I jxcore-log: DEBUG createNativeListener: new mux
03-29 13:30:03.692 11202 11266 I jxcore-log: 
,03-29 13:30:03.702 11202 11266 I jxcore-log: ok 31 we should not have gotten an error
03-29 13:30:03.702 11202 11266 I jxcore-log: 
,03-29 13:30:03.707 11202 11266 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:30:03.707 11202 11266 I jxcore-log: 
,03-29 13:30:03.712 11202 11266 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:30:03.712 11202 11266 I jxcore-log: 
,03-29 13:30:03.722 11202 11266 I jxcore-log: ok 32 Buffers are identical
03-29 13:30:03.722 11202 11266 I jxcore-log: 
,03-29 13:30:03.727 11202 11266 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:30:03.727 11202 11266 I jxcore-log: 
,03-29 13:30:03.727 11202 11266 I jxcore-log: DEBUG createNativeListener: mux close
03-29 13:30:03.727 11202 11266 I jxcore-log: 
,03-29 13:30:03.742 11202 11266 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 13:30:03.742 11202 11266 I jxcore-log: 
,03-29 13:30:03.747 11202 11266 I jxcore-log: ok 33 server should be fine
03-29 13:30:03.747 11202 11266 I jxcore-log: 
,03-29 13:30:03.747 11202 11266 I jxcore-log: ok 34 server should be open
03-29 13:30:03.747 11202 11266 I jxcore-log: 
,03-29 13:30:03.747 11202 11266 I jxcore-log: ok 35 incoming has been removed
03-29 13:30:03.747 11202 11266 I jxcore-log: 
,03-29 13:30:03.752 11202 11266 I jxcore-log: ok 36 The mux object should be closed
03-29 13:30:03.752 11202 11266 I jxcore-log: 
,03-29 13:30:03.752 11202 11266 I jxcore-log: ok 37 The mux stream should be closed
03-29 13:30:03.752 11202 11266 I jxcore-log: 
,03-29 13:30:03.762 11202 11266 I jxcore-log: # teardown
03-29 13:30:03.762 11202 11266 I jxcore-log: 
,03-29 13:30:04.117  3481  6174 D SSRM:n  : SIOP:: AP = 290, PST = 282 (W:14), CUR = 17, LCD = 0,
,03-29 13:30:04.312 11202 11266 I jxcore-log: # setup
03-29 13:30:04.312 11202 11266 I jxcore-log: 
,03-29 13:30:04.417 11202 11266 I jxcore-log: # 11. native server - timing out the incoming connection cleans everything up
03-29 13:30:04.417 11202 11266 I jxcore-log: 
,03-29 13:30:04.752 11202 11266 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 13:30:04.752 11202 11266 I jxcore-log: 
,03-29 13:30:04.757 11202 11266 I jxcore-log: DEBUG createNativeListener: listening 45786
03-29 13:30:04.757 11202 11266 I jxcore-log: 
,03-29 13:30:04.767 11202 11266 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 13:30:04.767 11202 11266 I jxcore-log: 
,03-29 13:30:04.772 11202 11266 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 13:30:04.772 11202 11266 I jxcore-log: 
,03-29 13:30:04.772 11202 11266 I jxcore-log: DEBUG createNativeListener: new mux
03-29 13:30:04.772 11202 11266 I jxcore-log: 
,03-29 13:30:04.782 11202 11266 I jxcore-log: ok 38 we should not have gotten an error
03-29 13:30:04.782 11202 11266 I jxcore-log: 
,03-29 13:30:04.787 11202 11266 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:30:04.787 11202 11266 I jxcore-log: 
,03-29 13:30:04.792 11202 11266 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:30:04.792 11202 11266 I jxcore-log: 
,03-29 13:30:04.802 11202 11266 I jxcore-log: ok 39 Buffers are identical
03-29 13:30:04.802 11202 11266 I jxcore-log: 
,03-29 13:30:04.807 11202 11266 I jxcore-log: DEBUG createNativeListener: incoming socket timeout
03-29 13:30:04.807 11202 11266 I jxcore-log: 
,03-29 13:30:04.807 11202 11266 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:30:04.807 11202 11266 I jxcore-log: 
,03-29 13:30:04.812 11202 11266 I jxcore-log: DEBUG createNativeListener: mux close
03-29 13:30:04.812 11202 11266 I jxcore-log: 
,03-29 13:30:04.817 11202 11266 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 13:30:04.817 11202 11266 I jxcore-log: 
,03-29 13:30:04.817 11202 11266 I jxcore-log: ok 40 server should be fine
03-29 13:30:04.817 11202 11266 I jxcore-log: 
,03-29 13:30:04.817 11202 11266 I jxcore-log: ok 41 server should be open
03-29 13:30:04.817 11202 11266 I jxcore-log: 
,03-29 13:30:04.817 11202 11266 I jxcore-log: ok 42 incoming has been removed
03-29 13:30:04.817 11202 11266 I jxcore-log: 
,03-29 13:30:04.822 11202 11266 I jxcore-log: ok 43 The mux object should be closed
03-29 13:30:04.822 11202 11266 I jxcore-log: 
,03-29 13:30:04.822 11202 11266 I jxcore-log: ok 44 The mux stream should be closed
03-29 13:30:04.822 11202 11266 I jxcore-log: 
,03-29 13:30:04.832 11202 11266 I jxcore-log: # teardown
03-29 13:30:04.832 11202 11266 I jxcore-log: 
,03-29 13:30:04.952 11202 11266 I jxcore-log: # setup
03-29 13:30:04.952 11202 11266 I jxcore-log: 
,03-29 13:30:05.102 11202 11266 I jxcore-log: # 12. closeAll can close even when connections open
03-29 13:30:05.102 11202 11266 I jxcore-log: 
,03-29 13:30:05.322 11202 11266 I jxcore-log: ok 45 not possible to connect to the server anymore
03-29 13:30:05.322 11202 11266 I jxcore-log: 
,03-29 13:30:05.327 11202 11266 I jxcore-log: # teardown
03-29 13:30:05.327 11202 11266 I jxcore-log: 
,03-29 13:30:05.412 11202 11266 I jxcore-log: # setup
03-29 13:30:05.412 11202 11266 I jxcore-log: 
,03-29 13:30:05.547 11202 11266 I jxcore-log: # 13. closeAll with promise
03-29 13:30:05.547 11202 11266 I jxcore-log: 
,03-29 13:30:05.827 11202 11266 I jxcore-log: ok 46 not possible to connect to the server anymore
03-29 13:30:05.827 11202 11266 I jxcore-log: 
,03-29 13:30:05.832 11202 11266 I jxcore-log: # teardown
03-29 13:30:05.832 11202 11266 I jxcore-log: 
,03-29 13:30:05.997 11202 11266 I jxcore-log: # setup
03-29 13:30:05.997 11202 11266 I jxcore-log: 
,03-29 13:30:06.137 11202 11266 I jxcore-log: # 14. closeAll properly throws when closing a non open server with eatNotRunning set to false
03-29 13:30:06.137 11202 11266 I jxcore-log: 
,03-29 13:30:06.332 11202 11266 I jxcore-log: ok 47 Got the right error
03-29 13:30:06.332 11202 11266 I jxcore-log: 
,03-29 13:30:06.337 11202 11266 I jxcore-log: # teardown
03-29 13:30:06.337 11202 11266 I jxcore-log: 
,03-29 13:30:06.512 11202 11266 I jxcore-log: # setup
03-29 13:30:06.512 11202 11266 I jxcore-log: 
,03-29 13:30:06.667 11202 11266 I jxcore-log: # 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true
03-29 13:30:06.667 11202 11266 I jxcore-log: 
,03-29 13:30:06.767 11202 11266 I jxcore-log: # teardown
03-29 13:30:06.767 11202 11266 I jxcore-log: 
,03-29 13:30:07.022 11202 11266 I jxcore-log: # setup
03-29 13:30:07.022 11202 11266 I jxcore-log: 
,03-29 13:30:07.207 11202 11266 I jxcore-log: # 16. multiplex can send data
03-29 13:30:07.207 11202 11266 I jxcore-log: 
,03-29 13:30:07.427 11202 11266 I jxcore-log: ok 48 String should be length:200
03-29 13:30:07.427 11202 11266 I jxcore-log: 
,03-29 13:30:07.442 11202 11266 I jxcore-log: # teardown
03-29 13:30:07.442 11202 11266 I jxcore-log: 
,03-29 13:30:07.607 11202 11266 I jxcore-log: # setup
03-29 13:30:07.607 11202 11266 I jxcore-log: 
,03-29 13:30:07.732 11202 11266 I jxcore-log: # 17. enqueue and run in order
03-29 13:30:07.732 11202 11266 I jxcore-log: 
,03-29 13:30:07.987 11202 11266 I jxcore-log: ok 49 firstPromise setTimeout,
,03-29 13:30:07.987 11202 11266 I jxcore-log: 
,03-29 13:30:08.002 11202 11266 I jxcore-log: ok 50 firstPromise result
03-29 13:30:08.002 11202 11266 I jxcore-log: 
,03-29 13:30:08.007 11202 11266 I jxcore-log: ok 51 firstPromise testValue
03-29 13:30:08.007 11202 11266 I jxcore-log: 
,03-29 13:30:08.112 11202 11266 I jxcore-log: ok 52 secondPromise setTimeout
03-29 13:30:08.112 11202 11266 I jxcore-log: 
,03-29 13:30:08.122 11202 11266 I jxcore-log: ok 53 secondPromise result
03-29 13:30:08.122 11202 11266 I jxcore-log: 
,03-29 13:30:08.127 11202 11266 I jxcore-log: ok 54 secondPromise testValue
03-29 13:30:08.127 11202 11266 I jxcore-log: 
,03-29 13:30:08.137 11202 11266 I jxcore-log: ok 55 thirdPromise in promise
03-29 13:30:08.137 11202 11266 I jxcore-log: 
,03-29 13:30:08.142 11202 11266 I jxcore-log: ok 56 thirdPromise result
03-29 13:30:08.142 11202 11266 I jxcore-log: 
,03-29 13:30:08.147 11202 11266 I jxcore-log: ok 57 thirdPromise testValue
03-29 13:30:08.147 11202 11266 I jxcore-log: 
,03-29 13:30:08.157 11202 11266 I jxcore-log: # teardown
03-29 13:30:08.157 11202 11266 I jxcore-log: 
,03-29 13:30:08.252 11202 11266 I jxcore-log: # setup
03-29 13:30:08.252 11202 11266 I jxcore-log: 
,03-29 13:30:08.547 11202 11266 I jxcore-log: # 18. enqueueAtTop and run backwards
03-29 13:30:08.547 11202 11266 I jxcore-log: 
,03-29 13:30:08.682 11202 11266 I jxcore-log: ok 58 thirdPromise - first to run
03-29 13:30:08.682 11202 11266 I jxcore-log: 
,03-29 13:30:08.687 11202 11266 I jxcore-log: ok 59 thirdPromise - in resolve
03-29 13:30:08.687 11202 11266 I jxcore-log: 
,03-29 13:30:08.692 11202 11266 I jxcore-log: ok 60 secondPromise - second to run
03-29 13:30:08.692 11202 11266 I jxcore-log: 
,03-29 13:30:08.692 11202 11266 I jxcore-log: ok 61 secondPromise - in catch
03-29 13:30:08.692 11202 11266 I jxcore-log: 
,03-29 13:30:08.697 11202 11266 I jxcore-log: ok 62 firstPromise - third to run
03-29 13:30:08.697 11202 11266 I jxcore-log: 
,03-29 13:30:08.697 11202 11266 I jxcore-log: ok 63 firstPromise - in then,
03-29 13:30:08.697 11202 11266 I jxcore-log: 
,03-29 13:30:08.702 11202 11266 I jxcore-log: ok 64 testing promises
03-29 13:30:08.702 11202 11266 I jxcore-log: 
,03-29 13:30:08.707 11202 11266 I jxcore-log: # teardown
03-29 13:30:08.707 11202 11266 I jxcore-log: 
,03-29 13:30:08.807 11202 11266 I jxcore-log: # setup
03-29 13:30:08.807 11202 11266 I jxcore-log: 
,03-29 13:30:08.907 11202 11266 I jxcore-log: # 19. mix enqueue and enqueueAtTop
03-29 13:30:08.907 11202 11266 I jxcore-log: 
,03-29 13:30:09.467 11202 11266 I jxcore-log: ok 65 fourth
03-29 13:30:09.467 11202 11266 I jxcore-log: 
,03-29 13:30:09.472 11202 11266 I jxcore-log: ok 66 fourth
03-29 13:30:09.472 11202 11266 I jxcore-log: 
,03-29 13:30:09.472 11202 11266 I jxcore-log: ok 67 second
03-29 13:30:09.472 11202 11266 I jxcore-log: 
,03-29 13:30:09.477 11202 11266 I jxcore-log: ok 68 secondPromise - in then
03-29 13:30:09.477 11202 11266 I jxcore-log: 
,03-29 13:30:09.582 11202 11266 I jxcore-log: ok 69 first
03-29 13:30:09.582 11202 11266 I jxcore-log: 
,03-29 13:30:09.582 11202 11266 I jxcore-log: ok 70 firstPromise - in catch
03-29 13:30:09.582 11202 11266 I jxcore-log: 
,03-29 13:30:09.587 11202 11266 I jxcore-log: ok 71 third
03-29 13:30:09.587 11202 11266 I jxcore-log: 
,03-29 13:30:09.592 11202 11266 I jxcore-log: ok 72 thirdPromise - in then
03-29 13:30:09.592 11202 11266 I jxcore-log: 
,03-29 13:30:09.597 11202 11266 I jxcore-log: ok 73 testingPromises
03-29 13:30:09.597 11202 11266 I jxcore-log: 
,03-29 13:30:09.602 11202 11266 I jxcore-log: # teardown
03-29 13:30:09.602 11202 11266 I jxcore-log: 
,03-29 13:30:09.672 11202 11266 I jxcore-log: # setup
03-29 13:30:09.672 11202 11266 I jxcore-log: 
,03-29 13:30:09.787 11202 11266 I jxcore-log: # 20. queues handled independently,
03-29 13:30:09.787 11202 11266 I jxcore-log: 
,03-29 13:30:09.857  3481  3863 E Watchdog: !@Sync 7 [03-29 13:30:09.861],
,03-29 13:30:10.067 11202 11266 I jxcore-log: ok 74 all short operations completed before the long resolves
03-29 13:30:10.067 11202 11266 I jxcore-log: 
,03-29 13:30:10.077 11202 11266 I jxcore-log: # teardown
03-29 13:30:10.077 11202 11266 I jxcore-log: 
,03-29 13:30:10.197 11202 11266 I jxcore-log: # setup
03-29 13:30:10.197 11202 11266 I jxcore-log: 
,03-29 13:30:10.367 11202 11266 I jxcore-log: # 21. basic
03-29 13:30:10.367 11202 11266 I jxcore-log: 
,03-29 13:30:10.527 11202 11266 I jxcore-log: ok 75 sane
03-29 13:30:10.527 11202 11266 I jxcore-log: 
,03-29 13:30:10.532 11202 11266 I jxcore-log: # teardown
03-29 13:30:10.532 11202 11266 I jxcore-log: 
,03-29 13:30:10.752 11202 11266 I jxcore-log: # setup
03-29 13:30:10.752 11202 11266 I jxcore-log: 
,03-29 13:30:10.867 11202 11266 I jxcore-log: # 22. another
03-29 13:30:10.867 11202 11266 I jxcore-log: 
,03-29 13:30:10.962 11202 11266 I jxcore-log: ok 76 sane
03-29 13:30:10.962 11202 11266 I jxcore-log: 
,03-29 13:30:10.967 11202 11266 I jxcore-log: # teardown
03-29 13:30:10.967 11202 11266 I jxcore-log: 
,03-29 13:30:11.107 11202 11266 I jxcore-log: # setup
03-29 13:30:11.107 11202 11266 I jxcore-log: 
,03-29 13:30:11.232 11202 11266 I jxcore-log: # 23. can pass data in setup
03-29 13:30:11.232 11202 11266 I jxcore-log: 
,03-29 13:30:11.352 11202 11266 I jxcore-log: ok 77 test participant has uuid,
,03-29 13:30:11.352 11202 11266 I jxcore-log: 
,03-29 13:30:11.362 11202 11266 I jxcore-log: ok 78 participant data matches
03-29 13:30:11.362 11202 11266 I jxcore-log: 
,03-29 13:30:11.367 11202 11266 I jxcore-log: ok 79 test participant has uuid
03-29 13:30:11.367 11202 11266 I jxcore-log: 
,03-29 13:30:11.367 11202 11266 I jxcore-log: ok 80 participant data matches
03-29 13:30:11.367 11202 11266 I jxcore-log: 
,03-29 13:30:11.372 11202 11266 I jxcore-log: ok 81 test participant has uuid
03-29 13:30:11.372 11202 11266 I jxcore-log: 
,03-29 13:30:11.372 11202 11266 I jxcore-log: ok 82 participant data matches
03-29 13:30:11.372 11202 11266 I jxcore-log: 
,03-29 13:30:11.377 11202 11266 I jxcore-log: # teardown
03-29 13:30:11.377 11202 11266 I jxcore-log: 
,03-29 13:30:11.507 11202 11266 I jxcore-log: # setup
03-29 13:30:11.507 11202 11266 I jxcore-log: 
,03-29 13:30:11.627 11202 11266 I jxcore-log: # 24. #startListeningForAdvertisements should fail if start not called
03-29 13:30:11.627 11202 11266 I jxcore-log: 
,03-29 13:30:11.797 11202 11266 I jxcore-log: ok 83 specific error should be returned
03-29 13:30:11.797 11202 11266 I jxcore-log: 
,03-29 13:30:11.802 11202 11266 I jxcore-log: # teardown
03-29 13:30:11.802 11202 11266 I jxcore-log: 
,03-29 13:30:11.897 11202 11266 I jxcore-log: ok 84 error should be null
03-29 13:30:11.897 11202 11266 I jxcore-log: 
,03-29 13:30:11.902 11202 11266 I jxcore-log: ok 85 error should be null
03-29 13:30:11.902 11202 11266 I jxcore-log: 
,03-29 13:30:11.907 11202 11266 I jxcore-log: # setup
03-29 13:30:11.907 11202 11266 I jxcore-log: 
,03-29 13:30:12.007 11202 11266 I jxcore-log: # 25. #startUpdateAdvertisingAndListening should fail if start not called
03-29 13:30:12.007 11202 11266 I jxcore-log: 
,03-29 13:30:12.112 11202 11266 I jxcore-log: ok 86 specific error should be returned
03-29 13:30:12.112 11202 11266 I jxcore-log: 
,03-29 13:30:12.117 11202 11266 I jxcore-log: # teardown
03-29 13:30:12.117 11202 11266 I jxcore-log: 
,03-29 13:30:12.217 11202 11266 I jxcore-log: ok 87 error should be null
03-29 13:30:12.217 11202 11266 I jxcore-log: 
,03-29 13:30:12.217 11202 11266 I jxcore-log: ok 88 error should be null
03-29 13:30:12.217 11202 11266 I jxcore-log: 
,03-29 13:30:12.217 11202 11266 I jxcore-log: # setup
03-29 13:30:12.217 11202 11266 I jxcore-log: 
,03-29 13:30:12.382 11202 11266 I jxcore-log: # 26. should be able to call #stopListeningForAdvertisements many times
03-29 13:30:12.382 11202 11266 I jxcore-log: 
,03-29 13:30:12.607 11202 11266 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 13:30:12.607 11202 11266 I jxcore-log: 
,03-29 13:30:12.607 11202 11266 I jxcore-log: DEBUG createNativeListener: listening 58572
03-29 13:30:12.607 11202 11266 I jxcore-log: 
,03-29 13:30:12.612 11202 11266 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-29 13:30:12.612 11202 11266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-29 13:30:12.612 11202 11266 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 13:30:12.617 11202 11266 I jxcore-log: ok 89 error should be null
03-29 13:30:12.617 11202 11266 I jxcore-log: 
,03-29 13:30:12.622 11202 11266 I jxcore-log: ok 90 error should be null
03-29 13:30:12.622 11202 11266 I jxcore-log: 
,03-29 13:30:12.622 11202 11266 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-29 13:30:12.622 11202 11266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-29 13:30:12.622 11202 11266 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 13:30:12.622 11202 11266 I jxcore-log: ok 91 error should be null
03-29 13:30:12.622 11202 11266 I jxcore-log: 
,03-29 13:30:12.622 11202 11266 I jxcore-log: ok 92 error should be null
03-29 13:30:12.622 11202 11266 I jxcore-log: 
,03-29 13:30:12.627 11202 11266 I jxcore-log: # teardown
03-29 13:30:12.627 11202 11266 I jxcore-log: 
,03-29 13:30:12.657  3481  3985 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-29 13:30:12.657  3481  3985 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-29 13:30:12.657  3481  3985 D BatteryService: online:4, current avg:33, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:41
03-29 13:30:12.657  3481  3985 D BatteryService: stay LED for fully charged
03-29 13:30:12.657  3481  3481 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-29 13:30:12.662  3481  3481 I MotionRecognitionService: Plugged
03-29 13:30:12.662  3481  3481 D MotionRecognitionService:   cableConnection= 1
03-29 13:30:12.662  3481  3481 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-29 13:30:12.662  3481  3481 D MotionRecognitionService: skip setTransmitPower. 
,03-29 13:30:12.667  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-29 13:30:12.667  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-29 13:30:12.667  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-29 13:30:12.672  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-29 13:30:12.672  5947  5947 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-29 13:30:12.672  5947  6065 D HeadsetStateMachine: Disconnected process message: 10
,03-29 13:30:12.687  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-29 13:30:12.687  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-29 13:30:12.687  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-29 13:30:12.712 11202 11266 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-29 13:30:12.712 11202 11266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 13:30:12.712 11202 11266 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 13:30:12.717 11202 11266 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-29 13:30:12.717 11202 11266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-29 13:30:12.717 11202 11266 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 13:30:12.722 11202 11266 I jxcore-log: ok 93 error should be null
03-29 13:30:12.722 11202 11266 I jxcore-log: 
,03-29 13:30:12.722 11202 11266 I jxcore-log: ok 94 error should be null
03-29 13:30:12.722 11202 11266 I jxcore-log: 
,03-29 13:30:12.732 11202 11266 I jxcore-log: # setup
03-29 13:30:12.732 11202 11266 I jxcore-log: 
,03-29 13:30:12.892 11202 11266 I jxcore-log: # 27. should be able to call #startListeningForAdvertisements many times
03-29 13:30:12.892 11202 11266 I jxcore-log: 
,03-29 13:30:13.512 11202 11266 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 13:30:13.512 11202 11266 I jxcore-log: 
,03-29 13:30:13.517 11202 11266 I jxcore-log: DEBUG createNativeListener: listening 51115
03-29 13:30:13.517 11202 11266 I jxcore-log: 
,03-29 13:30:13.527 11202 11266 I io.jxcore.node.ConnectionHelper: start: Port number: 0, start advertisements: false
,03-29 13:30:13.532 11202 11266 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-29 13:30:13.532 11202 11266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-29 13:30:13.532 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-29 13:30:13.532 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-29 13:30:13.532 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-29 13:30:13.537 11202 11266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-29 13:30:13.552 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-29 13:30:13.557 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-29 13:30:13.557 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-29 13:30:13.557 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-29 13:30:13.557 11202 11266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-29 13:30:13.567  5947  6068 D BtGatt.GattService: registerClient() - UUID=e8dd3d71-0819-4c1d-9938-e5364e28e031
,03-29 13:30:13.612  5947  6057 D BtGatt.GattService: onClientRegistered() - UUID=e8dd3d71-0819-4c1d-9938-e5364e28e031, clientIf=6
,03-29 13:30:13.612 11202 11214 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-29 13:30:13.612  5947  5956 D BtGatt.GattService: start scan with filters
,03-29 13:30:13.627  5947  5956 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 48
,03-29 13:30:13.632 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-29 13:30:13.632  5947  6061 D BtGatt.ScanManager: handling starting scan
03-29 13:30:13.632 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-29 13:30:13.632  5947  6061 D BtGatt.ScanManager: isFilteringSupported
03-29 13:30:13.632 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-29 13:30:13.632  5947  6061 D BluetoothAdapter: setting StandAloneBleMode
03-29 13:30:13.632 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-29 13:30:13.632 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 13:30:13.632 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-29 13:30:13.632 11202 11202 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-29 13:30:13.632  5947  6061 D BtGatt.ScanManager: isFilteringSupported
03-29 13:30:13.632  5947  6061 D BluetoothAdapter: setting StandAloneBleMode
,03-29 13:30:13.637  5947  6061 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d3d4163
,03-29 13:30:13.637 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
03-29 13:30:13.637 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-29 13:30:13.637 11202 11266 I io.jxcore.node.ConnectionHelper: start: OK
03-29 13:30:13.637 11202 11202 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-29 13:30:13.637 11202 11202 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 13:30:13.637 11202 11202 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-29 13:30:13.647  5947  6057 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,03-29 13:30:13.647  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:30:13.647  5947  6061 D BtGatt.ScanManager: allow scan with filters
03-29 13:30:13.647  5947  6061 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,03-29 13:30:13.647  5947  6061 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,03-29 13:30:13.647 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 13:30:13.647 11202 11266 I jxcore-log: 
03-29 13:30:13.647  5947  6057 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-29 13:30:13.647  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 13:30:13.652  5947  6061 D BtGatt.ScanManager: Starting BLE batch scan
03-29 13:30:13.652  5947  6061 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-29 13:30:13.652 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 13:30:13.652 11202 11266 I jxcore-log: 
,03-29 13:30:13.652  5947  6057 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-29 13:30:13.652  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 13:30:13.652 11202 11266 I jxcore-log: ok 95 error should be null
03-29 13:30:13.652 11202 11266 I jxcore-log: 
,03-29 13:30:13.652  5947  6057 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-29 13:30:13.652  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 13:30:13.657 11202 11266 I jxcore-log: ok 96 error should be null
03-29 13:30:13.657 11202 11266 I jxcore-log: 
,03-29 13:30:13.662 11202 11266 I io.jxcore.node.ConnectionHelper: start: Port number: 0, start advertisements: false
03-29 13:30:13.662 11202 11266 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-29 13:30:13.662 11202 11266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-29 13:30:13.662 11202 11266 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-29 13:30:13.662 11202 11266 I io.jxcore.node.ConnectionHelper: start: OK
,03-29 13:30:13.667 11202 11266 I jxcore-log: ok 97 error should be null
03-29 13:30:13.667 11202 11266 I jxcore-log: 
,03-29 13:30:13.667 11202 11266 I jxcore-log: ok 98 error should be null
03-29 13:30:13.667 11202 11266 I jxcore-log: 
,03-29 13:30:13.672 11202 11266 I jxcore-log: # teardown
03-29 13:30:13.672 11202 11266 I jxcore-log: 
,03-29 13:30:14.152  3481  6174 D SSRM:n  : SIOP:: AP = 280, PST = 282 (W:14), CUR = 33, LCD = 0,
,03-29 13:30:14.657  3481  3619 V AlarmManager: waitForAlarm result :4
,03-29 13:30:14.682  5947  5947 D BtGatt.ScanManager: awakened up at time 227666
,03-29 13:30:14.687  5947  6061 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-29 13:30:14.692  5947  6057 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-29 13:30:14.692  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 13:30:14.702  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
03-29 13:30:14.702  3726  3726 I PERF    : received broadcast android.intent.action.TIME_TICK
03-29 13:30:14.702  3726  3726 D KeyguardUpdateMonitor: handleTimeUpdate
,03-29 13:30:14.717  3726  3726 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,03-29 13:30:14.722  3726  3726 D SecKeyguardClockView: HomeTimezone(): 1
,03-29 13:30:14.732  3726  3726 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-29 13:30:14.732  3726  3726 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,03-29 13:30:14.737  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,03-29 13:30:14.772  3726  3726 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-29 13:30:14.772  3726  3726 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-29 13:30:14.777  3726  3726 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-29 13:30:14.777  3726  3726 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-29 13:30:14.782  3726  3726 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-29 13:30:14.782  3726  3726 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-29 13:30:14.802  3726  3726 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-29 13:30:15.367 11202 11266 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-29 13:30:15.367 11202 11266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,03-29 13:30:15.372 11202 11266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,03-29 13:30:15.372 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-29 13:30:15.372 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...,
,03-29 13:30:15.372 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-29 13:30:15.377 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-29 13:30:15.377 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-29 13:30:15.377 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-29 13:30:15.382  5947  5958 D BtGatt.GattService: stopScan() - queue size =1,
03-29 13:30:15.382  5947  6061 D BtGatt.ScanManager: filter size is 1
03-29 13:30:15.387  5947  6061 D BtGatt.ScanManager: delete FilterIndex - 3
03-29 13:30:15.387  5947  6057 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-29 13:30:15.387  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 13:30:15.387  5947  6061 D BtGatt.ScanManager: stopping BLe Batch,
03-29 13:30:15.392  5947  6057 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-29 13:30:15.392  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,03-29 13:30:15.392  5947  6061 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6,
03-29 13:30:15.392  5947  6057 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-29 13:30:15.392  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 13:30:15.397  5947  6068 D BtGatt.GattService: unregisterClient() - clientIf=6,
,03-29 13:30:15.402 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-29 13:30:15.402 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-29 13:30:15.402 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,03-29 13:30:15.407 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED],
03-29 13:30:15.407 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-29 13:30:15.407 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-29 13:30:15.407 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
03-29 13:30:15.407 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-29 13:30:15.407 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-29 13:30:15.412 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
03-29 13:30:15.412 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-29 13:30:15.412 11202 11202 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-29 13:30:15.412 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-29 13:30:15.412 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-29 13:30:15.422 11202 11202 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
03-29 13:30:15.422 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-29 13:30:15.427 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-29 13:30:15.427 11202 11202 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-29 13:30:15.427 11202 11202 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false,
03-29 13:30:15.427 11202 11202 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 13:30:15.427 11202 11202 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed,
,03-29 13:30:15.432 11202 11266 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).,
03-29 13:30:15.432 11202 11266 I jxcore-log: 
,03-29 13:30:15.432 11202 11202 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false,
,03-29 13:30:15.437 11202 11266 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-29 13:30:15.437 11202 11266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-29 13:30:15.442 11202 11266 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 13:30:15.442 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 13:30:15.442 11202 11266 I jxcore-log: 
,03-29 13:30:15.442 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 13:30:15.442 11202 11266 I jxcore-log: 
,03-29 13:30:15.452 11202 11266 I jxcore-log: ok 99 error should be null
03-29 13:30:15.452 11202 11266 I jxcore-log: 
,03-29 13:30:15.452 11202 11266 I jxcore-log: ok 100 error should be null
03-29 13:30:15.452 11202 11266 I jxcore-log: 
,03-29 13:30:15.457 11202 11266 I jxcore-log: # setup
03-29 13:30:15.457 11202 11266 I jxcore-log: 
,03-29 13:30:16.667 11202 11266 I jxcore-log: # 28. should be able to call #startUpdateAdvertisingAndListening many times
03-29 13:30:16.667 11202 11266 I jxcore-log: 
,03-29 13:30:17.602  3481  6205 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-29 13:30:17.957 11202 11266 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 13:30:17.957 11202 11266 I jxcore-log: 
,03-29 13:30:17.962 11202 11266 I jxcore-log: DEBUG createNativeListener: listening 53710
03-29 13:30:17.962 11202 11266 I jxcore-log: 
,03-29 13:30:17.982 11202 11266 I io.jxcore.node.ConnectionHelper: start: Port number: 53710, start advertisements: true
,03-29 13:30:17.982 11202 11266 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-29 13:30:17.982 11202 11266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-29 13:30:17.982 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-29 13:30:17.987 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-29 13:30:17.987 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-29 13:30:17.987 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-29 13:30:17.987 11202 11266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-29 13:30:17.992  5947  5956 D BtGatt.GattService: registerClient() - UUID=2acb4f5d-0046-43f7-af34-22222aac7bb2
,03-29 13:30:18.032  5947  6057 D BtGatt.GattService: onClientRegistered() - UUID=2acb4f5d-0046-43f7-af34-22222aac7bb2, clientIf=6
,03-29 13:30:18.032 11202 11212 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-29 13:30:18.032  5947  5958 D BtGatt.GattService: start scan with filters
,03-29 13:30:18.047  5947  5958 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 49
,03-29 13:30:18.047 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-29 13:30:18.047 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-29 13:30:18.047 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-29 13:30:18.047 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-29 13:30:18.047 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 13:30:18.047  5947  6061 D BtGatt.ScanManager: handling starting scan
03-29 13:30:18.047  5947  6061 D BtGatt.ScanManager: isFilteringSupported
03-29 13:30:18.047  5947  6061 D BluetoothAdapter: setting StandAloneBleMode
03-29 13:30:18.047 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-29 13:30:18.047 11202 11202 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 13:30:18.047 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-29 13:30:18.047 11202 11266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-29 13:30:18.047 11202 11266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 13:30:18.047 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 13:30:18.047 11202 11266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-29 13:30:18.052  5947  6057 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-29 13:30:18.052  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:30:18.052  5947  6061 D BtGatt.ScanManager: allow scan with filters
03-29 13:30:18.052  5947  6061 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,03-29 13:30:18.052  5947  6061 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,03-29 13:30:18.052  5947  6057 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,03-29 13:30:18.052  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:30:18.052  5947  6061 D BtGatt.ScanManager: Starting BLE batch scan
,03-29 13:30:18.052  5947  6061 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-29 13:30:18.057  5947  6068 D BtGatt.GattService: registerClient() - UUID=66d00ea6-ac1e-4313-897c-a9c2f2ae1be3
03-29 13:30:18.057  5947  6057 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-29 13:30:18.057  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 13:30:18.057  5947  6057 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-29 13:30:18.057  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 13:30:18.102  5947  6057 D BtGatt.GattService: onClientRegistered() - UUID=66d00ea6-ac1e-4313-897c-a9c2f2ae1be3, clientIf=7
,03-29 13:30:18.102 11202 11214 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-29 13:30:18.122  5947  5956 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 40
,03-29 13:30:18.127  5947  6060 D BtGatt.AdvertiseManager: message : 0
,03-29 13:30:18.132  5947  6060 D BtGatt.AdvertiseManager: number of adv instance running0
03-29 13:30:18.132  5947  6060 D BtGatt.AdvertiseManager: size of list is =0
,03-29 13:30:18.132  5947  6060 D BtGatt.AdvertiseManager: starting advertising
,03-29 13:30:18.132  5947  6060 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-29 13:30:18.137  5947  6057 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-29 13:30:18.142  5947  6060 D BtGatt.AdvertiseManager: starting multi advertising
,03-29 13:30:18.142  5947  6057 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-29 13:30:18.142  5947  6060 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-29 13:30:18.142  5947  6060 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,03-29 13:30:18.147 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-29 13:30:18.147 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-29 13:30:18.152 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-29 13:30:18.152 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-29 13:30:18.152 11202 11266 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-29 13:30:18.152 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-29 13:30:18.152 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-29 13:30:18.157 11202 11266 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,03-29 13:30:18.157 11202 11266 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-29 13:30:18.157 11202 11266 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-29 13:30:18.157 11202 11266 I io.jxcore.node.ConnectionHelper: start: OK
03-29 13:30:18.157 11202 11202 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-29 13:30:18.157 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-29 13:30:18.157 11202 11202 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-29 13:30:18.157 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-29 13:30:18.157 11202 11202 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-29 13:30:18.157 11202 11202 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-29 13:30:18.157 11202 11202 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-29 13:30:18.157 11202 11202 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-29 13:30:18.157 11202 11202 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-29 13:30:18.157 11202 11202 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 13:30:18.157 11202 11202 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,03-29 13:30:18.157 11202 11202 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-29 13:30:18.167 11202 11576 D BluetoothSocket: bindListen(): myUserId = 0,
03-29 13:30:18.167 11202 11576 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-29 13:30:18.172 11202 11576 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[114]}
,03-29 13:30:18.172 11202 11576 D BluetoothSocket: bindListen(), new LocalSocket 
03-29 13:30:18.172 11202 11576 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-29 13:30:18.172 11202 11576 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@25f7a96a
03-29 13:30:18.172 11202 11576 D BluetoothSocket: channel: 6
03-29 13:30:18.172 11202 11576 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-29 13:30:18.192 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 13:30:18.192 11202 11266 I jxcore-log: 
,03-29 13:30:18.197 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 13:30:18.197 11202 11266 I jxcore-log: 
,03-29 13:30:18.197 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-29 13:30:18.197 11202 11266 I jxcore-log: 
,03-29 13:30:18.202 11202 11266 I jxcore-log: ok 101 error should be null
03-29 13:30:18.202 11202 11266 I jxcore-log: 
,03-29 13:30:18.202 11202 11266 I jxcore-log: ok 102 error should be null
03-29 13:30:18.202 11202 11266 I jxcore-log: 
,03-29 13:30:18.207 11202 11266 I io.jxcore.node.ConnectionHelper: start: Port number: 53710, start advertisements: true
,03-29 13:30:18.207 11202 11266 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-29 13:30:18.207 11202 11266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-29 13:30:18.207 11202 11266 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-29 13:30:18.207 11202 11266 I io.jxcore.node.ConnectionHelper: start: OK
,03-29 13:30:18.222 11202 11266 I jxcore-log: ok 103 error should be null
03-29 13:30:18.222 11202 11266 I jxcore-log: 
,03-29 13:30:18.227 11202 11266 I jxcore-log: ok 104 error should be null
03-29 13:30:18.227 11202 11266 I jxcore-log: 
,03-29 13:30:18.232 11202 11266 I jxcore-log: # teardown
03-29 13:30:18.232 11202 11266 I jxcore-log: 
,03-29 13:30:19.037 11202 11266 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-29 13:30:19.037 11202 11266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
,03-29 13:30:19.042 11202 11266 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,03-29 13:30:19.042 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,03-29 13:30:19.042 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,03-29 13:30:19.047 11202 11266 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@120d9e5b, channel: 6, state: LISTENING
,03-29 13:30:19.047 11202 11266 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@120d9e5b, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@25f7a96a, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2b6e56f8mSocket: android.net.LocalSocket@184ac7d1 impl:android.net.LocalSocketImpl@3d5ef236 fd:FileDescriptor[114]
,03-29 13:30:19.052 11202 11266 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@184ac7d1 impl:android.net.LocalSocketImpl@3d5ef236 fd:FileDescriptor[114]
,03-29 13:30:19.057 11202 11266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-29 13:30:19.057 11202 11576 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-29 13:30:19.057  3481  3619 V AlarmManager: waitForAlarm result :4
03-29 13:30:19.057 11202 11576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-29 13:30:19.057 11202 11576 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-29 13:30:19.062 11202 11202 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-29 13:30:19.062  5947  5947 D BtGatt.ScanManager: awakened up at time 232048
03-29 13:30:19.067  5947  6061 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-29 13:30:19.072  5947  6057 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
03-29 13:30:19.072  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:30:19.072  5947  6057 D BtGatt.GattService: current time is 232058941443
03-29 13:30:19.072  5947  6057 D BtGatt.GattService: Batch record : [22, -71, -84, 66, 60, 74, 1, -128, -75, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, 15, 27, 95, -48, -7, 122, 1, -128, -60, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0]
,03-29 13:30:19.082 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-29 13:30:19.082 11202 11202 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-29 13:30:19.082 11202 11202 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-29 13:30:19.082 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-29 13:30:19.082 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-29 13:30:19.082 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-29 13:30:19.082 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-29 13:30:19.082 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-29 13:30:19.082  5947  5958 D BtGatt.GattService: stopScan() - queue size =1,
,03-29 13:30:19.087  5947  6068 D BtGatt.GattService: unregisterClient() - clientIf=6
03-29 13:30:19.087  5947  6061 D BtGatt.ScanManager: filter size is 1
03-29 13:30:19.087  5947  6061 D BtGatt.ScanManager: delete FilterIndex - 4
,03-29 13:30:19.087  5947  6057 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-29 13:30:19.087  5947  6057 D ScanRecord: parseFromBytes
,03-29 13:30:19.087  5947  6057 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-29 13:30:19.087  5947  6057 D ScanRecord: parseFromBytes
,03-29 13:30:19.092 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
03-29 13:30:19.092 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-29 13:30:19.092 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-29 13:30:19.092 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
,03-29 13:30:19.092 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-29 13:30:19.092  5947  6057 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-29 13:30:19.092  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:30:19.092 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-29 13:30:19.092 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-29 13:30:19.092  5947  6061 D BtGatt.ScanManager: stopping BLe Batch
03-29 13:30:19.092  5947  6060 D BtGatt.AdvertiseManager: message : 1
,03-29 13:30:19.092  5947  6060 D BtGatt.AdvertiseManager: stop advertise for client 7,
03-29 13:30:19.092  5947  6060 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-29 13:30:19.092  5947  6057 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-29 13:30:19.092  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:30:19.092  5947  6061 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-29 13:30:19.097  5947  6057 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-29 13:30:19.097  5947  6060 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-29 13:30:19.097  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,03-29 13:30:19.097  5947  6057 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-29 13:30:19.097  5947  6057 D BtGatt.GattService: Client app is not null!
,03-29 13:30:19.097  5947  6068 D BtGatt.GattService: unregisterClient() - clientIf=7
,03-29 13:30:19.097 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-29 13:30:19.102 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,03-29 13:30:19.102 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-29 13:30:19.102 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-29 13:30:19.102 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-29 13:30:19.102 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-29 13:30:19.102 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-29 13:30:19.102 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-29 13:30:19.102 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-29 13:30:19.102 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-29 13:30:19.102 11202 11202 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 13:30:19.102 11202 11202 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 13:30:19.102 11202 11202 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-29 13:30:19.102 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-29 13:30:19.102 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-29 13:30:19.102 11202 11266 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-29 13:30:19.102 11202 11266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-29 13:30:19.102 11202 11266 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 13:30:19.107 11202 11202 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-29 13:30:19.107 11202 11266 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-29 13:30:19.107 11202 11266 I jxcore-log: 
,03-29 13:30:19.112 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-29 13:30:19.112 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-29 13:30:19.112 11202 11202 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-29 13:30:19.117 11202 11202 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-29 13:30:19.117 11202 11202 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-29 13:30:19.117 11202 11202 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-29 13:30:19.117 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-29 13:30:19.117 11202 11266 I jxcore-log: 
,03-29 13:30:19.117 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 13:30:19.117 11202 11266 I jxcore-log: 
,03-29 13:30:19.117 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 13:30:19.117 11202 11266 I jxcore-log: 
,03-29 13:30:19.122 11202 11266 I jxcore-log: ok 105 error should be null
03-29 13:30:19.122 11202 11266 I jxcore-log: 
,03-29 13:30:19.127 11202 11266 I jxcore-log: ok 106 error should be null
03-29 13:30:19.127 11202 11266 I jxcore-log: 
,03-29 13:30:19.132 11202 11266 I jxcore-log: # setup
03-29 13:30:19.132 11202 11266 I jxcore-log: 
,03-29 13:30:20.242 11202 11266 I jxcore-log: # 29. should be able to call #stopAdvertisingAndListening many times
03-29 13:30:20.242 11202 11266 I jxcore-log: 
,03-29 13:30:22.797  3481  4029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-29 13:30:22.797  3481  4029 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-29 13:30:22.797  3481  4029 D BatteryService: online:4, current avg:38, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:28
,03-29 13:30:22.802  3481  3481 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-29 13:30:22.812  3481  4029 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 11ms
03-29 13:30:22.812  3481  4029 D BatteryService: stay LED for fully charged
,03-29 13:30:22.812  3481  3481 I MotionRecognitionService: Plugged
03-29 13:30:22.812  3481  3481 D MotionRecognitionService:   cableConnection= 1
03-29 13:30:22.812  3481  3481 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-29 13:30:22.812  3481  3481 D MotionRecognitionService: skip setTransmitPower. 
,03-29 13:30:22.822  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-29 13:30:22.822  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-29 13:30:22.827  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-29 13:30:22.837  5947  5947 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-29 13:30:22.837  5947  6065 D HeadsetStateMachine: Disconnected process message: 10
,03-29 13:30:22.847  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-29 13:30:22.847  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-29 13:30:22.852  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-29 13:30:22.852  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-29 13:30:23.052 11202 11266 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 13:30:23.052 11202 11266 I jxcore-log: 
,03-29 13:30:23.057 11202 11266 I jxcore-log: DEBUG createNativeListener: listening 40277
03-29 13:30:23.057 11202 11266 I jxcore-log: 
,03-29 13:30:23.067 11202 11266 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-29 13:30:23.067 11202 11266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-29 13:30:23.067 11202 11266 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 13:30:23.072 11202 11266 I jxcore-log: ok 107 error should be null
03-29 13:30:23.072 11202 11266 I jxcore-log: 
,03-29 13:30:23.072 11202 11266 I jxcore-log: ok 108 error should be null
03-29 13:30:23.072 11202 11266 I jxcore-log: 
,03-29 13:30:23.077 11202 11266 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-29 13:30:23.077 11202 11266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-29 13:30:23.077 11202 11266 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 13:30:23.087 11202 11266 I jxcore-log: ok 109 error should be null
03-29 13:30:23.087 11202 11266 I jxcore-log: 
,03-29 13:30:23.087 11202 11266 I jxcore-log: ok 110 error should be null
03-29 13:30:23.087 11202 11266 I jxcore-log: 
,03-29 13:30:23.092 11202 11266 I jxcore-log: # teardown
03-29 13:30:23.092 11202 11266 I jxcore-log: 
,03-29 13:30:23.797  3481  3586 I PowerManagerService: [PWL] Off : 180s ago
,03-29 13:30:24.182  3481  6174 D SSRM:n  : SIOP:: AP = 280, PST = 282 (W:14), CUR = 38, LCD = 0
,03-29 13:30:32.262 11202 11266 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-29 13:30:32.262 11202 11266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 13:30:32.267 11202 11266 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 13:30:32.267 11202 11266 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-29 13:30:32.272 11202 11266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-29 13:30:32.272 11202 11266 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 13:30:32.282 11202 11266 I jxcore-log: ok 111 error should be null
03-29 13:30:32.282 11202 11266 I jxcore-log: 
,03-29 13:30:32.282 11202 11266 I jxcore-log: ok 112 error should be null
03-29 13:30:32.282 11202 11266 I jxcore-log: 
,03-29 13:30:32.292 11202 11266 I jxcore-log: # setup
03-29 13:30:32.292 11202 11266 I jxcore-log: 
,03-29 13:30:32.407 11202 11266 I jxcore-log: # 30. #start should fail if called twice in a row
03-29 13:30:32.407 11202 11266 I jxcore-log: 
,03-29 13:30:32.937  3481  4417 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-29 13:30:32.937  3481  4417 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-29 13:30:32.937  3481  4417 D BatteryService: online:4, current avg:37, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
,03-29 13:30:32.937  3481  3481 D BatteryService: Sending ACTION_BATTERY_CHANGED.,
03-29 13:30:32.942  3481  4417 D BatteryService: stay LED for fully charged,
,03-29 13:30:32.957  3481  3481 I MotionRecognitionService: Plugged,
03-29 13:30:32.957  3481  3481 D MotionRecognitionService:   cableConnection= 1
03-29 13:30:32.957  3481  3481 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-29 13:30:32.957  3481  3481 D MotionRecognitionService: skip setTransmitPower. 
,03-29 13:30:32.967  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-29 13:30:32.967  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-29 13:30:32.967  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-29 13:30:32.982  5947  5947 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-29 13:30:32.982  5947  6065 D HeadsetStateMachine: Disconnected process message: 10
,03-29 13:30:32.992  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-29 13:30:32.992  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-29 13:30:32.992  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-29 13:30:32.992  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-29 13:30:33.002 11202 11266 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 13:30:33.002 11202 11266 I jxcore-log: 
,03-29 13:30:33.007 11202 11266 I jxcore-log: DEBUG createNativeListener: listening 44243
03-29 13:30:33.007 11202 11266 I jxcore-log: 
,03-29 13:30:33.007 11202 11266 I jxcore-log: ok 113 first call should succeed
03-29 13:30:33.007 11202 11266 I jxcore-log: 
,03-29 13:30:33.012 11202 11266 I jxcore-log: ok 114 first call should succeed
03-29 13:30:33.012 11202 11266 I jxcore-log: 
,03-29 13:30:33.012 11202 11266 I jxcore-log: ok 115 specific error should be returned
03-29 13:30:33.012 11202 11266 I jxcore-log: 
,03-29 13:30:33.017 11202 11266 I jxcore-log: # teardown
03-29 13:30:33.017 11202 11266 I jxcore-log: 
,03-29 13:30:33.157 11202 11266 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-29 13:30:33.157 11202 11266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 13:30:33.157 11202 11266 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 13:30:33.162 11202 11266 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-29 13:30:33.162 11202 11266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-29 13:30:33.162 11202 11266 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 13:30:33.167 11202 11266 I jxcore-log: ok 116 error should be null
03-29 13:30:33.167 11202 11266 I jxcore-log: 
,03-29 13:30:33.172 11202 11266 I jxcore-log: ok 117 error should be null
03-29 13:30:33.172 11202 11266 I jxcore-log: 
,03-29 13:30:33.177 11202 11266 I jxcore-log: # setup
03-29 13:30:33.177 11202 11266 I jxcore-log: 
,03-29 13:30:34.112 11202 11266 I jxcore-log: # 31. does not emit duplicate discoveryAdvertisingStateUpdate
03-29 13:30:34.112 11202 11266 I jxcore-log: 
,03-29 13:30:34.222  3481  6174 D SSRM:n  : SIOP:: AP = 280, PST = 283 (W:16), CUR = 37, LCD = 0
,03-29 13:30:34.247 11202 11266 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 13:30:34.247 11202 11266 I jxcore-log: 
,03-29 13:30:34.252 11202 11266 I jxcore-log: DEBUG createNativeListener: listening 55532
03-29 13:30:34.252 11202 11266 I jxcore-log: 
,03-29 13:30:34.257 11202 11266 I io.jxcore.node.ConnectionHelper: start: Port number: 53710, start advertisements: false
,03-29 13:30:34.257 11202 11266 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-29 13:30:34.262 11202 11266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-29 13:30:34.262 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-29 13:30:34.262 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-29 13:30:34.262 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-29 13:30:34.262 11202 11266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-29 13:30:34.267  5947  5958 D BtGatt.GattService: registerClient() - UUID=4db6fd39-6f54-437a-82a7-422650eb3395
,03-29 13:30:34.307  5947  6057 D BtGatt.GattService: onClientRegistered() - UUID=4db6fd39-6f54-437a-82a7-422650eb3395, clientIf=6
03-29 13:30:34.307 11202 11212 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-29 13:30:34.312  5947  6068 D BtGatt.GattService: start scan with filters
,03-29 13:30:34.322  5947  6068 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 50
,03-29 13:30:34.327 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-29 13:30:34.327 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-29 13:30:34.327 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-29 13:30:34.327 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-29 13:30:34.327 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 13:30:34.327 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-29 13:30:34.327  5947  6061 D BtGatt.ScanManager: handling starting scan
03-29 13:30:34.327  5947  6061 D BtGatt.ScanManager: isFilteringSupported
03-29 13:30:34.327  5947  6061 D BluetoothAdapter: setting StandAloneBleMode
03-29 13:30:34.327 11202 11202 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-29 13:30:34.327 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-29 13:30:34.327 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-29 13:30:34.327 11202 11266 I io.jxcore.node.ConnectionHelper: start: OK
03-29 13:30:34.327 11202 11202 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-29 13:30:34.327 11202 11202 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 13:30:34.327 11202 11202 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-29 13:30:34.332 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 13:30:34.332 11202 11266 I jxcore-log: 
,03-29 13:30:34.337 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 13:30:34.337 11202 11266 I jxcore-log: 
,03-29 13:30:34.337  5947  6057 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,03-29 13:30:34.337  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:30:34.337  5947  6061 D BtGatt.ScanManager: allow scan with filters
03-29 13:30:34.337  5947  6061 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-29 13:30:34.337  5947  6061 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,03-29 13:30:34.337  5947  6057 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-29 13:30:34.337  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:30:34.337  5947  6061 D BtGatt.ScanManager: Starting BLE batch scan
03-29 13:30:34.337  5947  6061 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-29 13:30:34.342  5947  6057 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,03-29 13:30:34.342  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 13:30:34.342  5947  6057 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-29 13:30:34.342  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 13:30:34.352 11202 11266 I io.jxcore.node.ConnectionHelper: start: Port number: 55532, start advertisements: true
,03-29 13:30:34.352 11202 11266 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-29 13:30:34.352 11202 11266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-29 13:30:34.352 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-29 13:30:34.352 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-29 13:30:34.352 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
03-29 13:30:34.352 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-29 13:30:34.352 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-29 13:30:34.352 11202 11266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-29 13:30:34.357 11202 11266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 13:30:34.357 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 13:30:34.357 11202 11266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-29 13:30:34.357  5947  5956 D BtGatt.GattService: registerClient() - UUID=4f485e59-bb6c-4077-b726-7318603018fe
,03-29 13:30:34.402  5947  6057 D BtGatt.GattService: onClientRegistered() - UUID=4f485e59-bb6c-4077-b726-7318603018fe, clientIf=7
,03-29 13:30:34.402 11202 11214 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-29 13:30:34.427  5947  6068 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 41
,03-29 13:30:34.427  5947  6060 D BtGatt.AdvertiseManager: message : 0
03-29 13:30:34.427  5947  6060 D BtGatt.AdvertiseManager: number of adv instance running0
03-29 13:30:34.427  5947  6060 D BtGatt.AdvertiseManager: size of list is =0
,03-29 13:30:34.437  5947  6060 D BtGatt.AdvertiseManager: starting advertising
03-29 13:30:34.437  5947  6060 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-29 13:30:34.442  5947  6057 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-29 13:30:34.447  5947  6060 D BtGatt.AdvertiseManager: starting multi advertising
,03-29 13:30:34.447  5947  6057 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-29 13:30:34.447  5947  6060 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-29 13:30:34.447  5947  6060 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,03-29 13:30:34.452 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess,
03-29 13:30:34.452 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-29 13:30:34.452 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-29 13:30:34.452 11202 11202 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-29 13:30:34.452 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-29 13:30:34.452 11202 11202 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-29 13:30:34.452 11202 11202 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-29 13:30:34.457 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-29 13:30:34.457 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-29 13:30:34.457 11202 11202 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-29 13:30:34.457 11202 11266 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-29 13:30:34.457 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-29 13:30:34.462 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...,
03-29 13:30:34.462 11202 11266 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-29 13:30:34.462 11202 11266 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,03-29 13:30:34.462 11202 11266 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-29 13:30:34.462 11202 11202 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-29 13:30:34.462 11202 11202 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 13:30:34.462 11202 11202 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,03-29 13:30:34.462 11202 11266 I io.jxcore.node.ConnectionHelper: start: OK
,03-29 13:30:34.477 11202 11617 D BluetoothSocket: bindListen(): myUserId = 0
,03-29 13:30:34.477 11202 11617 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-29 13:30:34.477 11202 11617 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[114]}
,03-29 13:30:34.482 11202 11617 D BluetoothSocket: bindListen(), new LocalSocket 
03-29 13:30:34.482 11202 11617 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,03-29 13:30:34.482 11202 11617 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@251ffbc2
03-29 13:30:34.482 11202 11617 D BluetoothSocket: channel: 6
,03-29 13:30:34.482 11202 11617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-29 13:30:34.497 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-29 13:30:34.497 11202 11266 I jxcore-log: 
,03-29 13:30:34.502 11202 11266 I jxcore-log: ok 118 called only once
03-29 13:30:34.502 11202 11266 I jxcore-log: 
,03-29 13:30:34.507 11202 11266 I jxcore-log: ok 119 discovery state matches
03-29 13:30:34.507 11202 11266 I jxcore-log: 
,03-29 13:30:34.507 11202 11266 I jxcore-log: ok 120 advertising state matches
03-29 13:30:34.507 11202 11266 I jxcore-log: 
,03-29 13:30:34.517 11202 11266 I jxcore-log: # teardown
03-29 13:30:34.517 11202 11266 I jxcore-log: 
,03-29 13:30:35.342  3481  3619 V AlarmManager: waitForAlarm result :4
,03-29 13:30:35.347  5947  5947 D BtGatt.ScanManager: awakened up at time 248333
,03-29 13:30:35.357  5947  6061 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-29 13:30:35.367  5947  6057 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
03-29 13:30:35.367  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:30:35.367  5947  6057 D BtGatt.GattService: current time is 248351995403
03-29 13:30:35.367  5947  6057 D BtGatt.GattService: Batch record : [-96, 70, -29, 108, 32, 82, 1, -128, -76, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, 89, 53, -118, 70, -98, 127, 1, -128, -61, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0]
03-29 13:30:35.367  5947  6057 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-29 13:30:35.367  5947  6057 D ScanRecord: parseFromBytes
03-29 13:30:35.367  5947  6057 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-29 13:30:35.367  5947  6057 D ScanRecord: parseFromBytes
03-29 13:30:35.367  5947  6057 D BtGatt.GattService: result: ScanResult{mDevice=7F:9E:46:8A:35:59, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-61, mTimestampNanos=248352217278}
03-29 13:30:35.367  5947  6057 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-29 13:30:35.367  5947  6057 D BtGatt.GattService: result: ScanResult{mDevice=52:20:6C:E3:46:A0, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-76, mTimestampNanos=248252217278}
03-29 13:30:35.367  5947  6057 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-29 13:30:35.367 11202 11214 D ScanRecord: parseFromBytes
03-29 13:30:35.372 11202 11214 D ScanRecord: parseFromBytes
03-29 13:30:35.372 11202 11202 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:CF:C5:D9:E5:61], added - the peer count is 1
03-29 13:30:35.372 11202 11202 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 2
03-29 13:30:35.372 11202 11202 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:CF:C5:D9:E5:61], Bluetooth address: F8:CF:C5:D9:E5:61, device name: , device address: 
,03-29 13:30:35.387 11202 11202 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
,03-29 13:30:35.387 11202 11266 I jxcore-log: DEBUG createPeerListener: createPeerListener
03-29 13:30:35.387 11202 11266 I jxcore-log: 
,03-29 13:30:35.392 11202 11266 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false
03-29 13:30:35.392 11202 11266 I jxcore-log: 
,03-29 13:30:35.397 11202 11266 I jxcore-log: DEBUG createPeerListener: createPeerListener
03-29 13:30:35.397 11202 11266 I jxcore-log: 
,03-29 13:30:35.402 11202 11266 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false
03-29 13:30:35.402 11202 11266 I jxcore-log: 
,03-29 13:30:36.382  3481  3619 V AlarmManager: waitForAlarm result :4
03-29 13:30:36.387  5947  5947 D BtGatt.ScanManager: awakened up at time 249371
03-29 13:30:36.387  5947  6061 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-29 13:30:36.397  5947  6057 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
03-29 13:30:36.397  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:30:36.397  5947  6057 D BtGatt.GattService: current time is 249384028528
03-29 13:30:36.397  5947  6057 D BtGatt.GattService: Batch record : [-96, 70, -29, 108, 32, 82, 1, -128, -74, 9, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, 89, 53, -118, 70, -98, 127, 1, -128, -60, 10, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0]
03-29 13:30:36.397  5947  6057 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-29 13:30:36.397  5947  6057 D ScanRecord: parseFromBytes
03-29 13:30:36.397  5947  6057 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-29 13:30:36.397  5947  6057 D ScanRecord: parseFromBytes
,03-29 13:30:36.402  5947  6057 D BtGatt.GattService: result: ScanResult{mDevice=7F:9E:46:8A:35:59, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-60, mTimestampNanos=248884254695}
03-29 13:30:36.402  5947  6057 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-29 13:30:36.402  5947  6057 D BtGatt.GattService: result: ScanResult{mDevice=52:20:6C:E3:46:A0, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-74, mTimestampNanos=248934254695}
03-29 13:30:36.402  5947  6057 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null],
03-29 13:30:36.402 11202 11212 D ScanRecord: parseFromBytes
03-29 13:30:36.402 11202 11212 D ScanRecord: parseFromBytes
03-29 13:30:36.402 11202 11202 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:CF:C5:D9:E5:61] updated - the peer count is 2
03-29 13:30:36.402 11202 11202 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
,03-29 13:30:36.422 11202 11266 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-29 13:30:36.422 11202 11266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-29 13:30:36.422 11202 11266 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,03-29 13:30:36.422 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-29 13:30:36.422 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-29 13:30:36.422 11202 11266 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@101a242f, channel: 6, state: LISTENING
03-29 13:30:36.427 11202 11266 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@101a242f, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@251ffbc2, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3d81ea3cmSocket: android.net.LocalSocket@2c1733c5 impl:android.net.LocalSocketImpl@2705411a fd:FileDescriptor[114]
03-29 13:30:36.427 11202 11266 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2c1733c5 impl:android.net.LocalSocketImpl@2705411a fd:FileDescriptor[114]
03-29 13:30:36.427 11202 11266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-29 13:30:36.427 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-29 13:30:36.427 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-29 13:30:36.427 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-29 13:30:36.427 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-29 13:30:36.427 11202 11617 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-29 13:30:36.427 11202 11617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,03-29 13:30:36.427 11202 11617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-29 13:30:36.427 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-29 13:30:36.427 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...,
03-29 13:30:36.427  5947  5956 D BtGatt.GattService: stopScan() - queue size =1
03-29 13:30:36.427  5947  6061 D BtGatt.ScanManager: filter size is 1
03-29 13:30:36.427  5947  6061 D BtGatt.ScanManager: delete FilterIndex - 5
03-29 13:30:36.427  5947  5958 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-29 13:30:36.427 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-29 13:30:36.427 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-29 13:30:36.427 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-29 13:30:36.427 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-29 13:30:36.427 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
,03-29 13:30:36.427  5947  6057 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-29 13:30:36.427 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-29 13:30:36.427  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:30:36.427 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-29 13:30:36.427  5947  6061 D BtGatt.ScanManager: stopping BLe Batch
,03-29 13:30:36.432  5947  6060 D BtGatt.AdvertiseManager: message : 1
03-29 13:30:36.432  5947  6060 D BtGatt.AdvertiseManager: stop advertise for client 7
03-29 13:30:36.432  5947  6060 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-29 13:30:36.432  5947  6060 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-29 13:30:36.432  5947  6057 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-29 13:30:36.432  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 13:30:36.432  5947  6061 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-29 13:30:36.432  5947  6057 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-29 13:30:36.432  5947  6057 D BtGatt.GattService: Client app is not null!
,03-29 13:30:36.437  5947  5958 D BtGatt.GattService: unregisterClient() - clientIf=7
,03-29 13:30:36.437 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-29 13:30:36.437 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,03-29 13:30:36.437 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-29 13:30:36.437 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-29 13:30:36.437 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-29 13:30:36.437 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-29 13:30:36.437 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-29 13:30:36.437 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-29 13:30:36.437  5947  6057 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-29 13:30:36.437  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:30:36.437 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-29 13:30:36.437 11202 11266 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-29 13:30:36.437 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-29 13:30:36.437 11202 11202 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-29 13:30:36.437 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-29 13:30:36.437 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-29 13:30:36.442 11202 11202 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-29 13:30:36.447 11202 11266 I jxcore-log: INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
03-29 13:30:36.447 11202 11266 I jxcore-log: 
,03-29 13:30:36.447 11202 11266 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-29 13:30:36.447 11202 11266 I jxcore-log: 
,03-29 13:30:36.447 11202 11266 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-29 13:30:36.447 11202 11266 I jxcore-log: 
,03-29 13:30:36.447 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-29 13:30:36.447 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-29 13:30:36.452 11202 11202 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-29 13:30:36.452 11202 11202 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-29 13:30:36.452 11202 11202 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-29 13:30:36.452 11202 11202 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-29 13:30:36.452 11202 11202 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 13:30:36.452 11202 11202 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 13:30:36.452 11202 11202 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-29 13:30:36.452 11202 11202 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-29 13:30:36.452 11202 11202 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-29 13:30:36.452 11202 11266 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-29 13:30:36.452 11202 11266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-29 13:30:36.452 11202 11266 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 13:30:36.457 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-29 13:30:36.457 11202 11266 I jxcore-log: 
,03-29 13:30:36.457 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 13:30:36.457 11202 11266 I jxcore-log: 
,03-29 13:30:36.457 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 13:30:36.457 11202 11266 I jxcore-log: 
,03-29 13:30:36.462 11202 11266 I jxcore-log: ok 121 error should be null
03-29 13:30:36.462 11202 11266 I jxcore-log: 
,03-29 13:30:36.462 11202 11266 I jxcore-log: ok 122 error should be null
03-29 13:30:36.462 11202 11266 I jxcore-log: 
,03-29 13:30:36.472 11202 11266 I jxcore-log: # setup
03-29 13:30:36.472 11202 11266 I jxcore-log: 
,03-29 13:30:37.307 11202 11266 I jxcore-log: # 32. does not send duplicate availability changes
03-29 13:30:37.307 11202 11266 I jxcore-log: 
,03-29 13:30:37.607  3481  6205 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-29 13:30:37.657 11202 11266 I jxcore-log: ok 123 should be called once
03-29 13:30:37.657 11202 11266 I jxcore-log: 
,03-29 13:30:37.662 11202 11266 I jxcore-log: ok 124 should not have been called more than once
03-29 13:30:37.662 11202 11266 I jxcore-log: 
,03-29 13:30:37.667 11202 11266 I jxcore-log: # teardown
03-29 13:30:37.667 11202 11266 I jxcore-log: 
,03-29 13:30:39.842 11202 11266 I jxcore-log: ok 125 error should be null
03-29 13:30:39.842 11202 11266 I jxcore-log: 
,03-29 13:30:39.847 11202 11266 I jxcore-log: ok 126 error should be null
03-29 13:30:39.847 11202 11266 I jxcore-log: 
,03-29 13:30:39.852 11202 11266 I jxcore-log: # setup
03-29 13:30:39.852 11202 11266 I jxcore-log: 
,03-29 13:30:39.862  3481  3863 E Watchdog: !@Sync 8 [03-29 13:30:39.870]
,03-29 13:30:41.267 11202 11266 I jxcore-log: # 33. can get the network status
03-29 13:30:41.267 11202 11266 I jxcore-log: 
,03-29 13:30:42.412 11202 11266 I jxcore-log: ok 127 network status should have certain non-empty properties
03-29 13:30:42.412 11202 11266 I jxcore-log: 
,03-29 13:30:42.417 11202 11266 I jxcore-log: # teardown
03-29 13:30:42.417 11202 11266 I jxcore-log: 
,03-29 13:30:42.992  2895  4777 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-29 13:30:43.077  3481  4718 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-29 13:30:43.077  3481  4718 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-29 13:30:43.077  3481  4718 D BatteryService: online:4, current avg:36, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:42
,03-29 13:30:43.077  3481  3481 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-29 13:30:43.082  3481  4718 D BatteryService: stay LED for fully charged
,03-29 13:30:43.087  3481  3481 I MotionRecognitionService: Plugged
03-29 13:30:43.087  3481  3481 D MotionRecognitionService:   cableConnection= 1,
03-29 13:30:43.087  3481  3481 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-29 13:30:43.087  3481  3481 D MotionRecognitionService: skip setTransmitPower. ,
,03-29 13:30:43.097  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-29 13:30:43.097  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-29 13:30:43.097  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-29 13:30:43.117  5947  5947 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-29 13:30:43.117  5947  6065 D HeadsetStateMachine: Disconnected process message: 10
,03-29 13:30:43.127  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-29 13:30:43.127  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-29 13:30:43.127  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-29 13:30:43.127  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-29 13:30:44.252  3481  6174 D SSRM:n  : SIOP:: AP = 270, PST = 283 (W:16), CUR = 36, LCD = 0
,03-29 13:30:45.682 11202 11266 I jxcore-log: ok 128 error should be null
03-29 13:30:45.682 11202 11266 I jxcore-log: 
,03-29 13:30:45.682 11202 11266 I jxcore-log: ok 129 error should be null
03-29 13:30:45.682 11202 11266 I jxcore-log: 
,03-29 13:30:45.697 11202 11266 I jxcore-log: # setup
03-29 13:30:45.697 11202 11266 I jxcore-log: 
,03-29 13:30:46.287 11202 11266 I jxcore-log: # 34. wifi peer is marked unavailable if announcements stop
03-29 13:30:46.287 11202 11266 I jxcore-log: 
,03-29 13:30:46.557 11202 11266 I jxcore-log: ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
03-29 13:30:46.557 11202 11266 I jxcore-log: 
,03-29 13:30:46.587 11202 11266 I jxcore-log: ok 130 host address should match
03-29 13:30:46.587 11202 11266 I jxcore-log: 
,03-29 13:30:46.587 11202 11266 I jxcore-log: ok 131 port should match
03-29 13:30:46.587 11202 11266 I jxcore-log: 
,03-29 13:30:48.567 11202 11266 I jxcore-log: ok 132 host address should be null,
03-29 13:30:48.567 11202 11266 I jxcore-log: 
,03-29 13:30:48.577 11202 11266 I jxcore-log: ok 133 port should should be null
03-29 13:30:48.577 11202 11266 I jxcore-log: 
,03-29 13:30:48.602 11202 11266 I jxcore-log: # teardown
03-29 13:30:48.602 11202 11266 I jxcore-log: 
,03-29 13:30:49.162 11202 11266 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-29 13:30:49.162 11202 11266 I jxcore-log: 
,03-29 13:30:49.167 11202 11266 I jxcore-log: ok 134 error should be null
03-29 13:30:49.167 11202 11266 I jxcore-log: 
,03-29 13:30:49.167 11202 11266 I jxcore-log: ok 135 error should be null
03-29 13:30:49.167 11202 11266 I jxcore-log: 
,03-29 13:30:49.172 11202 11266 I jxcore-log: # setup
03-29 13:30:49.172 11202 11266 I jxcore-log: 
,03-29 13:30:49.342 11202 11266 I jxcore-log: # 35. Can call start/stopListeningForAdvertisements
03-29 13:30:49.342 11202 11266 I jxcore-log: 
,03-29 13:30:49.542 11202 11266 I io.jxcore.node.ConnectionHelper: start: Port number: 55532, start advertisements: false
,03-29 13:30:49.542 11202 11266 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-29 13:30:49.542 11202 11266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,03-29 13:30:49.542 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-29 13:30:49.547 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-29 13:30:49.552 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-29 13:30:49.552 11202 11266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-29 13:30:49.557  5947  6068 D BtGatt.GattService: registerClient() - UUID=6d4e2629-759c-41a2-8136-91bea0c886a7
,03-29 13:30:49.602  5947  6057 D BtGatt.GattService: onClientRegistered() - UUID=6d4e2629-759c-41a2-8136-91bea0c886a7, clientIf=6
03-29 13:30:49.602 11202 11214 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-29 13:30:49.602  5947  5956 D BtGatt.GattService: start scan with filters
,03-29 13:30:49.627  5947  5956 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 51
,03-29 13:30:49.632  5947  6061 D BtGatt.ScanManager: handling starting scan
03-29 13:30:49.632  5947  6061 D BtGatt.ScanManager: isFilteringSupported
03-29 13:30:49.632  5947  6061 D BluetoothAdapter: setting StandAloneBleMode
,03-29 13:30:49.642 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-29 13:30:49.642 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-29 13:30:49.642 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-29 13:30:49.642 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-29 13:30:49.642 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 13:30:49.642 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-29 13:30:49.642 11202 11202 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 13:30:49.647 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-29 13:30:49.647  5947  6057 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-29 13:30:49.647  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:30:49.647  5947  6061 D BtGatt.ScanManager: allow scan with filters
03-29 13:30:49.647  5947  6061 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-29 13:30:49.647  5947  6061 D BtGatt.ScanManager: set filter index= 6 for clientIf= 6
03-29 13:30:49.647  5947  6057 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-29 13:30:49.647  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 13:30:49.652  5947  6061 D BtGatt.ScanManager: Starting BLE batch scan,
03-29 13:30:49.652  5947  6061 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-29 13:30:49.652  5947  6057 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0,
03-29 13:30:49.652  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:30:49.652  5947  6057 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,03-29 13:30:49.652  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 13:30:49.657 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK,
03-29 13:30:49.657 11202 11202 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-29 13:30:49.657 11202 11202 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-29 13:30:49.662 11202 11202 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-29 13:30:49.662 11202 11266 I io.jxcore.node.ConnectionHelper: start: OK
03-29 13:30:49.662 11202 11266 I jxcore-log: ok 136 Can call startListeningForAdvertisements without error
03-29 13:30:49.662 11202 11266 I jxcore-log: 
03-29 13:30:49.662 11202 11266 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-29 13:30:49.662 11202 11266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-29 13:30:49.662 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-29 13:30:49.662 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-29 13:30:49.667  5947  5958 D BtGatt.GattService: stopScan() - queue size =1
03-29 13:30:49.672  5947  6061 D BtGatt.ScanManager: filter size is 1
03-29 13:30:49.672  5947  6061 D BtGatt.ScanManager: delete FilterIndex - 6
03-29 13:30:49.672  5947  6057 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-29 13:30:49.672  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:30:49.672  5947  6061 D BtGatt.ScanManager: stopping BLe Batch
,03-29 13:30:49.672  5947  5956 D BtGatt.GattService: unregisterClient() - clientIf=6
03-29 13:30:49.677  5947  6057 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-29 13:30:49.677  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:30:49.677  5947  6061 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-29 13:30:49.677  5947  6057 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-29 13:30:49.677  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 13:30:49.677 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-29 13:30:49.677 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-29 13:30:49.677 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-29 13:30:49.682 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,03-29 13:30:49.682 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-29 13:30:49.682 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-29 13:30:49.682 11202 11202 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-29 13:30:49.682 11202 11202 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-29 13:30:49.682 11202 11202 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-29 13:30:49.687 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 13:30:49.687 11202 11266 I jxcore-log: 
,03-29 13:30:49.687 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 13:30:49.687 11202 11266 I jxcore-log: 
,03-29 13:30:49.692 11202 11266 I jxcore-log: ok 137 Can call stopListeningForAdvertisements without error
03-29 13:30:49.692 11202 11266 I jxcore-log: 
,03-29 13:30:49.697 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 13:30:49.697 11202 11266 I jxcore-log: 
,03-29 13:30:49.697 11202 11266 I jxcore-log: # teardown
03-29 13:30:49.697 11202 11266 I jxcore-log: 
,03-29 13:30:49.792 11202 11266 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-29 13:30:49.792 11202 11266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-29 13:30:49.792 11202 11266 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 13:30:49.802 11202 11266 I jxcore-log: ok 138 Should be able to call stopListeningForAdvertisments in teardown
03-29 13:30:49.802 11202 11266 I jxcore-log: 
,03-29 13:30:49.807 11202 11266 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-29 13:30:49.807 11202 11266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 13:30:49.807 11202 11266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-29 13:30:49.807 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-29 13:30:49.807 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-29 13:30:49.807 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-29 13:30:49.807 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-29 13:30:49.807 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-29 13:30:49.807 11202 11266 D BluetoothLeScanner: could not find callback wrapper
03-29 13:30:49.807 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-29 13:30:49.812 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-29 13:30:49.812 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-29 13:30:49.812 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-29 13:30:49.812 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-29 13:30:49.812 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-29 13:30:49.812 11202 11202 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-29 13:30:49.812 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-29 13:30:49.812 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-29 13:30:49.817 11202 11202 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-29 13:30:49.827 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-29 13:30:49.837 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-29 13:30:49.837 11202 11202 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-29 13:30:49.842 11202 11202 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-29 13:30:49.842 11202 11202 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-29 13:30:49.847 11202 11202 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-29 13:30:49.847 11202 11266 I jxcore-log: ok 139 Should be able to call stopAdvertisingAndListening in teardown
03-29 13:30:49.847 11202 11266 I jxcore-log: 
,03-29 13:30:49.857 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 13:30:49.857 11202 11266 I jxcore-log: 
,03-29 13:30:49.862 11202 11266 I jxcore-log: # setup
03-29 13:30:49.862 11202 11266 I jxcore-log: 
,03-29 13:30:50.042 11202 11266 I jxcore-log: # 36. Calling startListeningForAdvertisements twice is NOT an error
03-29 13:30:50.042 11202 11266 I jxcore-log: 
,03-29 13:30:50.697 11202 11266 I io.jxcore.node.ConnectionHelper: start: Port number: 55532, start advertisements: false
,03-29 13:30:50.697 11202 11266 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-29 13:30:50.697 11202 11266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-29 13:30:50.697 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-29 13:30:50.702 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-29 13:30:50.707 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-29 13:30:50.707 11202 11266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-29 13:30:50.712  5947  5958 D BtGatt.GattService: registerClient() - UUID=2887118f-725f-4765-ad3f-ca387394b352
,03-29 13:30:50.752  5947  6057 D BtGatt.GattService: onClientRegistered() - UUID=2887118f-725f-4765-ad3f-ca387394b352, clientIf=6
,03-29 13:30:50.752 11202 11214 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-29 13:30:50.752  5947  5956 D BtGatt.GattService: start scan with filters
,03-29 13:30:50.762  5947  5956 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 52
,03-29 13:30:50.762 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-29 13:30:50.762 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-29 13:30:50.762 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-29 13:30:50.762 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-29 13:30:50.762 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 13:30:50.762  5947  6061 D BtGatt.ScanManager: handling starting scan
03-29 13:30:50.762  5947  6061 D BtGatt.ScanManager: isFilteringSupported
03-29 13:30:50.762  5947  6061 D BluetoothAdapter: setting StandAloneBleMode
03-29 13:30:50.762 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-29 13:30:50.762 11202 11202 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-29 13:30:50.767 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-29 13:30:50.767 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-29 13:30:50.767 11202 11266 I io.jxcore.node.ConnectionHelper: start: OK
,03-29 13:30:50.767 11202 11202 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-29 13:30:50.767 11202 11202 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 13:30:50.767 11202 11202 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-29 13:30:50.767  5947  6057 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-29 13:30:50.767  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:30:50.767  5947  6061 D BtGatt.ScanManager: allow scan with filters
,03-29 13:30:50.767  5947  6061 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-29 13:30:50.772  5947  6061 D BtGatt.ScanManager: set filter index= 7 for clientIf= 6
,03-29 13:30:50.772  5947  6057 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-29 13:30:50.772 11202 11266 I jxcore-log: ok 140 Can call startListeningForAdvertisements without error
03-29 13:30:50.772 11202 11266 I jxcore-log: 
03-29 13:30:50.772  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:30:50.772  5947  6061 D BtGatt.ScanManager: Starting BLE batch scan
03-29 13:30:50.772  5947  6061 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-29 13:30:50.772  5947  6057 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,03-29 13:30:50.772  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:30:50.777  5947  6057 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-29 13:30:50.777  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 13:30:50.777 11202 11266 I io.jxcore.node.ConnectionHelper: start: Port number: 55532, start advertisements: false
03-29 13:30:50.777 11202 11266 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-29 13:30:50.777 11202 11266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-29 13:30:50.777 11202 11266 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-29 13:30:50.777 11202 11266 I io.jxcore.node.ConnectionHelper: start: OK
,03-29 13:30:50.777 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 13:30:50.777 11202 11266 I jxcore-log: 
,03-29 13:30:50.777 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 13:30:50.777 11202 11266 I jxcore-log: 
,03-29 13:30:50.782 11202 11266 I jxcore-log: ok 141 Can call startListeningForAdvertisements twice without error
03-29 13:30:50.782 11202 11266 I jxcore-log: 
,03-29 13:30:50.787 11202 11266 I jxcore-log: # teardown
03-29 13:30:50.787 11202 11266 I jxcore-log: 
,03-29 13:30:50.942 11202 11266 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-29 13:30:50.942 11202 11266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
03-29 13:30:50.942 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,03-29 13:30:50.947 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-29 13:30:50.947  5947  5958 D BtGatt.GattService: stopScan() - queue size =1
03-29 13:30:50.947  5947  6061 D BtGatt.ScanManager: filter size is 1
03-29 13:30:50.947  5947  6061 D BtGatt.ScanManager: delete FilterIndex - 7
03-29 13:30:50.952  5947  6057 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-29 13:30:50.952  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:30:50.952  5947  6061 D BtGatt.ScanManager: stopping BLe Batch
,03-29 13:30:50.957  5947  6057 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-29 13:30:50.957  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:30:50.957  5947  6068 D BtGatt.GattService: unregisterClient() - clientIf=6
03-29 13:30:50.957  5947  6061 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-29 13:30:50.962  5947  6057 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-29 13:30:50.962  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 13:30:50.962 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-29 13:30:50.962 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-29 13:30:50.962 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-29 13:30:50.962 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-29 13:30:50.962 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-29 13:30:50.962 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-29 13:30:50.962 11202 11202 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-29 13:30:50.967 11202 11202 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-29 13:30:50.967 11202 11202 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-29 13:30:50.972 11202 11266 I jxcore-log: ok 142 Should be able to call stopListeningForAdvertisments in teardown,
03-29 13:30:50.972 11202 11266 I jxcore-log: 
03-29 13:30:50.972 11202 11266 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-29 13:30:50.972 11202 11266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
03-29 13:30:50.972 11202 11266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-29 13:30:50.972 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-29 13:30:50.972 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-29 13:30:50.972 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-29 13:30:50.972 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-29 13:30:50.972 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-29 13:30:50.972 11202 11266 D BluetoothLeScanner: could not find callback wrapper
03-29 13:30:50.972 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-29 13:30:50.977 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-29 13:30:50.977 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-29 13:30:50.977 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-29 13:30:50.977 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-29 13:30:50.977 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-29 13:30:50.977 11202 11202 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-29 13:30:50.977 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-29 13:30:50.977 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-29 13:30:50.977 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 13:30:50.977 11202 11266 I jxcore-log: 
,03-29 13:30:50.982 11202 11202 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-29 13:30:50.987 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-29 13:30:50.987 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-29 13:30:50.987 11202 11202 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-29 13:30:50.992 11202 11202 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-29 13:30:50.992 11202 11202 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 13:30:50.992 11202 11202 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 13:30:50.992 11202 11266 I jxcore-log: ok 143 Should be able to call stopAdvertisingAndListening in teardown
03-29 13:30:50.992 11202 11266 I jxcore-log: 
,03-29 13:30:50.997 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 13:30:50.997 11202 11266 I jxcore-log: 
,03-29 13:30:51.002 11202 11266 I jxcore-log: # setup
03-29 13:30:51.002 11202 11266 I jxcore-log: 
,03-29 13:30:51.322 11202 11266 I jxcore-log: # 37. Can call start/stopUpdateAdvertisingAndListening
03-29 13:30:51.322 11202 11266 I jxcore-log: 
,03-29 13:30:51.462 11202 11266 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true
,03-29 13:30:51.462 11202 11266 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-29 13:30:51.462 11202 11266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,03-29 13:30:51.462 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-29 13:30:51.467 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-29 13:30:51.467 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-29 13:30:51.472 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-29 13:30:51.472 11202 11266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-29 13:30:51.477  5947  6068 D BtGatt.GattService: registerClient() - UUID=9a2ba4a7-49db-4c4c-84e0-e9baee9ffdd5
,03-29 13:30:51.517  5947  6057 D BtGatt.GattService: onClientRegistered() - UUID=9a2ba4a7-49db-4c4c-84e0-e9baee9ffdd5, clientIf=6
,03-29 13:30:51.517 11202 11212 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-29 13:30:51.517  5947  5956 D BtGatt.GattService: start scan with filters
,03-29 13:30:51.532  5947  5956 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 53
,03-29 13:30:51.532 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-29 13:30:51.532 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-29 13:30:51.532 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-29 13:30:51.532 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-29 13:30:51.532  5947  6061 D BtGatt.ScanManager: handling starting scan
03-29 13:30:51.532  5947  6061 D BtGatt.ScanManager: isFilteringSupported
03-29 13:30:51.532 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 13:30:51.532  5947  6061 D BluetoothAdapter: setting StandAloneBleMode
03-29 13:30:51.532 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-29 13:30:51.532 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-29 13:30:51.532 11202 11202 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 13:30:51.532 11202 11266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
,03-29 13:30:51.532 11202 11266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 13:30:51.532 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 13:30:51.532 11202 11266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-29 13:30:51.532  5947  6057 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-29 13:30:51.532  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 13:30:51.532  5947  6061 D BtGatt.ScanManager: allow scan with filters
03-29 13:30:51.532  5947  6061 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-29 13:30:51.532  5947  6061 D BtGatt.ScanManager: set filter index= 8 for clientIf= 6
03-29 13:30:51.537  5947  6057 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,03-29 13:30:51.537  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:30:51.537  5947  6061 D BtGatt.ScanManager: Starting BLE batch scan
03-29 13:30:51.537  5947  6061 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-29 13:30:51.537  5947  5958 D BtGatt.GattService: registerClient() - UUID=df245a98-a665-4d82-bb93-6e356dc4668f
,03-29 13:30:51.537  5947  6057 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-29 13:30:51.537  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 13:30:51.542  5947  6057 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-29 13:30:51.542  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 13:30:51.582  5947  6057 D BtGatt.GattService: onClientRegistered() - UUID=df245a98-a665-4d82-bb93-6e356dc4668f, clientIf=7
,03-29 13:30:51.582 11202 11214 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-29 13:30:51.622  5947  6068 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 42
,03-29 13:30:51.627  5947  6060 D BtGatt.AdvertiseManager: message : 0
03-29 13:30:51.632  5947  6060 D BtGatt.AdvertiseManager: number of adv instance running0
03-29 13:30:51.632  5947  6060 D BtGatt.AdvertiseManager: size of list is =0
03-29 13:30:51.637  5947  6060 D BtGatt.AdvertiseManager: starting advertising
03-29 13:30:51.642  5947  6060 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-29 13:30:51.647  5947  6057 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-29 13:30:51.652  5947  6060 D BtGatt.AdvertiseManager: starting multi advertising
03-29 13:30:51.652  5947  6057 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
03-29 13:30:51.652  5947  6060 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-29 13:30:51.652  5947  6060 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
03-29 13:30:51.652 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-29 13:30:51.652 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-29 13:30:51.657 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-29 13:30:51.657 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-29 13:30:51.657 11202 11266 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-29 13:30:51.657 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-29 13:30:51.662 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-29 13:30:51.662 11202 11266 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-29 13:30:51.662 11202 11266 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-29 13:30:51.662 11202 11266 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-29 13:30:51.662 11202 11202 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-29 13:30:51.662 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-29 13:30:51.662 11202 11202 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-29 13:30:51.662 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-29 13:30:51.662 11202 11202 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-29 13:30:51.662 11202 11202 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-29 13:30:51.662 11202 11202 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-29 13:30:51.662 11202 11202 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-29 13:30:51.662 11202 11202 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-29 13:30:51.662 11202 11202 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 13:30:51.662 11202 11202 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-29 13:30:51.662 11202 11202 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-29 13:30:51.662 11202 11266 I io.jxcore.node.ConnectionHelper: start: OK
,03-29 13:30:51.672 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 13:30:51.672 11202 11266 I jxcore-log: 
03-29 13:30:51.677 11202 11718 D BluetoothSocket: bindListen(): myUserId = 0
03-29 13:30:51.677 11202 11718 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-29 13:30:51.682 11202 11718 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[92]}
03-29 13:30:51.682 11202 11718 D BluetoothSocket: bindListen(), new LocalSocket 
03-29 13:30:51.682 11202 11718 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-29 13:30:51.682 11202 11718 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1569da40
03-29 13:30:51.682 11202 11718 D BluetoothSocket: channel: 6
03-29 13:30:51.682 11202 11718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-29 13:30:51.687 11202 11266 I jxcore-log: ok 144 Can call startUpdateAdvertisingAndListening without error
03-29 13:30:51.687 11202 11266 I jxcore-log: 
03-29 13:30:51.687 11202 11266 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-29 13:30:51.692 11202 11266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-29 13:30:51.692 11202 11266 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-29 13:30:51.692 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-29 13:30:51.692 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-29 13:30:51.692 11202 11266 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2c119d79, channel: 6, state: LISTENING
03-29 13:30:51.692 11202 11266 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2c119d79, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1569da40, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@26111abemSocket: android.net.LocalSocket@1862771f impl:android.net.LocalSocketImpl@23325a6c fd:FileDescriptor[92]
03-29 13:30:51.692 11202 11266 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1862771f impl:android.net.LocalSocketImpl@23325a6c fd:FileDescriptor[92]
03-29 13:30:51.692 11202 11266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-29 13:30:51.692 11202 11718 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-29 13:30:51.692 11202 11718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-29 13:30:51.692 11202 11718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-29 13:30:51.697 11202 11202 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-29 13:30:51.697 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-29 13:30:51.697 11202 11202 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-29 13:30:51.697 11202 11202 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-29 13:30:51.697 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-29 13:30:51.697 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-29 13:30:51.697 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-29 13:30:51.697 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-29 13:30:51.697 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-29 13:30:51.702  5947  5956 D BtGatt.GattService: stopScan() - queue size =1,
03-29 13:30:51.702  5947  6061 D BtGatt.ScanManager: filter size is 1
03-29 13:30:51.702  5947  6061 D BtGatt.ScanManager: delete FilterIndex - 8
03-29 13:30:51.702  5947  6057 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-29 13:30:51.702  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:30:51.702  5947  6061 D BtGatt.ScanManager: stopping BLe Batch
03-29 13:30:51.707  5947  6057 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-29 13:30:51.707  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:30:51.707  5947  6061 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-29 13:30:51.707  5947  6057 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
03-29 13:30:51.707  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:30:51.707  5947  6057 D BtGatt.GattService: current time is 264693818905
03-29 13:30:51.707  5947  6057 D BtGatt.GattService: Batch record : [125, 64, -47, 60, 15, 71, 1, -128, -60, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0]
03-29 13:30:51.707  5947  6057 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-29 13:30:51.707  5947  6057 D ScanRecord: parseFromBytes
03-29 13:30:51.712  5947  6068 D BtGatt.GattService: unregisterClient() - clientIf=6
03-29 13:30:51.712 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-29 13:30:51.717 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-29 13:30:51.717 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,03-29 13:30:51.717 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
,03-29 13:30:51.717 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-29 13:30:51.717 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-29 13:30:51.717 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-29 13:30:51.722  5947  6060 D BtGatt.AdvertiseManager: message : 1
03-29 13:30:51.722  5947  6060 D BtGatt.AdvertiseManager: stop advertise for client 7
03-29 13:30:51.722  5947  6060 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-29 13:30:51.722  5947  6060 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-29 13:30:51.722  5947  6057 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-29 13:30:51.722  5947  6057 D BtGatt.GattService: Client app is not null!
03-29 13:30:51.722  5947  6068 D BtGatt.GattService: unregisterClient() - clientIf=7
03-29 13:30:51.727 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-29 13:30:51.727 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-29 13:30:51.727 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-29 13:30:51.727 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-29 13:30:51.727 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-29 13:30:51.727 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false,
03-29 13:30:51.727 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-29 13:30:51.727 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-29 13:30:51.732 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-29 13:30:51.732 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-29 13:30:51.732 11202 11202 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 13:30:51.732 11202 11202 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 13:30:51.732 11202 11202 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
,03-29 13:30:51.732 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
03-29 13:30:51.732 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-29 13:30:51.737 11202 11202 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-29 13:30:51.742 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
03-29 13:30:51.742 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 13:30:51.742 11202 11266 I jxcore-log: ,
03-29 13:30:51.747 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-29 13:30:51.752 11202 11202 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-29 13:30:51.752 11202 11202 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-29 13:30:51.752 11202 11202 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-29 13:30:51.752 11202 11202 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-29 13:30:51.752 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-29 13:30:51.752 11202 11266 I jxcore-log: 
,03-29 13:30:51.757 11202 11266 I jxcore-log: ok 145 Can call stopAdvertisingAndListening without error,
03-29 13:30:51.757 11202 11266 I jxcore-log: 
,03-29 13:30:51.767 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-29 13:30:51.767 11202 11266 I jxcore-log: 
,03-29 13:30:51.772 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 13:30:51.772 11202 11266 I jxcore-log: 
,03-29 13:30:51.772 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 13:30:51.772 11202 11266 I jxcore-log: 
,03-29 13:30:51.777 11202 11266 I jxcore-log: # teardown
03-29 13:30:51.777 11202 11266 I jxcore-log: 
,03-29 13:30:51.907 11202 11266 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-29 13:30:51.907 11202 11266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-29 13:30:51.912 11202 11266 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 13:30:51.912 11202 11266 I jxcore-log: ok 146 Should be able to call stopListeningForAdvertisments in teardown
03-29 13:30:51.912 11202 11266 I jxcore-log: 
,03-29 13:30:51.917 11202 11266 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-29 13:30:51.917 11202 11266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 13:30:51.917 11202 11266 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 13:30:51.922 11202 11266 I jxcore-log: ok 147 Should be able to call stopAdvertisingAndListening in teardown
03-29 13:30:51.922 11202 11266 I jxcore-log: 
,03-29 13:30:51.932 11202 11266 I jxcore-log: # setup
03-29 13:30:51.932 11202 11266 I jxcore-log: 
,03-29 13:30:52.072 11202 11266 I jxcore-log: # 38. Calling startUpdateAdvertisingAndListening twice is NOT an error
03-29 13:30:52.072 11202 11266 I jxcore-log: 
,03-29 13:30:52.162 11202 11266 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true
03-29 13:30:52.162 11202 11266 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-29 13:30:52.162 11202 11266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-29 13:30:52.162 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-29 13:30:52.167 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-29 13:30:52.167 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-29 13:30:52.167 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-29 13:30:52.167 11202 11266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-29 13:30:52.172  5947  6068 D BtGatt.GattService: registerClient() - UUID=bc3e5640-c60b-4e0a-b69e-94abda50a910
,03-29 13:30:52.217  5947  6057 D BtGatt.GattService: onClientRegistered() - UUID=bc3e5640-c60b-4e0a-b69e-94abda50a910, clientIf=6
,03-29 13:30:52.217 11202 11214 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-29 13:30:52.217  5947  5958 D BtGatt.GattService: start scan with filters
,03-29 13:30:52.237  5947  5958 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 54
,03-29 13:30:52.237  5947  6061 D BtGatt.ScanManager: handling starting scan
03-29 13:30:52.237  5947  6061 D BtGatt.ScanManager: isFilteringSupported
03-29 13:30:52.237  5947  6061 D BluetoothAdapter: setting StandAloneBleMode
,03-29 13:30:52.247  5947  6057 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-29 13:30:52.247  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 13:30:52.247  5947  6061 D BtGatt.ScanManager: allow scan with filters
03-29 13:30:52.247  5947  6061 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-29 13:30:52.247  5947  6061 D BtGatt.ScanManager: set filter index= 9 for clientIf= 6
03-29 13:30:52.252  5947  6057 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-29 13:30:52.252  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 13:30:52.252  5947  6061 D BtGatt.ScanManager: Starting BLE batch scan
03-29 13:30:52.252  5947  6061 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-29 13:30:52.257  5947  6057 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,03-29 13:30:52.257  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
03-29 13:30:52.257  5947  6057 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-29 13:30:52.257  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 13:30:52.262 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
03-29 13:30:52.262 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-29 13:30:52.262 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-29 13:30:52.262 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING],
03-29 13:30:52.262 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 13:30:52.262 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-29 13:30:52.262 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-29 13:30:52.262 11202 11266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
,03-29 13:30:52.262 11202 11266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-29 13:30:52.262 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false],
03-29 13:30:52.262 11202 11266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-29 13:30:52.262 11202 11202 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 13:30:52.267  5947  6068 D BtGatt.GattService: registerClient() - UUID=558c78fd-bc5b-4796-8f34-8ee635eb1e28
,03-29 13:30:52.307  5947  6057 D BtGatt.GattService: onClientRegistered() - UUID=558c78fd-bc5b-4796-8f34-8ee635eb1e28, clientIf=7,
03-29 13:30:52.307 11202 11212 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-29 13:30:52.322  5947  5956 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 43,
,03-29 13:30:52.322  5947  6060 D BtGatt.AdvertiseManager: message : 0,
,03-29 13:30:52.322  5947  6060 D BtGatt.AdvertiseManager: number of adv instance running0,
,03-29 13:30:52.322  5947  6060 D BtGatt.AdvertiseManager: size of list is =0
03-29 13:30:52.322  5947  6060 D BtGatt.AdvertiseManager: starting advertising
,03-29 13:30:52.322  5947  6060 D BtGatt.AdvertiseManager: isStandardAdvfalse
03-29 13:30:52.327  5947  6057 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
03-29 13:30:52.327  5947  6060 D BtGatt.AdvertiseManager: starting multi advertising
03-29 13:30:52.332  5947  6057 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-29 13:30:52.332  5947  6060 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-29 13:30:52.332  5947  6060 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0,
03-29 13:30:52.332 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-29 13:30:52.332 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK,
03-29 13:30:52.337 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
,03-29 13:30:52.337 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-29 13:30:52.337 11202 11266 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-29 13:30:52.337 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-29 13:30:52.337 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-29 13:30:52.337 11202 11266 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-29 13:30:52.337 11202 11266 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-29 13:30:52.337 11202 11266 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-29 13:30:52.337 11202 11266 I io.jxcore.node.ConnectionHelper: start: OK
03-29 13:30:52.337 11202 11202 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-29 13:30:52.337 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess,
03-29 13:30:52.337 11202 11202 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-29 13:30:52.337 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,03-29 13:30:52.337 11202 11202 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-29 13:30:52.337 11202 11202 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-29 13:30:52.337 11202 11202 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-29 13:30:52.337 11202 11202 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-29 13:30:52.337 11202 11202 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-29 13:30:52.337 11202 11202 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 13:30:52.337 11202 11202 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-29 13:30:52.337 11202 11202 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-29 13:30:52.337 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 13:30:52.337 11202 11266 I jxcore-log: 
03-29 13:30:52.342 11202 11266 I jxcore-log: ok 148 Can call startUpdateAdvertisingAndListening without error
03-29 13:30:52.342 11202 11266 I jxcore-log: 
03-29 13:30:52.342 11202 11734 D BluetoothSocket: bindListen(): myUserId = 0
,03-29 13:30:52.342 11202 11734 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-29 13:30:52.347 11202 11266 I io.jxcore.node.ConnectionHelper: start: Port number: 4243, start advertisements: true
03-29 13:30:52.347 11202 11266 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-29 13:30:52.347 11202 11266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-29 13:30:52.347 11202 11266 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-29 13:30:52.347 11202 11266 I io.jxcore.node.ConnectionHelper: start: OK
,03-29 13:30:52.347 11202 11734 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[92]}
03-29 13:30:52.347 11202 11734 D BluetoothSocket: bindListen(), new LocalSocket 
03-29 13:30:52.347 11202 11734 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-29 13:30:52.347 11202 11734 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2e20b158
03-29 13:30:52.347 11202 11734 D BluetoothSocket: channel: 6
03-29 13:30:52.347 11202 11734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-29 13:30:52.347 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 13:30:52.347 11202 11266 I jxcore-log: 
,03-29 13:30:52.347 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-29 13:30:52.347 11202 11266 I jxcore-log: 
,03-29 13:30:52.352 11202 11266 I jxcore-log: ok 149 Can call startUpdateAdvertisingAndListening twice without error
03-29 13:30:52.352 11202 11266 I jxcore-log: 
,03-29 13:30:52.357 11202 11266 I jxcore-log: # teardown
03-29 13:30:52.357 11202 11266 I jxcore-log: 
,03-29 13:30:53.212  3481  3834 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-29 13:30:53.212  3481  3834 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-29 13:30:53.212  3481  3834 D BatteryService: online:4, current avg:35, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:39
03-29 13:30:53.217  3481  3481 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-29 13:30:53.217  3481  3834 D BatteryService: stay LED for fully charged
03-29 13:30:53.222  3481  3481 I MotionRecognitionService: Plugged
03-29 13:30:53.222  3481  3481 D MotionRecognitionService:   cableConnection= 1
03-29 13:30:53.222  3481  3481 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-29 13:30:53.222  3481  3481 D MotionRecognitionService: skip setTransmitPower. 
,03-29 13:30:53.232  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-29 13:30:53.232  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,03-29 13:30:53.232  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-29 13:30:53.257  3481  3619 V AlarmManager: waitForAlarm result :4
,03-29 13:30:53.262  5947  5947 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-29 13:30:53.262  5947  6065 D HeadsetStateMachine: Disconnected process message: 10
,03-29 13:30:53.272  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-29 13:30:53.272  5947  5947 D BtGatt.ScanManager: awakened up at time 266256
03-29 13:30:53.272  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-29 13:30:53.272  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-29 13:30:53.272  5947  6061 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-29 13:30:53.272  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-29 13:30:53.277  5947  6057 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
03-29 13:30:53.277  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:30:53.277  5947  6057 D BtGatt.GattService: current time is 266263682572
03-29 13:30:53.277  5947  6057 D BtGatt.GattService: Batch record : [-41, 29, 57, -26, -43, 70, 1, -128, -64, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, 28, 114, -31, -26, -120, 120, 1, -128, -62, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0]
03-29 13:30:53.277  5947  6057 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-29 13:30:53.277  5947  6057 D ScanRecord: parseFromBytes
,03-29 13:30:53.277  5947  6057 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-29 13:30:53.277  5947  6057 D ScanRecord: parseFromBytes
03-29 13:30:53.277  5947  6057 D BtGatt.GattService: result: ScanResult{mDevice=78:88:E6:E1:72:1C, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-62, mTimestampNanos=266213864614}
03-29 13:30:53.277  5947  6057 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-29 13:30:53.282  5947  6057 D BtGatt.GattService: result: ScanResult{mDevice=46:D5:E6:39:1D:D7, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-64, mTimestampNanos=266163864614}
03-29 13:30:53.282  5947  6057 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-29 13:30:53.282 11202 11212 D ScanRecord: parseFromBytes
03-29 13:30:53.282 11202 11212 D ScanRecord: parseFromBytes
,03-29 13:30:53.282 11202 11202 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:CF:C5:D9:E5:61], added - the peer count is 1
03-29 13:30:53.282 11202 11202 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 2
03-29 13:30:53.282 11202 11202 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:CF:C5:D9:E5:61], Bluetooth address: F8:CF:C5:D9:E5:61, device name: , device address: 
,03-29 13:30:53.282 11202 11202 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
,03-29 13:30:53.282 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
03-29 13:30:53.282 11202 11266 I jxcore-log: 
,03-29 13:30:53.287 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
03-29 13:30:53.287 11202 11266 I jxcore-log: 
,03-29 13:30:53.742 11202 11266 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-29 13:30:53.742 11202 11266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
,03-29 13:30:53.747 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,03-29 13:30:53.747 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-29 13:30:53.752  5947  5956 D BtGatt.GattService: stopScan() - queue size =1
03-29 13:30:53.752  5947  6061 D BtGatt.ScanManager: filter size is 1
03-29 13:30:53.752  5947  6061 D BtGatt.ScanManager: delete FilterIndex - 9
03-29 13:30:53.752  5947  6057 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,03-29 13:30:53.752  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,03-29 13:30:53.752  5947  6061 D BtGatt.ScanManager: stopping BLe Batch
,03-29 13:30:53.757  5947  6057 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-29 13:30:53.757  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 13:30:53.757  5947  6061 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-29 13:30:53.762  5947  6057 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
,03-29 13:30:53.762  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,03-29 13:30:53.762  5947  6057 D BtGatt.GattService: current time is 266747591405
,03-29 13:30:53.762  5947  6057 D BtGatt.GattService: Batch record : [28, 114, -31, -26, -120, 120, 1, -128, -62, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0, -41, 29, 57, -26, -43, 70, 1, -128, -65, 5, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0],
,03-29 13:30:53.762  5947  6057 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-29 13:30:53.762  5947  6057 D ScanRecord: parseFromBytes
,03-29 13:30:53.762  5947  6057 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-29 13:30:53.762  5947  6057 D ScanRecord: parseFromBytes,
03-29 13:30:53.772  5947  6068 D BtGatt.GattService: unregisterClient() - clientIf=6
03-29 13:30:53.772 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-29 13:30:53.772 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED,
03-29 13:30:53.772 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-29 13:30:53.772 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-29 13:30:53.772 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING],
03-29 13:30:53.772 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true,
03-29 13:30:53.777 11202 11202 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-29 13:30:53.777 11202 11202 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-29 13:30:53.777 11202 11202 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-29 13:30:53.787 11202 11266 I jxcore-log: ok 150 Should be able to call stopListeningForAdvertisments in teardown,
03-29 13:30:53.787 11202 11266 I jxcore-log: 
,03-29 13:30:53.787 11202 11266 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-29 13:30:53.787 11202 11266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-29 13:30:53.787 11202 11266 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,03-29 13:30:53.787 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-29 13:30:53.787 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,03-29 13:30:53.787 11202 11266 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1e562b17, channel: 6, state: LISTENING
03-29 13:30:53.787 11202 11266 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1e562b17, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2e20b158, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@169b8b04mSocket: android.net.LocalSocket@dad98ed impl:android.net.LocalSocketImpl@2bd08322 fd:FileDescriptor[92]
,03-29 13:30:53.792 11202 11266 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@dad98ed impl:android.net.LocalSocketImpl@2bd08322 fd:FileDescriptor[92]
,03-29 13:30:53.792 11202 11266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed,
,03-29 13:30:53.792 11202 11734 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-29 13:30:53.792 11202 11734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-29 13:30:53.792 11202 11734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,03-29 13:30:53.792 11202 11202 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-29 13:30:53.792 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-29 13:30:53.792 11202 11202 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-29 13:30:53.792 11202 11202 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-29 13:30:53.797 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-29 13:30:53.797 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-29 13:30:53.797 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-29 13:30:53.797 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-29 13:30:53.797 11202 11266 D BluetoothLeScanner: could not find callback wrapper,
03-29 13:30:53.797 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-29 13:30:53.797 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-29 13:30:53.802  5947  6060 D BtGatt.AdvertiseManager: message : 1,
,03-29 13:30:53.802  5947  6060 D BtGatt.AdvertiseManager: stop advertise for client 7
,03-29 13:30:53.802  5947  6060 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-29 13:30:53.802  5947  6060 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-29 13:30:53.802  5947  6057 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-29 13:30:53.802  5947  6057 D BtGatt.GattService: Client app is not null!
03-29 13:30:53.807  5947  5958 D BtGatt.GattService: unregisterClient() - clientIf=7
,03-29 13:30:53.812 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-29 13:30:53.812 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-29 13:30:53.812 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-29 13:30:53.812 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-29 13:30:53.812 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-29 13:30:53.812 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-29 13:30:53.812 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-29 13:30:53.812 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-29 13:30:53.812 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-29 13:30:53.812 11202 11266 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-29 13:30:53.812 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-29 13:30:53.812 11202 11202 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-29 13:30:53.812 11202 11202 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 13:30:53.812 11202 11202 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-29 13:30:53.812 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-29 13:30:53.812 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-29 13:30:53.812 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-29 13:30:53.812 11202 11266 I jxcore-log: 
,03-29 13:30:53.817 11202 11266 I jxcore-log: ok 151 Should be able to call stopAdvertisingAndListening in teardown
03-29 13:30:53.817 11202 11266 I jxcore-log: 
,03-29 13:30:53.822 11202 11202 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-29 13:30:53.827 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-29 13:30:53.827 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-29 13:30:53.827 11202 11202 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-29 13:30:53.832 11202 11202 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-29 13:30:53.832 11202 11202 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-29 13:30:53.837 11202 11266 I jxcore-log: # setup
03-29 13:30:53.837 11202 11266 I jxcore-log: 
,03-29 13:30:53.837 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 13:30:53.837 11202 11266 I jxcore-log: 
,03-29 13:30:53.842 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 13:30:53.842 11202 11266 I jxcore-log: 
,03-29 13:30:54.002 11202 11266 I jxcore-log: # 39. peerAvailabilityChange is called
03-29 13:30:54.002 11202 11266 I jxcore-log: 
,03-29 13:30:54.287  3481  6174 D SSRM:n  : SIOP:: AP = 270, PST = 283 (W:16), CUR = 35, LCD = 0
,03-29 13:30:54.317 11202 11266 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true
,03-29 13:30:54.317 11202 11266 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-29 13:30:54.317 11202 11266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-29 13:30:54.317 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-29 13:30:54.322 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-29 13:30:54.322 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-29 13:30:54.327 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-29 13:30:54.327 11202 11266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-29 13:30:54.332  5947  5958 D BtGatt.GattService: registerClient() - UUID=f81fe079-c0a9-4a62-9f7e-8f2fae4ca101
,03-29 13:30:54.372  5947  6057 D BtGatt.GattService: onClientRegistered() - UUID=f81fe079-c0a9-4a62-9f7e-8f2fae4ca101, clientIf=6
03-29 13:30:54.372 11202 11214 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-29 13:30:54.382  5947  5956 D BtGatt.GattService: start scan with filters
,03-29 13:30:54.407  5947  5956 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 55
,03-29 13:30:54.407 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-29 13:30:54.407 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-29 13:30:54.407 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-29 13:30:54.407 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-29 13:30:54.407 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 13:30:54.407 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-29 13:30:54.407 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-29 13:30:54.407  5947  6061 D BtGatt.ScanManager: handling starting scan
03-29 13:30:54.407 11202 11266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
,03-29 13:30:54.407  5947  6061 D BtGatt.ScanManager: isFilteringSupported
03-29 13:30:54.407  5947  6061 D BluetoothAdapter: setting StandAloneBleMode
03-29 13:30:54.407 11202 11266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 13:30:54.407 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 13:30:54.407 11202 11266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-29 13:30:54.407 11202 11202 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-29 13:30:54.412  5947  5958 D BtGatt.GattService: registerClient() - UUID=bb609db3-1bef-42a3-9151-10f5e59e88c9
,03-29 13:30:54.417  5947  6057 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1,
03-29 13:30:54.417  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:30:54.417  5947  6061 D BtGatt.ScanManager: allow scan with filters
,03-29 13:30:54.417  5947  6061 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-29 13:30:54.417  5947  6061 D BtGatt.ScanManager: set filter index= 10 for clientIf= 6
03-29 13:30:54.417  5947  6057 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-29 13:30:54.417  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 13:30:54.417  5947  6061 D BtGatt.ScanManager: Starting BLE batch scan
03-29 13:30:54.417  5947  6061 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-29 13:30:54.422  5947  6057 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0,
03-29 13:30:54.422  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 13:30:54.422  5947  6057 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-29 13:30:54.422  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 13:30:54.457  5947  6057 D BtGatt.GattService: onClientRegistered() - UUID=bb609db3-1bef-42a3-9151-10f5e59e88c9, clientIf=7
,03-29 13:30:54.457 11202 11212 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-29 13:30:54.472  5947  5956 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 44,
03-29 13:30:54.472  5947  6060 D BtGatt.AdvertiseManager: message : 0
,03-29 13:30:54.472  5947  6060 D BtGatt.AdvertiseManager: number of adv instance running0
03-29 13:30:54.472  5947  6060 D BtGatt.AdvertiseManager: size of list is =0
,03-29 13:30:54.472  5947  6060 D BtGatt.AdvertiseManager: starting advertising
,03-29 13:30:54.472  5947  6060 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-29 13:30:54.477  5947  6057 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-29 13:30:54.477  5947  6060 D BtGatt.AdvertiseManager: starting multi advertising
,03-29 13:30:54.482  5947  6057 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
03-29 13:30:54.482  5947  6060 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-29 13:30:54.482  5947  6060 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
03-29 13:30:54.482 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-29 13:30:54.482 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-29 13:30:54.487 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-29 13:30:54.487 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-29 13:30:54.487 11202 11266 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,03-29 13:30:54.487 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-29 13:30:54.487 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-29 13:30:54.487 11202 11266 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-29 13:30:54.487 11202 11266 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-29 13:30:54.487 11202 11266 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-29 13:30:54.487 11202 11202 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-29 13:30:54.487 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-29 13:30:54.487 11202 11202 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-29 13:30:54.487 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-29 13:30:54.487 11202 11202 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-29 13:30:54.487 11202 11202 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
,03-29 13:30:54.487 11202 11202 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-29 13:30:54.487 11202 11202 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-29 13:30:54.487 11202 11202 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-29 13:30:54.487 11202 11202 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-29 13:30:54.492 11202 11202 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,03-29 13:30:54.492 11202 11202 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-29 13:30:54.492 11202 11266 I io.jxcore.node.ConnectionHelper: start: OK
,03-29 13:30:54.492 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false},
03-29 13:30:54.492 11202 11266 I jxcore-log: 
03-29 13:30:54.492 11202 11763 D BluetoothSocket: bindListen(): myUserId = 0
,03-29 13:30:54.492 11202 11763 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-29 13:30:54.497 11202 11266 I jxcore-log: ok 152 Can call startUpdateAdvertisingAndListeningwithout error
03-29 13:30:54.497 11202 11266 I jxcore-log: 
,03-29 13:30:54.497 11202 11763 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[92]}
,03-29 13:30:54.497 11202 11763 D BluetoothSocket: bindListen(), new LocalSocket ,
03-29 13:30:54.497 11202 11763 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-29 13:30:54.497 11202 11763 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1f17af6e
03-29 13:30:54.497 11202 11763 D BluetoothSocket: channel: 6
,03-29 13:30:54.497 11202 11763 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-29 13:30:54.507 11202 11266 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: false,
03-29 13:30:54.507 11202 11266 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-29 13:30:54.507 11202 11266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
,03-29 13:30:54.507 11202 11266 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-29 13:30:54.507 11202 11266 I io.jxcore.node.ConnectionHelper: start: OK
,03-29 13:30:54.507 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false},
03-29 13:30:54.507 11202 11266 I jxcore-log: 
,03-29 13:30:54.527 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-29 13:30:54.527 11202 11266 I jxcore-log: 
,03-29 13:30:54.527 11202 11266 I jxcore-log: ok 153 Can call startListeningForAdvertisements without error
03-29 13:30:54.527 11202 11266 I jxcore-log: 
,03-29 13:30:55.422  3481  3619 V AlarmManager: waitForAlarm result :4
,03-29 13:30:55.437  5947  5947 D BtGatt.ScanManager: awakened up at time 268420
,03-29 13:30:55.442  5947  6061 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-29 13:30:55.452  5947  6057 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
03-29 13:30:55.452  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:30:55.452  5947  6057 D BtGatt.GattService: current time is 268437581156
03-29 13:30:55.452  5947  6057 D BtGatt.GattService: Batch record : [73, 94, -23, -116, 61, 117, 1, -128, -70, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, 83, 91, 63, -63, -49, 68, 1, -128, -55, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0]
03-29 13:30:55.452  5947  6057 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-29 13:30:55.452  5947  6057 D ScanRecord: parseFromBytes
03-29 13:30:55.452  5947  6057 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-29 13:30:55.452  5947  6057 D ScanRecord: parseFromBytes
,03-29 13:30:55.452  5947  6057 D BtGatt.GattService: result: ScanResult{mDevice=75:3D:8C:E9:5E:49, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-70, mTimestampNanos=268387868114}
03-29 13:30:55.452  5947  6057 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
,03-29 13:30:55.452  5947  6057 D BtGatt.GattService: result: ScanResult{mDevice=44:CF:C1:3F:5B:53, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-55, mTimestampNanos=268337868114}
,03-29 13:30:55.452  5947  6057 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-29 13:30:55.457 11202 11212 D ScanRecord: parseFromBytes
,03-29 13:30:55.457 11202 11212 D ScanRecord: parseFromBytes,
03-29 13:30:55.457 11202 11202 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 1
03-29 13:30:55.457 11202 11202 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:CF:C5:D9:E5:61], added - the peer count is 2
,03-29 13:30:55.457 11202 11202 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
03-29 13:30:55.457 11202 11202 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:CF:C5:D9:E5:61], Bluetooth address: F8:CF:C5:D9:E5:61, device name: , device address: 
,03-29 13:30:55.467 11202 11266 I jxcore-log: ok 154 peers must be an array,
03-29 13:30:55.467 11202 11266 I jxcore-log: 
,03-29 13:30:55.467 11202 11266 I jxcore-log: ok 155 peers must not be zero-length
03-29 13:30:55.467 11202 11266 I jxcore-log: 
,03-29 13:30:55.467 11202 11266 I jxcore-log: ok 156 peer must have peerIdentifier
03-29 13:30:55.467 11202 11266 I jxcore-log: 
,03-29 13:30:55.472 11202 11266 I jxcore-log: ok 157 peerIdentifier must be a string
03-29 13:30:55.472 11202 11266 I jxcore-log: 
,03-29 13:30:55.472 11202 11266 I jxcore-log: ok 158 peer must have peerAvailable
03-29 13:30:55.472 11202 11266 I jxcore-log: 
,03-29 13:30:55.472 11202 11266 I jxcore-log: ok 159 peer must have pleaseConnect
03-29 13:30:55.472 11202 11266 I jxcore-log: 
,03-29 13:30:55.487 11202 11266 I jxcore-log: # teardown
03-29 13:30:55.487 11202 11266 I jxcore-log: 
,03-29 13:30:56.082 11202 11266 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-29 13:30:56.087 11202 11266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
,03-29 13:30:56.087 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,03-29 13:30:56.092 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-29 13:30:56.092  5947  6068 D BtGatt.GattService: stopScan() - queue size =1,
03-29 13:30:56.092  5947  6061 D BtGatt.ScanManager: filter size is 1
,03-29 13:30:56.092  5947  6061 D BtGatt.ScanManager: delete FilterIndex - 10
,03-29 13:30:56.097  5947  6057 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-29 13:30:56.097  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:30:56.097  5947  6061 D BtGatt.ScanManager: stopping BLe Batch
03-29 13:30:56.097  5947  6057 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-29 13:30:56.097  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
03-29 13:30:56.097  5947  6061 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-29 13:30:56.102  5947  6057 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
03-29 13:30:56.102  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:30:56.102  5947  6057 D BtGatt.GattService: current time is 269088106114
03-29 13:30:56.102  5947  6057 D BtGatt.GattService: Batch record : [83, 91, 63, -63, -49, 68, 1, -128, -61, 6, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0, 73, 94, -23, -116, 61, 117, 1, -128, -75, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-29 13:30:56.102  5947  6057 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-29 13:30:56.102  5947  6057 D ScanRecord: parseFromBytes,
03-29 13:30:56.102  5947  6057 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-29 13:30:56.102  5947  6057 D ScanRecord: parseFromBytes,
,03-29 13:30:56.112  5947  5958 D BtGatt.GattService: unregisterClient() - clientIf=6
03-29 13:30:56.112 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-29 13:30:56.112 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED,
03-29 13:30:56.112 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-29 13:30:56.112 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
,03-29 13:30:56.112 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-29 13:30:56.112 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true,
,03-29 13:30:56.117 11202 11202 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-29 13:30:56.117 11202 11202 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-29 13:30:56.117 11202 11202 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-29 13:30:56.122 11202 11266 I jxcore-log: ok 160 Should be able to call stopListeningForAdvertisments in teardown
03-29 13:30:56.122 11202 11266 I jxcore-log: 
,03-29 13:30:56.122 11202 11266 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-29 13:30:56.122 11202 11266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-29 13:30:56.122 11202 11266 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,03-29 13:30:56.122 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-29 13:30:56.122 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-29 13:30:56.122 11202 11266 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@304df8a5, channel: 6, state: LISTENING
,03-29 13:30:56.127 11202 11266 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@304df8a5, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1f17af6e, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@793547amSocket: android.net.LocalSocket@2dd4542b impl:android.net.LocalSocketImpl@394f2088 fd:FileDescriptor[92]
,03-29 13:30:56.127 11202 11266 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2dd4542b impl:android.net.LocalSocketImpl@394f2088 fd:FileDescriptor[92]
,03-29 13:30:56.127 11202 11266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-29 13:30:56.127 11202 11763 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-29 13:30:56.127 11202 11763 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-29 13:30:56.127 11202 11763 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-29 13:30:56.127 11202 11202 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-29 13:30:56.132 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-29 13:30:56.132 11202 11202 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-29 13:30:56.132 11202 11202 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED,
03-29 13:30:56.132 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-29 13:30:56.132 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-29 13:30:56.132 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-29 13:30:56.132 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-29 13:30:56.132 11202 11266 D BluetoothLeScanner: could not find callback wrapper
,03-29 13:30:56.132 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-29 13:30:56.132 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-29 13:30:56.137  5947  6060 D BtGatt.AdvertiseManager: message : 1,
,03-29 13:30:56.137  5947  6060 D BtGatt.AdvertiseManager: stop advertise for client 7
03-29 13:30:56.137  5947  6060 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-29 13:30:56.137  5947  6060 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,03-29 13:30:56.137  5947  6057 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-29 13:30:56.137  5947  6057 D BtGatt.GattService: Client app is not null!
,03-29 13:30:56.142  5947  5956 D BtGatt.GattService: unregisterClient() - clientIf=7,
,03-29 13:30:56.147 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-29 13:30:56.147 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-29 13:30:56.147 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,03-29 13:30:56.147 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,03-29 13:30:56.147 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-29 13:30:56.147 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false,
03-29 13:30:56.147 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped,
03-29 13:30:56.147 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...,
,03-29 13:30:56.152 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-29 13:30:56.152 11202 11266 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
,03-29 13:30:56.152 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-29 13:30:56.152 11202 11202 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 13:30:56.152 11202 11202 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 13:30:56.152 11202 11202 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-29 13:30:56.152 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
03-29 13:30:56.152 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener,
,03-29 13:30:56.157 11202 11202 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-29 13:30:56.162 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-29 13:30:56.162 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-29 13:30:56.162 11202 11202 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-29 13:30:56.167 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-29 13:30:56.167 11202 11266 I jxcore-log: 
03-29 13:30:56.167 11202 11266 I jxcore-log: ok 161 Should be able to call stopAdvertisingAndListening in teardown
03-29 13:30:56.167 11202 11266 I jxcore-log: 
,03-29 13:30:56.177 11202 11202 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-29 13:30:56.177 11202 11202 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-29 13:30:56.182 11202 11266 I jxcore-log: # setup
03-29 13:30:56.182 11202 11266 I jxcore-log: 
,03-29 13:30:56.187 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 13:30:56.187 11202 11266 I jxcore-log: 
,03-29 13:30:56.187 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 13:30:56.187 11202 11266 I jxcore-log: 
,03-29 13:30:56.292 11202 11266 I jxcore-log: # 40. Can connect to a remote peer
03-29 13:30:56.292 11202 11266 I jxcore-log: 
,03-29 13:30:56.947 11202 11266 I io.jxcore.node.ConnectionHelper: start: Port number: 58543, start advertisements: true
,03-29 13:30:56.947 11202 11266 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-29 13:30:56.952 11202 11266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,03-29 13:30:56.952 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-29 13:30:56.957 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-29 13:30:56.957 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-29 13:30:56.957 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-29 13:30:56.957 11202 11266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-29 13:30:56.962  5947  5956 D BtGatt.GattService: registerClient() - UUID=4e8ae88c-d6db-4ea5-bec6-f910e40571a0
,03-29 13:30:57.007  5947  6057 D BtGatt.GattService: onClientRegistered() - UUID=4e8ae88c-d6db-4ea5-bec6-f910e40571a0, clientIf=6
03-29 13:30:57.007 11202 11214 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-29 13:30:57.012  5947  6068 D BtGatt.GattService: start scan with filters,
,03-29 13:30:57.037  5947  6068 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 56
,03-29 13:30:57.037  5947  6061 D BtGatt.ScanManager: handling starting scan
03-29 13:30:57.037  5947  6061 D BtGatt.ScanManager: isFilteringSupported
03-29 13:30:57.037  5947  6061 D BluetoothAdapter: setting StandAloneBleMode
,03-29 13:30:57.047  5947  6057 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-29 13:30:57.047  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 13:30:57.047  5947  6061 D BtGatt.ScanManager: allow scan with filters
03-29 13:30:57.047  5947  6061 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-29 13:30:57.047  5947  6061 D BtGatt.ScanManager: set filter index= 11 for clientIf= 6
03-29 13:30:57.047  5947  6057 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-29 13:30:57.047  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 13:30:57.052  5947  6061 D BtGatt.ScanManager: Starting BLE batch scan
,03-29 13:30:57.052  5947  6061 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-29 13:30:57.052  5947  6057 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,03-29 13:30:57.052  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:30:57.057  5947  6057 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,03-29 13:30:57.057  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,03-29 13:30:57.062 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-29 13:30:57.062 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-29 13:30:57.062 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-29 13:30:57.062 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-29 13:30:57.062 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 13:30:57.062 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-29 13:30:57.062 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
,03-29 13:30:57.062 11202 11266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-29 13:30:57.062 11202 11266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 13:30:57.062 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 13:30:57.062 11202 11266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-29 13:30:57.062 11202 11202 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 13:30:57.067  5947  5956 D BtGatt.GattService: registerClient() - UUID=f186b2a2-298b-4245-94ef-d317f388c1e2
,03-29 13:30:57.107  5947  6057 D BtGatt.GattService: onClientRegistered() - UUID=f186b2a2-298b-4245-94ef-d317f388c1e2, clientIf=7,
,03-29 13:30:57.112 11202 11212 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-29 13:30:57.137  5947  5958 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 45
,03-29 13:30:57.137  5947  6060 D BtGatt.AdvertiseManager: message : 0
,03-29 13:30:57.137  5947  6060 D BtGatt.AdvertiseManager: number of adv instance running0
03-29 13:30:57.137  5947  6060 D BtGatt.AdvertiseManager: size of list is =0
,03-29 13:30:57.142  5947  6060 D BtGatt.AdvertiseManager: starting advertising
03-29 13:30:57.142  5947  6060 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-29 13:30:57.147  5947  6057 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-29 13:30:57.147  5947  6060 D BtGatt.AdvertiseManager: starting multi advertising
,03-29 13:30:57.152  5947  6057 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-29 13:30:57.152  5947  6060 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-29 13:30:57.152  5947  6060 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,03-29 13:30:57.152 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-29 13:30:57.152 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-29 13:30:57.157 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-29 13:30:57.157 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-29 13:30:57.157 11202 11266 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-29 13:30:57.157 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-29 13:30:57.157 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-29 13:30:57.157 11202 11266 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-29 13:30:57.157 11202 11266 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-29 13:30:57.157 11202 11266 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-29 13:30:57.157 11202 11202 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-29 13:30:57.157 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-29 13:30:57.157 11202 11202 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-29 13:30:57.157 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-29 13:30:57.157 11202 11202 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-29 13:30:57.157 11202 11202 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-29 13:30:57.157 11202 11202 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-29 13:30:57.157 11202 11202 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-29 13:30:57.157 11202 11202 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-29 13:30:57.157 11202 11202 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 13:30:57.157 11202 11202 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-29 13:30:57.157 11202 11202 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-29 13:30:57.157 11202 11266 I io.jxcore.node.ConnectionHelper: start: OK
,03-29 13:30:57.167 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false},
03-29 13:30:57.167 11202 11266 I jxcore-log: 
,03-29 13:30:57.167 11202 11784 D BluetoothSocket: bindListen(): myUserId = 0,
03-29 13:30:57.167 11202 11784 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-29 13:30:57.172 11202 11784 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[93]},
,03-29 13:30:57.172 11202 11784 D BluetoothSocket: bindListen(), new LocalSocket 
03-29 13:30:57.172 11202 11784 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,03-29 13:30:57.177 11202 11784 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@18f9bd34
03-29 13:30:57.177 11202 11784 D BluetoothSocket: channel: 6
,03-29 13:30:57.177 11202 11784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-29 13:30:57.177 11202 11266 I jxcore-log: ok 162 Can call startUpdateAdvertisingAndListening without error
03-29 13:30:57.177 11202 11266 I jxcore-log: 
,03-29 13:30:57.182 11202 11266 I io.jxcore.node.ConnectionHelper: start: Port number: 58543, start advertisements: false
,03-29 13:30:57.182 11202 11266 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-29 13:30:57.182 11202 11266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
,03-29 13:30:57.182 11202 11266 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 13:30:57.182 11202 11266 I io.jxcore.node.ConnectionHelper: start: OK
,03-29 13:30:57.187 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 13:30:57.187 11202 11266 I jxcore-log: 
,03-29 13:30:57.187 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-29 13:30:57.187 11202 11266 I jxcore-log: 
,03-29 13:30:57.192 11202 11266 I jxcore-log: ok 163 Can call startListeningForAdvertisements without error
03-29 13:30:57.192 11202 11266 I jxcore-log: 
,03-29 13:30:57.607  3481  6205 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,03-29 13:30:58.057  3481  3619 V AlarmManager: waitForAlarm result :4
,03-29 13:30:58.067  5947  5947 D BtGatt.ScanManager: awakened up at time 271053
03-29 13:30:58.072  5947  6061 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-29 13:30:58.077  5947  6057 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
03-29 13:30:58.077  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:30:58.077  5947  6057 D BtGatt.GattService: current time is 271064946531
,03-29 13:30:58.082  5947  6057 D BtGatt.GattService: Batch record : [110, 107, -32, 25, 105, 114, 1, -128, -65, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -106, -95, -79, -6, -5, 114, 1, -128, -53, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0]
03-29 13:30:58.082  5947  6057 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81],
,03-29 13:30:58.082  5947  6057 D ScanRecord: parseFromBytes
03-29 13:30:58.082  5947  6057 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
,03-29 13:30:58.082  5947  6057 D ScanRecord: parseFromBytes,
03-29 13:30:58.082  5947  6057 D BtGatt.GattService: result: ScanResult{mDevice=72:FB:FA:B1:A1:96, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-53, mTimestampNanos=271015257948}
03-29 13:30:58.082  5947  6057 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
,03-29 13:30:58.082  5947  6057 D BtGatt.GattService: result: ScanResult{mDevice=72:69:19:E0:6B:6E, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-65, mTimestampNanos=270965257948}
03-29 13:30:58.082  5947  6057 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-29 13:30:58.082 11202 11214 D ScanRecord: parseFromBytes
03-29 13:30:58.082 11202 11214 D ScanRecord: parseFromBytes
03-29 13:30:58.082 11202 11202 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:CF:C5:D9:E5:61], added - the peer count is 1
,03-29 13:30:58.082 11202 11202 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 2
03-29 13:30:58.082 11202 11202 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:CF:C5:D9:E5:61], Bluetooth address: F8:CF:C5:D9:E5:61, device name: , device address: 
,03-29 13:30:58.082 11202 11202 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: ,
03-29 13:30:58.097 11202 11266 I jxcore-log: INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"F8:CF:C5:D9:E5:61","peerAvailable":true,"pleaseConnect":false}]
03-29 13:30:58.097 11202 11266 I jxcore-log: 
,03-29 13:30:58.112 11202 11266 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID F8:CF:C5:D9:E5:61
,03-29 13:30:58.112 11202 11266 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> F8:CF:C5:D9:E5:61]
,03-29 13:30:58.117 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address F8:CF:C5:D9:E5:61
,03-29 13:30:58.117 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,03-29 13:30:58.117 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,03-29 13:30:58.117 11202 11266 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null F8:CF:C5:D9:E5:61
,03-29 13:30:58.122 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address F8:CF:C5:D9:E5:61
03-29 13:30:58.122 11202 11266 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: F8:CF:C5:D9:E5:61)
,03-29 13:30:58.122 11202 11266 I jxcore-log: INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"pleaseConnect":false}]
03-29 13:30:58.122 11202 11266 I jxcore-log: 
,03-29 13:30:58.122 11202 11791 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address F8:CF:C5:D9:E5:61 (thread ID: 1551)
,03-29 13:30:58.132 11202 11791 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
,03-29 13:30:58.132 11202 11791 D BluetoothSocket: connect(): myUserId = 0
,03-29 13:30:58.137 11202 11791 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-29 13:30:58.137  5947  5956 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
03-29 13:30:58.137  5947  6139 D IOP_DB_BT: db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-29 13:30:58.137  5947  6139 D IOP_DB_BT: db_query_add_key: key KEY_LMP_MFCT, value 15
03-29 13:30:58.137  5947  6139 D IOP_DB_BT: db_query_add_key: key KEY_LMP_VER, value 7:8975
03-29 13:30:58.137  5947  6139 D IOP_DB_BT: db_query_add_key: key KEY_DIR_ALL, value 1
03-29 13:30:58.137  5947  6139 D IOP_DB_BT: db_query_execute: result 1
03-29 13:30:58.137  5947  6139 W bt-btif : bta_dm_acl_change(), event : 2
,03-29 13:30:58.142 11202 11791 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[112]}
,03-29 13:30:59.102  3481  3619 V AlarmManager: waitForAlarm result :4
,03-29 13:30:59.112  5947  5947 D BtGatt.ScanManager: awakened up at time 272098
,03-29 13:30:59.117  5947  6061 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-29 13:30:59.127  5947  6057 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
03-29 13:30:59.127  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:30:59.127  5947  6057 D BtGatt.GattService: current time is 272110752906
03-29 13:30:59.127  5947  6057 D BtGatt.GattService: Batch record : [110, 107, -32, 25, 105, 114, 1, -128, -65, 20, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -106, -95, -79, -6, -5, 114, 1, -128, -53, 20, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0],
03-29 13:30:59.127  5947  6057 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81],
03-29 13:30:59.127  5947  6057 D ScanRecord: parseFromBytes,
03-29 13:30:59.127  5947  6057 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-29 13:30:59.127  5947  6057 D ScanRecord: parseFromBytes
03-29 13:30:59.127  5947  6057 D BtGatt.GattService: result: ScanResult{mDevice=72:69:19:E0:6B:6E, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-65, mTimestampNanos=271110927781}
,03-29 13:30:59.127  5947  6057 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-29 13:30:59.127  5947  6057 D BtGatt.GattService: result: ScanResult{mDevice=72:FB:FA:B1:A1:96, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-53, mTimestampNanos=271110927781},
,03-29 13:30:59.127  5947  6057 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-29 13:30:59.127 11202 11212 D ScanRecord: parseFromBytes
03-29 13:30:59.127 11202 11212 D ScanRecord: parseFromBytes
03-29 13:30:59.127 11202 11202 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2,
03-29 13:30:59.127 11202 11202 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:CF:C5:D9:E5:61] updated - the peer count is 2
,03-29 13:30:59.222  5947  6139 D IOP_DB_BT: db_query: id SkipSdpInfo :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
,03-29 13:30:59.222  5947  6139 D IOP_DB_BT: db_query: result 1
03-29 13:30:59.222  5947  6139 W bt-btif : bta_dm_acl_change(), event : 2
,03-29 13:30:59.232  5947  6139 D IOP_DB_BT: db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-29 13:30:59.232  5947  6139 D IOP_DB_BT: db_query_add_key: key KEY_LMP_MFCT, value 15
03-29 13:30:59.232  5947  6139 D IOP_DB_BT: db_query_add_key: key KEY_LMP_VER, value 7:8975
03-29 13:30:59.232  5947  6139 D IOP_DB_BT: db_query_add_key: key KEY_DIR_ALL, value *
03-29 13:30:59.232  5947  6139 D IOP_DB_BT: db_query_execute: result 1
,03-29 13:30:59.232  5947  6139 W bt-btif : bta_dm_acl_change(), event : 0
03-29 13:30:59.232  5947  6139 W bt-btif : info:x10
03-29 13:30:59.232  5947  6139 W bt-btif : btif_dm_upstreams_cback  ev: BTA_DM_LINK_UP_EVT
03-29 13:30:59.232  5947  6057 D         : remote version info [f8:cf:c5:d9:e5:61]: 7, f, 230f
03-29 13:30:59.232  5947  6057 E BluetoothRemoteDevices: aclStateChangeCallback: Device is NULL
,03-29 13:30:59.247  5947  6057 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,03-29 13:30:59.272  5947  6139 W bt-sdp  : process_service_search_attr_rsp
,03-29 13:30:59.947  5947  6139 D IOP_DB_BT: db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51,
03-29 13:30:59.947  5947  6139 D IOP_DB_BT: db_query_add_key: key KEY_LMP_MFCT, value 15
,03-29 13:30:59.947  5947  6139 D IOP_DB_BT: db_query_add_key: key KEY_LMP_VER, value 7:8975
,03-29 13:30:59.947  5947  6139 D IOP_DB_BT: db_query_add_key: key KEY_DIR_ALL, value *,
,03-29 13:30:59.947  5947  6139 D IOP_DB_BT: db_query_execute: result 1,
03-29 13:30:59.947  5947  6139 D IOP_DB_BT: db_query_create: id EnforceSlaveRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-29 13:30:59.992  3481  3619 V AlarmManager: waitForAlarm result :8
03-29 13:30:59.947  5947  6139 D IOP_DB_BT: db_query_add_key: key KEY_LMP_MFCT, value 15
03-29 13:31:00.007  3726  3726 D BluetoothTile:  onBluetoothPairedDevicesChanged:
03-29 13:30:59.947  5947  6139 D IOP_DB_BT: db_query_add_key: key KEY_LMP_VER, value 7:8975
,03-29 13:30:59.947  5947  6139 D IOP_DB_BT: db_query_add_key: key KEY_DIR_ALL, value *
03-29 13:30:59.947  5947  6139 D IOP_DB_BT: db_query_execute: result 1
,03-29 13:31:00.012  3481  3575 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d90f8d5 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{f0b4290 10260:com.android.settings/1000}
,03-29 13:30:59.962  5947  6057 W bt-btif : btif_dm_ssp_cfm_req_evt
03-29 13:31:00.012  3481  3745 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
03-29 13:30:59.972  5947  6057 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
03-29 13:31:00.017  3726  4794 D BluetoothTile:  handleUpdatestate:false name:null
03-29 13:30:59.977  5947  6057 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
03-29 13:30:59.982  5947  6057 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:CF:C5:D9:E5:61 newState: 1
03-29 13:30:59.982  3481  3834 D SecContentProvider: query(), uri = 4 selection = bluetoothLogForRemote
03-29 13:30:59.987  5947  6057 E bt-btif : check_cod: remote_cod = 0x5a020c
03-29 13:30:59.987  5947  6057 W bt-btif : btif_dm_ssp_reply: accept=1
,03-29 13:31:00.002  3481  3481 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
03-29 13:31:00.002  3481  3481 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.device.action.BOND_STATE_CHANGED
03-29 13:31:00.002  3481  3481 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED
03-29 13:31:00.002  3481  3481 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 10
03-29 13:31:00.002  3481  3481 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 11
03-29 13:31:00.002  3481  3481 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
03-29 13:31:00.012  5947  6059 I BluetoothBondStateMachine: Bond State Change Intent:F8:CF:C5:D9:E5:61 OldState: 10 NewState: 11
03-29 13:31:00.022  5947  6059 D BtConfig.SecureMode: isSecureModeOn:false
03-29 13:31:00.022  5947  6059 I BluetoothBondStateMachine: Entering PendingCommandState State
03-29 13:31:00.022 10260 10260 D BluetoothNotiBroadcastReceiver: onReceive
,03-29 13:31:00.022 10367 11807 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,03-29 13:31:00.027 10367 10367 D [CarModeFW]: ConnectivityManager-handleMessage PAIRING_DEVICES
,03-29 13:31:00.027  3481  3834 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d90f8d5 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{3de2f252 10367:com.sec.android.automotive.drivelink/u0a102}
,03-29 13:31:00.027 10367 10367 D [CarMode]: [AutoLaunchReceiver]-action: android.bluetooth.device.action.BOND_STATE_CHANGED
,03-29 13:31:00.032 10367 10367 D [CarMode]: [AutoLaunchReceiver]-ACTION_BOND_STATE_CHANGED Nexus 6 state is 11
,03-29 13:31:00.037  3481  3982 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d90f8d5 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{3de2f252 10367:com.sec.android.automotive.drivelink/u0a102}
,03-29 13:31:00.037  3481  4028 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
,03-29 13:31:00.042 10367 11808 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
03-29 13:31:00.042 10367 10367 D [CarModeFW]: ConnectivityManager-handleMessage PAIRING_DEVICES
,03-29 13:31:00.047  3481  3985 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d90f8d5 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{1d7b7c10 10512:com.samsung.android.app.watchmanagerstub/u0a121}
,03-29 13:31:00.062 10512 10512 E BluetoothHeadset: BTStateChangeCB is registed
,03-29 13:31:00.062 10512 10512 D GMHFPReceiver: android.bluetooth.device.action.BOND_STATE_CHANGED
03-29 13:31:00.062 10512 10512 D GMHFPReceiver: jangil::setProperties()
,03-29 13:31:00.067 10512 10512 D GMHFPReceiver: jangil::printBTStatus()
,03-29 13:31:00.067  3481  3982 D SettingsProvider: name = Wearable0001
03-29 13:31:00.067  3481  3982 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-29 13:31:00.067  3481  3982 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-29 13:31:00.067  3481  3982 D SettingsProvider: selectionArgs: false
03-29 13:31:00.067  3481  3982 D SettingsProvider: selectionArgs: 10121
03-29 13:31:00.067  3481  3982 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,03-29 13:31:00.072  3481  3982 D SettingsProvider: ret = -1
,03-29 13:31:00.087  3481  3982 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10121
,03-29 13:31:00.092 10512 10512 D GMHFPReceiver: ::::::::Wearable0001::false
,03-29 13:31:00.092  3481  3745 D SettingsProvider: name = Wearable0002
03-29 13:31:00.092  3481  3745 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-29 13:31:00.092  3481  3745 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-29 13:31:00.092  3481  3745 D SettingsProvider: selectionArgs: false
03-29 13:31:00.092  3481  3745 D SettingsProvider: selectionArgs: 10121
03-29 13:31:00.092  3481  3745 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,03-29 13:31:00.092  3481  3745 D SettingsProvider: ret = -1
,03-29 13:31:00.102  3481  3745 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10121
,03-29 13:31:00.107 10512 10512 D GMHFPReceiver: ::::::::Wearable0002::false
,03-29 13:31:00.107  3726  3726 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-29 13:31:00.112  3481  3985 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d90f8d5 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{25050ac8 4418:com.google.android.gms.persistent/u0a14}
,03-29 13:31:00.142  3481  3619 V AlarmManager: waitForAlarm result :4
,03-29 13:31:00.152  5947  5947 D BtGatt.ScanManager: awakened up at time 273137
03-29 13:31:00.152  5947  6061 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-29 13:31:00.157  5947  6057 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-29 13:31:00.157  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 13:31:00.167 10512 10512 D GMHFPReceiver: onServiceConnected() : 1
,03-29 13:31:00.172  3726  3726 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-29 13:31:00.182  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,03-29 13:31:00.182  3726  3726 I PERF    : received broadcast android.intent.action.TIME_TICK
,03-29 13:31:00.182  3726  3726 D KeyguardUpdateMonitor: handleTimeUpdate
,03-29 13:31:00.192  3726  3726 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,03-29 13:31:00.197  3726  3726 D SecKeyguardClockView: HomeTimezone(): 1
,03-29 13:31:00.207  3726  3726 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-29 13:31:00.207  3726  3726 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,03-29 13:31:00.217  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,03-29 13:31:00.217 10512 10512 D GMHFPReceiver: mBluetoothHeadset = true
,03-29 13:31:00.262  3726  3726 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-29 13:31:00.262  3726  3726 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-29 13:31:00.267  3726  3726 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-29 13:31:00.267  3726  3726 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-29 13:31:00.272  3726  3726 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-29 13:31:00.272  3726  3726 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-29 13:31:00.287  3726  3726 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-29 13:31:00.382  5947  6057 W bt-btif : btif_dm_auth_cmpl_evt
,03-29 13:31:00.387  5947  6057 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,03-29 13:31:00.412  5947  6057 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:CF:C5:D9:E5:61 newState: 0
,03-29 13:31:00.412  5947  6059 D BluetoothAdapterProperties: Failed to remove device: F8:CF:C5:D9:E5:61
,03-29 13:31:00.417  3481  4438 D SecContentProvider: query(), uri = 4 selection = bluetoothLogForRemote
,03-29 13:31:00.422  5947  6059 I BluetoothBondStateMachine: Bond State Change Intent:F8:CF:C5:D9:E5:61 OldState: 11 NewState: 10
,03-29 13:31:00.422  5947  6059 D BtConfig.SecureMode: isSecureModeOn:false
,03-29 13:31:00.437  5947  6059 D HidService: getHidService(): returning com.android.bluetooth.hid.HidService@29f99b6f
,03-29 13:31:00.437  3481  4417 D SettingsProvider: name = bluetooth_input_device_priority_F8:CF:C5:D9:E5:61
03-29 13:31:00.437  3481  4417 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-29 13:31:00.437  3481  4417 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-29 13:31:00.437  3481  4417 D SettingsProvider: selectionArgs: false
03-29 13:31:00.437  3481  4417 D SettingsProvider: selectionArgs: 1002
03-29 13:31:00.442  3481  4417 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,03-29 13:31:00.442  3481  4417 D SettingsProvider: ret = -1
03-29 13:31:00.442  5947  6059 D HidService: Saved priority F8:CF:C5:D9:E5:61 = -1
,03-29 13:31:00.442  3481  3512 D SettingsProvider: name = bluetooth_a2dp_sink_priority_F8:CF:C5:D9:E5:61
03-29 13:31:00.442  3481  3512 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-29 13:31:00.442  3481  3512 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-29 13:31:00.442  3481  3512 D SettingsProvider: selectionArgs: false
03-29 13:31:00.442  3481  3512 D SettingsProvider: selectionArgs: 1002
03-29 13:31:00.442  3481  3512 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,03-29 13:31:00.447  3481  3512 D SettingsProvider: ret = -1
,03-29 13:31:00.447  3481  4718 D SettingsProvider: name = bluetooth_headset_priority_F8:CF:C5:D9:E5:61
,03-29 13:31:00.447  3481  4718 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-29 13:31:00.447  3481  4718 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-29 13:31:00.447  3481  4718 D SettingsProvider: selectionArgs: false
03-29 13:31:00.447  3481  4718 D SettingsProvider: selectionArgs: 1002
,03-29 13:31:00.447  3481  4718 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
03-29 13:31:00.447  3481  4718 D SettingsProvider: ret = -1
03-29 13:31:00.452  5947  6059 I BluetoothBondStateMachine: StableState(): Entering Off State
,03-29 13:31:00.457  5947  6139 D IOP_DB_BT: db_query: id SkipSdpInfo :: key KEY_BDADDR, value f8:95:c7:87:3c:51,
03-29 13:31:00.457  5947  6139 D IOP_DB_BT: db_query: result 1
,03-29 13:31:00.462  3481  3481 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
03-29 13:31:00.462  3481  3481 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.device.action.BOND_STATE_CHANGED
03-29 13:31:00.462  3481  3481 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED
03-29 13:31:00.462  3481  3481 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 11
03-29 13:31:00.462  3481  3481 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 10
03-29 13:31:00.462  3481  3481 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
03-29 13:31:00.462  3726  3726 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,03-29 13:31:00.467  5947  6139 D IOP_DB_BT: db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-29 13:31:00.467  5947  6139 D IOP_DB_BT: db_query_add_key: key KEY_LMP_MFCT, value 15
03-29 13:31:00.467  5947  6139 D IOP_DB_BT: db_query_add_key: key KEY_LMP_VER, value 7:24841
03-29 13:31:00.467  5947  6139 D IOP_DB_BT: db_query_add_key: key KEY_DIR_ALL, value *
03-29 13:31:00.467  5947  6139 D IOP_DB_BT: db_query_execute: result 1
03-29 13:31:00.467  5947  6139 W bt-btif : bta_dm_acl_change(), event : 0
03-29 13:31:00.467  5947  6139 W bt-btif : info:x10
03-29 13:31:00.467  5947  6057 D         : remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
03-29 13:31:00.467  5947  6139 W bt-btif : bta_dm_acl_change(), event : 2
,03-29 13:31:00.467  5947  6057 E BluetoothRemoteDevices: aclStateChangeCallback: Device is NULL
,03-29 13:31:00.472  3726  4794 D BluetoothTile:  handleUpdatestate:false name:null
,03-29 13:31:00.482  3481  3575 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{194dcb42 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{f0b4290 10260:com.android.settings/1000}
03-29 13:31:00.482  3481  4438 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
,03-29 13:31:00.482 10260 10260 D BluetoothNotiBroadcastReceiver: onReceive
,03-29 13:31:00.497 10367 11826 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,03-29 13:31:00.497  3481  4028 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{194dcb42 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{3de2f252 10367:com.sec.android.automotive.drivelink/u0a102}
,03-29 13:31:00.497 10367 10367 D [CarMode]: [AutoLaunchReceiver]-action: android.bluetooth.device.action.BOND_STATE_CHANGED
,03-29 13:31:00.502 10367 10367 D [CarMode]: [AutoLaunchReceiver]-ACTION_BOND_STATE_CHANGED Nexus 6 state is 10
,03-29 13:31:00.507  3481  4718 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{194dcb42 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{3de2f252 10367:com.sec.android.automotive.drivelink/u0a102}
,03-29 13:31:00.512  3481  3982 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
,03-29 13:31:00.522 10367 11827 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,03-29 13:31:00.522  3481  3835 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{194dcb42 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{1d7b7c10 10512:com.samsung.android.app.watchmanagerstub/u0a121}
,03-29 13:31:00.527 10512 10512 E BluetoothHeadset: BTStateChangeCB is registed
,03-29 13:31:00.527 10512 10512 D GMHFPReceiver: android.bluetooth.device.action.BOND_STATE_CHANGED
,03-29 13:31:00.527 10512 10512 D GMHFPReceiver: jangil::setProperties()
,03-29 13:31:00.532 10512 10512 D GMHFPReceiver: jangil::printBTStatus()
,03-29 13:31:00.532  3481  4417 D SettingsProvider: name = Wearable0001
03-29 13:31:00.532  3481  4417 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-29 13:31:00.532  3481  4417 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-29 13:31:00.532  3481  4417 D SettingsProvider: selectionArgs: false
03-29 13:31:00.532  3481  4417 D SettingsProvider: selectionArgs: 10121
03-29 13:31:00.537  3481  4417 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
03-29 13:31:00.537  3481  4417 D SettingsProvider: ret = -1
03-29 13:31:00.537 10512 10512 D GMHFPReceiver: ::::::::Wearable0001::false
,03-29 13:31:00.537  3481  3745 D SettingsProvider: name = Wearable0002
03-29 13:31:00.537  3481  3745 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,03-29 13:31:00.537  3481  3745 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-29 13:31:00.537  3481  3745 D SettingsProvider: selectionArgs: false
03-29 13:31:00.537  3481  3745 D SettingsProvider: selectionArgs: 10121
03-29 13:31:00.537  3481  3745 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,03-29 13:31:00.537  3481  3745 D SettingsProvider: ret = -1
03-29 13:31:00.537 10512 10512 D GMHFPReceiver: ::::::::Wearable0002::false
,03-29 13:31:00.547  3481  4028 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{194dcb42 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{25050ac8 4418:com.google.android.gms.persistent/u0a14},
,03-29 13:31:00.632 10512 10512 D GMHFPReceiver: onServiceConnected() : 1
,03-29 13:31:00.632 10512 10512 D GMHFPReceiver: mBluetoothHeadset = true
,03-29 13:31:00.762  5947  6057 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,03-29 13:31:01.172  3481  3619 V AlarmManager: waitForAlarm result :4
,03-29 13:31:01.187  5947  5947 D BtGatt.ScanManager: awakened up at time 274172
03-29 13:31:01.187  5947  6061 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-29 13:31:01.192  5947  6057 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-29 13:31:01.192  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 13:31:01.452  5947  6139 E bt-btm  : tBTM_SEC_DEV:0xb35540d8 rs_disc_pending=1
03-29 13:31:01.452  5947  6139 W bt-btif : bta_dm_acl_change(), event : 3
03-29 13:31:01.452  5947  6139 W bt-btif : bta_dm_check_av:0
,03-29 13:31:01.452  5947  6057 W bt-btif : btif_dm_cback : unhandled event (14)
,03-29 13:31:02.197  3481  3619 V AlarmManager: waitForAlarm result :4
,03-29 13:31:02.212  5947  5947 D BtGatt.ScanManager: awakened up at time 275196
03-29 13:31:02.217  5947  6061 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-29 13:31:02.217  5947  6057 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-29 13:31:02.217  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 13:31:02.232  5947  6139 W bt-btif : new conn_srvc id:26, app_id:1,
03-29 13:31:02.232  5947  6139 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:1
03-29 13:31:02.232  5947  6139 W bt-btif : bta_dm_pm_ssr:2, lat:1200
,03-29 13:31:02.237  5947  5956 E BluetoothRemoteDevices: setRfcommConnected true
,03-29 13:31:02.247 11202 11791 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onSocketConnected: [<no peer name> F8:CF:C5:D9:E5:61] (thread ID: 1551)
,03-29 13:31:02.247 11202 11791 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 1551)
,03-29 13:31:02.257 11202 11791 D BluetoothSocket: getInputStream(): myUserId = 0,
,03-29 13:31:02.262 11202 11791 D BluetoothSocket: getOutputStream(): myUserId = 0
,03-29 13:31:02.262 11202 11791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesWritten: 15 bytes successfully written (thread ID: 1552)
03-29 13:31:02.262 11202 11791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Outgoing connection initialized (*handshake* thread ID: 1552)
03-29 13:31:02.262 11202 11791 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1551)
,03-29 13:31:02.267 11202 11837 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 1552)
,03-29 13:31:02.367  5947  6139 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61,
,03-29 13:31:02.372  5947  6139 D IOP_DB_BT: db_query: result 1
,03-29 13:31:02.372  5947  6139 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61,
03-29 13:31:02.372  5947  6139 D IOP_DB_BT: db_query: result 1
,03-29 13:31:02.502  5947  6139 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-29 13:31:02.502  5947  6139 D IOP_DB_BT: db_query: result 1
03-29 13:31:02.502  5947  6139 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-29 13:31:02.507  5947  6139 D IOP_DB_BT: db_query: result 1
03-29 13:31:02.507 11202 11837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesRead: Read 15 bytes successfully (thread ID: 1552)
03-29 13:31:02.507 11202 11837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Handshake succeeded with [<no peer name> F8:CF:C5:D9:E5:61]
,03-29 13:31:02.512 11202 11837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onHandshakeSucceeded: [<no peer name> F8:CF:C5:D9:E5:61] (thread ID: 1551)
,03-29 13:31:02.517 11202 11837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: handleSuccessfulClientThread: [<no peer name> F8:CF:C5:D9:E5:61] (thread ID: 1551)
,03-29 13:31:02.522 11202 11202 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:CF:C5:D9:E5:61]
03-29 13:31:02.522 11202 11202 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing connection to peer [<no peer name> F8:CF:C5:D9:E5:61]
03-29 13:31:02.522 11202 11202 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:CF:C5:D9:E5:61] updated - the peer count is 2
,03-29 13:31:02.527 11202 11837 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 1552)
,03-29 13:31:02.532 11202 11202 D BluetoothSocket: getInputStream(): myUserId = 0
,03-29 13:31:02.542 11202 11202 D BluetoothSocket: getOutputStream(): myUserId = 0
,03-29 13:31:02.542 11202 11202 I io.jxcore.node.ConnectionHelper: lowerBleDiscoveryPowerAndStartResetTimer: Lowering the power settings
03-29 13:31:02.542 11202 11202 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 2 -> 0
,03-29 13:31:02.547 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-29 13:31:02.547 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-29 13:31:02.547 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-29 13:31:02.547 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-29 13:31:02.547 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-29 13:31:02.547 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-29 13:31:02.552  5947  6060 D BtGatt.AdvertiseManager: message : 1
,03-29 13:31:02.552  5947  6060 D BtGatt.AdvertiseManager: stop advertise for client 7
03-29 13:31:02.552  5947  6060 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
,03-29 13:31:02.557  5947  6060 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-29 13:31:02.557  5947  6057 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-29 13:31:02.557  5947  6057 D BtGatt.GattService: Client app is not null!
,03-29 13:31:02.557  5947  5958 D BtGatt.GattService: unregisterClient() - clientIf=7
03-29 13:31:02.582  3726  3726 D BluetoothTile:  onBluetoothPairedDevicesChanged:
03-29 13:31:02.562  5947  6057 W bt-btif : btif_dm_ssp_cfm_req_evt
03-29 13:31:02.562  5947  6057 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
03-29 13:31:02.567  5947  6057 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
03-29 13:31:02.567  5947  6057 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
03-29 13:31:02.572  3481  3835 D SecContentProvider: query(), uri = 4 selection = bluetoothLogForRemote
03-29 13:31:02.572  5947  6057 E bt-btif : check_cod: remote_cod = 0x5a020c
03-29 13:31:02.572  5947  6057 W bt-btif : btif_dm_ssp_reply: accept=1
03-29 13:31:02.577  5947  6059 I BluetoothBondStateMachine: Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
03-29 13:31:02.582  3481  3481 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
03-29 13:31:02.582  3481  3481 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.device.action.BOND_STATE_CHANGED
03-29 13:31:02.582  3481  3481 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED
03-29 13:31:02.582  3481  3481 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 10
03-29 13:31:02.582  3481  3481 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 11
03-29 13:31:02.582  3481  3481 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
,03-29 13:31:02.592 11202 11202 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
03-29 13:31:02.592 11202 11202 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-29 13:31:02.592 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 3, timeout: 0, is connectable: false
03-29 13:31:02.592 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-29 13:31:02.592 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-29 13:31:02.592 11202 11202 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-29 13:31:02.592 11202 11202 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 13:31:02.592 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 13:31:02.592 11202 11202 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-29 13:31:02.592  3481  3575 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c2c145 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{f0b4290 10260:com.android.settings/1000}
,03-29 13:31:02.597  5947  6059 D BtConfig.SecureMode: isSecureModeOn:false
03-29 13:31:02.597  5947  6059 I BluetoothBondStateMachine: Entering PendingCommandState State
03-29 13:31:02.597 10260 10260 D BluetoothNotiBroadcastReceiver: onReceive
,03-29 13:31:02.597  3726  4794 D BluetoothTile:  handleUpdatestate:false name:null
,03-29 13:31:02.602  5947  5956 D BtGatt.GattService: registerClient() - UUID=f8130ae7-6a41-4ae8-ac54-16e69abdd9b6
,03-29 13:31:02.602  3481  3835 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c2c145 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{3de2f252 10367:com.sec.android.automotive.drivelink/u0a102}
,03-29 13:31:02.607  3481  3512 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
,03-29 13:31:02.612 10367 10367 D [CarMode]: [AutoLaunchReceiver]-action: android.bluetooth.device.action.BOND_STATE_CHANGED
,03-29 13:31:02.612 10367 10367 D [CarMode]: [AutoLaunchReceiver]-ACTION_BOND_STATE_CHANGED G4-1 state is 11
,03-29 13:31:02.612 10367 11844 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
03-29 13:31:02.612 10367 10367 D [CarModeFW]: ConnectivityManager-handleMessage PAIRING_DEVICES
,03-29 13:31:02.617  3481  3985 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c2c145 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{3de2f252 10367:com.sec.android.automotive.drivelink/u0a102}
,03-29 13:31:02.617  3481  4718 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
,03-29 13:31:02.627 10367 11845 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
03-29 13:31:02.627 10367 10367 D [CarModeFW]: ConnectivityManager-handleMessage PAIRING_DEVICES
,03-29 13:31:02.627  3481  4417 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c2c145 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{1d7b7c10 10512:com.samsung.android.app.watchmanagerstub/u0a121}
,03-29 13:31:02.632 10512 10512 E BluetoothHeadset: BTStateChangeCB is registed
,03-29 13:31:02.632 10512 10512 D GMHFPReceiver: android.bluetooth.device.action.BOND_STATE_CHANGED
03-29 13:31:02.632 10512 10512 D GMHFPReceiver: jangil::setProperties()
,03-29 13:31:02.632 10512 10512 D GMHFPReceiver: jangil::printBTStatus()
,03-29 13:31:02.637  3481  3511 D SettingsProvider: name = Wearable0001
03-29 13:31:02.637  3481  3511 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-29 13:31:02.637  3481  3511 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-29 13:31:02.637  3481  3511 D SettingsProvider: selectionArgs: false
03-29 13:31:02.637  3481  3511 D SettingsProvider: selectionArgs: 10121
03-29 13:31:02.637  3481  3511 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,03-29 13:31:02.637  3481  3511 D SettingsProvider: ret = -1
03-29 13:31:02.637 10512 10512 D GMHFPReceiver: ::::::::Wearable0001::false
,03-29 13:31:02.637  3481  3651 D SettingsProvider: name = Wearable0002
03-29 13:31:02.637  3481  3651 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-29 13:31:02.637  3481  3651 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-29 13:31:02.637  3481  3651 D SettingsProvider: selectionArgs: false
03-29 13:31:02.637  3481  3651 D SettingsProvider: selectionArgs: 10121
03-29 13:31:02.637  3481  3651 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
03-29 13:31:02.637  3481  3651 D SettingsProvider: ret = -1
,03-29 13:31:02.637 10512 10512 D GMHFPReceiver: ::::::::Wearable0002::false
,03-29 13:31:02.642  5947  6057 D BtGatt.GattService: onClientRegistered() - UUID=f8130ae7-6a41-4ae8-ac54-16e69abdd9b6, clientIf=7
,03-29 13:31:02.642 11202 11214 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-29 13:31:02.642  3481  4028 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c2c145 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{25050ac8 4418:com.google.android.gms.persistent/u0a14}
,03-29 13:31:02.652  5947  6057 W bt-btif : btif_dm_auth_cmpl_evt
,03-29 13:31:02.652  5947  6057 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,03-29 13:31:02.657  5947  6068 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 46
,03-29 13:31:02.657  5947  6060 D BtGatt.AdvertiseManager: message : 0
03-29 13:31:02.657  5947  6060 D BtGatt.AdvertiseManager: number of adv instance running0
03-29 13:31:02.657  5947  6060 D BtGatt.AdvertiseManager: size of list is =0
,03-29 13:31:02.657  5947  6060 D BtGatt.AdvertiseManager: starting advertising,
03-29 13:31:02.657  5947  6060 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-29 13:31:02.667  5947  6057 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0,
03-29 13:31:02.667  5947  6059 D BluetoothAdapterProperties: Failed to remove device: F8:95:C7:87:3C:51
,03-29 13:31:02.667  5947  6057 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-29 13:31:02.672  3481  3745 D SecContentProvider: query(), uri = 4 selection = bluetoothLogForRemote
,03-29 13:31:02.672  5947  6060 D BtGatt.AdvertiseManager: starting multi advertising
,03-29 13:31:02.672  5947  6057 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
03-29 13:31:02.672  5947  6060 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-29 13:31:02.672  5947  6060 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 0, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,03-29 13:31:02.672 11202 11202 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-29 13:31:02.672  5947  6059 I BluetoothBondStateMachine: Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,03-29 13:31:02.677  5947  6068 D BtGatt.GattService: stopScan() - queue size =1
03-29 13:31:02.677  3481  3481 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
03-29 13:31:02.677  3481  3481 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.device.action.BOND_STATE_CHANGED
03-29 13:31:02.677  3481  3481 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED
03-29 13:31:02.677  3481  3481 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 11
03-29 13:31:02.677  3481  3481 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 10
03-29 13:31:02.677  3481  3481 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
03-29 13:31:02.677  5947  5956 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-29 13:31:02.677  5947  6061 D BtGatt.ScanManager: filter size is 1,
03-29 13:31:02.682  3726  3726 D BluetoothTile:  onBluetoothPairedDevicesChanged:
03-29 13:31:02.677  5947  6061 D BtGatt.ScanManager: delete FilterIndex - 11
03-29 13:31:02.677 11202 11202 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-29 13:31:02.677 11202 11202 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-29 13:31:02.677 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-29 13:31:02.677 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-29 13:31:02.677 11202 11202 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-29 13:31:02.677 11202 11202 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-29 13:31:02.677  5947  6057 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,03-29 13:31:02.677  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:31:02.682  5947  6061 D BtGatt.ScanManager: stopping BLe Batch
03-29 13:31:02.682  5947  6057 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-29 13:31:02.682  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:31:02.682  5947  6061 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-29 13:31:02.682  5947  6057 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-29 13:31:02.682  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 13:31:02.687  3726  4794 D BluetoothTile:  handleUpdatestate:false name:null
,03-29 13:31:02.687  3481  3575 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2ed32cc1 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{f0b4290 10260:com.android.settings/1000}
,03-29 13:31:02.687  5947 11847 D BtGatt.GattService: registerClient() - UUID=045c8ff9-3ae1-47db-9865-339fdc37d364
03-29 13:31:02.687  3481  4417 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
03-29 13:31:02.687 10260 10260 D BluetoothNotiBroadcastReceiver: onReceive
,03-29 13:31:02.692  5947  6059 D BtConfig.SecureMode: isSecureModeOn:false,
,03-29 13:31:02.697  5947  6059 D HidService: getHidService(): returning com.android.bluetooth.hid.HidService@29f99b6f
,03-29 13:31:02.697 10367 11849 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
03-29 13:31:02.697  3481  4718 D SettingsProvider: name = bluetooth_input_device_priority_F8:95:C7:87:3C:51
,03-29 13:31:02.697  3481  4718 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-29 13:31:02.697  3481  4718 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-29 13:31:02.697  3481  4718 D SettingsProvider: selectionArgs: false
03-29 13:31:02.697  3481  4718 D SettingsProvider: selectionArgs: 1002
03-29 13:31:02.697  3481  4718 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,03-29 13:31:02.697  3481  4718 D SettingsProvider: ret = -1
03-29 13:31:02.697  5947  6059 D HidService: Saved priority F8:95:C7:87:3C:51 = -1,
03-29 13:31:02.697  3481  3745 D SettingsProvider: name = bluetooth_a2dp_sink_priority_F8:95:C7:87:3C:51
03-29 13:31:02.697  3481  3745 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,03-29 13:31:02.697  3481  3745 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-29 13:31:02.697  3481  3745 D SettingsProvider: selectionArgs: false,
03-29 13:31:02.702  3481  3834 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2ed32cc1 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{3de2f252 10367:com.sec.android.automotive.drivelink/u0a102}
,03-29 13:31:02.697  3481  3745 D SettingsProvider: selectionArgs: 1002
03-29 13:31:02.697  3481  3745 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
03-29 13:31:02.702  3481  3745 D SettingsProvider: ret = -1
03-29 13:31:02.702  3481  4417 D SettingsProvider: name = bluetooth_headset_priority_F8:95:C7:87:3C:51
,03-29 13:31:02.702  3481  4417 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-29 13:31:02.702 10367 10367 D [CarMode]: [AutoLaunchReceiver]-action: android.bluetooth.device.action.BOND_STATE_CHANGED
03-29 13:31:02.702  3481  4417 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-29 13:31:02.702  3481  4417 D SettingsProvider: selectionArgs: false
03-29 13:31:02.702  3481  4417 D SettingsProvider: selectionArgs: 1002
03-29 13:31:02.702  3481  4417 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,03-29 13:31:02.702  3481  4417 D SettingsProvider: ret = -1
03-29 13:31:02.702  5947  6059 I BluetoothBondStateMachine: StableState(): Entering Off State
,03-29 13:31:02.707 10367 10367 D [CarMode]: [AutoLaunchReceiver]-ACTION_BOND_STATE_CHANGED G4-1 state is 10
,03-29 13:31:02.707  3481  4718 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2ed32cc1 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{3de2f252 10367:com.sec.android.automotive.drivelink/u0a102}
,03-29 13:31:02.712  3481  3982 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
,03-29 13:31:02.717  5947  6139 W bt-btif : new conn_srvc id:26, app_id:255
03-29 13:31:02.717  5947  6139 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
03-29 13:31:02.717  5947  6139 W bt-btif : bta_dm_pm_ssr:2, lat:1200
03-29 13:31:02.717 11202 11784 D BluetoothSocket: socket fd passed by stack  fds: [Ljava.io.FileDescriptor;@2104d01e
,03-29 13:31:02.717  5947  6068 E BluetoothRemoteDevices: setRfcommConnected true
03-29 13:31:02.717 11202 11784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection accepted
,03-29 13:31:02.722 10367 11854 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,03-29 13:31:02.722  3481  4438 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2ed32cc1 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{1d7b7c10 10512:com.samsung.android.app.watchmanagerstub/u0a121}
,03-29 13:31:02.722 10512 10512 E BluetoothHeadset: BTStateChangeCB is registed
,03-29 13:31:02.727  5947  6139 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-29 13:31:02.727  5947  6139 D IOP_DB_BT: db_query: result 1
03-29 13:31:02.727  5947  6139 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-29 13:31:02.727  5947  6139 D IOP_DB_BT: db_query: result 1
03-29 13:31:02.727 10512 10512 D GMHFPReceiver: android.bluetooth.device.action.BOND_STATE_CHANGED
03-29 13:31:02.727 10512 10512 D GMHFPReceiver: jangil::setProperties()
03-29 13:31:02.727 11202 11784 D BluetoothSocket: getInputStream(): myUserId = 0
,03-29 13:31:02.727  5947  6057 D BtGatt.GattService: onClientRegistered() - UUID=045c8ff9-3ae1-47db-9865-339fdc37d364, clientIf=6
03-29 13:31:02.732 11202 11214 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-29 13:31:02.732  5947 11847 D BtGatt.GattService: start scan with filters
03-29 13:31:02.732 10512 10512 D GMHFPReceiver: jangil::printBTStatus()
03-29 13:31:02.732 11202 11784 D BluetoothSocket: getOutputStream(): myUserId = 0
03-29 13:31:02.732 11202 11784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection initialized (thread ID: 1554)
03-29 13:31:02.732 11202 11784 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1ba9f0ff, channel: 6, state: LISTENING
03-29 13:31:02.732  3481  3511 D SettingsProvider: name = Wearable0001
03-29 13:31:02.732  3481  3511 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-29 13:31:02.732 11202 11784 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1ba9f0ff, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@18f9bd34, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@33037eccmSocket: android.net.LocalSocket@26e75515 impl:android.net.LocalSocketImpl@2fa9d02a fd:FileDescriptor[93]
03-29 13:31:02.732  3481  3511 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-29 13:31:02.732  3481  3511 D SettingsProvider: selectionArgs: false
03-29 13:31:02.732  3481  3511 D SettingsProvider: selectionArgs: 10121
03-29 13:31:02.732 11202 11784 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@26e75515 impl:android.net.LocalSocketImpl@2fa9d02a fd:FileDescriptor[93]
03-29 13:31:02.732  3481  3511 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
03-29 13:31:02.732 11202 11784 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-29 13:31:02.732 11202 11855 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 1554)
03-29 13:31:02.732 11202 11855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesRead: Read 15 bytes successfully (thread ID: 1554)
,03-29 13:31:02.732  3481  3511 D SettingsProvider: ret = -1
,03-29 13:31:02.732 10512 10512 D GMHFPReceiver: ::::::::Wearable0001::false
,03-29 13:31:02.732 11202 11855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Got valid identity from [<no peer name> F8:95:C7:87:3C:51]
,03-29 13:31:02.732 11202 11855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesWritten: 15 bytes successfully written (thread ID: 1554)
03-29 13:31:02.732 11202 11855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: removeThreadFromList: Removing thread with ID 1554
03-29 13:31:02.732  5947  6139 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-29 13:31:02.732 11202 11855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Handshake thread disposed (thread ID: 1554)
,03-29 13:31:02.732 11202 11855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onIncomingConnectionConnected: [<no peer name> F8:95:C7:87:3C:51]
03-29 13:31:02.732  3481  3745 D SettingsProvider: name = Wearable0002
03-29 13:31:02.732  3481  3745 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,03-29 13:31:02.732  3481  3745 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-29 13:31:02.732  3481  3745 D SettingsProvider: selectionArgs: false
03-29 13:31:02.732  3481  3745 D SettingsProvider: selectionArgs: 10121
03-29 13:31:02.732  5947  6139 D IOP_DB_BT: db_query: result 1
03-29 13:31:02.732  5947  6139 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-29 13:31:02.732  3481  3745 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
03-29 13:31:02.737  5947  6139 D IOP_DB_BT: db_query: result 1
03-29 13:31:02.737  3481  3745 D SettingsProvider: ret = -1
03-29 13:31:02.737 11202 11855 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 1554)
03-29 13:31:02.737 10512 10512 D GMHFPReceiver: ::::::::Wearable0002::false
03-29 13:31:02.737 11202 11784 D BluetoothSocket: bindListen(): myUserId = 0
,03-29 13:31:02.737 11202 11784 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-29 13:31:02.737 10512 10512 D GMHFPReceiver: onServiceConnected() : 1
03-29 13:31:02.737 10512 10512 D GMHFPReceiver: mBluetoothHeadset = true
03-29 13:31:02.742  3481  3982 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2ed32cc1 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{25050ac8 4418:com.google.android.gms.persistent/u0a14}
,03-29 13:31:02.742  5947 11847 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 57,
03-29 13:31:02.742  5947  6061 D BtGatt.ScanManager: handling starting scan
03-29 13:31:02.742  5947  6061 D BtGatt.ScanManager: isFilteringSupported
03-29 13:31:02.742  5947  6061 D BluetoothAdapter: setting StandAloneBleMode
03-29 13:31:02.742 11202 11202 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-29 13:31:02.742 11202 11784 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[113]}
03-29 13:31:02.742 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-29 13:31:02.742 11202 11784 D BluetoothSocket: bindListen(), new LocalSocket 
03-29 13:31:02.742 11202 11784 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-29 13:31:02.742 11202 11784 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@33369e1b
03-29 13:31:02.742 11202 11202 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 3 -> 1
03-29 13:31:02.742 11202 11784 D BluetoothSocket: channel: 6
03-29 13:31:02.742 11202 11784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-29 13:31:02.742 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-29 13:31:02.742 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-29 13:31:02.742 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-29 13:31:02.742 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-29 13:31:02.742 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-29 13:31:02.742 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-29 13:31:02.747  5947  6057 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-29 13:31:02.747  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:31:02.747  5947  6060 D BtGatt.AdvertiseManager: message : 1
03-29 13:31:02.747  5947  6061 D BtGatt.ScanManager: allow scan with filters
03-29 13:31:02.747  5947  6061 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-29 13:31:02.747  5947  6061 D BtGatt.ScanManager: set filter index= 12 for clientIf= 6
03-29 13:31:02.747  5947  6060 D BtGatt.AdvertiseManager: stop advertise for client 7
03-29 13:31:02.747  5947  6060 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
,03-29 13:31:02.747  5947  6057 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-29 13:31:02.747  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:31:02.747  5947  6061 D BtGatt.ScanManager: Starting BLE batch scan
03-29 13:31:02.747  5947  6061 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-29 13:31:02.747  5947  6060 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-29 13:31:02.752  5947  6057 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-29 13:31:02.752  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 13:31:02.752  5947  6057 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0,
03-29 13:31:02.752  5947  6057 D BtGatt.GattService: Client app is not null!
,03-29 13:31:02.752  5947 11847 D BtGatt.GattService: unregisterClient() - clientIf=7
03-29 13:31:02.752 11202 11202 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-29 13:31:02.752 11202 11202 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-29 13:31:02.752 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-29 13:31:02.752 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-29 13:31:02.752 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-29 13:31:02.752 11202 11202 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-29 13:31:02.752  5947  6057 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1,
03-29 13:31:02.752  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:31:02.752 11202 11202 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 13:31:02.752 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-29 13:31:02.752 11202 11202 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-29 13:31:02.757  5947  6068 D BtGatt.GattService: registerClient() - UUID=c31a1432-ee75-4fed-ba53-3a2e601f9ff3
,03-29 13:31:02.767 11202 11213 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1ba9f0ff, channel: 6, state: CLOSED
,03-29 13:31:02.772 11202 11213 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@304df8a5, channel: 6, state: CLOSED
,03-29 13:31:02.772 11202 11213 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1e562b17, channel: 6, state: CLOSED
,03-29 13:31:02.772 11202 11213 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2c119d79, channel: 6, state: CLOSED
,03-29 13:31:02.772 11202 11213 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@120d9e5b, channel: 6, state: CLOSED
,03-29 13:31:02.777 11202 11213 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@101a242f, channel: 6, state: CLOSED
,03-29 13:31:02.797  5947  6057 D BtGatt.GattService: onClientRegistered() - UUID=c31a1432-ee75-4fed-ba53-3a2e601f9ff3, clientIf=7
,03-29 13:31:02.802 11202 11214 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-29 13:31:02.812  5947 11847 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 47
,03-29 13:31:02.812  5947  6060 D BtGatt.AdvertiseManager: message : 0
03-29 13:31:02.812  5947  6060 D BtGatt.AdvertiseManager: number of adv instance running0
,03-29 13:31:02.812  5947  6060 D BtGatt.AdvertiseManager: size of list is =0
,03-29 13:31:02.812  5947  6060 D BtGatt.AdvertiseManager: starting advertising
,03-29 13:31:02.812  5947  6060 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-29 13:31:02.817  5947  6057 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-29 13:31:02.817  5947  6060 D BtGatt.AdvertiseManager: starting multi advertising
,03-29 13:31:02.817  5947  6057 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-29 13:31:02.817  5947  6060 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-29 13:31:02.817  5947  6060 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 0, TxPowerLevel: 1, isConnectable: false, Timeout: 0
03-29 13:31:02.822 11202 11202 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-29 13:31:02.822  5947 11846 D BtGatt.GattService: stopScan() - queue size =1
,03-29 13:31:02.822  5947  6061 D BtGatt.ScanManager: filter size is 1
03-29 13:31:02.822  5947  6061 D BtGatt.ScanManager: delete FilterIndex - 12
03-29 13:31:02.822  5947  5956 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-29 13:31:02.822 11202 11202 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-29 13:31:02.822 11202 11202 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-29 13:31:02.822 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-29 13:31:02.822 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-29 13:31:02.822 11202 11202 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-29 13:31:02.822  5947  6057 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-29 13:31:02.827  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:31:02.827 11202 11202 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-29 13:31:02.827  5947  6061 D BtGatt.ScanManager: stopping BLe Batch
,03-29 13:31:02.827 10512 10512 D GMHFPReceiver: onServiceConnected() : 1
03-29 13:31:02.827 10512 10512 D GMHFPReceiver: mBluetoothHeadset = true
03-29 13:31:02.827  5947  6057 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-29 13:31:02.827  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 13:31:02.827  5947  6061 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-29 13:31:02.832  5947 11846 D BtGatt.GattService: registerClient() - UUID=4f7f132f-2fba-4452-9e05-22cc15696cb9
,03-29 13:31:02.832  5947  6057 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=3
03-29 13:31:02.832  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:31:02.832  5947  6057 D BtGatt.GattService: current time is 275817728406
03-29 13:31:02.832  5947  6057 D BtGatt.GattService: Batch record : [-52, 97, -92, -108, 32, 106, 1, -128, -70, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -35, -90, 72, 4, 0, 114, 1, -128, -82, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -80, -123, 94, -87, -25, 82, 1, -128, -82, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-29 13:31:02.832  5947  6057 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-29 13:31:02.832  5947  6057 D ScanRecord: parseFromBytes
03-29 13:31:02.832  5947  6057 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-29 13:31:02.832  5947  6057 D ScanRecord: parseFromBytes
03-29 13:31:02.832  5947  6057 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-29 13:31:02.832  5947  6057 D ScanRecord: parseFromBytes
,03-29 13:31:02.872  5947  6057 D BtGatt.GattService: onClientRegistered() - UUID=4f7f132f-2fba-4452-9e05-22cc15696cb9, clientIf=6
,03-29 13:31:02.872 11202 11214 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-29 13:31:02.872  5947  5956 D BtGatt.GattService: start scan with filters
,03-29 13:31:02.892  5947  5956 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 58
,03-29 13:31:02.892 11202 11202 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-29 13:31:02.892 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-29 13:31:02.892 11202 11202 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 2 -> 0
03-29 13:31:02.892  5947  6061 D BtGatt.ScanManager: handling starting scan
03-29 13:31:02.892  5947  6061 D BtGatt.ScanManager: isFilteringSupported
03-29 13:31:02.892  5947  6061 D BluetoothAdapter: setting StandAloneBleMode
03-29 13:31:02.892 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-29 13:31:02.892 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-29 13:31:02.892 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-29 13:31:02.892 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-29 13:31:02.892 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-29 13:31:02.892 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-29 13:31:02.897  5947  6057 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,03-29 13:31:02.897  5947  6060 D BtGatt.AdvertiseManager: message : 1
03-29 13:31:02.897  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:31:02.897  5947  6061 D BtGatt.ScanManager: allow scan with filters
03-29 13:31:02.897  5947  6061 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-29 13:31:02.897  5947  6061 D BtGatt.ScanManager: set filter index= 13 for clientIf= 6
03-29 13:31:02.897  5947  6060 D BtGatt.AdvertiseManager: stop advertise for client 7
,03-29 13:31:02.897  5947  6060 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-29 13:31:02.897  5947  6057 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-29 13:31:02.897  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:31:02.897  5947  6061 D BtGatt.ScanManager: Starting BLE batch scan
03-29 13:31:02.897  5947  6060 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-29 13:31:02.897  5947  6061 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-29 13:31:02.897  5947  6057 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-29 13:31:02.897  5947  6057 D BtGatt.GattService: Client app is not null!
,03-29 13:31:02.902  5947  5958 D BtGatt.GattService: unregisterClient() - clientIf=7
,03-29 13:31:02.902 11202 11202 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-29 13:31:02.902 11202 11202 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-29 13:31:02.902 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-29 13:31:02.902 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-29 13:31:02.902 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-29 13:31:02.902 11202 11202 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-29 13:31:02.902 11202 11202 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 13:31:02.902 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 13:31:02.902 11202 11202 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-29 13:31:02.907  5947  6057 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-29 13:31:02.907  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 13:31:02.907  5947  6057 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-29 13:31:02.907  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 13:31:02.912  5947 11847 D BtGatt.GattService: registerClient() - UUID=8c2b95c9-c10b-44f6-9ab0-c1c182c9e08a,
,03-29 13:31:02.952  5947  6057 D BtGatt.GattService: onClientRegistered() - UUID=8c2b95c9-c10b-44f6-9ab0-c1c182c9e08a, clientIf=7
,03-29 13:31:02.952 11202 11214 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-29 13:31:02.972  5947  5958 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 48
,03-29 13:31:02.972  5947  6060 D BtGatt.AdvertiseManager: message : 0
,03-29 13:31:02.972  5947  6060 D BtGatt.AdvertiseManager: number of adv instance running0
03-29 13:31:02.972  5947  6060 D BtGatt.AdvertiseManager: size of list is =0
,03-29 13:31:02.977  5947  6060 D BtGatt.AdvertiseManager: starting advertising
,03-29 13:31:02.982  5947  6060 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-29 13:31:02.987  5947  6057 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-29 13:31:02.992  5947  6060 D BtGatt.AdvertiseManager: starting multi advertising
,03-29 13:31:02.992  5947  6057 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-29 13:31:02.992  5947  6060 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,03-29 13:31:02.992  5947  6060 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 0, TxPowerLevel: 1, isConnectable: false, Timeout: 0
,03-29 13:31:02.997 11202 11202 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-29 13:31:02.997  5947  5956 D BtGatt.GattService: stopScan() - queue size =1
03-29 13:31:02.997  5947  6061 D BtGatt.ScanManager: filter size is 1
03-29 13:31:02.997  5947  6061 D BtGatt.ScanManager: delete FilterIndex - 13
03-29 13:31:02.997  5947  6057 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-29 13:31:02.997  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:31:02.997  5947  6068 D BtGatt.GattService: unregisterClient() - clientIf=6
03-29 13:31:03.002  5947  6061 D BtGatt.ScanManager: stopping BLe Batch
03-29 13:31:03.002 11202 11202 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-29 13:31:03.002 11202 11202 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-29 13:31:03.002 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-29 13:31:03.002 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-29 13:31:03.002 11202 11202 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-29 13:31:03.002 11202 11202 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-29 13:31:03.002  5947  6057 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0,
03-29 13:31:03.002  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:31:03.002  5947  6061 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-29 13:31:03.007  5947  6057 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-29 13:31:03.007  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 13:31:03.012  5947  5956 D BtGatt.GattService: registerClient() - UUID=5862124b-218d-4cc8-ad85-462501ee6b56
,03-29 13:31:03.052  5947  6057 D BtGatt.GattService: onClientRegistered() - UUID=5862124b-218d-4cc8-ad85-462501ee6b56, clientIf=6
,03-29 13:31:03.052 11202 11214 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-29 13:31:03.052  5947  6068 D BtGatt.GattService: start scan with filters
,03-29 13:31:03.067  5947  6068 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 59
,03-29 13:31:03.067 11202 11202 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-29 13:31:03.067 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-29 13:31:03.067  5947  6061 D BtGatt.ScanManager: handling starting scan
03-29 13:31:03.067  5947  6061 D BtGatt.ScanManager: isFilteringSupported
03-29 13:31:03.067  5947  6061 D BluetoothAdapter: setting StandAloneBleMode
03-29 13:31:03.067 11202 11202 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing socket thread, for peer [<no peer name> F8:CF:C5:D9:E5:61], created successfully
03-29 13:31:03.067 11202 11202 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 1
03-29 13:31:03.067 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-29 13:31:03.067 11202 11202 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-29 13:31:03.067 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-29 13:31:03.067 11202 11202 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:95:C7:87:3C:51]
03-29 13:31:03.067 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-29 13:31:03.067 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-29 13:31:03.067 11202 11202 I io.jxcore.node.ConnectionHelper: onConnected: Incoming connection to peer [<no peer name> F8:95:C7:87:3C:51]
03-29 13:31:03.067 11202 11202 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
,03-29 13:31:03.067 11202 11869 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1553)
,03-29 13:31:03.067  5947  6057 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1,
03-29 13:31:03.067  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:31:03.072  5947  6061 D BtGatt.ScanManager: allow scan with filters
03-29 13:31:03.072 11202 11869 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 35164
03-29 13:31:03.072 11202 11869 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
03-29 13:31:03.072  5947  6061 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,03-29 13:31:03.072  5947  6061 D BtGatt.ScanManager: set filter index= 14 for clientIf= 6
03-29 13:31:03.072 11202 11869 I io.jxcore.node.ConnectionHelper: onListeningForIncomingConnections: Outgoing connection is using port 35164 (peer ID: F8:CF:C5:D9:E5:61)
03-29 13:31:03.072 11202 11869 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "F8:CF:C5:D9:E5:61" removed
03-29 13:31:03.072  5947  6057 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-29 13:31:03.072  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:31:03.072  5947  6061 D BtGatt.ScanManager: Starting BLE batch scan
,03-29 13:31:03.072  5947  6061 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-29 13:31:03.072 11202 11202 D BluetoothSocket: getInputStream(): myUserId = 0
,03-29 13:31:03.072  5947  6057 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-29 13:31:03.072  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 13:31:03.077  5947  6057 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,03-29 13:31:03.077  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:31:03.077 11202 11202 D BluetoothSocket: getOutputStream(): myUserId = 0
,03-29 13:31:03.077 11202 11202 I io.jxcore.node.ConnectionHelper: onConnected: Incoming socket thread, for peer [<no peer name> F8:95:C7:87:3C:51], created successfully
03-29 13:31:03.077 11202 11202 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 2
,03-29 13:31:03.077 11202 11870 D io.jxcore.node.IncomingSocketThread: Entering thread (ID: 1555)
,03-29 13:31:03.077  2873  3455 D EnterpriseController: netId is 0
03-29 13:31:03.077  2873  3455 D Netd    : getNetworkForDns: using netid 502 for uid 10011
03-29 13:31:03.082 11202 11266 I jxcore-log: INFO testThaliMobileNative: 
03-29 13:31:03.082 11202 11266 I jxcore-log: 
,03-29 13:31:03.082 11202 11266 I jxcore-log: ok 164 Must have listeningPort
03-29 13:31:03.082 11202 11266 I jxcore-log: 
,03-29 13:31:03.082 11202 11266 I jxcore-log: ok 165 listeningPort must be a number
03-29 13:31:03.082 11202 11266 I jxcore-log: 
,03-29 13:31:03.082 11202 11266 I jxcore-log: ok 166 Connection must have clientPort
03-29 13:31:03.082 11202 11266 I jxcore-log: 
,03-29 13:31:03.082 11202 11266 I jxcore-log: ok 167 clientPort must be a number
03-29 13:31:03.082 11202 11266 I jxcore-log: 
03-29 13:31:03.082 11202 11870 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 58543
03-29 13:31:03.082 11202 11870 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,03-29 13:31:03.082 11202 11266 I jxcore-log: ok 168 Connection must have serverPort
03-29 13:31:03.082 11202 11266 I jxcore-log: 
03-29 13:31:03.082 11202 11870 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
,03-29 13:31:03.082 11202 11870 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-29 13:31:03.082 11202 11266 I jxcore-log: ok 169 serverPort must be a number
03-29 13:31:03.082 11202 11266 I jxcore-log: 
,03-29 13:31:03.087 11202 11872 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1556, name: Sender)
03-29 13:31:03.087 11202 11870 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 1555)
,03-29 13:31:03.087 11202 11870 D io.jxcore.node.IncomingSocketThread: Exiting thread (ID: 1555)
03-29 13:31:03.087 11202 11266 I jxcore-log: ok 170 forward connection must have clientPort == 0
03-29 13:31:03.087 11202 11266 I jxcore-log: 
,03-29 13:31:03.087 11202 11266 I jxcore-log: ok 171 forward connection must have serverPort == 0
03-29 13:31:03.087 11202 11266 I jxcore-log: 
03-29 13:31:03.087 11202 11873 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1557, name: Receiver)
,03-29 13:31:03.097 11202 11266 I jxcore-log: # teardown
03-29 13:31:03.097 11202 11266 I jxcore-log: 
,03-29 13:31:03.362  3481  3834 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-29 13:31:03.362  3481  3834 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-29 13:31:03.362  3481  3834 D BatteryService: online:4, current avg:34, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:42
,03-29 13:31:03.362  3481  3481 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-29 13:31:03.367  3481  3834 D BatteryService: stay LED for fully charged
,03-29 13:31:03.372  3481  3481 I MotionRecognitionService: Plugged,
03-29 13:31:03.372  3481  3481 D MotionRecognitionService:   cableConnection= 1
,03-29 13:31:03.372  3481  3481 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-29 13:31:03.372  3481  3481 D MotionRecognitionService: skip setTransmitPower. 
,03-29 13:31:03.387  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-29 13:31:03.387  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-29 13:31:03.387  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-29 13:31:03.397  5947  5947 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-29 13:31:03.397  5947  6065 D HeadsetStateMachine: Disconnected process message: 10
,03-29 13:31:03.412  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-29 13:31:03.412  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-29 13:31:03.412  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-29 13:31:03.412  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-29 13:31:04.077  3481  3619 V AlarmManager: waitForAlarm result :4
,03-29 13:31:04.087  5947  5947 D BtGatt.ScanManager: awakened up at time 277073
03-29 13:31:04.092  5947  6061 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-29 13:31:04.097  5947  6057 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-29 13:31:04.097  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 13:31:04.317  3481  6174 D SSRM:n  : SIOP:: AP = 270, PST = 283 (W:16), CUR = 34, LCD = 0
,03-29 13:31:05.107  3481  3619 V AlarmManager: waitForAlarm result :4
,03-29 13:31:05.117  5947  5947 D BtGatt.ScanManager: awakened up at time 278103
03-29 13:31:05.127  5947  6061 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-29 13:31:05.137  5947  6057 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
03-29 13:31:05.137  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:31:05.137  5947  6057 D BtGatt.GattService: current time is 278123101532
03-29 13:31:05.137  5947  6057 D BtGatt.GattService: Batch record : [-80, -123, 94, -87, -25, 82, 1, -128, -82, 6, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-29 13:31:05.137  5947  6057 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-29 13:31:05.137  5947  6057 D ScanRecord: parseFromBytes
03-29 13:31:05.137  5947  6057 D BtGatt.GattService: result: ScanResult{mDevice=52:E7:A9:5E:85:B0, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-82, mTimestampNanos=277823253865}
03-29 13:31:05.137  5947  6057 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-29 13:31:05.137 11202 11214 D ScanRecord: parseFromBytes
03-29 13:31:05.142 11202 11202 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
,03-29 13:31:06.147  5947  6139 E bt-btm  : tBTM_SEC_DEV:0xb35540d8 rs_disc_pending=0
03-29 13:31:06.147  5947  6139 W bt-btif : bta_dm_acl_change(), event : 3
03-29 13:31:06.147  5947  6139 W bt-btif : bta_dm_check_av:0
03-29 13:31:06.147  5947  6057 W bt-btif : btif_dm_cback : unhandled event (14)
,03-29 13:31:06.152  3481  3619 V AlarmManager: waitForAlarm result :4,
,03-29 13:31:06.172  5947  5947 D BtGatt.ScanManager: awakened up at time 279155
03-29 13:31:06.172  5947  6061 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6,
03-29 13:31:06.177  5947  6057 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-29 13:31:06.177  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 13:31:06.222  3481  3575 W ProcessCpuTracker: Skipping unknown process pid 11888
,03-29 13:31:07.182  5947  6139 E bt-btm  : tBTM_SEC_DEV:0xb355429c rs_disc_pending=0
03-29 13:31:07.182  5947  6139 W bt-btif : bta_dm_acl_change(), event : 3
03-29 13:31:07.182  5947  6139 W bt-btif : bta_dm_check_av:0
,03-29 13:31:07.182  5947  6057 W bt-btif : btif_dm_cback : unhandled event (14)
,03-29 13:31:07.187  3481  3619 V AlarmManager: waitForAlarm result :4,
,03-29 13:31:07.202  5947  5947 D BtGatt.ScanManager: awakened up at time 280187,
03-29 13:31:07.207  5947  6061 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-29 13:31:07.207  5947  6057 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-29 13:31:07.207  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 13:31:07.477  5947  6139 W bt-btif : dm_pm_timer expires
03-29 13:31:07.477  5947  6139 W bt-btif : dm_pm_timer expires 0
03-29 13:31:07.477  5947  6139 W bt-btif : proc dm_pm_timer expires
,03-29 13:31:08.217  3481  3619 V AlarmManager: waitForAlarm result :4
,03-29 13:31:08.232  5947  5947 D BtGatt.ScanManager: awakened up at time 281216,
03-29 13:31:08.237  5947  6061 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-29 13:31:08.247  5947  6057 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-29 13:31:08.247  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 13:31:08.282  5947  6303 W bt-btif : invalid rfc slot id: 9
03-29 13:31:08.282 11202 11873 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 1557, thread name: Receiver): bt socket closed, read return: -1
03-29 13:31:08.282 11202 11873 E io.jxcore.node.IncomingSocketThread: The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
03-29 13:31:08.282 11202 11873 W io.jxcore.node.ConnectionHelper: onDisconnected: Incoming connection, peer [<no peer name> F8:95:C7:87:3C:51] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
03-29 13:31:08.282 11202 11873 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1555
03-29 13:31:08.282 11202 11873 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 1555)
03-29 13:31:08.282 11202 11873 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2becc4f6, channel: 6, state: CONNECTED
,03-29 13:31:08.287 11202 11873 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2becc4f6, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@241700f7, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1620db64mSocket: android.net.LocalSocket@22e11cd impl:android.net.LocalSocketImpl@8983a82 fd:FileDescriptor[92]
03-29 13:31:08.287 11202 11873 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@22e11cd impl:android.net.LocalSocketImpl@8983a82 fd:FileDescriptor[92]
03-29 13:31:08.287 11202 11873 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2becc4f6, channel: 6, state: CLOSED
03-29 13:31:08.287 11202 11873 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2becc4f6, channel: 6, state: CLOSED
03-29 13:31:08.287 11202 11873 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-29 13:31:08.287 11202 11873 D io.jxcore.node.IncomingSocketThread: close: Stopping receiving thread...
03-29 13:31:08.287 11202 11873 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 1557
03-29 13:31:08.287 11202 11873 D io.jxcore.node.IncomingSocketThread: close: Stopping sending thread...
03-29 13:31:08.287 11202 11873 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 1556
03-29 13:31:08.287 11202 11873 D io.jxcore.node.IncomingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 1555)
,03-29 13:31:08.287 11202 11872 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 1556, thread name: Sender): Socket closed,
03-29 13:31:08.287 11202 11872 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1556, name: Sender)
,03-29 13:31:08.292 11202 11873 I io.jxcore.node.IncomingSocketThread: close: Complete (thread ID: 1555),
,03-29 13:31:08.292 11202 11873 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,03-29 13:31:08.297 11202 11873 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1557, name: Receiver),
,03-29 13:31:08.307 11202 11266 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-29 13:31:08.307 11202 11266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
03-29 13:31:08.307 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-29 13:31:08.307 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-29 13:31:08.312  5947  6068 D BtGatt.GattService: stopScan() - queue size =1
03-29 13:31:08.312  5947  6303 W bt-btif : invalid rfc slot id: 10
03-29 13:31:08.312  5947  6139 E bt-btm  : tBTM_SEC_DEV:0xb355429c rs_disc_pending=1
03-29 13:31:08.312  5947  6139 W bt-btif : bta_dm_acl_change(), event : 3
03-29 13:31:08.312  5947  6139 W bt-btif : bta_dm_check_av:0
03-29 13:31:08.312  5947  6057 W bt-btif : btif_dm_cback : unhandled event (14)
03-29 13:31:08.312  5947  6061 D BtGatt.ScanManager: filter size is 1
03-29 13:31:08.312  5947  6061 D BtGatt.ScanManager: delete FilterIndex - 14
,03-29 13:31:08.317  5947  6057 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-29 13:31:08.317  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:31:08.317  5947  6061 D BtGatt.ScanManager: stopping BLe Batch
03-29 13:31:08.317  5947 11847 D BtGatt.GattService: unregisterClient() - clientIf=6
03-29 13:31:08.317  5947  6057 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-29 13:31:08.317  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:31:08.317  5947  6061 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-29 13:31:08.322  5947  6057 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-29 13:31:08.322  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 13:31:08.322 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-29 13:31:08.322 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-29 13:31:08.322 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-29 13:31:08.322 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
,03-29 13:31:08.322 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-29 13:31:08.322 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-29 13:31:08.327 11202 11202 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-29 13:31:08.327 11202 11202 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-29 13:31:08.327 11202 11202 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-29 13:31:08.332 11202 11266 I jxcore-log: INFO thaliMobileNativeWrapper: incomingConnectionToPortNumberFailed: %s
03-29 13:31:08.332 11202 11266 I jxcore-log: 
,03-29 13:31:08.332 11202 11266 I jxcore-log: INFO thaliMobileNativeWrapper: got incomingConnectionToPortNumberFailed while not in start
03-29 13:31:08.332 11202 11266 I jxcore-log: 
,03-29 13:31:08.337 11202 11266 I jxcore-log: ok 172 Should be able to call stopListeningForAdvertisments in teardown
03-29 13:31:08.337 11202 11266 I jxcore-log: 
,03-29 13:31:08.337 11202 11266 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-29 13:31:08.337 11202 11266 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> F8:CF:C5:D9:E5:61]
03-29 13:31:08.337 11202 11266 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1553)
03-29 13:31:08.337 11202 11266 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 1553)
,03-29 13:31:08.337 11202 11266 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@d30b593, channel: 5, state: CONNECTED
03-29 13:31:08.337 11202 11266 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@d30b593, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@37c249d0, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1716fdc9mSocket: android.net.LocalSocket@28937cce impl:android.net.LocalSocketImpl@c2717ef fd:FileDescriptor[112]
03-29 13:31:08.337 11202 11266 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@28937cce impl:android.net.LocalSocketImpl@c2717ef fd:FileDescriptor[112]
,03-29 13:31:08.342 11202 11266 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@d30b593, channel: 5, state: CLOSED
03-29 13:31:08.342 11202 11266 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@d30b593, channel: 5, state: CLOSED
03-29 13:31:08.342 11202 11266 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-29 13:31:08.342 11202 11266 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Nothing to close (thread ID: 1553)
03-29 13:31:08.342 11202 11266 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1553)
,03-29 13:31:08.342 11202 11869 D io.jxcore.node.OutgoingSocketThread: Exiting thread (ID: 1553)
03-29 13:31:08.342 11202 11266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-29 13:31:08.342 11202 11266 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-29 13:31:08.342 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,03-29 13:31:08.342 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-29 13:31:08.342 11202 11266 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@7ca32fc, channel: 6, state: LISTENING
03-29 13:31:08.342 11202 11266 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@7ca32fc, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@33369e1b, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1788ad85mSocket: android.net.LocalSocket@23ee97da impl:android.net.LocalSocketImpl@b77440b fd:FileDescriptor[113]
03-29 13:31:08.342 11202 11266 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@23ee97da impl:android.net.LocalSocketImpl@b77440b fd:FileDescriptor[113]
,03-29 13:31:08.347 11202 11266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-29 13:31:08.347 11202 11784 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-29 13:31:08.347 11202 11784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-29 13:31:08.347 11202 11784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-29 13:31:08.347 11202 11202 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-29 13:31:08.347 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-29 13:31:08.347 11202 11202 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-29 13:31:08.347 11202 11202 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-29 13:31:08.347 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-29 13:31:08.347 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-29 13:31:08.347 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-29 13:31:08.347 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-29 13:31:08.352 11202 11266 D BluetoothLeScanner: could not find callback wrapper
03-29 13:31:08.352 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-29 13:31:08.352 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-29 13:31:08.352  5947  6060 D BtGatt.AdvertiseManager: message : 1,
03-29 13:31:08.352  5947  6060 D BtGatt.AdvertiseManager: stop advertise for client 7
03-29 13:31:08.357  5947  6060 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-29 13:31:08.357  5947  6060 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-29 13:31:08.357  5947  6057 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-29 13:31:08.357  5947  6057 D BtGatt.GattService: Client app is not null!
,03-29 13:31:08.362  5947  6068 D BtGatt.GattService: unregisterClient() - clientIf=7,
,03-29 13:31:08.362 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-29 13:31:08.362 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-29 13:31:08.362 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-29 13:31:08.362 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-29 13:31:08.362 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-29 13:31:08.362 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-29 13:31:08.362 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-29 13:31:08.362 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-29 13:31:08.367 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-29 13:31:08.367 11202 11266 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-29 13:31:08.367 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-29 13:31:08.367 11202 11202 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 13:31:08.367 11202 11202 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 13:31:08.367 11202 11202 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-29 13:31:08.367 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-29 13:31:08.367 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-29 13:31:08.372 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-29 13:31:08.372 11202 11266 I jxcore-log: 
,03-29 13:31:08.372 11202 11266 I jxcore-log: ok 173 Should be able to call stopAdvertisingAndListening in teardown
03-29 13:31:08.372 11202 11266 I jxcore-log: 
,03-29 13:31:08.377 11202 11202 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-29 13:31:08.382 11202 11266 I jxcore-log: # setup
03-29 13:31:08.382 11202 11266 I jxcore-log: 
,03-29 13:31:08.382 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
,03-29 13:31:08.387 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-29 13:31:08.387 11202 11202 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-29 13:31:08.387 11202 11202 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-29 13:31:08.387 11202 11202 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-29 13:31:08.392 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 13:31:08.392 11202 11266 I jxcore-log: 
,03-29 13:31:08.392 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 13:31:08.392 11202 11266 I jxcore-log: 
,03-29 13:31:08.527 11202 11266 I jxcore-log: # 41. Can shift large amounts of data
03-29 13:31:08.527 11202 11266 I jxcore-log: 
,03-29 13:31:08.707 11202 11266 I io.jxcore.node.ConnectionHelper: start: Port number: 35027, start advertisements: true
,03-29 13:31:08.707 11202 11266 I io.jxcore.node.ConnectionHelper: restoreDefaultBleDiscoverySettings: Powering the BLE discovery back up
03-29 13:31:08.707 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 0 -> 2
,03-29 13:31:08.712 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-29 13:31:08.712 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-29 13:31:08.712 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-29 13:31:08.712 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-29 13:31:08.712 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-29 13:31:08.712 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-29 13:31:08.717 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 1, timeout: 0, is connectable: false
,03-29 13:31:08.717 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-29 13:31:08.717 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 1 -> 3
03-29 13:31:08.717 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-29 13:31:08.717 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-29 13:31:08.717 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-29 13:31:08.717 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-29 13:31:08.717 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-29 13:31:08.717 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-29 13:31:08.717 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-29 13:31:08.717 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
,03-29 13:31:08.717 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 0 -> 2
03-29 13:31:08.717 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-29 13:31:08.717 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-29 13:31:08.717 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-29 13:31:08.717 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-29 13:31:08.717 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-29 13:31:08.717 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-29 13:31:08.717 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-29 13:31:08.717 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-29 13:31:08.722 11202 11266 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-29 13:31:08.722 11202 11266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,03-29 13:31:08.722 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-29 13:31:08.722 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-29 13:31:08.722 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-29 13:31:08.722 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-29 13:31:08.722 11202 11266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-29 13:31:08.727  5947  5956 D BtGatt.GattService: registerClient() - UUID=415069c2-030f-4f66-b634-39738f0fb9d3
,03-29 13:31:08.767  5947  6057 D BtGatt.GattService: onClientRegistered() - UUID=415069c2-030f-4f66-b634-39738f0fb9d3, clientIf=6
,03-29 13:31:08.767 11202 11214 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-29 13:31:08.772  5947  6068 D BtGatt.GattService: start scan with filters
,03-29 13:31:08.787  5947  6068 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 60,
03-29 13:31:08.787 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-29 13:31:08.787 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-29 13:31:08.787 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-29 13:31:08.787 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-29 13:31:08.787 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 13:31:08.787 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-29 13:31:08.787 11202 11202 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 13:31:08.787 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
,03-29 13:31:08.787 11202 11266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-29 13:31:08.787 11202 11266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 13:31:08.787 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 13:31:08.787 11202 11266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-29 13:31:08.792  5947  6061 D BtGatt.ScanManager: handling starting scan
03-29 13:31:08.792  5947  6061 D BtGatt.ScanManager: isFilteringSupported
03-29 13:31:08.792  5947  6061 D BluetoothAdapter: setting StandAloneBleMode
,03-29 13:31:08.792  5947  6057 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,03-29 13:31:08.792  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:31:08.792  5947  6061 D BtGatt.ScanManager: allow scan with filters
03-29 13:31:08.792  5947  6061 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-29 13:31:08.797  3481  3586 I PowerManagerService: [PWL] Off : 225s ago
03-29 13:31:08.792  5947  6061 D BtGatt.ScanManager: set filter index= 15 for clientIf= 6,
03-29 13:31:08.797  3481  3586 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
03-29 13:31:08.797  5947  6057 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,03-29 13:31:08.797  3481  3586 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
03-29 13:31:08.797  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:31:08.797  3481  3586 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'bluedroid_timer' (uid=1002, pid=5947, ws=null) (elapsedTime=555)
03-29 13:31:08.797  5947  6061 D BtGatt.ScanManager: Starting BLE batch scan
03-29 13:31:08.797  5947  6061 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-29 13:31:08.797  5947  5956 D BtGatt.GattService: registerClient() - UUID=d868ad36-ffda-42fa-9d75-4b1b1ecababc
03-29 13:31:08.797  5947  6057 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-29 13:31:08.797  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:31:08.802  5947  6057 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-29 13:31:08.802  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 13:31:08.837  5947  6057 D BtGatt.GattService: onClientRegistered() - UUID=d868ad36-ffda-42fa-9d75-4b1b1ecababc, clientIf=7
,03-29 13:31:08.837 11202 11212 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-29 13:31:08.852  5947  6068 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 49
,03-29 13:31:08.852  5947  6060 D BtGatt.AdvertiseManager: message : 0
03-29 13:31:08.852  5947  6060 D BtGatt.AdvertiseManager: number of adv instance running0
03-29 13:31:08.852  5947  6060 D BtGatt.AdvertiseManager: size of list is =0
,03-29 13:31:08.852  5947  6060 D BtGatt.AdvertiseManager: starting advertising
03-29 13:31:08.852  5947  6060 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-29 13:31:08.857  5947  6057 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-29 13:31:08.857  5947  6060 D BtGatt.AdvertiseManager: starting multi advertising
,03-29 13:31:08.857  5947  6057 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-29 13:31:08.857  5947  6060 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-29 13:31:08.857  5947  6060 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
03-29 13:31:08.857 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-29 13:31:08.857 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-29 13:31:08.862 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-29 13:31:08.862 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-29 13:31:08.862 11202 11266 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-29 13:31:08.862 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-29 13:31:08.862 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-29 13:31:08.862 11202 11266 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-29 13:31:08.862 11202 11266 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-29 13:31:08.862 11202 11266 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-29 13:31:08.862 11202 11266 I io.jxcore.node.ConnectionHelper: start: OK
03-29 13:31:08.862 11202 11202 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-29 13:31:08.862 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-29 13:31:08.862 11202 11202 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-29 13:31:08.862 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-29 13:31:08.862 11202 11202 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
,03-29 13:31:08.862 11202 11202 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-29 13:31:08.862 11202 11202 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-29 13:31:08.862 11202 11202 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-29 13:31:08.862 11202 11202 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-29 13:31:08.862 11202 11202 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 13:31:08.862 11202 11202 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,03-29 13:31:08.862 11202 11202 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-29 13:31:08.862 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 13:31:08.862 11202 11266 I jxcore-log: 
03-29 13:31:08.867 11202 11916 D BluetoothSocket: bindListen(): myUserId = 0
03-29 13:31:08.867 11202 11916 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-29 13:31:08.867 11202 11266 I jxcore-log: ok 174 Can call startUpdateAdvertisingAndListening without error
03-29 13:31:08.867 11202 11266 I jxcore-log: 
03-29 13:31:08.867 11202 11916 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[93]},
03-29 13:31:08.867 11202 11916 D BluetoothSocket: bindListen(), new LocalSocket 
03-29 13:31:08.867 11202 11916 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-29 13:31:08.867 11202 11916 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@165415e7
03-29 13:31:08.867 11202 11916 D BluetoothSocket: channel: 6
03-29 13:31:08.867 11202 11916 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-29 13:31:08.872 11202 11266 I io.jxcore.node.ConnectionHelper: start: Port number: 35027, start advertisements: false
03-29 13:31:08.872 11202 11266 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-29 13:31:08.872 11202 11266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
03-29 13:31:08.872 11202 11266 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 13:31:08.872 11202 11266 I io.jxcore.node.ConnectionHelper: start: OK
03-29 13:31:08.872 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 13:31:08.872 11202 11266 I jxcore-log: 
,03-29 13:31:08.872 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-29 13:31:08.872 11202 11266 I jxcore-log: 
,03-29 13:31:08.872 11202 11266 I jxcore-log: ok 175 Can call startListeningForAdvertisements without error
03-29 13:31:08.872 11202 11266 I jxcore-log: 
,03-29 13:31:09.322  5947  6139 W bt-rfcomm: rfc_find_lcid_mcb LCID reused LCID:0x43 current:0x0
03-29 13:31:09.322  5947  6139 W bt-rfcomm: RFCOMM_DisconnectInd LCID:0x43
,03-29 13:31:09.657  5947  6139 E bt-btm  : tBTM_SEC_DEV:0xb35540d8 rs_disc_pending=1
03-29 13:31:09.657  5947  6139 W bt-btif : bta_dm_acl_change(), event : 3
,03-29 13:31:09.657  5947  6139 W bt-btif : bta_dm_check_av:0,
03-29 13:31:09.662  5947  6057 W bt-btif : btif_dm_cback : unhandled event (14)
,03-29 13:31:09.807  3481  3619 V AlarmManager: waitForAlarm result :4
,03-29 13:31:09.812  5947  5947 D BtGatt.ScanManager: awakened up at time 282799
03-29 13:31:09.817  5947  6061 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-29 13:31:09.822  5947  6057 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
03-29 13:31:09.822  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:31:09.822  5947  6057 D BtGatt.GattService: current time is 282808060532
03-29 13:31:09.822  5947  6057 D BtGatt.GattService: Batch record : [112, 22, 64, 61, -23, 86, 1, -128, -53, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0, -74, -21, -90, -51, -57, 94, 1, -128, -64, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-29 13:31:09.822  5947  6057 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-29 13:31:09.822  5947  6057 D ScanRecord: parseFromBytes
03-29 13:31:09.822  5947  6057 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-29 13:31:09.822  5947  6057 D ScanRecord: parseFromBytes
,03-29 13:31:09.822  5947  6057 D BtGatt.GattService: result: ScanResult{mDevice=5E:C7:CD:A6:EB:B6, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-64, mTimestampNanos=282758319824},
03-29 13:31:09.822  5947  6057 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-29 13:31:09.822  5947  6057 D BtGatt.GattService: result: ScanResult{mDevice=56:E9:3D:40:16:70, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-53, mTimestampNanos=282708319824}
,03-29 13:31:09.822  5947  6057 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-29 13:31:09.827 11202 11212 D ScanRecord: parseFromBytes
03-29 13:31:09.827 11202 11212 D ScanRecord: parseFromBytes
03-29 13:31:09.827 11202 11202 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 1
03-29 13:31:09.827 11202 11202 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:CF:C5:D9:E5:61], added - the peer count is 2
03-29 13:31:09.827 11202 11202 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
,03-29 13:31:09.827 11202 11202 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:CF:C5:D9:E5:61], Bluetooth address: F8:CF:C5:D9:E5:61, device name: , device address: 
,03-29 13:31:09.852 11202 11266 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID F8:95:C7:87:3C:51,
,03-29 13:31:09.857 11202 11266 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> F8:95:C7:87:3C:51],
,03-29 13:31:09.862 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to G4-1 in address F8:95:C7:87:3C:51,
03-29 13:31:09.862 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
03-29 13:31:09.862 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,03-29 13:31:09.862 11202 11266 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: G4-1 F8:95:C7:87:3C:51
,03-29 13:31:09.862 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to G4-1 in address F8:95:C7:87:3C:51
03-29 13:31:09.867  3481  3863 E Watchdog: !@Sync 9 [03-29 13:31:09.871]
03-29 13:31:09.867 11202 11266 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: F8:95:C7:87:3C:51)
,03-29 13:31:09.867 11202 11923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address F8:95:C7:87:3C:51 (thread ID: 1559)
,03-29 13:31:09.872 11202 11923 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
,03-29 13:31:09.877 11202 11923 D BluetoothSocket: connect(): myUserId = 0
03-29 13:31:09.877 11202 11923 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-29 13:31:09.877  5947 11847 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-29 13:31:09.882 11202 11923 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[112]}
,03-29 13:31:10.442  5947  6139 W bt-sdp  : process_service_search_attr_rsp
,03-29 13:31:10.847  3481  3619 V AlarmManager: waitForAlarm result :4
,03-29 13:31:10.857  5947  5947 D BtGatt.ScanManager: awakened up at time 283844
,03-29 13:31:10.867  5947  6061 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-29 13:31:10.872  5947  6057 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
,03-29 13:31:10.872  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:31:10.872  5947  6057 D BtGatt.GattService: current time is 283855716949
03-29 13:31:10.872  5947  6057 D BtGatt.GattService: Batch record : [112, 22, 64, 61, -23, 86, 1, -128, -53, 4, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0, -74, -21, -90, -51, -57, 94, 1, -128, -64, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0],
03-29 13:31:10.872  5947  6057 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
,03-29 13:31:10.872  5947  6057 D ScanRecord: parseFromBytes,
,03-29 13:31:10.872  5947  6057 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-29 13:31:10.872  5947  6057 D ScanRecord: parseFromBytes
03-29 13:31:10.872  5947  6057 D BtGatt.GattService: result: ScanResult{mDevice=5E:C7:CD:A6:EB:B6, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-64, mTimestampNanos=283855891991}
03-29 13:31:10.872  5947  6057 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-29 13:31:10.872  5947  6057 D BtGatt.GattService: result: ScanResult{mDevice=56:E9:3D:40:16:70, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-53, mTimestampNanos=283655891991}
,03-29 13:31:10.872  5947  6057 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-29 13:31:10.872 11202 11214 D ScanRecord: parseFromBytes
03-29 13:31:10.872 11202 11214 D ScanRecord: parseFromBytes
03-29 13:31:10.872 11202 11202 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
,03-29 13:31:10.872 11202 11202 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:CF:C5:D9:E5:61] updated - the peer count is 2
,03-29 13:31:11.312  5947  6139 W bt-btif : new conn_srvc id:26, app_id:1
,03-29 13:31:11.317  5947 11846 E BluetoothRemoteDevices: setRfcommConnected true
,03-29 13:31:11.337 11202 11923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onSocketConnected: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 1559)
,03-29 13:31:11.337 11202 11923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 1559)
,03-29 13:31:11.347 11202 11923 D BluetoothSocket: getInputStream(): myUserId = 0
,03-29 13:31:11.352 11202 11923 D BluetoothSocket: getOutputStream(): myUserId = 0
,03-29 13:31:11.352 11202 11923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesWritten: 15 bytes successfully written (thread ID: 1560)
03-29 13:31:11.357 11202 11923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Outgoing connection initialized (*handshake* thread ID: 1560)
03-29 13:31:11.357 11202 11923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1559)
03-29 13:31:11.357 11202 11938 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 1560)
,03-29 13:31:11.782  5947  6139 E bt-btm  : tBTM_SEC_DEV:0xb355429c rs_disc_pending=1
03-29 13:31:11.782  5947  6139 W bt-btif : bta_dm_acl_change(), event : 3
03-29 13:31:11.782  5947  6139 W bt-btif : bta_dm_check_av:0
,03-29 13:31:11.787  5947  6057 W bt-btif : btif_dm_cback : unhandled event (14)
,03-29 13:31:11.812  5947  6139 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-29 13:31:11.812  5947  6139 D IOP_DB_BT: db_query: result 1
,03-29 13:31:11.812  5947  6139 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-29 13:31:11.812  5947  6139 D IOP_DB_BT: db_query: result 1
,03-29 13:31:11.892  3481  3619 V AlarmManager: waitForAlarm result :4
,03-29 13:31:11.897  5947  6139 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51,
,03-29 13:31:11.897  5947  6139 D IOP_DB_BT: db_query: result 1
,03-29 13:31:11.897  5947  6139 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-29 13:31:11.897  5947  6139 D IOP_DB_BT: db_query: result 1,
03-29 13:31:11.897 11202 11938 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesRead: Read 15 bytes successfully (thread ID: 1560)
03-29 13:31:11.902 11202 11938 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Handshake succeeded with [<no peer name> F8:95:C7:87:3C:51]
03-29 13:31:11.902 11202 11938 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onHandshakeSucceeded: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 1559)
03-29 13:31:11.902 11202 11938 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: handleSuccessfulClientThread: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 1559)
,03-29 13:31:11.917  5947  5947 D BtGatt.ScanManager: awakened up at time 284903
03-29 13:31:11.917  5947  6061 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-29 13:31:11.922  5947  6057 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=4
03-29 13:31:11.922  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:31:11.922  5947  6057 D BtGatt.GattService: current time is 284909266199,
,03-29 13:31:11.922  5947  6057 D BtGatt.GattService: Batch record : [112, 22, 64, 61, -23, 86, 1, -128, -53, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0, -74, -21, -90, -51, -57, 94, 1, -128, -64, 8, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, 104, -62, 105, 48, 71, 64, 1, -128, -64, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -56, 110, -95, -17, -114, 69, 1, -128, -77, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,03-29 13:31:11.922  5947  6057 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
,03-29 13:31:11.922  5947  6057 D ScanRecord: parseFromBytes
03-29 13:31:11.927  5947  6057 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-29 13:31:11.927  5947  6057 D ScanRecord: parseFromBytes
03-29 13:31:11.927  5947  6057 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81],
,03-29 13:31:11.927  5947  6057 D ScanRecord: parseFromBytes
,03-29 13:31:11.927  5947  6057 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-29 13:31:11.927  5947  6057 D ScanRecord: parseFromBytes
03-29 13:31:11.927  5947  6057 D BtGatt.GattService: result: ScanResult{mDevice=5E:C7:CD:A6:EB:B6, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-64, mTimestampNanos=284509537408}
03-29 13:31:11.927  5947  6057 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-29 13:31:11.927  5947  6057 D BtGatt.GattService: result: ScanResult{mDevice=40:47:30:69:C2:68, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-64, mTimestampNanos=284859537408}
,03-29 13:31:11.927  5947  6057 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-29 13:31:11.927  5947  6057 D BtGatt.GattService: result: ScanResult{mDevice=56:E9:3D:40:16:70, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-53, mTimestampNanos=284859537408}
03-29 13:31:11.927  5947  6057 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-29 13:31:11.927  5947  6057 D BtGatt.GattService: result: ScanResult{mDevice=45:8E:EF:A1:6E:C8, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-77, mTimestampNanos=284909537408}
03-29 13:31:11.927  5947  6057 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null],
03-29 13:31:11.927 11202 11212 D ScanRecord: parseFromBytes
03-29 13:31:11.927 11202 11212 D ScanRecord: parseFromBytes
,03-29 13:31:11.927 11202 11212 D ScanRecord: parseFromBytes
03-29 13:31:11.927 11202 11212 D ScanRecord: parseFromBytes
03-29 13:31:11.942 11202 11202 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:95:C7:87:3C:51]
03-29 13:31:11.942 11202 11202 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing connection to peer [<no peer name> F8:95:C7:87:3C:51]
03-29 13:31:11.942 11202 11202 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
03-29 13:31:11.947 11202 11202 D BluetoothSocket: getInputStream(): myUserId = 0
03-29 13:31:11.947 11202 11202 D BluetoothSocket: getOutputStream(): myUserId = 0
03-29 13:31:11.947 11202 11202 I io.jxcore.node.ConnectionHelper: lowerBleDiscoveryPowerAndStartResetTimer: Lowering the power settings
03-29 13:31:11.947 11202 11202 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 2 -> 0
03-29 13:31:11.952 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-29 13:31:11.952 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-29 13:31:11.952 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-29 13:31:11.952 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-29 13:31:11.952 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-29 13:31:11.952 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-29 13:31:11.952  5947  6060 D BtGatt.AdvertiseManager: message : 1
,03-29 13:31:11.957  5947  6060 D BtGatt.AdvertiseManager: stop advertise for client 7
03-29 13:31:11.957  5947  6060 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-29 13:31:11.957 11202 11938 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 1560)
03-29 13:31:11.962  5947  6060 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-29 13:31:11.962  5947  6057 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-29 13:31:11.962  5947  6057 D BtGatt.GattService: Client app is not null!
,03-29 13:31:11.967  5947  5956 D BtGatt.GattService: unregisterClient() - clientIf=7
03-29 13:31:11.967 11202 11202 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-29 13:31:11.967 11202 11202 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-29 13:31:11.967 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 3, timeout: 0, is connectable: false
03-29 13:31:11.967 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-29 13:31:11.967 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-29 13:31:11.967 11202 11202 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-29 13:31:11.967 11202 11202 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 13:31:11.967 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 13:31:11.967 11202 11202 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-29 13:31:11.972  5947 11846 D BtGatt.GattService: registerClient() - UUID=ae9a7714-72e0-472f-82f0-ad8397933730
,03-29 13:31:12.017  5947  6057 D BtGatt.GattService: onClientRegistered() - UUID=ae9a7714-72e0-472f-82f0-ad8397933730, clientIf=7
,03-29 13:31:12.017 11202 11212 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-29 13:31:12.027  5947  5956 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 50
,03-29 13:31:12.027  5947  6060 D BtGatt.AdvertiseManager: message : 0
03-29 13:31:12.027  5947  6060 D BtGatt.AdvertiseManager: number of adv instance running0
03-29 13:31:12.027  5947  6060 D BtGatt.AdvertiseManager: size of list is =0
,03-29 13:31:12.027  5947  6060 D BtGatt.AdvertiseManager: starting advertising
03-29 13:31:12.027  5947  6060 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-29 13:31:12.032  5947  6057 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-29 13:31:12.032  5947  6060 D BtGatt.AdvertiseManager: starting multi advertising
,03-29 13:31:12.032  5947  6057 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-29 13:31:12.032  5947  6060 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-29 13:31:12.032  5947  6060 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 0, TxPowerLevel: 3, isConnectable: false, Timeout: 0
03-29 13:31:12.032 11202 11202 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-29 13:31:12.037  5947 11847 D BtGatt.GattService: stopScan() - queue size =1
,03-29 13:31:12.037  5947  6061 D BtGatt.ScanManager: filter size is 1
03-29 13:31:12.037  5947  6061 D BtGatt.ScanManager: delete FilterIndex - 15
03-29 13:31:12.037  5947  5958 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-29 13:31:12.037 11202 11202 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-29 13:31:12.037 11202 11202 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-29 13:31:12.042 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-29 13:31:12.042 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-29 13:31:12.042 11202 11202 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-29 13:31:12.042 11202 11202 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-29 13:31:12.042  5947  6057 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-29 13:31:12.042  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:31:12.042  5947  6061 D BtGatt.ScanManager: stopping BLe Batch
,03-29 13:31:12.047  5947  6057 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-29 13:31:12.047  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 13:31:12.047  5947  6061 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-29 13:31:12.047  5947 11847 D BtGatt.GattService: registerClient() - UUID=bde53fee-9799-440f-a35d-466e67346a2a
,03-29 13:31:12.047  5947  6057 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1,
03-29 13:31:12.047  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:31:12.047  5947  6057 D BtGatt.GattService: current time is 285033936074
03-29 13:31:12.047  5947  6057 D BtGatt.GattService: Batch record : [18, 43, 91, 87, -111, 113, 1, -128, -76, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-29 13:31:12.047  5947  6057 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-29 13:31:12.047  5947  6057 D ScanRecord: parseFromBytes
,03-29 13:31:12.092  5947  6057 D BtGatt.GattService: onClientRegistered() - UUID=bde53fee-9799-440f-a35d-466e67346a2a, clientIf=6
03-29 13:31:12.092 11202 11212 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-29 13:31:12.092  5947  5958 D BtGatt.GattService: start scan with filters
,03-29 13:31:12.112  5947  5958 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 61
,03-29 13:31:12.112  5947  6061 D BtGatt.ScanManager: handling starting scan
03-29 13:31:12.112  5947  6061 D BtGatt.ScanManager: isFilteringSupported
03-29 13:31:12.112  5947  6061 D BluetoothAdapter: setting StandAloneBleMode
,03-29 13:31:12.122  5947  6057 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-29 13:31:12.122  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 13:31:12.122  5947  6061 D BtGatt.ScanManager: allow scan with filters
03-29 13:31:12.122  5947  6061 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-29 13:31:12.122  5947  6061 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
03-29 13:31:12.122  5947  6057 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-29 13:31:12.122  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 13:31:12.127  5947  6061 D BtGatt.ScanManager: Starting BLE batch scan
03-29 13:31:12.127  5947  6061 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-29 13:31:12.127  5947  6057 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-29 13:31:12.127  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 13:31:12.132  5947  6057 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-29 13:31:12.132  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:31:12.137 11202 11202 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-29 13:31:12.137 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-29 13:31:12.137 11202 11202 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 3 -> 1
03-29 13:31:12.137 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-29 13:31:12.137 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-29 13:31:12.137 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-29 13:31:12.137 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-29 13:31:12.137 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-29 13:31:12.137 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-29 13:31:12.142  5947  6060 D BtGatt.AdvertiseManager: message : 1
03-29 13:31:12.142  5947  6060 D BtGatt.AdvertiseManager: stop advertise for client 7
03-29 13:31:12.142  5947  6060 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-29 13:31:12.147  5947  6060 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-29 13:31:12.147  5947  6057 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-29 13:31:12.147  5947  6057 D BtGatt.GattService: Client app is not null!
03-29 13:31:12.147  5947  6068 D BtGatt.GattService: unregisterClient() - clientIf=7
03-29 13:31:12.147 11202 11202 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-29 13:31:12.147 11202 11202 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-29 13:31:12.147 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-29 13:31:12.147 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-29 13:31:12.147 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-29 13:31:12.147 11202 11202 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
,03-29 13:31:12.147 11202 11202 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false],
,03-29 13:31:12.147 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 13:31:12.147 11202 11202 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-29 13:31:12.152  5947  6068 D BtGatt.GattService: registerClient() - UUID=f89a7c2a-7d9f-422e-a837-7182d0268f2e
,03-29 13:31:12.197  5947  6057 D BtGatt.GattService: onClientRegistered() - UUID=f89a7c2a-7d9f-422e-a837-7182d0268f2e, clientIf=7,
03-29 13:31:12.197 11202 11212 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-29 13:31:12.242  5947 11847 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 51
,03-29 13:31:12.242  5947  6060 D BtGatt.AdvertiseManager: message : 0
,03-29 13:31:12.242  5947  6060 D BtGatt.AdvertiseManager: number of adv instance running0
03-29 13:31:12.242  5947  6060 D BtGatt.AdvertiseManager: size of list is =0
,03-29 13:31:12.247  5947  6060 D BtGatt.AdvertiseManager: starting advertising
03-29 13:31:12.247  5947  6060 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-29 13:31:12.252  5947  6057 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-29 13:31:12.252  5947  6060 D BtGatt.AdvertiseManager: starting multi advertising
,03-29 13:31:12.257  5947  6057 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-29 13:31:12.257  5947  6060 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-29 13:31:12.257  5947  6060 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 0, TxPowerLevel: 1, isConnectable: false, Timeout: 0
,03-29 13:31:12.257  3481  3575 W ProcessCpuTracker: Skipping unknown process pid 11948
,03-29 13:31:12.257 11202 11202 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-29 13:31:12.257  5947  5956 D BtGatt.GattService: stopScan() - queue size =1
03-29 13:31:12.262  5947  6061 D BtGatt.ScanManager: filter size is 1
03-29 13:31:12.262  5947  6061 D BtGatt.ScanManager: delete FilterIndex - 3,
03-29 13:31:12.262  5947  5958 D BtGatt.GattService: unregisterClient() - clientIf=6
03-29 13:31:12.262 11202 11202 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-29 13:31:12.262 11202 11202 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-29 13:31:12.262  5947  6057 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-29 13:31:12.262  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 13:31:12.262 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-29 13:31:12.262 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-29 13:31:12.262 11202 11202 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-29 13:31:12.262  5947  6061 D BtGatt.ScanManager: stopping BLe Batch
03-29 13:31:12.262 11202 11202 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-29 13:31:12.262  5947  6057 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0,
03-29 13:31:12.262  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:31:12.267  5947  6061 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-29 13:31:12.267  5947  5956 D BtGatt.GattService: registerClient() - UUID=c5d0f081-6125-4bb2-9818-0a143b21b9cc,
03-29 13:31:12.267  5947  6057 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
03-29 13:31:12.267  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:31:12.267  5947  6057 D BtGatt.GattService: current time is 285253365533
,03-29 13:31:12.267  5947  6057 D BtGatt.GattService: Batch record : [112, 22, 64, 61, -23, 86, 1, -128, -56, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0]
03-29 13:31:12.267  5947  6057 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-29 13:31:12.267  5947  6057 D ScanRecord: parseFromBytes
,03-29 13:31:12.307  5947  6057 D BtGatt.GattService: onClientRegistered() - UUID=c5d0f081-6125-4bb2-9818-0a143b21b9cc, clientIf=6,
03-29 13:31:12.307 11202 11212 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-29 13:31:12.307  5947  5958 D BtGatt.GattService: start scan with filters
,03-29 13:31:12.327  5947  5958 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 62
,03-29 13:31:12.332  5947  6061 D BtGatt.ScanManager: handling starting scan
,03-29 13:31:12.332  5947  6061 D BtGatt.ScanManager: isFilteringSupported
,03-29 13:31:12.332  5947  6061 D BluetoothAdapter: setting StandAloneBleMode
03-29 13:31:12.332 11202 11202 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-29 13:31:12.332 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-29 13:31:12.332 11202 11202 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 2 -> 0
03-29 13:31:12.332 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-29 13:31:12.332 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-29 13:31:12.332 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
,03-29 13:31:12.332 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-29 13:31:12.332 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-29 13:31:12.332 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-29 13:31:12.342  5947  6057 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1,
03-29 13:31:12.342  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 13:31:12.342  5947  6061 D BtGatt.ScanManager: allow scan with filters,
,03-29 13:31:12.342  5947  6061 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,03-29 13:31:12.342  5947  6061 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,03-29 13:31:12.342  5947  6060 D BtGatt.AdvertiseManager: message : 1
03-29 13:31:12.342  5947  6057 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-29 13:31:12.342  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 13:31:12.342  5947  6060 D BtGatt.AdvertiseManager: stop advertise for client 7,
03-29 13:31:12.342  5947  6060 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
,03-29 13:31:12.347  5947  6139 W bt-btif : new conn_srvc id:26, app_id:255
03-29 13:31:12.347 11202 11916 D BluetoothSocket: socket fd passed by stack  fds: [Ljava.io.FileDescriptor;@4ddeb39,
03-29 13:31:12.347  5947  6061 D BtGatt.ScanManager: Starting BLE batch scan
03-29 13:31:12.347  5947  6061 D BtGatt.ScanManager: configuring batch scan storage, appIf 6,
03-29 13:31:12.347  5947  6060 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-29 13:31:12.347  5947  5956 E BluetoothRemoteDevices: setRfcommConnected true
03-29 13:31:12.347  5947  6057 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,03-29 13:31:12.352  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:31:12.352 11202 11916 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection accepted
03-29 13:31:12.352  5947  6057 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0,
03-29 13:31:12.352  5947  6057 D BtGatt.GattService: Client app is not null!
03-29 13:31:12.352  5947  5958 D BtGatt.GattService: unregisterClient() - clientIf=7
,03-29 13:31:12.357  5947  6057 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,03-29 13:31:12.357  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:31:12.357 11202 11202 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-29 13:31:12.357 11202 11202 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-29 13:31:12.357 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-29 13:31:12.357 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-29 13:31:12.357 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
,03-29 13:31:12.357 11202 11202 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0,
03-29 13:31:12.357 11202 11202 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 13:31:12.357 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-29 13:31:12.357 11202 11202 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-29 13:31:12.362 11202 11916 D BluetoothSocket: getInputStream(): myUserId = 0
03-29 13:31:12.367  5947 11847 D BtGatt.GattService: registerClient() - UUID=cf8dd51b-7e3a-443d-bdfb-060099b744d2
03-29 13:31:12.367 11202 11916 D BluetoothSocket: getOutputStream(): myUserId = 0
03-29 13:31:12.367 11202 11916 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection initialized (thread ID: 1562)
,03-29 13:31:12.367 11202 11916 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@173eb57e, channel: 6, state: LISTENING
03-29 13:31:12.372 11202 11916 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@173eb57e, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@165415e7, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1e73dadfmSocket: android.net.LocalSocket@2b7e532c impl:android.net.LocalSocketImpl@22901f5 fd:FileDescriptor[93]
03-29 13:31:12.372 11202 11916 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2b7e532c impl:android.net.LocalSocketImpl@22901f5 fd:FileDescriptor[93]
03-29 13:31:12.372 11202 11916 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed,
03-29 13:31:12.372 11202 11954 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 1562)
,03-29 13:31:12.372 11202 11916 D BluetoothSocket: bindListen(): myUserId = 0
03-29 13:31:12.372 11202 11916 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-29 13:31:12.377 11202 11916 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[93]}
03-29 13:31:12.377 11202 11916 D BluetoothSocket: bindListen(), new LocalSocket 
03-29 13:31:12.377 11202 11916 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-29 13:31:12.377 11202 11916 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@228cab8a
,03-29 13:31:12.377 11202 11916 D BluetoothSocket: channel: 6
03-29 13:31:12.377 11202 11916 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-29 13:31:12.407  5947  6057 D BtGatt.GattService: onClientRegistered() - UUID=cf8dd51b-7e3a-443d-bdfb-060099b744d2, clientIf=7
,03-29 13:31:12.407 11202 11212 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-29 13:31:12.422  5947 11846 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 52
,03-29 13:31:12.422  5947  6060 D BtGatt.AdvertiseManager: message : 0
03-29 13:31:12.422  5947  6060 D BtGatt.AdvertiseManager: number of adv instance running0
,03-29 13:31:12.422  5947  6060 D BtGatt.AdvertiseManager: size of list is =0
,03-29 13:31:12.422  5947  6060 D BtGatt.AdvertiseManager: starting advertising
,03-29 13:31:12.422  5947  6060 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-29 13:31:12.427  5947  6057 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-29 13:31:12.427  5947  6060 D BtGatt.AdvertiseManager: starting multi advertising
,03-29 13:31:12.427  5947  6057 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0,
03-29 13:31:12.427  5947  6060 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,03-29 13:31:12.432  5947  6060 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 0, TxPowerLevel: 1, isConnectable: false, Timeout: 0
03-29 13:31:12.432 11202 11202 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-29 13:31:12.432  5947  6068 D BtGatt.GattService: stopScan() - queue size =1
,03-29 13:31:12.432  5947  5958 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-29 13:31:12.432  5947  6061 D BtGatt.ScanManager: filter size is 1
03-29 13:31:12.432  5947  6061 D BtGatt.ScanManager: delete FilterIndex - 4
,03-29 13:31:12.432  5947  6057 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-29 13:31:12.432  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 13:31:12.432 11202 11202 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
03-29 13:31:12.432 11202 11202 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-29 13:31:12.432 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-29 13:31:12.432 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-29 13:31:12.432 11202 11202 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-29 13:31:12.432  5947  6061 D BtGatt.ScanManager: stopping BLe Batch
,03-29 13:31:12.432 11202 11202 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-29 13:31:12.437  5947  6057 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-29 13:31:12.437  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:31:12.437  5947  6061 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-29 13:31:12.442  5947 11847 D BtGatt.GattService: registerClient() - UUID=07bf9b10-29a2-4de5-a065-0fb446c157d0
03-29 13:31:12.442  5947  6057 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
,03-29 13:31:12.442  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:31:12.442  5947  6057 D BtGatt.GattService: current time is 285426221824
03-29 13:31:12.442  5947  6057 D BtGatt.GattService: Batch record : [112, 22, 64, 61, -23, 86, 1, -128, -55, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0]
03-29 13:31:12.442  5947  6057 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-29 13:31:12.442  5947  6057 D ScanRecord: parseFromBytes
,03-29 13:31:12.482  5947  6057 D BtGatt.GattService: onClientRegistered() - UUID=07bf9b10-29a2-4de5-a065-0fb446c157d0, clientIf=6
,03-29 13:31:12.482 11202 11212 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-29 13:31:12.482  5947  5958 D BtGatt.GattService: start scan with filters
,03-29 13:31:12.497  5947  5958 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 63,
,03-29 13:31:12.502 11202 11202 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-29 13:31:12.502 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-29 13:31:12.502 11202 11202 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing socket thread, for peer [<no peer name> F8:95:C7:87:3C:51], created successfully
,03-29 13:31:12.502 11202 11202 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 1
03-29 13:31:12.502 11202 11202 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
03-29 13:31:12.502  5947  6061 D BtGatt.ScanManager: handling starting scan
03-29 13:31:12.502 11202 11202 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
03-29 13:31:12.502  5947  6061 D BtGatt.ScanManager: isFilteringSupported
,03-29 13:31:12.502  5947  6061 D BluetoothAdapter: setting StandAloneBleMode
03-29 13:31:12.502 11202 11202 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:CF:C5:D9:E5:61] updated - the peer count is 2
03-29 13:31:12.502 11202 11202 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2,
03-29 13:31:12.502 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-29 13:31:12.502 11202 11202 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-29 13:31:12.502 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,03-29 13:31:12.502 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-29 13:31:12.502 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-29 13:31:12.507 11202 11957 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1561)
03-29 13:31:12.507 11202 11957 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 53764
03-29 13:31:12.507 11202 11957 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,03-29 13:31:12.507 11202 11957 I io.jxcore.node.ConnectionHelper: onListeningForIncomingConnections: Outgoing connection is using port 53764 (peer ID: F8:95:C7:87:3C:51)
03-29 13:31:12.507 11202 11957 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "F8:95:C7:87:3C:51" removed
03-29 13:31:12.507  5947  6057 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-29 13:31:12.507  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:31:12.507  5947  6061 D BtGatt.ScanManager: allow scan with filters
,03-29 13:31:12.507  5947  6061 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-29 13:31:12.507  5947  6061 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
03-29 13:31:12.512  5947  6057 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-29 13:31:12.512  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:31:12.512  5947  6061 D BtGatt.ScanManager: Starting BLE batch scan
03-29 13:31:12.512  5947  6061 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-29 13:31:12.512 11202 11266 I jxcore-log: INFO testThaliMobileNative: 
03-29 13:31:12.512 11202 11266 I jxcore-log: 
03-29 13:31:12.512  5947  6057 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0,
03-29 13:31:12.512  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:31:12.512 11202 11266 I jxcore-log: INFO testThaliMobileNative: Forward connection
03-29 13:31:12.512 11202 11266 I jxcore-log: 
,03-29 13:31:12.517  5947  6057 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-29 13:31:12.517  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 13:31:12.522 11202 11957 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 53764
03-29 13:31:12.522 11202 11957 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
03-29 13:31:12.522 11202 11957 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-29 13:31:12.522 11202 11957 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-29 13:31:12.522 11202 11957 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1561)
03-29 13:31:12.522 11202 11957 D io.jxcore.node.OutgoingSocketThread: Exiting thread (ID: 1561)
,03-29 13:31:12.522 11202 11958 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1563, name: Sender)
,03-29 13:31:12.522 11202 11266 I jxcore-log: INFO testThaliMobileNative: forwardSend
03-29 13:31:12.522 11202 11266 I jxcore-log: 
,03-29 13:31:12.527 11202 11959 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1564, name: Receiver)
,03-29 13:31:12.782  5947  6139 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-29 13:31:12.782  5947  6139 D IOP_DB_BT: db_query: result 1
03-29 13:31:12.782  5947  6139 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-29 13:31:12.782  5947  6139 D IOP_DB_BT: db_query: result 1
03-29 13:31:12.782 11202 11954 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesRead: Read 15 bytes successfully (thread ID: 1562)
03-29 13:31:12.787 11202 11954 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Got valid identity from [<no peer name> F8:95:C7:87:3C:51]
,03-29 13:31:12.797  5947  6139 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-29 13:31:12.797  5947  6139 D IOP_DB_BT: db_query: result 1
03-29 13:31:12.797  5947  6139 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-29 13:31:12.797  5947  6139 D IOP_DB_BT: db_query: result 1
,03-29 13:31:12.802 11202 11954 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesWritten: 15 bytes successfully written (thread ID: 1562),
,03-29 13:31:12.802 11202 11954 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: removeThreadFromList: Removing thread with ID 1562
,03-29 13:31:12.802 11202 11954 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Handshake thread disposed (thread ID: 1562)
03-29 13:31:12.802 11202 11954 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onIncomingConnectionConnected: [<no peer name> F8:95:C7:87:3C:51],
,03-29 13:31:12.807 11202 11202 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:95:C7:87:3C:51]
03-29 13:31:12.807 11202 11202 I io.jxcore.node.ConnectionHelper: onConnected: Incoming connection to peer [<no peer name> F8:95:C7:87:3C:51],
,03-29 13:31:12.807 11202 11202 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2,
03-29 13:31:12.812 11202 11202 D BluetoothSocket: getInputStream(): myUserId = 0
03-29 13:31:12.817 11202 11202 D BluetoothSocket: getOutputStream(): myUserId = 0
03-29 13:31:12.817 11202 11202 I io.jxcore.node.ConnectionHelper: onConnected: Incoming socket thread, for peer [<no peer name> F8:95:C7:87:3C:51], created successfully
,03-29 13:31:12.817 11202 11202 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 2
03-29 13:31:12.817 11202 11954 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 1562)
,03-29 13:31:12.822 11202 11963 D io.jxcore.node.IncomingSocketThread: Entering thread (ID: 1565),
,03-29 13:31:12.827  2873  3455 D EnterpriseController: netId is 0
03-29 13:31:12.827  2873  3455 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,03-29 13:31:12.827 11202 11963 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 35027
,03-29 13:31:12.832 11202 11963 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,03-29 13:31:12.832 11202 11963 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
,03-29 13:31:12.832 11202 11963 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
,03-29 13:31:12.837 11202 11963 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 1565)
03-29 13:31:12.837 11202 11963 D io.jxcore.node.IncomingSocketThread: Exiting thread (ID: 1565)
,03-29 13:31:12.837 11202 11965 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1566, name: Sender)
,03-29 13:31:12.837 11202 11966 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1567, name: Receiver)
,03-29 13:31:12.852  5947  6139 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-29 13:31:12.852  5947  6139 D IOP_DB_BT: db_query: result 1
03-29 13:31:12.852  5947  6139 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-29 13:31:12.852  5947  6139 D IOP_DB_BT: db_query: result 1
,03-29 13:31:12.857 11202 11213 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@173eb57e, channel: 6, state: CLOSED
,03-29 13:31:12.857 11202 11266 I jxcore-log: INFO testThaliMobileNative: forwardData
03-29 13:31:12.857 11202 11266 I jxcore-log: 
,03-29 13:31:12.917  5947  6139 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-29 13:31:12.922  5947  6139 D IOP_DB_BT: db_query: result 1
03-29 13:31:12.922  5947  6139 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-29 13:31:12.922  5947  6139 D IOP_DB_BT: db_query: result 1
,03-29 13:31:12.952 11202 11266 I jxcore-log: INFO testThaliMobileNative: forwardData
03-29 13:31:12.952 11202 11266 I jxcore-log: 
,03-29 13:31:12.987  5947  6139 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-29 13:31:12.987  5947  6139 D IOP_DB_BT: db_query: result 1
03-29 13:31:12.987  5947  6139 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-29 13:31:12.987  5947  6139 D IOP_DB_BT: db_query: result 1
03-29 13:31:12.992 11202 11266 I jxcore-log: INFO testThaliMobileNative: forwardData
03-29 13:31:12.992 11202 11266 I jxcore-log: 
,03-29 13:31:13.052  5947  6139 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-29 13:31:13.052  5947  6139 D IOP_DB_BT: db_query: result 1
03-29 13:31:13.052  5947  6139 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-29 13:31:13.057  5947  6139 D IOP_DB_BT: db_query: result 1
,03-29 13:31:13.067 11202 11266 I jxcore-log: INFO testThaliMobileNative: forwardData
03-29 13:31:13.067 11202 11266 I jxcore-log: 
,03-29 13:31:13.112  5947  6139 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-29 13:31:13.112  5947  6139 D IOP_DB_BT: db_query: result 1
03-29 13:31:13.112  5947  6139 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-29 13:31:13.117  5947  6139 D IOP_DB_BT: db_query: result 1
,03-29 13:31:13.122  5947  6139 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-29 13:31:13.122  5947  6139 D IOP_DB_BT: db_query: result 1
03-29 13:31:13.122  5947  6139 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-29 13:31:13.122  5947  6139 D IOP_DB_BT: db_query: result 1
,03-29 13:31:13.127 11202 11266 I jxcore-log: INFO testThaliMobileNative: forwardData
03-29 13:31:13.127 11202 11266 I jxcore-log: 
,03-29 13:31:13.132 11202 11266 I jxcore-log: ok 176 received should match sent forward
03-29 13:31:13.132 11202 11266 I jxcore-log: 
,03-29 13:31:13.147  5947  6139 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-29 13:31:13.147  5947  6139 D IOP_DB_BT: db_query: result 1
03-29 13:31:13.147  5947  6139 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-29 13:31:13.147  5947  6139 D IOP_DB_BT: db_query: result 1
,03-29 13:31:13.157 11202 11266 I jxcore-log: # teardown
03-29 13:31:13.157 11202 11266 I jxcore-log: 
,03-29 13:31:13.317  5947  6139 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-29 13:31:13.317  5947  6139 D IOP_DB_BT: db_query: result 1
03-29 13:31:13.317  5947  6139 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-29 13:31:13.317  5947  6139 D IOP_DB_BT: db_query: result 1
03-29 13:31:13.317  5947  6139 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-29 13:31:13.317  5947  6139 D IOP_DB_BT: db_query: result 1
03-29 13:31:13.317  5947  6139 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-29 13:31:13.322  5947  6139 D IOP_DB_BT: db_query: result 1
,03-29 13:31:13.332  5947  6139 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51,
,03-29 13:31:13.332  5947  6139 D IOP_DB_BT: db_query: result 1
,03-29 13:31:13.332  5947  6139 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51,
03-29 13:31:13.337  5947  6139 D IOP_DB_BT: db_query: result 1
,03-29 13:31:13.412  5947  6139 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-29 13:31:13.412  5947  6139 D IOP_DB_BT: db_query: result 1
03-29 13:31:13.412  5947  6139 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-29 13:31:13.412  5947  6139 D IOP_DB_BT: db_query: result 1
,03-29 13:31:13.417  5947  6139 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-29 13:31:13.417  5947  6139 D IOP_DB_BT: db_query: result 1
03-29 13:31:13.417  5947  6139 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-29 13:31:13.417  5947  6139 D IOP_DB_BT: db_query: result 1
,03-29 13:31:13.477  5947  6139 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-29 13:31:13.477  5947  6139 D IOP_DB_BT: db_query: result 1
03-29 13:31:13.477  5947  6139 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-29 13:31:13.477  5947  6139 D IOP_DB_BT: db_query: result 1
,03-29 13:31:13.482  5947  6139 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-29 13:31:13.482  5947  6139 D IOP_DB_BT: db_query: result 1
03-29 13:31:13.482  5947  6139 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-29 13:31:13.482  5947  6139 D IOP_DB_BT: db_query: result 1
,03-29 13:31:13.507  3481  4417 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-29 13:31:13.507  3481  4417 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-29 13:31:13.507  3481  4417 D BatteryService: online:4, current avg:32, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:39
03-29 13:31:13.507  3481  4417 D BatteryService: stay LED for fully charged
03-29 13:31:13.507  3481  3481 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-29 13:31:13.507  3481  3481 I MotionRecognitionService: Plugged
03-29 13:31:13.507  3481  3481 D MotionRecognitionService:   cableConnection= 1
03-29 13:31:13.507  3481  3481 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-29 13:31:13.507  3481  3481 D MotionRecognitionService: skip setTransmitPower. 
,03-29 13:31:13.512  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-29 13:31:13.512  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-29 13:31:13.512  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-29 13:31:13.517  3481  3619 V AlarmManager: waitForAlarm result :4
,03-29 13:31:13.517  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-29 13:31:13.522  5947  5947 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-29 13:31:13.522  5947  6065 D HeadsetStateMachine: Disconnected process message: 10
,03-29 13:31:13.527  5947  5947 D BtGatt.ScanManager: awakened up at time 286510,
03-29 13:31:13.527  5947  6061 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-29 13:31:13.527  5947  6057 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2,
03-29 13:31:13.527  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:31:13.527  5947  6057 D BtGatt.GattService: current time is 286514043783
03-29 13:31:13.527  5947  6057 D BtGatt.GattService: Batch record : [112, 22, 64, 61, -23, 86, 1, -128, -60, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0, 18, 43, 91, 87, -111, 113, 1, -128, -82, 11, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,03-29 13:31:13.527  5947  6057 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-29 13:31:13.527  5947  6057 D ScanRecord: parseFromBytes
03-29 13:31:13.527  5947  6057 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-29 13:31:13.527  5947  6057 D ScanRecord: parseFromBytes
03-29 13:31:13.532  5947  6057 D BtGatt.GattService: result: ScanResult{mDevice=71:91:57:5B:2B:12, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-82, mTimestampNanos=285964248741}
03-29 13:31:13.532  5947  6057 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
,03-29 13:31:13.532  5947  6057 D BtGatt.GattService: result: ScanResult{mDevice=56:E9:3D:40:16:70, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-60, mTimestampNanos=286464248741}
03-29 13:31:13.532  5947  6057 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-29 13:31:13.532 11202 11214 D ScanRecord: parseFromBytes
03-29 13:31:13.532 11202 11214 D ScanRecord: parseFromBytes
03-29 13:31:13.532 11202 11202 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
,03-29 13:31:13.532 11202 11202 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:CF:C5:D9:E5:61] updated - the peer count is 2
,03-29 13:31:13.537  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-29 13:31:13.537  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-29 13:31:13.537  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-29 13:31:13.887  5947  6139 E bt-btm  : Reset sec_bd_name and name flag. (BR/EDR link)
03-29 13:31:13.887  5947  6139 E bt-btm  : btm_sec_disconnected - Clearing Pending flag
03-29 13:31:13.887  5947  6139 W bt-btif : bta_dm_acl_change(), event : 1
03-29 13:31:13.887  5947  6139 W bt-btif : bta_dm_acl_change(), event : 2
,03-29 13:31:13.887  5947  6057 E BluetoothRemoteDevices: aclStateChangeCallback: State:DisConnected to Device:F8:CF:C5:D9:E5:XX
03-29 13:31:13.912  5947  6057 D BluetoothUtils: getBtEnabledContainers(): btContainers = [],
03-29 13:31:13.917  3726  3726 D KeyguardViewMediator: Received android.bluetooth.device.action.ACL_DISCONNECTED
,03-29 13:31:13.932  3481  3481 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
03-29 13:31:13.932  3481  3481 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.device.action.ACL_DISCONNECTED
03-29 13:31:13.932  3481  3481 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_ACL_DISCONNECTED
,03-29 13:31:13.942  3481  3575 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{32dae84 u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{175ebf7c 5947:com.android.bluetooth/1002}
,03-29 13:31:13.947  3481  4718 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
,03-29 13:31:13.947  3726  3726 D KeyguardViewMediator: isGear1: device is not B1!
,03-29 13:31:13.957  5947  5947 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d3d4163
03-29 13:31:13.957  5947  5947 D BtConfig.SecureMode: isSecureModeOn:false
,03-29 13:31:13.957  3481  3982 D SecContentProvider: query(), uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,03-29 13:31:13.962 10367 11988 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.ACL_DISCONNECTED State = -2147483648 Previous = -2147483648
,03-29 13:31:13.967  3481  4028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,03-29 13:31:13.967  5947  5947 I BluetoothPbapService: action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,03-29 13:31:13.972 10367 10367 D [CarModeFW]: ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED
,03-29 13:31:13.972 10367 10367 D [CarModeFW]: ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED onNotifyBluetoothDeviceDisconnected
,03-29 13:31:13.972  3481  3982 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-29 13:31:13.972  3481  3982 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-29 13:31:13.972  3481  3982 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-29 13:31:13.972  3481  3982 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-29 13:31:13.977 10367 10367 D [CarModeFW]: ConnectivityManager-Paired Devices list is empty
,03-29 13:31:13.977 10367 10367 E [CarMode]: [BluetoothConnectivityListener]-onNotifyBluetoothProfileDisconnected: Unexpected error: Invalid device
,03-29 13:31:13.987 11989 11989 E Zygote  : MountEmulatedStorage()
03-29 13:31:13.987 11989 11989 E Zygote  : v2
03-29 13:31:13.987 11989 11989 I libpersona: KNOX_SDCARD checking this for 10036
03-29 13:31:13.987 11989 11989 I libpersona: KNOX_SDCARD not a persona
,03-29 13:31:13.992 11989 11989 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
,03-29 13:31:13.992  3481  3982 I ActivityManager: Start proc 11989:com.sec.android.app.shealth/u0a36 for broadcast-3 com.sec.android.app.shealth/com.samsung.android.app.shealth.tracker.weight.receiver.TrackerWeightReceiver
,03-29 13:31:13.992 11989 11989 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
03-29 13:31:13.997 11989 11989 E Zygote  : accessInfo : 0
03-29 13:31:13.997 11989 11989 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-29 13:31:14.017 11989 11989 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-29 13:31:14.017 11989 11989 D ActivityThread: Added TimaKeyStore provider
,03-29 13:31:14.027  3481  4028 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{32dae84 u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{141c12a2 11989:com.sec.android.app.shealth/u0a36}
,03-29 13:31:14.042 11989 11989 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-29 13:31:14.132 11989 11989 D HealthConsole: Service for HealthDataConsole is connected
,03-29 13:31:14.137  3481  3745 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{32dae84 u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{141c12a2 11989:com.sec.android.app.shealth/u0a36}
,03-29 13:31:14.152 11989 11989 D HealthConsole: Service for HealthDataConsole is connected
,03-29 13:31:14.157  3481  3651 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{32dae84 u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{141c12a2 11989:com.sec.android.app.shealth/u0a36}
,03-29 13:31:14.167  3481  3745 I ActivityManager: Killing 10225:com.facebook.system/u0a10 (adj 15): emptyCount ##31
,03-29 13:31:14.172  3481  3745 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{32dae84 u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{338c15d0 4130:com.google.android.googlequicksearchbox:search/u0a64}
,03-29 13:31:14.187  4130  4130 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,03-29 13:31:14.192  4130  4130 I BluetoothClassifier: Bluetooth Device Name: Nexus 6
,03-29 13:31:14.342  3481  6174 D SSRM:n  : SIOP:: AP = 270, PST = 283 (W:18), CUR = 32, LCD = 0
,03-29 13:31:14.532  3481  3619 V AlarmManager: waitForAlarm result :4
,03-29 13:31:14.542  5947  5947 D BtGatt.ScanManager: awakened up at time 287529
,03-29 13:31:14.552  5947  6061 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-29 13:31:14.557  5947  6057 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
03-29 13:31:14.557  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:31:14.557  5947  6057 D BtGatt.GattService: current time is 287540481324
03-29 13:31:14.557  5947  6057 D BtGatt.GattService: Batch record : [112, 22, 64, 61, -23, 86, 1, -128, -55, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0]
03-29 13:31:14.557  5947  6057 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-29 13:31:14.557  5947  6057 D ScanRecord: parseFromBytes
03-29 13:31:14.557  5947  6057 D BtGatt.GattService: result: ScanResult{mDevice=56:E9:3D:40:16:70, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-55, mTimestampNanos=287440656908}
03-29 13:31:14.557  5947  6057 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-29 13:31:14.557 11202 11212 D ScanRecord: parseFromBytes
03-29 13:31:14.557 11202 11202 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:CF:C5:D9:E5:61] updated - the peer count is 2
,03-29 13:31:14.662  5947  6139 E bt-btm  : tBTM_SEC_DEV:0xb355429c rs_disc_pending=0
03-29 13:31:14.662  5947  6139 W bt-btif : bta_dm_acl_change(), event : 3
03-29 13:31:14.662  5947  6139 W bt-btif : bta_dm_check_av:0
03-29 13:31:14.662  5947  6057 W bt-btif : btif_dm_cback : unhandled event (14)
,03-29 13:31:15.572  3481  3619 V AlarmManager: waitForAlarm result :4,
,03-29 13:31:15.587  5947  5947 D BtGatt.ScanManager: awakened up at time 288569
03-29 13:31:15.592  5947  6061 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-29 13:31:15.597  5947  6057 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=4
03-29 13:31:15.597  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:31:15.597  5947  6057 D BtGatt.GattService: current time is 288583701658
03-29 13:31:15.597  5947  6057 D BtGatt.GattService: Batch record : [123, -25, 93, 25, -126, 89, 1, -128, -55, 17, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0, 55, 93, -19, 22, 111, 100, 1, -128, -68, 16, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0, -96, -10, 69, 89, -21, 109, 1, -128, -68, 15, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0, 18, 43, 91, 87, -111, 113, 1, -128, -81, 13, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-29 13:31:15.597  5947  6057 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-29 13:31:15.597  5947  6057 D ScanRecord: parseFromBytes
03-29 13:31:15.597  5947  6057 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-29 13:31:15.597  5947  6057 D ScanRecord: parseFromBytes
03-29 13:31:15.597  5947  6057 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-29 13:31:15.597  5947  6057 D ScanRecord: parseFromBytes
03-29 13:31:15.602  5947  6057 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-29 13:31:15.602  5947  6057 D ScanRecord: parseFromBytes
,03-29 13:31:15.602  5947  6057 D BtGatt.GattService: result: ScanResult{mDevice=6D:EB:59:45:F6:A0, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-68, mTimestampNanos=287833990658}
,03-29 13:31:15.602  5947  6057 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-29 13:31:15.602  5947  6057 D BtGatt.GattService: result: ScanResult{mDevice=71:91:57:5B:2B:12, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-81, mTimestampNanos=287933990658}
03-29 13:31:15.602  5947  6057 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-29 13:31:15.602  5947  6057 D BtGatt.GattService: result: ScanResult{mDevice=59:82:19:5D:E7:7B, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-55, mTimestampNanos=287733990658}
,03-29 13:31:15.602  5947  6057 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-29 13:31:15.602  5947  6057 D BtGatt.GattService: result: ScanResult{mDevice=64:6F:16:ED:5D:37, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-68, mTimestampNanos=287783990658}
03-29 13:31:15.602  5947  6057 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-29 13:31:15.602 11202 11214 D ScanRecord: parseFromBytes
03-29 13:31:15.602 11202 11214 D ScanRecord: parseFromBytes
03-29 13:31:15.602 11202 11214 D ScanRecord: parseFromBytes
03-29 13:31:15.602 11202 11214 D ScanRecord: parseFromBytes
,03-29 13:31:15.602 11202 11202 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:CF:C5:D9:E5:61] updated - the peer count is 2
03-29 13:31:15.602 11202 11202 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
03-29 13:31:15.602 11202 11202 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:CF:C5:D9:E5:61] updated - the peer count is 2
03-29 13:31:15.602 11202 11202 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:CF:C5:D9:E5:61] updated - the peer count is 2
,03-29 13:31:15.627 11202 11965 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 1566, thread name: Sender)
03-29 13:31:15.627 11202 11965 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Input stream got -1 on read
03-29 13:31:15.632 11202 11965 W io.jxcore.node.ConnectionHelper: onDisconnected: Incoming connection, peer [<no peer name> F8:95:C7:87:3C:51] disconnected: Input stream got -1 on read
03-29 13:31:15.632 11202 11965 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1565
03-29 13:31:15.632 11202 11965 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 1565)
03-29 13:31:15.632 11202 11965 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@23af39cf, channel: 6, state: CONNECTED
03-29 13:31:15.632 11202 11965 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@23af39cf, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1a52df5c, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@127f5265mSocket: android.net.LocalSocket@a6f0b3a impl:android.net.LocalSocketImpl@2f8fa3eb fd:FileDescriptor[113]
,03-29 13:31:15.632 11202 11965 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@a6f0b3a impl:android.net.LocalSocketImpl@2f8fa3eb fd:FileDescriptor[113]
03-29 13:31:15.632 11202 11966 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 1567, thread name: Receiver): bt socket closed, read return: -1
03-29 13:31:15.632 11202 11966 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1567, name: Receiver)
03-29 13:31:15.632 11202 11266 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-29 13:31:15.632 11202 11266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
03-29 13:31:15.632 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-29 13:31:15.632 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-29 13:31:15.632  5947  6139 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-29 13:31:15.632  5947  6139 D IOP_DB_BT: db_query: result 1
03-29 13:31:15.632  5947  6139 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-29 13:31:15.632  5947  6139 D IOP_DB_BT: db_query: result 1
,03-29 13:31:15.632  5947  6068 D BtGatt.GattService: stopScan() - queue size =1
,03-29 13:31:15.637 11202 11965 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@23af39cf, channel: 6, state: CLOSED
03-29 13:31:15.637  5947  6061 D BtGatt.ScanManager: filter size is 1
03-29 13:31:15.637  5947  6061 D BtGatt.ScanManager: delete FilterIndex - 5
,03-29 13:31:15.637 11202 11965 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@23af39cf, channel: 6, state: CLOSED,
03-29 13:31:15.637 11202 11965 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
,03-29 13:31:15.637 11202 11965 D io.jxcore.node.IncomingSocketThread: close: Stopping receiving thread...
03-29 13:31:15.637 11202 11965 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 1567
,03-29 13:31:15.637 11202 11965 D io.jxcore.node.IncomingSocketThread: close: Stopping sending thread...
03-29 13:31:15.637  5947  6057 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,03-29 13:31:15.637  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
03-29 13:31:15.637  5947 11847 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-29 13:31:15.637  5947  6061 D BtGatt.ScanManager: stopping BLe Batch
03-29 13:31:15.637 11202 11965 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 1566
03-29 13:31:15.637 11202 11965 D io.jxcore.node.IncomingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 1565)
03-29 13:31:15.637 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-29 13:31:15.637 11202 11965 I io.jxcore.node.IncomingSocketThread: close: Complete (thread ID: 1565)
03-29 13:31:15.637 11202 11965 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
03-29 13:31:15.637 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-29 13:31:15.637 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,03-29 13:31:15.642 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-29 13:31:15.642 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-29 13:31:15.642 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-29 13:31:15.642 11202 11202 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-29 13:31:15.642  5947  6057 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-29 13:31:15.642  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:31:15.642 11202 11965 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1566, name: Sender)
,03-29 13:31:15.642  5947  6061 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-29 13:31:15.642 11202 11202 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-29 13:31:15.642 11202 11202 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 13:31:15.642  5947  6057 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-29 13:31:15.642  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:31:15.647 11202 11266 I jxcore-log: ok 177 Should be able to call stopListeningForAdvertisments in teardown
03-29 13:31:15.647 11202 11266 I jxcore-log: 
03-29 13:31:15.647  5947  6139 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0x13):jv handle:0x0 not FOUND
03-29 13:31:15.647  5947  6139 E bt-btif : bta_jv_port_mgmt_sr_cback, p_cb:0x0, p_cb->p_cback0x0
03-29 13:31:15.647 11202 11266 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-29 13:31:15.647 11202 11266 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> F8:95:C7:87:3C:51]
03-29 13:31:15.647 11202 11266 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1561)
03-29 13:31:15.647 11202 11266 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 1561)
03-29 13:31:15.647 11202 11266 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@36dc9548, channel: 7, state: CONNECTED
03-29 13:31:15.647 11202 11266 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@36dc9548, channel: 7, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@f17afe1, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@db2a106mSocket: android.net.LocalSocket@12c293c7 impl:android.net.LocalSocketImpl@18c9bdf4 fd:FileDescriptor[112]
03-29 13:31:15.647 11202 11266 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@12c293c7 impl:android.net.LocalSocketImpl@18c9bdf4 fd:FileDescriptor[112]
03-29 13:31:15.647 11202 11266 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@36dc9548, channel: 7, state: CLOSED
03-29 13:31:15.647 11202 11266 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@36dc9548, channel: 7, state: CLOSED
03-29 13:31:15.647 11202 11266 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
,03-29 13:31:15.647 11202 11266 D io.jxcore.node.OutgoingSocketThread: close: Stopping receiving thread...
03-29 13:31:15.647 11202 11266 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 1564
03-29 13:31:15.647 11202 11266 D io.jxcore.node.OutgoingSocketThread: close: Stopping sending thread...
03-29 13:31:15.647 11202 11959 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 1564, thread name: Receiver): bt socket closed, read return: -1
03-29 13:31:15.647 11202 11266 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 1563
03-29 13:31:15.647 11202 11959 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1564, name: Receiver)
03-29 13:31:15.647 11202 11266 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 1561)
03-29 13:31:15.647 11202 11958 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 1563, thread name: Sender): Socket closed
,03-29 13:31:15.647 11202 11958 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1563, name: Sender)
03-29 13:31:15.647 11202 11266 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1561)
03-29 13:31:15.652 11202 11266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-29 13:31:15.652 11202 11266 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-29 13:31:15.652 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-29 13:31:15.652 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-29 13:31:15.652 11202 11266 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@247e691d, channel: 6, state: LISTENING
03-29 13:31:15.652 11202 11266 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@247e691d, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@228cab8a, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3747c792mSocket: android.net.LocalSocket@154aa563 impl:android.net.LocalSocketImpl@1cbec560 fd:FileDescriptor[93]
03-29 13:31:15.652 11202 11266 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@154aa563 impl:android.net.LocalSocketImpl@1cbec560 fd:FileDescriptor[93]
,03-29 13:31:15.652 11202 11266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-29 13:31:15.652 11202 11916 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-29 13:31:15.652 11202 11916 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-29 13:31:15.652 11202 11916 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,03-29 13:31:15.652 11202 11202 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-29 13:31:15.652 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-29 13:31:15.652 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-29 13:31:15.652 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-29 13:31:15.652 11202 11202 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-29 13:31:15.652 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-29 13:31:15.652 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-29 13:31:15.652 11202 11266 D BluetoothLeScanner: could not find callback wrapper
,03-29 13:31:15.652 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-29 13:31:15.652 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-29 13:31:15.657  5947  6060 D BtGatt.AdvertiseManager: message : 1
,03-29 13:31:15.657  5947  6060 D BtGatt.AdvertiseManager: stop advertise for client 7
03-29 13:31:15.657  5947  6060 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7,
03-29 13:31:15.657  5947  6060 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,03-29 13:31:15.662  5947  6057 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
,03-29 13:31:15.662  5947  6057 D BtGatt.GattService: Client app is not null!
03-29 13:31:15.662  5947  5958 D BtGatt.GattService: unregisterClient() - clientIf=7
,03-29 13:31:15.662 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-29 13:31:15.662 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-29 13:31:15.662 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-29 13:31:15.662 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-29 13:31:15.662 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,03-29 13:31:15.662 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-29 13:31:15.662 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-29 13:31:15.662 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-29 13:31:15.667 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-29 13:31:15.667 11202 11266 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-29 13:31:15.667 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-29 13:31:15.667 11202 11202 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-29 13:31:15.667 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-29 13:31:15.667 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-29 13:31:15.667 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-29 13:31:15.667 11202 11266 I jxcore-log: 
03-29 13:31:15.667 11202 11266 I jxcore-log: INFO thaliMobileNativeWrapper: incomingConnectionToPortNumberFailed: %s
03-29 13:31:15.667 11202 11266 I jxcore-log: 
03-29 13:31:15.667 11202 11266 I jxcore-log: INFO thaliMobileNativeWrapper: got incomingConnectionToPortNumberFailed while not in start
03-29 13:31:15.667 11202 11266 I jxcore-log: 
,03-29 13:31:15.672 11202 11202 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-29 13:31:15.677 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false,
03-29 13:31:15.677 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
,03-29 13:31:15.677 11202 11202 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-29 13:31:15.677 11202 11202 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 13:31:15.677 11202 11202 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 13:31:15.677 11202 11202 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-29 13:31:15.682 11202 11266 I jxcore-log: ok 178 Should be able to call stopAdvertisingAndListening in teardown
03-29 13:31:15.682 11202 11266 I jxcore-log: 
,03-29 13:31:15.682 11202 11202 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-29 13:31:15.682 11202 11202 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-29 13:31:15.687 11202 11266 I jxcore-log: # setup
03-29 13:31:15.687 11202 11266 I jxcore-log: 
,03-29 13:31:15.687 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 13:31:15.687 11202 11266 I jxcore-log: 
,03-29 13:31:15.692 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 13:31:15.692 11202 11266 I jxcore-log: 
,03-29 13:31:15.757  5947  6139 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0x14):jv handle:0x0 not FOUND
,03-29 13:31:16.292 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-29 13:31:16.292 11202 11266 I jxcore-log: 
,03-29 13:31:16.297 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-29 13:31:16.297 11202 11266 I jxcore-log: 
,03-29 13:31:16.307 11202 11266 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-29 13:31:16.307 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-29 13:31:16.307 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-29 13:31:16.307 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-29 13:31:16.307 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-29 13:31:16.307 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-29 13:31:16.307 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-29 13:31:16.307 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-29 13:31:16.312 11202 11266 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-29 13:31:16.312 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-29 13:31:16.312 11202 11266 I jxcore-log: 
,03-29 13:31:16.317 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-29 13:31:16.317 11202 11266 I jxcore-log: 
,03-29 13:31:16.322 11202 11266 I jxcore-log: # 42. #startListeningForAdvertisements should fail if start not called
03-29 13:31:16.322 11202 11266 I jxcore-log: 
,03-29 13:31:16.322 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-29 13:31:16.322 11202 11266 I jxcore-log: 
,03-29 13:31:17.222 11202 11266 I jxcore-log: ok 179 specific error should be returned
03-29 13:31:17.222 11202 11266 I jxcore-log: 
,03-29 13:31:17.227 11202 11266 I jxcore-log: # teardown
03-29 13:31:17.227 11202 11266 I jxcore-log: 
,03-29 13:31:17.342 11202 11266 I jxcore-log: ok 180 must be stopped
03-29 13:31:17.342 11202 11266 I jxcore-log: 
,03-29 13:31:17.342 11202 11266 I jxcore-log: # setup
03-29 13:31:17.342 11202 11266 I jxcore-log: 
,03-29 13:31:17.617  3481  6205 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-29 13:31:18.242 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-29 13:31:18.242 11202 11266 I jxcore-log: 
,03-29 13:31:18.247 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-29 13:31:18.247 11202 11266 I jxcore-log: 
,03-29 13:31:18.257 11202 11266 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-29 13:31:18.257 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-29 13:31:18.257 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-29 13:31:18.257 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-29 13:31:18.257 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-29 13:31:18.257 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-29 13:31:18.257 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-29 13:31:18.257 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-29 13:31:18.262 11202 11266 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-29 13:31:18.262 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-29 13:31:18.262 11202 11266 I jxcore-log: 
,03-29 13:31:18.267 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-29 13:31:18.267 11202 11266 I jxcore-log: 
,03-29 13:31:18.272 11202 11266 I jxcore-log: # 43. #startUpdateAdvertisingAndListening should fail if start not called
03-29 13:31:18.272 11202 11266 I jxcore-log: 
,03-29 13:31:18.272 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-29 13:31:18.272 11202 11266 I jxcore-log: 
,03-29 13:31:18.512 11202 11266 I jxcore-log: ok 181 specific error should be returned
03-29 13:31:18.512 11202 11266 I jxcore-log: 
,03-29 13:31:18.517 11202 11266 I jxcore-log: # teardown
03-29 13:31:18.517 11202 11266 I jxcore-log: 
,03-29 13:31:20.597 11202 11266 I jxcore-log: ok 182 must be stopped
03-29 13:31:20.597 11202 11266 I jxcore-log: 
,03-29 13:31:20.602 11202 11266 I jxcore-log: # setup
03-29 13:31:20.602 11202 11266 I jxcore-log: 
,03-29 13:31:20.682  5947  6139 E bt-btm  : Reset sec_bd_name and name flag. (BR/EDR link)
03-29 13:31:20.682  5947  6139 E bt-btm  : btm_sec_disconnected - Clearing Pending flag
03-29 13:31:20.682  5947  6139 W bt-btif : bta_dm_acl_change(), event : 1
03-29 13:31:20.682  5947  6139 W bt-btif : bta_dm_acl_change(), event : 2
03-29 13:31:20.682  5947  6057 E BluetoothRemoteDevices: aclStateChangeCallback: State:DisConnected to Device:F8:95:C7:87:3C:XX
,03-29 13:31:20.687  3726  3726 D KeyguardViewMediator: Received android.bluetooth.device.action.ACL_DISCONNECTED
03-29 13:31:20.687  5947  6057 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,03-29 13:31:20.702  3481  3481 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
03-29 13:31:20.702  3481  3481 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.device.action.ACL_DISCONNECTED
03-29 13:31:20.702  3481  3481 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_ACL_DISCONNECTED
,03-29 13:31:20.712  3481  3575 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f0e3420 u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{175ebf7c 5947:com.android.bluetooth/1002}
,03-29 13:31:20.712  3481  3511 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
,03-29 13:31:20.717  3726  3726 D KeyguardViewMediator: isGear1: device is not B1!
,03-29 13:31:20.722  5947  5947 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d3d4163
03-29 13:31:20.722  5947  5947 D BtConfig.SecureMode: isSecureModeOn:false
03-29 13:31:20.727 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-29 13:31:20.727 11202 11266 I jxcore-log: 
03-29 13:31:20.727  3481  4438 D SecContentProvider: query(), uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,03-29 13:31:20.727 10367 12079 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.ACL_DISCONNECTED State = -2147483648 Previous = -2147483648
,03-29 13:31:20.727 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-29 13:31:20.727 11202 11266 I jxcore-log: 
,03-29 13:31:20.732 10367 10367 D [CarModeFW]: ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED
03-29 13:31:20.732 10367 10367 D [CarModeFW]: ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED onNotifyBluetoothDeviceDisconnected
,03-29 13:31:20.737  3481  3985 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,03-29 13:31:20.737 10367 10367 D [CarModeFW]: ConnectivityManager-Paired Devices list is empty
03-29 13:31:20.737  5947  5947 I BluetoothPbapService: action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
03-29 13:31:20.737 11202 11266 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-29 13:31:20.737 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-29 13:31:20.737 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-29 13:31:20.737 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-29 13:31:20.737 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-29 13:31:20.737 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-29 13:31:20.737 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-29 13:31:20.737 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-29 13:31:20.737 10367 10367 E [CarMode]: [BluetoothConnectivityListener]-onNotifyBluetoothProfileDisconnected: Unexpected error: Invalid device
,03-29 13:31:20.742 11202 11266 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-29 13:31:20.742 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-29 13:31:20.742 11202 11266 I jxcore-log: 
,03-29 13:31:20.742  3481  3982 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f0e3420 u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{141c12a2 11989:com.sec.android.app.shealth/u0a36}
,03-29 13:31:20.742 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-29 13:31:20.742 11202 11266 I jxcore-log: 
,03-29 13:31:20.747 11202 11266 I jxcore-log: # 44. should be able to call #stopListeningForAdvertisements many times
03-29 13:31:20.747 11202 11266 I jxcore-log: 
,03-29 13:31:20.752 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-29 13:31:20.752 11202 11266 I jxcore-log: 
,03-29 13:31:20.757  3481  3982 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f0e3420 u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{141c12a2 11989:com.sec.android.app.shealth/u0a36}
,03-29 13:31:20.762  3481  3512 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f0e3420 u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{141c12a2 11989:com.sec.android.app.shealth/u0a36}
,03-29 13:31:20.772  3481  4438 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f0e3420 u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{338c15d0 4130:com.google.android.googlequicksearchbox:search/u0a64}
,03-29 13:31:20.782  4130  4130 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,03-29 13:31:20.782  4130  4130 I BluetoothClassifier: Bluetooth Device Name: G4-1
,03-29 13:31:20.957 11202 11266 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 13:31:20.957 11202 11266 I jxcore-log: 
,03-29 13:31:20.962 11202 11266 I jxcore-log: DEBUG createNativeListener: listening 48963
03-29 13:31:20.962 11202 11266 I jxcore-log: 
,03-29 13:31:20.962 11202 11266 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-29 13:31:20.962 11202 11266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-29 13:31:20.962 11202 11266 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 13:31:20.972 11202 11266 I jxcore-log: ok 183 no errors
03-29 13:31:20.972 11202 11266 I jxcore-log: 
,03-29 13:31:20.972 11202 11266 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-29 13:31:20.972 11202 11266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-29 13:31:20.972 11202 11266 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 13:31:20.977 11202 11266 I jxcore-log: ok 184 still no errors
03-29 13:31:20.977 11202 11266 I jxcore-log: 
,03-29 13:31:20.987 11202 11266 I jxcore-log: # teardown
03-29 13:31:20.987 11202 11266 I jxcore-log: 
,03-29 13:31:21.122 11202 11266 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-29 13:31:21.122 11202 11266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-29 13:31:21.122 11202 11266 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 13:31:21.127 11202 11266 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-29 13:31:21.127 11202 11266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-29 13:31:21.132 11202 11266 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 13:31:21.137 11202 11266 I jxcore-log: ok 185 must be stopped
03-29 13:31:21.137 11202 11266 I jxcore-log: 
,03-29 13:31:21.147 11202 11266 I jxcore-log: # setup
03-29 13:31:21.147 11202 11266 I jxcore-log: 
,03-29 13:31:21.292 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-29 13:31:21.292 11202 11266 I jxcore-log: 
,03-29 13:31:21.297 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-29 13:31:21.297 11202 11266 I jxcore-log: 
,03-29 13:31:21.302 11202 11266 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-29 13:31:21.302 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-29 13:31:21.302 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-29 13:31:21.302 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-29 13:31:21.302 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-29 13:31:21.302 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-29 13:31:21.302 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-29 13:31:21.302 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-29 13:31:21.307 11202 11266 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-29 13:31:21.312 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-29 13:31:21.312 11202 11266 I jxcore-log: 
,03-29 13:31:21.317 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-29 13:31:21.317 11202 11266 I jxcore-log: 
,03-29 13:31:21.317 11202 11266 I jxcore-log: # 45. should be able to call #startListeningForAdvertisements many times
03-29 13:31:21.317 11202 11266 I jxcore-log: 
,03-29 13:31:21.322 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-29 13:31:21.322 11202 11266 I jxcore-log: 
,03-29 13:31:21.507 11202 11266 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 13:31:21.507 11202 11266 I jxcore-log: 
,03-29 13:31:21.512 11202 11266 I jxcore-log: DEBUG createNativeListener: listening 34201
03-29 13:31:21.512 11202 11266 I jxcore-log: 
,03-29 13:31:21.517 11202 11266 I io.jxcore.node.ConnectionHelper: start: Port number: 35027, start advertisements: false
,03-29 13:31:21.517 11202 11266 I io.jxcore.node.ConnectionHelper: restoreDefaultBleDiscoverySettings: Powering the BLE discovery back up
03-29 13:31:21.517 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 0 -> 2
,03-29 13:31:21.522 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-29 13:31:21.522 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-29 13:31:21.522 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-29 13:31:21.522 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-29 13:31:21.522 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-29 13:31:21.522 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-29 13:31:21.527 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 1, timeout: 0, is connectable: false
,03-29 13:31:21.527 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
,03-29 13:31:21.527 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 1 -> 3
03-29 13:31:21.527 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-29 13:31:21.527 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-29 13:31:21.527 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-29 13:31:21.527 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-29 13:31:21.527 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-29 13:31:21.527 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-29 13:31:21.532 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-29 13:31:21.532 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-29 13:31:21.532 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 0 -> 2
,03-29 13:31:21.532 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-29 13:31:21.532 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-29 13:31:21.532 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-29 13:31:21.532 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-29 13:31:21.532 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-29 13:31:21.532 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-29 13:31:21.532 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-29 13:31:21.532 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-29 13:31:21.537 11202 11266 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-29 13:31:21.537 11202 11266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-29 13:31:21.537 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-29 13:31:21.542 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-29 13:31:21.542 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-29 13:31:21.542 11202 11266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-29 13:31:21.547  5947  5958 D BtGatt.GattService: registerClient() - UUID=dc78e5bf-e422-4b3d-ba99-24a263fdf82b
,03-29 13:31:21.592  5947  6057 D BtGatt.GattService: onClientRegistered() - UUID=dc78e5bf-e422-4b3d-ba99-24a263fdf82b, clientIf=6
,03-29 13:31:21.592 11202 11212 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-29 13:31:21.592  5947 11847 D BtGatt.GattService: start scan with filters
,03-29 13:31:21.607  5947 11847 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 64
,03-29 13:31:21.607 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-29 13:31:21.607 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-29 13:31:21.607  5947  6061 D BtGatt.ScanManager: handling starting scan
03-29 13:31:21.607 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-29 13:31:21.607  5947  6061 D BtGatt.ScanManager: isFilteringSupported
03-29 13:31:21.607  5947  6061 D BluetoothAdapter: setting StandAloneBleMode
03-29 13:31:21.607 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-29 13:31:21.607 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 13:31:21.607 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-29 13:31:21.607 11202 11202 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-29 13:31:21.612 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-29 13:31:21.612 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-29 13:31:21.612 11202 11266 I io.jxcore.node.ConnectionHelper: start: OK
03-29 13:31:21.612 11202 11202 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-29 13:31:21.612 11202 11202 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 13:31:21.612 11202 11202 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-29 13:31:21.612  5947  6057 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-29 13:31:21.612  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 13:31:21.612  5947  6061 D BtGatt.ScanManager: allow scan with filters
03-29 13:31:21.612  5947  6061 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-29 13:31:21.612  5947  6061 D BtGatt.ScanManager: set filter index= 6 for clientIf= 6
03-29 13:31:21.612 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 13:31:21.612 11202 11266 I jxcore-log: 
03-29 13:31:21.612  5947  6057 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-29 13:31:21.612  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:31:21.612  5947  6061 D BtGatt.ScanManager: Starting BLE batch scan
03-29 13:31:21.612  5947  6061 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-29 13:31:21.612 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 13:31:21.612 11202 11266 I jxcore-log: 
,03-29 13:31:21.617  5947  6057 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-29 13:31:21.617  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:31:21.617 11202 11266 I jxcore-log: ok 186 no errors
03-29 13:31:21.617 11202 11266 I jxcore-log: 
,03-29 13:31:21.617  5947  6057 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-29 13:31:21.617  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 13:31:21.617 11202 11266 I io.jxcore.node.ConnectionHelper: start: Port number: 35027, start advertisements: false,
03-29 13:31:21.617 11202 11266 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-29 13:31:21.617 11202 11266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-29 13:31:21.622 11202 11266 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-29 13:31:21.622 11202 11266 I io.jxcore.node.ConnectionHelper: start: OK
,03-29 13:31:21.622 11202 11266 I jxcore-log: ok 187 still no errors
03-29 13:31:21.622 11202 11266 I jxcore-log: 
,03-29 13:31:21.627 11202 11266 I jxcore-log: # teardown
03-29 13:31:21.627 11202 11266 I jxcore-log: 
,03-29 13:31:21.807 11202 11266 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-29 13:31:21.812 11202 11266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,03-29 13:31:21.812 11202 11266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-29 13:31:21.812 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-29 13:31:21.812 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-29 13:31:21.812 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-29 13:31:21.812 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-29 13:31:21.812 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-29 13:31:21.812 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-29 13:31:21.817  5947  5956 D BtGatt.GattService: stopScan() - queue size =1
,03-29 13:31:21.822  5947  6061 D BtGatt.ScanManager: filter size is 1
,03-29 13:31:21.822  5947  6061 D BtGatt.ScanManager: delete FilterIndex - 6
03-29 13:31:21.822  5947 11846 D BtGatt.GattService: unregisterClient() - clientIf=6
03-29 13:31:21.827  5947  6057 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16,
03-29 13:31:21.827  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:31:21.827  5947  6061 D BtGatt.ScanManager: stopping BLe Batch,
03-29 13:31:21.827 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-29 13:31:21.827 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-29 13:31:21.827 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-29 13:31:21.827 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-29 13:31:21.827 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,03-29 13:31:21.827 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-29 13:31:21.837 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-29 13:31:21.837 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped,
,03-29 13:31:21.837  5947  6057 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-29 13:31:21.837  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:31:21.837 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-29 13:31:21.837  5947  6061 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-29 13:31:21.837 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-29 13:31:21.837 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-29 13:31:21.837  5947  6057 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0,
03-29 13:31:21.837 11202 11202 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-29 13:31:21.837  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:31:21.837 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-29 13:31:21.837 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-29 13:31:21.852 11202 11202 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-29 13:31:21.862 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-29 13:31:21.867 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-29 13:31:21.867 11202 11202 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-29 13:31:21.872 11202 11202 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-29 13:31:21.872 11202 11202 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 13:31:21.872 11202 11202 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-29 13:31:21.877 11202 11266 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-29 13:31:21.877 11202 11266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-29 13:31:21.877 11202 11266 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 13:31:21.882 11202 11202 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-29 13:31:21.882 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 13:31:21.882 11202 11266 I jxcore-log: 
,03-29 13:31:21.887 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 13:31:21.887 11202 11266 I jxcore-log: 
,03-29 13:31:21.897 11202 11266 I jxcore-log: ok 188 must be stopped
03-29 13:31:21.897 11202 11266 I jxcore-log: 
,03-29 13:31:21.902 11202 11266 I jxcore-log: # setup
03-29 13:31:21.902 11202 11266 I jxcore-log: 
,03-29 13:31:22.077 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-29 13:31:22.077 11202 11266 I jxcore-log: 
,03-29 13:31:22.077 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-29 13:31:22.077 11202 11266 I jxcore-log: 
,03-29 13:31:22.082 11202 11266 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-29 13:31:22.082 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-29 13:31:22.082 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-29 13:31:22.082 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-29 13:31:22.082 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-29 13:31:22.082 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-29 13:31:22.082 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-29 13:31:22.082 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-29 13:31:22.087 11202 11266 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-29 13:31:22.087 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-29 13:31:22.087 11202 11266 I jxcore-log: 
,03-29 13:31:22.087 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-29 13:31:22.087 11202 11266 I jxcore-log: 
,03-29 13:31:22.092 11202 11266 I jxcore-log: # 46. should be able to call #startUpdateAdvertisingAndListening many times
03-29 13:31:22.092 11202 11266 I jxcore-log: 
,03-29 13:31:22.092 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-29 13:31:22.092 11202 11266 I jxcore-log: 
,03-29 13:31:22.217 11202 11266 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 13:31:22.217 11202 11266 I jxcore-log: 
,03-29 13:31:22.222 11202 11266 I jxcore-log: DEBUG createNativeListener: listening 46509
03-29 13:31:22.222 11202 11266 I jxcore-log: 
,03-29 13:31:22.227 11202 11266 I io.jxcore.node.ConnectionHelper: start: Port number: 46509, start advertisements: true
,03-29 13:31:22.227 11202 11266 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-29 13:31:22.227 11202 11266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,03-29 13:31:22.232 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-29 13:31:22.232 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-29 13:31:22.232 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-29 13:31:22.232 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-29 13:31:22.237 11202 11266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-29 13:31:22.242  5947 11847 D BtGatt.GattService: registerClient() - UUID=59b51058-4947-4cf0-978b-6beeb1f4fb91
,03-29 13:31:22.282  5947  6057 D BtGatt.GattService: onClientRegistered() - UUID=59b51058-4947-4cf0-978b-6beeb1f4fb91, clientIf=6
03-29 13:31:22.282 11202 11212 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-29 13:31:22.292  5947  5956 D BtGatt.GattService: start scan with filters
,03-29 13:31:22.312  5947  5956 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 65
,03-29 13:31:22.312 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-29 13:31:22.312 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-29 13:31:22.312  5947  6061 D BtGatt.ScanManager: handling starting scan
03-29 13:31:22.312 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-29 13:31:22.312  5947  6061 D BtGatt.ScanManager: isFilteringSupported
03-29 13:31:22.312 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-29 13:31:22.312  5947  6061 D BluetoothAdapter: setting StandAloneBleMode
03-29 13:31:22.312 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 13:31:22.312 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-29 13:31:22.312 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-29 13:31:22.312 11202 11266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-29 13:31:22.312 11202 11266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 13:31:22.312 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 13:31:22.312 11202 11266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-29 13:31:22.312 11202 11202 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-29 13:31:22.317  5947  6057 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1,
03-29 13:31:22.317  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:31:22.317  5947  6061 D BtGatt.ScanManager: allow scan with filters
03-29 13:31:22.317  5947  6061 D BtGatt.ScanManager: client filter size is = 1available filters are = 13,
03-29 13:31:22.317  5947  6061 D BtGatt.ScanManager: set filter index= 7 for clientIf= 6
03-29 13:31:22.317  5947  6057 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-29 13:31:22.317  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:31:22.317  5947  6061 D BtGatt.ScanManager: Starting BLE batch scan
03-29 13:31:22.317  5947  6061 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-29 13:31:22.317  5947 11847 D BtGatt.GattService: registerClient() - UUID=c7012beb-8511-449d-a770-b99a12131d37
,03-29 13:31:22.322  5947  6057 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-29 13:31:22.322  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 13:31:22.322  5947  6057 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-29 13:31:22.322  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 13:31:22.362  5947  6057 D BtGatt.GattService: onClientRegistered() - UUID=c7012beb-8511-449d-a770-b99a12131d37, clientIf=7
,03-29 13:31:22.362 11202 11214 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-29 13:31:22.377  5947  5956 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 53,
03-29 13:31:22.377  5947  6060 D BtGatt.AdvertiseManager: message : 0
,03-29 13:31:22.377  5947  6060 D BtGatt.AdvertiseManager: number of adv instance running0
03-29 13:31:22.377  5947  6060 D BtGatt.AdvertiseManager: size of list is =0
,03-29 13:31:22.377  5947  6060 D BtGatt.AdvertiseManager: starting advertising
,03-29 13:31:22.377  5947  6060 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-29 13:31:22.382  5947  6057 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-29 13:31:22.382  5947  6060 D BtGatt.AdvertiseManager: starting multi advertising
,03-29 13:31:22.387  5947  6057 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
03-29 13:31:22.387  5947  6060 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-29 13:31:22.387  5947  6060 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,03-29 13:31:22.387 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-29 13:31:22.387 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-29 13:31:22.392 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-29 13:31:22.392 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-29 13:31:22.392 11202 11266 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-29 13:31:22.392 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-29 13:31:22.392 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-29 13:31:22.392 11202 11266 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-29 13:31:22.392 11202 11266 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-29 13:31:22.392 11202 11266 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-29 13:31:22.392 11202 11266 I io.jxcore.node.ConnectionHelper: start: OK
,03-29 13:31:22.392 11202 11202 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-29 13:31:22.397 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-29 13:31:22.397 11202 11202 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-29 13:31:22.397 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-29 13:31:22.397 11202 11202 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-29 13:31:22.397 11202 11202 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
,03-29 13:31:22.397 11202 11202 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-29 13:31:22.397 11202 11202 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-29 13:31:22.397 11202 11202 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-29 13:31:22.397 11202 11202 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 13:31:22.397 11202 11202 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-29 13:31:22.397 11202 11202 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-29 13:31:22.397 11202 12113 D BluetoothSocket: bindListen(): myUserId = 0
03-29 13:31:22.397 11202 12113 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-29 13:31:22.397 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 13:31:22.397 11202 11266 I jxcore-log: 
03-29 13:31:22.402 11202 12113 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[112]}
03-29 13:31:22.402 11202 12113 D BluetoothSocket: bindListen(), new LocalSocket 
03-29 13:31:22.402 11202 12113 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,03-29 13:31:22.402 11202 12113 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@25455ddb
03-29 13:31:22.402 11202 12113 D BluetoothSocket: channel: 6
03-29 13:31:22.402 11202 12113 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-29 13:31:22.402 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 13:31:22.402 11202 11266 I jxcore-log: 
,03-29 13:31:22.402 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-29 13:31:22.402 11202 11266 I jxcore-log: 
,03-29 13:31:22.407 11202 11266 I jxcore-log: ok 189 no errors
03-29 13:31:22.407 11202 11266 I jxcore-log: 
,03-29 13:31:22.412 11202 11266 I io.jxcore.node.ConnectionHelper: start: Port number: 46509, start advertisements: true,
,03-29 13:31:22.412 11202 11266 V io.jxcore.node.ConnectivityMonitor: start: Already started,
03-29 13:31:22.412 11202 11266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything,
03-29 13:31:22.412 11202 11266 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
03-29 13:31:22.412 11202 11266 I io.jxcore.node.ConnectionHelper: start: OK,
,03-29 13:31:22.422 11202 11266 I jxcore-log: ok 190 still no errors
03-29 13:31:22.422 11202 11266 I jxcore-log: 
,03-29 13:31:22.432 11202 11266 I jxcore-log: # teardown
03-29 13:31:22.432 11202 11266 I jxcore-log: 
,03-29 13:31:22.852 11202 11266 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-29 13:31:22.852 11202 11266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
,03-29 13:31:22.852 11202 11266 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,03-29 13:31:22.857 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-29 13:31:22.857 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,03-29 13:31:22.857 11202 11266 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3383e078, channel: 6, state: LISTENING
,03-29 13:31:22.857 11202 11266 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3383e078, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@25455ddb, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@325b5351mSocket: android.net.LocalSocket@5eb57b6 impl:android.net.LocalSocketImpl@6b1fcb7 fd:FileDescriptor[112],
03-29 13:31:22.857 11202 11266 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@5eb57b6 impl:android.net.LocalSocketImpl@6b1fcb7 fd:FileDescriptor[112]
,03-29 13:31:22.862 11202 11266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-29 13:31:22.862 11202 12113 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close,
03-29 13:31:22.862 11202 12113 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,03-29 13:31:22.862 11202 12113 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-29 13:31:22.862 11202 11202 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-29 13:31:22.862 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-29 13:31:22.867 11202 11202 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED,
03-29 13:31:22.867 11202 11202 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-29 13:31:22.867 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-29 13:31:22.867 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-29 13:31:22.867 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-29 13:31:22.867 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser,
,03-29 13:31:22.867 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...,
,03-29 13:31:22.872  5947 11847 D BtGatt.GattService: stopScan() - queue size =1,
03-29 13:31:22.872  5947  6061 D BtGatt.ScanManager: filter size is 1,
,03-29 13:31:22.872  5947  6061 D BtGatt.ScanManager: delete FilterIndex - 7,
03-29 13:31:22.877  5947  6057 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-29 13:31:22.877  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
03-29 13:31:22.877  5947  6061 D BtGatt.ScanManager: stopping BLe Batch,
,03-29 13:31:22.882  5947  6057 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-29 13:31:22.882  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,03-29 13:31:22.882  5947  5956 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-29 13:31:22.882  5947  6061 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-29 13:31:22.887 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
,03-29 13:31:22.887 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-29 13:31:22.887 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false,
,03-29 13:31:22.887 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-29 13:31:22.887 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-29 13:31:22.887 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-29 13:31:22.887 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-29 13:31:22.887  5947  6057 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
03-29 13:31:22.887  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:31:22.887  5947  6057 D BtGatt.GattService: current time is 295872741867
03-29 13:31:22.887  5947  6057 D BtGatt.GattService: Batch record : [125, 100, -126, 50, -12, 89, 1, -128, -75, 6, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -12, 51, 3, 110, 9, 74, 1, -128, -60, 6, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0]
03-29 13:31:22.887  5947  6057 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-29 13:31:22.887  5947  6057 D ScanRecord: parseFromBytes
03-29 13:31:22.887  5947  6057 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-29 13:31:22.887  5947  6057 D ScanRecord: parseFromBytes
03-29 13:31:22.892  5947  6060 D BtGatt.AdvertiseManager: message : 1
03-29 13:31:22.892  5947  6060 D BtGatt.AdvertiseManager: stop advertise for client 7,
03-29 13:31:22.892  5947  6060 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-29 13:31:22.897  5947  6060 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-29 13:31:22.897  5947  6057 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-29 13:31:22.897  5947  6057 D BtGatt.GattService: Client app is not null!
03-29 13:31:22.897  5947  5958 D BtGatt.GattService: unregisterClient() - clientIf=7
03-29 13:31:22.902 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-29 13:31:22.902 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,03-29 13:31:22.902 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-29 13:31:22.902 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-29 13:31:22.902 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-29 13:31:22.902 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-29 13:31:22.902 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-29 13:31:22.902 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-29 13:31:22.902 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-29 13:31:22.902 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-29 13:31:22.907 11202 11202 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 13:31:22.907 11202 11202 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 13:31:22.907 11202 11202 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-29 13:31:22.907 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-29 13:31:22.907 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-29 13:31:22.912 11202 11202 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
03-29 13:31:22.917 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-29 13:31:22.917 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-29 13:31:22.917 11202 11202 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-29 13:31:22.922 11202 11202 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-29 13:31:22.922 11202 11202 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-29 13:31:22.922 11202 11202 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-29 13:31:22.927 11202 11266 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-29 13:31:22.927 11202 11266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-29 13:31:22.927 11202 11266 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 13:31:22.927 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-29 13:31:22.927 11202 11266 I jxcore-log: 
,03-29 13:31:22.927 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 13:31:22.927 11202 11266 I jxcore-log: 
,03-29 13:31:22.932 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 13:31:22.932 11202 11266 I jxcore-log: 
,03-29 13:31:22.937 11202 11266 I jxcore-log: ok 191 must be stopped
03-29 13:31:22.937 11202 11266 I jxcore-log: 
,03-29 13:31:22.942 11202 11266 I jxcore-log: # setup
03-29 13:31:22.942 11202 11266 I jxcore-log: 
,03-29 13:31:23.087 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-29 13:31:23.087 11202 11266 I jxcore-log: 
,03-29 13:31:23.092 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-29 13:31:23.092 11202 11266 I jxcore-log: 
,03-29 13:31:23.102 11202 11266 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-29 13:31:23.102 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-29 13:31:23.102 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-29 13:31:23.102 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-29 13:31:23.102 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-29 13:31:23.102 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-29 13:31:23.102 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-29 13:31:23.102 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-29 13:31:23.107 11202 11266 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-29 13:31:23.107 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-29 13:31:23.107 11202 11266 I jxcore-log: 
,03-29 13:31:23.112 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-29 13:31:23.112 11202 11266 I jxcore-log: 
,03-29 13:31:23.117 11202 11266 I jxcore-log: # 47. should be able to call #stopAdvertisingAndListening many times
03-29 13:31:23.117 11202 11266 I jxcore-log: 
,03-29 13:31:23.122 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-29 13:31:23.122 11202 11266 I jxcore-log: 
,03-29 13:31:23.412 11202 11266 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 13:31:23.412 11202 11266 I jxcore-log: 
,03-29 13:31:23.417 11202 11266 I jxcore-log: DEBUG createNativeListener: listening 60871
03-29 13:31:23.417 11202 11266 I jxcore-log: 
,03-29 13:31:23.422 11202 11266 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-29 13:31:23.422 11202 11266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 13:31:23.422 11202 11266 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 13:31:23.427 11202 11266 I jxcore-log: ok 192 no errors
03-29 13:31:23.427 11202 11266 I jxcore-log: 
,03-29 13:31:23.432 11202 11266 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-29 13:31:23.432 11202 11266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-29 13:31:23.432 11202 11266 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 13:31:23.437 11202 11266 I jxcore-log: ok 193 still no errors
03-29 13:31:23.437 11202 11266 I jxcore-log: 
,03-29 13:31:23.442 11202 11266 I jxcore-log: # teardown
03-29 13:31:23.442 11202 11266 I jxcore-log: 
,03-29 13:31:23.547 11202 11266 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-29 13:31:23.547 11202 11266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 13:31:23.547 11202 11266 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 13:31:23.547 11202 11266 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-29 13:31:23.547 11202 11266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-29 13:31:23.547 11202 11266 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 13:31:23.552 11202 11266 I jxcore-log: ok 194 must be stopped
03-29 13:31:23.552 11202 11266 I jxcore-log: 
,03-29 13:31:23.562 11202 11266 I jxcore-log: # setup
03-29 13:31:23.562 11202 11266 I jxcore-log: 
,03-29 13:31:23.617  3481  3985 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-29 13:31:23.617  3481  3985 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-29 13:31:23.617  3481  3985 D BatteryService: online:4, current avg:32, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
03-29 13:31:23.617  3481  3985 D BatteryService: stay LED for fully charged
03-29 13:31:23.617  3481  3481 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-29 13:31:23.622  3481  3481 I MotionRecognitionService: Plugged
,03-29 13:31:23.622  3481  3481 D MotionRecognitionService:   cableConnection= 1
03-29 13:31:23.622  3481  3481 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-29 13:31:23.622  3481  3481 D MotionRecognitionService: skip setTransmitPower. 
,03-29 13:31:23.627  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-29 13:31:23.627  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-29 13:31:23.627  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-29 13:31:23.632  5947  5947 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-29 13:31:23.632  5947  6065 D HeadsetStateMachine: Disconnected process message: 10
,03-29 13:31:23.647  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-29 13:31:23.647  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-29 13:31:23.647  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-29 13:31:23.647  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-29 13:31:23.707 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-29 13:31:23.707 11202 11266 I jxcore-log: 
,03-29 13:31:23.717 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-29 13:31:23.717 11202 11266 I jxcore-log: 
,03-29 13:31:23.722 11202 11266 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-29 13:31:23.722 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-29 13:31:23.722 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-29 13:31:23.722 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-29 13:31:23.722 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-29 13:31:23.722 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-29 13:31:23.722 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-29 13:31:23.722 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-29 13:31:23.727 11202 11266 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-29 13:31:23.732 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-29 13:31:23.732 11202 11266 I jxcore-log: 
,03-29 13:31:23.737 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-29 13:31:23.737 11202 11266 I jxcore-log: 
,03-29 13:31:23.737 11202 11266 I jxcore-log: # 48. can get the network status before starting
03-29 13:31:23.737 11202 11266 I jxcore-log: 
,03-29 13:31:23.742 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-29 13:31:23.742 11202 11266 I jxcore-log: 
,03-29 13:31:23.982 11202 11266 I jxcore-log: ok 195 network status should have certain non-empty properties
03-29 13:31:23.982 11202 11266 I jxcore-log: 
,03-29 13:31:23.987 11202 11266 I jxcore-log: # teardown
03-29 13:31:23.987 11202 11266 I jxcore-log: 
,03-29 13:31:24.142 11202 11266 I jxcore-log: ok 196 must be stopped
03-29 13:31:24.142 11202 11266 I jxcore-log: 
,03-29 13:31:24.147 11202 11266 I jxcore-log: # setup
03-29 13:31:24.147 11202 11266 I jxcore-log: 
,03-29 13:31:24.262 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-29 13:31:24.262 11202 11266 I jxcore-log: 
,03-29 13:31:24.267 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-29 13:31:24.267 11202 11266 I jxcore-log: 
,03-29 13:31:24.277 11202 11266 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-29 13:31:24.277 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-29 13:31:24.277 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-29 13:31:24.277 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-29 13:31:24.277 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-29 13:31:24.277 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-29 13:31:24.277 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-29 13:31:24.277 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-29 13:31:24.282 11202 11266 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-29 13:31:24.282 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-29 13:31:24.282 11202 11266 I jxcore-log: 
,03-29 13:31:24.287 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-29 13:31:24.287 11202 11266 I jxcore-log: 
,03-29 13:31:24.292 11202 11266 I jxcore-log: # 49. error returned with bad router
03-29 13:31:24.292 11202 11266 I jxcore-log: 
,03-29 13:31:24.292 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-29 13:31:24.292 11202 11266 I jxcore-log: 
,03-29 13:31:24.352  3481  6174 D SSRM:n  : SIOP:: AP = 270, PST = 279 (W:18), CUR = 32, LCD = 0
,03-29 13:31:24.487 11202 11266 I jxcore-log: ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
03-29 13:31:24.487 11202 11266 I jxcore-log: 
,03-29 13:31:24.492 11202 11266 I jxcore-log: ok 197 specific error expected
03-29 13:31:24.492 11202 11266 I jxcore-log: 
,03-29 13:31:24.497 11202 11266 I jxcore-log: # teardown
03-29 13:31:24.497 11202 11266 I jxcore-log: 
,03-29 13:31:24.617 11202 11266 I jxcore-log: ok 198 must be stopped
03-29 13:31:24.617 11202 11266 I jxcore-log: 
,03-29 13:31:24.622 11202 11266 I jxcore-log: # setup
03-29 13:31:24.622 11202 11266 I jxcore-log: 
,03-29 13:31:24.737 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-29 13:31:24.737 11202 11266 I jxcore-log: 
,03-29 13:31:24.747 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-29 13:31:24.747 11202 11266 I jxcore-log: 
,03-29 13:31:24.757 11202 11266 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-29 13:31:24.757 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-29 13:31:24.757 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-29 13:31:24.757 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-29 13:31:24.757 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-29 13:31:24.757 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-29 13:31:24.757 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-29 13:31:24.757 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-29 13:31:24.762 11202 11266 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-29 13:31:24.762 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-29 13:31:24.762 11202 11266 I jxcore-log: 
,03-29 13:31:24.767 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-29 13:31:24.767 11202 11266 I jxcore-log: 
,03-29 13:31:24.772 11202 11266 I jxcore-log: # 50. all services are stopped when we call stop
03-29 13:31:24.772 11202 11266 I jxcore-log: 
,03-29 13:31:24.782 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-29 13:31:24.782 11202 11266 I jxcore-log: 
,03-29 13:31:25.417 11202 11266 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 13:31:25.417 11202 11266 I jxcore-log: 
,03-29 13:31:25.422 11202 11266 I jxcore-log: DEBUG createNativeListener: listening 40417
03-29 13:31:25.422 11202 11266 I jxcore-log: 
,03-29 13:31:25.427 11202 11266 I io.jxcore.node.ConnectionHelper: start: Port number: 46509, start advertisements: false
,03-29 13:31:25.427 11202 11266 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-29 13:31:25.427 11202 11266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,03-29 13:31:25.427 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-29 13:31:25.432 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-29 13:31:25.432 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-29 13:31:25.432 11202 11266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-29 13:31:25.437  5947  6068 D BtGatt.GattService: registerClient() - UUID=e0a0261a-3d3c-40e2-b643-4488a2ef4ef5
,03-29 13:31:25.482  5947  6057 D BtGatt.GattService: onClientRegistered() - UUID=e0a0261a-3d3c-40e2-b643-4488a2ef4ef5, clientIf=6
03-29 13:31:25.482 11202 11214 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-29 13:31:25.482  5947 11846 D BtGatt.GattService: start scan with filters
,03-29 13:31:25.522  5947 11846 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 66
,03-29 13:31:25.527 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-29 13:31:25.527 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-29 13:31:25.527 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-29 13:31:25.527 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-29 13:31:25.527 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 13:31:25.527 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-29 13:31:25.527 11202 11202 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-29 13:31:25.527  5947  6061 D BtGatt.ScanManager: handling starting scan
03-29 13:31:25.527  5947  6061 D BtGatt.ScanManager: isFilteringSupported
03-29 13:31:25.527  5947  6061 D BluetoothAdapter: setting StandAloneBleMode
03-29 13:31:25.542 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-29 13:31:25.542 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-29 13:31:25.542 11202 11202 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-29 13:31:25.542 11202 11202 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 13:31:25.542 11202 11202 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-29 13:31:25.542 11202 11266 I io.jxcore.node.ConnectionHelper: start: OK
,03-29 13:31:25.547  5947  6057 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-29 13:31:25.547  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:31:25.547  5947  6061 D BtGatt.ScanManager: allow scan with filters,
03-29 13:31:25.547  5947  6061 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-29 13:31:25.547  5947  6061 D BtGatt.ScanManager: set filter index= 8 for clientIf= 6
,03-29 13:31:25.547  5947  6057 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-29 13:31:25.552  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:31:25.552  5947  6061 D BtGatt.ScanManager: Starting BLE batch scan
03-29 13:31:25.552  5947  6061 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-29 13:31:25.552 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
,03-29 13:31:25.552 11202 11266 I jxcore-log: 
03-29 13:31:25.552  5947  6057 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0,
03-29 13:31:25.552  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:31:25.552  5947  6057 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-29 13:31:25.552  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:31:25.557 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 13:31:25.557 11202 11266 I jxcore-log: 
,03-29 13:31:25.562 11202 11266 I io.jxcore.node.ConnectionHelper: start: Port number: 40417, start advertisements: true
,03-29 13:31:25.562 11202 11266 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-29 13:31:25.562 11202 11266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-29 13:31:25.562 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-29 13:31:25.567 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-29 13:31:25.567 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
03-29 13:31:25.567 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-29 13:31:25.567 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-29 13:31:25.567 11202 11266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-29 13:31:25.567 11202 11266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-29 13:31:25.567 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 13:31:25.567 11202 11266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-29 13:31:25.572  5947 11847 D BtGatt.GattService: registerClient() - UUID=9569957a-c004-4d39-bef6-e09135c7b2e3
,03-29 13:31:25.612  5947  6057 D BtGatt.GattService: onClientRegistered() - UUID=9569957a-c004-4d39-bef6-e09135c7b2e3, clientIf=7
03-29 13:31:25.612 11202 11212 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-29 13:31:25.627  5947  5956 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 54
,03-29 13:31:25.627  5947  6060 D BtGatt.AdvertiseManager: message : 0
03-29 13:31:25.627  5947  6060 D BtGatt.AdvertiseManager: number of adv instance running0
,03-29 13:31:25.627  5947  6060 D BtGatt.AdvertiseManager: size of list is =0
,03-29 13:31:25.627  5947  6060 D BtGatt.AdvertiseManager: starting advertising
,03-29 13:31:25.627  5947  6060 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-29 13:31:25.632  5947  6057 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-29 13:31:25.632  5947  6060 D BtGatt.AdvertiseManager: starting multi advertising
,03-29 13:31:25.632  5947  6057 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-29 13:31:25.632  5947  6060 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-29 13:31:25.632  5947  6060 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,03-29 13:31:25.637 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-29 13:31:25.637 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-29 13:31:25.637 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-29 13:31:25.637 11202 11202 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-29 13:31:25.637 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-29 13:31:25.637 11202 11202 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-29 13:31:25.637 11202 11202 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
,03-29 13:31:25.637 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-29 13:31:25.637 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-29 13:31:25.637 11202 11266 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,03-29 13:31:25.637 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-29 13:31:25.637 11202 11202 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-29 13:31:25.642 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-29 13:31:25.642 11202 11266 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-29 13:31:25.642 11202 11266 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-29 13:31:25.642 11202 11266 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-29 13:31:25.642 11202 11266 I io.jxcore.node.ConnectionHelper: start: OK
03-29 13:31:25.642 11202 11202 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,03-29 13:31:25.642 11202 11202 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 13:31:25.642 11202 11202 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,03-29 13:31:25.642 11202 12162 D BluetoothSocket: bindListen(): myUserId = 0
,03-29 13:31:25.642 11202 12162 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-29 13:31:25.642 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-29 13:31:25.642 11202 11266 I jxcore-log: 
,03-29 13:31:25.647 11202 12162 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[112]}
,03-29 13:31:25.647 11202 12162 D BluetoothSocket: bindListen(), new LocalSocket 
03-29 13:31:25.647 11202 12162 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-29 13:31:25.647 11202 12162 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@22dfad53
03-29 13:31:25.647 11202 12162 D BluetoothSocket: channel: 6
03-29 13:31:25.647 11202 12162 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-29 13:31:25.652 11202 11266 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 13:31:25.652 11202 11266 I jxcore-log: 
,03-29 13:31:25.652 11202 11266 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 13:31:25.652 11202 11266 I jxcore-log: 
,03-29 13:31:25.657 11202 11266 I jxcore-log: DEBUG createNativeListener: new mux
03-29 13:31:25.657 11202 11266 I jxcore-log: 
,03-29 13:31:25.662 11202 11266 I jxcore-log: ok 199 connection to servers manager should succeed after starting
03-29 13:31:25.662 11202 11266 I jxcore-log: 
,03-29 13:31:25.687 11202 11266 I jxcore-log: ok 200 connection to router server should succeed after starting
03-29 13:31:25.687 11202 11266 I jxcore-log: 
,03-29 13:31:25.687 11202 11266 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-29 13:31:25.687 11202 11266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-29 13:31:25.687 11202 11266 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-29 13:31:25.687 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-29 13:31:25.687 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-29 13:31:25.687 11202 11266 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@213e4690, channel: 6, state: LISTENING
03-29 13:31:25.687 11202 11266 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@213e4690, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@22dfad53, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@4641b89mSocket: android.net.LocalSocket@33f9a78e impl:android.net.LocalSocketImpl@182dcbaf fd:FileDescriptor[112]
03-29 13:31:25.687 11202 11266 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@33f9a78e impl:android.net.LocalSocketImpl@182dcbaf fd:FileDescriptor[112]
03-29 13:31:25.687 11202 11266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-29 13:31:25.687 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-29 13:31:25.687 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-29 13:31:25.687 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-29 13:31:25.687 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-29 13:31:25.687 11202 12162 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-29 13:31:25.687 11202 12162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-29 13:31:25.687 11202 12162 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,03-29 13:31:25.687 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-29 13:31:25.687 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-29 13:31:25.692  5947  6068 D BtGatt.GattService: stopScan() - queue size =1
03-29 13:31:25.692  5947  6061 D BtGatt.ScanManager: filter size is 1
,03-29 13:31:25.692  5947  6061 D BtGatt.ScanManager: delete FilterIndex - 8
03-29 13:31:25.692  5947 11846 D BtGatt.GattService: unregisterClient() - clientIf=6
03-29 13:31:25.692  5947  6057 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,03-29 13:31:25.692  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:31:25.692 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-29 13:31:25.692 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-29 13:31:25.692 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-29 13:31:25.692  5947  6061 D BtGatt.ScanManager: stopping BLe Batch
03-29 13:31:25.692 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-29 13:31:25.692 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-29 13:31:25.692 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-29 13:31:25.692 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-29 13:31:25.697  5947  6060 D BtGatt.AdvertiseManager: message : 1
,03-29 13:31:25.697  5947  6060 D BtGatt.AdvertiseManager: stop advertise for client 7
03-29 13:31:25.697  5947  6060 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
,03-29 13:31:25.697  5947  6057 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-29 13:31:25.697  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:31:25.697  5947  6061 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-29 13:31:25.697  5947  6060 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,03-29 13:31:25.697  5947  6057 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0,
03-29 13:31:25.697  5947  6057 D BtGatt.GattService: Client app is not null!
,03-29 13:31:25.702  5947  5956 D BtGatt.GattService: unregisterClient() - clientIf=7
03-29 13:31:25.702 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-29 13:31:25.702 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-29 13:31:25.702 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-29 13:31:25.702 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-29 13:31:25.702 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-29 13:31:25.702 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false,
,03-29 13:31:25.702 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-29 13:31:25.702  5947  6057 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
03-29 13:31:25.702 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-29 13:31:25.702  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:31:25.702  5947  6057 D BtGatt.GattService: current time is 298687139659
03-29 13:31:25.702  5947  6057 D BtGatt.GattService: Batch record : [39, 105, 46, -107, 43, 127, 1, -128, -76, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-29 13:31:25.702  5947  6057 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-29 13:31:25.702  5947  6057 D ScanRecord: parseFromBytes
03-29 13:31:25.702 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-29 13:31:25.702 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-29 13:31:25.702 11202 11202 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-29 13:31:25.702 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-29 13:31:25.702 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-29 13:31:25.707 11202 11266 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 13:31:25.707 11202 11266 I jxcore-log: 
03-29 13:31:25.707 11202 11202 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-29 13:31:25.712 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-29 13:31:25.712 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-29 13:31:25.712 11202 11202 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-29 13:31:25.712 11202 11202 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-29 13:31:25.712 11202 11202 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-29 13:31:25.717 11202 11202 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true,
03-29 13:31:25.717 11202 11202 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 13:31:25.717 11202 11202 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 13:31:25.717 11202 11202 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-29 13:31:25.717 11202 11202 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-29 13:31:25.717 11202 11202 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-29 13:31:25.727 11202 11266 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements,
03-29 13:31:25.727 11202 11266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-29 13:31:25.727 11202 11266 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 13:31:25.727 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-29 13:31:25.727 11202 11266 I jxcore-log: 
,03-29 13:31:25.732 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 13:31:25.732 11202 11266 I jxcore-log: 
,03-29 13:31:25.732 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 13:31:25.732 11202 11266 I jxcore-log: 
,03-29 13:31:25.737 11202 11266 I jxcore-log: ok 201 is stopped after calling stop
03-29 13:31:25.737 11202 11266 I jxcore-log: 
,03-29 13:31:25.747 11202 11266 I jxcore-log: ok 202 connection to servers manager should fail after stopping
03-29 13:31:25.747 11202 11266 I jxcore-log: 
,03-29 13:31:25.752 11202 11266 I jxcore-log: ok 203 connection to router server should fail after stopping
03-29 13:31:25.752 11202 11266 I jxcore-log: 
,03-29 13:31:25.762 11202 11266 I jxcore-log: # teardown
03-29 13:31:25.762 11202 11266 I jxcore-log: 
,03-29 13:31:25.857 11202 11266 I jxcore-log: ok 204 must be stopped
03-29 13:31:25.857 11202 11266 I jxcore-log: 
,03-29 13:31:25.882 11202 11266 I jxcore-log: # setup,
03-29 13:31:25.882 11202 11266 I jxcore-log: 
,03-29 13:31:26.082 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-29 13:31:26.082 11202 11266 I jxcore-log: 
,03-29 13:31:26.087 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-29 13:31:26.087 11202 11266 I jxcore-log: 
,03-29 13:31:26.097 11202 11266 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-29 13:31:26.097 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-29 13:31:26.097 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-29 13:31:26.097 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-29 13:31:26.097 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-29 13:31:26.097 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-29 13:31:26.097 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-29 13:31:26.097 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-29 13:31:26.097 11202 11266 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-29 13:31:26.102 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-29 13:31:26.102 11202 11266 I jxcore-log: 
,03-29 13:31:26.107 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-29 13:31:26.107 11202 11266 I jxcore-log: 
,03-29 13:31:26.112 11202 11266 I jxcore-log: # 51. make sure terminateConnection is properly hooked up
03-29 13:31:26.112 11202 11266 I jxcore-log: 
,03-29 13:31:26.117 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-29 13:31:26.117 11202 11266 I jxcore-log: 
,03-29 13:31:26.282 11202 11266 I jxcore-log: ok 205 called with right arguments
03-29 13:31:26.282 11202 11266 I jxcore-log: 
,03-29 13:31:26.287 11202 11266 I jxcore-log: # teardown
03-29 13:31:26.287 11202 11266 I jxcore-log: 
,03-29 13:31:26.367 11202 11266 I jxcore-log: ok 206 must be stopped
03-29 13:31:26.367 11202 11266 I jxcore-log: 
,03-29 13:31:26.372 11202 11266 I jxcore-log: # setup
03-29 13:31:26.372 11202 11266 I jxcore-log: 
,03-29 13:31:26.557 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-29 13:31:26.557 11202 11266 I jxcore-log: 
,03-29 13:31:26.562 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-29 13:31:26.562 11202 11266 I jxcore-log: 
,03-29 13:31:26.572 11202 11266 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-29 13:31:26.572 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-29 13:31:26.572 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-29 13:31:26.572 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-29 13:31:26.572 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-29 13:31:26.572 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-29 13:31:26.572 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-29 13:31:26.572 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-29 13:31:26.577 11202 11266 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-29 13:31:26.577 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-29 13:31:26.577 11202 11266 I jxcore-log: 
,03-29 13:31:26.582 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-29 13:31:26.582 11202 11266 I jxcore-log: 
,03-29 13:31:26.587 11202 11266 I jxcore-log: # 52. make sure terminateListener is properly hooked up
03-29 13:31:26.587 11202 11266 I jxcore-log: 
,03-29 13:31:26.587 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-29 13:31:26.587 11202 11266 I jxcore-log: 
,03-29 13:31:26.687 11202 11266 I jxcore-log: ok 207 called with right arguments
03-29 13:31:26.687 11202 11266 I jxcore-log: 
,03-29 13:31:26.692 11202 11266 I jxcore-log: # teardown
03-29 13:31:26.692 11202 11266 I jxcore-log: 
,03-29 13:31:26.912 11202 11266 I jxcore-log: ok 208 must be stopped
03-29 13:31:26.912 11202 11266 I jxcore-log: 
,03-29 13:31:26.917 11202 11266 I jxcore-log: # setup
03-29 13:31:26.917 11202 11266 I jxcore-log: 
,03-29 13:31:27.072 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-29 13:31:27.072 11202 11266 I jxcore-log: 
,03-29 13:31:27.077 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-29 13:31:27.077 11202 11266 I jxcore-log: 
,03-29 13:31:27.087 11202 11266 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-29 13:31:27.087 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-29 13:31:27.087 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-29 13:31:27.087 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-29 13:31:27.087 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-29 13:31:27.087 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-29 13:31:27.087 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-29 13:31:27.087 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-29 13:31:27.092 11202 11266 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-29 13:31:27.092 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-29 13:31:27.092 11202 11266 I jxcore-log: 
,03-29 13:31:27.097 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-29 13:31:27.097 11202 11266 I jxcore-log: 
,03-29 13:31:27.102 11202 11266 I jxcore-log: # 53. make sure we actually call kill connections properly
03-29 13:31:27.102 11202 11266 I jxcore-log: 
,03-29 13:31:27.107 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-29 13:31:27.107 11202 11266 I jxcore-log: 
,03-29 13:31:27.217 11202 11266 I jxcore-log: ok 209 specific error expected
03-29 13:31:27.217 11202 11266 I jxcore-log: 
,03-29 13:31:27.227 11202 11266 I jxcore-log: # teardown
03-29 13:31:27.227 11202 11266 I jxcore-log: 
,03-29 13:31:27.362 11202 11266 I jxcore-log: ok 210 must be stopped
03-29 13:31:27.362 11202 11266 I jxcore-log: 
,03-29 13:31:27.377 11202 11266 I jxcore-log: # setup
03-29 13:31:27.377 11202 11266 I jxcore-log: 
,03-29 13:31:27.487 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-29 13:31:27.487 11202 11266 I jxcore-log: 
,03-29 13:31:27.492 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-29 13:31:27.492 11202 11266 I jxcore-log: 
,03-29 13:31:27.502 11202 11266 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-29 13:31:27.502 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-29 13:31:27.502 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-29 13:31:27.502 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-29 13:31:27.502 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-29 13:31:27.502 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-29 13:31:27.502 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-29 13:31:27.502 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-29 13:31:27.502 11202 11266 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-29 13:31:27.507 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-29 13:31:27.507 11202 11266 I jxcore-log: 
,03-29 13:31:27.512 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-29 13:31:27.512 11202 11266 I jxcore-log: 
,03-29 13:31:27.517 11202 11266 I jxcore-log: # 54. thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
03-29 13:31:27.517 11202 11266 I jxcore-log: 
,03-29 13:31:27.522 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-29 13:31:27.522 11202 11266 I jxcore-log: 
,03-29 13:31:27.692 11202 11266 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 13:31:27.692 11202 11266 I jxcore-log: 
,03-29 13:31:27.697 11202 11266 I jxcore-log: DEBUG createNativeListener: listening 46175
03-29 13:31:27.697 11202 11266 I jxcore-log: 
,03-29 13:31:27.702 11202 11266 I jxcore-log: INFO thaliMobileNativeWrapper: routerPortConnectionFailed - {"routerPort":41337,"error":{}}
03-29 13:31:27.702 11202 11266 I jxcore-log: 
,03-29 13:31:27.707 11202 11266 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-29 13:31:27.707 11202 11266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-29 13:31:27.707 11202 11266 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 13:31:27.712 11202 11266 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-29 13:31:27.712 11202 11266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-29 13:31:27.712 11202 11266 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 13:31:27.727 11202 11266 I jxcore-log: ok 211 failure reason is as expected
03-29 13:31:27.727 11202 11266 I jxcore-log: 
,03-29 13:31:27.727 11202 11266 I jxcore-log: ok 212 error description is as expected
03-29 13:31:27.727 11202 11266 I jxcore-log: 
,03-29 13:31:27.732 11202 11266 I jxcore-log: ok 213 must be stopped
03-29 13:31:27.732 11202 11266 I jxcore-log: 
,03-29 13:31:27.737 11202 11266 I jxcore-log: # teardown
03-29 13:31:27.737 11202 11266 I jxcore-log: 
,03-29 13:31:27.857 11202 11266 I jxcore-log: ok 214 must be stopped
03-29 13:31:27.857 11202 11266 I jxcore-log: 
,03-29 13:31:27.862 11202 11266 I jxcore-log: # setup
03-29 13:31:27.862 11202 11266 I jxcore-log: 
,03-29 13:31:28.022 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-29 13:31:28.022 11202 11266 I jxcore-log: 
,03-29 13:31:28.032 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-29 13:31:28.032 11202 11266 I jxcore-log: 
,03-29 13:31:28.037 11202 11266 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-29 13:31:28.037 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-29 13:31:28.037 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-29 13:31:28.037 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-29 13:31:28.037 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-29 13:31:28.037 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-29 13:31:28.037 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-29 13:31:28.037 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-29 13:31:28.042 11202 11266 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-29 13:31:28.047 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-29 13:31:28.047 11202 11266 I jxcore-log: 
,03-29 13:31:28.052 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-29 13:31:28.052 11202 11266 I jxcore-log: 
,03-29 13:31:28.057 11202 11266 I jxcore-log: # 55. We repeat failedConnection event when we get it from thaliTcpServersManager
03-29 13:31:28.057 11202 11266 I jxcore-log: 
,03-29 13:31:28.057 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-29 13:31:28.057 11202 11266 I jxcore-log: 
,03-29 13:31:28.237 11202 11266 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 13:31:28.237 11202 11266 I jxcore-log: 
,03-29 13:31:28.242 11202 11266 I jxcore-log: DEBUG createNativeListener: listening 37802
03-29 13:31:28.242 11202 11266 I jxcore-log: 
,03-29 13:31:28.252 11202 11266 I jxcore-log: ok 215 peerIdentifier matches
03-29 13:31:28.252 11202 11266 I jxcore-log: 
,03-29 13:31:28.252 11202 11266 I jxcore-log: ok 216 error description matches
03-29 13:31:28.252 11202 11266 I jxcore-log: 
,03-29 13:31:28.257 11202 11266 I jxcore-log: # teardown
03-29 13:31:28.257 11202 11266 I jxcore-log: 
,03-29 13:31:28.367 11202 11266 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-29 13:31:28.367 11202 11266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 13:31:28.367 11202 11266 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 13:31:28.372 11202 11266 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-29 13:31:28.372 11202 11266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-29 13:31:28.372 11202 11266 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 13:31:28.377 11202 11266 I jxcore-log: ok 217 must be stopped
03-29 13:31:28.377 11202 11266 I jxcore-log: 
,03-29 13:31:28.382 11202 11266 I jxcore-log: # setup
03-29 13:31:28.382 11202 11266 I jxcore-log: 
,03-29 13:31:28.537 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-29 13:31:28.537 11202 11266 I jxcore-log: 
,03-29 13:31:28.547 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-29 13:31:28.547 11202 11266 I jxcore-log: 
,03-29 13:31:28.567 11202 11266 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-29 13:31:28.567 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-29 13:31:28.567 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-29 13:31:28.567 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-29 13:31:28.567 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-29 13:31:28.567 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-29 13:31:28.567 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-29 13:31:28.567 11202 11266 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-29 13:31:28.572 11202 11266 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-29 13:31:28.577 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-29 13:31:28.577 11202 11266 I jxcore-log: 
,03-29 13:31:28.582 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-29 13:31:28.582 11202 11266 I jxcore-log: 
,03-29 13:31:28.587 11202 11213 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@213e4690, channel: 6, state: CLOSED
,03-29 13:31:28.592 11202 11213 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3383e078, channel: 6, state: CLOSED
,03-29 13:31:28.602 11202 11266 I jxcore-log: # 56. we successfully receive and replay discoveryAdvertisingStateUpdate
03-29 13:31:28.602 11202 11266 I jxcore-log: 
,03-29 13:31:28.607 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-29 13:31:28.607 11202 11266 I jxcore-log: 
,03-29 13:31:28.792 11202 11266 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 13:31:28.792 11202 11266 I jxcore-log: 
,03-29 13:31:28.797 11202 11266 I jxcore-log: DEBUG createNativeListener: listening 44538
03-29 13:31:28.797 11202 11266 I jxcore-log: 
,03-29 13:31:28.802 11202 11266 I io.jxcore.node.ConnectionHelper: start: Port number: 40417, start advertisements: false
,03-29 13:31:28.802 11202 11266 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-29 13:31:28.802 11202 11266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-29 13:31:28.802 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-29 13:31:28.807 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-29 13:31:28.807 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-29 13:31:28.807 11202 11266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-29 13:31:28.812  5947  6068 D BtGatt.GattService: registerClient() - UUID=1bc3b852-f8d1-4336-9ed3-837fc63127a1
,03-29 13:31:28.857  5947  6057 D BtGatt.GattService: onClientRegistered() - UUID=1bc3b852-f8d1-4336-9ed3-837fc63127a1, clientIf=6
03-29 13:31:28.857 11202 11212 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-29 13:31:28.857  5947 11846 D BtGatt.GattService: start scan with filters
,03-29 13:31:28.872  5947 11846 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 67
,03-29 13:31:28.872 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-29 13:31:28.872 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-29 13:31:28.872 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-29 13:31:28.872 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-29 13:31:28.872  5947  6061 D BtGatt.ScanManager: handling starting scan
03-29 13:31:28.872 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 13:31:28.872  5947  6061 D BtGatt.ScanManager: isFilteringSupported
03-29 13:31:28.872  5947  6061 D BluetoothAdapter: setting StandAloneBleMode
03-29 13:31:28.872 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-29 13:31:28.877 11202 11202 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-29 13:31:28.882 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
03-29 13:31:28.882 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-29 13:31:28.882 11202 11266 I io.jxcore.node.ConnectionHelper: start: OK
,03-29 13:31:28.882 11202 11202 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-29 13:31:28.882 11202 11202 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 13:31:28.882 11202 11202 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-29 13:31:28.882  5947  6057 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-29 13:31:28.882  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:31:28.882  5947  6061 D BtGatt.ScanManager: allow scan with filters
03-29 13:31:28.882  5947  6061 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-29 13:31:28.882  5947  6061 D BtGatt.ScanManager: set filter index= 9 for clientIf= 6
,03-29 13:31:28.887 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 13:31:28.887 11202 11266 I jxcore-log: 
,03-29 13:31:28.887  5947  6057 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-29 13:31:28.887  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:31:28.887  5947  6061 D BtGatt.ScanManager: Starting BLE batch scan
03-29 13:31:28.887  5947  6061 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-29 13:31:28.887 11202 11266 I jxcore-log: ok 218 discoveryActive matches
03-29 13:31:28.887 11202 11266 I jxcore-log: 
,03-29 13:31:28.887 11202 11266 I jxcore-log: ok 219 advertisingActive matches
03-29 13:31:28.887 11202 11266 I jxcore-log: 
,03-29 13:31:28.887  5947  6057 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-29 13:31:28.887  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:31:28.892  5947  6057 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-29 13:31:28.892  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 13:31:28.892 11202 11266 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-29 13:31:28.892 11202 11266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,03-29 13:31:28.892 11202 11266 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,03-29 13:31:28.892 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-29 13:31:28.892 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-29 13:31:28.892 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-29 13:31:28.892 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-29 13:31:28.892 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-29 13:31:28.892 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-29 13:31:28.892  5947  6068 D BtGatt.GattService: stopScan() - queue size =1
03-29 13:31:28.897  5947 11846 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-29 13:31:28.897 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-29 13:31:28.897 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-29 13:31:28.897 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-29 13:31:28.897 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,03-29 13:31:28.897 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-29 13:31:28.897 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-29 13:31:28.902 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-29 13:31:28.902 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-29 13:31:28.902 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-29 13:31:28.902 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-29 13:31:28.902 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-29 13:31:28.902 11202 11202 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-29 13:31:28.902 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-29 13:31:28.902 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-29 13:31:28.902  5947  6061 D BtGatt.ScanManager: filter size is 1
03-29 13:31:28.902  5947  6061 D BtGatt.ScanManager: delete FilterIndex - 9
,03-29 13:31:28.907  5947  6057 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,03-29 13:31:28.907  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:31:28.907 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 13:31:28.907 11202 11266 I jxcore-log: 
03-29 13:31:28.907  5947  6061 D BtGatt.ScanManager: stopping BLe Batch
,03-29 13:31:28.907  5947  6057 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,03-29 13:31:28.907  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:31:28.907  5947  6061 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-29 13:31:28.912 11202 11202 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-29 13:31:28.912  5947  6057 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-29 13:31:28.912  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 13:31:28.917 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-29 13:31:28.917 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-29 13:31:28.917 11202 11202 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-29 13:31:28.922 11202 11202 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-29 13:31:28.922 11202 11202 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 13:31:28.922 11202 11202 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 13:31:28.922 11202 11202 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-29 13:31:28.922 11202 11266 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-29 13:31:28.922 11202 11266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-29 13:31:28.922 11202 11266 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 13:31:28.927 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 13:31:28.927 11202 11266 I jxcore-log: 
,03-29 13:31:28.927 11202 11266 I jxcore-log: ok 220 discoveryActive matches
03-29 13:31:28.927 11202 11266 I jxcore-log: 
,03-29 13:31:28.927 11202 11266 I jxcore-log: ok 221 advertisingActive matches
03-29 13:31:28.927 11202 11266 I jxcore-log: 
,03-29 13:31:28.932 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 13:31:28.932 11202 11266 I jxcore-log: 
,03-29 13:31:28.952 11202 11266 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 13:31:28.952 11202 11266 I jxcore-log: 
,03-29 13:31:28.957 11202 11266 I jxcore-log: DEBUG createNativeListener: listening 35749
03-29 13:31:28.957 11202 11266 I jxcore-log: 
,03-29 13:31:28.962 11202 11266 I io.jxcore.node.ConnectionHelper: start: Port number: 35749, start advertisements: true
,03-29 13:31:28.962 11202 11266 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-29 13:31:28.962 11202 11266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-29 13:31:28.962 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-29 13:31:28.962 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-29 13:31:28.962 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-29 13:31:28.962 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-29 13:31:28.962 11202 11266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-29 13:31:28.967  5947 11846 D BtGatt.GattService: registerClient() - UUID=abc4e89f-e917-4730-bf48-846b1c32daed
,03-29 13:31:29.007  5947  6057 D BtGatt.GattService: onClientRegistered() - UUID=abc4e89f-e917-4730-bf48-846b1c32daed, clientIf=6
,03-29 13:31:29.007 11202 11212 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-29 13:31:29.007  5947  5958 D BtGatt.GattService: start scan with filters
,03-29 13:31:29.017  5947  5958 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 68
,03-29 13:31:29.022 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-29 13:31:29.022 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-29 13:31:29.022 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,03-29 13:31:29.022  5947  6061 D BtGatt.ScanManager: handling starting scan
03-29 13:31:29.022 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,03-29 13:31:29.022  5947  6061 D BtGatt.ScanManager: isFilteringSupported
03-29 13:31:29.022 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 13:31:29.022  5947  6061 D BluetoothAdapter: setting StandAloneBleMode
03-29 13:31:29.022 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-29 13:31:29.022 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-29 13:31:29.022 11202 11202 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 13:31:29.022 11202 11266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
,03-29 13:31:29.022 11202 11266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 13:31:29.022 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 13:31:29.022 11202 11266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-29 13:31:29.022  5947  6057 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-29 13:31:29.022  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 13:31:29.022  5947  6061 D BtGatt.ScanManager: allow scan with filters
03-29 13:31:29.022  5947  6061 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-29 13:31:29.022  5947  6061 D BtGatt.ScanManager: set filter index= 10 for clientIf= 6
03-29 13:31:29.027  5947  6057 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-29 13:31:29.027  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:31:29.027  5947  6061 D BtGatt.ScanManager: Starting BLE batch scan
03-29 13:31:29.027  5947  6061 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-29 13:31:29.027  5947 11846 D BtGatt.GattService: registerClient() - UUID=cc96fc85-d14f-45af-8bc1-4a6d39b638a3
,03-29 13:31:29.027  5947  6057 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-29 13:31:29.027  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 13:31:29.032  5947  6057 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-29 13:31:29.032  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-29 13:31:29.072  5947  6057 D BtGatt.GattService: onClientRegistered() - UUID=cc96fc85-d14f-45af-8bc1-4a6d39b638a3, clientIf=7
,03-29 13:31:29.072 11202 11214 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-29 13:31:29.092  5947  5958 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 55
,03-29 13:31:29.092  5947  6060 D BtGatt.AdvertiseManager: message : 0
03-29 13:31:29.092  5947  6060 D BtGatt.AdvertiseManager: number of adv instance running0
03-29 13:31:29.092  5947  6060 D BtGatt.AdvertiseManager: size of list is =0
,03-29 13:31:29.097  5947  6060 D BtGatt.AdvertiseManager: starting advertising
03-29 13:31:29.097  5947  6060 D BtGatt.AdvertiseManager: isStandardAdvfalse
03-29 13:31:29.102  5947  6057 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
03-29 13:31:29.107  5947  6060 D BtGatt.AdvertiseManager: starting multi advertising
03-29 13:31:29.107  5947  6057 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
03-29 13:31:29.107  5947  6060 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-29 13:31:29.107  5947  6060 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
03-29 13:31:29.107 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-29 13:31:29.112 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-29 13:31:29.112 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-29 13:31:29.112 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-29 13:31:29.112 11202 11266 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-29 13:31:29.112 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-29 13:31:29.112 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-29 13:31:29.117 11202 11266 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true,
03-29 13:31:29.117 11202 11266 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-29 13:31:29.117 11202 11266 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-29 13:31:29.117 11202 11202 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-29 13:31:29.117 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-29 13:31:29.117 11202 11202 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-29 13:31:29.117 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true,
03-29 13:31:29.117 11202 11202 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-29 13:31:29.117 11202 11202 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-29 13:31:29.117 11202 11202 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-29 13:31:29.117 11202 11202 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-29 13:31:29.117 11202 11202 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-29 13:31:29.117 11202 11202 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-29 13:31:29.117 11202 11202 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-29 13:31:29.117 11202 11202 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-29 13:31:29.117 11202 11266 I io.jxcore.node.ConnectionHelper: start: OK
,03-29 13:31:29.122 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false},
03-29 13:31:29.122 11202 11266 I jxcore-log: 
,03-29 13:31:29.127 11202 12224 D BluetoothSocket: bindListen(): myUserId = 0
,03-29 13:31:29.127 11202 12224 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-29 13:31:29.137 11202 12224 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[112]}
,03-29 13:31:29.137 11202 12224 D BluetoothSocket: bindListen(), new LocalSocket 
03-29 13:31:29.137 11202 12224 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,03-29 13:31:29.137 11202 12224 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@30d71a66
03-29 13:31:29.137 11202 12224 D BluetoothSocket: channel: 6
03-29 13:31:29.137 11202 12224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-29 13:31:29.142 11202 11266 I jxcore-log: not ok 222 discoveryActive matches
03-29 13:31:29.142 11202 11266 I jxcore-log: 
,03-29 13:31:29.142 11202 11266 I jxcore-log:   ---
03-29 13:31:29.142 11202 11266 I jxcore-log: 
,03-29 13:31:29.142 11202 11266 I jxcore-log:     operator: equal
03-29 13:31:29.142 11202 11266 I jxcore-log: 
,03-29 13:31:29.147 11202 11266 I jxcore-log:     expected: false
03-29 13:31:29.147 11202 11266 I jxcore-log: 
,03-29 13:31:29.147 11202 11266 I jxcore-log:     actual:   true
03-29 13:31:29.147 11202 11266 I jxcore-log: 
,03-29 13:31:29.147 11202 11266 I jxcore-log:   ...
03-29 13:31:29.147 11202 11266 I jxcore-log: 
,03-29 13:31:29.152 11202 11266 I jxcore-log: not ok 223 advertisingActive matches
03-29 13:31:29.152 11202 11266 I jxcore-log: 
,03-29 13:31:29.152 11202 11266 I jxcore-log:   ---
03-29 13:31:29.152 11202 11266 I jxcore-log: 
,03-29 13:31:29.152 11202 11266 I jxcore-log:     operator: equal
03-29 13:31:29.152 11202 11266 I jxcore-log: 
,03-29 13:31:29.152 11202 11266 I jxcore-log:     expected: true
03-29 13:31:29.152 11202 11266 I jxcore-log: 
,03-29 13:31:29.152 11202 11266 I jxcore-log:     actual:   false
03-29 13:31:29.152 11202 11266 I jxcore-log: 
,03-29 13:31:29.157 11202 11266 I jxcore-log:   ...
03-29 13:31:29.157 11202 11266 I jxcore-log: 
,03-29 13:31:29.157 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 13:31:29.157 11202 11266 I jxcore-log: 
,03-29 13:31:29.162 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-29 13:31:29.162 11202 11266 I jxcore-log: 
,03-29 13:31:29.162 11202 11266 I jxcore-log: not ok 224 discoveryActive matches
03-29 13:31:29.162 11202 11266 I jxcore-log: 
,03-29 13:31:29.167 11202 11266 I jxcore-log:   ---
03-29 13:31:29.167 11202 11266 I jxcore-log: 
,03-29 13:31:29.167 11202 11266 I jxcore-log:     operator: equal
03-29 13:31:29.167 11202 11266 I jxcore-log: 
,03-29 13:31:29.167 11202 11266 I jxcore-log:     expected: false
03-29 13:31:29.167 11202 11266 I jxcore-log: 
,03-29 13:31:29.167 11202 11266 I jxcore-log:     actual:   true
03-29 13:31:29.167 11202 11266 I jxcore-log: 
,03-29 13:31:29.167 11202 11266 I jxcore-log:   ...
03-29 13:31:29.167 11202 11266 I jxcore-log: 
,03-29 13:31:29.172 11202 11266 I jxcore-log: not ok 225 advertisingActive matches
03-29 13:31:29.172 11202 11266 I jxcore-log: 
,03-29 13:31:29.172 11202 11266 I jxcore-log:   ---
03-29 13:31:29.172 11202 11266 I jxcore-log: 
,03-29 13:31:29.172 11202 11266 I jxcore-log:     operator: equal
03-29 13:31:29.172 11202 11266 I jxcore-log: 
,03-29 13:31:29.177 11202 11266 I jxcore-log:     expected: false
03-29 13:31:29.177 11202 11266 I jxcore-log: 
,03-29 13:31:29.177 11202 11266 I jxcore-log:     actual:   true
03-29 13:31:29.177 11202 11266 I jxcore-log: 
,03-29 13:31:29.177 11202 11266 I jxcore-log:   ...
03-29 13:31:29.177 11202 11266 I jxcore-log: 
,03-29 13:31:29.177 11202 11266 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-29 13:31:29.182 11202 11266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
,03-29 13:31:29.182 11202 11266 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-29 13:31:29.182 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,03-29 13:31:29.182 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-29 13:31:29.182 11202 11266 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@268581a7, channel: 6, state: LISTENING
,03-29 13:31:29.182 11202 11266 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@268581a7, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@30d71a66, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2834654mSocket: android.net.LocalSocket@a4ab9fd impl:android.net.LocalSocketImpl@3d2a76f2 fd:FileDescriptor[112]
,03-29 13:31:29.182 11202 11266 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@a4ab9fd impl:android.net.LocalSocketImpl@3d2a76f2 fd:FileDescriptor[112]
,03-29 13:31:29.182 11202 11266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-29 13:31:29.182 11202 12224 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-29 13:31:29.187 11202 12224 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-29 13:31:29.187 11202 12224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-29 13:31:29.187 11202 11202 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-29 13:31:29.187 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-29 13:31:29.187 11202 11202 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-29 13:31:29.187 11202 11202 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-29 13:31:29.187 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-29 13:31:29.187 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-29 13:31:29.187 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-29 13:31:29.192 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-29 13:31:29.192 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-29 13:31:29.192  5947 11847 D BtGatt.GattService: stopScan() - queue size =1,
,03-29 13:31:29.192  5947  6061 D BtGatt.ScanManager: filter size is 1
03-29 13:31:29.192  5947  6061 D BtGatt.ScanManager: delete FilterIndex - 10
03-29 13:31:29.192  5947  5956 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-29 13:31:29.192 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-29 13:31:29.192 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-29 13:31:29.192 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,03-29 13:31:29.192 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-29 13:31:29.192 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-29 13:31:29.192 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-29 13:31:29.192 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-29 13:31:29.197  5947  6057 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16,
03-29 13:31:29.197  5947  6060 D BtGatt.AdvertiseManager: message : 1
03-29 13:31:29.197  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:31:29.197  5947  6060 D BtGatt.AdvertiseManager: stop advertise for client 7
03-29 13:31:29.197  5947  6060 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
,03-29 13:31:29.197  5947  6061 D BtGatt.ScanManager: stopping BLe Batch
03-29 13:31:29.197  5947  6060 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-29 13:31:29.197  5947  6057 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,03-29 13:31:29.197  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:31:29.197  5947  6061 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-29 13:31:29.202  5947  6057 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
,03-29 13:31:29.202  5947  6057 D BtGatt.GattService: Client app is not null!
,03-29 13:31:29.202  5947  5958 D BtGatt.GattService: unregisterClient() - clientIf=7
,03-29 13:31:29.202 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-29 13:31:29.202 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-29 13:31:29.202 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-29 13:31:29.202 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-29 13:31:29.202 11202 11266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-29 13:31:29.202 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-29 13:31:29.202 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-29 13:31:29.202 11202 11266 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-29 13:31:29.202  5947  6057 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-29 13:31:29.202  5947  6057 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-29 13:31:29.202 11202 11266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-29 13:31:29.202 11202 11266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-29 13:31:29.202 11202 11202 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-29 13:31:29.202 11202 11202 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 13:31:29.207 11202 11202 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-29 13:31:29.207 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-29 13:31:29.207 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-29 13:31:29.207 11202 11266 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-29 13:31:29.207 11202 11266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-29 13:31:29.207 11202 11266 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 13:31:29.207 11202 11202 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-29 13:31:29.212 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-29 13:31:29.212 11202 11202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-29 13:31:29.217 11202 11202 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-29 13:31:29.217 11202 11202 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-29 13:31:29.217 11202 11202 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-29 13:31:29.217 11202 11202 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-29 13:31:29.217 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-29 13:31:29.217 11202 11266 I jxcore-log: 
,03-29 13:31:29.222 11202 11266 I jxcore-log: ok 226 discoveryActive matches
03-29 13:31:29.222 11202 11266 I jxcore-log: 
,03-29 13:31:29.222 11202 11266 I jxcore-log: not ok 227 advertisingActive matches
03-29 13:31:29.222 11202 11266 I jxcore-log: 
,03-29 13:31:29.222 11202 11266 I jxcore-log:   ---
03-29 13:31:29.222 11202 11266 I jxcore-log: 
03-29 13:31:29.222 11202 11266 I jxcore-log:     operator: equal
03-29 13:31:29.222 11202 11266 I jxcore-log: 
03-29 13:31:29.222 11202 11266 I jxcore-log:     expected: false
03-29 13:31:29.222 11202 11266 I jxcore-log: 
03-29 13:31:29.222 11202 11266 I jxcore-log:     actual:   true
,03-29 13:31:29.222 11202 11266 I jxcore-log: 
03-29 13:31:29.222 11202 11266 I jxcore-log:   ...
03-29 13:31:29.222 11202 11266 I jxcore-log: 
,03-29 13:31:29.227 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 13:31:29.227 11202 11266 I jxcore-log: 
,03-29 13:31:29.227 11202 11266 I jxcore-log: ok 228 discoveryActive matches
03-29 13:31:29.227 11202 11266 I jxcore-log: ,
,03-29 13:31:29.227 11202 11266 I jxcore-log: ok 229 advertisingActive matches
03-29 13:31:29.227 11202 11266 I jxcore-log: 
,03-29 13:31:29.232 11202 11266 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 13:31:29.232 11202 11266 I jxcore-log: 
,03-29 13:31:29.242 11202 11266 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 13:31:29.242 11202 11266 I jxcore-log: 
,03-29 13:31:29.247 11202 11266 I jxcore-log: DEBUG createNativeListener: listening 51061
03-29 13:31:29.247 11202 11266 I jxcore-log: 
,03-29 13:31:29.257 11202 11266 I jxcore-log: Uncaught Promise Rejection: {}
03-29 13:31:29.257 11202 11266 I jxcore-log: 
,03-29 13:31:29.262 11202 11266 E jxcore-log: Trace: [Error: Call Stop!]
03-29 13:31:29.262 11202 11266 E jxcore-log:     at $3.prototype.trace@console.js:139:8
03-29 13:31:29.262 11202 11266 E jxcore-log:     at @/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:38:3
03-29 13:31:29.262 11202 11266 E jxcore-log:     at emit@events.js:98:1
03-29 13:31:29.262 11202 11266 E jxcore-log:     at handlers.reject/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/thali/node_modules/lie/lib/index.js:128:11
03-29 13:31:29.262 11202 11266 E jxcore-log:     at nextTick@/data/data/com.test.thalitest/files/www/jxcore/node_modules/immediate/lib/index.js:61:7
03-29 13:31:29.262 11202 11266 E jxcore-log:     at $0a@node.js:917:1
03-29 13:31:29.262 11202 11266 E jxcore-log: 
,03-29 13:31:29.262 11202 11266 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
03-29 13:31:29.262 11202 11266 I jxcore-log: 
,03-29 13:31:29.267 11202 11266 I jxcore-log: # teardown
03-29 13:31:29.267 11202 11266 I jxcore-log: 
,03-29 13:31:29.612 12232 12232 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,03-29 13:31:29.617 12232 12232 D AndroidRuntime: CheckJNI is OFF
,03-29 13:31:29.617 12232 12232 D AndroidRuntime: readGMSProperty: start
03-29 13:31:29.617 12232 12232 D AndroidRuntime: readGMSProperty: already setted!!
03-29 13:31:29.617 12232 12232 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-29 13:31:29.617 12232 12232 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-29 13:31:29.617 12232 12232 D AndroidRuntime: readGMSProperty: end
03-29 13:31:29.617 12232 12232 D AndroidRuntime: addProductProperty: start
,03-29 13:31:29.702 12232 12232 E AffinityControl: AffinityControl: registerfunction enter
,03-29 13:31:29.717 12232 12232 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,03-29 13:31:29.727  3481  3651 D PackageManager: START PACKAGE DELETE: observer{147731273}
03-29 13:31:29.727  3481  3651 D PackageManager: pkg{<packageName>}
03-29 13:31:29.727  3481  3651 D PackageManager: user{0}
03-29 13:31:29.727  3481  3651 D PackageManager: caller{2000}
03-29 13:31:29.727  3481  3651 D PackageManager: flags{2}
03-29 13:31:29.727  3481  3651 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
03-29 13:31:29.727  3481  3651 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
03-29 13:31:29.727  3481  3651 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
03-29 13:31:29.727  3481  3651 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
03-29 13:31:29.727  3481  3651 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
03-29 13:31:29.727  3481  3592 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
03-29 13:31:29.727  3481  3592 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
03-29 13:31:29.727  3481  3592 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
03-29 13:31:29.727  3481  3592 D ApplicationPolicy: getApplicationUninstallationEnabled
03-29 13:31:29.727  3481  3592 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,03-29 13:31:29.732  3481  3592 D PackageManager: !@killApplicatoin: 10011, uninstall pkg
,03-29 13:31:29.737  3481  3575 I ActivityManager: Force stopping com.test.thalitest appid=10011 user=-1: uninstall pkg
,03-29 13:31:29.737  3481  3575 I ActivityManager: Killing 11202:com.test.thalitest/u0a11 (adj 0): stop com.test.thalitest cause uninstall pkg
,03-29 13:31:29.757  3481  3575 I ActivityManager:   Force finishing activity 3 ActivityRecord{1e2b8bb3 u0 com.test.thalitest/.MainActivity t42}
,03-29 13:31:29.762  3481  3575 W ActivityManager: mDVFSHelper.acquire()
,03-29 13:31:29.862  3481  3592 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
,03-29 13:31:29.867  3481  3592 W PackageSettings: Skipping PackageSetting{36ff5b78 com.example.hello/10691} due to missing metadata
,03-29 13:31:29.887  3481  3592 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,03-29 13:31:29.887  3481  3575 D PowerManagerService: setKeyboardVisibility: false
,03-29 13:31:29.892  3481  3575 I ActivityManager: Skip updateThumbnail for r=ActivityRecord{dce746a u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t40}
,03-29 13:31:29.897  3481  3512 I WindowState: WIN DEATH: Window{96c37c9 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}
,03-29 13:31:29.897  2860  3688 I SurfaceFlinger: id=15 Removed NainActivit (6/8)
,03-29 13:31:29.897  2860  3021 I SurfaceFlinger: id=15 Removed NainActivit (-2/8)
,03-29 13:31:29.897  3481  3512 D InputDispatcher: Focus left window: 11202
,03-29 13:31:29.902  3481  3512 D MultiWindowConverter: dismissGuide() : Before attaching the guide view, mForceDismissGuide : false
,03-29 13:31:29.907  3481  3592 I ActivityManager: Force stopping com.test.thalitest appid=10011 user=0: pkg removed
03-29 13:31:29.912  6713  6713 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(433/onResume)] 
,03-29 13:31:29.922  3481  3592 I ActivityManager:   Force finishing activity 3 ActivityRecord{1e2b8bb3 u0 com.test.thalitest/.MainActivity t42 f}
,03-29 13:31:29.922  3481  3592 W ActivityManager: Duplicate finish request for ActivityRecord{1e2b8bb3 u0 com.test.thalitest/.MainActivity t42 f}
,03-29 13:31:29.922  3481  3584 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3481 uid:1000
03-29 13:31:29.922  3481  3584 D PointerIcon: setMouseCustomIcon IconType is same.101
03-29 13:31:29.922  3481  3584 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3481 uid:1000
03-29 13:31:29.922  3481  3584 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,03-29 13:31:29.927  6713  6713 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5412/IlIlllIlllllIlIllllI)] Get Postpone Count : 0
,03-29 13:31:29.942  3481  3592 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-29 13:31:29.947  6713  6713 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5134/lIIIIIIIlllllllIIlll)] Get Priority : 0
,03-29 13:31:29.957  3481  3575 D InputDispatcher: Focused application released
,03-29 13:31:29.962  3481  3693 D TaskPersister: removeObsoleteFile: deleting file=42_task.xml
,03-29 13:31:29.962  3481  3693 D TaskPersister: removeObsoleteFile: deleting file=42_task_thumbnail.png
,03-29 13:31:29.967  3941  3941 I art     : Explicit concurrent mark sweep GC freed 1661(87KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 770us total 20.777ms
,03-29 13:31:29.967  9164  9164 I art     : Explicit concurrent mark sweep GC freed 21176(1187KB) AllocSpace objects, 2(32KB) LOS objects, 69% free, 1812KB/5MB, paused 441us total 23.551ms
03-29 13:31:29.967  6713  6713 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5434/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
03-29 13:31:29.967  6713  6713 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(443/onResume)] Postpone Count : 0
,03-29 13:31:29.972  6713  6713 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5475/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,03-29 13:31:29.987  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.PACKAGE_REMOVED
,03-29 13:31:29.992  4527  4527 E SamsungIME: mOCRHelper is null
,03-29 13:31:29.997  4418  4841 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,03-29 13:31:30.002  4130  4130 I art     : Explicit concurrent mark sweep GC freed 23220(1314KB) AllocSpace objects, 2(32KB) LOS objects, 24% free, 6MB/8MB, paused 977us total 50.832ms
,03-29 13:31:30.012 10682 10682 D LWLocationManager: getDeviceLocationId :  id = -100
03-29 13:31:30.012 10682 10682 D LocationWidgetApplication: getLastUiLocationId() : mLastUiLocationId = -100
,03-29 13:31:30.017  4013  4013 I art     : Explicit concurrent mark sweep GC freed 16056(921KB) AllocSpace objects, 9(1362KB) LOS objects, 12% free, 56MB/64MB, paused 557us total 50.983ms
03-29 13:31:30.017  3481  3632 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-29 13:31:30.022  3481  3653 D NtpTrustedTime: currentTimeMillis() cache hit
03-29 13:31:30.022  3481  3653 V NetworkStats: removeUidsLocked() for UIDs [10011]
03-29 13:31:30.022  3481  3653 V NetworkStats: performPollLocked(flags=0x3)
,03-29 13:31:30.022  4704  4704 I art     : Explicit concurrent mark sweep GC freed 2985(185KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 8MB/11MB, paused 1.042ms total 95.251ms
,03-29 13:31:30.032  3481  3653 D NtpTrustedTime: currentTimeMillis() cache hit
03-29 13:31:30.032  3481  3653 V NetworkStats: performPollLocked() took 10ms
03-29 13:31:30.032  3481  3575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-29 13:31:30.032  3481  3575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-29 13:31:30.032  3481  3575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-29 13:31:30.032  3481  3575 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-29 13:31:30.042  5618  5636 W ResourceType: For resource 0x7f020570, entry index(1392) is beyond type entryCount(787)
03-29 13:31:30.042  5618  5636 W ResourceType: Failure getting entry for 0x7f020570 (t=1 e=1392) (error -75)
,03-29 13:31:30.047  3481  3572 D EnterpriseDeviceManagerService: Package has changed for user 0
03-29 13:31:30.047  3481  3572 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
03-29 13:31:30.047  3481  3572 W TextServicesManagerService: no available spell checker services found
,03-29 13:31:30.047 12244 12244 E Zygote  : MountEmulatedStorage()
,03-29 13:31:30.047 12244 12244 E Zygote  : v2
03-29 13:31:30.047 12244 12244 I libpersona: KNOX_SDCARD checking this for 10063
03-29 13:31:30.047 12244 12244 I libpersona: KNOX_SDCARD not a persona
,03-29 13:31:30.047 12244 12244 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
,03-29 13:31:30.047  3481  3575 I ActivityManager: Start proc 12244:com.samsung.android.app.vrsetupwizardstub/u0a63 for broadcast-3 com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver
,03-29 13:31:30.052  6713  6713 I DBG_DM  : [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
03-29 13:31:30.052  6713  6713 I DBG_DM  : [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(327/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,03-29 13:31:30.052 12244 12244 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
,03-29 13:31:30.052 12244 12244 E Zygote  : accessInfo : 0
03-29 13:31:30.052 12244 12244 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-29 13:31:30.067  3981  3981 D RegisteredServicesCache: empty dynamic service
,03-29 13:31:30.077  3981  3981 D RegisteredComponentCache: Collect Tech packages for Knox
,03-29 13:31:30.092  6713  6713 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5134/lIIIIIIIlllllllIIlll)] Get Priority : 0
,03-29 13:31:30.097 12244 12244 D TimaKeyStoreProvider: TimaSignature is unavailable
03-29 13:31:30.102 12244 12244 D ActivityThread: Added TimaKeyStore provider
,03-29 13:31:30.112  3481  4028 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{335477b2 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{1d1b6303 12244:com.samsung.android.app.vrsetupwizardstub/u0a63}
,03-29 13:31:30.122  3481  3654 D NtpTrustedTime: currentTimeMillis() cache hit
03-29 13:31:30.122  3481  3654 D NtpTrustedTime: currentTimeMillis() cache hit
,03-29 13:31:30.127  3481  3982 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
03-29 13:31:30.127  3481  3982 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,03-29 13:31:30.132  6713  6713 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5412/IlIlllIlllllIlIllllI)] Get Postpone Count : 0
,03-29 13:31:30.132  3481  3481 I art     : Explicit concurrent mark sweep GC freed 99358(7MB) AllocSpace objects, 109(1745KB) LOS objects, 33% free, 32MB/48MB, paused 3.046ms total 185.831ms
03-29 13:31:30.132  3481  3592 I art     : WaitForGcToComplete blocked for 177.457ms for cause Explicit
,03-29 13:31:30.137  6713  6713 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5054/IIlllIlIIlIllIlllIll)] Get Force status : 0
,03-29 13:31:30.142  6713  6713 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5434/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
03-29 13:31:30.142  6713  6713 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(537/llIIIIlllllIIllIIllI)] Check Force Install : false
03-29 13:31:30.142  6713  6713 I DBG_DM  : [llIIlIIlIllIllIlllII(337/IllIlIIIIlIIlIIIllIl)] 
,03-29 13:31:30.142  6713  6713 I DBG_DM  : [llIIlIIlIllIllIlllII(343/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
03-29 13:31:30.147  3481  3835 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-29 13:31:30.147  3481  3835 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-29 13:31:30.147  3481  3835 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,03-29 13:31:30.147  6713  6713 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(425/onPause)] 
,03-29 13:31:30.152  2860  2860 I SurfaceFlinger: id=16 createSurf (1440x2560),1 flag=404, YUIInstallC
,03-29 13:31:30.152  3481  3835 D MultiWindowConverter: dismissGuide() : Before attaching the guide view, mForceDismissGuide : false
03-29 13:31:30.157  3481  3582 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{1fb2a860 u0 d0 com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}
,03-29 13:31:30.157  3481  3835 D InputDispatcher: Focus entered window: 6713
,03-29 13:31:30.157  3481  3584 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3481 uid:1000
03-29 13:31:30.157  3481  3584 D PointerIcon: setMouseCustomIcon IconType is same.101
03-29 13:31:30.157  3481  3584 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3481 uid:1000
03-29 13:31:30.157  3481  3584 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
03-29 13:31:30.157  6713  6713 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-29 13:31:30.162  6713  9332 D mali_winsys: new_window_surface returns 0x3000,  [1440x2560]-format:1
,03-29 13:31:30.162  6713  6713 V ActivityThread: updateVisibility : ActivityRecord{2b930f32 token=android.os.BinderProxy@27aad868 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,03-29 13:31:30.167  3481  3512 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-29 13:31:30.167  3481  3572 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,03-29 13:31:30.167 12244 12244 D VRSetupWizardStub/PackageIntentReceiver: onReceive()
03-29 13:31:30.167 12244 12244 D VRSetupWizardStub/PackageIntentReceiver: Action Package Remove
03-29 13:31:30.172 12244 12244 D VRSetupWizardStub/PackageIntentReceiver: packagename:com.test.thalitest
,03-29 13:31:30.172  3481  3512 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 11202 uid 10011
,03-29 13:31:30.177  3481  3651 I ActivityManager: Killing 10285:com.sec.android.app.soundalive/u0a59 (adj 15): emptyCount ##31
,03-29 13:31:30.182  3481  3651 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{335477b2 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{2fdb9a74 6099:com.samsung.klmsagent/u0a21}
,03-29 13:31:30.182  4527  4527 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,03-29 13:31:30.192  6099  6099 I KLMS-2.5.262: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Mar 29 13:31:30 GMT+02:00 2016
,03-29 13:31:30.252 10682 12250 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-29 13:31:30.267  3481  3592 I art     : Explicit concurrent mark sweep GC freed 13641(701KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 31MB/47MB, paused 1.625ms total 136.548ms
03-29 13:31:30.267  3481  4417 I art     : WaitForGcToComplete blocked for 95.602ms for cause Explicit
,03-29 13:31:30.287 10682 12250 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-29 13:31:30.287 10682 12250 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-29 13:31:30.287 10682 12250 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-29 13:31:30.287 10682 12250 W ResourcesManager: Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,03-29 13:31:30.292  3481  3572 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-29 13:31:30.292  3481  3572 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-29 13:31:30.292  3481  3572 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-29 13:31:30.292  3481  3572 W ResourcesManager: Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,03-29 13:31:30.317  3481  3592 D PackageManager: delete codoeFile: 
03-29 13:31:30.317  3481  3592 D PackageManager: Resopt: Clean up res: /data/app/com.test.thalitest-1/base.apk
03-29 13:31:30.317  3481  3592 D AASAuninstall: userId = 0, info.removedAppID = 10011, info.uid = 10011, packageName = com.test.thalitest
03-29 13:31:30.322  3481  3592 I AASA_removePackage: UID=10011 Target=com.test.thalitest
03-29 13:31:30.322  3481  3592 D PackageManager: result of delete: 1{147731273}
03-29 13:31:30.322 12232 12232 I art     : System.exit called, status: 0
03-29 13:31:30.322  3481  3592 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
03-29 13:31:30.322  3481  3592 D PackageManager: userId{-1}
03-29 13:31:30.322  3481  3592 D PackageManager: andCode{true}
03-29 13:31:30.322 12232 12232 I AndroidRuntime: VM exiting with result code 0.
,03-29 13:31:30.337  9903 12263 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.test.thalitest
03-29 13:31:30.337  9903 12263 W System.err: remove failed: EACCES (Permission denied) : /storage/extSdCard/Android/data/com.test.thalitest
03-29 13:31:30.337  9903 12263 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.test.thalitest
03-29 13:31:30.337  9903 12263 W System.err: remove failed: EACCES (Permission denied) : /storage/extSdCard/Android/media/com.test.thalitest
03-29 13:31:30.337  9903 12263 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/obb/com.test.thalitest
03-29 13:31:30.337  9903 12263 W System.err: remove failed: EACCES (Permission denied) : /storage/extSdCard/Android/obb/com.test.thalitest
03-29 13:31:30.362  3481  3572 D UsbSettingsManager: clearDefaults: com.test.thalitest
03-29 13:31:30.362  3481  3572 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
03-29 13:31:30.362  3481  3481 D RCPManagerService: PackageReceiver onReceive()
03-29 13:31:30.362  3481  3481 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
03-29 13:31:30.362  4013  4013 E Launcher.Model: onPackageRemoved :com.test.thalitest
03-29 13:31:30.362  3481  3481 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
03-29 13:31:30.362  3481  3481 I OTPFW   : PackageRemovalReceiver::onReceive Enter
03-29 13:31:30.362  3481  3481 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10011 container id = 0
,03-29 13:31:30.367  3481  3481 I OTPFW   : ProvisionData::getAllEntries Enter
03-29 13:31:30.367  3481  3481 E OTPFW   : ProvisionData::getAllEntries Table is empty
03-29 13:31:30.372  3481  3481 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
03-29 13:31:30.372  3481  3481 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
03-29 13:31:30.372  3481  3481 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
03-29 13:31:30.372  3481  3481 V EnterpriseBillingPolicy: uID is 10011
03-29 13:31:30.372  3481  3481 V EnterpriseBillingPolicy: Removed Packageuid is0
03-29 13:31:30.372  3481  3481 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
03-29 13:31:30.372  3481  3481 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
03-29 13:31:30.372  3481  3481 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
03-29 13:31:30.372  3481  3481 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
03-29 13:31:30.372  3481  3481 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
03-29 13:31:30.372  3481  3481 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
03-29 13:31:30.372  3481  3481 D SdpManagerService:  ActionReceiver::onReceive() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
03-29 13:31:30.372  3481  3481 D SdpManagerService: ACTION_PACKAGE_REMOVED Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) } DATA= package:com.test.thalitest UID 1000 userId 0
03-29 13:31:30.372  3481  3481 D SdpManagerService: ACTION_PACKAGE_REMOVED packageName:: com.test.thalitest
03-29 13:31:30.392  3481  3481 D EnterprisePartitionManager: SND -> {secure_fs remove_enc_dir}
03-29 13:31:30.392  3481  3594 D EnterprisePartitionManager: RCV <-
03-29 13:31:30.392  3481  3481 D EnterprisePartitionManager: RMV <-
03-29 13:31:30.397  3481  4417 I art     : Explicit concurrent mark sweep GC freed 8675(492KB) AllocSpace objects, 2(4MB) LOS objects, 33% free, 27MB/41MB, paused 16.139ms total 127.080ms
03-29 13:31:30.397  3481  4417 D SecContentProvider2: query(), uri = 11 selection = getMyKnoxAdmin
03-29 13:31:30.397  3481  3835 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,03-29 13:31:30.407  6099  6099 I KLMS-2.5.262: : KLMSAbstractReciever(): onReceive().END.
03-29 13:31:30.407  3481  3481 E EnterprisePartitionManager: Failed to send commandcom.sec.knox.container.util.DaemonConnector$DaemonArgumentException: command 'secure_fs' failed with '500 3 Command not recognized'
03-29 13:31:30.407  3481  3481 W System.err: java.io.FileNotFoundException: /data/system/users/sdp_engine_list.xml: open failed: ENOENT (No such file or directory)
03-29 13:31:30.407  3481  3481 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-29 13:31:30.407  3481  3481 W System.err: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
03-29 13:31:30.412  3481  6174 D SSRM:bd : MSG_TYPE_APP_REMOVED::
03-29 13:31:30.407  3481  3481 W System.err: 	at com.android.server.SdpManagerService$SdpEngineDatabase$EngineListHandler.getEngineListLocked(SdpManagerService.java:1514)
03-29 13:31:30.407  3481  3481 W System.err: 	at com.android.server.SdpManagerService$SdpEngineDatabase$EngineListHandler.access$1100(SdpManagerService.java:1434)
03-29 13:31:30.407  3481  3481 W System.err: 	at com.android.server.SdpManagerService$SdpEngineDatabase.getEngineListLocked(SdpManagerService.java:1418)
03-29 13:31:30.407  3481  3481 W System.err: 	at com.android.server.SdpManagerService$SdpEngineDatabase.access$2200(SdpManagerService.java:1393)
03-29 13:31:30.407  3481  3481 W System.err: 	at com.android.server.SdpManagerService.handlePkgRemoved(SdpManagerService.java:2647)
03-29 13:31:30.407  3481  3481 W System.err: 	at com.android.server.SdpManagerService.access$2500(SdpManagerService.java:137)
03-29 13:31:30.407  3481  3481 W System.err: 	at com.android.server.SdpManagerService$ActionReceiver.onReceive(SdpManagerService.java:2719)
03-29 13:31:30.407  3481  3481 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:972)
03-29 13:31:30.407  3481  3481 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
03-29 13:31:30.407  3481  3481 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-29 13:31:30.407  3481  3481 W System.err: 	at android.os.Looper.loop(Looper.java:145)
03-29 13:31:30.407  3481  3481 W System.err: 	at com.android.server.SystemServer.run(SystemServer.java:469)
03-29 13:31:30.407  3481  3481 W System.err: 	at com.android.server.SystemServer.main(SystemServer.java:353)
03-29 13:31:30.407  3481  3481 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
03-29 13:31:30.407  3481  3481 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-29 13:31:30.407  3481  3481 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
03-29 13:31:30.407  3481  3481 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
03-29 13:31:30.407  3481  3481 W System.err: Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
03-29 13:31:30.407  3481  3481 W System.err: 	at libcore.io.Posix.open(Native Method)
03-29 13:31:30.407  3481  3481 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-29 13:31:30.407  3481  3481 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-29 13:31:30.407  3481  3481 W System.err: 	... 18 more
03-29 13:31:30.407  3481  3481 E SdpManagerService: failed to get engine list
03-29 13:31:30.412  3481  3481 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
03-29 13:31:30.412  3481  3481 V EnterpriseBillingPolicy: uID is 10011
03-29 13:31:30.412  3481  3481 V EnterpriseBillingPolicy: Removed Packageuid is0
03-29 13:31:30.412  3481  3481 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
03-29 13:31:30.412  3481  3481 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
03-29 13:31:30.412  3481  3481 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
03-29 13:31:30.412  3481  3481 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
03-29 13:31:30.412  3481  3481 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
03-29 13:31:30.417  3481  3481 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
03-29 13:31:30.417  3481  3481 D KnoxTimeoutHandler: handleActiveUserChange for user 0
03-29 13:31:30.417  3481  3481 E EnterpriseSharedDevicePolicy: isSharedDeviceEnabled
03-29 13:31:30.422  3481  3481 I EnterpriseSharedDevicePolicy: isSharedDeviceEnabled in Service
03-29 13:31:30.422  3481  3651 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=14, mSplitNum[1]=26, mSplitNum[2]=38, mBgSplitQueueNum=3 divideNum= 12 r.nextReceiver= 2 receivers.size=50
03-29 13:31:30.422  3481  3651 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
03-29 13:31:30.422  3481  3481 I EnterpriseSharedDevicePolicy: Get Result: -1
03-29 13:31:30.422  3481  3481 I EnterpriseSharedDevicePolicy: status: false
03-29 13:31:30.427  3481  3481 D PersonaManagerService: getPersonasForUser(): returning null!
03-29 13:31:30.422  3481  3481 I KnoxTimeoutHandler: Shared devices show user statefalse
03-29 13:31:30.422  6713  6713 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@27aad868 time:303409
03-29 13:31:30.427  3481  3481 V AlarmManagerEXT: com.test.thalitest(10011) is removed.
03-29 13:31:30.427  6099  6099 I KLMS-2.5.262: : KLMSIntentService(): onCreate()
03-29 13:31:30.427  6099  6099 I KLMS-2.5.262: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
03-29 13:31:30.427  3726  3726 D PanelView: There is/are notification(s) 
03-29 13:31:30.427  6099  6099 I KLMS-2.5.262: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
03-29 13:31:30.427  6099 12265 I KLMS-2.5.262: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.service.KLMSIntentService (has extras) }
03-29 13:31:30.427  6099 12265 D KLMS-2.5.262: : KLMSIntentService(): PACKAGE_REMOVED
03-29 13:31:30.427  6099 12265 I KLMS-2.5.262: : Systemprocess(): listeningToPackageRemoved().START
03-29 13:31:30.427  6099 12265 I KLMS-2.5.262: : Systemprocess(): listeningToPackageRemoved().packageName: com.test.thalitest
03-29 13:31:30.427  6099 12265 I KLMS-2.5.262: : listeningToPackageRemovedforELM().START
03-29 13:31:30.427  6099 12265 I KLMS-2.5.262: : MDMBridge.getInstance()
03-29 13:31:30.427  6099 12265 I KLMS-2.5.262: : MDMBridge.getAllLicenseInfoFromSDK()
03-29 13:31:30.437  3481  3651 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{335477b2 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{f1e0aee 6890:com.samsung.aasaservice/1000}
03-29 13:31:30.437  6890  6890 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
03-29 13:31:30.437  6099 12265 I KLMS-2.5.262: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
03-29 13:31:30.442  6099 12265 I KLMS-2.5.262: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
03-29 13:31:30.442  6099 12265 I KLMS-2.5.262: : MDMBridge.getAllLicenseInfoFromSDK()
03-29 13:31:30.442  6099 12265 E KLMS-2.5.262: : arr si null
,03-29 13:31:30.442  3481  3575 V BroadcastQueue: [backgroundsplit_0] Process cur broadcast BroadcastRecord{3edd30ef u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{3a0ed62e 10192:com.samsung.android.sdk.samsunglink/u0a42}
03-29 13:31:30.447  6890  6890 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
03-29 13:31:30.447  3481  3575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-29 13:31:30.447  3481  3575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-29 13:31:30.447  3481  3575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-29 13:31:30.447  3481  3575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-29 13:31:30.452  6890  6890 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:334)
03-29 13:31:30.452  6890  6890 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
03-29 13:31:30.452  6890  6890 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3509)
03-29 13:31:30.452  6890  6890 W System.err: 	at android.app.ActivityThread.access$1900(ActivityThread.java:197)
03-29 13:31:30.457  6099 12265 D KLMS-2.5.262: : DataSource(): Fetched Data from data base count : 0
03-29 13:31:30.462  6099 12265 I KLMS-2.5.262: : listeningToPackageRemovedforELM().END
03-29 13:31:30.462  6099 12265 I KLMS-2.5.262: : Systemprocess(): listeningToPackageRemovedforKLM().START
03-29 13:31:30.462  6099 12265 I KLMS-2.5.262: : Systemprocess(): .pkgName: com.test.thalitest
03-29 13:31:30.467 12266 12266 E Zygote  : MountEmulatedStorage()
03-29 13:31:30.472  6890  6890 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1758)
03-29 13:31:30.472  6890  6890 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-29 13:31:30.472  6890  6890 W System.err: 	at android.os.Looper.loop(Looper.java:145)
03-29 13:31:30.472 12266 12266 E Zygote  : v2
03-29 13:31:30.472  6890  6890 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6872)
03-29 13:31:30.472  6890  6890 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
03-29 13:31:30.472  6890  6890 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-29 13:31:30.472  6890  6890 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
03-29 13:31:30.472  6890  6890 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
03-29 13:31:30.472 12266 12266 I libpersona: KNOX_SDCARD checking this for 1000
03-29 13:31:30.472 12266 12266 I libpersona: KNOX_SDCARD not a persona
03-29 13:31:30.472  3481  3575 I ActivityManager: Start proc 12266:com.samsung.android.sm/1000 for broadcast-4 com.samsung.android.sm/.ui.security.MonitorReceiver
03-29 13:31:30.477  3726  3726 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
03-29 13:31:30.477  3481  3575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-29 13:31:30.477  3481  3575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-29 13:31:30.477  3481  3575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-29 13:31:30.477  3481  3575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-29 13:31:30.482 12266 12266 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
03-29 13:31:30.482  3726  3726 D PanelView: There is/are notification(s) 
03-29 13:31:30.482  3726  3726 D PanelView: kidsfalse mQsExpansionEnabled:true
03-29 13:31:30.482 12266 12266 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
,03-29 13:31:30.487  3726  3726 D PanelView: There is/are notification(s) 
03-29 13:31:30.487  3726  3726 D PanelView: kidsfalse mQsExpansionEnabled:true
03-29 13:31:30.487 12266 12266 E Zygote  : accessInfo : 0
03-29 13:31:30.487 12266 12266 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-29 13:31:30.497 12273 12273 E Zygote  : MountEmulatedStorage()
03-29 13:31:30.497 12273 12273 I libpersona: KNOX_SDCARD checking this for 1000
03-29 13:31:30.497 12273 12273 E Zygote  : v2
03-29 13:31:30.497 12273 12273 I libpersona: KNOX_SDCARD not a persona
,03-29 13:31:30.497  3481  3575 I ActivityManager: Start proc 12273:com.sec.android.app.popupuireceiver/1000 for broadcast-4 com.sec.android.app.popupuireceiver/.PopupuiReceiver
,03-29 13:31:30.502 12273 12273 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
,03-29 13:31:30.502  3481  3584 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{dce746a u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t40} time:303487
03-29 13:31:30.502  3481  3584 W ActivityManager: mDVFSHelper.release()
,03-29 13:31:30.507 12273 12273 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
,03-29 13:31:30.507 12273 12273 E Zygote  : accessInfo : 0
,03-29 13:31:30.512 12273 12273 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-29 13:31:30.512  3481  3651 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-29 13:31:30.512  3481  3651 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-29 13:31:30.512  3481  3651 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-29 13:31:30.512  3481  3651 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-29 13:31:30.532 12266 12266 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-29 13:31:30.532 12266 12266 D ActivityThread: Added TimaKeyStore provider
,03-29 13:31:30.542 12273 12273 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-29 13:31:30.542 12273 12273 D ActivityThread: Added TimaKeyStore provider
,03-29 13:31:30.547  2902  2902 I art     : Explicit concurrent mark sweep GC freed 8741(372KB) AllocSpace objects, 0(0B) LOS objects, 72% free, 1529KB/5MB, paused 430us total 32.876ms
,03-29 13:31:30.552  6099 12265 D KLMS-2.5.262: : KLMSUtility(): IsPackageExistInDevice().mAppInfoList: 322
03-29 13:31:30.552  2902  2902 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 72% free, 1529KB/5MB, paused 297us total 8.926ms
03-29 13:31:30.552  3726  3726 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
03-29 13:31:30.552  6099 12265 D KLMS-2.5.262: : KLMSSharedPreferences(): deleteNotificationAppList().pkgName: com.test.thalitest
03-29 13:31:30.552  6099 12265 I KLMS-2.5.262: : KLMSSharedPreferences(): getNotificationAppList(): null
03-29 13:31:30.552  6099 12265 I KLMS-2.5.262: : Systemprocess(): Notification App List is Null. Remove Notification.
,03-29 13:31:30.557  6099 12265 E SQLiteLog: (28) failed to open "/data/data/com.samsung.klmsagent/databases/klms.db" with flag (131138) and mode_t (0) due to error (30)
,03-29 13:31:30.557  6099 12265 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.klmsagent/databases/klms.db'.
03-29 13:31:30.557  6099 12265 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-29 13:31:30.557  6099 12265 E SQLiteDatabase: #################################################################
03-29 13:31:30.557  6099 12265 E SQLiteDatabase: Error Code : 0 (SQLITE_OK)
03-29 13:31:30.557  6099 12265 E SQLiteDatabase: Caused By : not an error (code 0): Could not open the database in read/write mode.
03-29 13:31:30.557  6099 12265 E SQLiteDatabase: #################################################################
03-29 13:31:30.557  6099 12265 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-29 13:31:30.557  6099 12265 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-29 13:31:30.557  6099 12265 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-29 13:31:30.557  6099 12265 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-29 13:31:30.557  6099 12265 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-29 13:31:30.557  6099 12265 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-29 13:31:30.557  6099 12265 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-29 13:31:30.557  6099 12265 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-29 13:31:30.557  6099 12265 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-29 13:31:30.557  6099 12265 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1585)
03-29 13:31:30.557  6099 12265 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
03-29 13:31:30.557  6099 12265 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-29 13:31:30.557  6099 12265 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-29 13:31:30.557  6099 12265 E SQLiteDatabase: 	at com.samsung.klmsagent.database.DataSource.fetchData(DataSource.java:132)
03-29 13:31:30.557  6099 12265 E SQLiteDatabase: 	at com.samsung.klmsagent.process.Systemprocess.IsPackageExistInDeviceDB(Systemprocess.java:644)
03-29 13:31:30.557  6099 12265 E SQLiteDatabase: 	at com.samsung.klmsagent.process.Systemprocess.listeningToPackageRemovedforKLM(Systemprocess.java:615)
03-29 13:31:30.557  6099 12265 E SQLiteDatabase: 	at com.samsung.klmsagent.process.Systemprocess.listeningToPackageRemoved(Systemprocess.java:518)
03-29 13:31:30.557  6099 12265 E SQLiteDatabase: 	at com.samsung.klmsagent.service.KLMSIntentService.onHandleIntent(KLMSIntentService.java:199)
03-29 13:31:30.557  6099 12265 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-29 13:31:30.557  6099 12265 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-29 13:31:30.557  6099 12265 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-29 13:31:30.557  6099 12265 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-29 13:31:30.557  6099 12265 E SQLiteOpenHelper: Couldn't open klms.db for writing (will try read-only):
03-29 13:31:30.557  6099 12265 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-29 13:31:30.557  6099 12265 E SQLiteOpenHelper: #################################################################
03-29 13:31:30.557  6099 12265 E SQLiteOpenHelper: Error Code : 0 (SQLITE_OK)
03-29 13:31:30.557  60,99 12265 E SQLiteOpenHelper: Caused By : not an error (code 0): Could not open the database in read/write mode.
03-29 13:31:30.557  6099 12265 E SQLiteOpenHelper: #################################################################
03-29 13:31:30.557  6099 12265 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-29 13:31:30.557  6099 12265 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-29 13:31:30.557  6099 12265 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-29 13:31:30.557  6099 12265 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-29 13:31:30.557  6099 12265 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-29 13:31:30.557  6099 12265 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-29 13:31:30.557  6099 12265 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-29 13:31:30.557  6099 12265 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-29 13:31:30.557  6099 12265 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-29 13:31:30.557  6099 12265 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1585)
03-29 13:31:30.557  6099 12265 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
03-29 13:31:30.557  6099 12265 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-29 13:31:30.557  6099 12265 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-29 13:31:30.557  6099 12265 E SQLiteOpenHelper: 	at com.samsung.klmsagent.database.DataSource.fetchData(DataSource.java:132)
03-29 13:31:30.557  6099 12265 E SQLiteOpenHelper: 	at com.samsung.klmsagent.process.Systemprocess.IsPackageExistInDeviceDB(Systemprocess.java:644)
03-29 13:31:30.557  6099 12265 E SQLiteOpenHelper: 	at com.samsung.klmsagent.process.Systemprocess.listeningToPackageRemovedforKLM(Systemprocess.java:615)
03-29 13:31:30.557  6099 12265 E SQLiteOpenHelper: 	at com.samsung.klmsagent.process.Systemprocess.listeningToPackageRemoved(Systemprocess.java:518)
03-29 13:31:30.557  6099 12265 E SQLiteOpenHelper: 	at com.samsung.klmsagent.service.KLMSIntentService.onHandleIntent(KLMSIntentService.java:199)
03-29 13:31:30.557  6099 12265 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-29 13:31:30.557  6099 12265 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-29 13:31:30.557  6099 12265 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
03-29 13:31:30.557  6099 12265 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-29 13:31:30.562  6099 12265 W SQLiteOpenHelper: Opened klms.db in read-only mode
,03-29 13:31:30.562  6099 12265 D KLMS-2.5.262: : DataSource(): Fetched Data from data base count : 0
03-29 13:31:30.562  6099 12265 I KLMS-2.5.262: : Systemprocess(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,03-29 13:31:30.562  6099 12265 I KLMS-2.5.262: : Systemprocess(): listeningToPackageRemovedforKLM().END
03-29 13:31:30.562  6099 12265 I KLMS-2.5.262: : Systemprocess(): listeningToPackageRemoved().END
,03-29 13:31:30.567  2902  2902 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 72% free, 1529KB/5MB, paused 293us total 8.124ms
,03-29 13:31:30.582 12297 12297 E Zygote  : MountEmulatedStorage()
03-29 13:31:30.582 12297 12297 E Zygote  : v2
03-29 13:31:30.582 12297 12297 I libpersona: KNOX_SDCARD checking this for 10045
03-29 13:31:30.582 12297 12297 I libpersona: KNOX_SDCARD not a persona
,03-29 13:31:30.587  3481  3651 I ActivityManager: Start proc 12297:com.osp.app.signin/u0a45 for broadcast-4 com.osp.app.signin/com.msc.sa.selfupdate.SelfUpgradeReceiver
,03-29 13:31:30.592 12297 12297 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
,03-29 13:31:30.597 12297 12297 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
,03-29 13:31:30.597 12297 12297 E Zygote  : accessInfo : 0
,03-29 13:31:30.597 12297 12297 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,03-29 13:31:30.602  3481  3512 V BroadcastQueue: [backgroundsplit_1] Process cur broadcast BroadcastRecord{297177e8 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{1d48ee01 12266:com.samsung.android.sm/1000}
,03-29 13:31:30.612  3481  3834 V BroadcastQueue: [backgroundsplit_2] Process cur broadcast BroadcastRecord{657d4a6 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{14944ee7 12273:com.sec.android.app.popupuireceiver/1000}
03-29 13:31:30.612  6099  6099 I KLMS-2.5.262: : KLMSIntentService(): onDestroy()
03-29 13:31:30.612  3481  3604 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/2/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.0
03-29 13:31:30.612  3481  3604 D UsbHostManager: displayNotification : [02h,02h,01h]
,03-29 13:31:30.612  3481  3604 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.1
03-29 13:31:30.612  3481  3604 D UsbHostManager: displayNotification : [0ah,00h,00h]
,03-29 13:31:30.612  3481  3604 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/13/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.2
03-29 13:31:30.617  3481  3604 D UsbHostManager: displayNotification : [02h,0dh,00h]
03-29 13:31:30.617 12297 12297 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-29 13:31:30.617 12297 12297 D ActivityThread: Added TimaKeyStore provider
03-29 13:31:30.617  3481  3651 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{335477b2 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{2222e7bb 3481:system/1000}
,03-29 13:31:30.617  3481  3604 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.3
03-29 13:31:30.617  3481  3604 D UsbHostManager: displayNotification : [0ah,00h,01h]
,03-29 13:31:30.622  3481  3695 D UsbHostManager: usbDeviceRemoved : /dev/bus/usb/001/003
03-29 13:31:30.622  3481  3695 E UsbHostManager: usbDeviceRemoved :: deviceName = /dev/bus/usb/001/003
03-29 13:31:30.622  3481  3695 D UsbSettingsManager: usbDeviceRemoved, sending Intent { act=android.hardware.usb.action.USB_DEVICE_DETACHED (has extras) }
,03-29 13:31:30.622  3481  3481 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{335477b2 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{26791cff 6239:com.sec.android.service.health/u0a19}
,03-29 13:31:30.627  6239  6239 D com.sec.android.service.health.upgrade.UninstallReceiver: onReceive()
,03-29 13:31:30.627  6239  6239 I com.sec.android.service.health.upgrade.UninstallReceiver: onReceive called  PACKAGE_REMOVED package:com.test.thalitest
03-29 13:31:30.627  6239  6239 D com.sec.android.service.health.upgrade.UninstallReceiver: onReceive() : package name is not s health. Return !!!
,03-29 13:31:30.627 12266 12266 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-29 13:31:30.637  3481  4029 V BroadcastQueue: [backgroundsplit_0] Process cur broadcast BroadcastRecord{3edd30ef u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{20da2a94 12297:com.osp.app.signin/u0a45}
,03-29 13:31:30.637  3481  3604 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 1d6b/2/310, type = 9/0/0, interface = 9/0/0, devpath = /devices/15510000.usb/usb1/1-0:1.0
03-29 13:31:30.637  3481  3604 D UsbHostManager: displayNotification : [09h,00h,00h]
,03-29 13:31:30.647  3481  3651 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{335477b2 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{14624fd2 10682:com.sec.android.widgetapp.locationwidget/u0a22}
,03-29 13:31:30.647 10682 10682 D LocationWidgetApplication: getLastUiLocationId() : mLastUiLocationId = -100
,03-29 13:31:30.652  3481  3695 D UsbHostManager: usbDeviceRemoved : /dev/bus/usb/001/001
03-29 13:31:30.652  3481  3695 E UsbHostManager: usbDeviceRemoved :: deviceName = /dev/bus/usb/001/001
,03-29 13:31:30.672 12273 12273 D PopupuiReceiver: onReceive() getAction : android.intent.action.PACKAGE_REMOVED
,03-29 13:31:30.677  3481  4417 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-29 13:31:30.677  3481  4417 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-29 13:31:30.677  3481  4417 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-29 13:31:30.677  3481  4417 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-29 13:31:30.682 12266 12266 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.sm/databases/lowpowercontext-system-db" with flag (131138) and mode_t (0) due to error (30)
,03-29 13:31:30.682 12297 12297 I SA      : [SSP] onCreated
,03-29 13:31:30.687 12266 12266 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.sm/databases/lowpowercontext-system-db'.
03-29 13:31:30.687 12266 12266 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-29 13:31:30.687 12266 12266 E SQLiteDatabase: #################################################################
03-29 13:31:30.687 12266 12266 E SQLiteDatabase: Error Code : 0 (SQLITE_OK)
03-29 13:31:30.687 12266 12266 E SQLiteDatabase: Caused By : not an error (code 0): Could not open the database in read/write mode.
03-29 13:31:30.687 12266 12266 E SQLiteDatabase: #################################################################
03-29 13:31:30.687 12266 12266 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-29 13:31:30.687 12266 12266 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-29 13:31:30.687 12266 12266 E SQLiteDatabase: 	,at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-29 13:31:30.687 12266 12266 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-29 13:31:30.687 12266 12266 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-29 13:31:30.687 12266 12266 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-29 13:31:30.687 12266 12266 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-29 13:31:30.687 12266 12266 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-29 13:31:30.687 12266 12266 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-29 13:31:30.687 12266 12266 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1585)
03-29 13:31:30.687 12266 12266 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
03-29 13:31:30.687 12266 12266 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-29 13:31:30.687 12266 12266 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-29 13:31:30.687 12266 12266 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2441)
03-29 13:31:30.687 12266 12266 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.a(DataStore.java:86)
03-29 13:31:30.687 12266 12266 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextProvider.onCreate(LowpowerContextProvider.java:302)
03-29 13:31:30.687 12266 12266 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1737)
03-29 13:31:30.687 12266 12266 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
03-29 13:31:30.687 12266 12266 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:6413)
03-29 13:31:30.687 12266 12266 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:6008)
03-29 13:31:30.687 12266 12266 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5948)
03-29 13:31:30.687 12266 12266 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:197)
03-29 13:31:30.687 12266 12266 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1742)
03-29 13:31:30.687 12266 12266 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-29 13:31:30.687 12266 12266 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-29 13:31:30.687 12266 12266 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6872)
03-29 13:31:30.687 12266 12266 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
03-29 13:31:30.687 12266 12266 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-29 13:31:30.687 12266 12266 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
03-29 13:31:30.687 12266 12266 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
,03-29 13:31:30.687 12297 12297 E SQLiteLog: (28) failed to open "/data/data/com.osp.app.signin/databases/samsungaccount.db" with flag (131138) and mode_t (0) due to error (30)
,03-29 13:31:30.692 12297 12297 E SQLiteDatabase: Failed to open database '/data/data/com.osp.app.signin/databases/samsungaccount.db'.,
03-29 13:31:30.692 12297 12297 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-29 13:31:30.692 12297 12297 E SQLiteDatabase: #################################################################
03-29 13:31:30.692 12297 12297 E SQLiteDatabase: Error Code : 0 (SQLITE_OK)
03-29 13:31:30.692 12297 12297 E SQLiteDatabase: Caused By : not an error (code 0): Could not open the database in read/write mode.
03-29 13:31:30.692 12297 12297 E SQLiteDatabase: #################################################################
03-29 13:31:30.692 12297 12297 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-29 13:31:30.692 12297 12297 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-29 13:31:30.692 12297 12297 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-29 13:31:30.692 12297 12297 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-29 13:31:30.692 12297 12297 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-29 13:31:30.692 12297 12297 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-29 13:31:30.692 12297 12297 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-29 13:31:30.692 12297 12297 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-29 13:31:30.692 12297 12297 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-29 13:31:30.692 12297 12297 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1585)
03-29 13:31:30.692 12297 12297 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
03-29 13:31:30.692 12297 12297 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-29 13:31:30.692 12297 12297 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-29 13:31:30.692 12297 12297 E SQLiteDatabase: 	at com.msc.contentprovider.SamsungServiceProvider.onCreate(SamsungServiceProvider.java:575)
03-29 13:31:30.692 12297 12297 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1737)
03-29 13:31:30.692 12297 12297 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
03-29 13:31:30.692 12297 12297 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:6413)
03-29 13:31:30.692 12297 12297 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:6008)
03-29 13:31:30.692 12297 12297 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5948)
03-29 13:31:30.692 12297 12297 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:197)
03-29 13:31:30.692 12297 12297 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1742)
03-29 13:31:30.692 12297 12297 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-29 13:31:30.692 12297 12297 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-29 13:31:30.692 12297 12297 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6872)
03-29 13:31:30.692 12297 12297 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
03-29 13:31:30.692 12297 12297 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-29 13:31:30.692 12297 12297 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
03-29 13:31:30.692 12297 12297 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1,199)
03-29 13:31:30.692 12266 12266 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.sm/databases/sm.db" with flag (131138) and mode_t (0) due to error (30)
03-29 13:31:30.697 12297 12297 E SQLiteLog: (28) failed to open "/data/data/com.osp.app.signin/databases/openData.db" with flag (131138) and mode_t (0) due to error (30)
,03-29 13:31:30.697 12266 12266 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.sm/databases/sm.db'.
03-29 13:31:30.697 12266 12266 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-29 13:31:30.697 12266 12266 E SQLiteDatabase: #################################################################
03-29 13:31:30.697 12266 12266 E SQLiteDatabase: Error Code : 0 (SQLITE_OK)
03-29 13:31:30.697 12266 12266 E SQLiteDatabase: Caused By : not an error (code 0): Could not open the database in read/write mode.
03-29 13:31:30.697 12266 12266 E SQLiteDatabase: #################################################################
03-29 13:31:30.697 12266 12266 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-29 13:31:30.697 12266 12266 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-29 13:31:30.697 12266 12266 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-29 13:31:30.697 12266 12266 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-29 13:31:30.697 12266 12266 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-29 13:31:30.697 12266 12266 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-29 13:31:30.697 12266 12266 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-29 13:31:30.697 12266 12266 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-29 13:31:30.697 12266 12266 E SQLiteDatabase: 	,at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-29 13:31:30.697 12266 12266 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1585)
03-29 13:31:30.697 12266 12266 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
03-29 13:31:30.697 12266 12266 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-29 13:31:30.697 12266 12266 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-29 13:31:30.697 12266 12266 E SQLiteDatabase: 	at com.samsung.android.sm.database.b.<init>(SmDatabaseHelper.java:55)
03-29 13:31:30.697 12266 12266 E SQLiteDatabase: 	at com.samsung.android.sm.database.b.a(SmDatabaseHelper.java:44)
03-29 13:31:30.697 12266 12266 E SQLiteDatabase: 	at com.samsung.android.sm.database.SmProvider.onCreate(SmProvider.java:78)
03-29 13:31:30.697 12266 12266 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1737)
03-29 13:31:30.697 12266 12266 E SQLiteDatabase: 	,at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
03-29 13:31:30.697 12266 12266 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:6413)
03-29 13:31:30.697 12266 12266 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:6008)
03-29 13:31:30.697 12266 12266 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5948)
03-29 13:31:30.697 12266 12266 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:197)
03-29 13:31:30.697 12266 12266 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1742)
03-29 13:31:30.697 12266 12266 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-29 13:31:30.697 12266 12266 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-29 13:31:30.697 12266 12266 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6872)
03-29 13:31:30.697 12266 12266 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
03-29 13:31:30.697 12266 12266 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-29 13:31:30.697 12266 12266 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
03-29 13:31:30.697 12266 12266 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
03-29 13:31:30.697 12297 12297 E SQLiteDatabase: Failed to open database '/data/data/com.osp.app.signin/databases/openData.db'.
03-29 13:31:30.697 12297 12297 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-29 13:31:30.697 12297 12297 E SQLiteDatabase: #################################################################
03-29 13:31:30.697 12297 12297 E SQLiteDatabase: Error Code : 0 (SQLITE_OK),
,03-29 13:31:30.697 12297 12297 E SQLiteDatabase: Caused By : not an error (code 0): Could not open the database in read/write mode.
03-29 13:31:30.697 12297 12297 E SQLiteDatabase: #################################################################
03-29 13:31:30.697 12297 12297 E SQLiteDatabase: 	,at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-29 13:31:30.697 12297 12297 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-29 13:31:30.697 12297 12297 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-29 13:31:30.697 12297 12297 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-29 13:31:30.697 12297 12297 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-29 13:31:30.697 12297 12297 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-29 13:31:30.697 12297 12297 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-29 13:31:30.697 12297 12297 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-29 13:31:30.697 12297 12297 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-29 13:31:30.697 12297 12297 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1585)
03-29 13:31:30.697 12297 12297 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
03-29 13:31:30.697 12297 12297 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-29 13:31:30.697 12297 12297 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-29 13:31:30.697 12297 12297 E SQLiteDatabase: 	at com.msc.openprovider.OpenContentProvider.onCreate(OpenContentProvider.java:214)
03-29 13:31:30.697 12297 12297 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1737)
03-29 13:31:30.697 12297 12297 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
03-29 13:31:30.697 12297 12297 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:6413)
03-29 13:31:30.697 12297 12297 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:6008)
03-29 13:31:30.697 12297 12297 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5948)
03-29 13:31:30.697 12297 12297 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:197)
03-29 13:31:30.697 12297 12297 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1742)
03-29 13:31:30.697 12297 12297 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-29 13:31:30.697 12297 12297 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-29 13:31:30.697 12297 12297 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6872)
03-29 13:31:30.697 12297 12297 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
03-29 13:31:30.697 12297 12297 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-29 13:31:30.697 12297 12297 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
03-29 13:31:30.697 12297 12297 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
,03-29 13:31:30.697 12266 12266 D AndroidRuntime: Shutting down VM
03-29 13:31:30.697 12266 12266 E AndroidRuntime: FATAL EXCEPTION: main
03-29 13:31:30.697 12266 12266 E AndroidRuntime: Process: com.samsung.android.sm, PID: 12266
03-29 13:31:30.697 12266 12266 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.samsung.android.sm.database.SmProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-29 13:31:30.697 12266 12266 E AndroidRuntime: #################################################################
03-29 13:31:30.697 12266 12266 E AndroidRuntime: Error Code : 0 (SQLITE_OK)
03-29 13:31:30.697 12266 12266 E AndroidRuntime: Caused By : not an error (code 0): Could not open the database in read/write mode.
03-29 13:31:30.697 12266 12266 E AndroidRuntime: #################################################################
03-29 13:31:30.697 12266 12266 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:6416)
03-29 13:31:30.697 12266 12266 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:6008)
03-29 13:31:30.697 12266 12266 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5948)
03-29 13:31:30.697 12266 12266 E AndroidRuntime: 	at android.app.ActivityThread.access$1700(ActivityThread.java:197)
03-29 13:31:30.697 12266 12266 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1742)
03-29 13:31:30.697 12266 12266 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-29 13:31:30.697 12266 12266 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
03-29 13:31:30.697 12266 12266 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6872)
03-29 13:31:30.697 12266 12266 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
03-29 13:31:30.697 12266 12266 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-29 13:31:30.697 12266 12266 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
03-29 13:31:30.697 12266 12266 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
03-29 13:31:30.697 12266 12266 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-29 13:31:30.697 12266 12266 E AndroidRuntime: #################################################################
03-29 13:31:30.697 12266 12266 E AndroidRuntime: Error Code : 0 (SQLITE_OK)
03-29 13:31:30.697 12266 12266 E AndroidRuntime: Caused By : not an error (code 0): Could not open the database in read/write mode.
03-29 13:31:30.697 12266 12266 E AndroidRuntime: #################################################################
,03-29 13:31:30.697 12266 12266 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-29 13:31:30.697 12266 12266 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-29 13:31:30.697 12266 12266 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-29 13:31:30.697 12266 12266 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-29 13:31:30.697 12266 12266 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-29 13:31:30.697 12266 12266 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-29 13:31:30.697 12266 12266 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-29 13:31:30.697 12266 12266 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-29 13:31:30.697 12266 12266 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-29 13:31:30.697 12266 12266 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1585)
03-29 13:31:30.697 12266 12266 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
03-29 13:31:30.697 12266 12266 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-29 13:31:30.697 12266 12266 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-29 13:31:30.697 12266 12266 E AndroidRuntime: 	at com.samsung.android.sm.database.b.<init>(SmDatabaseHelper.java:55)
03-29 13:31:30.697 12266 12266 E AndroidRuntime: 	at com.samsung.android.sm.database.b.a(SmDatabaseHelper.java:44)
03-29 13:31:30.697 12266 12266 E AndroidRuntime: 	at com.samsung.android.sm.database.SmProvider.onCreate(SmProvider.java:78)
03-29 13:31:30.697 12266 12266 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1737)
03-29 13:31:30.697 12266 12266 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
03-29 13:31:30.697 12266 12266 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:6413)
03-29 13:31:30.697 12266 12266 E AndroidRuntime: 	... 11 more
03-29 13:31:30.702  3481  3632 I EventHub: Removing device '/dev/input/event10' due to inotify event
,03-29 13:31:30.727 12319 12319 E Zygote  : MountEmulatedStorage(),
03-29 13:31:30.727 12319 12319 E Zygote  : v2
03-29 13:31:30.727 12319 12319 I libpersona: KNOX_SDCARD checking this for 1000
03-29 13:31:30.727 12319 12319 I libpersona: KNOX_SDCARD not a persona
,03-29 13:31:30.732 12319 12319 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
,03-29 13:31:30.742  3481  4417 I ActivityManager: Start proc 12319:com.sec.pcw.device/1000 for broadcast-3 com.sec.pcw.device/.receiver.SYSTEMReceiver
,03-29 13:31:30.747  3481  3632 I EventHub: Removing device '/dev/input/event7' due to inotify event
03-29 13:31:30.747 12319 12319 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
03-29 13:31:30.747 12319 12319 E Zygote  : accessInfo : 0
03-29 13:31:30.752 12319 12319 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-29 13:31:30.767  3481  4718 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.samsung.android.sm
,03-29 13:31:30.782  3481  3835 D SecContentProvider2: query(), uri = -1 selection = getSealedState,
,03-29 13:31:30.797  3481 12329 E DropBoxManagerService: Can't write: system_app_crash
03-29 13:31:30.797  3481 12329 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop225.tmp: open failed: EROFS (Read-only file system)
03-29 13:31:30.797  3481 12329 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-29 13:31:30.797  3481 12329 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-29 13:31:30.797  3481 12329 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-29 13:31:30.797  3481 12329 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-29 13:31:30.797  3481 12329 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-29 13:31:30.797  3481 12329 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$23.run(ActivityManagerService.java:16408)
03-29 13:31:30.797  3481 12329 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-29 13:31:30.797  3481 12329 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-29 13:31:30.797  3481 12329 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-29 13:31:30.797  3481 12329 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-29 13:31:30.797  3481 12329 E DropBoxManagerService: 	... 5 more
,03-29 13:31:30.797  3481 12329 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/dropbox/drop225.tmp
,03-29 13:31:30.802  3481  3575 V BroadcastQueue: [backgroundsplit_1] Process cur broadcast BroadcastRecord{297177e8 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{1d48ee01 12266:com.samsung.android.sm/1000}
,03-29 13:31:30.807 12266 12266 I Process : Sending signal. PID: 12266 SIG: 9
,03-29 13:31:30.812 12319 12319 D TimaKeyStoreProvider: TimaSignature is unavailable
03-29 13:31:30.812 12319 12319 D ActivityThread: Added TimaKeyStore provider
,03-29 13:31:30.817  3481  3632 I EventHub: Removing device '/dev/input/event8' due to inotify event
03-29 13:31:30.817  3481  4028 D SecContentProvider2: query(), uri = 15 selection = getSealedHideNotificationMessages
,03-29 13:31:30.827 12273 12273 I PopupuiReceiver_KNOX: getSealedHideNotificationMessages : 0
,03-29 13:31:30.837  3481  3512 D SecContentProvider2: query(), uri = 15 selection = getCheckCoverPopupState
03-29 13:31:30.837  3481  3982 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{335477b2 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{249c9532 12319:com.sec.pcw.device/1000}
,03-29 13:31:30.842 12273 12273 I PopupuiReceiver_KNOX: getCheckCoverPopupState : false
,03-29 13:31:30.842 12273 12273 D PopupuiReceiver: Action package removed
,03-29 13:31:30.857 12297 12297 I SA      : [TPM] There is no property file
,03-29 13:31:30.862  3481  4028 V BroadcastQueue: [backgroundsplit_2] Process cur broadcast BroadcastRecord{657d4a6 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{a8cacb3 10619:com.samsung.android.snote/u0a160}
,03-29 13:31:30.867 12297 12297 I SA      : [SCU] isHaveSA() - false
,03-29 13:31:30.872  3481  3632 I EventHub: Removing device '/dev/input/event9' due to inotify event
,03-29 13:31:30.877 12319 12319 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
03-29 13:31:30.877 12319 12319 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
03-29 13:31:30.877 12319 12319 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,03-29 13:31:30.877 12319 12319 E SQLiteLog: (28) failed to open "/data/data/com.sec.pcw.device/databases/value.db" with flag (131138) and mode_t (0) due to error (30)
,03-29 13:31:30.882 12319 12319 E SQLiteDatabase: Failed to open database '/data/data/com.sec.pcw.device/databases/value.db'.
03-29 13:31:30.882 12319 12319 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-29 13:31:30.882 12319 12319 E SQLiteDatabase: #################################################################
03-29 13:31:30.882 12319 12319 E SQLiteDatabase: Error Code : 0 (SQLITE_OK)
03-29 13:31:30.882 12319 12319 E SQLiteDatabase: Caused By : not an error (code 0): Could not open the database in read/write mode.
03-29 13:31:30.882 12319 12319 E SQLiteDatabase: #################################################################
03-29 13:31:30.882 12319 12319 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-29 13:31:30.882 12319 12319 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-29 13:31:30.882 12319 12319 E SQLiteDatabase: 	,at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-29 13:31:30.882 12319 12319 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-29 13:31:30.882 12319 12319 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-29 13:31:30.882 12319 12319 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-29 13:31:30.882 12319 12319 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-29 13:31:30.882 12319 12319 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-29 13:31:30.882 12319 12319 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-29 13:31:30.882 12319 12319 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1585)
03-29 13:31:30.882 12319 12319 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
03-29 13:31:30.882 12319 12319 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-29 13:31:30.882 12319 12319 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-29 13:31:30.882 12319 12319 E SQLiteDatabase: 	at com.sec.pcw.device.contentprovider.DMProvider.onCreate(DMProvider.java:32)
03-29 13:31:30.882 12319 12319 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1737)
03-29 13:31:30.882 12319 12319 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
03-29 13:31:30.882 12319 12319 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:6413)
03-29 13:31:30.882 12319 12319 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:6008)
03-29 13:31:30.882 12319 12319 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5948)
03-29 13:31:30.882 12319 12319 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:197)
03-29 13:31:30.882 12319 12319 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1742)
03-29 13:31:30.882 12319 12319 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-29 13:31:30.882 12319 12319 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-29 13:31:30.882 12319 12319 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6872)
03-29 13:31:30.882 12319 12319 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
03-29 13:31:30.882 12319 12319 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-29 13:31:30.882 12319 12319 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
03-29 13:31:30.882 12319 12319 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
03-29 13:31:30.882 12319 12319 D AndroidRuntime: Shutting down VM
03-29 13:31:30.882 12297 12297 I SA      : [TPM] getModelProperty : null
03-29 13:31:30.882 12297 12297 I SA      : [TPM] getCSCProperty : null
,03-29 13:31:30.882 12319 12319 E AndroidRuntime: FATAL EXCEPTION: main
03-29 13:31:30.882 12319 12319 E AndroidRuntime: Process: com.sec.pcw.device, PID: 12319
03-29 13:31:30.882 12319 12319 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.sec.pcw.device.contentprovider.DMProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-29 13:31:30.882 12319 12319 E AndroidRuntime: #################################################################
03-29 13:31:30.882 12319 12319 E AndroidRuntime: Error Code : 0 (SQLITE_OK)
03-29 13:31:30.882 12319 12319 E AndroidRuntime: Caused By : not an error (code 0): Could not open the database in read/write mode.
03-29 13:31:30.882 12319 12319 E AndroidRuntime: #################################################################
03-29 13:31:30.882 12319 12319 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:6416)
03-29 13:31:30.882 12319 12319 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:6008)
03-29 13:31:30.882 12319 12319 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5948)
03-29 13:31:30.882 12319 12319 E AndroidRuntime: 	at android.app.ActivityThread.access$1700(ActivityThread.java:197)
03-29 13:31:30.882 12319 12319 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1742)
03-29 13:31:30.882 12319 12319 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-29 13:31:30.882 12319 12319 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
03-29 13:31:30.882 12319 12319 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6872)
03-29 13:31:30.882 12319 12319 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
03-29 13:31:30.882 12319 12319 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-29 13:31:30.882 12319 12319 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
03-29 13:31:30.882 12319 12319 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
03-29 13:31:30.882 12319 12319 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-29 13:31:30.882 12319 12319 E AndroidRuntime: #################################################################
03-29 13:31:30.882 12319 12319 E AndroidRuntime: Error Code : 0 (SQLITE_OK)
03-29 13:31:30.882 12319 12319 E AndroidRuntime: Caused By : not an error (code 0): Could not open the database in read/write mode.
03-29 13:31:30.882 12319 12319 E AndroidRuntime: #################################################################
03-29 13:31:30.882 12319 12319 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-29 13:31:30.882 12319 12319 E AndroidRuntime: 	,at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-29 13:31:30.882 12319 12319 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-29 13:31:30.882 12319 12319 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-29 13:31:30.882 12319 12319 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-29 13:31:30.882 12319 12319 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-29 13:31:30.882 12319 12319 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-29 13:31:30.882 12319 12319 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-29 13:31:30.882 12319 12319 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-29 13:31:30.882 12319 12319 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1585)
03-29 13:31:30.882 12319 12319 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
03-29 13:31:30.882 12319 12319 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-29 13:31:30.882 12319 12319 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-29 13:31:30.882 12319 12319 E AndroidRuntime: 	at com.sec.pcw.device.contentprovider.DMProvider.onCreate(DMProvider.java:32)
03-29 13:31:30.882 12319 12319 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1737)
03-29 13:31:30.882 12319 12319 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
03-29 13:31:30.882 12319 12319 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:6413)
03-29 13:31:30.882 12319 12319 E AndroidRuntime: 	... 11 more
03-29 13:31:30.887 12297 12297 I SA      : [DM] FLOATING AMOLED FEATURE: true
03-29 13:31:30.887  3481  4028 I ActivityManager: Process com.samsung.android.sm (pid 12266)(adj 0) has died(243,1479)
03-29 13:31:30.887 12297 12297 I SA      : [DM] PRODUCT AMOLED FEATURE: false
03-29 13:31:30.887 12297 12297 I SA      : [DM] TFT FEATURE: false
,03-29 13:31:30.887 12297 12297 I SA      : [SUR] onReceive called
03-29 13:31:30.887 12297 12297 I SA      : [SUR] Not SA Package.. finish
,03-29 13:31:30.897  3481  3632 I EventHub: Removing device '/dev/input/event11' due to inotify event
,03-29 13:31:30.902  3481  3651 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.pcw.device
,03-29 13:31:30.902  3481  3575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-29 13:31:30.902  3481  3575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-29 13:31:30.902  3481  3575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-29 13:31:30.902  3481  3575 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-29 13:31:30.932 12337 12337 E Zygote  : MountEmulatedStorage()
03-29 13:31:30.932 12337 12337 E Zygote  : v2
03-29 13:31:30.932 12337 12337 I libpersona: KNOX_SDCARD checking this for 1000
,03-29 13:31:30.932 12337 12337 I libpersona: KNOX_SDCARD not a persona
03-29 13:31:30.932  3481  3632 I EventHub: Removing device '/dev/input/event12' due to inotify event
,03-29 13:31:30.937 12337 12337 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
,03-29 13:31:30.942 12337 12337 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
03-29 13:31:30.947  3481  3575 I ActivityManager: Start proc 12337:com.samsung.android.sm/1000 for broadcast-4 com.samsung.android.sm/.database.lowpowercontext.LowpowerContextReceiver
,03-29 13:31:30.947 12337 12337 E Zygote  : accessInfo : 0
,03-29 13:31:30.947 12337 12337 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-29 13:31:30.957  3481  3985 V BroadcastQueue: [backgroundsplit_0] Process cur broadcast BroadcastRecord{3edd30ef u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{1f5c147 4351:android.process.acore/u0a23}
,03-29 13:31:30.972  3481  3985 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-29 13:31:30.972  3481  3985 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-29 13:31:30.972  3481  3985 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-29 13:31:30.977  3481  3985 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-29 13:31:30.977  3481  3632 I EventHub: Removing device '/dev/input/event13' due to inotify event
,03-29 13:31:31.007 12337 12337 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-29 13:31:31.007 12337 12337 D ActivityThread: Added TimaKeyStore provider
,03-29 13:31:31.022 12352 12352 E Zygote  : MountEmulatedStorage()
03-29 13:31:31.022 12352 12352 E Zygote  : v2
,03-29 13:31:31.022 12352 12352 I libpersona: KNOX_SDCARD checking this for 10183
03-29 13:31:31.027 12352 12352 I libpersona: KNOX_SDCARD not a persona
,03-29 13:31:31.027 12352 12352 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
,03-29 13:31:31.037 12352 12352 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
03-29 13:31:31.037  3481  3985 I ActivityManager: Start proc 12352:com.samsung.android.provider.shootingmodeprovider/u0a183 for broadcast-4 com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver
,03-29 13:31:31.037 12352 12352 E Zygote  : accessInfo : 0
,03-29 13:31:31.042 12352 12352 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-29 13:31:31.047  3481  3985 I ActivityManager: Killing 10417:com.vlingo.midas/u0a34 (adj 15): emptyCount ##31
03-29 13:31:31.047  3481  3632 I EventHub: Removing device '/dev/input/event14' due to inotify event
,03-29 13:31:31.052  3481  3985 I ActivityManager: Killing 10137:com.google.android.apps.docs/u0a101 (adj 15): emptyCount ##32
,03-29 13:31:31.057  3481  3982 D ActivityManager: startService callerProcessName:com.android.providers.contacts, calleePkgName: com.android.providers.contacts
,03-29 13:31:31.097  3481  3834 V BroadcastQueue: [backgroundsplit_1] Process cur broadcast BroadcastRecord{297177e8 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{20b45c39 12337:com.samsung.android.sm/1000}
,03-29 13:31:31.102  3481 12368 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/dropbox/drop226.tmp
03-29 13:31:31.102  3481 12368 E DropBoxManagerService: Can't write: system_app_crash
03-29 13:31:31.102  3481 12368 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop226.tmp: open failed: EROFS (Read-only file system)
03-29 13:31:31.102  3481 12368 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-29 13:31:31.102  3481 12368 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-29 13:31:31.102  3481 12368 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-29 13:31:31.102  3481 12368 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-29 13:31:31.102  3481 12368 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-29 13:31:31.102  3481 12368 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$23.run(ActivityManagerService.java:16408)
03-29 13:31:31.102  3481 12368 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-29 13:31:31.102  3481 12368 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-29 13:31:31.102  3481 12368 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-29 13:31:31.102  3481 12368 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-29 13:31:31.102  3481 12368 E DropBoxManagerService: 	... 5 more
,03-29 13:31:31.112 12352 12352 D TimaKeyStoreProvider: TimaSignature is unavailable
03-29 13:31:31.112 12352 12352 D ActivityThread: Added TimaKeyStore provider
03-29 13:31:31.112  3481  4718 I ActivityManager: Killing 10491:com.samsung.android.app.filterinstaller/1000 (adj 15): emptyCount ##31
,03-29 13:31:31.127  3481  4718 V BroadcastQueue: [backgroundsplit_0] Process cur broadcast BroadcastRecord{3edd30ef u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{1adeddbb 5618:com.android.contacts/u0a23}
,03-29 13:31:31.157  3481  3834 V BroadcastQueue: [backgroundsplit_2] Process cur broadcast BroadcastRecord{657d4a6 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{b6233df 12352:com.samsung.android.provider.shootingmodeprovider/u0a183}
,03-29 13:31:31.162 12337 12337 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-29 13:31:31.187 12337 12337 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.sm/databases/lowpowercontext-system-db" with flag (131138) and mode_t (0) due to error (30)

```
