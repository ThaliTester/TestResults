#### Test 64613803adf70b9_thali08_samsung-SM-N910C Logs


```
--------- beginning of system
,03-31 16:28:53.441  3440  3484 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 16:28:53.441  3440  3484 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 16:28:53.441  3440  3484 D BatteryService: online:4, current avg:41, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:50
03-31 16:28:53.446  3440  3440 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 16:28:53.451  3440  3484 D BatteryService: stay LED for fully charged
--------- beginning of main
03-31 16:28:53.461  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 16:28:53.451  3440  3440 I MotionRecognitionService: Plugged
03-31 16:28:53.461  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 16:28:53.451  3440  3440 D MotionRecognitionService:   cableConnection= 1
03-31 16:28:53.461  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
03-31 16:28:53.451  3440  3440 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 16:28:53.451  3440  3440 D MotionRecognitionService: skip setTransmitPower. 
03-31 16:28:53.486  5838  5838 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 16:28:53.486  5838  5954 D HeadsetStateMachine: Disconnected process message: 10
03-31 16:28:53.496  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 16:28:53.501  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 16:28:53.501  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 16:28:53.501  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 16:28:53.901 11103 11103 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
03-31 16:28:53.911 11103 11103 D AndroidRuntime: CheckJNI is OFF
03-31 16:28:53.911 11103 11103 D AndroidRuntime: readGMSProperty: start
03-31 16:28:53.911 11103 11103 D AndroidRuntime: readGMSProperty: already setted!!
03-31 16:28:53.911 11103 11103 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-31 16:28:53.911 11103 11103 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-31 16:28:53.911 11103 11103 D AndroidRuntime: readGMSProperty: end
03-31 16:28:53.911 11103 11103 D AndroidRuntime: addProductProperty: start
03-31 16:28:54.121 11103 11103 E AffinityControl: AffinityControl: registerfunction enter
03-31 16:28:54.146 11103 11103 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-31 16:28:54.161  3440  3965 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
03-31 16:28:54.176  3440  3965 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-31 16:28:54.211  3440  3965 W ActivityManager: mDVFSHelper.acquire()
03-31 16:28:54.216  3440  3965 V WindowManager: addAppToken: AppWindowToken{24e105d4 token=Token{27cc8f27 ActivityRecord{2cc3ede6 u0 com.test.thalitest/.MainActivity t42}}} to stack=1 task=42 at 0
03-31 16:28:54.216  3440  3965 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 16:28:54.216  3440  3965 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 16:28:54.216  3440  3965 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 16:28:54.216  3440  3965 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 16:28:54.226  3440  3583 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-31 16:28:54.226  3440  3583 D PhoneWindow: *FMB* installDecor flags : -2122120936
03-31 16:28:54.231  3440  3583 D SecWifiDisplayUtil: Metadata value : none
03-31 16:28:54.231  3440  3583 V WindowManager: Adding window Window{3cda3c1f u0 d0 Starting com.test.thalitest} at 3 of 7 (after Window{3214a421 u0 d0 com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity})
03-31 16:28:54.241 11128 11128 E Zygote  : MountEmulatedStorage()
03-31 16:28:54.241 11128 11128 E Zygote  : v2
03-31 16:28:54.241 11128 11128 I libpersona: KNOX_SDCARD checking this for 10011
03-31 16:28:54.241 11128 11128 I libpersona: KNOX_SDCARD not a persona
03-31 16:28:54.251  3440  3965 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
03-31 16:28:54.251  3440  3965 I ActivityManager: Start proc 11128:com.test.thalitest/u0a11 for activity com.test.thalitest/.MainActivity
03-31 16:28:54.251  3440  3965 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-31 16:28:54.251  3440  3965 D MultiWindowConverter: dismissGuide() : Before attaching the guide view, mForceDismissGuide : false
03-31 16:28:54.251  3440  3965 D InputDispatcher: Focused application set to: xxxx
03-31 16:28:54.251  3440  3965 D InputDispatcher: Focus left window: 6534
03-31 16:28:54.251  3440  3583 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-31 16:28:54.251  3440  3583 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
03-31 16:28:54.251  2860  2860 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=404, uhalitest
03-31 16:28:54.256 11128 11128 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
03-31 16:28:54.256 11103 11103 D AndroidRuntime: Shutting down VM
03-31 16:28:54.271 11128 11128 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
03-31 16:28:54.271 11128 11128 E Zygote  : accessInfo : 0
03-31 16:28:54.276  3440  3583 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3440 uid:1000
03-31 16:28:54.281  3440  3583 D PointerIcon: setMouseCustomIcon IconType is same.101
03-31 16:28:54.281  3440  3583 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3440 uid:1000
03-31 16:28:54.281  3440  3583 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
03-31 16:28:54.281 11128 11128 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-31 16:28:54.336 11128 11128 D TimaKeyStoreProvider: TimaSignature is unavailable
03-31 16:28:54.336 11128 11128 D ActivityThread: Added TimaKeyStore provider
03-31 16:28:54.346  3440  4724 D PowerManagerService: setKeyboardVisibility: false
03-31 16:28:54.351  3440  3581 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{3cda3c1f u0 d0 Starting com.test.thalitest}
03-31 16:28:54.356  3440  4724 D ActivityManager:  Launching com.test.thalitest, updated priority
03-31 16:28:54.376  3440  4724 I ActivityManager: Skip updateThumbnail for r=ActivityRecord{2cc3ede6 u0 com.test.thalitest/.MainActivity t42}
03-31 16:28:54.391  2860  3024 I SurfaceFlinger: id=12 Removed YUIInstallC (5/9)
03-31 16:28:54.391  2860  3903 I SurfaceFlinger: id=12 Removed YUIInstallC (-2/9)
03-31 16:28:54.416  6534  6534 V ActivityThread: updateVisibility : ActivityRecord{3db8aeed token=android.os.BinderProxy@3842cbb {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
03-31 16:28:54.421  3440  6049 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
03-31 16:28:54.456 11128 11128 D SecWifiDisplayUtil: Metadata value : none
,03-31 16:28:54.506 11128 11128 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,03-31 16:28:54.516 11128 11128 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 5932-5933)
03-31 16:28:54.516 11128 11128 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-31 16:28:54.531 11128 11153 W System.err: remove failed: ENOENT (No such file or directory) : /data/data/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
,03-31 16:28:54.531 11128 11128 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {a5f1d82}
,03-31 16:28:54.531 11128 11128 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-31 16:28:54.531 11128 11128 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,03-31 16:28:54.551 11128 11128 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-31 16:28:54.556 11128 11128 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-31 16:28:54.556 11128 11128 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-31 16:28:54.576 11128 11128 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
03-31 16:28:54.576 11128 11128 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=37 off=50556 len=3379
03-31 16:28:54.576 11128 11128 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:38 off:7638088 len:1165478
,03-31 16:28:54.641 11128 11176 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,03-31 16:28:54.671 11128 11128 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-31 16:28:54.691 11128 11128 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-31 16:28:54.696 11128 11128 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-31 16:28:54.696 11128 11128 D PhoneWindow: *FMB* installDecor flags : -2139027200
,03-31 16:28:54.701 11128 11128 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,03-31 16:28:54.711 11128 11128 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-31 16:28:54.711 11128 11128 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-31 16:28:54.771 11128 11189 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,03-31 16:28:54.781  3440  3965 V WindowManager: Adding window Window{361bfe34 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity} at 3 of 8 (before Window{3cda3c1f u0 d0 Starting com.test.thalitest})
,03-31 16:28:54.791  3440  3901 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-31 16:28:54.791  3440  3901 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-31 16:28:54.791  3440  3901 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-31 16:28:54.791  3440  3440 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,03-31 16:28:54.791  3440  3440 E EnterpriseSharedDevicePolicy: isSharedDeviceEnabled
,03-31 16:28:54.796  3440  3440 I EnterpriseSharedDevicePolicy: isSharedDeviceEnabled in Service
,03-31 16:28:54.801  3440  3440 I EnterpriseSharedDevicePolicy: Get Result: -1
,03-31 16:28:54.801  3440  3440 D PersonaManagerService: getPersonasForUser(): returning null!
03-31 16:28:54.801  3440  3440 I EnterpriseSharedDevicePolicy: status: false
03-31 16:28:54.801  3440  3440 I KnoxTimeoutHandler: Shared devices show user statefalse
,03-31 16:28:54.816 11128 11128 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-31 16:28:54.816 11128 11128 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,03-31 16:28:54.821 11128 11128 D SecWifiDisplayUtil: Metadata value : none
,03-31 16:28:54.831  2860  2860 I SurfaceFlinger: id=15 createSurf (1x1),1 flag=404, NainActivit
,03-31 16:28:54.831  3440  4739 D MultiWindowConverter: dismissGuide() : Before attaching the guide view, mForceDismissGuide : false
,03-31 16:28:54.851  3440  4739 D InputDispatcher: Focus entered window: 11128
,03-31 16:28:54.856  3440  3583 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3440 uid:1000
03-31 16:28:54.856  3440  3583 D PointerIcon: setMouseCustomIcon IconType is same.101
03-31 16:28:54.856  3440  3583 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3440 uid:1000
03-31 16:28:54.856  3440  3583 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
03-31 16:28:54.856 11128 11128 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
03-31 16:28:54.856 11128 11189 I OpenGLRenderer: Initialized EGL, version 1.4
,03-31 16:28:54.856 11128 11189 I OpenGLRenderer: HWUI protection enabled for context ,  &this =0xae430910 ,&mEglDisplay = 1 , &mEglConfig = -1266843376 
,03-31 16:28:54.861 11128 11189 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
03-31 16:28:54.861 11128 11189 D OpenGLRenderer: Enabling debug mode 0
,03-31 16:28:54.861 11128 11189 D mali_winsys: new_window_surface returns 0x3000,  [1440x2560]-format:1
,03-31 16:28:54.861 11128 11128 V ActivityThread: updateVisibility : ActivityRecord{2a03ae8a token=android.os.BinderProxy@81ede2c {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,03-31 16:28:54.931  3440  3966 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-31 16:28:54.936  3440  3583 I ActivityManager: Displayed Component not be shown by security: +541ms (total +1m17s302ms)
,03-31 16:28:54.936  3724  3724 D PanelView: There is/are notification(s) 
03-31 16:28:54.936  3440  3583 W ActivityManager: mDVFSHelper.release()
03-31 16:28:54.936  3440  3583 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2cc3ede6 u0 com.test.thalitest/.MainActivity t42} time:176352
,03-31 16:28:54.936  2860  3903 I SurfaceFlinger: id=14 Removed uhalitest (7/9)
03-31 16:28:54.941  2860  3903 I SurfaceFlinger: id=14 Removed uhalitest (-2/9)
,03-31 16:28:54.966 11128 11128 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
03-31 16:28:54.966 11128 11128 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@81ede2c time:176384
,03-31 16:28:54.991 11128 11128 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 11128
,03-31 16:28:55.121 11128 11128 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-31 16:28:55.201 11128 11193 D jxcore_app_log: JniHelper::setJavaVM(0xb449d200), pthread_self() = -1626347392
,03-31 16:28:55.206 11128 11193 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-31 16:28:55.206 11128 11193 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-31 16:28:55.206 11128 11193 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-31 16:28:55.206 11128 11193 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-31 16:28:55.206 11128 11193 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-31 16:28:55.206 11128 11193 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13c5aaeb added. We now have 1 listener(s)
,03-31 16:28:55.211 11128 11193 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: E0:DB:10:14:E2:C0
,03-31 16:28:55.211 11128 11193 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-31 16:28:55.211 11128 11193 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
03-31 16:28:55.211 11128 11193 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
03-31 16:28:55.211 11128 11153 W System.err: remove failed: ENOENT (No such file or directory) : /data/data/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
03-31 16:28:55.216 11128 11193 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-31 16:28:55.216 11128 11193 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-31 16:28:55.216 11128 11193 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-31 16:28:55.216 11128 11193 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: E0:DB:10:14:E2:C0
03-31 16:28:55.216 11128 11193 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-31 16:28:55.216 11128 11193 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-31 16:28:55.216 11128 11193 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
03-31 16:28:55.216 11128 11193 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-31 16:28:55.216 11128 11193 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-31 16:28:55.216 11128 11193 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-31 16:28:55.216 11128 11193 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-31 16:28:55.216 11128 11193 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@99406 added. We now have 1 listener(s)
03-31 16:28:55.216 11128 11193 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
03-31 16:28:55.221 11128 11193 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
03-31 16:28:55.221 11128 11193 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
03-31 16:28:55.221 11128 11193 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
03-31 16:28:55.221 11128 11193 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-31 16:28:55.221 11128 11193 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
03-31 16:28:55.226 11128 11193 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 16:28:55.226 11128 11193 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is E0:DB:10:14:E2:C0
03-31 16:28:55.231 11128 11193 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 16:28:55.231 11128 11193 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 16:28:55.231 11128 11193 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 16:28:55.231 11128 11193 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 16:28:55.231 11128 11193 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 16:28:55.231 11128 11193 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 16:28:55.231 11128 11193 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 16:28:55.231 11128 11193 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-31 16:28:55.231 11128 11193 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-31 16:28:55.231 11128 11193 D io.jxcore.node.ConnectivityMonitor: start: OK
03-31 16:28:55.231 11128 11193 I io.jxcore.node.LifeCycleMonitor: start: OK
03-31 16:28:55.236 11128 11128 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
03-31 16:28:55.236 11128 11128 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-31 16:28:55.261 11128 11128 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-31 16:28:55.416  3440  6049 D SSRM:n  : SIOP:: AP = 270, PST = 282 (W:14), CUR = 41, LCD = 0
,03-31 16:28:55.681 11128 11200 W jxcore-log: Initializing JXcore engine
03-31 16:28:55.681 11128 11200 W jxcore-log: JXcore engine is ready
,03-31 16:28:55.711  4685  4685 E auditd  : In denial and Property audit_ondenial is set to 1 
,03-31 16:28:55.711  4685  4685 E audit   : type=1400 msg=audit(1459434535.711:196): avc:  denied  { ioctl } for  pid=11200 comm="Thread-1538" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3220 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
03-31 16:28:55.711  3440  3579 D SecurityLogAgent:SEDenialService: Got Modify Event and sending Denial Intent foraudit.log
03-31 16:28:55.711  4685  4685 E audit   :  SEPF_SM-N910C_5.1.1_0038
03-31 16:28:55.711  3440  3579 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.android.server.SEDenialService$AuditFileObserver.onEvent:80 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
03-31 16:28:55.711  4685  4685 E audit   : type=1300 msg=audit(1459434535.711:196): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=a a1=5451 a2=2 a3=971008d8 items=0 ppid=2902 ppcomm=main pid=11200 auid=4294967295 uid=10011 gid=10011 euid=10011 suid=10011 fsuid=10011 egid=10011 sgid=10011 fsgid=10011 ses=4294967295 tty=(none) comm="Thread-1538" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
03-31 16:28:55.711  4685  4685 E audit   : type=1320 msg=audit(1459434535.711:196): 
,03-31 16:28:55.716  3440  3579 D SecurityLogAgent:SEDenialService: audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,03-31 16:28:55.716  3440  3575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 16:28:55.716  3440  3575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 16:28:55.716  3440  3575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 16:28:55.716  3440  3575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 16:28:55.716 11128 11200 W jxcore-log: Starting JXcore engine
,03-31 16:28:55.726 11201 11201 E Zygote  : MountEmulatedStorage()
03-31 16:28:55.726 11201 11201 E Zygote  : v2
03-31 16:28:55.726 11201 11201 I libpersona: KNOX_SDCARD checking this for 1000
03-31 16:28:55.726 11201 11201 I libpersona: KNOX_SDCARD not a persona
,03-31 16:28:55.731 11201 11201 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
,03-31 16:28:55.731  3440  3575 I ActivityManager: Start proc 11201:com.samsung.android.securitylogagent/1000 for broadcast-3 com.samsung.android.securitylogagent/.receivers.SeDenialReceiver
,03-31 16:28:55.731 11201 11201 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
,03-31 16:28:55.736 11201 11201 E Zygote  : accessInfo : 0
,03-31 16:28:55.736 11201 11201 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-31 16:28:55.751 11201 11201 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-31 16:28:55.756 11201 11201 D ActivityThread: Added TimaKeyStore provider
,03-31 16:28:55.761  3440  3828 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{90e2cb8 u0 samsung.intent.action.knox.DENIAL_NOTIFICATION} DELIVERED for app ProcessRecord{3af94a91 11201:com.samsung.android.securitylogagent/1000}
,03-31 16:28:55.766 11128 11200 W jxcore-log: Platform android
03-31 16:28:55.766 11128 11200 W jxcore-log: 
03-31 16:28:55.766 11128 11200 W jxcore-log: Process ARCH arm
03-31 16:28:55.766 11128 11200 W jxcore-log: 
,03-31 16:28:55.776 11201 11201 D SecurityLogAgent:  SeDenialReceiver : Intent received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,03-31 16:28:55.776 11201 11201 D SecurityLogAgent:  SeDenialReceiver : File path = null
,03-31 16:28:55.781  3440  4421 I ActivityManager: Killing 10186:com.sec.android.app.myfiles/u0a53 (adj 15): emptyCount ##31
,03-31 16:28:55.861 11128 11200 I jxcore-log: JXcore Cordova bridge is ready!
03-31 16:28:55.861 11128 11200 I jxcore-log: 
03-31 16:28:55.861 11128 11200 W jxcore-log: JXcore engine is started
,03-31 16:28:55.866 11128 11193 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-31 16:28:55.871 11128 11128 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-31 16:28:57.206  3440  3618 V AlarmManager: waitForAlarm result :4
,03-31 16:28:57.206  3440  3440 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
,03-31 16:28:57.211  3440  3440 V AlarmManagerEXT: <AppSync3 Whitelist>
03-31 16:28:57.211  3440  3440 V AlarmManagerEXT: (AppSync) ### 0 added ###
,03-31 16:28:57.211  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
03-31 16:28:57.211  3724  3724 I PERF    : received broadcast android.intent.action.TIME_TICK
03-31 16:28:57.211  3724  3724 D KeyguardUpdateMonitor: handleTimeUpdate
,03-31 16:28:57.216  3724  3724 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,03-31 16:28:57.216  3724  3724 D SecKeyguardClockView: HomeTimezone(): 1
,03-31 16:28:57.221  3724  3724 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
03-31 16:28:57.221  3724  3724 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,03-31 16:28:57.221  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,03-31 16:28:57.226  3440  3690 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/42_task.xml.bak
,03-31 16:28:57.246  3724  3724 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 16:28:57.246  3724  3724 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 16:28:57.251  3724  3724 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 16:28:57.251  3724  3724 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 16:28:57.251  3724  3724 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
03-31 16:28:57.251  3724  3724 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 16:28:57.256  3724  3724 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 16:28:59.991  3440  3618 V AlarmManager: waitForAlarm result :8
,03-31 16:29:01.591 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 16:29:01.591 11128 11200 I jxcore-log: 
,03-31 16:29:01.596 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 16:29:01.596 11128 11200 I jxcore-log: 
,03-31 16:29:01.596 11128 11200 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 16:29:01.596 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 16:29:01.596 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 16:29:01.596 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 16:29:01.596 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 16:29:01.596 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 16:29:01.596 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 16:29:01.596 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 16:29:01.596 11128 11200 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 16:29:01.601 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 16:29:01.601 11128 11200 I jxcore-log: 
,03-31 16:29:01.601 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 16:29:01.601 11128 11200 I jxcore-log: 
,03-31 16:29:01.926 11128 11200 I jxcore-log: Unit Test app is loaded
03-31 16:29:01.926 11128 11200 I jxcore-log: 
,03-31 16:29:01.931 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 16:29:01.931 11128 11200 I jxcore-log: 
,03-31 16:29:01.936 11128 11128 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
03-31 16:29:01.936 11128 11200 I jxcore-log: My device name is: samsung-SM-N910C
03-31 16:29:01.936 11128 11200 I jxcore-log: 
,03-31 16:29:01.936 11128 11200 I jxcore-log: WARN testUtils: myNameCallback not set!
03-31 16:29:01.936 11128 11200 I jxcore-log: 
,03-31 16:29:03.561  3440  3965 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 16:29:03.561  3440  3965 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 16:29:03.561  3440  3965 D BatteryService: online:4, current avg:-85, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-212
03-31 16:29:03.561  3440  3965 D BatteryService: stay LED for fully charged
03-31 16:29:03.561  3440  3440 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 16:29:03.561  3440  3440 I MotionRecognitionService: Plugged
03-31 16:29:03.561  3440  3440 D MotionRecognitionService:   cableConnection= 1
03-31 16:29:03.561  3440  3440 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 16:29:03.561  3440  3440 D MotionRecognitionService: skip setTransmitPower. 
03-31 16:29:03.561  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 16:29:03.561  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 16:29:03.561  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 16:29:03.566  5838  5838 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 16:29:03.566  5838  5954 D HeadsetStateMachine: Disconnected process message: 10
,03-31 16:29:03.581  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 16:29:03.581  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 16:29:03.581  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 16:29:03.581  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 16:29:04.266  3440  3591 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,03-31 16:29:04.276  3440  3591 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,03-31 16:29:04.311 11128 11200 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
03-31 16:29:04.311 11128 11200 I jxcore-log: 
,03-31 16:29:04.521 11128 11200 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
03-31 16:29:04.521 11128 11200 I jxcore-log: 
,03-31 16:29:04.531 11128 11200 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
03-31 16:29:04.531 11128 11200 I jxcore-log: 
,03-31 16:29:04.531 11128 11200 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
03-31 16:29:04.531 11128 11200 I jxcore-log: 
,03-31 16:29:04.551 11128 11200 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
03-31 16:29:04.551 11128 11200 I jxcore-log: 
,03-31 16:29:04.561 11128 11200 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
03-31 16:29:04.561 11128 11200 I jxcore-log: 
,03-31 16:29:04.561 11128 11200 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
03-31 16:29:04.561 11128 11200 I jxcore-log: 
,03-31 16:29:04.711  3440  3618 V AlarmManager: waitForAlarm result :4
,03-31 16:29:04.711  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
03-31 16:29:04.711  3724  3724 I PERF    : received broadcast android.intent.action.TIME_TICK
03-31 16:29:04.711  3724  3724 D KeyguardUpdateMonitor: handleTimeUpdate
,03-31 16:29:04.716  3724  3724 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,03-31 16:29:04.721  3724  3724 D SecKeyguardClockView: HomeTimezone(): 1
,03-31 16:29:04.726  3724  3724 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 16:29:04.726  3724  3724 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,03-31 16:29:04.726  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.TIME_TICK
03-31 16:29:04.736  3724  3724 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
03-31 16:29:04.736  3724  3724 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 16:29:04.751  3724  3724 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 16:29:04.751  3724  3724 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 16:29:04.756  3724  3724 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 16:29:04.756  3724  3724 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 16:29:04.761  3724  3724 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 16:29:05.421  3440  6049 D SSRM:n  : SIOP:: AP = 300, PST = 280 (W:10), CUR = -85, LCD = 0
,03-31 16:29:05.791 11128 11200 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
03-31 16:29:05.791 11128 11200 I jxcore-log: 
,03-31 16:29:05.796 11128 11200 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
03-31 16:29:05.796 11128 11200 I jxcore-log: 
,03-31 16:29:05.801 11128 11200 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
03-31 16:29:05.801 11128 11200 I jxcore-log: 
,03-31 16:29:05.956 11128 11200 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
03-31 16:29:05.956 11128 11200 I jxcore-log: 
03-31 16:29:05.996 11128 11200 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
03-31 16:29:05.996 11128 11200 I jxcore-log: 
03-31 16:29:06.026 11128 11200 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
03-31 16:29:06.026 11128 11200 I jxcore-log: 
03-31 16:29:06.031 11128 11200 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
03-31 16:29:06.031 11128 11200 I jxcore-log: 
03-31 16:29:06.036 11128 11200 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
03-31 16:29:06.036 11128 11200 I jxcore-log: 
03-31 16:29:06.041 11128 11200 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
03-31 16:29:06.041 11128 11200 I jxcore-log: 
03-31 16:29:06.041 11128 11200 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
03-31 16:29:06.041 11128 11200 I jxcore-log: 
03-31 16:29:06.051 11128 11200 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
03-31 16:29:06.051 11128 11200 I jxcore-log: 
03-31 16:29:06.061 11128 11200 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
03-31 16:29:06.061 11128 11200 I jxcore-log: 
03-31 16:29:06.111 11128 11200 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
03-31 16:29:06.111 11128 11200 I jxcore-log: 
03-31 16:29:06.116 11128 11200 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
03-31 16:29:06.116 11128 11200 I jxcore-log: 
03-31 16:29:06.131 11128 11200 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
03-31 16:29:06.131 11128 11200 I jxcore-log: 
03-31 16:29:06.136 11128 11200 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
03-31 16:29:06.136 11128 11200 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
03-31 16:29:06.136 11128 11200 I jxcore-log: 
,03-31 16:29:08.726  3440  6080 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-31 16:29:11.351  3440  3862 E Watchdog: !@Sync 6 [03-31 16:29:11.357],
,03-31 16:29:13.701  3440  4739 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 16:29:13.706  3440  4739 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 16:29:13.706  3440  4739 D BatteryService: online:4, current avg:-30, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:59
,03-31 16:29:13.706  3440  3440 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 16:29:13.716  3440  3440 I MotionRecognitionService: Plugged
03-31 16:29:13.716  3440  3440 D MotionRecognitionService:   cableConnection= 1,
03-31 16:29:13.716  3440  3440 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
03-31 16:29:13.716  3440  3440 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 16:29:13.716  3440  4739 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 14ms
,03-31 16:29:13.716  3440  4739 D BatteryService: stay LED for fully charged
,03-31 16:29:13.731  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-31 16:29:13.731  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,03-31 16:29:13.731  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-31 16:29:13.751  5838  5838 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 16:29:13.751  5838  5954 D HeadsetStateMachine: Disconnected process message: 10
,03-31 16:29:13.761  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 16:29:13.761  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 16:29:13.761  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 16:29:13.761  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 16:29:14.521  2895  4732 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-31 16:29:15.451  3440  6049 D SSRM:n  : SIOP:: AP = 290, PST = 276 (W:10), CUR = -30, LCD = 0
,03-31 16:29:23.841  3440  3901 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 16:29:23.841  3440  3901 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 16:29:23.841  3440  3901 D BatteryService: online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:54
,03-31 16:29:23.841  3440  3440 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 16:29:23.846  3440  3901 D BatteryService: stay LED for fully charged
,03-31 16:29:23.851  3440  3440 I MotionRecognitionService: Plugged,
03-31 16:29:23.851  3440  3440 D MotionRecognitionService:   cableConnection= 1
,03-31 16:29:23.851  3440  3440 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
03-31 16:29:23.851  3440  3440 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 16:29:23.861  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-31 16:29:23.861  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 16:29:23.861  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-31 16:29:23.886  5838  5838 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 16:29:23.886  5838  5954 D HeadsetStateMachine: Disconnected process message: 10
,03-31 16:29:23.891  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 16:29:23.896  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 16:29:23.896  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 16:29:23.896  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 16:29:24.946  3440  3585 I PowerManagerService: [PWL] Off : 140s ago
,03-31 16:29:25.481  3440  6049 D SSRM:n  : SIOP:: AP = 280, PST = 276 (W:10), CUR = 17, LCD = 0
,03-31 16:29:27.751 11128 11200 I jxcore-log: TAP version 13
03-31 16:29:27.751 11128 11200 I jxcore-log: 
,03-31 16:29:27.751 11128 11200 I jxcore-log: # setup
03-31 16:29:27.751 11128 11200 I jxcore-log: 
,03-31 16:29:27.926 11128 11200 I jxcore-log: # 1. calling createNativeListener directly rejects
03-31 16:29:27.926 11128 11200 I jxcore-log: 
,03-31 16:29:28.186 11128 11200 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 16:29:28.186 11128 11200 I jxcore-log: 
,03-31 16:29:28.196 11128 11200 I jxcore-log: DEBUG createNativeListener: listening 50489
03-31 16:29:28.196 11128 11200 I jxcore-log: 
,03-31 16:29:28.206 11128 11200 I jxcore-log: ok 1 Should throw
03-31 16:29:28.206 11128 11200 I jxcore-log: 
,03-31 16:29:28.211 11128 11200 I jxcore-log: # teardown
03-31 16:29:28.211 11128 11200 I jxcore-log: 
,03-31 16:29:28.356 11128 11200 I jxcore-log: # setup
03-31 16:29:28.356 11128 11200 I jxcore-log: 
,03-31 16:29:28.506 11128 11200 I jxcore-log: # 2. emits incomingConnectionState
03-31 16:29:28.506 11128 11200 I jxcore-log: 
,03-31 16:29:28.656 11128 11200 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 16:29:28.656 11128 11200 I jxcore-log: 
,03-31 16:29:28.666 11128 11200 I jxcore-log: DEBUG createNativeListener: listening 58286
03-31 16:29:28.666 11128 11200 I jxcore-log: 
,03-31 16:29:28.676 11128 11200 I jxcore-log: DEBUG createNativeListener: new incoming socket,
03-31 16:29:28.676 11128 11200 I jxcore-log: 
,03-31 16:29:28.686 11128 11200 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 16:29:28.686 11128 11200 I jxcore-log: 
,03-31 16:29:28.696 11128 11200 I jxcore-log: DEBUG createNativeListener: new mux
03-31 16:29:28.696 11128 11200 I jxcore-log: 
,03-31 16:29:28.711 11128 11200 I jxcore-log: ok 2 initial connection state should be CONNECTED
03-31 16:29:28.711 11128 11200 I jxcore-log: 
,03-31 16:29:28.731  3440  6080 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-31 16:29:28.736 11128 11200 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 16:29:28.736 11128 11200 I jxcore-log: 
,03-31 16:29:28.736 11128 11200 I jxcore-log: ok 3 final connection state should be DISCONNECTED
03-31 16:29:28.736 11128 11200 I jxcore-log: 
,03-31 16:29:28.751 11128 11200 I jxcore-log: # teardown
03-31 16:29:28.751 11128 11200 I jxcore-log: 
,03-31 16:29:28.866 11128 11200 I jxcore-log: # setup
03-31 16:29:28.866 11128 11200 I jxcore-log: 
,03-31 16:29:29.241 11128 11200 I jxcore-log: # 3. emits routerPortConnectionFailed
03-31 16:29:29.241 11128 11200 I jxcore-log: 
,03-31 16:29:29.416 11128 11200 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 16:29:29.416 11128 11200 I jxcore-log: 
,03-31 16:29:29.416 11128 11200 I jxcore-log: DEBUG createNativeListener: listening 57449
03-31 16:29:29.416 11128 11200 I jxcore-log: 
,03-31 16:29:29.426 11128 11200 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 16:29:29.426 11128 11200 I jxcore-log: 
,03-31 16:29:29.426 11128 11200 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 16:29:29.426 11128 11200 I jxcore-log: 
,03-31 16:29:29.431 11128 11200 I jxcore-log: DEBUG createNativeListener: new mux
03-31 16:29:29.431 11128 11200 I jxcore-log: 
,03-31 16:29:29.466 11128 11200 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:29.466 11128 11200 I jxcore-log: 
,03-31 16:29:29.471 11128 11200 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:29.471 11128 11200 I jxcore-log: 
,03-31 16:29:29.476 11128 11200 I jxcore-log: DEBUG createNativeListener: 
03-31 16:29:29.476 11128 11200 I jxcore-log: 
,03-31 16:29:29.481 11128 11200 I jxcore-log: ok 4 tried to connect to right port
03-31 16:29:29.481 11128 11200 I jxcore-log: 
,03-31 16:29:29.481 11128 11200 I jxcore-log: ok 5 failed due to refused connection
03-31 16:29:29.481 11128 11200 I jxcore-log: 
,03-31 16:29:29.481 11128 11200 I jxcore-log: ok 6 routerPortConnectionFailed is emitted
03-31 16:29:29.481 11128 11200 I jxcore-log: 
,03-31 16:29:29.486 11128 11200 I jxcore-log: # teardown
03-31 16:29:29.486 11128 11200 I jxcore-log: 
,03-31 16:29:29.491 11128 11200 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:29.491 11128 11200 I jxcore-log: 
,03-31 16:29:29.626 11128 11200 I jxcore-log: DEBUG createNativeListener: mux close
03-31 16:29:29.626 11128 11200 I jxcore-log: 
,03-31 16:29:29.636 11128 11200 I jxcore-log: # setup
03-31 16:29:29.636 11128 11200 I jxcore-log: 
,03-31 16:29:29.636 11128 11200 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 16:29:29.636 11128 11200 I jxcore-log: 
,03-31 16:29:29.831 11128 11200 I jxcore-log: # 4. native server connections all up
03-31 16:29:29.831 11128 11200 I jxcore-log: 
,03-31 16:29:30.026 11128 11200 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 16:29:30.026 11128 11200 I jxcore-log: 
,03-31 16:29:30.036 11128 11200 I jxcore-log: DEBUG createNativeListener: listening 33644
03-31 16:29:30.036 11128 11200 I jxcore-log: 
,03-31 16:29:30.051 11128 11200 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 16:29:30.051 11128 11200 I jxcore-log: 
,03-31 16:29:30.051 11128 11200 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 16:29:30.051 11128 11200 I jxcore-log: 
,03-31 16:29:30.056 11128 11200 I jxcore-log: DEBUG createNativeListener: new mux
03-31 16:29:30.056 11128 11200 I jxcore-log: 
,03-31 16:29:30.091 11128 11200 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:30.091 11128 11200 I jxcore-log: 
,03-31 16:29:30.096 11128 11200 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:30.096 11128 11200 I jxcore-log: 
,03-31 16:29:30.096 11128 11200 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:30.096 11128 11200 I jxcore-log: 
,03-31 16:29:30.106 11128 11200 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:30.106 11128 11200 I jxcore-log: 
,03-31 16:29:30.146 11128 11200 I jxcore-log: ok 7 Send/recvd #1 should be equal length
03-31 16:29:30.146 11128 11200 I jxcore-log: 
,03-31 16:29:30.146 11128 11200 I jxcore-log: ok 8 Send/recvd #1 should be same
03-31 16:29:30.146 11128 11200 I jxcore-log: 
,03-31 16:29:30.151 11128 11200 I jxcore-log: ok 9 Send/recvd #2 should be equal length
03-31 16:29:30.151 11128 11200 I jxcore-log: 
,03-31 16:29:30.151 11128 11200 I jxcore-log: ok 10 Send/recvd #2 should be same
03-31 16:29:30.151 11128 11200 I jxcore-log: 
,03-31 16:29:30.156 11128 11200 I jxcore-log: ok 11 Should be exactly 2 client sockets
03-31 16:29:30.156 11128 11200 I jxcore-log: 
,03-31 16:29:30.166 11128 11200 I jxcore-log: # teardown
03-31 16:29:30.166 11128 11200 I jxcore-log: 
,03-31 16:29:30.381 11128 11200 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:30.381 11128 11200 I jxcore-log: 
,03-31 16:29:30.391 11128 11200 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:30.391 11128 11200 I jxcore-log: 
,03-31 16:29:30.396 11128 11200 I jxcore-log: DEBUG createNativeListener: mux close
03-31 16:29:30.396 11128 11200 I jxcore-log: 
,03-31 16:29:30.401 11128 11200 I jxcore-log: # setup
03-31 16:29:30.401 11128 11200 I jxcore-log: 
,03-31 16:29:30.406 11128 11200 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 16:29:30.406 11128 11200 I jxcore-log: 
,03-31 16:29:30.621 11128 11200 I jxcore-log: # 5. native server - closing incoming stream cleans outgoing socket
03-31 16:29:30.621 11128 11200 I jxcore-log: 
,03-31 16:29:30.836 11128 11200 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 16:29:30.836 11128 11200 I jxcore-log: 
,03-31 16:29:30.841 11128 11200 I jxcore-log: DEBUG createNativeListener: listening 60688
03-31 16:29:30.841 11128 11200 I jxcore-log: 
,03-31 16:29:30.851 11128 11200 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 16:29:30.851 11128 11200 I jxcore-log: 
,03-31 16:29:30.856 11128 11200 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 16:29:30.856 11128 11200 I jxcore-log: 
,03-31 16:29:30.856 11128 11200 I jxcore-log: DEBUG createNativeListener: new mux
03-31 16:29:30.856 11128 11200 I jxcore-log: 
,03-31 16:29:30.871 11128 11200 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:30.871 11128 11200 I jxcore-log: 
,03-31 16:29:30.876 11128 11200 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:30.876 11128 11200 I jxcore-log: 
,03-31 16:29:30.891 11128 11200 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:30.891 11128 11200 I jxcore-log: 
,03-31 16:29:30.911 11128 11200 I jxcore-log: ok 12 socket shouldn't close until after stream
03-31 16:29:30.911 11128 11200 I jxcore-log: 
,03-31 16:29:30.916 11128 11200 I jxcore-log: ok 13 incoming remains open
03-31 16:29:30.916 11128 11200 I jxcore-log: 
,03-31 16:29:30.921 11128 11200 I jxcore-log: # teardown
03-31 16:29:30.921 11128 11200 I jxcore-log: 
,03-31 16:29:31.126 11128 11200 I jxcore-log: DEBUG createNativeListener: mux close
03-31 16:29:31.126 11128 11200 I jxcore-log: 
,03-31 16:29:31.136 11128 11200 I jxcore-log: # setup
03-31 16:29:31.136 11128 11200 I jxcore-log: 
,03-31 16:29:31.141 11128 11200 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 16:29:31.141 11128 11200 I jxcore-log: 
,03-31 16:29:31.701 11128 11200 I jxcore-log: # 6. native server - closing incoming connection cleans outgoing socket
03-31 16:29:31.701 11128 11200 I jxcore-log: 
,03-31 16:29:32.356 11128 11200 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 16:29:32.356 11128 11200 I jxcore-log: 
,03-31 16:29:32.361 11128 11200 I jxcore-log: DEBUG createNativeListener: listening 52707
03-31 16:29:32.361 11128 11200 I jxcore-log: 
,03-31 16:29:32.371 11128 11200 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 16:29:32.371 11128 11200 I jxcore-log: 
,03-31 16:29:32.376 11128 11200 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 16:29:32.376 11128 11200 I jxcore-log: 
,03-31 16:29:32.376 11128 11200 I jxcore-log: DEBUG createNativeListener: new mux
03-31 16:29:32.376 11128 11200 I jxcore-log: 
,03-31 16:29:32.391 11128 11200 I jxcore-log: ok 14 we should not have gotten an error
03-31 16:29:32.391 11128 11200 I jxcore-log: 
,03-31 16:29:32.396 11128 11200 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:32.396 11128 11200 I jxcore-log: 
,03-31 16:29:32.406 11128 11200 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:32.406 11128 11200 I jxcore-log: 
,03-31 16:29:32.416 11128 11200 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:32.416 11128 11200 I jxcore-log: 
,03-31 16:29:32.421 11128 11200 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 16:29:32.421 11128 11200 I jxcore-log: 
,03-31 16:29:32.431 11128 11200 I jxcore-log: ok 15 socket shouldn't close until after incoming
03-31 16:29:32.431 11128 11200 I jxcore-log: 
,03-31 16:29:32.436 11128 11200 I jxcore-log: ok 16 incoming is cleaned up
03-31 16:29:32.436 11128 11200 I jxcore-log: 
,03-31 16:29:32.441 11128 11200 I jxcore-log: # teardown
03-31 16:29:32.441 11128 11200 I jxcore-log: 
,03-31 16:29:32.831 11128 11200 I jxcore-log: # setup
03-31 16:29:32.831 11128 11200 I jxcore-log: 
,03-31 16:29:33.676 11128 11200 I jxcore-log: # 7. native server - closing outgoing socket cleans associated mux stream
03-31 16:29:33.676 11128 11200 I jxcore-log: 
,03-31 16:29:33.976  3440  4064 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 16:29:33.976  3440  4064 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 16:29:33.976  3440  4064 D BatteryService: online:4, current avg:35, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:33
,03-31 16:29:33.976  3440  3440 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 16:29:33.986  3440  4064 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 11ms
03-31 16:29:33.986  3440  4064 D BatteryService: stay LED for fully charged
,03-31 16:29:33.986  3440  3440 I MotionRecognitionService: Plugged
03-31 16:29:33.986  3440  3440 D MotionRecognitionService:   cableConnection= 1,
03-31 16:29:33.986  3440  3440 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-31 16:29:33.986  3440  3440 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 16:29:34.001  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 16:29:34.001  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-31 16:29:34.001  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-31 16:29:34.021  5838  5838 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 16:29:34.021  5838  5954 D HeadsetStateMachine: Disconnected process message: 10
,03-31 16:29:34.031  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 16:29:34.031  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 16:29:34.031  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 16:29:34.031  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 16:29:34.456 11128 11200 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 16:29:34.456 11128 11200 I jxcore-log: 
,03-31 16:29:34.461 11128 11200 I jxcore-log: DEBUG createNativeListener: listening 34290
03-31 16:29:34.461 11128 11200 I jxcore-log: 
,03-31 16:29:34.471 11128 11200 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 16:29:34.471 11128 11200 I jxcore-log: 
,03-31 16:29:34.476 11128 11200 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 16:29:34.476 11128 11200 I jxcore-log: 
,03-31 16:29:34.476 11128 11200 I jxcore-log: DEBUG createNativeListener: new mux
03-31 16:29:34.476 11128 11200 I jxcore-log: 
,03-31 16:29:34.496 11128 11200 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:34.496 11128 11200 I jxcore-log: 
,03-31 16:29:34.501 11128 11200 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:34.501 11128 11200 I jxcore-log: 
,03-31 16:29:34.516 11128 11200 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:34.516 11128 11200 I jxcore-log: 
,03-31 16:29:34.526 11128 11200 I jxcore-log: ok 17 stream was closed
03-31 16:29:34.526 11128 11200 I jxcore-log: 
,03-31 16:29:34.531 11128 11200 I jxcore-log: ok 18 incoming should survive
03-31 16:29:34.531 11128 11200 I jxcore-log: 
,03-31 16:29:34.531 11128 11200 I jxcore-log: ok 19 mux should have no streams
03-31 16:29:34.531 11128 11200 I jxcore-log: 
,03-31 16:29:34.536 11128 11200 I jxcore-log: # teardown
03-31 16:29:34.536 11128 11200 I jxcore-log: 
,03-31 16:29:35.506  3440  6049 D SSRM:n  : SIOP:: AP = 280, PST = 277 (W:10), CUR = 35, LCD = 0
,03-31 16:29:35.591 11128 11200 I jxcore-log: DEBUG createNativeListener: mux close
03-31 16:29:35.591 11128 11200 I jxcore-log: 
,03-31 16:29:35.606 11128 11200 I jxcore-log: # setup
03-31 16:29:35.606 11128 11200 I jxcore-log: 
,03-31 16:29:35.606 11128 11200 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 16:29:35.606 11128 11200 I jxcore-log: 
,03-31 16:29:36.616 11128 11200 I jxcore-log: # 8. native server - closing the whole server cleans everything up
03-31 16:29:36.616 11128 11200 I jxcore-log: 
,03-31 16:29:38.166 11128 11200 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 16:29:38.166 11128 11200 I jxcore-log: 
,03-31 16:29:38.176 11128 11200 I jxcore-log: DEBUG createNativeListener: listening 50617
03-31 16:29:38.176 11128 11200 I jxcore-log: 
,03-31 16:29:38.186 11128 11200 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 16:29:38.186 11128 11200 I jxcore-log: 
,03-31 16:29:38.191 11128 11200 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 16:29:38.191 11128 11200 I jxcore-log: 
,03-31 16:29:38.191 11128 11200 I jxcore-log: DEBUG createNativeListener: new mux
03-31 16:29:38.191 11128 11200 I jxcore-log: 
,03-31 16:29:38.201 11128 11200 I jxcore-log: ok 20 we should not have gotten an error
03-31 16:29:38.201 11128 11200 I jxcore-log: 
,03-31 16:29:38.211 11128 11200 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:38.211 11128 11200 I jxcore-log: 
,03-31 16:29:38.216 11128 11200 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:38.216 11128 11200 I jxcore-log: 
,03-31 16:29:38.231 11128 11200 I jxcore-log: ok 21 Buffers are identical
03-31 16:29:38.231 11128 11200 I jxcore-log: 
,03-31 16:29:38.236 11128 11200 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:38.236 11128 11200 I jxcore-log: 
,03-31 16:29:38.241 11128 11200 I jxcore-log: DEBUG createNativeListener: mux close
03-31 16:29:38.241 11128 11200 I jxcore-log: 
,03-31 16:29:38.246 11128 11200 I jxcore-log: ok 22 native server is nulled out
03-31 16:29:38.246 11128 11200 I jxcore-log: 
,03-31 16:29:38.246 11128 11200 I jxcore-log: ok 23 native server should be closed
03-31 16:29:38.246 11128 11200 I jxcore-log: 
,03-31 16:29:38.251 11128 11200 I jxcore-log: ok 24 incoming has been removed
03-31 16:29:38.251 11128 11200 I jxcore-log: 
,03-31 16:29:38.251 11128 11200 I jxcore-log: ok 25 Incoming should be done
03-31 16:29:38.251 11128 11200 I jxcore-log: 
,03-31 16:29:38.251 11128 11200 I jxcore-log: ok 26 The mux object should be closed
03-31 16:29:38.251 11128 11200 I jxcore-log: 
,03-31 16:29:38.251 11128 11200 I jxcore-log: ok 27 The mux stream should be closed
03-31 16:29:38.251 11128 11200 I jxcore-log: 
,03-31 16:29:38.256 11128 11200 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 16:29:38.256 11128 11200 I jxcore-log: 
,03-31 16:29:38.281 11128 11200 I jxcore-log: # teardown
03-31 16:29:38.281 11128 11200 I jxcore-log: 
,03-31 16:29:39.321 11128 11200 I jxcore-log: # setup
03-31 16:29:39.321 11128 11200 I jxcore-log: 
,03-31 16:29:40.146 11128 11200 I jxcore-log: # 9. native server - we can get a ton of connections and data through and still clean up the server completely
03-31 16:29:40.146 11128 11200 I jxcore-log: 
,03-31 16:29:41.366  3440  3862 E Watchdog: !@Sync 7 [03-31 16:29:41.371]
,03-31 16:29:43.291 11128 11200 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 16:29:43.291 11128 11200 I jxcore-log: 
,03-31 16:29:43.296 11128 11200 I jxcore-log: DEBUG createNativeListener: listening 60362
03-31 16:29:43.296 11128 11200 I jxcore-log: 
,03-31 16:29:43.326 11128 11200 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 16:29:43.326 11128 11200 I jxcore-log: 
,03-31 16:29:43.331 11128 11200 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 16:29:43.331 11128 11200 I jxcore-log: 
,03-31 16:29:43.331 11128 11200 I jxcore-log: DEBUG createNativeListener: new mux
03-31 16:29:43.331 11128 11200 I jxcore-log: 
,03-31 16:29:43.336 11128 11200 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 16:29:43.336 11128 11200 I jxcore-log: 
,03-31 16:29:43.336 11128 11200 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 16:29:43.336 11128 11200 I jxcore-log: 
,03-31 16:29:43.341 11128 11200 I jxcore-log: DEBUG createNativeListener: new mux
03-31 16:29:43.341 11128 11200 I jxcore-log: 
,03-31 16:29:43.346 11128 11200 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 16:29:43.346 11128 11200 I jxcore-log: 
,03-31 16:29:43.346 11128 11200 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 16:29:43.346 11128 11200 I jxcore-log: 
,03-31 16:29:43.351 11128 11200 I jxcore-log: DEBUG createNativeListener: new mux
03-31 16:29:43.351 11128 11200 I jxcore-log: 
,03-31 16:29:43.356 11128 11200 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 16:29:43.356 11128 11200 I jxcore-log: 
,03-31 16:29:43.356 11128 11200 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 16:29:43.356 11128 11200 I jxcore-log: 
,03-31 16:29:43.356 11128 11200 I jxcore-log: DEBUG createNativeListener: new mux
03-31 16:29:43.356 11128 11200 I jxcore-log: 
,03-31 16:29:43.361 11128 11200 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 16:29:43.361 11128 11200 I jxcore-log: 
,03-31 16:29:43.361 11128 11200 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 16:29:43.361 11128 11200 I jxcore-log: 
,03-31 16:29:43.366 11128 11200 I jxcore-log: DEBUG createNativeListener: new mux
03-31 16:29:43.366 11128 11200 I jxcore-log: 
,03-31 16:29:43.366 11128 11200 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 16:29:43.366 11128 11200 I jxcore-log: 
,03-31 16:29:43.366 11128 11200 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 16:29:43.366 11128 11200 I jxcore-log: 
,03-31 16:29:43.371 11128 11200 I jxcore-log: DEBUG createNativeListener: new mux
03-31 16:29:43.371 11128 11200 I jxcore-log: 
,03-31 16:29:43.371 11128 11200 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 16:29:43.371 11128 11200 I jxcore-log: 
,03-31 16:29:43.376 11128 11200 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 16:29:43.376 11128 11200 I jxcore-log: 
,03-31 16:29:43.376 11128 11200 I jxcore-log: DEBUG createNativeListener: new mux
03-31 16:29:43.376 11128 11200 I jxcore-log: 
,03-31 16:29:43.381 11128 11200 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 16:29:43.381 11128 11200 I jxcore-log: 
,03-31 16:29:43.381 11128 11200 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 16:29:43.381 11128 11200 I jxcore-log: 
,03-31 16:29:43.381 11128 11200 I jxcore-log: DEBUG createNativeListener: new mux
03-31 16:29:43.381 11128 11200 I jxcore-log: 
,03-31 16:29:43.386 11128 11200 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 16:29:43.386 11128 11200 I jxcore-log: 
,03-31 16:29:43.386 11128 11200 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 16:29:43.386 11128 11200 I jxcore-log: 
,03-31 16:29:43.386 11128 11200 I jxcore-log: DEBUG createNativeListener: new mux
03-31 16:29:43.386 11128 11200 I jxcore-log: 
,03-31 16:29:43.391 11128 11200 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 16:29:43.391 11128 11200 I jxcore-log: 
,03-31 16:29:43.391 11128 11200 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 16:29:43.391 11128 11200 I jxcore-log: 
,03-31 16:29:43.391 11128 11200 I jxcore-log: DEBUG createNativeListener: new mux
03-31 16:29:43.391 11128 11200 I jxcore-log: 
,03-31 16:29:43.491 11128 11200 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:43.491 11128 11200 I jxcore-log: 
,03-31 16:29:43.496 11128 11200 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:43.496 11128 11200 I jxcore-log: 
,03-31 16:29:43.496 11128 11200 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:43.496 11128 11200 I jxcore-log: 
,03-31 16:29:43.501 11128 11200 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:43.501 11128 11200 I jxcore-log: 
,03-31 16:29:43.501 11128 11200 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:43.501 11128 11200 I jxcore-log: 
,03-31 16:29:43.501 11128 11200 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:43.501 11128 11200 I jxcore-log: 
,03-31 16:29:43.501 11128 11200 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:43.501 11128 11200 I jxcore-log: 
,03-31 16:29:43.506 11128 11200 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:43.506 11128 11200 I jxcore-log: 
,03-31 16:29:43.506 11128 11200 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:43.506 11128 11200 I jxcore-log: 
,03-31 16:29:43.506 11128 11200 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:43.506 11128 11200 I jxcore-log: 
,03-31 16:29:43.511 11128 11200 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:43.511 11128 11200 I jxcore-log: 
,03-31 16:29:43.511 11128 11200 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:43.511 11128 11200 I jxcore-log: 
,03-31 16:29:43.511 11128 11200 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:43.511 11128 11200 I jxcore-log: 
,03-31 16:29:43.511 11128 11200 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:43.511 11128 11200 I jxcore-log: 
,03-31 16:29:43.511 11128 11200 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:43.511 11128 11200 I jxcore-log: 
,03-31 16:29:43.516 11128 11200 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:43.516 11128 11200 I jxcore-log: 
,03-31 16:29:43.516 11128 11200 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:43.516 11128 11200 I jxcore-log: 
,03-31 16:29:43.516 11128 11200 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:43.516 11128 11200 I jxcore-log: 
,03-31 16:29:43.521 11128 11200 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:43.521 11128 11200 I jxcore-log: 
,03-31 16:29:43.521 11128 11200 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:43.521 11128 11200 I jxcore-log: 
,03-31 16:29:43.526 11128 11200 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:43.526 11128 11200 I jxcore-log: 
,03-31 16:29:43.526 11128 11200 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:43.526 11128 11200 I jxcore-log: 
,03-31 16:29:43.526 11128 11200 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:43.526 11128 11200 I jxcore-log: 
,03-31 16:29:43.526 11128 11200 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:43.526 11128 11200 I jxcore-log: 
,03-31 16:29:43.531 11128 11200 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:43.531 11128 11200 I jxcore-log: 
,03-31 16:29:43.531 11128 11200 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:43.531 11128 11200 I jxcore-log: 
,03-31 16:29:43.531 11128 11200 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:43.531 11128 11200 I jxcore-log: 
,03-31 16:29:43.531 11128 11200 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:43.531 11128 11200 I jxcore-log: 
,03-31 16:29:43.536 11128 11200 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:43.536 11128 11200 I jxcore-log: 
,03-31 16:29:43.536 11128 11200 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:43.536 11128 11200 I jxcore-log: 
,03-31 16:29:43.536 11128 11200 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:43.536 11128 11200 I jxcore-log: 
,03-31 16:29:43.536 11128 11200 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:43.536 11128 11200 I jxcore-log: 
,03-31 16:29:43.541 11128 11200 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:43.541 11128 11200 I jxcore-log: 
,03-31 16:29:43.541 11128 11200 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:43.541 11128 11200 I jxcore-log: 
,03-31 16:29:43.541 11128 11200 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:43.541 11128 11200 I jxcore-log: 
,03-31 16:29:43.541 11128 11200 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:43.541 11128 11200 I jxcore-log: 
,03-31 16:29:43.546 11128 11200 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:43.546 11128 11200 I jxcore-log: 
,03-31 16:29:43.546 11128 11200 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:43.546 11128 11200 I jxcore-log: 
,03-31 16:29:43.546 11128 11200 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:43.546 11128 11200 I jxcore-log: 
,03-31 16:29:43.546 11128 11200 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:43.546 11128 11200 I jxcore-log: 
,03-31 16:29:43.551 11128 11200 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:43.551 11128 11200 I jxcore-log: 
,03-31 16:29:43.551 11128 11200 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:43.551 11128 11200 I jxcore-log: 
,03-31 16:29:43.551 11128 11200 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:43.551 11128 11200 I jxcore-log: 
,03-31 16:29:43.551 11128 11200 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:43.551 11128 11200 I jxcore-log: 
,03-31 16:29:43.551 11128 11200 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:43.551 11128 11200 I jxcore-log: 
,03-31 16:29:43.556 11128 11200 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:43.556 11128 11200 I jxcore-log: 
,03-31 16:29:43.561 11128 11200 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:43.561 11128 11200 I jxcore-log: 
,03-31 16:29:43.566 11128 11200 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:43.566 11128 11200 I jxcore-log: 
,03-31 16:29:43.566 11128 11200 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:43.566 11128 11200 I jxcore-log: 
,03-31 16:29:43.566 11128 11200 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:43.566 11128 11200 I jxcore-log: 
,03-31 16:29:43.566 11128 11200 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:43.566 11128 11200 I jxcore-log: 
,03-31 16:29:43.571 11128 11200 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:43.571 11128 11200 I jxcore-log: 
,03-31 16:29:43.571 11128 11200 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:43.571 11128 11200 I jxcore-log: 
,03-31 16:29:43.571 11128 11200 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:43.571 11128 11200 I jxcore-log: 
,03-31 16:29:43.571 11128 11200 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:43.571 11128 11200 I jxcore-log: 
,03-31 16:29:43.571 11128 11200 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:43.571 11128 11200 I jxcore-log: 
,03-31 16:29:43.576 11128 11200 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:43.576 11128 11200 I jxcore-log: 
,03-31 16:29:43.576 11128 11200 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:43.576 11128 11200 I jxcore-log: 
,03-31 16:29:43.576 11128 11200 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:43.576 11128 11200 I jxcore-log: 
,03-31 16:29:43.581 11128 11200 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:43.581 11128 11200 I jxcore-log: 
,03-31 16:29:43.581 11128 11200 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:43.581 11128 11200 I jxcore-log: 
,03-31 16:29:43.581 11128 11200 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:43.581 11128 11200 I jxcore-log: 
,03-31 16:29:43.581 11128 11200 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:43.581 11128 11200 I jxcore-log: 
,03-31 16:29:43.581 11128 11200 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:43.581 11128 11200 I jxcore-log: ,
,03-31 16:29:43.586 11128 11200 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:43.586 11128 11200 I jxcore-log: 
,03-31 16:29:43.586 11128 11200 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:43.586 11128 11200 I jxcore-log: 
,03-31 16:29:43.586 11128 11200 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:43.586 11128 11200 I jxcore-log: 
,03-31 16:29:43.591 11128 11200 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:43.591 11128 11200 I jxcore-log: 
,03-31 16:29:43.591 11128 11200 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:43.591 11128 11200 I jxcore-log: 
,03-31 16:29:43.591 11128 11200 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:43.591 11128 11200 I jxcore-log: 
,03-31 16:29:43.591 11128 11200 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:43.591 11128 11200 I jxcore-log: 
,03-31 16:29:43.591 11128 11200 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:43.591 11128 11200 I jxcore-log: 
,03-31 16:29:43.596 11128 11200 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:43.596 11128 11200 I jxcore-log: 
,03-31 16:29:43.596 11128 11200 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:43.596 11128 11200 I jxcore-log: 
,03-31 16:29:43.596 11128 11200 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:43.596 11128 11200 I jxcore-log: 
,03-31 16:29:43.596 11128 11200 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:43.596 11128 11200 I jxcore-log: 
,03-31 16:29:43.601 11128 11200 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:43.601 11128 11200 I jxcore-log: 
,03-31 16:29:43.601 11128 11200 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:43.601 11128 11200 I jxcore-log: 
,03-31 16:29:43.601 11128 11200 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:43.601 11128 11200 I jxcore-log: 
,03-31 16:29:43.601 11128 11200 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:43.601 11128 11200 I jxcore-log: 
,03-31 16:29:43.661 11128 11200 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:43.661 11128 11200 I jxcore-log: 
,03-31 16:29:43.661 11128 11200 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:43.661 11128 11200 I jxcore-log: 
,03-31 16:29:43.661 11128 11200 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:43.661 11128 11200 I jxcore-log: 
03-31 16:29:43.661 11128 11200 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:43.661 11128 11200 I jxcore-log: 
,03-31 16:29:43.661 11128 11200 I jxcore-log: DEBUG createNativeListener: mux close
03-31 16:29:43.661 11128 11200 I jxcore-log: 
,03-31 16:29:43.666 11128 11200 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:43.666 11128 11200 I jxcore-log: 
,03-31 16:29:43.666 11128 11200 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:43.666 11128 11200 I jxcore-log: 
03-31 16:29:43.666 11128 11200 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:43.666 11128 11200 I jxcore-log: 
03-31 16:29:43.666 11128 11200 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:43.666 11128 11200 I jxcore-log: 
,03-31 16:29:43.666 11128 11200 I jxcore-log: DEBUG createNativeListener: mux close
03-31 16:29:43.666 11128 11200 I jxcore-log: 
,03-31 16:29:43.666 11128 11200 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:43.666 11128 11200 I jxcore-log: 
,03-31 16:29:43.671 11128 11200 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:43.671 11128 11200 I jxcore-log: 
03-31 16:29:43.671 11128 11200 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:43.671 11128 11200 I jxcore-log: 
,03-31 16:29:43.671 11128 11200 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:43.671 11128 11200 I jxcore-log: 
,03-31 16:29:43.671 11128 11200 I jxcore-log: DEBUG createNativeListener: mux close
03-31 16:29:43.671 11128 11200 I jxcore-log: 
,03-31 16:29:43.671 11128 11200 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:43.671 11128 11200 I jxcore-log: 
03-31 16:29:43.671 11128 11200 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:43.671 11128 11200 I jxcore-log: 
,03-31 16:29:43.671 11128 11200 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:43.671 11128 11200 I jxcore-log: 
03-31 16:29:43.671 11128 11200 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:43.671 11128 11200 I jxcore-log: 
,03-31 16:29:43.676 11128 11200 I jxcore-log: DEBUG createNativeListener: mux close
03-31 16:29:43.676 11128 11200 I jxcore-log: 
03-31 16:29:43.676 11128 11200 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:43.676 11128 11200 I jxcore-log: 
,03-31 16:29:43.676 11128 11200 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:43.676 11128 11200 I jxcore-log: 
03-31 16:29:43.676 11128 11200 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:43.676 11128 11200 I jxcore-log: 
,03-31 16:29:43.676 11128 11200 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:43.676 11128 11200 I jxcore-log: 
03-31 16:29:43.676 11128 11200 I jxcore-log: DEBUG createNativeListener: mux close
03-31 16:29:43.676 11128 11200 I jxcore-log: 
,03-31 16:29:43.676 11128 11200 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:43.676 11128 11200 I jxcore-log: 
,03-31 16:29:43.676 11128 11200 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:43.676 11128 11200 I jxcore-log: 
03-31 16:29:43.676 11128 11200 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:43.676 11128 11200 I jxcore-log: 
03-31 16:29:43.676 11128 11200 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:43.676 11128 11200 I jxcore-log: 
03-31 16:29:43.681 11128 11200 I jxcore-log: DEBUG createNativeListener: mux close
03-31 16:29:43.681 11128 11200 I jxcore-log: 
03-31 16:29:43.681 11128 11200 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:43.681 11128 11200 I jxcore-log: 
03-31 16:29:43.681 11128 11200 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:43.681 11128 11200 I jxcore-log: 
03-31 16:29:43.681 11128 11200 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:43.681 11128 11200 I jxcore-log: 
03-31 16:29:43.681 11128 11200 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:43.681 11128 11200 I jxcore-log: 
,03-31 16:29:43.681 11128 11200 I jxcore-log: DEBUG createNativeListener: mux close
03-31 16:29:43.681 11128 11200 I jxcore-log: 
03-31 16:29:43.681 11128 11200 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:43.681 11128 11200 I jxcore-log: 
,03-31 16:29:43.681 11128 11200 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:43.681 11128 11200 I jxcore-log: 
03-31 16:29:43.681 11128 11200 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:43.681 11128 11200 I jxcore-log: 
03-31 16:29:43.681 11128 11200 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:43.681 11128 11200 I jxcore-log: 
,03-31 16:29:43.686 11128 11200 I jxcore-log: DEBUG createNativeListener: mux close
03-31 16:29:43.686 11128 11200 I jxcore-log: 
03-31 16:29:43.686 11128 11200 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:43.686 11128 11200 I jxcore-log: 
,03-31 16:29:43.686 11128 11200 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:43.686 11128 11200 I jxcore-log: 
03-31 16:29:43.686 11128 11200 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:43.686 11128 11200 I jxcore-log: 
03-31 16:29:43.686 11128 11200 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:43.686 11128 11200 I jxcore-log: 
,03-31 16:29:43.686 11128 11200 I jxcore-log: DEBUG createNativeListener: mux close
03-31 16:29:43.686 11128 11200 I jxcore-log: 
03-31 16:29:43.686 11128 11200 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:43.686 11128 11200 I jxcore-log: 
,03-31 16:29:43.686 11128 11200 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:43.686 11128 11200 I jxcore-log: 
03-31 16:29:43.686 11128 11200 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:43.686 11128 11200 I jxcore-log: 
,03-31 16:29:43.686 11128 11200 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:43.686 11128 11200 I jxcore-log: 
03-31 16:29:43.691 11128 11200 I jxcore-log: DEBUG createNativeListener: mux close
03-31 16:29:43.691 11128 11200 I jxcore-log: 
,03-31 16:29:43.691 11128 11200 I jxcore-log: ok 28 native server is nulled out
03-31 16:29:43.691 11128 11200 I jxcore-log: 
,03-31 16:29:43.691 11128 11200 I jxcore-log: ok 29 native server should be closed
03-31 16:29:43.691 11128 11200 I jxcore-log: 
03-31 16:29:43.691 11128 11200 I jxcore-log: ok 30 incoming has been removed
03-31 16:29:43.691 11128 11200 I jxcore-log: 
,03-31 16:29:43.691 11128 11200 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 16:29:43.691 11128 11200 I jxcore-log: 
03-31 16:29:43.691 11128 11200 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 16:29:43.691 11128 11200 I jxcore-log: 
03-31 16:29:43.691 11128 11200 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 16:29:43.691 11128 11200 I jxcore-log: 
,03-31 16:29:43.691 11128 11200 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 16:29:43.691 11128 11200 I jxcore-log: 
03-31 16:29:43.691 11128 11200 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 16:29:43.691 11128 11200 I jxcore-log: 
03-31 16:29:43.691 11128 11200 I jxcore-log: DEBUG createNativeListener: incoming socket close
,03-31 16:29:43.691 11128 11200 I jxcore-log: 
03-31 16:29:43.696 11128 11200 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 16:29:43.696 11128 11200 I jxcore-log: 
03-31 16:29:43.696 11128 11200 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 16:29:43.696 11128 11200 I jxcore-log: 
03-31 16:29:43.696 11128 11200 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 16:29:43.696 11128 11200 I jxcore-log: 
03-31 16:29:43.696 11128 11200 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 16:29:43.696 11128 11200 I jxcore-log: 
,03-31 16:29:43.776 11128 11200 I jxcore-log: # teardown
03-31 16:29:43.776 11128 11200 I jxcore-log: 
,03-31 16:29:44.111  3440  4048 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 16:29:44.111  3440  4048 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 16:29:44.111  3440  4048 D BatteryService: online:4, current avg:39, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:62
03-31 16:29:44.116  3440  3440 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 16:29:44.116  3440  4048 D BatteryService: stay LED for fully charged
03-31 16:29:44.121  3440  3440 I MotionRecognitionService: Plugged
03-31 16:29:44.121  3440  3440 D MotionRecognitionService:   cableConnection= 1
03-31 16:29:44.121  3440  3440 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 16:29:44.121  3440  3440 D MotionRecognitionService: skip setTransmitPower. 
,03-31 16:29:44.131  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 16:29:44.131  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 16:29:44.131  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 16:29:44.151  5838  5838 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 16:29:44.151  5838  5954 D HeadsetStateMachine: Disconnected process message: 10
,03-31 16:29:44.161  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 16:29:44.161  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 16:29:44.161  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 16:29:44.161  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 16:29:45.031 11128 11200 I jxcore-log: # setup
03-31 16:29:45.031 11128 11200 I jxcore-log: 
,03-31 16:29:45.536  3440  6049 D SSRM:n  : SIOP:: AP = 270, PST = 277 (W:12), CUR = 39, LCD = 0
,03-31 16:29:46.911 11128 11200 I jxcore-log: # 10. native server - simulate mux failure, make sure everything is cleaned up
03-31 16:29:46.911 11128 11200 I jxcore-log: 
,03-31 16:29:48.736  3440  6080 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-31 16:29:49.256 11128 11200 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 16:29:49.256 11128 11200 I jxcore-log: 
,03-31 16:29:49.271 11128 11200 I jxcore-log: DEBUG createNativeListener: listening 59494
03-31 16:29:49.271 11128 11200 I jxcore-log: 
,03-31 16:29:49.281 11128 11200 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 16:29:49.281 11128 11200 I jxcore-log: 
,03-31 16:29:49.286 11128 11200 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 16:29:49.286 11128 11200 I jxcore-log: 
,03-31 16:29:49.291 11128 11200 I jxcore-log: DEBUG createNativeListener: new mux
03-31 16:29:49.291 11128 11200 I jxcore-log: 
,03-31 16:29:49.301 11128 11200 I jxcore-log: ok 31 we should not have gotten an error
03-31 16:29:49.301 11128 11200 I jxcore-log: 
,03-31 16:29:49.306 11128 11200 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:49.306 11128 11200 I jxcore-log: 
,03-31 16:29:49.306 11128 11200 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:49.306 11128 11200 I jxcore-log: 
,03-31 16:29:49.316 11128 11200 I jxcore-log: ok 32 Buffers are identical
03-31 16:29:49.316 11128 11200 I jxcore-log: 
,03-31 16:29:49.316 11128 11200 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:49.316 11128 11200 I jxcore-log: 
,03-31 16:29:49.321 11128 11200 I jxcore-log: DEBUG createNativeListener: mux close
03-31 16:29:49.321 11128 11200 I jxcore-log: 
,03-31 16:29:49.336 11128 11200 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 16:29:49.336 11128 11200 I jxcore-log: 
,03-31 16:29:49.336 11128 11200 I jxcore-log: ok 33 server should be fine
03-31 16:29:49.336 11128 11200 I jxcore-log: 
,03-31 16:29:49.336 11128 11200 I jxcore-log: ok 34 server should be open
03-31 16:29:49.336 11128 11200 I jxcore-log: 
,03-31 16:29:49.336 11128 11200 I jxcore-log: ok 35 incoming has been removed
03-31 16:29:49.336 11128 11200 I jxcore-log: 
,03-31 16:29:49.341 11128 11200 I jxcore-log: ok 36 The mux object should be closed
03-31 16:29:49.341 11128 11200 I jxcore-log: 
03-31 16:29:49.341 11128 11200 I jxcore-log: ok 37 The mux stream should be closed
03-31 16:29:49.341 11128 11200 I jxcore-log: 
,03-31 16:29:49.346 11128 11200 I jxcore-log: # teardown
03-31 16:29:49.346 11128 11200 I jxcore-log: 
,03-31 16:29:49.466 11128 11200 I jxcore-log: # setup
03-31 16:29:49.466 11128 11200 I jxcore-log: 
,03-31 16:29:49.786 11128 11200 I jxcore-log: # 11. native server - timing out the incoming connection cleans everything up
03-31 16:29:49.786 11128 11200 I jxcore-log: 
,03-31 16:29:51.171 11128 11200 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 16:29:51.171 11128 11200 I jxcore-log: 
,03-31 16:29:51.181 11128 11200 I jxcore-log: DEBUG createNativeListener: listening 41295
03-31 16:29:51.181 11128 11200 I jxcore-log: 
,03-31 16:29:51.191 11128 11200 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 16:29:51.191 11128 11200 I jxcore-log: 
,03-31 16:29:51.191 11128 11200 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 16:29:51.191 11128 11200 I jxcore-log: 
,03-31 16:29:51.196 11128 11200 I jxcore-log: DEBUG createNativeListener: new mux
03-31 16:29:51.196 11128 11200 I jxcore-log: 
,03-31 16:29:51.201 11128 11200 I jxcore-log: ok 38 we should not have gotten an error
03-31 16:29:51.201 11128 11200 I jxcore-log: 
,03-31 16:29:51.206 11128 11200 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:51.206 11128 11200 I jxcore-log: 
,03-31 16:29:51.211 11128 11200 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:51.211 11128 11200 I jxcore-log: 
,03-31 16:29:51.221 11128 11200 I jxcore-log: ok 39 Buffers are identical
03-31 16:29:51.221 11128 11200 I jxcore-log: 
,03-31 16:29:51.226 11128 11200 I jxcore-log: DEBUG createNativeListener: incoming socket timeout
03-31 16:29:51.226 11128 11200 I jxcore-log: 
,03-31 16:29:51.231 11128 11200 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:51.231 11128 11200 I jxcore-log: 
,03-31 16:29:51.231 11128 11200 I jxcore-log: DEBUG createNativeListener: mux close
03-31 16:29:51.231 11128 11200 I jxcore-log: 
,03-31 16:29:51.241 11128 11200 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 16:29:51.241 11128 11200 I jxcore-log: 
,03-31 16:29:51.241 11128 11200 I jxcore-log: ok 40 server should be fine
03-31 16:29:51.241 11128 11200 I jxcore-log: 
,03-31 16:29:51.241 11128 11200 I jxcore-log: ok 41 server should be open
03-31 16:29:51.241 11128 11200 I jxcore-log: 
,03-31 16:29:51.246 11128 11200 I jxcore-log: ok 42 incoming has been removed
03-31 16:29:51.246 11128 11200 I jxcore-log: 
,03-31 16:29:51.246 11128 11200 I jxcore-log: ok 43 The mux object should be closed
03-31 16:29:51.246 11128 11200 I jxcore-log: 
,03-31 16:29:51.246 11128 11200 I jxcore-log: ok 44 The mux stream should be closed
03-31 16:29:51.246 11128 11200 I jxcore-log: 
,03-31 16:29:51.256 11128 11200 I jxcore-log: # teardown
03-31 16:29:51.256 11128 11200 I jxcore-log: 
,03-31 16:29:52.881 11128 11200 I jxcore-log: # setup
03-31 16:29:52.881 11128 11200 I jxcore-log: 
,03-31 16:29:54.246  3440  4737 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-31 16:29:54.251  3440  4737 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 16:29:54.251  3440  4737 D BatteryService: online:4, current avg:38, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:42
03-31 16:29:54.251  3440  3440 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 16:29:54.256  3440  4737 D BatteryService: stay LED for fully charged
,03-31 16:29:54.261  3440  3440 I MotionRecognitionService: Plugged,
03-31 16:29:54.261  3440  3440 D MotionRecognitionService:   cableConnection= 1
03-31 16:29:54.261  3440  3440 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-31 16:29:54.261  3440  3440 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 16:29:54.271  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 16:29:54.271  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 16:29:54.276  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 16:29:54.296  5838  5838 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 16:29:54.296  5838  5954 D HeadsetStateMachine: Disconnected process message: 10
,03-31 16:29:54.306  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 16:29:54.306  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 16:29:54.306  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 16:29:54.306  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 16:29:55.561  3440  6049 D SSRM:n  : SIOP:: AP = 270, PST = 275 (W:12), CUR = 38, LCD = 0
,03-31 16:29:57.626 11128 11200 I jxcore-log: # 12. closeAll can close even when connections open
03-31 16:29:57.626 11128 11200 I jxcore-log: 
,03-31 16:29:57.776 11128 11200 I jxcore-log: ok 45 not possible to connect to the server anymore
03-31 16:29:57.776 11128 11200 I jxcore-log: 
,03-31 16:29:57.786 11128 11200 I jxcore-log: # teardown
03-31 16:29:57.786 11128 11200 I jxcore-log: 
,03-31 16:29:58.351 11128 11200 I jxcore-log: # setup
03-31 16:29:58.351 11128 11200 I jxcore-log: 
,03-31 16:29:58.506 11128 11200 I jxcore-log: # 13. closeAll with promise
03-31 16:29:58.506 11128 11200 I jxcore-log: 
,03-31 16:29:58.716 11128 11200 I jxcore-log: ok 46 not possible to connect to the server anymore
03-31 16:29:58.716 11128 11200 I jxcore-log: 
,03-31 16:29:58.721 11128 11200 I jxcore-log: # teardown
03-31 16:29:58.721 11128 11200 I jxcore-log: 
,03-31 16:29:58.841 11128 11200 I jxcore-log: # setup
03-31 16:29:58.841 11128 11200 I jxcore-log: 
,03-31 16:29:58.961 11128 11200 I jxcore-log: # 14. closeAll properly throws when closing a non open server with eatNotRunning set to false
03-31 16:29:58.961 11128 11200 I jxcore-log: 
,03-31 16:29:59.141 11128 11200 I jxcore-log: ok 47 Got the right error
03-31 16:29:59.141 11128 11200 I jxcore-log: 
,03-31 16:29:59.146 11128 11200 I jxcore-log: # teardown
03-31 16:29:59.146 11128 11200 I jxcore-log: 
,03-31 16:29:59.311 11128 11200 I jxcore-log: # setup
03-31 16:29:59.311 11128 11200 I jxcore-log: 
,03-31 16:29:59.456 11128 11200 I jxcore-log: # 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true
03-31 16:29:59.456 11128 11200 I jxcore-log: 
,03-31 16:29:59.621 11128 11200 I jxcore-log: # teardown
03-31 16:29:59.621 11128 11200 I jxcore-log: 
,03-31 16:29:59.786 11128 11200 I jxcore-log: # setup
03-31 16:29:59.786 11128 11200 I jxcore-log: 
,03-31 16:29:59.896 11128 11200 I jxcore-log: # 16. multiplex can send data
03-31 16:29:59.896 11128 11200 I jxcore-log: 
,03-31 16:29:59.996  3440  3618 V AlarmManager: waitForAlarm result :8
,03-31 16:30:00.076 11128 11200 I jxcore-log: ok 48 String should be length:200
03-31 16:30:00.076 11128 11200 I jxcore-log: 
,03-31 16:30:00.086 11128 11200 I jxcore-log: # teardown
03-31 16:30:00.086 11128 11200 I jxcore-log: 
,03-31 16:30:00.211 11128 11200 I jxcore-log: # setup
03-31 16:30:00.211 11128 11200 I jxcore-log: 
,03-31 16:30:00.336 11128 11200 I jxcore-log: # 17. enqueue and run in order
03-31 16:30:00.336 11128 11200 I jxcore-log: 
,03-31 16:30:00.586 11128 11200 I jxcore-log: ok 49 firstPromise setTimeout
03-31 16:30:00.586 11128 11200 I jxcore-log: 
,03-31 16:30:00.596 11128 11200 I jxcore-log: ok 50 firstPromise result
03-31 16:30:00.596 11128 11200 I jxcore-log: 
,03-31 16:30:00.601 11128 11200 I jxcore-log: ok 51 firstPromise testValue
03-31 16:30:00.601 11128 11200 I jxcore-log: 
,03-31 16:30:00.711 11128 11200 I jxcore-log: ok 52 secondPromise setTimeout
03-31 16:30:00.711 11128 11200 I jxcore-log: 
,03-31 16:30:00.721 11128 11200 I jxcore-log: ok 53 secondPromise result,
03-31 16:30:00.721 11128 11200 I jxcore-log: 
,03-31 16:30:00.731 11128 11200 I jxcore-log: ok 54 secondPromise testValue
03-31 16:30:00.731 11128 11200 I jxcore-log: 
,03-31 16:30:00.731 11128 11200 I jxcore-log: ok 55 thirdPromise in promise
03-31 16:30:00.731 11128 11200 I jxcore-log: 
,03-31 16:30:00.736 11128 11200 I jxcore-log: ok 56 thirdPromise result
03-31 16:30:00.736 11128 11200 I jxcore-log: 
,03-31 16:30:00.741 11128 11200 I jxcore-log: ok 57 thirdPromise testValue
03-31 16:30:00.741 11128 11200 I jxcore-log: 
,03-31 16:30:00.751 11128 11200 I jxcore-log: # teardown
03-31 16:30:00.751 11128 11200 I jxcore-log: 
,03-31 16:30:00.881 11128 11200 I jxcore-log: # setup
03-31 16:30:00.881 11128 11200 I jxcore-log: 
,03-31 16:30:01.096 11128 11200 I jxcore-log: # 18. enqueueAtTop and run backwards
03-31 16:30:01.096 11128 11200 I jxcore-log: 
,03-31 16:30:01.206 11128 11200 I jxcore-log: ok 58 thirdPromise - first to run
03-31 16:30:01.206 11128 11200 I jxcore-log: 
,03-31 16:30:01.211 11128 11200 I jxcore-log: ok 59 thirdPromise - in resolve
03-31 16:30:01.211 11128 11200 I jxcore-log: 
,03-31 16:30:01.216 11128 11200 I jxcore-log: ok 60 secondPromise - second to run
03-31 16:30:01.216 11128 11200 I jxcore-log: 
,03-31 16:30:01.216 11128 11200 I jxcore-log: ok 61 secondPromise - in catch
03-31 16:30:01.216 11128 11200 I jxcore-log: 
,03-31 16:30:01.221 11128 11200 I jxcore-log: ok 62 firstPromise - third to run
03-31 16:30:01.221 11128 11200 I jxcore-log: 
,03-31 16:30:01.221 11128 11200 I jxcore-log: ok 63 firstPromise - in then
03-31 16:30:01.221 11128 11200 I jxcore-log: 
,03-31 16:30:01.226 11128 11200 I jxcore-log: ok 64 testing promises
03-31 16:30:01.226 11128 11200 I jxcore-log: 
,03-31 16:30:01.231 11128 11200 I jxcore-log: # teardown
03-31 16:30:01.231 11128 11200 I jxcore-log: 
,03-31 16:30:01.436 11128 11200 I jxcore-log: # setup
03-31 16:30:01.436 11128 11200 I jxcore-log: 
,03-31 16:30:01.571 11128 11200 I jxcore-log: # 19. mix enqueue and enqueueAtTop
03-31 16:30:01.571 11128 11200 I jxcore-log: 
,03-31 16:30:01.716 11128 11200 I jxcore-log: ok 65 fourth
03-31 16:30:01.716 11128 11200 I jxcore-log: 
,03-31 16:30:01.721 11128 11200 I jxcore-log: ok 66 fourth
03-31 16:30:01.721 11128 11200 I jxcore-log: 
,03-31 16:30:01.726 11128 11200 I jxcore-log: ok 67 second
03-31 16:30:01.726 11128 11200 I jxcore-log: 
,03-31 16:30:01.726 11128 11200 I jxcore-log: ok 68 secondPromise - in then
03-31 16:30:01.726 11128 11200 I jxcore-log: 
,03-31 16:30:01.836 11128 11200 I jxcore-log: ok 69 first
03-31 16:30:01.836 11128 11200 I jxcore-log: 
,03-31 16:30:01.846 11128 11200 I jxcore-log: ok 70 firstPromise - in catch
03-31 16:30:01.846 11128 11200 I jxcore-log: 
,03-31 16:30:01.851 11128 11200 I jxcore-log: ok 71 third
03-31 16:30:01.851 11128 11200 I jxcore-log: 
,03-31 16:30:01.856 11128 11200 I jxcore-log: ok 72 thirdPromise - in then
03-31 16:30:01.856 11128 11200 I jxcore-log: 
,03-31 16:30:01.856 11128 11200 I jxcore-log: ok 73 testingPromises
03-31 16:30:01.856 11128 11200 I jxcore-log: 
,03-31 16:30:01.866 11128 11200 I jxcore-log: # teardown
03-31 16:30:01.866 11128 11200 I jxcore-log: 
,03-31 16:30:02.021 11128 11200 I jxcore-log: # setup,
03-31 16:30:02.021 11128 11200 I jxcore-log: 
,03-31 16:30:02.166 11128 11200 I jxcore-log: # 20. queues handled independently
03-31 16:30:02.166 11128 11200 I jxcore-log: 
,03-31 16:30:03.086 11128 11200 I jxcore-log: ok 74 all short operations completed before the long resolves
03-31 16:30:03.086 11128 11200 I jxcore-log: 
,03-31 16:30:03.096 11128 11200 I jxcore-log: # teardown
03-31 16:30:03.096 11128 11200 I jxcore-log: 
,03-31 16:30:03.171 11128 11200 I jxcore-log: # setup
03-31 16:30:03.171 11128 11200 I jxcore-log: 
,03-31 16:30:03.771 11128 11200 I jxcore-log: # 21. basic,
03-31 16:30:03.771 11128 11200 I jxcore-log: 
,03-31 16:30:03.916 11128 11200 I jxcore-log: ok 75 sane
03-31 16:30:03.916 11128 11200 I jxcore-log: 
,03-31 16:30:03.921 11128 11200 I jxcore-log: # teardown
03-31 16:30:03.921 11128 11200 I jxcore-log: 
,03-31 16:30:04.096 11128 11200 I jxcore-log: # setup
03-31 16:30:04.096 11128 11200 I jxcore-log: 
,03-31 16:30:04.201 11128 11200 I jxcore-log: # 22. another
03-31 16:30:04.201 11128 11200 I jxcore-log: 
,03-31 16:30:04.316 11128 11200 I jxcore-log: ok 76 sane
03-31 16:30:04.316 11128 11200 I jxcore-log: 
,03-31 16:30:04.331 11128 11200 I jxcore-log: # teardown
03-31 16:30:04.331 11128 11200 I jxcore-log: 
,03-31 16:30:04.371  3440  3483 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-31 16:30:04.376  3440  3483 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 16:30:04.376  3440  3483 D BatteryService: online:4, current avg:37, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:47
03-31 16:30:04.376  3440  3483 D BatteryService: stay LED for fully charged
03-31 16:30:04.376  3440  3440 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 16:30:04.376  3440  3440 I MotionRecognitionService: Plugged
03-31 16:30:04.376  3440  3440 D MotionRecognitionService:   cableConnection= 1
03-31 16:30:04.376  3440  3440 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 16:30:04.376  3440  3440 D MotionRecognitionService: skip setTransmitPower. 
,03-31 16:30:04.381  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 16:30:04.381  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 16:30:04.381  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 16:30:04.386  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 16:30:04.386  5838  5838 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 16:30:04.386  5838  5954 D HeadsetStateMachine: Disconnected process message: 10
,03-31 16:30:04.401  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 16:30:04.401  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 16:30:04.401  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 16:30:04.406 11128 11200 I jxcore-log: # setup
03-31 16:30:04.406 11128 11200 I jxcore-log: 
,03-31 16:30:04.596 11128 11200 I jxcore-log: # 23. can pass data in setup
03-31 16:30:04.596 11128 11200 I jxcore-log: 
,03-31 16:30:04.746 11128 11200 I jxcore-log: [{"uuid":"e53a4725-b258-4357-b9c9-4ce37336a0f4","data":"custom data"},{"uuid":"18d69230-3e98-40c1-aeb6-4768d8d99ac3","data":"custom data"},{"uuid":"225be878-d40d-41a8-b923-e9d5889e0944","data":"custom data"}]
03-31 16:30:04.746 11128 11200 I jxcore-log: 
,03-31 16:30:04.751 11128 11200 I jxcore-log: ok 77 test participant has uuid
03-31 16:30:04.751 11128 11200 I jxcore-log: 
,03-31 16:30:04.751 11128 11200 I jxcore-log: ok 78 participant data matches
03-31 16:30:04.751 11128 11200 I jxcore-log: 
,03-31 16:30:04.756 11128 11200 I jxcore-log: ok 79 test participant has uuid
03-31 16:30:04.756 11128 11200 I jxcore-log: 
03-31 16:30:04.756 11128 11200 I jxcore-log: ok 80 participant data matches
03-31 16:30:04.756 11128 11200 I jxcore-log: 
,03-31 16:30:04.761 11128 11200 I jxcore-log: ok 81 test participant has uuid
03-31 16:30:04.761 11128 11200 I jxcore-log: 
,03-31 16:30:04.761 11128 11200 I jxcore-log: ok 82 participant data matches
03-31 16:30:04.761 11128 11200 I jxcore-log: 
,03-31 16:30:04.761 11128 11200 I jxcore-log: ok 83 own UUID is found from the participants list
03-31 16:30:04.761 11128 11200 I jxcore-log: 
,03-31 16:30:04.766 11128 11200 I jxcore-log: # teardown
03-31 16:30:04.766 11128 11200 I jxcore-log: 
,03-31 16:30:04.851 11128 11200 I jxcore-log: # setup
03-31 16:30:04.851 11128 11200 I jxcore-log: 
,03-31 16:30:04.951  3440  3585 I PowerManagerService: [PWL] Off : 180s ago
,03-31 16:30:04.971 11128 11200 I jxcore-log: # 24. #startListeningForAdvertisements should fail if start not called
03-31 16:30:04.971 11128 11200 I jxcore-log: 
,03-31 16:30:05.071 11128 11200 I jxcore-log: ok 84 specific error should be returned
03-31 16:30:05.071 11128 11200 I jxcore-log: 
,03-31 16:30:05.076 11128 11200 I jxcore-log: # teardown
03-31 16:30:05.076 11128 11200 I jxcore-log: 
,03-31 16:30:05.166 11128 11200 I jxcore-log: ok 85 error should be null
03-31 16:30:05.166 11128 11200 I jxcore-log: 
,03-31 16:30:05.166 11128 11200 I jxcore-log: ok 86 error should be null
03-31 16:30:05.166 11128 11200 I jxcore-log: 
,03-31 16:30:05.171 11128 11200 I jxcore-log: # setup
03-31 16:30:05.171 11128 11200 I jxcore-log: 
,03-31 16:30:05.326 11128 11200 I jxcore-log: # 25. #startUpdateAdvertisingAndListening should fail if start not called
03-31 16:30:05.326 11128 11200 I jxcore-log: 
,03-31 16:30:05.446 11128 11200 I jxcore-log: ok 87 specific error should be returned
03-31 16:30:05.446 11128 11200 I jxcore-log: 
,03-31 16:30:05.451 11128 11200 I jxcore-log: # teardown
03-31 16:30:05.451 11128 11200 I jxcore-log: 
,03-31 16:30:05.586 11128 11200 I jxcore-log: ok 88 error should be null
03-31 16:30:05.586 11128 11200 I jxcore-log: 
,03-31 16:30:05.591 11128 11200 I jxcore-log: ok 89 error should be null
03-31 16:30:05.591 11128 11200 I jxcore-log: 
,03-31 16:30:05.601 11128 11200 I jxcore-log: # setup
03-31 16:30:05.601 11128 11200 I jxcore-log: 
,03-31 16:30:05.601  3440  6049 D SSRM:n  : SIOP:: AP = 270, PST = 275 (W:12), CUR = 37, LCD = 0
,03-31 16:30:05.731 11128 11200 I jxcore-log: # 26. should be able to call #stopListeningForAdvertisements many times
03-31 16:30:05.731 11128 11200 I jxcore-log: 
,03-31 16:30:06.001 11128 11200 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 16:30:06.001 11128 11200 I jxcore-log: 
,03-31 16:30:06.006 11128 11200 I jxcore-log: DEBUG createNativeListener: listening 37654
03-31 16:30:06.006 11128 11200 I jxcore-log: 
,03-31 16:30:06.011 11128 11200 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 16:30:06.011 11128 11200 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 16:30:06.016 11128 11200 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 16:30:06.021 11128 11200 I jxcore-log: ok 90 error should be null
03-31 16:30:06.021 11128 11200 I jxcore-log: 
,03-31 16:30:06.021 11128 11200 I jxcore-log: ok 91 error should be null
03-31 16:30:06.021 11128 11200 I jxcore-log: 
,03-31 16:30:06.026 11128 11200 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 16:30:06.026 11128 11200 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 16:30:06.026 11128 11200 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 16:30:06.026 11128 11200 I jxcore-log: ok 92 error should be null
03-31 16:30:06.026 11128 11200 I jxcore-log: 
,03-31 16:30:06.026 11128 11200 I jxcore-log: ok 93 error should be null
,03-31 16:30:06.026 11128 11200 I jxcore-log: 
,03-31 16:30:06.036 11128 11200 I jxcore-log: # teardown
03-31 16:30:06.036 11128 11200 I jxcore-log: 
,03-31 16:30:06.211 11128 11200 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 16:30:06.211 11128 11200 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-31 16:30:06.211 11128 11200 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 16:30:06.221 11128 11200 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 16:30:06.221 11128 11200 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-31 16:30:06.221 11128 11200 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 16:30:06.231 11128 11200 I jxcore-log: ok 94 error should be null
03-31 16:30:06.231 11128 11200 I jxcore-log: 
,03-31 16:30:06.231 11128 11200 I jxcore-log: ok 95 error should be null
03-31 16:30:06.231 11128 11200 I jxcore-log: 
,03-31 16:30:06.236 11128 11200 I jxcore-log: # setup
03-31 16:30:06.236 11128 11200 I jxcore-log: 
,03-31 16:30:06.421 11128 11200 I jxcore-log: # 27. should be able to call #startListeningForAdvertisements many times
03-31 16:30:06.421 11128 11200 I jxcore-log: 
,03-31 16:30:06.621 11128 11200 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 16:30:06.621 11128 11200 I jxcore-log: 
,03-31 16:30:06.626 11128 11200 I jxcore-log: DEBUG createNativeListener: listening 58347
03-31 16:30:06.626 11128 11200 I jxcore-log: 
,03-31 16:30:06.636 11128 11200 I io.jxcore.node.ConnectionHelper: start: Port number: 0, start advertisements: false
,03-31 16:30:06.636 11128 11200 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-31 16:30:06.641 11128 11200 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,03-31 16:30:06.641 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-31 16:30:06.641 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 16:30:06.641 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-31 16:30:06.646 11128 11200 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-31 16:30:06.661 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-31 16:30:06.666 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-31 16:30:06.666 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-31 16:30:06.666 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-31 16:30:06.666 11128 11200 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 16:30:06.676  5838  5955 D BtGatt.GattService: registerClient() - UUID=fdda3110-b09d-46c7-8633-61f82b203e89
,03-31 16:30:06.721  5838  5944 D BtGatt.GattService: onClientRegistered() - UUID=fdda3110-b09d-46c7-8633-61f82b203e89, clientIf=6
,03-31 16:30:06.721 11128 11138 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-31 16:30:06.721  5838  9004 D BtGatt.GattService: start scan with filters
,03-31 16:30:06.741  5838  9004 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 65
,03-31 16:30:06.746 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 16:30:06.746 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 16:30:06.746  5838  5952 D BtGatt.ScanManager: handling starting scan
03-31 16:30:06.746  5838  5952 D BtGatt.ScanManager: isFilteringSupported
03-31 16:30:06.746 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-31 16:30:06.746 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 16:30:06.746  5838  5952 D BluetoothAdapter: setting StandAloneBleMode
03-31 16:30:06.746 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,03-31 16:30:06.746 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-31 16:30:06.746 11128 11128 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 16:30:06.746  5838  5952 D BtGatt.ScanManager: isFilteringSupported
,03-31 16:30:06.746  5838  5952 D BluetoothAdapter: setting StandAloneBleMode
03-31 16:30:06.751  5838  5952 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a5f1d82
,03-31 16:30:06.751 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-31 16:30:06.751 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 16:30:06.751 11128 11200 I io.jxcore.node.ConnectionHelper: start: OK
03-31 16:30:06.751 11128 11128 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 16:30:06.751 11128 11128 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-31 16:30:06.751 11128 11128 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-31 16:30:06.761  5838  5944 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,03-31 16:30:06.761  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 16:30:06.761  5838  5952 D BtGatt.ScanManager: allow scan with filters
03-31 16:30:06.761  5838  5952 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,03-31 16:30:06.761  5838  5952 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,03-31 16:30:06.761  5838  5944 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,03-31 16:30:06.761  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 16:30:06.761 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 16:30:06.761 11128 11200 I jxcore-log: 
03-31 16:30:06.761  5838  5952 D BtGatt.ScanManager: Starting BLE batch scan
,03-31 16:30:06.761  5838  5952 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-31 16:30:06.766  5838  5944 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,03-31 16:30:06.766  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 16:30:06.766 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 16:30:06.766 11128 11200 I jxcore-log: 
,03-31 16:30:06.766  5838  5944 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-31 16:30:06.766  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 16:30:06.771 11128 11200 I jxcore-log: ok 96 error should be null
03-31 16:30:06.771 11128 11200 I jxcore-log: 
,03-31 16:30:06.771 11128 11200 I jxcore-log: ok 97 error should be null
03-31 16:30:06.771 11128 11200 I jxcore-log: 
,03-31 16:30:06.776 11128 11200 I io.jxcore.node.ConnectionHelper: start: Port number: 0, start advertisements: false
,03-31 16:30:06.776 11128 11200 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 16:30:06.776 11128 11200 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 16:30:06.776 11128 11200 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-31 16:30:06.776 11128 11200 I io.jxcore.node.ConnectionHelper: start: OK
,03-31 16:30:06.776 11128 11200 I jxcore-log: ok 98 error should be null
03-31 16:30:06.776 11128 11200 I jxcore-log: 
,03-31 16:30:06.781 11128 11200 I jxcore-log: ok 99 error should be null
03-31 16:30:06.781 11128 11200 I jxcore-log: 
,03-31 16:30:06.786 11128 11200 I jxcore-log: # teardown
03-31 16:30:06.786 11128 11200 I jxcore-log: 
,03-31 16:30:06.966 11128 11200 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 16:30:06.966 11128 11200 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,03-31 16:30:06.966 11128 11200 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,03-31 16:30:06.971 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-31 16:30:06.971 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-31 16:30:06.971 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-31 16:30:06.971 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-31 16:30:06.971 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-31 16:30:06.976 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-31 16:30:06.976  5838  5955 D BtGatt.GattService: stopScan() - queue size =1
03-31 16:30:06.976  5838  5952 D BtGatt.ScanManager: filter size is 1
03-31 16:30:06.981  5838  5952 D BtGatt.ScanManager: delete FilterIndex - 3
03-31 16:30:06.981  5838  5944 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-31 16:30:06.981  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 16:30:06.981  5838  5952 D BtGatt.ScanManager: stopping BLe Batch,
,03-31 16:30:06.986  5838  5944 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-31 16:30:06.986  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 16:30:06.986  5838  5952 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6,
03-31 16:30:06.986  5838  5944 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-31 16:30:06.991  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 16:30:06.991  5838  9004 D BtGatt.GattService: unregisterClient() - clientIf=6,
,03-31 16:30:06.996 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
03-31 16:30:06.996 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 16:30:06.996 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-31 16:30:06.996 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-31 16:30:06.996 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,03-31 16:30:06.996 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-31 16:30:07.001 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
03-31 16:30:07.001 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 16:30:07.001 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-31 16:30:07.001 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
03-31 16:30:07.001 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 16:30:07.001 11128 11128 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
03-31 16:30:07.001 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 16:30:07.001 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-31 16:30:07.011 11128 11128 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-31 16:30:07.016 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
03-31 16:30:07.016 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
03-31 16:30:07.016 11128 11128 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 16:30:07.021 11128 11128 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false,
03-31 16:30:07.021 11128 11128 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 16:30:07.021 11128 11128 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 16:30:07.021 11128 11128 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 16:30:07.026 11128 11200 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-31 16:30:07.026 11128 11200 I jxcore-log: 
,03-31 16:30:07.031 11128 11200 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 16:30:07.031 11128 11200 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 16:30:07.031 11128 11200 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 16:30:07.031 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 16:30:07.031 11128 11200 I jxcore-log: 
,03-31 16:30:07.036 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 16:30:07.036 11128 11200 I jxcore-log: 
,03-31 16:30:07.041 11128 11200 I jxcore-log: ok 100 error should be null
03-31 16:30:07.041 11128 11200 I jxcore-log: 
,03-31 16:30:07.041 11128 11200 I jxcore-log: ok 101 error should be null
03-31 16:30:07.041 11128 11200 I jxcore-log: 
,03-31 16:30:07.051 11128 11200 I jxcore-log: # setup
03-31 16:30:07.051 11128 11200 I jxcore-log: 
,03-31 16:30:07.131 11128 11200 I jxcore-log: # 28. should be able to call #startUpdateAdvertisingAndListening many times
03-31 16:30:07.131 11128 11200 I jxcore-log: 
,03-31 16:30:07.326 11128 11200 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 16:30:07.326 11128 11200 I jxcore-log: 
,03-31 16:30:07.331 11128 11200 I jxcore-log: DEBUG createNativeListener: listening 59471
03-31 16:30:07.331 11128 11200 I jxcore-log: 
,03-31 16:30:07.351 11128 11200 I io.jxcore.node.ConnectionHelper: start: Port number: 59471, start advertisements: true
,03-31 16:30:07.351 11128 11200 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 16:30:07.351 11128 11200 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,03-31 16:30:07.351 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-31 16:30:07.356 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-31 16:30:07.356 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 16:30:07.356 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-31 16:30:07.356 11128 11200 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 16:30:07.361  5838  5850 D BtGatt.GattService: registerClient() - UUID=3b4a43b0-c64c-4156-8b0b-8ea91a80fa84
,03-31 16:30:07.401  5838  5944 D BtGatt.GattService: onClientRegistered() - UUID=3b4a43b0-c64c-4156-8b0b-8ea91a80fa84, clientIf=6
,03-31 16:30:07.401 11128 11138 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-31 16:30:07.401  5838  5848 D BtGatt.GattService: start scan with filters
,03-31 16:30:07.421  5838  5848 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 66
,03-31 16:30:07.421 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 16:30:07.421 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 16:30:07.421 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-31 16:30:07.421 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 16:30:07.421 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 16:30:07.421  5838  5952 D BtGatt.ScanManager: handling starting scan
03-31 16:30:07.421  5838  5952 D BtGatt.ScanManager: isFilteringSupported
03-31 16:30:07.421  5838  5952 D BluetoothAdapter: setting StandAloneBleMode
03-31 16:30:07.421 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 16:30:07.421 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-31 16:30:07.421 11128 11128 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 16:30:07.421 11128 11200 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-31 16:30:07.421 11128 11200 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 16:30:07.421 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 16:30:07.421 11128 11200 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-31 16:30:07.421  5838  5944 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-31 16:30:07.421  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 16:30:07.421  5838  5952 D BtGatt.ScanManager: allow scan with filters
03-31 16:30:07.421  5838  5952 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-31 16:30:07.421  5838  5952 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
03-31 16:30:07.426  5838  5944 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-31 16:30:07.426  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 16:30:07.426  5838  5952 D BtGatt.ScanManager: Starting BLE batch scan
03-31 16:30:07.426  5838  5952 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-31 16:30:07.426  5838  9004 D BtGatt.GattService: registerClient() - UUID=759651bf-ce81-4831-8e8a-26c37ca4cdae
03-31 16:30:07.426  5838  5944 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-31 16:30:07.426  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 16:30:07.426  5838  5944 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-31 16:30:07.426  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 16:30:07.471  5838  5944 D BtGatt.GattService: onClientRegistered() - UUID=759651bf-ce81-4831-8e8a-26c37ca4cdae, clientIf=7
,03-31 16:30:07.471 11128 11144 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-31 16:30:07.501  5838  5955 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 52
,03-31 16:30:07.506  5838  5951 D BtGatt.AdvertiseManager: message : 0
,03-31 16:30:07.511  5838  5951 D BtGatt.AdvertiseManager: number of adv instance running0
03-31 16:30:07.511  5838  5951 D BtGatt.AdvertiseManager: size of list is =0
,03-31 16:30:07.511  5838  5951 D BtGatt.AdvertiseManager: starting advertising
,03-31 16:30:07.516  5838  5951 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-31 16:30:07.521  5838  5944 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-31 16:30:07.526  5838  5951 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 16:30:07.526  5838  5944 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-31 16:30:07.526  5838  5951 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,03-31 16:30:07.526  5838  5951 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,03-31 16:30:07.531 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-31 16:30:07.531 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-31 16:30:07.531 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-31 16:30:07.536 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-31 16:30:07.536 11128 11200 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,03-31 16:30:07.536 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-31 16:30:07.536 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-31 16:30:07.541 11128 11200 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,03-31 16:30:07.541 11128 11200 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,03-31 16:30:07.541 11128 11200 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-31 16:30:07.541 11128 11128 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-31 16:30:07.541 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 16:30:07.541 11128 11128 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-31 16:30:07.541 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-31 16:30:07.541 11128 11128 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-31 16:30:07.541 11128 11128 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-31 16:30:07.541 11128 11128 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 16:30:07.541 11128 11128 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 16:30:07.541 11128 11128 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-31 16:30:07.541 11128 11128 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 16:30:07.546 11128 11128 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-31 16:30:07.546 11128 11128 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-31 16:30:07.546 11128 11200 I io.jxcore.node.ConnectionHelper: start: OK
,03-31 16:30:07.556 11128 11509 D BluetoothSocket: bindListen(): myUserId = 0
,03-31 16:30:07.561 11128 11509 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-31 16:30:07.566 11128 11509 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[120]}
,03-31 16:30:07.566 11128 11509 D BluetoothSocket: bindListen(), new LocalSocket 
03-31 16:30:07.566 11128 11509 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,03-31 16:30:07.566 11128 11509 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3dc4007c
,03-31 16:30:07.566 11128 11509 D BluetoothSocket: channel: 6
03-31 16:30:07.566 11128 11509 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-31 16:30:07.571 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 16:30:07.571 11128 11200 I jxcore-log: 
,03-31 16:30:07.586 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 16:30:07.586 11128 11200 I jxcore-log: 
,03-31 16:30:07.586 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-31 16:30:07.586 11128 11200 I jxcore-log: 
,03-31 16:30:07.591 11128 11200 I jxcore-log: ok 102 error should be null
03-31 16:30:07.591 11128 11200 I jxcore-log: 
,03-31 16:30:07.591 11128 11200 I jxcore-log: ok 103 error should be null
03-31 16:30:07.591 11128 11200 I jxcore-log: 
,03-31 16:30:07.601 11128 11200 I io.jxcore.node.ConnectionHelper: start: Port number: 59471, start advertisements: true
03-31 16:30:07.601 11128 11200 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 16:30:07.601 11128 11200 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-31 16:30:07.601 11128 11200 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-31 16:30:07.601 11128 11200 I io.jxcore.node.ConnectionHelper: start: OK
,03-31 16:30:07.611 11128 11200 I jxcore-log: ok 104 error should be null
03-31 16:30:07.611 11128 11200 I jxcore-log: 
,03-31 16:30:07.611 11128 11200 I jxcore-log: ok 105 error should be null
03-31 16:30:07.611 11128 11200 I jxcore-log: 
,03-31 16:30:07.621 11128 11200 I jxcore-log: # teardown
03-31 16:30:07.621 11128 11200 I jxcore-log: 
,03-31 16:30:08.431  3440  3618 V AlarmManager: waitForAlarm result :4
,03-31 16:30:08.451  5838  5838 D BtGatt.ScanManager: awakened up at time 249866
,03-31 16:30:08.456  5838  5952 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-31 16:30:08.466  5838  5944 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
03-31 16:30:08.466  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 16:30:08.466  5838  5944 D BtGatt.GattService: current time is 249881152196
03-31 16:30:08.466  5838  5944 D BtGatt.GattService: Batch record : [-3, -30, -40, 105, -46, 71, 1, -128, -77, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, 30, 60, 90, 6, 83, 78, 1, -128, -61, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0]
,03-31 16:30:08.471  5838  5944 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-31 16:30:08.476  5838  5944 D ScanRecord: parseFromBytes
,03-31 16:30:08.486  5838  5944 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-31 16:30:08.486  5838  5944 D ScanRecord: parseFromBytes
03-31 16:30:08.486  5838  5944 D BtGatt.GattService: result: ScanResult{mDevice=4E:53:06:5A:3C:1E, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-61, mTimestampNanos=249881632029}
03-31 16:30:08.486  5838  5944 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-31 16:30:08.486  5838  5944 D BtGatt.GattService: result: ScanResult{mDevice=47:D2:69:D8:E2:FD, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-77, mTimestampNanos=249881632029}
03-31 16:30:08.486  5838  5944 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-31 16:30:08.491 11128 11144 D ScanRecord: parseFromBytes
03-31 16:30:08.491 11128 11144 D ScanRecord: parseFromBytes
03-31 16:30:08.491 11128 11128 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:CF:C5:D9:E5:61], added - the peer count is 1
03-31 16:30:08.491 11128 11128 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 2
03-31 16:30:08.491 11128 11128 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:CF:C5:D9:E5:61], Bluetooth address: F8:CF:C5:D9:E5:61, device name: , device address: 
03-31 16:30:08.491 11128 11128 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
,03-31 16:30:08.496 11128 11200 I jxcore-log: DEBUG createPeerListener: createPeerListener
03-31 16:30:08.496 11128 11200 I jxcore-log: 
,03-31 16:30:08.511  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
03-31 16:30:08.511  3724  3724 I PERF    : received broadcast android.intent.action.TIME_TICK
03-31 16:30:08.511  3724  3724 D KeyguardUpdateMonitor: handleTimeUpdate
03-31 16:30:08.516  3724  3724 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,03-31 16:30:08.521  3724  3724 D SecKeyguardClockView: HomeTimezone(): 1
,03-31 16:30:08.521 11128 11200 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false
03-31 16:30:08.521 11128 11200 I jxcore-log: 
,03-31 16:30:08.526 11128 11200 I jxcore-log: DEBUG createPeerListener: createPeerListener
03-31 16:30:08.526 11128 11200 I jxcore-log: 
,03-31 16:30:08.531  3724  3724 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 16:30:08.531  3724  3724 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,03-31 16:30:08.531 11128 11200 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false
03-31 16:30:08.531 11128 11200 I jxcore-log: 
,03-31 16:30:08.536  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,03-31 16:30:08.571  3724  3724 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 16:30:08.571  3724  3724 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 16:30:08.576  3724  3724 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 16:30:08.581  3724  3724 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 16:30:08.581  3724  3724 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 16:30:08.586  3724  3724 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 16:30:08.601  3724  3724 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 16:30:08.741  3440  6080 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-31 16:30:09.481  3440  3618 V AlarmManager: waitForAlarm result :4
,03-31 16:30:09.496  5838  5838 D BtGatt.ScanManager: awakened up at time 250910
,03-31 16:30:09.501  5838  5952 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-31 16:30:09.516  5838  5944 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
03-31 16:30:09.516  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 16:30:09.516  5838  5944 D BtGatt.GattService: current time is 250930778904,
03-31 16:30:09.516  5838  5944 D BtGatt.GattService: Batch record : [30, 60, 90, 6, 83, 78, 1, -128, -65, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0, -3, -30, -40, 105, -46, 71, 1, -128, -64, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-31 16:30:09.516  5838  5944 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-31 16:30:09.516  5838  5944 D ScanRecord: parseFromBytes,
,03-31 16:30:09.516  5838  5944 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-31 16:30:09.516  5838  5944 D ScanRecord: parseFromBytes
,03-31 16:30:09.516  5838  5944 D BtGatt.GattService: result: ScanResult{mDevice=47:D2:69:D8:E2:FD, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-64, mTimestampNanos=250880953029}
03-31 16:30:09.516  5838  5944 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-31 16:30:09.516  5838  5944 D BtGatt.GattService: result: ScanResult{mDevice=4E:53:06:5A:3C:1E, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-65, mTimestampNanos=250930953029},
03-31 16:30:09.516  5838  5944 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-31 16:30:09.516 11128 11138 D ScanRecord: parseFromBytes,
,03-31 16:30:09.516 11128 11138 D ScanRecord: parseFromBytes
,03-31 16:30:09.516 11128 11128 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
03-31 16:30:09.516 11128 11128 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:CF:C5:D9:E5:61] updated - the peer count is 2
,03-31 16:30:09.696 11128 11200 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 16:30:09.696 11128 11200 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
,03-31 16:30:09.701 11128 11200 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-31 16:30:09.701 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,03-31 16:30:09.701 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,03-31 16:30:09.701 11128 11200 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@77d9481, channel: 6, state: LISTENING
,03-31 16:30:09.706 11128 11200 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@77d9481, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3dc4007c, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@107db926mSocket: android.net.LocalSocket@2d559967 impl:android.net.LocalSocketImpl@2ed9e314 fd:FileDescriptor[120]
,03-31 16:30:09.706 11128 11200 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2d559967 impl:android.net.LocalSocketImpl@2ed9e314 fd:FileDescriptor[120]
,03-31 16:30:09.706 11128 11200 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-31 16:30:09.706 11128 11509 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-31 16:30:09.706 11128 11509 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-31 16:30:09.706 11128 11509 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,03-31 16:30:09.711 11128 11128 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-31 16:30:09.711 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-31 16:30:09.711 11128 11128 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-31 16:30:09.711 11128 11128 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-31 16:30:09.711 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-31 16:30:09.716 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-31 16:30:09.716 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-31 16:30:09.716 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-31 16:30:09.716 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-31 16:30:09.716  5838  9004 D BtGatt.GattService: stopScan() - queue size =1
03-31 16:30:09.721  5838  5952 D BtGatt.ScanManager: filter size is 1
03-31 16:30:09.721  5838  5952 D BtGatt.ScanManager: delete FilterIndex - 4
03-31 16:30:09.721  5838  5944 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-31 16:30:09.721  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 16:30:09.721  5838  5952 D BtGatt.ScanManager: stopping BLe Batch
,03-31 16:30:09.721  5838  5944 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0,
,03-31 16:30:09.721  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,03-31 16:30:09.721  5838  5952 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6,
03-31 16:30:09.726  5838  5944 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
03-31 16:30:09.726  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
03-31 16:30:09.726  5838  5944 D BtGatt.GattService: current time is 251142433737,
,03-31 16:30:09.726  5838  5944 D BtGatt.GattService: Batch record : [-3, -30, -40, 105, -46, 71, 1, -128, -65, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, 30, 60, 90, 6, 83, 78, 1, -128, -65, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0]
03-31 16:30:09.726  5838  5944 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81],
03-31 16:30:09.726  5838  5944 D ScanRecord: parseFromBytes
,03-31 16:30:09.726  5838  5944 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97],
03-31 16:30:09.726  5838  5944 D ScanRecord: parseFromBytes,
,03-31 16:30:09.731  5838  5955 D BtGatt.GattService: unregisterClient() - clientIf=6,
03-31 16:30:09.736 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
,03-31 16:30:09.736 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-31 16:30:09.736 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false,
03-31 16:30:09.736 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-31 16:30:09.736 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING],
03-31 16:30:09.736 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 16:30:09.736 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-31 16:30:09.736  5838  5951 D BtGatt.AdvertiseManager: message : 1
,03-31 16:30:09.741  5838  5951 D BtGatt.AdvertiseManager: stop advertise for client 7
03-31 16:30:09.741  5838  5951 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-31 16:30:09.741  5838  5951 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-31 16:30:09.741  5838  5944 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-31 16:30:09.741  5838  5944 D BtGatt.GattService: Client app is not null!
,03-31 16:30:09.741  5838  9004 D BtGatt.GattService: unregisterClient() - clientIf=7
03-31 16:30:09.746 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 16:30:09.746 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-31 16:30:09.746 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-31 16:30:09.746 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,03-31 16:30:09.746 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-31 16:30:09.746 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 16:30:09.746 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 16:30:09.746 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-31 16:30:09.746 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
,03-31 16:30:09.746 11128 11200 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
,03-31 16:30:09.746 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 16:30:09.751 11128 11128 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 16:30:09.751 11128 11128 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-31 16:30:09.751 11128 11128 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
,03-31 16:30:09.751 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 16:30:09.751 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-31 16:30:09.756 11128 11128 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-31 16:30:09.761 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-31 16:30:09.761 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 16:30:09.761 11128 11128 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 16:30:09.761 11128 11200 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 16:30:09.761 11128 11200 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 16:30:09.761 11128 11200 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-31 16:30:09.771 11128 11128 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-31 16:30:09.771 11128 11128 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 16:30:09.771 11128 11128 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 16:30:09.781 11128 11200 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,03-31 16:30:09.781 11128 11200 I jxcore-log: 
,03-31 16:30:09.781 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-31 16:30:09.781 11128 11200 I jxcore-log: 
,03-31 16:30:09.781 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
03-31 16:30:09.781 11128 11200 I jxcore-log: 
03-31 16:30:09.786 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 16:30:09.786 11128 11200 I jxcore-log: 
,03-31 16:30:09.791 11128 11200 I jxcore-log: ok 106 error should be null
03-31 16:30:09.791 11128 11200 I jxcore-log: 
,03-31 16:30:09.791 11128 11200 I jxcore-log: ok 107 error should be null
03-31 16:30:09.791 11128 11200 I jxcore-log: 
,03-31 16:30:09.801 11128 11200 I jxcore-log: # setup
03-31 16:30:09.801 11128 11200 I jxcore-log: 
,03-31 16:30:09.956 11128 11200 I jxcore-log: # 29. should be able to call #stopAdvertisingAndListening many times
03-31 16:30:09.956 11128 11200 I jxcore-log: 
,03-31 16:30:10.086 11128 11200 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 16:30:10.086 11128 11200 I jxcore-log: 
,03-31 16:30:10.091 11128 11200 I jxcore-log: DEBUG createNativeListener: listening 40753
03-31 16:30:10.091 11128 11200 I jxcore-log: 
,03-31 16:30:10.096 11128 11200 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 16:30:10.096 11128 11200 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-31 16:30:10.096 11128 11200 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 16:30:10.101 11128 11200 I jxcore-log: ok 108 error should be null,
03-31 16:30:10.101 11128 11200 I jxcore-log: 
,03-31 16:30:10.106 11128 11200 I jxcore-log: ok 109 error should be null
03-31 16:30:10.106 11128 11200 I jxcore-log: 
,03-31 16:30:10.111 11128 11200 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 16:30:10.111 11128 11200 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-31 16:30:10.111 11128 11200 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 16:30:10.116 11128 11200 I jxcore-log: ok 110 error should be null
03-31 16:30:10.116 11128 11200 I jxcore-log: 
03-31 16:30:10.116 11128 11200 I jxcore-log: ok 111 error should be null
03-31 16:30:10.116 11128 11200 I jxcore-log: 
,03-31 16:30:10.121 11128 11200 I jxcore-log: # teardown
03-31 16:30:10.121 11128 11200 I jxcore-log: 
,03-31 16:30:10.301 11128 11200 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 16:30:10.306 11128 11200 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-31 16:30:10.306 11128 11200 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 16:30:10.311 11128 11200 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 16:30:10.311 11128 11200 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-31 16:30:10.311 11128 11200 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 16:30:10.321 11128 11200 I jxcore-log: ok 112 error should be null
03-31 16:30:10.321 11128 11200 I jxcore-log: 
,03-31 16:30:10.321 11128 11200 I jxcore-log: ok 113 error should be null
03-31 16:30:10.321 11128 11200 I jxcore-log: 
,03-31 16:30:10.331 11128 11200 I jxcore-log: # setup
03-31 16:30:10.331 11128 11200 I jxcore-log: 
,03-31 16:30:10.461 11128 11200 I jxcore-log: # 30. #start should fail if called twice in a row
03-31 16:30:10.461 11128 11200 I jxcore-log: 
,03-31 16:30:10.636 11128 11200 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 16:30:10.636 11128 11200 I jxcore-log: 
,03-31 16:30:10.646 11128 11200 I jxcore-log: DEBUG createNativeListener: listening 35407
03-31 16:30:10.646 11128 11200 I jxcore-log: 
,03-31 16:30:10.651 11128 11200 I jxcore-log: ok 114 first call should succeed
03-31 16:30:10.651 11128 11200 I jxcore-log: 
,03-31 16:30:10.651 11128 11200 I jxcore-log: ok 115 first call should succeed
03-31 16:30:10.651 11128 11200 I jxcore-log: 
,03-31 16:30:10.656 11128 11200 I jxcore-log: ok 116 specific error should be returned
03-31 16:30:10.656 11128 11200 I jxcore-log: 
,03-31 16:30:10.661 11128 11200 I jxcore-log: # teardown
03-31 16:30:10.661 11128 11200 I jxcore-log: 
,03-31 16:30:10.751 11128 11200 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-31 16:30:10.751 11128 11200 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 16:30:10.751 11128 11200 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 16:30:10.756 11128 11200 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 16:30:10.756 11128 11200 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 16:30:10.756 11128 11200 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 16:30:10.766 11128 11200 I jxcore-log: ok 117 error should be null
03-31 16:30:10.766 11128 11200 I jxcore-log: 
,03-31 16:30:10.766 11128 11200 I jxcore-log: ok 118 error should be null
03-31 16:30:10.766 11128 11200 I jxcore-log: 
,03-31 16:30:10.781 11128 11200 I jxcore-log: # setup
03-31 16:30:10.781 11128 11200 I jxcore-log: 
,03-31 16:30:10.916 11128 11200 I jxcore-log: # 31. does not emit duplicate discoveryAdvertisingStateUpdate
03-31 16:30:10.916 11128 11200 I jxcore-log: 
,03-31 16:30:11.076 11128 11200 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 16:30:11.076 11128 11200 I jxcore-log: 
,03-31 16:30:11.081 11128 11200 I jxcore-log: DEBUG createNativeListener: listening 60722
03-31 16:30:11.081 11128 11200 I jxcore-log: 
,03-31 16:30:11.091 11128 11200 I io.jxcore.node.ConnectionHelper: start: Port number: 59471, start advertisements: false
,03-31 16:30:11.091 11128 11200 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-31 16:30:11.091 11128 11200 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 16:30:11.091 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-31 16:30:11.096 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-31 16:30:11.096 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-31 16:30:11.096 11128 11200 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 16:30:11.101  5838  9004 D BtGatt.GattService: registerClient() - UUID=f586e885-4d51-4128-82e5-5bf57ce41651
,03-31 16:30:11.146  5838  5944 D BtGatt.GattService: onClientRegistered() - UUID=f586e885-4d51-4128-82e5-5bf57ce41651, clientIf=6
03-31 16:30:11.146 11128 11144 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-31 16:30:11.146  5838  5955 D BtGatt.GattService: start scan with filters
,03-31 16:30:11.156  5838  5955 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 67
,03-31 16:30:11.156  5838  5952 D BtGatt.ScanManager: handling starting scan
03-31 16:30:11.156  5838  5952 D BtGatt.ScanManager: isFilteringSupported
03-31 16:30:11.156  5838  5952 D BluetoothAdapter: setting StandAloneBleMode
,03-31 16:30:11.166  5838  5944 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-31 16:30:11.166  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 16:30:11.166  5838  5952 D BtGatt.ScanManager: allow scan with filters
03-31 16:30:11.166  5838  5952 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-31 16:30:11.166  5838  5952 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
03-31 16:30:11.171  5838  5944 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-31 16:30:11.171  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 16:30:11.171  5838  5952 D BtGatt.ScanManager: Starting BLE batch scan
03-31 16:30:11.171  5838  5952 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-31 16:30:11.176  5838  5944 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0,
03-31 16:30:11.176  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 16:30:11.181  5838  5944 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-31 16:30:11.181  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 16:30:11.181 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 16:30:11.181 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 16:30:11.181 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-31 16:30:11.181 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 16:30:11.181 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 16:30:11.181 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-31 16:30:11.181 11128 11128 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-31 16:30:11.186 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-31 16:30:11.186 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 16:30:11.186 11128 11200 I io.jxcore.node.ConnectionHelper: start: OK
03-31 16:30:11.186 11128 11128 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,03-31 16:30:11.186 11128 11128 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 16:30:11.186 11128 11128 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-31 16:30:11.196 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 16:30:11.196 11128 11200 I jxcore-log: 
,03-31 16:30:11.196 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 16:30:11.196 11128 11200 I jxcore-log: 
,03-31 16:30:11.216 11128 11200 I io.jxcore.node.ConnectionHelper: start: Port number: 60722, start advertisements: true
03-31 16:30:11.216 11128 11200 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-31 16:30:11.216 11128 11200 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-31 16:30:11.216 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-31 16:30:11.221 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-31 16:30:11.221 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
03-31 16:30:11.221 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 16:30:11.221 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-31 16:30:11.221 11128 11200 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-31 16:30:11.221 11128 11200 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 16:30:11.221 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 16:30:11.221 11128 11200 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-31 16:30:11.226  5838  5955 D BtGatt.GattService: registerClient() - UUID=30e1581f-86a5-43eb-b1be-46f1335f8bad
,03-31 16:30:11.266  5838  5944 D BtGatt.GattService: onClientRegistered() - UUID=30e1581f-86a5-43eb-b1be-46f1335f8bad, clientIf=7
,03-31 16:30:11.271 11128 11138 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-31 16:30:11.316  5838  5850 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 53
,03-31 16:30:11.316  5838  5951 D BtGatt.AdvertiseManager: message : 0
,03-31 16:30:11.321  5838  5951 D BtGatt.AdvertiseManager: number of adv instance running0
03-31 16:30:11.321  5838  5951 D BtGatt.AdvertiseManager: size of list is =0
,03-31 16:30:11.326  5838  5951 D BtGatt.AdvertiseManager: starting advertising
,03-31 16:30:11.326  5838  5951 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-31 16:30:11.331  5838  5944 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-31 16:30:11.331  5838  5951 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 16:30:11.336  5838  5944 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-31 16:30:11.336  5838  5951 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,03-31 16:30:11.336  5838  5951 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0,
,03-31 16:30:11.341 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-31 16:30:11.341 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-31 16:30:11.341 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-31 16:30:11.341 11128 11128 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-31 16:30:11.341 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-31 16:30:11.341 11128 11128 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
,03-31 16:30:11.341 11128 11128 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-31 16:30:11.346 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 16:30:11.346 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 16:30:11.346 11128 11128 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-31 16:30:11.346 11128 11200 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-31 16:30:11.346 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 16:30:11.346 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-31 16:30:11.346 11128 11200 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-31 16:30:11.346 11128 11200 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-31 16:30:11.346 11128 11200 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-31 16:30:11.351 11128 11128 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything,
03-31 16:30:11.351 11128 11128 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 16:30:11.351 11128 11128 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING,
03-31 16:30:11.351 11128 11200 I io.jxcore.node.ConnectionHelper: start: OK
,03-31 16:30:11.361 11128 11560 D BluetoothSocket: bindListen(): myUserId = 0,
03-31 16:30:11.361 11128 11560 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-31 16:30:11.361 11128 11560 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[121]},
03-31 16:30:11.361 11128 11560 D BluetoothSocket: bindListen(), new LocalSocket 
,03-31 16:30:11.366 11128 11560 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,03-31 16:30:11.366 11128 11560 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@34fc1c80
,03-31 16:30:11.366 11128 11560 D BluetoothSocket: channel: 6
03-31 16:30:11.366 11128 11560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...,
,03-31 16:30:11.371  3440  3862 E Watchdog: !@Sync 8 [03-31 16:30:11.379]
,03-31 16:30:11.381 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-31 16:30:11.381 11128 11200 I jxcore-log: 
,03-31 16:30:11.386 11128 11200 I jxcore-log: ok 119 called only once
03-31 16:30:11.386 11128 11200 I jxcore-log: 
,03-31 16:30:11.391 11128 11200 I jxcore-log: ok 120 discovery state matches
03-31 16:30:11.391 11128 11200 I jxcore-log: 
,03-31 16:30:11.391 11128 11200 I jxcore-log: ok 121 advertising state matches
03-31 16:30:11.391 11128 11200 I jxcore-log: 
,03-31 16:30:11.401 11128 11200 I jxcore-log: # teardown
03-31 16:30:11.401 11128 11200 I jxcore-log: 
,03-31 16:30:11.661 11128 11200 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 16:30:11.661 11128 11200 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
,03-31 16:30:11.661 11128 11200 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,03-31 16:30:11.666 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,03-31 16:30:11.666 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-31 16:30:11.666 11128 11200 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2b0752b9, channel: 6, state: LISTENING
,03-31 16:30:11.666 11128 11200 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2b0752b9, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@34fc1c80, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@168c6femSocket: android.net.LocalSocket@2cb24e5f impl:android.net.LocalSocketImpl@184680ac fd:FileDescriptor[121]
,03-31 16:30:11.666 11128 11200 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2cb24e5f impl:android.net.LocalSocketImpl@184680ac fd:FileDescriptor[121]
,03-31 16:30:11.666 11128 11200 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-31 16:30:11.671 11128 11560 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close,
03-31 16:30:11.671 11128 11560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-31 16:30:11.671 11128 11560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,03-31 16:30:11.671 11128 11128 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-31 16:30:11.671 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-31 16:30:11.671 11128 11128 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-31 16:30:11.671 11128 11128 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-31 16:30:11.676 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...,
03-31 16:30:11.676 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-31 16:30:11.676 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-31 16:30:11.676 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-31 16:30:11.676 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-31 16:30:11.676  5838  9004 D BtGatt.GattService: stopScan() - queue size =1,
03-31 16:30:11.676  5838  5952 D BtGatt.ScanManager: filter size is 1
03-31 16:30:11.676  5838  5952 D BtGatt.ScanManager: delete FilterIndex - 5
,03-31 16:30:11.681  5838  5944 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16,
,03-31 16:30:11.681  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,03-31 16:30:11.681  5838  5952 D BtGatt.ScanManager: stopping BLe Batch,
03-31 16:30:11.681  5838  5944 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,03-31 16:30:11.681  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
03-31 16:30:11.681  5838  5952 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6,
,03-31 16:30:11.686  5838  5944 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2,
03-31 16:30:11.686  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 16:30:11.686  5838  5944 D BtGatt.GattService: current time is 253101140571
,03-31 16:30:11.686  5838  5944 D BtGatt.GattService: Batch record : [-104, 45, -117, -88, -22, 103, 1, -128, -81, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -3, 37, 79, 24, -59, 70, 1, -128, -69, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0],
,03-31 16:30:11.686  5838  5944 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-31 16:30:11.686  5838  5944 D ScanRecord: parseFromBytes,
,03-31 16:30:11.686  5838  5944 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
,03-31 16:30:11.686  5838  5944 D ScanRecord: parseFromBytes
03-31 16:30:11.686  5838  5955 D BtGatt.GattService: unregisterClient() - clientIf=6
03-31 16:30:11.691 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-31 16:30:11.691 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 16:30:11.691 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-31 16:30:11.691 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-31 16:30:11.691 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
,03-31 16:30:11.691 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 16:30:11.691 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-31 16:30:11.696  5838  5951 D BtGatt.AdvertiseManager: message : 1
03-31 16:30:11.696  5838  5951 D BtGatt.AdvertiseManager: stop advertise for client 7
03-31 16:30:11.696  5838  5951 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
,03-31 16:30:11.696  5838  5951 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-31 16:30:11.696  5838  5944 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-31 16:30:11.701  5838  5944 D BtGatt.GattService: Client app is not null!
03-31 16:30:11.701  5838  9004 D BtGatt.GattService: unregisterClient() - clientIf=7,
,03-31 16:30:11.701 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-31 16:30:11.701 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-31 16:30:11.701 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,03-31 16:30:11.701 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-31 16:30:11.701 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-31 16:30:11.701 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 16:30:11.701 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped,
03-31 16:30:11.701 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-31 16:30:11.706 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-31 16:30:11.706 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 16:30:11.706 11128 11128 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 16:30:11.706 11128 11128 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-31 16:30:11.706 11128 11128 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 16:30:11.706 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 16:30:11.706 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-31 16:30:11.711 11128 11128 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-31 16:30:11.716 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-31 16:30:11.716 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 16:30:11.716 11128 11128 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
03-31 16:30:11.721 11128 11200 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 16:30:11.721 11128 11200 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 16:30:11.721 11128 11200 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-31 16:30:11.721 11128 11200 I jxcore-log: INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
03-31 16:30:11.721 11128 11200 I jxcore-log: 
03-31 16:30:11.721 11128 11200 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-31 16:30:11.721 11128 11200 I jxcore-log: 
03-31 16:30:11.731 11128 11128 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-31 16:30:11.731 11128 11128 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 16:30:11.731 11128 11128 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 16:30:11.741 11128 11200 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-31 16:30:11.741 11128 11200 I jxcore-log: 
,03-31 16:30:11.746 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-31 16:30:11.746 11128 11200 I jxcore-log: 
,03-31 16:30:11.751 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 16:30:11.751 11128 11200 I jxcore-log: 
,03-31 16:30:11.751 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 16:30:11.751 11128 11200 I jxcore-log: 
,03-31 16:30:11.756 11128 11200 I jxcore-log: ok 122 error should be null
03-31 16:30:11.756 11128 11200 I jxcore-log: 
,03-31 16:30:11.756 11128 11200 I jxcore-log: ok 123 error should be null
03-31 16:30:11.756 11128 11200 I jxcore-log: 
,03-31 16:30:11.761 11128 11200 I jxcore-log: # setup
03-31 16:30:11.761 11128 11200 I jxcore-log: 
,03-31 16:30:11.891 11128 11200 I jxcore-log: # 32. does not send duplicate availability changes
03-31 16:30:11.891 11128 11200 I jxcore-log: 
,03-31 16:30:12.041 11128 11200 I jxcore-log: ok 124 should be called once
03-31 16:30:12.041 11128 11200 I jxcore-log: 
,03-31 16:30:12.046 11128 11200 I jxcore-log: ok 125 should not have been called more than once
03-31 16:30:12.046 11128 11200 I jxcore-log: 
,03-31 16:30:12.051 11128 11200 I jxcore-log: # teardown
03-31 16:30:12.051 11128 11200 I jxcore-log: 
,03-31 16:30:12.141 11128 11200 I jxcore-log: ok 126 error should be null
03-31 16:30:12.141 11128 11200 I jxcore-log: 
,03-31 16:30:12.141 11128 11200 I jxcore-log: ok 127 error should be null
03-31 16:30:12.141 11128 11200 I jxcore-log: 
,03-31 16:30:12.146 11128 11200 I jxcore-log: # setup
03-31 16:30:12.146 11128 11200 I jxcore-log: 
,03-31 16:30:12.291 11128 11200 I jxcore-log: # 33. can get the network status
03-31 16:30:12.291 11128 11200 I jxcore-log: 
,03-31 16:30:12.416 11128 11200 I jxcore-log: ok 128 network status should have certain non-empty properties
03-31 16:30:12.416 11128 11200 I jxcore-log: 
,03-31 16:30:12.421 11128 11200 I jxcore-log: # teardown
03-31 16:30:12.421 11128 11200 I jxcore-log: 
,03-31 16:30:12.576 11128 11200 I jxcore-log: ok 129 error should be null
03-31 16:30:12.576 11128 11200 I jxcore-log: 
,03-31 16:30:12.576 11128 11200 I jxcore-log: ok 130 error should be null
03-31 16:30:12.576 11128 11200 I jxcore-log: 
,03-31 16:30:12.596 11128 11200 I jxcore-log: # setup
03-31 16:30:12.596 11128 11200 I jxcore-log: 
,03-31 16:30:12.786 11128 11200 I jxcore-log: # 34. wifi peer is marked unavailable if announcements stop
03-31 16:30:12.786 11128 11200 I jxcore-log: 
,03-31 16:30:12.961 11128 11200 I jxcore-log: ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
03-31 16:30:12.961 11128 11200 I jxcore-log: 
,03-31 16:30:13.001 11128 11200 I jxcore-log: ok 131 host address should match
03-31 16:30:13.001 11128 11200 I jxcore-log: 
,03-31 16:30:13.001 11128 11200 I jxcore-log: ok 132 port should match
03-31 16:30:13.001 11128 11200 I jxcore-log: 
,03-31 16:30:14.511  3440  3946 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 16:30:14.511  3440  3946 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 16:30:14.511  3440  3946 D BatteryService: online:4, current avg:37, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
03-31 16:30:14.511  3440  3946 D BatteryService: stay LED for fully charged
03-31 16:30:14.511  3440  3440 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 16:30:14.516  3440  3440 I MotionRecognitionService: Plugged
,03-31 16:30:14.516  3440  3440 D MotionRecognitionService:   cableConnection= 1
03-31 16:30:14.516  3440  3440 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 16:30:14.516  3440  3440 D MotionRecognitionService: skip setTransmitPower. 
,03-31 16:30:14.521  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 16:30:14.521  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 16:30:14.521  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 16:30:14.521  2895  4732 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-31 16:30:14.531  5838  5838 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-31 16:30:14.531  5838  5954 D HeadsetStateMachine: Disconnected process message: 10
,03-31 16:30:14.546  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 16:30:14.546  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 16:30:14.546  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 16:30:14.546  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 16:30:14.976 11128 11200 I jxcore-log: ok 133 host address should be null
03-31 16:30:14.976 11128 11200 I jxcore-log: 
,03-31 16:30:14.981 11128 11200 I jxcore-log: ok 134 port should should be null
03-31 16:30:14.981 11128 11200 I jxcore-log: 
,03-31 16:30:15.011 11128 11200 I jxcore-log: # teardown
03-31 16:30:15.011 11128 11200 I jxcore-log: 
,03-31 16:30:15.081 11128 11200 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-31 16:30:15.081 11128 11200 I jxcore-log: 
,03-31 16:30:15.086 11128 11200 I jxcore-log: ok 135 error should be null
03-31 16:30:15.086 11128 11200 I jxcore-log: 
,03-31 16:30:15.086 11128 11200 I jxcore-log: ok 136 error should be null
03-31 16:30:15.086 11128 11200 I jxcore-log: 
,03-31 16:30:15.086 11128 11200 I jxcore-log: # setup
03-31 16:30:15.086 11128 11200 I jxcore-log: 
,03-31 16:30:15.246 11128 11200 I jxcore-log: # 35. Can call start/stopListeningForAdvertisements
03-31 16:30:15.246 11128 11200 I jxcore-log: 
,03-31 16:30:15.391 11128 11200 I io.jxcore.node.ConnectionHelper: start: Port number: 60722, start advertisements: false
03-31 16:30:15.391 11128 11200 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 16:30:15.391 11128 11200 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 16:30:15.391 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-31 16:30:15.406 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 16:30:15.406 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 16:30:15.406 11128 11200 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 16:30:15.416  5838  5955 D BtGatt.GattService: registerClient() - UUID=93f364a6-0229-4f80-8f92-def6d93873b8
,03-31 16:30:15.461  5838  5944 D BtGatt.GattService: onClientRegistered() - UUID=93f364a6-0229-4f80-8f92-def6d93873b8, clientIf=6
03-31 16:30:15.461 11128 11138 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-31 16:30:15.461  5838  5850 D BtGatt.GattService: start scan with filters
,03-31 16:30:15.476  5838  5850 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 68
,03-31 16:30:15.476  5838  5952 D BtGatt.ScanManager: handling starting scan
03-31 16:30:15.476  5838  5952 D BtGatt.ScanManager: isFilteringSupported
03-31 16:30:15.476  5838  5952 D BluetoothAdapter: setting StandAloneBleMode
,03-31 16:30:15.491  5838  5944 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-31 16:30:15.491  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 16:30:15.491  5838  5952 D BtGatt.ScanManager: allow scan with filters
03-31 16:30:15.491  5838  5952 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-31 16:30:15.491  5838  5952 D BtGatt.ScanManager: set filter index= 6 for clientIf= 6
03-31 16:30:15.491  5838  5944 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-31 16:30:15.491  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 16:30:15.496  5838  5952 D BtGatt.ScanManager: Starting BLE batch scan
,03-31 16:30:15.496  5838  5952 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-31 16:30:15.496  5838  5944 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-31 16:30:15.496  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 16:30:15.501  5838  5944 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1,
03-31 16:30:15.501  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 16:30:15.501 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 16:30:15.501 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 16:30:15.501 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING],
,03-31 16:30:15.501 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 16:30:15.501 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,03-31 16:30:15.501 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-31 16:30:15.501 11128 11128 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 16:30:15.516 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 16:30:15.516 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK,
03-31 16:30:15.516 11128 11128 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 16:30:15.516 11128 11128 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-31 16:30:15.516 11128 11128 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 16:30:15.516 11128 11200 I io.jxcore.node.ConnectionHelper: start: OK
03-31 16:30:15.521 11128 11200 I jxcore-log: ok 137 Can call startListeningForAdvertisements without error
03-31 16:30:15.521 11128 11200 I jxcore-log: 
03-31 16:30:15.521 11128 11200 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 16:30:15.521 11128 11200 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 16:30:15.521 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-31 16:30:15.521 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-31 16:30:15.526  5838  5848 D BtGatt.GattService: stopScan() - queue size =1
,03-31 16:30:15.531  5838  5952 D BtGatt.ScanManager: filter size is 1
03-31 16:30:15.531  5838  5952 D BtGatt.ScanManager: delete FilterIndex - 6
03-31 16:30:15.531  5838  9004 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-31 16:30:15.531 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 16:30:15.531  5838  5944 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-31 16:30:15.531  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 16:30:15.531 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED,
,03-31 16:30:15.531 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-31 16:30:15.531 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-31 16:30:15.531 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-31 16:30:15.531 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 16:30:15.531  5838  5952 D BtGatt.ScanManager: stopping BLe Batch
03-31 16:30:15.531 11128 11128 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 16:30:15.531 11128 11128 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-31 16:30:15.531 11128 11128 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 16:30:15.536 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 16:30:15.536 11128 11200 I jxcore-log: 
03-31 16:30:15.536  5838  5944 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-31 16:30:15.536  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 16:30:15.536  5838  5952 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-31 16:30:15.536 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 16:30:15.536 11128 11200 I jxcore-log: 
03-31 16:30:15.536  5838  5944 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-31 16:30:15.536  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 16:30:15.541 11128 11200 I jxcore-log: ok 138 Can call stopListeningForAdvertisements without error
03-31 16:30:15.541 11128 11200 I jxcore-log: 
,03-31 16:30:15.551 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 16:30:15.551 11128 11200 I jxcore-log: 
,03-31 16:30:15.551 11128 11200 I jxcore-log: # teardown
03-31 16:30:15.551 11128 11200 I jxcore-log: 
,03-31 16:30:15.626  3440  6049 D SSRM:n  : SIOP:: AP = 270, PST = 275 (W:12), CUR = 37, LCD = 0
,03-31 16:30:15.646 11128 11200 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 16:30:15.646 11128 11200 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 16:30:15.646 11128 11200 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 16:30:15.651 11128 11200 I jxcore-log: ok 139 Should be able to call stopListeningForAdvertisments in teardown
03-31 16:30:15.651 11128 11200 I jxcore-log: 
,03-31 16:30:15.656 11128 11200 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 16:30:15.656 11128 11200 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 16:30:15.656 11128 11200 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-31 16:30:15.656 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-31 16:30:15.656 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-31 16:30:15.656 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-31 16:30:15.656 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-31 16:30:15.656 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-31 16:30:15.661 11128 11200 D BluetoothLeScanner: could not find callback wrapper
,03-31 16:30:15.661 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-31 16:30:15.661 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-31 16:30:15.666 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 16:30:15.666 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-31 16:30:15.666 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-31 16:30:15.666 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 16:30:15.666 11128 11128 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
03-31 16:30:15.666 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 16:30:15.666 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-31 16:30:15.676 11128 11128 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-31 16:30:15.686 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-31 16:30:15.686 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-31 16:30:15.686 11128 11128 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 16:30:15.691 11128 11128 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 16:30:15.691 11128 11128 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 16:30:15.696 11128 11128 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-31 16:30:15.696 11128 11200 I jxcore-log: ok 140 Should be able to call stopAdvertisingAndListening in teardown
03-31 16:30:15.696 11128 11200 I jxcore-log: 
,03-31 16:30:15.706 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 16:30:15.706 11128 11200 I jxcore-log: 
,03-31 16:30:15.706 11128 11200 I jxcore-log: # setup
03-31 16:30:15.706 11128 11200 I jxcore-log: 
,03-31 16:30:15.791 11128 11200 I jxcore-log: # 36. Calling startListeningForAdvertisements twice is NOT an error
03-31 16:30:15.791 11128 11200 I jxcore-log: 
,03-31 16:30:15.926 11128 11200 I io.jxcore.node.ConnectionHelper: start: Port number: 60722, start advertisements: false
03-31 16:30:15.926 11128 11200 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 16:30:15.926 11128 11200 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 16:30:15.926 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-31 16:30:15.931 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 16:30:15.931 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 16:30:15.931 11128 11200 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 16:30:15.936  5838  5955 D BtGatt.GattService: registerClient() - UUID=e4da6865-de25-4f92-b7cb-3925b668c89e
,03-31 16:30:15.976  5838  5944 D BtGatt.GattService: onClientRegistered() - UUID=e4da6865-de25-4f92-b7cb-3925b668c89e, clientIf=6,
03-31 16:30:15.976 11128 11138 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-31 16:30:15.976  5838  5848 D BtGatt.GattService: start scan with filters
,03-31 16:30:15.996  5838  5848 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 69
,03-31 16:30:15.996  5838  5952 D BtGatt.ScanManager: handling starting scan
03-31 16:30:15.996  5838  5952 D BtGatt.ScanManager: isFilteringSupported
03-31 16:30:15.996  5838  5952 D BluetoothAdapter: setting StandAloneBleMode
,03-31 16:30:16.001  5838  5944 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-31 16:30:16.001  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 16:30:16.001  5838  5952 D BtGatt.ScanManager: allow scan with filters
03-31 16:30:16.001  5838  5952 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-31 16:30:16.001  5838  5952 D BtGatt.ScanManager: set filter index= 7 for clientIf= 6
03-31 16:30:16.006  5838  5944 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-31 16:30:16.006  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 16:30:16.006  5838  5952 D BtGatt.ScanManager: Starting BLE batch scan
03-31 16:30:16.006  5838  5952 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-31 16:30:16.011  5838  5944 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-31 16:30:16.011  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 16:30:16.011  5838  5944 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1,
03-31 16:30:16.011  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 16:30:16.016 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
03-31 16:30:16.016 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 16:30:16.016 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-31 16:30:16.016 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 16:30:16.016 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 16:30:16.016 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-31 16:30:16.016 11128 11128 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false,
03-31 16:30:16.016 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 16:30:16.016 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 16:30:16.021 11128 11128 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 16:30:16.021 11128 11128 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 16:30:16.021 11128 11128 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 16:30:16.021 11128 11200 I io.jxcore.node.ConnectionHelper: start: OK
03-31 16:30:16.021 11128 11200 I jxcore-log: ok 141 Can call startListeningForAdvertisements without error
03-31 16:30:16.021 11128 11200 I jxcore-log: 
,03-31 16:30:16.031 11128 11200 I io.jxcore.node.ConnectionHelper: start: Port number: 60722, start advertisements: false
,03-31 16:30:16.036 11128 11200 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 16:30:16.036 11128 11200 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 16:30:16.036 11128 11200 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-31 16:30:16.036 11128 11200 I io.jxcore.node.ConnectionHelper: start: OK
,03-31 16:30:16.036 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 16:30:16.036 11128 11200 I jxcore-log: 
,03-31 16:30:16.041 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 16:30:16.041 11128 11200 I jxcore-log: 
,03-31 16:30:16.041 11128 11200 I jxcore-log: ok 142 Can call startListeningForAdvertisements twice without error
03-31 16:30:16.041 11128 11200 I jxcore-log: 
,03-31 16:30:16.051 11128 11200 I jxcore-log: # teardown
03-31 16:30:16.051 11128 11200 I jxcore-log: 
,03-31 16:30:16.211 11128 11200 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 16:30:16.211 11128 11200 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 16:30:16.211 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,03-31 16:30:16.211 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-31 16:30:16.216  5838  5850 D BtGatt.GattService: stopScan() - queue size =1
03-31 16:30:16.216  5838  5952 D BtGatt.ScanManager: filter size is 1
03-31 16:30:16.216  5838  5952 D BtGatt.ScanManager: delete FilterIndex - 7
03-31 16:30:16.216  5838  5944 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-31 16:30:16.216  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 16:30:16.221  5838  5952 D BtGatt.ScanManager: stopping BLe Batch
,03-31 16:30:16.221  5838  5944 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0,
03-31 16:30:16.221  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 16:30:16.221  5838  5955 D BtGatt.GattService: unregisterClient() - clientIf=6
03-31 16:30:16.226  5838  5952 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-31 16:30:16.226  5838  5944 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-31 16:30:16.226  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 16:30:16.231 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 16:30:16.231 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 16:30:16.231 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-31 16:30:16.231 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,03-31 16:30:16.231 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-31 16:30:16.231 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 16:30:16.231 11128 11128 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 16:30:16.231 11128 11128 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 16:30:16.231 11128 11128 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-31 16:30:16.236 11128 11200 I jxcore-log: ok 143 Should be able to call stopListeningForAdvertisments in teardown
03-31 16:30:16.236 11128 11200 I jxcore-log: 
,03-31 16:30:16.236 11128 11200 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 16:30:16.241 11128 11200 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 16:30:16.241 11128 11200 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-31 16:30:16.241 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-31 16:30:16.241 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-31 16:30:16.241 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-31 16:30:16.241 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-31 16:30:16.241 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-31 16:30:16.241 11128 11200 D BluetoothLeScanner: could not find callback wrapper
,03-31 16:30:16.241 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-31 16:30:16.246 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 16:30:16.246 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 16:30:16.246 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-31 16:30:16.246 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-31 16:30:16.246 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 16:30:16.246 11128 11128 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 16:30:16.246 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 16:30:16.246 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-31 16:30:16.256 11128 11128 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-31 16:30:16.261 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-31 16:30:16.261 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-31 16:30:16.266 11128 11128 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 16:30:16.266 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 16:30:16.266 11128 11200 I jxcore-log: 
,03-31 16:30:16.271 11128 11128 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 16:30:16.271 11128 11128 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-31 16:30:16.271 11128 11128 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-31 16:30:16.271 11128 11200 I jxcore-log: ok 144 Should be able to call stopAdvertisingAndListening in teardown
03-31 16:30:16.271 11128 11200 I jxcore-log: 
,03-31 16:30:16.281 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 16:30:16.281 11128 11200 I jxcore-log: 
,03-31 16:30:16.286 11128 11200 I jxcore-log: # setup
03-31 16:30:16.286 11128 11200 I jxcore-log: 
,03-31 16:30:16.391 11128 11200 I jxcore-log: # 37. Can call start/stopUpdateAdvertisingAndListening
03-31 16:30:16.391 11128 11200 I jxcore-log: 
,03-31 16:30:16.576 11128 11200 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true
,03-31 16:30:16.576 11128 11200 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-31 16:30:16.576 11128 11200 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,03-31 16:30:16.576 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-31 16:30:16.581 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-31 16:30:16.581 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 16:30:16.581 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-31 16:30:16.581 11128 11200 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 16:30:16.586  5838  9004 D BtGatt.GattService: registerClient() - UUID=99731756-6d9a-4d76-8e2e-74122cd48d74
,03-31 16:30:16.631  5838  5944 D BtGatt.GattService: onClientRegistered() - UUID=99731756-6d9a-4d76-8e2e-74122cd48d74, clientIf=6
,03-31 16:30:16.631 11128 11138 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-31 16:30:16.631  5838  5850 D BtGatt.GattService: start scan with filters
,03-31 16:30:16.716  5838  5850 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 70
,03-31 16:30:16.716  5838  5952 D BtGatt.ScanManager: handling starting scan
03-31 16:30:16.716  5838  5952 D BtGatt.ScanManager: isFilteringSupported
03-31 16:30:16.716  5838  5952 D BluetoothAdapter: setting StandAloneBleMode
,03-31 16:30:16.726  5838  5944 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-31 16:30:16.726  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 16:30:16.726  5838  5952 D BtGatt.ScanManager: allow scan with filters
03-31 16:30:16.726  5838  5952 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-31 16:30:16.726  5838  5952 D BtGatt.ScanManager: set filter index= 8 for clientIf= 6
03-31 16:30:16.731  5838  5944 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-31 16:30:16.731  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 16:30:16.731 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 16:30:16.731 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 16:30:16.731 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-31 16:30:16.731 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 16:30:16.731 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 16:30:16.731 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 16:30:16.731 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-31 16:30:16.731 11128 11200 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-31 16:30:16.731 11128 11200 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 16:30:16.731 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 16:30:16.731 11128 11200 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-31 16:30:16.731 11128 11128 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 16:30:16.736  5838  5955 D BtGatt.GattService: registerClient() - UUID=1f95ae08-33c2-46de-9b48-59f747b2d6b1
,03-31 16:30:16.741  5838  5952 D BtGatt.ScanManager: Starting BLE batch scan
03-31 16:30:16.741  5838  5952 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-31 16:30:16.741  5838  5944 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-31 16:30:16.741  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 16:30:16.746  5838  5944 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-31 16:30:16.746  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 16:30:16.781  5838  5944 D BtGatt.GattService: onClientRegistered() - UUID=1f95ae08-33c2-46de-9b48-59f747b2d6b1, clientIf=7,
,03-31 16:30:16.781 11128 11144 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7,
,03-31 16:30:16.866  5838  5848 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 54
,03-31 16:30:16.866  5838  5951 D BtGatt.AdvertiseManager: message : 0
,03-31 16:30:16.866  5838  5951 D BtGatt.AdvertiseManager: number of adv instance running0
03-31 16:30:16.866  5838  5951 D BtGatt.AdvertiseManager: size of list is =0
,03-31 16:30:16.871  5838  5951 D BtGatt.AdvertiseManager: starting advertising
03-31 16:30:16.871  5838  5951 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-31 16:30:16.876  5838  5944 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-31 16:30:16.881  5838  5951 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 16:30:16.881  5838  5944 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-31 16:30:16.886  5838  5951 D BtGatt.AdvertiseManager: logClientsSet() - status: 0,
03-31 16:30:16.886  5838  5951 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,03-31 16:30:16.886 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-31 16:30:16.886 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK,
03-31 16:30:16.891 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 16:30:16.891 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-31 16:30:16.891 11128 11200 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-31 16:30:16.891 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 16:30:16.891 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-31 16:30:16.891 11128 11200 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-31 16:30:16.891 11128 11200 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-31 16:30:16.891 11128 11200 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK,
,03-31 16:30:16.896 11128 11128 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything,
03-31 16:30:16.896 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-31 16:30:16.896 11128 11128 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-31 16:30:16.896 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-31 16:30:16.896 11128 11128 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-31 16:30:16.896 11128 11128 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-31 16:30:16.896 11128 11128 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 16:30:16.896 11128 11128 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 16:30:16.896 11128 11128 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-31 16:30:16.896 11128 11128 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 16:30:16.896 11128 11128 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-31 16:30:16.896 11128 11128 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true,
03-31 16:30:16.896 11128 11200 I io.jxcore.node.ConnectionHelper: start: OK
03-31 16:30:16.896 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 16:30:16.896 11128 11200 I jxcore-log: 
,03-31 16:30:16.906 11128 11635 D BluetoothSocket: bindListen(): myUserId = 0
,03-31 16:30:16.906 11128 11635 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-31 16:30:16.911 11128 11635 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[92]}
03-31 16:30:16.911 11128 11635 D BluetoothSocket: bindListen(), new LocalSocket 
,03-31 16:30:16.911 11128 11635 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-31 16:30:16.911 11128 11635 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@28a47b62
03-31 16:30:16.911 11128 11635 D BluetoothSocket: channel: 6
03-31 16:30:16.911 11128 11635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-31 16:30:16.911 11128 11200 I jxcore-log: ok 145 Can call startUpdateAdvertisingAndListening without error
03-31 16:30:16.911 11128 11200 I jxcore-log: 
,03-31 16:30:16.911 11128 11200 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-31 16:30:16.911 11128 11200 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-31 16:30:16.911 11128 11200 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-31 16:30:16.911 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-31 16:30:16.911 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-31 16:30:16.911 11128 11200 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3b6c94f3, channel: 6, state: LISTENING
,03-31 16:30:16.916 11128 11200 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3b6c94f3, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@28a47b62, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@98fa5b0mSocket: android.net.LocalSocket@2cc55c29 impl:android.net.LocalSocketImpl@22d2ebae fd:FileDescriptor[92],
03-31 16:30:16.916 11128 11200 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2cc55c29 impl:android.net.LocalSocketImpl@22d2ebae fd:FileDescriptor[92]
03-31 16:30:16.916 11128 11200 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-31 16:30:16.916 11128 11635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-31 16:30:16.916 11128 11635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread,
03-31 16:30:16.916 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-31 16:30:16.916 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-31 16:30:16.916 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-31 16:30:16.916 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-31 16:30:16.916 11128 11635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,03-31 16:30:16.916 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-31 16:30:16.916 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-31 16:30:16.921  5838  5850 D BtGatt.GattService: stopScan() - queue size =1
,03-31 16:30:16.921  5838  5952 D BtGatt.ScanManager: filter size is 1
03-31 16:30:16.921  5838  5952 D BtGatt.ScanManager: delete FilterIndex - 8
03-31 16:30:16.921  5838  5955 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-31 16:30:16.921  5838  5944 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-31 16:30:16.921  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 16:30:16.921  5838  5952 D BtGatt.ScanManager: stopping BLe Batch
,03-31 16:30:16.921 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 16:30:16.921 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-31 16:30:16.926  5838  5944 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0,
03-31 16:30:16.926  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 16:30:16.926  5838  5952 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-31 16:30:16.926 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-31 16:30:16.926 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-31 16:30:16.926 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-31 16:30:16.926 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-31 16:30:16.926  5838  5944 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-31 16:30:16.926  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 16:30:16.926 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-31 16:30:16.931  5838  5951 D BtGatt.AdvertiseManager: message : 1
,03-31 16:30:16.931  5838  5951 D BtGatt.AdvertiseManager: stop advertise for client 7
03-31 16:30:16.931  5838  5951 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
,03-31 16:30:16.931  5838  5951 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,03-31 16:30:16.931  5838  5944 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-31 16:30:16.931  5838  5944 D BtGatt.GattService: Client app is not null!
,03-31 16:30:16.931  5838  5850 D BtGatt.GattService: unregisterClient() - clientIf=7
,03-31 16:30:16.936 11128 11140 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2b0752b9, channel: 6, state: CLOSED,
03-31 16:30:16.936 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 16:30:16.936 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-31 16:30:16.936 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-31 16:30:16.936 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-31 16:30:16.936 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-31 16:30:16.936 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 16:30:16.936 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 16:30:16.936 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-31 16:30:16.936 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-31 16:30:16.936 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 16:30:16.936 11128 11128 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 16:30:16.936 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 16:30:16.936 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-31 16:30:16.936 11128 11140 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@77d9481, channel: 6, state: CLOSED
,03-31 16:30:16.941 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 16:30:16.941 11128 11200 I jxcore-log: 
,03-31 16:30:16.941 11128 11128 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-31 16:30:16.941 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-31 16:30:16.941 11128 11200 I jxcore-log: 
,03-31 16:30:16.946 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-31 16:30:16.946 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 16:30:16.946 11128 11128 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 16:30:16.951 11128 11128 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-31 16:30:16.951 11128 11128 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-31 16:30:16.951 11128 11128 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 16:30:16.951 11128 11128 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 16:30:16.951 11128 11128 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 16:30:16.951 11128 11128 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 16:30:16.951 11128 11128 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 16:30:16.951 11128 11128 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-31 16:30:16.951 11128 11200 I jxcore-log: ok 146 Can call stopAdvertisingAndListening without error
03-31 16:30:16.951 11128 11200 I jxcore-log: 
,03-31 16:30:16.956 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-31 16:30:16.956 11128 11200 I jxcore-log: 
,03-31 16:30:16.956 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 16:30:16.956 11128 11200 I jxcore-log: 
,03-31 16:30:16.956 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 16:30:16.956 11128 11200 I jxcore-log: 
,03-31 16:30:16.961 11128 11200 I jxcore-log: # teardown
03-31 16:30:16.961 11128 11200 I jxcore-log: 
,03-31 16:30:17.046 11128 11200 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 16:30:17.046 11128 11200 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-31 16:30:17.051 11128 11200 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 16:30:17.051 11128 11200 I jxcore-log: ok 147 Should be able to call stopListeningForAdvertisments in teardown
03-31 16:30:17.051 11128 11200 I jxcore-log: 
,03-31 16:30:17.056 11128 11200 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 16:30:17.056 11128 11200 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-31 16:30:17.056 11128 11200 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 16:30:17.061 11128 11200 I jxcore-log: ok 148 Should be able to call stopAdvertisingAndListening in teardown
03-31 16:30:17.061 11128 11200 I jxcore-log: 
,03-31 16:30:17.071 11128 11200 I jxcore-log: # setup
03-31 16:30:17.071 11128 11200 I jxcore-log: 
,03-31 16:30:17.226 11128 11200 I jxcore-log: # 38. Calling startUpdateAdvertisingAndListening twice is NOT an error
03-31 16:30:17.226 11128 11200 I jxcore-log: 
,03-31 16:30:17.236  3440  3575 W ProcessCpuTracker: Skipping unknown process pid 11641
,03-31 16:30:17.376 11128 11200 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true
,03-31 16:30:17.376 11128 11200 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-31 16:30:17.381 11128 11200 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,03-31 16:30:17.381 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-31 16:30:17.386 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-31 16:30:17.386 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 16:30:17.386 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-31 16:30:17.386 11128 11200 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 16:30:17.391  5838  5850 D BtGatt.GattService: registerClient() - UUID=91c4c62c-1fde-43ca-aa1d-0f24f346be3b
,03-31 16:30:17.431  5838  5944 D BtGatt.GattService: onClientRegistered() - UUID=91c4c62c-1fde-43ca-aa1d-0f24f346be3b, clientIf=6
03-31 16:30:17.436 11128 11144 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-31 16:30:17.441  5838  5955 D BtGatt.GattService: start scan with filters
,03-31 16:30:17.466  5838  5955 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 71
,03-31 16:30:17.466  5838  5952 D BtGatt.ScanManager: handling starting scan
03-31 16:30:17.466  5838  5952 D BtGatt.ScanManager: isFilteringSupported
03-31 16:30:17.466  5838  5952 D BluetoothAdapter: setting StandAloneBleMode
,03-31 16:30:17.471  5838  5944 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-31 16:30:17.471  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 16:30:17.471  5838  5952 D BtGatt.ScanManager: allow scan with filters
03-31 16:30:17.471  5838  5952 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-31 16:30:17.471  5838  5952 D BtGatt.ScanManager: set filter index= 9 for clientIf= 6
03-31 16:30:17.476  5838  5944 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-31 16:30:17.476  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 16:30:17.476  5838  5952 D BtGatt.ScanManager: Starting BLE batch scan
,03-31 16:30:17.476  5838  5952 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-31 16:30:17.481  5838  5944 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-31 16:30:17.481  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 16:30:17.481  5838  5944 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-31 16:30:17.481  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 16:30:17.481 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
03-31 16:30:17.481 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true,
03-31 16:30:17.486 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-31 16:30:17.486 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,03-31 16:30:17.486 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 16:30:17.486 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 16:30:17.486 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-31 16:30:17.486 11128 11200 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
,03-31 16:30:17.486 11128 11200 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 16:30:17.486 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 16:30:17.486 11128 11200 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-31 16:30:17.486 11128 11128 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-31 16:30:17.486  5838  5848 D BtGatt.GattService: registerClient() - UUID=d033927b-6f56-471a-baa4-4e583e2dc396
,03-31 16:30:17.531  5838  5944 D BtGatt.GattService: onClientRegistered() - UUID=d033927b-6f56-471a-baa4-4e583e2dc396, clientIf=7,
,03-31 16:30:17.531 11128 11138 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7,
,03-31 16:30:17.566  5838  9004 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 55
,03-31 16:30:17.566  5838  5951 D BtGatt.AdvertiseManager: message : 0
,03-31 16:30:17.566  5838  5951 D BtGatt.AdvertiseManager: number of adv instance running0
03-31 16:30:17.566  5838  5951 D BtGatt.AdvertiseManager: size of list is =0
,03-31 16:30:17.571  5838  5951 D BtGatt.AdvertiseManager: starting advertising
03-31 16:30:17.571  5838  5951 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-31 16:30:17.576  5838  5944 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-31 16:30:17.581  5838  5951 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 16:30:17.581  5838  5944 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-31 16:30:17.581  5838  5951 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,03-31 16:30:17.581  5838  5951 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,03-31 16:30:17.586 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-31 16:30:17.586 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-31 16:30:17.586 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
03-31 16:30:17.586 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 16:30:17.586 11128 11200 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-31 16:30:17.586 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-31 16:30:17.591 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-31 16:30:17.591 11128 11200 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-31 16:30:17.591 11128 11200 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-31 16:30:17.591 11128 11200 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-31 16:30:17.591 11128 11128 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything,
03-31 16:30:17.591 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 16:30:17.591 11128 11128 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-31 16:30:17.591 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,03-31 16:30:17.591 11128 11128 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-31 16:30:17.596 11128 11128 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-31 16:30:17.596 11128 11128 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 16:30:17.596 11128 11128 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-31 16:30:17.596 11128 11128 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-31 16:30:17.596 11128 11128 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 16:30:17.596 11128 11128 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-31 16:30:17.596 11128 11128 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-31 16:30:17.596 11128 11200 I io.jxcore.node.ConnectionHelper: start: OK,
,03-31 16:30:17.601 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false},
03-31 16:30:17.601 11128 11200 I jxcore-log: 
03-31 16:30:17.601 11128 11200 I jxcore-log: ok 149 Can call startUpdateAdvertisingAndListening without error
03-31 16:30:17.601 11128 11200 I jxcore-log: 
,03-31 16:30:17.606 11128 11650 D BluetoothSocket: bindListen(): myUserId = 0,
03-31 16:30:17.606 11128 11650 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-31 16:30:17.611 11128 11650 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[92]},
03-31 16:30:17.611 11128 11650 D BluetoothSocket: bindListen(), new LocalSocket 
03-31 16:30:17.611 11128 11650 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-31 16:30:17.611 11128 11650 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@136614ba,
03-31 16:30:17.611 11128 11650 D BluetoothSocket: channel: 6
03-31 16:30:17.611 11128 11650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-31 16:30:17.616 11128 11200 I io.jxcore.node.ConnectionHelper: start: Port number: 4243, start advertisements: true
,03-31 16:30:17.616 11128 11200 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 16:30:17.616 11128 11200 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,03-31 16:30:17.616 11128 11200 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 16:30:17.616 11128 11200 I io.jxcore.node.ConnectionHelper: start: OK
,03-31 16:30:17.621 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 16:30:17.621 11128 11200 I jxcore-log: 
,03-31 16:30:17.621 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-31 16:30:17.621 11128 11200 I jxcore-log: 
,03-31 16:30:17.626 11128 11200 I jxcore-log: ok 150 Can call startUpdateAdvertisingAndListening twice without error
03-31 16:30:17.626 11128 11200 I jxcore-log: 
,03-31 16:30:17.631 11128 11200 I jxcore-log: # teardown
03-31 16:30:17.631 11128 11200 I jxcore-log: 
,03-31 16:30:18.091 11128 11200 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 16:30:18.091 11128 11200 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
,03-31 16:30:18.091 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,03-31 16:30:18.091 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-31 16:30:18.096  5838  5850 D BtGatt.GattService: stopScan() - queue size =1
03-31 16:30:18.096  5838  5952 D BtGatt.ScanManager: filter size is 1
03-31 16:30:18.096  5838  5952 D BtGatt.ScanManager: delete FilterIndex - 9
03-31 16:30:18.101  5838  5944 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-31 16:30:18.101  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 16:30:18.101  5838  5952 D BtGatt.ScanManager: stopping BLe Batch
,03-31 16:30:18.106  5838  5955 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-31 16:30:18.106  5838  5944 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-31 16:30:18.106  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 16:30:18.111  5838  5952 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-31 16:30:18.111  5838  5944 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
03-31 16:30:18.111  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 16:30:18.111  5838  5944 D BtGatt.GattService: current time is 259529134863
03-31 16:30:18.111  5838  5944 D BtGatt.GattService: Batch record : [38, 99, -28, -47, -98, 117, 1, -128, -62, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0, -55, 13, -15, -118, -70, 102, 1, -128, -76, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-31 16:30:18.111  5838  5944 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-31 16:30:18.111  5838  5944 D ScanRecord: parseFromBytes
03-31 16:30:18.111  5838  5944 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-31 16:30:18.111  5838  5944 D ScanRecord: parseFromBytes
,03-31 16:30:18.116 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
03-31 16:30:18.116 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 16:30:18.116 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-31 16:30:18.116 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
,03-31 16:30:18.116 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-31 16:30:18.116 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-31 16:30:18.116 11128 11128 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-31 16:30:18.121 11128 11128 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only,
03-31 16:30:18.121 11128 11128 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-31 16:30:18.121 11128 11200 I jxcore-log: ok 151 Should be able to call stopListeningForAdvertisments in teardown
03-31 16:30:18.121 11128 11200 I jxcore-log: 
,03-31 16:30:18.126 11128 11200 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 16:30:18.126 11128 11200 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,03-31 16:30:18.126 11128 11200 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-31 16:30:18.126 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,03-31 16:30:18.126 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-31 16:30:18.126 11128 11200 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1ea3af6b, channel: 6, state: LISTENING
,03-31 16:30:18.126 11128 11200 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1ea3af6b, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@136614ba, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2e67ac8mSocket: android.net.LocalSocket@343b6761 impl:android.net.LocalSocketImpl@2cd0c286 fd:FileDescriptor[92]
03-31 16:30:18.126 11128 11200 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@343b6761 impl:android.net.LocalSocketImpl@2cd0c286 fd:FileDescriptor[92]
,03-31 16:30:18.131 11128 11200 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-31 16:30:18.131 11128 11650 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-31 16:30:18.131 11128 11650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-31 16:30:18.131 11128 11650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-31 16:30:18.131 11128 11128 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-31 16:30:18.131 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-31 16:30:18.131 11128 11128 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-31 16:30:18.131 11128 11128 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-31 16:30:18.131 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-31 16:30:18.131 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-31 16:30:18.131 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-31 16:30:18.136 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-31 16:30:18.136 11128 11200 D BluetoothLeScanner: could not find callback wrapper,
03-31 16:30:18.136 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-31 16:30:18.136 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-31 16:30:18.141  5838  5951 D BtGatt.AdvertiseManager: message : 1,
,03-31 16:30:18.141  5838  5951 D BtGatt.AdvertiseManager: stop advertise for client 7,
,03-31 16:30:18.141  5838  5951 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-31 16:30:18.141  5838  5951 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-31 16:30:18.141  5838  5944 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
,03-31 16:30:18.141  5838  5944 D BtGatt.GattService: Client app is not null!
,03-31 16:30:18.146  5838  5955 D BtGatt.GattService: unregisterClient() - clientIf=7,
,03-31 16:30:18.151 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
03-31 16:30:18.151 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-31 16:30:18.151 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false,
03-31 16:30:18.151 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED],
03-31 16:30:18.151 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-31 16:30:18.151 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false,
,03-31 16:30:18.151 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 16:30:18.151 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...,
,03-31 16:30:18.151 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-31 16:30:18.151 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 16:30:18.151 11128 11128 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 16:30:18.151 11128 11128 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed,
03-31 16:30:18.156 11128 11128 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 16:30:18.156 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 16:30:18.156 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-31 16:30:18.161 11128 11128 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-31 16:30:18.166 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-31 16:30:18.166 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 16:30:18.166 11128 11128 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 16:30:18.166 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-31 16:30:18.166 11128 11200 I jxcore-log: 
,03-31 16:30:18.176 11128 11128 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false,
03-31 16:30:18.176 11128 11128 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 16:30:18.176 11128 11200 I jxcore-log: ok 152 Should be able to call stopAdvertisingAndListening in teardown,
03-31 16:30:18.176 11128 11200 I jxcore-log: 
,03-31 16:30:18.181 11128 11200 I jxcore-log: # setup
03-31 16:30:18.181 11128 11200 I jxcore-log: 
,03-31 16:30:18.186 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 16:30:18.186 11128 11200 I jxcore-log: 
,03-31 16:30:18.186 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 16:30:18.186 11128 11200 I jxcore-log: 
,03-31 16:30:18.826 11128 11200 I jxcore-log: # 39. peerAvailabilityChange is called
03-31 16:30:18.826 11128 11200 I jxcore-log: 
,03-31 16:30:18.966 11128 11200 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true
,03-31 16:30:18.966 11128 11200 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-31 16:30:18.966 11128 11200 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,03-31 16:30:18.966 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-31 16:30:18.971 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-31 16:30:18.971 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-31 16:30:18.971 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-31 16:30:18.971 11128 11200 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 16:30:18.981  5838  5955 D BtGatt.GattService: registerClient() - UUID=7bac8dc6-8b81-40aa-afea-6be989b23977
,03-31 16:30:19.026  5838  5944 D BtGatt.GattService: onClientRegistered() - UUID=7bac8dc6-8b81-40aa-afea-6be989b23977, clientIf=6
03-31 16:30:19.026 11128 11138 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-31 16:30:19.031  5838  5848 D BtGatt.GattService: start scan with filters
,03-31 16:30:19.051  5838  5848 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 72
,03-31 16:30:19.051  5838  5952 D BtGatt.ScanManager: handling starting scan
03-31 16:30:19.051  5838  5952 D BtGatt.ScanManager: isFilteringSupported
03-31 16:30:19.051  5838  5952 D BluetoothAdapter: setting StandAloneBleMode
,03-31 16:30:19.056  5838  5944 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-31 16:30:19.056  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 16:30:19.056  5838  5952 D BtGatt.ScanManager: allow scan with filters
03-31 16:30:19.056  5838  5952 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,03-31 16:30:19.056  5838  5952 D BtGatt.ScanManager: set filter index= 10 for clientIf= 6
03-31 16:30:19.061  5838  5944 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-31 16:30:19.061  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 16:30:19.061  5838  5952 D BtGatt.ScanManager: Starting BLE batch scan
03-31 16:30:19.061  5838  5952 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-31 16:30:19.061  5838  5944 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-31 16:30:19.061  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 16:30:19.066  5838  5944 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1,
03-31 16:30:19.066  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 16:30:19.071 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
03-31 16:30:19.071 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 16:30:19.071 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-31 16:30:19.071 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 16:30:19.071 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 16:30:19.071 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-31 16:30:19.071 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-31 16:30:19.071 11128 11200 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-31 16:30:19.071 11128 11200 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 16:30:19.071 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 16:30:19.071 11128 11200 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-31 16:30:19.071 11128 11128 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 16:30:19.076  5838  9004 D BtGatt.GattService: registerClient() - UUID=8d7f6efb-06b2-455c-a150-6c3050bad695,
,03-31 16:30:19.116  5838  5944 D BtGatt.GattService: onClientRegistered() - UUID=8d7f6efb-06b2-455c-a150-6c3050bad695, clientIf=7,
,03-31 16:30:19.116 11128 11144 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-31 16:30:19.131  5838  5850 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 56,
03-31 16:30:19.131  5838  5951 D BtGatt.AdvertiseManager: message : 0
03-31 16:30:19.131  5838  5951 D BtGatt.AdvertiseManager: number of adv instance running0
,03-31 16:30:19.131  5838  5951 D BtGatt.AdvertiseManager: size of list is =0
,03-31 16:30:19.131  5838  5951 D BtGatt.AdvertiseManager: starting advertising
03-31 16:30:19.131  5838  5951 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-31 16:30:19.136  5838  5944 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-31 16:30:19.141  5838  5951 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 16:30:19.141  5838  5944 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-31 16:30:19.141  5838  5951 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-31 16:30:19.141  5838  5951 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
03-31 16:30:19.141 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-31 16:30:19.141 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-31 16:30:19.146 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-31 16:30:19.146 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 16:30:19.146 11128 11200 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-31 16:30:19.146 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 16:30:19.146 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-31 16:30:19.146 11128 11200 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-31 16:30:19.146 11128 11200 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,03-31 16:30:19.146 11128 11200 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-31 16:30:19.146 11128 11200 I io.jxcore.node.ConnectionHelper: start: OK
03-31 16:30:19.146 11128 11128 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-31 16:30:19.146 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 16:30:19.146 11128 11128 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-31 16:30:19.146 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-31 16:30:19.146 11128 11128 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-31 16:30:19.146 11128 11128 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-31 16:30:19.146 11128 11128 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 16:30:19.146 11128 11128 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-31 16:30:19.146 11128 11128 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-31 16:30:19.146 11128 11128 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 16:30:19.146 11128 11128 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-31 16:30:19.146 11128 11128 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 16:30:19.151 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 16:30:19.151 11128 11200 I jxcore-log: 
,03-31 16:30:19.151 11128 11668 D BluetoothSocket: bindListen(): myUserId = 0
03-31 16:30:19.151 11128 11668 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-31 16:30:19.151 11128 11668 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[92]}
,03-31 16:30:19.151 11128 11668 D BluetoothSocket: bindListen(), new LocalSocket 
03-31 16:30:19.151 11128 11668 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-31 16:30:19.151 11128 11668 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3e68112
03-31 16:30:19.151 11128 11668 D BluetoothSocket: channel: 6
03-31 16:30:19.151 11128 11668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-31 16:30:19.161 11128 11200 I jxcore-log: ok 153 Can call startUpdateAdvertisingAndListeningwithout error
03-31 16:30:19.161 11128 11200 I jxcore-log: 
,03-31 16:30:19.166 11128 11200 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: false
,03-31 16:30:19.166 11128 11200 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 16:30:19.166 11128 11200 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
03-31 16:30:19.166 11128 11200 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-31 16:30:19.166 11128 11200 I io.jxcore.node.ConnectionHelper: start: OK
,03-31 16:30:19.166 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 16:30:19.166 11128 11200 I jxcore-log: 
,03-31 16:30:19.171 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-31 16:30:19.171 11128 11200 I jxcore-log: 
,03-31 16:30:19.171 11128 11200 I jxcore-log: ok 154 Can call startListeningForAdvertisements without error
03-31 16:30:19.171 11128 11200 I jxcore-log: ,
,03-31 16:30:20.066  3440  3618 V AlarmManager: waitForAlarm result :4,
03-31 16:30:20.076  5838  5838 D BtGatt.ScanManager: awakened up at time 261492
03-31 16:30:20.081  5838  5952 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-31 16:30:20.091  5838  5944 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
,03-31 16:30:20.091  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 16:30:20.091  5838  5944 D BtGatt.GattService: current time is 261505798739
03-31 16:30:20.091  5838  5944 D BtGatt.GattService: Batch record : [115, -54, -38, 88, -36, 99, 1, -128, -72, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, 61, -19, -83, 103, -117, 93, 1, -128, -55, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0]
03-31 16:30:20.091  5838  5944 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-31 16:30:20.091  5838  5944 D ScanRecord: parseFromBytes
03-31 16:30:20.091  5838  5944 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
,03-31 16:30:20.091  5838  5944 D ScanRecord: parseFromBytes,
,03-31 16:30:20.091  5838  5944 D BtGatt.GattService: result: ScanResult{mDevice=63:DC:58:DA:CA:73, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-72, mTimestampNanos=261406095155}
,03-31 16:30:20.091  5838  5944 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-31 16:30:20.091  5838  5944 D BtGatt.GattService: result: ScanResult{mDevice=5D:8B:67:AD:ED:3D, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-55, mTimestampNanos=261406095155}
03-31 16:30:20.091  5838  5944 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 16:30:20.091 11128 11144 D ScanRecord: parseFromBytes
03-31 16:30:20.091 11128 11144 D ScanRecord: parseFromBytes
03-31 16:30:20.091 11128 11128 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 1
03-31 16:30:20.096 11128 11128 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:CF:C5:D9:E5:61], added - the peer count is 2
03-31 16:30:20.096 11128 11128 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
03-31 16:30:20.096 11128 11128 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:CF:C5:D9:E5:61], Bluetooth address: F8:CF:C5:D9:E5:61, device name: , device address: 
,03-31 16:30:20.101 11128 11200 I jxcore-log: ok 155 peers must be an array
03-31 16:30:20.101 11128 11200 I jxcore-log: 
03-31 16:30:20.101 11128 11200 I jxcore-log: ok 156 peers must not be zero-length
03-31 16:30:20.101 11128 11200 I jxcore-log: 
,03-31 16:30:20.121 11128 11200 I jxcore-log: ok 157 peer must have peerIdentifier
,03-31 16:30:20.121 11128 11200 I jxcore-log: 
,03-31 16:30:20.126 11128 11200 I jxcore-log: ok 158 peerIdentifier must be a string
03-31 16:30:20.126 11128 11200 I jxcore-log: 
,03-31 16:30:20.126 11128 11200 I jxcore-log: ok 159 peer must have peerAvailable
03-31 16:30:20.126 11128 11200 I jxcore-log: 
,03-31 16:30:20.131 11128 11200 I jxcore-log: ok 160 peer must have pleaseConnect
03-31 16:30:20.131 11128 11200 I jxcore-log: 
,03-31 16:30:20.146 11128 11200 I jxcore-log: # teardown
03-31 16:30:20.146 11128 11200 I jxcore-log: 
,03-31 16:30:20.201 11128 11200 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 16:30:20.201 11128 11200 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
03-31 16:30:20.201 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-31 16:30:20.201 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-31 16:30:20.206  5838  5848 D BtGatt.GattService: stopScan() - queue size =1
,03-31 16:30:20.206  5838  5952 D BtGatt.ScanManager: filter size is 1
03-31 16:30:20.206  5838  5952 D BtGatt.ScanManager: delete FilterIndex - 10
03-31 16:30:20.206  5838  9004 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-31 16:30:20.206 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
03-31 16:30:20.206 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 16:30:20.206 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-31 16:30:20.211 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-31 16:30:20.211 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-31 16:30:20.211 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 16:30:20.211 11128 11128 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 16:30:20.211  5838  5944 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-31 16:30:20.211  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 16:30:20.211  5838  5952 D BtGatt.ScanManager: stopping BLe Batch
,03-31 16:30:20.211 11128 11128 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-31 16:30:20.211 11128 11128 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 16:30:20.211  5838  5944 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,03-31 16:30:20.211  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 16:30:20.211  5838  5952 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-31 16:30:20.211 11128 11200 I jxcore-log: ok 161 Should be able to call stopListeningForAdvertisments in teardown
03-31 16:30:20.211 11128 11200 I jxcore-log: 
03-31 16:30:20.211 11128 11200 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 16:30:20.211 11128 11200 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-31 16:30:20.211 11128 11200 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-31 16:30:20.211 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-31 16:30:20.211 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,03-31 16:30:20.211 11128 11200 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3590a199, channel: 6, state: LISTENING
03-31 16:30:20.211 11128 11200 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3590a199, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3e68112, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@35279c5emSocket: android.net.LocalSocket@236683f impl:android.net.LocalSocketImpl@24a7c50c fd:FileDescriptor[92]
03-31 16:30:20.211 11128 11200 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@236683f impl:android.net.LocalSocketImpl@24a7c50c fd:FileDescriptor[92]
03-31 16:30:20.211 11128 11200 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-31 16:30:20.211 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-31 16:30:20.211 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-31 16:30:20.211 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-31 16:30:20.211 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-31 16:30:20.211 11128 11668 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
,03-31 16:30:20.211 11128 11668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-31 16:30:20.216 11128 11668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-31 16:30:20.216 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-31 16:30:20.216  5838  5944 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
03-31 16:30:20.216  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 16:30:20.216  5838  5944 D BtGatt.GattService: current time is 261631118822
03-31 16:30:20.216 11128 11200 D BluetoothLeScanner: could not find callback wrapper
03-31 16:30:20.216 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 16:30:20.216 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-31 16:30:20.216  5838  5944 D BtGatt.GattService: Batch record : [61, -19, -83, 103, -117, 93, 1, -128, -69, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0, 115, -54, -38, 88, -36, 99, 1, -128, -72, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-31 16:30:20.216  5838  5944 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-31 16:30:20.216  5838  5944 D ScanRecord: parseFromBytes
,03-31 16:30:20.216  5838  5944 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-31 16:30:20.216  5838  5944 D ScanRecord: parseFromBytes
03-31 16:30:20.216  5838  5951 D BtGatt.AdvertiseManager: message : 1
03-31 16:30:20.216  5838  5951 D BtGatt.AdvertiseManager: stop advertise for client 7
03-31 16:30:20.216  5838  5951 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-31 16:30:20.216  5838  5951 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,03-31 16:30:20.221  5838  5944 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-31 16:30:20.221  5838  5944 D BtGatt.GattService: Client app is not null!
,03-31 16:30:20.221  5838  9004 D BtGatt.GattService: unregisterClient() - clientIf=7
03-31 16:30:20.221 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 16:30:20.221 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-31 16:30:20.221 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-31 16:30:20.221 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,03-31 16:30:20.221 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-31 16:30:20.221 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 16:30:20.221 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 16:30:20.221 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-31 16:30:20.221 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-31 16:30:20.221 11128 11200 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-31 16:30:20.221 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 16:30:20.221 11128 11128 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 16:30:20.221 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 16:30:20.221 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-31 16:30:20.226 11128 11128 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-31 16:30:20.231 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-31 16:30:20.231 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 16:30:20.231 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-31 16:30:20.231 11128 11200 I jxcore-log: 
,03-31 16:30:20.231 11128 11128 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-31 16:30:20.231 11128 11128 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-31 16:30:20.231 11128 11128 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 16:30:20.236 11128 11128 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-31 16:30:20.236 11128 11128 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 16:30:20.236 11128 11128 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 16:30:20.236 11128 11128 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 16:30:20.236 11128 11128 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-31 16:30:20.236 11128 11200 I jxcore-log: ok 162 Should be able to call stopAdvertisingAndListening in teardown
03-31 16:30:20.236 11128 11200 I jxcore-log: 
,03-31 16:30:20.246 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 16:30:20.246 11128 11200 I jxcore-log: 
,03-31 16:30:20.251 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 16:30:20.251 11128 11200 I jxcore-log: 
,03-31 16:30:20.251 11128 11200 I jxcore-log: # setup
03-31 16:30:20.251 11128 11200 I jxcore-log: 
,03-31 16:30:20.361 11128 11200 I jxcore-log: # 40. Can connect to a remote peer
03-31 16:30:20.361 11128 11200 I jxcore-log: 
,03-31 16:30:20.476 11128 11200 I io.jxcore.node.ConnectionHelper: start: Port number: 46988, start advertisements: true
,03-31 16:30:20.481 11128 11200 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-31 16:30:20.481 11128 11200 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-31 16:30:20.481 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-31 16:30:20.486 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-31 16:30:20.486 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 16:30:20.486 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 16:30:20.486 11128 11200 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 16:30:20.496  5838  9004 D BtGatt.GattService: registerClient() - UUID=ec0e7ed2-d0db-4b1a-8b38-54d4948062fd
,03-31 16:30:20.536  5838  5944 D BtGatt.GattService: onClientRegistered() - UUID=ec0e7ed2-d0db-4b1a-8b38-54d4948062fd, clientIf=6
,03-31 16:30:20.536 11128 11138 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-31 16:30:20.536  5838  5850 D BtGatt.GattService: start scan with filters
,03-31 16:30:20.551  5838  5850 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 73
,03-31 16:30:20.551 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 16:30:20.551 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 16:30:20.551 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-31 16:30:20.551  5838  5952 D BtGatt.ScanManager: handling starting scan
,03-31 16:30:20.551  5838  5952 D BtGatt.ScanManager: isFilteringSupported
03-31 16:30:20.551 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 16:30:20.551  5838  5952 D BluetoothAdapter: setting StandAloneBleMode
03-31 16:30:20.551 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 16:30:20.551 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-31 16:30:20.551 11128 11128 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 16:30:20.551 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-31 16:30:20.551 11128 11200 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-31 16:30:20.551 11128 11200 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 16:30:20.551 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 16:30:20.551 11128 11200 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-31 16:30:20.551  5838  5944 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-31 16:30:20.551  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 16:30:20.551  5838  5952 D BtGatt.ScanManager: allow scan with filters
03-31 16:30:20.551  5838  5952 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-31 16:30:20.551  5838  5952 D BtGatt.ScanManager: set filter index= 11 for clientIf= 6
,03-31 16:30:20.556  5838  5944 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,03-31 16:30:20.556  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 16:30:20.556  5838  5952 D BtGatt.ScanManager: Starting BLE batch scan
03-31 16:30:20.556  5838  5952 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-31 16:30:20.556  5838  5955 D BtGatt.GattService: registerClient() - UUID=edc0bc9f-7691-4ff6-837c-c2ba0daa8710
,03-31 16:30:20.561  5838  5944 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-31 16:30:20.561  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 16:30:20.561  5838  5944 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-31 16:30:20.561  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 16:30:20.601  5838  5944 D BtGatt.GattService: onClientRegistered() - UUID=edc0bc9f-7691-4ff6-837c-c2ba0daa8710, clientIf=7
03-31 16:30:20.601 11128 11144 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-31 16:30:20.621  5838  5848 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 57
,03-31 16:30:20.621  5838  5951 D BtGatt.AdvertiseManager: message : 0
,03-31 16:30:20.621  5838  5951 D BtGatt.AdvertiseManager: number of adv instance running0
03-31 16:30:20.626  5838  5951 D BtGatt.AdvertiseManager: size of list is =0
,03-31 16:30:20.626  5838  5951 D BtGatt.AdvertiseManager: starting advertising
03-31 16:30:20.626  5838  5951 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-31 16:30:20.631  5838  5944 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-31 16:30:20.636  5838  5951 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 16:30:20.641  5838  5944 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-31 16:30:20.641  5838  5951 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,03-31 16:30:20.641  5838  5951 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,03-31 16:30:20.641 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-31 16:30:20.641 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK,
03-31 16:30:20.646 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 16:30:20.646 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 16:30:20.646 11128 11200 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,03-31 16:30:20.646 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-31 16:30:20.646 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...,
03-31 16:30:20.651 11128 11200 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-31 16:30:20.651 11128 11200 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,03-31 16:30:20.651 11128 11200 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-31 16:30:20.651 11128 11128 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-31 16:30:20.651 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 16:30:20.651 11128 11128 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,03-31 16:30:20.651 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-31 16:30:20.651 11128 11128 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-31 16:30:20.651 11128 11128 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-31 16:30:20.651 11128 11128 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-31 16:30:20.651 11128 11128 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 16:30:20.651 11128 11128 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-31 16:30:20.651 11128 11128 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 16:30:20.651 11128 11128 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-31 16:30:20.651 11128 11128 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-31 16:30:20.651 11128 11200 I io.jxcore.node.ConnectionHelper: start: OK
03-31 16:30:20.651 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 16:30:20.651 11128 11200 I jxcore-log: 
03-31 16:30:20.651 11128 11200 I jxcore-log: ok 163 Can call startUpdateAdvertisingAndListening without error
03-31 16:30:20.651 11128 11200 I jxcore-log: 
,03-31 16:30:20.661 11128 11693 D BluetoothSocket: bindListen(): myUserId = 0,
03-31 16:30:20.661 11128 11693 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-31 16:30:20.666 11128 11693 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[93]}
,03-31 16:30:20.666 11128 11693 D BluetoothSocket: bindListen(), new LocalSocket 
03-31 16:30:20.666 11128 11693 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-31 16:30:20.666 11128 11693 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@69225f8
03-31 16:30:20.666 11128 11693 D BluetoothSocket: channel: 6
,03-31 16:30:20.666 11128 11693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-31 16:30:20.671 11128 11200 I io.jxcore.node.ConnectionHelper: start: Port number: 46988, start advertisements: false,
03-31 16:30:20.671 11128 11200 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-31 16:30:20.671 11128 11200 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
03-31 16:30:20.671 11128 11200 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 16:30:20.671 11128 11200 I io.jxcore.node.ConnectionHelper: start: OK
,03-31 16:30:20.676 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 16:30:20.676 11128 11200 I jxcore-log: 
,03-31 16:30:20.676 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-31 16:30:20.676 11128 11200 I jxcore-log: 
,03-31 16:30:20.681 11128 11200 I jxcore-log: ok 164 Can call startListeningForAdvertisements without error
03-31 16:30:20.681 11128 11200 I jxcore-log: 
,03-31 16:30:21.561  3440  3618 V AlarmManager: waitForAlarm result :4
,03-31 16:30:21.576  5838  5838 D BtGatt.ScanManager: awakened up at time 262991
,03-31 16:30:21.581  5838  5952 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-31 16:30:21.596  5838  5944 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=3
03-31 16:30:21.596  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 16:30:21.596  5838  5944 D BtGatt.GattService: current time is 263011749072
03-31 16:30:21.596  5838  5944 D BtGatt.GattService: Batch record : [-108, -13, -97, -74, 10, 114, 1, -128, -54, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0, 38, 24, -30, 89, -36, 81, 1, -128, -74, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -28, -44, -106, -22, -38, 116, 0, -128, -94, 12, 0, 23, 2, 1, 6, 3, 2, 5, 24, 15, 9, 90, 101, 70, 105, 116, 50, 32, 35, 54, 54, 48, 55, 53, 0, 16, 15, 9, 90, 101, 70, 105, 116, 50, 32, 35, 54, 54, 48, 55, 53, 0]
03-31 16:30:21.596  5838  5944 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-31 16:30:21.596  5838  5944 D ScanRecord: parseFromBytes
03-31 16:30:21.596  5838  5944 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-31 16:30:21.596  5838  5944 D ScanRecord: parseFromBytes
03-31 16:30:21.596  5838  5944 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 5, 24, 15, 9, 90, 101, 70, 105, 116, 50, 32, 35, 54, 54, 48, 55, 53, 0, 15, 9, 90, 101, 70, 105, 116, 50, 32, 35, 54, 54, 48, 55, 53, 0]
03-31 16:30:21.596  5838  5944 D ScanRecord: parseFromBytes
03-31 16:30:21.596  5838  5944 D BtGatt.GattService: result: ScanResult{mDevice=51:DC:59:E2:18:26, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-74, mTimestampNanos=262962009197}
03-31 16:30:21.596  5838  5944 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-31 16:30:21.596  5838  5944 D BtGatt.GattService: result: ScanResult{mDevice=74:DA:EA:96:D4:E4, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[00001805-0000-1000-8000-00805f9b34fb], mManufacturerSpecificData={}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=ZeFit2 #66075��], mRssi=-94, mTimestampNanos=262412009197}
03-31 16:30:21.596  5838  5944 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-31 16:30:21.596  5838  5944 D BtGatt.GattService: result: ScanResult{mDevice=72:0A:B6:9F:F3:94, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-54, mTimestampNanos=262962009197}
03-31 16:30:21.596  5838  5944 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-31 16:30:21.596 11128 11144 D ScanRecord: parseFromBytes
03-31 16:30:21.596 11128 11144 D ScanRecord: parseFromBytes
03-31 16:30:21.596 11128 11144 D ScanRecord: parseFromBytes
03-31 16:30:21.601 11128 11128 V org.thaliproject.p2p.b,tconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 1
03-31 16:30:21.601 11128 11128 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:CF:C5:D9:E5:61], added - the peer count is 2
03-31 16:30:21.601 11128 11128 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
03-31 16:30:21.601 11128 11128 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:CF:C5:D9:E5:61], Bluetooth address: F8:CF:C5:D9:E5:61, device name: , device address: 
,03-31 16:30:21.611 11128 11200 I jxcore-log: INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"pleaseConnect":false}],
03-31 16:30:21.611 11128 11200 I jxcore-log: 
,03-31 16:30:21.626 11128 11200 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID F8:95:C7:87:3C:51
,03-31 16:30:21.626 11128 11200 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> F8:95:C7:87:3C:51]
,03-31 16:30:21.626 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address F8:95:C7:87:3C:51
,03-31 16:30:21.631 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,03-31 16:30:21.631 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,03-31 16:30:21.631 11128 11200 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null F8:95:C7:87:3C:51
,03-31 16:30:21.631 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address F8:95:C7:87:3C:51
03-31 16:30:21.631 11128 11200 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: F8:95:C7:87:3C:51)
,03-31 16:30:21.636 11128 11200 I jxcore-log: INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"F8:CF:C5:D9:E5:61","peerAvailable":true,"pleaseConnect":false}]
03-31 16:30:21.636 11128 11200 I jxcore-log: 
,03-31 16:30:21.636 11128 11700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address F8:95:C7:87:3C:51 (thread ID: 1545)
,03-31 16:30:21.646 11128 11700 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
03-31 16:30:21.646 11128 11700 D BluetoothSocket: connect(): myUserId = 0
03-31 16:30:21.646 11128 11700 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-31 16:30:21.651  5838  5850 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-31 16:30:21.651  5838  6006 D IOP_DB_BT: db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-31 16:30:21.651  5838  6006 D IOP_DB_BT: db_query_add_key: key KEY_LMP_MFCT, value 15
03-31 16:30:21.651  5838  6006 D IOP_DB_BT: db_query_add_key: key KEY_LMP_VER, value 7:24841
03-31 16:30:21.651  5838  6006 D IOP_DB_BT: db_query_add_key: key KEY_DIR_ALL, value 1
03-31 16:30:21.651 11128 11700 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[118]}
03-31 16:30:21.651  5838  6006 D IOP_DB_BT: db_query_execute: result 1
,03-31 16:30:21.651  5838  6006 W bt-btif : bta_dm_acl_change(), event : 2
,03-31 16:30:22.616  3440  3618 V AlarmManager: waitForAlarm result :4
,03-31 16:30:22.631  5838  5838 D BtGatt.ScanManager: awakened up at time 264046
,03-31 16:30:22.636  5838  5952 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-31 16:30:22.641  5838  5944 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=3
03-31 16:30:22.641  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 16:30:22.641  5838  5944 D BtGatt.GattService: current time is 264059821072
,03-31 16:30:22.646  5838  5944 D BtGatt.GattService: Batch record : [-108, -13, -97, -74, 10, 114, 1, -128, -62, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0, 38, 24, -30, 89, -36, 81, 1, -128, -76, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -28, -44, -106, -22, -38, 116, 0, -128, -91, 13, 0, 23, 2, 1, 6, 3, 2, 5, 24, 15, 9, 90, 101, 70, 105, 116, 50, 32, 35, 54, 54, 48, 55, 53, 0, 16, 15, 9, 90, 101, 70, 105, 116, 50, 32, 35, 54, 54, 48, 55, 53, 0]
03-31 16:30:22.646  5838  5944 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-31 16:30:22.646  5838  5944 D ScanRecord: parseFromBytes
03-31 16:30:22.646  5838  5944 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81],
,03-31 16:30:22.646  5838  5944 D ScanRecord: parseFromBytes
03-31 16:30:22.646  5838  5944 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 5, 24, 15, 9, 90, 101, 70, 105, 116, 50, 32, 35, 54, 54, 48, 55, 53, 0, 15, 9, 90, 101, 70, 105, 116, 50, 32, 35, 54, 54, 48, 55, 53, 0]
03-31 16:30:22.646  5838  5944 D ScanRecord: parseFromBytes
03-31 16:30:22.646  5838  5944 D BtGatt.GattService: result: ScanResult{mDevice=74:DA:EA:96:D4:E4, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[00001805-0000-1000-8000-00805f9b34fb], mManufacturerSpecificData={}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=ZeFit2 #66075��], mRssi=-91, mTimestampNanos=263410205489},
03-31 16:30:22.646  5838  5944 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-31 16:30:22.646  5838  5944 D BtGatt.GattService: result: ScanResult{mDevice=72:0A:B6:9F:F3:94, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-62, mTimestampNanos=264010205489}
03-31 16:30:22.646  5838  5944 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null],
,03-31 16:30:22.646  5838  5944 D BtGatt.GattService: result: ScanResult{mDevice=51:DC:59:E2:18:26, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-76, mTimestampNanos=263960205489}
03-31 16:30:22.646  5838  5944 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-31 16:30:22.646 11128 11138 D ScanRecord: parseFromBytes
03-31 16:30:22.646 11128 11138 D ScanRecord: parseFromBytes
,03-31 16:30:22.646 11128 11138 D ScanRecord: parseFromBytes
03-31 16:30:22.646 11128 11128 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:CF:C5:D9:E5:61] updated - the peer count is 2
03-31 16:30:22.646 11128 11128 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
,03-31 16:30:23.366  5838  6006 W bt-btif : bta_dm_acl_change(), event : 2
03-31 16:30:23.371  5838  6006 W bt-btif : bta_dm_acl_change(), event : 4
03-31 16:30:23.371  5838  6006 W bt-btif : scb return value : 1
,03-31 16:30:23.386  5838  6006 D IOP_DB_BT: db_query: id SkipSdpInfo :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-31 16:30:23.386  5838  6006 D IOP_DB_BT: db_query: result 1
,03-31 16:30:23.421  5838  6006 D IOP_DB_BT: db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-31 16:30:23.421  5838  6006 D IOP_DB_BT: db_query_add_key: key KEY_LMP_MFCT, value 15
03-31 16:30:23.421  5838  6006 D IOP_DB_BT: db_query_add_key: key KEY_LMP_VER, value 7:24841
03-31 16:30:23.421  5838  6006 D IOP_DB_BT: db_query_add_key: key KEY_DIR_ALL, value *
03-31 16:30:23.421  5838  6006 D IOP_DB_BT: db_query_execute: result 1
03-31 16:30:23.421  5838  6006 W bt-btif : bta_dm_acl_change(), event : 0
03-31 16:30:23.421  5838  6006 W bt-btif : info:x10
03-31 16:30:23.421  5838  5944 D         : remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
03-31 16:30:23.421  5838  6006 W bt-btif : bta_dm_acl_change(), event : 2
03-31 16:30:23.421  5838  5944 E BluetoothRemoteDevices: aclStateChangeCallback: Device is NULL
03-31 16:30:23.431  5838  5944 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,03-31 16:30:23.441  5838  6006 W bt-sdp  : process_service_search_attr_rsp
,03-31 16:30:23.616  5838  5944 W bt-btif : btif_dm_ssp_cfm_req_evt
,03-31 16:30:23.626  5838  5944 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,03-31 16:30:23.641  5838  5944 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
03-31 16:30:23.641  5838  5944 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
03-31 16:30:23.646  3440  3901 D SecContentProvider: query(), uri = 4 selection = bluetoothLogForRemote
,03-31 16:30:23.651  5838  5944 E bt-btif : check_cod: remote_cod = 0x5a020c
03-31 16:30:23.661  3440  3618 V AlarmManager: waitForAlarm result :4
03-31 16:30:23.651  5838  5944 W bt-btif : btif_dm_ssp_reply: accept=1
,03-31 16:30:23.666  5838  5950 I BluetoothBondStateMachine: Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11,
,03-31 16:30:23.671  3440  3440 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive,
03-31 16:30:23.671  3440  3440 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.device.action.BOND_STATE_CHANGED
,03-31 16:30:23.681  3440  3440 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED
03-31 16:30:23.681  3440  3440 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 10
03-31 16:30:23.681  3440  3440 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 11
03-31 16:30:23.681  3440  3440 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
,03-31 16:30:23.681  3724  3724 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,03-31 16:30:23.691  3724  4681 D BluetoothTile:  handleUpdatestate:false name:null
,03-31 16:30:23.691  3440  3575 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{305a732e u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{26a43956 10218:com.android.settings/1000}
,03-31 16:30:23.691  5838  5950 D BtConfig.SecureMode: isSecureModeOn:false
03-31 16:30:23.691  3440  3483 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
03-31 16:30:23.691  5838  5950 I BluetoothBondStateMachine: Entering PendingCommandState State
,03-31 16:30:23.696 10218 10218 D BluetoothNotiBroadcastReceiver: onReceive
,03-31 16:30:23.706 10279 11719 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,03-31 16:30:23.706 10279 10279 D [CarModeFW]: ConnectivityManager-handleMessage PAIRING_DEVICES
,03-31 16:30:23.711  3440  3966 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{305a732e u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{37e85c63 10279:com.sec.android.automotive.drivelink/u0a102}
,03-31 16:30:23.711 10279 10279 D [CarMode]: [AutoLaunchReceiver]-action: android.bluetooth.device.action.BOND_STATE_CHANGED
,03-31 16:30:23.716 10279 10279 D [CarMode]: [AutoLaunchReceiver]-ACTION_BOND_STATE_CHANGED G4-1 state is 11
,03-31 16:30:23.721  3440  4064 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{305a732e u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{37e85c63 10279:com.sec.android.automotive.drivelink/u0a102}
,03-31 16:30:23.721  3440  4724 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink,
,03-31 16:30:23.731 10279 11720 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,03-31 16:30:23.731 10279 10279 D [CarModeFW]: ConnectivityManager-handleMessage PAIRING_DEVICES
,03-31 16:30:23.731  3440  4064 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{305a732e u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{3d08b54e 10469:com.samsung.android.app.watchmanagerstub/u0a121}
,03-31 16:30:23.746 10469 10469 E BluetoothHeadset: BTStateChangeCB is registed
,03-31 16:30:23.746 10469 10469 D GMHFPReceiver: android.bluetooth.device.action.BOND_STATE_CHANGED
,03-31 16:30:23.746 10469 10469 D GMHFPReceiver: jangil::setProperties()
,03-31 16:30:23.751 10469 10469 D GMHFPReceiver: jangil::printBTStatus()
,03-31 16:30:23.751  3440  4047 D SettingsProvider: name = Wearable0001
,03-31 16:30:23.751  3440  4047 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-31 16:30:23.751  3440  4047 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-31 16:30:23.751  3440  4047 D SettingsProvider: selectionArgs: false
03-31 16:30:23.751  3440  4047 D SettingsProvider: selectionArgs: 10121
03-31 16:30:23.756  3440  4047 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
03-31 16:30:23.756  3440  4047 D SettingsProvider: ret = -1
,03-31 16:30:23.761  3440  4047 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10121
,03-31 16:30:23.761 10469 10469 D GMHFPReceiver: ::::::::Wearable0001::false
,03-31 16:30:23.766  3440  3733 D SettingsProvider: name = Wearable0002
03-31 16:30:23.766  3440  3733 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-31 16:30:23.766  3440  3733 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-31 16:30:23.766  3440  3733 D SettingsProvider: selectionArgs: false
03-31 16:30:23.766  3440  3733 D SettingsProvider: selectionArgs: 10121
03-31 16:30:23.766  3440  3733 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,03-31 16:30:23.766  3440  3733 D SettingsProvider: ret = -1
,03-31 16:30:23.771  3440  3733 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10121
,03-31 16:30:23.771 10469 10469 D GMHFPReceiver: ::::::::Wearable0002::false
03-31 16:30:23.771  3724  3724 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-31 16:30:23.786  3440  4737 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{305a732e u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{374a433e 4334:com.google.android.gms.persistent/u0a14}
,03-31 16:30:23.791  5838  5838 D BtGatt.ScanManager: awakened up at time 265204,
03-31 16:30:23.791  5838  5952 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-31 16:30:23.791  5838  5944 W bt-btif : btif_dm_auth_cmpl_evt
,03-31 16:30:23.796  5838  5944 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,03-31 16:30:23.801  3724  3724 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-31 16:30:23.811  5838  5944 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,03-31 16:30:23.811  5838  5944 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
03-31 16:30:23.811  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 16:30:23.811  5838  5944 D BtGatt.GattService: current time is 265227998989
03-31 16:30:23.811  5838  5950 D BluetoothAdapterProperties: Failed to remove device: F8:95:C7:87:3C:51
03-31 16:30:23.811  5838  5944 D BtGatt.GattService: Batch record : [38, 24, -30, 89, -36, 81, 1, -128, -64, 10, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -108, -13, -97, -74, 10, 114, 1, -128, -66, 11, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0]
03-31 16:30:23.811  5838  5944 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-31 16:30:23.811  5838  5944 D ScanRecord: parseFromBytes
,03-31 16:30:23.811  5838  5944 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-31 16:30:23.811  5838  5944 D ScanRecord: parseFromBytes
03-31 16:30:23.811  5838  5944 D BtGatt.GattService: result: ScanResult{mDevice=72:0A:B6:9F:F3:94, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-66, mTimestampNanos=264678166156}
03-31 16:30:23.811  5838  5944 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-31 16:30:23.811  5838  5944 D BtGatt.GattService: result: ScanResult{mDevice=51:DC:59:E2:18:26, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-64, mTimestampNanos=264728166156}
03-31 16:30:23.811  5838  5944 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-31 16:30:23.811 11128 11144 D ScanRecord: parseFromBytes
03-31 16:30:23.811 11128 11144 D ScanRecord: parseFromBytes
03-31 16:30:23.816  3440  3946 D SecContentProvider: query(), uri = 4 selection = bluetoothLogForRemote
,03-31 16:30:23.816 11128 11128 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:CF:C5:D9:E5:61] updated - the peer count is 2
03-31 16:30:23.816 11128 11128 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
03-31 16:30:23.816  5838  6006 E bt-btm  : btm_sec_encrypt_change collision_start_time is not 0, it 2147457694
03-31 16:30:23.816  5838  6006 E bt-btm  : return here let's wait the timer is expired...
03-31 16:30:23.816  5838  5950 I BluetoothBondStateMachine: Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,03-31 16:30:23.821  3440  3440 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
,03-31 16:30:23.821  3440  3440 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.device.action.BOND_STATE_CHANGED
03-31 16:30:23.821  3440  3440 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED
03-31 16:30:23.821  3440  3440 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 11
03-31 16:30:23.821  3440  3440 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 10
03-31 16:30:23.821  3440  3440 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
,03-31 16:30:23.821  3724  3724 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,03-31 16:30:23.826  3724  4681 D BluetoothTile:  handleUpdatestate:false name:null
,03-31 16:30:23.826  3440  3575 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2cc5c648 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{26a43956 10218:com.android.settings/1000}
,03-31 16:30:23.826  3440  4047 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
03-31 16:30:23.826  5838  5950 D BtConfig.SecureMode: isSecureModeOn:false
03-31 16:30:23.826 10218 10218 D BluetoothNotiBroadcastReceiver: onReceive
,03-31 16:30:23.836 10279 11724 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,03-31 16:30:23.836  5838  5950 D HidService: getHidService(): returning com.android.bluetooth.hid.HidService@3842cbb
,03-31 16:30:23.836  3440  3828 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2cc5c648 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{37e85c63 10279:com.sec.android.automotive.drivelink/u0a102}
03-31 16:30:23.841  3440  3966 D SettingsProvider: name = bluetooth_input_device_priority_F8:95:C7:87:3C:51
03-31 16:30:23.841  3440  3966 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-31 16:30:23.841  3440  3966 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-31 16:30:23.841 10279 10279 D [CarMode]: [AutoLaunchReceiver]-action: android.bluetooth.device.action.BOND_STATE_CHANGED
03-31 16:30:23.841  3440  3966 D SettingsProvider: selectionArgs: false
03-31 16:30:23.841  3440  3966 D SettingsProvider: selectionArgs: 1002
03-31 16:30:23.841  3440  3966 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
03-31 16:30:23.841  3440  3966 D SettingsProvider: ret = -1
03-31 16:30:23.841  5838  5950 D HidService: Saved priority F8:95:C7:87:3C:51 = -1
,03-31 16:30:23.841  3440  4421 D SettingsProvider: name = bluetooth_a2dp_sink_priority_F8:95:C7:87:3C:51
03-31 16:30:23.841  3440  4421 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-31 16:30:23.841  3440  4421 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-31 16:30:23.841  3440  4421 D SettingsProvider: selectionArgs: false
03-31 16:30:23.841  3440  4421 D SettingsProvider: selectionArgs: 1002
03-31 16:30:23.841  3440  4421 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
03-31 16:30:23.841  3440  4421 D SettingsProvider: ret = -1
,03-31 16:30:23.841 10279 10279 D [CarMode]: [AutoLaunchReceiver]-ACTION_BOND_STATE_CHANGED G4-1 state is 10
03-31 16:30:23.841  3440  3483 D SettingsProvider: name = bluetooth_headset_priority_F8:95:C7:87:3C:51
03-31 16:30:23.841  3440  3483 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-31 16:30:23.841  3440  3483 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-31 16:30:23.841  3440  3483 D SettingsProvider: selectionArgs: false
03-31 16:30:23.841  3440  3483 D SettingsProvider: selectionArgs: 1002
03-31 16:30:23.846  3440  3483 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,03-31 16:30:23.846  3440  3483 D SettingsProvider: ret = -1
03-31 16:30:23.846  5838  5950 I BluetoothBondStateMachine: StableState(): Entering Off State
,03-31 16:30:23.846  3440  4048 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2cc5c648 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{37e85c63 10279:com.sec.android.automotive.drivelink/u0a102}
,03-31 16:30:23.846 10469 10469 D GMHFPReceiver: onServiceConnected() : 1
03-31 16:30:23.846 10469 10469 D GMHFPReceiver: mBluetoothHeadset = true
,03-31 16:30:23.851  3440  4047 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
,03-31 16:30:23.856 10279 11725 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,03-31 16:30:23.861  3440  3946 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2cc5c648 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{3d08b54e 10469:com.samsung.android.app.watchmanagerstub/u0a121}
,03-31 16:30:23.861 10469 10469 E BluetoothHeadset: BTStateChangeCB is registed
,03-31 16:30:23.861 10469 10469 D GMHFPReceiver: android.bluetooth.device.action.BOND_STATE_CHANGED
03-31 16:30:23.861 10469 10469 D GMHFPReceiver: jangil::setProperties()
,03-31 16:30:23.866 10469 10469 D GMHFPReceiver: jangil::printBTStatus()
,03-31 16:30:23.866  3440  4064 D SettingsProvider: name = Wearable0001
03-31 16:30:23.866  3440  4064 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-31 16:30:23.866  3440  4064 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-31 16:30:23.866  3440  4064 D SettingsProvider: selectionArgs: false
03-31 16:30:23.866  3440  4064 D SettingsProvider: selectionArgs: 10121
03-31 16:30:23.866  3440  4064 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,03-31 16:30:23.866  3440  4064 D SettingsProvider: ret = -1
03-31 16:30:23.866 10469 10469 D GMHFPReceiver: ::::::::Wearable0001::false
,03-31 16:30:23.866  3440  4421 D SettingsProvider: name = Wearable0002
03-31 16:30:23.866  3440  4421 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-31 16:30:23.866  3440  4421 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-31 16:30:23.866  3440  4421 D SettingsProvider: selectionArgs: false
03-31 16:30:23.866  3440  4421 D SettingsProvider: selectionArgs: 10121
03-31 16:30:23.866  3440  4421 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,03-31 16:30:23.866  3440  4421 D SettingsProvider: ret = -1
03-31 16:30:23.866 10469 10469 D GMHFPReceiver: ::::::::Wearable0002::false
,03-31 16:30:23.871  3440  3901 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2cc5c648 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{374a433e 4334:com.google.android.gms.persistent/u0a14}
,03-31 16:30:23.966 10469 10469 D GMHFPReceiver: onServiceConnected() : 1
03-31 16:30:23.966 10469 10469 D GMHFPReceiver: mBluetoothHeadset = true
,03-31 16:30:24.646  3440  4047 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-31 16:30:24.651  3440  4047 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 16:30:24.651  3440  4047 D BatteryService: online:4, current avg:36, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:42
03-31 16:30:24.651  3440  3440 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 16:30:24.656  3440  4047 D BatteryService: stay LED for fully charged
,03-31 16:30:24.661  3440  3440 I MotionRecognitionService: Plugged,
03-31 16:30:24.661  3440  3440 D MotionRecognitionService:   cableConnection= 1,
,03-31 16:30:24.661  3440  3440 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
,03-31 16:30:24.661  3440  3440 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 16:30:24.676  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-31 16:30:24.676  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 16:30:24.676  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 16:30:24.696  5838  5838 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 16:30:24.696  5838  5954 D HeadsetStateMachine: Disconnected process message: 10
,03-31 16:30:24.706  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 16:30:24.706  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 16:30:24.706  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 16:30:24.706  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 16:30:24.811  3440  3618 V AlarmManager: waitForAlarm result :4
,03-31 16:30:24.821  5838  5838 D BtGatt.ScanManager: awakened up at time 266238
,03-31 16:30:24.826  5838  5952 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-31 16:30:24.831  5838  5944 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,03-31 16:30:24.831  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 16:30:24.841  5838  6006 D IOP_DB_BT: db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 16:30:24.841  5838  6006 D IOP_DB_BT: db_query_add_key: key KEY_LMP_MFCT, value 15
03-31 16:30:24.841  5838  6006 D IOP_DB_BT: db_query_add_key: key KEY_LMP_VER, value 7:8975
03-31 16:30:24.841  5838  6006 D IOP_DB_BT: db_query_add_key: key KEY_DIR_ALL, value *
03-31 16:30:24.841  5838  6006 D IOP_DB_BT: db_query_execute: result 1
03-31 16:30:24.841  5838  6006 D IOP_DB_BT: db_query_create: id EnforceSlaveRole :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 16:30:24.841  5838  6006 D IOP_DB_BT: db_query_add_key: key KEY_LMP_MFCT, value 15
03-31 16:30:24.841  5838  6006 D IOP_DB_BT: db_query_add_key: key KEY_LMP_VER, value 7:8975
03-31 16:30:24.841  5838  6006 D IOP_DB_BT: db_query_add_key: key KEY_DIR_ALL, value *
03-31 16:30:24.841  5838  6006 D IOP_DB_BT: db_query_execute: result 1
,03-31 16:30:25.056  5838  6006 D IOP_DB_BT: db_query: id SkipSdpInfo :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61,
,03-31 16:30:25.056  5838  6006 D IOP_DB_BT: db_query: result 1
,03-31 16:30:25.076  5838  6006 D IOP_DB_BT: db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 16:30:25.076  5838  6006 D IOP_DB_BT: db_query_add_key: key KEY_LMP_MFCT, value 15
03-31 16:30:25.076  5838  6006 D IOP_DB_BT: db_query_add_key: key KEY_LMP_VER, value 7:8975
03-31 16:30:25.076  5838  6006 D IOP_DB_BT: db_query_add_key: key KEY_DIR_ALL, value *
03-31 16:30:25.076  5838  6006 D IOP_DB_BT: db_query_execute: result 1
03-31 16:30:25.076  5838  6006 W bt-btif : bta_dm_acl_change(), event : 0
03-31 16:30:25.076  5838  6006 W bt-btif : info:x10
03-31 16:30:25.076  5838  5944 D         : remote version info [f8:cf:c5:d9:e5:61]: 7, f, 230f
03-31 16:30:25.076  5838  5944 E BluetoothRemoteDevices: aclStateChangeCallback: Device is NULL
03-31 16:30:25.076  5838  6006 W bt-btif : bta_dm_acl_change(), event : 2
,03-31 16:30:25.121  5838  5944 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,03-31 16:30:25.621  5838  6006 E bt-btm  : tBTM_SEC_DEV:0xb34a50d8 rs_disc_pending=1
03-31 16:30:25.621  5838  6006 W bt-btif : bta_dm_acl_change(), event : 3
03-31 16:30:25.621  5838  6006 W bt-btif : bta_dm_check_av:0
03-31 16:30:25.621  5838  5944 W bt-btif : btif_dm_cback : unhandled event (14)
,03-31 16:30:25.651  3440  6049 D SSRM:n  : SIOP:: AP = 270, PST = 275 (W:14), CUR = 36, LCD = 0
,03-31 16:30:25.831  3440  3618 V AlarmManager: waitForAlarm result :4
,03-31 16:30:25.846  5838  5838 D BtGatt.ScanManager: awakened up at time 267261
03-31 16:30:25.851  5838  5952 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-31 16:30:25.851  5838  5944 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-31 16:30:25.851  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 16:30:25.876  5838  5944 W bt-btif : btif_dm_ssp_cfm_req_evt
,03-31 16:30:25.881  5838  5944 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
03-31 16:30:25.881  5838  5944 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
03-31 16:30:25.881  5838  5944 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:CF:C5:D9:E5:61 newState: 1
,03-31 16:30:25.891  3440  3965 D SecContentProvider: query(), uri = 4 selection = bluetoothLogForRemote
03-31 16:30:25.891  5838  5944 E bt-btif : check_cod: remote_cod = 0x5a020c
03-31 16:30:25.891  5838  5944 W bt-btif : btif_dm_ssp_reply: accept=1
03-31 16:30:25.896  5838  5950 I BluetoothBondStateMachine: Bond State Change Intent:F8:CF:C5:D9:E5:61 OldState: 10 NewState: 11
,03-31 16:30:25.901  3440  3440 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
03-31 16:30:25.901  3724  3724 D BluetoothTile:  onBluetoothPairedDevicesChanged:
03-31 16:30:25.901  3440  3440 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.device.action.BOND_STATE_CHANGED
03-31 16:30:25.901  3440  3440 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED
03-31 16:30:25.901  3440  3440 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 10,
03-31 16:30:25.901  3440  3440 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 11
03-31 16:30:25.901  3440  3440 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
,03-31 16:30:25.911  5838  5944 W bt-btif : btif_dm_auth_cmpl_evt
,03-31 16:30:25.916  3440  3575 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3e7d1660 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{26a43956 10218:com.android.settings/1000}
,03-31 16:30:25.911  5838  5944 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,03-31 16:30:25.916  3440  4739 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
,03-31 16:30:25.921  5838  5950 D BtConfig.SecureMode: isSecureModeOn:false
03-31 16:30:25.921  5838  5950 I BluetoothBondStateMachine: Entering PendingCommandState State
03-31 16:30:25.926 10218 10218 D BluetoothNotiBroadcastReceiver: onReceive
,03-31 16:30:25.926  5838  5944 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:CF:C5:D9:E5:61 newState: 0
03-31 16:30:25.926  5838  5950 D BluetoothAdapterProperties: Failed to remove device: F8:CF:C5:D9:E5:61
,03-31 16:30:25.931 10279 11749 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,03-31 16:30:25.931  3440  3946 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3e7d1660 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{37e85c63 10279:com.sec.android.automotive.drivelink/u0a102}
,03-31 16:30:25.931 10279 10279 D [CarModeFW]: ConnectivityManager-handleMessage PAIRING_DEVICES
,03-31 16:30:25.931 10279 10279 D [CarMode]: [AutoLaunchReceiver]-action: android.bluetooth.device.action.BOND_STATE_CHANGED
,03-31 16:30:25.936  3440  3483 D SecContentProvider: query(), uri = 4 selection = bluetoothLogForRemote
,03-31 16:30:25.936  3724  4681 D BluetoothTile:  handleUpdatestate:false name:null
,03-31 16:30:25.936 10279 10279 D [CarMode]: [AutoLaunchReceiver]-ACTION_BOND_STATE_CHANGED Nexus 6 state is 11
,03-31 16:30:25.941  5838  5950 I BluetoothBondStateMachine: Bond State Change Intent:F8:CF:C5:D9:E5:61 OldState: 11 NewState: 10
,03-31 16:30:25.941  3440  3440 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
03-31 16:30:25.941  3440  3440 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.device.action.BOND_STATE_CHANGED
03-31 16:30:25.941  3440  3440 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED
03-31 16:30:25.941  3440  3440 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 11
03-31 16:30:25.941  3440  3440 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 10
03-31 16:30:25.941  3440  3440 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
,03-31 16:30:25.941  3724  3724 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,03-31 16:30:25.946  3724  4681 D BluetoothTile:  handleUpdatestate:false name:null
,03-31 16:30:25.951  3440  3575 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3e7d1660 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{37e85c63 10279:com.sec.android.automotive.drivelink/u0a102}
,03-31 16:30:25.951  3440  4737 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
,03-31 16:30:25.956  5838  5950 D BtConfig.SecureMode: isSecureModeOn:false
,03-31 16:30:25.956  3440  4739 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
,03-31 16:30:25.956  5838  5950 D HidService: getHidService(): returning com.android.bluetooth.hid.HidService@3842cbb
,03-31 16:30:25.961  3440  3965 D SettingsProvider: name = bluetooth_input_device_priority_F8:CF:C5:D9:E5:61
03-31 16:30:25.961  3440  3965 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-31 16:30:25.961  3440  3965 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-31 16:30:25.961  3440  3965 D SettingsProvider: selectionArgs: false
03-31 16:30:25.961  3440  3965 D SettingsProvider: selectionArgs: 1002
03-31 16:30:25.961  3440  3965 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,03-31 16:30:25.961  3440  3965 D SettingsProvider: ret = -1
03-31 16:30:25.961  5838  5950 D HidService: Saved priority F8:CF:C5:D9:E5:61 = -1
,03-31 16:30:25.961 10279 11752 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
03-31 16:30:25.961  3440  4047 D SettingsProvider: name = bluetooth_a2dp_sink_priority_F8:CF:C5:D9:E5:61
03-31 16:30:25.961  3440  4047 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-31 16:30:25.961  3440  4047 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-31 16:30:25.961  3440  4047 D SettingsProvider: selectionArgs: false
03-31 16:30:25.961  3440  4047 D SettingsProvider: selectionArgs: 1002
03-31 16:30:25.961  3440  4047 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,03-31 16:30:25.966  3440  4047 D SettingsProvider: ret = -1
,03-31 16:30:25.966  3440  4421 D SettingsProvider: name = bluetooth_headset_priority_F8:CF:C5:D9:E5:61
03-31 16:30:25.966  3440  4421 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-31 16:30:25.966  3440  4421 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-31 16:30:25.966  3440  4421 D SettingsProvider: selectionArgs: false
03-31 16:30:25.966  3440  4421 D SettingsProvider: selectionArgs: 1002
03-31 16:30:25.966  3440  4724 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3e7d1660 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{3d08b54e 10469:com.samsung.android.app.watchmanagerstub/u0a121}
03-31 16:30:25.966  3440  4421 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,03-31 16:30:25.966  3440  4421 D SettingsProvider: ret = -1
03-31 16:30:25.966 10279 11752 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
03-31 16:30:25.966 10469 10469 E BluetoothHeadset: BTStateChangeCB is registed
03-31 16:30:25.966  5838  5950 I BluetoothBondStateMachine: StableState(): Entering Off State
,03-31 16:30:25.966 10279 10279 D [CarModeFW]: ConnectivityManager-handleMessage PAIRING_DEVICES
,03-31 16:30:25.971 10469 10469 D GMHFPReceiver: android.bluetooth.device.action.BOND_STATE_CHANGED
03-31 16:30:25.971 10469 10469 D GMHFPReceiver: jangil::setProperties()
,03-31 16:30:25.976 10469 10469 D GMHFPReceiver: jangil::printBTStatus()
,03-31 16:30:25.976  3440  3733 D SettingsProvider: name = Wearable0001
03-31 16:30:25.976  3440  3733 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,03-31 16:30:25.976  3440  3733 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-31 16:30:25.976  3440  3733 D SettingsProvider: selectionArgs: false
03-31 16:30:25.976  3440  3733 D SettingsProvider: selectionArgs: 10121
03-31 16:30:25.976  3440  3733 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
03-31 16:30:25.976  3440  3733 D SettingsProvider: ret = -1
,03-31 16:30:25.976 10469 10469 D GMHFPReceiver: ::::::::Wearable0001::false
03-31 16:30:25.976  3440  3965 D SettingsProvider: name = Wearable0002
,03-31 16:30:25.976  3440  3965 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-31 16:30:25.976  3440  3965 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-31 16:30:25.976  3440  3965 D SettingsProvider: selectionArgs: false
03-31 16:30:25.976  3440  3965 D SettingsProvider: selectionArgs: 10121
,03-31 16:30:25.976  3440  3965 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
03-31 16:30:25.976  3440  3965 D SettingsProvider: ret = -1
03-31 16:30:25.976 10469 10469 D GMHFPReceiver: ::::::::Wearable0002::false
,03-31 16:30:25.981  3440  4064 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3e7d1660 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{374a433e 4334:com.google.android.gms.persistent/u0a14}
,03-31 16:30:25.986  3440  4064 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{110d388c u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{26a43956 10218:com.android.settings/1000}
,03-31 16:30:25.991 10218 10218 D BluetoothNotiBroadcastReceiver: onReceive
,03-31 16:30:25.996  3440  4064 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{110d388c u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{37e85c63 10279:com.sec.android.automotive.drivelink/u0a102}
,03-31 16:30:25.996 10279 10279 D [CarMode]: [AutoLaunchReceiver]-action: android.bluetooth.device.action.BOND_STATE_CHANGED
,03-31 16:30:25.996 10279 10279 D [CarMode]: [AutoLaunchReceiver]-ACTION_BOND_STATE_CHANGED Nexus 6 state is 10
,03-31 16:30:26.001  3440  4737 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{110d388c u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{37e85c63 10279:com.sec.android.automotive.drivelink/u0a102}
,03-31 16:30:26.001  3440  4421 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
,03-31 16:30:26.011 10279 11753 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,03-31 16:30:26.011  3440  3901 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{110d388c u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{3d08b54e 10469:com.samsung.android.app.watchmanagerstub/u0a121}
,03-31 16:30:26.016 10469 10469 E BluetoothHeadset: BTStateChangeCB is registed
,03-31 16:30:26.016 10469 10469 D GMHFPReceiver: android.bluetooth.device.action.BOND_STATE_CHANGED
03-31 16:30:26.016 10469 10469 D GMHFPReceiver: jangil::setProperties()
,03-31 16:30:26.016 10469 10469 D GMHFPReceiver: jangil::printBTStatus()
,03-31 16:30:26.016  3440  3965 D SettingsProvider: name = Wearable0001
03-31 16:30:26.016  3440  3965 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-31 16:30:26.016  3440  3965 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-31 16:30:26.016  3440  3965 D SettingsProvider: selectionArgs: false
03-31 16:30:26.016  3440  3965 D SettingsProvider: selectionArgs: 10121
03-31 16:30:26.016  3440  3965 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,03-31 16:30:26.021  3440  3965 D SettingsProvider: ret = -1
03-31 16:30:26.021 10469 10469 D GMHFPReceiver: ::::::::Wearable0001::false
,03-31 16:30:26.021  3440  4047 D SettingsProvider: name = Wearable0002
03-31 16:30:26.021  3440  4047 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-31 16:30:26.021  3440  4047 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-31 16:30:26.021  3440  4047 D SettingsProvider: selectionArgs: false
03-31 16:30:26.021  3440  4047 D SettingsProvider: selectionArgs: 10121
03-31 16:30:26.021  3440  4047 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,03-31 16:30:26.021  3440  4047 D SettingsProvider: ret = -1
03-31 16:30:26.021 10469 10469 D GMHFPReceiver: ::::::::Wearable0002::false
,03-31 16:30:26.021  5838  6006 W bt-btif : new conn_srvc id:26, app_id:255
03-31 16:30:26.021  5838  6006 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
,03-31 16:30:26.021  5838  6006 W bt-btif : bta_dm_pm_ssr:2, lat:1200
03-31 16:30:26.021 11128 11693 D BluetoothSocket: socket fd passed by stack  fds: [Ljava.io.FileDescriptor;@62f88d3
,03-31 16:30:26.026  3440  4064 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{110d388c u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{374a433e 4334:com.google.android.gms.persistent/u0a14}
,03-31 16:30:26.031  5838  9004 E BluetoothRemoteDevices: setRfcommConnected true
,03-31 16:30:26.031 11128 11693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection accepted
,03-31 16:30:26.036 11128 11693 D BluetoothSocket: getInputStream(): myUserId = 0
,03-31 16:30:26.036 11128 11693 D BluetoothSocket: getOutputStream(): myUserId = 0
,03-31 16:30:26.041 11128 11693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection initialized (thread ID: 1546)
03-31 16:30:26.041 11128 11693 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@41fbc10, channel: 6, state: LISTENING
03-31 16:30:26.041 11128 11693 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@41fbc10, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@69225f8, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@31302309mSocket: android.net.LocalSocket@3e21d90e impl:android.net.LocalSocketImpl@335fdf2f fd:FileDescriptor[93]
03-31 16:30:26.041 11128 11693 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3e21d90e impl:android.net.LocalSocketImpl@335fdf2f fd:FileDescriptor[93]
03-31 16:30:26.041 11128 11693 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-31 16:30:26.041 11128 11755 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 1546)
,03-31 16:30:26.041 11128 11693 D BluetoothSocket: bindListen(): myUserId = 0
03-31 16:30:26.041 11128 11693 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-31 16:30:26.046 11128 11693 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[119]}
03-31 16:30:26.046 11128 11693 D BluetoothSocket: bindListen(), new LocalSocket 
03-31 16:30:26.046 11128 11693 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-31 16:30:26.046 11128 11693 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@232c893c
03-31 16:30:26.046 11128 11693 D BluetoothSocket: channel: 6
03-31 16:30:26.046 11128 11693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-31 16:30:26.051  5838  6006 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
,03-31 16:30:26.051 11128 11755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesRead: Read 15 bytes successfully (thread ID: 1546)
03-31 16:30:26.051  5838  6006 D IOP_DB_BT: db_query: result 1
03-31 16:30:26.051  5838  6006 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 16:30:26.051  5838  6006 D IOP_DB_BT: db_query: result 1
,03-31 16:30:26.051 11128 11755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Got valid identity from [<no peer name> F8:CF:C5:D9:E5:61]
03-31 16:30:26.051 11128 11755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesWritten: 15 bytes successfully written (thread ID: 1546)
03-31 16:30:26.051 11128 11755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: removeThreadFromList: Removing thread with ID 1546
03-31 16:30:26.051 11128 11755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Handshake thread disposed (thread ID: 1546)
,03-31 16:30:26.051  5838  6006 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 16:30:26.051 11128 11755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onIncomingConnectionConnected: [<no peer name> F8:CF:C5:D9:E5:61]
03-31 16:30:26.051  5838  6006 D IOP_DB_BT: db_query: result 1
03-31 16:30:26.051  5838  6006 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 16:30:26.051 11128 11755 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 1546)
03-31 16:30:26.051 11128 11128 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:CF:C5:D9:E5:61]
03-31 16:30:26.051  5838  6006 D IOP_DB_BT: db_query: result 1
03-31 16:30:26.051 11128 11128 I io.jxcore.node.ConnectionHelper: onConnected: Incoming connection to peer [<no peer name> F8:CF:C5:D9:E5:61]
,03-31 16:30:26.051 11128 11128 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:CF:C5:D9:E5:61] updated - the peer count is 2
,03-31 16:30:26.056 11128 11128 D BluetoothSocket: getInputStream(): myUserId = 0
,03-31 16:30:26.056 11128 11128 D BluetoothSocket: getOutputStream(): myUserId = 0
,03-31 16:30:26.056 11128 11128 I io.jxcore.node.ConnectionHelper: lowerBleDiscoveryPowerAndStartResetTimer: Lowering the power settings
03-31 16:30:26.056 11128 11128 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 2 -> 0
03-31 16:30:26.056 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-31 16:30:26.056 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 16:30:26.056 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-31 16:30:26.056 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-31 16:30:26.056 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-31 16:30:26.056 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-31 16:30:26.061  5838  5951 D BtGatt.AdvertiseManager: message : 1
,03-31 16:30:26.061  5838  5951 D BtGatt.AdvertiseManager: stop advertise for client 7
03-31 16:30:26.061  5838  5951 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
,03-31 16:30:26.061  5838  5951 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,03-31 16:30:26.061  5838  5944 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-31 16:30:26.061  5838  5944 D BtGatt.GattService: Client app is not null!
,03-31 16:30:26.061  5838  5850 D BtGatt.GattService: unregisterClient() - clientIf=7
03-31 16:30:26.066 11128 11128 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-31 16:30:26.066 11128 11128 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-31 16:30:26.066 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 3, timeout: 0, is connectable: false
03-31 16:30:26.066 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 16:30:26.066 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-31 16:30:26.066 11128 11128 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-31 16:30:26.066 11128 11128 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 16:30:26.066 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 16:30:26.066 11128 11128 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-31 16:30:26.066  5838  5850 D BtGatt.GattService: registerClient() - UUID=8711aa6e-078c-4969-991e-899fa7b3ecbb
,03-31 16:30:26.071 10469 10469 D GMHFPReceiver: onServiceConnected() : 1
03-31 16:30:26.071 10469 10469 D GMHFPReceiver: mBluetoothHeadset = true
,03-31 16:30:26.111  5838  5944 D BtGatt.GattService: onClientRegistered() - UUID=8711aa6e-078c-4969-991e-899fa7b3ecbb, clientIf=7
,03-31 16:30:26.111 11128 11144 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-31 16:30:26.116 10469 10469 D GMHFPReceiver: onServiceConnected() : 1
,03-31 16:30:26.116 10469 10469 D GMHFPReceiver: mBluetoothHeadset = true
,03-31 16:30:26.141  5838  5955 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 58
,03-31 16:30:26.141  5838  5951 D BtGatt.AdvertiseManager: message : 0
03-31 16:30:26.141  5838  5951 D BtGatt.AdvertiseManager: number of adv instance running0
,03-31 16:30:26.141  5838  5951 D BtGatt.AdvertiseManager: size of list is =0
,03-31 16:30:26.146  5838  5951 D BtGatt.AdvertiseManager: starting advertising
03-31 16:30:26.146  5838  5951 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-31 16:30:26.151  5838  5944 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0,
03-31 16:30:26.151  5838  5951 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 16:30:26.151  5838  5944 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
03-31 16:30:26.151  5838  5951 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-31 16:30:26.151  5838  5951 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 0, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,03-31 16:30:26.156 11128 11128 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-31 16:30:26.156  5838  9004 D BtGatt.GattService: stopScan() - queue size =1
,03-31 16:30:26.156  5838  5952 D BtGatt.ScanManager: filter size is 1
,03-31 16:30:26.156  5838  5952 D BtGatt.ScanManager: delete FilterIndex - 11
03-31 16:30:26.161  5838  5850 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-31 16:30:26.161  5838  5944 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-31 16:30:26.161  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 16:30:26.161  5838  5952 D BtGatt.ScanManager: stopping BLe Batch
03-31 16:30:26.161 11128 11128 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 16:30:26.161 11128 11128 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-31 16:30:26.161 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 16:30:26.161 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 16:30:26.161 11128 11128 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 16:30:26.161 11128 11128 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 16:30:26.161  5838  5944 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-31 16:30:26.161  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 16:30:26.171  5838  5952 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-31 16:30:26.171  5838  5944 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-31 16:30:26.171  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 16:30:26.171  5838  5955 D BtGatt.GattService: registerClient() - UUID=3637fdeb-b723-44d0-84f5-fe21c1ecee6c,
,03-31 16:30:26.211  5838  5944 D BtGatt.GattService: onClientRegistered() - UUID=3637fdeb-b723-44d0-84f5-fe21c1ecee6c, clientIf=6
,03-31 16:30:26.211 11128 11144 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-31 16:30:26.216  5838  5848 D BtGatt.GattService: start scan with filters
,03-31 16:30:26.231  5838  5848 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 74
,03-31 16:30:26.231  5838  5952 D BtGatt.ScanManager: handling starting scan
03-31 16:30:26.231  5838  5952 D BtGatt.ScanManager: isFilteringSupported
03-31 16:30:26.231  5838  5952 D BluetoothAdapter: setting StandAloneBleMode
,03-31 16:30:26.236  5838  5944 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-31 16:30:26.236  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 16:30:26.236  5838  5952 D BtGatt.ScanManager: allow scan with filters
03-31 16:30:26.236  5838  5952 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-31 16:30:26.236  5838  5952 D BtGatt.ScanManager: set filter index= 12 for clientIf= 6
03-31 16:30:26.241  5838  5944 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-31 16:30:26.241  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 16:30:26.241  5838  5952 D BtGatt.ScanManager: Starting BLE batch scan
03-31 16:30:26.241  5838  5952 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-31 16:30:26.246  5838  5944 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-31 16:30:26.246  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 16:30:26.246  5838  5944 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-31 16:30:26.246  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 16:30:26.251 11128 11128 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 16:30:26.251 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 16:30:26.251 11128 11128 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 3 -> 1
03-31 16:30:26.251 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-31 16:30:26.251 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 16:30:26.251 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-31 16:30:26.251 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-31 16:30:26.251 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-31 16:30:26.251 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-31 16:30:26.256  5838  5951 D BtGatt.AdvertiseManager: message : 1
03-31 16:30:26.256  5838  5951 D BtGatt.AdvertiseManager: stop advertise for client 7
03-31 16:30:26.256  5838  5951 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-31 16:30:26.256  5838  5951 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-31 16:30:26.256  5838  5944 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-31 16:30:26.256  5838  5944 D BtGatt.GattService: Client app is not null!
03-31 16:30:26.261  5838  5955 D BtGatt.GattService: unregisterClient() - clientIf=7
03-31 16:30:26.261 11128 11128 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 16:30:26.261 11128 11128 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-31 16:30:26.261 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-31 16:30:26.261 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 16:30:26.261 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-31 16:30:26.261 11128 11128 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-31 16:30:26.261 11128 11128 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 16:30:26.261 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 16:30:26.261 11128 11128 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-31 16:30:26.271  5838  5850 D BtGatt.GattService: registerClient() - UUID=595283d6-cb4f-4562-8127-3a3ee73ae4fb
,03-31 16:30:26.311  5838  5944 D BtGatt.GattService: onClientRegistered() - UUID=595283d6-cb4f-4562-8127-3a3ee73ae4fb, clientIf=7
,03-31 16:30:26.311 11128 11144 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-31 16:30:26.326  5838  9004 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 59
,03-31 16:30:26.326  5838  5951 D BtGatt.AdvertiseManager: message : 0
,03-31 16:30:26.326  5838  5951 D BtGatt.AdvertiseManager: number of adv instance running0
03-31 16:30:26.326  5838  5951 D BtGatt.AdvertiseManager: size of list is =0
,03-31 16:30:26.326  5838  5951 D BtGatt.AdvertiseManager: starting advertising
,03-31 16:30:26.326  5838  5951 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-31 16:30:26.331  5838  5944 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0,
,03-31 16:30:26.331  5838  5951 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 16:30:26.331  5838  5944 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0,
03-31 16:30:26.336  5838  5951 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-31 16:30:26.336  5838  5951 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 0, TxPowerLevel: 1, isConnectable: false, Timeout: 0
,03-31 16:30:26.336 11128 11128 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-31 16:30:26.336  5838  5848 D BtGatt.GattService: stopScan() - queue size =1
03-31 16:30:26.336 11128 11140 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3b6c94f3, channel: 6, state: CLOSED,
03-31 16:30:26.336  5838  5952 D BtGatt.ScanManager: filter size is 1,
03-31 16:30:26.336  5838  5952 D BtGatt.ScanManager: delete FilterIndex - 12
03-31 16:30:26.336  5838  5850 D BtGatt.GattService: unregisterClient() - clientIf=6
03-31 16:30:26.336 11128 11128 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-31 16:30:26.336 11128 11128 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 16:30:26.336 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 16:30:26.336 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 16:30:26.336 11128 11128 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 16:30:26.336 11128 11128 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-31 16:30:26.336  5838  5944 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-31 16:30:26.336  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 16:30:26.336  5838  5952 D BtGatt.ScanManager: stopping BLe Batch
03-31 16:30:26.341 11128 11140 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1ea3af6b, channel: 6, state: CLOSED
03-31 16:30:26.341 11128 11140 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3590a199, channel: 6, state: CLOSED
,03-31 16:30:26.341  5838  5944 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-31 16:30:26.341  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 16:30:26.341  5838  5952 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-31 16:30:26.341 11128 11140 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@41fbc10, channel: 6, state: CLOSED
,03-31 16:30:26.341  5838  5944 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-31 16:30:26.341  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 16:30:26.341  5838  5850 D BtGatt.GattService: registerClient() - UUID=fa4bcd62-caba-44c8-a18c-98892d253d0a
,03-31 16:30:26.386  5838  5944 D BtGatt.GattService: onClientRegistered() - UUID=fa4bcd62-caba-44c8-a18c-98892d253d0a, clientIf=6
,03-31 16:30:26.386 11128 11144 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-31 16:30:26.386  5838  9004 D BtGatt.GattService: start scan with filters
,03-31 16:30:26.406  5838  9004 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 75
,03-31 16:30:26.406 11128 11128 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 16:30:26.406 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 16:30:26.406 11128 11128 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 2 -> 0
03-31 16:30:26.406 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-31 16:30:26.406 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 16:30:26.406 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-31 16:30:26.406 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-31 16:30:26.406 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-31 16:30:26.406 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-31 16:30:26.406  5838  5952 D BtGatt.ScanManager: handling starting scan
03-31 16:30:26.406  5838  5952 D BtGatt.ScanManager: isFilteringSupported
03-31 16:30:26.406  5838  5952 D BluetoothAdapter: setting StandAloneBleMode
,03-31 16:30:26.411  5838  5944 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1,
03-31 16:30:26.411  5838  5951 D BtGatt.AdvertiseManager: message : 1
03-31 16:30:26.411  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 16:30:26.411  5838  5952 D BtGatt.ScanManager: allow scan with filters
03-31 16:30:26.411  5838  5952 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,03-31 16:30:26.411  5838  5952 D BtGatt.ScanManager: set filter index= 13 for clientIf= 6
03-31 16:30:26.411  5838  5951 D BtGatt.AdvertiseManager: stop advertise for client 7
03-31 16:30:26.411  5838  5951 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-31 16:30:26.411  5838  5944 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,03-31 16:30:26.411  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 16:30:26.411  5838  5952 D BtGatt.ScanManager: Starting BLE batch scan
03-31 16:30:26.416  5838  5951 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-31 16:30:26.416  5838  5952 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-31 16:30:26.416  5838  5944 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-31 16:30:26.416  5838  5944 D BtGatt.GattService: Client app is not null!
,03-31 16:30:26.416  5838  5848 D BtGatt.GattService: unregisterClient() - clientIf=7
,03-31 16:30:26.421 11128 11128 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-31 16:30:26.421  5838  5944 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-31 16:30:26.421 11128 11128 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-31 16:30:26.421  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 16:30:26.421 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
,03-31 16:30:26.421 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 16:30:26.421 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-31 16:30:26.421 11128 11128 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-31 16:30:26.421 11128 11128 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 16:30:26.421 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 16:30:26.421 11128 11128 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-31 16:30:26.421  5838  5944 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-31 16:30:26.421  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 16:30:26.431  5838  5848 D BtGatt.GattService: registerClient() - UUID=41eff409-8769-4060-85c5-52a5fc7dffde,
,03-31 16:30:26.471  5838  5944 D BtGatt.GattService: onClientRegistered() - UUID=41eff409-8769-4060-85c5-52a5fc7dffde, clientIf=7
,03-31 16:30:26.471 11128 11777 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-31 16:30:26.486  5838  5850 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 60
,03-31 16:30:26.486  5838  5951 D BtGatt.AdvertiseManager: message : 0
03-31 16:30:26.486  5838  5951 D BtGatt.AdvertiseManager: number of adv instance running0
,03-31 16:30:26.486  5838  5951 D BtGatt.AdvertiseManager: size of list is =0
,03-31 16:30:26.486  5838  5951 D BtGatt.AdvertiseManager: starting advertising
,03-31 16:30:26.486  5838  5951 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-31 16:30:26.491  5838  5944 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-31 16:30:26.491  5838  5951 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 16:30:26.491  5838  5944 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-31 16:30:26.491  5838  5951 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-31 16:30:26.491  5838  5951 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 0, TxPowerLevel: 1, isConnectable: false, Timeout: 0
03-31 16:30:26.491 11128 11128 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-31 16:30:26.496  5838  9004 D BtGatt.GattService: stopScan() - queue size =1
,03-31 16:30:26.496  5838  5952 D BtGatt.ScanManager: filter size is 1
03-31 16:30:26.496  5838  5952 D BtGatt.ScanManager: delete FilterIndex - 13
03-31 16:30:26.496  5838  5848 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-31 16:30:26.496 11128 11128 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 16:30:26.496 11128 11128 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-31 16:30:26.496 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-31 16:30:26.496 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 16:30:26.496 11128 11128 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-31 16:30:26.496 11128 11128 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-31 16:30:26.496  5838  5944 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-31 16:30:26.496  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 16:30:26.496  5838  5952 D BtGatt.ScanManager: stopping BLe Batch
03-31 16:30:26.496  5838  5944 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,03-31 16:30:26.496  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 16:30:26.501  5838  5952 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-31 16:30:26.501  5838  5848 D BtGatt.GattService: registerClient() - UUID=b644cbf8-4d3e-42fe-ba06-9141a7c264a4
,03-31 16:30:26.501  5838  5944 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-31 16:30:26.501  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 16:30:26.541  5838  5944 D BtGatt.GattService: onClientRegistered() - UUID=b644cbf8-4d3e-42fe-ba06-9141a7c264a4, clientIf=6
,03-31 16:30:26.541 11128 11138 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-31 16:30:26.541  5838  5955 D BtGatt.GattService: start scan with filters
,03-31 16:30:26.556  5838  5955 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 76
,03-31 16:30:26.556 11128 11128 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-31 16:30:26.556 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 16:30:26.556  5838  5952 D BtGatt.ScanManager: handling starting scan
03-31 16:30:26.556  5838  5952 D BtGatt.ScanManager: isFilteringSupported
,03-31 16:30:26.556  5838  5952 D BluetoothAdapter: setting StandAloneBleMode
03-31 16:30:26.556 11128 11128 I io.jxcore.node.ConnectionHelper: onConnected: Incoming socket thread, for peer [<no peer name> F8:CF:C5:D9:E5:61], created successfully
03-31 16:30:26.556 11128 11128 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 1
,03-31 16:30:26.556 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 16:30:26.556 11128 11128 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-31 16:30:26.556 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-31 16:30:26.556 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 16:30:26.556 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 16:30:26.556 11128 11779 D io.jxcore.node.IncomingSocketThread: Entering thread (ID: 1547)
03-31 16:30:26.561  5838  5944 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-31 16:30:26.561  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 16:30:26.561  5838  5952 D BtGatt.ScanManager: allow scan with filters
03-31 16:30:26.561  5838  5952 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-31 16:30:26.561  5838  5952 D BtGatt.ScanManager: set filter index= 14 for clientIf= 6
03-31 16:30:26.561  2874  3473 D EnterpriseController: netId is 0
03-31 16:30:26.561  2874  3473 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,03-31 16:30:26.561  5838  5944 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-31 16:30:26.561  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 16:30:26.561  5838  5952 D BtGatt.ScanManager: Starting BLE batch scan
03-31 16:30:26.561  5838  5952 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-31 16:30:26.566  5838  5944 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0,
,03-31 16:30:26.566  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 16:30:26.566 11128 11779 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 46988
03-31 16:30:26.566 11128 11779 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
03-31 16:30:26.566 11128 11779 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-31 16:30:26.566  5838  5944 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,03-31 16:30:26.566  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 16:30:26.566 11128 11779 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-31 16:30:26.566 11128 11779 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 1547)
03-31 16:30:26.566 11128 11779 D io.jxcore.node.IncomingSocketThread: Exiting thread (ID: 1547)
03-31 16:30:26.571 11128 11782 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1550, name: Receiver)
,03-31 16:30:26.571 11128 11781 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1549, name: Sender)
,03-31 16:30:27.566  3440  3618 V AlarmManager: waitForAlarm result :4
,03-31 16:30:27.581  5838  5838 D BtGatt.ScanManager: awakened up at time 268995
,03-31 16:30:27.586  5838  5952 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-31 16:30:27.591  5838  5944 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0,
03-31 16:30:27.591  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,03-31 16:30:28.611  3440  3618 V AlarmManager: waitForAlarm result :4
,03-31 16:30:28.621  5838  5838 D BtGatt.ScanManager: awakened up at time 270037
03-31 16:30:28.626  5838  5952 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-31 16:30:28.631  5838  5944 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-31 16:30:28.631  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 16:30:28.741  3440  6080 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-31 16:30:29.646  3440  3618 V AlarmManager: waitForAlarm result :4
,03-31 16:30:29.666  5838  5838 D BtGatt.ScanManager: awakened up at time 271080
,03-31 16:30:29.671  5838  5952 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-31 16:30:29.676  5838  5944 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-31 16:30:29.676  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 16:30:30.176  5838  6006 W bt-l2cap: L2CAP - no CCB for conn rsp, LCID: 66 RCID: 67
,03-31 16:30:30.446  5838  6006 W bt-btif : new conn_srvc id:26, app_id:255
03-31 16:30:30.446  5838  6006 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
03-31 16:30:30.446  5838  6006 W bt-btif : bta_dm_pm_ssr:2, lat:1200
,03-31 16:30:30.456 11128 11693 D BluetoothSocket: socket fd passed by stack  fds: [Ljava.io.FileDescriptor;@1ba6781a,
,03-31 16:30:30.461  5838  5955 E BluetoothRemoteDevices: setRfcommConnected true,
,03-31 16:30:30.466 11128 11693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection accepted,
,03-31 16:30:30.481 11128 11693 D BluetoothSocket: getInputStream(): myUserId = 0,
,03-31 16:30:30.486 11128 11693 D BluetoothSocket: getOutputStream(): myUserId = 0,
,03-31 16:30:30.486 11128 11693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection initialized (thread ID: 1551)
,03-31 16:30:30.486 11128 11693 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3c953f4b, channel: 6, state: LISTENING
,03-31 16:30:30.491 11128 11693 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3c953f4b, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@232c893c, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3d6fd28mSocket: android.net.LocalSocket@189c2a41 impl:android.net.LocalSocketImpl@3ea3fbe6 fd:FileDescriptor[119]
,03-31 16:30:30.491 11128 11693 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@189c2a41 impl:android.net.LocalSocketImpl@3ea3fbe6 fd:FileDescriptor[119]
,03-31 16:30:30.491 11128 11693 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-31 16:30:30.496 11128 11693 D BluetoothSocket: bindListen(): myUserId = 0
,03-31 16:30:30.496 11128 11693 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-31 16:30:30.501 11128 11693 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[122]}
,03-31 16:30:30.506 11128 11799 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 1551)
03-31 16:30:30.506 11128 11693 D BluetoothSocket: bindListen(), new LocalSocket 
03-31 16:30:30.506 11128 11693 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-31 16:30:30.506 11128 11693 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1c768527
03-31 16:30:30.506 11128 11693 D BluetoothSocket: channel: 6
03-31 16:30:30.506 11128 11693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-31 16:30:30.511  5838  6006 W bt-btif : new conn_srvc id:26, app_id:1,
03-31 16:30:30.511  5838  6006 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
03-31 16:30:30.511  5838  6006 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:1
03-31 16:30:30.511  5838  6006 W bt-btif : bta_dm_pm_ssr:2, lat:1200
,03-31 16:30:30.516  5838  9004 E BluetoothRemoteDevices: setRfcommConnected true
,03-31 16:30:30.516 11128 11700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onSocketConnected: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 1545)
,03-31 16:30:30.516 11128 11700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 1545)
,03-31 16:30:30.521 11128 11700 D BluetoothSocket: getInputStream(): myUserId = 0
,03-31 16:30:30.526 11128 11700 D BluetoothSocket: getOutputStream(): myUserId = 0
,03-31 16:30:30.526 11128 11700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesWritten: 15 bytes successfully written (thread ID: 1552)
03-31 16:30:30.526 11128 11700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Outgoing connection initialized (*handshake* thread ID: 1552)
03-31 16:30:30.526 11128 11700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1545)
,03-31 16:30:30.526 11128 11803 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 1552)
,03-31 16:30:30.681  3440  3618 V AlarmManager: waitForAlarm result :4
,03-31 16:30:30.691  5838  5838 D BtGatt.ScanManager: awakened up at time 272109
,03-31 16:30:30.701  5838  5952 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-31 16:30:30.701  5838  5944 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-31 16:30:30.701  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,03-31 16:30:30.716  5838  6006 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-31 16:30:30.716  5838  6006 D IOP_DB_BT: db_query: result 1,
03-31 16:30:30.716  5838  6006 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-31 16:30:30.716  5838  6006 D IOP_DB_BT: db_query: result 1
,03-31 16:30:30.721 11128 11799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesRead: Read 15 bytes successfully (thread ID: 1551)
03-31 16:30:30.721 11128 11799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Got valid identity from [<no peer name> F8:95:C7:87:3C:51]
03-31 16:30:30.721  5838  6006 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-31 16:30:30.721  5838  6006 D IOP_DB_BT: db_query: result 1
03-31 16:30:30.721  5838  6006 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-31 16:30:30.726  5838  6006 D IOP_DB_BT: db_query: result 1
,03-31 16:30:30.731 11128 11799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesWritten: 15 bytes successfully written (thread ID: 1551),
03-31 16:30:30.731 11128 11799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: removeThreadFromList: Removing thread with ID 1551
03-31 16:30:30.731 11128 11799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Handshake thread disposed (thread ID: 1551)
,03-31 16:30:30.731 11128 11799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onIncomingConnectionConnected: [<no peer name> F8:95:C7:87:3C:51],
03-31 16:30:30.731 11128 11128 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:95:C7:87:3C:51]
03-31 16:30:30.731 11128 11128 I io.jxcore.node.ConnectionHelper: onConnected: Incoming connection to peer [<no peer name> F8:95:C7:87:3C:51]
03-31 16:30:30.731 11128 11128 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
03-31 16:30:30.731 11128 11799 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 1551)
,03-31 16:30:30.741 11128 11128 D BluetoothSocket: getInputStream(): myUserId = 0
,03-31 16:30:30.741 11128 11128 D BluetoothSocket: getOutputStream(): myUserId = 0
,03-31 16:30:30.746 11128 11128 I io.jxcore.node.ConnectionHelper: onConnected: Incoming socket thread, for peer [<no peer name> F8:95:C7:87:3C:51], created successfully
,03-31 16:30:30.746 11128 11128 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 2
03-31 16:30:30.746 11128 11809 D io.jxcore.node.IncomingSocketThread: Entering thread (ID: 1553)
,03-31 16:30:30.746  2874  3473 D EnterpriseController: netId is 0
03-31 16:30:30.746  2874  3473 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,03-31 16:30:30.746 11128 11809 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 46988
,03-31 16:30:30.746 11128 11809 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
03-31 16:30:30.746 11128 11809 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-31 16:30:30.746 11128 11809 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
,03-31 16:30:30.751 11128 11812 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1554, name: Sender)
03-31 16:30:30.751 11128 11809 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 1553)
03-31 16:30:30.751 11128 11809 D io.jxcore.node.IncomingSocketThread: Exiting thread (ID: 1553)
,03-31 16:30:30.751 11128 11813 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1555, name: Receiver)
,03-31 16:30:30.771  5838  6006 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-31 16:30:30.771 11128 11803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesRead: Read 15 bytes successfully (thread ID: 1552)
03-31 16:30:30.771  5838  6006 D IOP_DB_BT: db_query: result 1
03-31 16:30:30.771  5838  6006 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-31 16:30:30.771  5838  6006 D IOP_DB_BT: db_query: result 1
03-31 16:30:30.771 11128 11803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Handshake succeeded with [<no peer name> F8:95:C7:87:3C:51]
03-31 16:30:30.771 11128 11803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onHandshakeSucceeded: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 1545)
03-31 16:30:30.771 11128 11803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: handleSuccessfulClientThread: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 1545)
,03-31 16:30:30.771 11128 11803 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 1552)
03-31 16:30:30.771 11128 11128 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:95:C7:87:3C:51]
03-31 16:30:30.771 11128 11128 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing connection to peer [<no peer name> F8:95:C7:87:3C:51]
03-31 16:30:30.771 11128 11128 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
,03-31 16:30:30.776 11128 11128 D BluetoothSocket: getInputStream(): myUserId = 0
,03-31 16:30:30.776 11128 11128 D BluetoothSocket: getOutputStream(): myUserId = 0
,03-31 16:30:30.776 11128 11128 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing socket thread, for peer [<no peer name> F8:95:C7:87:3C:51], created successfully
03-31 16:30:30.776 11128 11128 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 3
,03-31 16:30:30.781 11128 11814 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1556)
,03-31 16:30:30.781 11128 11814 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 53211
,03-31 16:30:30.781 11128 11814 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
03-31 16:30:30.781 11128 11814 I io.jxcore.node.ConnectionHelper: onListeningForIncomingConnections: Outgoing connection is using port 53211 (peer ID: F8:95:C7:87:3C:51)
03-31 16:30:30.781 11128 11814 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "F8:95:C7:87:3C:51" removed
,03-31 16:30:30.786 11128 11200 I jxcore-log: INFO testThaliMobileNative: 
03-31 16:30:30.786 11128 11200 I jxcore-log: 
,03-31 16:30:30.786 11128 11200 I jxcore-log: ok 165 Must have listeningPort
03-31 16:30:30.786 11128 11200 I jxcore-log: 
,03-31 16:30:30.786 11128 11200 I jxcore-log: ok 166 listeningPort must be a number
03-31 16:30:30.786 11128 11200 I jxcore-log: 
,03-31 16:30:30.786 11128 11200 I jxcore-log: ok 167 Connection must have clientPort
03-31 16:30:30.786 11128 11200 I jxcore-log: 
,03-31 16:30:30.786 11128 11200 I jxcore-log: ok 168 clientPort must be a number
03-31 16:30:30.786 11128 11200 I jxcore-log: 
,03-31 16:30:30.791 11128 11200 I jxcore-log: ok 169 Connection must have serverPort
03-31 16:30:30.791 11128 11200 I jxcore-log: 
,03-31 16:30:30.791 11128 11200 I jxcore-log: ok 170 serverPort must be a number
03-31 16:30:30.791 11128 11200 I jxcore-log: 
,03-31 16:30:30.791 11128 11200 I jxcore-log: ok 171 forward connection must have clientPort == 0
03-31 16:30:30.791 11128 11200 I jxcore-log: 
,03-31 16:30:30.791 11128 11200 I jxcore-log: ok 172 forward connection must have serverPort == 0
03-31 16:30:30.791 11128 11200 I jxcore-log: 
,03-31 16:30:30.801 11128 11200 I jxcore-log: # teardown
03-31 16:30:30.801 11128 11200 I jxcore-log: 
,03-31 16:30:31.091 11128 11781 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 1549, thread name: Sender)
03-31 16:30:31.091 11128 11781 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Input stream got -1 on read
03-31 16:30:31.091 11128 11781 W io.jxcore.node.ConnectionHelper: onDisconnected: Incoming connection, peer [<no peer name> F8:CF:C5:D9:E5:61] disconnected: Input stream got -1 on read
03-31 16:30:31.091 11128 11781 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1547
03-31 16:30:31.091 11128 11781 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 1547)
03-31 16:30:31.091 11128 11781 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@14a3f072, channel: 6, state: CONNECTED
03-31 16:30:31.091 11128 11781 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@14a3f072, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@273c4cc3, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@35e24940mSocket: android.net.LocalSocket@b2ae079 impl:android.net.LocalSocketImpl@283ca1be fd:FileDescriptor[92]
,03-31 16:30:31.096 11128 11812 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 1554, thread name: Sender),
03-31 16:30:31.101 11128 11812 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Input stream got -1 on read
,03-31 16:30:31.101 11128 11812 W io.jxcore.node.ConnectionHelper: onDisconnected: Incoming connection, peer [<no peer name> F8:95:C7:87:3C:51] disconnected: Input stream got -1 on read
,03-31 16:30:31.101 11128 11781 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@b2ae079 impl:android.net.LocalSocketImpl@283ca1be fd:FileDescriptor[92],
03-31 16:30:31.106 11128 11782 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 1550, thread name: Receiver): bt socket closed, read return: -1
,03-31 16:30:31.106 11128 11782 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1550, name: Receiver)
,03-31 16:30:31.106 11128 11781 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@14a3f072, channel: 6, state: CLOSED,
03-31 16:30:31.106 11128 11781 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@14a3f072, channel: 6, state: CLOSED
,03-31 16:30:31.106 11128 11781 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-31 16:30:31.106 11128 11781 D io.jxcore.node.IncomingSocketThread: close: Stopping receiving thread...
,03-31 16:30:31.106 11128 11781 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 1550
03-31 16:30:31.106 11128 11781 D io.jxcore.node.IncomingSocketThread: close: Stopping sending thread...
03-31 16:30:31.106 11128 11781 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 1549
,03-31 16:30:31.106 11128 11781 D io.jxcore.node.IncomingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 1547)
,03-31 16:30:31.111 11128 11781 I io.jxcore.node.IncomingSocketThread: close: Complete (thread ID: 1547)
,03-31 16:30:31.111 11128 11781 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
03-31 16:30:31.111 11128 11812 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1553
03-31 16:30:31.116 11128 11812 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 1553)
03-31 16:30:31.116 11128 11812 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@320cf21f, channel: 6, state: CONNECTED
03-31 16:30:31.116 11128 11812 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@320cf21f, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2442b96c, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1a700b35mSocket: android.net.LocalSocket@51d1bca impl:android.net.LocalSocketImpl@1418913b fd:FileDescriptor[121]
03-31 16:30:31.116 11128 11812 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@51d1bca impl:android.net.LocalSocketImpl@1418913b fd:FileDescriptor[121]
,03-31 16:30:31.116 11128 11812 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@320cf21f, channel: 6, state: CLOSED
03-31 16:30:31.116 11128 11812 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@320cf21f, channel: 6, state: CLOSED
03-31 16:30:31.116 11128 11812 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-31 16:30:31.116 11128 11812 D io.jxcore.node.IncomingSocketThread: close: Stopping receiving thread...
03-31 16:30:31.116 11128 11812 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 1555
03-31 16:30:31.116 11128 11812 D io.jxcore.node.IncomingSocketThread: close: Stopping sending thread...
03-31 16:30:31.116 11128 11812 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 1554
03-31 16:30:31.116 11128 11812 D io.jxcore.node.IncomingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 1553)
,03-31 16:30:31.116 11128 11812 I io.jxcore.node.IncomingSocketThread: close: Complete (thread ID: 1553)
03-31 16:30:31.116 11128 11812 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
03-31 16:30:31.116 11128 11813 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 1555, thread name: Receiver): bt socket closed, read return: -1
03-31 16:30:31.116 11128 11813 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1555, name: Receiver)
03-31 16:30:31.121 11128 11812 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1554, name: Sender)
03-31 16:30:31.121 11128 11781 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1549, name: Sender)
,03-31 16:30:31.126 11128 11200 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements,
03-31 16:30:31.126 11128 11200 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
03-31 16:30:31.126  5838  6114 W bt-btif : invalid rfc slot id: 10
03-31 16:30:31.126  5838  6006 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-31 16:30:31.126  5838  6006 D IOP_DB_BT: db_query: result 1
03-31 16:30:31.126  5838  6006 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-31 16:30:31.126 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-31 16:30:31.126 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-31 16:30:31.126  5838  6006 D IOP_DB_BT: db_query: result 1
,03-31 16:30:31.131  5838  9004 D BtGatt.GattService: stopScan() - queue size =1
,03-31 16:30:31.131  5838  5952 D BtGatt.ScanManager: filter size is 1
,03-31 16:30:31.131  5838  5952 D BtGatt.ScanManager: delete FilterIndex - 14
03-31 16:30:31.131  5838  5848 D BtGatt.GattService: unregisterClient() - clientIf=6
03-31 16:30:31.131 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 16:30:31.131 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 16:30:31.131 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-31 16:30:31.131 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
,03-31 16:30:31.131 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-31 16:30:31.131 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 16:30:31.131 11128 11128 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 16:30:31.131 11128 11128 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-31 16:30:31.131 11128 11128 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-31 16:30:31.136 11128 11200 I jxcore-log: INFO thaliMobileNativeWrapper: incomingConnectionToPortNumberFailed: %s
03-31 16:30:31.136 11128 11200 I jxcore-log: 
,03-31 16:30:31.136 11128 11200 I jxcore-log: INFO thaliMobileNativeWrapper: got incomingConnectionToPortNumberFailed while not in start
03-31 16:30:31.136 11128 11200 I jxcore-log: 
,03-31 16:30:31.141 11128 11200 I jxcore-log: ok 173 Should be able to call stopListeningForAdvertisments in teardown
03-31 16:30:31.141 11128 11200 I jxcore-log: 
,03-31 16:30:31.141 11128 11200 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 16:30:31.141 11128 11200 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> F8:95:C7:87:3C:51]
03-31 16:30:31.141 11128 11200 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1556)
03-31 16:30:31.141 11128 11200 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 1556)
03-31 16:30:31.141 11128 11200 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@19580058, channel: 7, state: CONNECTED
03-31 16:30:31.141 11128 11200 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@19580058, channel: 7, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@36a325b1, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@10d92a96mSocket: android.net.LocalSocket@1d750617 impl:android.net.LocalSocketImpl@3f78ca04 fd:FileDescriptor[118]
,03-31 16:30:31.141 11128 11200 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1d750617 impl:android.net.LocalSocketImpl@3f78ca04 fd:FileDescriptor[118]
03-31 16:30:31.141 11128 11200 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@19580058, channel: 7, state: CLOSED
03-31 16:30:31.141 11128 11200 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@19580058, channel: 7, state: CLOSED
03-31 16:30:31.141 11128 11200 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-31 16:30:31.141 11128 11200 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Nothing to close (thread ID: 1556)
03-31 16:30:31.141 11128 11200 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1556)
03-31 16:30:31.141 11128 11200 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,03-31 16:30:31.141 11128 11200 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-31 16:30:31.141 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-31 16:30:31.141 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-31 16:30:31.141 11128 11200 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@17136bed, channel: 6, state: LISTENING
03-31 16:30:31.141 11128 11200 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@17136bed, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1c768527, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@24755a22mSocket: android.net.LocalSocket@1fb9ecb3 impl:android.net.LocalSocketImpl@2dba8270 fd:FileDescriptor[122]
03-31 16:30:31.141 11128 11814 D io.jxcore.node.OutgoingSocketThread: Exiting thread (ID: 1556)
03-31 16:30:31.141 11128 11200 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1fb9ecb3 impl:android.net.LocalSocketImpl@2dba8270 fd:FileDescriptor[122]
,03-31 16:30:31.141 11128 11200 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-31 16:30:31.141 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-31 16:30:31.141 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-31 16:30:31.141 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-31 16:30:31.141 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-31 16:30:31.141 11128 11693 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-31 16:30:31.141 11128 11693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-31 16:30:31.141 11128 11693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-31 16:30:31.141 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-31 16:30:31.141 11128 11200 D BluetoothLeScanner: could not find callback wrapper
03-31 16:30:31.141 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-31 16:30:31.141 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-31 16:30:31.146  5838  5944 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-31 16:30:31.146  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 16:30:31.146  5838  5952 D BtGatt.ScanManager: stopping BLe Batch
03-31 16:30:31.146  5838  5951 D BtGatt.AdvertiseManager: message : 1
03-31 16:30:31.146  5838  5951 D BtGatt.AdvertiseManager: stop advertise for client 7
03-31 16:30:31.146  5838  5951 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-31 16:30:31.146  5838  5944 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,03-31 16:30:31.146  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 16:30:31.146  5838  5952 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-31 16:30:31.146  5838  5951 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,03-31 16:30:31.146  5838  5944 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-31 16:30:31.146  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 16:30:31.146  5838  5944 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-31 16:30:31.146  5838  5944 D BtGatt.GattService: Client app is not null!
,03-31 16:30:31.151  5838  5848 D BtGatt.GattService: unregisterClient() - clientIf=7
,03-31 16:30:31.151 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 16:30:31.151 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-31 16:30:31.151 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-31 16:30:31.151 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-31 16:30:31.151 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,03-31 16:30:31.151 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 16:30:31.151 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 16:30:31.151 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-31 16:30:31.151 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-31 16:30:31.151 11128 11200 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-31 16:30:31.151 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 16:30:31.151 11128 11128 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 16:30:31.151 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 16:30:31.151 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-31 16:30:31.156 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-31 16:30:31.156 11128 11200 I jxcore-log: 
,03-31 16:30:31.156 11128 11128 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-31 16:30:31.161 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
,03-31 16:30:31.161 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
,03-31 16:30:31.161 11128 11128 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-31 16:30:31.161 11128 11128 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-31 16:30:31.161 11128 11128 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 16:30:31.166 11128 11128 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-31 16:30:31.166 11128 11128 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 16:30:31.166 11128 11128 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 16:30:31.166 11128 11128 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 16:30:31.166 11128 11128 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-31 16:30:31.166 11128 11200 I jxcore-log: ok 174 Should be able to call stopAdvertisingAndListening in teardown
03-31 16:30:31.166 11128 11200 I jxcore-log: 
,03-31 16:30:31.171 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 16:30:31.171 11128 11200 I jxcore-log: 
,03-31 16:30:31.171 11128 11200 I jxcore-log: # setup
03-31 16:30:31.171 11128 11200 I jxcore-log: 
,03-31 16:30:31.176 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 16:30:31.176 11128 11200 I jxcore-log: 
,03-31 16:30:31.316  5838  6006 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0xf):jv handle:0x0 not FOUND
03-31 16:30:31.316  5838  6006 E bt-btif : bta_jv_port_mgmt_sr_cback, p_cb:0x0, p_cb->p_cback0x0
,03-31 16:30:31.376 11128 11200 I jxcore-log: # 41. Can shift large amounts of data
03-31 16:30:31.376 11128 11200 I jxcore-log: 
,03-31 16:30:31.621 11128 11200 I io.jxcore.node.ConnectionHelper: start: Port number: 58150, start advertisements: true
,03-31 16:30:31.626 11128 11200 I io.jxcore.node.ConnectionHelper: restoreDefaultBleDiscoverySettings: Powering the BLE discovery back up
03-31 16:30:31.626 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 0 -> 2
,03-31 16:30:31.626 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-31 16:30:31.626 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 16:30:31.626 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-31 16:30:31.626 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-31 16:30:31.626 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-31 16:30:31.626 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-31 16:30:31.631 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 1, timeout: 0, is connectable: false
,03-31 16:30:31.631 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-31 16:30:31.631 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 1 -> 3
,03-31 16:30:31.631 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-31 16:30:31.631 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 16:30:31.631 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-31 16:30:31.631 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-31 16:30:31.631 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-31 16:30:31.631 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-31 16:30:31.631 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-31 16:30:31.636 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
,03-31 16:30:31.636 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 0 -> 2
,03-31 16:30:31.641 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-31 16:30:31.641 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 16:30:31.641 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-31 16:30:31.641 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-31 16:30:31.641 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-31 16:30:31.641 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-31 16:30:31.641 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-31 16:30:31.641 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-31 16:30:31.641 11128 11200 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-31 16:30:31.646 11128 11200 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,03-31 16:30:31.646 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-31 16:30:31.651 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-31 16:30:31.651 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 16:30:31.651 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 16:30:31.651 11128 11200 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 16:30:31.651  5838  5848 D BtGatt.GattService: registerClient() - UUID=7e9c5079-2a57-4ffb-94f7-9728bcfaf72a
,03-31 16:30:31.691  5838  5944 D BtGatt.GattService: onClientRegistered() - UUID=7e9c5079-2a57-4ffb-94f7-9728bcfaf72a, clientIf=6
,03-31 16:30:31.691 11128 11777 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-31 16:30:31.696  5838  5955 D BtGatt.GattService: start scan with filters
,03-31 16:30:31.706  5838  5955 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 77
,03-31 16:30:31.706 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 16:30:31.706 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 16:30:31.706 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-31 16:30:31.706 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 16:30:31.706  5838  5952 D BtGatt.ScanManager: handling starting scan
03-31 16:30:31.706 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 16:30:31.706  5838  5952 D BtGatt.ScanManager: isFilteringSupported
03-31 16:30:31.706  5838  5952 D BluetoothAdapter: setting StandAloneBleMode
03-31 16:30:31.706 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 16:30:31.706 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-31 16:30:31.706 11128 11128 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 16:30:31.706 11128 11200 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-31 16:30:31.706 11128 11200 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 16:30:31.706 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 16:30:31.706 11128 11200 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-31 16:30:31.706  5838  5944 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1,
03-31 16:30:31.706  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 16:30:31.706  5838  5952 D BtGatt.ScanManager: allow scan with filters
03-31 16:30:31.706  5838  5952 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,03-31 16:30:31.706  5838  5952 D BtGatt.ScanManager: set filter index= 15 for clientIf= 6
03-31 16:30:31.711  5838  5944 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-31 16:30:31.711  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 16:30:31.711  5838  5952 D BtGatt.ScanManager: Starting BLE batch scan
03-31 16:30:31.711  5838  5955 D BtGatt.GattService: registerClient() - UUID=74cde3cb-5948-41c2-a146-8eeb5381d495
03-31 16:30:31.711  5838  5952 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-31 16:30:31.711  5838  5944 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,03-31 16:30:31.711  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 16:30:31.716  5838  5944 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,03-31 16:30:31.716  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 16:30:31.751  5838  5944 D BtGatt.GattService: onClientRegistered() - UUID=74cde3cb-5948-41c2-a146-8eeb5381d495, clientIf=7
03-31 16:30:31.751 11128 11144 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-31 16:30:31.776  5838  9004 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 61,
,03-31 16:30:31.776  5838  5951 D BtGatt.AdvertiseManager: message : 0,
,03-31 16:30:31.776  5838  5951 D BtGatt.AdvertiseManager: number of adv instance running0,
03-31 16:30:31.776  5838  5951 D BtGatt.AdvertiseManager: size of list is =0
03-31 16:30:31.781  5838  5951 D BtGatt.AdvertiseManager: starting advertising
,03-31 16:30:31.781  5838  5951 D BtGatt.AdvertiseManager: isStandardAdvfalse
03-31 16:30:31.781  5838  5944 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0,
,03-31 16:30:31.791  5838  5951 D BtGatt.AdvertiseManager: starting multi advertising,
,03-31 16:30:31.791  5838  5944 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0,
03-31 16:30:31.791  5838  5951 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-31 16:30:31.791  5838  5951 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,03-31 16:30:31.791 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-31 16:30:31.791 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-31 16:30:31.796 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 16:30:31.796 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-31 16:30:31.796 11128 11200 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-31 16:30:31.796 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 16:30:31.801 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-31 16:30:31.801 11128 11200 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-31 16:30:31.801 11128 11200 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,03-31 16:30:31.801 11128 11200 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-31 16:30:31.801 11128 11128 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-31 16:30:31.801 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 16:30:31.801 11128 11128 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING,
,03-31 16:30:31.801 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-31 16:30:31.801 11128 11128 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
,03-31 16:30:31.801 11128 11128 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-31 16:30:31.801 11128 11128 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 16:30:31.801 11128 11128 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 16:30:31.801 11128 11128 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,03-31 16:30:31.801 11128 11128 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 16:30:31.801 11128 11128 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-31 16:30:31.801 11128 11128 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true,
,03-31 16:30:31.801 11128 11200 I io.jxcore.node.ConnectionHelper: start: OK,
03-31 16:30:31.806  5838  6006 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0x12):jv handle:0x0 not FOUND
03-31 16:30:31.806  5838  6006 E bt-btif : bta_jv_port_mgmt_sr_cback, p_cb:0x0, p_cb->p_cback0x0,
03-31 16:30:31.811 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false},
03-31 16:30:31.811 11128 11200 I jxcore-log: 
03-31 16:30:31.816 11128 11839 D BluetoothSocket: bindListen(): myUserId = 0
03-31 16:30:31.816 11128 11839 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback,
,03-31 16:30:31.821 11128 11839 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[93]}
03-31 16:30:31.821 11128 11839 D BluetoothSocket: bindListen(), new LocalSocket 
03-31 16:30:31.821 11128 11839 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,03-31 16:30:31.821 11128 11839 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@151d559c,
03-31 16:30:31.821 11128 11839 D BluetoothSocket: channel: 6
03-31 16:30:31.821 11128 11839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-31 16:30:31.826 11128 11200 I jxcore-log: ok 175 Can call startUpdateAdvertisingAndListening without error,
03-31 16:30:31.826 11128 11200 I jxcore-log: 
,03-31 16:30:31.831 11128 11200 I io.jxcore.node.ConnectionHelper: start: Port number: 58150, start advertisements: false,
,03-31 16:30:31.831 11128 11200 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 16:30:31.831 11128 11200 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
,03-31 16:30:31.831 11128 11200 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 16:30:31.831 11128 11200 I io.jxcore.node.ConnectionHelper: start: OK
,03-31 16:30:31.836 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 16:30:31.836 11128 11200 I jxcore-log: 
,03-31 16:30:31.836 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-31 16:30:31.836 11128 11200 I jxcore-log: 
,03-31 16:30:31.841 11128 11200 I jxcore-log: ok 176 Can call startListeningForAdvertisements without error
03-31 16:30:31.841 11128 11200 I jxcore-log: 
,03-31 16:30:32.716  3440  3618 V AlarmManager: waitForAlarm result :4
,03-31 16:30:32.736  5838  5838 D BtGatt.ScanManager: awakened up at time 274151
,03-31 16:30:32.741  5838  5952 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-31 16:30:32.751  5838  5944 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=3
03-31 16:30:32.751  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 16:30:32.751  5838  5944 D BtGatt.GattService: current time is 274168988615
03-31 16:30:32.751  5838  5944 D BtGatt.GattService: Batch record : [19, 49, 50, 70, -28, 80, 1, -128, -54, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0, 89, -14, 26, -103, 28, 91, 1, -128, -73, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -28, -44, -106, -22, -38, 116, 0, -128, -92, 14, 0, 23, 2, 1, 6, 3, 2, 5, 24, 15, 9, 90, 101, 70, 105, 116, 50, 32, 35, 54, 54, 48, 55, 53, 0, 0],
03-31 16:30:32.751  5838  5944 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
,03-31 16:30:32.751  5838  5944 D ScanRecord: parseFromBytes
03-31 16:30:32.751  5838  5944 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-31 16:30:32.751  5838  5944 D ScanRecord: parseFromBytes
,03-31 16:30:32.756  5838  5944 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 5, 24, 15, 9, 90, 101, 70, 105, 116, 50, 32, 35, 54, 54, 48, 55, 53, 0]
03-31 16:30:32.756  5838  5944 D ScanRecord: parseFromBytes
,03-31 16:30:32.756  5838  5944 D BtGatt.GattService: result: ScanResult{mDevice=74:DA:EA:96:D4:E4, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[00001805-0000-1000-8000-00805f9b34fb], mManufacturerSpecificData={}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=ZeFit2 #66075��], mRssi=-92, mTimestampNanos=273469215032},
03-31 16:30:32.756  5838  5944 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null],
03-31 16:30:32.756  5838  5944 D BtGatt.GattService: result: ScanResult{mDevice=50:E4:46:32:31:13, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-54, mTimestampNanos=274119215032}
03-31 16:30:32.756  5838  5944 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null],
03-31 16:30:32.756  5838  5944 D BtGatt.GattService: result: ScanResult{mDevice=5B:1C:99:1A:F2:59, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-73, mTimestampNanos=274169215032}
03-31 16:30:32.756  5838  5944 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-31 16:30:32.756 11128 11777 D ScanRecord: parseFromBytes
,03-31 16:30:32.756 11128 11777 D ScanRecord: parseFromBytes
03-31 16:30:32.756 11128 11777 D ScanRecord: parseFromBytes
03-31 16:30:32.756 11128 11128 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:CF:C5:D9:E5:61], added - the peer count is 1
03-31 16:30:32.756 11128 11128 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 2
,03-31 16:30:32.756 11128 11128 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:CF:C5:D9:E5:61], Bluetooth address: F8:CF:C5:D9:E5:61, device name: , device address: 
03-31 16:30:32.756 11128 11128 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
,03-31 16:30:32.781 11128 11200 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID F8:CF:C5:D9:E5:61,
03-31 16:30:32.781 11128 11200 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> F8:CF:C5:D9:E5:61]
,03-31 16:30:32.781 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to Nexus 6 in address F8:CF:C5:D9:E5:61,
03-31 16:30:32.781 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
03-31 16:30:32.781 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,03-31 16:30:32.781 11128 11200 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: Nexus 6 F8:CF:C5:D9:E5:61
03-31 16:30:32.781 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to Nexus 6 in address F8:CF:C5:D9:E5:61
03-31 16:30:32.781 11128 11200 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: F8:CF:C5:D9:E5:61)
,03-31 16:30:32.786 11128 11846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address F8:CF:C5:D9:E5:61 (thread ID: 1558)
,03-31 16:30:32.791 11128 11846 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
,03-31 16:30:32.796 11128 11846 D BluetoothSocket: connect(): myUserId = 0
03-31 16:30:32.796 11128 11846 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-31 16:30:32.796  5838  5850 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-31 16:30:32.801 11128 11846 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[118]}
,03-31 16:30:33.206  5838  6006 W bt-sdp  : process_service_search_attr_rsp
,03-31 16:30:33.776  3440  3618 V AlarmManager: waitForAlarm result :4
,03-31 16:30:33.791  5838  5838 D BtGatt.ScanManager: awakened up at time 275206
,03-31 16:30:33.796  5838  5952 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-31 16:30:33.801  5838  5944 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
03-31 16:30:33.801  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 16:30:33.801  5838  5944 D BtGatt.GattService: current time is 275216414574
03-31 16:30:33.801  5838  5944 D BtGatt.GattService: Batch record : [19, 49, 50, 70, -28, 80, 1, -128, -51, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0, 89, -14, 26, -103, 28, 91, 1, -128, -66, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-31 16:30:33.801  5838  5944 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-31 16:30:33.801  5838  5944 D ScanRecord: parseFromBytes
03-31 16:30:33.801  5838  5944 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-31 16:30:33.801  5838  5944 D ScanRecord: parseFromBytes
03-31 16:30:33.801  5838  5944 D BtGatt.GattService: result: ScanResult{mDevice=5B:1C:99:1A:F2:59, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-66, mTimestampNanos=275116601490}
03-31 16:30:33.801  5838  5944 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-31 16:30:33.801  5838  5944 D BtGatt.GattService: result: ScanResult{mDevice=50:E4:46:32:31:13, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-51, mTimestampNanos=275166601490}
03-31 16:30:33.801  5838  5944 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-31 16:30:33.801 11128 11144 D ScanRecord: parseFromBytes
03-31 16:30:33.801 11128 11144 D ScanRecord: parseFromBytes
03-31 16:30:33.801 11128 11128 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
03-31 16:30:33.801 11128 11128 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:CF:C5:D9:E5:61] updated - the peer count is 2
,03-31 16:30:33.826  5838  6006 W bt-btif : new conn_srvc id:26, app_id:1
,03-31 16:30:33.826  5838  5955 E BluetoothRemoteDevices: setRfcommConnected true
,03-31 16:30:33.836 11128 11846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onSocketConnected: [<no peer name> F8:CF:C5:D9:E5:61] (thread ID: 1558)
03-31 16:30:33.836 11128 11846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 1558)
,03-31 16:30:33.841 11128 11846 D BluetoothSocket: getInputStream(): myUserId = 0
,03-31 16:30:33.841 11128 11846 D BluetoothSocket: getOutputStream(): myUserId = 0
,03-31 16:30:33.846 11128 11846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesWritten: 15 bytes successfully written (thread ID: 1559)
03-31 16:30:33.846 11128 11856 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 1559)
03-31 16:30:33.846 11128 11846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Outgoing connection initialized (*handshake* thread ID: 1559)
03-31 16:30:33.846 11128 11846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1558)
,03-31 16:30:33.966  5838  6006 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 16:30:33.966  5838  6006 D IOP_DB_BT: db_query: result 1
03-31 16:30:33.966  5838  6006 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 16:30:33.971  5838  6006 D IOP_DB_BT: db_query: result 1
,03-31 16:30:34.106  5838  6006 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 16:30:34.106  5838  6006 D IOP_DB_BT: db_query: result 1
03-31 16:30:34.106  5838  6006 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 16:30:34.106  5838  6006 D IOP_DB_BT: db_query: result 1
03-31 16:30:34.111 11128 11856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesRead: Read 15 bytes successfully (thread ID: 1559)
03-31 16:30:34.111 11128 11856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Handshake succeeded with [<no peer name> F8:CF:C5:D9:E5:61]
03-31 16:30:34.111 11128 11856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onHandshakeSucceeded: [<no peer name> F8:CF:C5:D9:E5:61] (thread ID: 1558)
03-31 16:30:34.111 11128 11856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: handleSuccessfulClientThread: [<no peer name> F8:CF:C5:D9:E5:61] (thread ID: 1558)
,03-31 16:30:34.121 11128 11128 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:CF:C5:D9:E5:61],
,03-31 16:30:34.121 11128 11128 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing connection to peer [<no peer name> F8:CF:C5:D9:E5:61],
,03-31 16:30:34.121 11128 11128 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:CF:C5:D9:E5:61] updated - the peer count is 2,
,03-31 16:30:34.136 11128 11856 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 1559),
,03-31 16:30:34.141 11128 11128 D BluetoothSocket: getInputStream(): myUserId = 0,
,03-31 16:30:34.146 11128 11128 D BluetoothSocket: getOutputStream(): myUserId = 0,
03-31 16:30:34.146 11128 11128 I io.jxcore.node.ConnectionHelper: lowerBleDiscoveryPowerAndStartResetTimer: Lowering the power settings
,03-31 16:30:34.146 11128 11128 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 2 -> 0
,03-31 16:30:34.156 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:,
03-31 16:30:34.156 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 16:30:34.156 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-31 16:30:34.156 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-31 16:30:34.156 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-31 16:30:34.156 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-31 16:30:34.161  5838  5951 D BtGatt.AdvertiseManager: message : 1,
03-31 16:30:34.161  5838  5951 D BtGatt.AdvertiseManager: stop advertise for client 7
03-31 16:30:34.161  5838  5951 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-31 16:30:34.166  5838  5951 D BtGatt.AdvertiseManager: logClientsSet() - status: -1,
,03-31 16:30:34.166  5838  5944 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0,
,03-31 16:30:34.166  5838  5944 D BtGatt.GattService: Client app is not null!,
,03-31 16:30:34.166  5838  5850 D BtGatt.GattService: unregisterClient() - clientIf=7
03-31 16:30:34.171 11128 11128 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 16:30:34.171 11128 11128 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-31 16:30:34.171 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 3, timeout: 0, is connectable: false
03-31 16:30:34.171 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 16:30:34.171 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-31 16:30:34.171 11128 11128 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-31 16:30:34.176 11128 11128 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 16:30:34.176 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-31 16:30:34.176 11128 11128 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-31 16:30:34.181  5838  5850 D BtGatt.GattService: registerClient() - UUID=b09d0e24-fe2b-4ebf-ab5c-667fa86e9e48
,03-31 16:30:34.221  5838  5944 D BtGatt.GattService: onClientRegistered() - UUID=b09d0e24-fe2b-4ebf-ab5c-667fa86e9e48, clientIf=7
,03-31 16:30:34.221 11128 11777 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-31 16:30:34.236  5838  5848 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 62
03-31 16:30:34.236  5838  5951 D BtGatt.AdvertiseManager: message : 0
,03-31 16:30:34.236  5838  5951 D BtGatt.AdvertiseManager: number of adv instance running0
03-31 16:30:34.236  5838  5951 D BtGatt.AdvertiseManager: size of list is =0
,03-31 16:30:34.236  5838  5951 D BtGatt.AdvertiseManager: starting advertising
,03-31 16:30:34.236  5838  5951 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-31 16:30:34.241  5838  5944 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-31 16:30:34.241  5838  5951 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 16:30:34.241  5838  5944 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-31 16:30:34.241  5838  5951 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-31 16:30:34.241  5838  5951 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 0, TxPowerLevel: 3, isConnectable: false, Timeout: 0
03-31 16:30:34.246 11128 11128 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-31 16:30:34.246  5838  9004 D BtGatt.GattService: stopScan() - queue size =1
,03-31 16:30:34.246  5838  5952 D BtGatt.ScanManager: filter size is 1
03-31 16:30:34.246  5838  5952 D BtGatt.ScanManager: delete FilterIndex - 15
03-31 16:30:34.246  5838  5850 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-31 16:30:34.251  5838  5944 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-31 16:30:34.251  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 16:30:34.251  5838  5952 D BtGatt.ScanManager: stopping BLe Batch
,03-31 16:30:34.251 11128 11128 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 16:30:34.251 11128 11128 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 16:30:34.251 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 16:30:34.251 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 16:30:34.251 11128 11128 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 16:30:34.251 11128 11128 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 16:30:34.251  5838  5944 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,03-31 16:30:34.251  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 16:30:34.251  5838  5952 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-31 16:30:34.256  5838  5944 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=5
03-31 16:30:34.256  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 16:30:34.256  5838  5944 D BtGatt.GattService: current time is 275673217740
03-31 16:30:34.256  5838  5944 D BtGatt.GattService: Batch record : [89, -14, 26, -103, 28, 91, 1, -128, -66, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, 19, 49, 50, 70, -28, 80, 1, -128, -51, 6, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0, -28, -44, -106, -22, -38, 116, 0, -128, -93, 4, 0, 23, 2, 1, 6, 3, 2, 5, 24, 15, 9, 90, 101, 70, 105, 116, 50, 32, 35, 54, 54, 48, 55, 53, 0, 16, 15, 9, 90, 101, 70, 105, 116, 50, 32, 35, 54, 54, 48, 55, 53, 0, -51, -90, 113, -79, 95, 79, 1, -128, -51, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0, 42, -24, -35, 122, 44, 85, 1, -128, -64, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0]
03-31 16:30:34.256  5838  5944 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-31 16:30:34.256  5838  5850 D BtGatt.GattService: registerClient() - UUID=2855af52-910d-4d98-a567-e4889e68d943
03-31 16:30:34.256  5838  5944 D ScanRecord: parseFromBytes
,03-31 16:30:34.256  5838  5944 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-31 16:30:34.256  5838  5944 D ScanRecord: parseFromBytes
03-31 16:30:34.256  5838  5944 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 5, 24, 15, 9, 90, 101, 70, 105, 116, 50, 32, 35, 54, 54, 48, 55, 53, 0, 15, 9, 90, 101, 70, 105, 116, 50, 32, 35, 54, 54, 48, 55, 53, 0]
03-31 16:30:34.256  5838  5944 D ScanRecord: parseFromBytes
03-31 16:30:34.256  5838  5944 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
,03-31 16:30:34.256  5838  5944 D ScanRecord: parseFromBytes
03-31 16:30:34.261  5838  5944 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-31 16:30:34.261  5838  5944 D ScanRecord: parseFromBytes
,03-31 16:30:34.296  5838  5944 D BtGatt.GattService: onClientRegistered() - UUID=2855af52-910d-4d98-a567-e4889e68d943, clientIf=6
03-31 16:30:34.301 11128 11138 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-31 16:30:34.301  5838  6006 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-31 16:30:34.301  5838  6006 D IOP_DB_BT: db_query: result 1
03-31 16:30:34.301  5838  6006 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-31 16:30:34.301  5838  6006 D IOP_DB_BT: db_query: result 1
03-31 16:30:34.301  5838  5848 D BtGatt.GattService: start scan with filters
,03-31 16:30:34.321  5838  5848 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 78
,03-31 16:30:34.321  5838  5952 D BtGatt.ScanManager: handling starting scan
03-31 16:30:34.321  5838  5952 D BtGatt.ScanManager: isFilteringSupported
03-31 16:30:34.321  5838  5952 D BluetoothAdapter: setting StandAloneBleMode
,03-31 16:30:34.326  5838  5944 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-31 16:30:34.326  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 16:30:34.331  5838  5952 D BtGatt.ScanManager: allow scan with filters
03-31 16:30:34.331  5838  5952 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-31 16:30:34.331  5838  5952 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
03-31 16:30:34.331  5838  5944 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-31 16:30:34.331  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 16:30:34.331  5838  5952 D BtGatt.ScanManager: Starting BLE batch scan
03-31 16:30:34.331  5838  5952 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-31 16:30:34.336  5838  5944 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-31 16:30:34.336  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 16:30:34.336  5838  5944 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-31 16:30:34.336  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 16:30:34.341 11128 11128 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
03-31 16:30:34.341 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-31 16:30:34.341 11128 11128 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 3 -> 1
,03-31 16:30:34.341 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-31 16:30:34.341 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 16:30:34.341 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0,
,03-31 16:30:34.341 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1,
03-31 16:30:34.341 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-31 16:30:34.341 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-31 16:30:34.346  5838  5951 D BtGatt.AdvertiseManager: message : 1
03-31 16:30:34.346  5838  5951 D BtGatt.AdvertiseManager: stop advertise for client 7
,03-31 16:30:34.346  5838  5951 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7,
03-31 16:30:34.346  5838  5951 D BtGatt.AdvertiseManager: logClientsSet() - status: -1,
,03-31 16:30:34.346  5838  5944 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0,
03-31 16:30:34.346  5838  5944 D BtGatt.GattService: Client app is not null!
03-31 16:30:34.351  5838  5850 D BtGatt.GattService: unregisterClient() - clientIf=7,
,03-31 16:30:34.351 11128 11128 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 16:30:34.351 11128 11128 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
,03-31 16:30:34.351 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false,
03-31 16:30:34.351 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...,
03-31 16:30:34.351 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-31 16:30:34.351 11128 11128 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
,03-31 16:30:34.351 11128 11128 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 16:30:34.351 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 16:30:34.351 11128 11128 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-31 16:30:34.356  5838  5955 D BtGatt.GattService: registerClient() - UUID=95ed03dd-3c53-44be-a1a4-9b7a4039a821
,03-31 16:30:34.396  5838  5944 D BtGatt.GattService: onClientRegistered() - UUID=95ed03dd-3c53-44be-a1a4-9b7a4039a821, clientIf=7
03-31 16:30:34.396 11128 11144 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-31 16:30:34.411  5838  9004 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 63
,03-31 16:30:34.411  5838  5951 D BtGatt.AdvertiseManager: message : 0
03-31 16:30:34.411  5838  5951 D BtGatt.AdvertiseManager: number of adv instance running0
03-31 16:30:34.411  5838  5951 D BtGatt.AdvertiseManager: size of list is =0
,03-31 16:30:34.411  5838  5951 D BtGatt.AdvertiseManager: starting advertising
03-31 16:30:34.411  5838  5951 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-31 16:30:34.416  5838  5944 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-31 16:30:34.416  5838  5951 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 16:30:34.416  5838  5944 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
03-31 16:30:34.416  5838  5951 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-31 16:30:34.416  5838  5951 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 0, TxPowerLevel: 1, isConnectable: false, Timeout: 0
,03-31 16:30:34.421 11128 11128 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-31 16:30:34.421  5838  5848 D BtGatt.GattService: stopScan() - queue size =1
,03-31 16:30:34.421  5838  5952 D BtGatt.ScanManager: filter size is 1
03-31 16:30:34.421  5838  5952 D BtGatt.ScanManager: delete FilterIndex - 3
03-31 16:30:34.421  5838  5955 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-31 16:30:34.421 11128 11128 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-31 16:30:34.421 11128 11128 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 16:30:34.421 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 16:30:34.421  5838  5944 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-31 16:30:34.421  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 16:30:34.421 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 16:30:34.421  5838  5952 D BtGatt.ScanManager: stopping BLe Batch
,03-31 16:30:34.421 11128 11128 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 16:30:34.421 11128 11128 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 16:30:34.426  5838  5944 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,03-31 16:30:34.426  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 16:30:34.426  5838  5952 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-31 16:30:34.426  5838  5955 D BtGatt.GattService: registerClient() - UUID=d692b731-6ec8-4e5d-a3fd-7022ff4f683f
,03-31 16:30:34.426  5838  5944 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-31 16:30:34.426  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 16:30:34.466  5838  5944 D BtGatt.GattService: onClientRegistered() - UUID=d692b731-6ec8-4e5d-a3fd-7022ff4f683f, clientIf=6
,03-31 16:30:34.466 11128 11777 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-31 16:30:34.471  5838  9004 D BtGatt.GattService: start scan with filters
,03-31 16:30:34.501  5838  9004 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 79
,03-31 16:30:34.501 11128 11128 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 16:30:34.501 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 16:30:34.501 11128 11128 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 2 -> 0
03-31 16:30:34.501  5838  5952 D BtGatt.ScanManager: handling starting scan
03-31 16:30:34.501  5838  5952 D BtGatt.ScanManager: isFilteringSupported
03-31 16:30:34.501  5838  5952 D BluetoothAdapter: setting StandAloneBleMode
03-31 16:30:34.501 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-31 16:30:34.501 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 16:30:34.501 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-31 16:30:34.501 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-31 16:30:34.501 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-31 16:30:34.501 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-31 16:30:34.506  5838  5951 D BtGatt.AdvertiseManager: message : 1,
03-31 16:30:34.506  5838  5944 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-31 16:30:34.506  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 16:30:34.506  5838  5952 D BtGatt.ScanManager: allow scan with filters
03-31 16:30:34.506  5838  5952 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,03-31 16:30:34.506  5838  5952 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
03-31 16:30:34.506  5838  5951 D BtGatt.AdvertiseManager: stop advertise for client 7
03-31 16:30:34.506  5838  5951 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-31 16:30:34.516  5838  5944 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-31 16:30:34.516  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 16:30:34.516  5838  5952 D BtGatt.ScanManager: Starting BLE batch scan
03-31 16:30:34.516  5838  5952 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-31 16:30:34.516  5838  5951 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,03-31 16:30:34.516  5838  5944 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,03-31 16:30:34.516  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 16:30:34.516  5838  5944 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-31 16:30:34.521  5838  5944 D BtGatt.GattService: Client app is not null!
,03-31 16:30:34.521  5838  5955 D BtGatt.GattService: unregisterClient() - clientIf=7,
03-31 16:30:34.521  5838  5944 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-31 16:30:34.521  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 16:30:34.526 11128 11128 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 16:30:34.526 11128 11128 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-31 16:30:34.526 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-31 16:30:34.526 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-31 16:30:34.526 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-31 16:30:34.526 11128 11128 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-31 16:30:34.526 11128 11128 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 16:30:34.526 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 16:30:34.526 11128 11128 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-31 16:30:34.531  5838  5850 D BtGatt.GattService: registerClient() - UUID=d82f0dcb-cb98-4a86-b645-92b2e84c6d53
,03-31 16:30:34.571  5838  5944 D BtGatt.GattService: onClientRegistered() - UUID=d82f0dcb-cb98-4a86-b645-92b2e84c6d53, clientIf=7
,03-31 16:30:34.576 11128 11138 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-31 16:30:34.606  5838  9004 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 64
,03-31 16:30:34.606  5838  5951 D BtGatt.AdvertiseManager: message : 0
,03-31 16:30:34.611  5838  5951 D BtGatt.AdvertiseManager: number of adv instance running0
,03-31 16:30:34.611  5838  5951 D BtGatt.AdvertiseManager: size of list is =0
,03-31 16:30:34.621  5838  5951 D BtGatt.AdvertiseManager: starting advertising
03-31 16:30:34.621  5838  5951 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-31 16:30:34.626  5838  5944 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-31 16:30:34.631  5838  5951 D BtGatt.AdvertiseManager: starting multi advertising,
,03-31 16:30:34.631  5838  5944 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
03-31 16:30:34.631  5838  5951 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,03-31 16:30:34.631  5838  5951 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 0, TxPowerLevel: 1, isConnectable: false, Timeout: 0
,03-31 16:30:34.636 11128 11128 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING,
,03-31 16:30:34.636  5838  5955 D BtGatt.GattService: stopScan() - queue size =1
,03-31 16:30:34.641  5838  5952 D BtGatt.ScanManager: filter size is 1
03-31 16:30:34.641  5838  5952 D BtGatt.ScanManager: delete FilterIndex - 4
,03-31 16:30:34.641  5838  5944 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16,
03-31 16:30:34.641  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 16:30:34.641  5838  5850 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-31 16:30:34.641  5838  5952 D BtGatt.ScanManager: stopping BLe Batch
,03-31 16:30:34.646 11128 11128 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-31 16:30:34.646  5838  5944 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-31 16:30:34.646  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 16:30:34.646  5838  5952 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-31 16:30:34.646 11128 11128 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-31 16:30:34.646 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
,03-31 16:30:34.646 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-31 16:30:34.646 11128 11128 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 16:30:34.646 11128 11128 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-31 16:30:34.646  5838  5944 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,03-31 16:30:34.646  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 16:30:34.651  5838  5850 D BtGatt.GattService: registerClient() - UUID=8403663f-cd98-425d-8c44-55e5aa5cfcae
,03-31 16:30:34.691  5838  5944 D BtGatt.GattService: onClientRegistered() - UUID=8403663f-cd98-425d-8c44-55e5aa5cfcae, clientIf=6
,03-31 16:30:34.691 11128 11144 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-31 16:30:34.696  5838  9004 D BtGatt.GattService: start scan with filters
,03-31 16:30:34.706  5838  9004 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 80
,03-31 16:30:34.706 11128 11128 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 16:30:34.706 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 16:30:34.706  5838  5952 D BtGatt.ScanManager: handling starting scan
03-31 16:30:34.706  5838  5952 D BtGatt.ScanManager: isFilteringSupported
03-31 16:30:34.706  5838  5952 D BluetoothAdapter: setting StandAloneBleMode
03-31 16:30:34.706 11128 11128 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing socket thread, for peer [<no peer name> F8:CF:C5:D9:E5:61], created successfully
03-31 16:30:34.706 11128 11128 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 1
03-31 16:30:34.706 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 16:30:34.706 11128 11128 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-31 16:30:34.706 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-31 16:30:34.706 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 16:30:34.706 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-31 16:30:34.706 11128 11876 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1560)
03-31 16:30:34.706  5838  5944 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-31 16:30:34.706  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 16:30:34.706 11128 11876 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 51477
03-31 16:30:34.706 11128 11876 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
03-31 16:30:34.706 11128 11876 I io.jxcore.node.ConnectionHelper: onListeningForIncomingConnections: Outgoing connection is using port 51477 (peer ID: F8:CF:C5:D9:E5:61)
,03-31 16:30:34.706  5838  5952 D BtGatt.ScanManager: allow scan with filters
,03-31 16:30:34.706  5838  5952 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-31 16:30:34.706  5838  5952 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
03-31 16:30:34.706 11128 11876 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "F8:CF:C5:D9:E5:61" removed
,03-31 16:30:34.711  5838  5944 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-31 16:30:34.711  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 16:30:34.711  5838  5952 D BtGatt.ScanManager: Starting BLE batch scan
,03-31 16:30:34.711  5838  5952 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-31 16:30:34.711 11128 11200 I jxcore-log: INFO testThaliMobileNative: 
03-31 16:30:34.711 11128 11200 I jxcore-log: 
03-31 16:30:34.711  5838  5944 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-31 16:30:34.711  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 16:30:34.711 11128 11200 I jxcore-log: INFO testThaliMobileNative: Forward connection
03-31 16:30:34.711 11128 11200 I jxcore-log: 
03-31 16:30:34.711  5838  5944 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1,
03-31 16:30:34.711  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 16:30:34.716 11128 11876 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 51477
,03-31 16:30:34.716 11128 11876 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
03-31 16:30:34.716 11128 11876 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-31 16:30:34.716 11128 11876 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-31 16:30:34.716 11128 11876 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1560)
03-31 16:30:34.716 11128 11876 D io.jxcore.node.OutgoingSocketThread: Exiting thread (ID: 1560)
03-31 16:30:34.716 11128 11877 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1561, name: Sender),
,03-31 16:30:34.721 11128 11878 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1562, name: Receiver)
,03-31 16:30:34.721 11128 11200 I jxcore-log: INFO testThaliMobileNative: forwardSend
03-31 16:30:34.721 11128 11200 I jxcore-log: 
,03-31 16:30:34.721  5838  6006 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
,03-31 16:30:34.721  5838  6006 D IOP_DB_BT: db_query: result 1
03-31 16:30:34.721  5838  6006 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
,03-31 16:30:34.726  5838  6006 D IOP_DB_BT: db_query: result 1
,03-31 16:30:34.771  3440  3901 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 16:30:34.776  3440  3901 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 16:30:34.776  3440  3901 D BatteryService: online:4, current avg:33, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:35
,03-31 16:30:34.776  3440  3901 D BatteryService: stay LED for fully charged
03-31 16:30:34.776  3440  3440 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 16:30:34.776  3440  3440 I MotionRecognitionService: Plugged
,03-31 16:30:34.776  3440  3440 D MotionRecognitionService:   cableConnection= 1
03-31 16:30:34.776  3440  3440 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 16:30:34.776  3440  3440 D MotionRecognitionService: skip setTransmitPower. 
,03-31 16:30:34.781  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 16:30:34.781  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 16:30:34.781  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 16:30:34.786  5838  5838 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 16:30:34.786  5838  5954 D HeadsetStateMachine: Disconnected process message: 10
,03-31 16:30:34.801  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 16:30:34.801  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 16:30:34.801  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 16:30:34.801  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 16:30:34.851  5838  6006 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61,
03-31 16:30:34.851  5838  6006 D IOP_DB_BT: db_query: result 1
03-31 16:30:34.851  5838  6006 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 16:30:34.856  5838  6006 D IOP_DB_BT: db_query: result 1
,03-31 16:30:34.866 11128 11200 I jxcore-log: INFO testThaliMobileNative: forwardData
03-31 16:30:34.866 11128 11200 I jxcore-log: 
,03-31 16:30:34.936  5838  6006 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 16:30:34.936  5838  6006 D IOP_DB_BT: db_query: result 1
03-31 16:30:34.936  5838  6006 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 16:30:34.936  5838  6006 D IOP_DB_BT: db_query: result 1
,03-31 16:30:34.946 11128 11200 I jxcore-log: INFO testThaliMobileNative: forwardData
03-31 16:30:34.946 11128 11200 I jxcore-log: 
,03-31 16:30:34.996  5838  6006 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 16:30:34.996  5838  6006 D IOP_DB_BT: db_query: result 1
03-31 16:30:34.996  5838  6006 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 16:30:34.996  5838  6006 D IOP_DB_BT: db_query: result 1
,03-31 16:30:35.001 11128 11200 I jxcore-log: INFO testThaliMobileNative: forwardData
03-31 16:30:35.001 11128 11200 I jxcore-log: 
,03-31 16:30:35.066  5838  6006 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 16:30:35.066  5838  6006 D IOP_DB_BT: db_query: result 1
03-31 16:30:35.071  5838  6006 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
,03-31 16:30:35.071  5838  6006 D IOP_DB_BT: db_query: result 1,
,03-31 16:30:35.081 11128 11200 I jxcore-log: INFO testThaliMobileNative: forwardData
03-31 16:30:35.081 11128 11200 I jxcore-log: 
,03-31 16:30:35.141  5838  6006 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 16:30:35.141  5838  6006 D IOP_DB_BT: db_query: result 1
03-31 16:30:35.141  5838  6006 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 16:30:35.141  5838  6006 D IOP_DB_BT: db_query: result 1
,03-31 16:30:35.146  5838  6006 W bt-btif : new conn_srvc id:26, app_id:255,
03-31 16:30:35.146 11128 11839 D BluetoothSocket: socket fd passed by stack  fds: [Ljava.io.FileDescriptor;@29cf6546
,03-31 16:30:35.151  5838  5955 E BluetoothRemoteDevices: setRfcommConnected true
,03-31 16:30:35.161 11128 11839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection accepted,
03-31 16:30:35.166 11128 11839 D BluetoothSocket: getInputStream(): myUserId = 0
,03-31 16:30:35.171 11128 11839 D BluetoothSocket: getOutputStream(): myUserId = 0,
,03-31 16:30:35.171 11128 11839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection initialized (thread ID: 1563)
03-31 16:30:35.171 11128 11839 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@184da307, channel: 6, state: LISTENING,
03-31 16:30:35.171 11128 11839 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@184da307, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@151d559c, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1f24bc34mSocket: android.net.LocalSocket@38342a5d impl:android.net.LocalSocketImpl@340c8fd2 fd:FileDescriptor[93]
,03-31 16:30:35.171 11128 11839 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@38342a5d impl:android.net.LocalSocketImpl@340c8fd2 fd:FileDescriptor[93],
,03-31 16:30:35.171 11128 11839 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-31 16:30:35.176 11128 11839 D BluetoothSocket: bindListen(): myUserId = 0,
,03-31 16:30:35.176 11128 11839 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-31 16:30:35.181 11128 11839 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[122]}
,03-31 16:30:35.181 11128 11839 D BluetoothSocket: bindListen(), new LocalSocket 
03-31 16:30:35.181 11128 11839 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-31 16:30:35.181 11128 11839 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@b9768a3
03-31 16:30:35.181 11128 11839 D BluetoothSocket: channel: 6
,03-31 16:30:35.181 11128 11839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-31 16:30:35.181 11128 11885 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 1563)
,03-31 16:30:35.191 11128 11200 I jxcore-log: INFO testThaliMobileNative: forwardData
03-31 16:30:35.191 11128 11200 I jxcore-log: 
,03-31 16:30:35.196 11128 11200 I jxcore-log: ok 177 received should match sent forward
03-31 16:30:35.196 11128 11200 I jxcore-log: 
,03-31 16:30:35.206 11128 11200 I jxcore-log: # teardown
03-31 16:30:35.206 11128 11200 I jxcore-log: 
,03-31 16:30:35.391  5838  6006 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 16:30:35.391  5838  6006 D IOP_DB_BT: db_query: result 1
03-31 16:30:35.391  5838  6006 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 16:30:35.391  5838  6006 D IOP_DB_BT: db_query: result 1
03-31 16:30:35.396 11128 11885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesRead: Read 15 bytes successfully (thread ID: 1563)
,03-31 16:30:35.411 11128 11885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Got valid identity from [<no peer name> F8:CF:C5:D9:E5:61],
03-31 16:30:35.411 11128 11885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesWritten: 15 bytes successfully written (thread ID: 1563)
03-31 16:30:35.411 11128 11885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: removeThreadFromList: Removing thread with ID 1563
03-31 16:30:35.411  5838  6006 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 16:30:35.416  5838  6006 D IOP_DB_BT: db_query: result 1
,03-31 16:30:35.416  5838  6006 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61,
,03-31 16:30:35.416  5838  6006 D IOP_DB_BT: db_query: result 1
03-31 16:30:35.416 11128 11885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Handshake thread disposed (thread ID: 1563)
03-31 16:30:35.416 11128 11885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onIncomingConnectionConnected: [<no peer name> F8:CF:C5:D9:E5:61]
,03-31 16:30:35.421 11128 11128 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:CF:C5:D9:E5:61]
,03-31 16:30:35.421 11128 11128 I io.jxcore.node.ConnectionHelper: onConnected: Incoming connection to peer [<no peer name> F8:CF:C5:D9:E5:61]
03-31 16:30:35.421 11128 11128 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:CF:C5:D9:E5:61] updated - the peer count is 2
03-31 16:30:35.426 11128 11885 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 1563)
,03-31 16:30:35.436 11128 11128 D BluetoothSocket: getInputStream(): myUserId = 0
,03-31 16:30:35.451 11128 11128 D BluetoothSocket: getOutputStream(): myUserId = 0
,03-31 16:30:35.456 11128 11128 I io.jxcore.node.ConnectionHelper: onConnected: Incoming socket thread, for peer [<no peer name> F8:CF:C5:D9:E5:61], created successfully
03-31 16:30:35.456 11128 11128 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 2
,03-31 16:30:35.456 11128 11891 D io.jxcore.node.IncomingSocketThread: Entering thread (ID: 1564),
,03-31 16:30:35.461  2874  3473 D EnterpriseController: netId is 0
,03-31 16:30:35.461  2874  3473 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,03-31 16:30:35.471 11128 11891 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 58150
,03-31 16:30:35.471 11128 11891 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
03-31 16:30:35.471 11128 11891 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-31 16:30:35.471 11128 11891 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-31 16:30:35.471 11128 11891 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 1564)
,03-31 16:30:35.471 11128 11891 D io.jxcore.node.IncomingSocketThread: Exiting thread (ID: 1564)
,03-31 16:30:35.481 11128 11893 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1565, name: Sender),
,03-31 16:30:35.481 11128 11894 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1566, name: Receiver)
,03-31 16:30:35.541  5838  6006 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61,
,03-31 16:30:35.546  5838  6006 D IOP_DB_BT: db_query: result 1,
,03-31 16:30:35.546  5838  6006 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61,
,03-31 16:30:35.546  5838  6006 D IOP_DB_BT: db_query: result 1,
,03-31 16:30:35.566  5838  6006 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61,
,03-31 16:30:35.571  5838  6006 D IOP_DB_BT: db_query: result 1,
,03-31 16:30:35.571  5838  6006 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61,
,03-31 16:30:35.571  5838  6006 D IOP_DB_BT: db_query: result 1,
,03-31 16:30:35.641  5838  6006 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 16:30:35.641  5838  6006 D IOP_DB_BT: db_query: result 1
03-31 16:30:35.641  5838  6006 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 16:30:35.641  5838  6006 D IOP_DB_BT: db_query: result 1
,03-31 16:30:35.656  5838  6006 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
,03-31 16:30:35.656  5838  6006 D IOP_DB_BT: db_query: result 1
03-31 16:30:35.656  5838  6006 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 16:30:35.656  5838  6006 D IOP_DB_BT: db_query: result 1
,03-31 16:30:35.671  3440  6049 D SSRM:n  : SIOP:: AP = 270, PST = 275 (W:14), CUR = 33, LCD = 0
,03-31 16:30:35.716  3440  3618 V AlarmManager: waitForAlarm result :4
03-31 16:30:35.721  5838  6006 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 16:30:35.721  5838  6006 D IOP_DB_BT: db_query: result 1
03-31 16:30:35.721  5838  6006 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 16:30:35.721  5838  6006 D IOP_DB_BT: db_query: result 1
,03-31 16:30:35.736  5838  6006 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 16:30:35.736  5838  6006 D IOP_DB_BT: db_query: result 1
03-31 16:30:35.736  5838  6006 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 16:30:35.736  5838  6006 D IOP_DB_BT: db_query: result 1
,03-31 16:30:35.741  5838  5838 D BtGatt.ScanManager: awakened up at time 277156,
03-31 16:30:35.746  5838  5952 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-31 16:30:35.746  5838  5944 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0,
03-31 16:30:35.746  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 16:30:35.786  5838  6006 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
,03-31 16:30:35.786  5838  6006 D IOP_DB_BT: db_query: result 1
03-31 16:30:35.786  5838  6006 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 16:30:35.786  5838  6006 D IOP_DB_BT: db_query: result 1
,03-31 16:30:35.791  5838  6006 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
,03-31 16:30:35.791  5838  6006 D IOP_DB_BT: db_query: result 1
03-31 16:30:35.791  5838  6006 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 16:30:35.791  5838  6006 D IOP_DB_BT: db_query: result 1
,03-31 16:30:35.866  5838  6006 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
,03-31 16:30:35.866  5838  6006 D IOP_DB_BT: db_query: result 1
,03-31 16:30:35.866  5838  6006 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 16:30:35.866  5838  6006 D IOP_DB_BT: db_query: result 1
,03-31 16:30:35.876  5838  6006 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
,03-31 16:30:35.876  5838  6006 D IOP_DB_BT: db_query: result 1
03-31 16:30:35.876  5838  6006 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
,03-31 16:30:35.876  5838  6006 D IOP_DB_BT: db_query: result 1
,03-31 16:30:36.751  3440  3618 V AlarmManager: waitForAlarm result :4
,03-31 16:30:36.766  5838  5838 D BtGatt.ScanManager: awakened up at time 278182
,03-31 16:30:36.771  5838  5952 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-31 16:30:36.776  5838  5944 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-31 16:30:36.776  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 16:30:36.871  5838  6006 E bt-btm  : tBTM_SEC_DEV:0xb34a50d8 rs_disc_pending=0
03-31 16:30:36.871  5838  6006 W bt-btif : bta_dm_acl_change(), event : 3
03-31 16:30:36.871  5838  6006 W bt-btif : bta_dm_check_av:0
03-31 16:30:36.871  5838  5944 W bt-btif : btif_dm_cback : unhandled event (14)
,03-31 16:30:37.786  3440  3618 V AlarmManager: waitForAlarm result :4
,03-31 16:30:37.801  5838  5838 D BtGatt.ScanManager: awakened up at time 279219
,03-31 16:30:37.811  5838  5952 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-31 16:30:37.811  5838  5944 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0,
03-31 16:30:37.811  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,03-31 16:30:38.081  5838  6006 E bt-btm  : Reset sec_bd_name and name flag. (BR/EDR link)
03-31 16:30:38.081  5838  6006 E bt-btm  : btm_sec_disconnected - Clearing Pending flag
,03-31 16:30:38.081  5838  6006 W bt-btif : bta_dm_acl_change(), event : 1,
03-31 16:30:38.081  5838  6006 W bt-btif : bta_dm_acl_change(), event : 2
,03-31 16:30:38.086  5838  5944 E BluetoothRemoteDevices: aclStateChangeCallback: State:DisConnected to Device:F8:95:C7:87:3C:XX
03-31 16:30:38.111  5838  5944 D BluetoothUtils: getBtEnabledContainers(): btContainers = [],
,03-31 16:30:38.111  3724  3724 D KeyguardViewMediator: Received android.bluetooth.device.action.ACL_DISCONNECTED
,03-31 16:30:38.126  3440  3440 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive,
,03-31 16:30:38.126  3440  3440 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.device.action.ACL_DISCONNECTED
03-31 16:30:38.126  3440  3440 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_ACL_DISCONNECTED
,03-31 16:30:38.141  3440  3575 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1a14b79a u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{2e187ce8 5838:com.android.bluetooth/1002}
,03-31 16:30:38.146  5838  5838 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a5f1d82
03-31 16:30:38.146  5838  5838 D BtConfig.SecureMode: isSecureModeOn:false
03-31 16:30:38.146  3440  3965 D SecContentProvider: query(), uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,03-31 16:30:38.151  3724  3724 D KeyguardViewMediator: isGear1: device is not B1!
03-31 16:30:38.151  3440  3733 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
03-31 16:30:38.156  5838  5838 I BluetoothPbapService: action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,03-31 16:30:38.161  3440  4737 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 16:30:38.161  3440  4737 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 16:30:38.161  3440  4737 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-31 16:30:38.161  3440  4737 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-31 16:30:38.176 11916 11916 E Zygote  : MountEmulatedStorage()
03-31 16:30:38.176 11916 11916 E Zygote  : v2
03-31 16:30:38.176 11916 11916 I libpersona: KNOX_SDCARD checking this for 10036
03-31 16:30:38.176 11916 11916 I libpersona: KNOX_SDCARD not a persona
,03-31 16:30:38.176 11916 11916 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
,03-31 16:30:38.181  3440  4737 I ActivityManager: Start proc 11916:com.sec.android.app.shealth/u0a36 for broadcast-3 com.sec.android.app.shealth/com.samsung.android.app.shealth.tracker.weight.receiver.TrackerWeightReceiver
,03-31 16:30:38.181 11916 11916 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
,03-31 16:30:38.181 11916 11916 E Zygote  : accessInfo : 0
,03-31 16:30:38.181 11916 11916 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-31 16:30:38.186  3440  4048 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
,03-31 16:30:38.196 10279 11926 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.ACL_DISCONNECTED State = -2147483648 Previous = -2147483648
,03-31 16:30:38.196 10279 10279 D [CarModeFW]: ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED
03-31 16:30:38.196 10279 10279 D [CarModeFW]: ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED onNotifyBluetoothDeviceDisconnected
,03-31 16:30:38.201 10279 10279 D [CarModeFW]: ConnectivityManager-Paired Devices list is empty
03-31 16:30:38.201 10279 10279 E [CarMode]: [BluetoothConnectivityListener]-onNotifyBluetoothProfileDisconnected: Unexpected error: Invalid device
,03-31 16:30:38.211 11916 11916 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-31 16:30:38.211 11916 11916 D ActivityThread: Added TimaKeyStore provider
,03-31 16:30:38.216  3440  3484 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1a14b79a u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{204208a8 11916:com.sec.android.app.shealth/u0a36}
,03-31 16:30:38.231 11916 11916 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-31 16:30:38.321 11916 11916 D HealthConsole: Service for HealthDataConsole is connected
,03-31 16:30:38.326  3440  4064 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1a14b79a u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{204208a8 11916:com.sec.android.app.shealth/u0a36}
,03-31 16:30:38.341 11916 11916 D HealthConsole: Service for HealthDataConsole is connected
,03-31 16:30:38.346  3440  3484 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1a14b79a u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{204208a8 11916:com.sec.android.app.shealth/u0a36}
,03-31 16:30:38.361  3440  4724 I ActivityManager: Killing 10249:com.sec.android.app.soundalive/u0a59 (adj 15): emptyCount ##31
,03-31 16:30:38.366  3440  4724 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1a14b79a u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{1c02850e 4131:com.google.android.googlequicksearchbox:search/u0a64}
,03-31 16:30:38.406  4131  4131 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,03-31 16:30:38.416  4131  4131 I BluetoothClassifier: Bluetooth Device Name: G4-1
,03-31 16:30:38.831  3440  3618 V AlarmManager: waitForAlarm result :4
,03-31 16:30:38.851  5838  5838 D BtGatt.ScanManager: awakened up at time 280268
,03-31 16:30:38.861  5838  5952 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-31 16:30:38.861  5838  5944 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0,
03-31 16:30:38.861  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 16:30:39.876  3440  3618 V AlarmManager: waitForAlarm result :4
,03-31 16:30:39.886  5838  5838 D BtGatt.ScanManager: awakened up at time 281304
,03-31 16:30:39.896  5838  5952 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-31 16:30:39.896  5838  5944 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-31 16:30:39.896  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 16:30:40.871  5838  6006 W bt-btif : dm_pm_timer expires
03-31 16:30:40.871  5838  6006 W bt-btif : dm_pm_timer expires 0
03-31 16:30:40.871  5838  6006 W bt-btif : proc dm_pm_timer expires
,03-31 16:30:40.911  3440  3618 V AlarmManager: waitForAlarm result :4
,03-31 16:30:40.921  5838  5838 D BtGatt.ScanManager: awakened up at time 282336
,03-31 16:30:40.921  5838  5952 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-31 16:30:40.926  5838  5944 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,03-31 16:30:40.926  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 16:30:41.271  5838  6006 W bt-btif : dm_pm_timer expires
03-31 16:30:41.271  5838  6006 W bt-btif : dm_pm_timer expires 1
03-31 16:30:41.271  5838  6006 W bt-btif : proc dm_pm_timer expires
,03-31 16:30:41.376  3440  3862 E Watchdog: !@Sync 9 [03-31 16:30:41.382]
,03-31 16:30:41.801  5838  6006 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 16:30:41.801  5838  6006 D IOP_DB_BT: db_query: result 1
03-31 16:30:41.801  5838  6006 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 16:30:41.801  5838  6006 D IOP_DB_BT: db_query: result 1
,03-31 16:30:41.931  3440  3618 V AlarmManager: waitForAlarm result :4
,03-31 16:30:41.946  5838  5838 D BtGatt.ScanManager: awakened up at time 283361
,03-31 16:30:41.951  5838  5952 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-31 16:30:41.956  5838  5944 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-31 16:30:41.956  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,03-31 16:30:41.986  5838  6006 E bt-btm  : tBTM_SEC_DEV:0xb34a529c rs_disc_pending=0
03-31 16:30:41.986  5838  6006 W bt-btif : bta_dm_acl_change(), event : 3
03-31 16:30:41.986  5838  6006 W bt-btif : bta_dm_check_av:0
03-31 16:30:41.986  5838  5944 W bt-btif : btif_dm_cback : unhandled event (14)
,03-31 16:30:42.291 11128 11893 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 1565, thread name: Sender)
03-31 16:30:42.291 11128 11893 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Input stream got -1 on read
03-31 16:30:42.291 11128 11893 W io.jxcore.node.ConnectionHelper: onDisconnected: Incoming connection, peer [<no peer name> F8:CF:C5:D9:E5:61] disconnected: Input stream got -1 on read
03-31 16:30:42.291 11128 11893 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1564
03-31 16:30:42.291 11128 11893 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 1564)
03-31 16:30:42.291 11128 11893 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@270e0f59, channel: 6, state: CONNECTED
03-31 16:30:42.291 11128 11893 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@270e0f59, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@217fd71e, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@362debffmSocket: android.net.LocalSocket@15af5dcc impl:android.net.LocalSocketImpl@2074815 fd:FileDescriptor[121]
03-31 16:30:42.291 11128 11893 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@15af5dcc impl:android.net.LocalSocketImpl@2074815 fd:FileDescriptor[121]
03-31 16:30:42.291 11128 11894 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 1566, thread name: Receiver): bt socket closed, read return: -1
03-31 16:30:42.291 11128 11894 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1566, name: Receiver)
,03-31 16:30:42.296  5838  6006 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61,
03-31 16:30:42.301  5838  6006 D IOP_DB_BT: db_query: result 1
03-31 16:30:42.301  5838  6006 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 16:30:42.301  5838  6006 D IOP_DB_BT: db_query: result 1
03-31 16:30:42.301  5838  6114 W bt-btif : invalid rfc slot id: 16
,03-31 16:30:42.301 11128 11878 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 1562, thread name: Receiver): bt socket closed, read return: -1
03-31 16:30:42.301 11128 11878 E io.jxcore.node.OutgoingSocketThread: The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
03-31 16:30:42.301 11128 11878 W io.jxcore.node.ConnectionHelper: onDisconnected: Outgoing connection, peer [<no peer name> F8:CF:C5:D9:E5:61] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
03-31 16:30:42.301 11128 11893 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@270e0f59, channel: 6, state: CLOSED,
,03-31 16:30:42.301 11128 11893 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@270e0f59, channel: 6, state: CLOSED
03-31 16:30:42.301 11128 11893 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-31 16:30:42.301 11128 11893 D io.jxcore.node.IncomingSocketThread: close: Stopping receiving thread...
03-31 16:30:42.301 11128 11893 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 1566
03-31 16:30:42.301 11128 11893 D io.jxcore.node.IncomingSocketThread: close: Stopping sending thread...
,03-31 16:30:42.301 11128 11893 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 1565
03-31 16:30:42.301 11128 11893 D io.jxcore.node.IncomingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 1564)
03-31 16:30:42.301 11128 11893 I io.jxcore.node.IncomingSocketThread: close: Complete (thread ID: 1564),
03-31 16:30:42.301 11128 11893 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
03-31 16:30:42.306 11128 11878 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: F8:CF:C5:D9:E5:61
03-31 16:30:42.306 11128 11878 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1560)
03-31 16:30:42.306 11128 11878 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 1560),
03-31 16:30:42.306 11128 11878 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2a4e472a, channel: 5, state: CONNECTED
03-31 16:30:42.306 11128 11878 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2a4e472a, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@117f491b, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@215a8ab8mSocket: android.net.LocalSocket@c215091 impl:android.net.LocalSocketImpl@31e1abf6 fd:FileDescriptor[118]
,03-31 16:30:42.306 11128 11878 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@c215091 impl:android.net.LocalSocketImpl@31e1abf6 fd:FileDescriptor[118]
03-31 16:30:42.306 11128 11878 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2a4e472a, channel: 5, state: CLOSED
03-31 16:30:42.306 11128 11878 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2a4e472a, channel: 5, state: CLOSED
03-31 16:30:42.306 11128 11878 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-31 16:30:42.306 11128 11878 D io.jxcore.node.OutgoingSocketThread: close: Stopping receiving thread...
03-31 16:30:42.306 11128 11878 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 1562,
,03-31 16:30:42.306 11128 11878 D io.jxcore.node.OutgoingSocketThread: close: Stopping sending thread...,
,03-31 16:30:42.306 11128 11878 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 1561,
03-31 16:30:42.306 11128 11878 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 1560)
03-31 16:30:42.306 11128 11877 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 1561, thread name: Sender): Socket closed
03-31 16:30:42.306 11128 11877 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1561, name: Sender)
03-31 16:30:42.306 11128 11878 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1560)
03-31 16:30:42.306 11128 11878 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
03-31 16:30:42.306 11128 11878 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1562, name: Receiver)
,03-31 16:30:42.316 11128 11893 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1565, name: Sender)
03-31 16:30:42.321 11128 11200 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 16:30:42.321 11128 11200 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
03-31 16:30:42.321 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-31 16:30:42.321 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-31 16:30:42.326  5838  5848 D BtGatt.GattService: stopScan() - queue size =1
03-31 16:30:42.331  5838  5952 D BtGatt.ScanManager: filter size is 1
03-31 16:30:42.331  5838  5952 D BtGatt.ScanManager: delete FilterIndex - 5,
,03-31 16:30:42.331  5838  5944 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-31 16:30:42.331  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 16:30:42.331  5838  5952 D BtGatt.ScanManager: stopping BLe Batch
03-31 16:30:42.331  5838  5944 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-31 16:30:42.331  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 16:30:42.331  5838  5952 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-31 16:30:42.331  5838  5944 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0,
03-31 16:30:42.331  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 16:30:42.336  5838  5955 D BtGatt.GattService: unregisterClient() - clientIf=6
03-31 16:30:42.341 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 16:30:42.341 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 16:30:42.341 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-31 16:30:42.341 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-31 16:30:42.341 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-31 16:30:42.341 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 16:30:42.341 11128 11128 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 16:30:42.341 11128 11128 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
,03-31 16:30:42.341 11128 11128 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 16:30:42.341 11128 11200 I jxcore-log: INFO thaliMobileNativeWrapper: incomingConnectionToPortNumberFailed: %s
03-31 16:30:42.341 11128 11200 I jxcore-log: 
03-31 16:30:42.341 11128 11200 I jxcore-log: INFO thaliMobileNativeWrapper: got incomingConnectionToPortNumberFailed while not in start
03-31 16:30:42.341 11128 11200 I jxcore-log: 
03-31 16:30:42.341 11128 11200 I jxcore-log: ok 178 Should be able to call stopListeningForAdvertisments in teardown
03-31 16:30:42.341 11128 11200 I jxcore-log: 
,03-31 16:30:42.351 11128 11200 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-31 16:30:42.351 11128 11200 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-31 16:30:42.351 11128 11200 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,03-31 16:30:42.351 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-31 16:30:42.356 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-31 16:30:42.356 11128 11200 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@35bf5bf7, channel: 6, state: LISTENING
03-31 16:30:42.356 11128 11200 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@35bf5bf7, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@b9768a3, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@8899a64mSocket: android.net.LocalSocket@1cf964cd impl:android.net.LocalSocketImpl@16749182 fd:FileDescriptor[122]
,03-31 16:30:42.356 11128 11200 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1cf964cd impl:android.net.LocalSocketImpl@16749182 fd:FileDescriptor[122]
,03-31 16:30:42.356 11128 11200 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-31 16:30:42.356 11128 11839 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-31 16:30:42.356 11128 11839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-31 16:30:42.356 11128 11839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-31 16:30:42.356 11128 11128 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-31 16:30:42.356 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-31 16:30:42.356 11128 11128 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-31 16:30:42.356 11128 11128 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-31 16:30:42.361 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-31 16:30:42.361 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-31 16:30:42.361 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-31 16:30:42.361 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-31 16:30:42.361 11128 11200 D BluetoothLeScanner: could not find callback wrapper
03-31 16:30:42.361 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 16:30:42.361 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-31 16:30:42.366  5838  5951 D BtGatt.AdvertiseManager: message : 1,
03-31 16:30:42.366  5838  5951 D BtGatt.AdvertiseManager: stop advertise for client 7
,03-31 16:30:42.366  5838  5951 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-31 16:30:42.366  5838  5951 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-31 16:30:42.366  5838  5944 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0,
,03-31 16:30:42.366  5838  5944 D BtGatt.GattService: Client app is not null!
,03-31 16:30:42.371  5838  5955 D BtGatt.GattService: unregisterClient() - clientIf=7
03-31 16:30:42.371 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
03-31 16:30:42.371 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-31 16:30:42.371 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false,
,03-31 16:30:42.371 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-31 16:30:42.371 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-31 16:30:42.371 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false,
,03-31 16:30:42.371 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 16:30:42.371 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...,
03-31 16:30:42.376 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-31 16:30:42.376 11128 11200 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-31 16:30:42.376 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 16:30:42.376 11128 11128 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 16:30:42.376 11128 11128 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed,
03-31 16:30:42.376 11128 11128 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
03-31 16:30:42.376 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 16:30:42.376 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-31 16:30:42.381 11128 11128 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-31 16:30:42.386 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-31 16:30:42.386 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-31 16:30:42.386 11128 11128 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 16:30:42.386 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-31 16:30:42.386 11128 11200 I jxcore-log: 
,03-31 16:30:42.396 11128 11128 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 16:30:42.396 11128 11128 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 16:30:42.396 11128 11200 I jxcore-log: ok 179 Should be able to call stopAdvertisingAndListening in teardown
03-31 16:30:42.396 11128 11200 I jxcore-log: 
,03-31 16:30:42.401 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 16:30:42.401 11128 11200 I jxcore-log: 
,03-31 16:30:42.406 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 16:30:42.406 11128 11200 I jxcore-log: 
,03-31 16:30:42.406 11128 11200 I jxcore-log: # setup
03-31 16:30:42.406 11128 11200 I jxcore-log: 
,03-31 16:30:42.426  5838  6006 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0x15):jv handle:0x0 not FOUND
,03-31 16:30:42.426  5838  6006 E bt-btif : bta_jv_port_mgmt_sr_cback, p_cb:0x0, p_cb->p_cback0x0
,03-31 16:30:42.546 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 16:30:42.546 11128 11200 I jxcore-log: 
,03-31 16:30:42.551 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 16:30:42.551 11128 11200 I jxcore-log: 
,03-31 16:30:42.561 11128 11200 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 16:30:42.561 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 16:30:42.561 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 16:30:42.561 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 16:30:42.561 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 16:30:42.561 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 16:30:42.561 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 16:30:42.561 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 16:30:42.561 11128 11200 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 16:30:42.566 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 16:30:42.566 11128 11200 I jxcore-log: 
,03-31 16:30:42.566 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 16:30:42.566 11128 11200 I jxcore-log: 
,03-31 16:30:42.571 11128 11200 I jxcore-log: # 42. #startListeningForAdvertisements should fail if start not called
03-31 16:30:42.571 11128 11200 I jxcore-log: 
,03-31 16:30:42.576 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 16:30:42.576 11128 11200 I jxcore-log: 
,03-31 16:30:42.741 11128 11200 I jxcore-log: ok 180 specific error should be returned
03-31 16:30:42.741 11128 11200 I jxcore-log: 
,03-31 16:30:42.746 11128 11200 I jxcore-log: # teardown
03-31 16:30:42.746 11128 11200 I jxcore-log: 
,03-31 16:30:42.881 11128 11200 I jxcore-log: ok 181 must be stopped
03-31 16:30:42.881 11128 11200 I jxcore-log: 
,03-31 16:30:42.886 11128 11200 I jxcore-log: # setup
03-31 16:30:42.886 11128 11200 I jxcore-log: 
,03-31 16:30:43.031 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 16:30:43.031 11128 11200 I jxcore-log: 
,03-31 16:30:43.041 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 16:30:43.041 11128 11200 I jxcore-log: 
,03-31 16:30:43.056 11128 11200 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
03-31 16:30:43.056 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 16:30:43.056 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 16:30:43.056 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 16:30:43.056 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 16:30:43.056 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 16:30:43.056 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 16:30:43.056 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 16:30:43.061 11128 11200 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
,03-31 16:30:43.066 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 16:30:43.066 11128 11200 I jxcore-log: 
,03-31 16:30:43.071 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 16:30:43.071 11128 11200 I jxcore-log: 
,03-31 16:30:43.076 11128 11200 I jxcore-log: # 43. #startUpdateAdvertisingAndListening should fail if start not called
03-31 16:30:43.076 11128 11200 I jxcore-log: 
,03-31 16:30:43.076 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 16:30:43.076 11128 11200 I jxcore-log: 
,03-31 16:30:43.256 11128 11200 I jxcore-log: ok 182 specific error should be returned
03-31 16:30:43.256 11128 11200 I jxcore-log: 
,03-31 16:30:43.261 11128 11200 I jxcore-log: # teardown
03-31 16:30:43.261 11128 11200 I jxcore-log: 
,03-31 16:30:43.341 11128 11200 I jxcore-log: ok 183 must be stopped
03-31 16:30:43.341 11128 11200 I jxcore-log: 
,03-31 16:30:43.341 11128 11200 I jxcore-log: # setup
03-31 16:30:43.341 11128 11200 I jxcore-log: 
,03-31 16:30:43.501 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 16:30:43.501 11128 11200 I jxcore-log: 
,03-31 16:30:43.511 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 16:30:43.511 11128 11200 I jxcore-log: 
,03-31 16:30:43.516 11128 11200 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 16:30:43.516 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 16:30:43.516 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 16:30:43.516 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 16:30:43.516 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 16:30:43.516 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 16:30:43.516 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 16:30:43.516 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 16:30:43.521 11128 11200 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 16:30:43.526 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 16:30:43.526 11128 11200 I jxcore-log: 
,03-31 16:30:43.531 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 16:30:43.531 11128 11200 I jxcore-log: 
,03-31 16:30:43.536 11128 11200 I jxcore-log: # 44. should be able to call #stopListeningForAdvertisements many times
03-31 16:30:43.536 11128 11200 I jxcore-log: 
,03-31 16:30:43.536 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 16:30:43.536 11128 11200 I jxcore-log: 
,03-31 16:30:43.671 11128 11200 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 16:30:43.671 11128 11200 I jxcore-log: 
,03-31 16:30:43.676 11128 11200 I jxcore-log: DEBUG createNativeListener: listening 51221
03-31 16:30:43.676 11128 11200 I jxcore-log: 
,03-31 16:30:43.681 11128 11200 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 16:30:43.681 11128 11200 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-31 16:30:43.681 11128 11200 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 16:30:43.686 11128 11200 I jxcore-log: ok 184 no errors
03-31 16:30:43.686 11128 11200 I jxcore-log: 
,03-31 16:30:43.691 11128 11200 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 16:30:43.691 11128 11200 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-31 16:30:43.691 11128 11200 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 16:30:43.696 11128 11200 I jxcore-log: ok 185 still no errors
03-31 16:30:43.696 11128 11200 I jxcore-log: 
,03-31 16:30:43.706 11128 11200 I jxcore-log: # teardown
03-31 16:30:43.706 11128 11200 I jxcore-log: 
,03-31 16:30:43.861 11128 11200 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 16:30:43.861 11128 11200 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 16:30:43.861 11128 11200 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 16:30:43.866 11128 11200 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 16:30:43.866 11128 11200 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 16:30:43.871 11128 11200 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 16:30:43.876 11128 11200 I jxcore-log: ok 186 must be stopped
03-31 16:30:43.876 11128 11200 I jxcore-log: 
,03-31 16:30:43.886 11128 11200 I jxcore-log: # setup
03-31 16:30:43.886 11128 11200 I jxcore-log: 
,03-31 16:30:43.991 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 16:30:43.991 11128 11200 I jxcore-log: 
,03-31 16:30:43.996 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 16:30:43.996 11128 11200 I jxcore-log: 
,03-31 16:30:44.006 11128 11200 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 16:30:44.006 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 16:30:44.006 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 16:30:44.006 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 16:30:44.006 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 16:30:44.006 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 16:30:44.006 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 16:30:44.006 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 16:30:44.011 11128 11200 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 16:30:44.011 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 16:30:44.011 11128 11200 I jxcore-log: 
,03-31 16:30:44.016 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 16:30:44.016 11128 11200 I jxcore-log: 
,03-31 16:30:44.021 11128 11200 I jxcore-log: # 45. should be able to call #startListeningForAdvertisements many times
03-31 16:30:44.021 11128 11200 I jxcore-log: 
,03-31 16:30:44.021 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 16:30:44.021 11128 11200 I jxcore-log: 
,03-31 16:30:44.161 11128 11200 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 16:30:44.161 11128 11200 I jxcore-log: 
,03-31 16:30:44.166 11128 11200 I jxcore-log: DEBUG createNativeListener: listening 46072
03-31 16:30:44.166 11128 11200 I jxcore-log: 
,03-31 16:30:44.171 11128 11200 I io.jxcore.node.ConnectionHelper: start: Port number: 58150, start advertisements: false
,03-31 16:30:44.171 11128 11200 I io.jxcore.node.ConnectionHelper: restoreDefaultBleDiscoverySettings: Powering the BLE discovery back up
03-31 16:30:44.171 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 0 -> 2
,03-31 16:30:44.176 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-31 16:30:44.176 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 16:30:44.176 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-31 16:30:44.176 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-31 16:30:44.176 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-31 16:30:44.176 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-31 16:30:44.176 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 1, timeout: 0, is connectable: false
,03-31 16:30:44.176 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-31 16:30:44.176 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 1 -> 3
,03-31 16:30:44.181 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-31 16:30:44.181 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 16:30:44.181 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-31 16:30:44.181 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-31 16:30:44.181 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-31 16:30:44.181 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-31 16:30:44.181 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-31 16:30:44.181 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-31 16:30:44.181 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 0 -> 2
03-31 16:30:44.181 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-31 16:30:44.181 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 16:30:44.181 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-31 16:30:44.181 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-31 16:30:44.181 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-31 16:30:44.181 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-31 16:30:44.186 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-31 16:30:44.186 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 16:30:44.186 11128 11200 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-31 16:30:44.186 11128 11200 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,03-31 16:30:44.186 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-31 16:30:44.191 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-31 16:30:44.191 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 16:30:44.191 11128 11200 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 16:30:44.201  5838  5955 D BtGatt.GattService: registerClient() - UUID=b7b2753f-6aa7-427b-85d2-9d0a8d7ddc0d
,03-31 16:30:44.241  5838  5944 D BtGatt.GattService: onClientRegistered() - UUID=b7b2753f-6aa7-427b-85d2-9d0a8d7ddc0d, clientIf=6
03-31 16:30:44.246 11128 11138 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-31 16:30:44.251  5838  9004 D BtGatt.GattService: start scan with filters
,03-31 16:30:44.276  5838  9004 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 81
,03-31 16:30:44.276  5838  5952 D BtGatt.ScanManager: handling starting scan
03-31 16:30:44.276  5838  5952 D BtGatt.ScanManager: isFilteringSupported
03-31 16:30:44.276  5838  5952 D BluetoothAdapter: setting StandAloneBleMode
,03-31 16:30:44.281  5838  5944 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-31 16:30:44.281  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 16:30:44.286  5838  5952 D BtGatt.ScanManager: allow scan with filters
03-31 16:30:44.286  5838  5952 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-31 16:30:44.286  5838  5952 D BtGatt.ScanManager: set filter index= 6 for clientIf= 6
,03-31 16:30:44.291  5838  5944 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-31 16:30:44.291  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 16:30:44.291  5838  5952 D BtGatt.ScanManager: Starting BLE batch scan
03-31 16:30:44.291  5838  5952 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-31 16:30:44.296  5838  5944 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-31 16:30:44.296  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 16:30:44.296 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
03-31 16:30:44.296 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-31 16:30:44.296 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-31 16:30:44.296 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,03-31 16:30:44.296 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false,
,03-31 16:30:44.296 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-31 16:30:44.296 11128 11128 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-31 16:30:44.301 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 16:30:44.301 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 16:30:44.301 11128 11128 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 16:30:44.301 11128 11128 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed,
,03-31 16:30:44.301 11128 11128 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 16:30:44.301 11128 11200 I io.jxcore.node.ConnectionHelper: start: OK
03-31 16:30:44.306  5838  5944 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1,
03-31 16:30:44.306  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,03-31 16:30:44.321 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false},
03-31 16:30:44.321 11128 11200 I jxcore-log: 
,03-31 16:30:44.321 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 16:30:44.321 11128 11200 I jxcore-log: 
,03-31 16:30:44.326 11128 11200 I jxcore-log: ok 187 no errors
03-31 16:30:44.326 11128 11200 I jxcore-log: 
,03-31 16:30:44.331 11128 11200 I io.jxcore.node.ConnectionHelper: start: Port number: 58150, start advertisements: false
,03-31 16:30:44.331 11128 11200 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-31 16:30:44.331 11128 11200 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 16:30:44.331 11128 11200 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 16:30:44.336 11128 11200 I io.jxcore.node.ConnectionHelper: start: OK
,03-31 16:30:44.336 11128 11200 I jxcore-log: ok 188 still no errors
03-31 16:30:44.336 11128 11200 I jxcore-log: 
,03-31 16:30:44.346 11128 11200 I jxcore-log: # teardown
03-31 16:30:44.346 11128 11200 I jxcore-log: 
,03-31 16:30:44.511 11128 11200 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 16:30:44.511 11128 11200 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,03-31 16:30:44.511 11128 11200 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,03-31 16:30:44.511 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-31 16:30:44.511 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-31 16:30:44.511 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-31 16:30:44.516 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-31 16:30:44.516 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser,
03-31 16:30:44.516 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-31 16:30:44.521  5838  5848 D BtGatt.GattService: stopScan() - queue size =1,
,03-31 16:30:44.521  5838  5952 D BtGatt.ScanManager: filter size is 1
03-31 16:30:44.521  5838  5952 D BtGatt.ScanManager: delete FilterIndex - 6
03-31 16:30:44.521  5838  5944 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-31 16:30:44.521  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 16:30:44.521  5838  5952 D BtGatt.ScanManager: stopping BLe Batch
03-31 16:30:44.521  5838  5944 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-31 16:30:44.521  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 16:30:44.526  5838  5952 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-31 16:30:44.526  5838  5944 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-31 16:30:44.526  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 16:30:44.531  5838  5955 D BtGatt.GattService: unregisterClient() - clientIf=6,
,03-31 16:30:44.531 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 16:30:44.531 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 16:30:44.531 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-31 16:30:44.531 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,03-31 16:30:44.531 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-31 16:30:44.531 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-31 16:30:44.536 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
03-31 16:30:44.536 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 16:30:44.536 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-31 16:30:44.536 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
03-31 16:30:44.536 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 16:30:44.536 11128 11128 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
03-31 16:30:44.536 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 16:30:44.536 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-31 16:30:44.546 11128 11128 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-31 16:30:44.551 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-31 16:30:44.551 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
03-31 16:30:44.551 11128 11128 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
,03-31 16:30:44.561 11128 11128 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false,
03-31 16:30:44.561 11128 11128 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 16:30:44.561 11128 11128 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 16:30:44.561 11128 11128 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false,
,03-31 16:30:44.561 11128 11200 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements,
03-31 16:30:44.561 11128 11200 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 16:30:44.566 11128 11200 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 16:30:44.571 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 16:30:44.571 11128 11200 I jxcore-log: 
,03-31 16:30:44.576 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 16:30:44.576 11128 11200 I jxcore-log: 
,03-31 16:30:44.581 11128 11200 I jxcore-log: ok 189 must be stopped
03-31 16:30:44.581 11128 11200 I jxcore-log: 
,03-31 16:30:44.586 11128 11200 I jxcore-log: # setup
03-31 16:30:44.586 11128 11200 I jxcore-log: 
,03-31 16:30:44.751 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 16:30:44.751 11128 11200 I jxcore-log: 
,03-31 16:30:44.756 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 16:30:44.756 11128 11200 I jxcore-log: 
,03-31 16:30:44.766 11128 11200 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 16:30:44.766 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 16:30:44.766 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 16:30:44.766 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 16:30:44.766 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 16:30:44.766 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 16:30:44.766 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 16:30:44.766 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 16:30:44.771 11128 11200 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 16:30:44.776 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 16:30:44.776 11128 11200 I jxcore-log: 
,03-31 16:30:44.781 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 16:30:44.781 11128 11200 I jxcore-log: 
,03-31 16:30:44.791 11128 11200 I jxcore-log: # 46. should be able to call #startUpdateAdvertisingAndListening many times
03-31 16:30:44.791 11128 11200 I jxcore-log: 
,03-31 16:30:44.796 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 16:30:44.796 11128 11200 I jxcore-log: 
,03-31 16:30:44.886  3440  3901 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-31 16:30:44.886  3440  3901 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 16:30:44.886  3440  3901 D BatteryService: online:4, current avg:33, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:46
03-31 16:30:44.886  3440  3901 D BatteryService: stay LED for fully charged
03-31 16:30:44.886  3440  3440 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 16:30:44.891  3440  3440 I MotionRecognitionService: Plugged
03-31 16:30:44.891  3440  3440 D MotionRecognitionService:   cableConnection= 1
03-31 16:30:44.891  3440  3440 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 16:30:44.891  3440  3440 D MotionRecognitionService: skip setTransmitPower. 
,03-31 16:30:44.891  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 16:30:44.891  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 16:30:44.891  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 16:30:44.901  5838  5838 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 16:30:44.901  5838  5954 D HeadsetStateMachine: Disconnected process message: 10
,03-31 16:30:44.916  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 16:30:44.916  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 16:30:44.916  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 16:30:44.916  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 16:30:44.931 11128 11200 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 16:30:44.931 11128 11200 I jxcore-log: 
,03-31 16:30:44.936 11128 11200 I jxcore-log: DEBUG createNativeListener: listening 36040
03-31 16:30:44.936 11128 11200 I jxcore-log: 
,03-31 16:30:44.941 11128 11200 I io.jxcore.node.ConnectionHelper: start: Port number: 36040, start advertisements: true
03-31 16:30:44.941 11128 11200 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 16:30:44.941 11128 11200 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-31 16:30:44.941 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-31 16:30:44.946 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-31 16:30:44.946 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 16:30:44.946 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 16:30:44.946 11128 11200 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 16:30:44.946  5838  5850 D BtGatt.GattService: registerClient() - UUID=040373d4-2949-49ff-927d-fdc54b5cd95f
,03-31 16:30:44.991  5838  5944 D BtGatt.GattService: onClientRegistered() - UUID=040373d4-2949-49ff-927d-fdc54b5cd95f, clientIf=6
,03-31 16:30:44.991 11128 11144 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-31 16:30:44.991  5838  9004 D BtGatt.GattService: start scan with filters
,03-31 16:30:45.006  5838  9004 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 82
,03-31 16:30:45.011 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-31 16:30:45.011 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 16:30:45.011  5838  5952 D BtGatt.ScanManager: handling starting scan
03-31 16:30:45.011  5838  5952 D BtGatt.ScanManager: isFilteringSupported
03-31 16:30:45.011 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-31 16:30:45.011  5838  5952 D BluetoothAdapter: setting StandAloneBleMode
03-31 16:30:45.011 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 16:30:45.011 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 16:30:45.011 11128 11128 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 16:30:45.011 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 16:30:45.011 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-31 16:30:45.011 11128 11200 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
,03-31 16:30:45.011 11128 11200 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 16:30:45.011 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 16:30:45.011 11128 11200 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-31 16:30:45.011  5838  5944 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-31 16:30:45.021  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 16:30:45.021  5838  5952 D BtGatt.ScanManager: allow scan with filters
,03-31 16:30:45.021  5838  5952 D BtGatt.ScanManager: client filter size is = 1available filters are = 13,
03-31 16:30:45.021  5838  5952 D BtGatt.ScanManager: set filter index= 7 for clientIf= 6
,03-31 16:30:45.021  5838  5944 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-31 16:30:45.021  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 16:30:45.021  5838  5952 D BtGatt.ScanManager: Starting BLE batch scan
03-31 16:30:45.021  5838  5952 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-31 16:30:45.026  5838  9004 D BtGatt.GattService: registerClient() - UUID=868d1204-2f28-498e-8aaf-2c59f6cc9f87
03-31 16:30:45.026  5838  5944 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-31 16:30:45.026  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 16:30:45.031  5838  5944 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-31 16:30:45.031  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 16:30:45.066  5838  5944 D BtGatt.GattService: onClientRegistered() - UUID=868d1204-2f28-498e-8aaf-2c59f6cc9f87, clientIf=7,
03-31 16:30:45.066 11128 11138 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-31 16:30:45.086  5838  5848 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 65
,03-31 16:30:45.086  5838  5951 D BtGatt.AdvertiseManager: message : 0
,03-31 16:30:45.086  5838  5951 D BtGatt.AdvertiseManager: number of adv instance running0
03-31 16:30:45.086  5838  5951 D BtGatt.AdvertiseManager: size of list is =0
,03-31 16:30:45.091  5838  5951 D BtGatt.AdvertiseManager: starting advertising
03-31 16:30:45.091  5838  5951 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-31 16:30:45.096  5838  5944 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-31 16:30:45.101  5838  5951 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 16:30:45.101  5838  5944 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-31 16:30:45.101  5838  5951 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,03-31 16:30:45.106  5838  5951 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,03-31 16:30:45.106 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-31 16:30:45.106 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-31 16:30:45.111 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
03-31 16:30:45.111 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 16:30:45.111 11128 11200 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-31 16:30:45.111 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
03-31 16:30:45.111 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-31 16:30:45.111 11128 11200 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-31 16:30:45.111 11128 11200 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-31 16:30:45.111 11128 11200 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-31 16:30:45.111 11128 11128 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything,
03-31 16:30:45.111 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 16:30:45.111 11128 11128 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,03-31 16:30:45.111 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-31 16:30:45.116 11128 11128 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-31 16:30:45.116 11128 11128 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
,03-31 16:30:45.116 11128 11128 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 16:30:45.116 11128 11128 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-31 16:30:45.116 11128 11128 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-31 16:30:45.116 11128 11128 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 16:30:45.116 11128 11128 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-31 16:30:45.116 11128 11128 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-31 16:30:45.116 11128 11200 I io.jxcore.node.ConnectionHelper: start: OK
03-31 16:30:45.116 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 16:30:45.116 11128 11200 I jxcore-log: 
03-31 16:30:45.116 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 16:30:45.116 11128 11200 I jxcore-log: 
,03-31 16:30:45.126 11128 12020 D BluetoothSocket: bindListen(): myUserId = 0
,03-31 16:30:45.126 11128 12020 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-31 16:30:45.131 11128 12020 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[118]}
,03-31 16:30:45.131 11128 12020 D BluetoothSocket: bindListen(), new LocalSocket 
03-31 16:30:45.131 11128 12020 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-31 16:30:45.131 11128 12020 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@100b6085
03-31 16:30:45.131 11128 12020 D BluetoothSocket: channel: 6
03-31 16:30:45.131 11128 12020 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-31 16:30:45.136 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-31 16:30:45.136 11128 11200 I jxcore-log: 
,03-31 16:30:45.136 11128 11200 I jxcore-log: ok 190 no errors
03-31 16:30:45.136 11128 11200 I jxcore-log: 
,03-31 16:30:45.141 11128 11200 I io.jxcore.node.ConnectionHelper: start: Port number: 36040, start advertisements: true
03-31 16:30:45.141 11128 11200 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 16:30:45.141 11128 11200 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-31 16:30:45.141 11128 11200 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 16:30:45.141 11128 11200 I io.jxcore.node.ConnectionHelper: start: OK
,03-31 16:30:45.146 11128 11200 I jxcore-log: ok 191 still no errors
03-31 16:30:45.146 11128 11200 I jxcore-log: 
,03-31 16:30:45.151 11128 11200 I jxcore-log: # teardown
03-31 16:30:45.151 11128 11200 I jxcore-log: 
,03-31 16:30:45.286 11128 11200 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 16:30:45.291 11128 11200 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
,03-31 16:30:45.291 11128 11200 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,03-31 16:30:45.291 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-31 16:30:45.291 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,03-31 16:30:45.291 11128 11200 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@381eceda, channel: 6, state: LISTENING
,03-31 16:30:45.291 11128 11200 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@381eceda, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@100b6085, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1ec0af0bmSocket: android.net.LocalSocket@3ae211e8 impl:android.net.LocalSocketImpl@35268001 fd:FileDescriptor[118]
,03-31 16:30:45.291 11128 11200 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3ae211e8 impl:android.net.LocalSocketImpl@35268001 fd:FileDescriptor[118]
,03-31 16:30:45.296 11128 11200 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-31 16:30:45.296 11128 12020 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-31 16:30:45.296 11128 12020 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-31 16:30:45.296 11128 12020 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-31 16:30:45.296 11128 11128 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-31 16:30:45.296 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-31 16:30:45.301 11128 11128 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED,
03-31 16:30:45.301 11128 11128 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-31 16:30:45.301 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-31 16:30:45.301 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-31 16:30:45.301 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-31 16:30:45.301 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-31 16:30:45.301 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-31 16:30:45.306  5838  5955 D BtGatt.GattService: stopScan() - queue size =1,
,03-31 16:30:45.306  5838  5952 D BtGatt.ScanManager: filter size is 1,
,03-31 16:30:45.306  5838  5952 D BtGatt.ScanManager: delete FilterIndex - 7
,03-31 16:30:45.306  5838  5944 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-31 16:30:45.306  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 16:30:45.306  5838  5952 D BtGatt.ScanManager: stopping BLe Batch
,03-31 16:30:45.311  5838  5944 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-31 16:30:45.311  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 16:30:45.311  5838  5952 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-31 16:30:45.311  5838  5944 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
,03-31 16:30:45.311  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,03-31 16:30:45.311  5838  5944 D BtGatt.GattService: current time is 286728956658
03-31 16:30:45.311  5838  5944 D BtGatt.GattService: Batch record : [-65, 101, -65, 109, 49, 108, 1, -128, -75, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, 31, -120, 48, -53, -76, 96, 1, -128, -62, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0]
,03-31 16:30:45.311  5838  5944 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-31 16:30:45.311  5838  5944 D ScanRecord: parseFromBytes
,03-31 16:30:45.311  5838  5944 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97],
03-31 16:30:45.311  5838  5944 D ScanRecord: parseFromBytes
03-31 16:30:45.321  5838  5850 D BtGatt.GattService: unregisterClient() - clientIf=6,
03-31 16:30:45.326 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
03-31 16:30:45.326 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 16:30:45.326 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-31 16:30:45.326 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING],
,03-31 16:30:45.326 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING],
03-31 16:30:45.326 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 16:30:45.326 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-31 16:30:45.336  5838  5951 D BtGatt.AdvertiseManager: message : 1
03-31 16:30:45.336  5838  5951 D BtGatt.AdvertiseManager: stop advertise for client 7
03-31 16:30:45.336  5838  5951 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-31 16:30:45.336  5838  5951 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,03-31 16:30:45.336  5838  5944 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-31 16:30:45.336  5838  5944 D BtGatt.GattService: Client app is not null!
03-31 16:30:45.336  5838  5955 D BtGatt.GattService: unregisterClient() - clientIf=7
03-31 16:30:45.341 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
,03-31 16:30:45.341 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,03-31 16:30:45.341 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false,
,03-31 16:30:45.341 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED],
03-31 16:30:45.341 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,03-31 16:30:45.341 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 16:30:45.341 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,03-31 16:30:45.341 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-31 16:30:45.341 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-31 16:30:45.341 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 16:30:45.341 11128 11128 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
,03-31 16:30:45.341 11128 11128 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 16:30:45.341 11128 11128 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 16:30:45.341 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 16:30:45.341 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener,
03-31 16:30:45.346 11128 11200 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 16:30:45.346 11128 11200 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 16:30:45.346 11128 11200 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-31 16:30:45.351 11128 11128 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-31 16:30:45.366 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-31 16:30:45.366 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 16:30:45.366 11128 11128 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 16:30:45.366 11128 11128 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 16:30:45.366 11128 11128 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 16:30:45.366 11128 11128 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 16:30:45.371 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-31 16:30:45.371 11128 11200 I jxcore-log: 
,03-31 16:30:45.371 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 16:30:45.371 11128 11200 I jxcore-log: 
03-31 16:30:45.371 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 16:30:45.371 11128 11200 I jxcore-log: 
03-31 16:30:45.376 11128 11200 I jxcore-log: ok 192 must be stopped
03-31 16:30:45.376 11128 11200 I jxcore-log: 
03-31 16:30:45.386 11128 11200 I jxcore-log: # setup
03-31 16:30:45.386 11128 11200 I jxcore-log: 
,03-31 16:30:45.526  3440  3462 I art     : Background partial concurrent mark sweep GC freed 49622(3MB) AllocSpace objects, 60(3MB) LOS objects, 33% free, 29MB/44MB, paused 2.320ms total 210.404ms
,03-31 16:30:45.706  3440  6049 D SSRM:n  : SIOP:: AP = 270, PST = 272 (W:14), CUR = 33, LCD = 0
,03-31 16:30:46.276 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 16:30:46.276 11128 11200 I jxcore-log: 
,03-31 16:30:46.281 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 16:30:46.281 11128 11200 I jxcore-log: 
,03-31 16:30:46.291 11128 11200 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 16:30:46.291 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 16:30:46.291 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 16:30:46.291 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 16:30:46.291 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 16:30:46.291 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 16:30:46.291 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 16:30:46.291 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 16:30:46.296 11128 11200 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 16:30:46.296 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 16:30:46.296 11128 11200 I jxcore-log: 
,03-31 16:30:46.301 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 16:30:46.301 11128 11200 I jxcore-log: 
,03-31 16:30:46.306 11128 11200 I jxcore-log: # 47. should be able to call #stopAdvertisingAndListening many times
03-31 16:30:46.306 11128 11200 I jxcore-log: 
,03-31 16:30:46.306 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 16:30:46.306 11128 11200 I jxcore-log: 
,03-31 16:30:48.021 11128 11200 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 16:30:48.021 11128 11200 I jxcore-log: 
,03-31 16:30:48.026 11128 11200 I jxcore-log: DEBUG createNativeListener: listening 48520
03-31 16:30:48.026 11128 11200 I jxcore-log: 
,03-31 16:30:48.031 11128 11200 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 16:30:48.031 11128 11200 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 16:30:48.031 11128 11200 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 16:30:48.036 11128 11200 I jxcore-log: ok 193 no errors
03-31 16:30:48.036 11128 11200 I jxcore-log: 
,03-31 16:30:48.036 11128 11200 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 16:30:48.041 11128 11200 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-31 16:30:48.041 11128 11200 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 16:30:48.046 11128 11200 I jxcore-log: ok 194 still no errors
03-31 16:30:48.046 11128 11200 I jxcore-log: 
,03-31 16:30:48.051 11128 11200 I jxcore-log: # teardown
03-31 16:30:48.051 11128 11200 I jxcore-log: 
,03-31 16:30:48.146 11128 11200 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-31 16:30:48.146 11128 11200 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 16:30:48.146 11128 11200 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 16:30:48.146 11128 11200 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 16:30:48.146 11128 11200 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 16:30:48.146 11128 11200 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 16:30:48.151 11128 11200 I jxcore-log: ok 195 must be stopped
03-31 16:30:48.151 11128 11200 I jxcore-log: 
,03-31 16:30:48.161 11128 11200 I jxcore-log: # setup
03-31 16:30:48.161 11128 11200 I jxcore-log: 
,03-31 16:30:48.321  5838  6006 E bt-btm  : Reset sec_bd_name and name flag. (BR/EDR link)
03-31 16:30:48.321  5838  6006 E bt-btm  : btm_sec_disconnected - Clearing Pending flag
03-31 16:30:48.321  5838  6006 W bt-btif : bta_dm_acl_change(), event : 1
03-31 16:30:48.321  5838  6006 W bt-btif : bta_dm_acl_change(), event : 2
,03-31 16:30:48.326  5838  5944 E BluetoothRemoteDevices: aclStateChangeCallback: State:DisConnected to Device:F8:CF:C5:D9:E5:XX
03-31 16:30:48.346  5838  5944 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
03-31 16:30:48.346  3724  3724 D KeyguardViewMediator: Received android.bluetooth.device.action.ACL_DISCONNECTED
,03-31 16:30:48.356  3440  3440 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
03-31 16:30:48.356  3440  3440 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.device.action.ACL_DISCONNECTED
03-31 16:30:48.356  3440  3440 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_ACL_DISCONNECTED
,03-31 16:30:48.371  3440  3575 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{16cdfdee u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{2e187ce8 5838:com.android.bluetooth/1002}
,03-31 16:30:48.376  5838  5838 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a5f1d82
03-31 16:30:48.381  3440  3483 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
03-31 16:30:48.376  5838  5838 D BtConfig.SecureMode: isSecureModeOn:false
03-31 16:30:48.376  3440  4064 D SecContentProvider: query(), uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,03-31 16:30:48.386  5838  5838 I BluetoothPbapService: action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
03-31 16:30:48.386  3724  3724 D KeyguardViewMediator: isGear1: device is not B1!
,03-31 16:30:48.391  3440  3965 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{16cdfdee u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{204208a8 11916:com.sec.android.app.shealth/u0a36}
,03-31 16:30:48.396  3440  3733 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
,03-31 16:30:48.416 10279 12056 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.ACL_DISCONNECTED State = -2147483648 Previous = -2147483648
,03-31 16:30:48.421  3440  3966 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{16cdfdee u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{204208a8 11916:com.sec.android.app.shealth/u0a36}
,03-31 16:30:48.421 10279 10279 D [CarModeFW]: ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED
03-31 16:30:48.421 10279 10279 D [CarModeFW]: ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED onNotifyBluetoothDeviceDisconnected
,03-31 16:30:48.426 10279 10279 D [CarModeFW]: ConnectivityManager-Paired Devices list is empty
03-31 16:30:48.426 10279 10279 E [CarMode]: [BluetoothConnectivityListener]-onNotifyBluetoothProfileDisconnected: Unexpected error: Invalid device
,03-31 16:30:48.431  3440  3965 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{16cdfdee u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{204208a8 11916:com.sec.android.app.shealth/u0a36}
,03-31 16:30:48.431 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 16:30:48.431 11128 11200 I jxcore-log: 
,03-31 16:30:48.436 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 16:30:48.436 11128 11200 I jxcore-log: 
,03-31 16:30:48.441 11128 11200 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 16:30:48.441 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 16:30:48.441 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 16:30:48.441 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 16:30:48.441 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 16:30:48.441 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 16:30:48.441 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 16:30:48.441 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 16:30:48.441  3440  3965 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{16cdfdee u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{1c02850e 4131:com.google.android.googlequicksearchbox:search/u0a64}
,03-31 16:30:48.446 11128 11200 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 16:30:48.446 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 16:30:48.446 11128 11200 I jxcore-log: 
,03-31 16:30:48.451 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 16:30:48.451 11128 11200 I jxcore-log: 
,03-31 16:30:48.451  4131  4131 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,03-31 16:30:48.451  4131  4131 I BluetoothClassifier: Bluetooth Device Name: Nexus 6
,03-31 16:30:48.456 11128 11200 I jxcore-log: # 48. can get the network status before starting
03-31 16:30:48.456 11128 11200 I jxcore-log: 
,03-31 16:30:48.456 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 16:30:48.456 11128 11200 I jxcore-log: 
,03-31 16:30:48.586 11128 11200 I jxcore-log: ok 196 network status should have certain non-empty properties
03-31 16:30:48.586 11128 11200 I jxcore-log: 
,03-31 16:30:48.586 11128 11200 I jxcore-log: # teardown
03-31 16:30:48.586 11128 11200 I jxcore-log: 
,03-31 16:30:48.676 11128 11200 I jxcore-log: ok 197 must be stopped
03-31 16:30:48.676 11128 11200 I jxcore-log: 
,03-31 16:30:48.681 11128 11200 I jxcore-log: # setup
03-31 16:30:48.681 11128 11200 I jxcore-log: 
,03-31 16:30:48.741  3440  6080 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-31 16:30:48.796 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 16:30:48.796 11128 11200 I jxcore-log: 
,03-31 16:30:48.801 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 16:30:48.801 11128 11200 I jxcore-log: 
,03-31 16:30:48.806 11128 11200 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 16:30:48.806 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 16:30:48.806 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 16:30:48.806 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 16:30:48.806 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 16:30:48.806 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 16:30:48.806 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 16:30:48.806 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 16:30:48.811 11128 11200 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 16:30:48.816 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 16:30:48.816 11128 11200 I jxcore-log: 
,03-31 16:30:48.816 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 16:30:48.816 11128 11200 I jxcore-log: 
,03-31 16:30:48.821 11128 11200 I jxcore-log: # 49. error returned with bad router
03-31 16:30:48.821 11128 11200 I jxcore-log: 
,03-31 16:30:48.826 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 16:30:48.826 11128 11200 I jxcore-log: 
,03-31 16:30:48.951 11128 11200 I jxcore-log: ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string,
03-31 16:30:48.951 11128 11200 I jxcore-log: 
,03-31 16:30:48.956 11128 11200 I jxcore-log: ok 198 specific error expected,
03-31 16:30:48.956 11128 11200 I jxcore-log: 
,03-31 16:30:48.966 11128 11200 I jxcore-log: # teardown
03-31 16:30:48.966 11128 11200 I jxcore-log: 
,03-31 16:30:49.076 11128 11200 I jxcore-log: ok 199 must be stopped
03-31 16:30:49.076 11128 11200 I jxcore-log: 
,03-31 16:30:49.081 11128 11200 I jxcore-log: # setup
03-31 16:30:49.081 11128 11200 I jxcore-log: 
,03-31 16:30:49.256 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 16:30:49.256 11128 11200 I jxcore-log: 
,03-31 16:30:49.261 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 16:30:49.261 11128 11200 I jxcore-log: 
,03-31 16:30:49.266 11128 11200 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 16:30:49.266 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 16:30:49.266 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 16:30:49.266 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 16:30:49.266 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 16:30:49.266 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 16:30:49.266 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 16:30:49.266 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 16:30:49.271 11128 11200 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 16:30:49.276 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 16:30:49.276 11128 11200 I jxcore-log: 
,03-31 16:30:49.276 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 16:30:49.276 11128 11200 I jxcore-log: 
,03-31 16:30:49.281 11128 11200 I jxcore-log: # 50. all services are stopped when we call stop
03-31 16:30:49.281 11128 11200 I jxcore-log: 
,03-31 16:30:49.286 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 16:30:49.286 11128 11200 I jxcore-log: 
,03-31 16:30:49.436 11128 11200 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 16:30:49.436 11128 11200 I jxcore-log: 
,03-31 16:30:49.441 11128 11200 I jxcore-log: DEBUG createNativeListener: listening 35363
03-31 16:30:49.441 11128 11200 I jxcore-log: 
,03-31 16:30:49.451 11128 11200 I io.jxcore.node.ConnectionHelper: start: Port number: 36040, start advertisements: false
,03-31 16:30:49.451 11128 11200 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 16:30:49.451 11128 11200 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,03-31 16:30:49.451 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-31 16:30:49.461 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 16:30:49.461 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 16:30:49.461 11128 11200 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 16:30:49.461  5838  9004 D BtGatt.GattService: registerClient() - UUID=c973fc78-c115-4914-8f3f-485f182ebf71
,03-31 16:30:49.506  5838  5944 D BtGatt.GattService: onClientRegistered() - UUID=c973fc78-c115-4914-8f3f-485f182ebf71, clientIf=6
,03-31 16:30:49.506 11128 11777 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-31 16:30:49.506  5838  5850 D BtGatt.GattService: start scan with filters
,03-31 16:30:49.516  5838  5850 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 83,
03-31 16:30:49.516 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 16:30:49.516 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 16:30:49.516 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,03-31 16:30:49.516  5838  5952 D BtGatt.ScanManager: handling starting scan
03-31 16:30:49.516  5838  5952 D BtGatt.ScanManager: isFilteringSupported
03-31 16:30:49.516  5838  5952 D BluetoothAdapter: setting StandAloneBleMode
03-31 16:30:49.516 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 16:30:49.516 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 16:30:49.516 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-31 16:30:49.516 11128 11128 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false,
,03-31 16:30:49.521  5838  5944 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-31 16:30:49.521  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 16:30:49.521 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 16:30:49.521 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-31 16:30:49.521  5838  5952 D BtGatt.ScanManager: allow scan with filters
03-31 16:30:49.521 11128 11200 I io.jxcore.node.ConnectionHelper: start: OK
03-31 16:30:49.521  5838  5952 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-31 16:30:49.521 11128 11128 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 16:30:49.521  5838  5952 D BtGatt.ScanManager: set filter index= 8 for clientIf= 6
03-31 16:30:49.521 11128 11128 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-31 16:30:49.521 11128 11128 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 16:30:49.521  5838  5944 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-31 16:30:49.521  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 16:30:49.526  5838  5952 D BtGatt.ScanManager: Starting BLE batch scan
03-31 16:30:49.526  5838  5952 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-31 16:30:49.526  5838  5944 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0,
03-31 16:30:49.526  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 16:30:49.526 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 16:30:49.526 11128 11200 I jxcore-log: 
,03-31 16:30:49.526  5838  5944 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-31 16:30:49.526  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 16:30:49.531 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 16:30:49.531 11128 11200 I jxcore-log: 
,03-31 16:30:49.536 11128 11200 I io.jxcore.node.ConnectionHelper: start: Port number: 35363, start advertisements: true
,03-31 16:30:49.536 11128 11200 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 16:30:49.536 11128 11200 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-31 16:30:49.536 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-31 16:30:49.541 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-31 16:30:49.541 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
03-31 16:30:49.541 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 16:30:49.541 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-31 16:30:49.541 11128 11200 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-31 16:30:49.541 11128 11200 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-31 16:30:49.541 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 16:30:49.541 11128 11200 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-31 16:30:49.546  5838  5850 D BtGatt.GattService: registerClient() - UUID=a087cf66-b8b6-4346-9d6f-42fbaeed5f40
,03-31 16:30:49.586  5838  5944 D BtGatt.GattService: onClientRegistered() - UUID=a087cf66-b8b6-4346-9d6f-42fbaeed5f40, clientIf=7,
03-31 16:30:49.586 11128 11144 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-31 16:30:49.606  5838  5955 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 66
,03-31 16:30:49.606  5838  5951 D BtGatt.AdvertiseManager: message : 0
,03-31 16:30:49.606  5838  5951 D BtGatt.AdvertiseManager: number of adv instance running0
03-31 16:30:49.606  5838  5951 D BtGatt.AdvertiseManager: size of list is =0
,03-31 16:30:49.611  5838  5951 D BtGatt.AdvertiseManager: starting advertising
03-31 16:30:49.611  5838  5951 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-31 16:30:49.616  5838  5944 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-31 16:30:49.621  5838  5951 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 16:30:49.621  5838  5944 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-31 16:30:49.621  5838  5951 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,03-31 16:30:49.626  5838  5951 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,03-31 16:30:49.626 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 16:30:49.626 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-31 16:30:49.626 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK,
03-31 16:30:49.626 11128 11128 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-31 16:30:49.626 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-31 16:30:49.626 11128 11128 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING],
03-31 16:30:49.626 11128 11128 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-31 16:30:49.631 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-31 16:30:49.631 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 16:30:49.631 11128 11128 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 16:30:49.631 11128 11200 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-31 16:30:49.631 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 16:30:49.631 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-31 16:30:49.631 11128 11200 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,03-31 16:30:49.631 11128 11200 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-31 16:30:49.631 11128 11200 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-31 16:30:49.636 11128 11128 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything,
03-31 16:30:49.636 11128 11128 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 16:30:49.636 11128 11128 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,03-31 16:30:49.636 11128 11200 I io.jxcore.node.ConnectionHelper: start: OK
,03-31 16:30:49.641 11128 12081 D BluetoothSocket: bindListen(): myUserId = 0,
,03-31 16:30:49.646 11128 12081 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-31 16:30:49.646 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true},
03-31 16:30:49.646 11128 11200 I jxcore-log: 
,03-31 16:30:49.651 11128 12081 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[118]}
03-31 16:30:49.651 11128 12081 D BluetoothSocket: bindListen(), new LocalSocket 
03-31 16:30:49.651 11128 12081 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() ,
03-31 16:30:49.651 11128 12081 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@257a1b3d
03-31 16:30:49.651 11128 12081 D BluetoothSocket: channel: 6
03-31 16:30:49.651 11128 12081 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-31 16:30:49.656 11128 11200 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 16:30:49.656 11128 11200 I jxcore-log: 
,03-31 16:30:49.661 11128 11200 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 16:30:49.661 11128 11200 I jxcore-log: 
,03-31 16:30:49.666 11128 11200 I jxcore-log: DEBUG createNativeListener: new mux
03-31 16:30:49.666 11128 11200 I jxcore-log: 
,03-31 16:30:49.671 11128 11200 I jxcore-log: ok 200 connection to servers manager should succeed after starting
03-31 16:30:49.671 11128 11200 I jxcore-log: 
,03-31 16:30:49.696 11128 11200 I jxcore-log: ok 201 connection to router server should succeed after starting
03-31 16:30:49.696 11128 11200 I jxcore-log: 
,03-31 16:30:49.696 11128 11200 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-31 16:30:49.696 11128 11200 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-31 16:30:49.696 11128 11200 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-31 16:30:49.696 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-31 16:30:49.696 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-31 16:30:49.696 11128 11200 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@37785f32, channel: 6, state: LISTENING
03-31 16:30:49.696 11128 11200 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@37785f32, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@257a1b3d, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1dedf483mSocket: android.net.LocalSocket@1f233600 impl:android.net.LocalSocketImpl@722e39 fd:FileDescriptor[118]
03-31 16:30:49.696 11128 11200 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1f233600 impl:android.net.LocalSocketImpl@722e39 fd:FileDescriptor[118]
03-31 16:30:49.696 11128 11200 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-31 16:30:49.696 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-31 16:30:49.696 11128 12081 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-31 16:30:49.696 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-31 16:30:49.696 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-31 16:30:49.696 11128 12081 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-31 16:30:49.696 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-31 16:30:49.696 11128 12081 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-31 16:30:49.696 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-31 16:30:49.696 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-31 16:30:49.701  5838  9004 D BtGatt.GattService: stopScan() - queue size =1
,03-31 16:30:49.701  5838  5952 D BtGatt.ScanManager: filter size is 1
03-31 16:30:49.701  5838  5952 D BtGatt.ScanManager: delete FilterIndex - 8
,03-31 16:30:49.701  5838  5850 D BtGatt.GattService: unregisterClient() - clientIf=6
03-31 16:30:49.701  5838  5944 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,03-31 16:30:49.701  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 16:30:49.701 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 16:30:49.701 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 16:30:49.701 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-31 16:30:49.701 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-31 16:30:49.701 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-31 16:30:49.701  5838  5952 D BtGatt.ScanManager: stopping BLe Batch
,03-31 16:30:49.701 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 16:30:49.701 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-31 16:30:49.706  5838  5951 D BtGatt.AdvertiseManager: message : 1
03-31 16:30:49.706  5838  5951 D BtGatt.AdvertiseManager: stop advertise for client 7
03-31 16:30:49.706  5838  5951 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
,03-31 16:30:49.706  5838  5944 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-31 16:30:49.706  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 16:30:49.706  5838  5952 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-31 16:30:49.706  5838  5951 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,03-31 16:30:49.706  5838  5944 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-31 16:30:49.706  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 16:30:49.706  5838  5944 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
,03-31 16:30:49.706  5838  5944 D BtGatt.GattService: Client app is not null!
,03-31 16:30:49.711  5838  9004 D BtGatt.GattService: unregisterClient() - clientIf=7
03-31 16:30:49.711 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-31 16:30:49.711 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-31 16:30:49.711 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-31 16:30:49.711 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-31 16:30:49.711 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-31 16:30:49.711 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 16:30:49.711 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 16:30:49.711 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-31 16:30:49.711 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-31 16:30:49.711 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 16:30:49.711 11128 11128 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 16:30:49.711 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 16:30:49.711 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-31 16:30:49.716 11128 11200 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 16:30:49.716 11128 11200 I jxcore-log: 
,03-31 16:30:49.716 11128 11128 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-31 16:30:49.721 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-31 16:30:49.721 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-31 16:30:49.721 11128 11128 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-31 16:30:49.721 11128 11128 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-31 16:30:49.721 11128 11128 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 16:30:49.726 11128 11128 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-31 16:30:49.726 11128 11128 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 16:30:49.726 11128 11128 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 16:30:49.726 11128 11128 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 16:30:49.726 11128 11128 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 16:30:49.726 11128 11128 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-31 16:30:49.731 11128 11200 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 16:30:49.731 11128 11200 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 16:30:49.731 11128 11200 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 16:30:49.731 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-31 16:30:49.731 11128 11200 I jxcore-log: 
,03-31 16:30:49.736 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 16:30:49.736 11128 11200 I jxcore-log: 
,03-31 16:30:49.736 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 16:30:49.736 11128 11200 I jxcore-log: 
,03-31 16:30:49.741 11128 11200 I jxcore-log: ok 202 is stopped after calling stop
03-31 16:30:49.741 11128 11200 I jxcore-log: 
,03-31 16:30:49.751 11128 11200 I jxcore-log: ok 203 connection to servers manager should fail after stopping
03-31 16:30:49.751 11128 11200 I jxcore-log: 
,03-31 16:30:49.756 11128 11200 I jxcore-log: ok 204 connection to router server should fail after stopping
03-31 16:30:49.756 11128 11200 I jxcore-log: 
,03-31 16:30:49.766 11128 11200 I jxcore-log: # teardown
03-31 16:30:49.766 11128 11200 I jxcore-log: 
,03-31 16:30:49.901 11128 11200 I jxcore-log: ok 205 must be stopped
03-31 16:30:49.901 11128 11200 I jxcore-log: 
,03-31 16:30:49.901 11128 11200 I jxcore-log: # setup
03-31 16:30:49.901 11128 11200 I jxcore-log: 
,03-31 16:30:49.951  3440  3585 I PowerManagerService: [PWL] Off : 225s ago
03-31 16:30:49.951  3440  3585 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
03-31 16:30:49.951  3440  3585 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
03-31 16:30:49.951  3440  3585 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'bluedroid_timer' (uid=1002, pid=5838, ws=null) (elapsedTime=431)
,03-31 16:30:50.466 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 16:30:50.466 11128 11200 I jxcore-log: 
,03-31 16:30:50.471 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 16:30:50.471 11128 11200 I jxcore-log: 
,03-31 16:30:50.481 11128 11200 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 16:30:50.481 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 16:30:50.481 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 16:30:50.481 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 16:30:50.481 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 16:30:50.481 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 16:30:50.481 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 16:30:50.481 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 16:30:50.486 11128 11200 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 16:30:50.491 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 16:30:50.491 11128 11200 I jxcore-log: 
,03-31 16:30:50.491 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 16:30:50.491 11128 11200 I jxcore-log: 
,03-31 16:30:50.496 11128 11200 I jxcore-log: # 51. make sure terminateConnection is properly hooked up
03-31 16:30:50.496 11128 11200 I jxcore-log: 
,03-31 16:30:50.501 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 16:30:50.501 11128 11200 I jxcore-log: 
,03-31 16:30:50.611 11128 11200 I jxcore-log: ok 206 called with right arguments
03-31 16:30:50.611 11128 11200 I jxcore-log: 
,03-31 16:30:50.616 11128 11200 I jxcore-log: # teardown
03-31 16:30:50.616 11128 11200 I jxcore-log: 
,03-31 16:30:51.491 11128 11200 I jxcore-log: ok 207 must be stopped
03-31 16:30:51.491 11128 11200 I jxcore-log: 
,03-31 16:30:51.496 11128 11200 I jxcore-log: # setup
03-31 16:30:51.496 11128 11200 I jxcore-log: 
,03-31 16:30:51.591 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 16:30:51.591 11128 11200 I jxcore-log: 
,03-31 16:30:51.591 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 16:30:51.591 11128 11200 I jxcore-log: 
,03-31 16:30:51.601 11128 11200 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 16:30:51.601 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 16:30:51.601 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 16:30:51.601 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 16:30:51.601 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 16:30:51.601 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 16:30:51.601 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 16:30:51.601 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 16:30:51.601 11128 11200 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 16:30:51.606 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 16:30:51.606 11128 11200 I jxcore-log: 
,03-31 16:30:51.606 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 16:30:51.606 11128 11200 I jxcore-log: 
,03-31 16:30:51.611 11128 11200 I jxcore-log: # 52. make sure terminateListener is properly hooked up
03-31 16:30:51.611 11128 11200 I jxcore-log: 
,03-31 16:30:51.611 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 16:30:51.611 11128 11200 I jxcore-log: 
,03-31 16:30:52.221 11128 11200 I jxcore-log: ok 208 called with right arguments
03-31 16:30:52.221 11128 11200 I jxcore-log: 
,03-31 16:30:52.226 11128 11200 I jxcore-log: # teardown
03-31 16:30:52.226 11128 11200 I jxcore-log: 
,03-31 16:30:52.341 11128 11200 I jxcore-log: ok 209 must be stopped
03-31 16:30:52.341 11128 11200 I jxcore-log: 
,03-31 16:30:52.346 11128 11200 I jxcore-log: # setup
03-31 16:30:52.346 11128 11200 I jxcore-log: 
,03-31 16:30:52.921 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 16:30:52.921 11128 11200 I jxcore-log: 
,03-31 16:30:52.926 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 16:30:52.926 11128 11200 I jxcore-log: 
,03-31 16:30:52.936 11128 11200 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 16:30:52.936 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 16:30:52.936 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 16:30:52.936 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 16:30:52.936 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 16:30:52.936 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 16:30:52.936 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 16:30:52.936 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 16:30:52.941 11128 11200 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 16:30:52.946 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 16:30:52.946 11128 11200 I jxcore-log: 
,03-31 16:30:52.946 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 16:30:52.946 11128 11200 I jxcore-log: 
,03-31 16:30:52.951 11128 11200 I jxcore-log: # 53. make sure we actually call kill connections properly
03-31 16:30:52.951 11128 11200 I jxcore-log: 
,03-31 16:30:52.956 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 16:30:52.956 11128 11200 I jxcore-log: 
,03-31 16:30:53.086 11128 11200 I jxcore-log: ok 210 specific error expected
03-31 16:30:53.086 11128 11200 I jxcore-log: 
,03-31 16:30:53.091 11128 11200 I jxcore-log: # teardown
03-31 16:30:53.091 11128 11200 I jxcore-log: 
,03-31 16:30:53.746 11128 11200 I jxcore-log: ok 211 must be stopped
03-31 16:30:53.746 11128 11200 I jxcore-log: 
,03-31 16:30:53.751 11128 11200 I jxcore-log: # setup
03-31 16:30:53.751 11128 11200 I jxcore-log: 
,03-31 16:30:53.886 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 16:30:53.886 11128 11200 I jxcore-log: 
,03-31 16:30:53.891 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 16:30:53.891 11128 11200 I jxcore-log: 
,03-31 16:30:53.901 11128 11200 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 16:30:53.901 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 16:30:53.901 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 16:30:53.901 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 16:30:53.901 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 16:30:53.901 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 16:30:53.901 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 16:30:53.901 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 16:30:53.901 11128 11200 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 16:30:53.906 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 16:30:53.906 11128 11200 I jxcore-log: 
,03-31 16:30:53.911 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 16:30:53.911 11128 11200 I jxcore-log: 
,03-31 16:30:53.916 11128 11200 I jxcore-log: # 54. thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
03-31 16:30:53.916 11128 11200 I jxcore-log: 
,03-31 16:30:53.916 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 16:30:53.916 11128 11200 I jxcore-log: 
,03-31 16:30:54.191 11128 11200 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 16:30:54.191 11128 11200 I jxcore-log: 
,03-31 16:30:54.201 11128 11200 I jxcore-log: DEBUG createNativeListener: listening 59429
03-31 16:30:54.201 11128 11200 I jxcore-log: 
,03-31 16:30:54.206 11128 11200 I jxcore-log: INFO thaliMobileNativeWrapper: routerPortConnectionFailed - {"routerPort":55730,"error":{}}
03-31 16:30:54.206 11128 11200 I jxcore-log: 
,03-31 16:30:54.211 11128 11200 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 16:30:54.211 11128 11200 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 16:30:54.211 11128 11200 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 16:30:54.216 11128 11200 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 16:30:54.216 11128 11200 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 16:30:54.216 11128 11200 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 16:30:54.226 11128 11200 I jxcore-log: ok 212 failure reason is as expected
03-31 16:30:54.226 11128 11200 I jxcore-log: 
,03-31 16:30:54.231 11128 11200 I jxcore-log: ok 213 error description is as expected
03-31 16:30:54.231 11128 11200 I jxcore-log: 
,03-31 16:30:54.231 11128 11200 I jxcore-log: ok 214 must be stopped
03-31 16:30:54.231 11128 11200 I jxcore-log: 
,03-31 16:30:54.241 11128 11200 I jxcore-log: # teardown
03-31 16:30:54.241 11128 11200 I jxcore-log: 
,03-31 16:30:54.411 11128 11200 I jxcore-log: ok 215 must be stopped
03-31 16:30:54.411 11128 11200 I jxcore-log: 
,03-31 16:30:54.416 11128 11200 I jxcore-log: # setup
03-31 16:30:54.416 11128 11200 I jxcore-log: 
,03-31 16:30:54.606 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 16:30:54.606 11128 11200 I jxcore-log: 
,03-31 16:30:54.616 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 16:30:54.616 11128 11200 I jxcore-log: 
,03-31 16:30:54.621 11128 11200 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 16:30:54.621 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 16:30:54.621 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 16:30:54.621 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 16:30:54.621 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 16:30:54.621 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 16:30:54.621 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 16:30:54.621 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 16:30:54.626 11128 11200 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 16:30:54.631 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 16:30:54.631 11128 11200 I jxcore-log: 
,03-31 16:30:54.636 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 16:30:54.636 11128 11200 I jxcore-log: 
,03-31 16:30:54.641 11128 11200 I jxcore-log: # 55. We repeat failedConnection event when we get it from thaliTcpServersManager
03-31 16:30:54.641 11128 11200 I jxcore-log: 
,03-31 16:30:54.641 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 16:30:54.641 11128 11200 I jxcore-log: 
,03-31 16:30:54.806 11128 11200 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 16:30:54.806 11128 11200 I jxcore-log: 
,03-31 16:30:54.811 11128 11200 I jxcore-log: DEBUG createNativeListener: listening 43950
03-31 16:30:54.811 11128 11200 I jxcore-log: 
,03-31 16:30:54.816 11128 11200 I jxcore-log: ok 216 peerIdentifier matches
03-31 16:30:54.816 11128 11200 I jxcore-log: 
,03-31 16:30:54.816 11128 11200 I jxcore-log: ok 217 error description matches
03-31 16:30:54.816 11128 11200 I jxcore-log: 
,03-31 16:30:54.821 11128 11200 I jxcore-log: # teardown
03-31 16:30:54.821 11128 11200 I jxcore-log: 
,03-31 16:30:54.951 11128 11200 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 16:30:54.956 11128 11200 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-31 16:30:54.956 11128 11200 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 16:30:54.961 11128 11200 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 16:30:54.966 11128 11200 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-31 16:30:54.966 11128 11200 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 16:30:54.981 11128 11200 I jxcore-log: ok 218 must be stopped
03-31 16:30:54.981 11128 11200 I jxcore-log: 
,03-31 16:30:54.996 11128 11200 I jxcore-log: # setup
03-31 16:30:54.996 11128 11200 I jxcore-log: 
,03-31 16:30:55.026  3440  4737 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-31 16:30:55.026  3440  4737 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 16:30:55.026  3440  4737 D BatteryService: online:4, current avg:33, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:41
03-31 16:30:55.026  3440  4737 D BatteryService: stay LED for fully charged
03-31 16:30:55.026  3440  3440 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 16:30:55.026  3440  3440 I MotionRecognitionService: Plugged
03-31 16:30:55.026  3440  3440 D MotionRecognitionService:   cableConnection= 1
03-31 16:30:55.026  3440  3440 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 16:30:55.026  3440  3440 D MotionRecognitionService: skip setTransmitPower. 
,03-31 16:30:55.031  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 16:30:55.031  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 16:30:55.031  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 16:30:55.036  5838  5838 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 16:30:55.036  5838  5954 D HeadsetStateMachine: Disconnected process message: 10
,03-31 16:30:55.051  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 16:30:55.051  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 16:30:55.051  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 16:30:55.051  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 16:30:55.106 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native,
03-31 16:30:55.106 11128 11200 I jxcore-log: 
,03-31 16:30:55.116 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 16:30:55.116 11128 11200 I jxcore-log: 
,03-31 16:30:55.126 11128 11200 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 16:30:55.126 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 16:30:55.126 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 16:30:55.126 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 16:30:55.126 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 16:30:55.126 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 16:30:55.126 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 16:30:55.126 11128 11200 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 16:30:55.131 11128 11200 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 16:30:55.136 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 16:30:55.136 11128 11200 I jxcore-log: 
,03-31 16:30:55.141 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 16:30:55.141 11128 11200 I jxcore-log: 
,03-31 16:30:55.151 11128 11200 I jxcore-log: # 56. we successfully receive and replay discoveryAdvertisingStateUpdate
03-31 16:30:55.151 11128 11200 I jxcore-log: 
,03-31 16:30:55.156 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 16:30:55.156 11128 11200 I jxcore-log: 
,03-31 16:30:55.291 11128 11200 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 16:30:55.291 11128 11200 I jxcore-log: 
,03-31 16:30:55.296 11128 11200 I jxcore-log: DEBUG createNativeListener: listening 34710
03-31 16:30:55.296 11128 11200 I jxcore-log: 
,03-31 16:30:55.301 11128 11200 I io.jxcore.node.ConnectionHelper: start: Port number: 35363, start advertisements: false
,03-31 16:30:55.306 11128 11200 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 16:30:55.306 11128 11200 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 16:30:55.306 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-31 16:30:55.306 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-31 16:30:55.311 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-31 16:30:55.311 11128 11200 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 16:30:55.311  5838  5848 D BtGatt.GattService: registerClient() - UUID=10c528e6-16ff-4c27-8993-f27fef58cd17
,03-31 16:30:55.356  5838  5944 D BtGatt.GattService: onClientRegistered() - UUID=10c528e6-16ff-4c27-8993-f27fef58cd17, clientIf=6
,03-31 16:30:55.356 11128 11138 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-31 16:30:55.356  5838  9004 D BtGatt.GattService: start scan with filters
,03-31 16:30:55.366  5838  9004 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 84
,03-31 16:30:55.366 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 16:30:55.366 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 16:30:55.366 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-31 16:30:55.366 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 16:30:55.366 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 16:30:55.366  5838  5952 D BtGatt.ScanManager: handling starting scan
03-31 16:30:55.366  5838  5952 D BtGatt.ScanManager: isFilteringSupported
03-31 16:30:55.366  5838  5952 D BluetoothAdapter: setting StandAloneBleMode
03-31 16:30:55.366 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-31 16:30:55.366 11128 11128 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-31 16:30:55.366 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
03-31 16:30:55.366 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 16:30:55.366 11128 11200 I io.jxcore.node.ConnectionHelper: start: OK
03-31 16:30:55.366 11128 11128 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 16:30:55.371 11128 11128 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 16:30:55.371 11128 11128 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-31 16:30:55.371 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 16:30:55.371 11128 11200 I jxcore-log: 
,03-31 16:30:55.371 11128 11200 I jxcore-log: ok 219 discoveryActive matches
03-31 16:30:55.371 11128 11200 I jxcore-log: 
,03-31 16:30:55.371 11128 11200 I jxcore-log: ok 220 advertisingActive matches
03-31 16:30:55.371 11128 11200 I jxcore-log: 
,03-31 16:30:55.376  5838  5944 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,03-31 16:30:55.376 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 16:30:55.376 11128 11200 I jxcore-log: 
03-31 16:30:55.376  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 16:30:55.376  5838  5952 D BtGatt.ScanManager: allow scan with filters
03-31 16:30:55.376  5838  5952 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-31 16:30:55.376  5838  5952 D BtGatt.ScanManager: set filter index= 9 for clientIf= 6
,03-31 16:30:55.376 11128 11200 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-31 16:30:55.376  5838  5944 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,03-31 16:30:55.376 11128 11200 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
03-31 16:30:55.376  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 16:30:55.376 11128 11200 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,03-31 16:30:55.376 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-31 16:30:55.376 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-31 16:30:55.376 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-31 16:30:55.376 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-31 16:30:55.376  5838  5952 D BtGatt.ScanManager: Starting BLE batch scan
03-31 16:30:55.376 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-31 16:30:55.376 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-31 16:30:55.376  5838  5952 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-31 16:30:55.381  5838  5848 D BtGatt.GattService: stopScan() - queue size =1
,03-31 16:30:55.381  5838  5944 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-31 16:30:55.381  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 16:30:55.381  5838  9004 D BtGatt.GattService: unregisterClient() - clientIf=6
03-31 16:30:55.381 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 16:30:55.381 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 16:30:55.381 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-31 16:30:55.381 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,03-31 16:30:55.381 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-31 16:30:55.381 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 16:30:55.381  5838  5944 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-31 16:30:55.381  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 16:30:55.381 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 16:30:55.381 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 16:30:55.381 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-31 16:30:55.381 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-31 16:30:55.381 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 16:30:55.381 11128 11128 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 16:30:55.381 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 16:30:55.381 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-31 16:30:55.386  5838  5952 D BtGatt.ScanManager: filter size is 1
03-31 16:30:55.386  5838  5952 D BtGatt.ScanManager: delete FilterIndex - 9
03-31 16:30:55.386  5838  5944 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-31 16:30:55.386  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 16:30:55.386  5838  5952 D BtGatt.ScanManager: stopping BLe Batch
,03-31 16:30:55.391 11128 11128 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-31 16:30:55.391  5838  5944 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,03-31 16:30:55.391  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 16:30:55.391  5838  5952 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-31 16:30:55.391  5838  5944 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-31 16:30:55.391  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 16:30:55.396 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-31 16:30:55.396 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 16:30:55.396 11128 11128 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 16:30:55.396 11128 11128 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-31 16:30:55.396 11128 11128 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 16:30:55.396 11128 11128 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 16:30:55.396 11128 11128 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 16:30:55.401 11128 11200 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 16:30:55.401 11128 11200 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 16:30:55.401 11128 11200 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 16:30:55.401 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 16:30:55.401 11128 11200 I jxcore-log: 
,03-31 16:30:55.401 11128 11200 I jxcore-log: ok 221 discoveryActive matches
03-31 16:30:55.401 11128 11200 I jxcore-log: ,
03-31 16:30:55.401 11128 11200 I jxcore-log: ok 222 advertisingActive matches
03-31 16:30:55.401 11128 11200 I jxcore-log: 
,03-31 16:30:55.406 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 16:30:55.406 11128 11200 I jxcore-log: 
,03-31 16:30:55.416 11128 11200 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 16:30:55.416 11128 11200 I jxcore-log: 
,03-31 16:30:55.421 11128 11200 I jxcore-log: DEBUG createNativeListener: listening 59116
03-31 16:30:55.421 11128 11200 I jxcore-log: 
,03-31 16:30:55.426 11128 11200 I io.jxcore.node.ConnectionHelper: start: Port number: 59116, start advertisements: true
,03-31 16:30:55.426 11128 11200 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 16:30:55.426 11128 11200 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-31 16:30:55.426 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-31 16:30:55.426 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-31 16:30:55.426 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-31 16:30:55.431 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 16:30:55.431 11128 11200 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 16:30:55.431  5838  5850 D BtGatt.GattService: registerClient() - UUID=81e710e4-41b7-4e9f-ae23-397a7349c798
,03-31 16:30:55.476  5838  5944 D BtGatt.GattService: onClientRegistered() - UUID=81e710e4-41b7-4e9f-ae23-397a7349c798, clientIf=6
,03-31 16:30:55.476 11128 11138 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-31 16:30:55.476  5838  5955 D BtGatt.GattService: start scan with filters
,03-31 16:30:55.511  5838  5955 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 85
,03-31 16:30:55.516 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-31 16:30:55.516 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 16:30:55.516 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,03-31 16:30:55.516 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,03-31 16:30:55.516 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 16:30:55.516  5838  5952 D BtGatt.ScanManager: handling starting scan
03-31 16:30:55.516  5838  5952 D BtGatt.ScanManager: isFilteringSupported
,03-31 16:30:55.516  5838  5952 D BluetoothAdapter: setting StandAloneBleMode
,03-31 16:30:55.516 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 16:30:55.516 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-31 16:30:55.516 11128 11200 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-31 16:30:55.516 11128 11128 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-31 16:30:55.516 11128 11200 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-31 16:30:55.516 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 16:30:55.516 11128 11200 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-31 16:30:55.526  5838  5944 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-31 16:30:55.526  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 16:30:55.526  5838  5952 D BtGatt.ScanManager: allow scan with filters
03-31 16:30:55.526  5838  5952 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-31 16:30:55.526  5838  5952 D BtGatt.ScanManager: set filter index= 10 for clientIf= 6
,03-31 16:30:55.531  5838  5944 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-31 16:30:55.531  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 16:30:55.531  5838  5952 D BtGatt.ScanManager: Starting BLE batch scan
03-31 16:30:55.531  5838  5952 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-31 16:30:55.536  5838  5944 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-31 16:30:55.536  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 16:30:55.536  5838  5955 D BtGatt.GattService: registerClient() - UUID=75367ffc-62cd-4959-8176-13acb3fe5c66
03-31 16:30:55.541  5838  5944 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-31 16:30:55.541  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 16:30:55.581  5838  5944 D BtGatt.GattService: onClientRegistered() - UUID=75367ffc-62cd-4959-8176-13acb3fe5c66, clientIf=7
03-31 16:30:55.581 11128 11777 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-31 16:30:55.601  5838  5848 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 67
,03-31 16:30:55.601  5838  5951 D BtGatt.AdvertiseManager: message : 0
,03-31 16:30:55.606  5838  5951 D BtGatt.AdvertiseManager: number of adv instance running0
03-31 16:30:55.606  5838  5951 D BtGatt.AdvertiseManager: size of list is =0
,03-31 16:30:55.611  5838  5951 D BtGatt.AdvertiseManager: starting advertising
,03-31 16:30:55.611  5838  5951 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-31 16:30:55.621  5838  5944 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-31 16:30:55.626  5838  5951 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 16:30:55.631  5838  5944 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-31 16:30:55.631  5838  5951 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,03-31 16:30:55.636  5838  5951 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,03-31 16:30:55.636 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-31 16:30:55.636 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-31 16:30:55.651 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-31 16:30:55.651 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 16:30:55.651 11128 11200 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-31 16:30:55.651 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-31 16:30:55.656 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...,
03-31 16:30:55.656 11128 11200 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true,
03-31 16:30:55.656 11128 11200 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING,
03-31 16:30:55.656 11128 11200 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-31 16:30:55.656 11128 11200 I io.jxcore.node.ConnectionHelper: start: OK
03-31 16:30:55.656 11128 11128 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,03-31 16:30:55.661 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 16:30:55.661 11128 11128 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,03-31 16:30:55.661 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,03-31 16:30:55.661 11128 11128 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
,03-31 16:30:55.661 11128 11128 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
,03-31 16:30:55.661 11128 11128 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 16:30:55.661 11128 11128 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 16:30:55.661 11128 11128 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-31 16:30:55.661 11128 11128 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-31 16:30:55.661 11128 11128 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-31 16:30:55.661 11128 11128 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 16:30:55.666 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 16:30:55.666 11128 11200 I jxcore-log: 
,03-31 16:30:55.681 11128 12151 D BluetoothSocket: bindListen(): myUserId = 0
03-31 16:30:55.681 11128 12151 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-31 16:30:55.691 11128 12151 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[118]}
03-31 16:30:55.691 11128 12151 D BluetoothSocket: bindListen(), new LocalSocket 
03-31 16:30:55.691 11128 12151 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-31 16:30:55.691 11128 12151 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1ab1c518
03-31 16:30:55.691 11128 12151 D BluetoothSocket: channel: 6
03-31 16:30:55.691 11128 12151 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-31 16:30:55.726 11128 11200 I jxcore-log: not ok 223 discoveryActive matches
03-31 16:30:55.726 11128 11200 I jxcore-log: 
,03-31 16:30:55.726 11128 11200 I jxcore-log:   ---
03-31 16:30:55.726 11128 11200 I jxcore-log: 
,03-31 16:30:55.731 11128 11200 I jxcore-log:     operator: equal
03-31 16:30:55.731 11128 11200 I jxcore-log: 
,03-31 16:30:55.731 11128 11200 I jxcore-log:     expected: false
03-31 16:30:55.731 11128 11200 I jxcore-log: 
,03-31 16:30:55.736 11128 11200 I jxcore-log:     actual:   true
03-31 16:30:55.736 11128 11200 I jxcore-log: 
,03-31 16:30:55.736 11128 11200 I jxcore-log:   ...
03-31 16:30:55.736 11128 11200 I jxcore-log: 
,03-31 16:30:55.746  3440  6049 D SSRM:n  : SIOP:: AP = 270, PST = 271 (W:14), CUR = 33, LCD = 0
,03-31 16:30:55.751 11128 11200 I jxcore-log: not ok 224 advertisingActive matches
03-31 16:30:55.751 11128 11200 I jxcore-log: 
,03-31 16:30:55.751 11128 11200 I jxcore-log:   ---
03-31 16:30:55.751 11128 11200 I jxcore-log: 
,03-31 16:30:55.751 11128 11200 I jxcore-log:     operator: equal
03-31 16:30:55.751 11128 11200 I jxcore-log: 
,03-31 16:30:55.751 11128 11200 I jxcore-log:     expected: true
03-31 16:30:55.751 11128 11200 I jxcore-log: 
,03-31 16:30:55.756 11128 11200 I jxcore-log:     actual:   false
03-31 16:30:55.756 11128 11200 I jxcore-log: 
,03-31 16:30:55.756 11128 11200 I jxcore-log:   ...
03-31 16:30:55.756 11128 11200 I jxcore-log: 
,03-31 16:30:55.756 11128 11200 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 16:30:55.756 11128 11200 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
,03-31 16:30:55.761 11128 11200 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-31 16:30:55.761 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,03-31 16:30:55.761 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-31 16:30:55.761 11128 11200 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@104e6b71, channel: 6, state: LISTENING
,03-31 16:30:55.761 11128 11200 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@104e6b71, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1ab1c518, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@20865d56mSocket: android.net.LocalSocket@102a21d7 impl:android.net.LocalSocketImpl@3b8a1ac4 fd:FileDescriptor[118]
03-31 16:30:55.761 11128 11200 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@102a21d7 impl:android.net.LocalSocketImpl@3b8a1ac4 fd:FileDescriptor[118]
,03-31 16:30:55.761 11128 11200 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-31 16:30:55.761 11128 12151 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-31 16:30:55.761 11128 12151 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-31 16:30:55.761 11128 12151 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-31 16:30:55.766 11128 11128 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-31 16:30:55.766 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-31 16:30:55.766 11128 11128 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-31 16:30:55.766 11128 11128 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-31 16:30:55.766 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-31 16:30:55.766 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-31 16:30:55.766 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-31 16:30:55.766 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-31 16:30:55.766 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-31 16:30:55.771  5838  5850 D BtGatt.GattService: stopScan() - queue size =1,
03-31 16:30:55.771  5838  5952 D BtGatt.ScanManager: filter size is 1
03-31 16:30:55.771  5838  5952 D BtGatt.ScanManager: delete FilterIndex - 10
,03-31 16:30:55.771  5838  5944 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,03-31 16:30:55.771  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
03-31 16:30:55.771  5838  5952 D BtGatt.ScanManager: stopping BLe Batch
03-31 16:30:55.776  5838  5944 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0,
03-31 16:30:55.776  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,03-31 16:30:55.776  5838  5952 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-31 16:30:55.776  5838  5944 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,03-31 16:30:55.776  5838  5944 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
03-31 16:30:55.781  5838  5955 D BtGatt.GattService: unregisterClient() - clientIf=6,
,03-31 16:30:55.781 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
03-31 16:30:55.781 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED,
,03-31 16:30:55.781 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-31 16:30:55.781 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING],
,03-31 16:30:55.781 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
,03-31 16:30:55.781 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-31 16:30:55.781 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-31 16:30:55.786  5838  5951 D BtGatt.AdvertiseManager: message : 1
,03-31 16:30:55.786  5838  5951 D BtGatt.AdvertiseManager: stop advertise for client 7
03-31 16:30:55.786  5838  5951 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-31 16:30:55.786  5838  5951 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-31 16:30:55.791  5838  5944 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0,
03-31 16:30:55.791  5838  5944 D BtGatt.GattService: Client app is not null!,
03-31 16:30:55.791  5838  5850 D BtGatt.GattService: unregisterClient() - clientIf=7
,03-31 16:30:55.791 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 16:30:55.791 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-31 16:30:55.791 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-31 16:30:55.791 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-31 16:30:55.791 11128 11200 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-31 16:30:55.791 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-31 16:30:55.791 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 16:30:55.791 11128 11200 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-31 16:30:55.796 11128 11200 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-31 16:30:55.796 11128 11200 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 16:30:55.796 11128 11128 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 16:30:55.796 11128 11128 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 16:30:55.796 11128 11128 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 16:30:55.796 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 16:30:55.796 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-31 16:30:55.801 11128 11128 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-31 16:30:55.806 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-31 16:30:55.806 11128 11128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 16:30:55.806 11128 11128 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 16:30:55.811 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 16:30:55.811 11128 11200 I jxcore-log: 
,03-31 16:30:55.816 11128 11128 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 16:30:55.816 11128 11128 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 16:30:55.816 11128 11128 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 16:30:55.816 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-31 16:30:55.816 11128 11200 I jxcore-log: 
03-31 16:30:55.821 11128 11200 I jxcore-log: not ok 225 discoveryActive matches
03-31 16:30:55.821 11128 11200 I jxcore-log: 
03-31 16:30:55.821 11128 11200 I jxcore-log:   ---
03-31 16:30:55.821 11128 11200 I jxcore-log: 
03-31 16:30:55.821 11128 11200 I jxcore-log:     operator: equal
03-31 16:30:55.821 11128 11200 I jxcore-log: 
,03-31 16:30:55.821 11128 11200 I jxcore-log:     expected: false
03-31 16:30:55.821 11128 11200 I jxcore-log: 
03-31 16:30:55.821 11128 11200 I jxcore-log:     actual:   true
03-31 16:30:55.821 11128 11200 I jxcore-log: 
03-31 16:30:55.821 11128 11200 I jxcore-log:   ...
03-31 16:30:55.821 11128 11200 I jxcore-log: 
,03-31 16:30:55.826 11128 11200 I jxcore-log: not ok 226 advertisingActive matches
03-31 16:30:55.826 11128 11200 I jxcore-log: 
,03-31 16:30:55.826 11128 11200 I jxcore-log:   ---
03-31 16:30:55.826 11128 11200 I jxcore-log: 
03-31 16:30:55.826 11128 11200 I jxcore-log:     operator: equal
03-31 16:30:55.826 11128 11200 I jxcore-log: 
03-31 16:30:55.826 11128 11200 I jxcore-log:     expected: false
03-31 16:30:55.826 11128 11200 I jxcore-log: 
03-31 16:30:55.826 11128 11200 I jxcore-log:     actual:   true
03-31 16:30:55.826 11128 11200 I jxcore-log: 
03-31 16:30:55.826 11128 11200 I jxcore-log:   ...
03-31 16:30:55.826 11128 11200 I jxcore-log: 
,03-31 16:30:55.826 11128 11200 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 16:30:55.826 11128 11200 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 16:30:55.826 11128 11200 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 16:30:55.831 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-31 16:30:55.831 11128 11200 I jxcore-log: 
,03-31 16:30:55.831 11128 11200 I jxcore-log: ok 227 discoveryActive matches
03-31 16:30:55.831 11128 11200 I jxcore-log: 
,03-31 16:30:55.836 11128 11200 I jxcore-log: not ok 228 advertisingActive matches
03-31 16:30:55.836 11128 11200 I jxcore-log: 
,03-31 16:30:55.836 11128 11200 I jxcore-log:   ---
03-31 16:30:55.836 11128 11200 I jxcore-log: 
03-31 16:30:55.836 11128 11200 I jxcore-log:     operator: equal
03-31 16:30:55.836 11128 11200 I jxcore-log: 
03-31 16:30:55.836 11128 11200 I jxcore-log:     expected: false
03-31 16:30:55.836 11128 11200 I jxcore-log: 
03-31 16:30:55.836 11128 11200 I jxcore-log:     actual:   true
03-31 16:30:55.836 11128 11200 I jxcore-log: 
03-31 16:30:55.836 11128 11200 I jxcore-log:   ...
03-31 16:30:55.836 11128 11200 I jxcore-log: 
,03-31 16:30:55.836 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 16:30:55.836 11128 11200 I jxcore-log: 
,03-31 16:30:55.841 11128 11200 I jxcore-log: ok 229 discoveryActive matches
03-31 16:30:55.841 11128 11200 I jxcore-log: 
,03-31 16:30:55.841 11128 11200 I jxcore-log: ok 230 advertisingActive matches
03-31 16:30:55.841 11128 11200 I jxcore-log: 
,03-31 16:30:55.841 11128 11200 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 16:30:55.841 11128 11200 I jxcore-log: 
,03-31 16:30:55.856 11128 11200 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 16:30:55.856 11128 11200 I jxcore-log: 
,03-31 16:30:55.856 11128 11200 I jxcore-log: DEBUG createNativeListener: listening 41064
03-31 16:30:55.856 11128 11200 I jxcore-log: 
,03-31 16:30:55.871 11128 11200 E jxcore-log: Trace: [Error: Call Stop!]
03-31 16:30:55.871 11128 11200 E jxcore-log:     at $3.prototype.trace@console.js:139:8
03-31 16:30:55.871 11128 11200 E jxcore-log:     at @/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:38:3
03-31 16:30:55.871 11128 11200 E jxcore-log:     at emit@events.js:98:1
03-31 16:30:55.871 11128 11200 E jxcore-log:     at handlers.reject/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/thali/node_modules/lie/lib/index.js:128:11
03-31 16:30:55.871 11128 11200 E jxcore-log:     at nextTick@/data/data/com.test.thalitest/files/www/jxcore/node_modules/immediate/lib/index.js:61:7
03-31 16:30:55.871 11128 11200 E jxcore-log:     at $0a@node.js:917:1
03-31 16:30:55.871 11128 11200 E jxcore-log: 
,03-31 16:30:55.876 11128 11200 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
03-31 16:30:55.876 11128 11200 I jxcore-log: 
,03-31 16:30:55.876 11128 11200 I jxcore-log: # teardown
03-31 16:30:55.876 11128 11200 I jxcore-log: 
,03-31 16:30:56.231 12162 12162 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,03-31 16:30:56.236 12162 12162 D AndroidRuntime: CheckJNI is OFF
,03-31 16:30:56.236 12162 12162 D AndroidRuntime: readGMSProperty: start
03-31 16:30:56.236 12162 12162 D AndroidRuntime: readGMSProperty: already setted!!
03-31 16:30:56.236 12162 12162 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-31 16:30:56.236 12162 12162 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-31 16:30:56.236 12162 12162 D AndroidRuntime: readGMSProperty: end
03-31 16:30:56.236 12162 12162 D AndroidRuntime: addProductProperty: start
,03-31 16:30:56.321 12162 12162 E AffinityControl: AffinityControl: registerfunction enter
,03-31 16:30:56.336 12162 12162 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,03-31 16:30:56.346  3440  3828 D PackageManager: START PACKAGE DELETE: observer{320776157}
03-31 16:30:56.346  3440  3828 D PackageManager: pkg{<packageName>}
03-31 16:30:56.346  3440  3828 D PackageManager: user{0}
03-31 16:30:56.346  3440  3828 D PackageManager: caller{2000}
03-31 16:30:56.346  3440  3828 D PackageManager: flags{2}
03-31 16:30:56.346  3440  3828 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
03-31 16:30:56.346  3440  3828 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
03-31 16:30:56.346  3440  3828 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
03-31 16:30:56.346  3440  3828 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
03-31 16:30:56.351  3440  3591 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
03-31 16:30:56.346  3440  3828 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
03-31 16:30:56.351  3440  3591 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
03-31 16:30:56.351  3440  3591 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
03-31 16:30:56.351  3440  3591 D ApplicationPolicy: getApplicationUninstallationEnabled
03-31 16:30:56.351  3440  3591 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,03-31 16:30:56.351  3440  3591 D PackageManager: !@killApplicatoin: 10011, uninstall pkg
,03-31 16:30:56.356  3440  3575 I ActivityManager: Force stopping com.test.thalitest appid=10011 user=-1: uninstall pkg
,03-31 16:30:56.356  3440  3575 I ActivityManager: Killing 11128:com.test.thalitest/u0a11 (adj 0): stop com.test.thalitest cause uninstall pkg
,03-31 16:30:56.381  3440  3575 I ActivityManager:   Force finishing activity 3 ActivityRecord{2cc3ede6 u0 com.test.thalitest/.MainActivity t42}
,03-31 16:30:56.386  3440  3575 W ActivityManager: mDVFSHelper.acquire()
,03-31 16:30:56.476  3440  3591 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
,03-31 16:30:56.481  3440  3591 W PackageSettings: Skipping PackageSetting{21f0d3d0 com.example.hello/10691} due to missing metadata
,03-31 16:30:56.501  3440  4048 I WindowState: WIN DEATH: Window{361bfe34 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}
,03-31 16:30:56.501  2860  3900 I SurfaceFlinger: id=15 Removed NainActivit (6/8)
,03-31 16:30:56.501  2860  3903 I SurfaceFlinger: id=15 Removed NainActivit (-2/8)
,03-31 16:30:56.506  3440  4048 D InputDispatcher: Focus left window: 11128
,03-31 16:30:56.506  3440  4048 D MultiWindowConverter: dismissGuide() : Before attaching the guide view, mForceDismissGuide : false
,03-31 16:30:56.506  3440  3591 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,03-31 16:30:56.511  3440  3583 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3440 uid:1000
03-31 16:30:56.511  3440  3583 D PointerIcon: setMouseCustomIcon IconType is same.101
03-31 16:30:56.511  3440  3583 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3440 uid:1000
03-31 16:30:56.511  3440  3583 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,03-31 16:30:56.516  3440  3575 D PowerManagerService: setKeyboardVisibility: false
,03-31 16:30:56.516  3440  3575 I ActivityManager: Skip updateThumbnail for r=ActivityRecord{40084aa u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t40}
,03-31 16:30:56.536  3440  3591 I ActivityManager: Force stopping com.test.thalitest appid=10011 user=0: pkg removed
,03-31 16:30:56.541  3440  3591 I ActivityManager:   Force finishing activity 3 ActivityRecord{2cc3ede6 u0 com.test.thalitest/.MainActivity t42 f}
03-31 16:30:56.541  3440  3591 W ActivityManager: Duplicate finish request for ActivityRecord{2cc3ede6 u0 com.test.thalitest/.MainActivity t42 f}
,03-31 16:30:56.576  3440  3591 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-31 16:30:56.576  3923  3923 I art     : Explicit concurrent mark sweep GC freed 1697(88KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 473us total 18.186ms
,03-31 16:30:56.586  9055  9055 I art     : Explicit concurrent mark sweep GC freed 2670(151KB) AllocSpace objects, 0(0B) LOS objects, 69% free, 1770KB/5MB, paused 7.391ms total 31.281ms
,03-31 16:30:56.586  6534  6534 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(433/onResume)] 
,03-31 16:30:56.586  3440  3690 D TaskPersister: removeObsoleteFile: deleting file=42_task.xml
03-31 16:30:56.586  3440  3690 D TaskPersister: removeObsoleteFile: deleting file=42_task_thumbnail.png
03-31 16:30:56.591  3440  3575 D InputDispatcher: Focused application released
,03-31 16:30:56.601  6534  6534 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5412/IlIlllIlllllIlIllllI)] Get Postpone Count : 0
,03-31 16:30:56.616  6534  6534 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5134/lIIIIIIIlllllllIIlll)] Get Priority : 0
,03-31 16:30:56.621  3440  3631 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-31 16:30:56.621  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.PACKAGE_REMOVED
,03-31 16:30:56.626  4576  4576 I art     : Explicit concurrent mark sweep GC freed 3041(188KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 8MB/11MB, paused 1.589ms total 82.207ms
03-31 16:30:56.626  4509  4509 E SamsungIME: mOCRHelper is null
,03-31 16:30:56.626  4131  4131 I art     : Explicit concurrent mark sweep GC freed 23249(1279KB) AllocSpace objects, 2(32KB) LOS objects, 25% free, 6MB/8MB, paused 1.670ms total 70.467ms
,03-31 16:30:56.631  4334  4718 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,03-31 16:30:56.631  6534  6534 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5434/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,03-31 16:30:56.636  6534  6534 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(443/onResume)] Postpone Count : 0
,03-31 16:30:56.641  4049  4049 I art     : Explicit concurrent mark sweep GC freed 16088(923KB) AllocSpace objects, 8(1218KB) LOS objects, 12% free, 56MB/64MB, paused 395us total 67.886ms
03-31 16:30:56.641 10691 10691 D LWLocationManager: getDeviceLocationId :  id = -100
03-31 16:30:56.641 10691 10691 D LocationWidgetApplication: getLastUiLocationId() : mLastUiLocationId = -100
,03-31 16:30:56.646  6534  6534 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5475/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,03-31 16:30:56.656  3440  3651 V NetworkStats: removeUidsLocked() for UIDs [10011]
03-31 16:30:56.656  3440  3651 D NtpTrustedTime: currentTimeMillis() cache hit
03-31 16:30:56.656  3440  3651 V NetworkStats: performPollLocked(flags=0x3)
,03-31 16:30:56.661  3440  3651 V NetworkStats: performPollLocked() took 7ms
,03-31 16:30:56.661  3440  3651 D NtpTrustedTime: currentTimeMillis() cache hit
,03-31 16:30:56.666  3440  3575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 16:30:56.666  3440  3575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 16:30:56.666  3440  3575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 16:30:56.666  3440  3575 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-31 16:30:56.676  5596  5614 W ResourceType: For resource 0x7f020570, entry index(1392) is beyond type entryCount(787)
03-31 16:30:56.676  5596  5614 W ResourceType: Failure getting entry for 0x7f020570 (t=1 e=1392) (error -75)
,03-31 16:30:56.681 12174 12174 E Zygote  : MountEmulatedStorage()
03-31 16:30:56.681 12174 12174 E Zygote  : v2
03-31 16:30:56.681 12174 12174 I libpersona: KNOX_SDCARD checking this for 10063
03-31 16:30:56.681  3440  3568 D EnterpriseDeviceManagerService: Package has changed for user 0
03-31 16:30:56.681 12174 12174 I libpersona: KNOX_SDCARD not a persona
03-31 16:30:56.686  3440  3568 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
03-31 16:30:56.686  3440  3568 W TextServicesManagerService: no available spell checker services found
,03-31 16:30:56.686 12174 12174 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
,03-31 16:30:56.686  3440  3575 I ActivityManager: Start proc 12174:com.samsung.android.app.vrsetupwizardstub/u0a63 for broadcast-3 com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver
,03-31 16:30:56.691 12174 12174 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
03-31 16:30:56.691 12174 12174 E Zygote  : accessInfo : 0
,03-31 16:30:56.691  6534  6534 I DBG_DM  : [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,03-31 16:30:56.691 12174 12174 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-31 16:30:56.691  6534  6534 I DBG_DM  : [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(327/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
03-31 16:30:56.691  3440  3652 D NtpTrustedTime: currentTimeMillis() cache hit
03-31 16:30:56.691  3440  3652 D NtpTrustedTime: currentTimeMillis() cache hit
,03-31 16:30:56.701  4017  4017 D RegisteredServicesCache: empty dynamic service
,03-31 16:30:56.711  6534  6534 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5134/lIIIIIIIlllllllIIlll)] Get Priority : 0
,03-31 16:30:56.716  4017  4017 D RegisteredComponentCache: Collect Tech packages for Knox
,03-31 16:30:56.726 12174 12174 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-31 16:30:56.726  3440  4737 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
03-31 16:30:56.726  3440  3440 I art     : Explicit concurrent mark sweep GC freed 32782(2MB) AllocSpace objects, 15(240KB) LOS objects, 33% free, 29MB/44MB, paused 2.665ms total 153.852ms
03-31 16:30:56.726  3440  4737 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
03-31 16:30:56.726  3440  3591 I art     : WaitForGcToComplete blocked for 141.320ms for cause Explicit
,03-31 16:30:56.731 12174 12174 D ActivityThread: Added TimaKeyStore provider
,03-31 16:30:56.731  6534  6534 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5412/IlIlllIlllllIlIllllI)] Get Postpone Count : 0
,03-31 16:30:56.736  6534  6534 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5054/IIlllIlIIlIllIlllIll)] Get Force status : 0
,03-31 16:30:56.741  3440  3965 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{203b3638 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{2b0b5611 12174:com.samsung.android.app.vrsetupwizardstub/u0a63}
03-31 16:30:56.741  6534  6534 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5434/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,03-31 16:30:56.746  6534  6534 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(537/llIIIIlllllIIllIIllI)] Check Force Install : false
03-31 16:30:56.746  6534  6534 I DBG_DM  : [llIIlIIlIllIllIlllII(337/IllIlIIIIlIIlIIIllIl)] 
,03-31 16:30:56.746  6534  6534 I DBG_DM  : [llIIlIIlIllIllIlllII(343/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
,03-31 16:30:56.746  3440  3733 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,03-31 16:30:56.751  3440  3733 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-31 16:30:56.751  3440  3733 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-31 16:30:56.751  6534  6534 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(425/onPause)] 
,03-31 16:30:56.756  2860  2860 I SurfaceFlinger: id=16 createSurf (1440x2560),1 flag=404, YUIInstallC
03-31 16:30:56.756  3440  4047 D MultiWindowConverter: dismissGuide() : Before attaching the guide view, mForceDismissGuide : false
,03-31 16:30:56.761  3440  3581 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{3214a421 u0 d0 com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}
,03-31 16:30:56.761  3440  4047 D InputDispatcher: Focus entered window: 6534
,03-31 16:30:56.766  6534  6534 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
03-31 16:30:56.766  3440  3583 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3440 uid:1000
03-31 16:30:56.766  3440  3583 D PointerIcon: setMouseCustomIcon IconType is same.101
03-31 16:30:56.766  3440  3583 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3440 uid:1000
03-31 16:30:56.766  3440  3583 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,03-31 16:30:56.766  6534  9089 D mali_winsys: new_window_surface returns 0x3000,  [1440x2560]-format:1
,03-31 16:30:56.766  6534  6534 V ActivityThread: updateVisibility : ActivityRecord{3db8aeed token=android.os.BinderProxy@3842cbb {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
03-31 16:30:56.766  3440  4421 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-31 16:30:56.771  3440  4421 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 11128 uid 10011
,03-31 16:30:56.776  4509  4509 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,03-31 16:30:56.781  3440  4737 D SecContentProvider2: query(), uri = 11 selection = getMyKnoxAdmin
,03-31 16:30:56.796 12174 12174 D VRSetupWizardStub/PackageIntentReceiver: onReceive()
03-31 16:30:56.796 12174 12174 D VRSetupWizardStub/PackageIntentReceiver: Action Package Remove
03-31 16:30:56.796 12174 12174 D VRSetupWizardStub/PackageIntentReceiver: packagename:com.test.thalitest
,03-31 16:30:56.801  3440  4739 I ActivityManager: Killing 10046:com.google.android.apps.docs/u0a101 (adj 15): emptyCount ##31
,03-31 16:30:56.806  3440  4739 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{203b3638 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{11cd21fa 7117:com.samsung.klmsagent/u0a21}
,03-31 16:30:56.806  7117  7117 I KLMS-2.5.262: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Mar 31 16:30:56 GMT+02:00 2016
,03-31 16:30:56.811  3440  4047 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,03-31 16:30:56.816  6534  6534 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3842cbb time:298234
,03-31 16:30:56.821  7117  7117 I KLMS-2.5.262: : KLMSAbstractReciever(): onReceive().END.
,03-31 16:30:56.821  7117  7117 I KLMS-2.5.262: : KLMSIntentService(): onCreate()
,03-31 16:30:56.826  7117  7117 I KLMS-2.5.262: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,03-31 16:30:56.826  3440  3583 W ActivityManager: mDVFSHelper.release()
03-31 16:30:56.826  3440  3583 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{40084aa u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t40} time:298243
,03-31 16:30:56.826  7117  7117 I KLMS-2.5.262: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
03-31 16:30:56.826  3440  3484 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=14, mSplitNum[1]=26, mSplitNum[2]=38, mBgSplitQueueNum=3 divideNum= 12 r.nextReceiver= 2 receivers.size=50
,03-31 16:30:56.831  3440  3484 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
03-31 16:30:56.831  7117 12192 I KLMS-2.5.262: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.service.KLMSIntentService (has extras) }
03-31 16:30:56.831  7117 12192 D KLMS-2.5.262: : KLMSIntentService(): PACKAGE_REMOVED
03-31 16:30:56.831  7117 12192 I KLMS-2.5.262: : Systemprocess(): listeningToPackageRemoved().START
,03-31 16:30:56.831  7117 12192 I KLMS-2.5.262: : Systemprocess(): listeningToPackageRemoved().packageName: com.test.thalitest
03-31 16:30:56.831  7117 12192 I KLMS-2.5.262: : listeningToPackageRemovedforELM().START
03-31 16:30:56.831  7117 12192 I KLMS-2.5.262: : MDMBridge.getInstance()
03-31 16:30:56.831  7117 12192 I KLMS-2.5.262: : MDMBridge.getAllLicenseInfoFromSDK()
,03-31 16:30:56.831  7117 12192 I KLMS-2.5.262: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,03-31 16:30:56.836  7117 12192 I KLMS-2.5.262: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,03-31 16:30:56.836  3440  3484 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{203b3638 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{173ae7e8 6831:com.samsung.aasaservice/1000}
,03-31 16:30:56.836  6831  6831 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
,03-31 16:30:56.836  7117 12192 I KLMS-2.5.262: : MDMBridge.getAllLicenseInfoFromSDK()
03-31 16:30:56.836  6831  6831 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,03-31 16:30:56.836  6831  6831 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:334)
03-31 16:30:56.836  6831  6831 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
03-31 16:30:56.836  6831  6831 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3509)
03-31 16:30:56.836  6831  6831 W System.err: 	at android.app.ActivityThread.access$1900(ActivityThread.java:197)
03-31 16:30:56.836  6831  6831 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1758)
03-31 16:30:56.836  6831  6831 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-31 16:30:56.836  6831  6831 W System.err: 	at android.os.Looper.loop(Looper.java:145)
03-31 16:30:56.836  6831  6831 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6872)
03-31 16:30:56.836  6831  6831 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
03-31 16:30:56.836  6831  6831 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-31 16:30:56.836  6831  6831 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
03-31 16:30:56.836  6831  6831 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
03-31 16:30:56.836  3440  3568 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,03-31 16:30:56.841  7117 12192 E KLMS-2.5.262: : arr si null
,03-31 16:30:56.846  3440  3575 V BroadcastQueue: [backgroundsplit_0] Process cur broadcast BroadcastRecord{5f0388b u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{354806b8 10143:com.samsung.android.sdk.samsunglink/u0a42}
,03-31 16:30:56.851  3440  3575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 16:30:56.851  3440  3575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 16:30:56.851  3440  3575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 16:30:56.851  3440  3575 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-31 16:30:56.851  7117 12192 D KLMS-2.5.262: : DataSource(): Fetched Data from data base count : 0
,03-31 16:30:56.856  7117 12192 I KLMS-2.5.262: : listeningToPackageRemovedforELM().END
03-31 16:30:56.856  7117 12192 I KLMS-2.5.262: : Systemprocess(): listeningToPackageRemovedforKLM().START
03-31 16:30:56.856  7117 12192 I KLMS-2.5.262: : Systemprocess(): .pkgName: com.test.thalitest
,03-31 16:30:56.866 12193 12193 E Zygote  : MountEmulatedStorage()
03-31 16:30:56.866 12193 12193 I libpersona: KNOX_SDCARD checking this for 1000
03-31 16:30:56.866 12193 12193 E Zygote  : v2
03-31 16:30:56.866 12193 12193 I libpersona: KNOX_SDCARD not a persona
03-31 16:30:56.866 12193 12193 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
03-31 16:30:56.866 12193 12193 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
03-31 16:30:56.871 12193 12193 E Zygote  : accessInfo : 0
03-31 16:30:56.871 12193 12193 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-31 16:30:56.871  3440  3575 I ActivityManager: Start proc 12193:com.samsung.android.sm/1000 for broadcast-4 com.samsung.android.sm/.ui.security.MonitorReceiver
,03-31 16:30:56.876  3440  3575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 16:30:56.876  3440  3575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 16:30:56.876  3440  3575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 16:30:56.876  3440  3575 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-31 16:30:56.886  3440  3591 I art     : Explicit concurrent mark sweep GC freed 9732(830KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 29MB/44MB, paused 2.204ms total 159.632ms
,03-31 16:30:56.901 12207 12207 E Zygote  : MountEmulatedStorage()
,03-31 16:30:56.901 12207 12207 E Zygote  : v2
03-31 16:30:56.901  3440  3575 I ActivityManager: Start proc 12207:com.sec.android.app.popupuireceiver/1000 for broadcast-4 com.sec.android.app.popupuireceiver/.PopupuiReceiver
,03-31 16:30:56.901 12207 12207 I libpersona: KNOX_SDCARD checking this for 1000
03-31 16:30:56.901 12207 12207 I libpersona: KNOX_SDCARD not a persona
,03-31 16:30:56.906 12193 12193 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-31 16:30:56.906 12193 12193 D ActivityThread: Added TimaKeyStore provider
,03-31 16:30:56.906 12207 12207 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
,03-31 16:30:56.906 12207 12207 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
,03-31 16:30:56.911 12207 12207 E Zygote  : accessInfo : 0
,03-31 16:30:56.911 12207 12207 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-31 16:30:56.921  3440  3901 V BroadcastQueue: [backgroundsplit_1] Process cur broadcast BroadcastRecord{17c45a7b u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{284e3098 12193:com.samsung.android.sm/1000}
,03-31 16:30:56.921  3440  3484 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{203b3638 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{35f03930 3440:system/1000}
,03-31 16:30:56.926 10691 12180 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-31 16:30:56.931 12207 12207 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-31 16:30:56.931 12207 12207 D ActivityThread: Added TimaKeyStore provider
,03-31 16:30:56.931  3440  3484 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 16:30:56.931  3440  3484 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 16:30:56.931  3440  3484 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 16:30:56.931  3440  3484 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-31 16:30:56.941 12193 12193 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-31 16:30:56.951 12223 12223 E Zygote  : MountEmulatedStorage()
03-31 16:30:56.951 12223 12223 E Zygote  : v2
03-31 16:30:56.951 12223 12223 I libpersona: KNOX_SDCARD checking this for 10045
03-31 16:30:56.951 12223 12223 I libpersona: KNOX_SDCARD not a persona
,03-31 16:30:56.951 12223 12223 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
,03-31 16:30:56.956 12223 12223 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
03-31 16:30:56.956  3440  3484 I ActivityManager: Start proc 12223:com.osp.app.signin/u0a45 for broadcast-4 com.osp.app.signin/com.msc.sa.selfupdate.SelfUpgradeReceiver
03-31 16:30:56.956 12223 12223 E Zygote  : accessInfo : 0
03-31 16:30:56.956 12223 12223 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,03-31 16:30:56.961  3440  3946 V BroadcastQueue: [backgroundsplit_2] Process cur broadcast BroadcastRecord{29a930f1 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{155974d6 12207:com.sec.android.app.popupuireceiver/1000}
,03-31 16:30:56.981 12223 12223 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-31 16:30:56.981 12223 12223 D ActivityThread: Added TimaKeyStore provider
,03-31 16:30:56.981  2902  2902 I art     : Explicit concurrent mark sweep GC freed 8764(372KB) AllocSpace objects, 0(0B) LOS objects, 72% free, 1529KB/5MB, paused 425us total 25.953ms
,03-31 16:30:56.991  3440  4739 V BroadcastQueue: [backgroundsplit_0] Process cur broadcast BroadcastRecord{5f0388b u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{c342357 12223:com.osp.app.signin/u0a45}
,03-31 16:30:56.991  2902  2902 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 72% free, 1529KB/5MB, paused 307us total 9.730ms
,03-31 16:30:56.996  7117 12192 D KLMS-2.5.262: : KLMSUtility(): IsPackageExistInDevice().mAppInfoList: 322
03-31 16:30:56.996  7117 12192 D KLMS-2.5.262: : KLMSSharedPreferences(): deleteNotificationAppList().pkgName: com.test.thalitest
03-31 16:30:56.996  7117 12192 I KLMS-2.5.262: : KLMSSharedPreferences(): getNotificationAppList(): null
03-31 16:30:56.996  7117 12192 I KLMS-2.5.262: : Systemprocess(): Notification App List is Null. Remove Notification.
,03-31 16:30:57.001 12193 12193 I art     : Explicit concurrent mark sweep GC freed 8428(393KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 1733KB/3MB, paused 361us total 14.505ms
,03-31 16:30:57.001  2902  2902 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 72% free, 1529KB/5MB, paused 247us total 7.932ms
,03-31 16:30:57.001  7117 12192 D KLMS-2.5.262: : DataSource(): Fetched Data from data base count : 0
03-31 16:30:57.001  7117 12192 I KLMS-2.5.262: : Systemprocess(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
03-31 16:30:57.001  7117 12192 I KLMS-2.5.262: : Systemprocess(): listeningToPackageRemovedforKLM().END
03-31 16:30:57.001  7117 12192 I KLMS-2.5.262: : Systemprocess(): listeningToPackageRemoved().END
,03-31 16:30:57.001  7117  7117 I KLMS-2.5.262: : KLMSIntentService(): onDestroy()
,03-31 16:30:57.006 10691 12180 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-31 16:30:57.006 10691 12180 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-31 16:30:57.006 10691 12180 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-31 16:30:57.006 10691 12180 W ResourcesManager: Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,03-31 16:30:57.006 12207 12207 D PopupuiReceiver: onReceive() getAction : android.intent.action.PACKAGE_REMOVED
,03-31 16:30:57.011  3440  3966 D SecContentProvider2: query(), uri = -1 selection = getSealedState
,03-31 16:30:57.011  3440  4724 D SecContentProvider2: query(), uri = 15 selection = getSealedHideNotificationMessages
,03-31 16:30:57.016 12207 12207 I PopupuiReceiver_KNOX: getSealedHideNotificationMessages : 0
,03-31 16:30:57.016  3440  4421 D SecContentProvider2: query(), uri = 15 selection = getCheckCoverPopupState
03-31 16:30:57.016  3440  4048 V BroadcastQueue: [backgroundsplit_1] Process cur broadcast BroadcastRecord{17c45a7b u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{284e3098 12193:com.samsung.android.sm/1000}
,03-31 16:30:57.016 12207 12207 I PopupuiReceiver_KNOX: getCheckCoverPopupState : false
,03-31 16:30:57.016 12207 12207 D PopupuiReceiver: Action package removed
,03-31 16:30:57.021  3440  3568 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-31 16:30:57.021  3440  3568 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-31 16:30:57.021  3440  4048 V BroadcastQueue: [backgroundsplit_1] Process cur broadcast BroadcastRecord{17c45a7b u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{284e3098 12193:com.samsung.android.sm/1000}
,03-31 16:30:57.021  3440  3568 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-31 16:30:57.026  3440  3568 W ResourcesManager: Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,03-31 16:30:57.031  3440  4048 V BroadcastQueue: [backgroundsplit_2] Process cur broadcast BroadcastRecord{29a930f1 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{1bcf2ae 10611:com.samsung.android.snote/u0a160}
,03-31 16:30:57.031 12223 12223 I SA      : [SSP] onCreated
,03-31 16:30:57.036  3440  4048 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 16:30:57.036  3440  4048 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 16:30:57.036  3440  4048 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 16:30:57.036  3440  4048 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-31 16:30:57.046 12193 12238 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
,03-31 16:30:57.051 12241 12241 E Zygote  : MountEmulatedStorage()
03-31 16:30:57.051 12241 12241 E Zygote  : v2
03-31 16:30:57.051 12241 12241 I libpersona: KNOX_SDCARD checking this for 1000
03-31 16:30:57.051 12241 12241 I libpersona: KNOX_SDCARD not a persona
,03-31 16:30:57.051 12241 12241 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
,03-31 16:30:57.051 12241 12241 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
,03-31 16:30:57.056 12241 12241 E Zygote  : accessInfo : 0
03-31 16:30:57.056  3440  4048 I ActivityManager: Start proc 12241:com.samsung.android.app.assistantmenu/1000 for broadcast-4 com.samsung.android.app.assistantmenu/.AssistantMenuReceiver
,03-31 16:30:57.056 12241 12241 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-31 16:30:57.061 10790 10813 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
,03-31 16:30:57.061 10790 10813 D BadgeProvider: sendNotify, [notify] : null
03-31 16:30:57.061 10790 10813 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
03-31 16:30:57.061 10790 10813 D BadgeProvider: update, [uri.query] : null
03-31 16:30:57.061 10790 10813 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-31 16:30:57.061 10790 10813 D BadgeProvider: update, [UpdateCount] : 1
03-31 16:30:57.061  4049  4049 D Launcher.Model: reloadBadges entered.
,03-31 16:30:57.066  3440  4048 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 16:30:57.066  3440  4048 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 16:30:57.066  3440  4048 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 16:30:57.066  3440  4048 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-31 16:30:57.071 12223 12223 I SA      : [TPM] There is no property file
,03-31 16:30:57.071 12223 12223 I SA      : [SCU] isHaveSA() - false
,03-31 16:30:57.076 12223 12223 I SA      : [TPM] getModelProperty : null
03-31 16:30:57.076 12223 12223 I SA      : [TPM] getCSCProperty : null
03-31 16:30:57.076 12223 12223 I SA      : [DM] FLOATING AMOLED FEATURE: true
03-31 16:30:57.076 12223 12223 I SA      : [DM] PRODUCT AMOLED FEATURE: false
03-31 16:30:57.076  3440  3591 D PackageManager: delete codoeFile: 
03-31 16:30:57.076 12223 12223 I SA      : [DM] TFT FEATURE: false
03-31 16:30:57.076  3440  3591 D PackageManager: Resopt: Clean up res: /data/app/com.test.thalitest-1/base.apk
03-31 16:30:57.076 12241 12241 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-31 16:30:57.076 12241 12241 D ActivityThread: Added TimaKeyStore provider
03-31 16:30:57.076 12223 12223 I SA      : [SUR] onReceive called
03-31 16:30:57.076 12223 12223 I SA      : [SUR] Not SA Package.. finish
,03-31 16:30:57.076 12258 12258 E Zygote  : MountEmulatedStorage()
03-31 16:30:57.076 12258 12258 E Zygote  : v2
03-31 16:30:57.076 12258 12258 I libpersona: KNOX_SDCARD checking this for 10183
03-31 16:30:57.076 12258 12258 I libpersona: KNOX_SDCARD not a persona
,03-31 16:30:57.081 12258 12258 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
03-31 16:30:57.081  3440  3591 D AASAuninstall: userId = 0, info.removedAppID = 10011, info.uid = 10011, packageName = com.test.thalitest
,03-31 16:30:57.081  3440  3591 I AASA_removePackage: UID=10011 Target=com.test.thalitest
,03-31 16:30:57.081  3440  3591 D PackageManager: result of delete: 1{320776157}
,03-31 16:30:57.081 12258 12258 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
03-31 16:30:57.081  3440  4048 I ActivityManager: Start proc 12258:com.samsung.android.provider.shootingmodeprovider/u0a183 for broadcast-4 com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver
03-31 16:30:57.081 12258 12258 E Zygote  : accessInfo : 0
,03-31 16:30:57.081 12258 12258 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-31 16:30:57.086 12162 12162 I art     : System.exit called, status: 0
03-31 16:30:57.086 12162 12162 I AndroidRuntime: VM exiting with result code 0.
,03-31 16:30:57.086  3440  3946 I ActivityManager: Killing 10362:com.facebook.system/u0a10 (adj 15): emptyCount ##31
,03-31 16:30:57.091  3440  3591 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
03-31 16:30:57.091  3440  3591 D PackageManager: userId{-1}
03-31 16:30:57.091  3440  3591 D PackageManager: andCode{true}
,03-31 16:30:57.101 12258 12258 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-31 16:30:57.101 12258 12258 D ActivityThread: Added TimaKeyStore provider
,03-31 16:30:57.101 10790 10801 D BadgeProvider: query, [selection] : null
,03-31 16:30:57.111  3440  4737 V BroadcastQueue: [backgroundsplit_1] Process cur broadcast BroadcastRecord{17c45a7b u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{322d08ca 12241:com.samsung.android.app.assistantmenu/1000}
,03-31 16:30:57.131  3440  3440 D RCPManagerService: PackageReceiver onReceive()
03-31 16:30:57.131  3440  3440 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,03-31 16:30:57.136  3440  4739 I ActivityManager: Killing 10324:com.vlingo.midas/u0a34 (adj 15): emptyCount ##31
,03-31 16:30:57.136  3440  3440 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
03-31 16:30:57.136  3440  3440 I OTPFW   : PackageRemovalReceiver::onReceive Enter
03-31 16:30:57.136  3440  3440 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10011 container id = 0
03-31 16:30:57.136  3440  4739 V BroadcastQueue: [backgroundsplit_2] Process cur broadcast BroadcastRecord{29a930f1 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{1f5db1a3 12258:com.samsung.android.provider.shootingmodeprovider/u0a183}
,03-31 16:30:57.146  3440  4048 V BroadcastQueue: [backgroundsplit_0] Process cur broadcast BroadcastRecord{5f0388b u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{1f61fedb 4371:android.process.acore/u0a23}
,03-31 16:30:57.151  3440  3440 I OTPFW   : ProvisionData::getAllEntries Enter
,03-31 16:30:57.151  3440  3440 E OTPFW   : ProvisionData::getAllEntries Table is empty
,03-31 16:30:57.151  3440  3568 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
03-31 16:30:57.151  3440  3568 D UsbSettingsManager: clearDefaults: com.test.thalitest
,03-31 16:30:57.151  3440  3440 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
03-31 16:30:57.151  3440  3440 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
03-31 16:30:57.151  3440  3440 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
03-31 16:30:57.151  3440  3440 V EnterpriseBillingPolicy: uID is 10011
03-31 16:30:57.151  3440  3440 V EnterpriseBillingPolicy: Removed Packageuid is0
03-31 16:30:57.151  3440  3440 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
03-31 16:30:57.151  3440  3440 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
03-31 16:30:57.151  3440  3440 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
03-31 16:30:57.151  3440  3440 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
03-31 16:30:57.151  3440  3440 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
03-31 16:30:57.156  3440  3440 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
03-31 16:30:57.156  3440  4724 D ActivityManager: startService callerProcessName:com.android.providers.contacts, calleePkgName: com.android.providers.contacts
,03-31 16:30:57.156  4049  4049 E Launcher.Model: onPackageRemoved :com.test.thalitest
03-31 16:30:57.156  3440  3440 D SdpManagerService:  ActionReceiver::onReceive() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
03-31 16:30:57.156  3440  3440 D SdpManagerService: ACTION_PACKAGE_REMOVED Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) } DATA= package:com.test.thalitest UID 1000 userId 0
03-31 16:30:57.156  3440  3440 D SdpManagerService: ACTION_PACKAGE_REMOVED packageName:: com.test.thalitest
,03-31 16:30:57.156  3440  3440 D EnterprisePartitionManager: SND -> {secure_fs remove_enc_dir}
03-31 16:30:57.161  3440  3593 D EnterprisePartitionManager: RCV <-
03-31 16:30:57.161  3440  3440 D EnterprisePartitionManager: RMV <-
,03-31 16:30:57.166  9732 12275 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.test.thalitest
03-31 16:30:57.166  3440  3946 V BroadcastQueue: [backgroundsplit_0] Process cur broadcast BroadcastRecord{5f0388b u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{2965d18 5596:com.android.contacts/u0a23}
,03-31 16:30:57.166  9732 12275 W System.err: remove failed: EACCES (Permission denied) : /storage/extSdCard/Android/data/com.test.thalitest
,03-31 16:30:57.171  9732 12275 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.test.thalitest
03-31 16:30:57.171 12241 12241 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2129 android.content.ContextWrapper.startService:534 android.content.ContextWrapper.startService:534 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3509 
,03-31 16:30:57.171  9732 12275 W System.err: remove failed: EACCES (Permission denied) : /storage/extSdCard/Android/media/com.test.thalitest
,03-31 16:30:57.171  3440  3440 E EnterprisePartitionManager: Failed to send commandcom.sec.knox.container.util.DaemonConnector$DaemonArgumentException: command 'secure_fs' failed with '500 3 Command not recognized'
03-31 16:30:57.171  3440  3440 W System.err: java.io.FileNotFoundException: /data/system/users/sdp_engine_list.xml: open failed: ENOENT (No such file or directory)
03-31 16:30:57.171  3440  3440 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-31 16:30:57.171  3440  3440 W System.err: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
03-31 16:30:57.171  3440  3440 W System.err: 	at com.android.server.SdpManagerService$SdpEngineDatabase$EngineListHandler.getEngineListLocked(SdpManagerService.java:1514)
03-31 16:30:57.171  3440  3440 W System.err: 	at com.android.server.SdpManagerService$SdpEngineDatabase$EngineListHandler.access$1100(SdpManagerService.java:1434)
03-31 16:30:57.171  3440  3440 W System.err: 	at com.android.server.SdpManagerService$SdpEngineDatabase.getEngineListLocked(SdpManagerService.java:1418)
03-31 16:30:57.171  3440  3440 W System.err: 	at com.android.server.SdpManagerService$SdpEngineDatabase.access$2200(SdpManagerService.java:1393)
03-31 16:30:57.171  3440  3440 W System.err: 	at com.android.server.SdpManagerService.handlePkgRemoved(SdpManagerService.java:2647)
03-31 16:30:57.171  3440  3440 W System.err: 	at com.android.server.SdpManagerService.access$2500(SdpManagerService.java:137)
03-31 16:30:57.171  3440  3440 W System.err: 	at com.android.server.SdpManagerService$ActionReceiver.onReceive(SdpManagerService.java:2719)
03-31 16:30:57.171  3440  3440 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:972)
03-31 16:30:57.171  3440  3440 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
03-31 16:30:57.171  3440  3440 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-31 16:30:57.176  3440  6049 D SSRM:bd : MSG_TYPE_APP_REMOVED::
03-31 16:30:57.171  3440  3440 W System.err: 	at android.os.Looper.loop(Looper.java:145)
03-31 16:30:57.171  3440  3440 W System.err: 	at com.android.server.SystemServer.run(SystemServer.java:469)
03-31 16:30:57.171  3440  3440 W System.err: 	at com.android.server.SystemServer.main(SystemServer.java:353)
03-31 16:30:57.171  3440  3440 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
03-31 16:30:57.171  3440  3440 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-31 16:30:57.171  3440  3440 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
03-31 16:30:57.171  3440  3440 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
03-31 16:30:57.171  3440  3440 W System.err: Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
03-31 16:30:57.171  3440  3440 W System.err: 	at libcore.io.Posix.open(Native Method)
03-31 16:30:57.171  3440  3440 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-31 16:30:57.176  3440  3901 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
03-31 16:30:57.171  3440  3440 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-31 16:30:57.171  3440  3440 W System.err: 	... 18 more
03-31 16:30:57.171  3440  3440 E SdpManagerService: failed to get engine list
03-31 16:30:57.176  9732 12275 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/obb/com.test.thalitest
03-31 16:30:57.176  3440  3440 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
03-31 16:30:57.176  3440  3440 V EnterpriseBillingPolicy: uID is 10011
03-31 16:30:57.176  3440  3440 V EnterpriseBillingPolicy: Removed Packageuid is0
03-31 16:30:57.176  3440  3440 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
03-31 16:30:57.176  9732 12275 W System.err: remove f,ailed: EACCES (Permission denied) : /storage/extSdCard/Android/obb/com.test.thalitest
03-31 16:30:57.176  3440  3440 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
03-31 16:30:57.176  3440  3440 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
03-31 16:30:57.176  3440  3440 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
03-31 16:30:57.176  3440  3440 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
03-31 16:30:57.176  3440  3440 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
03-31 16:30:57.186  3440  3946 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 16:30:57.186  3440  3946 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 16:30:57.186  3440  3946 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 16:30:57.186  3440  3946 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 16:30:57.201 12278 12278 E Zygote  : MountEmulatedStorage()
03-31 16:30:57.201 12278 12278 E Zygote  : v2
03-31 16:30:57.201 12278 12278 I libpersona: KNOX_SDCARD checking this for 10050
03-31 16:30:57.201 12278 12278 I libpersona: KNOX_SDCARD not a persona
03-31 16:30:57.201 12278 12278 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
03-31 16:30:57.206 12278 12278 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
03-31 16:30:57.206 12278 12278 E Zygote  : accessInfo : 0
03-31 16:30:57.206 12278 12278 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-31 16:30:57.206 12258 12258 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
03-31 16:30:57.211  3440  3946 I ActivityManager: Start proc 12278:com.sec.android.gallery3d/u0a50 for broadcast-4 com.sec.android.gallery3d/.app.PackagesMonitor
,03-31 16:30:57.216  3440  3440 D KnoxTimeoutHandler: handleActiveUserChange for user 0
03-31 16:30:57.216  3440  3440 D PersonaManagerService: getPersonasForUser(): returning null!
03-31 16:30:57.216  3440  3440 E EnterpriseSharedDevicePolicy: isSharedDeviceEnabled
03-31 16:30:57.216  3440  3440 I EnterpriseSharedDevicePolicy: isSharedDeviceEnabled in Service
03-31 16:30:57.216  3440  3440 I EnterpriseSharedDevicePolicy: Get Result: -1
03-31 16:30:57.216  3440  3440 I EnterpriseSharedDevicePolicy: status: false
03-31 16:30:57.216  3440  3440 I KnoxTimeoutHandler: Shared devices show user statefalse
,03-31 16:30:57.216  3724  3724 D PanelView: There is/are notification(s) 
,03-31 16:30:57.221  3440  3440 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{203b3638 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{9c5453c 6116:com.sec.android.service.health/u0a19}
03-31 16:30:57.221  3440  3828 D ActivityManager: startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
,03-31 16:30:57.231  6116  6116 D com.sec.android.service.health.upgrade.UninstallReceiver: onReceive()
03-31 16:30:57.231  3440  3946 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 16:30:57.231  6116  6116 I com.sec.android.service.health.upgrade.UninstallReceiver: onReceive called  PACKAGE_REMOVED package:com.test.thalitest
03-31 16:30:57.231  3440  3946 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 16:30:57.231  6116  6116 D com.sec.android.service.health.upgrade.UninstallReceiver: onReceive() : package name is not s health. Return !!!
03-31 16:30:57.231  3440  3946 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 16:30:57.231  3440  3946 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-31 16:30:57.236 12278 12278 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-31 16:30:57.236 12278 12278 D ActivityThread: Added TimaKeyStore provider
,03-31 16:30:57.246 12294 12294 E Zygote  : MountEmulatedStorage()
03-31 16:30:57.246 12294 12294 I libpersona: KNOX_SDCARD checking this for 1000
03-31 16:30:57.246 12294 12294 E Zygote  : v2
03-31 16:30:57.246 12294 12294 I libpersona: KNOX_SDCARD not a persona
,03-31 16:30:57.246 12294 12294 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
,03-31 16:30:57.246 12294 12294 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
03-31 16:30:57.246  3440  3946 I ActivityManager: Start proc 12294:com.sec.knox.bridge/1000 for broadcast-4 com.sec.knox.bridge/.PersonaShortcutReceiver
03-31 16:30:57.251 12294 12294 E Zygote  : accessInfo : 0
03-31 16:30:57.251 12294 12294 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-31 16:30:57.256  3440  3440 V AlarmManagerEXT: com.test.thalitest(10011) is removed.
,03-31 16:30:57.271 12294 12294 D TimaKeyStoreProvider: TimaSignature is unavailable
03-31 16:30:57.276 12294 12294 D ActivityThread: Added TimaKeyStore provider
,03-31 16:30:57.276  3440  3483 V BroadcastQueue: [backgroundsplit_0] Process cur broadcast BroadcastRecord{5f0388b u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{7389f64 12278:com.sec.android.gallery3d/u0a50}
,03-31 16:30:57.291  3440  3966 V BroadcastQueue: [backgroundsplit_1] Process cur broadcast BroadcastRecord{17c45a7b u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{3f0485cd 12294:com.sec.knox.bridge/1000}
,03-31 16:30:57.296  3440  3946 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 16:30:57.296  3440  3946 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 16:30:57.296  3440  3946 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 16:30:57.296  3440  3946 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-31 16:30:57.306  3724  3724 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,03-31 16:30:57.311  3724  3724 D PanelView: There is/are notification(s) 
,03-31 16:30:57.311  3724  3724 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-31 16:30:57.316  3724  3724 D PanelView: There is/are notification(s) 
03-31 16:30:57.316 12309 12309 I libpersona: KNOX_SDCARD checking this for 10190
03-31 16:30:57.316  3724  3724 D PanelView: kidsfalse mQsExpansionEnabled:true
03-31 16:30:57.316 12309 12309 I libpersona: KNOX_SDCARD not a persona
03-31 16:30:57.316 12309 12309 E Zygote  : MountEmulatedStorage()
03-31 16:30:57.316 12309 12309 E Zygote  : v2
03-31 16:30:57.316 12309 12309 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
,03-31 16:30:57.326 12193 12239 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
,03-31 16:30:57.326 12278 12278 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-31 16:30:57.326 12278 12278 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-31 16:30:57.326 12278 12278 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-31 16:30:57.326 12278 12278 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-31 16:30:57.326 12278 12278 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
03-31 16:30:57.326 12278 12278 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
03-31 16:30:57.326 12278 12278 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
03-31 16:30:57.326 12278 12278 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
03-31 16:30:57.326 12309 12309 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
03-31 16:30:57.326  3440  3946 I ActivityManager: Start proc 12309:com.sec.android.widgetapp.tapandpay/u0a190 for broadcast-4 com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider
03-31 16:30:57.326 12309 12309 E Zygote  : accessInfo : 0
03-31 16:30:57.326 12294 12294 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-31 16:30:57.326 12309 12309 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-31 16:30:57.331 12193 12239 E SQLiteLog: (6922) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
,03-31 16:30:57.336  3440  3946 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{203b3638 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{3443d7c3 10691:com.sec.android.widgetapp.locationwidget/u0a22}
,03-31 16:30:57.341 10691 10691 D LocationWidgetApplication: getLastUiLocationId() : mLastUiLocationId = -100
,03-31 16:30:57.351  3440  3946 I ActivityManager: Killing 10449:com.samsung.android.app.filterinstaller/1000 (adj 15): emptyCount ##31
,03-31 16:30:57.351 12309 12309 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-31 16:30:57.356 12193 12239 E SQLiteDatabase: Error inserting name=LPCSystemVersion value=1.0.0
03-31 16:30:57.356 12193 12239 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 6922)
03-31 16:30:57.356 12193 12239 E SQLiteDatabase: #################################################################
03-31 16:30:57.356 12193 12239 E SQLiteDatabase: Error Code : 6922 (SQLITE_IOERR_LOCK_EBADF)
03-31 16:30:57.356 12193 12239 E SQLiteDatabase: Caused By : I/O error happened due to bad file descriptor. There is possibility the partition changed to read-only.
03-31 16:30:57.356 12193 12239 E SQLiteDatabase: 	(disk I/O error (code 6922))
03-31 16:30:57.356 12193 12239 E SQLiteDatabase: #################################################################
03-31 16:30:57.356 12193 12239 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
03-31 16:30:57.356 12193 12239 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
03-31 16:30:57.356 12193 12239 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
03-31 16:30:57.356 12193 12239 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
03-31 16:30:57.356 12193 12239 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
03-31 16:30:57.356 12193 12239 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
03-31 16:30:57.356 12193 12239 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
03-31 16:30:57.356 12193 12239 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
03-31 16:30:57.356 12193 12239 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:188)
03-31 16:30:57.356 12193 12239 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
03-31 16:30:57.356 12193 12239 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
03-31 16:30:57.356 12193 12239 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
03-31 16:30:57.356 12193 12239 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
03-31 16:30:57.356 12193 12239 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
03-31 16:30:57.356 12193 12239 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
03-31 16:30:57.356 12193 12239 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-31 16:30:57.356 12193 12239 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-31 16:30:57.356 12193 12239 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-31 16:30:57.356 12193 12239 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-31 16:30:57.356 12309 12309 D ActivityThread: Added TimaKeyStore provider
,03-31 16:30:57.361  3440  3946 I ActivityManager: Killing 10486:com.samsung.helphub/1000 (adj 15): emptyCount ##31
,03-31 16:30:57.366 12193 12239 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-31 16:30:57.366 12193 12239 E SQLiteLog: (6922) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
,03-31 16:30:57.371  3440  4737 V BroadcastQueue: [backgroundsplit_2] Process cur broadcast BroadcastRecord{29a930f1 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{1c924dd0 12309:com.sec.android.widgetapp.tapandpay/u0a190}
,03-31 16:30:57.371  3440  3946 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 16:30:57.371  3440  3946 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 16:30:57.371  3440  3946 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 16:30:57.371  3440  3946 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-31 16:30:57.376 12294 12294 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
,03-31 16:30:57.376 12193 12239 E SQLiteDatabase: Error inserting name=UT enabled value=false
03-31 16:30:57.376 12193 12239 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 6922)
03-31 16:30:57.376 12193 12239 E SQLiteDatabase: #################################################################
03-31 16:30:57.376 12193 12239 E SQLiteDatabase: Error Code : 6922 (SQLITE_IOERR_LOCK_EBADF)
03-31 16:30:57.376 12193 12239 E SQLiteDatabase: Caused By : I/O error happened due to bad file descriptor. There is possibility the partition changed to read-only.
03-31 16:30:57.376 12193 12239 E SQLiteDatabase: 	(disk I/O error (code 6922))
03-31 16:30:57.376 12193 12239 E SQLiteDatabase: #################################################################
03-31 16:30:57.376 12193 12239 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
03-31 16:30:57.376 12193 12239 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
03-31 16:30:57.376 12193 12239 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
03-31 16:30:57.376 12193 12239 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
03-31 16:30:57.376 12193 12239 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
03-31 16:30:57.376 12193 12239 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
03-31 16:30:57.376 12193 12239 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
03-31 16:30:57.376 12193 12239 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
03-31 16:30:57.376 12193 12239 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:189)
03-31 16:30:57.376 12193 12239 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
03-31 16:30:57.376 12193 12239 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
03-31 16:30:57.376 12193 12239 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
03-31 16:30:57.376 12193 12239 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
03-31 16:30:57.376 12193 12239 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
03-31 16:30:57.376 12193 12239 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
03-31 16:30:57.376 12193 12239 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-31 16:30:57.376 12193 12239 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-31 16:30:57.376 12193 12239 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-31 16:30:57.376 12193 12239 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-31 16:30:57.376  3440  3603 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/2/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.0
03-31 16:30:57.376  3440  3603 D UsbHostManager: displayNotification : [02h,02h,01h]
,03-31 16:30:57.381  3440  3603 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.1
03-31 16:30:57.381  3440  3603 D UsbHostManager: displayNotification : [0ah,00h,00h]
,03-31 16:30:57.381  3440  3603 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/13/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.2
03-31 16:30:57.381  3440  3603 D UsbHostManager: displayNotification : [02h,0dh,00h]
,03-31 16:30:57.381  3440  3603 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.3
03-31 16:30:57.381  3440  3603 D UsbHostManager: displayNotification : [0ah,00h,01h]
,03-31 16:30:57.381 12193 12239 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
,03-31 16:30:57.386  3724  3724 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
03-31 16:30:57.386  3440  3692 D UsbHostManager: usbDeviceRemoved : /dev/bus/usb/001/003
03-31 16:30:57.386  3440  3692 E UsbHostManager: usbDeviceRemoved :: deviceName = /dev/bus/usb/001/003
03-31 16:30:57.386  3440  3692 D UsbSettingsManager: usbDeviceRemoved, sending Intent { act=android.hardware.usb.action.USB_DEVICE_DETACHED (has extras) }
,03-31 16:30:57.386 12193 12239 E SQLiteLog: (6922) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
,03-31 16:30:57.386 12331 12331 E Zygote  : MountEmulatedStorage()
03-31 16:30:57.386 12331 12331 E Zygote  : v2
03-31 16:30:57.386 12331 12331 I libpersona: KNOX_SDCARD checking this for 1000
03-31 16:30:57.386 12331 12331 I libpersona: KNOX_SDCARD not a persona
,03-31 16:30:57.391 12193 12239 E SQLiteDatabase: Error inserting name=AFP Enabled value=true
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 6922)
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: #################################################################
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: Error Code : 6922 (SQLITE_IOERR_LOCK_EBADF)
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: Caused By : I/O error happened due to bad file descriptor. There is possibility the partition changed to read-only.
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: 	(disk I/O error (code 6922))
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: #################################################################
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:190)
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-31 16:30:57.391 12331 12331 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
,03-31 16:30:57.391 12193 12239 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-31 16:30:57.391 12193 12239 E SQLiteLog: (6922) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: Error inserting name=SleepDetection Enabled value=false
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 6922)
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: #################################################################
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: Error Code : 6922 (SQLITE_IOERR_LOCK_EBADF)
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: Caused By : I/O error happened due to bad file descriptor. There is possibility the partition changed to read-only.
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: 	(disk I/O error (code 6922))
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: #################################################################
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:191)
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-31 16:30:57.391 12193 12239 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-31 16:30:57.391 12193 12239 E SQLiteLog: (6922) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: Error inserting name=System Build Version Release value=5.1.1
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 6922)
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: #################################################################
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: Error Code : 6922 (SQLITE_IOERR_LOCK_EBADF)
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: Caused By : I/O error happened due to bad file descriptor. There is possibility the partition changed to read-only.
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: 	(disk I/O error (code 6922))
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: #################################################################
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:192)
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-31 16:30:57.391 12193 12239 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-31 16:30:57.391 12193 12239 E SQLiteLog: (6922) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
,03-31 16:30:57.391 12193 12239 E SQLiteDatabase: Error inserting name=status value=successfully initialized
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 6922)
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: #################################################################
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: Error Code : 6922 (SQLITE_IOERR_LOCK_EBADF)
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: Caused By : I/O error happened due to bad file descriptor. There is possibility the partition changed to read-only.
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: 	(disk I/O error (code 6922))
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: #################################################################
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:193)
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-31 16:30:57.391 12193 12239 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-31 16:30:57.396  3440  4064 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
03-31 16:30:57.396  3440  4064 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
,03-31 16:30:57.396  3440  3946 I ActivityManager: Start proc 12331:com.sec.pcw.device/1000 for broadcast-3 com.sec.pcw.device/.receiver.SYSTEMReceiver
,03-31 16:30:57.401  3440  3946 I ActivityManager: Killing 10520:com.samsung.android.bbc.bbcagent/1000 (adj 15): emptyCount ##31
,03-31 16:30:57.401 12331 12331 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
03-31 16:30:57.401  3440  3603 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 1d6b/2/310, type = 9/0/0, interface = 9/0/0, devpath = /devices/15510000.usb/usb1/1-0:1.0
03-31 16:30:57.401 12331 12331 E Zygote  : accessInfo : 0
03-31 16:30:57.401  3440  3603 D UsbHostManager: displayNotification : [09h,00h,00h]
03-31 16:30:57.401 12331 12331 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-31 16:30:57.406 12278 12278 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.gallery3d/databases/picasa.db" with flag (131138) and mode_t (0) due to error (30)
,03-31 16:30:57.406  3440  3946 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 16:30:57.406  3440  3946 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 16:30:57.406  3440  3946 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 16:30:57.406  3440  3946 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-31 16:30:57.416 12278 12278 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.gallery3d/databases/picasa.db'.
03-31 16:30:57.416 12278 12278 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-31 16:30:57.416 12278 12278 E SQLiteDatabase: #################################################################
03-31 16:30:57.416 12278 12278 E SQLiteDatabase: Error Code : 0 (SQLITE_OK)
03-31 16:30:57.416 12278 12278 E SQLiteDatabase: Caused By : not an error (code 0): Could not open the database in read/write mode.
03-31 16:30:57.416 12278 12278 E SQLiteDatabase: #################################################################
03-31 16:30:57.416 12278 12278 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-31 16:30:57.416 12278 12278 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-31 16:30:57.416 12278 12278 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-31 16:30:57.416 12278 12278 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-31 16:30:57.416 12278 12278 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-31 16:30:57.416 12278 12278 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-31 16:30:57.416 12278 12278 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-31 16:30:57.416 12278 12278 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-31 16:30:57.416 12278 12278 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-31 16:30:57.416 12278 12278 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1585)
03-31 16:30:57.416 12278 12278 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
03-31 16:30:57.416 12278 12278 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-31 16:30:57.416 12278 12278 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-31 16:30:57.416 12278 12278 E SQLiteDatabase: 	at com.sec.android.gallery3d.remote.picasa.PicasaContentProvider$SyncContext.<init>(PicasaContentProvider.java:911)
03-31 16:30:57.416 12278 12278 E SQLiteDatabase: 	at com.sec.android.gallery3d.remote.picasa.PicasaContentProvider.attachInfo(PicasaContentProvider.java:103)
03-31 16:30:57.416 12278 12278 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:6413)
03-31 16:30:57.416 12278 12278 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:6008)
03-31 16:30:57.416 12278 12278 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5948)
03-31 16:30:57.416 12278 12278 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:197)
03-31 16:30:57.416 12278 12278 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1742)
03-31 16:30:57.416 12278 12278 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-31 16:30:57.416 12278 12278 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-31 16:30:57.416 12278 12278 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6872)
03-31 16:30:57.416 12278 12278 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
03-31 16:30:57.416 12278 12278 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-31 16:30:57.416 12278 12278 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
03-31 16:30:57.416 12278 12278 E SQLiteData,base: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
03-31 16:30:57.421 12309 12309 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
03-31 16:30:57.421 12309 12309 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
03-31 16:30:57.426 12347 12347 E Zygote  : MountEmulatedStorage()
03-31 16:30:57.426 12347 12347 E Zygote  : v2
03-31 16:30:57.426 12347 12347 I libpersona: KNOX_SDCARD checking this for 10101
03-31 16:30:57.426 12309 12309 I TapandpayWidget:Utils: Clear T&P info.
03-31 16:30:57.426 12347 12347 I libpersona: KNOX_SDCARD not a persona
03-31 16:30:57.426 12347 12347 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
03-31 16:30:57.431  3440  3692 D UsbHostManager: usbDeviceRemoved : /dev/bus/usb/001/001
03-31 16:30:57.431  3440  3692 E UsbHostManager: usbDeviceRemoved :: deviceName = /dev/bus/usb/001/001
03-31 16:30:57.431 12309 12309 D TapandpayWidget:TapandpayAppWidgetProvider: Widget is not attached.
03-31 16:30:57.436 12347 12347 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
03-31 16:30:57.451 12347 12347 E Zygote  : accessInfo : 0
,03-31 16:30:57.451 12331 12331 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-31 16:30:57.456 12331 12331 D ActivityThread: Added TimaKeyStore provider
03-31 16:30:57.456  3440  3946 I ActivityManager: Start proc 12347:com.google.android.apps.docs/u0a101 for broadcast-4 com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,03-31 16:30:57.461 12347 12347 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-31 16:30:57.466  3440  3946 I ActivityManager: Killing 10536:com.samsung.android.intelligenceservice/u0a3 (adj 15): emptyCount ##31
,03-31 16:30:57.501 12347 12347 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-31 16:30:57.501 12347 12347 D ActivityThread: Added TimaKeyStore provider
,03-31 16:30:57.511  3440  3631 I EventHub: Removing device '/dev/input/event10' due to inotify event
,03-31 16:30:57.511  3440  3901 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{203b3638 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{3ce0b1c9 12331:com.sec.pcw.device/1000}
,03-31 16:30:57.536  3440  3631 I EventHub: Removing device '/dev/input/event7' due to inotify event
,03-31 16:30:57.546  3440  3946 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 16:30:57.546  3440  3946 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 16:30:57.546  3440  3946 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 16:30:57.546  3440  3946 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-31 16:30:57.576  3440  3631 I EventHub: Removing device '/dev/input/event8' due to inotify event
03-31 16:30:57.596 12193 12193 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
03-31 16:30:57.606  3440  3631 I EventHub: Removing device '/dev/input/event9' due to inotify event
,03-31 16:30:57.621 12331 12331 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
03-31 16:30:57.621 12331 12331 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
03-31 16:30:57.621 12331 12331 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,03-31 16:30:57.631 12331 12331 E SQLiteLog: (28) failed to open "/data/data/com.sec.pcw.device/databases/value.db" with flag (131138) and mode_t (0) due to error (30)
,03-31 16:30:57.631 12331 12331 E SQLiteDatabase: Failed to open database '/data/data/com.sec.pcw.device/databases/value.db'.
03-31 16:30:57.631 12331 12331 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-31 16:30:57.631 12331 12331 E SQLiteDatabase: #################################################################
03-31 16:30:57.631 12331 12331 E SQLiteDatabase: Error Code : 0 (SQLITE_OK)
03-31 16:30:57.631 12331 12331 E SQLiteDatabase: Caused By : not an error (code 0): Could not open the database in read/write mode.
03-31 16:30:57.631 12331 12331 E SQLiteDatabase: #################################################################
03-31 16:30:57.631 12331 12331 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-31 16:30:57.631 12331 12331 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-31 16:30:57.631 12331 12331 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-31 16:30:57.631 12331 12331 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-31 16:30:57.631 12331 12331 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-31 16:30:57.631 12331 12331 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-31 16:30:57.631 12331 12331 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-31 16:30:57.631 12331 12331 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-31 16:30:57.631 12331 12331 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-31 16:30:57.631 12331 12331 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1585)
03-31 16:30:57.631 12331 12331 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
03-31 16:30:57.631 12331 12331 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-31 16:30:57.631 12331 12331 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-31 16:30:57.631 12331 12331 E SQLiteDatabase: 	at com.sec.pcw.device.contentprovider.DMProvider.onCreate(DMProvider.java:32)
03-31 16:30:57.631 12331 12331 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1737)
03-31 16:30:57.631 12331 12331 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
03-31 16:30:57.631 12331 12331 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:6413)
03-31 16:30:57.631 12331 12331 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:6008)
03-31 16:30:57.631 12331 12331 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5948)
03-31 16:30:57.631 12331 12331 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:197)
03-31 16:30:57.631 12331 12331 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1742)
03-31 16:30:57.631 12331 12331 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-31 16:30:57.631 12331 12331 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-31 16:30:57.631 12331 12331 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6872)
03-31 16:30:57.631 12331 12331 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
03-31 16:30:57.631 12331 12331 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-31 16:30:57.631 12331 12331 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
,03-31 16:30:57.631 12331 12331 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
03-31 16:30:57.636 12331 12331 D AndroidRuntime: Shutting down VM
03-31 16:30:57.636 12331 12331 E AndroidRuntime: FATAL EXCEPTION: main
03-31 16:30:57.636 12331 12331 E AndroidRuntime: Process: com.sec.pcw.device, PID: 12331
03-31 16:30:57.636 12331 12331 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.sec.pcw.device.contentprovider.DMProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-31 16:30:57.636 12331 12331 E AndroidRuntime: #################################################################
03-31 16:30:57.636 12331 12331 E AndroidRuntime: Error Code : 0 (SQLITE_OK)
03-31 16:30:57.636 12331 12331 E AndroidRuntime: Caused By : not an error (code 0): Could not open the database in read/write mode.
03-31 16:30:57.636 12331 12331 E AndroidRuntime: #################################################################
03-31 16:30:57.636 12331 12331 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:6416)
03-31 16:30:57.636 12331 12331 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:6008)
03-31 16:30:57.636 12331 12331 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5948)
03-31 16:30:57.636 12331 12331 E AndroidRuntime: 	at android.app.ActivityThread.access$1700(ActivityThread.java:197)
03-31 16:30:57.636 12331 12331 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1742)
03-31 16:30:57.636 12331 12331 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-31 16:30:57.636 12331 12331 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
03-31 16:30:57.636 12331 12331 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6872)
03-31 16:30:57.636 12331 12331 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
03-31 16:30:57.636 12331 12331 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-31 16:30:57.636 12331 12331 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
03-31 16:30:57.636 12331 12331 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
03-31 16:30:57.636 12331 12331 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-31 16:30:57.636 12331 12331 E AndroidRuntime: #################################################################
03-31 16:30:57.636 12331 12331 E AndroidRuntime: Error Code : 0 (SQLITE_OK)
03-31 16:30:57.636 12331 12331 E AndroidRuntime: Caused By : not an error (code 0): Could not open the database in read/write mode.
03-31 16:30:57.636 12331 12331 E AndroidRuntime: #################################################################
03-31 16:30:57.636 12331 12331 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-31 16:30:57.636 12331 12331 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-31 16:30:57.636 12331 12331 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-31 16:30:57.636 12331 12331 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-31 16:30:57.636 12331 12331 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-31 16:30:57.636 12331 12331 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-31 16:30:57.636 12331 12331 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-31 16:30:57.636 12331 12331 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-31 16:30:57.636 12331 12331 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-31 16:30:57.636 12331 12331 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1585)
03-31 16:30:57.636 12331 12331 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
03-31 16:30:57.636 12331 12331 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-31 16:30:57.636 12331 12331 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-31 16:30:57.636 12331 12331 E AndroidRuntime: 	at com.sec.pcw.device.contentprovider.DMProvider.onCreate(DMProvider.java:32)
03-31 16:30:57.636 12331 12331 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1737)
03-31 16:30:57.636 12331 12331 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
03-31 16:30:57.636 12331 12331 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:6413)
03-31 16:30:57.636 12331 12331 E AndroidRuntime: 	... 11 more
03-31 16:30:57.641 12365 12365 E Zygote  : MountEmulatedStorage()
03-31 16:30:57.641 12365 12365 E Zygote  : v2
03-31 16:30:57.641 12365 12365 I libpersona: KNOX_SDCARD checking this for 10193
03-31 16:30:57.641 12365 12365 I libpersona: KNOX_SDCARD not a persona
03-31 16:30:57.646 12365 12365 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
03-31 16:30:57.646  3440  3946 I ActivityManager: Start proc 12365:com.sec.enterprise.knox.cloudmdm.smdms/u0a193 for broadcast-4 com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver
03-31 16:30:57.651 12365 12365 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
03-31 16:30:57.651 12365 12365 E Zygote  : accessInfo : 0
03-31 16:30:57.651 12365 12365 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-31 16:30:57.651  3440  3631 I EventHub: Removing device '/dev/input/event11' due to inotify event
03-31 16:30:57.656  3440  3946 I ActivityManager: Killing 10577:com.sec.android.app.samsungapps/u0a13 (adj 15): emptyCount ##31
,03-31 16:30:57.691 12365 12365 D TimaKeyStoreProvider: TimaSignature is unavailable
03-31 16:30:57.696 12365 12365 D ActivityThread: Added TimaKeyStore provider
03-31 16:30:57.701  3440  4739 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.pcw.device
03-31 16:30:57.701  3440  3631 I EventHub: Removing device '/dev/input/event12' due to inotify event
03-31 16:30:57.706 10790 10801 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-31 16:30:57.706 10790 10801 E SQLiteLog: (6922) statement aborts at 27: [UPDATE apps SET badgecount=? WHERE package=? AND class=?] disk I/O error
,03-31 16:30:57.716  3440  3484 V BroadcastQueue: [backgroundsplit_1] Process cur broadcast BroadcastRecord{17c45a7b u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{2c4d20ce 12347:com.google.android.apps.docs/u0a101}
03-31 16:30:57.716 10790 10801 E DatabaseUtils: Writing exception to parcel
03-31 16:30:57.716 10790 10801 E DatabaseUtils: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 6922)
03-31 16:30:57.716 10790 10801 E DatabaseUtils: #################################################################
03-31 16:30:57.716 10790 10801 E DatabaseUtils: Error Code : 6922 (SQLITE_IOERR_LOCK_EBADF)
03-31 16:30:57.716 10790 10801 E DatabaseUtils: Caused By : I/O error happened due to bad file descriptor. There is possibility the partition changed to read-only.
03-31 16:30:57.716 10790 10801 E DatabaseUtils: 	(disk I/O error (code 6922))
03-31 16:30:57.716 10790 10801 E DatabaseUtils: #################################################################
03-31 16:30:57.716 10790 10801 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
03-31 16:30:57.716 10790 10801 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
03-31 16:30:57.716 10790 10801 E DatabaseUtils: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
03-31 16:30:57.716 10790 10801 E DatabaseUtils: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
03-31 16:30:57.716 10790 10801 E DatabaseUtils: 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1714)
03-31 16:30:57.716 10790 10801 E DatabaseUtils: 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1660)
03-31 16:30:57.716 10790 10801 E DatabaseUtils: 	at com.sec.android.provider.badge.BadgeProvider.update(BadgeProvider.java:176)
03-31 16:30:57.716 10790 10801 E DatabaseUtils: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:341)
03-31 16:30:57.716 10790 10801 E DatabaseUtils: 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:222)
03-31 16:30:57.716 10790 10801 E DatabaseUtils: 	at android.os.Binder.execTransact(Binder.java:461)
,03-31 16:30:57.736  3440  4421 V BroadcastQueue: [backgroundsplit_2] Process cur broadcast BroadcastRecord{29a930f1 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{139e7bda 12365:com.sec.enterprise.knox.cloudmdm.smdms/u0a193}
,03-31 16:30:57.761  3440  3631 I EventHub: Removing device '/dev/input/event13' due to inotify event
,03-31 16:30:57.766  3440  3575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 16:30:57.766  3440  3575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 16:30:57.766  3440  3575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 16:30:57.766  3440  3575 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-31 16:30:57.781  3440 12380 E DropBoxManagerService: Can't write: system_app_crash
03-31 16:30:57.781  3440 12380 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop228.tmp: open failed: EROFS (Read-only file system)
03-31 16:30:57.781  3440 12380 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-31 16:30:57.781  3440 12380 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-31 16:30:57.781  3440 12380 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-31 16:30:57.781  3440 12380 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-31 16:30:57.781  3440 12380 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-31 16:30:57.781  3440 12380 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$23.run(ActivityManagerService.java:16408)
03-31 16:30:57.781  3440 12380 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-31 16:30:57.781  3440 12380 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-31 16:30:57.781  3440 12380 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-31 16:30:57.781  3440 12380 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-31 16:30:57.781  3440 12380 E DropBoxManagerService: 	... 5 more
03-31 16:30:57.781  3440 12380 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/dropbox/drop228.tmp
,03-31 16:30:57.791 12365 12365 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-31 16:30:57.806 12278 12278 D NearbySource: Nearby Source Create!
,03-31 16:30:57.811 12278 12278 D NearbyContext: Nearby Context Create!
,03-31 16:30:57.816 12381 12381 E Zygote  : MountEmulatedStorage()
03-31 16:30:57.816 12381 12381 I libpersona: KNOX_SDCARD checking this for 10035
03-31 16:30:57.816 12381 12381 E Zygote  : v2
03-31 16:30:57.816 12381 12381 I libpersona: KNOX_SDCARD not a persona
03-31 16:30:57.821 12381 12381 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
03-31 16:30:57.831 12381 12381 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
,03-31 16:30:57.831 12381 12381 E Zygote  : accessInfo : 0
03-31 16:30:57.831 12381 12381 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-31 16:30:57.836  3440  3631 I EventHub: Removing device '/dev/input/event14' due to inotify event
,03-31 16:30:57.841  3440  3575 I ActivityManager: Start proc 12381:com.samsung.android.app.galaxyfinder/u0a35 for broadcast-3 com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver
,03-31 16:30:57.856  3440  4421 I ActivityManager: Killing 10551:com.google.android.apps.plus/u0a147 (adj 15): emptyCount ##31
,03-31 16:30:57.866 12331 12331 I Process : Sending signal. PID: 12331 SIG: 9
,03-31 16:30:57.871  2858  3091 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
03-31 16:30:57.871  2858  3091 W Vold    : Returning OperationFailed - no handler for errno 0
03-31 16:30:57.871 12365 12365 D [0]UMC:UMCContentProvider: @onCreate
,03-31 16:30:57.876 12278 12278 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,03-31 16:30:57.881 12278 12278 D SLinkSource: Samsung link source created
,03-31 16:30:57.886 12365 12365 D [0]UMC:Core: onCreate(): 
03-31 16:30:57.886 12365 12365 D [0]UMC:Core: @isManagedProfileUser
,03-31 16:30:57.891 12365 12365 D [0]UMC:Core: userInfo.isManagedProfile() : false
,03-31 16:30:57.911 12381 12381 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-31 16:30:57.911 12381 12381 D ActivityThread: Added TimaKeyStore provider
,03-31 16:30:57.936  3440  4047 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{203b3638 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{a5206e8 12381:com.samsung.android.app.galaxyfinder/u0a35}
,03-31 16:30:57.956  3440  3946 I ActivityManager: Process com.sec.pcw.device (pid 12331)(adj 9) has died(263,1466)
03-31 16:30:57.961 12365 12365 D [0]UMC:DeviceInfo: USA==US==

```
