#### Test 64613803717efd7_thali08_samsung-SM-N910C Logs


```
--------- beginning of system
03-31 12:59:37.211  3461  3617 V AlarmManager: waitForAlarm result :4
,--------- beginning of main
03-31 12:59:37.246  3728  3728 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
03-31 12:59:37.246  3728  3728 I PERF    : received broadcast android.intent.action.TIME_TICK
03-31 12:59:37.251  3728  3728 D KeyguardUpdateMonitor: handleTimeUpdate
03-31 12:59:37.261  3728  3728 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
03-31 12:59:37.266  3728  3728 D SecKeyguardClockView: HomeTimezone(): 1
03-31 12:59:37.276  3728  3728 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
03-31 12:59:37.281  3728  3728 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
03-31 12:59:37.286  3728  3728 D CoverUpdateMonitor: received broadcast android.intent.action.TIME_TICK
03-31 12:59:37.341  3728  3728 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
03-31 12:59:37.346  3728  3728 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
03-31 12:59:37.356  3728  3728 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
03-31 12:59:37.361  3728  3728 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
03-31 12:59:37.361  3728  3728 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
03-31 12:59:37.366  3728  3728 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
03-31 12:59:37.381  3728  3728 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
03-31 12:59:37.631 11205 11205 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
03-31 12:59:37.641 11205 11205 D AndroidRuntime: CheckJNI is OFF
03-31 12:59:37.641 11205 11205 D AndroidRuntime: readGMSProperty: start
03-31 12:59:37.641 11205 11205 D AndroidRuntime: readGMSProperty: already setted!!
03-31 12:59:37.641 11205 11205 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-31 12:59:37.641 11205 11205 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-31 12:59:37.641 11205 11205 D AndroidRuntime: readGMSProperty: end
03-31 12:59:37.641 11205 11205 D AndroidRuntime: addProductProperty: start
03-31 12:59:37.826 11205 11205 E AffinityControl: AffinityControl: registerfunction enter
03-31 12:59:37.851 11205 11205 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-31 12:59:37.866  3461  4244 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
03-31 12:59:37.871  3461  4244 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-31 12:59:37.906  3461  4244 W ActivityManager: mDVFSHelper.acquire()
03-31 12:59:37.906  3461  4244 V WindowManager: addAppToken: AppWindowToken{310eb288 token=Token{96eee2b ActivityRecord{20f0167a u0 com.test.thalitest/.MainActivity t42}}} to stack=1 task=42 at 0
03-31 12:59:37.911  3461  4244 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 12:59:37.911  3461  4244 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 12:59:37.911  3461  4244 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 12:59:37.911  3461  4244 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 12:59:37.916  3461  3579 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-31 12:59:37.916  3461  3579 D PhoneWindow: *FMB* installDecor flags : -2122120936
03-31 12:59:37.921  3461  3579 D SecWifiDisplayUtil: Metadata value : none
03-31 12:59:37.921  3461  3579 V WindowManager: Adding window Window{600f7a3 u0 d0 Starting com.test.thalitest} at 3 of 7 (after Window{23ed104f u0 d0 com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity})
03-31 12:59:37.931 11224 11224 E Zygote  : MountEmulatedStorage()
03-31 12:59:37.931 11224 11224 E Zygote  : v2
03-31 12:59:37.931 11224 11224 I libpersona: KNOX_SDCARD checking this for 10011
03-31 12:59:37.931 11224 11224 I libpersona: KNOX_SDCARD not a persona
03-31 12:59:37.936  3461  4244 I ActivityManager: Start proc 11224:com.test.thalitest/u0a11 for activity com.test.thalitest/.MainActivity
03-31 12:59:37.936  3461  4244 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
03-31 12:59:37.936  3461  4244 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-31 12:59:37.936 11224 11224 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
03-31 12:59:37.936  3461  4244 D InputDispatcher: Focused application set to: xxxx
03-31 12:59:37.936  3461  4244 D MultiWindowConverter: dismissGuide() : Before attaching the guide view, mForceDismissGuide : false
03-31 12:59:37.936  3461  4244 D InputDispatcher: Focus left window: 6571
03-31 12:59:37.936  3461  3579 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-31 12:59:37.936  3461  3579 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
03-31 12:59:37.936 11205 11205 D AndroidRuntime: Shutting down VM
03-31 12:59:37.941 11224 11224 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
03-31 12:59:37.941  2861  2861 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=404, uhalitest
03-31 12:59:37.941 11224 11224 E Zygote  : accessInfo : 0
03-31 12:59:37.941 11224 11224 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-31 12:59:37.956  3461  3579 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3461 uid:1000
03-31 12:59:37.956  3461  3579 D PointerIcon: setMouseCustomIcon IconType is same.101
03-31 12:59:37.956  3461  3579 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3461 uid:1000
03-31 12:59:37.956  3461  3579 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
03-31 12:59:37.966 11224 11224 D TimaKeyStoreProvider: TimaSignature is unavailable
03-31 12:59:37.966 11224 11224 D ActivityThread: Added TimaKeyStore provider
03-31 12:59:37.971  3461  4439 D PowerManagerService: setKeyboardVisibility: false
03-31 12:59:37.976  3461  4439 D ActivityManager:  Launching com.test.thalitest, updated priority
03-31 12:59:37.976  3461  3577 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{600f7a3 u0 d0 Starting com.test.thalitest}
03-31 12:59:37.991  3461  4439 I ActivityManager: Skip updateThumbnail for r=ActivityRecord{20f0167a u0 com.test.thalitest/.MainActivity t42}
03-31 12:59:38.001  2861  3032 I SurfaceFlinger: id=12 Removed YUIInstallC (7/9)
03-31 12:59:38.001  2861  3030 I SurfaceFlinger: id=12 Removed YUIInstallC (-2/9)
03-31 12:59:38.006  6571  6571 V ActivityThread: updateVisibility : ActivityRecord{384c2fd2 token=android.os.BinderProxy@38dc2608 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
,03-31 12:59:38.156  3461  6089 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,03-31 12:59:38.196 11224 11224 D SecWifiDisplayUtil: Metadata value : none
,03-31 12:59:38.246 11224 11224 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,03-31 12:59:38.256 11224 11224 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 9351-9353)
03-31 12:59:38.256 11224 11224 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-31 12:59:38.271 11224 11224 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {be0f583}
,03-31 12:59:38.271 11224 11224 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-31 12:59:38.271 11224 11224 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,03-31 12:59:38.276 11224 11240 W System.err: remove failed: ENOENT (No such file or directory) : /data/data/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
,03-31 12:59:38.291 11224 11224 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-31 12:59:38.291 11224 11224 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-31 12:59:38.296 11224 11224 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-31 12:59:38.321 11224 11224 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,03-31 12:59:38.321 11224 11224 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=37 off=50556 len=3379
03-31 12:59:38.321 11224 11224 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:38 off:7638088 len:1165478
,03-31 12:59:38.401 11224 11263 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,03-31 12:59:38.436 11224 11224 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-31 12:59:38.456 11224 11224 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-31 12:59:38.471 11224 11224 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-31 12:59:38.471 11224 11224 D PhoneWindow: *FMB* installDecor flags : -2139027200
,03-31 12:59:38.476 11224 11224 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,03-31 12:59:38.481 11224 11224 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-31 12:59:38.481 11224 11224 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-31 12:59:38.546 11224 11276 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,03-31 12:59:38.546  3461  3653 V WindowManager: Adding window Window{2ef614e8 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity} at 3 of 8 (before Window{600f7a3 u0 d0 Starting com.test.thalitest})
,03-31 12:59:38.551  3461  4244 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-31 12:59:38.551  3461  4244 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-31 12:59:38.551  3461  4244 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-31 12:59:38.551  3461  3461 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,03-31 12:59:38.551  3461  3461 E EnterpriseSharedDevicePolicy: isSharedDeviceEnabled
,03-31 12:59:38.556  3461  3461 I EnterpriseSharedDevicePolicy: isSharedDeviceEnabled in Service
03-31 12:59:38.556  3461  3461 I EnterpriseSharedDevicePolicy: Get Result: -1
03-31 12:59:38.556  3461  3461 I EnterpriseSharedDevicePolicy: status: false
03-31 12:59:38.556  3461  3461 I KnoxTimeoutHandler: Shared devices show user statefalse
03-31 12:59:38.556  3461  3461 D PersonaManagerService: getPersonasForUser(): returning null!
,03-31 12:59:38.566 11224 11224 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-31 12:59:38.566 11224 11224 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,03-31 12:59:38.571 11224 11224 D SecWifiDisplayUtil: Metadata value : none
,03-31 12:59:38.576  2861  2861 I SurfaceFlinger: id=15 createSurf (1x1),1 flag=404, NainActivit
,03-31 12:59:38.581  3461  3968 D MultiWindowConverter: dismissGuide() : Before attaching the guide view, mForceDismissGuide : false
,03-31 12:59:38.586  3461  3968 D InputDispatcher: Focus entered window: 11224
,03-31 12:59:38.591  3461  3579 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3461 uid:1000
03-31 12:59:38.591  3461  3579 D PointerIcon: setMouseCustomIcon IconType is same.101
03-31 12:59:38.591  3461  3579 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3461 uid:1000
03-31 12:59:38.591  3461  3579 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
03-31 12:59:38.591 11224 11224 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
03-31 12:59:38.591 11224 11276 I OpenGLRenderer: Initialized EGL, version 1.4
,03-31 12:59:38.591 11224 11276 I OpenGLRenderer: HWUI protection enabled for context ,  &this =0xae82fb50 ,&mEglDisplay = 1 , &mEglConfig = -1266863856 
,03-31 12:59:38.596 11224 11276 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
,03-31 12:59:38.596 11224 11276 D OpenGLRenderer: Enabling debug mode 0
03-31 12:59:38.596 11224 11276 D mali_winsys: new_window_surface returns 0x3000,  [1440x2560]-format:1
,03-31 12:59:38.596 11224 11224 V ActivityThread: updateVisibility : ActivityRecord{a66efeb token=android.os.BinderProxy@323abe65 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,03-31 12:59:38.666  3461  3653 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-31 12:59:38.671  3728  3728 D PanelView: There is/are notification(s) 
,03-31 12:59:38.671  3461  3579 I ActivityManager: Displayed Component not be shown by security: +543ms (total +1m21s300ms)
03-31 12:59:38.671  3461  3579 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{20f0167a u0 com.test.thalitest/.MainActivity t42} time:179768
03-31 12:59:38.671  3461  3579 W ActivityManager: mDVFSHelper.release()
,03-31 12:59:38.676  2861  3032 I SurfaceFlinger: id=14 Removed uhalitest (7/9)
,03-31 12:59:38.676  2861  3030 I SurfaceFlinger: id=14 Removed uhalitest (-2/9)
,03-31 12:59:38.701 11224 11224 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,03-31 12:59:38.701 11224 11224 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@323abe65 time:179798
,03-31 12:59:38.726 11224 11224 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 11224
,03-31 12:59:38.891 11224 11224 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-31 12:59:38.986 11224 11281 D jxcore_app_log: JniHelper::setJavaVM(0xb449d200), pthread_self() = -1626384256
,03-31 12:59:38.996 11224 11281 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-31 12:59:38.996 11224 11281 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-31 12:59:38.996 11224 11281 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-31 12:59:38.996 11224 11281 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-31 12:59:38.996 11224 11281 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-31 12:59:38.996 11224 11281 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3be63c78 added. We now have 1 listener(s)
,03-31 12:59:39.006 11224 11281 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: E0:DB:10:14:E2:C0
,03-31 12:59:39.006 11224 11281 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
,03-31 12:59:39.006 11224 11281 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-31 12:59:39.006 11224 11281 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,03-31 12:59:39.011 11224 11240 W System.err: remove failed: ENOENT (No such file or directory) : /data/data/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,03-31 12:59:39.016 11224 11281 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-31 12:59:39.016 11224 11281 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-31 12:59:39.016 11224 11281 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-31 12:59:39.016 11224 11281 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: E0:DB:10:14:E2:C0
03-31 12:59:39.016 11224 11281 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-31 12:59:39.016 11224 11281 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-31 12:59:39.016 11224 11281 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
03-31 12:59:39.016 11224 11281 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-31 12:59:39.016 11224 11281 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-31 12:59:39.016 11224 11281 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-31 12:59:39.016 11224 11281 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-31 12:59:39.016 11224 11281 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bcd08b7 added. We now have 1 listener(s)
03-31 12:59:39.016 11224 11281 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-31 12:59:39.021 11224 11281 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,03-31 12:59:39.026 11224 11281 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,03-31 12:59:39.026 11224 11281 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
,03-31 12:59:39.026 11224 11281 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-31 12:59:39.026 11224 11281 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,03-31 12:59:39.031 11224 11281 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-31 12:59:39.036 11224 11281 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is E0:DB:10:14:E2:C0
,03-31 12:59:39.046 11224 11281 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 12:59:39.046 11224 11281 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 12:59:39.046 11224 11281 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 12:59:39.046 11224 11281 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 12:59:39.046 11224 11281 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
,03-31 12:59:39.046 11224 11281 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 12:59:39.046 11224 11281 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 12:59:39.046 11224 11281 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-31 12:59:39.046 11224 11281 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-31 12:59:39.046 11224 11281 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-31 12:59:39.046 11224 11281 I io.jxcore.node.LifeCycleMonitor: start: OK
,03-31 12:59:39.051 11224 11224 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-31 12:59:39.051 11224 11224 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-31 12:59:39.086 11224 11224 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-31 12:59:39.551 11224 11287 W jxcore-log: Initializing JXcore engine
03-31 12:59:39.551 11224 11287 W jxcore-log: JXcore engine is ready
,03-31 12:59:39.581  4805  4805 E auditd  : In denial and Property audit_ondenial is set to 1 
03-31 12:59:39.581  4805  4805 E audit   : type=1400 msg=audit(1459421979.581:196): avc:  denied  { ioctl } for  pid=11287 comm="Thread-1559" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3225 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
03-31 12:59:39.581  3461  3575 D SecurityLogAgent:SEDenialService: Got Modify Event and sending Denial Intent foraudit.log
03-31 12:59:39.586  4805  4805 E audit   :  SEPF_SM-N910C_5.1.1_0038
03-31 12:59:39.586  4805  4805 E audit   : type=1300 msg=audit(1459421979.581:196): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=2 a3=97b008d8 items=0 ppid=2903 ppcomm=main pid=11287 auid=4294967295 uid=10011 gid=10011 euid=10011 suid=10011 fsuid=10011 egid=10011 sgid=10011 fsgid=10011 ses=4294967295 tty=(none) comm="Thread-1559" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
03-31 12:59:39.586  4805  4805 E audit   : type=1320 msg=audit(1459421979.581:196): 
,03-31 12:59:39.586  3461  3575 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.android.server.SEDenialService$AuditFileObserver.onEvent:80 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,03-31 12:59:39.586  3461  3575 D SecurityLogAgent:SEDenialService: audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,03-31 12:59:39.586  3461  3568 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 12:59:39.586  3461  3568 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 12:59:39.586  3461  3568 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 12:59:39.586  3461  3568 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-31 12:59:39.591 11224 11287 W jxcore-log: Starting JXcore engine
,03-31 12:59:39.601 11288 11288 E Zygote  : MountEmulatedStorage()
03-31 12:59:39.601 11288 11288 E Zygote  : v2
03-31 12:59:39.601 11288 11288 I libpersona: KNOX_SDCARD checking this for 1000
03-31 12:59:39.601 11288 11288 I libpersona: KNOX_SDCARD not a persona
,03-31 12:59:39.601 11288 11288 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
,03-31 12:59:39.601  3461  3568 I ActivityManager: Start proc 11288:com.samsung.android.securitylogagent/1000 for broadcast-3 com.samsung.android.securitylogagent/.receivers.SeDenialReceiver
,03-31 12:59:39.606 11288 11288 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
,03-31 12:59:39.606 11288 11288 E Zygote  : accessInfo : 0
,03-31 12:59:39.606 11288 11288 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-31 12:59:39.621 11288 11288 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-31 12:59:39.621 11288 11288 D ActivityThread: Added TimaKeyStore provider
,03-31 12:59:39.631  3461  3833 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{34ea452c u0 samsung.intent.action.knox.DENIAL_NOTIFICATION} DELIVERED for app ProcessRecord{14db0bf5 11288:com.samsung.android.securitylogagent/1000}
,03-31 12:59:39.646 11224 11287 W jxcore-log: Platform android
03-31 12:59:39.646 11224 11287 W jxcore-log: 
03-31 12:59:39.646 11224 11287 W jxcore-log: Process ARCH arm
03-31 12:59:39.646 11224 11287 W jxcore-log: 
,03-31 12:59:39.646 11288 11288 D SecurityLogAgent:  SeDenialReceiver : Intent received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,03-31 12:59:39.646 11288 11288 D SecurityLogAgent:  SeDenialReceiver : File path = null
,03-31 12:59:39.651  3461  4438 I ActivityManager: Killing 10238:com.sec.spp.push:RemoteNotiProcess/u0a39 (adj 15): emptyCount ##31
,03-31 12:59:39.746 11224 11287 I jxcore-log: JXcore Cordova bridge is ready!
03-31 12:59:39.746 11224 11287 I jxcore-log: 
03-31 12:59:39.746 11224 11287 W jxcore-log: JXcore engine is started
,03-31 12:59:39.751 11224 11281 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-31 12:59:39.756 11224 11224 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-31 12:59:40.921  3461  3694 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/42_task.xml.bak
,03-31 12:59:44.256  3461  4440 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 12:59:44.256  3461  4440 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 12:59:44.256  3461  4440 D BatteryService: online:4, current avg:-37, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-185
,03-31 12:59:44.256  3461  4440 D BatteryService: stay LED for fully charged
03-31 12:59:44.256  3461  3461 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 12:59:44.256  3461  3461 I MotionRecognitionService: Plugged
03-31 12:59:44.261  3461  3461 D MotionRecognitionService:   cableConnection= 1
03-31 12:59:44.261  3461  3461 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 12:59:44.261  3461  3461 D MotionRecognitionService: skip setTransmitPower. 
,03-31 12:59:44.261  3728  3728 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 12:59:44.261  3728  3728 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 12:59:44.261  3728  3728 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 12:59:44.261  3728  3728 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 12:59:44.266  5893  5893 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 12:59:44.266  5893  5980 D HeadsetStateMachine: Disconnected process message: 10
,03-31 12:59:44.281  3728  3728 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 12:59:44.281  3728  3728 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 12:59:44.281  3728  3728 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 12:59:44.641  3461  3617 V AlarmManager: waitForAlarm result :4
,03-31 12:59:44.651  3461  3568 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{194c8818 u0 null} DELIVERED for app ProcessRecord{e5a4798 4729:com.google.android.gms/u0a14}
,03-31 12:59:44.651  3461  4016 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-31 12:59:44.671  4729 11305 I EventLogService: Aggregate from 1459420173864 (log), 1459420173864 (data)
,03-31 12:59:44.721  3461  3568 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 12:59:44.721  3461  3568 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 12:59:44.721  3461  3568 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 12:59:44.721  3461  3568 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-31 12:59:44.731 11306 11306 E Zygote  : MountEmulatedStorage()
03-31 12:59:44.731 11306 11306 I libpersona: KNOX_SDCARD checking this for 1000
03-31 12:59:44.731 11306 11306 E Zygote  : v2
03-31 12:59:44.731 11306 11306 I libpersona: KNOX_SDCARD not a persona
,03-31 12:59:44.731 11306 11306 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
,03-31 12:59:44.736 11306 11306 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
03-31 12:59:44.736 11306 11306 E Zygote  : accessInfo : 0
03-31 12:59:44.736  3461  3568 I ActivityManager: Start proc 11306:com.samsung.android.sm/1000 for broadcast-3 com.samsung.android.sm/.common.SmartManagerReceiver
03-31 12:59:44.736 11306 11306 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-31 12:59:44.741  2903  2903 I art     : Explicit concurrent mark sweep GC freed 8766(373KB) AllocSpace objects, 0(0B) LOS objects, 72% free, 1529KB/5MB, paused 279us total 7.714ms
,03-31 12:59:44.746  2903  2903 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 72% free, 1529KB/5MB, paused 204us total 5.776ms
,03-31 12:59:44.756 11306 11306 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-31 12:59:44.756  2903  2903 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 72% free, 1529KB/5MB, paused 250us total 5.888ms
03-31 12:59:44.756 11306 11306 D ActivityThread: Added TimaKeyStore provider
,03-31 12:59:44.761  3461  3967 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3a45c4ad u0 android.intent.action.DROPBOX_ENTRY_ADDED} DELIVERED for app ProcessRecord{1c6fa3e2 11306:com.samsung.android.sm/1000}
,03-31 12:59:44.766 11306 11306 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-31 12:59:44.786  3461  3968 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{243d373 u0 android.intent.action.DROPBOX_ENTRY_ADDED} DELIVERED for app ProcessRecord{1c6fa3e2 11306:com.samsung.android.sm/1000}
,03-31 12:59:44.786  3461  3968 I ActivityManager: Killing 10282:com.sec.android.app.soundalive/u0a59 (adj 15): emptyCount ##31
,03-31 12:59:45.086  3461  6089 D SSRM:n  : SIOP:: AP = 280, PST = 272 (W:10), CUR = -37, LCD = 0
,03-31 12:59:45.591 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 12:59:45.591 11224 11287 I jxcore-log: 
,03-31 12:59:45.596 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 12:59:45.596 11224 11287 I jxcore-log: 
,03-31 12:59:45.596 11224 11287 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 12:59:45.596 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 12:59:45.596 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 12:59:45.596 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 12:59:45.596 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 12:59:45.596 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 12:59:45.596 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 12:59:45.596 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-31 12:59:45.596 11224 11287 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
03-31 12:59:45.601 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 12:59:45.601 11224 11287 I jxcore-log: 
03-31 12:59:45.601 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 12:59:45.601 11224 11287 I jxcore-log: 
,03-31 12:59:45.921 11224 11287 I jxcore-log: Unit Test app is loaded
03-31 12:59:45.921 11224 11287 I jxcore-log: 
,03-31 12:59:45.926 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 12:59:45.926 11224 11287 I jxcore-log: 
,03-31 12:59:45.931 11224 11224 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,03-31 12:59:45.931 11224 11287 I jxcore-log: My device name is: samsung-SM-N910C
03-31 12:59:45.931 11224 11287 I jxcore-log: 
,03-31 12:59:47.961  3461  3587 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,03-31 12:59:47.971  3461  3587 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,03-31 12:59:48.326 11224 11287 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
03-31 12:59:48.326 11224 11287 I jxcore-log: 
,03-31 12:59:48.536 11224 11287 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
03-31 12:59:48.536 11224 11287 I jxcore-log: 
,03-31 12:59:48.541 11224 11287 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
03-31 12:59:48.541 11224 11287 I jxcore-log: 
,03-31 12:59:48.546 11224 11287 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
03-31 12:59:48.546 11224 11287 I jxcore-log: 
,03-31 12:59:48.566 11224 11287 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
03-31 12:59:48.566 11224 11287 I jxcore-log: 
,03-31 12:59:48.576 11224 11287 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
03-31 12:59:48.576 11224 11287 I jxcore-log: 
,03-31 12:59:48.576 11224 11287 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
03-31 12:59:48.576 11224 11287 I jxcore-log: 
,03-31 12:59:48.786  3461  6120 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-31 12:59:49.806 11224 11287 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
03-31 12:59:49.806 11224 11287 I jxcore-log: 
,03-31 12:59:49.816 11224 11287 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
03-31 12:59:49.816 11224 11287 I jxcore-log: 
,03-31 12:59:49.821 11224 11287 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
03-31 12:59:49.821 11224 11287 I jxcore-log: 
,03-31 12:59:49.971 11224 11287 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
03-31 12:59:49.971 11224 11287 I jxcore-log: 
,03-31 12:59:50.011 11224 11287 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
03-31 12:59:50.011 11224 11287 I jxcore-log: 
,03-31 12:59:50.046 11224 11287 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
03-31 12:59:50.046 11224 11287 I jxcore-log: 
,03-31 12:59:50.046 11224 11287 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
03-31 12:59:50.046 11224 11287 I jxcore-log: 
,03-31 12:59:50.056 11224 11287 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
03-31 12:59:50.056 11224 11287 I jxcore-log: 
,03-31 12:59:50.056 11224 11287 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
03-31 12:59:50.056 11224 11287 I jxcore-log: 
,03-31 12:59:50.061 11224 11287 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
03-31 12:59:50.061 11224 11287 I jxcore-log: 
,03-31 12:59:50.066 11224 11287 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
03-31 12:59:50.066 11224 11287 I jxcore-log: 
,03-31 12:59:50.081 11224 11287 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
03-31 12:59:50.081 11224 11287 I jxcore-log: 
,03-31 12:59:50.126 11224 11287 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
03-31 12:59:50.126 11224 11287 I jxcore-log: 
,03-31 12:59:50.131 11224 11287 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
03-31 12:59:50.131 11224 11287 I jxcore-log: 
,03-31 12:59:50.146 11224 11287 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
03-31 12:59:50.146 11224 11287 I jxcore-log: 
,03-31 12:59:50.151 11224 11287 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,03-31 12:59:50.151 11224 11287 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
03-31 12:59:50.151 11224 11287 I jxcore-log: 
,03-31 12:59:51.551  3461  3867 E Watchdog: !@Sync 6 [03-31 12:59:51.551]
,03-31 12:59:54.406  3461  3967 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-31 12:59:54.406  3461  3967 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
,03-31 12:59:54.406  3461  3967 D BatteryService: online:4, current avg:-54, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:51
03-31 12:59:54.406  3461  3967 D BatteryService: stay LED for fully charged
03-31 12:59:54.406  3461  3461 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 12:59:54.411  3461  3461 I MotionRecognitionService: Plugged
,03-31 12:59:54.411  3461  3461 D MotionRecognitionService:   cableConnection= 1
03-31 12:59:54.411  3461  3461 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 12:59:54.411  3461  3461 D MotionRecognitionService: skip setTransmitPower. 
,03-31 12:59:54.416  3728  3728 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 12:59:54.416  3728  3728 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 12:59:54.416  3728  3728 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 12:59:54.436  5893  5893 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 12:59:54.436  5893  5980 D HeadsetStateMachine: Disconnected process message: 10
,03-31 12:59:54.446  3728  3728 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 12:59:54.446  3728  3728 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 12:59:54.446  3728  3728 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 12:59:54.446  3728  3728 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 12:59:54.871  2893  4818 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-31 12:59:55.116  3461  6089 D SSRM:n  : SIOP:: AP = 290, PST = 268 (W:10), CUR = -54, LCD = 0
,03-31 12:59:59.996  3461  3617 V AlarmManager: waitForAlarm result :8
,03-31 13:00:04.536  3461  3653 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 13:00:04.536  3461  3653 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 13:00:04.536  3461  3653 D BatteryService: online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:70
,03-31 13:00:04.536  3461  3461 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 13:00:04.541  3461  3653 D BatteryService: stay LED for fully charged
,03-31 13:00:04.546  3461  3461 I MotionRecognitionService: Plugged,
,03-31 13:00:04.546  3461  3461 D MotionRecognitionService:   cableConnection= 1,
03-31 13:00:04.546  3461  3461 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-31 13:00:04.546  3461  3461 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 13:00:04.561  3728  3728 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 13:00:04.561  3728  3728 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,03-31 13:00:04.561  3728  3728 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-31 13:00:04.581  5893  5893 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 13:00:04.581  5893  5980 D HeadsetStateMachine: Disconnected process message: 10
,03-31 13:00:04.591  3728  3728 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 13:00:04.591  3728  3728 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 13:00:04.591  3728  3728 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 13:00:04.591  3728  3728 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 13:00:04.746  3461  3581 I PowerManagerService: [PWL] Off : 140s ago
,03-31 13:00:05.146  3461  6089 D SSRM:n  : SIOP:: AP = 280, PST = 269 (W:10), CUR = 11, LCD = 0
,03-31 13:00:08.686 11224 11287 I jxcore-log: TAP version 13
03-31 13:00:08.686 11224 11287 I jxcore-log: 
,03-31 13:00:08.691 11224 11287 I jxcore-log: # setup
03-31 13:00:08.691 11224 11287 I jxcore-log: 
,03-31 13:00:08.771 11224 11287 I jxcore-log: # 1. calling createNativeListener directly rejects
03-31 13:00:08.771 11224 11287 I jxcore-log: 
,03-31 13:00:08.791  3461  6120 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-31 13:00:09.326 11224 11287 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 13:00:09.326 11224 11287 I jxcore-log: 
,03-31 13:00:09.336 11224 11287 I jxcore-log: DEBUG createNativeListener: listening 48313
03-31 13:00:09.336 11224 11287 I jxcore-log: 
,03-31 13:00:09.346 11224 11287 I jxcore-log: ok 1 Should throw
03-31 13:00:09.346 11224 11287 I jxcore-log: 
,03-31 13:00:09.351 11224 11287 I jxcore-log: # teardown
03-31 13:00:09.351 11224 11287 I jxcore-log: 
,03-31 13:00:09.636 11224 11287 I jxcore-log: # setup
03-31 13:00:09.636 11224 11287 I jxcore-log: 
,03-31 13:00:09.946 11224 11287 I jxcore-log: # 2. emits incomingConnectionState
03-31 13:00:09.946 11224 11287 I jxcore-log: 
,03-31 13:00:10.111 11224 11287 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 13:00:10.111 11224 11287 I jxcore-log: 
,03-31 13:00:10.121 11224 11287 I jxcore-log: DEBUG createNativeListener: listening 51917
03-31 13:00:10.121 11224 11287 I jxcore-log: 
,03-31 13:00:10.136 11224 11287 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 13:00:10.136 11224 11287 I jxcore-log: 
,03-31 13:00:10.141 11224 11287 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 13:00:10.141 11224 11287 I jxcore-log: 
,03-31 13:00:10.151 11224 11287 I jxcore-log: DEBUG createNativeListener: new mux
03-31 13:00:10.151 11224 11287 I jxcore-log: 
,03-31 13:00:10.161 11224 11287 I jxcore-log: ok 2 initial connection state should be CONNECTED
03-31 13:00:10.161 11224 11287 I jxcore-log: 
,03-31 13:00:10.186 11224 11287 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 13:00:10.186 11224 11287 I jxcore-log: 
,03-31 13:00:10.186 11224 11287 I jxcore-log: ok 3 final connection state should be DISCONNECTED
03-31 13:00:10.186 11224 11287 I jxcore-log: 
,03-31 13:00:10.196 11224 11287 I jxcore-log: # teardown
03-31 13:00:10.196 11224 11287 I jxcore-log: 
,03-31 13:00:10.411 11224 11287 I jxcore-log: # setup
03-31 13:00:10.411 11224 11287 I jxcore-log: 
,03-31 13:00:10.571 11224 11287 I jxcore-log: # 3. emits routerPortConnectionFailed
03-31 13:00:10.571 11224 11287 I jxcore-log: 
,03-31 13:00:10.751 11224 11287 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 13:00:10.751 11224 11287 I jxcore-log: 
,03-31 13:00:10.751 11224 11287 I jxcore-log: DEBUG createNativeListener: listening 54726
03-31 13:00:10.751 11224 11287 I jxcore-log: 
,03-31 13:00:10.761 11224 11287 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 13:00:10.761 11224 11287 I jxcore-log: 
,03-31 13:00:10.761 11224 11287 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 13:00:10.761 11224 11287 I jxcore-log: 
,03-31 13:00:10.766 11224 11287 I jxcore-log: DEBUG createNativeListener: new mux
03-31 13:00:10.766 11224 11287 I jxcore-log: 
,03-31 13:00:10.801 11224 11287 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 13:00:10.801 11224 11287 I jxcore-log: 
,03-31 13:00:10.806 11224 11287 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 13:00:10.806 11224 11287 I jxcore-log: 
,03-31 13:00:10.811 11224 11287 I jxcore-log: DEBUG createNativeListener: 
03-31 13:00:10.811 11224 11287 I jxcore-log: 
,03-31 13:00:10.816 11224 11287 I jxcore-log: ok 4 tried to connect to right port
03-31 13:00:10.816 11224 11287 I jxcore-log: 
,03-31 13:00:10.821 11224 11287 I jxcore-log: ok 5 failed due to refused connection
03-31 13:00:10.821 11224 11287 I jxcore-log: 
,03-31 13:00:10.826 11224 11287 I jxcore-log: ok 6 routerPortConnectionFailed is emitted
03-31 13:00:10.826 11224 11287 I jxcore-log: 
,03-31 13:00:10.831 11224 11287 I jxcore-log: # teardown
03-31 13:00:10.831 11224 11287 I jxcore-log: 
,03-31 13:00:10.831 11224 11287 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 13:00:10.831 11224 11287 I jxcore-log: 
,03-31 13:00:10.946 11224 11287 I jxcore-log: DEBUG createNativeListener: mux close
03-31 13:00:10.946 11224 11287 I jxcore-log: 
,03-31 13:00:10.956 11224 11287 I jxcore-log: # setup
03-31 13:00:10.956 11224 11287 I jxcore-log: 
,03-31 13:00:10.956 11224 11287 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 13:00:10.956 11224 11287 I jxcore-log: 
,03-31 13:00:11.251 11224 11287 I jxcore-log: # 4. native server connections all up
03-31 13:00:11.251 11224 11287 I jxcore-log: 
,03-31 13:00:11.496 11224 11287 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 13:00:11.496 11224 11287 I jxcore-log: 
,03-31 13:00:11.506 11224 11287 I jxcore-log: DEBUG createNativeListener: listening 58038
03-31 13:00:11.506 11224 11287 I jxcore-log: 
,03-31 13:00:11.521 11224 11287 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 13:00:11.521 11224 11287 I jxcore-log: 
,03-31 13:00:11.526 11224 11287 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 13:00:11.526 11224 11287 I jxcore-log: 
,03-31 13:00:11.526 11224 11287 I jxcore-log: DEBUG createNativeListener: new mux
03-31 13:00:11.526 11224 11287 I jxcore-log: 
,03-31 13:00:11.566 11224 11287 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 13:00:11.566 11224 11287 I jxcore-log: 
,03-31 13:00:11.571 11224 11287 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 13:00:11.571 11224 11287 I jxcore-log: 
,03-31 13:00:11.576 11224 11287 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 13:00:11.576 11224 11287 I jxcore-log: 
,03-31 13:00:11.576 11224 11287 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 13:00:11.576 11224 11287 I jxcore-log: 
,03-31 13:00:11.621 11224 11287 I jxcore-log: ok 7 Send/recvd #1 should be equal length
03-31 13:00:11.621 11224 11287 I jxcore-log: 
,03-31 13:00:11.621 11224 11287 I jxcore-log: ok 8 Send/recvd #1 should be same
03-31 13:00:11.621 11224 11287 I jxcore-log: 
,03-31 13:00:11.626 11224 11287 I jxcore-log: ok 9 Send/recvd #2 should be equal length
03-31 13:00:11.626 11224 11287 I jxcore-log: 
,03-31 13:00:11.626 11224 11287 I jxcore-log: ok 10 Send/recvd #2 should be same
03-31 13:00:11.626 11224 11287 I jxcore-log: 
,03-31 13:00:11.631 11224 11287 I jxcore-log: ok 11 Should be exactly 2 client sockets
03-31 13:00:11.631 11224 11287 I jxcore-log: 
,03-31 13:00:11.641 11224 11287 I jxcore-log: # teardown
03-31 13:00:11.641 11224 11287 I jxcore-log: 
,03-31 13:00:11.841 11224 11287 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 13:00:11.841 11224 11287 I jxcore-log: 
,03-31 13:00:11.846 11224 11287 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 13:00:11.846 11224 11287 I jxcore-log: 
,03-31 13:00:11.851 11224 11287 I jxcore-log: DEBUG createNativeListener: mux close
03-31 13:00:11.851 11224 11287 I jxcore-log: 
,03-31 13:00:11.856 11224 11287 I jxcore-log: # setup
03-31 13:00:11.856 11224 11287 I jxcore-log: 
,03-31 13:00:11.856 11224 11287 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 13:00:11.856 11224 11287 I jxcore-log: 
,03-31 13:00:12.511 11224 11287 I jxcore-log: # 5. native server - closing incoming stream cleans outgoing socket
03-31 13:00:12.511 11224 11287 I jxcore-log: 
,03-31 13:00:12.656 11224 11287 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 13:00:12.656 11224 11287 I jxcore-log: 
,03-31 13:00:12.666 11224 11287 I jxcore-log: DEBUG createNativeListener: listening 51634
03-31 13:00:12.666 11224 11287 I jxcore-log: 
,03-31 13:00:12.676 11224 11287 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 13:00:12.676 11224 11287 I jxcore-log: 
,03-31 13:00:12.681 11224 11287 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 13:00:12.681 11224 11287 I jxcore-log: 
,03-31 13:00:12.686 11224 11287 I jxcore-log: DEBUG createNativeListener: new mux
03-31 13:00:12.686 11224 11287 I jxcore-log: 
,03-31 13:00:12.696 11224 11287 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 13:00:12.696 11224 11287 I jxcore-log: 
,03-31 13:00:12.701 11224 11287 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 13:00:12.701 11224 11287 I jxcore-log: 
,03-31 13:00:12.721 11224 11287 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 13:00:12.721 11224 11287 I jxcore-log: 
,03-31 13:00:12.741 11224 11287 I jxcore-log: ok 12 socket shouldn't close until after stream
03-31 13:00:12.741 11224 11287 I jxcore-log: 
,03-31 13:00:12.741 11224 11287 I jxcore-log: ok 13 incoming remains open
03-31 13:00:12.741 11224 11287 I jxcore-log: 
,03-31 13:00:12.746 11224 11287 I jxcore-log: # teardown
03-31 13:00:12.746 11224 11287 I jxcore-log: 
,03-31 13:00:12.901 11224 11287 I jxcore-log: DEBUG createNativeListener: mux close
03-31 13:00:12.901 11224 11287 I jxcore-log: 
,03-31 13:00:12.911 11224 11287 I jxcore-log: # setup
03-31 13:00:12.911 11224 11287 I jxcore-log: 
,03-31 13:00:12.916 11224 11287 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 13:00:12.916 11224 11287 I jxcore-log: 
,03-31 13:00:13.041 11224 11287 I jxcore-log: # 6. native server - closing incoming connection cleans outgoing socket
03-31 13:00:13.041 11224 11287 I jxcore-log: 
,03-31 13:00:13.136 11224 11287 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 13:00:13.136 11224 11287 I jxcore-log: 
,03-31 13:00:13.141 11224 11287 I jxcore-log: DEBUG createNativeListener: listening 37180
03-31 13:00:13.141 11224 11287 I jxcore-log: 
,03-31 13:00:13.151 11224 11287 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 13:00:13.151 11224 11287 I jxcore-log: 
,03-31 13:00:13.156 11224 11287 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 13:00:13.156 11224 11287 I jxcore-log: 
,03-31 13:00:13.161 11224 11287 I jxcore-log: DEBUG createNativeListener: new mux
03-31 13:00:13.161 11224 11287 I jxcore-log: 
,03-31 13:00:13.171 11224 11287 I jxcore-log: ok 14 we should not have gotten an error
03-31 13:00:13.171 11224 11287 I jxcore-log: 
,03-31 13:00:13.181 11224 11287 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 13:00:13.181 11224 11287 I jxcore-log: 
,03-31 13:00:13.186 11224 11287 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 13:00:13.186 11224 11287 I jxcore-log: 
,03-31 13:00:13.201 11224 11287 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 13:00:13.201 11224 11287 I jxcore-log: 
,03-31 13:00:13.206 11224 11287 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 13:00:13.206 11224 11287 I jxcore-log: 
,03-31 13:00:13.216 11224 11287 I jxcore-log: ok 15 socket shouldn't close until after incoming
03-31 13:00:13.216 11224 11287 I jxcore-log: 
,03-31 13:00:13.216 11224 11287 I jxcore-log: ok 16 incoming is cleaned up
03-31 13:00:13.216 11224 11287 I jxcore-log: 
,03-31 13:00:13.226 11224 11287 I jxcore-log: # teardown
03-31 13:00:13.226 11224 11287 I jxcore-log: 
,03-31 13:00:13.291 11224 11287 I jxcore-log: # setup
03-31 13:00:13.291 11224 11287 I jxcore-log: 
,03-31 13:00:13.481 11224 11287 I jxcore-log: # 7. native server - closing outgoing socket cleans associated mux stream
03-31 13:00:13.481 11224 11287 I jxcore-log: 
,03-31 13:00:13.706 11224 11287 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 13:00:13.706 11224 11287 I jxcore-log: 
,03-31 13:00:13.721 11224 11287 I jxcore-log: DEBUG createNativeListener: listening 53536
03-31 13:00:13.721 11224 11287 I jxcore-log: 
,03-31 13:00:13.731 11224 11287 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 13:00:13.731 11224 11287 I jxcore-log: 
,03-31 13:00:13.731 11224 11287 I jxcore-log: DEBUG createNativeListener: creating incoming mux,
03-31 13:00:13.731 11224 11287 I jxcore-log: 
,03-31 13:00:13.741 11224 11287 I jxcore-log: DEBUG createNativeListener: new mux
03-31 13:00:13.741 11224 11287 I jxcore-log: 
,03-31 13:00:13.756 11224 11287 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 13:00:13.756 11224 11287 I jxcore-log: 
,03-31 13:00:13.761 11224 11287 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 13:00:13.761 11224 11287 I jxcore-log: 
,03-31 13:00:13.776 11224 11287 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 13:00:13.776 11224 11287 I jxcore-log: 
,03-31 13:00:13.791 11224 11287 I jxcore-log: ok 17 stream was closed
03-31 13:00:13.791 11224 11287 I jxcore-log: 
,03-31 13:00:13.791 11224 11287 I jxcore-log: ok 18 incoming should survive
03-31 13:00:13.791 11224 11287 I jxcore-log: 
,03-31 13:00:13.791 11224 11287 I jxcore-log: ok 19 mux should have no streams
03-31 13:00:13.791 11224 11287 I jxcore-log: 
,03-31 13:00:13.801 11224 11287 I jxcore-log: # teardown
03-31 13:00:13.801 11224 11287 I jxcore-log: 
,03-31 13:00:13.881 11224 11287 I jxcore-log: DEBUG createNativeListener: mux close
03-31 13:00:13.881 11224 11287 I jxcore-log: 
,03-31 13:00:13.896 11224 11287 I jxcore-log: # setup
03-31 13:00:13.896 11224 11287 I jxcore-log: 
,03-31 13:00:13.896 11224 11287 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 13:00:13.896 11224 11287 I jxcore-log: 
,03-31 13:00:14.016 11224 11287 I jxcore-log: # 8. native server - closing the whole server cleans everything up
03-31 13:00:14.016 11224 11287 I jxcore-log: 
,03-31 13:00:14.226 11224 11287 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 13:00:14.226 11224 11287 I jxcore-log: 
,03-31 13:00:14.231 11224 11287 I jxcore-log: DEBUG createNativeListener: listening 36823
03-31 13:00:14.231 11224 11287 I jxcore-log: 
,03-31 13:00:14.241 11224 11287 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 13:00:14.241 11224 11287 I jxcore-log: 
,03-31 13:00:14.246 11224 11287 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 13:00:14.246 11224 11287 I jxcore-log: 
,03-31 13:00:14.246 11224 11287 I jxcore-log: DEBUG createNativeListener: new mux
03-31 13:00:14.246 11224 11287 I jxcore-log: 
,03-31 13:00:14.261 11224 11287 I jxcore-log: ok 20 we should not have gotten an error
03-31 13:00:14.261 11224 11287 I jxcore-log: 
,03-31 13:00:14.266 11224 11287 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 13:00:14.266 11224 11287 I jxcore-log: 
,03-31 13:00:14.271 11224 11287 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 13:00:14.271 11224 11287 I jxcore-log: 
,03-31 13:00:14.286 11224 11287 I jxcore-log: ok 21 Buffers are identical
03-31 13:00:14.286 11224 11287 I jxcore-log: 
,03-31 13:00:14.291 11224 11287 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 13:00:14.291 11224 11287 I jxcore-log: 
,03-31 13:00:14.296 11224 11287 I jxcore-log: DEBUG createNativeListener: mux close
03-31 13:00:14.296 11224 11287 I jxcore-log: 
,03-31 13:00:14.301 11224 11287 I jxcore-log: ok 22 native server is nulled out
03-31 13:00:14.301 11224 11287 I jxcore-log: 
03-31 13:00:14.301 11224 11287 I jxcore-log: ok 23 native server should be closed
03-31 13:00:14.301 11224 11287 I jxcore-log: 
,03-31 13:00:14.301 11224 11287 I jxcore-log: ok 24 incoming has been removed
03-31 13:00:14.301 11224 11287 I jxcore-log: 
,03-31 13:00:14.306 11224 11287 I jxcore-log: ok 25 Incoming should be done
03-31 13:00:14.306 11224 11287 I jxcore-log: 
,03-31 13:00:14.306 11224 11287 I jxcore-log: ok 26 The mux object should be closed
03-31 13:00:14.306 11224 11287 I jxcore-log: 
,03-31 13:00:14.306 11224 11287 I jxcore-log: ok 27 The mux stream should be closed
03-31 13:00:14.306 11224 11287 I jxcore-log: 
,03-31 13:00:14.306 11224 11287 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 13:00:14.306 11224 11287 I jxcore-log: 
,03-31 13:00:14.326 11224 11287 I jxcore-log: # teardown
03-31 13:00:14.326 11224 11287 I jxcore-log: 
,03-31 13:00:14.416 11224 11287 I jxcore-log: # setup
03-31 13:00:14.416 11224 11287 I jxcore-log: 
,03-31 13:00:14.551 11224 11287 I jxcore-log: # 9. native server - we can get a ton of connections and data through and still clean up the server completely
03-31 13:00:14.551 11224 11287 I jxcore-log: 
,03-31 13:00:14.646  3461  3967 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-31 13:00:14.646  3461  3967 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 13:00:14.646  3461  3967 D BatteryService: online:4, current avg:34, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:35
03-31 13:00:14.646  3461  3967 D BatteryService: stay LED for fully charged
03-31 13:00:14.646  3461  3461 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 13:00:14.651  3461  3461 I MotionRecognitionService: Plugged
03-31 13:00:14.651  3461  3461 D MotionRecognitionService:   cableConnection= 1
03-31 13:00:14.651  3461  3461 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 13:00:14.651  3461  3461 D MotionRecognitionService: skip setTransmitPower. 
,03-31 13:00:14.651  3728  3728 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 13:00:14.651  3728  3728 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 13:00:14.651  3728  3728 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 13:00:14.661  5893  5893 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 13:00:14.661  5893  5980 D HeadsetStateMachine: Disconnected process message: 10
,03-31 13:00:14.676  3728  3728 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 13:00:14.676  3728  3728 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 13:00:14.676  3728  3728 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 13:00:14.676  3728  3728 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 13:00:14.711 11224 11287 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 13:00:14.711 11224 11287 I jxcore-log: 
,03-31 13:00:14.716 11224 11287 I jxcore-log: DEBUG createNativeListener: listening 35582
03-31 13:00:14.716 11224 11287 I jxcore-log: 
,03-31 13:00:14.766 11224 11287 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 13:00:14.766 11224 11287 I jxcore-log: 
,03-31 13:00:14.766 11224 11287 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 13:00:14.766 11224 11287 I jxcore-log: 
,03-31 13:00:14.771 11224 11287 I jxcore-log: DEBUG createNativeListener: new mux
03-31 13:00:14.771 11224 11287 I jxcore-log: 
,03-31 13:00:14.776 11224 11287 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 13:00:14.776 11224 11287 I jxcore-log: 
,03-31 13:00:14.776 11224 11287 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 13:00:14.776 11224 11287 I jxcore-log: 
,03-31 13:00:14.781 11224 11287 I jxcore-log: DEBUG createNativeListener: new mux
03-31 13:00:14.781 11224 11287 I jxcore-log: 
,03-31 13:00:14.786 11224 11287 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 13:00:14.786 11224 11287 I jxcore-log: 
,03-31 13:00:14.786 11224 11287 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 13:00:14.786 11224 11287 I jxcore-log: 
,03-31 13:00:14.791 11224 11287 I jxcore-log: DEBUG createNativeListener: new mux
03-31 13:00:14.791 11224 11287 I jxcore-log: 
,03-31 13:00:14.796 11224 11287 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 13:00:14.796 11224 11287 I jxcore-log: 
,03-31 13:00:14.796 11224 11287 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 13:00:14.796 11224 11287 I jxcore-log: 
,03-31 13:00:14.801 11224 11287 I jxcore-log: DEBUG createNativeListener: new mux
03-31 13:00:14.801 11224 11287 I jxcore-log: 
,03-31 13:00:14.806 11224 11287 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 13:00:14.806 11224 11287 I jxcore-log: 
,03-31 13:00:14.811 11224 11287 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 13:00:14.811 11224 11287 I jxcore-log: 
,03-31 13:00:14.811 11224 11287 I jxcore-log: DEBUG createNativeListener: new mux
03-31 13:00:14.811 11224 11287 I jxcore-log: 
,03-31 13:00:14.816 11224 11287 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 13:00:14.816 11224 11287 I jxcore-log: 
,03-31 13:00:14.821 11224 11287 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 13:00:14.821 11224 11287 I jxcore-log: 
,03-31 13:00:14.821 11224 11287 I jxcore-log: DEBUG createNativeListener: new mux
03-31 13:00:14.821 11224 11287 I jxcore-log: 
,03-31 13:00:14.826 11224 11287 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 13:00:14.826 11224 11287 I jxcore-log: 
,03-31 13:00:14.826 11224 11287 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 13:00:14.826 11224 11287 I jxcore-log: 
,03-31 13:00:14.831 11224 11287 I jxcore-log: DEBUG createNativeListener: new mux
03-31 13:00:14.831 11224 11287 I jxcore-log: 
,03-31 13:00:14.836 11224 11287 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 13:00:14.836 11224 11287 I jxcore-log: 
,03-31 13:00:14.836 11224 11287 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 13:00:14.836 11224 11287 I jxcore-log: 
,03-31 13:00:14.841 11224 11287 I jxcore-log: DEBUG createNativeListener: new mux
03-31 13:00:14.841 11224 11287 I jxcore-log: 
,03-31 13:00:14.841 11224 11287 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 13:00:14.841 11224 11287 I jxcore-log: 
,03-31 13:00:14.841 11224 11287 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 13:00:14.841 11224 11287 I jxcore-log: 
,03-31 13:00:14.846 11224 11287 I jxcore-log: DEBUG createNativeListener: new mux
03-31 13:00:14.846 11224 11287 I jxcore-log: 
,03-31 13:00:14.846 11224 11287 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 13:00:14.846 11224 11287 I jxcore-log: 
,03-31 13:00:14.851 11224 11287 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 13:00:14.851 11224 11287 I jxcore-log: 
,03-31 13:00:14.851 11224 11287 I jxcore-log: DEBUG createNativeListener: new mux
03-31 13:00:14.851 11224 11287 I jxcore-log: 
,03-31 13:00:14.986 11224 11287 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 13:00:14.986 11224 11287 I jxcore-log: 
,03-31 13:00:14.991 11224 11287 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 13:00:14.991 11224 11287 I jxcore-log: 
,03-31 13:00:14.991 11224 11287 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 13:00:14.991 11224 11287 I jxcore-log: 
,03-31 13:00:14.991 11224 11287 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 13:00:14.991 11224 11287 I jxcore-log: 
,03-31 13:00:14.991 11224 11287 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 13:00:14.991 11224 11287 I jxcore-log: 
,03-31 13:00:14.996 11224 11287 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 13:00:14.996 11224 11287 I jxcore-log: 
,03-31 13:00:14.996 11224 11287 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 13:00:14.996 11224 11287 I jxcore-log: 
,03-31 13:00:15.001 11224 11287 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 13:00:15.001 11224 11287 I jxcore-log: 
,03-31 13:00:15.001 11224 11287 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 13:00:15.001 11224 11287 I jxcore-log: 
,03-31 13:00:15.006 11224 11287 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 13:00:15.006 11224 11287 I jxcore-log: 
,03-31 13:00:15.006 11224 11287 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 13:00:15.006 11224 11287 I jxcore-log: 
,03-31 13:00:15.006 11224 11287 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 13:00:15.006 11224 11287 I jxcore-log: 
,03-31 13:00:15.006 11224 11287 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 13:00:15.006 11224 11287 I jxcore-log: 
,03-31 13:00:15.011 11224 11287 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 13:00:15.011 11224 11287 I jxcore-log: 
,03-31 13:00:15.011 11224 11287 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 13:00:15.011 11224 11287 I jxcore-log: 
,03-31 13:00:15.011 11224 11287 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 13:00:15.011 11224 11287 I jxcore-log: 
,03-31 13:00:15.016 11224 11287 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 13:00:15.016 11224 11287 I jxcore-log: 
,03-31 13:00:15.016 11224 11287 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 13:00:15.016 11224 11287 I jxcore-log: 
,03-31 13:00:15.016 11224 11287 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 13:00:15.016 11224 11287 I jxcore-log: 
,03-31 13:00:15.021 11224 11287 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 13:00:15.021 11224 11287 I jxcore-log: 
,03-31 13:00:15.026 11224 11287 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 13:00:15.026 11224 11287 I jxcore-log: 
,03-31 13:00:15.026 11224 11287 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 13:00:15.026 11224 11287 I jxcore-log: 
,03-31 13:00:15.026 11224 11287 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 13:00:15.026 11224 11287 I jxcore-log: 
,03-31 13:00:15.031 11224 11287 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 13:00:15.031 11224 11287 I jxcore-log: 
,03-31 13:00:15.031 11224 11287 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 13:00:15.031 11224 11287 I jxcore-log: 
,03-31 13:00:15.031 11224 11287 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 13:00:15.031 11224 11287 I jxcore-log: 
,03-31 13:00:15.036 11224 11287 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 13:00:15.036 11224 11287 I jxcore-log: 
,03-31 13:00:15.036 11224 11287 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 13:00:15.036 11224 11287 I jxcore-log: 
,03-31 13:00:15.036 11224 11287 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 13:00:15.036 11224 11287 I jxcore-log: 
,03-31 13:00:15.036 11224 11287 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 13:00:15.036 11224 11287 I jxcore-log: 
,03-31 13:00:15.041 11224 11287 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 13:00:15.041 11224 11287 I jxcore-log: 
,03-31 13:00:15.041 11224 11287 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 13:00:15.041 11224 11287 I jxcore-log: 
,03-31 13:00:15.041 11224 11287 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 13:00:15.041 11224 11287 I jxcore-log: 
,03-31 13:00:15.046 11224 11287 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 13:00:15.046 11224 11287 I jxcore-log: 
,03-31 13:00:15.046 11224 11287 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 13:00:15.046 11224 11287 I jxcore-log: 
,03-31 13:00:15.046 11224 11287 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 13:00:15.046 11224 11287 I jxcore-log: 
,03-31 13:00:15.046 11224 11287 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 13:00:15.046 11224 11287 I jxcore-log: 
,03-31 13:00:15.051 11224 11287 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 13:00:15.051 11224 11287 I jxcore-log: 
,03-31 13:00:15.051 11224 11287 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 13:00:15.051 11224 11287 I jxcore-log: 
,03-31 13:00:15.051 11224 11287 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 13:00:15.051 11224 11287 I jxcore-log: 
,03-31 13:00:15.056 11224 11287 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 13:00:15.056 11224 11287 I jxcore-log: 
,03-31 13:00:15.056 11224 11287 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 13:00:15.056 11224 11287 I jxcore-log: 
,03-31 13:00:15.056 11224 11287 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 13:00:15.056 11224 11287 I jxcore-log: 
,03-31 13:00:15.056 11224 11287 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 13:00:15.056 11224 11287 I jxcore-log: 
,03-31 13:00:15.061 11224 11287 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 13:00:15.061 11224 11287 I jxcore-log: 
,03-31 13:00:15.061 11224 11287 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 13:00:15.061 11224 11287 I jxcore-log: 
,03-31 13:00:15.061 11224 11287 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 13:00:15.061 11224 11287 I jxcore-log: 
,03-31 13:00:15.061 11224 11287 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 13:00:15.061 11224 11287 I jxcore-log: 
,03-31 13:00:15.071 11224 11287 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 13:00:15.071 11224 11287 I jxcore-log: 
,03-31 13:00:15.076 11224 11287 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 13:00:15.076 11224 11287 I jxcore-log: 
,03-31 13:00:15.076 11224 11287 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 13:00:15.076 11224 11287 I jxcore-log: 
,03-31 13:00:15.076 11224 11287 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 13:00:15.076 11224 11287 I jxcore-log: 
,03-31 13:00:15.076 11224 11287 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 13:00:15.076 11224 11287 I jxcore-log: 
,03-31 13:00:15.081 11224 11287 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 13:00:15.081 11224 11287 I jxcore-log: 
,03-31 13:00:15.081 11224 11287 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 13:00:15.081 11224 11287 I jxcore-log: 
,03-31 13:00:15.081 11224 11287 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 13:00:15.081 11224 11287 I jxcore-log: 
,03-31 13:00:15.086 11224 11287 I jxcore-log: DEBUG createNativeListener: new stream: ,
03-31 13:00:15.086 11224 11287 I jxcore-log: 
,03-31 13:00:15.086 11224 11287 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 13:00:15.086 11224 11287 I jxcore-log: 
,03-31 13:00:15.086 11224 11287 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 13:00:15.086 11224 11287 I jxcore-log: 
,03-31 13:00:15.091 11224 11287 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 13:00:15.091 11224 11287 I jxcore-log: 
,03-31 13:00:15.091 11224 11287 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 13:00:15.091 11224 11287 I jxcore-log: 
,03-31 13:00:15.091 11224 11287 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 13:00:15.091 11224 11287 I jxcore-log: 
,03-31 13:00:15.096 11224 11287 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 13:00:15.096 11224 11287 I jxcore-log: 
,03-31 13:00:15.096 11224 11287 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 13:00:15.096 11224 11287 I jxcore-log: 
,03-31 13:00:15.096 11224 11287 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 13:00:15.096 11224 11287 I jxcore-log: 
,03-31 13:00:15.096 11224 11287 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 13:00:15.096 11224 11287 I jxcore-log: 
,03-31 13:00:15.101 11224 11287 I jxcore-log: DEBUG createNativeListener: new stream: ,
03-31 13:00:15.101 11224 11287 I jxcore-log: 
,03-31 13:00:15.101 11224 11287 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 13:00:15.101 11224 11287 I jxcore-log: 
,03-31 13:00:15.101 11224 11287 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 13:00:15.101 11224 11287 I jxcore-log: 
,03-31 13:00:15.101 11224 11287 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 13:00:15.101 11224 11287 I jxcore-log: 
,03-31 13:00:15.106 11224 11287 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 13:00:15.106 11224 11287 I jxcore-log: 
,03-31 13:00:15.106 11224 11287 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 13:00:15.106 11224 11287 I jxcore-log: 
,03-31 13:00:15.106 11224 11287 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 13:00:15.106 11224 11287 I jxcore-log: 
,03-31 13:00:15.106 11224 11287 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 13:00:15.106 11224 11287 I jxcore-log: 
,03-31 13:00:15.111 11224 11287 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 13:00:15.111 11224 11287 I jxcore-log: 
,03-31 13:00:15.111 11224 11287 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 13:00:15.111 11224 11287 I jxcore-log: 
,03-31 13:00:15.111 11224 11287 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 13:00:15.111 11224 11287 I jxcore-log: 
,03-31 13:00:15.111 11224 11287 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 13:00:15.111 11224 11287 I jxcore-log: 
03-31 13:00:15.111 11224 11287 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 13:00:15.111 11224 11287 I jxcore-log: ,
,03-31 13:00:15.116 11224 11287 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 13:00:15.116 11224 11287 I jxcore-log: 
,03-31 13:00:15.156  3461  6089 D SSRM:n  : SIOP:: AP = 270, PST = 269 (W:10), CUR = 34, LCD = 0
,03-31 13:00:15.176 11224 11287 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 13:00:15.176 11224 11287 I jxcore-log: 
,03-31 13:00:15.181 11224 11287 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 13:00:15.181 11224 11287 I jxcore-log: 
,03-31 13:00:15.181 11224 11287 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 13:00:15.181 11224 11287 I jxcore-log: 
,03-31 13:00:15.181 11224 11287 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 13:00:15.181 11224 11287 I jxcore-log: 
,03-31 13:00:15.181 11224 11287 I jxcore-log: DEBUG createNativeListener: mux close
03-31 13:00:15.181 11224 11287 I jxcore-log: 
03-31 13:00:15.181 11224 11287 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 13:00:15.181 11224 11287 I jxcore-log: 
,03-31 13:00:15.186 11224 11287 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 13:00:15.186 11224 11287 I jxcore-log: 
03-31 13:00:15.186 11224 11287 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 13:00:15.186 11224 11287 I jxcore-log: 
,03-31 13:00:15.186 11224 11287 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 13:00:15.186 11224 11287 I jxcore-log: 
03-31 13:00:15.186 11224 11287 I jxcore-log: DEBUG createNativeListener: mux close
03-31 13:00:15.186 11224 11287 I jxcore-log: 
,03-31 13:00:15.186 11224 11287 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 13:00:15.186 11224 11287 I jxcore-log: 
,03-31 13:00:15.191 11224 11287 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 13:00:15.191 11224 11287 I jxcore-log: 
,03-31 13:00:15.191 11224 11287 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 13:00:15.191 11224 11287 I jxcore-log: 
03-31 13:00:15.191 11224 11287 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 13:00:15.191 11224 11287 I jxcore-log: 
,03-31 13:00:15.191 11224 11287 I jxcore-log: DEBUG createNativeListener: mux close
03-31 13:00:15.191 11224 11287 I jxcore-log: 
,03-31 13:00:15.191 11224 11287 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 13:00:15.191 11224 11287 I jxcore-log: 
,03-31 13:00:15.191 11224 11287 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 13:00:15.191 11224 11287 I jxcore-log: 
03-31 13:00:15.191 11224 11287 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 13:00:15.191 11224 11287 I jxcore-log: 
,03-31 13:00:15.196 11224 11287 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 13:00:15.196 11224 11287 I jxcore-log: 
,03-31 13:00:15.196 11224 11287 I jxcore-log: DEBUG createNativeListener: mux close
03-31 13:00:15.196 11224 11287 I jxcore-log: 
03-31 13:00:15.196 11224 11287 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 13:00:15.196 11224 11287 I jxcore-log: 
,03-31 13:00:15.196 11224 11287 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 13:00:15.196 11224 11287 I jxcore-log: 
03-31 13:00:15.196 11224 11287 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 13:00:15.196 11224 11287 I jxcore-log: 
,03-31 13:00:15.196 11224 11287 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 13:00:15.196 11224 11287 I jxcore-log: 
,03-31 13:00:15.196 11224 11287 I jxcore-log: DEBUG createNativeListener: mux close
03-31 13:00:15.196 11224 11287 I jxcore-log: 
,03-31 13:00:15.196 11224 11287 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 13:00:15.196 11224 11287 I jxcore-log: 
,03-31 13:00:15.201 11224 11287 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 13:00:15.201 11224 11287 I jxcore-log: 
03-31 13:00:15.201 11224 11287 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 13:00:15.201 11224 11287 I jxcore-log: 
,03-31 13:00:15.201 11224 11287 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 13:00:15.201 11224 11287 I jxcore-log: 
03-31 13:00:15.201 11224 11287 I jxcore-log: DEBUG createNativeListener: mux close
03-31 13:00:15.201 11224 11287 I jxcore-log: 
,03-31 13:00:15.201 11224 11287 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 13:00:15.201 11224 11287 I jxcore-log: 
,03-31 13:00:15.201 11224 11287 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 13:00:15.201 11224 11287 I jxcore-log: 
03-31 13:00:15.201 11224 11287 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 13:00:15.201 11224 11287 I jxcore-log: 
,03-31 13:00:15.201 11224 11287 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 13:00:15.201 11224 11287 I jxcore-log: 
,03-31 13:00:15.206 11224 11287 I jxcore-log: DEBUG createNativeListener: mux close
03-31 13:00:15.206 11224 11287 I jxcore-log: 
03-31 13:00:15.206 11224 11287 I jxcore-log: DEBUG createNativeListener: stream close:
,03-31 13:00:15.206 11224 11287 I jxcore-log: 
03-31 13:00:15.206 11224 11287 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 13:00:15.206 11224 11287 I jxcore-log: 
,03-31 13:00:15.206 11224 11287 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 13:00:15.206 11224 11287 I jxcore-log: 
03-31 13:00:15.206 11224 11287 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 13:00:15.206 11224 11287 I jxcore-log: 
,03-31 13:00:15.206 11224 11287 I jxcore-log: DEBUG createNativeListener: mux close
03-31 13:00:15.206 11224 11287 I jxcore-log: 
,03-31 13:00:15.206 11224 11287 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 13:00:15.206 11224 11287 I jxcore-log: 
03-31 13:00:15.206 11224 11287 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 13:00:15.206 11224 11287 I jxcore-log: 
,03-31 13:00:15.206 11224 11287 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 13:00:15.206 11224 11287 I jxcore-log: 
,03-31 13:00:15.211 11224 11287 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 13:00:15.211 11224 11287 I jxcore-log: 
,03-31 13:00:15.211 11224 11287 I jxcore-log: DEBUG createNativeListener: mux close
03-31 13:00:15.211 11224 11287 I jxcore-log: 
03-31 13:00:15.211 11224 11287 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 13:00:15.211 11224 11287 I jxcore-log: 
,03-31 13:00:15.211 11224 11287 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 13:00:15.211 11224 11287 I jxcore-log: 
03-31 13:00:15.211 11224 11287 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 13:00:15.211 11224 11287 I jxcore-log: 
,03-31 13:00:15.211 11224 11287 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 13:00:15.211 11224 11287 I jxcore-log: 
03-31 13:00:15.211 11224 11287 I jxcore-log: DEBUG createNativeListener: mux close
03-31 13:00:15.211 11224 11287 I jxcore-log: 
,03-31 13:00:15.216 11224 11287 I jxcore-log: ok 28 native server is nulled out
03-31 13:00:15.216 11224 11287 I jxcore-log: 
,03-31 13:00:15.216 11224 11287 I jxcore-log: ok 29 native server should be closed
03-31 13:00:15.216 11224 11287 I jxcore-log: 
03-31 13:00:15.216 11224 11287 I jxcore-log: ok 30 incoming has been removed
03-31 13:00:15.216 11224 11287 I jxcore-log: 
03-31 13:00:15.216 11224 11287 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 13:00:15.216 11224 11287 I jxcore-log: 
,03-31 13:00:15.216 11224 11287 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 13:00:15.216 11224 11287 I jxcore-log: 
03-31 13:00:15.216 11224 11287 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 13:00:15.216 11224 11287 I jxcore-log: 
03-31 13:00:15.216 11224 11287 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 13:00:15.216 11224 11287 I jxcore-log: 
,03-31 13:00:15.216 11224 11287 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 13:00:15.216 11224 11287 I jxcore-log: 
03-31 13:00:15.216 11224 11287 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 13:00:15.216 11224 11287 I jxcore-log: 
03-31 13:00:15.216 11224 11287 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 13:00:15.216 11224 11287 I jxcore-log: 
,03-31 13:00:15.216 11224 11287 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 13:00:15.216 11224 11287 I jxcore-log: 
03-31 13:00:15.221 11224 11287 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 13:00:15.221 11224 11287 I jxcore-log: 
03-31 13:00:15.221 11224 11287 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 13:00:15.221 11224 11287 I jxcore-log: 
,03-31 13:00:15.311 11224 11287 I jxcore-log: # teardown
03-31 13:00:15.311 11224 11287 I jxcore-log: 
,03-31 13:00:15.346 11224 11287 I jxcore-log: # setup
03-31 13:00:15.346 11224 11287 I jxcore-log: 
,03-31 13:00:15.426 11224 11287 I jxcore-log: # 10. native server - simulate mux failure, make sure everything is cleaned up
03-31 13:00:15.426 11224 11287 I jxcore-log: 
,03-31 13:00:15.516 11224 11287 I jxcore-log: DEBUG createNativeListener: creating native server,
03-31 13:00:15.516 11224 11287 I jxcore-log: 
,03-31 13:00:15.526 11224 11287 I jxcore-log: DEBUG createNativeListener: listening 40468
03-31 13:00:15.526 11224 11287 I jxcore-log: 
,03-31 13:00:15.531 11224 11287 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 13:00:15.531 11224 11287 I jxcore-log: 
,03-31 13:00:15.536 11224 11287 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 13:00:15.536 11224 11287 I jxcore-log: 
,03-31 13:00:15.541 11224 11287 I jxcore-log: DEBUG createNativeListener: new mux
03-31 13:00:15.541 11224 11287 I jxcore-log: 
,03-31 13:00:15.551 11224 11287 I jxcore-log: ok 31 we should not have gotten an error
03-31 13:00:15.551 11224 11287 I jxcore-log: 
,03-31 13:00:15.556 11224 11287 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 13:00:15.556 11224 11287 I jxcore-log: 
,03-31 13:00:15.556 11224 11287 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 13:00:15.556 11224 11287 I jxcore-log: 
,03-31 13:00:15.571 11224 11287 I jxcore-log: ok 32 Buffers are identical
03-31 13:00:15.571 11224 11287 I jxcore-log: 
,03-31 13:00:15.571 11224 11287 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 13:00:15.571 11224 11287 I jxcore-log: 
,03-31 13:00:15.571 11224 11287 I jxcore-log: DEBUG createNativeListener: mux close
03-31 13:00:15.571 11224 11287 I jxcore-log: 
,03-31 13:00:15.586 11224 11287 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 13:00:15.586 11224 11287 I jxcore-log: 
,03-31 13:00:15.591 11224 11287 I jxcore-log: ok 33 server should be fine
03-31 13:00:15.591 11224 11287 I jxcore-log: 
,03-31 13:00:15.591 11224 11287 I jxcore-log: ok 34 server should be open
03-31 13:00:15.591 11224 11287 I jxcore-log: 
03-31 13:00:15.591 11224 11287 I jxcore-log: ok 35 incoming has been removed
03-31 13:00:15.591 11224 11287 I jxcore-log: 
,03-31 13:00:15.591 11224 11287 I jxcore-log: ok 36 The mux object should be closed
03-31 13:00:15.591 11224 11287 I jxcore-log: 
,03-31 13:00:15.591 11224 11287 I jxcore-log: ok 37 The mux stream should be closed
03-31 13:00:15.591 11224 11287 I jxcore-log: 
,03-31 13:00:15.601 11224 11287 I jxcore-log: # teardown
03-31 13:00:15.601 11224 11287 I jxcore-log: 
,03-31 13:00:15.796 11224 11287 I jxcore-log: # setup
03-31 13:00:15.796 11224 11287 I jxcore-log: 
,03-31 13:00:15.936 11224 11287 I jxcore-log: # 11. native server - timing out the incoming connection cleans everything up
03-31 13:00:15.936 11224 11287 I jxcore-log: 
,03-31 13:00:16.076 11224 11287 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 13:00:16.076 11224 11287 I jxcore-log: 
,03-31 13:00:16.081 11224 11287 I jxcore-log: DEBUG createNativeListener: listening 52155
03-31 13:00:16.081 11224 11287 I jxcore-log: 
,03-31 13:00:16.091 11224 11287 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 13:00:16.091 11224 11287 I jxcore-log: 
,03-31 13:00:16.091 11224 11287 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 13:00:16.091 11224 11287 I jxcore-log: 
,03-31 13:00:16.096 11224 11287 I jxcore-log: DEBUG createNativeListener: new mux
03-31 13:00:16.096 11224 11287 I jxcore-log: 
,03-31 13:00:16.106 11224 11287 I jxcore-log: ok 38 we should not have gotten an error
03-31 13:00:16.106 11224 11287 I jxcore-log: 
,03-31 13:00:16.111 11224 11287 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 13:00:16.111 11224 11287 I jxcore-log: 
,03-31 13:00:16.116 11224 11287 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 13:00:16.116 11224 11287 I jxcore-log: 
,03-31 13:00:16.121 11224 11287 I jxcore-log: ok 39 Buffers are identical
03-31 13:00:16.121 11224 11287 I jxcore-log: 
,03-31 13:00:16.126 11224 11287 I jxcore-log: DEBUG createNativeListener: incoming socket timeout
03-31 13:00:16.126 11224 11287 I jxcore-log: 
,03-31 13:00:16.131 11224 11287 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 13:00:16.131 11224 11287 I jxcore-log: 
,03-31 13:00:16.131 11224 11287 I jxcore-log: DEBUG createNativeListener: mux close
03-31 13:00:16.131 11224 11287 I jxcore-log: 
,03-31 13:00:16.141 11224 11287 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 13:00:16.141 11224 11287 I jxcore-log: 
,03-31 13:00:16.141 11224 11287 I jxcore-log: ok 40 server should be fine
03-31 13:00:16.141 11224 11287 I jxcore-log: 
,03-31 13:00:16.141 11224 11287 I jxcore-log: ok 41 server should be open
03-31 13:00:16.141 11224 11287 I jxcore-log: 
,03-31 13:00:16.141 11224 11287 I jxcore-log: ok 42 incoming has been removed
03-31 13:00:16.141 11224 11287 I jxcore-log: 
,03-31 13:00:16.141 11224 11287 I jxcore-log: ok 43 The mux object should be closed
03-31 13:00:16.141 11224 11287 I jxcore-log: 
03-31 13:00:16.141 11224 11287 I jxcore-log: ok 44 The mux stream should be closed
03-31 13:00:16.141 11224 11287 I jxcore-log: 
,03-31 13:00:16.151 11224 11287 I jxcore-log: # teardown
03-31 13:00:16.151 11224 11287 I jxcore-log: 
,03-31 13:00:16.281 11224 11287 I jxcore-log: # setup
03-31 13:00:16.281 11224 11287 I jxcore-log: 
,03-31 13:00:16.381 11224 11287 I jxcore-log: # 12. closeAll can close even when connections open
03-31 13:00:16.381 11224 11287 I jxcore-log: 
,03-31 13:00:16.506 11224 11287 I jxcore-log: ok 45 not possible to connect to the server anymore
03-31 13:00:16.506 11224 11287 I jxcore-log: 
,03-31 13:00:16.511 11224 11287 I jxcore-log: # teardown
03-31 13:00:16.511 11224 11287 I jxcore-log: 
,03-31 13:00:16.591 11224 11287 I jxcore-log: # setup
03-31 13:00:16.591 11224 11287 I jxcore-log: 
,03-31 13:00:16.726 11224 11287 I jxcore-log: # 13. closeAll with promise
03-31 13:00:16.726 11224 11287 I jxcore-log: 
,03-31 13:00:16.891 11224 11287 I jxcore-log: ok 46 not possible to connect to the server anymore
03-31 13:00:16.891 11224 11287 I jxcore-log: 
,03-31 13:00:16.896 11224 11287 I jxcore-log: # teardown
03-31 13:00:16.896 11224 11287 I jxcore-log: 
,03-31 13:00:16.961 11224 11287 I jxcore-log: # setup
03-31 13:00:16.961 11224 11287 I jxcore-log: 
,03-31 13:00:17.096 11224 11287 I jxcore-log: # 14. closeAll properly throws when closing a non open server with eatNotRunning set to false
03-31 13:00:17.096 11224 11287 I jxcore-log: 
,03-31 13:00:17.266 11224 11287 I jxcore-log: ok 47 Got the right error
03-31 13:00:17.266 11224 11287 I jxcore-log: 
,03-31 13:00:17.271 11224 11287 I jxcore-log: # teardown
03-31 13:00:17.271 11224 11287 I jxcore-log: 
,03-31 13:00:17.411 11224 11287 I jxcore-log: # setup
03-31 13:00:17.411 11224 11287 I jxcore-log: 
,03-31 13:00:17.571 11224 11287 I jxcore-log: # 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true
03-31 13:00:17.571 11224 11287 I jxcore-log: 
,03-31 13:00:17.786 11224 11287 I jxcore-log: # teardown
03-31 13:00:17.786 11224 11287 I jxcore-log: 
,03-31 13:00:17.976 11224 11287 I jxcore-log: # setup
03-31 13:00:17.976 11224 11287 I jxcore-log: 
,03-31 13:00:18.211 11224 11287 I jxcore-log: # 16. multiplex can send data
03-31 13:00:18.211 11224 11287 I jxcore-log: 
,03-31 13:00:18.426 11224 11287 I jxcore-log: ok 48 String should be length:200
03-31 13:00:18.426 11224 11287 I jxcore-log: 
,03-31 13:00:18.436 11224 11287 I jxcore-log: # teardown
03-31 13:00:18.436 11224 11287 I jxcore-log: 
,03-31 13:00:18.491 11224 11287 I jxcore-log: # setup
03-31 13:00:18.491 11224 11287 I jxcore-log: 
,03-31 13:00:18.691 11224 11287 I jxcore-log: # 17. enqueue and run in order
03-31 13:00:18.691 11224 11287 I jxcore-log: 
,03-31 13:00:18.896 11224 11287 I jxcore-log: ok 49 firstPromise setTimeout
03-31 13:00:18.896 11224 11287 I jxcore-log: 
,03-31 13:00:18.901 11224 11287 I jxcore-log: ok 50 firstPromise result
03-31 13:00:18.901 11224 11287 I jxcore-log: 
,03-31 13:00:18.906 11224 11287 I jxcore-log: ok 51 firstPromise testValue
03-31 13:00:18.906 11224 11287 I jxcore-log: 
,03-31 13:00:19.016 11224 11287 I jxcore-log: ok 52 secondPromise setTimeout
03-31 13:00:19.016 11224 11287 I jxcore-log: 
,03-31 13:00:19.026 11224 11287 I jxcore-log: ok 53 secondPromise result,
03-31 13:00:19.026 11224 11287 I jxcore-log: 
,03-31 13:00:19.036 11224 11287 I jxcore-log: ok 54 secondPromise testValue
03-31 13:00:19.036 11224 11287 I jxcore-log: 
,03-31 13:00:19.036 11224 11287 I jxcore-log: ok 55 thirdPromise in promise
03-31 13:00:19.036 11224 11287 I jxcore-log: 
,03-31 13:00:19.041 11224 11287 I jxcore-log: ok 56 thirdPromise result
03-31 13:00:19.041 11224 11287 I jxcore-log: 
,03-31 13:00:19.046 11224 11287 I jxcore-log: ok 57 thirdPromise testValue
03-31 13:00:19.046 11224 11287 I jxcore-log: 
,03-31 13:00:19.056 11224 11287 I jxcore-log: # teardown
03-31 13:00:19.056 11224 11287 I jxcore-log: 
,03-31 13:00:19.156 11224 11287 I jxcore-log: # setup
03-31 13:00:19.156 11224 11287 I jxcore-log: 
,03-31 13:00:19.311 11224 11287 I jxcore-log: # 18. enqueueAtTop and run backwards
03-31 13:00:19.311 11224 11287 I jxcore-log: 
,03-31 13:00:19.421 11224 11287 I jxcore-log: ok 58 thirdPromise - first to run
03-31 13:00:19.421 11224 11287 I jxcore-log: 
,03-31 13:00:19.426 11224 11287 I jxcore-log: ok 59 thirdPromise - in resolve
03-31 13:00:19.426 11224 11287 I jxcore-log: 
,03-31 13:00:19.431 11224 11287 I jxcore-log: ok 60 secondPromise - second to run
03-31 13:00:19.431 11224 11287 I jxcore-log: 
,03-31 13:00:19.431 11224 11287 I jxcore-log: ok 61 secondPromise - in catch
03-31 13:00:19.431 11224 11287 I jxcore-log: 
,03-31 13:00:19.436 11224 11287 I jxcore-log: ok 62 firstPromise - third to run
03-31 13:00:19.436 11224 11287 I jxcore-log: 
,03-31 13:00:19.436 11224 11287 I jxcore-log: ok 63 firstPromise - in then
03-31 13:00:19.436 11224 11287 I jxcore-log: 
,03-31 13:00:19.436 11224 11287 I jxcore-log: ok 64 testing promises
03-31 13:00:19.436 11224 11287 I jxcore-log: 
,03-31 13:00:19.441 11224 11287 I jxcore-log: # teardown
03-31 13:00:19.441 11224 11287 I jxcore-log: 
,03-31 13:00:19.556 11224 11287 I jxcore-log: # setup
03-31 13:00:19.556 11224 11287 I jxcore-log: 
,03-31 13:00:19.696 11224 11287 I jxcore-log: # 19. mix enqueue and enqueueAtTop
03-31 13:00:19.696 11224 11287 I jxcore-log: 
,03-31 13:00:19.791 11224 11287 I jxcore-log: ok 65 fourth
03-31 13:00:19.791 11224 11287 I jxcore-log: 
,03-31 13:00:19.796 11224 11287 I jxcore-log: ok 66 fourth
03-31 13:00:19.796 11224 11287 I jxcore-log: 
,03-31 13:00:19.801 11224 11287 I jxcore-log: ok 67 second
03-31 13:00:19.801 11224 11287 I jxcore-log: 
,03-31 13:00:19.801 11224 11287 I jxcore-log: ok 68 secondPromise - in then
03-31 13:00:19.801 11224 11287 I jxcore-log: 
,03-31 13:00:19.911 11224 11287 I jxcore-log: ok 69 first
03-31 13:00:19.911 11224 11287 I jxcore-log: 
,03-31 13:00:19.921 11224 11287 I jxcore-log: ok 70 firstPromise - in catch
03-31 13:00:19.921 11224 11287 I jxcore-log: 
,03-31 13:00:19.926 11224 11287 I jxcore-log: ok 71 third
03-31 13:00:19.926 11224 11287 I jxcore-log: 
,03-31 13:00:19.936 11224 11287 I jxcore-log: ok 72 thirdPromise - in then
03-31 13:00:19.936 11224 11287 I jxcore-log: 
,03-31 13:00:19.936 11224 11287 I jxcore-log: ok 73 testingPromises
03-31 13:00:19.936 11224 11287 I jxcore-log: 
,03-31 13:00:19.946 11224 11287 I jxcore-log: # teardown
03-31 13:00:19.946 11224 11287 I jxcore-log: 
,03-31 13:00:20.056 11224 11287 I jxcore-log: # setup
03-31 13:00:20.056 11224 11287 I jxcore-log: 
,03-31 13:00:20.171 11224 11287 I jxcore-log: # 20. queues handled independently
03-31 13:00:20.171 11224 11287 I jxcore-log: 
,03-31 13:00:20.351 11224 11287 I jxcore-log: ok 74 all short operations completed before the long resolves
03-31 13:00:20.351 11224 11287 I jxcore-log: 
,03-31 13:00:20.361 11224 11287 I jxcore-log: # teardown
03-31 13:00:20.361 11224 11287 I jxcore-log: 
,03-31 13:00:20.621 11224 11287 I jxcore-log: # setup
03-31 13:00:20.621 11224 11287 I jxcore-log: 
,03-31 13:00:20.861 11224 11287 I jxcore-log: # 21. basic
03-31 13:00:20.861 11224 11287 I jxcore-log: 
,03-31 13:00:21.106 11224 11287 I jxcore-log: ok 75 sane
03-31 13:00:21.106 11224 11287 I jxcore-log: 
,03-31 13:00:21.121 11224 11287 I jxcore-log: # teardown
03-31 13:00:21.121 11224 11287 I jxcore-log: 
,03-31 13:00:21.381 11224 11287 I jxcore-log: # setup
03-31 13:00:21.381 11224 11287 I jxcore-log: 
,03-31 13:00:21.556  3461  3867 E Watchdog: !@Sync 7 [03-31 13:00:21.560]
,03-31 13:00:21.761 11224 11287 I jxcore-log: # 22. another
03-31 13:00:21.761 11224 11287 I jxcore-log: 
,03-31 13:00:21.956 11224 11287 I jxcore-log: ok 76 sane
03-31 13:00:21.956 11224 11287 I jxcore-log: 
,03-31 13:00:21.966 11224 11287 I jxcore-log: # teardown
03-31 13:00:21.966 11224 11287 I jxcore-log: 
,03-31 13:00:22.156 11224 11287 I jxcore-log: # setup
03-31 13:00:22.156 11224 11287 I jxcore-log: 
,03-31 13:00:22.256 11224 11287 I jxcore-log: # 23. can pass data in setup
03-31 13:00:22.256 11224 11287 I jxcore-log: 
,03-31 13:00:22.386 11224 11287 I jxcore-log: [{"uuid":"0801153d-cb21-4b69-ae10-cc9025041f1c","data":"custom data"},{"uuid":"ee1607fb-b6c1-4c59-970d-20fad78ae487","data":"custom data"},{"uuid":"6b5d8d06-647f-425d-badb-69df4a5f8f84","data":"custom data"}]
03-31 13:00:22.386 11224 11287 I jxcore-log: 
,03-31 13:00:22.396 11224 11287 I jxcore-log: ok 77 test participant has uuid
03-31 13:00:22.396 11224 11287 I jxcore-log: 
,03-31 13:00:22.401 11224 11287 I jxcore-log: ok 78 participant data matches
03-31 13:00:22.401 11224 11287 I jxcore-log: 
,03-31 13:00:22.401 11224 11287 I jxcore-log: ok 79 test participant has uuid
03-31 13:00:22.401 11224 11287 I jxcore-log: 
,03-31 13:00:22.401 11224 11287 I jxcore-log: ok 80 participant data matches
03-31 13:00:22.401 11224 11287 I jxcore-log: 
,03-31 13:00:22.406 11224 11287 I jxcore-log: ok 81 test participant has uuid
03-31 13:00:22.406 11224 11287 I jxcore-log: 
,03-31 13:00:22.406 11224 11287 I jxcore-log: ok 82 participant data matches
03-31 13:00:22.406 11224 11287 I jxcore-log: 
,03-31 13:00:22.411 11224 11287 I jxcore-log: ok 83 own UUID is found from the participants list
03-31 13:00:22.411 11224 11287 I jxcore-log: 
,03-31 13:00:22.416 11224 11287 I jxcore-log: # teardown
03-31 13:00:22.416 11224 11287 I jxcore-log: 
,03-31 13:00:22.531 11224 11287 I jxcore-log: # setup
03-31 13:00:22.531 11224 11287 I jxcore-log: 
,03-31 13:00:22.706 11224 11287 I jxcore-log: # 24. #startListeningForAdvertisements should fail if start not called
03-31 13:00:22.706 11224 11287 I jxcore-log: 
,03-31 13:00:22.861 11224 11287 I jxcore-log: ok 84 specific error should be returned
03-31 13:00:22.861 11224 11287 I jxcore-log: 
,03-31 13:00:22.866 11224 11287 I jxcore-log: # teardown
03-31 13:00:22.866 11224 11287 I jxcore-log: 
,03-31 13:00:22.981 11224 11287 I jxcore-log: ok 85 error should be null
03-31 13:00:22.981 11224 11287 I jxcore-log: 
,03-31 13:00:22.986 11224 11287 I jxcore-log: ok 86 error should be null
03-31 13:00:22.986 11224 11287 I jxcore-log: 
,03-31 13:00:22.991 11224 11287 I jxcore-log: # setup
03-31 13:00:22.991 11224 11287 I jxcore-log: 
,03-31 13:00:23.196 11224 11287 I jxcore-log: # 25. #startUpdateAdvertisingAndListening should fail if start not called
03-31 13:00:23.196 11224 11287 I jxcore-log: 
,03-31 13:00:23.356 11224 11287 I jxcore-log: ok 87 specific error should be returned
03-31 13:00:23.356 11224 11287 I jxcore-log: 
,03-31 13:00:23.361 11224 11287 I jxcore-log: # teardown
03-31 13:00:23.361 11224 11287 I jxcore-log: 
,03-31 13:00:23.521 11224 11287 I jxcore-log: ok 88 error should be null
03-31 13:00:23.521 11224 11287 I jxcore-log: 
,03-31 13:00:23.526 11224 11287 I jxcore-log: ok 89 error should be null
03-31 13:00:23.526 11224 11287 I jxcore-log: 
,03-31 13:00:23.531 11224 11287 I jxcore-log: # setup
03-31 13:00:23.531 11224 11287 I jxcore-log: 
,03-31 13:00:23.621 11224 11287 I jxcore-log: # 26. should be able to call #stopListeningForAdvertisements many times
03-31 13:00:23.621 11224 11287 I jxcore-log: 
,03-31 13:00:23.896 11224 11287 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 13:00:23.896 11224 11287 I jxcore-log: 
,03-31 13:00:23.901 11224 11287 I jxcore-log: DEBUG createNativeListener: listening 45903
03-31 13:00:23.901 11224 11287 I jxcore-log: 
,03-31 13:00:23.906 11224 11287 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 13:00:23.906 11224 11287 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 13:00:23.906 11224 11287 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 13:00:23.911 11224 11287 I jxcore-log: ok 90 error should be null
03-31 13:00:23.911 11224 11287 I jxcore-log: 
,03-31 13:00:23.916 11224 11287 I jxcore-log: ok 91 error should be null
03-31 13:00:23.916 11224 11287 I jxcore-log: 
,03-31 13:00:23.916 11224 11287 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 13:00:23.916 11224 11287 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 13:00:23.916 11224 11287 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 13:00:23.921 11224 11287 I jxcore-log: ok 92 error should be null
03-31 13:00:23.921 11224 11287 I jxcore-log: 
,03-31 13:00:23.921 11224 11287 I jxcore-log: ok 93 error should be null
03-31 13:00:23.921 11224 11287 I jxcore-log: 
,03-31 13:00:23.926 11224 11287 I jxcore-log: # teardown
03-31 13:00:23.926 11224 11287 I jxcore-log: 
,03-31 13:00:24.041 11224 11287 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 13:00:24.046 11224 11287 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-31 13:00:24.046 11224 11287 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 13:00:24.051 11224 11287 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 13:00:24.051 11224 11287 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 13:00:24.051 11224 11287 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 13:00:24.061 11224 11287 I jxcore-log: ok 94 error should be null
03-31 13:00:24.061 11224 11287 I jxcore-log: 
,03-31 13:00:24.061 11224 11287 I jxcore-log: ok 95 error should be null
03-31 13:00:24.061 11224 11287 I jxcore-log: 
,03-31 13:00:24.071 11224 11287 I jxcore-log: # setup
03-31 13:00:24.071 11224 11287 I jxcore-log: 
,03-31 13:00:24.201 11224 11287 I jxcore-log: # 27. should be able to call #startListeningForAdvertisements many times
03-31 13:00:24.201 11224 11287 I jxcore-log: 
,03-31 13:00:24.371 11224 11287 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 13:00:24.371 11224 11287 I jxcore-log: 
,03-31 13:00:24.381 11224 11287 I jxcore-log: DEBUG createNativeListener: listening 49492
03-31 13:00:24.381 11224 11287 I jxcore-log: 
,03-31 13:00:24.391 11224 11287 I io.jxcore.node.ConnectionHelper: start: Port number: 0, start advertisements: false
,03-31 13:00:24.391 11224 11287 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-31 13:00:24.391 11224 11287 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,03-31 13:00:24.391 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
03-31 13:00:24.391 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 13:00:24.391 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-31 13:00:24.401 11224 11287 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-31 13:00:24.411 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-31 13:00:24.421 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-31 13:00:24.421 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-31 13:00:24.421 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 13:00:24.421 11224 11287 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 13:00:24.431  5893  8993 D BtGatt.GattService: registerClient() - UUID=f67bd686-16ba-4363-a3e0-6f41a1c5fa5f
,03-31 13:00:24.476  5893  5958 D BtGatt.GattService: onClientRegistered() - UUID=f67bd686-16ba-4363-a3e0-6f41a1c5fa5f, clientIf=6
,03-31 13:00:24.476 11224 11234 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-31 13:00:24.476  5893  5905 D BtGatt.GattService: start scan with filters
,03-31 13:00:24.496  5893  5905 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 44
,03-31 13:00:24.501 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 13:00:24.501 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 13:00:24.501  5893  5979 D BtGatt.ScanManager: handling starting scan
03-31 13:00:24.501  5893  5979 D BtGatt.ScanManager: isFilteringSupported
03-31 13:00:24.501 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-31 13:00:24.501  5893  5979 D BluetoothAdapter: setting StandAloneBleMode
03-31 13:00:24.501 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 13:00:24.501 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,03-31 13:00:24.501 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-31 13:00:24.501 11224 11224 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-31 13:00:24.501  5893  5979 D BtGatt.ScanManager: isFilteringSupported
03-31 13:00:24.501  5893  5979 D BluetoothAdapter: setting StandAloneBleMode
,03-31 13:00:24.501  5893  5979 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@be0f583
,03-31 13:00:24.506 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
03-31 13:00:24.506 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 13:00:24.506 11224 11287 I io.jxcore.node.ConnectionHelper: start: OK
03-31 13:00:24.506 11224 11224 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 13:00:24.506 11224 11224 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 13:00:24.506 11224 11224 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-31 13:00:24.516  5893  5958 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,03-31 13:00:24.516  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 13:00:24.516  5893  5979 D BtGatt.ScanManager: allow scan with filters
03-31 13:00:24.516  5893  5979 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,03-31 13:00:24.521  5893  5979 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,03-31 13:00:24.521 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 13:00:24.521 11224 11287 I jxcore-log: 
,03-31 13:00:24.521  5893  5958 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-31 13:00:24.521  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 13:00:24.521 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 13:00:24.521 11224 11287 I jxcore-log: 
,03-31 13:00:24.521  5893  5979 D BtGatt.ScanManager: Starting BLE batch scan
03-31 13:00:24.521  5893  5979 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-31 13:00:24.526 11224 11287 I jxcore-log: ok 96 error should be null
,03-31 13:00:24.526 11224 11287 I jxcore-log: 
03-31 13:00:24.526  5893  5958 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-31 13:00:24.526  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 13:00:24.526 11224 11287 I jxcore-log: ok 97 error should be null
03-31 13:00:24.526 11224 11287 I jxcore-log: 
,03-31 13:00:24.526  5893  5958 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-31 13:00:24.526  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 13:00:24.536 11224 11287 I io.jxcore.node.ConnectionHelper: start: Port number: 0, start advertisements: false
,03-31 13:00:24.536 11224 11287 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 13:00:24.536 11224 11287 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 13:00:24.536 11224 11287 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-31 13:00:24.536 11224 11287 I io.jxcore.node.ConnectionHelper: start: OK
,03-31 13:00:24.536 11224 11287 I jxcore-log: ok 98 error should be null
03-31 13:00:24.536 11224 11287 I jxcore-log: 
,03-31 13:00:24.536 11224 11287 I jxcore-log: ok 99 error should be null
03-31 13:00:24.536 11224 11287 I jxcore-log: 
,03-31 13:00:24.546 11224 11287 I jxcore-log: # teardown
03-31 13:00:24.546 11224 11287 I jxcore-log: 
,03-31 13:00:24.801  3461  4033 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-31 13:00:24.811  3728  3728 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 13:00:24.801  3461  4033 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 13:00:24.811  3728  3728 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-31 13:00:24.801  3461  4033 D BatteryService: online:4, current avg:42, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:42
03-31 13:00:24.811  3728  3728 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 13:00:24.801  3461  3461 D BatteryService: Sending ACTION_BATTERY_CHANGED.,
,03-31 13:00:24.801  3461  4033 D BatteryService: stay LED for fully charged
03-31 13:00:24.806  3461  3461 I MotionRecognitionService: Plugged
,03-31 13:00:24.806  3461  3461 D MotionRecognitionService:   cableConnection= 1,
03-31 13:00:24.806  3461  3461 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 13:00:24.806  3461  3461 D MotionRecognitionService: skip setTransmitPower. 
,03-31 13:00:24.836  5893  5893 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-31 13:00:24.836  5893  5980 D HeadsetStateMachine: Disconnected process message: 10
,03-31 13:00:24.841  3728  3728 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 13:00:24.841  3728  3728 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 13:00:24.841  3728  3728 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 13:00:24.841  3728  3728 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 13:00:24.851 11224 11287 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 13:00:24.851 11224 11287 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,03-31 13:00:24.851 11224 11287 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,03-31 13:00:24.856 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-31 13:00:24.856 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-31 13:00:24.856 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-31 13:00:24.856 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-31 13:00:24.856 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-31 13:00:24.856 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-31 13:00:24.861  5893  8993 D BtGatt.GattService: stopScan() - queue size =1
,03-31 13:00:24.861  5893  5979 D BtGatt.ScanManager: filter size is 1
03-31 13:00:24.861  5893  5979 D BtGatt.ScanManager: delete FilterIndex - 3
03-31 13:00:24.861  5893  5958 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-31 13:00:24.861  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 13:00:24.861  5893  5979 D BtGatt.ScanManager: stopping BLe Batch
,03-31 13:00:24.866  5893  5958 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-31 13:00:24.866  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 13:00:24.866  5893  5905 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-31 13:00:24.871  5893  5979 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-31 13:00:24.871 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-31 13:00:24.871  5893  5958 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-31 13:00:24.871  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 13:00:24.876 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 13:00:24.876 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-31 13:00:24.876 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-31 13:00:24.876 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-31 13:00:24.881 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-31 13:00:24.881 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 13:00:24.881 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 13:00:24.881 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-31 13:00:24.881 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
03-31 13:00:24.881 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 13:00:24.881 11224 11224 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 13:00:24.881 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 13:00:24.881 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-31 13:00:24.886 11224 11287 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-31 13:00:24.886 11224 11287 I jxcore-log: 
,03-31 13:00:24.886 11224 11224 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
,03-31 13:00:24.896 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-31 13:00:24.896 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-31 13:00:24.896 11224 11224 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 13:00:24.896 11224 11224 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-31 13:00:24.896 11224 11224 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 13:00:24.896 11224 11224 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 13:00:24.896 11224 11224 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 13:00:24.901 11224 11287 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 13:00:24.901 11224 11287 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 13:00:24.901 11224 11287 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 13:00:24.901 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 13:00:24.901 11224 11287 I jxcore-log: 
,03-31 13:00:24.901 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 13:00:24.901 11224 11287 I jxcore-log: 
,03-31 13:00:24.906 11224 11287 I jxcore-log: ok 100 error should be null
03-31 13:00:24.906 11224 11287 I jxcore-log: 
,03-31 13:00:24.906 11224 11287 I jxcore-log: ok 101 error should be null
03-31 13:00:24.906 11224 11287 I jxcore-log: 
,03-31 13:00:24.911 11224 11287 I jxcore-log: # setup
03-31 13:00:24.911 11224 11287 I jxcore-log: 
,03-31 13:00:25.111 11224 11287 I jxcore-log: # 28. should be able to call #startUpdateAdvertisingAndListening many times
03-31 13:00:25.111 11224 11287 I jxcore-log: 
,03-31 13:00:25.171  3461  6089 D SSRM:n  : SIOP:: AP = 270, PST = 269 (W:10), CUR = 42, LCD = 0
,03-31 13:00:25.501 11224 11287 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 13:00:25.501 11224 11287 I jxcore-log: 
,03-31 13:00:25.506 11224 11287 I jxcore-log: DEBUG createNativeListener: listening 45029
03-31 13:00:25.506 11224 11287 I jxcore-log: 
,03-31 13:00:25.531 11224 11287 I io.jxcore.node.ConnectionHelper: start: Port number: 45029, start advertisements: true
03-31 13:00:25.531 11224 11287 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 13:00:25.531 11224 11287 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-31 13:00:25.531 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-31 13:00:25.536 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-31 13:00:25.536 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 13:00:25.536 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 13:00:25.536 11224 11287 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 13:00:25.541  5893  5987 D BtGatt.GattService: registerClient() - UUID=cc8d9c4c-863f-4be5-a43d-c9609581a78f
,03-31 13:00:25.581  5893  5958 D BtGatt.GattService: onClientRegistered() - UUID=cc8d9c4c-863f-4be5-a43d-c9609581a78f, clientIf=6
,03-31 13:00:25.581 11224 11233 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-31 13:00:25.581  5893  5903 D BtGatt.GattService: start scan with filters
,03-31 13:00:25.606  5893  5903 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 45
,03-31 13:00:25.606 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-31 13:00:25.606 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 13:00:25.611 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-31 13:00:25.611  5893  5979 D BtGatt.ScanManager: handling starting scan
03-31 13:00:25.611 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,03-31 13:00:25.611  5893  5979 D BtGatt.ScanManager: isFilteringSupported
03-31 13:00:25.611  5893  5979 D BluetoothAdapter: setting StandAloneBleMode
03-31 13:00:25.611 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,03-31 13:00:25.611 11224 11224 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-31 13:00:25.611 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 13:00:25.611 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-31 13:00:25.611 11224 11287 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-31 13:00:25.611 11224 11287 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 13:00:25.611 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 13:00:25.611 11224 11287 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-31 13:00:25.616  5893  5958 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-31 13:00:25.616  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 13:00:25.616  5893  5979 D BtGatt.ScanManager: allow scan with filters
03-31 13:00:25.616  5893  5979 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,03-31 13:00:25.616  5893  5979 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
03-31 13:00:25.621  5893  5958 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-31 13:00:25.621  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 13:00:25.621  5893  5979 D BtGatt.ScanManager: Starting BLE batch scan
03-31 13:00:25.621  5893  5979 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-31 13:00:25.626  5893  5958 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,03-31 13:00:25.626  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 13:00:25.626  5893  5903 D BtGatt.GattService: registerClient() - UUID=6af60bf8-baf2-4492-a972-ac3897548439
03-31 13:00:25.626  5893  5958 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1,
03-31 13:00:25.626  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 13:00:25.666  5893  5958 D BtGatt.GattService: onClientRegistered() - UUID=6af60bf8-baf2-4492-a972-ac3897548439, clientIf=7
,03-31 13:00:25.666 11224 11234 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-31 13:00:25.686  5893  8993 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 36
,03-31 13:00:25.691  5893  5978 D BtGatt.AdvertiseManager: message : 0
,03-31 13:00:25.696  5893  5978 D BtGatt.AdvertiseManager: number of adv instance running0
03-31 13:00:25.696  5893  5978 D BtGatt.AdvertiseManager: size of list is =0
,03-31 13:00:25.696  5893  5978 D BtGatt.AdvertiseManager: starting advertising
03-31 13:00:25.696  5893  5978 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-31 13:00:25.701  5893  5958 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-31 13:00:25.706  5893  5978 D BtGatt.AdvertiseManager: starting multi advertising,
,03-31 13:00:25.706  5893  5958 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
03-31 13:00:25.706  5893  5978 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,03-31 13:00:25.706  5893  5978 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,03-31 13:00:25.711 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-31 13:00:25.711 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-31 13:00:25.716 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-31 13:00:25.716 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 13:00:25.716 11224 11287 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,03-31 13:00:25.716 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 13:00:25.716 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-31 13:00:25.721 11224 11287 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-31 13:00:25.721 11224 11287 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,03-31 13:00:25.721 11224 11287 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-31 13:00:25.721 11224 11224 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-31 13:00:25.726 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 13:00:25.726 11224 11224 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,03-31 13:00:25.726 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,03-31 13:00:25.726 11224 11224 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
,03-31 13:00:25.726 11224 11224 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-31 13:00:25.726 11224 11224 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-31 13:00:25.726 11224 11224 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false,
,03-31 13:00:25.726 11224 11224 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything,
03-31 13:00:25.726 11224 11224 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-31 13:00:25.726 11224 11224 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING,
03-31 13:00:25.726 11224 11224 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true,
,03-31 13:00:25.736 11224 11287 I io.jxcore.node.ConnectionHelper: start: OK,
,03-31 13:00:25.771 11224 11538 D BluetoothSocket: bindListen(): myUserId = 0,
03-31 13:00:25.771 11224 11538 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-31 13:00:25.781 11224 11538 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[119]},
03-31 13:00:25.781 11224 11538 D BluetoothSocket: bindListen(), new LocalSocket 
03-31 13:00:25.781 11224 11538 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-31 13:00:25.781 11224 11538 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@57a9e75
,03-31 13:00:25.781 11224 11538 D BluetoothSocket: channel: 6
03-31 13:00:25.781 11224 11538 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-31 13:00:25.796 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 13:00:25.796 11224 11287 I jxcore-log: 
,03-31 13:00:25.811 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 13:00:25.811 11224 11287 I jxcore-log: 
,03-31 13:00:25.811 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-31 13:00:25.811 11224 11287 I jxcore-log: 
,03-31 13:00:25.816 11224 11287 I jxcore-log: ok 102 error should be null
03-31 13:00:25.816 11224 11287 I jxcore-log: 
,03-31 13:00:25.821 11224 11287 I jxcore-log: ok 103 error should be null
03-31 13:00:25.821 11224 11287 I jxcore-log: 
,03-31 13:00:25.826 11224 11287 I io.jxcore.node.ConnectionHelper: start: Port number: 45029, start advertisements: true
,03-31 13:00:25.826 11224 11287 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 13:00:25.826 11224 11287 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-31 13:00:25.831 11224 11287 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-31 13:00:25.831 11224 11287 I io.jxcore.node.ConnectionHelper: start: OK
,03-31 13:00:25.841 11224 11287 I jxcore-log: ok 104 error should be null
03-31 13:00:25.841 11224 11287 I jxcore-log: 
,03-31 13:00:25.841 11224 11287 I jxcore-log: ok 105 error should be null
03-31 13:00:25.841 11224 11287 I jxcore-log: 
,03-31 13:00:25.851 11224 11287 I jxcore-log: # teardown
03-31 13:00:25.851 11224 11287 I jxcore-log: 
,03-31 13:00:26.626  3461  3617 V AlarmManager: waitForAlarm result :4
,03-31 13:00:26.646  5893  5893 D BtGatt.ScanManager: awakened up at time 227741
,03-31 13:00:26.651  5893  5979 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-31 13:00:26.656  5893  5958 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=4
03-31 13:00:26.656  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 13:00:26.656  5893  5958 D BtGatt.GattService: current time is 227753529567
03-31 13:00:26.656  5893  5958 D BtGatt.GattService: Batch record : [70, -104, -9, 72, 43, 109, 1, -128, -78, 18, 0, 0, 0, -21, -45, -39, -22, -58, 69, 1, -128, -62, 18, 0, 0, 0, 70, -104, -9, 72, 43, 109, 1, -128, -90, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -21, -45, -39, -22, -58, 69, 1, -128, -64, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0]
,03-31 13:00:26.671  5893  5958 D BtGatt.GattService: ScanRecord : []
03-31 13:00:26.671  5893  5958 D ScanRecord: parseFromBytes
03-31 13:00:26.671  5893  5958 D BtGatt.GattService: ScanRecord : []
03-31 13:00:26.671  5893  5958 D ScanRecord: parseFromBytes
03-31 13:00:26.671  5893  5958 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-31 13:00:26.671  5893  5958 D ScanRecord: parseFromBytes
,03-31 13:00:26.676  5893  5958 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97],
03-31 13:00:26.676  5893  5958 D ScanRecord: parseFromBytes
03-31 13:00:26.676  5893  5958 D BtGatt.GattService: result: ScanResult{mDevice=45:C6:EA:D9:D3:EB, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=null, mManufacturerSpecificData={}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-62, mTimestampNanos=226854026400}
03-31 13:00:26.676  5893  5958 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-31 13:00:26.676  5893  5958 D BtGatt.GattService: result: ScanResult{mDevice=45:C6:EA:D9:D3:EB, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-64, mTimestampNanos=227754026400}
03-31 13:00:26.676  5893  5958 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 13:00:26.676  5893  5958 D BtGatt.GattService: result: ScanResult{mDevice=6D:2B:48:F7:98:46, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-90, mTimestampNanos=227704026400}
03-31 13:00:26.676  5893  5958 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-31 13:00:26.676  5893  5958 D BtGatt.GattService: result: ScanResult{mDevice=6D:2B:48:F7:98:46, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=null, mManufacturerSpecificData={}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-78, mTimestampNanos=226854026400}
03-31 13:00:26.676  5893  5958 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-31 13:00:26.676 11224 11233 D ScanRecord: parseFromBytes
,03-31 13:00:26.676 11224 11233 D ScanRecord: parseFromBytes
03-31 13:00:26.676 11224 11233 D ScanRecord: parseFromBytes
03-31 13:00:26.676 11224 11233 D ScanRecord: parseFromBytes
,03-31 13:00:26.686 11224 11224 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:CF:C5:D9:E5:61], added - the peer count is 1,
03-31 13:00:26.686 11224 11224 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 2
03-31 13:00:26.686 11224 11224 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:CF:C5:D9:E5:61], Bluetooth address: F8:CF:C5:D9:E5:61, device name: , device address: 
03-31 13:00:26.686 11224 11224 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
03-31 13:00:26.691 11224 11287 I jxcore-log: DEBUG createPeerListener: createPeerListener
03-31 13:00:26.691 11224 11287 I jxcore-log: 
03-31 13:00:26.701 11224 11287 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false
03-31 13:00:26.701 11224 11287 I jxcore-log: 
03-31 13:00:26.701  3728  3728 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
03-31 13:00:26.701  3728  3728 I PERF    : received broadcast android.intent.action.TIME_TICK
03-31 13:00:26.701  3728  3728 D KeyguardUpdateMonitor: handleTimeUpdate
03-31 13:00:26.701 11224 11287 I jxcore-log: DEBUG createPeerListener: createPeerListener
03-31 13:00:26.701 11224 11287 I jxcore-log: 
,03-31 13:00:26.706 11224 11287 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false
03-31 13:00:26.706 11224 11287 I jxcore-log: 
,03-31 13:00:26.711  3728  3728 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,03-31 13:00:26.716  3728  3728 D SecKeyguardClockView: HomeTimezone(): 1
,03-31 13:00:26.726  3728  3728 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 13:00:26.726  3728  3728 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,03-31 13:00:26.731  3728  3728 D CoverUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,03-31 13:00:26.761  3728  3728 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 13:00:26.766  3728  3728 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 13:00:26.771  3728  3728 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 13:00:26.771  3728  3728 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 13:00:26.776  3728  3728 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 13:00:26.776  3728  3728 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 13:00:26.791  3728  3728 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 13:00:27.666  3461  3617 V AlarmManager: waitForAlarm result :4
,03-31 13:00:27.676  5893  5893 D BtGatt.ScanManager: awakened up at time 228773
,03-31 13:00:27.686  5893  5979 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-31 13:00:27.701  5893  5958 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
03-31 13:00:27.701  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 13:00:27.701  5893  5958 D BtGatt.GattService: current time is 228796638150
03-31 13:00:27.701  5893  5958 D BtGatt.GattService: Batch record : [70, -104, -9, 72, 43, 109, 1, -128, -77, 9, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -21, -45, -39, -22, -58, 69, 1, -128, -62, 11, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0]
,03-31 13:00:27.701  5893  5958 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-31 13:00:27.701  5893  5958 D ScanRecord: parseFromBytes,
03-31 13:00:27.701  5893  5958 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97],
03-31 13:00:27.701  5893  5958 D ScanRecord: parseFromBytes
,03-31 13:00:27.701  5893  5958 D BtGatt.GattService: result: ScanResult{mDevice=45:C6:EA:D9:D3:EB, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-62, mTimestampNanos=228246876400}
03-31 13:00:27.701  5893  5958 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-31 13:00:27.701  5893  5958 D BtGatt.GattService: result: ScanResult{mDevice=6D:2B:48:F7:98:46, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-77, mTimestampNanos=228346876400}
,03-31 13:00:27.701  5893  5958 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-31 13:00:27.701 11224 11234 D ScanRecord: parseFromBytes
03-31 13:00:27.701 11224 11234 D ScanRecord: parseFromBytes
03-31 13:00:27.706 11224 11224 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:CF:C5:D9:E5:61] updated - the peer count is 2
03-31 13:00:27.706 11224 11224 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
,03-31 13:00:28.456 11224 11287 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 13:00:28.461 11224 11287 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
,03-31 13:00:28.461 11224 11287 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,03-31 13:00:28.461 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,03-31 13:00:28.461 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,03-31 13:00:28.461 11224 11287 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@270840d6, channel: 6, state: LISTENING
,03-31 13:00:28.466 11224 11287 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@270840d6, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@57a9e75, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1dc8ff57mSocket: android.net.LocalSocket@ab6a44 impl:android.net.LocalSocketImpl@37f5272d fd:FileDescriptor[119]
,03-31 13:00:28.466 11224 11287 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@ab6a44 impl:android.net.LocalSocketImpl@37f5272d fd:FileDescriptor[119]
,03-31 13:00:28.471 11224 11287 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-31 13:00:28.471 11224 11538 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-31 13:00:28.471 11224 11538 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-31 13:00:28.471 11224 11538 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-31 13:00:28.471 11224 11224 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-31 13:00:28.471 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-31 13:00:28.476 11224 11224 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-31 13:00:28.476 11224 11224 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-31 13:00:28.476 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-31 13:00:28.476 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-31 13:00:28.476 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-31 13:00:28.476 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-31 13:00:28.476 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-31 13:00:28.481  5893  5903 D BtGatt.GattService: stopScan() - queue size =1
03-31 13:00:28.481  5893  5979 D BtGatt.ScanManager: filter size is 1
03-31 13:00:28.481  5893  5979 D BtGatt.ScanManager: delete FilterIndex - 4
03-31 13:00:28.481  5893  5958 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-31 13:00:28.481  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 13:00:28.481  5893  5979 D BtGatt.ScanManager: stopping BLe Batch
,03-31 13:00:28.486  5893  5958 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0,
,03-31 13:00:28.486  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 13:00:28.486  5893  5979 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6,
03-31 13:00:28.486  5893  5958 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-31 13:00:28.486  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,03-31 13:00:28.491  5893  8993 D BtGatt.GattService: unregisterClient() - clientIf=6,
,03-31 13:00:28.491 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 13:00:28.491 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED,
03-31 13:00:28.491 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false,
03-31 13:00:28.496 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
,03-31 13:00:28.496 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING],
03-31 13:00:28.496 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true,
,03-31 13:00:28.496 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...,
,03-31 13:00:28.501  5893  5978 D BtGatt.AdvertiseManager: message : 1
03-31 13:00:28.501  5893  5978 D BtGatt.AdvertiseManager: stop advertise for client 7,
03-31 13:00:28.501  5893  5978 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7,
03-31 13:00:28.501  5893  5978 D BtGatt.AdvertiseManager: logClientsSet() - status: -1,
,03-31 13:00:28.501  5893  5958 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-31 13:00:28.501  5893  5958 D BtGatt.GattService: Client app is not null!,
,03-31 13:00:28.501  5893  5903 D BtGatt.GattService: unregisterClient() - clientIf=7,
,03-31 13:00:28.506 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 13:00:28.506 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED,
03-31 13:00:28.506 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-31 13:00:28.506 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,03-31 13:00:28.506 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED],
,03-31 13:00:28.506 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 13:00:28.506 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 13:00:28.506 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-31 13:00:28.511 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-31 13:00:28.511 11224 11287 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-31 13:00:28.511 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 13:00:28.511 11224 11224 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 13:00:28.511 11224 11224 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-31 13:00:28.511 11224 11224 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 13:00:28.511 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 13:00:28.511 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-31 13:00:28.516 11224 11224 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-31 13:00:28.526 11224 11287 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 13:00:28.526 11224 11287 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 13:00:28.526 11224 11287 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 13:00:28.531 11224 11287 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-31 13:00:28.531 11224 11287 I jxcore-log: 
,03-31 13:00:28.531 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
,03-31 13:00:28.536 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 13:00:28.536 11224 11224 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 13:00:28.536 11224 11224 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-31 13:00:28.536 11224 11224 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 13:00:28.536 11224 11224 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 13:00:28.541 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-31 13:00:28.541 11224 11287 I jxcore-log: 
,03-31 13:00:28.541 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 13:00:28.541 11224 11287 I jxcore-log: 
03-31 13:00:28.541 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 13:00:28.541 11224 11287 I jxcore-log: 
,03-31 13:00:28.551 11224 11287 I jxcore-log: ok 106 error should be null
03-31 13:00:28.551 11224 11287 I jxcore-log: 
,03-31 13:00:28.551 11224 11287 I jxcore-log: ok 107 error should be null
03-31 13:00:28.551 11224 11287 I jxcore-log: 
,03-31 13:00:28.556 11224 11287 I jxcore-log: # setup
03-31 13:00:28.556 11224 11287 I jxcore-log: 
,03-31 13:00:28.716 11224 11287 I jxcore-log: # 29. should be able to call #stopAdvertisingAndListening many times
03-31 13:00:28.716 11224 11287 I jxcore-log: 
,03-31 13:00:28.791  3461  6120 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-31 13:00:28.906 11224 11287 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 13:00:28.906 11224 11287 I jxcore-log: 
,03-31 13:00:28.911 11224 11287 I jxcore-log: DEBUG createNativeListener: listening 51971
03-31 13:00:28.911 11224 11287 I jxcore-log: 
,03-31 13:00:28.921 11224 11287 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 13:00:28.921 11224 11287 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 13:00:28.921 11224 11287 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 13:00:28.926 11224 11287 I jxcore-log: ok 108 error should be null
03-31 13:00:28.926 11224 11287 I jxcore-log: 
,03-31 13:00:28.926 11224 11287 I jxcore-log: ok 109 error should be null
03-31 13:00:28.926 11224 11287 I jxcore-log: 
,03-31 13:00:28.931 11224 11287 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 13:00:28.931 11224 11287 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-31 13:00:28.931 11224 11287 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 13:00:28.936 11224 11287 I jxcore-log: ok 110 error should be null
03-31 13:00:28.936 11224 11287 I jxcore-log: 
,03-31 13:00:28.936 11224 11287 I jxcore-log: ok 111 error should be null
03-31 13:00:28.936 11224 11287 I jxcore-log: 
,03-31 13:00:28.946 11224 11287 I jxcore-log: # teardown
03-31 13:00:28.946 11224 11287 I jxcore-log: 
,03-31 13:00:29.046 11224 11287 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-31 13:00:29.046 11224 11287 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 13:00:29.046 11224 11287 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 13:00:29.051 11224 11287 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 13:00:29.051 11224 11287 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 13:00:29.051 11224 11287 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 13:00:29.061 11224 11287 I jxcore-log: ok 112 error should be null
03-31 13:00:29.061 11224 11287 I jxcore-log: 
,03-31 13:00:29.061 11224 11287 I jxcore-log: ok 113 error should be null
03-31 13:00:29.061 11224 11287 I jxcore-log: 
,03-31 13:00:29.071 11224 11287 I jxcore-log: # setup,
03-31 13:00:29.071 11224 11287 I jxcore-log: 
,03-31 13:00:29.456 11224 11287 I jxcore-log: # 30. #start should fail if called twice in a row
03-31 13:00:29.456 11224 11287 I jxcore-log: 
,03-31 13:00:30.136 11224 11287 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 13:00:30.136 11224 11287 I jxcore-log: 
,03-31 13:00:30.141 11224 11287 I jxcore-log: DEBUG createNativeListener: listening 46756
03-31 13:00:30.141 11224 11287 I jxcore-log: 
,03-31 13:00:30.141 11224 11287 I jxcore-log: ok 114 first call should succeed
03-31 13:00:30.141 11224 11287 I jxcore-log: 
,03-31 13:00:30.146 11224 11287 I jxcore-log: ok 115 first call should succeed
03-31 13:00:30.146 11224 11287 I jxcore-log: 
,03-31 13:00:30.151 11224 11287 I jxcore-log: ok 116 specific error should be returned
03-31 13:00:30.151 11224 11287 I jxcore-log: 
,03-31 13:00:30.151 11224 11287 I jxcore-log: # teardown
03-31 13:00:30.151 11224 11287 I jxcore-log: 
,03-31 13:00:30.321 11224 11287 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 13:00:30.321 11224 11287 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-31 13:00:30.321 11224 11287 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 13:00:30.326 11224 11287 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 13:00:30.326 11224 11287 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-31 13:00:30.326 11224 11287 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 13:00:30.336 11224 11287 I jxcore-log: ok 117 error should be null
03-31 13:00:30.336 11224 11287 I jxcore-log: 
,03-31 13:00:30.341 11224 11287 I jxcore-log: ok 118 error should be null
03-31 13:00:30.341 11224 11287 I jxcore-log: 
,03-31 13:00:30.346 11224 11287 I jxcore-log: # setup
03-31 13:00:30.346 11224 11287 I jxcore-log: 
,03-31 13:00:30.476 11224 11287 I jxcore-log: # 31. does not emit duplicate discoveryAdvertisingStateUpdate
03-31 13:00:30.476 11224 11287 I jxcore-log: 
,03-31 13:00:30.656 11224 11287 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 13:00:30.656 11224 11287 I jxcore-log: 
,03-31 13:00:30.661 11224 11287 I jxcore-log: DEBUG createNativeListener: listening 37281
03-31 13:00:30.661 11224 11287 I jxcore-log: 
,03-31 13:00:30.671 11224 11287 I io.jxcore.node.ConnectionHelper: start: Port number: 45029, start advertisements: false
,03-31 13:00:30.671 11224 11287 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-31 13:00:30.671 11224 11287 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 13:00:30.671 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-31 13:00:30.676 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-31 13:00:30.676 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-31 13:00:30.676 11224 11287 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 13:00:30.681  5893  5903 D BtGatt.GattService: registerClient() - UUID=d53d6c21-b602-4789-820b-827b86aaba0d
,03-31 13:00:30.721  5893  5958 D BtGatt.GattService: onClientRegistered() - UUID=d53d6c21-b602-4789-820b-827b86aaba0d, clientIf=6
,03-31 13:00:30.721 11224 11234 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-31 13:00:30.726  5893  8993 D BtGatt.GattService: start scan with filters
,03-31 13:00:30.731  5893  8993 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 46
,03-31 13:00:30.731 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 13:00:30.731 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 13:00:30.731  5893  5979 D BtGatt.ScanManager: handling starting scan
03-31 13:00:30.731  5893  5979 D BtGatt.ScanManager: isFilteringSupported
03-31 13:00:30.731 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-31 13:00:30.731  5893  5979 D BluetoothAdapter: setting StandAloneBleMode
03-31 13:00:30.731 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 13:00:30.731 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 13:00:30.736 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-31 13:00:30.736 11224 11224 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-31 13:00:30.736 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 13:00:30.736 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 13:00:30.736 11224 11287 I io.jxcore.node.ConnectionHelper: start: OK
03-31 13:00:30.736 11224 11224 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 13:00:30.736 11224 11224 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 13:00:30.736 11224 11224 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-31 13:00:30.736  5893  5958 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-31 13:00:30.736  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 13:00:30.736  5893  5979 D BtGatt.ScanManager: allow scan with filters
03-31 13:00:30.736  5893  5979 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-31 13:00:30.741  5893  5979 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,03-31 13:00:30.741  5893  5958 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,03-31 13:00:30.741  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 13:00:30.741  5893  5979 D BtGatt.ScanManager: Starting BLE batch scan
03-31 13:00:30.741  5893  5979 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-31 13:00:30.741 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false},
03-31 13:00:30.741 11224 11287 I jxcore-log: 
03-31 13:00:30.741  5893  5958 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-31 13:00:30.741  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 13:00:30.746  5893  5958 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,03-31 13:00:30.746 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 13:00:30.746 11224 11287 I jxcore-log: 
03-31 13:00:30.746  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 13:00:30.756 11224 11287 I io.jxcore.node.ConnectionHelper: start: Port number: 37281, start advertisements: true
,03-31 13:00:30.756 11224 11287 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 13:00:30.756 11224 11287 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-31 13:00:30.756 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-31 13:00:30.761 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-31 13:00:30.761 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
03-31 13:00:30.761 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 13:00:30.761 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-31 13:00:30.761 11224 11287 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-31 13:00:30.761 11224 11287 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-31 13:00:30.761 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 13:00:30.761 11224 11287 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-31 13:00:30.766  5893  5987 D BtGatt.GattService: registerClient() - UUID=92b64c29-d8c3-4689-983d-d8cf3ba5bee8
,03-31 13:00:30.806  5893  5958 D BtGatt.GattService: onClientRegistered() - UUID=92b64c29-d8c3-4689-983d-d8cf3ba5bee8, clientIf=7,
03-31 13:00:30.811 11224 11280 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-31 13:00:30.836  5893  5905 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 37
,03-31 13:00:30.836  5893  5978 D BtGatt.AdvertiseManager: message : 0
,03-31 13:00:30.836  5893  5978 D BtGatt.AdvertiseManager: number of adv instance running0
03-31 13:00:30.836  5893  5978 D BtGatt.AdvertiseManager: size of list is =0
,03-31 13:00:30.836  5893  5978 D BtGatt.AdvertiseManager: starting advertising
,03-31 13:00:30.836  5893  5978 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-31 13:00:30.841  5893  5958 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-31 13:00:30.841  5893  5978 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 13:00:30.846  5893  5958 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-31 13:00:30.846  5893  5978 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-31 13:00:30.846  5893  5978 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
03-31 13:00:30.846 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 13:00:30.846 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-31 13:00:30.846 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-31 13:00:30.846 11224 11224 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-31 13:00:30.846 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-31 13:00:30.846 11224 11224 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
,03-31 13:00:30.846 11224 11224 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
,03-31 13:00:30.851 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-31 13:00:30.851 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 13:00:30.851 11224 11287 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-31 13:00:30.851 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 13:00:30.851 11224 11224 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-31 13:00:30.851 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-31 13:00:30.856 11224 11287 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,03-31 13:00:30.856 11224 11287 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-31 13:00:30.856 11224 11287 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-31 13:00:30.856 11224 11287 I io.jxcore.node.ConnectionHelper: start: OK
03-31 13:00:30.856 11224 11224 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-31 13:00:30.856 11224 11224 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-31 13:00:30.856 11224 11224 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,03-31 13:00:30.856 11224 11592 D BluetoothSocket: bindListen(): myUserId = 0
,03-31 13:00:30.856 11224 11592 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-31 13:00:30.861 11224 11592 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[121]}
,03-31 13:00:30.861 11224 11592 D BluetoothSocket: bindListen(), new LocalSocket 
03-31 13:00:30.861 11224 11592 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-31 13:00:30.861 11224 11592 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2d2a0929
03-31 13:00:30.861 11224 11592 D BluetoothSocket: channel: 6
,03-31 13:00:30.861 11224 11592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-31 13:00:30.866 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-31 13:00:30.866 11224 11287 I jxcore-log: 
,03-31 13:00:30.876 11224 11287 I jxcore-log: ok 119 called only once
03-31 13:00:30.876 11224 11287 I jxcore-log: 
,03-31 13:00:30.876 11224 11287 I jxcore-log: ok 120 discovery state matches
03-31 13:00:30.876 11224 11287 I jxcore-log: 
,03-31 13:00:30.876 11224 11287 I jxcore-log: ok 121 advertising state matches
03-31 13:00:30.876 11224 11287 I jxcore-log: 
,03-31 13:00:30.896 11224 11287 I jxcore-log: # teardown
03-31 13:00:30.896 11224 11287 I jxcore-log: 
,03-31 13:00:31.101 11224 11287 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 13:00:31.106 11224 11287 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
,03-31 13:00:31.106 11224 11287 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,03-31 13:00:31.106 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-31 13:00:31.106 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,03-31 13:00:31.106 11224 11287 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@86694ae, channel: 6, state: LISTENING
,03-31 13:00:31.106 11224 11287 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@86694ae, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2d2a0929, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@18e824fmSocket: android.net.LocalSocket@2d7bbddc impl:android.net.LocalSocketImpl@5b10ee5 fd:FileDescriptor[121]
,03-31 13:00:31.106 11224 11287 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2d7bbddc impl:android.net.LocalSocketImpl@5b10ee5 fd:FileDescriptor[121]
,03-31 13:00:31.111 11224 11287 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-31 13:00:31.111 11224 11592 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-31 13:00:31.111 11224 11592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-31 13:00:31.111 11224 11592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-31 13:00:31.111 11224 11224 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-31 13:00:31.111 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-31 13:00:31.116 11224 11224 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-31 13:00:31.116 11224 11224 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-31 13:00:31.116 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-31 13:00:31.116 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-31 13:00:31.116 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode,
03-31 13:00:31.116 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-31 13:00:31.116 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-31 13:00:31.121  5893  8993 D BtGatt.GattService: stopScan() - queue size =1,
03-31 13:00:31.121  5893  5979 D BtGatt.ScanManager: filter size is 1
03-31 13:00:31.121  5893  5979 D BtGatt.ScanManager: delete FilterIndex - 5
,03-31 13:00:31.126  5893  5958 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16,
,03-31 13:00:31.126  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,03-31 13:00:31.126  5893  5979 D BtGatt.ScanManager: stopping BLe Batch,
03-31 13:00:31.126  5893  5958 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0,
03-31 13:00:31.126  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
03-31 13:00:31.126  5893  5979 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6,
,03-31 13:00:31.131  5893  5958 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2,
,03-31 13:00:31.131  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 13:00:31.131  5893  5958 D BtGatt.GattService: current time is 232226535651,
,03-31 13:00:31.131  5893  5958 D BtGatt.GattService: Batch record : [-13, -4, 57, -12, 39, 108, 1, -128, -80, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, 51, -101, -54, 51, 38, 107, 1, -128, -61, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0]
03-31 13:00:31.131  5893  5958 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81],
,03-31 13:00:31.131  5893  5958 D ScanRecord: parseFromBytes
,03-31 13:00:31.131  5893  5958 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-31 13:00:31.131  5893  5958 D ScanRecord: parseFromBytes
03-31 13:00:31.131  5893  5987 D BtGatt.GattService: unregisterClient() - clientIf=6,
03-31 13:00:31.136 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 13:00:31.136 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 13:00:31.136 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,03-31 13:00:31.136 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-31 13:00:31.136 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-31 13:00:31.136 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 13:00:31.136 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-31 13:00:31.141  5893  5978 D BtGatt.AdvertiseManager: message : 1
03-31 13:00:31.141  5893  5978 D BtGatt.AdvertiseManager: stop advertise for client 7
03-31 13:00:31.141  5893  5978 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-31 13:00:31.141  5893  5978 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-31 13:00:31.146  5893  5958 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-31 13:00:31.146  5893  5958 D BtGatt.GattService: Client app is not null!
,03-31 13:00:31.146  5893  8993 D BtGatt.GattService: unregisterClient() - clientIf=7
03-31 13:00:31.146 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
,03-31 13:00:31.146 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED,
03-31 13:00:31.146 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-31 13:00:31.146 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,03-31 13:00:31.146 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-31 13:00:31.146 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 13:00:31.146 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 13:00:31.146 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-31 13:00:31.151 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-31 13:00:31.151 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 13:00:31.151 11224 11224 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 13:00:31.151 11224 11224 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 13:00:31.151 11224 11224 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 13:00:31.151 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-31 13:00:31.151 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-31 13:00:31.156 11224 11224 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-31 13:00:31.161 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
03-31 13:00:31.171 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 13:00:31.171 11224 11224 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 13:00:31.171 11224 11224 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-31 13:00:31.171 11224 11224 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 13:00:31.171 11224 11224 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 13:00:31.171 11224 11287 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 13:00:31.171 11224 11287 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-31 13:00:31.171 11224 11287 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-31 13:00:31.176 11224 11287 I jxcore-log: INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
03-31 13:00:31.176 11224 11287 I jxcore-log: 
03-31 13:00:31.176 11224 11287 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-31 13:00:31.176 11224 11287 I jxcore-log: 
,03-31 13:00:31.186 11224 11287 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-31 13:00:31.186 11224 11287 I jxcore-log: 
,03-31 13:00:31.191 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-31 13:00:31.191 11224 11287 I jxcore-log: 
,03-31 13:00:31.191 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 13:00:31.191 11224 11287 I jxcore-log: 
,03-31 13:00:31.196 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 13:00:31.196 11224 11287 I jxcore-log: 
,03-31 13:00:31.206 11224 11287 I jxcore-log: ok 122 error should be null
03-31 13:00:31.206 11224 11287 I jxcore-log: 
,03-31 13:00:31.206 11224 11287 I jxcore-log: ok 123 error should be null
03-31 13:00:31.206 11224 11287 I jxcore-log: 
,03-31 13:00:31.211 11224 11287 I jxcore-log: # setup
03-31 13:00:31.211 11224 11287 I jxcore-log: 
,03-31 13:00:31.271 11224 11287 I jxcore-log: # 32. does not send duplicate availability changes
03-31 13:00:31.271 11224 11287 I jxcore-log: 
,03-31 13:00:31.421 11224 11287 I jxcore-log: ok 124 should be called once
03-31 13:00:31.421 11224 11287 I jxcore-log: 
,03-31 13:00:31.426 11224 11287 I jxcore-log: ok 125 should not have been called more than once
03-31 13:00:31.426 11224 11287 I jxcore-log: 
,03-31 13:00:31.431 11224 11287 I jxcore-log: # teardown
03-31 13:00:31.431 11224 11287 I jxcore-log: 
,03-31 13:00:31.546 11224 11287 I jxcore-log: ok 126 error should be null
03-31 13:00:31.546 11224 11287 I jxcore-log: 
,03-31 13:00:31.551 11224 11287 I jxcore-log: ok 127 error should be null
03-31 13:00:31.551 11224 11287 I jxcore-log: 
,03-31 13:00:31.556 11224 11287 I jxcore-log: # setup
03-31 13:00:31.556 11224 11287 I jxcore-log: 
,03-31 13:00:32.151 11224 11287 I jxcore-log: # 33. can get the network status
03-31 13:00:32.151 11224 11287 I jxcore-log: 
,03-31 13:00:32.816 11224 11287 I jxcore-log: ok 128 network status should have certain non-empty properties
03-31 13:00:32.816 11224 11287 I jxcore-log: 
,03-31 13:00:32.821 11224 11287 I jxcore-log: # teardown
03-31 13:00:32.821 11224 11287 I jxcore-log: 
,03-31 13:00:32.991 11224 11287 I jxcore-log: ok 129 error should be null
03-31 13:00:32.991 11224 11287 I jxcore-log: 
,03-31 13:00:32.991 11224 11287 I jxcore-log: ok 130 error should be null
03-31 13:00:32.991 11224 11287 I jxcore-log: 
,03-31 13:00:33.001 11224 11287 I jxcore-log: # setup
03-31 13:00:33.001 11224 11287 I jxcore-log: 
,03-31 13:00:33.266 11224 11287 I jxcore-log: # 34. wifi peer is marked unavailable if announcements stop
03-31 13:00:33.266 11224 11287 I jxcore-log: 
,03-31 13:00:33.421 11224 11287 I jxcore-log: ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
03-31 13:00:33.421 11224 11287 I jxcore-log: 
,03-31 13:00:33.451 11224 11287 I jxcore-log: ok 131 host address should match
03-31 13:00:33.451 11224 11287 I jxcore-log: 
,03-31 13:00:33.451 11224 11287 I jxcore-log: ok 132 port should match
03-31 13:00:33.451 11224 11287 I jxcore-log: 
,03-31 13:00:34.936  3461  3967 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 13:00:34.936  3461  3967 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 13:00:34.936  3461  3967 D BatteryService: online:4, current avg:42, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:39
,03-31 13:00:34.941  3461  3461 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 13:00:34.951  3461  3461 I MotionRecognitionService: Plugged
03-31 13:00:34.951  3461  3461 D MotionRecognitionService:   cableConnection= 1,
03-31 13:00:34.951  3461  3461 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-31 13:00:34.951  3461  3461 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 13:00:34.951  3461  3967 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 12ms
,03-31 13:00:34.951  3461  3967 D BatteryService: stay LED for fully charged,
,03-31 13:00:34.961  3728  3728 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-31 13:00:34.961  3728  3728 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 13:00:34.961  3728  3728 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-31 13:00:34.981  5893  5893 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 13:00:34.981  5893  5980 D HeadsetStateMachine: Disconnected process message: 10
,03-31 13:00:34.991  3728  3728 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 13:00:34.991  3728  3728 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 13:00:34.991  3728  3728 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 13:00:34.991  3728  3728 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 13:00:35.196  3461  6089 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:12), CUR = 42, LCD = 0
,03-31 13:00:35.436 11224 11287 I jxcore-log: ok 133 host address should be null,
,03-31 13:00:35.436 11224 11287 I jxcore-log: 
,03-31 13:00:35.446 11224 11287 I jxcore-log: ok 134 port should should be null
03-31 13:00:35.446 11224 11287 I jxcore-log: 
,03-31 13:00:35.471 11224 11287 I jxcore-log: # teardown
03-31 13:00:35.471 11224 11287 I jxcore-log: 
,03-31 13:00:35.526 11224 11287 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-31 13:00:35.526 11224 11287 I jxcore-log: 
,03-31 13:00:35.531 11224 11287 I jxcore-log: ok 135 error should be null
03-31 13:00:35.531 11224 11287 I jxcore-log: 
,03-31 13:00:35.531 11224 11287 I jxcore-log: ok 136 error should be null
03-31 13:00:35.531 11224 11287 I jxcore-log: 
,03-31 13:00:35.531 11224 11287 I jxcore-log: # setup
03-31 13:00:35.531 11224 11287 I jxcore-log: 
,03-31 13:00:35.671 11224 11287 I jxcore-log: # 35. Can call start/stopListeningForAdvertisements
03-31 13:00:35.671 11224 11287 I jxcore-log: 
,03-31 13:00:35.796 11224 11287 I io.jxcore.node.ConnectionHelper: start: Port number: 37281, start advertisements: false
,03-31 13:00:35.796 11224 11287 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 13:00:35.796 11224 11287 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,03-31 13:00:35.796 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-31 13:00:35.801 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-31 13:00:35.801 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 13:00:35.801 11224 11287 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 13:00:35.806  5893  5987 D BtGatt.GattService: registerClient() - UUID=965c06a4-c9d6-479b-af7c-4862c0b5c175
,03-31 13:00:35.851  5893  5958 D BtGatt.GattService: onClientRegistered() - UUID=965c06a4-c9d6-479b-af7c-4862c0b5c175, clientIf=6
03-31 13:00:35.851 11224 11233 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-31 13:00:35.856  5893  5905 D BtGatt.GattService: start scan with filters
,03-31 13:00:35.876  5893  5905 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 47
,03-31 13:00:35.881  5893  5979 D BtGatt.ScanManager: handling starting scan
03-31 13:00:35.881  5893  5979 D BtGatt.ScanManager: isFilteringSupported
03-31 13:00:35.881  5893  5979 D BluetoothAdapter: setting StandAloneBleMode
,03-31 13:00:35.891  5893  5958 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-31 13:00:35.891  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 13:00:35.891  5893  5979 D BtGatt.ScanManager: allow scan with filters
03-31 13:00:35.891  5893  5979 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-31 13:00:35.891  5893  5979 D BtGatt.ScanManager: set filter index= 6 for clientIf= 6
03-31 13:00:35.891  5893  5958 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-31 13:00:35.891  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 13:00:35.891  5893  5979 D BtGatt.ScanManager: Starting BLE batch scan
,03-31 13:00:35.891  5893  5979 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-31 13:00:35.896  5893  5958 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,03-31 13:00:35.896  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 13:00:35.896  5893  5958 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1,
03-31 13:00:35.896  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,03-31 13:00:35.901 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
03-31 13:00:35.906 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-31 13:00:35.906 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-31 13:00:35.906 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,03-31 13:00:35.906 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 13:00:35.906 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-31 13:00:35.906 11224 11224 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 13:00:35.906 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 13:00:35.906 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-31 13:00:35.906 11224 11224 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 13:00:35.906 11224 11224 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 13:00:35.906 11224 11224 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 13:00:35.911 11224 11287 I io.jxcore.node.ConnectionHelper: start: OK
,03-31 13:00:35.911 11224 11287 I jxcore-log: ok 137 Can call startListeningForAdvertisements without error
03-31 13:00:35.911 11224 11287 I jxcore-log: 
03-31 13:00:35.911 11224 11287 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 13:00:35.911 11224 11287 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 13:00:35.911 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-31 13:00:35.911 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-31 13:00:35.921  5893  5987 D BtGatt.GattService: stopScan() - queue size =1,
03-31 13:00:35.921  5893  5979 D BtGatt.ScanManager: filter size is 1
03-31 13:00:35.921  5893  5979 D BtGatt.ScanManager: delete FilterIndex - 6
,03-31 13:00:35.921  5893  5958 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,03-31 13:00:35.921  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,03-31 13:00:35.921  5893  5979 D BtGatt.ScanManager: stopping BLe Batch
03-31 13:00:35.926  5893  5958 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0,
03-31 13:00:35.926  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,03-31 13:00:35.926  5893  5979 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-31 13:00:35.926  5893  5958 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0,
03-31 13:00:35.926  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,03-31 13:00:35.931  5893  5903 D BtGatt.GattService: unregisterClient() - clientIf=6,
03-31 13:00:35.931 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
03-31 13:00:35.931 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 13:00:35.931 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false,
03-31 13:00:35.931 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED],
03-31 13:00:35.931 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-31 13:00:35.931 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false,
03-31 13:00:35.936 11224 11224 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false,
03-31 13:00:35.936 11224 11224 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 13:00:35.936 11224 11224 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed,
,03-31 13:00:35.941 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false},
03-31 13:00:35.941 11224 11287 I jxcore-log: 
,03-31 13:00:35.941 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 13:00:35.941 11224 11287 I jxcore-log: 
,03-31 13:00:35.946 11224 11287 I jxcore-log: ok 138 Can call stopListeningForAdvertisements without error
03-31 13:00:35.946 11224 11287 I jxcore-log: 
,03-31 13:00:35.956 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 13:00:35.956 11224 11287 I jxcore-log: 
,03-31 13:00:35.956 11224 11287 I jxcore-log: # teardown
03-31 13:00:35.956 11224 11287 I jxcore-log: 
,03-31 13:00:36.066 11224 11287 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 13:00:36.066 11224 11287 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 13:00:36.066 11224 11287 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 13:00:36.076 11224 11287 I jxcore-log: ok 139 Should be able to call stopListeningForAdvertisments in teardown
03-31 13:00:36.076 11224 11287 I jxcore-log: 
,03-31 13:00:36.076 11224 11287 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 13:00:36.076 11224 11287 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 13:00:36.076 11224 11287 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,03-31 13:00:36.081 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-31 13:00:36.081 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-31 13:00:36.081 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-31 13:00:36.081 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-31 13:00:36.081 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-31 13:00:36.081 11224 11287 D BluetoothLeScanner: could not find callback wrapper
,03-31 13:00:36.081 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-31 13:00:36.086 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
03-31 13:00:36.086 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 13:00:36.086 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-31 13:00:36.091 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-31 13:00:36.091 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 13:00:36.091 11224 11224 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 13:00:36.091 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 13:00:36.091 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-31 13:00:36.101 11224 11224 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
,03-31 13:00:36.106 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-31 13:00:36.106 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-31 13:00:36.111 11224 11224 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 13:00:36.111 11224 11224 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 13:00:36.116 11224 11224 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 13:00:36.116 11224 11224 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-31 13:00:36.116 11224 11287 I jxcore-log: ok 140 Should be able to call stopAdvertisingAndListening in teardown
03-31 13:00:36.116 11224 11287 I jxcore-log: 
,03-31 13:00:36.126 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 13:00:36.126 11224 11287 I jxcore-log: 
,03-31 13:00:36.126 11224 11287 I jxcore-log: # setup
03-31 13:00:36.126 11224 11287 I jxcore-log: 
,03-31 13:00:36.181 11224 11287 I jxcore-log: # 36. Calling startListeningForAdvertisements twice is NOT an error
03-31 13:00:36.181 11224 11287 I jxcore-log: 
,03-31 13:00:36.321 11224 11287 I io.jxcore.node.ConnectionHelper: start: Port number: 37281, start advertisements: false
,03-31 13:00:36.321 11224 11287 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-31 13:00:36.321 11224 11287 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 13:00:36.321 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-31 13:00:36.326 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-31 13:00:36.326 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-31 13:00:36.326 11224 11287 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 13:00:36.336  5893  8993 D BtGatt.GattService: registerClient() - UUID=31eed20e-ffc2-478f-b958-13c804f2cc7e
,03-31 13:00:36.376  5893  5958 D BtGatt.GattService: onClientRegistered() - UUID=31eed20e-ffc2-478f-b958-13c804f2cc7e, clientIf=6
03-31 13:00:36.376 11224 11280 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-31 13:00:36.376  5893  5987 D BtGatt.GattService: start scan with filters,
,03-31 13:00:36.406  5893  5987 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 48
,03-31 13:00:36.406  5893  5979 D BtGatt.ScanManager: handling starting scan
03-31 13:00:36.406  5893  5979 D BtGatt.ScanManager: isFilteringSupported
03-31 13:00:36.406  5893  5979 D BluetoothAdapter: setting StandAloneBleMode
,03-31 13:00:36.411  5893  5958 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-31 13:00:36.411  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 13:00:36.411  5893  5979 D BtGatt.ScanManager: allow scan with filters
03-31 13:00:36.411  5893  5979 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-31 13:00:36.411  5893  5979 D BtGatt.ScanManager: set filter index= 7 for clientIf= 6
03-31 13:00:36.416  5893  5958 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-31 13:00:36.416  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 13:00:36.416  5893  5979 D BtGatt.ScanManager: Starting BLE batch scan
,03-31 13:00:36.416  5893  5979 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-31 13:00:36.421  5893  5958 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-31 13:00:36.421  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 13:00:36.426  5893  5958 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-31 13:00:36.426  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 13:00:36.426 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
03-31 13:00:36.426 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 13:00:36.426 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,03-31 13:00:36.426 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 13:00:36.426 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 13:00:36.426 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-31 13:00:36.426 11224 11224 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-31 13:00:36.431 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 13:00:36.431 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 13:00:36.431 11224 11224 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 13:00:36.431 11224 11224 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 13:00:36.431 11224 11224 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 13:00:36.431 11224 11287 I io.jxcore.node.ConnectionHelper: start: OK
03-31 13:00:36.431 11224 11287 I jxcore-log: ok 141 Can call startListeningForAdvertisements without error
03-31 13:00:36.431 11224 11287 I jxcore-log: 
,03-31 13:00:36.441 11224 11287 I io.jxcore.node.ConnectionHelper: start: Port number: 37281, start advertisements: false
,03-31 13:00:36.446 11224 11287 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 13:00:36.446 11224 11287 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,03-31 13:00:36.446 11224 11287 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 13:00:36.446 11224 11287 I io.jxcore.node.ConnectionHelper: start: OK
,03-31 13:00:36.446 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 13:00:36.446 11224 11287 I jxcore-log: 
,03-31 13:00:36.451 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 13:00:36.451 11224 11287 I jxcore-log: 
,03-31 13:00:36.451 11224 11287 I jxcore-log: ok 142 Can call startListeningForAdvertisements twice without error
03-31 13:00:36.451 11224 11287 I jxcore-log: 
,03-31 13:00:36.461 11224 11287 I jxcore-log: # teardown
03-31 13:00:36.461 11224 11287 I jxcore-log: 
,03-31 13:00:36.666 11224 11287 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 13:00:36.666 11224 11287 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-31 13:00:36.666 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-31 13:00:36.666 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-31 13:00:36.671  5893  5905 D BtGatt.GattService: stopScan() - queue size =1
03-31 13:00:36.671  5893  5979 D BtGatt.ScanManager: filter size is 1
03-31 13:00:36.671  5893  5979 D BtGatt.ScanManager: delete FilterIndex - 7
03-31 13:00:36.671  5893  5958 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,03-31 13:00:36.671  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 13:00:36.676  5893  5979 D BtGatt.ScanManager: stopping BLe Batch
,03-31 13:00:36.676  5893  5958 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0,
03-31 13:00:36.676  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 13:00:36.676  5893  5979 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-31 13:00:36.681  5893  5958 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,03-31 13:00:36.681  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 13:00:36.681  5893  8993 D BtGatt.GattService: unregisterClient() - clientIf=6,
,03-31 13:00:36.686 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 13:00:36.686 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 13:00:36.686 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-31 13:00:36.686 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-31 13:00:36.686 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,03-31 13:00:36.686 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false,
03-31 13:00:36.691 11224 11224 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false,
03-31 13:00:36.691 11224 11224 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 13:00:36.691 11224 11224 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-31 13:00:36.696 11224 11287 I jxcore-log: ok 143 Should be able to call stopListeningForAdvertisments in teardown
03-31 13:00:36.696 11224 11287 I jxcore-log: 
,03-31 13:00:36.696 11224 11287 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 13:00:36.696 11224 11287 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 13:00:36.696 11224 11287 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-31 13:00:36.696 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-31 13:00:36.696 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-31 13:00:36.696 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-31 13:00:36.696 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-31 13:00:36.696 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-31 13:00:36.701 11224 11287 D BluetoothLeScanner: could not find callback wrapper
,03-31 13:00:36.701 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-31 13:00:36.701 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-31 13:00:36.701 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 13:00:36.701 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-31 13:00:36.706 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-31 13:00:36.706 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 13:00:36.706 11224 11224 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 13:00:36.706 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 13:00:36.706 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-31 13:00:36.711 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 13:00:36.711 11224 11287 I jxcore-log: 
,03-31 13:00:36.716 11224 11224 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-31 13:00:36.721 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-31 13:00:36.721 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 13:00:36.721 11224 11224 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 13:00:36.726 11224 11224 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 13:00:36.726 11224 11224 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 13:00:36.726 11224 11224 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-31 13:00:36.726 11224 11287 I jxcore-log: ok 144 Should be able to call stopAdvertisingAndListening in teardown
03-31 13:00:36.726 11224 11287 I jxcore-log: 
,03-31 13:00:36.731 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 13:00:36.731 11224 11287 I jxcore-log: 
,03-31 13:00:36.731 11224 11287 I jxcore-log: # setup
03-31 13:00:36.731 11224 11287 I jxcore-log: 
,03-31 13:00:36.866 11224 11287 I jxcore-log: # 37. Can call start/stopUpdateAdvertisingAndListening
03-31 13:00:36.866 11224 11287 I jxcore-log: 
,03-31 13:00:37.026 11224 11287 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true
,03-31 13:00:37.026 11224 11287 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 13:00:37.026 11224 11287 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-31 13:00:37.026 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-31 13:00:37.031 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-31 13:00:37.031 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-31 13:00:37.031 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 13:00:37.031 11224 11287 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 13:00:37.036  5893  5903 D BtGatt.GattService: registerClient() - UUID=832d2aff-b3bb-493c-a92d-b7a02aa533a4
,03-31 13:00:37.081  5893  5958 D BtGatt.GattService: onClientRegistered() - UUID=832d2aff-b3bb-493c-a92d-b7a02aa533a4, clientIf=6
,03-31 13:00:37.081 11224 11280 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-31 13:00:37.081  5893  5905 D BtGatt.GattService: start scan with filters
,03-31 13:00:37.091  5893  5905 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 49
,03-31 13:00:37.091 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 13:00:37.091 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 13:00:37.091 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-31 13:00:37.091 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 13:00:37.091 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 13:00:37.091  5893  5979 D BtGatt.ScanManager: handling starting scan
03-31 13:00:37.091  5893  5979 D BtGatt.ScanManager: isFilteringSupported
,03-31 13:00:37.091 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 13:00:37.091  5893  5979 D BluetoothAdapter: setting StandAloneBleMode
03-31 13:00:37.091 11224 11224 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 13:00:37.091 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-31 13:00:37.091 11224 11287 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-31 13:00:37.091 11224 11287 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 13:00:37.091 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 13:00:37.091 11224 11287 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-31 13:00:37.096  5893  5905 D BtGatt.GattService: registerClient() - UUID=f081dc07-447b-406a-b9f1-4f06aa5f403f
,03-31 13:00:37.096  5893  5958 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-31 13:00:37.096  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 13:00:37.096  5893  5979 D BtGatt.ScanManager: allow scan with filters
03-31 13:00:37.096  5893  5979 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-31 13:00:37.096  5893  5979 D BtGatt.ScanManager: set filter index= 8 for clientIf= 6
,03-31 13:00:37.096  5893  5958 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-31 13:00:37.096  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 13:00:37.096  5893  5979 D BtGatt.ScanManager: Starting BLE batch scan
,03-31 13:00:37.096  5893  5979 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-31 13:00:37.101  5893  5958 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-31 13:00:37.101  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 13:00:37.101  5893  5958 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-31 13:00:37.101  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 13:00:37.136  5893  5958 D BtGatt.GattService: onClientRegistered() - UUID=f081dc07-447b-406a-b9f1-4f06aa5f403f, clientIf=7
,03-31 13:00:37.136 11224 11234 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-31 13:00:37.181  5893  8993 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 38
,03-31 13:00:37.186  5893  5978 D BtGatt.AdvertiseManager: message : 0
03-31 13:00:37.186  5893  5978 D BtGatt.AdvertiseManager: number of adv instance running0
03-31 13:00:37.186  5893  5978 D BtGatt.AdvertiseManager: size of list is =0
03-31 13:00:37.191  5893  5978 D BtGatt.AdvertiseManager: starting advertising
03-31 13:00:37.191  5893  5978 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-31 13:00:37.196  5893  5958 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-31 13:00:37.201  5893  5978 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 13:00:37.201  5893  5958 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-31 13:00:37.201  5893  5978 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,03-31 13:00:37.201  5893  5978 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,03-31 13:00:37.206 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-31 13:00:37.206 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-31 13:00:37.206 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 13:00:37.206 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 13:00:37.206 11224 11287 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-31 13:00:37.206 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 13:00:37.211 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-31 13:00:37.211 11224 11287 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-31 13:00:37.211 11224 11287 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-31 13:00:37.211 11224 11287 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-31 13:00:37.211 11224 11224 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-31 13:00:37.211 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 13:00:37.211 11224 11224 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-31 13:00:37.211 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-31 13:00:37.211 11224 11224 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-31 13:00:37.211 11224 11224 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-31 13:00:37.211 11224 11224 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 13:00:37.211 11224 11224 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 13:00:37.211 11224 11224 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-31 13:00:37.211 11224 11224 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 13:00:37.211 11224 11224 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING,
03-31 13:00:37.211 11224 11224 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 13:00:37.211 11224 11287 I io.jxcore.node.ConnectionHelper: start: OK
,03-31 13:00:37.216 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false},
03-31 13:00:37.216 11224 11287 I jxcore-log: 
,03-31 13:00:37.221 11224 11287 I jxcore-log: ok 145 Can call startUpdateAdvertisingAndListening without error,
03-31 13:00:37.221 11224 11287 I jxcore-log: 
,03-31 13:00:37.226 11224 11664 D BluetoothSocket: bindListen(): myUserId = 0
,03-31 13:00:37.226 11224 11664 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-31 13:00:37.231 11224 11664 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[92]},
03-31 13:00:37.231 11224 11664 D BluetoothSocket: bindListen(), new LocalSocket 
,03-31 13:00:37.231 11224 11664 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-31 13:00:37.231 11224 11664 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1c1f85e3
,03-31 13:00:37.231 11224 11664 D BluetoothSocket: channel: 6
03-31 13:00:37.231 11224 11664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-31 13:00:37.236 11224 11287 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 13:00:37.236 11224 11287 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-31 13:00:37.236 11224 11287 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,03-31 13:00:37.236 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-31 13:00:37.236 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-31 13:00:37.236 11224 11287 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@4c95be0, channel: 6, state: LISTENING
,03-31 13:00:37.236 11224 11287 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@4c95be0, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1c1f85e3, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@12fa8e99mSocket: android.net.LocalSocket@f77855e impl:android.net.LocalSocketImpl@53a9d3f fd:FileDescriptor[92]
03-31 13:00:37.236 11224 11287 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@f77855e impl:android.net.LocalSocketImpl@53a9d3f fd:FileDescriptor[92]
,03-31 13:00:37.236 11224 11287 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-31 13:00:37.236 11224 11664 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-31 13:00:37.236 11224 11664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-31 13:00:37.236 11224 11664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-31 13:00:37.241 11224 11224 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-31 13:00:37.241 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-31 13:00:37.241 11224 11224 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-31 13:00:37.241 11224 11224 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-31 13:00:37.241 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-31 13:00:37.241 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-31 13:00:37.241 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-31 13:00:37.241 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-31 13:00:37.241 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-31 13:00:37.246  5893  5903 D BtGatt.GattService: stopScan() - queue size =1,
03-31 13:00:37.246  5893  5979 D BtGatt.ScanManager: filter size is 1
03-31 13:00:37.246  5893  5979 D BtGatt.ScanManager: delete FilterIndex - 8
03-31 13:00:37.246  5893  5958 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,03-31 13:00:37.246  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 13:00:37.246  5893  5979 D BtGatt.ScanManager: stopping BLe Batch
,03-31 13:00:37.251  5893  5958 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0,
03-31 13:00:37.251  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 13:00:37.251  5893  5905 D BtGatt.GattService: unregisterClient() - clientIf=6
03-31 13:00:37.251  5893  5979 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6,
,03-31 13:00:37.251  5893  5958 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-31 13:00:37.251  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 13:00:37.256 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 13:00:37.256 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED,
,03-31 13:00:37.256 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false,
,03-31 13:00:37.256 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING],
03-31 13:00:37.256 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING],
,03-31 13:00:37.256 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 13:00:37.256 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...,
,03-31 13:00:37.261  5893  5978 D BtGatt.AdvertiseManager: message : 1
03-31 13:00:37.261  5893  5978 D BtGatt.AdvertiseManager: stop advertise for client 7
,03-31 13:00:37.261  5893  5978 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7,
,03-31 13:00:37.261  5893  5978 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-31 13:00:37.261  5893  5958 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-31 13:00:37.261  5893  5958 D BtGatt.GattService: Client app is not null!
03-31 13:00:37.266  5893  5903 D BtGatt.GattService: unregisterClient() - clientIf=7
03-31 13:00:37.266 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 13:00:37.266 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-31 13:00:37.266 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-31 13:00:37.266 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,03-31 13:00:37.266 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-31 13:00:37.266 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 13:00:37.266 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 13:00:37.266 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-31 13:00:37.271 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-31 13:00:37.271 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 13:00:37.271 11224 11224 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 13:00:37.271 11224 11224 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 13:00:37.271 11224 11224 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 13:00:37.271 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 13:00:37.271 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-31 13:00:37.276 11224 11224 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-31 13:00:37.281 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 13:00:37.281 11224 11287 I jxcore-log: 
03-31 13:00:37.281 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-31 13:00:37.281 11224 11287 I jxcore-log: 
03-31 13:00:37.286 11224 11287 I jxcore-log: ok 146 Can call stopAdvertisingAndListening without error
03-31 13:00:37.286 11224 11287 I jxcore-log: 
03-31 13:00:37.286 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-31 13:00:37.286 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 13:00:37.291 11224 11224 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 13:00:37.291 11224 11287 I jxcore-log: # teardown
03-31 13:00:37.291 11224 11287 I jxcore-log: 
03-31 13:00:37.296 11224 11224 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-31 13:00:37.296 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-31 13:00:37.296 11224 11287 I jxcore-log: 
03-31 13:00:37.296 11224 11224 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-31 13:00:37.296 11224 11224 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 13:00:37.296 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 13:00:37.296 11224 11287 I jxcore-log: 
,03-31 13:00:37.301 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 13:00:37.301 11224 11287 I jxcore-log: 
,03-31 13:00:37.406 11224 11287 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 13:00:37.406 11224 11287 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 13:00:37.406 11224 11287 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 13:00:37.416 11224 11287 I jxcore-log: ok 147 Should be able to call stopListeningForAdvertisments in teardown
03-31 13:00:37.416 11224 11287 I jxcore-log: 
,03-31 13:00:37.416 11224 11287 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 13:00:37.421 11224 11287 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-31 13:00:37.421 11224 11287 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 13:00:37.426 11224 11287 I jxcore-log: ok 148 Should be able to call stopAdvertisingAndListening in teardown
03-31 13:00:37.426 11224 11287 I jxcore-log: 
,03-31 13:00:37.436 11224 11287 I jxcore-log: # setup
03-31 13:00:37.436 11224 11287 I jxcore-log: 
,03-31 13:00:38.071 11224 11287 I jxcore-log: # 38. Calling startUpdateAdvertisingAndListening twice is NOT an error
03-31 13:00:38.071 11224 11287 I jxcore-log: 
,03-31 13:00:38.166 11224 11287 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true
03-31 13:00:38.166 11224 11287 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 13:00:38.166 11224 11287 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-31 13:00:38.166 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-31 13:00:38.171 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-31 13:00:38.171 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 13:00:38.171 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 13:00:38.171 11224 11287 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 13:00:38.176  5893  5903 D BtGatt.GattService: registerClient() - UUID=9caa0fb1-730b-419f-9a86-2bca889e56ca
,03-31 13:00:38.216  5893  5958 D BtGatt.GattService: onClientRegistered() - UUID=9caa0fb1-730b-419f-9a86-2bca889e56ca, clientIf=6
,03-31 13:00:38.216 11224 11233 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-31 13:00:38.221  5893  5905 D BtGatt.GattService: start scan with filters
,03-31 13:00:38.241  5893  5905 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 50
,03-31 13:00:38.241  5893  5979 D BtGatt.ScanManager: handling starting scan
03-31 13:00:38.241  5893  5979 D BtGatt.ScanManager: isFilteringSupported
03-31 13:00:38.241  5893  5979 D BluetoothAdapter: setting StandAloneBleMode
,03-31 13:00:38.251  5893  5958 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-31 13:00:38.251  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 13:00:38.251  5893  5979 D BtGatt.ScanManager: allow scan with filters
03-31 13:00:38.251  5893  5979 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-31 13:00:38.251  5893  5979 D BtGatt.ScanManager: set filter index= 9 for clientIf= 6
03-31 13:00:38.256  5893  5958 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-31 13:00:38.256  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 13:00:38.256  5893  5979 D BtGatt.ScanManager: Starting BLE batch scan
03-31 13:00:38.256  5893  5979 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-31 13:00:38.261  5893  5958 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0,
03-31 13:00:38.261  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
03-31 13:00:38.261  5893  5958 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1,
,03-31 13:00:38.261  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 13:00:38.271 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
03-31 13:00:38.271 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 13:00:38.271 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-31 13:00:38.271 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 13:00:38.271 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,03-31 13:00:38.271 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 13:00:38.271 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-31 13:00:38.271 11224 11287 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-31 13:00:38.271 11224 11287 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 13:00:38.271 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false],
03-31 13:00:38.271 11224 11287 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...,
03-31 13:00:38.271 11224 11224 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 13:00:38.276  5893  8993 D BtGatt.GattService: registerClient() - UUID=07fb75fc-c94e-45b3-a2a9-2d648091068d
,03-31 13:00:38.316  5893  5958 D BtGatt.GattService: onClientRegistered() - UUID=07fb75fc-c94e-45b3-a2a9-2d648091068d, clientIf=7,
03-31 13:00:38.316 11224 11280 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-31 13:00:38.336  5893  5987 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 39
,03-31 13:00:38.336  5893  5978 D BtGatt.AdvertiseManager: message : 0
03-31 13:00:38.336  5893  5978 D BtGatt.AdvertiseManager: number of adv instance running0
03-31 13:00:38.336  5893  5978 D BtGatt.AdvertiseManager: size of list is =0
,03-31 13:00:38.336  5893  5978 D BtGatt.AdvertiseManager: starting advertising
03-31 13:00:38.336  5893  5978 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-31 13:00:38.341  5893  5958 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-31 13:00:38.341  5893  5978 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 13:00:38.341  5893  5958 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-31 13:00:38.341  5893  5978 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-31 13:00:38.341  5893  5978 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
03-31 13:00:38.341 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-31 13:00:38.341 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-31 13:00:38.346 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-31 13:00:38.346 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 13:00:38.346 11224 11287 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-31 13:00:38.346 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 13:00:38.346 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-31 13:00:38.346 11224 11287 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-31 13:00:38.346 11224 11287 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-31 13:00:38.346 11224 11287 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-31 13:00:38.346 11224 11287 I io.jxcore.node.ConnectionHelper: start: OK
03-31 13:00:38.346 11224 11224 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-31 13:00:38.346 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 13:00:38.346 11224 11224 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-31 13:00:38.346 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-31 13:00:38.346 11224 11224 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-31 13:00:38.346 11224 11224 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-31 13:00:38.346 11224 11224 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-31 13:00:38.346 11224 11224 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 13:00:38.346 11224 11224 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-31 13:00:38.346 11224 11224 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 13:00:38.351 11224 11224 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-31 13:00:38.351 11224 11224 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-31 13:00:38.351 11224 11682 D BluetoothSocket: bindListen(): myUserId = 0
03-31 13:00:38.351 11224 11682 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-31 13:00:38.351 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 13:00:38.351 11224 11287 I jxcore-log: 
,03-31 13:00:38.351 11224 11682 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[92]}
,03-31 13:00:38.351 11224 11682 D BluetoothSocket: bindListen(), new LocalSocket 
03-31 13:00:38.351 11224 11682 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-31 13:00:38.351 11224 11682 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@4c5ce5b
03-31 13:00:38.351 11224 11682 D BluetoothSocket: channel: 6
03-31 13:00:38.351 11224 11682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-31 13:00:38.356 11224 11287 I jxcore-log: ok 149 Can call startUpdateAdvertisingAndListening without error
03-31 13:00:38.356 11224 11287 I jxcore-log: 
,03-31 13:00:38.356 11224 11287 I io.jxcore.node.ConnectionHelper: start: Port number: 4243, start advertisements: true
,03-31 13:00:38.356 11224 11287 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 13:00:38.356 11224 11287 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-31 13:00:38.356 11224 11287 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-31 13:00:38.356 11224 11287 I io.jxcore.node.ConnectionHelper: start: OK
,03-31 13:00:38.361 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 13:00:38.361 11224 11287 I jxcore-log: 
,03-31 13:00:38.361 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-31 13:00:38.361 11224 11287 I jxcore-log: 
,03-31 13:00:38.361 11224 11287 I jxcore-log: ok 150 Can call startUpdateAdvertisingAndListening twice without error
03-31 13:00:38.361 11224 11287 I jxcore-log: 
,03-31 13:00:38.371 11224 11287 I jxcore-log: # teardown
03-31 13:00:38.371 11224 11287 I jxcore-log: 
,03-31 13:00:38.551 11224 11287 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 13:00:38.551 11224 11287 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
,03-31 13:00:38.556 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,03-31 13:00:38.556 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-31 13:00:38.561  5893  5903 D BtGatt.GattService: stopScan() - queue size =1
03-31 13:00:38.561  5893  5979 D BtGatt.ScanManager: filter size is 1
,03-31 13:00:38.561  5893  5979 D BtGatt.ScanManager: delete FilterIndex - 9
03-31 13:00:38.561  5893  5958 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,03-31 13:00:38.561  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 13:00:38.566  5893  5979 D BtGatt.ScanManager: stopping BLe Batch
,03-31 13:00:38.566  5893  5958 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0,
,03-31 13:00:38.571  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 13:00:38.571  5893  5979 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-31 13:00:38.571  5893  5958 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2,
03-31 13:00:38.571  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 13:00:38.571  5893  5958 D BtGatt.GattService: current time is 239669208485,
03-31 13:00:38.571  5893  5958 D BtGatt.GattService: Batch record : [-68, 26, -115, -51, 88, 125, 1, -128, -91, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -13, 69, -67, 43, 88, 87, 1, -128, -68, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0]
03-31 13:00:38.571  5893  5958 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-31 13:00:38.571  5893  5958 D ScanRecord: parseFromBytes
,03-31 13:00:38.576  5893  5958 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-31 13:00:38.576  5893  5958 D ScanRecord: parseFromBytes
03-31 13:00:38.576  5893  5905 D BtGatt.GattService: unregisterClient() - clientIf=6
03-31 13:00:38.581 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-31 13:00:38.581 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 13:00:38.581 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-31 13:00:38.581 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-31 13:00:38.581 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-31 13:00:38.581 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 13:00:38.586 11224 11224 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 13:00:38.586 11224 11224 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
,03-31 13:00:38.586 11224 11224 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 13:00:38.586 11224 11287 I jxcore-log: ok 151 Should be able to call stopListeningForAdvertisments in teardown
03-31 13:00:38.586 11224 11287 I jxcore-log: 
,03-31 13:00:38.596 11224 11287 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-31 13:00:38.596 11224 11287 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-31 13:00:38.596 11224 11287 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-31 13:00:38.596 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-31 13:00:38.596 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,03-31 13:00:38.596 11224 11287 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@27ac6f8, channel: 6, state: LISTENING
,03-31 13:00:38.596 11224 11287 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@27ac6f8, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@4c5ce5b, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@12b677d1mSocket: android.net.LocalSocket@cd8e236 impl:android.net.LocalSocketImpl@3908f537 fd:FileDescriptor[92]
03-31 13:00:38.596 11224 11287 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@cd8e236 impl:android.net.LocalSocketImpl@3908f537 fd:FileDescriptor[92]
,03-31 13:00:38.596 11224 11287 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-31 13:00:38.596 11224 11682 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close,
03-31 13:00:38.596 11224 11682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-31 13:00:38.596 11224 11682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-31 13:00:38.601 11224 11224 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-31 13:00:38.601 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-31 13:00:38.601 11224 11224 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED,
03-31 13:00:38.601 11224 11224 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-31 13:00:38.601 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-31 13:00:38.601 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart,
,03-31 13:00:38.601 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode,
03-31 13:00:38.601 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser,
,03-31 13:00:38.601 11224 11287 D BluetoothLeScanner: could not find callback wrapper
03-31 13:00:38.601 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-31 13:00:38.601 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...,
03-31 13:00:38.606  5893  5978 D BtGatt.AdvertiseManager: message : 1,
,03-31 13:00:38.606  5893  5978 D BtGatt.AdvertiseManager: stop advertise for client 7
03-31 13:00:38.606  5893  5978 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
,03-31 13:00:38.611  5893  5978 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-31 13:00:38.611  5893  5958 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-31 13:00:38.611  5893  5958 D BtGatt.GattService: Client app is not null!
03-31 13:00:38.611  5893  5905 D BtGatt.GattService: unregisterClient() - clientIf=7
,03-31 13:00:38.616 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 13:00:38.616 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-31 13:00:38.616 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-31 13:00:38.616 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-31 13:00:38.616 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,03-31 13:00:38.616 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 13:00:38.616 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 13:00:38.616 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-31 13:00:38.616 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-31 13:00:38.616 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 13:00:38.616 11224 11224 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 13:00:38.616 11224 11224 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-31 13:00:38.616 11224 11224 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 13:00:38.616 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 13:00:38.616 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener,
,03-31 13:00:38.621 11224 11224 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-31 13:00:38.626 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-31 13:00:38.626 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
03-31 13:00:38.626 11224 11224 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 13:00:38.631 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-31 13:00:38.631 11224 11287 I jxcore-log: 
03-31 13:00:38.631 11224 11287 I jxcore-log: ok 152 Should be able to call stopAdvertisingAndListening in teardown
03-31 13:00:38.631 11224 11287 I jxcore-log: 
03-31 13:00:38.641 11224 11224 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-31 13:00:38.641 11224 11224 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 13:00:38.646 11224 11287 I jxcore-log: # setup
03-31 13:00:38.646 11224 11287 I jxcore-log: 
,03-31 13:00:38.651 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 13:00:38.651 11224 11287 I jxcore-log: 
,03-31 13:00:38.651 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 13:00:38.651 11224 11287 I jxcore-log: 
,03-31 13:00:38.816 11224 11287 I jxcore-log: # 39. peerAvailabilityChange is called
03-31 13:00:38.816 11224 11287 I jxcore-log: 
,03-31 13:00:39.081 11224 11287 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true
,03-31 13:00:39.086 11224 11287 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 13:00:39.086 11224 11287 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-31 13:00:39.086 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-31 13:00:39.091 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-31 13:00:39.091 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 13:00:39.091 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-31 13:00:39.091 11224 11287 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 13:00:39.096  5893  5905 D BtGatt.GattService: registerClient() - UUID=6e9efd28-4d1b-4d5e-ae53-467056b813c2
,03-31 13:00:39.141  5893  5958 D BtGatt.GattService: onClientRegistered() - UUID=6e9efd28-4d1b-4d5e-ae53-467056b813c2, clientIf=6
03-31 13:00:39.141 11224 11234 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-31 13:00:39.141  5893  8993 D BtGatt.GattService: start scan with filters
,03-31 13:00:39.156  5893  8993 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 51
,03-31 13:00:39.156  5893  5979 D BtGatt.ScanManager: handling starting scan
03-31 13:00:39.156  5893  5979 D BtGatt.ScanManager: isFilteringSupported
03-31 13:00:39.156  5893  5979 D BluetoothAdapter: setting StandAloneBleMode
,03-31 13:00:39.161  5893  5958 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-31 13:00:39.161  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 13:00:39.161  5893  5979 D BtGatt.ScanManager: allow scan with filters
03-31 13:00:39.161  5893  5979 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-31 13:00:39.161  5893  5979 D BtGatt.ScanManager: set filter index= 10 for clientIf= 6
03-31 13:00:39.161  5893  5958 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-31 13:00:39.161  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 13:00:39.161  5893  5979 D BtGatt.ScanManager: Starting BLE batch scan
,03-31 13:00:39.161  5893  5979 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-31 13:00:39.166  5893  5958 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-31 13:00:39.166  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 13:00:39.166  5893  5958 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-31 13:00:39.166  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 13:00:39.171 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 13:00:39.171 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 13:00:39.171 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-31 13:00:39.171 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 13:00:39.171 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 13:00:39.171 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 13:00:39.171 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-31 13:00:39.171 11224 11287 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-31 13:00:39.176 11224 11287 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 13:00:39.176 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 13:00:39.176 11224 11287 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-31 13:00:39.176 11224 11224 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 13:00:39.176  5893  5987 D BtGatt.GattService: registerClient() - UUID=31a3c9a9-e38d-47f9-99a4-e4187fc48057
,03-31 13:00:39.216  5893  5958 D BtGatt.GattService: onClientRegistered() - UUID=31a3c9a9-e38d-47f9-99a4-e4187fc48057, clientIf=7
,03-31 13:00:39.216 11224 11233 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-31 13:00:39.231  5893  5903 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 40
,03-31 13:00:39.231  5893  5978 D BtGatt.AdvertiseManager: message : 0
03-31 13:00:39.231  5893  5978 D BtGatt.AdvertiseManager: number of adv instance running0
03-31 13:00:39.231  5893  5978 D BtGatt.AdvertiseManager: size of list is =0
,03-31 13:00:39.231  5893  5978 D BtGatt.AdvertiseManager: starting advertising
03-31 13:00:39.231  5893  5978 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-31 13:00:39.236  5893  5958 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-31 13:00:39.236  5893  5978 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 13:00:39.236  5893  5958 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
03-31 13:00:39.236  5893  5978 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,03-31 13:00:39.236  5893  5978 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
03-31 13:00:39.236 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-31 13:00:39.236 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-31 13:00:39.241 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 13:00:39.241 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 13:00:39.241 11224 11287 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-31 13:00:39.241 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-31 13:00:39.241 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-31 13:00:39.241 11224 11287 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-31 13:00:39.241 11224 11287 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-31 13:00:39.241 11224 11287 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-31 13:00:39.241 11224 11287 I io.jxcore.node.ConnectionHelper: start: OK
03-31 13:00:39.241 11224 11224 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-31 13:00:39.241 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 13:00:39.241 11224 11224 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-31 13:00:39.241 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-31 13:00:39.241 11224 11224 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-31 13:00:39.241 11224 11224 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-31 13:00:39.241 11224 11224 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-31 13:00:39.241 11224 11224 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 13:00:39.241 11224 11224 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-31 13:00:39.241 11224 11224 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 13:00:39.241 11224 11224 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-31 13:00:39.241 11224 11224 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 13:00:39.246 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 13:00:39.246 11224 11287 I jxcore-log: 
,03-31 13:00:39.246 11224 11697 D BluetoothSocket: bindListen(): myUserId = 0
03-31 13:00:39.246 11224 11697 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-31 13:00:39.246 11224 11287 I jxcore-log: ok 153 Can call startUpdateAdvertisingAndListeningwithout error
03-31 13:00:39.246 11224 11287 I jxcore-log: 
,03-31 13:00:39.246 11224 11697 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[92]}
03-31 13:00:39.246 11224 11697 D BluetoothSocket: bindListen(), new LocalSocket 
03-31 13:00:39.246 11224 11697 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-31 13:00:39.246 11224 11697 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@32edadd3
03-31 13:00:39.246 11224 11697 D BluetoothSocket: channel: 6
03-31 13:00:39.246 11224 11697 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-31 13:00:39.251 11224 11287 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: false
,03-31 13:00:39.251 11224 11287 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 13:00:39.251 11224 11287 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
03-31 13:00:39.251 11224 11287 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-31 13:00:39.251 11224 11287 I io.jxcore.node.ConnectionHelper: start: OK
,03-31 13:00:39.251 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 13:00:39.251 11224 11287 I jxcore-log: 
,03-31 13:00:39.256 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-31 13:00:39.256 11224 11287 I jxcore-log: 
,03-31 13:00:39.256 11224 11287 I jxcore-log: ok 154 Can call startListeningForAdvertisements without error
03-31 13:00:39.256 11224 11287 I jxcore-log: 
,03-31 13:00:40.171  3461  3617 V AlarmManager: waitForAlarm result :4,
,03-31 13:00:40.186  5893  5893 D BtGatt.ScanManager: awakened up at time 241280
,03-31 13:00:40.186  5893  5979 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-31 13:00:40.201  5893  5958 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
03-31 13:00:40.201  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 13:00:40.201  5893  5958 D BtGatt.GattService: current time is 241296979152
,03-31 13:00:40.201  5893  5958 D BtGatt.GattService: Batch record : [-122, -50, -114, 105, -33, 70, 1, -128, -55, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0, -55, 64, 90, -54, 3, 67, 1, -128, -72, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-31 13:00:40.201  5893  5958 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-31 13:00:40.201  5893  5958 D ScanRecord: parseFromBytes
,03-31 13:00:40.201  5893  5958 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81],
03-31 13:00:40.201  5893  5958 D ScanRecord: parseFromBytes
03-31 13:00:40.201  5893  5958 D BtGatt.GattService: result: ScanResult{mDevice=43:03:CA:5A:40:C9, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-72, mTimestampNanos=241197193319}
03-31 13:00:40.201  5893  5958 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-31 13:00:40.201  5893  5958 D BtGatt.GattService: result: ScanResult{mDevice=46:DF:69:8E:CE:86, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-55, mTimestampNanos=241247193319}
,03-31 13:00:40.201  5893  5958 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-31 13:00:40.201 11224 11234 D ScanRecord: parseFromBytes
03-31 13:00:40.201 11224 11234 D ScanRecord: parseFromBytes,
,03-31 13:00:40.206 11224 11224 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 1
03-31 13:00:40.206 11224 11224 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:CF:C5:D9:E5:61], added - the peer count is 2
03-31 13:00:40.206 11224 11224 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
03-31 13:00:40.206 11224 11224 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:CF:C5:D9:E5:61], Bluetooth address: F8:CF:C5:D9:E5:61, device name: , device address: 
03-31 13:00:40.216 11224 11287 I jxcore-log: ok 155 peers must be an array
03-31 13:00:40.216 11224 11287 I jxcore-log: 
,03-31 13:00:40.216 11224 11287 I jxcore-log: ok 156 peers must not be zero-length
03-31 13:00:40.216 11224 11287 I jxcore-log: 
03-31 13:00:40.216 11224 11287 I jxcore-log: ok 157 peer must have peerIdentifier
03-31 13:00:40.216 11224 11287 I jxcore-log: 
03-31 13:00:40.216 11224 11287 I jxcore-log: ok 158 peerIdentifier must be a string
03-31 13:00:40.216 11224 11287 I jxcore-log: 
03-31 13:00:40.226 11224 11287 I jxcore-log: ok 159 peer must have peerAvailable
03-31 13:00:40.226 11224 11287 I jxcore-log: 
,03-31 13:00:40.231 11224 11287 I jxcore-log: ok 160 peer must have pleaseConnect
03-31 13:00:40.231 11224 11287 I jxcore-log: 
,03-31 13:00:40.241 11224 11287 I jxcore-log: # teardown
03-31 13:00:40.241 11224 11287 I jxcore-log: 
,03-31 13:00:40.546 11224 11287 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 13:00:40.546 11224 11287 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
,03-31 13:00:40.546 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-31 13:00:40.546 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-31 13:00:40.551  5893  8993 D BtGatt.GattService: stopScan() - queue size =1
03-31 13:00:40.551  5893  5979 D BtGatt.ScanManager: filter size is 1
03-31 13:00:40.551  5893  5979 D BtGatt.ScanManager: delete FilterIndex - 10
03-31 13:00:40.551  5893  5958 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-31 13:00:40.551  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 13:00:40.551  5893  5979 D BtGatt.ScanManager: stopping BLe Batch,
,03-31 13:00:40.556  5893  5958 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,03-31 13:00:40.556  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
03-31 13:00:40.556  5893  5987 D BtGatt.GattService: unregisterClient() - clientIf=6
03-31 13:00:40.561  5893  5979 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-31 13:00:40.566  5893  5958 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
03-31 13:00:40.566  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 13:00:40.566  5893  5958 D BtGatt.GattService: current time is 241660315694
,03-31 13:00:40.566  5893  5958 D BtGatt.GattService: Batch record : [-55, 64, 90, -54, 3, 67, 1, -128, -77, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -122, -50, -114, 105, -33, 70, 1, -128, -62, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0]
03-31 13:00:40.566  5893  5958 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-31 13:00:40.566  5893  5958 D ScanRecord: parseFromBytes
03-31 13:00:40.566  5893  5958 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
,03-31 13:00:40.566  5893  5958 D ScanRecord: parseFromBytes,
03-31 13:00:40.571 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 13:00:40.571 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 13:00:40.571 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false,
03-31 13:00:40.571 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING],
,03-31 13:00:40.571 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING],
03-31 13:00:40.571 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true,
03-31 13:00:40.571 11224 11224 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 13:00:40.571 11224 11224 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only,
03-31 13:00:40.571 11224 11224 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-31 13:00:40.576 11224 11287 I jxcore-log: ok 161 Should be able to call stopListeningForAdvertisments in teardown,
03-31 13:00:40.576 11224 11287 I jxcore-log: 
,03-31 13:00:40.576 11224 11287 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 13:00:40.581 11224 11287 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-31 13:00:40.581 11224 11287 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-31 13:00:40.581 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-31 13:00:40.581 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,03-31 13:00:40.581 11224 11287 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@14be020e, channel: 6, state: LISTENING
03-31 13:00:40.581 11224 11287 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@14be020e, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@32edadd3, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1e5b542fmSocket: android.net.LocalSocket@be35a3c impl:android.net.LocalSocketImpl@1bb3e3c5 fd:FileDescriptor[92]
03-31 13:00:40.581 11224 11287 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@be35a3c impl:android.net.LocalSocketImpl@1bb3e3c5 fd:FileDescriptor[92]
,03-31 13:00:40.581 11224 11287 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-31 13:00:40.581 11224 11697 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-31 13:00:40.581 11224 11697 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-31 13:00:40.581 11224 11697 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-31 13:00:40.586 11224 11224 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-31 13:00:40.586 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-31 13:00:40.586 11224 11224 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-31 13:00:40.586 11224 11224 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-31 13:00:40.586 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-31 13:00:40.586 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-31 13:00:40.586 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-31 13:00:40.586 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-31 13:00:40.591 11224 11287 D BluetoothLeScanner: could not find callback wrapper
03-31 13:00:40.591 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 13:00:40.591 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-31 13:00:40.591  5893  5978 D BtGatt.AdvertiseManager: message : 1
,03-31 13:00:40.591  5893  5978 D BtGatt.AdvertiseManager: stop advertise for client 7
03-31 13:00:40.591  5893  5978 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-31 13:00:40.591  5893  5978 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,03-31 13:00:40.596  5893  5958 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
,03-31 13:00:40.596  5893  5958 D BtGatt.GattService: Client app is not null!
,03-31 13:00:40.596  5893  5987 D BtGatt.GattService: unregisterClient() - clientIf=7
,03-31 13:00:40.596 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 13:00:40.596 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-31 13:00:40.596 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-31 13:00:40.596 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-31 13:00:40.596 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-31 13:00:40.596 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-31 13:00:40.596 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 13:00:40.596 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-31 13:00:40.596 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-31 13:00:40.596 11224 11287 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-31 13:00:40.601 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 13:00:40.601 11224 11224 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 13:00:40.601 11224 11224 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 13:00:40.601 11224 11224 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 13:00:40.601 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 13:00:40.601 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-31 13:00:40.601 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-31 13:00:40.601 11224 11287 I jxcore-log: 
,03-31 13:00:40.606 11224 11224 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-31 13:00:40.606 11224 11287 I jxcore-log: ok 162 Should be able to call stopAdvertisingAndListening in teardown
03-31 13:00:40.606 11224 11287 I jxcore-log: 
,03-31 13:00:40.611 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-31 13:00:40.611 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 13:00:40.611 11224 11224 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 13:00:40.611 11224 11287 I jxcore-log: # setup
03-31 13:00:40.611 11224 11287 I jxcore-log: 
,03-31 13:00:40.616 11224 11224 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-31 13:00:40.616 11224 11224 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 13:00:40.621 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 13:00:40.621 11224 11287 I jxcore-log: 
,03-31 13:00:40.626 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 13:00:40.626 11224 11287 I jxcore-log: 
,03-31 13:00:40.931 11224 11287 I jxcore-log: # 40. Can connect to a remote peer
03-31 13:00:40.931 11224 11287 I jxcore-log: 
,03-31 13:00:40.946  3461  3568 W ProcessCpuTracker: Skipping unknown process pid 11719
,03-31 13:00:41.066 11224 11287 I io.jxcore.node.ConnectionHelper: start: Port number: 33300, start advertisements: true
,03-31 13:00:41.066 11224 11287 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-31 13:00:41.071 11224 11287 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,03-31 13:00:41.071 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-31 13:00:41.076 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-31 13:00:41.076 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-31 13:00:41.076 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-31 13:00:41.076 11224 11287 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 13:00:41.081  5893  5987 D BtGatt.GattService: registerClient() - UUID=3183323e-08ad-42ed-8ded-b5d01ee5ca1a
,03-31 13:00:41.126  5893  5958 D BtGatt.GattService: onClientRegistered() - UUID=3183323e-08ad-42ed-8ded-b5d01ee5ca1a, clientIf=6
03-31 13:00:41.126 11224 11234 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-31 13:00:41.126  5893  5903 D BtGatt.GattService: start scan with filters
,03-31 13:00:41.146  5893  5903 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 52
,03-31 13:00:41.151  5893  5979 D BtGatt.ScanManager: handling starting scan
,03-31 13:00:41.151  5893  5979 D BtGatt.ScanManager: isFilteringSupported
03-31 13:00:41.151  5893  5979 D BluetoothAdapter: setting StandAloneBleMode
,03-31 13:00:41.156  5893  5958 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-31 13:00:41.156  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 13:00:41.156  5893  5979 D BtGatt.ScanManager: allow scan with filters
03-31 13:00:41.156  5893  5979 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-31 13:00:41.156  5893  5979 D BtGatt.ScanManager: set filter index= 11 for clientIf= 6
,03-31 13:00:41.161  5893  5958 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-31 13:00:41.161  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 13:00:41.161  5893  5979 D BtGatt.ScanManager: Starting BLE batch scan
03-31 13:00:41.161  5893  5979 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-31 13:00:41.161  5893  5958 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-31 13:00:41.166  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 13:00:41.166 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
03-31 13:00:41.166 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 13:00:41.166 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,03-31 13:00:41.166 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 13:00:41.166 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 13:00:41.166 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-31 13:00:41.166 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-31 13:00:41.166 11224 11287 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-31 13:00:41.166 11224 11287 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false],
,03-31 13:00:41.166 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-31 13:00:41.166 11224 11287 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-31 13:00:41.171  5893  5905 D BtGatt.GattService: registerClient() - UUID=6e622e35-766b-4941-93b6-2651487386b3,
03-31 13:00:41.176  5893  5958 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1,
03-31 13:00:41.176  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 13:00:41.181 11224 11224 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false,
,03-31 13:00:41.216  5893  5958 D BtGatt.GattService: onClientRegistered() - UUID=6e622e35-766b-4941-93b6-2651487386b3, clientIf=7,
03-31 13:00:41.216 11224 11233 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-31 13:00:41.226  5893  8993 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 41,
,03-31 13:00:41.226  5893  5978 D BtGatt.AdvertiseManager: message : 0
,03-31 13:00:41.226  5893  5978 D BtGatt.AdvertiseManager: number of adv instance running0
03-31 13:00:41.226  5893  5978 D BtGatt.AdvertiseManager: size of list is =0
,03-31 13:00:41.226  5893  5978 D BtGatt.AdvertiseManager: starting advertising
03-31 13:00:41.226  5893  5978 D BtGatt.AdvertiseManager: isStandardAdvfalse
03-31 13:00:41.231  5893  5958 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
03-31 13:00:41.236  5893  5978 D BtGatt.AdvertiseManager: starting multi advertising
03-31 13:00:41.236  5893  5958 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0,
,03-31 13:00:41.236  5893  5978 D BtGatt.AdvertiseManager: logClientsSet() - status: 0,
,03-31 13:00:41.236  5893  5978 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,03-31 13:00:41.241 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-31 13:00:41.241 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-31 13:00:41.241 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 13:00:41.241 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 13:00:41.241 11224 11287 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-31 13:00:41.241 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-31 13:00:41.246 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-31 13:00:41.246 11224 11287 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-31 13:00:41.246 11224 11287 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-31 13:00:41.246 11224 11287 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK,
03-31 13:00:41.246 11224 11224 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,03-31 13:00:41.246 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 13:00:41.246 11224 11224 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-31 13:00:41.246 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-31 13:00:41.246 11224 11224 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
,03-31 13:00:41.246 11224 11224 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-31 13:00:41.246 11224 11224 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 13:00:41.246 11224 11224 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 13:00:41.246 11224 11224 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-31 13:00:41.246 11224 11224 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 13:00:41.246 11224 11224 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,03-31 13:00:41.246 11224 11224 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 13:00:41.246 11224 11287 I io.jxcore.node.ConnectionHelper: start: OK
03-31 13:00:41.246 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 13:00:41.246 11224 11287 I jxcore-log: 
03-31 13:00:41.246 11224 11287 I jxcore-log: ok 163 Can call startUpdateAdvertisingAndListening without error
03-31 13:00:41.246 11224 11287 I jxcore-log: 
03-31 13:00:41.256 11224 11726 D BluetoothSocket: bindListen(): myUserId = 0
03-31 13:00:41.256 11224 11726 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-31 13:00:41.256 11224 11726 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[93]}
,03-31 13:00:41.256 11224 11726 D BluetoothSocket: bindListen(), new LocalSocket 
03-31 13:00:41.256 11224 11726 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-31 13:00:41.256 11224 11726 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@27f3f741
03-31 13:00:41.256 11224 11726 D BluetoothSocket: channel: 6
03-31 13:00:41.256 11224 11726 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-31 13:00:41.256 11224 11287 I io.jxcore.node.ConnectionHelper: start: Port number: 33300, start advertisements: false
03-31 13:00:41.256 11224 11287 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 13:00:41.256 11224 11287 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
,03-31 13:00:41.256 11224 11287 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-31 13:00:41.256 11224 11287 I io.jxcore.node.ConnectionHelper: start: OK
03-31 13:00:41.261 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 13:00:41.261 11224 11287 I jxcore-log: 
03-31 13:00:41.261 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-31 13:00:41.261 11224 11287 I jxcore-log: 
03-31 13:00:41.261 11224 11287 I jxcore-log: ok 164 Can call startListeningForAdvertisements without error
03-31 13:00:41.261 11224 11287 I jxcore-log: 
,03-31 13:00:42.176  3461  3617 V AlarmManager: waitForAlarm result :4
,03-31 13:00:42.191  5893  5893 D BtGatt.ScanManager: awakened up at time 243285
,03-31 13:00:42.196  5893  5979 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6,
03-31 13:00:42.201  5893  5958 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
03-31 13:00:42.201  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 13:00:42.201  5893  5958 D BtGatt.GattService: current time is 243296562069
03-31 13:00:42.201  5893  5958 D BtGatt.GattService: Batch record : [117, 45, 127, 81, -94, 101, 1, -128, -72, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, 35, 125, -92, -18, 120, 86, 1, -128, -55, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0]
03-31 13:00:42.201  5893  5958 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-31 13:00:42.201  5893  5958 D ScanRecord: parseFromBytes
03-31 13:00:42.201  5893  5958 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-31 13:00:42.201  5893  5958 D ScanRecord: parseFromBytes
03-31 13:00:42.201  5893  5958 D BtGatt.GattService: result: ScanResult{mDevice=56:78:EE:A4:7D:23, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-55, mTimestampNanos=243296746277}
03-31 13:00:42.201  5893  5958 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-31 13:00:42.201  5893  5958 D BtGatt.GattService: result: ScanResult{mDevice=65:A2:51:7F:2D:75, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-72, mTimestampNanos=243296746277}
03-31 13:00:42.201  5893  5958 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-31 13:00:42.201 11224 11280 D ScanRecord: parseFromBytes
03-31 13:00:42.201 11224 11280 D ScanRecord: parseFromBytes
03-31 13:00:42.201 11224 11224 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:CF:C5:D9:E5:61], added - the peer count is 1
03-31 13:00:42.201 11224 11224 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 2
03-31 13:00:42.206 11224 11224 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:CF:C5:D9:E5:61], Bluetooth address: F8:CF:C5:D9:E5:61, device name: , device address: 
03-31 13:00:42.206 11224 11224 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
,03-31 13:00:42.216 11224 11287 I jxcore-log: INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"F8:CF:C5:D9:E5:61","peerAvailable":true,"pleaseConnect":false}],
03-31 13:00:42.216 11224 11287 I jxcore-log: 
,03-31 13:00:42.226 11224 11287 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID F8:CF:C5:D9:E5:61
,03-31 13:00:42.231 11224 11287 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> F8:CF:C5:D9:E5:61]
,03-31 13:00:42.236 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address F8:CF:C5:D9:E5:61
,03-31 13:00:42.236 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,03-31 13:00:42.236 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,03-31 13:00:42.241 11224 11287 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null F8:CF:C5:D9:E5:61
,03-31 13:00:42.241 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address F8:CF:C5:D9:E5:61
03-31 13:00:42.241 11224 11287 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: F8:CF:C5:D9:E5:61)
,03-31 13:00:42.241 11224 11287 I jxcore-log: INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"pleaseConnect":false}]
03-31 13:00:42.241 11224 11287 I jxcore-log: 
,03-31 13:00:42.246 11224 11733 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address F8:CF:C5:D9:E5:61 (thread ID: 1566)
,03-31 13:00:42.251 11224 11733 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
,03-31 13:00:42.251 11224 11733 D BluetoothSocket: connect(): myUserId = 0
,03-31 13:00:42.256 11224 11733 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-31 13:00:42.256  5893  8993 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
03-31 13:00:42.256  5893  6021 D IOP_DB_BT: db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 13:00:42.256  5893  6021 D IOP_DB_BT: db_query_add_key: key KEY_LMP_MFCT, value 15
03-31 13:00:42.256  5893  6021 D IOP_DB_BT: db_query_add_key: key KEY_LMP_VER, value 7:8975
03-31 13:00:42.256  5893  6021 D IOP_DB_BT: db_query_add_key: key KEY_DIR_ALL, value 1
03-31 13:00:42.256  5893  6021 D IOP_DB_BT: db_query_execute: result 1
,03-31 13:00:42.261  5893  6021 W bt-btif : bta_dm_acl_change(), event : 2
,03-31 13:00:42.266 11224 11733 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[118]}
,03-31 13:00:43.071  5893  6021 W bt-btif : bta_dm_acl_change(), event : 2
03-31 13:00:43.071  5893  6021 W bt-btif : bta_dm_acl_change(), event : 4
03-31 13:00:43.071  5893  6021 W bt-btif : scb return value : 1
,03-31 13:00:43.146  5893  6021 D IOP_DB_BT: db_query: id SkipSdpInfo :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
,03-31 13:00:43.151  5893  6021 D IOP_DB_BT: db_query: result 1
,03-31 13:00:43.171  5893  6021 D IOP_DB_BT: db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 13:00:43.171  5893  6021 D IOP_DB_BT: db_query_add_key: key KEY_LMP_MFCT, value 15
03-31 13:00:43.171  5893  6021 D IOP_DB_BT: db_query_add_key: key KEY_LMP_VER, value 7:8975
03-31 13:00:43.171  5893  6021 D IOP_DB_BT: db_query_add_key: key KEY_DIR_ALL, value *
03-31 13:00:43.171  5893  6021 D IOP_DB_BT: db_query_execute: result 1
03-31 13:00:43.171  5893  6021 W bt-btif : bta_dm_acl_change(), event : 0
03-31 13:00:43.171  5893  6021 W bt-btif : info:x10
03-31 13:00:43.171  5893  5958 D         : remote version info [f8:cf:c5:d9:e5:61]: 7, f, 230f
03-31 13:00:43.171  5893  5958 E BluetoothRemoteDevices: aclStateChangeCallback: Device is NULL
03-31 13:00:43.171  5893  6021 W bt-btif : bta_dm_acl_change(), event : 2
03-31 13:00:43.181  5893  5958 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,03-31 13:00:43.221  3461  3617 V AlarmManager: waitForAlarm result :4
,03-31 13:00:43.226  5893  5893 D BtGatt.ScanManager: awakened up at time 244320
,03-31 13:00:43.226  5893  5979 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-31 13:00:43.226  5893  5958 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
03-31 13:00:43.226  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 13:00:43.226  5893  5958 D BtGatt.GattService: current time is 244324430736
03-31 13:00:43.226  5893  5958 D BtGatt.GattService: Batch record : [117, 45, 127, 81, -94, 101, 1, -128, -74, 4, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, 35, 125, -92, -18, 120, 86, 1, -128, -54, 4, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0]
03-31 13:00:43.226  5893  5958 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-31 13:00:43.226  5893  5958 D ScanRecord: parseFromBytes
,03-31 13:00:43.231  5893  5958 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-31 13:00:43.231  5893  5958 D ScanRecord: parseFromBytes
03-31 13:00:43.231  5893  5958 D BtGatt.GattService: result: ScanResult{mDevice=65:A2:51:7F:2D:75, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-74, mTimestampNanos=244124602861}
03-31 13:00:43.231  5893  5958 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-31 13:00:43.231  5893  5958 D BtGatt.GattService: result: ScanResult{mDevice=56:78:EE:A4:7D:23, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-54, mTimestampNanos=244124602861}
03-31 13:00:43.231  5893  5958 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-31 13:00:43.231 11224 11234 D ScanRecord: parseFromBytes
03-31 13:00:43.231 11224 11234 D ScanRecord: parseFromBytes
03-31 13:00:43.231 11224 11224 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
03-31 13:00:43.231 11224 11224 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:CF:C5:D9:E5:61] updated - the peer count is 2
,03-31 13:00:43.296  5893  6021 W bt-sdp  : process_service_search_attr_rsp
,03-31 13:00:44.231  3461  3617 V AlarmManager: waitForAlarm result :4
,03-31 13:00:44.241  5893  5893 D BtGatt.ScanManager: awakened up at time 245337
,03-31 13:00:44.251  5893  5979 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-31 13:00:44.256  5893  5958 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
03-31 13:00:44.256  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 13:00:44.256  5893  5958 D BtGatt.GattService: current time is 245352705569
03-31 13:00:44.256  5893  5958 D BtGatt.GattService: Batch record : [117, 45, 127, 81, -94, 101, 1, -128, -73, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, 35, 125, -92, -18, 120, 86, 1, -128, -54, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0]
03-31 13:00:44.256  5893  5958 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81],
03-31 13:00:44.256  5893  5958 D ScanRecord: parseFromBytes,
03-31 13:00:44.256  5893  5958 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97],
03-31 13:00:44.256  5893  5958 D ScanRecord: parseFromBytes,
03-31 13:00:44.256  5893  5958 D BtGatt.GattService: result: ScanResult{mDevice=56:78:EE:A4:7D:23, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-54, mTimestampNanos=245352943902}
,03-31 13:00:44.256  5893  5958 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-31 13:00:44.256  5893  5958 D BtGatt.GattService: result: ScanResult{mDevice=65:A2:51:7F:2D:75, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-73, mTimestampNanos=245352943902}
03-31 13:00:44.256  5893  5958 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-31 13:00:44.256 11224 11233 D ScanRecord: parseFromBytes
03-31 13:00:44.261 11224 11233 D ScanRecord: parseFromBytes
03-31 13:00:44.261 11224 11224 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:CF:C5:D9:E5:61] updated - the peer count is 2
,03-31 13:00:44.261 11224 11224 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
,03-31 13:00:44.346  5893  6021 D IOP_DB_BT: db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-31 13:00:44.346  5893  6021 D IOP_DB_BT: db_query_add_key: key KEY_LMP_MFCT, value 15
03-31 13:00:44.346  5893  6021 D IOP_DB_BT: db_query_add_key: key KEY_LMP_VER, value 7:24841
03-31 13:00:44.346  5893  6021 D IOP_DB_BT: db_query_add_key: key KEY_DIR_ALL, value *
03-31 13:00:44.351  5893  6021 D IOP_DB_BT: db_query_execute: result 1
,03-31 13:00:44.351  5893  6021 D IOP_DB_BT: db_query_create: id EnforceSlaveRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-31 13:00:44.351  5893  6021 D IOP_DB_BT: db_query_add_key: key KEY_LMP_MFCT, value 15
03-31 13:00:44.351  5893  6021 D IOP_DB_BT: db_query_add_key: key KEY_LMP_VER, value 7:24841
03-31 13:00:44.351  5893  6021 D IOP_DB_BT: db_query_add_key: key KEY_DIR_ALL, value *
03-31 13:00:44.351  5893  6021 D IOP_DB_BT: db_query_execute: result 1
,03-31 13:00:44.491  5893  5958 W bt-btif : btif_dm_ssp_cfm_req_evt
,03-31 13:00:44.501  5893  5958 D BluetoothUtils: getBtEnabledContainers(): btContainers = [],
,03-31 13:00:44.511  5893  5958 D BluetoothUtils: getBtEnabledContainers(): btContainers = [],
03-31 13:00:44.516  5893  5958 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:CF:C5:D9:E5:61 newState: 1
,03-31 13:00:44.516  3461  4440 D SecContentProvider: query(), uri = 4 selection = bluetoothLogForRemote
,03-31 13:00:44.521  5893  5958 E bt-btif : check_cod: remote_cod = 0x5a020c
,03-31 13:00:44.521  5893  5958 W bt-btif : btif_dm_ssp_reply: accept=1
,03-31 13:00:44.526  5893  5976 I BluetoothBondStateMachine: Bond State Change Intent:F8:CF:C5:D9:E5:61 OldState: 10 NewState: 11
,03-31 13:00:44.531  3461  3461 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
03-31 13:00:44.531  3461  3461 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.device.action.BOND_STATE_CHANGED
,03-31 13:00:44.541  3461  3461 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED
03-31 13:00:44.541  3461  3461 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 10
03-31 13:00:44.541  3461  3461 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 11
03-31 13:00:44.541  3461  3461 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
,03-31 13:00:44.541  3461  3568 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3056adbc u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{1b336218 10216:com.android.settings/1000}
,03-31 13:00:44.541  3461  3833 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
,03-31 13:00:44.541  5893  5976 D BtConfig.SecureMode: isSecureModeOn:false
03-31 13:00:44.541  5893  5976 I BluetoothBondStateMachine: Entering PendingCommandState State
,03-31 13:00:44.546  3728  3728 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,03-31 13:00:44.546 10216 10216 D BluetoothNotiBroadcastReceiver: onReceive,
,03-31 13:00:44.551  3728  4803 D BluetoothTile:  handleUpdatestate:false name:null
,03-31 13:00:44.551  3461  3491 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3056adbc u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{1082dfc0 10370:com.sec.android.automotive.drivelink/u0a102}
,03-31 13:00:44.556 10370 11752 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,03-31 13:00:44.556 10370 10370 D [CarMode]: [AutoLaunchReceiver]-action: android.bluetooth.device.action.BOND_STATE_CHANGED
,03-31 13:00:44.561 10370 10370 D [CarMode]: [AutoLaunchReceiver]-ACTION_BOND_STATE_CHANGED Nexus 6 state is 11
,03-31 13:00:44.561 10370 10370 D [CarModeFW]: ConnectivityManager-handleMessage PAIRING_DEVICES
,03-31 13:00:44.566  3461  3968 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3056adbc u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{1082dfc0 10370:com.sec.android.automotive.drivelink/u0a102}
,03-31 13:00:44.566  3461  4438 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
,03-31 13:00:44.571 10370 11753 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,03-31 13:00:44.571 10370 10370 D [CarModeFW]: ConnectivityManager-handleMessage PAIRING_DEVICES
,03-31 13:00:44.576  3461  3967 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3056adbc u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{34687286 10556:com.samsung.android.app.watchmanagerstub/u0a121}
,03-31 13:00:44.586 10556 10556 E BluetoothHeadset: BTStateChangeCB is registed
,03-31 13:00:44.586 10556 10556 D GMHFPReceiver: android.bluetooth.device.action.BOND_STATE_CHANGED
,03-31 13:00:44.591 10556 10556 D GMHFPReceiver: jangil::setProperties()
,03-31 13:00:44.591 10556 10556 D GMHFPReceiver: jangil::printBTStatus()
,03-31 13:00:44.596  3461  4033 D SettingsProvider: name = Wearable0001
03-31 13:00:44.596  3461  4033 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-31 13:00:44.596  3461  4033 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-31 13:00:44.596  3461  4033 D SettingsProvider: selectionArgs: false
03-31 13:00:44.596  3461  4033 D SettingsProvider: selectionArgs: 10121
03-31 13:00:44.596  3461  4033 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,03-31 13:00:44.596  3461  4033 D SettingsProvider: ret = -1
,03-31 13:00:44.596  3461  4033 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10121
,03-31 13:00:44.601 10556 10556 D GMHFPReceiver: ::::::::Wearable0001::false
,03-31 13:00:44.601  3461  3833 D SettingsProvider: name = Wearable0002
03-31 13:00:44.601  3461  3833 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-31 13:00:44.601  3461  3833 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-31 13:00:44.601  3461  3833 D SettingsProvider: selectionArgs: false
03-31 13:00:44.601  3461  3833 D SettingsProvider: selectionArgs: 10121
03-31 13:00:44.601  3461  3833 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,03-31 13:00:44.601  3461  3833 D SettingsProvider: ret = -1
,03-31 13:00:44.606  3461  3833 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10121
,03-31 13:00:44.606 10556 10556 D GMHFPReceiver: ::::::::Wearable0002::false
,03-31 13:00:44.611  3728  3728 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-31 13:00:44.616  3461  4033 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3056adbc u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{3cd9dfc6 4376:com.google.android.gms.persistent/u0a14}
,03-31 13:00:44.631  3728  3728 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-31 13:00:44.681  5893  6021 D IOP_DB_BT: db_query: id SkipSdpInfo :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-31 13:00:44.686  5893  6021 D IOP_DB_BT: db_query: result 1
,03-31 13:00:44.691 10556 10556 D GMHFPReceiver: onServiceConnected() : 1
,03-31 13:00:44.691 10556 10556 D GMHFPReceiver: mBluetoothHeadset = true
,03-31 13:00:44.696  5893  6021 D IOP_DB_BT: db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-31 13:00:44.696  5893  6021 D IOP_DB_BT: db_query_add_key: key KEY_LMP_MFCT, value 15
,03-31 13:00:44.696  5893  6021 D IOP_DB_BT: db_query_add_key: key KEY_LMP_VER, value 7:24841
03-31 13:00:44.696  5893  6021 D IOP_DB_BT: db_query_add_key: key KEY_DIR_ALL, value *
03-31 13:00:44.696  5893  6021 D IOP_DB_BT: db_query_execute: result 1
03-31 13:00:44.696  5893  6021 W bt-btif : bta_dm_acl_change(), event : 0
03-31 13:00:44.696  5893  6021 W bt-btif : info:x10
03-31 13:00:44.696  5893  5958 D         : remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
03-31 13:00:44.701  5893  6021 W bt-btif : bta_dm_acl_change(), event : 2
,03-31 13:00:44.701  5893  5958 E BluetoothRemoteDevices: aclStateChangeCallback: Device is NULL
,03-31 13:00:44.711  5893  5958 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,03-31 13:00:44.746  3461  3581 I PowerManagerService: [PWL] Off : 180s ago,
,03-31 13:00:44.746  3461  3581 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
03-31 13:00:44.746  3461  3581 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
,03-31 13:00:44.746  3461  3581 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'bluedroid_timer' (uid=1002, pid=5893, ws=null) (elapsedTime=2488)
,03-31 13:00:44.911  5893  5958 W bt-btif : btif_dm_auth_cmpl_evt
,03-31 13:00:44.921  5893  5958 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,03-31 13:00:44.961  5893  5958 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:CF:C5:D9:E5:61 newState: 0
,03-31 13:00:44.961  5893  5976 D BluetoothAdapterProperties: Failed to remove device: F8:CF:C5:D9:E5:61
,03-31 13:00:44.966  3461  4438 D SecContentProvider: query(), uri = 4 selection = bluetoothLogForRemote
,03-31 13:00:44.971  5893  5976 I BluetoothBondStateMachine: Bond State Change Intent:F8:CF:C5:D9:E5:61 OldState: 11 NewState: 10
,03-31 13:00:44.971  3461  3461 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
03-31 13:00:44.971  3461  3461 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.device.action.BOND_STATE_CHANGED
03-31 13:00:44.971  3461  3461 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED
03-31 13:00:44.971  3461  3461 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 11
03-31 13:00:44.971  3461  3461 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 10
03-31 13:00:44.971  3461  3461 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
,03-31 13:00:44.976  3728  3728 D BluetoothTile:  onBluetoothPairedDevicesChanged:,
,03-31 13:00:44.981  3728  4803 D BluetoothTile:  handleUpdatestate:false name:null
,03-31 13:00:44.986 10216 10216 D BluetoothNotiBroadcastReceiver: onReceive,
,03-31 13:00:44.986  3461  3568 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{169ebba7 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{1b336218 10216:com.android.settings/1000}
03-31 13:00:44.986  5893  5976 D BtConfig.SecureMode: isSecureModeOn:false
03-31 13:00:44.986  3461  3491 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
,03-31 13:00:44.996 10370 11766 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,03-31 13:00:45.001  5893  5976 D HidService: getHidService(): returning com.android.bluetooth.hid.HidService@1336e41c
,03-31 13:00:45.001  3461  4439 D SettingsProvider: name = bluetooth_input_device_priority_F8:CF:C5:D9:E5:61
03-31 13:00:45.001  3461  4439 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-31 13:00:45.001  3461  4439 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-31 13:00:45.001  3461  4439 D SettingsProvider: selectionArgs: false
03-31 13:00:45.001  3461  4439 D SettingsProvider: selectionArgs: 1002
03-31 13:00:45.001  3461  4439 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
03-31 13:00:45.001  3461  4439 D SettingsProvider: ret = -1
03-31 13:00:45.001  5893  5976 D HidService: Saved priority F8:CF:C5:D9:E5:61 = -1
,03-31 13:00:45.001  3461  3833 D SettingsProvider: name = bluetooth_a2dp_sink_priority_F8:CF:C5:D9:E5:61
03-31 13:00:45.001  3461  3967 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{169ebba7 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{1082dfc0 10370:com.sec.android.automotive.drivelink/u0a102}
,03-31 13:00:45.001  3461  3833 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-31 13:00:45.001  3461  3833 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,03-31 13:00:45.001  3461  3833 D SettingsProvider: selectionArgs: false
,03-31 13:00:45.001  3461  3833 D SettingsProvider: selectionArgs: 1002
03-31 13:00:45.006  3461  3833 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
03-31 13:00:45.006  3461  3833 D SettingsProvider: ret = -1
,03-31 13:00:45.006 10370 10370 D [CarMode]: [AutoLaunchReceiver]-action: android.bluetooth.device.action.BOND_STATE_CHANGED
03-31 13:00:45.006  3461  4244 D SettingsProvider: name = bluetooth_headset_priority_F8:CF:C5:D9:E5:61
03-31 13:00:45.006  3461  4244 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-31 13:00:45.006  3461  4244 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-31 13:00:45.006  3461  4244 D SettingsProvider: selectionArgs: false
03-31 13:00:45.006  3461  4244 D SettingsProvider: selectionArgs: 1002
,03-31 13:00:45.006  3461  4244 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
03-31 13:00:45.006  3461  4244 D SettingsProvider: ret = -1
03-31 13:00:45.006  5893  5976 I BluetoothBondStateMachine: StableState(): Entering Off State
,03-31 13:00:45.011 10370 10370 D [CarMode]: [AutoLaunchReceiver]-ACTION_BOND_STATE_CHANGED Nexus 6 state is 10
,03-31 13:00:45.016  3461  3491 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{169ebba7 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{1082dfc0 10370:com.sec.android.automotive.drivelink/u0a102}
,03-31 13:00:45.016  3461  4438 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
,03-31 13:00:45.026 10370 11767 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,03-31 13:00:45.031  3461  4439 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{169ebba7 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{34687286 10556:com.samsung.android.app.watchmanagerstub/u0a121}
,03-31 13:00:45.036 10556 10556 E BluetoothHeadset: BTStateChangeCB is registed
,03-31 13:00:45.036 10556 10556 D GMHFPReceiver: android.bluetooth.device.action.BOND_STATE_CHANGED
,03-31 13:00:45.036 10556 10556 D GMHFPReceiver: jangil::setProperties()
,03-31 13:00:45.041 10556 10556 D GMHFPReceiver: jangil::printBTStatus()
,03-31 13:00:45.041  3461  4016 D SettingsProvider: name = Wearable0001
03-31 13:00:45.041  3461  4016 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-31 13:00:45.041  3461  4016 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-31 13:00:45.041  3461  4016 D SettingsProvider: selectionArgs: false
03-31 13:00:45.041  3461  4016 D SettingsProvider: selectionArgs: 10121
03-31 13:00:45.041  3461  4016 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,03-31 13:00:45.041  3461  4016 D SettingsProvider: ret = -1
03-31 13:00:45.041 10556 10556 D GMHFPReceiver: ::::::::Wearable0001::false
,03-31 13:00:45.041  3461  4440 D SettingsProvider: name = Wearable0002
03-31 13:00:45.041  3461  4440 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-31 13:00:45.041  3461  4440 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,03-31 13:00:45.041  3461  4440 D SettingsProvider: selectionArgs: false
03-31 13:00:45.041  3461  4440 D SettingsProvider: selectionArgs: 10121
03-31 13:00:45.041  3461  4440 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
03-31 13:00:45.041  3461  4440 D SettingsProvider: ret = -1
,03-31 13:00:45.046 10556 10556 D GMHFPReceiver: ::::::::Wearable0002::false
,03-31 13:00:45.051  3461  4033 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{169ebba7 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{3cd9dfc6 4376:com.google.android.gms.persistent/u0a14}
,03-31 13:00:45.106  3461  4438 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-31 13:00:45.106  3461  4438 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 13:00:45.106  3461  4438 D BatteryService: online:4, current avg:42, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:47
03-31 13:00:45.106  3461  4438 D BatteryService: stay LED for fully charged
03-31 13:00:45.106  3461  3461 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 13:00:45.111  3461  3461 I MotionRecognitionService: Plugged
03-31 13:00:45.111  3461  3461 D MotionRecognitionService:   cableConnection= 1
03-31 13:00:45.111  3461  3461 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 13:00:45.111  3461  3461 D MotionRecognitionService: skip setTransmitPower. 
,03-31 13:00:45.111  3728  3728 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 13:00:45.111  3728  3728 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 13:00:45.111  3728  3728 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 13:00:45.116  5893  5893 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-31 13:00:45.116  5893  5980 D HeadsetStateMachine: Disconnected process message: 10
,03-31 13:00:45.131  3728  3728 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 13:00:45.131  3728  3728 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 13:00:45.131  3728  3728 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 13:00:45.131  3728  3728 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 13:00:45.136 10556 10556 D GMHFPReceiver: onServiceConnected() : 1
,03-31 13:00:45.136 10556 10556 D GMHFPReceiver: mBluetoothHeadset = true
,03-31 13:00:45.221  3461  6089 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:12), CUR = 42, LCD = 0
,03-31 13:00:45.271  3461  3617 V AlarmManager: waitForAlarm result :4
,03-31 13:00:45.281  5893  5893 D BtGatt.ScanManager: awakened up at time 246378
03-31 13:00:45.286  5893  5979 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-31 13:00:45.291  5893  6021 E bt-btm  : tBTM_SEC_DEV:0xb35230d8 rs_disc_pending=1
03-31 13:00:45.291  5893  6021 W bt-btif : bta_dm_acl_change(), event : 3
03-31 13:00:45.291  5893  6021 W bt-btif : bta_dm_check_av:0
03-31 13:00:45.291  5893  5958 W bt-btif : btif_dm_cback : unhandled event (14)
03-31 13:00:45.296  5893  5958 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
03-31 13:00:45.296  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 13:00:45.296  5893  5958 D BtGatt.GattService: current time is 246392804944
03-31 13:00:45.296  5893  5958 D BtGatt.GattService: Batch record : [117, 45, 127, 81, -94, 101, 1, -128, -72, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, 35, 125, -92, -18, 120, 86, 1, -128, -55, 4, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0]
03-31 13:00:45.296  5893  5958 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-31 13:00:45.296  5893  5958 D ScanRecord: parseFromBytes
03-31 13:00:45.296  5893  5958 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-31 13:00:45.296  5893  5958 D ScanRecord: parseFromBytes
03-31 13:00:45.296  5893  5958 D BtGatt.GattService: result: ScanResult{mDevice=65:A2:51:7F:2D:75, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-72, mTimestampNanos=246393000694}
03-31 13:00:45.296  5893  5958 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-31 13:00:45.296  5893  5958 D BtGatt.GattService: result: ScanResult{mDevice=56:78:EE:A4:7D:23, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-55, mTimestampNanos=246193000694}
03-31 13:00:45.296  5893  5958 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-31 13:00:45.296 11224 11280 D ScanRecord: parseFromBytes
03-31 13:00:45.301 11224 11280 D ScanRecord: parseFromBytes
03-31 13:00:45.301 11224 11224 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
03-31 13:00:45.301 11224 11224 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:CF:C5:D9:E5:61] updated - the peer count is 2
,03-31 13:00:45.806  5893  5958 W bt-btif : btif_dm_ssp_cfm_req_evt
,03-31 13:00:45.821  5893  5958 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,03-31 13:00:45.836  5893  5958 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
03-31 13:00:45.836  5893  5958 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
03-31 13:00:45.841  3461  3488 D SecContentProvider: query(), uri = 4 selection = bluetoothLogForRemote
03-31 13:00:45.841  5893  5958 E bt-btif : check_cod: remote_cod = 0x5a020c
03-31 13:00:45.841  5893  5958 W bt-btif : btif_dm_ssp_reply: accept=1
,03-31 13:00:45.851  3461  3461 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive,
03-31 13:00:45.851  3461  3461 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.device.action.BOND_STATE_CHANGED
03-31 13:00:45.851  3461  3461 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED
03-31 13:00:45.851  3461  3461 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 10
03-31 13:00:45.851  3461  3461 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 11
,03-31 13:00:45.851  3461  3461 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit,
03-31 13:00:45.856  5893  5976 I BluetoothBondStateMachine: Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
,03-31 13:00:45.861  3728  3728 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,03-31 13:00:45.866  3728  4803 D BluetoothTile:  handleUpdatestate:false name:null
,03-31 13:00:45.871  3461  3568 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1ccd62f9 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{1b336218 10216:com.android.settings/1000}
,03-31 13:00:45.871  5893  5976 D BtConfig.SecureMode: isSecureModeOn:false
03-31 13:00:45.871  3461  4033 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
03-31 13:00:45.871  5893  5976 I BluetoothBondStateMachine: Entering PendingCommandState State
03-31 13:00:45.871 10216 10216 D BluetoothNotiBroadcastReceiver: onReceive
,03-31 13:00:45.876 10370 11784 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,03-31 13:00:45.876 10370 10370 D [CarModeFW]: ConnectivityManager-handleMessage PAIRING_DEVICES
,03-31 13:00:45.881  3461  4438 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1ccd62f9 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{1082dfc0 10370:com.sec.android.automotive.drivelink/u0a102}
,03-31 13:00:45.881 10370 10370 D [CarMode]: [AutoLaunchReceiver]-action: android.bluetooth.device.action.BOND_STATE_CHANGED
,03-31 13:00:45.886 10370 10370 D [CarMode]: [AutoLaunchReceiver]-ACTION_BOND_STATE_CHANGED G4-1 state is 11
,03-31 13:00:45.891  3461  4439 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1ccd62f9 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{1082dfc0 10370:com.sec.android.automotive.drivelink/u0a102}
,03-31 13:00:45.891  3461  3833 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
,03-31 13:00:45.901 10370 11785 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,03-31 13:00:45.901 10370 10370 D [CarModeFW]: ConnectivityManager-handleMessage PAIRING_DEVICES
,03-31 13:00:45.901  3461  4439 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1ccd62f9 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{34687286 10556:com.samsung.android.app.watchmanagerstub/u0a121}
,03-31 13:00:45.906 10556 10556 E BluetoothHeadset: BTStateChangeCB is registed
,03-31 13:00:45.906 10556 10556 D GMHFPReceiver: android.bluetooth.device.action.BOND_STATE_CHANGED
03-31 13:00:45.906 10556 10556 D GMHFPReceiver: jangil::setProperties()
,03-31 13:00:45.911 10556 10556 D GMHFPReceiver: jangil::printBTStatus()
,03-31 13:00:45.911  3461  3653 D SettingsProvider: name = Wearable0001
03-31 13:00:45.911  3461  3653 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-31 13:00:45.911  3461  3653 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-31 13:00:45.911  3461  3653 D SettingsProvider: selectionArgs: false
03-31 13:00:45.911  3461  3653 D SettingsProvider: selectionArgs: 10121
03-31 13:00:45.911  3461  3653 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,03-31 13:00:45.911  3461  3653 D SettingsProvider: ret = -1
03-31 13:00:45.911 10556 10556 D GMHFPReceiver: ::::::::Wearable0001::false
,03-31 13:00:45.911  3461  4244 D SettingsProvider: name = Wearable0002
03-31 13:00:45.911  3461  4244 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-31 13:00:45.911  3461  4244 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-31 13:00:45.911  3461  4244 D SettingsProvider: selectionArgs: false
03-31 13:00:45.911  3461  4244 D SettingsProvider: selectionArgs: 10121
03-31 13:00:45.911  3461  4244 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,03-31 13:00:45.911  3461  4244 D SettingsProvider: ret = -1
03-31 13:00:45.911 10556 10556 D GMHFPReceiver: ::::::::Wearable0002::false
,03-31 13:00:45.916  3461  4032 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1ccd62f9 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{3cd9dfc6 4376:com.google.android.gms.persistent/u0a14},
,03-31 13:00:46.006 10556 10556 D GMHFPReceiver: onServiceConnected() : 1
,03-31 13:00:46.006 10556 10556 D GMHFPReceiver: mBluetoothHeadset = true
,03-31 13:00:46.171  5893  5956 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,03-31 13:00:46.221  5893  5958 W bt-btif : btif_dm_auth_cmpl_evt
03-31 13:00:46.221  5893  5958 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,03-31 13:00:46.221  5893  5976 D BluetoothAdapterProperties: Failed to remove device: F8:95:C7:87:3C:51
,03-31 13:00:46.226  3461  4033 D SecContentProvider: query(), uri = 4 selection = bluetoothLogForRemote
,03-31 13:00:46.231  5893  5976 I BluetoothBondStateMachine: Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,03-31 13:00:46.236  5893  5976 D BtConfig.SecureMode: isSecureModeOn:false
,03-31 13:00:46.236  5893  5976 D HidService: getHidService(): returning com.android.bluetooth.hid.HidService@1336e41c
,03-31 13:00:46.241  3461  4244 D SettingsProvider: name = bluetooth_input_device_priority_F8:95:C7:87:3C:51
03-31 13:00:46.241  3461  4244 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-31 13:00:46.241  3461  4244 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-31 13:00:46.241  3461  4244 D SettingsProvider: selectionArgs: false
03-31 13:00:46.241  3461  4244 D SettingsProvider: selectionArgs: 1002
03-31 13:00:46.241  3461  4244 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,03-31 13:00:46.241  3461  4244 D SettingsProvider: ret = -1
,03-31 13:00:46.246  5893  5976 D HidService: Saved priority F8:95:C7:87:3C:51 = -1
,03-31 13:00:46.246  3461  4438 D SettingsProvider: name = bluetooth_a2dp_sink_priority_F8:95:C7:87:3C:51
03-31 13:00:46.246  3461  4438 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-31 13:00:46.246  3461  4438 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-31 13:00:46.246  3461  4438 D SettingsProvider: selectionArgs: false
03-31 13:00:46.246  3461  4438 D SettingsProvider: selectionArgs: 1002
03-31 13:00:46.246  3461  4438 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,03-31 13:00:46.251  3461  4438 D SettingsProvider: ret = -1
,03-31 13:00:46.256  3461  3833 D SettingsProvider: name = bluetooth_headset_priority_F8:95:C7:87:3C:51
03-31 13:00:46.256  3461  3833 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-31 13:00:46.256  3461  3833 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-31 13:00:46.256  3461  3833 D SettingsProvider: selectionArgs: false
03-31 13:00:46.256  3461  3833 D SettingsProvider: selectionArgs: 1002
03-31 13:00:46.256  3461  3833 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,03-31 13:00:46.256  3461  3833 D SettingsProvider: ret = -1
,03-31 13:00:46.256  5893  5976 I BluetoothBondStateMachine: StableState(): Entering Off State
,03-31 13:00:46.271  3728  3728 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,03-31 13:00:46.276  3461  3461 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
03-31 13:00:46.276  3461  3461 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.device.action.BOND_STATE_CHANGED
03-31 13:00:46.276  3461  3461 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED
03-31 13:00:46.276  3461  3461 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 11
03-31 13:00:46.276  3461  3461 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 10
03-31 13:00:46.276  3461  3461 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
,03-31 13:00:46.286  3728  4803 D BluetoothTile:  handleUpdatestate:false name:null
,03-31 13:00:46.286  3461  3568 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a344a u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{1b336218 10216:com.android.settings/1000}
,03-31 13:00:46.291 10216 10216 D BluetoothNotiBroadcastReceiver: onReceive
03-31 13:00:46.291  3461  3491 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
,03-31 13:00:46.296 10370 11791 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,03-31 13:00:46.301  3461  3653 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a344a u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{1082dfc0 10370:com.sec.android.automotive.drivelink/u0a102}
,03-31 13:00:46.301 10370 10370 D [CarMode]: [AutoLaunchReceiver]-action: android.bluetooth.device.action.BOND_STATE_CHANGED
,03-31 13:00:46.301 10370 10370 D [CarMode]: [AutoLaunchReceiver]-ACTION_BOND_STATE_CHANGED G4-1 state is 10
,03-31 13:00:46.306  3461  3833 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a344a u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{1082dfc0 10370:com.sec.android.automotive.drivelink/u0a102}
,03-31 13:00:46.306  3461  4440 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
,03-31 13:00:46.311  3461  3617 V AlarmManager: waitForAlarm result :4
,03-31 13:00:46.316 10370 11792 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,03-31 13:00:46.316  3461  3833 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a344a u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{34687286 10556:com.samsung.android.app.watchmanagerstub/u0a121}
,03-31 13:00:46.321 10556 10556 E BluetoothHeadset: BTStateChangeCB is registed,
03-31 13:00:46.321 10556 10556 D GMHFPReceiver: android.bluetooth.device.action.BOND_STATE_CHANGED
03-31 13:00:46.321 10556 10556 D GMHFPReceiver: jangil::setProperties()
,03-31 13:00:46.321 10556 10556 D GMHFPReceiver: jangil::printBTStatus()
03-31 13:00:46.321  3461  4032 D SettingsProvider: name = Wearable0001
03-31 13:00:46.321  3461  4032 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-31 13:00:46.321  3461  4032 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-31 13:00:46.321  3461  4032 D SettingsProvider: selectionArgs: false
03-31 13:00:46.321  3461  4032 D SettingsProvider: selectionArgs: 10121
03-31 13:00:46.326  3461  4032 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,03-31 13:00:46.326  3461  4032 D SettingsProvider: ret = -1
03-31 13:00:46.326 10556 10556 D GMHFPReceiver: ::::::::Wearable0001::false
03-31 13:00:46.326  3461  4244 D SettingsProvider: name = Wearable0002
03-31 13:00:46.326  3461  4244 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-31 13:00:46.326  3461  4244 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-31 13:00:46.326  3461  4244 D SettingsProvider: selectionArgs: false
03-31 13:00:46.326  3461  4244 D SettingsProvider: selectionArgs: 10121
03-31 13:00:46.326  3461  4244 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,03-31 13:00:46.326  3461  4244 D SettingsProvider: ret = -1
03-31 13:00:46.326 10556 10556 D GMHFPReceiver: ::::::::Wearable0002::false
,03-31 13:00:46.331  3461  4438 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a344a u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{3cd9dfc6 4376:com.google.android.gms.persistent/u0a14}
,03-31 13:00:46.336  5893  5893 D BtGatt.ScanManager: awakened up at time 247431,
03-31 13:00:46.336  5893  5979 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-31 13:00:46.336  5893  5958 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
,03-31 13:00:46.341  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 13:00:46.341  5893  5958 D BtGatt.GattService: current time is 247435238528
03-31 13:00:46.341  5893  5958 D BtGatt.GattService: Batch record : [35, 125, -92, -18, 120, 86, 1, -128, -54, 8, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0, 117, 45, 127, 81, -94, 101, 1, -128, -73, 8, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-31 13:00:46.341  5893  5958 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-31 13:00:46.341  5893  5958 D ScanRecord: parseFromBytes
03-31 13:00:46.341  5893  5958 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-31 13:00:46.341  5893  5958 D ScanRecord: parseFromBytes
03-31 13:00:46.341  5893  5958 D BtGatt.GattService: result: ScanResult{mDevice=65:A2:51:7F:2D:75, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-73, mTimestampNanos=247035402736}
03-31 13:00:46.341  5893  5958 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-31 13:00:46.341  5893  5958 D BtGatt.GattService: result: ScanResult{mDevice=56:78:EE:A4:7D:23, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-54, mTimestampNanos=247035402736}
,03-31 13:00:46.341  5893  5958 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-31 13:00:46.341 11224 11234 D ScanRecord: parseFromBytes
03-31 13:00:46.341 11224 11234 D ScanRecord: parseFromBytes
,03-31 13:00:46.341 11224 11224 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
03-31 13:00:46.341 11224 11224 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:CF:C5:D9:E5:61] updated - the peer count is 2
,03-31 13:00:46.421 10556 10556 D GMHFPReceiver: onServiceConnected() : 1
03-31 13:00:46.421 10556 10556 D GMHFPReceiver: mBluetoothHeadset = true
,03-31 13:00:47.116  5893  6021 W bt-btif : new conn_srvc id:26, app_id:255
03-31 13:00:47.116  5893  6021 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
03-31 13:00:47.116  5893  6021 W bt-btif : bta_dm_pm_ssr:2, lat:1200
,03-31 13:00:47.126 11224 11726 D BluetoothSocket: socket fd passed by stack  fds: [Ljava.io.FileDescriptor;@4cfca6c
,03-31 13:00:47.136  5893  8993 E BluetoothRemoteDevices: setRfcommConnected true
,03-31 13:00:47.136 11224 11726 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection accepted
,03-31 13:00:47.146 11224 11726 D BluetoothSocket: getInputStream(): myUserId = 0
,03-31 13:00:47.151 11224 11726 D BluetoothSocket: getOutputStream(): myUserId = 0
,03-31 13:00:47.156 11224 11726 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection initialized (thread ID: 1567)
,03-31 13:00:47.156 11224 11726 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@17ae4835, channel: 6, state: LISTENING
03-31 13:00:47.156 11224 11726 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@17ae4835, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@27f3f741, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3d3314camSocket: android.net.LocalSocket@3d51963b impl:android.net.LocalSocketImpl@24252158 fd:FileDescriptor[93]
,03-31 13:00:47.156 11224 11726 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3d51963b impl:android.net.LocalSocketImpl@24252158 fd:FileDescriptor[93]
,03-31 13:00:47.156 11224 11726 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-31 13:00:47.161 11224 11726 D BluetoothSocket: bindListen(): myUserId = 0
,03-31 13:00:47.166 11224 11726 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-31 13:00:47.171 11224 11726 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[119]}
,03-31 13:00:47.171 11224 11726 D BluetoothSocket: bindListen(), new LocalSocket 
03-31 13:00:47.171 11224 11726 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,03-31 13:00:47.171 11224 11726 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@160832b1
03-31 13:00:47.171 11224 11726 D BluetoothSocket: channel: 6
,03-31 13:00:47.176 11224 11726 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-31 13:00:47.176 11224 11796 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 1567)
,03-31 13:00:47.276  5893  6021 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-31 13:00:47.276 11224 11796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesRead: Read 15 bytes successfully (thread ID: 1567)
03-31 13:00:47.276  5893  6021 D IOP_DB_BT: db_query: result 1
03-31 13:00:47.276  5893  6021 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-31 13:00:47.276  5893  6021 D IOP_DB_BT: db_query: result 1
03-31 13:00:47.276 11224 11796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Got valid identity from [<no peer name> F8:95:C7:87:3C:51]
03-31 13:00:47.276 11224 11796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesWritten: 15 bytes successfully written (thread ID: 1567)
03-31 13:00:47.276 11224 11796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: removeThreadFromList: Removing thread with ID 1567
03-31 13:00:47.276  5893  6021 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-31 13:00:47.276 11224 11796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Handshake thread disposed (thread ID: 1567)
03-31 13:00:47.276 11224 11796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onIncomingConnectionConnected: [<no peer name> F8:95:C7:87:3C:51]
03-31 13:00:47.276  5893  6021 D IOP_DB_BT: db_query: result 1
03-31 13:00:47.276  5893  6021 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-31 13:00:47.276 11224 11796 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 1567)
03-31 13:00:47.276  5893  6021 D IOP_DB_BT: db_query: result 1
03-31 13:00:47.276 11224 11224 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:95:C7:87:3C:51]
03-31 13:00:47.276 11224 11224 I io.jxcore.node.ConnectionHelper: onConnected: Incoming connection to peer [<no peer name> F8:95:C7:87:3C:51]
03-31 13:00:47.276 11224 11224 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
,03-31 13:00:47.291 11224 11224 D BluetoothSocket: getInputStream(): myUserId = 0
,03-31 13:00:47.301 11224 11224 D BluetoothSocket: getOutputStream(): myUserId = 0
,03-31 13:00:47.306 11224 11224 I io.jxcore.node.ConnectionHelper: lowerBleDiscoveryPowerAndStartResetTimer: Lowering the power settings
03-31 13:00:47.306 11224 11224 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 2 -> 0
03-31 13:00:47.306 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-31 13:00:47.306 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 13:00:47.306 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-31 13:00:47.306 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-31 13:00:47.306 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-31 13:00:47.306 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-31 13:00:47.306  5893  5978 D BtGatt.AdvertiseManager: message : 1,
03-31 13:00:47.311  5893  5978 D BtGatt.AdvertiseManager: stop advertise for client 7
03-31 13:00:47.311  5893  5978 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
,03-31 13:00:47.311  5893  5978 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,03-31 13:00:47.311  5893  5958 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
,03-31 13:00:47.311  5893  5958 D BtGatt.GattService: Client app is not null!
03-31 13:00:47.316  5893  5903 D BtGatt.GattService: unregisterClient() - clientIf=7
,03-31 13:00:47.316 11224 11224 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-31 13:00:47.316 11224 11224 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-31 13:00:47.316 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 3, timeout: 0, is connectable: false
03-31 13:00:47.316 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 13:00:47.316 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-31 13:00:47.316 11224 11224 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
,03-31 13:00:47.316 11224 11224 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 13:00:47.316 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 13:00:47.316 11224 11224 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-31 13:00:47.326  5893  5903 D BtGatt.GattService: registerClient() - UUID=3af60683-daed-4393-847d-a299ccf3e2eb
,03-31 13:00:47.341  3461  3617 V AlarmManager: waitForAlarm result :4
,03-31 13:00:47.346  5893  5893 D BtGatt.ScanManager: awakened up at time 248440,
03-31 13:00:47.346  5893  5979 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-31 13:00:47.346  5893  5958 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,03-31 13:00:47.346  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 13:00:47.366  5893  5958 D BtGatt.GattService: onClientRegistered() - UUID=3af60683-daed-4393-847d-a299ccf3e2eb, clientIf=7
,03-31 13:00:47.371 11224 11234 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-31 13:00:47.391  5893  5905 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 42,
,03-31 13:00:47.391  5893  5978 D BtGatt.AdvertiseManager: message : 0
03-31 13:00:47.391  5893  5978 D BtGatt.AdvertiseManager: number of adv instance running0
,03-31 13:00:47.391  5893  5978 D BtGatt.AdvertiseManager: size of list is =0
,03-31 13:00:47.401  5893  5978 D BtGatt.AdvertiseManager: starting advertising
,03-31 13:00:47.401  5893  5978 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-31 13:00:47.406  5893  5958 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-31 13:00:47.411  5893  5978 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 13:00:47.411  5893  5958 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-31 13:00:47.411  5893  5978 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-31 13:00:47.411  5893  5978 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 0, TxPowerLevel: 3, isConnectable: false, Timeout: 0
03-31 13:00:47.416 11224 11224 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-31 13:00:47.416  5893  5987 D BtGatt.GattService: stopScan() - queue size =1
,03-31 13:00:47.416  5893  5979 D BtGatt.ScanManager: filter size is 1
03-31 13:00:47.416  5893  5979 D BtGatt.ScanManager: delete FilterIndex - 11
,03-31 13:00:47.416  5893  5903 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-31 13:00:47.421  5893  5958 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-31 13:00:47.421  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 13:00:47.421  5893  5979 D BtGatt.ScanManager: stopping BLe Batch
03-31 13:00:47.421 11224 11224 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 13:00:47.421 11224 11224 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 13:00:47.421 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 13:00:47.421 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 13:00:47.421 11224 11224 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 13:00:47.421 11224 11224 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-31 13:00:47.421  5893  5958 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-31 13:00:47.421  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 13:00:47.421  5893  5979 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-31 13:00:47.426  5893  5958 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-31 13:00:47.426  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 13:00:47.431  5893  5903 D BtGatt.GattService: registerClient() - UUID=b2b0e397-9c6d-4e1f-8607-00c05c712c9e
,03-31 13:00:47.471  5893  5958 D BtGatt.GattService: onClientRegistered() - UUID=b2b0e397-9c6d-4e1f-8607-00c05c712c9e, clientIf=6,
03-31 13:00:47.471 11224 11280 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-31 13:00:47.476  5893  5905 D BtGatt.GattService: start scan with filters
,03-31 13:00:47.506  5893  5905 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 53
,03-31 13:00:47.506 11224 11224 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 13:00:47.506 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 13:00:47.506  5893  5979 D BtGatt.ScanManager: handling starting scan
03-31 13:00:47.506  5893  5979 D BtGatt.ScanManager: isFilteringSupported
03-31 13:00:47.506  5893  5979 D BluetoothAdapter: setting StandAloneBleMode
03-31 13:00:47.506 11224 11224 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 3 -> 1
03-31 13:00:47.511 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-31 13:00:47.511 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 13:00:47.511 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-31 13:00:47.511 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-31 13:00:47.511 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-31 13:00:47.511 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-31 13:00:47.521  5893  5958 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-31 13:00:47.521  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 13:00:47.521  5893  5978 D BtGatt.AdvertiseManager: message : 1
03-31 13:00:47.521  5893  5979 D BtGatt.ScanManager: allow scan with filters
03-31 13:00:47.521  5893  5979 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-31 13:00:47.521  5893  5979 D BtGatt.ScanManager: set filter index= 12 for clientIf= 6
03-31 13:00:47.521  5893  5978 D BtGatt.AdvertiseManager: stop advertise for client 7
03-31 13:00:47.521  5893  5978 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
,03-31 13:00:47.526  5893  5978 D BtGatt.AdvertiseManager: logClientsSet() - status: -1,
03-31 13:00:47.526  5893  5958 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,03-31 13:00:47.526  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 13:00:47.526  5893  5979 D BtGatt.ScanManager: Starting BLE batch scan,
03-31 13:00:47.526  5893  5979 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-31 13:00:47.526  5893  5958 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
,03-31 13:00:47.526  5893  5958 D BtGatt.GattService: Client app is not null!
,03-31 13:00:47.531  5893  5903 D BtGatt.GattService: unregisterClient() - clientIf=7
,03-31 13:00:47.531  5893  5958 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-31 13:00:47.531  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 13:00:47.531 11224 11224 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
03-31 13:00:47.531 11224 11224 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-31 13:00:47.531 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
,03-31 13:00:47.531 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 13:00:47.531 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-31 13:00:47.531 11224 11224 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
,03-31 13:00:47.531 11224 11224 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-31 13:00:47.536 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 13:00:47.536 11224 11224 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-31 13:00:47.536  5893  5958 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-31 13:00:47.536  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 13:00:47.546  5893  5903 D BtGatt.GattService: registerClient() - UUID=d9b49871-8771-4738-87a5-af9cacac102f
,03-31 13:00:47.566 11224 11235 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@270840d6, channel: 6, state: CLOSED
,03-31 13:00:47.566 11224 11235 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@86694ae, channel: 6, state: CLOSED
,03-31 13:00:47.571 11224 11235 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@4c95be0, channel: 6, state: CLOSED
,03-31 13:00:47.571 11224 11235 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@27ac6f8, channel: 6, state: CLOSED
,03-31 13:00:47.571 11224 11235 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@14be020e, channel: 6, state: CLOSED
,03-31 13:00:47.571 11224 11235 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@17ae4835, channel: 6, state: CLOSED
,03-31 13:00:47.586  5893  5958 D BtGatt.GattService: onClientRegistered() - UUID=d9b49871-8771-4738-87a5-af9cacac102f, clientIf=7
,03-31 13:00:47.591 11224 11233 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-31 13:00:47.601  5893  5905 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 43,
03-31 13:00:47.601  5893  5978 D BtGatt.AdvertiseManager: message : 0
03-31 13:00:47.601  5893  5978 D BtGatt.AdvertiseManager: number of adv instance running0
03-31 13:00:47.601  5893  5978 D BtGatt.AdvertiseManager: size of list is =0
,03-31 13:00:47.601  5893  5978 D BtGatt.AdvertiseManager: starting advertising
03-31 13:00:47.601  5893  5978 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-31 13:00:47.606  5893  5958 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-31 13:00:47.606  5893  5978 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 13:00:47.606  5893  5958 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0,
03-31 13:00:47.606  5893  5978 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-31 13:00:47.606  5893  5978 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 0, TxPowerLevel: 1, isConnectable: false, Timeout: 0
,03-31 13:00:47.611 11224 11224 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-31 13:00:47.611  5893  5987 D BtGatt.GattService: stopScan() - queue size =1
03-31 13:00:47.611  5893  5979 D BtGatt.ScanManager: filter size is 1
03-31 13:00:47.611  5893  5979 D BtGatt.ScanManager: delete FilterIndex - 12
03-31 13:00:47.611  5893  5903 D BtGatt.GattService: unregisterClient() - clientIf=6
03-31 13:00:47.611  5893  5958 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,03-31 13:00:47.611  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 13:00:47.611 11224 11224 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 13:00:47.611 11224 11224 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 13:00:47.611 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-31 13:00:47.611 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 13:00:47.611 11224 11224 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 13:00:47.611 11224 11224 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-31 13:00:47.611  5893  5979 D BtGatt.ScanManager: stopping BLe Batch
03-31 13:00:47.616  5893  5958 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,03-31 13:00:47.616  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 13:00:47.616  5893  5979 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-31 13:00:47.621  5893  5958 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1,
03-31 13:00:47.621  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 13:00:47.621  5893  5958 D BtGatt.GattService: current time is 248715319195
03-31 13:00:47.621  5893  5903 D BtGatt.GattService: registerClient() - UUID=bd8a1138-dd72-48b2-9dba-808204840469
03-31 13:00:47.621  5893  5958 D BtGatt.GattService: Batch record : [35, 125, -92, -18, 120, 86, 1, -128, -55, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0]
03-31 13:00:47.621  5893  5958 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-31 13:00:47.621  5893  5958 D ScanRecord: parseFromBytes
,03-31 13:00:47.661  5893  5958 D BtGatt.GattService: onClientRegistered() - UUID=bd8a1138-dd72-48b2-9dba-808204840469, clientIf=6
,03-31 13:00:47.661 11224 11234 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-31 13:00:47.661  5893  8993 D BtGatt.GattService: start scan with filters
,03-31 13:00:47.671  5893  8993 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 54
,03-31 13:00:47.671 11224 11224 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 13:00:47.671 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 13:00:47.671 11224 11224 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 2 -> 0
03-31 13:00:47.671  5893  5979 D BtGatt.ScanManager: handling starting scan
03-31 13:00:47.671  5893  5979 D BtGatt.ScanManager: isFilteringSupported
03-31 13:00:47.671  5893  5979 D BluetoothAdapter: setting StandAloneBleMode
03-31 13:00:47.671 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-31 13:00:47.671 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 13:00:47.671 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-31 13:00:47.671 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-31 13:00:47.671 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-31 13:00:47.671 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-31 13:00:47.671  5893  5978 D BtGatt.AdvertiseManager: message : 1
03-31 13:00:47.671  5893  5958 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-31 13:00:47.671  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 13:00:47.671  5893  5979 D BtGatt.ScanManager: allow scan with filters
03-31 13:00:47.671  5893  5979 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,03-31 13:00:47.671  5893  5979 D BtGatt.ScanManager: set filter index= 13 for clientIf= 6
03-31 13:00:47.671  5893  5978 D BtGatt.AdvertiseManager: stop advertise for client 7
03-31 13:00:47.671  5893  5978 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-31 13:00:47.676  5893  5958 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-31 13:00:47.676  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 13:00:47.676  5893  5979 D BtGatt.ScanManager: Starting BLE batch scan
03-31 13:00:47.676  5893  5979 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-31 13:00:47.676  5893  5978 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-31 13:00:47.676  5893  5958 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,03-31 13:00:47.676  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 13:00:47.676  5893  5958 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-31 13:00:47.676  5893  5958 D BtGatt.GattService: Client app is not null!
,03-31 13:00:47.676  5893  5903 D BtGatt.GattService: unregisterClient() - clientIf=7
03-31 13:00:47.681 11224 11224 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 13:00:47.681 11224 11224 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-31 13:00:47.681 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false,
03-31 13:00:47.681 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 13:00:47.681 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-31 13:00:47.681 11224 11224 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
,03-31 13:00:47.681 11224 11224 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 13:00:47.681 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 13:00:47.681 11224 11224 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-31 13:00:47.681  5893  5958 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-31 13:00:47.681  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 13:00:47.681  5893  5903 D BtGatt.GattService: registerClient() - UUID=8c3bd087-d008-463d-9b15-2644ca308967
,03-31 13:00:47.726  5893  5958 D BtGatt.GattService: onClientRegistered() - UUID=8c3bd087-d008-463d-9b15-2644ca308967, clientIf=7
,03-31 13:00:47.726 11224 11280 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-31 13:00:47.761  5893  8993 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 44
,03-31 13:00:47.761  5893  5978 D BtGatt.AdvertiseManager: message : 0
,03-31 13:00:47.766  5893  5978 D BtGatt.AdvertiseManager: number of adv instance running0
03-31 13:00:47.766  5893  5978 D BtGatt.AdvertiseManager: size of list is =0
,03-31 13:00:47.776  5893  5978 D BtGatt.AdvertiseManager: starting advertising
03-31 13:00:47.776  5893  5978 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-31 13:00:47.786  5893  5958 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-31 13:00:47.786  5893  5978 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 13:00:47.791  5893  5958 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-31 13:00:47.791  5893  5978 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-31 13:00:47.791  5893  5978 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 0, TxPowerLevel: 1, isConnectable: false, Timeout: 0
,03-31 13:00:47.796 11224 11224 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-31 13:00:47.801  5893  5905 D BtGatt.GattService: stopScan() - queue size =1
,03-31 13:00:47.801  5893  5979 D BtGatt.ScanManager: filter size is 1
03-31 13:00:47.801  5893  5979 D BtGatt.ScanManager: delete FilterIndex - 13
,03-31 13:00:47.806  5893  5903 D BtGatt.GattService: unregisterClient() - clientIf=6
03-31 13:00:47.806  5893  5958 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,03-31 13:00:47.806  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 13:00:47.806 11224 11224 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 13:00:47.806 11224 11224 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 13:00:47.806 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-31 13:00:47.806 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 13:00:47.806 11224 11224 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 13:00:47.806  5893  5979 D BtGatt.ScanManager: stopping BLe Batch
03-31 13:00:47.811 11224 11224 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-31 13:00:47.811  5893  5958 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,03-31 13:00:47.816  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 13:00:47.816  5893  5979 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-31 13:00:47.816  5893  5958 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,03-31 13:00:47.816  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 13:00:47.831  5893  5903 D BtGatt.GattService: registerClient() - UUID=547381f8-770a-4122-96de-db5057b03dc1
,03-31 13:00:47.871  5893  5958 D BtGatt.GattService: onClientRegistered() - UUID=547381f8-770a-4122-96de-db5057b03dc1, clientIf=6
03-31 13:00:47.871 11224 11233 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-31 13:00:47.871  5893  8993 D BtGatt.GattService: start scan with filters,
,03-31 13:00:47.891  5893  8993 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 55
,03-31 13:00:47.891  5893  5979 D BtGatt.ScanManager: handling starting scan
03-31 13:00:47.891  5893  5979 D BtGatt.ScanManager: isFilteringSupported
03-31 13:00:47.891  5893  5979 D BluetoothAdapter: setting StandAloneBleMode
,03-31 13:00:47.896  5893  5958 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-31 13:00:47.896  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 13:00:47.896  5893  5979 D BtGatt.ScanManager: allow scan with filters
03-31 13:00:47.896  5893  5979 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-31 13:00:47.896  5893  5979 D BtGatt.ScanManager: set filter index= 14 for clientIf= 6
03-31 13:00:47.901  5893  5958 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-31 13:00:47.901  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 13:00:47.901  5893  5979 D BtGatt.ScanManager: Starting BLE batch scan
03-31 13:00:47.901  5893  5979 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-31 13:00:47.906  5893  5958 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-31 13:00:47.906  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 13:00:47.906  5893  5958 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-31 13:00:47.906  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 13:00:47.911 11224 11224 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
03-31 13:00:47.916 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 13:00:47.916 11224 11224 I io.jxcore.node.ConnectionHelper: onConnected: Incoming socket thread, for peer [<no peer name> F8:95:C7:87:3C:51], created successfully
03-31 13:00:47.916 11224 11224 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 1
03-31 13:00:47.916 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 13:00:47.916 11224 11224 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-31 13:00:47.916 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true,
03-31 13:00:47.916 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 13:00:47.916 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-31 13:00:47.916 11224 11811 D io.jxcore.node.IncomingSocketThread: Entering thread (ID: 1568)
,03-31 13:00:47.921  2874  3434 D EnterpriseController: netId is 0
03-31 13:00:47.921  2874  3434 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,03-31 13:00:47.926 11224 11811 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 33300
,03-31 13:00:47.926 11224 11811 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,03-31 13:00:47.931 11224 11811 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
,03-31 13:00:47.931 11224 11811 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-31 13:00:47.931 11224 11811 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 1568)
,03-31 13:00:47.931 11224 11811 D io.jxcore.node.IncomingSocketThread: Exiting thread (ID: 1568)
,03-31 13:00:47.936 11224 11813 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1569, name: Sender)
,03-31 13:00:47.936 11224 11814 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1570, name: Receiver)
,03-31 13:00:48.656  5893  6021 W bt-btif : new conn_srvc id:26, app_id:255
03-31 13:00:48.656  5893  6021 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
03-31 13:00:48.656  5893  6021 W bt-btif : bta_dm_pm_ssr:2, lat:1200
03-31 13:00:48.656 11224 11726 D BluetoothSocket: socket fd passed by stack  fds: [Ljava.io.FileDescriptor;@1b95b17
,03-31 13:00:48.661  5893  6021 W bt-btif : new conn_srvc id:26, app_id:1
03-31 13:00:48.661  5893  6021 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
03-31 13:00:48.661  5893  6021 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:1
03-31 13:00:48.661  5893  6021 W bt-btif : bta_dm_pm_ssr:2, lat:1200
,03-31 13:00:48.676  5893  5987 E BluetoothRemoteDevices: setRfcommConnected true
,03-31 13:00:48.676  5893  5905 E BluetoothRemoteDevices: setRfcommConnected true
03-31 13:00:48.681 11224 11726 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection accepted,
03-31 13:00:48.686 11224 11733 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onSocketConnected: [<no peer name> F8:CF:C5:D9:E5:61] (thread ID: 1566)
03-31 13:00:48.686 11224 11733 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 1566)
,03-31 13:00:48.691 11224 11726 D BluetoothSocket: getInputStream(): myUserId = 0
,03-31 13:00:48.696 11224 11733 D BluetoothSocket: getInputStream(): myUserId = 0
,03-31 13:00:48.696 11224 11726 D BluetoothSocket: getOutputStream(): myUserId = 0
03-31 13:00:48.696 11224 11726 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection initialized (thread ID: 1571)
03-31 13:00:48.696 11224 11726 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@76fb04, channel: 6, state: LISTENING
03-31 13:00:48.696 11224 11726 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@76fb04, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@160832b1, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1c3c48edmSocket: android.net.LocalSocket@38317322 impl:android.net.LocalSocketImpl@2c6e91b3 fd:FileDescriptor[119]
03-31 13:00:48.696 11224 11726 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@38317322 impl:android.net.LocalSocketImpl@2c6e91b3 fd:FileDescriptor[119]
03-31 13:00:48.696 11224 11726 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-31 13:00:48.701 11224 11823 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 1571)
,03-31 13:00:48.701 11224 11733 D BluetoothSocket: getOutputStream(): myUserId = 0
03-31 13:00:48.701 11224 11823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesRead: Read 15 bytes successfully (thread ID: 1571)
03-31 13:00:48.701 11224 11733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesWritten: 15 bytes successfully written (thread ID: 1572)
03-31 13:00:48.701  5893  6021 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 13:00:48.701 11224 11733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Outgoing connection initialized (*handshake* thread ID: 1572)
03-31 13:00:48.701 11224 11733 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1566)
,03-31 13:00:48.701 11224 11726 D BluetoothSocket: bindListen(): myUserId = 0
03-31 13:00:48.701 11224 11726 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-31 13:00:48.701  5893  6021 D IOP_DB_BT: db_query: result 1
03-31 13:00:48.701  5893  6021 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
,03-31 13:00:48.701  5893  6021 D IOP_DB_BT: db_query: result 1
03-31 13:00:48.706 11224 11726 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[122]}
03-31 13:00:48.706 11224 11726 D BluetoothSocket: bindListen(), new LocalSocket 
03-31 13:00:48.706 11224 11726 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-31 13:00:48.706 11224 11726 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3eeac370
,03-31 13:00:48.706 11224 11726 D BluetoothSocket: channel: 6
03-31 13:00:48.706 11224 11726 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-31 13:00:48.706 11224 11823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Got valid identity from [<no peer name> F8:CF:C5:D9:E5:61]
03-31 13:00:48.706 11224 11823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesWritten: 15 bytes successfully written (thread ID: 1571)
03-31 13:00:48.706  5893  6021 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 13:00:48.706  5893  6021 D IOP_DB_BT: db_query: result 1
03-31 13:00:48.706  5893  6021 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 13:00:48.706  5893  6021 D IOP_DB_BT: db_query: result 1
,03-31 13:00:48.706 11224 11824 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 1572)
03-31 13:00:48.711 11224 11823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: removeThreadFromList: Removing thread with ID 1571
03-31 13:00:48.711 11224 11823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Handshake thread disposed (thread ID: 1571)
03-31 13:00:48.711 11224 11823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onIncomingConnectionConnected: [<no peer name> F8:CF:C5:D9:E5:61]
03-31 13:00:48.711 11224 11823 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 1571)
03-31 13:00:48.711 11224 11224 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:CF:C5:D9:E5:61]
03-31 13:00:48.711 11224 11224 I io.jxcore.node.ConnectionHelper: onConnected: Incoming connection to peer [<no peer name> F8:CF:C5:D9:E5:61]
,03-31 13:00:48.711 11224 11224 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:CF:C5:D9:E5:61] updated - the peer count is 2
,03-31 13:00:48.716 11224 11224 D BluetoothSocket: getInputStream(): myUserId = 0
,03-31 13:00:48.716 11224 11224 D BluetoothSocket: getOutputStream(): myUserId = 0
,03-31 13:00:48.716 11224 11224 I io.jxcore.node.ConnectionHelper: onConnected: Incoming socket thread, for peer [<no peer name> F8:CF:C5:D9:E5:61], created successfully
03-31 13:00:48.716 11224 11224 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 2
03-31 13:00:48.721 11224 11825 D io.jxcore.node.IncomingSocketThread: Entering thread (ID: 1573)
,03-31 13:00:48.721 11224 11825 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 33300
03-31 13:00:48.721 11224 11825 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
03-31 13:00:48.721 11224 11825 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-31 13:00:48.721 11224 11825 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-31 13:00:48.721 11224 11825 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 1573)
03-31 13:00:48.721 11224 11825 D io.jxcore.node.IncomingSocketThread: Exiting thread (ID: 1573)
,03-31 13:00:48.721 11224 11826 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1574, name: Sender)
03-31 13:00:48.721 11224 11827 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1575, name: Receiver)
,03-31 13:00:48.731  5893  6021 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 13:00:48.731 11224 11824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesRead: Read 15 bytes successfully (thread ID: 1572)
03-31 13:00:48.731  5893  6021 D IOP_DB_BT: db_query: result 1
03-31 13:00:48.731  5893  6021 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 13:00:48.731  5893  6021 D IOP_DB_BT: db_query: result 1
,03-31 13:00:48.731 11224 11824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Handshake succeeded with [<no peer name> F8:CF:C5:D9:E5:61]
03-31 13:00:48.731 11224 11824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onHandshakeSucceeded: [<no peer name> F8:CF:C5:D9:E5:61] (thread ID: 1566)
03-31 13:00:48.731 11224 11824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: handleSuccessfulClientThread: [<no peer name> F8:CF:C5:D9:E5:61] (thread ID: 1566)
03-31 13:00:48.731 11224 11824 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 1572)
03-31 13:00:48.731 11224 11224 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:CF:C5:D9:E5:61]
03-31 13:00:48.731 11224 11224 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing connection to peer [<no peer name> F8:CF:C5:D9:E5:61],
03-31 13:00:48.731 11224 11224 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:CF:C5:D9:E5:61] updated - the peer count is 2
,03-31 13:00:48.736 11224 11224 D BluetoothSocket: getInputStream(): myUserId = 0
,03-31 13:00:48.736 11224 11224 D BluetoothSocket: getOutputStream(): myUserId = 0
03-31 13:00:48.736 11224 11224 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing socket thread, for peer [<no peer name> F8:CF:C5:D9:E5:61], created successfully
03-31 13:00:48.736 11224 11224 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 3
,03-31 13:00:48.741 11224 11828 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1576)
,03-31 13:00:48.741 11224 11828 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 45028
03-31 13:00:48.741 11224 11828 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,03-31 13:00:48.741 11224 11828 I io.jxcore.node.ConnectionHelper: onListeningForIncomingConnections: Outgoing connection is using port 45028 (peer ID: F8:CF:C5:D9:E5:61)
03-31 13:00:48.741 11224 11828 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "F8:CF:C5:D9:E5:61" removed
,03-31 13:00:48.746 11224 11287 I jxcore-log: INFO testThaliMobileNative: 
03-31 13:00:48.746 11224 11287 I jxcore-log: 
,03-31 13:00:48.746 11224 11287 I jxcore-log: ok 165 Must have listeningPort
03-31 13:00:48.746 11224 11287 I jxcore-log: 
,03-31 13:00:48.746 11224 11287 I jxcore-log: ok 166 listeningPort must be a number
03-31 13:00:48.746 11224 11287 I jxcore-log: 
03-31 13:00:48.746 11224 11287 I jxcore-log: ok 167 Connection must have clientPort
03-31 13:00:48.746 11224 11287 I jxcore-log: 
03-31 13:00:48.746 11224 11287 I jxcore-log: ok 168 clientPort must be a number
03-31 13:00:48.746 11224 11287 I jxcore-log: 
,03-31 13:00:48.751 11224 11287 I jxcore-log: ok 169 Connection must have serverPort
03-31 13:00:48.751 11224 11287 I jxcore-log: 
,03-31 13:00:48.751 11224 11287 I jxcore-log: ok 170 serverPort must be a number
03-31 13:00:48.751 11224 11287 I jxcore-log: 
03-31 13:00:48.751 11224 11287 I jxcore-log: ok 171 forward connection must have clientPort == 0
03-31 13:00:48.751 11224 11287 I jxcore-log: 
,03-31 13:00:48.751 11224 11287 I jxcore-log: ok 172 forward connection must have serverPort == 0
03-31 13:00:48.751 11224 11287 I jxcore-log: 
,03-31 13:00:48.761 11224 11287 I jxcore-log: # teardown
03-31 13:00:48.761 11224 11287 I jxcore-log: 
,03-31 13:00:48.796  3461  6120 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,03-31 13:00:48.906  3461  3617 V AlarmManager: waitForAlarm result :4
,03-31 13:00:48.921  5893  5893 D BtGatt.ScanManager: awakened up at time 250016
03-31 13:00:48.926  5893  5979 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-31 13:00:48.931  5893  5958 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
03-31 13:00:48.931  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 13:00:48.931  5893  5958 D BtGatt.GattService: current time is 250028170903
03-31 13:00:48.931  5893  5958 D BtGatt.GattService: Batch record : [35, 125, -92, -18, 120, 86, 1, -128, -54, 9, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0, 17, 78, 92, 121, 52, 91, 1, -128, -84, 11, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-31 13:00:48.931  5893  5958 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-31 13:00:48.931  5893  5958 D ScanRecord: parseFromBytes
03-31 13:00:48.931  5893  5958 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-31 13:00:48.931  5893  5958 D ScanRecord: parseFromBytes
03-31 13:00:48.931  5893  5958 D BtGatt.GattService: result: ScanResult{mDevice=5B:34:79:5C:4E:11, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-84, mTimestampNanos=249478435861}
03-31 13:00:48.931  5893  5958 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-31 13:00:48.931  5893  5958 D BtGatt.GattService: result: ScanResult{mDevice=56:78:EE:A4:7D:23, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-54, mTimestampNanos=249578435861}
03-31 13:00:48.936  5893  5958 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-31 13:00:48.936 11224 11280 D ScanRecord: parseFromBytes
03-31 13:00:48.936 11224 11280 D ScanRecord: parseFromBytes
,03-31 13:00:48.941 11224 11224 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2,
03-31 13:00:48.941 11224 11224 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:CF:C5:D9:E5:61] updated - the peer count is 2
,03-31 13:00:48.966 11224 11813 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 1569, thread name: Sender)
03-31 13:00:48.966 11224 11813 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Input stream got -1 on read
03-31 13:00:48.966 11224 11813 W io.jxcore.node.ConnectionHelper: onDisconnected: Incoming connection, peer [<no peer name> F8:95:C7:87:3C:51] disconnected: Input stream got -1 on read
03-31 13:00:48.966 11224 11813 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1568
03-31 13:00:48.966 11224 11813 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 1568)
03-31 13:00:48.966 11224 11813 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@c02a8a5, channel: 6, state: CONNECTED
03-31 13:00:48.966 11224 11813 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@c02a8a5, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@122447a, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1cd0842bmSocket: android.net.LocalSocket@314f9088 impl:android.net.LocalSocketImpl@e1a2a21 fd:FileDescriptor[92]
03-31 13:00:48.966 11224 11813 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@314f9088 impl:android.net.LocalSocketImpl@e1a2a21 fd:FileDescriptor[92]
03-31 13:00:48.966 11224 11813 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@c02a8a5, channel: 6, state: CLOSED
03-31 13:00:48.966 11224 11813 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@c02a8a5, channel: 6, state: CLOSED
03-31 13:00:48.966 11224 11813 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-31 13:00:48.966 11224 11813 D io.jxcore.node.IncomingSocketThread: close: Stopping receiving thread...
03-31 13:00:48.966 11224 11813 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 1570
03-31 13:00:48.966 11224 11813 D io.jxcore.node.IncomingSocketThread: close: Stopping sending thread...
03-31 13:00:48.966 11224 11813 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 1569
03-31 13:00:48.966 11224 11813 D io.jxcore.node.IncomingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 1568)
,03-31 13:00:48.971 11224 11814 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 1570, thread name: Receiver): bt socket closed, read return: -1
03-31 13:00:48.971 11224 11814 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1570, name: Receiver)
,03-31 13:00:48.971 11224 11813 I io.jxcore.node.IncomingSocketThread: close: Complete (thread ID: 1568),
03-31 13:00:48.976 11224 11813 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
03-31 13:00:48.976 11224 11813 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1569, name: Sender)
,03-31 13:00:48.976 11224 11826 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 1574, thread name: Sender),
03-31 13:00:48.976 11224 11826 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Input stream got -1 on read
03-31 13:00:48.976 11224 11826 W io.jxcore.node.ConnectionHelper: onDisconnected: Incoming connection, peer [<no peer name> F8:CF:C5:D9:E5:61] disconnected: Input stream got -1 on read
03-31 13:00:48.976 11224 11826 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1573
03-31 13:00:48.976 11224 11826 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 1573)
03-31 13:00:48.976 11224 11826 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@30802e46, channel: 6, state: CONNECTED
03-31 13:00:48.976 11224 11826 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@30802e46, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@4d13807, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@28912d34mSocket: android.net.LocalSocket@2bce475d impl:android.net.LocalSocketImpl@f80e8d2 fd:FileDescriptor[121]
,03-31 13:00:48.976 11224 11826 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2bce475d impl:android.net.LocalSocketImpl@f80e8d2 fd:FileDescriptor[121],
03-31 13:00:48.981 11224 11826 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@30802e46, channel: 6, state: CLOSED
03-31 13:00:48.981 11224 11826 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@30802e46, channel: 6, state: CLOSED
03-31 13:00:48.981 11224 11826 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
,03-31 13:00:48.981 11224 11826 D io.jxcore.node.IncomingSocketThread: close: Stopping receiving thread...
03-31 13:00:48.981 11224 11826 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 1575
03-31 13:00:48.981 11224 11826 D io.jxcore.node.IncomingSocketThread: close: Stopping sending thread...
03-31 13:00:48.981 11224 11826 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 1574
03-31 13:00:48.981 11224 11826 D io.jxcore.node.IncomingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 1573)
03-31 13:00:48.981 11224 11826 I io.jxcore.node.IncomingSocketThread: close: Complete (thread ID: 1573)
,03-31 13:00:48.981 11224 11826 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left,
03-31 13:00:48.981 11224 11826 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1574, name: Sender)
03-31 13:00:48.981 11224 11827 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 1575, thread name: Receiver): bt socket closed, read return: -1
03-31 13:00:48.981 11224 11827 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1575, name: Receiver)
,03-31 13:00:48.991 11224 11287 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements,
03-31 13:00:48.991 11224 11287 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
03-31 13:00:48.991 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-31 13:00:48.991 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-31 13:00:48.991  5893  5987 D BtGatt.GattService: stopScan() - queue size =1,
03-31 13:00:48.996  5893  5979 D BtGatt.ScanManager: filter size is 1
03-31 13:00:48.996  5893  5979 D BtGatt.ScanManager: delete FilterIndex - 14
03-31 13:00:48.996  5893  5958 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16,
,03-31 13:00:48.996  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
03-31 13:00:48.996  5893  5979 D BtGatt.ScanManager: stopping BLe Batch
03-31 13:00:48.996  5893  5958 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-31 13:00:48.996  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 13:00:48.996  5893  5979 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-31 13:00:48.996  5893  5958 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-31 13:00:48.996  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 13:00:49.001  5893  8993 D BtGatt.GattService: unregisterClient() - clientIf=6,
03-31 13:00:49.006 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 13:00:49.006 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-31 13:00:49.006 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-31 13:00:49.006 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING],
,03-31 13:00:49.006 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-31 13:00:49.006 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 13:00:49.006 11224 11224 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-31 13:00:49.006 11224 11224 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-31 13:00:49.006 11224 11224 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed,
,03-31 13:00:49.016 11224 11287 I jxcore-log: INFO thaliMobileNativeWrapper: incomingConnectionToPortNumberFailed: %s
03-31 13:00:49.016 11224 11287 I jxcore-log: 
,03-31 13:00:49.021 11224 11287 I jxcore-log: INFO thaliMobileNativeWrapper: got incomingConnectionToPortNumberFailed while not in start
03-31 13:00:49.021 11224 11287 I jxcore-log: 
,03-31 13:00:49.021 11224 11287 I jxcore-log: ok 173 Should be able to call stopListeningForAdvertisments in teardown
03-31 13:00:49.021 11224 11287 I jxcore-log: 
,03-31 13:00:49.021 11224 11287 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-31 13:00:49.021 11224 11287 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> F8:CF:C5:D9:E5:61]
03-31 13:00:49.021 11224 11287 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1576)
,03-31 13:00:49.021 11224 11287 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 1576)
03-31 13:00:49.021 11224 11287 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@53f4da3, channel: 5, state: CONNECTED
03-31 13:00:49.021 11224 11287 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@53f4da3, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@34ade8a0, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@36acfc59mSocket: android.net.LocalSocket@260c01e impl:android.net.LocalSocketImpl@32ef20ff fd:FileDescriptor[118]
,03-31 13:00:49.021 11224 11287 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@260c01e impl:android.net.LocalSocketImpl@32ef20ff fd:FileDescriptor[118]
03-31 13:00:49.021 11224 11287 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@53f4da3, channel: 5, state: CLOSED
03-31 13:00:49.021 11224 11287 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@53f4da3, channel: 5, state: CLOSED
03-31 13:00:49.021 11224 11287 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
,03-31 13:00:49.021 11224 11287 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Nothing to close (thread ID: 1576)
03-31 13:00:49.021 11224 11287 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1576)
03-31 13:00:49.021  5893  6021 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 13:00:49.026 11224 11828 D io.jxcore.node.OutgoingSocketThread: Exiting thread (ID: 1576)
03-31 13:00:49.026  5893  6021 D IOP_DB_BT: db_query: result 1
,03-31 13:00:49.026  5893  6021 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 13:00:49.026  5893  6021 D IOP_DB_BT: db_query: result 1
03-31 13:00:49.026 11224 11287 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-31 13:00:49.026 11224 11287 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-31 13:00:49.026 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-31 13:00:49.026 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,03-31 13:00:49.026 11224 11287 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1018eecc, channel: 6, state: LISTENING
03-31 13:00:49.026 11224 11287 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1018eecc, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3eeac370, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@31280515mSocket: android.net.LocalSocket@22d4c02a impl:android.net.LocalSocketImpl@319ece1b fd:FileDescriptor[122]
03-31 13:00:49.026 11224 11287 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@22d4c02a impl:android.net.LocalSocketImpl@319ece1b fd:FileDescriptor[122]
03-31 13:00:49.026 11224 11287 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-31 13:00:49.026 11224 11726 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-31 13:00:49.026 11224 11726 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-31 13:00:49.026 11224 11726 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-31 13:00:49.026 11224 11224 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-31 13:00:49.026 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-31 13:00:49.026 11224 11224 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-31 13:00:49.026 11224 11224 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-31 13:00:49.026 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-31 13:00:49.026 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-31 13:00:49.026 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-31 13:00:49.026 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-31 13:00:49.026 11224 11287 D BluetoothLeScanner: could not find callback wrapper
03-31 13:00:49.026 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 13:00:49.026 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-31 13:00:49.031  5893  5978 D BtGatt.AdvertiseManager: message : 1
,03-31 13:00:49.031  5893  5978 D BtGatt.AdvertiseManager: stop advertise for client 7
03-31 13:00:49.031  5893  5978 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
,03-31 13:00:49.031  5893  5978 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,03-31 13:00:49.031  5893  5958 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-31 13:00:49.031  5893  5958 D BtGatt.GattService: Client app is not null!
,03-31 13:00:49.031  5893  8993 D BtGatt.GattService: unregisterClient() - clientIf=7
,03-31 13:00:49.036 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 13:00:49.036 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-31 13:00:49.036 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-31 13:00:49.036 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-31 13:00:49.036 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-31 13:00:49.036 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 13:00:49.036 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,03-31 13:00:49.036 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-31 13:00:49.036 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-31 13:00:49.036 11224 11287 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-31 13:00:49.036 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 13:00:49.036 11224 11224 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 13:00:49.036 11224 11224 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 13:00:49.036 11224 11224 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 13:00:49.036 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 13:00:49.036 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-31 13:00:49.036 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-31 13:00:49.036 11224 11287 I jxcore-log: 
,03-31 13:00:49.041 11224 11287 I jxcore-log: ok 174 Should be able to call stopAdvertisingAndListening in teardown
03-31 13:00:49.041 11224 11287 I jxcore-log: 
,03-31 13:00:49.041 11224 11224 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-31 13:00:49.046 11224 11287 I jxcore-log: # setup
03-31 13:00:49.046 11224 11287 I jxcore-log: 
,03-31 13:00:49.046 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
,03-31 13:00:49.046 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-31 13:00:49.046 11224 11224 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 13:00:49.051 11224 11224 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-31 13:00:49.051 11224 11224 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 13:00:49.051 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 13:00:49.051 11224 11287 I jxcore-log: 
,03-31 13:00:49.051 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 13:00:49.051 11224 11287 I jxcore-log: 
,03-31 13:00:49.176  5893  6021 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0xf):jv handle:0x0 not FOUND,
,03-31 13:00:49.176  5893  6021 E bt-btif : bta_jv_port_mgmt_sr_cback, p_cb:0x0, p_cb->p_cback0x0,
,03-31 13:00:49.201  5893  6021 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0x12):jv handle:0x0 not FOUND,
,03-31 13:00:49.201  5893  6021 E bt-btif : bta_jv_port_mgmt_sr_cback, p_cb:0x0, p_cb->p_cback0x0,
,03-31 13:00:49.201  5893  6021 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0x10):jv handle:0x0 not FOUND,
,03-31 13:00:49.296 11224 11287 I jxcore-log: # 41. Can shift large amounts of data
03-31 13:00:49.296 11224 11287 I jxcore-log: 
,03-31 13:00:49.536 11224 11287 I io.jxcore.node.ConnectionHelper: start: Port number: 41471, start advertisements: true
,03-31 13:00:49.536 11224 11287 I io.jxcore.node.ConnectionHelper: restoreDefaultBleDiscoverySettings: Powering the BLE discovery back up
03-31 13:00:49.536 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 0 -> 2
,03-31 13:00:49.541 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-31 13:00:49.541 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 13:00:49.541 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-31 13:00:49.541 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-31 13:00:49.541 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-31 13:00:49.541 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-31 13:00:49.541 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 1, timeout: 0, is connectable: false
,03-31 13:00:49.541 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-31 13:00:49.541 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 1 -> 3
,03-31 13:00:49.546 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-31 13:00:49.546 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 13:00:49.546 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-31 13:00:49.546 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-31 13:00:49.546 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-31 13:00:49.546 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-31 13:00:49.546 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-31 13:00:49.551 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
,03-31 13:00:49.551 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 0 -> 2
03-31 13:00:49.551 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-31 13:00:49.551 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 13:00:49.551 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-31 13:00:49.551 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-31 13:00:49.551 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-31 13:00:49.551 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-31 13:00:49.551 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-31 13:00:49.551 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 13:00:49.551 11224 11287 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 13:00:49.551 11224 11287 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-31 13:00:49.551 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-31 13:00:49.556 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-31 13:00:49.556 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 13:00:49.556 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 13:00:49.556 11224 11287 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 13:00:49.561  5893  8993 D BtGatt.GattService: registerClient() - UUID=4a1dd9e7-f378-4b33-9ac8-8a641af16bc7
,03-31 13:00:49.601  5893  5958 D BtGatt.GattService: onClientRegistered() - UUID=4a1dd9e7-f378-4b33-9ac8-8a641af16bc7, clientIf=6
,03-31 13:00:49.601 11224 11234 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-31 13:00:49.601  5893  5903 D BtGatt.GattService: start scan with filters
,03-31 13:00:49.616  5893  5903 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 56
,03-31 13:00:49.616 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 13:00:49.616 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 13:00:49.616 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-31 13:00:49.616 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 13:00:49.616 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 13:00:49.616  5893  5979 D BtGatt.ScanManager: handling starting scan
,03-31 13:00:49.616  5893  5979 D BtGatt.ScanManager: isFilteringSupported
03-31 13:00:49.616  5893  5979 D BluetoothAdapter: setting StandAloneBleMode
03-31 13:00:49.616 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 13:00:49.616 11224 11224 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 13:00:49.616 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-31 13:00:49.616 11224 11287 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-31 13:00:49.616 11224 11287 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 13:00:49.616 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 13:00:49.616 11224 11287 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-31 13:00:49.616  5893  5958 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-31 13:00:49.616  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 13:00:49.616  5893  5979 D BtGatt.ScanManager: allow scan with filters
,03-31 13:00:49.616  5893  5979 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-31 13:00:49.616  5893  5979 D BtGatt.ScanManager: set filter index= 15 for clientIf= 6
,03-31 13:00:49.621  5893  5958 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,03-31 13:00:49.621  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 13:00:49.621  5893  5979 D BtGatt.ScanManager: Starting BLE batch scan
03-31 13:00:49.621  5893  5979 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-31 13:00:49.621  5893  5903 D BtGatt.GattService: registerClient() - UUID=445849e4-0eb2-4280-8988-05fc0d90eca3
,03-31 13:00:49.621  5893  5958 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-31 13:00:49.621  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 13:00:49.626  5893  5958 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,03-31 13:00:49.626  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 13:00:49.661  5893  5958 D BtGatt.GattService: onClientRegistered() - UUID=445849e4-0eb2-4280-8988-05fc0d90eca3, clientIf=7
,03-31 13:00:49.661 11224 11233 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-31 13:00:49.686  5893  5905 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 45
,03-31 13:00:49.686  5893  5978 D BtGatt.AdvertiseManager: message : 0
,03-31 13:00:49.686  5893  5978 D BtGatt.AdvertiseManager: number of adv instance running0
03-31 13:00:49.686  5893  5978 D BtGatt.AdvertiseManager: size of list is =0
,03-31 13:00:49.691  5893  5978 D BtGatt.AdvertiseManager: starting advertising
03-31 13:00:49.691  5893  5978 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-31 13:00:49.696  5893  5958 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-31 13:00:49.701  5893  5978 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 13:00:49.701  5893  5958 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-31 13:00:49.701  5893  5978 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,03-31 13:00:49.706  5893  5978 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,03-31 13:00:49.706 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING,
03-31 13:00:49.706 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-31 13:00:49.711 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 13:00:49.711 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK,
03-31 13:00:49.711 11224 11287 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-31 13:00:49.711 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-31 13:00:49.711 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-31 13:00:49.716 11224 11287 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,03-31 13:00:49.716 11224 11287 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,03-31 13:00:49.716 11224 11287 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-31 13:00:49.716 11224 11224 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-31 13:00:49.716 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 13:00:49.716 11224 11224 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,03-31 13:00:49.716 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-31 13:00:49.716 11224 11224 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-31 13:00:49.716 11224 11224 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-31 13:00:49.716 11224 11224 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 13:00:49.716 11224 11224 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-31 13:00:49.716 11224 11224 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-31 13:00:49.716 11224 11224 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 13:00:49.716 11224 11224 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-31 13:00:49.716 11224 11224 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-31 13:00:49.721 11224 11287 I io.jxcore.node.ConnectionHelper: start: OK,
03-31 13:00:49.721 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 13:00:49.721 11224 11287 I jxcore-log: 
03-31 13:00:49.721 11224 11287 I jxcore-log: ok 175 Can call startUpdateAdvertisingAndListening without error
03-31 13:00:49.721 11224 11287 I jxcore-log: 
,03-31 13:00:49.731 11224 11845 D BluetoothSocket: bindListen(): myUserId = 0
,03-31 13:00:49.731 11224 11845 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-31 13:00:49.731 11224 11845 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[93]}
,03-31 13:00:49.731 11224 11845 D BluetoothSocket: bindListen(), new LocalSocket 
03-31 13:00:49.731 11224 11845 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-31 13:00:49.731 11224 11845 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@18d230f7
03-31 13:00:49.731 11224 11845 D BluetoothSocket: channel: 6
03-31 13:00:49.731 11224 11845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-31 13:00:49.736 11224 11287 I io.jxcore.node.ConnectionHelper: start: Port number: 41471, start advertisements: false,
03-31 13:00:49.736 11224 11287 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-31 13:00:49.736 11224 11287 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
03-31 13:00:49.736 11224 11287 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 13:00:49.736 11224 11287 I io.jxcore.node.ConnectionHelper: start: OK
,03-31 13:00:49.741 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 13:00:49.741 11224 11287 I jxcore-log: 
,03-31 13:00:49.741 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-31 13:00:49.741 11224 11287 I jxcore-log: 
,03-31 13:00:49.746 11224 11287 I jxcore-log: ok 176 Can call startListeningForAdvertisements without error
03-31 13:00:49.746 11224 11287 I jxcore-log: 
,03-31 13:00:50.626  3461  3617 V AlarmManager: waitForAlarm result :4
,03-31 13:00:50.646  5893  5893 D BtGatt.ScanManager: awakened up at time 251742
,03-31 13:00:50.651  5893  5979 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-31 13:00:50.656  5893  5958 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
03-31 13:00:50.656  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 13:00:50.656  5893  5958 D BtGatt.GattService: current time is 251752129737
03-31 13:00:50.656  5893  5958 D BtGatt.GattService: Batch record : [90, -90, -68, -123, 34, 80, 1, -128, -72, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -17, -107, 32, 81, -102, 64, 1, -128, -54, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0]
03-31 13:00:50.656  5893  5958 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-31 13:00:50.656  5893  5958 D ScanRecord: parseFromBytes
03-31 13:00:50.656  5893  5958 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-31 13:00:50.656  5893  5958 D ScanRecord: parseFromBytes
03-31 13:00:50.656  5893  5958 D BtGatt.GattService: result: ScanResult{mDevice=40:9A:51:20:95:EF, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-54, mTimestampNanos=251702317737}
03-31 13:00:50.656  5893  5958 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-31 13:00:50.656  5893  5958 D BtGatt.GattService: result: ScanResult{mDevice=50:22:85:BC:A6:5A, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-72, mTimestampNanos=251702317737}
03-31 13:00:50.656  5893  5958 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-31 13:00:50.656 11224 11234 D ScanRecord: parseFromBytes
03-31 13:00:50.656 11224 11234 D ScanRecord: parseFromBytes
03-31 13:00:50.656 11224 11224 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:CF:C5:D9:E5:61], added - the peer count is 1
03-31 13:00:50.661 11224 11224 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 2
03-31 13:00:50.661 11224 11224 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:CF:C5:D9:E5:61], Bluetooth address: F8:CF:C5:D9:E5:61, device name: , device address: 
03-31 13:00:50.661 11224 11224 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
,03-31 13:00:50.681 11224 11287 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID F8:CF:C5:D9:E5:61
,03-31 13:00:50.681 11224 11287 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> F8:CF:C5:D9:E5:61]
,03-31 13:00:50.681 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to Nexus 6 in address F8:CF:C5:D9:E5:61
,03-31 13:00:50.681 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
03-31 13:00:50.686 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,03-31 13:00:50.686 11224 11287 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: Nexus 6 F8:CF:C5:D9:E5:61
03-31 13:00:50.686 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to Nexus 6 in address F8:CF:C5:D9:E5:61
03-31 13:00:50.686 11224 11287 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: F8:CF:C5:D9:E5:61)
,03-31 13:00:50.686 11224 11852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address F8:CF:C5:D9:E5:61 (thread ID: 1578)
,03-31 13:00:50.696 11224 11852 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
03-31 13:00:50.696 11224 11852 D BluetoothSocket: connect(): myUserId = 0
03-31 13:00:50.696 11224 11852 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-31 13:00:50.696  5893  5905 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
03-31 13:00:50.696 11224 11852 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[118]}
,03-31 13:00:51.111  5893  6021 W bt-sdp  : process_service_search_attr_rsp
,03-31 13:00:51.566  3461  3867 E Watchdog: !@Sync 8 [03-31 13:00:51.567]
,03-31 13:00:51.671  3461  3617 V AlarmManager: waitForAlarm result :4
,03-31 13:00:51.686  5893  5893 D BtGatt.ScanManager: awakened up at time 252780
,03-31 13:00:51.691  5893  5979 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-31 13:00:51.696  5893  5958 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=3
03-31 13:00:51.696  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 13:00:51.696  5893  5958 D BtGatt.GattService: current time is 252794812362
03-31 13:00:51.696  5893  5958 D BtGatt.GattService: Batch record : [90, -90, -68, -123, 34, 80, 1, -128, -72, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -17, -107, 32, 81, -102, 64, 1, -128, -54, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0, 90, -90, -68, -123, 34, 80, 1, -128, -73, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-31 13:00:51.701  5893  5958 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81],
03-31 13:00:51.701  5893  5958 D ScanRecord: parseFromBytes,
03-31 13:00:51.701  5893  5958 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-31 13:00:51.701  5893  5958 D ScanRecord: parseFromBytes
03-31 13:00:51.701  5893  5958 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-31 13:00:51.701  5893  5958 D ScanRecord: parseFromBytes
03-31 13:00:51.701  5893  5958 D BtGatt.GattService: result: ScanResult{mDevice=40:9A:51:20:95:EF, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-54, mTimestampNanos=252645118112}
03-31 13:00:51.701  5893  5958 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null],
,03-31 13:00:51.701  5893  5958 D BtGatt.GattService: result: ScanResult{mDevice=50:22:85:BC:A6:5A, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-73, mTimestampNanos=252795118112}
03-31 13:00:51.701  5893  5958 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-31 13:00:51.701  5893  5958 D BtGatt.GattService: result: ScanResult{mDevice=50:22:85:BC:A6:5A, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-72, mTimestampNanos=252695118112}
,03-31 13:00:51.701  5893  5958 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 13:00:51.701 11224 11233 D ScanRecord: parseFromBytes
,03-31 13:00:51.701 11224 11233 D ScanRecord: parseFromBytes
03-31 13:00:51.701 11224 11233 D ScanRecord: parseFromBytes
03-31 13:00:51.701 11224 11224 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:CF:C5:D9:E5:61] updated - the peer count is 2
03-31 13:00:51.701 11224 11224 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
03-31 13:00:51.701 11224 11224 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
,03-31 13:00:51.951  5893  6021 W bt-btif : new conn_srvc id:26, app_id:1
03-31 13:00:51.951  5893  6021 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
03-31 13:00:51.951  5893  6021 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:1
03-31 13:00:51.951  5893  6021 W bt-btif : bta_dm_pm_ssr:2, lat:1200
,03-31 13:00:51.966  5893  8993 E BluetoothRemoteDevices: setRfcommConnected true,
,03-31 13:00:51.991 11224 11852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onSocketConnected: [<no peer name> F8:CF:C5:D9:E5:61] (thread ID: 1578)
,03-31 13:00:51.991 11224 11852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 1578)
,03-31 13:00:52.006 11224 11852 D BluetoothSocket: getInputStream(): myUserId = 0
,03-31 13:00:52.016 11224 11852 D BluetoothSocket: getOutputStream(): myUserId = 0
,03-31 13:00:52.021 11224 11852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesWritten: 15 bytes successfully written (thread ID: 1579)
03-31 13:00:52.021 11224 11852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Outgoing connection initialized (*handshake* thread ID: 1579)
03-31 13:00:52.021  5893  6021 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 13:00:52.021 11224 11852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1578)
03-31 13:00:52.021  5893  6021 D IOP_DB_BT: db_query: result 1
03-31 13:00:52.021  5893  6021 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 13:00:52.021  5893  6021 D IOP_DB_BT: db_query: result 1
,03-31 13:00:52.026 11224 11867 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 1579)
,03-31 13:00:52.061  5893  6021 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
,03-31 13:00:52.061 11224 11867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesRead: Read 15 bytes successfully (thread ID: 1579)
03-31 13:00:52.061  5893  6021 D IOP_DB_BT: db_query: result 1
03-31 13:00:52.061  5893  6021 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
,03-31 13:00:52.061  5893  6021 D IOP_DB_BT: db_query: result 1
,03-31 13:00:52.066 11224 11867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Handshake succeeded with [<no peer name> F8:CF:C5:D9:E5:61]
,03-31 13:00:52.066 11224 11867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onHandshakeSucceeded: [<no peer name> F8:CF:C5:D9:E5:61] (thread ID: 1578)
03-31 13:00:52.066 11224 11867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: handleSuccessfulClientThread: [<no peer name> F8:CF:C5:D9:E5:61] (thread ID: 1578)
03-31 13:00:52.071 11224 11224 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:CF:C5:D9:E5:61]
,03-31 13:00:52.071 11224 11224 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing connection to peer [<no peer name> F8:CF:C5:D9:E5:61]
03-31 13:00:52.071 11224 11224 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:CF:C5:D9:E5:61] updated - the peer count is 2
,03-31 13:00:52.071 11224 11867 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 1579)
,03-31 13:00:52.081 11224 11224 D BluetoothSocket: getInputStream(): myUserId = 0
,03-31 13:00:52.091 11224 11224 D BluetoothSocket: getOutputStream(): myUserId = 0
,03-31 13:00:52.096 11224 11224 I io.jxcore.node.ConnectionHelper: lowerBleDiscoveryPowerAndStartResetTimer: Lowering the power settings
03-31 13:00:52.096 11224 11224 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 2 -> 0
,03-31 13:00:52.106 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:,
03-31 13:00:52.106 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 13:00:52.106 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-31 13:00:52.106 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-31 13:00:52.106 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-31 13:00:52.106 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-31 13:00:52.131  5893  5978 D BtGatt.AdvertiseManager: message : 1
,03-31 13:00:52.131  5893  5978 D BtGatt.AdvertiseManager: stop advertise for client 7
03-31 13:00:52.131  5893  5978 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
,03-31 13:00:52.136  5893  5978 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,03-31 13:00:52.136  5893  5958 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-31 13:00:52.136  5893  5958 D BtGatt.GattService: Client app is not null!
,03-31 13:00:52.141  5893  5905 D BtGatt.GattService: unregisterClient() - clientIf=7
,03-31 13:00:52.146 11224 11224 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 13:00:52.146 11224 11224 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,03-31 13:00:52.151 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 3, timeout: 0, is connectable: false
,03-31 13:00:52.151 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 13:00:52.151 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-31 13:00:52.151 11224 11224 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-31 13:00:52.151 11224 11224 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 13:00:52.151 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 13:00:52.151 11224 11224 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...,
,03-31 13:00:52.161  5893  5905 D BtGatt.GattService: registerClient() - UUID=91411160-aab0-4351-90c8-8baa412b34d8,
,03-31 13:00:52.201  5893  5958 D BtGatt.GattService: onClientRegistered() - UUID=91411160-aab0-4351-90c8-8baa412b34d8, clientIf=7
03-31 13:00:52.201 11224 11234 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-31 13:00:52.211  5893  6021 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
03-31 13:00:52.211  5893  6021 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:1
03-31 13:00:52.211  5893  6021 W bt-btif : bta_dm_pm_ssr:2, lat:1200
,03-31 13:00:52.216 11224 11845 D BluetoothSocket: socket fd passed by stack  fds: [Ljava.io.FileDescriptor;@10cb6cce
03-31 13:00:52.216  5893  5903 E BluetoothRemoteDevices: setRfcommConnected true
,03-31 13:00:52.221 11224 11845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection accepted
,03-31 13:00:52.226  5893  6021 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 13:00:52.226  5893  6021 D IOP_DB_BT: db_query: result 1
03-31 13:00:52.226  5893  6021 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 13:00:52.226  5893  6021 D IOP_DB_BT: db_query: result 1
,03-31 13:00:52.231 11224 11845 D BluetoothSocket: getInputStream(): myUserId = 0
,03-31 13:00:52.236 11224 11845 D BluetoothSocket: getOutputStream(): myUserId = 0
,03-31 13:00:52.236 11224 11845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection initialized (thread ID: 1581)
,03-31 13:00:52.236 11224 11845 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@171847ef, channel: 6, state: LISTENING
,03-31 13:00:52.241 11224 11845 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@171847ef, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@18d230f7, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@d1ba2fcmSocket: android.net.LocalSocket@b555d85 impl:android.net.LocalSocketImpl@2fb587da fd:FileDescriptor[93]
,03-31 13:00:52.241  5893  5987 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 46
03-31 13:00:52.241  5893  5978 D BtGatt.AdvertiseManager: message : 0
03-31 13:00:52.241  5893  5978 D BtGatt.AdvertiseManager: number of adv instance running0
03-31 13:00:52.241  5893  5978 D BtGatt.AdvertiseManager: size of list is =0
03-31 13:00:52.246  5893  5978 D BtGatt.AdvertiseManager: starting advertising
03-31 13:00:52.246  5893  5978 D BtGatt.AdvertiseManager: isStandardAdvfalse
03-31 13:00:52.246  5893  5958 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-31 13:00:52.251  5893  5978 D BtGatt.AdvertiseManager: starting multi advertising
03-31 13:00:52.251  5893  5958 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-31 13:00:52.251  5893  5978 D BtGatt.AdvertiseManager: logClientsSet() - status: 0,
03-31 13:00:52.251  5893  5978 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 0, TxPowerLevel: 3, isConnectable: false, Timeout: 0
03-31 13:00:52.256 11224 11224 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-31 13:00:52.256  5893  8993 D BtGatt.GattService: stopScan() - queue size =1
03-31 13:00:52.256  5893  5979 D BtGatt.ScanManager: filter size is 1
03-31 13:00:52.256  5893  5979 D BtGatt.ScanManager: delete FilterIndex - 15
,03-31 13:00:52.256  5893  5905 D BtGatt.GattService: unregisterClient() - clientIf=6
03-31 13:00:52.261 11224 11224 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 13:00:52.261 11224 11224 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 13:00:52.261 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 13:00:52.261 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 13:00:52.261 11224 11224 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 13:00:52.261 11224 11224 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-31 13:00:52.261  5893  5903 D BtGatt.GattService: registerClient() - UUID=2367e84e-6e14-40ef-b0fc-5e19eace8ced
03-31 13:00:52.266  5893  5958 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,03-31 13:00:52.266  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 13:00:52.266  5893  5979 D BtGatt.ScanManager: stopping BLe Batch
,03-31 13:00:52.271  5893  5958 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-31 13:00:52.271  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 13:00:52.271  5893  5979 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-31 13:00:52.271 11224 11845 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@b555d85 impl:android.net.LocalSocketImpl@2fb587da fd:FileDescriptor[93]
,03-31 13:00:52.271 11224 11871 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 1581)
,03-31 13:00:52.271 11224 11871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesRead: Read 15 bytes successfully (thread ID: 1581)
03-31 13:00:52.271  5893  5958 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
03-31 13:00:52.271  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 13:00:52.271  5893  5958 D BtGatt.GattService: current time is 253368315570
03-31 13:00:52.271  5893  5958 D BtGatt.GattService: Batch record : [-17, -107, 32, 81, -102, 64, 1, -128, -54, 9, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0, 90, -90, -68, -123, 34, 80, 1, -128, -73, 9, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-31 13:00:52.271  5893  5958 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-31 13:00:52.271  5893  5958 D ScanRecord: parseFromBytes
03-31 13:00:52.271  5893  5958 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81],
03-31 13:00:52.271  5893  5958 D ScanRecord: parseFromBytes
,03-31 13:00:52.276 11224 11845 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed,
,03-31 13:00:52.276 11224 11871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Got valid identity from [<no peer name> F8:CF:C5:D9:E5:61]
03-31 13:00:52.276 11224 11845 D BluetoothSocket: bindListen(): myUserId = 0
,03-31 13:00:52.276 11224 11845 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-31 13:00:52.276 11224 11871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesWritten: 15 bytes successfully written (thread ID: 1581)
,03-31 13:00:52.276  5893  6021 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 13:00:52.276 11224 11871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: removeThreadFromList: Removing thread with ID 1581
03-31 13:00:52.276 11224 11871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Handshake thread disposed (thread ID: 1581)
,03-31 13:00:52.276 11224 11871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onIncomingConnectionConnected: [<no peer name> F8:CF:C5:D9:E5:61]
03-31 13:00:52.276 11224 11871 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 1581)
03-31 13:00:52.276  5893  6021 D IOP_DB_BT: db_query: result 1
03-31 13:00:52.276  5893  6021 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 13:00:52.276  5893  6021 D IOP_DB_BT: db_query: result 1
,03-31 13:00:52.281 11224 11845 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[119]},
03-31 13:00:52.281 11224 11845 D BluetoothSocket: bindListen(), new LocalSocket 
03-31 13:00:52.281 11224 11845 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-31 13:00:52.281 11224 11845 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@c4b740b
03-31 13:00:52.281 11224 11845 D BluetoothSocket: channel: 6
03-31 13:00:52.281 11224 11845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-31 13:00:52.301  5893  5958 D BtGatt.GattService: onClientRegistered() - UUID=2367e84e-6e14-40ef-b0fc-5e19eace8ced, clientIf=6
,03-31 13:00:52.306 11224 11280 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-31 13:00:52.306  5893  5987 D BtGatt.GattService: start scan with filters
,03-31 13:00:52.311  5893  5987 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 57
,03-31 13:00:52.316 11224 11224 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 13:00:52.316 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 13:00:52.316 11224 11224 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 3 -> 1
03-31 13:00:52.316  5893  5979 D BtGatt.ScanManager: handling starting scan
03-31 13:00:52.316  5893  5979 D BtGatt.ScanManager: isFilteringSupported
03-31 13:00:52.316  5893  5979 D BluetoothAdapter: setting StandAloneBleMode
03-31 13:00:52.316 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-31 13:00:52.316 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 13:00:52.316 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-31 13:00:52.316 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-31 13:00:52.316 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-31 13:00:52.316 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-31 13:00:52.316  5893  5978 D BtGatt.AdvertiseManager: message : 1
03-31 13:00:52.316  5893  5958 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-31 13:00:52.316  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 13:00:52.316  5893  5979 D BtGatt.ScanManager: allow scan with filters
03-31 13:00:52.316  5893  5979 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-31 13:00:52.316  5893  5979 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,03-31 13:00:52.316  5893  5978 D BtGatt.AdvertiseManager: stop advertise for client 7
03-31 13:00:52.316  5893  5978 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-31 13:00:52.316  5893  5978 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-31 13:00:52.316  5893  5958 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-31 13:00:52.316  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 13:00:52.316  5893  5979 D BtGatt.ScanManager: Starting BLE batch scan
03-31 13:00:52.316  5893  5979 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-31 13:00:52.321  5893  5958 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-31 13:00:52.321  5893  5958 D BtGatt.GattService: Client app is not null!
,03-31 13:00:52.321  5893  5903 D BtGatt.GattService: unregisterClient() - clientIf=7
,03-31 13:00:52.321 11224 11224 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 13:00:52.321 11224 11224 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-31 13:00:52.321 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-31 13:00:52.321 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 13:00:52.321 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-31 13:00:52.321 11224 11224 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-31 13:00:52.321 11224 11224 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 13:00:52.321 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-31 13:00:52.321  5893  5958 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-31 13:00:52.321 11224 11224 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-31 13:00:52.321  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 13:00:52.326  5893  5958 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-31 13:00:52.326  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 13:00:52.326  5893  5903 D BtGatt.GattService: registerClient() - UUID=43699675-5e0a-411d-86f0-e97fcf104e65
,03-31 13:00:52.366  5893  5958 D BtGatt.GattService: onClientRegistered() - UUID=43699675-5e0a-411d-86f0-e97fcf104e65, clientIf=7
,03-31 13:00:52.366 11224 11233 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-31 13:00:52.386  5893  6021 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 13:00:52.386  5893  5987 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 47
03-31 13:00:52.386  5893  6021 D IOP_DB_BT: db_query: result 1
03-31 13:00:52.386  5893  6021 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 13:00:52.391  5893  6021 D IOP_DB_BT: db_query: result 1
03-31 13:00:52.391  5893  5978 D BtGatt.AdvertiseManager: message : 0
,03-31 13:00:52.391  5893  5978 D BtGatt.AdvertiseManager: number of adv instance running0
03-31 13:00:52.391  5893  5978 D BtGatt.AdvertiseManager: size of list is =0
,03-31 13:00:52.391  5893  5978 D BtGatt.AdvertiseManager: starting advertising
03-31 13:00:52.396  5893  5978 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-31 13:00:52.396  5893  5958 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0,
,03-31 13:00:52.401  5893  5978 D BtGatt.AdvertiseManager: starting multi advertising,
03-31 13:00:52.406  5893  5958 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
03-31 13:00:52.406  5893  5978 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-31 13:00:52.406  5893  5978 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 0, TxPowerLevel: 1, isConnectable: false, Timeout: 0
03-31 13:00:52.406 11224 11224 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-31 13:00:52.411  5893  5905 D BtGatt.GattService: stopScan() - queue size =1
03-31 13:00:52.411  5893  5979 D BtGatt.ScanManager: filter size is 1
03-31 13:00:52.411  5893  5979 D BtGatt.ScanManager: delete FilterIndex - 3
03-31 13:00:52.411  5893  5958 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,03-31 13:00:52.411  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 13:00:52.411  5893  5903 D BtGatt.GattService: unregisterClient() - clientIf=6,
03-31 13:00:52.416  5893  5979 D BtGatt.ScanManager: stopping BLe Batch,
,03-31 13:00:52.416 11224 11224 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
03-31 13:00:52.416 11224 11224 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED,
03-31 13:00:52.416  5893  5958 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0,
,03-31 13:00:52.416  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,03-31 13:00:52.421  5893  5979 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-31 13:00:52.421 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 13:00:52.421 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-31 13:00:52.421 11224 11224 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-31 13:00:52.421 11224 11224 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-31 13:00:52.426  5893  6021 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
,03-31 13:00:52.431  5893  6021 D IOP_DB_BT: db_query: result 1
03-31 13:00:52.431  5893  6021 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 13:00:52.431  5893  6021 D IOP_DB_BT: db_query: result 1,
03-31 13:00:52.431  5893  5958 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
03-31 13:00:52.431  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 13:00:52.431  5893  5958 D BtGatt.GattService: current time is 253529008445
,03-31 13:00:52.431  5893  5958 D BtGatt.GattService: Batch record : [90, -90, -68, -123, 34, 80, 1, -128, -72, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-31 13:00:52.431  5893  5958 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81],
03-31 13:00:52.431  5893  5958 D ScanRecord: parseFromBytes
03-31 13:00:52.436  5893  6021 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
,03-31 13:00:52.436  5893  6021 D IOP_DB_BT: db_query: result 1
,03-31 13:00:52.436  5893  6021 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 13:00:52.436  5893  6021 D IOP_DB_BT: db_query: result 1
,03-31 13:00:52.436  5893  6021 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 13:00:52.436  5893  6021 D IOP_DB_BT: db_query: result 1,
03-31 13:00:52.436  5893  6021 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 13:00:52.436  5893  6021 D IOP_DB_BT: db_query: result 1
,03-31 13:00:52.436  5893  6021 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 13:00:52.441  5893  6021 D IOP_DB_BT: db_query: result 1
,03-31 13:00:52.441  5893  6021 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 13:00:52.441  5893  6021 D IOP_DB_BT: db_query: result 1
,03-31 13:00:52.446  5893  5903 D BtGatt.GattService: registerClient() - UUID=3a6e46a2-0b7c-4f31-bcfb-3c492296ea6a
,03-31 13:00:52.486  5893  5958 D BtGatt.GattService: onClientRegistered() - UUID=3a6e46a2-0b7c-4f31-bcfb-3c492296ea6a, clientIf=6,
,03-31 13:00:52.491 11224 11234 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-31 13:00:52.491  5893  5987 D BtGatt.GattService: start scan with filters
,03-31 13:00:52.511  5893  5987 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 58
,03-31 13:00:52.511  5893  5979 D BtGatt.ScanManager: handling starting scan,
03-31 13:00:52.511  5893  5979 D BtGatt.ScanManager: isFilteringSupported
03-31 13:00:52.511  5893  5979 D BluetoothAdapter: setting StandAloneBleMode
,03-31 13:00:52.516  5893  5958 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-31 13:00:52.516  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 13:00:52.521  5893  5979 D BtGatt.ScanManager: allow scan with filters
03-31 13:00:52.521  5893  5979 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-31 13:00:52.521  5893  5979 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
03-31 13:00:52.521  5893  5958 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-31 13:00:52.521  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 13:00:52.526  5893  5979 D BtGatt.ScanManager: Starting BLE batch scan,
,03-31 13:00:52.526  5893  5979 D BtGatt.ScanManager: configuring batch scan storage, appIf 6,
03-31 13:00:52.526  5893  5958 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,03-31 13:00:52.526  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 13:00:52.531  5893  5958 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,03-31 13:00:52.531  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,03-31 13:00:52.536 11224 11224 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 13:00:52.536 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 13:00:52.536 11224 11224 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 2 -> 0
03-31 13:00:52.536 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:,
03-31 13:00:52.536 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 13:00:52.536 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-31 13:00:52.536 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-31 13:00:52.536 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-31 13:00:52.536 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-31 13:00:52.541  5893  5978 D BtGatt.AdvertiseManager: message : 1
03-31 13:00:52.541  5893  5978 D BtGatt.AdvertiseManager: stop advertise for client 7
03-31 13:00:52.541  5893  5978 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
,03-31 13:00:52.541  5893  5978 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-31 13:00:52.541  5893  5958 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-31 13:00:52.541  5893  5958 D BtGatt.GattService: Client app is not null!
03-31 13:00:52.541  5893  5903 D BtGatt.GattService: unregisterClient() - clientIf=7
03-31 13:00:52.546 11224 11224 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 13:00:52.546 11224 11224 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-31 13:00:52.546 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
,03-31 13:00:52.546 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 13:00:52.546 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-31 13:00:52.546 11224 11224 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-31 13:00:52.546 11224 11224 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 13:00:52.546 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 13:00:52.546 11224 11224 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-31 13:00:52.551  5893  8993 D BtGatt.GattService: registerClient() - UUID=4231a80b-d162-46f7-ab9e-f769d9303152
,03-31 13:00:52.591  5893  5958 D BtGatt.GattService: onClientRegistered() - UUID=4231a80b-d162-46f7-ab9e-f769d9303152, clientIf=7
,03-31 13:00:52.591 11224 11280 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-31 13:00:52.606  5893  5905 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 48
,03-31 13:00:52.606  5893  5978 D BtGatt.AdvertiseManager: message : 0
03-31 13:00:52.606  5893  5978 D BtGatt.AdvertiseManager: number of adv instance running0
03-31 13:00:52.606  5893  5978 D BtGatt.AdvertiseManager: size of list is =0
,03-31 13:00:52.606  5893  5978 D BtGatt.AdvertiseManager: starting advertising
03-31 13:00:52.606  5893  5978 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-31 13:00:52.611  5893  5958 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-31 13:00:52.611  5893  5978 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 13:00:52.611  5893  5958 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
03-31 13:00:52.611  5893  5978 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-31 13:00:52.611  5893  5978 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 0, TxPowerLevel: 1, isConnectable: false, Timeout: 0
,03-31 13:00:52.611 11224 11224 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-31 13:00:52.616  5893  5987 D BtGatt.GattService: stopScan() - queue size =1,
03-31 13:00:52.616  5893  5979 D BtGatt.ScanManager: filter size is 1
,03-31 13:00:52.616  5893  5979 D BtGatt.ScanManager: delete FilterIndex - 4
03-31 13:00:52.616  5893  8993 D BtGatt.GattService: unregisterClient() - clientIf=6
03-31 13:00:52.616 11224 11224 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 13:00:52.616 11224 11224 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 13:00:52.616 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-31 13:00:52.616 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 13:00:52.616  5893  5958 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-31 13:00:52.616 11224 11224 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 13:00:52.616  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 13:00:52.616 11224 11224 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 13:00:52.616  5893  5979 D BtGatt.ScanManager: stopping BLe Batch
,03-31 13:00:52.621  5893  5958 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,03-31 13:00:52.621  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 13:00:52.621  5893  5979 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-31 13:00:52.621  5893  5958 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
,03-31 13:00:52.621  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 13:00:52.621  5893  5958 D BtGatt.GattService: current time is 253718505528
03-31 13:00:52.621  5893  5958 D BtGatt.GattService: Batch record : [90, -90, -68, -123, 34, 80, 1, -128, -72, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-31 13:00:52.621  5893  5958 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-31 13:00:52.621  5893  5958 D ScanRecord: parseFromBytes
,03-31 13:00:52.621  5893  8993 D BtGatt.GattService: registerClient() - UUID=2b71dfc5-2dd4-402a-8908-fc0ad71f7eac
,03-31 13:00:52.666  5893  5958 D BtGatt.GattService: onClientRegistered() - UUID=2b71dfc5-2dd4-402a-8908-fc0ad71f7eac, clientIf=6
,03-31 13:00:52.666 11224 11233 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-31 13:00:52.666  5893  5905 D BtGatt.GattService: start scan with filters
,03-31 13:00:52.691  5893  5905 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 59
,03-31 13:00:52.696 11224 11224 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-31 13:00:52.696 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 13:00:52.696  5893  5979 D BtGatt.ScanManager: handling starting scan
,03-31 13:00:52.696 11224 11224 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing socket thread, for peer [<no peer name> F8:CF:C5:D9:E5:61], created successfully
,03-31 13:00:52.696  5893  5979 D BtGatt.ScanManager: isFilteringSupported
03-31 13:00:52.696 11224 11224 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 1
03-31 13:00:52.696  5893  5979 D BluetoothAdapter: setting StandAloneBleMode
,03-31 13:00:52.696 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-31 13:00:52.696 11224 11224 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-31 13:00:52.696 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-31 13:00:52.696 11224 11224 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:CF:C5:D9:E5:61]
03-31 13:00:52.696 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-31 13:00:52.696 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-31 13:00:52.696 11224 11224 I io.jxcore.node.ConnectionHelper: onConnected: Incoming connection to peer [<no peer name> F8:CF:C5:D9:E5:61]
03-31 13:00:52.696 11224 11224 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:CF:C5:D9:E5:61] updated - the peer count is 2
03-31 13:00:52.701 11224 11886 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1580)
,03-31 13:00:52.706 11224 11886 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 56092
03-31 13:00:52.706 11224 11886 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
03-31 13:00:52.706 11224 11886 I io.jxcore.node.ConnectionHelper: onListeningForIncomingConnections: Outgoing connection is using port 56092 (peer ID: F8:CF:C5:D9:E5:61)
03-31 13:00:52.706 11224 11886 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "F8:CF:C5:D9:E5:61" removed
03-31 13:00:52.706  5893  5958 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-31 13:00:52.706  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 13:00:52.711  5893  5979 D BtGatt.ScanManager: allow scan with filters
03-31 13:00:52.711  5893  5979 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-31 13:00:52.711  5893  5979 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
03-31 13:00:52.711  5893  5958 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15,
03-31 13:00:52.711  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 13:00:52.711  5893  5979 D BtGatt.ScanManager: Starting BLE batch scan
03-31 13:00:52.711  5893  5979 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-31 13:00:52.716 11224 11224 D BluetoothSocket: getInputStream(): myUserId = 0
,03-31 13:00:52.716  5893  5958 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,03-31 13:00:52.716  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 13:00:52.716  5893  5958 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-31 13:00:52.721  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 13:00:52.721 11224 11224 D BluetoothSocket: getOutputStream(): myUserId = 0
,03-31 13:00:52.721 11224 11224 I io.jxcore.node.ConnectionHelper: onConnected: Incoming socket thread, for peer [<no peer name> F8:CF:C5:D9:E5:61], created successfully
03-31 13:00:52.721 11224 11224 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 2
03-31 13:00:52.721 11224 11887 D io.jxcore.node.IncomingSocketThread: Entering thread (ID: 1582)
03-31 13:00:52.726  2874  3434 D EnterpriseController: netId is 0
03-31 13:00:52.726  2874  3434 D Netd    : getNetworkForDns: using netid 502 for uid 10011
03-31 13:00:52.726 11224 11287 I jxcore-log: INFO testThaliMobileNative: 
03-31 13:00:52.726 11224 11287 I jxcore-log: 
03-31 13:00:52.726 11224 11287 I jxcore-log: INFO testThaliMobileNative: Forward connection
03-31 13:00:52.726 11224 11287 I jxcore-log: 
03-31 13:00:52.726 11224 11887 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 41471
03-31 13:00:52.726 11224 11887 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
03-31 13:00:52.726 11224 11887 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-31 13:00:52.726 11224 11887 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
,03-31 13:00:52.731 11224 11889 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1583, name: Sender)
03-31 13:00:52.731 11224 11887 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 1582)
03-31 13:00:52.731 11224 11887 D io.jxcore.node.IncomingSocketThread: Exiting thread (ID: 1582)
,03-31 13:00:52.731 11224 11890 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1584, name: Receiver)
03-31 13:00:52.731 11224 11886 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 56092
03-31 13:00:52.731 11224 11886 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,03-31 13:00:52.731 11224 11886 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-31 13:00:52.731 11224 11886 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
,03-31 13:00:52.731 11224 11891 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1585, name: Sender)
,03-31 13:00:52.731 11224 11886 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1580)
03-31 13:00:52.731 11224 11886 D io.jxcore.node.OutgoingSocketThread: Exiting thread (ID: 1580)
,03-31 13:00:52.736 11224 11892 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1586, name: Receiver)
,03-31 13:00:52.741 11224 11287 I jxcore-log: INFO testThaliMobileNative: forwardSend
03-31 13:00:52.741 11224 11287 I jxcore-log: 
,03-31 13:00:52.741  5893  6021 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
,03-31 13:00:52.741  5893  6021 D IOP_DB_BT: db_query: result 1
03-31 13:00:52.741  5893  6021 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
,03-31 13:00:52.741  5893  6021 D IOP_DB_BT: db_query: result 1
,03-31 13:00:52.746  5893  6021 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
,03-31 13:00:52.746  5893  6021 D IOP_DB_BT: db_query: result 1
03-31 13:00:52.746  5893  6021 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
,03-31 13:00:52.746  5893  6021 D IOP_DB_BT: db_query: result 1
,03-31 13:00:52.776  5893  6021 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
,03-31 13:00:52.776  5893  6021 D IOP_DB_BT: db_query: result 1
,03-31 13:00:52.776  5893  6021 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 13:00:52.776  5893  6021 D IOP_DB_BT: db_query: result 1
,03-31 13:00:52.781 11224 11287 I jxcore-log: INFO testThaliMobileNative: forwardData
03-31 13:00:52.781 11224 11287 I jxcore-log: 
03-31 13:00:52.781  5893  6021 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 13:00:52.781  5893  6021 D IOP_DB_BT: db_query: result 1
03-31 13:00:52.781  5893  6021 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
,03-31 13:00:52.781  5893  6021 D IOP_DB_BT: db_query: result 1
,03-31 13:00:52.786  5893  6021 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 13:00:52.791  5893  6021 D IOP_DB_BT: db_query: result 1
03-31 13:00:52.791  5893  6021 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 13:00:52.791 11224 11287 I jxcore-log: INFO testThaliMobileNative: forwardData
03-31 13:00:52.791 11224 11287 I jxcore-log: 
,03-31 13:00:52.791  5893  6021 D IOP_DB_BT: db_query: result 1
03-31 13:00:52.791 11224 11287 I jxcore-log: INFO testThaliMobileNative: forwardData
03-31 13:00:52.791 11224 11287 I jxcore-log: 
03-31 13:00:52.796  5893  6021 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 13:00:52.796  5893  6021 D IOP_DB_BT: db_query: result 1
03-31 13:00:52.796  5893  6021 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 13:00:52.796  5893  6021 D IOP_DB_BT: db_query: result 1
03-31 13:00:52.796  5893  6021 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 13:00:52.796  5893  6021 D IOP_DB_BT: db_query: result 1
03-31 13:00:52.796  5893  6021 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 13:00:52.796  5893  6021 D IOP_DB_BT: db_query: result 1
,03-31 13:00:52.801 11224 11287 I jxcore-log: INFO testThaliMobileNative: forwardData
03-31 13:00:52.801 11224 11287 I jxcore-log: 
,03-31 13:00:52.806 11224 11287 I jxcore-log: INFO testThaliMobileNative: forwardData
03-31 13:00:52.806 11224 11287 I jxcore-log: 
,03-31 13:00:52.806 11224 11287 I jxcore-log: ok 177 received should match sent forward
03-31 13:00:52.806 11224 11287 I jxcore-log: 
,03-31 13:00:52.816 11224 11287 I jxcore-log: # teardown
03-31 13:00:52.816 11224 11287 I jxcore-log: 
,03-31 13:00:53.016  5893  6021 E bt-btm  : Reset sec_bd_name and name flag. (BR/EDR link)
03-31 13:00:53.016  5893  6021 E bt-btm  : btm_sec_disconnected - Clearing Pending flag
03-31 13:00:53.016  5893  6021 W bt-btif : bta_dm_acl_change(), event : 1
03-31 13:00:53.016  5893  6021 W bt-btif : bta_dm_acl_change(), event : 2
03-31 13:00:53.016  5893  5958 E BluetoothRemoteDevices: aclStateChangeCallback: State:DisConnected to Device:F8:95:C7:87:3C:XX
03-31 13:00:53.041  5893  5958 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
03-31 13:00:53.041  3728  3728 D KeyguardViewMediator: Received android.bluetooth.device.action.ACL_DISCONNECTED
,03-31 13:00:53.056  3461  3461 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
03-31 13:00:53.056  3461  3461 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.device.action.ACL_DISCONNECTED
,03-31 13:00:53.056  3461  3461 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_ACL_DISCONNECTED
,03-31 13:00:53.071  3461  3568 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1133ba1c u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{388a0b6d 5893:com.android.bluetooth/1002}
,03-31 13:00:53.076  5893  5893 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@be0f583
03-31 13:00:53.081  3461  4032 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
03-31 13:00:53.076  5893  5893 D BtConfig.SecureMode: isSecureModeOn:false
03-31 13:00:53.076  3461  4438 D SecContentProvider: query(), uri = 4 selection = isProfileAuthorizedBySecurityPolicy
03-31 13:00:53.081  5893  5893 I BluetoothPbapService: action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
03-31 13:00:53.086  3728  3728 D KeyguardViewMediator: isGear1: device is not B1!
,03-31 13:00:53.091  3461  4439 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 13:00:53.091  3461  4439 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 13:00:53.091  3461  4439 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 13:00:53.091  3461  4439 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-31 13:00:53.101 11899 11899 E Zygote  : MountEmulatedStorage()
03-31 13:00:53.101 11899 11899 E Zygote  : v2
03-31 13:00:53.101 11899 11899 I libpersona: KNOX_SDCARD checking this for 10036
03-31 13:00:53.101 11899 11899 I libpersona: KNOX_SDCARD not a persona
,03-31 13:00:53.106 11899 11899 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
,03-31 13:00:53.106  3461  4439 I ActivityManager: Start proc 11899:com.sec.android.app.shealth/u0a36 for broadcast-3 com.sec.android.app.shealth/com.samsung.android.app.shealth.tracker.weight.receiver.TrackerWeightReceiver
,03-31 13:00:53.106 11899 11899 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
,03-31 13:00:53.111 11899 11899 E Zygote  : accessInfo : 0
03-31 13:00:53.111 11899 11899 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-31 13:00:53.111  3461  4033 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
,03-31 13:00:53.121 10370 11909 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.ACL_DISCONNECTED State = -2147483648 Previous = -2147483648
,03-31 13:00:53.126 10370 10370 D [CarModeFW]: ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED
,03-31 13:00:53.126 10370 10370 D [CarModeFW]: ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED onNotifyBluetoothDeviceDisconnected
,03-31 13:00:53.131 10370 10370 D [CarModeFW]: ConnectivityManager-Paired Devices list is empty
03-31 13:00:53.131 10370 10370 E [CarMode]: [BluetoothConnectivityListener]-onNotifyBluetoothProfileDisconnected: Unexpected error: Invalid device
,03-31 13:00:53.131 11899 11899 D TimaKeyStoreProvider: TimaSignature is unavailable
03-31 13:00:53.136 11899 11899 D ActivityThread: Added TimaKeyStore provider
,03-31 13:00:53.141  3461  4440 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1133ba1c u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{3dc043fa 11899:com.sec.android.app.shealth/u0a36}
,03-31 13:00:53.151 11899 11899 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-31 13:00:53.246 11899 11899 D HealthConsole: Service for HealthDataConsole is connected
,03-31 13:00:53.251  3461  3968 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1133ba1c u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{3dc043fa 11899:com.sec.android.app.shealth/u0a36}
,03-31 13:00:53.271 11899 11899 D HealthConsole: Service for HealthDataConsole is connected
,03-31 13:00:53.276  3461  3833 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1133ba1c u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{3dc043fa 11899:com.sec.android.app.shealth/u0a36}
,03-31 13:00:53.291  3461  3491 I ActivityManager: Killing 10266:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): emptyCount ##31
,03-31 13:00:53.296  3461  3491 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1133ba1c u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{385670e6 4131:com.google.android.googlequicksearchbox:search/u0a64}
,03-31 13:00:53.326  4131  4131 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,03-31 13:00:53.326  4131  4131 I BluetoothClassifier: Bluetooth Device Name: G4-1
,03-31 13:00:53.721  3461  3617 V AlarmManager: waitForAlarm result :4
,03-31 13:00:53.736  5893  5893 D BtGatt.ScanManager: awakened up at time 254829,
,03-31 13:00:53.741  5893  5979 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-31 13:00:53.746  5893  5958 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-31 13:00:53.746  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 13:00:54.046  5893  6021 E bt-btm  : tBTM_SEC_DEV:0xb35230d8 rs_disc_pending=0
03-31 13:00:54.046  5893  6021 W bt-btif : bta_dm_acl_change(), event : 3
03-31 13:00:54.046  5893  6021 W bt-btif : bta_dm_check_av:0
,03-31 13:00:54.046  5893  5958 W bt-btif : btif_dm_cback : unhandled event (14)
,03-31 13:00:54.761  3461  3617 V AlarmManager: waitForAlarm result :4
,03-31 13:00:54.776  5893  5893 D BtGatt.ScanManager: awakened up at time 255870
,03-31 13:00:54.781  5893  5979 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-31 13:00:54.791  5893  5958 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-31 13:00:54.791  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 13:00:54.871  2893  4818 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-31 13:00:55.171 11224 11889 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 1583, thread name: Sender)
,03-31 13:00:55.171 11224 11889 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Input stream got -1 on read
03-31 13:00:55.171 11224 11889 W io.jxcore.node.ConnectionHelper: onDisconnected: Incoming connection, peer [<no peer name> F8:CF:C5:D9:E5:61] disconnected: Input stream got -1 on read
,03-31 13:00:55.171 11224 11889 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1582,
,03-31 13:00:55.171 11224 11889 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 1582),
,03-31 13:00:55.171 11224 11889 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@7934d01, channel: 6, state: CONNECTED
,03-31 13:00:55.171 11224 11889 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@7934d01, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2af447a6, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@83b45e7mSocket: android.net.LocalSocket@8335594 impl:android.net.LocalSocketImpl@2666b83d fd:FileDescriptor[92],
,03-31 13:00:55.171 11224 11889 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@8335594 impl:android.net.LocalSocketImpl@2666b83d fd:FileDescriptor[92]
,03-31 13:00:55.171 11224 11889 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@7934d01, channel: 6, state: CLOSED,
03-31 13:00:55.171 11224 11889 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@7934d01, channel: 6, state: CLOSED
,03-31 13:00:55.171 11224 11889 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed,
,03-31 13:00:55.171 11224 11889 D io.jxcore.node.IncomingSocketThread: close: Stopping receiving thread...
,03-31 13:00:55.171 11224 11889 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 1584
,03-31 13:00:55.171 11224 11889 D io.jxcore.node.IncomingSocketThread: close: Stopping sending thread...,
,03-31 13:00:55.171 11224 11889 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 1583
,03-31 13:00:55.171 11224 11889 D io.jxcore.node.IncomingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 1582),
,03-31 13:00:55.176 11224 11890 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 1584, thread name: Receiver): bt socket closed, read return: -1,
,03-31 13:00:55.176 11224 11890 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1584, name: Receiver)
,03-31 13:00:55.181 11224 11889 I io.jxcore.node.IncomingSocketThread: close: Complete (thread ID: 1582)
,03-31 13:00:55.181 11224 11889 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left,
,03-31 13:00:55.181 11224 11889 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1583, name: Sender),
,03-31 13:00:55.196  5893  6021 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0x15):jv handle:0x0 not FOUND
,03-31 13:00:55.196  5893  6021 E bt-btif : bta_jv_port_mgmt_sr_cback, p_cb:0x0, p_cb->p_cback0x0,
,03-31 13:00:55.201 11224 11287 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 13:00:55.201 11224 11287 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
03-31 13:00:55.201 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-31 13:00:55.201 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-31 13:00:55.206  5893  8993 D BtGatt.GattService: stopScan() - queue size =1
03-31 13:00:55.206  5893  5979 D BtGatt.ScanManager: filter size is 1
03-31 13:00:55.206  5893  5979 D BtGatt.ScanManager: delete FilterIndex - 5
,03-31 13:00:55.211  5893  5958 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-31 13:00:55.211  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 13:00:55.211  5893  5979 D BtGatt.ScanManager: stopping BLe Batch
03-31 13:00:55.211  5893  5958 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,03-31 13:00:55.211  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
03-31 13:00:55.211  5893  5979 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-31 13:00:55.211  5893  5958 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-31 13:00:55.211  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 13:00:55.211  5893  5987 D BtGatt.GattService: unregisterClient() - clientIf=6
03-31 13:00:55.216 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-31 13:00:55.216 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 13:00:55.221 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-31 13:00:55.221 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-31 13:00:55.221 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-31 13:00:55.221 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 13:00:55.221 11224 11224 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-31 13:00:55.221 11224 11224 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-31 13:00:55.221 11224 11224 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 13:00:55.221 11224 11287 I jxcore-log: INFO thaliMobileNativeWrapper: incomingConnectionToPortNumberFailed: %s
03-31 13:00:55.221 11224 11287 I jxcore-log: 
,03-31 13:00:55.226 11224 11287 I jxcore-log: INFO thaliMobileNativeWrapper: got incomingConnectionToPortNumberFailed while not in start
03-31 13:00:55.226 11224 11287 I jxcore-log: 
,03-31 13:00:55.226 11224 11287 I jxcore-log: ok 178 Should be able to call stopListeningForAdvertisments in teardown,
03-31 13:00:55.226 11224 11287 I jxcore-log: 
,03-31 13:00:55.226 11224 11287 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 13:00:55.226 11224 11287 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> F8:CF:C5:D9:E5:61],
,03-31 13:00:55.226 11224 11287 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1580)
03-31 13:00:55.226 11224 11287 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 1580)
03-31 13:00:55.231  3461  6089 D SSRM:n  : SIOP:: AP = 270, PST = 271 (W:12), CUR = 41, LCD = 0
03-31 13:00:55.226 11224 11287 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@220d3832, channel: 5, state: CONNECTED
03-31 13:00:55.226 11224 11287 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@220d3832, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2f6c5983, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@32ba3700mSocket: android.net.LocalSocket@200b9b39 impl:android.net.LocalSocketImpl@3552a57e fd:FileDescriptor[118]
03-31 13:00:55.226 11224 11287 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@200b9b39 impl:android.net.LocalSocketImpl@3552a57e fd:FileDescriptor[118]
,03-31 13:00:55.226 11224 11287 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@220d3832, channel: 5, state: CLOSED
03-31 13:00:55.226 11224 11287 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@220d3832, channel: 5, state: CLOSED
03-31 13:00:55.226 11224 11287 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-31 13:00:55.226 11224 11287 D io.jxcore.node.OutgoingSocketThread: close: Stopping receiving thread...
03-31 13:00:55.226 11224 11287 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 1586
03-31 13:00:55.226 11224 11287 D io.jxcore.node.OutgoingSocketThread: close: Stopping sending thread...
03-31 13:00:55.226 11224 11892 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 1586, thread name: Receiver): bt socket closed, read return: -1
03-31 13:00:55.226 11224 11287 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 1585
03-31 13:00:55.226 11224 11287 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 1580)
03-31 13:00:55.226 11224 11892 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1586, name: Receiver)
03-31 13:00:55.226 11224 11891 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 1585, thread name: Sender): Socket closed
03-31 13:00:55.226 11224 11891 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1585, name: Sender)
,03-31 13:00:55.226  5893  6021 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 13:00:55.231  5893  6021 D IOP_DB_BT: db_query: result 1
03-31 13:00:55.231  5893  6021 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 13:00:55.231 11224 11287 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1580)
03-31 13:00:55.231 11224 11287 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-31 13:00:55.231 11224 11287 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-31 13:00:55.231 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-31 13:00:55.231 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-31 13:00:55.231  5893  6021 D IOP_DB_BT: db_query: result 1
03-31 13:00:55.231 11224 11287 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@20110adf, channel: 6, state: LISTENING
,03-31 13:00:55.231 11224 11287 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@20110adf, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@c4b740b, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@200bc32cmSocket: android.net.LocalSocket@1a81b1f5 impl:android.net.LocalSocketImpl@25ef9b8a fd:FileDescriptor[119]
03-31 13:00:55.231 11224 11287 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1a81b1f5 impl:android.net.LocalSocketImpl@25ef9b8a fd:FileDescriptor[119]
03-31 13:00:55.231 11224 11287 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-31 13:00:55.231 11224 11845 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-31 13:00:55.231 11224 11845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-31 13:00:55.231 11224 11845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-31 13:00:55.231 11224 11224 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-31 13:00:55.231 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-31 13:00:55.231 11224 11224 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-31 13:00:55.231 11224 11224 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-31 13:00:55.231 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-31 13:00:55.231 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-31 13:00:55.231 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-31 13:00:55.231 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-31 13:00:55.231 11224 11287 D BluetoothLeScanner: could not find callback wrapper
03-31 13:00:55.231 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 13:00:55.231 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-31 13:00:55.236  5893  5978 D BtGatt.AdvertiseManager: message : 1
03-31 13:00:55.236  5893  5978 D BtGatt.AdvertiseManager: stop advertise for client 7
03-31 13:00:55.236  5893  5978 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-31 13:00:55.236  5893  5978 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-31 13:00:55.236  5893  5958 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
,03-31 13:00:55.236  5893  5958 D BtGatt.GattService: Client app is not null!
03-31 13:00:55.236  5893  5987 D BtGatt.GattService: unregisterClient() - clientIf=7
,03-31 13:00:55.241 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 13:00:55.241 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-31 13:00:55.241 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,03-31 13:00:55.241 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-31 13:00:55.241 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-31 13:00:55.241 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 13:00:55.241 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 13:00:55.241 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-31 13:00:55.241 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-31 13:00:55.241 11224 11287 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-31 13:00:55.241 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 13:00:55.241 11224 11224 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 13:00:55.241 11224 11224 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 13:00:55.241 11224 11224 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 13:00:55.241 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 13:00:55.241 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-31 13:00:55.241 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-31 13:00:55.241 11224 11287 I jxcore-log: 
,03-31 13:00:55.246 11224 11224 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-31 13:00:55.246 11224 11287 I jxcore-log: ok 179 Should be able to call stopAdvertisingAndListening in teardown
03-31 13:00:55.246 11224 11287 I jxcore-log: 
,03-31 13:00:55.251 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
,03-31 13:00:55.251 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
,03-31 13:00:55.251 11224 11224 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 13:00:55.256 11224 11287 I jxcore-log: # setup
,03-31 13:00:55.256 11224 11287 I jxcore-log: 
,03-31 13:00:55.256 11224 11224 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-31 13:00:55.256 11224 11224 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 13:00:55.256 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 13:00:55.256 11224 11287 I jxcore-log: 
,03-31 13:00:55.261 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 13:00:55.261 11224 11287 I jxcore-log: 
,03-31 13:00:55.281  3461  4244 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-31 13:00:55.281  3461  4244 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 13:00:55.281  3461  4244 D BatteryService: online:4, current avg:41, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:39
03-31 13:00:55.281  3461  4244 D BatteryService: stay LED for fully charged
03-31 13:00:55.281  3461  3461 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 13:00:55.281  3461  3461 I MotionRecognitionService: Plugged
03-31 13:00:55.281  3461  3461 D MotionRecognitionService:   cableConnection= 1
03-31 13:00:55.281  3461  3461 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 13:00:55.281  3461  3461 D MotionRecognitionService: skip setTransmitPower. 
,03-31 13:00:55.286  3728  3728 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 13:00:55.286  3728  3728 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 13:00:55.286  3728  3728 D KeyguardUpdateMonitor: handleBatteryUpdate
03-31 13:00:55.286  5893  6021 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0x16):jv handle:0x0 not FOUND
,03-31 13:00:55.291  3728  3728 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 13:00:55.291  5893  5893 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 13:00:55.291  5893  5980 D HeadsetStateMachine: Disconnected process message: 10,
,03-31 13:00:55.306  3728  3728 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 13:00:55.306  3728  3728 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 13:00:55.306  3728  3728 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 13:00:56.106 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 13:00:56.106 11224 11287 I jxcore-log: 
,03-31 13:00:56.111 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 13:00:56.111 11224 11287 I jxcore-log: 
,03-31 13:00:56.121 11224 11287 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 13:00:56.121 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 13:00:56.121 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 13:00:56.121 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 13:00:56.121 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 13:00:56.121 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 13:00:56.121 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 13:00:56.121 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 13:00:56.121 11224 11287 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 13:00:56.126 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 13:00:56.126 11224 11287 I jxcore-log: 
,03-31 13:00:56.131 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 13:00:56.131 11224 11287 I jxcore-log: 
,03-31 13:00:56.136 11224 11287 I jxcore-log: # 42. #startListeningForAdvertisements should fail if start not called
03-31 13:00:56.136 11224 11287 I jxcore-log: 
,03-31 13:00:56.136 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 13:00:56.136 11224 11287 I jxcore-log: 
,03-31 13:00:56.226 11224 11287 I jxcore-log: ok 180 specific error should be returned
03-31 13:00:56.226 11224 11287 I jxcore-log: 
,03-31 13:00:56.226 11224 11287 I jxcore-log: # teardown
03-31 13:00:56.226 11224 11287 I jxcore-log: 
,03-31 13:00:56.316 11224 11287 I jxcore-log: ok 181 must be stopped
03-31 13:00:56.316 11224 11287 I jxcore-log: 
,03-31 13:00:56.316 11224 11287 I jxcore-log: # setup
03-31 13:00:56.316 11224 11287 I jxcore-log: 
,03-31 13:00:56.461 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 13:00:56.461 11224 11287 I jxcore-log: 
,03-31 13:00:56.466 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 13:00:56.466 11224 11287 I jxcore-log: 
,03-31 13:00:56.476 11224 11287 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 13:00:56.476 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 13:00:56.476 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 13:00:56.476 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 13:00:56.476 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 13:00:56.476 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 13:00:56.476 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 13:00:56.476 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 13:00:56.481 11224 11287 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
,03-31 13:00:56.486 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 13:00:56.486 11224 11287 I jxcore-log: 
,03-31 13:00:56.486 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 13:00:56.486 11224 11287 I jxcore-log: 
,03-31 13:00:56.491 11224 11287 I jxcore-log: # 43. #startUpdateAdvertisingAndListening should fail if start not called
03-31 13:00:56.491 11224 11287 I jxcore-log: 
,03-31 13:00:56.491 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 13:00:56.491 11224 11287 I jxcore-log: 
,03-31 13:00:56.676 11224 11287 I jxcore-log: ok 182 specific error should be returned
03-31 13:00:56.676 11224 11287 I jxcore-log: 
,03-31 13:00:56.681 11224 11287 I jxcore-log: # teardown
03-31 13:00:56.681 11224 11287 I jxcore-log: 
,03-31 13:00:56.861 11224 11287 I jxcore-log: ok 183 must be stopped
03-31 13:00:56.861 11224 11287 I jxcore-log: 
,03-31 13:00:56.866 11224 11287 I jxcore-log: # setup
03-31 13:00:56.866 11224 11287 I jxcore-log: 
,03-31 13:00:57.056 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 13:00:57.056 11224 11287 I jxcore-log: 
,03-31 13:00:57.061 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 13:00:57.061 11224 11287 I jxcore-log: 
,03-31 13:00:57.071 11224 11287 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 13:00:57.071 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 13:00:57.071 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 13:00:57.071 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 13:00:57.071 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 13:00:57.071 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 13:00:57.071 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 13:00:57.071 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 13:00:57.071 11224 11287 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 13:00:57.076 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 13:00:57.076 11224 11287 I jxcore-log: 
,03-31 13:00:57.081 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 13:00:57.081 11224 11287 I jxcore-log: 
,03-31 13:00:57.081 11224 11287 I jxcore-log: # 44. should be able to call #stopListeningForAdvertisements many times
03-31 13:00:57.081 11224 11287 I jxcore-log: 
,03-31 13:00:57.086 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 13:00:57.086 11224 11287 I jxcore-log: 
,03-31 13:00:57.391 11224 11287 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 13:00:57.391 11224 11287 I jxcore-log: 
,03-31 13:00:57.396 11224 11287 I jxcore-log: DEBUG createNativeListener: listening 52324
03-31 13:00:57.396 11224 11287 I jxcore-log: 
,03-31 13:00:57.396 11224 11287 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 13:00:57.396 11224 11287 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 13:00:57.396 11224 11287 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 13:00:57.401 11224 11287 I jxcore-log: ok 184 no errors
03-31 13:00:57.401 11224 11287 I jxcore-log: 
,03-31 13:00:57.406 11224 11287 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 13:00:57.406 11224 11287 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 13:00:57.406 11224 11287 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 13:00:57.411 11224 11287 I jxcore-log: ok 185 still no errors
03-31 13:00:57.411 11224 11287 I jxcore-log: 
,03-31 13:00:57.416 11224 11287 I jxcore-log: # teardown
03-31 13:00:57.416 11224 11287 I jxcore-log: 
,03-31 13:00:57.966 11224 11287 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 13:00:57.966 11224 11287 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 13:00:57.966 11224 11287 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 13:00:57.971 11224 11287 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 13:00:57.971 11224 11287 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 13:00:57.971 11224 11287 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 13:00:57.981 11224 11287 I jxcore-log: ok 186 must be stopped
03-31 13:00:57.981 11224 11287 I jxcore-log: 
,03-31 13:00:57.986 11224 11287 I jxcore-log: # setup
03-31 13:00:57.986 11224 11287 I jxcore-log: 
,03-31 13:00:58.141 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 13:00:58.141 11224 11287 I jxcore-log: 
,03-31 13:00:58.146 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 13:00:58.146 11224 11287 I jxcore-log: 
,03-31 13:00:58.156 11224 11287 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 13:00:58.156 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 13:00:58.156 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 13:00:58.156 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 13:00:58.156 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 13:00:58.156 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 13:00:58.156 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 13:00:58.156 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 13:00:58.161 11224 11287 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 13:00:58.166 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 13:00:58.166 11224 11287 I jxcore-log: 
,03-31 13:00:58.166 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 13:00:58.166 11224 11287 I jxcore-log: 
,03-31 13:00:58.176 11224 11287 I jxcore-log: # 45. should be able to call #startListeningForAdvertisements many times
03-31 13:00:58.176 11224 11287 I jxcore-log: 
,03-31 13:00:58.181 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 13:00:58.181 11224 11287 I jxcore-log: 
,03-31 13:00:58.296 11224 11287 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 13:00:58.296 11224 11287 I jxcore-log: 
,03-31 13:00:58.301 11224 11287 I jxcore-log: DEBUG createNativeListener: listening 58204
03-31 13:00:58.301 11224 11287 I jxcore-log: 
,03-31 13:00:58.311 11224 11287 I io.jxcore.node.ConnectionHelper: start: Port number: 41471, start advertisements: false
,03-31 13:00:58.311 11224 11287 I io.jxcore.node.ConnectionHelper: restoreDefaultBleDiscoverySettings: Powering the BLE discovery back up
03-31 13:00:58.311 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 0 -> 2
,03-31 13:00:58.321 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-31 13:00:58.321 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 13:00:58.321 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-31 13:00:58.321 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-31 13:00:58.321 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-31 13:00:58.321 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-31 13:00:58.321 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 1, timeout: 0, is connectable: false
,03-31 13:00:58.321 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-31 13:00:58.321 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 1 -> 3
,03-31 13:00:58.326 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-31 13:00:58.326 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 13:00:58.326 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-31 13:00:58.326 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-31 13:00:58.326 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-31 13:00:58.326 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-31 13:00:58.326 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-31 13:00:58.326 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-31 13:00:58.331 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 0 -> 2
,03-31 13:00:58.331 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-31 13:00:58.331 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 13:00:58.331 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-31 13:00:58.331 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-31 13:00:58.331 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-31 13:00:58.331 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-31 13:00:58.331 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-31 13:00:58.331 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 13:00:58.331 11224 11287 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 13:00:58.331 11224 11287 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 13:00:58.331 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-31 13:00:58.336 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-31 13:00:58.336 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 13:00:58.341 11224 11287 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 13:00:58.341  5893  5903 D BtGatt.GattService: registerClient() - UUID=b3780a80-dabd-43a1-b871-546cabc34d11
,03-31 13:00:58.386  5893  5958 D BtGatt.GattService: onClientRegistered() - UUID=b3780a80-dabd-43a1-b871-546cabc34d11, clientIf=6
03-31 13:00:58.386 11224 11234 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-31 13:00:58.386  5893  5905 D BtGatt.GattService: start scan with filters
,03-31 13:00:58.401  5893  5905 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 60
,03-31 13:00:58.401 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 13:00:58.401 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 13:00:58.401 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-31 13:00:58.401 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 13:00:58.401  5893  5979 D BtGatt.ScanManager: handling starting scan
,03-31 13:00:58.401  5893  5979 D BtGatt.ScanManager: isFilteringSupported
03-31 13:00:58.401 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 13:00:58.401  5893  5979 D BluetoothAdapter: setting StandAloneBleMode
03-31 13:00:58.401 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-31 13:00:58.401 11224 11224 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-31 13:00:58.401  5893  5958 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-31 13:00:58.401  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 13:00:58.406  5893  5979 D BtGatt.ScanManager: allow scan with filters
03-31 13:00:58.406  5893  5979 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-31 13:00:58.406 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 13:00:58.406  5893  5979 D BtGatt.ScanManager: set filter index= 6 for clientIf= 6
03-31 13:00:58.406 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 13:00:58.406 11224 11224 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 13:00:58.406 11224 11224 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 13:00:58.406 11224 11224 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 13:00:58.406 11224 11287 I io.jxcore.node.ConnectionHelper: start: OK
,03-31 13:00:58.406  5893  5958 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-31 13:00:58.406  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 13:00:58.406  5893  5979 D BtGatt.ScanManager: Starting BLE batch scan
03-31 13:00:58.406  5893  5979 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-31 13:00:58.406  5893  5958 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-31 13:00:58.406  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 13:00:58.406 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 13:00:58.406 11224 11287 I jxcore-log: 
,03-31 13:00:58.406  5893  5958 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-31 13:00:58.406  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 13:00:58.411 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 13:00:58.411 11224 11287 I jxcore-log: 
,03-31 13:00:58.411 11224 11287 I jxcore-log: ok 187 no errors
03-31 13:00:58.411 11224 11287 I jxcore-log: 
,03-31 13:00:58.416 11224 11287 I io.jxcore.node.ConnectionHelper: start: Port number: 41471, start advertisements: false
,03-31 13:00:58.416 11224 11287 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 13:00:58.416 11224 11287 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 13:00:58.416 11224 11287 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-31 13:00:58.416 11224 11287 I io.jxcore.node.ConnectionHelper: start: OK
,03-31 13:00:58.416 11224 11287 I jxcore-log: ok 188 still no errors
03-31 13:00:58.416 11224 11287 I jxcore-log: 
,03-31 13:00:58.421 11224 11287 I jxcore-log: # teardown
03-31 13:00:58.421 11224 11287 I jxcore-log: 
,03-31 13:00:58.676 11224 11287 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 13:00:58.681 11224 11287 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,03-31 13:00:58.681 11224 11287 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-31 13:00:58.681 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-31 13:00:58.681 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-31 13:00:58.681 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-31 13:00:58.681 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-31 13:00:58.681 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-31 13:00:58.681 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-31 13:00:58.686  5893  5903 D BtGatt.GattService: stopScan() - queue size =1
03-31 13:00:58.686  5893  5979 D BtGatt.ScanManager: filter size is 1
03-31 13:00:58.686  5893  5979 D BtGatt.ScanManager: delete FilterIndex - 6
03-31 13:00:58.691  5893  5958 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-31 13:00:58.691  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 13:00:58.691  5893  5979 D BtGatt.ScanManager: stopping BLe Batch
,03-31 13:00:58.691  5893  5958 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0,
03-31 13:00:58.691  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 13:00:58.691  5893  5979 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-31 13:00:58.691  5893  5958 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,03-31 13:00:58.691  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 13:00:58.696  5893  5905 D BtGatt.GattService: unregisterClient() - clientIf=6,
,03-31 13:00:58.701 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 13:00:58.701 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 13:00:58.701 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,03-31 13:00:58.701 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-31 13:00:58.701 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED],
,03-31 13:00:58.701 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 13:00:58.706 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
,03-31 13:00:58.706 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 13:00:58.706 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...,
,03-31 13:00:58.706 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
03-31 13:00:58.706 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 13:00:58.706 11224 11224 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 13:00:58.706 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-31 13:00:58.706 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-31 13:00:58.716 11224 11224 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
03-31 13:00:58.721 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-31 13:00:58.721 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-31 13:00:58.721 11224 11224 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 13:00:58.731 11224 11224 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 13:00:58.731 11224 11224 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 13:00:58.731 11224 11224 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 13:00:58.731 11224 11224 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 13:00:58.731 11224 11287 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 13:00:58.731 11224 11287 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-31 13:00:58.731 11224 11287 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 13:00:58.736 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 13:00:58.736 11224 11287 I jxcore-log: 
,03-31 13:00:58.736 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 13:00:58.736 11224 11287 I jxcore-log: 
,03-31 13:00:58.741 11224 11287 I jxcore-log: ok 189 must be stopped
03-31 13:00:58.741 11224 11287 I jxcore-log: 
,03-31 13:00:58.751 11224 11287 I jxcore-log: # setup
03-31 13:00:58.751 11224 11287 I jxcore-log: 
,03-31 13:00:58.896 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native,
03-31 13:00:58.896 11224 11287 I jxcore-log: 
03-31 13:00:58.896 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native,
03-31 13:00:58.896 11224 11287 I jxcore-log: 
,03-31 13:00:58.906 11224 11287 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 13:00:58.906 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 13:00:58.906 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 13:00:58.906 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 13:00:58.906 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 13:00:58.906 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 13:00:58.906 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 13:00:58.906 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 13:00:58.911 11224 11287 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 13:00:58.916 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 13:00:58.916 11224 11287 I jxcore-log: 
,03-31 13:00:58.916 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 13:00:58.916 11224 11287 I jxcore-log: 
,03-31 13:00:58.921 11224 11287 I jxcore-log: # 46. should be able to call #startUpdateAdvertisingAndListening many times
03-31 13:00:58.921 11224 11287 I jxcore-log: 
,03-31 13:00:58.926 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 13:00:58.926 11224 11287 I jxcore-log: 
,03-31 13:00:59.031 11224 11287 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 13:00:59.031 11224 11287 I jxcore-log: 
,03-31 13:00:59.031 11224 11287 I jxcore-log: DEBUG createNativeListener: listening 36080
03-31 13:00:59.031 11224 11287 I jxcore-log: 
,03-31 13:00:59.036 11224 11287 I io.jxcore.node.ConnectionHelper: start: Port number: 36080, start advertisements: true
03-31 13:00:59.036 11224 11287 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 13:00:59.036 11224 11287 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-31 13:00:59.036 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-31 13:00:59.041 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-31 13:00:59.041 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 13:00:59.041 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 13:00:59.041 11224 11287 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 13:00:59.046  5893  5905 D BtGatt.GattService: registerClient() - UUID=3d713e02-f4d0-41bb-b10e-4eb366080cf7
,03-31 13:00:59.086  5893  5958 D BtGatt.GattService: onClientRegistered() - UUID=3d713e02-f4d0-41bb-b10e-4eb366080cf7, clientIf=6
,03-31 13:00:59.086 11224 11280 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-31 13:00:59.086  5893  5987 D BtGatt.GattService: start scan with filters
,03-31 13:00:59.101  5893  5987 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 61
,03-31 13:00:59.101 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 13:00:59.101 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 13:00:59.101 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-31 13:00:59.101 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 13:00:59.101 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,03-31 13:00:59.101  5893  5979 D BtGatt.ScanManager: handling starting scan
03-31 13:00:59.101  5893  5979 D BtGatt.ScanManager: isFilteringSupported
03-31 13:00:59.101 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 13:00:59.101  5893  5979 D BluetoothAdapter: setting StandAloneBleMode
03-31 13:00:59.101 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-31 13:00:59.101 11224 11224 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 13:00:59.101 11224 11287 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-31 13:00:59.101 11224 11287 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 13:00:59.101 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 13:00:59.101 11224 11287 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-31 13:00:59.106  5893  5958 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-31 13:00:59.106  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 13:00:59.106  5893  5979 D BtGatt.ScanManager: allow scan with filters
03-31 13:00:59.106  5893  5979 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-31 13:00:59.106  5893  5979 D BtGatt.ScanManager: set filter index= 7 for clientIf= 6
,03-31 13:00:59.106  5893  5958 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-31 13:00:59.106  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 13:00:59.106  5893  5979 D BtGatt.ScanManager: Starting BLE batch scan
03-31 13:00:59.106  5893  5979 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-31 13:00:59.111  5893  5958 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0,
03-31 13:00:59.111  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 13:00:59.111  5893  5987 D BtGatt.GattService: registerClient() - UUID=04805ae7-a785-46b5-b58b-cc90470201a7
,03-31 13:00:59.111  5893  5958 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-31 13:00:59.111  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 13:00:59.151  5893  5958 D BtGatt.GattService: onClientRegistered() - UUID=04805ae7-a785-46b5-b58b-cc90470201a7, clientIf=7
,03-31 13:00:59.151 11224 11234 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-31 13:00:59.151  5893  6021 E bt-btm  : Reset sec_bd_name and name flag. (BR/EDR link)
03-31 13:00:59.151  5893  6021 E bt-btm  : btm_sec_disconnected - Clearing Pending flag
03-31 13:00:59.151  5893  6021 W bt-btif : bta_dm_acl_change(), event : 1
,03-31 13:00:59.151  5893  6021 W bt-btif : HAL bt_hal_cbacks->acl_state_c
03-31 13:00:59.151  5893  5958 E BluetoothRemoteDevices: aclStateChangeCallback: State:DisConnected to Device:F8:CF:C5:D9:E5:XX
,03-31 13:00:59.161  5893  5958 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,03-31 13:00:59.161  3728  3728 D KeyguardViewMediator: Received android.bluetooth.device.action.ACL_DISCONNECTED
,03-31 13:00:59.166  3461  3461 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
,03-31 13:00:59.166  3461  3461 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.device.action.ACL_DISCONNECTED
03-31 13:00:59.166  3461  3461 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_ACL_DISCONNECTED,
,03-31 13:00:59.171  5893  8993 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 49
03-31 13:00:59.171  5893  5978 D BtGatt.AdvertiseManager: message : 0
,03-31 13:00:59.176  5893  5978 D BtGatt.AdvertiseManager: number of adv instance running0
03-31 13:00:59.176  5893  5978 D BtGatt.AdvertiseManager: size of list is =0
,03-31 13:00:59.181  5893  5978 D BtGatt.AdvertiseManager: starting advertising
03-31 13:00:59.181  5893  5978 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-31 13:00:59.181  3461  3568 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ccf7277 u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{388a0b6d 5893:com.android.bluetooth/1002}
,03-31 13:00:59.186  5893  5958 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
03-31 13:00:59.186  3461  4438 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
03-31 13:00:59.186  3728  3728 D KeyguardViewMediator: isGear1: device is not B1!
,03-31 13:00:59.186  5893  5978 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 13:00:59.191  5893  5958 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-31 13:00:59.191  5893  5978 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-31 13:00:59.191  5893  5978 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
03-31 13:00:59.191 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-31 13:00:59.191 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-31 13:00:59.201  5893  5893 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@be0f583
03-31 13:00:59.201  5893  5893 D BtConfig.SecureMode: isSecureModeOn:false
03-31 13:00:59.201  3461  4438 D SecContentProvider: query(), uri = 4 selection = isProfileAuthorizedBySecurityPolicy
03-31 13:00:59.206 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-31 13:00:59.206 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-31 13:00:59.206 11224 11287 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-31 13:00:59.206 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-31 13:00:59.206  3461  4439 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
03-31 13:00:59.206 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-31 13:00:59.206 11224 11287 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-31 13:00:59.206 11224 11287 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-31 13:00:59.206 11224 11287 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-31 13:00:59.206 11224 11287 I io.jxcore.node.ConnectionHelper: start: OK
03-31 13:00:59.211 11224 11224 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-31 13:00:59.211 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 13:00:59.211 11224 11224 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-31 13:00:59.211 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-31 13:00:59.211 11224 11224 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-31 13:00:59.211 11224 11224 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-31 13:00:59.211 11224 11224 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 13:00:59.211 11224 11224 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 13:00:59.211 11224 11224 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-31 13:00:59.211 11224 11224 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 13:00:59.211 11224 11224 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-31 13:00:59.211 11224 11224 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 13:00:59.211 10370 12008 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.ACL_DISCONNECTED State = -2147483648 Previous = -2147483648
03-31 13:00:59.211  5893  5893 I BluetoothPbapService: action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,03-31 13:00:59.216 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 13:00:59.216 11224 11287 I jxcore-log: 
,03-31 13:00:59.221 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 13:00:59.221 11224 11287 I jxcore-log: 
,03-31 13:00:59.221  3461  3488 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ccf7277 u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{3dc043fa 11899:com.sec.android.app.shealth/u0a36}
03-31 13:00:59.221 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-31 13:00:59.221 11224 11287 I jxcore-log: 
,03-31 13:00:59.226 11224 11287 I jxcore-log: ok 190 no errors
03-31 13:00:59.226 11224 11287 I jxcore-log: 
,03-31 13:00:59.226 11224 12009 D BluetoothSocket: bindListen(): myUserId = 0
03-31 13:00:59.231 11224 12009 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-31 13:00:59.231 10370 10370 D [CarModeFW]: ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED
,03-31 13:00:59.231 10370 10370 D [CarModeFW]: ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED onNotifyBluetoothDeviceDisconnected
,03-31 13:00:59.231 11224 11287 I io.jxcore.node.ConnectionHelper: start: Port number: 36080, start advertisements: true
03-31 13:00:59.231 11224 12009 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[118]}
03-31 13:00:59.231 11224 12009 D BluetoothSocket: bindListen(), new LocalSocket 
03-31 13:00:59.231 11224 11287 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 13:00:59.231 11224 12009 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-31 13:00:59.231 11224 11287 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-31 13:00:59.231 11224 11287 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-31 13:00:59.231 11224 12009 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2d5b2aad
03-31 13:00:59.231 11224 11287 I io.jxcore.node.ConnectionHelper: start: OK
03-31 13:00:59.231 11224 12009 D BluetoothSocket: channel: 6
03-31 13:00:59.231 11224 12009 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-31 13:00:59.236 11224 11287 I jxcore-log: ok 191 still no errors
03-31 13:00:59.236 11224 11287 I jxcore-log: 
03-31 13:00:59.236  3461  3833 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ccf7277 u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{3dc043fa 11899:com.sec.android.app.shealth/u0a36}
03-31 13:00:59.236 10370 10370 D [CarModeFW]: ConnectivityManager-Paired Devices list is empty
03-31 13:00:59.241 10370 10370 E [CarMode]: [BluetoothConnectivityListener]-onNotifyBluetoothProfileDisconnected: Unexpected error: Invalid device
,03-31 13:00:59.246 11224 11287 I jxcore-log: # teardown
03-31 13:00:59.246 11224 11287 I jxcore-log: 
,03-31 13:00:59.251  3461  3853 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ccf7277 u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{3dc043fa 11899:com.sec.android.app.shealth/u0a36}
,03-31 13:00:59.261  3461  3653 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ccf7277 u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{385670e6 4131:com.google.android.googlequicksearchbox:search/u0a64}
,03-31 13:00:59.266  4131  4131 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,03-31 13:00:59.266  4131  4131 I BluetoothClassifier: Bluetooth Device Name: Nexus 6
,03-31 13:00:59.996  3461  3617 V AlarmManager: waitForAlarm result :8
,03-31 13:01:00.111  3461  3617 V AlarmManager: waitForAlarm result :4
,03-31 13:01:00.136  5893  5893 D BtGatt.ScanManager: awakened up at time 261232
,03-31 13:01:00.146  5893  5979 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-31 13:01:00.151  5893  5958 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
03-31 13:01:00.151  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 13:01:00.151  5893  5958 D BtGatt.GattService: current time is 261245640488
03-31 13:01:00.151  5893  5958 D BtGatt.GattService: Batch record : [-49, 45, 110, -73, 54, 124, 1, -128, -72, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -14, 78, 25, -57, 78, 90, 1, -128, -55, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0]
03-31 13:01:00.151  5893  5958 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-31 13:01:00.151  5893  5958 D ScanRecord: parseFromBytes
03-31 13:01:00.151  5893  5958 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-31 13:01:00.151  5893  5958 D ScanRecord: parseFromBytes
03-31 13:01:00.151  5893  5958 D BtGatt.GattService: result: ScanResult{mDevice=5A:4E:C7:19:4E:F2, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-55, mTimestampNanos=261195862821}
03-31 13:01:00.151  5893  5958 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-31 13:01:00.151  5893  5958 D BtGatt.GattService: result: ScanResult{mDevice=7C:36:B7:6E:2D:CF, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-72, mTimestampNanos=261145862821}
03-31 13:01:00.151  5893  5958 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-31 13:01:00.151 11224 11280 D ScanRecord: parseFromBytes
03-31 13:01:00.151 11224 11280 D ScanRecord: parseFromBytes
03-31 13:01:00.151 11224 11224 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:CF:C5:D9:E5:61], added - the peer count is 1
03-31 13:01:00.151 11224 11224 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 2
03-31 13:01:00.151 11224 11224 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:CF:C5:D9:E5:61], Bluetooth address: F8:CF:C5:D9:E5:61, device name: , device address: 
03-31 13:01:00.151 11224 11224 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
03-31 13:01:00.156 11224 11287 I jxcore-log: DEBUG createPeerListener: createPeerListener
03-31 13:01:00.156 11224 11287 I jxcore-log: 
,03-31 13:01:00.171  3728  3728 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK,
03-31 13:01:00.171  3728  3728 I PERF    : received broadcast android.intent.action.TIME_TICK
03-31 13:01:00.171  3728  3728 D KeyguardUpdateMonitor: handleTimeUpdate
,03-31 13:01:00.186  3728  3728 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false,
03-31 13:01:00.191  3728  3728 D SecKeyguardClockView: HomeTimezone(): 1
,03-31 13:01:00.196  3728  3728 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 13:01:00.201  3728  3728 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,03-31 13:01:00.201 11224 11287 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false
03-31 13:01:00.201 11224 11287 I jxcore-log: 
,03-31 13:01:00.211 11224 11287 I jxcore-log: DEBUG createPeerListener: createPeerListener
03-31 13:01:00.211 11224 11287 I jxcore-log: 
,03-31 13:01:00.216  3728  3728 D CoverUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,03-31 13:01:00.226 11224 11287 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false
03-31 13:01:00.226 11224 11287 I jxcore-log: 
,03-31 13:01:00.261  3728  3728 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 13:01:00.261  3728  3728 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 13:01:00.266  3728  3728 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 13:01:00.266  3728  3728 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 13:01:00.271  3728  3728 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 13:01:00.276  3728  3728 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 13:01:00.291  3728  3728 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 13:01:00.821 11224 11287 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 13:01:00.821 11224 11287 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
,03-31 13:01:00.826 11224 11287 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,03-31 13:01:00.826 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...,
03-31 13:01:00.826 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown,
,03-31 13:01:00.826 11224 11287 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2496030, channel: 6, state: LISTENING
,03-31 13:01:00.826 11224 11287 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2496030, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2d5b2aad, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@29acc4a9mSocket: android.net.LocalSocket@26316a2e impl:android.net.LocalSocketImpl@1ef869cf fd:FileDescriptor[118],
,03-31 13:01:00.831 11224 11287 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@26316a2e impl:android.net.LocalSocketImpl@1ef869cf fd:FileDescriptor[118]
,03-31 13:01:00.831 11224 11287 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed,
,03-31 13:01:00.831 11224 12009 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
,03-31 13:01:00.831 11224 12009 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-31 13:01:00.836 11224 12009 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,03-31 13:01:00.836 11224 11224 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-31 13:01:00.836 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-31 13:01:00.836 11224 11224 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED,
03-31 13:01:00.836 11224 11224 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED,
,03-31 13:01:00.836 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...,
,03-31 13:01:00.836 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart,
,03-31 13:01:00.836 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-31 13:01:00.836 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser,
,03-31 13:01:00.836 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...,
,03-31 13:01:00.841  5893  5987 D BtGatt.GattService: stopScan() - queue size =1,
03-31 13:01:00.846  5893  5979 D BtGatt.ScanManager: filter size is 1,
,03-31 13:01:00.846  5893  5979 D BtGatt.ScanManager: delete FilterIndex - 7
03-31 13:01:00.846  5893  5958 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16,
,03-31 13:01:00.846  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
03-31 13:01:00.846  5893  5979 D BtGatt.ScanManager: stopping BLe Batch
03-31 13:01:00.846  5893  5958 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,03-31 13:01:00.846  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 13:01:00.851  5893  5979 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-31 13:01:00.851  5893  5958 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
03-31 13:01:00.851  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 13:01:00.851  5893  5958 D BtGatt.GattService: current time is 261949115238
,03-31 13:01:00.851  5893  5958 D BtGatt.GattService: Batch record : [-49, 45, 110, -73, 54, 124, 1, -128, -72, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -14, 78, 25, -57, 78, 90, 1, -128, -55, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0]
03-31 13:01:00.851  5893  5958 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-31 13:01:00.851  5893  5958 D ScanRecord: parseFromBytes
03-31 13:01:00.851  5893  5958 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-31 13:01:00.851  5893  5958 D ScanRecord: parseFromBytes
03-31 13:01:00.856  5893  5903 D BtGatt.GattService: unregisterClient() - clientIf=6,
03-31 13:01:00.856 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 13:01:00.856 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 13:01:00.856 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-31 13:01:00.856 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-31 13:01:00.856 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
,03-31 13:01:00.856 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 13:01:00.856 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...,
,03-31 13:01:00.861  5893  5978 D BtGatt.AdvertiseManager: message : 1,
03-31 13:01:00.861  5893  5978 D BtGatt.AdvertiseManager: stop advertise for client 7
03-31 13:01:00.861  5893  5978 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
,03-31 13:01:00.861  5893  5978 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-31 13:01:00.866  5893  5958 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-31 13:01:00.866  5893  5958 D BtGatt.GattService: Client app is not null!
03-31 13:01:00.866  5893  8993 D BtGatt.GattService: unregisterClient() - clientIf=7,
03-31 13:01:00.871 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 13:01:00.871 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-31 13:01:00.871 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-31 13:01:00.871 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-31 13:01:00.871 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-31 13:01:00.871 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-31 13:01:00.871 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 13:01:00.871 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-31 13:01:00.871 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-31 13:01:00.871 11224 11287 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-31 13:01:00.871 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false,
03-31 13:01:00.871 11224 11224 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 13:01:00.871 11224 11224 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed,
03-31 13:01:00.871 11224 11224 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 13:01:00.871 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
03-31 13:01:00.871 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-31 13:01:00.881 11224 11224 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
03-31 13:01:00.886 11224 11287 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements,
03-31 13:01:00.886 11224 11287 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 13:01:00.886 11224 11287 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-31 13:01:00.886 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
03-31 13:01:00.891 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
03-31 13:01:00.891 11224 11224 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 13:01:00.896 11224 11224 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true,
03-31 13:01:00.896 11224 11224 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 13:01:00.896 11224 11224 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false,
03-31 13:01:00.896 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-31 13:01:00.896 11224 11287 I jxcore-log: 
,03-31 13:01:00.901 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
03-31 13:01:00.901 11224 11287 I jxcore-log: 
03-31 13:01:00.906 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 13:01:00.906 11224 11287 I jxcore-log: 
,03-31 13:01:00.916 11224 11287 I jxcore-log: ok 192 must be stopped
03-31 13:01:00.916 11224 11287 I jxcore-log: 
,03-31 13:01:00.931 11224 11287 I jxcore-log: # setup
03-31 13:01:00.931 11224 11287 I jxcore-log: 
,03-31 13:01:01.081 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 13:01:01.081 11224 11287 I jxcore-log: 
,03-31 13:01:01.086 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 13:01:01.086 11224 11287 I jxcore-log: 
,03-31 13:01:01.091 11224 11287 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 13:01:01.091 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 13:01:01.091 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 13:01:01.091 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 13:01:01.091 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 13:01:01.091 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 13:01:01.091 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 13:01:01.091 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 13:01:01.096 11224 11287 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 13:01:01.101 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 13:01:01.101 11224 11287 I jxcore-log: 
,03-31 13:01:01.101 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 13:01:01.101 11224 11287 I jxcore-log: 
,03-31 13:01:01.106 11224 11287 I jxcore-log: # 47. should be able to call #stopAdvertisingAndListening many times
03-31 13:01:01.106 11224 11287 I jxcore-log: 
,03-31 13:01:01.111 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 13:01:01.111 11224 11287 I jxcore-log: 
,03-31 13:01:01.231 11224 11287 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 13:01:01.231 11224 11287 I jxcore-log: 
,03-31 13:01:01.236 11224 11287 I jxcore-log: DEBUG createNativeListener: listening 45649
03-31 13:01:01.236 11224 11287 I jxcore-log: 
,03-31 13:01:01.241 11224 11287 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 13:01:01.241 11224 11287 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-31 13:01:01.241 11224 11287 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 13:01:01.246 11224 11287 I jxcore-log: ok 193 no errors
03-31 13:01:01.246 11224 11287 I jxcore-log: 
,03-31 13:01:01.246 11224 11287 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 13:01:01.246 11224 11287 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-31 13:01:01.251 11224 11287 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 13:01:01.251 11224 11287 I jxcore-log: ok 194 still no errors
03-31 13:01:01.251 11224 11287 I jxcore-log: 
,03-31 13:01:01.261 11224 11287 I jxcore-log: # teardown
03-31 13:01:01.261 11224 11287 I jxcore-log: 
,03-31 13:01:01.326 11224 11287 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-31 13:01:01.326 11224 11287 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 13:01:01.326 11224 11287 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 13:01:01.326 11224 11287 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 13:01:01.326 11224 11287 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 13:01:01.326 11224 11287 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 13:01:01.331 11224 11287 I jxcore-log: ok 195 must be stopped
03-31 13:01:01.331 11224 11287 I jxcore-log: 
,03-31 13:01:01.336 11224 11287 I jxcore-log: # setup
03-31 13:01:01.336 11224 11287 I jxcore-log: 
,03-31 13:01:01.446 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native,
03-31 13:01:01.446 11224 11287 I jxcore-log: 
,03-31 13:01:01.456 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 13:01:01.456 11224 11287 I jxcore-log: 
,03-31 13:01:01.466 11224 11287 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 13:01:01.466 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 13:01:01.466 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 13:01:01.466 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 13:01:01.466 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 13:01:01.466 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 13:01:01.466 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 13:01:01.466 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 13:01:01.466 11224 11287 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 13:01:01.471 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 13:01:01.471 11224 11287 I jxcore-log: 
,03-31 13:01:01.476 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 13:01:01.476 11224 11287 I jxcore-log: 
,03-31 13:01:01.481 11224 11287 I jxcore-log: # 48. can get the network status before starting
03-31 13:01:01.481 11224 11287 I jxcore-log: 
,03-31 13:01:01.481 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 13:01:01.481 11224 11287 I jxcore-log: 
,03-31 13:01:01.556 11224 11287 I jxcore-log: ok 196 network status should have certain non-empty properties
03-31 13:01:01.556 11224 11287 I jxcore-log: 
,03-31 13:01:01.556 11224 11287 I jxcore-log: # teardown
03-31 13:01:01.556 11224 11287 I jxcore-log: 
,03-31 13:01:01.666 11224 11287 I jxcore-log: ok 197 must be stopped
03-31 13:01:01.666 11224 11287 I jxcore-log: 
,03-31 13:01:01.671 11224 11287 I jxcore-log: # setup
03-31 13:01:01.671 11224 11287 I jxcore-log: 
,03-31 13:01:01.806 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 13:01:01.806 11224 11287 I jxcore-log: 
,03-31 13:01:01.811 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 13:01:01.811 11224 11287 I jxcore-log: 
,03-31 13:01:01.821 11224 11287 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 13:01:01.821 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 13:01:01.821 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 13:01:01.821 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 13:01:01.821 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 13:01:01.821 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 13:01:01.821 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 13:01:01.821 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 13:01:01.821 11224 11287 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 13:01:01.826 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 13:01:01.826 11224 11287 I jxcore-log: 
,03-31 13:01:01.831 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 13:01:01.831 11224 11287 I jxcore-log: 
,03-31 13:01:01.836 11224 11287 I jxcore-log: # 49. error returned with bad router,
03-31 13:01:01.836 11224 11287 I jxcore-log: 
,03-31 13:01:01.841 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"},
03-31 13:01:01.841 11224 11287 I jxcore-log: 
,03-31 13:01:01.956 11224 11287 I jxcore-log: ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
03-31 13:01:01.956 11224 11287 I jxcore-log: 
,03-31 13:01:01.961 11224 11287 I jxcore-log: ok 198 specific error expected
03-31 13:01:01.961 11224 11287 I jxcore-log: 
,03-31 13:01:01.966 11224 11287 I jxcore-log: # teardown
03-31 13:01:01.966 11224 11287 I jxcore-log: 
,03-31 13:01:02.116 11224 11287 I jxcore-log: ok 199 must be stopped
03-31 13:01:02.116 11224 11287 I jxcore-log: 
,03-31 13:01:02.121 11224 11287 I jxcore-log: # setup
03-31 13:01:02.121 11224 11287 I jxcore-log: 
,03-31 13:01:02.131  5893  6021 W bt-btif : dm_pm_timer expires
03-31 13:01:02.131  5893  6021 W bt-btif : dm_pm_timer expires 0
03-31 13:01:02.131  5893  6021 W bt-btif : proc dm_pm_timer expires
,03-31 13:01:02.226 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 13:01:02.226 11224 11287 I jxcore-log: 
,03-31 13:01:02.231 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 13:01:02.231 11224 11287 I jxcore-log: 
,03-31 13:01:02.241 11224 11287 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 13:01:02.241 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 13:01:02.241 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 13:01:02.241 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 13:01:02.241 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 13:01:02.241 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 13:01:02.241 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 13:01:02.241 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 13:01:02.246 11224 11287 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 13:01:02.251 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 13:01:02.251 11224 11287 I jxcore-log: 
,03-31 13:01:02.256 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native,
03-31 13:01:02.256 11224 11287 I jxcore-log: 
,03-31 13:01:02.256 11224 11287 I jxcore-log: # 50. all services are stopped when we call stop
03-31 13:01:02.256 11224 11287 I jxcore-log: 
,03-31 13:01:02.261 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 13:01:02.261 11224 11287 I jxcore-log: 
,03-31 13:01:02.441 11224 11287 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 13:01:02.441 11224 11287 I jxcore-log: 
,03-31 13:01:02.446 11224 11287 I jxcore-log: DEBUG createNativeListener: listening 56680
03-31 13:01:02.446 11224 11287 I jxcore-log: 
,03-31 13:01:02.456 11224 11287 I io.jxcore.node.ConnectionHelper: start: Port number: 36080, start advertisements: false
,03-31 13:01:02.456 11224 11287 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 13:01:02.456 11224 11287 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,03-31 13:01:02.456 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-31 13:01:02.461 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-31 13:01:02.461 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 13:01:02.461 11224 11287 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 13:01:02.466  5893 12003 D BtGatt.GattService: registerClient() - UUID=4cae0284-e976-4c6c-9418-53f45637ab9f
,03-31 13:01:02.506  5893  5958 D BtGatt.GattService: onClientRegistered() - UUID=4cae0284-e976-4c6c-9418-53f45637ab9f, clientIf=6
,03-31 13:01:02.506 11224 11280 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-31 13:01:02.506  5893 12002 D BtGatt.GattService: start scan with filters
,03-31 13:01:02.521  5893 12002 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 62
,03-31 13:01:02.521 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 13:01:02.521 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 13:01:02.521 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-31 13:01:02.521 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 13:01:02.521  5893  5979 D BtGatt.ScanManager: handling starting scan
03-31 13:01:02.521 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 13:01:02.521  5893  5979 D BtGatt.ScanManager: isFilteringSupported
03-31 13:01:02.521  5893  5979 D BluetoothAdapter: setting StandAloneBleMode
03-31 13:01:02.521 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-31 13:01:02.521 11224 11224 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-31 13:01:02.521 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
03-31 13:01:02.521 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 13:01:02.526 11224 11287 I io.jxcore.node.ConnectionHelper: start: OK
03-31 13:01:02.526 11224 11224 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 13:01:02.526 11224 11224 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-31 13:01:02.526  5893  5958 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,03-31 13:01:02.526  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 13:01:02.526  5893  5979 D BtGatt.ScanManager: allow scan with filters
03-31 13:01:02.526  5893  5979 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-31 13:01:02.526  5893  5979 D BtGatt.ScanManager: set filter index= 8 for clientIf= 6
03-31 13:01:02.526 11224 11224 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-31 13:01:02.526  5893  5958 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-31 13:01:02.526  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 13:01:02.526  5893  5979 D BtGatt.ScanManager: Starting BLE batch scan
,03-31 13:01:02.526  5893  5979 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-31 13:01:02.531 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 13:01:02.531 11224 11287 I jxcore-log: 
,03-31 13:01:02.531  5893  5958 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-31 13:01:02.531  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 13:01:02.531 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 13:01:02.531 11224 11287 I jxcore-log: 
03-31 13:01:02.531  5893  5958 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-31 13:01:02.531  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 13:01:02.536 11224 11287 I io.jxcore.node.ConnectionHelper: start: Port number: 56680, start advertisements: true
,03-31 13:01:02.536 11224 11287 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 13:01:02.536 11224 11287 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-31 13:01:02.536 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-31 13:01:02.536 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-31 13:01:02.536 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
03-31 13:01:02.536 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 13:01:02.536 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-31 13:01:02.536 11224 11287 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-31 13:01:02.536 11224 11287 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 13:01:02.536 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-31 13:01:02.536 11224 11287 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-31 13:01:02.541  5893 12002 D BtGatt.GattService: registerClient() - UUID=6a7d9333-55ef-4e0d-8694-24fecd696575
,03-31 13:01:02.581  5893  5958 D BtGatt.GattService: onClientRegistered() - UUID=6a7d9333-55ef-4e0d-8694-24fecd696575, clientIf=7
,03-31 13:01:02.581 11224 11234 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-31 13:01:02.601  5893  8993 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 50
,03-31 13:01:02.601  5893  5978 D BtGatt.AdvertiseManager: message : 0
03-31 13:01:02.601  5893  5978 D BtGatt.AdvertiseManager: number of adv instance running0
,03-31 13:01:02.601  5893  5978 D BtGatt.AdvertiseManager: size of list is =0
,03-31 13:01:02.601  5893  5978 D BtGatt.AdvertiseManager: starting advertising
03-31 13:01:02.601  5893  5978 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-31 13:01:02.606  5893  5958 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-31 13:01:02.606  5893  5978 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 13:01:02.611  5893  5958 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-31 13:01:02.611  5893  5978 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-31 13:01:02.611  5893  5978 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,03-31 13:01:02.611 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 13:01:02.611 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-31 13:01:02.611 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-31 13:01:02.611 11224 11224 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-31 13:01:02.611 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-31 13:01:02.611 11224 11224 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
,03-31 13:01:02.611 11224 11224 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
,03-31 13:01:02.616 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-31 13:01:02.616 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 13:01:02.616 11224 11287 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-31 13:01:02.616 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 13:01:02.616 11224 11224 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 13:01:02.616 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-31 13:01:02.616 11224 11287 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-31 13:01:02.616 11224 11287 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-31 13:01:02.616 11224 11287 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-31 13:01:02.616 11224 11287 I io.jxcore.node.ConnectionHelper: start: OK
03-31 13:01:02.616 11224 11224 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-31 13:01:02.616 11224 11224 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 13:01:02.616 11224 11224 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,03-31 13:01:02.621 11224 12068 D BluetoothSocket: bindListen(): myUserId = 0
,03-31 13:01:02.621 11224 12068 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-31 13:01:02.621 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-31 13:01:02.621 11224 11287 I jxcore-log: 
,03-31 13:01:02.626 11224 12068 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[118]}
,03-31 13:01:02.626 11224 12068 D BluetoothSocket: bindListen(), new LocalSocket 
03-31 13:01:02.626 11224 12068 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-31 13:01:02.626 11224 12068 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@e3bd3eb
03-31 13:01:02.626 11224 12068 D BluetoothSocket: channel: 6
,03-31 13:01:02.626 11224 12068 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-31 13:01:02.631 11224 11287 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 13:01:02.631 11224 11287 I jxcore-log: 
,03-31 13:01:02.636 11224 11287 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 13:01:02.636 11224 11287 I jxcore-log: 
,03-31 13:01:02.636 11224 11287 I jxcore-log: DEBUG createNativeListener: new mux
03-31 13:01:02.636 11224 11287 I jxcore-log: 
,03-31 13:01:02.641 11224 11287 I jxcore-log: ok 200 connection to servers manager should succeed after starting
03-31 13:01:02.641 11224 11287 I jxcore-log: 
,03-31 13:01:02.671 11224 11287 I jxcore-log: ok 201 connection to router server should succeed after starting
03-31 13:01:02.671 11224 11287 I jxcore-log: 
,03-31 13:01:02.671 11224 11287 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 13:01:02.671 11224 11287 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-31 13:01:02.671 11224 11287 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-31 13:01:02.671 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-31 13:01:02.671 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-31 13:01:02.671 11224 11287 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1ccd0548, channel: 6, state: LISTENING
03-31 13:01:02.671 11224 11287 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1ccd0548, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@e3bd3eb, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@18975fe1mSocket: android.net.LocalSocket@20b09106 impl:android.net.LocalSocketImpl@2801c3c7 fd:FileDescriptor[118]
03-31 13:01:02.671 11224 11287 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@20b09106 impl:android.net.LocalSocketImpl@2801c3c7 fd:FileDescriptor[118]
03-31 13:01:02.671 11224 11287 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-31 13:01:02.671 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-31 13:01:02.671 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-31 13:01:02.671 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-31 13:01:02.671 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-31 13:01:02.671 11224 12068 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-31 13:01:02.671 11224 12068 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-31 13:01:02.671 11224 12068 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-31 13:01:02.671 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-31 13:01:02.671 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-31 13:01:02.676  5893  8993 D BtGatt.GattService: stopScan() - queue size =1
,03-31 13:01:02.676  5893  5979 D BtGatt.ScanManager: filter size is 1
03-31 13:01:02.676  5893  5979 D BtGatt.ScanManager: delete FilterIndex - 8
,03-31 13:01:02.676  5893  5905 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-31 13:01:02.676  5893  5958 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-31 13:01:02.676 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 13:01:02.676  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 13:01:02.676 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 13:01:02.676 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-31 13:01:02.676  5893  5979 D BtGatt.ScanManager: stopping BLe Batch
,03-31 13:01:02.676 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-31 13:01:02.676 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-31 13:01:02.676 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 13:01:02.676 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-31 13:01:02.676  5893  5978 D BtGatt.AdvertiseManager: message : 1
,03-31 13:01:02.676  5893  5978 D BtGatt.AdvertiseManager: stop advertise for client 7
03-31 13:01:02.676  5893  5978 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-31 13:01:02.681  5893  5958 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-31 13:01:02.681  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 13:01:02.681  5893  5979 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-31 13:01:02.681  5893  5978 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-31 13:01:02.681  5893  5958 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-31 13:01:02.681  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 13:01:02.681  5893  5958 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
,03-31 13:01:02.681  5893  5958 D BtGatt.GattService: Client app is not null!
,03-31 13:01:02.681  5893 12003 D BtGatt.GattService: unregisterClient() - clientIf=7
03-31 13:01:02.686 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 13:01:02.686 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-31 13:01:02.686 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-31 13:01:02.686 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-31 13:01:02.686 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-31 13:01:02.686 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 13:01:02.686 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 13:01:02.686 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-31 13:01:02.686 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-31 13:01:02.686 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 13:01:02.686 11224 11224 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 13:01:02.686 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 13:01:02.686 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-31 13:01:02.686 11224 11287 I jxcore-log: DEBUG createNativeListener: incoming socket close
,03-31 13:01:02.686 11224 11287 I jxcore-log: 
,03-31 13:01:02.691 11224 11224 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-31 13:01:02.696 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-31 13:01:02.696 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 13:01:02.696 11224 11224 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 13:01:02.701 11224 11224 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-31 13:01:02.701 11224 11224 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-31 13:01:02.701 11224 11224 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 13:01:02.701 11224 11224 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 13:01:02.701 11224 11224 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 13:01:02.701 11224 11224 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 13:01:02.701 11224 11224 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 13:01:02.701 11224 11224 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-31 13:01:02.706 11224 11287 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 13:01:02.706 11224 11287 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 13:01:02.706 11224 11287 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 13:01:02.706 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-31 13:01:02.706 11224 11287 I jxcore-log: 
,03-31 13:01:02.711 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 13:01:02.711 11224 11287 I jxcore-log: 
,03-31 13:01:02.711 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 13:01:02.711 11224 11287 I jxcore-log: 
,03-31 13:01:02.716 11224 11287 I jxcore-log: ok 202 is stopped after calling stop
03-31 13:01:02.716 11224 11287 I jxcore-log: 
,03-31 13:01:02.721 11224 11287 I jxcore-log: ok 203 connection to servers manager should fail after stopping
03-31 13:01:02.721 11224 11287 I jxcore-log: 
,03-31 13:01:02.726 11224 11287 I jxcore-log: ok 204 connection to router server should fail after stopping
03-31 13:01:02.726 11224 11287 I jxcore-log: 
,03-31 13:01:02.726 11224 11287 I jxcore-log: # teardown
03-31 13:01:02.726 11224 11287 I jxcore-log: 
,03-31 13:01:03.061 11224 11287 I jxcore-log: ok 205 must be stopped
03-31 13:01:03.061 11224 11287 I jxcore-log: 
,03-31 13:01:03.066 11224 11287 I jxcore-log: # setup
03-31 13:01:03.066 11224 11287 I jxcore-log: 
,03-31 13:01:03.301 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 13:01:03.301 11224 11287 I jxcore-log: 
,03-31 13:01:03.306 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 13:01:03.306 11224 11287 I jxcore-log: 
,03-31 13:01:03.311 11224 11287 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 13:01:03.311 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 13:01:03.311 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 13:01:03.311 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 13:01:03.311 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 13:01:03.311 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 13:01:03.311 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 13:01:03.311 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 13:01:03.316 11224 11287 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 13:01:03.321 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 13:01:03.321 11224 11287 I jxcore-log: 
,03-31 13:01:03.326 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 13:01:03.326 11224 11287 I jxcore-log: 
,03-31 13:01:03.331 11224 11287 I jxcore-log: # 51. make sure terminateConnection is properly hooked up
03-31 13:01:03.331 11224 11287 I jxcore-log: 
,03-31 13:01:03.336 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 13:01:03.336 11224 11287 I jxcore-log: 
,03-31 13:01:03.886 11224 11287 I jxcore-log: ok 206 called with right arguments
03-31 13:01:03.886 11224 11287 I jxcore-log: 
,03-31 13:01:03.891 11224 11287 I jxcore-log: # teardown
03-31 13:01:03.891 11224 11287 I jxcore-log: 
,03-31 13:01:04.091 11224 11287 I jxcore-log: ok 207 must be stopped
03-31 13:01:04.091 11224 11287 I jxcore-log: 
,03-31 13:01:04.096 11224 11287 I jxcore-log: # setup
03-31 13:01:04.096 11224 11287 I jxcore-log: 
,03-31 13:01:04.911 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 13:01:04.911 11224 11287 I jxcore-log: 
,03-31 13:01:04.916 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 13:01:04.916 11224 11287 I jxcore-log: 
,03-31 13:01:04.921 11224 11287 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 13:01:04.921 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 13:01:04.921 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 13:01:04.921 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 13:01:04.921 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 13:01:04.921 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 13:01:04.921 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 13:01:04.921 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 13:01:04.926 11224 11287 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 13:01:04.931 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 13:01:04.931 11224 11287 I jxcore-log: 
,03-31 13:01:04.931 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 13:01:04.931 11224 11287 I jxcore-log: 
,03-31 13:01:04.936 11224 11287 I jxcore-log: # 52. make sure terminateListener is properly hooked up
03-31 13:01:04.936 11224 11287 I jxcore-log: 
,03-31 13:01:04.941 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 13:01:04.941 11224 11287 I jxcore-log: 
,03-31 13:01:05.091 11224 11287 I jxcore-log: ok 208 called with right arguments
03-31 13:01:05.091 11224 11287 I jxcore-log: 
,03-31 13:01:05.101 11224 11287 I jxcore-log: # teardown
03-31 13:01:05.101 11224 11287 I jxcore-log: 
,03-31 13:01:05.231 11224 11287 I jxcore-log: ok 209 must be stopped
03-31 13:01:05.231 11224 11287 I jxcore-log: 
,03-31 13:01:05.241 11224 11287 I jxcore-log: # setup
03-31 13:01:05.241 11224 11287 I jxcore-log: 
,03-31 13:01:05.251  3461  6089 D SSRM:n  : SIOP:: AP = 270, PST = 272 (W:12), CUR = 41, LCD = 0
,03-31 13:01:05.376 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 13:01:05.376 11224 11287 I jxcore-log: 
,03-31 13:01:05.381 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 13:01:05.381 11224 11287 I jxcore-log: 
,03-31 13:01:05.386 11224 11287 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 13:01:05.386 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 13:01:05.386 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 13:01:05.386 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 13:01:05.386 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 13:01:05.386 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 13:01:05.386 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 13:01:05.386 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 13:01:05.391  3461  3653 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 13:01:05.391 11224 11287 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
03-31 13:01:05.391  3461  3653 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 13:01:05.391  3461  3653 D BatteryService: online:4, current avg:39, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:39
03-31 13:01:05.391  3461  3653 D BatteryService: stay LED for fully charged
03-31 13:01:05.391  3461  3461 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 13:01:05.396 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 13:01:05.396 11224 11287 I jxcore-log: 
,03-31 13:01:05.396  3461  3461 I MotionRecognitionService: Plugged,
03-31 13:01:05.396  3461  3461 D MotionRecognitionService:   cableConnection= 1
,03-31 13:01:05.396 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native,
03-31 13:01:05.396 11224 11287 I jxcore-log: 
03-31 13:01:05.396  3461  3461 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 13:01:05.396  3461  3461 D MotionRecognitionService: skip setTransmitPower. 
03-31 13:01:05.406  3728  3728 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 13:01:05.406  3728  3728 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 13:01:05.406 11224 11287 I jxcore-log: # 53. make sure we actually call kill connections properly
03-31 13:01:05.406 11224 11287 I jxcore-log: 
03-31 13:01:05.406  3728  3728 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 13:01:05.406 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 13:01:05.406 11224 11287 I jxcore-log: 
,03-31 13:01:05.416  5893  5893 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 13:01:05.416  5893  5980 D HeadsetStateMachine: Disconnected process message: 10
,03-31 13:01:05.426  3728  3728 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 13:01:05.431  3728  3728 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 13:01:05.431  3728  3728 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 13:01:05.431  3728  3728 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 13:01:05.546 11224 11287 I jxcore-log: ok 210 specific error expected
03-31 13:01:05.546 11224 11287 I jxcore-log: 
,03-31 13:01:05.556 11224 11287 I jxcore-log: # teardown
03-31 13:01:05.556 11224 11287 I jxcore-log: 
,03-31 13:01:05.701 11224 11287 I jxcore-log: ok 211 must be stopped
03-31 13:01:05.701 11224 11287 I jxcore-log: 
,03-31 13:01:05.706 11224 11287 I jxcore-log: # setup
03-31 13:01:05.706 11224 11287 I jxcore-log: 
,03-31 13:01:05.861 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 13:01:05.861 11224 11287 I jxcore-log: 
,03-31 13:01:05.866 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 13:01:05.866 11224 11287 I jxcore-log: 
,03-31 13:01:05.876 11224 11287 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 13:01:05.876 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 13:01:05.876 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 13:01:05.876 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 13:01:05.876 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 13:01:05.876 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 13:01:05.876 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 13:01:05.876 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 13:01:05.881 11224 11287 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 13:01:05.881 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 13:01:05.881 11224 11287 I jxcore-log: 
,03-31 13:01:05.886 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 13:01:05.886 11224 11287 I jxcore-log: 
,03-31 13:01:05.891 11224 11287 I jxcore-log: # 54. thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
03-31 13:01:05.891 11224 11287 I jxcore-log: 
,03-31 13:01:05.891 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 13:01:05.891 11224 11287 I jxcore-log: 
,03-31 13:01:06.011 11224 11287 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 13:01:06.011 11224 11287 I jxcore-log: 
,03-31 13:01:06.026 11224 11287 I jxcore-log: DEBUG createNativeListener: listening 35802
03-31 13:01:06.026 11224 11287 I jxcore-log: 
,03-31 13:01:06.031 11224 11287 I jxcore-log: INFO thaliMobileNativeWrapper: routerPortConnectionFailed - {"routerPort":56616,"error":{}}
03-31 13:01:06.031 11224 11287 I jxcore-log: 
,03-31 13:01:06.031 11224 11287 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 13:01:06.031 11224 11287 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 13:01:06.031 11224 11287 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 13:01:06.036 11224 11287 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 13:01:06.036 11224 11287 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 13:01:06.036 11224 11287 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 13:01:06.041 11224 11287 I jxcore-log: ok 212 failure reason is as expected
03-31 13:01:06.041 11224 11287 I jxcore-log: 
,03-31 13:01:06.046 11224 11287 I jxcore-log: ok 213 error description is as expected
03-31 13:01:06.046 11224 11287 I jxcore-log: 
03-31 13:01:06.046 11224 11287 I jxcore-log: ok 214 must be stopped
03-31 13:01:06.046 11224 11287 I jxcore-log: 
,03-31 13:01:06.056 11224 11287 I jxcore-log: # teardown
03-31 13:01:06.056 11224 11287 I jxcore-log: 
,03-31 13:01:06.196 11224 11287 I jxcore-log: ok 215 must be stopped
03-31 13:01:06.196 11224 11287 I jxcore-log: 
,03-31 13:01:06.201 11224 11287 I jxcore-log: # setup
03-31 13:01:06.201 11224 11287 I jxcore-log: 
,03-31 13:01:06.281 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 13:01:06.281 11224 11287 I jxcore-log: 
,03-31 13:01:06.286 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 13:01:06.286 11224 11287 I jxcore-log: 
,03-31 13:01:06.296 11224 11287 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 13:01:06.296 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 13:01:06.296 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 13:01:06.296 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 13:01:06.296 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 13:01:06.296 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 13:01:06.296 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 13:01:06.296 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 13:01:06.296 11224 11287 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 13:01:06.301 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 13:01:06.301 11224 11287 I jxcore-log: 
,03-31 13:01:06.301 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 13:01:06.301 11224 11287 I jxcore-log: 
,03-31 13:01:06.306 11224 11287 I jxcore-log: # 55. We repeat failedConnection event when we get it from thaliTcpServersManager
03-31 13:01:06.306 11224 11287 I jxcore-log: 
,03-31 13:01:06.311 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 13:01:06.311 11224 11287 I jxcore-log: 
,03-31 13:01:06.451 11224 11287 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 13:01:06.451 11224 11287 I jxcore-log: 
,03-31 13:01:06.456 11224 11287 I jxcore-log: DEBUG createNativeListener: listening 36618
03-31 13:01:06.456 11224 11287 I jxcore-log: 
,03-31 13:01:06.461 11224 11287 I jxcore-log: ok 216 peerIdentifier matches
03-31 13:01:06.461 11224 11287 I jxcore-log: 
,03-31 13:01:06.461 11224 11287 I jxcore-log: ok 217 error description matches
03-31 13:01:06.461 11224 11287 I jxcore-log: 
,03-31 13:01:06.466 11224 11287 I jxcore-log: # teardown
03-31 13:01:06.466 11224 11287 I jxcore-log: 
,03-31 13:01:06.551 11224 11287 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-31 13:01:06.551 11224 11287 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 13:01:06.551 11224 11287 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 13:01:06.551 11224 11287 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 13:01:06.551 11224 11287 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-31 13:01:06.551 11224 11287 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 13:01:06.566 11224 11287 I jxcore-log: ok 218 must be stopped
03-31 13:01:06.566 11224 11287 I jxcore-log: 
,03-31 13:01:06.576 11224 11287 I jxcore-log: # setup
03-31 13:01:06.576 11224 11287 I jxcore-log: 
,03-31 13:01:06.696 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 13:01:06.696 11224 11287 I jxcore-log: 
,03-31 13:01:06.701 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 13:01:06.701 11224 11287 I jxcore-log: 
,03-31 13:01:06.711 11224 11287 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 13:01:06.711 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 13:01:06.711 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 13:01:06.711 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 13:01:06.711 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 13:01:06.711 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 13:01:06.711 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 13:01:06.711 11224 11287 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 13:01:06.716 11224 11287 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 13:01:06.716 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 13:01:06.716 11224 11287 I jxcore-log: 
,03-31 13:01:06.721 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 13:01:06.721 11224 11287 I jxcore-log: 
,03-31 13:01:06.731 11224 11287 I jxcore-log: # 56. we successfully receive and replay discoveryAdvertisingStateUpdate
03-31 13:01:06.731 11224 11287 I jxcore-log: 
,03-31 13:01:06.736 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 13:01:06.736 11224 11287 I jxcore-log: 
,03-31 13:01:06.846 11224 11287 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 13:01:06.846 11224 11287 I jxcore-log: 
,03-31 13:01:06.851 11224 11287 I jxcore-log: DEBUG createNativeListener: listening 58595
03-31 13:01:06.851 11224 11287 I jxcore-log: 
,03-31 13:01:06.856 11224 11287 I io.jxcore.node.ConnectionHelper: start: Port number: 56680, start advertisements: false
,03-31 13:01:06.856 11224 11287 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 13:01:06.861 11224 11287 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 13:01:06.861 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-31 13:01:06.861 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-31 13:01:06.861 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 13:01:06.866 11224 11287 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 13:01:06.866  5893 12002 D BtGatt.GattService: registerClient() - UUID=3e349910-5d53-4750-a144-387582702308
,03-31 13:01:06.911  5893  5958 D BtGatt.GattService: onClientRegistered() - UUID=3e349910-5d53-4750-a144-387582702308, clientIf=6
,03-31 13:01:06.911 11224 11233 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-31 13:01:06.911  5893  8993 D BtGatt.GattService: start scan with filters
,03-31 13:01:06.921  5893  8993 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 63
,03-31 13:01:06.921 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 13:01:06.921 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 13:01:06.921 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-31 13:01:06.921  5893  5979 D BtGatt.ScanManager: handling starting scan
03-31 13:01:06.921 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 13:01:06.921  5893  5979 D BtGatt.ScanManager: isFilteringSupported
03-31 13:01:06.921  5893  5979 D BluetoothAdapter: setting StandAloneBleMode
03-31 13:01:06.921 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 13:01:06.921 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-31 13:01:06.921 11224 11224 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-31 13:01:06.921 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
03-31 13:01:06.926 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 13:01:06.926 11224 11287 I io.jxcore.node.ConnectionHelper: start: OK
03-31 13:01:06.926 11224 11224 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 13:01:06.926 11224 11224 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 13:01:06.926 11224 11224 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-31 13:01:06.926  5893  5958 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-31 13:01:06.926  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 13:01:06.926  5893  5979 D BtGatt.ScanManager: allow scan with filters
03-31 13:01:06.926  5893  5979 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-31 13:01:06.926  5893  5979 D BtGatt.ScanManager: set filter index= 9 for clientIf= 6
03-31 13:01:06.926 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 13:01:06.926 11224 11287 I jxcore-log: 
03-31 13:01:06.926  5893  5958 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-31 13:01:06.926  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 13:01:06.926  5893  5979 D BtGatt.ScanManager: Starting BLE batch scan
03-31 13:01:06.926  5893  5979 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-31 13:01:06.926 11224 11287 I jxcore-log: ok 219 discoveryActive matches
03-31 13:01:06.926 11224 11287 I jxcore-log: 
03-31 13:01:06.931  5893  5958 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,03-31 13:01:06.931 11224 11287 I jxcore-log: ok 220 advertisingActive matches
03-31 13:01:06.931 11224 11287 I jxcore-log: 
03-31 13:01:06.931  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 13:01:06.931  5893  5958 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-31 13:01:06.931  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 13:01:06.931 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 13:01:06.931 11224 11287 I jxcore-log: 
03-31 13:01:06.931 11224 11287 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-31 13:01:06.931 11224 11287 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
03-31 13:01:06.931 11224 11287 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-31 13:01:06.931 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-31 13:01:06.931 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-31 13:01:06.931 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-31 13:01:06.931 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-31 13:01:06.931 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-31 13:01:06.931 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-31 13:01:06.936  5893  5903 D BtGatt.GattService: stopScan() - queue size =1
,03-31 13:01:06.936  5893 12003 D BtGatt.GattService: unregisterClient() - clientIf=6
03-31 13:01:06.936  5893  5979 D BtGatt.ScanManager: filter size is 1
03-31 13:01:06.936  5893  5979 D BtGatt.ScanManager: delete FilterIndex - 9
,03-31 13:01:06.936 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 13:01:06.936 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 13:01:06.936 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-31 13:01:06.936 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-31 13:01:06.936 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-31 13:01:06.936 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 13:01:06.936 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 13:01:06.936 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 13:01:06.936  5893  5958 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-31 13:01:06.936  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 13:01:06.936 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-31 13:01:06.936  5893  5979 D BtGatt.ScanManager: stopping BLe Batch
03-31 13:01:06.936 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-31 13:01:06.936 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 13:01:06.936 11224 11224 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 13:01:06.936 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 13:01:06.936 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-31 13:01:06.941  5893  5958 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-31 13:01:06.941  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 13:01:06.941  5893  5979 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-31 13:01:06.946 11224 11224 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-31 13:01:06.946  5893  5958 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
,03-31 13:01:06.946  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 13:01:06.946  5893  5958 D BtGatt.GattService: current time is 268040599280
03-31 13:01:06.946  5893  5958 D BtGatt.GattService: Batch record : [-63, -109, 68, 78, 12, 87, 1, -128, -90, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-31 13:01:06.946  5893  5958 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-31 13:01:06.946  5893  5958 D ScanRecord: parseFromBytes
,03-31 13:01:06.951 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-31 13:01:06.951 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 13:01:06.951 11224 11224 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 13:01:06.951 11224 11224 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 13:01:06.951 11224 11224 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 13:01:06.951 11224 11224 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 13:01:06.951 11224 11224 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 13:01:06.951 11224 11287 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 13:01:06.951 11224 11287 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 13:01:06.951 11224 11287 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 13:01:06.956 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 13:01:06.956 11224 11287 I jxcore-log: 
03-31 13:01:06.956 11224 11287 I jxcore-log: ok 221 discoveryActive matches
03-31 13:01:06.956 11224 11287 I jxcore-log: 
03-31 13:01:06.956 11224 11287 I jxcore-log: ok 222 advertisingActive matches
03-31 13:01:06.956 11224 11287 I jxcore-log: 
,03-31 13:01:06.956 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 13:01:06.956 11224 11287 I jxcore-log: 
,03-31 13:01:06.971 11224 11287 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 13:01:06.971 11224 11287 I jxcore-log: 
,03-31 13:01:06.976 11224 11287 I jxcore-log: DEBUG createNativeListener: listening 37115
03-31 13:01:06.976 11224 11287 I jxcore-log: 
,03-31 13:01:06.981 11224 11287 I io.jxcore.node.ConnectionHelper: start: Port number: 37115, start advertisements: true
,03-31 13:01:06.981 11224 11287 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 13:01:06.981 11224 11287 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-31 13:01:06.981 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-31 13:01:06.981 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-31 13:01:06.981 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 13:01:06.981 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 13:01:06.981 11224 11287 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 13:01:06.986  5893 12002 D BtGatt.GattService: registerClient() - UUID=f3a3bcbd-70c4-4e95-be44-b3822aedf26c
,03-31 13:01:07.026  5893  5958 D BtGatt.GattService: onClientRegistered() - UUID=f3a3bcbd-70c4-4e95-be44-b3822aedf26c, clientIf=6
,03-31 13:01:07.026 11224 11233 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-31 13:01:07.026  5893  8993 D BtGatt.GattService: start scan with filters
,03-31 13:01:07.041  5893  8993 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 64
,03-31 13:01:07.041 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 13:01:07.041 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 13:01:07.041 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-31 13:01:07.041 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 13:01:07.041 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,03-31 13:01:07.041  5893  5979 D BtGatt.ScanManager: handling starting scan
03-31 13:01:07.041  5893  5979 D BtGatt.ScanManager: isFilteringSupported
03-31 13:01:07.041 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 13:01:07.041  5893  5979 D BluetoothAdapter: setting StandAloneBleMode
03-31 13:01:07.041 11224 11224 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 13:01:07.041 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-31 13:01:07.041 11224 11287 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-31 13:01:07.041 11224 11287 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 13:01:07.041 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 13:01:07.041 11224 11287 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-31 13:01:07.046  5893  5958 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-31 13:01:07.046  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 13:01:07.046  5893  5979 D BtGatt.ScanManager: allow scan with filters
,03-31 13:01:07.046  5893  5979 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-31 13:01:07.046  5893  5979 D BtGatt.ScanManager: set filter index= 10 for clientIf= 6
03-31 13:01:07.046  5893  5958 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,03-31 13:01:07.046  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 13:01:07.046  5893  5979 D BtGatt.ScanManager: Starting BLE batch scan
03-31 13:01:07.046  5893  5979 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-31 13:01:07.046  5893 12002 D BtGatt.GattService: registerClient() - UUID=8a43fa9f-b7d6-4ee8-87cf-4f938a07fcfa
03-31 13:01:07.051  5893  5958 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-31 13:01:07.051  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 13:01:07.051  5893  5958 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,03-31 13:01:07.051  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 13:01:07.091  5893  5958 D BtGatt.GattService: onClientRegistered() - UUID=8a43fa9f-b7d6-4ee8-87cf-4f938a07fcfa, clientIf=7
,03-31 13:01:07.091 11224 11234 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-31 13:01:07.111  5893  8993 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 51
03-31 13:01:07.111  5893  5978 D BtGatt.AdvertiseManager: message : 0
,03-31 13:01:07.116  5893  5978 D BtGatt.AdvertiseManager: number of adv instance running0
03-31 13:01:07.116  5893  5978 D BtGatt.AdvertiseManager: size of list is =0
,03-31 13:01:07.121  5893  5978 D BtGatt.AdvertiseManager: starting advertising
,03-31 13:01:07.121  5893  5978 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-31 13:01:07.126  5893  5958 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-31 13:01:07.131  5893  5978 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 13:01:07.131  5893  5958 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
03-31 13:01:07.131  5893  5978 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-31 13:01:07.131  5893  5978 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,03-31 13:01:07.136 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-31 13:01:07.136 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-31 13:01:07.146 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 13:01:07.146 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 13:01:07.146 11224 11287 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-31 13:01:07.146 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-31 13:01:07.146 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...,
03-31 13:01:07.146 11224 11287 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,03-31 13:01:07.146 11224 11287 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,03-31 13:01:07.146 11224 11287 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK,
,03-31 13:01:07.146 11224 11224 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything,
,03-31 13:01:07.146 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess,
,03-31 13:01:07.146 11224 11224 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING,
,03-31 13:01:07.146 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,03-31 13:01:07.146 11224 11224 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
,03-31 13:01:07.146 11224 11224 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
,03-31 13:01:07.146 11224 11224 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true,
,03-31 13:01:07.146 11224 11224 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-31 13:01:07.146 11224 11224 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,03-31 13:01:07.146 11224 11224 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 13:01:07.146 11224 11224 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING,
03-31 13:01:07.146 11224 11224 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true,
,03-31 13:01:07.146 11224 11287 I io.jxcore.node.ConnectionHelper: start: OK,
,03-31 13:01:07.151 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false},
,03-31 13:01:07.151 11224 11287 I jxcore-log: 
03-31 13:01:07.161 11224 12131 D BluetoothSocket: bindListen(): myUserId = 0,
,03-31 13:01:07.161 11224 12131 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback,
03-31 13:01:07.161 11224 12131 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[118]},
,03-31 13:01:07.161 11224 12131 D BluetoothSocket: bindListen(), new LocalSocket 
,03-31 13:01:07.161 11224 12131 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() ,
03-31 13:01:07.161 11224 12131 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1e62bade,
,03-31 13:01:07.161 11224 12131 D BluetoothSocket: channel: 6
,03-31 13:01:07.161 11224 12131 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...,
,03-31 13:01:07.191 11224 11287 I jxcore-log: not ok 223 discoveryActive matches
03-31 13:01:07.191 11224 11287 I jxcore-log: 
,03-31 13:01:07.196 11224 11287 I jxcore-log:   ---
03-31 13:01:07.196 11224 11287 I jxcore-log: 
,03-31 13:01:07.196 11224 11287 I jxcore-log:     operator: equal
03-31 13:01:07.196 11224 11287 I jxcore-log: 
,03-31 13:01:07.196 11224 11287 I jxcore-log:     expected: false
03-31 13:01:07.196 11224 11287 I jxcore-log: 
,03-31 13:01:07.196 11224 11287 I jxcore-log:     actual:   true
03-31 13:01:07.196 11224 11287 I jxcore-log: 
,03-31 13:01:07.201 11224 11287 I jxcore-log:   ...
03-31 13:01:07.201 11224 11287 I jxcore-log: 
,03-31 13:01:07.206 11224 11287 I jxcore-log: not ok 224 advertisingActive matches
03-31 13:01:07.206 11224 11287 I jxcore-log: 
,03-31 13:01:07.206 11224 11287 I jxcore-log:   ---
03-31 13:01:07.206 11224 11287 I jxcore-log: 
,03-31 13:01:07.206 11224 11287 I jxcore-log:     operator: equal
03-31 13:01:07.206 11224 11287 I jxcore-log: 
,03-31 13:01:07.211 11224 11287 I jxcore-log:     expected: true
03-31 13:01:07.211 11224 11287 I jxcore-log: 
,03-31 13:01:07.211 11224 11287 I jxcore-log:     actual:   false
03-31 13:01:07.211 11224 11287 I jxcore-log: 
,03-31 13:01:07.211 11224 11287 I jxcore-log:   ...
03-31 13:01:07.211 11224 11287 I jxcore-log: 
,03-31 13:01:07.216 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 13:01:07.216 11224 11287 I jxcore-log: 
,03-31 13:01:07.216 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-31 13:01:07.216 11224 11287 I jxcore-log: 
,03-31 13:01:07.221 11224 11287 I jxcore-log: not ok 225 discoveryActive matches
03-31 13:01:07.221 11224 11287 I jxcore-log: 
,03-31 13:01:07.221 11224 11287 I jxcore-log:   ---
03-31 13:01:07.221 11224 11287 I jxcore-log: 
,03-31 13:01:07.226 11224 11287 I jxcore-log:     operator: equal
03-31 13:01:07.226 11224 11287 I jxcore-log: 
,03-31 13:01:07.226 11224 11287 I jxcore-log:     expected: false
03-31 13:01:07.226 11224 11287 I jxcore-log: 
,03-31 13:01:07.226 11224 11287 I jxcore-log:     actual:   true
03-31 13:01:07.226 11224 11287 I jxcore-log: 
,03-31 13:01:07.226 11224 11287 I jxcore-log:   ...
03-31 13:01:07.226 11224 11287 I jxcore-log: 
,03-31 13:01:07.231 11224 11287 I jxcore-log: not ok 226 advertisingActive matches
03-31 13:01:07.231 11224 11287 I jxcore-log: 
,03-31 13:01:07.231 11224 11287 I jxcore-log:   ---
03-31 13:01:07.231 11224 11287 I jxcore-log: 
,03-31 13:01:07.231 11224 11287 I jxcore-log:     operator: equal
03-31 13:01:07.231 11224 11287 I jxcore-log: 
,03-31 13:01:07.236 11224 11287 I jxcore-log:     expected: false
03-31 13:01:07.236 11224 11287 I jxcore-log: 
,03-31 13:01:07.236 11224 11287 I jxcore-log:     actual:   true
03-31 13:01:07.236 11224 11287 I jxcore-log: 
,03-31 13:01:07.236 11224 11287 I jxcore-log:   ...
03-31 13:01:07.236 11224 11287 I jxcore-log: 
,03-31 13:01:07.236 11224 11287 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 13:01:07.241 11224 11287 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
,03-31 13:01:07.241 11224 11287 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-31 13:01:07.241 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,03-31 13:01:07.241 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-31 13:01:07.241 11224 11287 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2aad64bf, channel: 6, state: LISTENING
,03-31 13:01:07.241 11224 11287 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2aad64bf, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1e62bade, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2b40478cmSocket: android.net.LocalSocket@22734ed5 impl:android.net.LocalSocketImpl@1adba6ea fd:FileDescriptor[118]
,03-31 13:01:07.241 11224 11287 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@22734ed5 impl:android.net.LocalSocketImpl@1adba6ea fd:FileDescriptor[118]
,03-31 13:01:07.241 11224 11287 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-31 13:01:07.241 11224 12131 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-31 13:01:07.241 11224 12131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-31 13:01:07.241 11224 12131 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-31 13:01:07.246 11224 11224 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-31 13:01:07.246 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-31 13:01:07.246 11224 11224 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-31 13:01:07.246 11224 11224 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-31 13:01:07.246 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-31 13:01:07.246 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-31 13:01:07.246 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-31 13:01:07.246 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-31 13:01:07.246 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-31 13:01:07.251  5893  8993 D BtGatt.GattService: stopScan() - queue size =1,
03-31 13:01:07.251  5893  5979 D BtGatt.ScanManager: filter size is 1
03-31 13:01:07.251  5893  5979 D BtGatt.ScanManager: delete FilterIndex - 10
03-31 13:01:07.251  5893  5958 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,03-31 13:01:07.251  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,03-31 13:01:07.251  5893  5979 D BtGatt.ScanManager: stopping BLe Batch
03-31 13:01:07.256  5893  5958 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,03-31 13:01:07.256  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 13:01:07.256  5893  5979 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-31 13:01:07.256  5893  5958 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0,
,03-31 13:01:07.256  5893  5958 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 13:01:07.261  5893  5905 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-31 13:01:07.261 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
03-31 13:01:07.261 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED,
,03-31 13:01:07.261 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false,
03-31 13:01:07.261 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-31 13:01:07.261 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING],
03-31 13:01:07.261 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-31 13:01:07.261 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...,
,03-31 13:01:07.266  5893  5978 D BtGatt.AdvertiseManager: message : 1
03-31 13:01:07.266  5893  5978 D BtGatt.AdvertiseManager: stop advertise for client 7
,03-31 13:01:07.266  5893  5978 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-31 13:01:07.266  5893  5978 D BtGatt.AdvertiseManager: logClientsSet() - status: -1,
,03-31 13:01:07.271  5893  5958 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-31 13:01:07.271  5893  5958 D BtGatt.GattService: Client app is not null!
03-31 13:01:07.271  5893 12003 D BtGatt.GattService: unregisterClient() - clientIf=7
03-31 13:01:07.276 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 13:01:07.276 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,03-31 13:01:07.276 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-31 13:01:07.276 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-31 13:01:07.276 11224 11287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,03-31 13:01:07.276 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false,
,03-31 13:01:07.276 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 13:01:07.276 11224 11287 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-31 13:01:07.276 11224 11287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-31 13:01:07.276 11224 11287 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 13:01:07.276 11224 11224 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 13:01:07.276 11224 11224 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-31 13:01:07.276 11224 11224 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 13:01:07.276 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 13:01:07.276 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-31 13:01:07.281 11224 11287 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 13:01:07.281 11224 11287 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 13:01:07.281 11224 11287 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-31 13:01:07.281 11224 11224 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-31 13:01:07.291 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-31 13:01:07.291 11224 11224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-31 13:01:07.291 11224 11224 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 13:01:07.291 11224 11224 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 13:01:07.291 11224 11224 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-31 13:01:07.291 11224 11224 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 13:01:07.296 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-31 13:01:07.296 11224 11287 I jxcore-log: 
,03-31 13:01:07.296 11224 11287 I jxcore-log: ok 227 discoveryActive matches
03-31 13:01:07.296 11224 11287 I jxcore-log: 
,03-31 13:01:07.301 11224 11287 I jxcore-log: not ok 228 advertisingActive matches
03-31 13:01:07.301 11224 11287 I jxcore-log: 
,03-31 13:01:07.301 11224 11287 I jxcore-log:   ---
03-31 13:01:07.301 11224 11287 I jxcore-log: 
03-31 13:01:07.301 11224 11287 I jxcore-log:     operator: equal
03-31 13:01:07.301 11224 11287 I jxcore-log: 
03-31 13:01:07.301 11224 11287 I jxcore-log:     expected: false
03-31 13:01:07.301 11224 11287 I jxcore-log: 
03-31 13:01:07.301 11224 11287 I jxcore-log:     actual:   true
03-31 13:01:07.301 11224 11287 I jxcore-log: 
03-31 13:01:07.301 11224 11287 I jxcore-log:   ...
03-31 13:01:07.301 11224 11287 I jxcore-log: 
,03-31 13:01:07.301 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 13:01:07.301 11224 11287 I jxcore-log: 
,03-31 13:01:07.306 11224 11287 I jxcore-log: ok 229 discoveryActive matches
03-31 13:01:07.306 11224 11287 I jxcore-log: 
,03-31 13:01:07.306 11224 11287 I jxcore-log: ok 230 advertisingActive matches
03-31 13:01:07.306 11224 11287 I jxcore-log: 
,03-31 13:01:07.306 11224 11287 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 13:01:07.306 11224 11287 I jxcore-log: 
,03-31 13:01:07.321 11224 11287 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 13:01:07.321 11224 11287 I jxcore-log: 
,03-31 13:01:07.321 11224 11287 I jxcore-log: DEBUG createNativeListener: listening 37000
03-31 13:01:07.321 11224 11287 I jxcore-log: 
,03-31 13:01:07.336 11224 11287 E jxcore-log: Trace: [Error: Call Stop!]
03-31 13:01:07.336 11224 11287 E jxcore-log:     at $3.prototype.trace@console.js:139:8
03-31 13:01:07.336 11224 11287 E jxcore-log:     at @/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:38:3
03-31 13:01:07.336 11224 11287 E jxcore-log:     at emit@events.js:98:1
03-31 13:01:07.336 11224 11287 E jxcore-log:     at handlers.reject/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/thali/node_modules/lie/lib/index.js:128:11
03-31 13:01:07.336 11224 11287 E jxcore-log:     at nextTick@/data/data/com.test.thalitest/files/www/jxcore/node_modules/immediate/lib/index.js:61:7
03-31 13:01:07.336 11224 11287 E jxcore-log:     at $0a@node.js:917:1
03-31 13:01:07.336 11224 11287 E jxcore-log: 
,03-31 13:01:07.336 11224 11287 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
03-31 13:01:07.336 11224 11287 I jxcore-log: 
,03-31 13:01:07.341 11224 11287 I jxcore-log: # teardown
03-31 13:01:07.341 11224 11287 I jxcore-log: 
,03-31 13:01:07.761 12139 12139 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,03-31 13:01:07.766 12139 12139 D AndroidRuntime: CheckJNI is OFF
,03-31 13:01:07.766 12139 12139 D AndroidRuntime: readGMSProperty: start
03-31 13:01:07.766 12139 12139 D AndroidRuntime: readGMSProperty: already setted!!
03-31 13:01:07.766 12139 12139 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-31 13:01:07.766 12139 12139 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-31 13:01:07.766 12139 12139 D AndroidRuntime: readGMSProperty: end
03-31 13:01:07.766 12139 12139 D AndroidRuntime: addProductProperty: start
,03-31 13:01:07.861 12139 12139 E AffinityControl: AffinityControl: registerfunction enter
,03-31 13:01:07.876 12139 12139 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,03-31 13:01:07.891  3461  3653 D PackageManager: START PACKAGE DELETE: observer{80471911}
03-31 13:01:07.891  3461  3653 D PackageManager: pkg{<packageName>}
03-31 13:01:07.891  3461  3653 D PackageManager: user{0}
03-31 13:01:07.891  3461  3653 D PackageManager: caller{2000}
03-31 13:01:07.891  3461  3653 D PackageManager: flags{2}
03-31 13:01:07.891  3461  3653 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
03-31 13:01:07.891  3461  3653 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
03-31 13:01:07.891  3461  3653 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
03-31 13:01:07.891  3461  3653 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
03-31 13:01:07.891  3461  3587 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
03-31 13:01:07.891  3461  3653 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
03-31 13:01:07.891  3461  3587 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
03-31 13:01:07.891  3461  3587 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
03-31 13:01:07.891  3461  3587 D ApplicationPolicy: getApplicationUninstallationEnabled
03-31 13:01:07.891  3461  3587 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,03-31 13:01:07.891  3461  3587 D PackageManager: !@killApplicatoin: 10011, uninstall pkg
,03-31 13:01:07.896  3461  3568 I ActivityManager: Force stopping com.test.thalitest appid=10011 user=-1: uninstall pkg
,03-31 13:01:07.896  3461  3568 I ActivityManager: Killing 11224:com.test.thalitest/u0a11 (adj 0): stop com.test.thalitest cause uninstall pkg
,03-31 13:01:07.916  3461  3568 I ActivityManager:   Force finishing activity 3 ActivityRecord{20f0167a u0 com.test.thalitest/.MainActivity t42}
,03-31 13:01:07.921  3461  3568 W ActivityManager: mDVFSHelper.acquire()
,03-31 13:01:08.046  3461  3587 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
,03-31 13:01:08.051  3461  3587 W PackageSettings: Skipping PackageSetting{2a9e118 com.example.hello/10691} due to missing metadata
,03-31 13:01:08.061  3461  3629 W InputDispatcher: channel ~ Consumer closed input channel or an error occurred.  events=0x9
03-31 13:01:08.061  3461  3629 E InputDispatcher: channel ~ Channel is unrecoverably broken and will be disposed!
,03-31 13:01:08.106  3461  3587 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,03-31 13:01:08.106  3461  3568 D PowerManagerService: setKeyboardVisibility: false
,03-31 13:01:08.106  3461  3568 I ActivityManager: Skip updateThumbnail for r=ActivityRecord{be3c2b6 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t40}
,03-31 13:01:08.111  3461  4440 I WindowState: WIN DEATH: Window{2ef614e8 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}
03-31 13:01:08.111  3461  4440 W InputDispatcher: Attempted to unregister already unregistered input channel
03-31 13:01:08.111  2861  3794 I SurfaceFlinger: id=15 Removed NainActivit (6/8)
03-31 13:01:08.111  2861 10970 I SurfaceFlinger: id=15 Removed NainActivit (-2/8)
,03-31 13:01:08.111  2861  3032 I SurfaceFlinger: id=15 Removed NainActivit (-2/8)
,03-31 13:01:08.111  3461  4440 D InputDispatcher: Focus left window: 11224
,03-31 13:01:08.116  3461  4440 D MultiWindowConverter: dismissGuide() : Before attaching the guide view, mForceDismissGuide : false
,03-31 13:01:08.121  3461  3579 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3461 uid:1000
03-31 13:01:08.121  3461  3579 D PointerIcon: setMouseCustomIcon IconType is same.101
03-31 13:01:08.121  3461  3579 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3461 uid:1000
03-31 13:01:08.121  3461  3579 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,03-31 13:01:08.121  3461  3587 I ActivityManager: Force stopping com.test.thalitest appid=10011 user=0: pkg removed
,03-31 13:01:08.121  6571  6571 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(433/onResume)] 
,03-31 13:01:08.126  3461  3587 I ActivityManager:   Force finishing activity 3 ActivityRecord{20f0167a u0 com.test.thalitest/.MainActivity t42 f}
,03-31 13:01:08.126  3461  3587 W ActivityManager: Duplicate finish request for ActivityRecord{20f0167a u0 com.test.thalitest/.MainActivity t42 f}
,03-31 13:01:08.136  6571  6571 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5412/IlIlllIlllllIlIllllI)] Get Postpone Count : 0
,03-31 13:01:08.151  6571  6571 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5134/lIIIIIIIlllllllIIlll)] Get Priority : 0
,03-31 13:01:08.161  6571  6571 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5434/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,03-31 13:01:08.166  6571  6571 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(443/onResume)] Postpone Count : 0
,03-31 13:01:08.176  6571  6571 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5475/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,03-31 13:01:08.181  3928  3928 I art     : Explicit concurrent mark sweep GC freed 1664(87KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 462us total 22.409ms
03-31 13:01:08.181  9216  9216 I art     : Explicit concurrent mark sweep GC freed 2670(151KB) AllocSpace objects, 0(0B) LOS objects, 69% free, 1770KB/5MB, paused 607us total 32.027ms
,03-31 13:01:08.196  3461  3587 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,03-31 13:01:08.211  4131  4131 I art     : Explicit concurrent mark sweep GC freed 22851(1264KB) AllocSpace objects, 2(32KB) LOS objects, 25% free, 6MB/8MB, paused 1.122ms total 78.292ms
,03-31 13:01:08.216  4729  4729 I art     : Explicit concurrent mark sweep GC freed 4622(316KB) AllocSpace objects, 3(48KB) LOS objects, 25% free, 8MB/11MB, paused 1.250ms total 78.740ms
,03-31 13:01:08.221  3461  3694 D TaskPersister: removeObsoleteFile: deleting file=42_task.xml
,03-31 13:01:08.221  3461  3694 D TaskPersister: removeObsoleteFile: deleting file=42_task_thumbnail.png
03-31 13:01:08.221  4017  4017 I art     : Explicit concurrent mark sweep GC freed 16066(922KB) AllocSpace objects, 9(1362KB) LOS objects, 12% free, 56MB/64MB, paused 530us total 58.361ms
,03-31 13:01:08.226  6571  6571 I DBG_DM  : [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : false
03-31 13:01:08.226  3461  3568 D InputDispatcher: Focused application released
,03-31 13:01:08.231  6571  6571 I DBG_DM  : [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(648/IIIIllIlIIlIIIIlllIl)] nWidgetStatus : 2
,03-31 13:01:08.231  6571  6571 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 android.content.ContextWrapper.sendBroadcast:392 com.wssyncmldm.ui.llllIIIllIlIIIIllllI.IIIIllIlIIlIIIIlllIl:651 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:171 com.wssyncmldm.ui.XUIInstallConfirmActivity.onResume:451 
,03-31 13:01:08.241  4729  4740 W SQLiteConnectionPool: A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,03-31 13:01:08.246  3728  3728 D CoverUpdateMonitor: received broadcast android.intent.action.PACKAGE_REMOVED
,03-31 13:01:08.251  4530  4530 E SamsungIME: mOCRHelper is null
,03-31 13:01:08.251  4376  4785 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,03-31 13:01:08.256  3461  3630 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-31 13:01:08.256 10745 10745 D LWLocationManager: getDeviceLocationId :  id = -100
03-31 13:01:08.256 10745 10745 D LocationWidgetApplication: getLastUiLocationId() : mLastUiLocationId = -100
,03-31 13:01:08.261  3461  3655 V NetworkStats: removeUidsLocked() for UIDs [10011]
03-31 13:01:08.261  3461  3655 D NtpTrustedTime: currentTimeMillis() cache hit
03-31 13:01:08.261  3461  3655 V NetworkStats: performPollLocked(flags=0x3)
,03-31 13:01:08.261  3461  3567 D EnterpriseDeviceManagerService: Package has changed for user 0
03-31 13:01:08.261  3461  3567 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
03-31 13:01:08.261  3461  3567 W TextServicesManagerService: no available spell checker services found
,03-31 13:01:08.266  3461  3568 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 13:01:08.266  3461  3568 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 13:01:08.266  3461  3568 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 13:01:08.266  3461  3568 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-31 13:01:08.271  3461  3655 V NetworkStats: performPollLocked() took 11ms
03-31 13:01:08.271  3461  3655 D NtpTrustedTime: currentTimeMillis() cache hit
,03-31 13:01:08.281 12170 12170 E Zygote  : MountEmulatedStorage()
,03-31 13:01:08.281 12170 12170 E Zygote  : v2
03-31 13:01:08.281 12170 12170 I libpersona: KNOX_SDCARD checking this for 10063
03-31 13:01:08.281 12170 12170 I libpersona: KNOX_SDCARD not a persona
,03-31 13:01:08.286 12170 12170 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
,03-31 13:01:08.286  3461  3568 I ActivityManager: Start proc 12170:com.samsung.android.app.vrsetupwizardstub/u0a63 for broadcast-3 com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver
03-31 13:01:08.286 12170 12170 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
,03-31 13:01:08.286  3461  4244 D SettingsProvider: name = SOFTWARE_UPDATE_NOTIFICATION_STATUS
,03-31 13:01:08.291 12170 12170 E Zygote  : accessInfo : 0
,03-31 13:01:08.291 12170 12170 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-31 13:01:08.296  5638  5657 W ResourceType: For resource 0x7f020570, entry index(1392) is beyond type entryCount(787)
03-31 13:01:08.296  5638  5657 W ResourceType: Failure getting entry for 0x7f020570 (t=1 e=1392) (error -75)
,03-31 13:01:08.296  6571  6571 I DBG_DM  : [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(327/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,03-31 13:01:08.311  3985  3985 D RegisteredServicesCache: empty dynamic service
,03-31 13:01:08.311 12170 12170 D TimaKeyStoreProvider: TimaSignature is unavailable
03-31 13:01:08.316 12170 12170 D ActivityThread: Added TimaKeyStore provider
,03-31 13:01:08.326  3461  4440 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8ce5198 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{10453df1 12170:com.samsung.android.app.vrsetupwizardstub/u0a63}
,03-31 13:01:08.331  3985  3985 D RegisteredComponentCache: Collect Tech packages for Knox
,03-31 13:01:08.331  3728  3728 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-31 13:01:08.336  6571  6571 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5134/lIIIIIIIlllllllIIlll)] Get Priority : 0
,03-31 13:01:08.346  3461  3461 I art     : Explicit concurrent mark sweep GC freed 110778(8MB) AllocSpace objects, 104(1665KB) LOS objects, 32% free, 32MB/48MB, paused 2.276ms total 179.250ms
03-31 13:01:08.346  3461  3587 I art     : WaitForGcToComplete blocked for 124.105ms for cause Explicit
03-31 13:01:08.346  3461  3656 D NtpTrustedTime: currentTimeMillis() cache hit
03-31 13:01:08.346  3461  3656 D NtpTrustedTime: currentTimeMillis() cache hit
,03-31 13:01:08.356  3461  4016 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
03-31 13:01:08.356  3461  4016 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,03-31 13:01:08.361 12170 12170 D VRSetupWizardStub/PackageIntentReceiver: onReceive()
03-31 13:01:08.361 12170 12170 D VRSetupWizardStub/PackageIntentReceiver: Action Package Remove
03-31 13:01:08.361 12170 12170 D VRSetupWizardStub/PackageIntentReceiver: packagename:com.test.thalitest
,03-31 13:01:08.361  6571  6571 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5412/IlIlllIlllllIlIllllI)] Get Postpone Count : 0
,03-31 13:01:08.366  3461  3653 I ActivityManager: Killing 10165:com.google.android.apps.docs/u0a101 (adj 15): emptyCount ##31
,03-31 13:01:08.366  3461  3653 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8ce5198 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{44d0f86 7180:com.samsung.klmsagent/u0a21}
,03-31 13:01:08.366  7180  7180 I KLMS-2.5.262: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Mar 31 13:01:08 GMT+02:00 2016
03-31 13:01:08.371  6571  6571 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5054/IIlllIlIIlIllIlllIll)] Get Force status : 0
,03-31 13:01:08.371  3461  3968 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,03-31 13:01:08.376  7180  7180 I KLMS-2.5.262: : KLMSAbstractReciever(): onReceive().END.
,03-31 13:01:08.376  3461  3488 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=14, mSplitNum[1]=26, mSplitNum[2]=38, mBgSplitQueueNum=3 divideNum= 12 r.nextReceiver= 2 receivers.size=50
,03-31 13:01:08.376  3461  3488 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,03-31 13:01:08.376  7180  7180 I KLMS-2.5.262: : KLMSIntentService(): onCreate()
,03-31 13:01:08.376  3461  3568 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 13:01:08.376  3461  3568 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 13:01:08.376  3461  3568 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 13:01:08.376  6571  6571 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5434/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
03-31 13:01:08.376  3461  3568 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-31 13:01:08.381  7180  7180 I KLMS-2.5.262: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
03-31 13:01:08.381  6571  6571 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(537/llIIIIlllllIIllIIllI)] Check Force Install : false
,03-31 13:01:08.381  6571  6571 I DBG_DM  : [llIIlIIlIllIllIlllII(337/IllIlIIIIlIIlIIIllIl)] 
,03-31 13:01:08.381  6571  6571 I DBG_DM  : [llIIlIIlIllIllIlllII(343/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
,03-31 13:01:08.386  7180  7180 I KLMS-2.5.262: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,03-31 13:01:08.386  7180 12187 I KLMS-2.5.262: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.service.KLMSIntentService (has extras) }
03-31 13:01:08.386  7180 12187 D KLMS-2.5.262: : KLMSIntentService(): PACKAGE_REMOVED
03-31 13:01:08.386  7180 12187 I KLMS-2.5.262: : Systemprocess(): listeningToPackageRemoved().START
03-31 13:01:08.386  7180 12187 I KLMS-2.5.262: : Systemprocess(): listeningToPackageRemoved().packageName: com.test.thalitest
03-31 13:01:08.386  7180 12187 I KLMS-2.5.262: : listeningToPackageRemovedforELM().START
03-31 13:01:08.386  7180 12187 I KLMS-2.5.262: : MDMBridge.getInstance()
03-31 13:01:08.386  7180 12187 I KLMS-2.5.262: : MDMBridge.getAllLicenseInfoFromSDK()
,03-31 13:01:08.391  7180 12187 I KLMS-2.5.262: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,03-31 13:01:08.391 12188 12188 E Zygote  : MountEmulatedStorage()
03-31 13:01:08.391 12188 12188 I libpersona: KNOX_SDCARD checking this for 10042
03-31 13:01:08.391 12188 12188 E Zygote  : v2
03-31 13:01:08.391 12188 12188 I libpersona: KNOX_SDCARD not a persona
,03-31 13:01:08.391 12188 12188 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
,03-31 13:01:08.396  7180 12187 I KLMS-2.5.262: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
03-31 13:01:08.396  3461  3567 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,03-31 13:01:08.396 12188 12188 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
,03-31 13:01:08.396 12188 12188 E Zygote  : accessInfo : 0
,03-31 13:01:08.396 12188 12188 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
03-31 13:01:08.401  3461  3568 I ActivityManager: Start proc 12188:com.samsung.android.sdk.samsunglink/u0a42 for broadcast-4 com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver
,03-31 13:01:08.401  7180 12187 I KLMS-2.5.262: : MDMBridge.getAllLicenseInfoFromSDK()
,03-31 13:01:08.401  7180 12187 E KLMS-2.5.262: : arr si null
,03-31 13:01:08.406  3461  3568 V BroadcastQueue: [backgroundsplit_1] Process cur broadcast BroadcastRecord{2dd9f1ae u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{1c6fa3e2 11306:com.samsung.android.sm/1000}
,03-31 13:01:08.406  3461  3568 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 13:01:08.406  3461  3568 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 13:01:08.406  3461  3568 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 13:01:08.406  3461  3568 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-31 13:01:08.406  7180 12187 D KLMS-2.5.262: : DataSource(): Fetched Data from data base count : 0
,03-31 13:01:08.411  7180 12187 I KLMS-2.5.262: : listeningToPackageRemovedforELM().END
03-31 13:01:08.411  7180 12187 I KLMS-2.5.262: : Systemprocess(): listeningToPackageRemovedforKLM().START
03-31 13:01:08.411  7180 12187 I KLMS-2.5.262: : Systemprocess(): .pkgName: com.test.thalitest
03-31 13:01:08.411  3461  3967 D SecContentProvider2: query(), uri = 11 selection = getMyKnoxAdmin
,03-31 13:01:08.421 12203 12203 E Zygote  : MountEmulatedStorage()
03-31 13:01:08.426 12203 12203 E Zygote  : v2
03-31 13:01:08.426 12203 12203 I libpersona: KNOX_SDCARD checking this for 1000
,03-31 13:01:08.426 12203 12203 I libpersona: KNOX_SDCARD not a persona
03-31 13:01:08.426 12188 12188 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-31 13:01:08.426 12203 12203 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
03-31 13:01:08.426 12188 12188 D ActivityThread: Added TimaKeyStore provider
,03-31 13:01:08.426 12203 12203 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
,03-31 13:01:08.426  3461  3568 I ActivityManager: Start proc 12203:com.sec.android.app.popupuireceiver/1000 for broadcast-4 com.sec.android.app.popupuireceiver/.PopupuiReceiver
,03-31 13:01:08.426 12203 12203 E Zygote  : accessInfo : 0
03-31 13:01:08.426 12203 12203 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-31 13:01:08.431  3461  3488 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8ce5198 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{3ab224 6889:com.samsung.aasaservice/1000}
,03-31 13:01:08.431  6889  6889 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
,03-31 13:01:08.436  6889  6889 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,03-31 13:01:08.436  6889  6889 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:334)
03-31 13:01:08.436  6889  6889 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
03-31 13:01:08.436  6889  6889 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3509)
03-31 13:01:08.436  6889  6889 W System.err: 	at android.app.ActivityThread.access$1900(ActivityThread.java:197)
03-31 13:01:08.436  6889  6889 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1758)
03-31 13:01:08.436  6889  6889 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-31 13:01:08.436  6889  6889 W System.err: 	at android.os.Looper.loop(Looper.java:145)
03-31 13:01:08.436  6889  6889 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6872)
03-31 13:01:08.436  6889  6889 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
03-31 13:01:08.436  6889  6889 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-31 13:01:08.436  6889  6889 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
03-31 13:01:08.436  6889  6889 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
,03-31 13:01:08.441 11306 11306 I art     : Explicit concurrent mark sweep GC freed 150(20KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 1735KB/3MB, paused 431us total 20.585ms
,03-31 13:01:08.441  3461  4244 V BroadcastQueue: [backgroundsplit_0] Process cur broadcast BroadcastRecord{3e812547 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{1242b174 12188:com.samsung.android.sdk.samsunglink/u0a42}
,03-31 13:01:08.451 12203 12203 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-31 13:01:08.451 12203 12203 D ActivityThread: Added TimaKeyStore provider
,03-31 13:01:08.451  3461  4440 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-31 13:01:08.456  3461  4440 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-31 13:01:08.456 12188 12188 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-31 13:01:08.456  3461  4440 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-31 13:01:08.456 12188 12188 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,03-31 13:01:08.456  2861  2861 I SurfaceFlinger: id=16 createSurf (1440x2560),1 flag=404, YUIInstallC
,03-31 13:01:08.461  3461  4032 D MultiWindowConverter: dismissGuide() : Before attaching the guide view, mForceDismissGuide : false
03-31 13:01:08.461  3461  3577 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{23ed104f u0 d0 com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}
,03-31 13:01:08.461  3461  3853 V BroadcastQueue: [backgroundsplit_2] Process cur broadcast BroadcastRecord{3287763f u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{3d6ebb0c 12203:com.sec.android.app.popupuireceiver/1000}
,03-31 13:01:08.461  3461  4032 D InputDispatcher: Focus entered window: 6571
,03-31 13:01:08.466  3461  3579 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3461 uid:1000
03-31 13:01:08.466  3461  3579 D PointerIcon: setMouseCustomIcon IconType is same.101
03-31 13:01:08.466  3461  3579 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3461 uid:1000
03-31 13:01:08.466  3461  3579 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
03-31 13:01:08.466  6571  6571 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-31 13:01:08.466  3461  3488 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8ce5198 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{38888fdb 3461:system/1000}
,03-31 13:01:08.466  6571  9247 D mali_winsys: new_window_surface returns 0x3000,  [1440x2560]-format:1
,03-31 13:01:08.471  6571  6571 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(425/onPause)] 
,03-31 13:01:08.476  3461  3488 V BroadcastQueue: [backgroundsplit_1] Process cur broadcast BroadcastRecord{2dd9f1ae u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{1c6fa3e2 11306:com.samsung.android.sm/1000}
,03-31 13:01:08.481  3461  3968 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-31 13:01:08.486  7180 12187 D KLMS-2.5.262: : KLMSUtility(): IsPackageExistInDevice().mAppInfoList: 322
03-31 13:01:08.486  3461  3968 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 11224 uid 10011
03-31 13:01:08.486  7180 12187 D KLMS-2.5.262: : KLMSSharedPreferences(): deleteNotificationAppList().pkgName: com.test.thalitest
03-31 13:01:08.486  7180 12187 I KLMS-2.5.262: : KLMSSharedPreferences(): getNotificationAppList(): null
03-31 13:01:08.486  7180 12187 I KLMS-2.5.262: : Systemprocess(): Notification App List is Null. Remove Notification.
,03-31 13:01:08.491 12203 12203 D PopupuiReceiver: onReceive() getAction : android.intent.action.PACKAGE_REMOVED
,03-31 13:01:08.491  3461  3488 V BroadcastQueue: [backgroundsplit_1] Process cur broadcast BroadcastRecord{2dd9f1ae u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{1c6fa3e2 11306:com.samsung.android.sm/1000}
,03-31 13:01:08.491  4530  4530 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,03-31 13:01:08.496  3461  3653 D SecContentProvider2: query(), uri = -1 selection = getSealedState
,03-31 13:01:08.501 11306 12218 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
,03-31 13:01:08.501  3461  4244 D SecContentProvider2: query(), uri = 15 selection = getSealedHideNotificationMessages
,03-31 13:01:08.506  7180 12187 D KLMS-2.5.262: : DataSource(): Fetched Data from data base count : 0
,03-31 13:01:08.506  7180 12187 I KLMS-2.5.262: : Systemprocess(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
03-31 13:01:08.506  7180 12187 I KLMS-2.5.262: : Systemprocess(): listeningToPackageRemovedforKLM().END
03-31 13:01:08.506  7180 12187 I KLMS-2.5.262: : Systemprocess(): listeningToPackageRemoved().END
,03-31 13:01:08.506  3461  3968 E ActivityManager: checkUser: useridlist=null, currentuser=0,
03-31 13:01:08.506  3461  3968 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 13:01:08.506 12203 12203 I PopupuiReceiver_KNOX: getSealedHideNotificationMessages : 0,
,03-31 13:01:08.506  3461  3968 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 13:01:08.506  3461  4438 D SecContentProvider2: query(), uri = 15 selection = getCheckCoverPopupState
,03-31 13:01:08.506  3461  3968 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-31 13:01:08.516 12203 12203 I PopupuiReceiver_KNOX: getCheckCoverPopupState : false
,03-31 13:01:08.516 12203 12203 D PopupuiReceiver: Action package removed
,03-31 13:01:08.516  6571  6571 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@38dc2608 time:269612
,03-31 13:01:08.516  6571  6571 V ActivityThread: updateVisibility : ActivityRecord{384c2fd2 token=android.os.BinderProxy@38dc2608 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,03-31 13:01:08.526 12224 12224 E Zygote  : MountEmulatedStorage()
03-31 13:01:08.526 12224 12224 E Zygote  : v2
03-31 13:01:08.526 12224 12224 I libpersona: KNOX_SDCARD checking this for 1000
03-31 13:01:08.526 12224 12224 I libpersona: KNOX_SDCARD not a persona
,03-31 13:01:08.526 12224 12224 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
,03-31 13:01:08.531 12224 12224 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
,03-31 13:01:08.531  3461  3968 I ActivityManager: Start proc 12224:com.samsung.android.app.assistantmenu/1000 for broadcast-4 com.samsung.android.app.assistantmenu/.AssistantMenuReceiver
,03-31 13:01:08.531  7180  7180 I KLMS-2.5.262: : KLMSIntentService(): onDestroy()
,03-31 13:01:08.531  3461  3587 I art     : Explicit concurrent mark sweep GC freed 16996(1035KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 32MB/48MB, paused 6.194ms total 187.429ms
03-31 13:01:08.536 12224 12224 E Zygote  : accessInfo : 0
03-31 13:01:08.536 12224 12224 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-31 13:01:08.541  3461  3579 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{be3c2b6 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t40} time:269636
,03-31 13:01:08.541  3461  3579 W ActivityManager: mDVFSHelper.release()
03-31 13:01:08.541  4017  4017 D Launcher.Model: reloadBadges entered.
03-31 13:01:08.541 10868 10879 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
,03-31 13:01:08.541 10868 10879 D BadgeProvider: sendNotify, [notify] : null
03-31 13:01:08.541 10868 10879 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
03-31 13:01:08.541 10868 10879 D BadgeProvider: update, [uri.query] : null
03-31 13:01:08.541 10868 10879 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-31 13:01:08.541 10868 10879 D BadgeProvider: update, [UpdateCount] : 1
,03-31 13:01:08.546  3461  4032 I ActivityManager: Killing 10429:com.facebook.system/u0a10 (adj 15): emptyCount ##31
,03-31 13:01:08.551 12224 12224 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-31 13:01:08.551 12224 12224 D ActivityThread: Added TimaKeyStore provider
,03-31 13:01:08.561  3461  3968 V BroadcastQueue: [backgroundsplit_2] Process cur broadcast BroadcastRecord{3287763f u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{346856c5 10680:com.samsung.android.snote/u0a160}
,03-31 13:01:08.566 12188 12188 I SL_DEBUG: isLoggable:: isProductShip = 1
,03-31 13:01:08.566 12188 12188 I SL_DEBUG: isLoggable:: SL_DEBUG_EXIST = false
,03-31 13:01:08.571 10745 12177 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-31 13:01:08.581 10868 10879 D BadgeProvider: query, [selection] : null
,03-31 13:01:08.581  3461  3491 V BroadcastQueue: [backgroundsplit_1] Process cur broadcast BroadcastRecord{2dd9f1ae u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{3fccbe79 12224:com.samsung.android.app.assistantmenu/1000}
,03-31 13:01:08.586  3461  3587 D PackageManager: Resopt: Clean up res: /data/app/com.test.thalitest-1/base.apk
03-31 13:01:08.586  3461  3587 D PackageManager: delete codoeFile: 
,03-31 13:01:08.591  3461  3587 D AASAuninstall: userId = 0, info.removedAppID = 10011, info.uid = 10011, packageName = com.test.thalitest
,03-31 13:01:08.591  3461  3587 I AASA_removePackage: UID=10011 Target=com.test.thalitest
,03-31 13:01:08.591  3461  3587 D PackageManager: result of delete: 1{80471911}
,03-31 13:01:08.596  3461  3587 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
03-31 13:01:08.596  3461  3587 D PackageManager: userId{-1}
03-31 13:01:08.596  3461  3587 D PackageManager: andCode{true}
,03-31 13:01:08.601 12139 12139 I art     : System.exit called, status: 0
03-31 13:01:08.601 12139 12139 I AndroidRuntime: VM exiting with result code 0.
,03-31 13:01:08.616 12224 12224 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2129 android.content.ContextWrapper.startService:534 android.content.ContextWrapper.startService:534 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3509 
,03-31 13:01:08.621  3461  3567 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-31 13:01:08.621  3461  3567 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-31 13:01:08.621  3461  3968 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 13:01:08.621  3461  3968 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 13:01:08.621  3461  3968 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 13:01:08.621  3461  3968 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 13:01:08.621 10745 12177 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-31 13:01:08.621 10745 12177 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-31 13:01:08.621 10745 12177 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-31 13:01:08.621 10745 12177 W ResourcesManager: Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
03-31 13:01:08.626  3461  3567 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-31 13:01:08.626  3461  3567 W ResourcesManager: Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,03-31 13:01:08.626  9935 12245 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.test.thalitest
,03-31 13:01:08.626  9935 12245 W System.err: remove failed: EACCES (Permission denied) : /storage/extSdCard/Android/data/com.test.thalitest
03-31 13:01:08.626  9935 12245 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.test.thalitest
03-31 13:01:08.626  9935 12245 W System.err: remove failed: EACCES (Permission denied) : /storage/extSdCard/Android/media/com.test.thalitest
,03-31 13:01:08.626  9935 12245 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/obb/com.test.thalitest
03-31 13:01:08.626  9935 12245 W System.err: remove failed: EACCES (Permission denied) : /storage/extSdCard/Android/obb/com.test.thalitest
,03-31 13:01:08.636 12246 12246 E Zygote  : MountEmulatedStorage()
,03-31 13:01:08.636 12246 12246 E Zygote  : v2
03-31 13:01:08.636 12246 12246 I libpersona: KNOX_SDCARD checking this for 10183
03-31 13:01:08.636 12246 12246 I libpersona: KNOX_SDCARD not a persona
,03-31 13:01:08.636 12246 12246 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
,03-31 13:01:08.641  3461  3968 I ActivityManager: Start proc 12246:com.samsung.android.provider.shootingmodeprovider/u0a183 for broadcast-4 com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver
,03-31 13:01:08.641 12246 12246 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
,03-31 13:01:08.641 12246 12246 E Zygote  : accessInfo : 0
,03-31 13:01:08.641 12246 12246 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-31 13:01:08.646  3461  4439 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
,03-31 13:01:08.646  3461  3461 D RCPManagerService: PackageReceiver onReceive()
03-31 13:01:08.646  3461  3461 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,03-31 13:01:08.646  3461  3461 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
03-31 13:01:08.646  3461  3461 I OTPFW   : PackageRemovalReceiver::onReceive Enter
03-31 13:01:08.646  3461  3461 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10011 container id = 0
,03-31 13:01:08.656  3461  3461 I OTPFW   : ProvisionData::getAllEntries Enter
03-31 13:01:08.656  3461  3461 E OTPFW   : ProvisionData::getAllEntries Table is empty
,03-31 13:01:08.661  3461  3461 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
03-31 13:01:08.661  3461  3461 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
03-31 13:01:08.661  3461  3968 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 13:01:08.661  3461  3968 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 13:01:08.661  3461  3968 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 13:01:08.661  3461  3968 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-31 13:01:08.681 12246 12246 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-31 13:01:08.681 12246 12246 D ActivityThread: Added TimaKeyStore provider
,03-31 13:01:08.681  3461  3968 I ActivityManager: Start proc 12264:com.sec.knox.bridge/1000 for broadcast-4 com.sec.knox.bridge/.PersonaShortcutReceiver
03-31 13:01:08.686  3461  3461 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
03-31 13:01:08.686  3461  3567 D UsbSettingsManager: clearDefaults: com.test.thalitest
03-31 13:01:08.686  3461  3461 V EnterpriseBillingPolicy: uID is 10011
03-31 13:01:08.686  3461  3461 V EnterpriseBillingPolicy: Removed Packageuid is0
03-31 13:01:08.686  3461  3461 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
03-31 13:01:08.686  3461  3567 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
03-31 13:01:08.686  3461  3461 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
03-31 13:01:08.686  3461  3461 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
03-31 13:01:08.686  3461  3461 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
03-31 13:01:08.686  3461  3461 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,03-31 13:01:08.686 12264 12264 E Zygote  : MountEmulatedStorage()
03-31 13:01:08.686 12264 12264 E Zygote  : v2
03-31 13:01:08.686 12264 12264 I libpersona: KNOX_SDCARD checking this for 1000
03-31 13:01:08.686  3461  3461 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
03-31 13:01:08.686 12264 12264 I libpersona: KNOX_SDCARD not a persona
,03-31 13:01:08.691  3461  3461 D SdpManagerService:  ActionReceiver::onReceive() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
03-31 13:01:08.691  3461  3461 D SdpManagerService: ACTION_PACKAGE_REMOVED Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) } DATA= package:com.test.thalitest UID 1000 userId 0
03-31 13:01:08.691  3461  3461 D SdpManagerService: ACTION_PACKAGE_REMOVED packageName:: com.test.thalitest
03-31 13:01:08.691 12264 12264 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
,03-31 13:01:08.696 12264 12264 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
,03-31 13:01:08.696 12264 12264 E Zygote  : accessInfo : 0
,03-31 13:01:08.696 12264 12264 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-31 13:01:08.696  3461  3461 D EnterprisePartitionManager: SND -> {secure_fs remove_enc_dir}
,03-31 13:01:08.696  3461  3589 D EnterprisePartitionManager: RCV <-
03-31 13:01:08.696  3461  3461 D EnterprisePartitionManager: RMV <-
,03-31 13:01:08.701  3461  4440 V BroadcastQueue: [backgroundsplit_2] Process cur broadcast BroadcastRecord{3287763f u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{2110888a 12246:com.samsung.android.provider.shootingmodeprovider/u0a183}
,03-31 13:01:08.706  4017  4017 E Launcher.Model: onPackageRemoved :com.test.thalitest
03-31 13:01:08.711  3461  3968 I ActivityManager: Killing 10413:com.vlingo.midas/u0a34 (adj 15): emptyCount ##31
,03-31 13:01:08.711  3461  3461 E EnterprisePartitionManager: Failed to send commandcom.sec.knox.container.util.DaemonConnector$DaemonArgumentException: command 'secure_fs' failed with '500 3 Command not recognized'
03-31 13:01:08.716  3461  3461 W System.err: java.io.FileNotFoundException: /data/system/users/sdp_engine_list.xml: open failed: ENOENT (No such file or directory)
,03-31 13:01:08.716  3461  3461 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-31 13:01:08.716  3461  3461 W System.err: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
03-31 13:01:08.716  3461  3461 W System.err: 	at com.android.server.SdpManagerService$SdpEngineDatabase$EngineListHandler.getEngineListLocked(SdpManagerService.java:1514)
03-31 13:01:08.716  3461  3461 W System.err: 	at com.android.server.SdpManagerService$SdpEngineDatabase$EngineListHandler.access$1100(SdpManagerService.java:1434)
03-31 13:01:08.716  3461  3461 W System.err: 	at com.android.server.SdpManagerService$SdpEngineDatabase.getEngineListLocked(SdpManagerService.java:1418)
03-31 13:01:08.716  3461  3461 W System.err: 	at com.android.server.SdpManagerService$SdpEngineDatabase.access$2200(SdpManagerService.java:1393)
,03-31 13:01:08.716  3461  3461 W System.err: 	at com.android.server.SdpManagerService.handlePkgRemoved(SdpManagerService.java:2647)
03-31 13:01:08.716  3461  3461 W System.err: 	at com.android.server.SdpManagerService.access$2500(SdpManagerService.java:137)
03-31 13:01:08.716  3461  3461 W System.err: 	at com.android.server.SdpManagerService$ActionReceiver.onReceive(SdpManagerService.java:2719)
03-31 13:01:08.716  3461  3461 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:972)
03-31 13:01:08.716  3461  3461 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
03-31 13:01:08.716  3461  3461 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-31 13:01:08.716  3461  3461 W System.err: 	at android.os.Looper.loop(Looper.java:145)
03-31 13:01:08.716  3461  3461 W System.err: 	at com.android.server.SystemServer.run(SystemServer.java:469)
03-31 13:01:08.716  3461  3461 W System.err: 	at com.android.server.SystemServer.main(SystemServer.java:353)
03-31 13:01:08.716  3461  3461 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
03-31 13:01:08.716  3461  3461 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-31 13:01:08.716  3461  3461 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
03-31 13:01:08.716  3461  3461 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
03-31 13:01:08.716  3461  3461 W System.err: Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
03-31 13:01:08.716  3461  3461 W System.err: 	at libcore.io.Posix.open(Native Method)
03-31 13:01:08.716  3461  3461 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-31 13:01:08.716  3461  3461 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
,03-31 13:01:08.721  3461  3461 W System.err: 	... 18 more
03-31 13:01:08.721  3461  3461 E SdpManagerService: failed to get engine list
,03-31 13:01:08.721 12264 12264 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-31 13:01:08.721  3461  3461 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
03-31 13:01:08.721  3461  6089 D SSRM:bd : MSG_TYPE_APP_REMOVED::
,03-31 13:01:08.721  3461  3461 V EnterpriseBillingPolicy: uID is 10011
03-31 13:01:08.721  3461  3461 V EnterpriseBillingPolicy: Removed Packageuid is0
03-31 13:01:08.721  3461  3461 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
03-31 13:01:08.721 12264 12264 D ActivityThread: Added TimaKeyStore provider
,03-31 13:01:08.736  3461  4438 V BroadcastQueue: [backgroundsplit_1] Process cur broadcast BroadcastRecord{2dd9f1ae u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{175c0971 12264:com.sec.knox.bridge/1000}
,03-31 13:01:08.736  3461  3461 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
03-31 13:01:08.736  3461  3461 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
03-31 13:01:08.736  3461  3461 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
03-31 13:01:08.736  3461  3461 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
03-31 13:01:08.736  3461  3461 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
03-31 13:01:08.741  3461  3461 D KnoxTimeoutHandler: handleActiveUserChange for user 0
03-31 13:01:08.741  3461  3461 E EnterpriseSharedDevicePolicy: isSharedDeviceEnabled
03-31 13:01:08.741  3461  3461 I EnterpriseSharedDevicePolicy: isSharedDeviceEnabled in Service
,03-31 13:01:08.746  3461  3461 I EnterpriseSharedDevicePolicy: Get Result: -1
03-31 13:01:08.746  3461  3461 I EnterpriseSharedDevicePolicy: status: false
03-31 13:01:08.746  3461  3461 I KnoxTimeoutHandler: Shared devices show user statefalse
03-31 13:01:08.746  3461  3461 D PersonaManagerService: getPersonasForUser(): returning null!
,03-31 13:01:08.746  3461  3461 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8ce5198 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{1dd3702b 6155:com.sec.android.service.health/u0a19}
,03-31 13:01:08.751  3461  3461 V AlarmManagerEXT: com.test.thalitest(10011) is removed.
,03-31 13:01:08.751  3728  3728 D PanelView: There is/are notification(s) 
,03-31 13:01:08.756  6155  6155 D com.sec.android.service.health.upgrade.UninstallReceiver: onReceive()
,03-31 13:01:08.756  6155  6155 I com.sec.android.service.health.upgrade.UninstallReceiver: onReceive called  PACKAGE_REMOVED package:com.test.thalitest
03-31 13:01:08.756  6155  6155 D com.sec.android.service.health.upgrade.UninstallReceiver: onReceive() : package name is not s health. Return !!!
,03-31 13:01:08.761  3461  3968 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8ce5198 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{8c8e21f 10745:com.sec.android.widgetapp.locationwidget/u0a22}
03-31 13:01:08.761 12246 12246 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
,03-31 13:01:08.766 10745 10745 D LocationWidgetApplication: getLastUiLocationId() : mLastUiLocationId = -100
,03-31 13:01:08.766 12264 12264 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-31 13:01:08.766  3461  3488 D ActivityManager: startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
,03-31 13:01:08.776  3461  4440 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 13:01:08.776  3461  4440 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 13:01:08.776  3461  4440 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 13:01:08.776  3461  4440 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-31 13:01:08.776  2859  3033 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
03-31 13:01:08.776  2859  3033 W Vold    : Returning OperationFailed - no handler for errno 0
,03-31 13:01:08.781 12188 12188 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
,03-31 13:01:08.781 12188 12188 D SecWifiDisplayUtil: Metadata value : none
,03-31 13:01:08.796  3728  3728 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,03-31 13:01:08.796 12282 12282 E Zygote  : MountEmulatedStorage()
03-31 13:01:08.796 12282 12282 E Zygote  : v2
03-31 13:01:08.796 12282 12282 I libpersona: KNOX_SDCARD checking this for 10190
03-31 13:01:08.796 12282 12282 I libpersona: KNOX_SDCARD not a persona
03-31 13:01:08.801  3461  6120 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-31 13:01:08.801  3728  3728 D PanelView: There is/are notification(s) 
03-31 13:01:08.801  3728  3728 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-31 13:01:08.801 12282 12282 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
03-31 13:01:08.801  3461  4440 I ActivityManager: Start proc 12282:com.sec.android.widgetapp.tapandpay/u0a190 for broadcast-4 com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider
03-31 13:01:08.801  3728  3728 D PanelView: There is/are notification(s) 
03-31 13:01:08.801  3728  3728 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-31 13:01:08.806 12282 12282 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
,03-31 13:01:08.806 12282 12282 E Zygote  : accessInfo : 0
,03-31 13:01:08.806  3461  4440 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 13:01:08.806  3461  4440 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 13:01:08.806  3461  4440 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 13:01:08.806  3461  4440 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-31 13:01:08.806 12282 12282 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-31 13:01:08.811 12264 12264 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
,03-31 13:01:08.826 12282 12282 D TimaKeyStoreProvider: TimaSignature is unavailable
03-31 13:01:08.826 12282 12282 D ActivityThread: Added TimaKeyStore provider
,03-31 13:01:08.831  3461  3967 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
03-31 13:01:08.831  3461  3967 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
,03-31 13:01:08.836 11306 12221 E SQLiteLog: (10) unixWrite() File Descriptor : 25 gets errno : 9
03-31 13:01:08.836 11306 12221 E SQLiteLog: (10) unixWrite() File Descriptor : 25 gets errno : 9
,03-31 13:01:08.836 12297 12297 E Zygote  : MountEmulatedStorage()
03-31 13:01:08.836 12297 12297 I libpersona: KNOX_SDCARD checking this for 1000
03-31 13:01:08.836 12297 12297 E Zygote  : v2
03-31 13:01:08.836 12297 12297 I libpersona: KNOX_SDCARD not a persona
03-31 13:01:08.841 12297 12297 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
03-31 13:01:08.841  3461  4440 I ActivityManager: Start proc 12297:com.sec.pcw.device/1000 for broadcast-3 com.sec.pcw.device/.receiver.SYSTEMReceiver
03-31 13:01:08.841 12297 12297 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
03-31 13:01:08.841 12297 12297 E Zygote  : accessInfo : 0
03-31 13:01:08.846 12297 12297 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-31 13:01:08.851  3461  3602 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/2/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.0
03-31 13:01:08.851  3461  3602 D UsbHostManager: displayNotification : [02h,02h,01h]
,03-31 13:01:08.856  3461  3602 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.1
03-31 13:01:08.856  3461  3602 D UsbHostManager: displayNotification : [0ah,00h,00h]
03-31 13:01:08.856  3461  3602 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/13/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.2
03-31 13:01:08.856  3461  3602 D UsbHostManager: displayNotification : [02h,0dh,00h]
03-31 13:01:08.856  3461  3602 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.3
03-31 13:01:08.856  3461  3602 D UsbHostManager: displayNotification : [0ah,00h,01h]
,03-31 13:01:08.861  3461  3696 D UsbHostManager: usbDeviceRemoved : /dev/bus/usb/001/003
03-31 13:01:08.861  3461  3696 E UsbHostManager: usbDeviceRemoved :: deviceName = /dev/bus/usb/001/003
03-31 13:01:08.861  3461  3696 D UsbSettingsManager: usbDeviceRemoved, sending Intent { act=android.hardware.usb.action.USB_DEVICE_DETACHED (has extras) }
,03-31 13:01:08.861 11306 12221 E SQLiteDatabase: Error inserting name=LPCSystemVersion value=1.0.0
03-31 13:01:08.861 11306 12221 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
03-31 13:01:08.861 11306 12221 E SQLiteDatabase: #################################################################
03-31 13:01:08.861 11306 12221 E SQLiteDatabase: Error Code : 778 (SQLITE_IOERR_WRITE)
03-31 13:01:08.861 11306 12221 E SQLiteDatabase: Caused By : Disk I/O error occurred during 'write' operation.
03-31 13:01:08.861 11306 12221 E SQLiteDatabase: 	(disk I/O error (code 778))
03-31 13:01:08.861 11306 12221 E SQLiteDatabase: #################################################################
03-31 13:01:08.861 11306 12221 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
03-31 13:01:08.861 11306 12221 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
03-31 13:01:08.861 11306 12221 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
03-31 13:01:08.861 11306 12221 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
03-31 13:01:08.861 11306 12221 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
03-31 13:01:08.861 11306 12221 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
03-31 13:01:08.861 11306 12221 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
03-31 13:01:08.861 11306 12221 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
03-31 13:01:08.861 11306 12221 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:188)
03-31 13:01:08.861 11306 12221 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
03-31 13:01:08.861 11306 12221 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
03-31 13:01:08.861 11306 12221 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
03-31 13:01:08.861 11306 12221 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
03-31 13:01:08.861 11306 12221 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
03-31 13:01:08.861 11306 12221 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
03-31 13:01:08.861 11306 12221 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-31 13:01:08.861 11306 12221 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-31 13:01:08.861 11306 12221 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-31 13:01:08.861 11306 12221 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-31 13:01:08.866  3461  3488 V BroadcastQueue: [backgroundsplit_2] Process cur broadcast BroadcastRecord{3287763f u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{1aeec72e 12282:com.sec.android.widgetapp.tapandpay/u0a190}
03-31 13:01:08.866  3461  3853 D ActivityManager: startService callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
,03-31 13:01:08.871  3728  3728 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,03-31 13:01:08.876 12297 12297 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-31 13:01:08.876  3461  4440 I ActivityManager: Killing 10518:com.samsung.android.app.filterinstaller/1000 (adj 15): emptyCount ##31
,03-31 13:01:08.881 12297 12297 D ActivityThread: Added TimaKeyStore provider
03-31 13:01:08.881  3461  3602 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 1d6b/2/310, type = 9/0/0, interface = 9/0/0, devpath = /devices/15510000.usb/usb1/1-0:1.0
03-31 13:01:08.881  3461  3602 D UsbHostManager: displayNotification : [09h,00h,00h]
,03-31 13:01:08.886  3461  4440 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 13:01:08.886  3461  4440 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 13:01:08.886  3461  4440 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 13:01:08.886  3461  4440 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-31 13:01:08.891  2859  3033 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
03-31 13:01:08.891  2859  3033 W Vold    : Returning OperationFailed - no handler for errno 0
,03-31 13:01:08.896 12188 12188 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
,03-31 13:01:08.896 11306 12221 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
,03-31 13:01:08.896 11306 12221 E SQLiteLog: (6922) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
,03-31 13:01:08.901 11306 12221 E SQLiteDatabase: Error inserting name=UT enabled value=false
03-31 13:01:08.901 11306 12221 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 6922)
03-31 13:01:08.901 11306 12221 E SQLiteDatabase: #################################################################
03-31 13:01:08.901 11306 12221 E SQLiteDatabase: Error Code : 6922 (SQLITE_IOERR_LOCK_EBADF)
03-31 13:01:08.901 11306 12221 E SQLiteDatabase: Caused By : I/O error happened due to bad file descriptor. There is possibility the partition changed to read-only.
03-31 13:01:08.901 11306 12221 E SQLiteDatabase: 	(disk I/O error (code 6922))
03-31 13:01:08.901 11306 12221 E SQLiteDatabase: #################################################################
03-31 13:01:08.901 11306 12221 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
03-31 13:01:08.901 11306 12221 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
03-31 13:01:08.901 11306 12221 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
03-31 13:01:08.901 11306 12221 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
03-31 13:01:08.901 11306 12221 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
03-31 13:01:08.901 11306 12221 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
03-31 13:01:08.901 11306 12221 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
03-31 13:01:08.901 11306 12221 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
03-31 13:01:08.901 11306 12221 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:189)
03-31 13:01:08.901 11306 12221 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
03-31 13:01:08.901 11306 12221 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
03-31 13:01:08.901 11306 12221 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
03-31 13:01:08.901 11306 12221 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
03-31 13:01:08.901 11306 12221 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
03-31 13:01:08.901 11306 12221 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
03-31 13:01:08.901 11306 12221 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-31 13:01:08.901 11306 12221 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-31 13:01:08.901 11306 12221 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-31 13:01:08.901 11306 12221 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-31 13:01:08.901 11306 12221 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
,03-31 13:01:08.906 12319 12319 E Zygote  : MountEmulatedStorage()
03-31 13:01:08.906 12319 12319 E Zygote  : v2
03-31 13:01:08.906 12319 12319 I libpersona: KNOX_SDCARD checking this for 10101
03-31 13:01:08.906 12319 12319 I libpersona: KNOX_SDCARD not a persona
,03-31 13:01:08.906 12319 12319 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
,03-31 13:01:08.906  3461  4440 I ActivityManager: Start proc 12319:com.google.android.apps.docs/u0a101 for broadcast-4 com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,03-31 13:01:08.911 12319 12319 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
03-31 13:01:08.911 11306 12221 E SQLiteLog: (6922) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
,03-31 13:01:08.911 12319 12319 E Zygote  : accessInfo : 0
03-31 13:01:08.911 12319 12319 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-31 13:01:08.911 11306 12221 E SQLiteDatabase: Error inserting name=AFP Enabled value=true
03-31 13:01:08.911 11306 12221 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 6922)
03-31 13:01:08.911 11306 12221 E SQLiteDatabase: #################################################################
03-31 13:01:08.911 11306 12221 E SQLiteDatabase: Error Code : 6922 (SQLITE_IOERR_LOCK_EBADF)
03-31 13:01:08.911 11306 12221 E SQLiteDatabase: Caused By : I/O error happened due to bad file descriptor. There is possibility the partition changed to read-only.
03-31 13:01:08.911 11306 12221 E SQLiteDatabase: 	(disk I/O error (code 6922))
03-31 13:01:08.911 11306 12221 E SQLiteDatabase: #################################################################
03-31 13:01:08.911 11306 12221 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
03-31 13:01:08.911 11306 12221 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
03-31 13:01:08.911 11306 12221 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
03-31 13:01:08.911 11306 12221 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
03-31 13:01:08.911 11306 12221 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
03-31 13:01:08.911 11306 12221 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
03-31 13:01:08.911 11306 12221 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
03-31 13:01:08.911 11306 12221 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
03-31 13:01:08.911 11306 12221 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:190)
03-31 13:01:08.911 11306 12221 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
03-31 13:01:08.911 11306 12221 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
03-31 13:01:08.911 11306 12221 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
03-31 13:01:08.911 11306 12221 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
03-31 13:01:08.911 11306 12221 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
03-31 13:01:08.911 11306 12221 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
03-31 13:01:08.911 11306 12221 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-31 13:01:08.911 11306 12221 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-31 13:01:08.911 11306 12221 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-31 13:01:08.911 11306 12221 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-31 13:01:08.911 11306 12221 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-31 13:01:08.911 11306 12221 E SQLiteLog: (6922) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
,03-31 13:01:08.911 11306 12221 E SQLiteDatabase: Error inserting name=SleepDetection Enabled value=false
03-31 13:01:08.911 11306 12221 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 6922)
03-31 13:01:08.911 11306 12221 E SQLiteDatabase: #################################################################
03-31 13:01:08.911 11306 12221 E SQLiteDatabase: Error Code : 6922 (SQLITE_IOERR_LOCK_EBADF)
03-31 13:01:08.911 11306 12221 E SQLiteDatabase: Caused By : I/O error happened due to bad file descriptor. There is possibility the partition changed to read-only.
03-31 13:01:08.911 11306 12221 E SQLiteDatabase: 	(disk I/O error (code 6922))
03-31 13:01:08.911 11306 12221 E SQLiteDatabase: #################################################################
03-31 13:01:08.911 11306 12221 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
03-31 13:01:08.911 11306 12221 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
03-31 13:01:08.911 11306 12221 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
03-31 13:01:08.911 11306 12221 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
03-31 13:01:08.911 11306 12221 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
03-31 13:01:08.911 11306 12221 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
03-31 13:01:08.911 11306 12221 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
03-31 13:01:08.911 11306 12221 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
03-31 13:01:08.911 11306 12221 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:191)
03-31 13:01:08.911 11306 12221 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
03-31 13:01:08.911 11306 12221 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
03-31 13:01:08.911 11306 12221 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
03-31 13:01:08.911 11306 12221 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
03-31 13:01:08.911 11306 12221 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
03-31 13:01:08.911 11306 12221 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
03-31 13:01:08.911 11306 12221 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-31 13:01:08.911 11306 12221 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-31 13:01:08.911 11306 12221 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-31 13:01:08.911 11306 12221 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-31 13:01:08.911 11306 12221 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-31 13:01:08.911  3461  4440 I ActivityManager: Killing 10571:com.samsung.android.intelligenceservice/u0a3 (adj 15): emptyCount ##31
03-31 13:01:08.911 11306 12221 E SQLiteLog: (6922) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
,03-31 13:01:08.916 11306 12221 E SQLiteDatabase: Error inserting name=System Build Version Release value=5.1.1
03-31 13:01:08.916 11306 12221 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 6922)
03-31 13:01:08.916 11306 12221 E SQLiteDatabase: #################################################################
03-31 13:01:08.916 11306 12221 E SQLiteDatabase: Error Code : 6922 (SQLITE_IOERR_LOCK_EBADF)
03-31 13:01:08.916 11306 12221 E SQLiteDatabase: Caused By : I/O error happened due to bad file descriptor. There is possibility the partition changed to read-only.
03-31 13:01:08.916 11306 12221 E SQLiteDatabase: 	(disk I/O error (code 6922))
03-31 13:01:08.916 11306 12221 E SQLiteDatabase: #################################################################
03-31 13:01:08.916 11306 12221 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
03-31 13:01:08.916 11306 12221 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
03-31 13:01:08.916 11306 12221 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
03-31 13:01:08.916 11306 12221 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
03-31 13:01:08.916 11306 12221 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
03-31 13:01:08.916 11306 12221 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
03-31 13:01:08.916 11306 12221 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
03-31 13:01:08.916 11306 12221 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
03-31 13:01:08.916 11306 12221 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:192)
03-31 13:01:08.916 11306 12221 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
03-31 13:01:08.916 11306 12221 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
03-31 13:01:08.916 11306 12221 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
03-31 13:01:08.916 11306 12221 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
03-31 13:01:08.916 11306 12221 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
03-31 13:01:08.916 11306 12221 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
03-31 13:01:08.916 11306 12221 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-31 13:01:08.916 11306 12221 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-31 13:01:08.916 11306 12221 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-31 13:01:08.916 11306 12221 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-31 13:01:08.921 11306 12221 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
,03-31 13:01:08.921 11306 12221 E SQLiteLog: (6922) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
03-31 13:01:08.921 11306 12221 E SQLiteDatabase: Error inserting name=status value=successfully initialized
03-31 13:01:08.921 11306 12221 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 6922)
03-31 13:01:08.921 11306 12221 E SQLiteDatabase: #################################################################
03-31 13:01:08.921 11306 12221 E SQLiteDatabase: Error Code : 6922 (SQLITE_IOERR_LOCK_EBADF)
03-31 13:01:08.921 11306 12221 E SQLiteDatabase: Caused By : I/O error happened due to bad file descriptor. There is possibility the partition changed to read-only.
03-31 13:01:08.921 11306 12221 E SQLiteDatabase: 	(disk I/O error (code 6922))
03-31 13:01:08.921 11306 12221 E SQLiteDatabase: #################################################################
03-31 13:01:08.921 11306 12221 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
03-31 13:01:08.921 11306 12221 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
03-31 13:01:08.921 11306 12221 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
03-31 13:01:08.921 11306 12221 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
03-31 13:01:08.921 11306 12221 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
03-31 13:01:08.921 11306 12221 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
03-31 13:01:08.921 11306 12221 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
03-31 13:01:08.921 11306 12221 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
03-31 13:01:08.921 11306 12221 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:193)
03-31 13:01:08.921 11306 12221 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
03-31 13:01:08.921 11306 12221 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
03-31 13:01:08.921 11306 12221 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
03-31 13:01:08.921 11306 12221 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
03-31 13:01:08.921 11306 12221 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
03-31 13:01:08.921 11306 12221 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
03-31 13:01:08.921 11306 12221 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-31 13:01:08.921 11306 12221 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-31 13:01:08.921 11306 12221 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-31 13:01:08.921 11306 12221 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-31 13:01:08.921  3461  3696 D UsbHostManager: usbDeviceRemoved : /dev/bus/usb/001/001
03-31 13:01:08.921  3461  3696 E UsbHostManager: usbDeviceRemoved :: deviceName = /dev/bus/usb/001/001
,03-31 13:01:08.936 12282 12282 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
03-31 13:01:08.936 12282 12282 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
,03-31 13:01:08.941  3461  3488 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8ce5198 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{2ab9745c 12297:com.sec.pcw.device/1000}
,03-31 13:01:08.941  3461  4016 D ActivityManager: startService callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
,03-31 13:01:08.956  3461  3630 I EventHub: Removing device '/dev/input/event10' due to inotify event,
,03-31 13:01:08.961 12282 12282 I TapandpayWidget:Utils: Clear T&P info.
,03-31 13:01:08.971 12319 12319 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-31 13:01:08.976 12319 12319 D ActivityThread: Added TimaKeyStore provider
03-31 13:01:08.976 12282 12282 D TapandpayWidget:TapandpayAppWidgetProvider: Widget is not attached.
,03-31 13:01:08.981  3461  3833 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 13:01:08.981  3461  3833 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 13:01:08.981  3461  3833 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 13:01:08.981  3461  3833 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-31 13:01:08.996  3461  3630 I EventHub: Removing device '/dev/input/event7' due to inotify event
,03-31 13:01:09.006 11306 11306 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
,03-31 13:01:09.026 12297 12297 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
03-31 13:01:09.026 12297 12297 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
03-31 13:01:09.026 12297 12297 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,03-31 13:01:09.031 12297 12297 E SQLiteLog: (28) failed to open "/data/data/com.sec.pcw.device/databases/value.db" with flag (131138) and mode_t (0) due to error (30)
,03-31 13:01:09.036 12297 12297 E SQLiteDatabase: Failed to open database '/data/data/com.sec.pcw.device/databases/value.db'.
03-31 13:01:09.036 12297 12297 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-31 13:01:09.036 12297 12297 E SQLiteDatabase: #################################################################
03-31 13:01:09.036 12297 12297 E SQLiteDatabase: Error Code : 0 (SQLITE_OK)
03-31 13:01:09.036 12297 12297 E SQLiteDatabase: Caused By : not an error (code 0): Could not open the database in read/write mode.
03-31 13:01:09.036 12297 12297 E SQLiteDatabase: #################################################################
03-31 13:01:09.036 12297 12297 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-31 13:01:09.036 12297 12297 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-31 13:01:09.036 12297 12297 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-31 13:01:09.036 12297 12297 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-31 13:01:09.036 12297 12297 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-31 13:01:09.036 12297 12297 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-31 13:01:09.036 12297 12297 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-31 13:01:09.036 12297 12297 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-31 13:01:09.036 12297 12297 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-31 13:01:09.036 12297 12297 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1585)
03-31 13:01:09.036 12297 12297 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
03-31 13:01:09.036 12297 12297 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-31 13:01:09.036 12297 12297 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-31 13:01:09.036 12297 12297 E SQLiteDatabase: 	at com.sec.pcw.device.contentprovider.DMProvider.onCreate(DMProvider.java:32)
03-31 13:01:09.036 12297 12297 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1737)
03-31 13:01:09.036 12297 12297 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
03-31 13:01:09.036 12297 12297 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:6413)
03-31 13:01:09.036 12297 12297 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:6008)
03-31 13:01:09.036 12297 12297 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5948)
03-31 13:01:09.036 12297 12297 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:197)
03-31 13:01:09.036 12297 12297 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1742)
03-31 13:01:09.036 12297 12297 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-31 13:01:09.036 12297 12297 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-31 13:01:09.036 12297 12297 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6872)
03-31 13:01:09.036 12297 12297 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
03-31 13:01:09.036 12297 12297 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-31 13:01:09.036 12297 12297 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
,03-31 13:01:09.036 12297 12297 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
03-31 13:01:09.036 12297 12297 D AndroidRuntime: Shutting down VM
03-31 13:01:09.041 12297 12297 E AndroidRuntime: FATAL EXCEPTION: main
03-31 13:01:09.041 12297 12297 E AndroidRuntime: Process: com.sec.pcw.device, PID: 12297
03-31 13:01:09.041 12297 12297 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.sec.pcw.device.contentprovider.DMProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-31 13:01:09.041 12297 12297 E AndroidRuntime: #################################################################
03-31 13:01:09.041 12297 12297 E AndroidRuntime: Error Code : 0 (SQLITE_OK)
03-31 13:01:09.041 12297 12297 E AndroidRuntime: Caused By : not an error (code 0): Could not open the database in read/write mode.
03-31 13:01:09.041 12297 12297 E AndroidRuntime: #################################################################
03-31 13:01:09.041 12297 12297 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:6416)
03-31 13:01:09.041 12297 12297 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:6008)
03-31 13:01:09.041 12297 12297 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5948)
03-31 13:01:09.041 12297 12297 E AndroidRuntime: 	at android.app.ActivityThread.access$1700(ActivityThread.java:197)
03-31 13:01:09.041 12297 12297 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1742)
03-31 13:01:09.041 12297 12297 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-31 13:01:09.041 12297 12297 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
03-31 13:01:09.041 12297 12297 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6872)
03-31 13:01:09.041 12297 12297 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
03-31 13:01:09.041 12297 12297 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-31 13:01:09.041 12297 12297 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
03-31 13:01:09.041 12297 12297 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
03-31 13:01:09.041 12297 12297 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-31 13:01:09.041 12297 12297 E AndroidRuntime: #################################################################
03-31 13:01:09.041 12297 12297 E AndroidRuntime: Error Code : 0 (SQLITE_OK)
03-31 13:01:09.041 12297 12297 E AndroidRuntime: Caused By : not an error (code 0): Could not open the database in read/write mode.
03-31 13:01:09.041 12297 12297 E AndroidRuntime: #################################################################
03-31 13:01:09.041 12297 12297 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-31 13:01:09.041 12297 12297 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-31 13:01:09.041 12297 12297 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-31 13:01:09.041 12297 12297 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-31 13:01:09.041 12297 12297 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-31 13:01:09.041 12297 12297 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-31 13:01:09.041 12297 12297 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-31 13:01:09.041 12297 12297 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-31 13:01:09.041 12297 12297 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-31 13:01:09.041 12297 12297 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1585)
03-31 13:01:09.041 12297 12297 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
03-31 13:01:09.041 12297 12297 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-31 13:01:09.041 12297 12297 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-31 13:01:09.041 12297 12297 E AndroidRuntime: 	at com.sec.pcw.device.contentprovider.DMProvider.onCreate(DMProvider.java:32)
03-31 13:01:09.041 12297 12297 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1737)
03-31 13:01:09.041 12297 12297 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
03-31 13:01:09.041 12297 12297 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:6413)
03-31 13:01:09.041 12297 12297 E AndroidRuntime: 	... 11 more
03-31 13:01:09.041  3461  3630 I EventHub: Removing device '/dev/input/event8' due to inotify event
03-31 13:01:09.046 12339 12339 E Zygote  : MountEmulatedStorage()
03-31 13:01:09.046 12339 12339 E Zygote  : v2
03-31 13:01:09.046 12339 12339 I libpersona: KNOX_SDCARD checking this for 10193
03-31 13:01:09.046 12339 12339 I libpersona: KNOX_SDCARD not a persona
03-31 13:01:09.046 12339 12339 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
03-31 13:01:09.046  3461  3833 I ActivityManager: Start proc 12339:com.sec.enterprise.knox.cloudmdm.smdms/u0a193 for broadcast-4 com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver
03-31 13:01:09.051 12339 12339 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
03-31 13:01:09.051 12339 12339 E Zygote  : accessInfo : 0
03-31 13:01:09.051 12339 12339 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-31 13:01:09.051  3461  3833 I ActivityManager: Killing 10585:com.samsung.helphub/1000 (adj 15): emptyCount ##31
,03-31 13:01:09.081  3461  3630 I EventHub: Removing device '/dev/input/event9' due to inotify event
03-31 13:01:09.086  2903  2903 I art     : Explicit concurrent mark sweep GC freed 8747(372KB) AllocSpace objects, 0(0B) LOS objects, 72% free, 1529KB/5MB, paused 496us total 36.919ms
03-31 13:01:09.086  3461  4032 V BroadcastQueue: [backgroundsplit_1] Process cur broadcast BroadcastRecord{2dd9f1ae u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{424283a 12319:com.google.android.apps.docs/u0a101}
03-31 13:01:09.101  3461  3968 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.pcw.device
03-31 13:01:09.106  2903  2903 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 72% free, 1529KB/5MB, paused 596us total 21.177ms
03-31 13:01:09.111 12339 12339 D TimaKeyStoreProvider: TimaSignature is unavailable
03-31 13:01:09.116 10868 10877 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-31 13:01:09.116 10868 10877 E SQLiteLog: (6922) statement aborts at 27: [UPDATE apps SET badgecount=? WHERE package=? AND class=?] disk I/O error
,03-31 13:01:09.116 12339 12339 D ActivityThread: Added TimaKeyStore provider
,03-31 13:01:09.121  3461  3488 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 13:01:09.121  3461  3488 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 13:01:09.121  3461  3630 I EventHub: Removing device '/dev/input/event11' due to inotify event
03-31 13:01:09.121  3461  3488 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 13:01:09.121  3461  3488 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-31 13:01:09.126 10868 10877 E DatabaseUtils: Writing exception to parcel
03-31 13:01:09.126 10868 10877 E DatabaseUtils: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 6922)
03-31 13:01:09.126 10868 10877 E DatabaseUtils: #################################################################
03-31 13:01:09.126 10868 10877 E DatabaseUtils: Error Code : 6922 (SQLITE_IOERR_LOCK_EBADF)
03-31 13:01:09.126 10868 10877 E DatabaseUtils: Caused By : I/O error happened due to bad file descriptor. There is possibility the partition changed to read-only.
03-31 13:01:09.126 10868 10877 E DatabaseUtils: 	(disk I/O error (code 6922))
03-31 13:01:09.126 10868 10877 E DatabaseUtils: #################################################################
03-31 13:01:09.126 10868 10877 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
03-31 13:01:09.126 10868 10877 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
03-31 13:01:09.126 10868 10877 E DatabaseUtils: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
03-31 13:01:09.126 10868 10877 E DatabaseUtils: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
03-31 13:01:09.126 10868 10877 E DatabaseUtils: 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1714)
03-31 13:01:09.126 10868 10877 E DatabaseUtils: 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1660)
03-31 13:01:09.126 10868 10877 E DatabaseUtils: 	at com.sec.android.provider.badge.BadgeProvider.update(BadgeProvider.java:176)
03-31 13:01:09.126 10868 10877 E DatabaseUtils: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:341)
03-31 13:01:09.126 10868 10877 E DatabaseUtils: 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:222)
03-31 13:01:09.126 10868 10877 E DatabaseUtils: 	at android.os.Binder.execTransact(Binder.java:461)
,03-31 13:01:09.131  2903  2903 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 72% free, 1529KB/5MB, paused 448us total 21.085ms
,03-31 13:01:09.171  3461  3630 I EventHub: Removing device '/dev/input/event12' due to inotify event
,03-31 13:01:09.186 12356 12356 E Zygote  : MountEmulatedStorage()
03-31 13:01:09.186 12356 12356 E Zygote  : v2
03-31 13:01:09.186 12356 12356 I libpersona: KNOX_SDCARD checking this for 10045
03-31 13:01:09.186 12356 12356 I libpersona: KNOX_SDCARD not a persona
,03-31 13:01:09.186 12356 12356 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
03-31 13:01:09.191  3461  3488 I ActivityManager: Start proc 12356:com.osp.app.signin/u0a45 for broadcast-4 com.osp.app.signin/com.msc.sa.selfupdate.SelfUpgradeReceiver
,03-31 13:01:09.191 12356 12356 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
,03-31 13:01:09.196 12356 12356 E Zygote  : accessInfo : 0
,03-31 13:01:09.196 12356 12356 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,03-31 13:01:09.216  3461  4439 V BroadcastQueue: [backgroundsplit_2] Process cur broadcast BroadcastRecord{3287763f u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{2a1c8e06 12339:com.sec.enterprise.knox.cloudmdm.smdms/u0a193}
,03-31 13:01:09.236  3461  3630 I EventHub: Removing device '/dev/input/event13' due to inotify event
,03-31 13:01:09.236 12356 12356 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-31 13:01:09.241 12356 12356 D ActivityThread: Added TimaKeyStore provider
03-31 13:01:09.241  3461  4244 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,03-31 13:01:09.251 12339 12339 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-31 13:01:09.266  3461 12371 E DropBoxManagerService: Can't write: system_app_crash
03-31 13:01:09.266  3461 12371 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop227.tmp: open failed: EROFS (Read-only file system)
03-31 13:01:09.266  3461 12371 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-31 13:01:09.266  3461 12371 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-31 13:01:09.266  3461 12371 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-31 13:01:09.266  3461 12371 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-31 13:01:09.266  3461 12371 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-31 13:01:09.266  3461 12371 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$23.run(ActivityManagerService.java:16408)
03-31 13:01:09.266  3461 12371 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-31 13:01:09.266  3461 12371 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-31 13:01:09.266  3461 12371 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-31 13:01:09.266  3461 12371 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-31 13:01:09.266  3461 12371 E DropBoxManagerService: 	... 5 more
03-31 13:01:09.266  3461 12371 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/dropbox/drop227.tmp
03-31 13:01:09.271  3461  4032 V BroadcastQueue: [backgroundsplit_0] Process cur broadcast BroadcastRecord{3e812547 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{127cc7 12356:com.osp.app.signin/u0a45}
03-31 13:01:09.291  3461  3568 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 13:01:09.291  3461  3568 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 13:01:09.291  3461  3568 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 13:01:09.291  3461  3568 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 13:01:09.291  3461  3630 I EventHub: Removing device '/dev/input/event14' due to inotify event
03-31 13:01:09.306 12339 12339 D [0]UMC:UMCContentProvider: @onCreate
03-31 13:01:09.326 12375 12375 E Zygote  : MountEmulatedStorage()
03-31 13:01:09.326 12375 12375 E Zygote  : v2
03-31 13:01:09.326 12375 12375 I libpersona: KNOX_SDCARD checking this for 10035
03-31 13:01:09.326 12375 12375 I libpersona: KNOX_SDCARD not a persona
03-31 13:01:09.326 12375 12375 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
,03-31 13:01:09.331  3461  3568 I ActivityManager: Start proc 12375:com.samsung.android.app.galaxyfinder/u0a35 for broadcast-3 com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver
,03-31 13:01:09.331 12375 12375 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
03-31 13:01:09.336 12375 12375 E Zygote  : accessInfo : 0
03-31 13:01:09.336 12297 12297 I Process : Sending signal. PID: 12297 SIG: 9
03-31 13:01:09.336 12375 12375 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-31 13:01:09.341 12339 12339 D [0]UMC:Core: onCreate(): 
03-31 13:01:09.341 12339 12339 D [0]UMC:Core: @isManagedProfileUser
03-31 13:01:09.341  2857  2857 E lowmemorykiller: Error writing /proc/12297/oom_score_adj; errno=22
,03-31 13:01:09.351  3461  4244 I ActivityManager: Killing 10641:com.sec.android.app.samsungapps/u0a13 (adj 15): emptyCount ##31
,03-31 13:01:09.356 12339 12339 D [0]UMC:Core: userInfo.isManagedProfile() : false
,03-31 13:01:09.356  3461  4244 I ActivityManager: Killing 10603:com.samsung.android.bbc.bbcagent/1000 (adj 15): emptyCount ##32
,03-31 13:01:09.366 12319 12319 E PhotosPlugin: Loading PhotosPlugin
,03-31 13:01:09.411 12356 12356 I SA      : [SSP] onCreated
,03-31 13:01:09.411 12375 12375 D TimaKeyStoreProvider: TimaSignature is unavailable

```
