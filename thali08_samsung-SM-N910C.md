#### Test 648099366fd8e87_thali08_samsung-SM-N910C Logs


```
--------- beginning of system
,04-01 10:28:35.700  3403  3616 V AlarmManager: waitForAlarm result :4
--------- beginning of main
04-01 10:28:35.730  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
04-01 10:28:35.730  3724  3724 I PERF    : received broadcast android.intent.action.TIME_TICK
04-01 10:28:35.730  3724  3724 D KeyguardUpdateMonitor: handleTimeUpdate
04-01 10:28:35.740  3724  3724 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
04-01 10:28:35.745  3724  3724 D SecKeyguardClockView: HomeTimezone(): 1
04-01 10:28:35.755  3724  3724 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
04-01 10:28:35.755  3724  3724 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
04-01 10:28:35.765  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.TIME_TICK
04-01 10:28:35.800  3724  3724 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
04-01 10:28:35.805  3724  3724 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
04-01 10:28:35.805  3724  3724 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
04-01 10:28:35.810  3724  3724 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
04-01 10:28:35.815  3724  3724 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
04-01 10:28:35.815  3724  3724 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
04-01 10:28:35.835  3724  3724 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
04-01 10:28:36.110 11382 11382 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
04-01 10:28:36.120 11382 11382 D AndroidRuntime: CheckJNI is OFF
04-01 10:28:36.120 11382 11382 D AndroidRuntime: readGMSProperty: start
04-01 10:28:36.120 11382 11382 D AndroidRuntime: readGMSProperty: already setted!!
04-01 10:28:36.120 11382 11382 D AndroidRuntime: propertySet: couldn't set property (it is from app)
04-01 10:28:36.120 11382 11382 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
04-01 10:28:36.120 11382 11382 D AndroidRuntime: readGMSProperty: end
04-01 10:28:36.120 11382 11382 D AndroidRuntime: addProductProperty: start
04-01 10:28:36.305 11382 11382 E AffinityControl: AffinityControl: registerfunction enter
04-01 10:28:36.330 11382 11382 D AndroidRuntime: Calling main entry com.android.commands.am.Am
04-01 10:28:36.345  3403  4396 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
04-01 10:28:36.350  3403  4396 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
04-01 10:28:36.385  3403  4396 W ActivityManager: mDVFSHelper.acquire()
04-01 10:28:36.390  3403  4396 V WindowManager: addAppToken: AppWindowToken{24da2fda token=Token{1103a585 ActivityRecord{ef60afc u0 com.test.thalitest/.MainActivity t42}}} to stack=1 task=42 at 0
04-01 10:28:36.395  3403  4396 E ActivityManager: checkUser: useridlist=null, currentuser=0
04-01 10:28:36.395  3403  4396 E ActivityManager: checkUser: useridlist=null, currentuser=0
04-01 10:28:36.395  3403  4396 E ActivityManager: checkUser: useridlist=null, currentuser=0
04-01 10:28:36.395  3403  4396 E ActivityManager: checkUser: useridlist=null, currentuser=0
04-01 10:28:36.400  3403  3581 D PhoneWindow: *FMB* installDecor mIsFloating : false
04-01 10:28:36.400  3403  3581 D PhoneWindow: *FMB* installDecor flags : -2122120936
04-01 10:28:36.400  3403  3581 D SecWifiDisplayUtil: Metadata value : none
04-01 10:28:36.405  3403  3581 V WindowManager: Adding window Window{1a96003d u0 d0 Starting com.test.thalitest} at 3 of 7 (after Window{10f7abb9 u0 d0 com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity})
04-01 10:28:36.410 11399 11399 E Zygote  : MountEmulatedStorage()
04-01 10:28:36.410 11399 11399 E Zygote  : v2
04-01 10:28:36.410 11399 11399 I libpersona: KNOX_SDCARD checking this for 10011
04-01 10:28:36.410 11399 11399 I libpersona: KNOX_SDCARD not a persona
04-01 10:28:36.410 11399 11399 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
04-01 10:28:36.415  3403  4396 I ActivityManager: Start proc 11399:com.test.thalitest/u0a11 for activity com.test.thalitest/.MainActivity
04-01 10:28:36.415  3403  4396 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
04-01 10:28:36.415  3403  4396 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
04-01 10:28:36.415  3403  4396 D InputDispatcher: Focused application set to: xxxx
04-01 10:28:36.415  3403  4396 D MultiWindowConverter: dismissGuide() : Before attaching the guide view, mForceDismissGuide : false
04-01 10:28:36.415  3403  4396 D InputDispatcher: Focus left window: 6603
04-01 10:28:36.415 11399 11399 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
04-01 10:28:36.415 11382 11382 D AndroidRuntime: Shutting down VM
04-01 10:28:36.415 11399 11399 E Zygote  : accessInfo : 0
04-01 10:28:36.420 11399 11399 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
04-01 10:28:36.420  3403  3581 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
04-01 10:28:36.420  3403  3581 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
04-01 10:28:36.420  2859  2859 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=404, uhalitest
04-01 10:28:36.430  3403  3581 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3403 uid:1000
04-01 10:28:36.430  3403  3581 D PointerIcon: setMouseCustomIcon IconType is same.101
04-01 10:28:36.430  3403  3581 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3403 uid:1000
04-01 10:28:36.430  3403  3581 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
04-01 10:28:36.435 11399 11399 D TimaKeyStoreProvider: TimaSignature is unavailable
04-01 10:28:36.435 11399 11399 D ActivityThread: Added TimaKeyStore provider
04-01 10:28:36.440  3403  4407 D PowerManagerService: setKeyboardVisibility: false
04-01 10:28:36.440  3403  3579 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{1a96003d u0 d0 Starting com.test.thalitest}
04-01 10:28:36.445  3403  4407 D ActivityManager:  Launching com.test.thalitest, updated priority
04-01 10:28:36.455  3403  4407 I ActivityManager: Skip updateThumbnail for r=ActivityRecord{ef60afc u0 com.test.thalitest/.MainActivity t42}
04-01 10:28:36.470  2859  3628 I SurfaceFlinger: id=12 Removed YUIInstallC (5/9)
04-01 10:28:36.475  2859  4726 I SurfaceFlinger: id=12 Removed YUIInstallC (-2/9)
04-01 10:28:36.480  6603  6603 V ActivityThread: updateVisibility : ActivityRecord{2cd300e0 token=android.os.BinderProxy@346b9306 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
04-01 10:28:36.625  3403  6140 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,04-01 10:28:36.670 11399 11399 D SecWifiDisplayUtil: Metadata value : none
,04-01 10:28:36.715 11399 11399 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,04-01 10:28:36.725 11399 11399 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 8927-8928)
04-01 10:28:36.725 11399 11399 I LibraryLoader: Expected native library version number "",actual native library version number ""
,04-01 10:28:36.740 11399 11399 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1755779}
,04-01 10:28:36.740 11399 11399 I LibraryLoader: Expected native library version number "",actual native library version number ""
04-01 10:28:36.745 11399 11399 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,04-01 10:28:36.745 11399 11415 W System.err: remove failed: ENOENT (No such file or directory) : /data/data/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
,04-01 10:28:36.765 11399 11399 I BrowserStartupController: Initializing chromium process, singleProcess=true
,04-01 10:28:36.765 11399 11399 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,04-01 10:28:36.765 11399 11399 E SysUtils: ApplicationContext is null in ApplicationStatus
,04-01 10:28:36.785 11399 11399 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
04-01 10:28:36.790 11399 11399 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=37 off=50556 len=3379
04-01 10:28:36.790 11399 11399 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:38 off:7638088 len:1165478
,04-01 10:28:36.865 11399 11438 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,04-01 10:28:36.900 11399 11399 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,04-01 10:28:36.915 11399 11399 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,04-01 10:28:36.930 11399 11399 D PhoneWindow: *FMB* installDecor mIsFloating : false
,04-01 10:28:36.930 11399 11399 D PhoneWindow: *FMB* installDecor flags : -2139027200
,04-01 10:28:36.940 11399 11399 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,04-01 10:28:36.950 11399 11399 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,04-01 10:28:36.950 11399 11399 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,04-01 10:28:37.030 11399 11451 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,04-01 10:28:37.035  3403  3432 V WindowManager: Adding window Window{3906a33a u0 d0 com.test.thalitest/com.test.thalitest.MainActivity} at 3 of 8 (before Window{1a96003d u0 d0 Starting com.test.thalitest})
,04-01 10:28:37.035  3403  4786 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,04-01 10:28:37.035  3403  4786 D KnoxTimeoutHandler: postActiveUserChange for user 0
04-01 10:28:37.035  3403  4786 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,04-01 10:28:37.035  3403  3403 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,04-01 10:28:37.040  3403  3403 E EnterpriseSharedDevicePolicy: isSharedDeviceEnabled
04-01 10:28:37.040  3403  3403 D PersonaManagerService: getPersonasForUser(): returning null!
04-01 10:28:37.040  3403  3403 I EnterpriseSharedDevicePolicy: isSharedDeviceEnabled in Service
04-01 10:28:37.040  3403  3403 I EnterpriseSharedDevicePolicy: Get Result: -1
04-01 10:28:37.040  3403  3403 I EnterpriseSharedDevicePolicy: status: false
04-01 10:28:37.040  3403  3403 I KnoxTimeoutHandler: Shared devices show user statefalse
,04-01 10:28:37.050 11399 11399 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null,
04-01 10:28:37.050 11399 11399 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,04-01 10:28:37.055 11399 11399 D SecWifiDisplayUtil: Metadata value : none
,04-01 10:28:37.065  2859  2859 I SurfaceFlinger: id=15 createSurf (1x1),1 flag=404, NainActivit
,04-01 10:28:37.065  3403  4737 D MultiWindowConverter: dismissGuide() : Before attaching the guide view, mForceDismissGuide : false
,04-01 10:28:37.080  3403  4737 D InputDispatcher: Focus entered window: 11399
,04-01 10:28:37.085  3403  3581 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3403 uid:1000
04-01 10:28:37.085  3403  3581 D PointerIcon: setMouseCustomIcon IconType is same.101
04-01 10:28:37.085  3403  3581 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3403 uid:1000
04-01 10:28:37.085  3403  3581 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
04-01 10:28:37.085 11399 11399 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
04-01 10:28:37.085 11399 11451 I OpenGLRenderer: Initialized EGL, version 1.4
,04-01 10:28:37.090 11399 11451 I OpenGLRenderer: HWUI protection enabled for context ,  &this =0xae42fb50 ,&mEglDisplay = 1 , &mEglConfig = -1266810608 
,04-01 10:28:37.090 11399 11451 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
04-01 10:28:37.090 11399 11451 D OpenGLRenderer: Enabling debug mode 0
,04-01 10:28:37.095 11399 11451 D mali_winsys: new_window_surface returns 0x3000,  [1440x2560]-format:1,
,04-01 10:28:37.095 11399 11399 V ActivityThread: updateVisibility : ActivityRecord{25ddf421 token=android.os.BinderProxy@2e58be2b {com.test.thalitest/com.test.thalitest.MainActivity}} show : true,
,04-01 10:28:37.170  3403  4786 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,04-01 10:28:37.175  3403  3581 I ActivityManager: Displayed Component not be shown by security: +584ms (total +1m20s846ms)
,04-01 10:28:37.175  3724  3724 D PanelView: There is/are notification(s) 
04-01 10:28:37.180  3403  3581 W ActivityManager: mDVFSHelper.release()
,04-01 10:28:37.180  3403  3581 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{ef60afc u0 com.test.thalitest/.MainActivity t42} time:179382
,04-01 10:28:37.180  2859  4727 I SurfaceFlinger: id=14 Removed uhalitest (7/9)
04-01 10:28:37.180  2859  3628 I SurfaceFlinger: id=14 Removed uhalitest (-2/9)
,04-01 10:28:37.205 11399 11399 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
04-01 10:28:37.210 11399 11399 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2e58be2b time:179410
,04-01 10:28:37.235 11399 11399 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 11399
,04-01 10:28:37.345 11399 11399 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,04-01 10:28:37.415 11399 11455 D jxcore_app_log: JniHelper::setJavaVM(0xb449d200), pthread_self() = -1626310528
,04-01 10:28:37.425 11399 11455 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
04-01 10:28:37.425 11399 11455 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
04-01 10:28:37.425 11399 11455 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
04-01 10:28:37.425 11399 11455 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
04-01 10:28:37.425 11399 11455 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
04-01 10:28:37.425 11399 11455 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@360436f6 added. We now have 1 listener(s)
,04-01 10:28:37.425 11399 11455 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: E0:DB:10:14:E2:C0
,04-01 10:28:37.430 11399 11455 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
,04-01 10:28:37.430 11399 11455 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
04-01 10:28:37.430 11399 11455 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
04-01 10:28:37.430 11399 11415 W System.err: remove failed: ENOENT (No such file or directory) : /data/data/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,04-01 10:28:37.435 11399 11455 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
04-01 10:28:37.435 11399 11455 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
04-01 10:28:37.435 11399 11455 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
04-01 10:28:37.435 11399 11455 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: E0:DB:10:14:E2:C0
04-01 10:28:37.435 11399 11455 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
04-01 10:28:37.435 11399 11455 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
04-01 10:28:37.435 11399 11455 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
04-01 10:28:37.435 11399 11455 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
04-01 10:28:37.435 11399 11455 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
04-01 10:28:37.435 11399 11455 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
04-01 10:28:37.435 11399 11455 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
04-01 10:28:37.435 11399 11455 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@679abcd added. We now have 1 listener(s)
04-01 10:28:37.435 11399 11455 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,04-01 10:28:37.435 11399 11455 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,04-01 10:28:37.440 11399 11455 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
04-01 10:28:37.440 11399 11455 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
04-01 10:28:37.440 11399 11455 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
04-01 10:28:37.440 11399 11455 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,04-01 10:28:37.445 11399 11455 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,04-01 10:28:37.445 11399 11455 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is E0:DB:10:14:E2:C0
,04-01 10:28:37.450 11399 11455 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
04-01 10:28:37.450 11399 11455 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
04-01 10:28:37.450 11399 11455 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
04-01 10:28:37.450 11399 11455 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
04-01 10:28:37.450 11399 11455 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
04-01 10:28:37.450 11399 11455 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
04-01 10:28:37.450 11399 11455 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
04-01 10:28:37.450 11399 11455 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,04-01 10:28:37.450 11399 11455 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
04-01 10:28:37.450 11399 11455 D io.jxcore.node.ConnectivityMonitor: start: OK
04-01 10:28:37.450 11399 11455 I io.jxcore.node.LifeCycleMonitor: start: OK
,04-01 10:28:37.450 11399 11399 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,04-01 10:28:37.455 11399 11399 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,04-01 10:28:37.505 11399 11399 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,04-01 10:28:37.960 11399 11462 W jxcore-log: Initializing JXcore engine
04-01 10:28:37.960 11399 11462 W jxcore-log: JXcore engine is ready
,04-01 10:28:37.985  4763  4763 E auditd  : In denial and Property audit_ondenial is set to 1 
,04-01 10:28:37.985  4763  4763 E audit   : type=1400 msg=audit(1459499317.985:196): avc:  denied  { ioctl } for  pid=11462 comm="Thread-1579" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2329 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
04-01 10:28:37.985  3403  3574 D SecurityLogAgent:SEDenialService: Got Modify Event and sending Denial Intent foraudit.log
04-01 10:28:37.985  4763  4763 E audit   :  SEPF_SM-N910C_5.1.1_0038
04-01 10:28:37.985  4763  4763 E audit   : type=1300 msg=audit(1459499317.985:196): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=2 a3=970008d8 items=0 ppid=2902 ppcomm=main pid=11462 auid=4294967295 uid=10011 gid=10011 euid=10011 suid=10011 fsuid=10011 egid=10011 sgid=10011 fsgid=10011 ses=4294967295 tty=(none) comm="Thread-1579" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
04-01 10:28:37.985  4763  4763 E audit   : type=1320 msg=audit(1459499317.985:196): 
,04-01 10:28:37.990  3403  3574 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.android.server.SEDenialService$AuditFileObserver.onEvent:80 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,04-01 10:28:37.990 11399 11462 W jxcore-log: Starting JXcore engine
04-01 10:28:37.990  3403  3574 D SecurityLogAgent:SEDenialService: audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,04-01 10:28:37.990  3403  3567 E ActivityManager: checkUser: useridlist=null, currentuser=0
04-01 10:28:37.990  3403  3567 E ActivityManager: checkUser: useridlist=null, currentuser=0
04-01 10:28:37.990  3403  3567 E ActivityManager: checkUser: useridlist=null, currentuser=0
04-01 10:28:37.990  3403  3567 E ActivityManager: checkUser: useridlist=null, currentuser=0
,04-01 10:28:38.000 11463 11463 E Zygote  : MountEmulatedStorage()
04-01 10:28:38.000 11463 11463 E Zygote  : v2
04-01 10:28:38.000 11463 11463 I libpersona: KNOX_SDCARD checking this for 1000
04-01 10:28:38.000 11463 11463 I libpersona: KNOX_SDCARD not a persona
,04-01 10:28:38.005 11463 11463 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
,04-01 10:28:38.005 11463 11463 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
,04-01 10:28:38.005  3403  3567 I ActivityManager: Start proc 11463:com.samsung.android.securitylogagent/1000 for broadcast-3 com.samsung.android.securitylogagent/.receivers.SeDenialReceiver
04-01 10:28:38.005 11463 11463 E Zygote  : accessInfo : 0
,04-01 10:28:38.010 11463 11463 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,04-01 10:28:38.025 11463 11463 D TimaKeyStoreProvider: TimaSignature is unavailable
,04-01 10:28:38.025 11463 11463 D ActivityThread: Added TimaKeyStore provider
,04-01 10:28:38.030  3403  4396 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{271ae2de u0 samsung.intent.action.knox.DENIAL_NOTIFICATION} DELIVERED for app ProcessRecord{2d466cbf 11463:com.samsung.android.securitylogagent/1000}
,04-01 10:28:38.040 11399 11462 W jxcore-log: Platform android
04-01 10:28:38.040 11399 11462 W jxcore-log: 
04-01 10:28:38.040 11399 11462 W jxcore-log: Process ARCH arm
04-01 10:28:38.040 11399 11462 W jxcore-log: 
,04-01 10:28:38.050 11463 11463 D SecurityLogAgent:  SeDenialReceiver : Intent received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,04-01 10:28:38.050 11463 11463 D SecurityLogAgent:  SeDenialReceiver : File path = null
,04-01 10:28:38.050  3403  3434 I ActivityManager: Killing 10279:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): emptyCount ##31
,04-01 10:28:38.135 11399 11462 I jxcore-log: JXcore Cordova bridge is ready!
04-01 10:28:38.135 11399 11462 I jxcore-log: 
04-01 10:28:38.135 11399 11462 W jxcore-log: JXcore engine is started
,04-01 10:28:38.145 11399 11455 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,04-01 10:28:38.145 11399 11399 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,04-01 10:28:39.400  3403  3690 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/42_task.xml.bak
,04-01 10:28:43.195  3403  3851 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:28:43.200  3403  3851 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:28:43.200  3403  3851 D BatteryService: online:4, current avg:-53, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-183
04-01 10:28:43.200  3403  3851 D BatteryService: stay LED for fully charged
04-01 10:28:43.200  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,04-01 10:28:43.200  3403  3403 I MotionRecognitionService: Plugged
04-01 10:28:43.200  3403  3403 D MotionRecognitionService:   cableConnection= 1
04-01 10:28:43.200  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
04-01 10:28:43.200  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:28:43.200  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:28:43.200  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:28:43.200  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:28:43.205  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
04-01 10:28:43.205  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:28:43.220  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:28:43.220  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:28:43.220  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:28:43.220  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:28:43.885  3403  3616 V AlarmManager: waitForAlarm result :4
,04-01 10:28:43.905 11399 11462 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
04-01 10:28:43.905 11399 11462 I jxcore-log: 
,04-01 10:28:43.905 11399 11462 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
04-01 10:28:43.905 11399 11462 I jxcore-log: 
,04-01 10:28:43.910 11399 11462 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
04-01 10:28:43.910 11399 11462 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
04-01 10:28:43.910 11399 11462 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
04-01 10:28:43.910 11399 11462 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
04-01 10:28:43.910 11399 11462 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
04-01 10:28:43.910 11399 11462 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
04-01 10:28:43.910 11399 11462 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
04-01 10:28:43.910 11399 11462 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,04-01 10:28:43.910 11399 11462 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,04-01 10:28:43.910 11399 11462 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
04-01 10:28:43.910 11399 11462 I jxcore-log: 
,04-01 10:28:43.915 11399 11462 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
04-01 10:28:43.915 11399 11462 I jxcore-log: 
,04-01 10:28:44.240 11399 11462 I jxcore-log: Unit Test app is loaded
04-01 10:28:44.240 11399 11462 I jxcore-log: 
,04-01 10:28:44.240 11399 11462 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
04-01 10:28:44.240 11399 11462 I jxcore-log: 
,04-01 10:28:44.245 11399 11462 I jxcore-log: My device name is: samsung-SM-N910C
04-01 10:28:44.245 11399 11462 I jxcore-log: 
,04-01 10:28:44.245 11399 11399 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
04-01 10:28:44.245 11399 11462 I jxcore-log: WARN testUtils: myNameCallback not set!
04-01 10:28:44.245 11399 11462 I jxcore-log: 
,04-01 10:28:44.335  3403  6140 D SSRM:n  : SIOP:: AP = 280, PST = 267 (W:10), CUR = -53, LCD = 0
,04-01 10:28:46.440  3403  3589 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,04-01 10:28:46.450  3403  3589 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,04-01 10:28:46.620 11399 11462 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
04-01 10:28:46.620 11399 11462 I jxcore-log: 
,04-01 10:28:46.830 11399 11462 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
04-01 10:28:46.830 11399 11462 I jxcore-log: 
,04-01 10:28:46.835 11399 11462 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
04-01 10:28:46.835 11399 11462 I jxcore-log: 
,04-01 10:28:46.835 11399 11462 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
04-01 10:28:46.835 11399 11462 I jxcore-log: 
,04-01 10:28:46.845 11399 11462 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
04-01 10:28:46.845 11399 11462 I jxcore-log: 
,04-01 10:28:46.850 11399 11462 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
04-01 10:28:46.850 11399 11462 I jxcore-log: 
,04-01 10:28:48.070 11399 11462 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
04-01 10:28:48.070 11399 11462 I jxcore-log: 
,04-01 10:28:48.085 11399 11462 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
04-01 10:28:48.085 11399 11462 I jxcore-log: 
,04-01 10:28:48.090 11399 11462 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
04-01 10:28:48.090 11399 11462 I jxcore-log: 
,04-01 10:28:48.160  3403  6173 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,04-01 10:28:48.180 11399 11462 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
04-01 10:28:48.180 11399 11462 I jxcore-log: 
,04-01 10:28:48.230 11399 11462 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
04-01 10:28:48.230 11399 11462 I jxcore-log: 
,04-01 10:28:48.260 11399 11462 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
04-01 10:28:48.260 11399 11462 I jxcore-log: 
,04-01 10:28:48.265 11399 11462 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
04-01 10:28:48.265 11399 11462 I jxcore-log: 
,04-01 10:28:48.345 11399 11462 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
04-01 10:28:48.345 11399 11462 I jxcore-log: 
,04-01 10:28:48.360 11399 11462 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
04-01 10:28:48.360 11399 11462 I jxcore-log: 
,04-01 10:28:48.360 11399 11462 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
04-01 10:28:48.360 11399 11462 I jxcore-log: 
,04-01 10:28:48.365 11399 11462 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
04-01 10:28:48.365 11399 11462 I jxcore-log: 
,04-01 10:28:48.375 11399 11462 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
04-01 10:28:48.375 11399 11462 I jxcore-log: 
,04-01 10:28:48.385 11399 11462 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
04-01 10:28:48.385 11399 11462 I jxcore-log: 
,04-01 10:28:48.435 11399 11462 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
04-01 10:28:48.435 11399 11462 I jxcore-log: 
,04-01 10:28:48.435 11399 11462 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
04-01 10:28:48.435 11399 11462 I jxcore-log: 
,04-01 10:28:48.450 11399 11462 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
04-01 10:28:48.450 11399 11462 I jxcore-log: 
,04-01 10:28:48.455 11399 11462 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,04-01 10:28:48.455 11399 11462 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
04-01 10:28:48.455 11399 11462 I jxcore-log: 
,04-01 10:28:50.465  3403  3863 E Watchdog: !@Sync 6 [04-01 10:28:50.471],
,04-01 10:28:53.345  3403  4028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:28:53.345  3403  4028 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:28:53.345  3403  4028 D BatteryService: online:4, current avg:-55, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:69
,04-01 10:28:53.345  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
04-01 10:28:53.350  3403  4028 D BatteryService: stay LED for fully charged,
,04-01 10:28:53.355  3403  3403 I MotionRecognitionService: Plugged,
04-01 10:28:53.355  3403  3403 D MotionRecognitionService:   cableConnection= 1
,04-01 10:28:53.355  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,04-01 10:28:53.355  3403  3403 D MotionRecognitionService: skip setTransmitPower. ,
04-01 10:28:53.365  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,04-01 10:28:53.365  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:28:53.365  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate,
,04-01 10:28:53.390  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
04-01 10:28:53.390  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
04-01 10:28:53.400  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:28:53.400  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:28:53.400  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:28:53.400  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:28:53.725  2891  4804 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,04-01 10:28:54.360  3403  6140 D SSRM:n  : SIOP:: AP = 290, PST = 265 (W:10), CUR = -55, LCD = 0
,04-01 10:28:59.995  3403  3616 V AlarmManager: waitForAlarm result :8
,04-01 10:29:03.485  3403  4737 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:29:03.485  3403  4737 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:29:03.485  3403  4737 D BatteryService: online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:63
,04-01 10:29:03.485  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,04-01 10:29:03.495  3403  3403 I MotionRecognitionService: Plugged
04-01 10:29:03.495  3403  3403 D MotionRecognitionService:   cableConnection= 1,
04-01 10:29:03.495  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
,04-01 10:29:03.495  3403  3403 D MotionRecognitionService: skip setTransmitPower. ,
,04-01 10:29:03.500  3403  4737 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 14ms
04-01 10:29:03.500  3403  4737 D BatteryService: stay LED for fully charged,
,04-01 10:29:03.510  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,04-01 10:29:03.510  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,04-01 10:29:03.510  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate,
,04-01 10:29:03.530  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
04-01 10:29:03.530  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:29:03.540  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:29:03.540  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:29:03.540  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:29:03.540  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:29:03.980  3403  3583 I PowerManagerService: [PWL] Off : 140s ago
,04-01 10:29:04.385  3403  6140 D SSRM:n  : SIOP:: AP = 270, PST = 266 (W:14), CUR = 8, LCD = 0
,04-01 10:29:07.455 11399 11462 I jxcore-log: TAP version 13
04-01 10:29:07.455 11399 11462 I jxcore-log: 
,04-01 10:29:07.455 11399 11462 I jxcore-log: # setup
04-01 10:29:07.455 11399 11462 I jxcore-log: 
,04-01 10:29:07.635 11399 11462 I jxcore-log: # 1. calling createNativeListener directly rejects
04-01 10:29:07.635 11399 11462 I jxcore-log: 
,04-01 10:29:08.165  3403  6173 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,04-01 10:29:08.185 11399 11462 I jxcore-log: DEBUG createNativeListener: creating native server
04-01 10:29:08.185 11399 11462 I jxcore-log: 
,04-01 10:29:08.195 11399 11462 I jxcore-log: DEBUG createNativeListener: listening 35331
04-01 10:29:08.195 11399 11462 I jxcore-log: 
,04-01 10:29:08.205 11399 11462 I jxcore-log: ok 1 Should throw
04-01 10:29:08.205 11399 11462 I jxcore-log: 
,04-01 10:29:08.205 11399 11462 I jxcore-log: # teardown
04-01 10:29:08.205 11399 11462 I jxcore-log: 
,04-01 10:29:08.400 11399 11462 I jxcore-log: # setup
04-01 10:29:08.400 11399 11462 I jxcore-log: 
,04-01 10:29:08.685 11399 11462 I jxcore-log: # 2. emits incomingConnectionState
04-01 10:29:08.685 11399 11462 I jxcore-log: 
,04-01 10:29:09.420 11399 11462 I jxcore-log: DEBUG createNativeListener: creating native server
04-01 10:29:09.420 11399 11462 I jxcore-log: 
,04-01 10:29:09.430 11399 11462 I jxcore-log: DEBUG createNativeListener: listening 40088
04-01 10:29:09.430 11399 11462 I jxcore-log: 
,04-01 10:29:09.440 11399 11462 I jxcore-log: DEBUG createNativeListener: new incoming socket
04-01 10:29:09.440 11399 11462 I jxcore-log: 
,04-01 10:29:09.445 11399 11462 I jxcore-log: DEBUG createNativeListener: creating incoming mux
04-01 10:29:09.445 11399 11462 I jxcore-log: 
,04-01 10:29:09.460 11399 11462 I jxcore-log: DEBUG createNativeListener: new mux
04-01 10:29:09.460 11399 11462 I jxcore-log: 
,04-01 10:29:09.465 11399 11462 I jxcore-log: ok 2 initial connection state should be CONNECTED
04-01 10:29:09.465 11399 11462 I jxcore-log: 
,04-01 10:29:09.495 11399 11462 I jxcore-log: DEBUG createNativeListener: incoming socket close
04-01 10:29:09.495 11399 11462 I jxcore-log: 
,04-01 10:29:09.495 11399 11462 I jxcore-log: ok 3 final connection state should be DISCONNECTED
04-01 10:29:09.495 11399 11462 I jxcore-log: 
,04-01 10:29:09.505 11399 11462 I jxcore-log: # teardown
04-01 10:29:09.505 11399 11462 I jxcore-log: 
,04-01 10:29:09.645 11399 11462 I jxcore-log: # setup
04-01 10:29:09.645 11399 11462 I jxcore-log: 
,04-01 10:29:09.940 11399 11462 I jxcore-log: # 3. emits routerPortConnectionFailed
04-01 10:29:09.940 11399 11462 I jxcore-log: 
,04-01 10:29:10.090 11399 11462 I jxcore-log: DEBUG createNativeListener: creating native server
04-01 10:29:10.090 11399 11462 I jxcore-log: 
,04-01 10:29:10.095 11399 11462 I jxcore-log: DEBUG createNativeListener: listening 59817
04-01 10:29:10.095 11399 11462 I jxcore-log: 
,04-01 10:29:10.105 11399 11462 I jxcore-log: DEBUG createNativeListener: new incoming socket
04-01 10:29:10.105 11399 11462 I jxcore-log: 
,04-01 10:29:10.110 11399 11462 I jxcore-log: DEBUG createNativeListener: creating incoming mux
04-01 10:29:10.110 11399 11462 I jxcore-log: 
,04-01 10:29:10.110 11399 11462 I jxcore-log: DEBUG createNativeListener: new mux
04-01 10:29:10.110 11399 11462 I jxcore-log: 
,04-01 10:29:10.145 11399 11462 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:10.145 11399 11462 I jxcore-log: 
,04-01 10:29:10.150 11399 11462 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:10.150 11399 11462 I jxcore-log: 
,04-01 10:29:10.155 11399 11462 I jxcore-log: DEBUG createNativeListener: 
04-01 10:29:10.155 11399 11462 I jxcore-log: 
,04-01 10:29:10.155 11399 11462 I jxcore-log: ok 4 tried to connect to right port
04-01 10:29:10.155 11399 11462 I jxcore-log: 
,04-01 10:29:10.155 11399 11462 I jxcore-log: ok 5 failed due to refused connection
04-01 10:29:10.155 11399 11462 I jxcore-log: 
,04-01 10:29:10.160 11399 11462 I jxcore-log: ok 6 routerPortConnectionFailed is emitted
04-01 10:29:10.160 11399 11462 I jxcore-log: 
,04-01 10:29:10.165 11399 11462 I jxcore-log: # teardown
04-01 10:29:10.165 11399 11462 I jxcore-log: 
,04-01 10:29:10.165 11399 11462 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:10.165 11399 11462 I jxcore-log: 
,04-01 10:29:10.385 11399 11462 I jxcore-log: DEBUG createNativeListener: mux close
04-01 10:29:10.385 11399 11462 I jxcore-log: 
,04-01 10:29:10.390 11399 11462 I jxcore-log: # setup
04-01 10:29:10.390 11399 11462 I jxcore-log: 
,04-01 10:29:10.395 11399 11462 I jxcore-log: DEBUG createNativeListener: incoming socket close
04-01 10:29:10.395 11399 11462 I jxcore-log: 
,04-01 10:29:10.640 11399 11462 I jxcore-log: # 4. native server connections all up,
04-01 10:29:10.640 11399 11462 I jxcore-log: 
,04-01 10:29:10.770 11399 11462 I jxcore-log: DEBUG createNativeListener: creating native server
04-01 10:29:10.770 11399 11462 I jxcore-log: 
,04-01 10:29:10.780 11399 11462 I jxcore-log: DEBUG createNativeListener: listening 42809
04-01 10:29:10.780 11399 11462 I jxcore-log: 
,04-01 10:29:10.790 11399 11462 I jxcore-log: DEBUG createNativeListener: new incoming socket
04-01 10:29:10.790 11399 11462 I jxcore-log: 
,04-01 10:29:10.795 11399 11462 I jxcore-log: DEBUG createNativeListener: creating incoming mux
04-01 10:29:10.795 11399 11462 I jxcore-log: 
,04-01 10:29:10.800 11399 11462 I jxcore-log: DEBUG createNativeListener: new mux
04-01 10:29:10.800 11399 11462 I jxcore-log: 
,04-01 10:29:10.830 11399 11462 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:10.830 11399 11462 I jxcore-log: 
,04-01 10:29:10.835 11399 11462 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:10.835 11399 11462 I jxcore-log: 
,04-01 10:29:10.850 11399 11462 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:10.850 11399 11462 I jxcore-log: 
,04-01 10:29:10.855 11399 11462 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:10.855 11399 11462 I jxcore-log: 
,04-01 10:29:10.895 11399 11462 I jxcore-log: ok 7 Send/recvd #1 should be equal length
04-01 10:29:10.895 11399 11462 I jxcore-log: 
,04-01 10:29:10.895 11399 11462 I jxcore-log: ok 8 Send/recvd #1 should be same
04-01 10:29:10.895 11399 11462 I jxcore-log: 
,04-01 10:29:10.900 11399 11462 I jxcore-log: ok 9 Send/recvd #2 should be equal length
04-01 10:29:10.900 11399 11462 I jxcore-log: 
,04-01 10:29:10.900 11399 11462 I jxcore-log: ok 10 Send/recvd #2 should be same
04-01 10:29:10.900 11399 11462 I jxcore-log: 
,04-01 10:29:10.905 11399 11462 I jxcore-log: ok 11 Should be exactly 2 client sockets
04-01 10:29:10.905 11399 11462 I jxcore-log: 
,04-01 10:29:10.915 11399 11462 I jxcore-log: # teardown
04-01 10:29:10.915 11399 11462 I jxcore-log: 
,04-01 10:29:11.035 11399 11462 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:11.035 11399 11462 I jxcore-log: 
,04-01 10:29:11.040 11399 11462 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:11.040 11399 11462 I jxcore-log: 
,04-01 10:29:11.045 11399 11462 I jxcore-log: DEBUG createNativeListener: mux close
04-01 10:29:11.045 11399 11462 I jxcore-log: 
,04-01 10:29:11.050 11399 11462 I jxcore-log: # setup
04-01 10:29:11.050 11399 11462 I jxcore-log: 
,04-01 10:29:11.055 11399 11462 I jxcore-log: DEBUG createNativeListener: incoming socket close
04-01 10:29:11.055 11399 11462 I jxcore-log: 
,04-01 10:29:11.170 11399 11462 I jxcore-log: # 5. native server - closing incoming stream cleans outgoing socket
04-01 10:29:11.170 11399 11462 I jxcore-log: 
,04-01 10:29:11.250 11399 11462 I jxcore-log: DEBUG createNativeListener: creating native server
04-01 10:29:11.250 11399 11462 I jxcore-log: 
,04-01 10:29:11.250 11399 11462 I jxcore-log: DEBUG createNativeListener: listening 42334
04-01 10:29:11.250 11399 11462 I jxcore-log: 
,04-01 10:29:11.260 11399 11462 I jxcore-log: DEBUG createNativeListener: new incoming socket
04-01 10:29:11.260 11399 11462 I jxcore-log: 
,04-01 10:29:11.260 11399 11462 I jxcore-log: DEBUG createNativeListener: creating incoming mux
04-01 10:29:11.260 11399 11462 I jxcore-log: 
,04-01 10:29:11.265 11399 11462 I jxcore-log: DEBUG createNativeListener: new mux
04-01 10:29:11.265 11399 11462 I jxcore-log: 
,04-01 10:29:11.275 11399 11462 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:11.275 11399 11462 I jxcore-log: 
,04-01 10:29:11.280 11399 11462 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:11.280 11399 11462 I jxcore-log: 
,04-01 10:29:11.295 11399 11462 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:11.295 11399 11462 I jxcore-log: 
,04-01 10:29:11.315 11399 11462 I jxcore-log: ok 12 socket shouldn't close until after stream,
04-01 10:29:11.315 11399 11462 I jxcore-log: 
,04-01 10:29:11.315 11399 11462 I jxcore-log: ok 13 incoming remains open
04-01 10:29:11.315 11399 11462 I jxcore-log: 
,04-01 10:29:11.320 11399 11462 I jxcore-log: # teardown
04-01 10:29:11.320 11399 11462 I jxcore-log: 
,04-01 10:29:11.475 11399 11462 I jxcore-log: DEBUG createNativeListener: mux close
04-01 10:29:11.475 11399 11462 I jxcore-log: 
,04-01 10:29:11.495 11399 11462 I jxcore-log: # setup
04-01 10:29:11.495 11399 11462 I jxcore-log: 
,04-01 10:29:11.500 11399 11462 I jxcore-log: DEBUG createNativeListener: incoming socket close
04-01 10:29:11.500 11399 11462 I jxcore-log: 
,04-01 10:29:11.670 11399 11462 I jxcore-log: # 6. native server - closing incoming connection cleans outgoing socket
04-01 10:29:11.670 11399 11462 I jxcore-log: 
,04-01 10:29:11.775 11399 11462 I jxcore-log: DEBUG createNativeListener: creating native server
04-01 10:29:11.775 11399 11462 I jxcore-log: 
,04-01 10:29:11.780 11399 11462 I jxcore-log: DEBUG createNativeListener: listening 56393
04-01 10:29:11.780 11399 11462 I jxcore-log: 
,04-01 10:29:11.795 11399 11462 I jxcore-log: DEBUG createNativeListener: new incoming socket
04-01 10:29:11.795 11399 11462 I jxcore-log: 
,04-01 10:29:11.795 11399 11462 I jxcore-log: DEBUG createNativeListener: creating incoming mux
04-01 10:29:11.795 11399 11462 I jxcore-log: 
,04-01 10:29:11.800 11399 11462 I jxcore-log: DEBUG createNativeListener: new mux
04-01 10:29:11.800 11399 11462 I jxcore-log: 
,04-01 10:29:11.810 11399 11462 I jxcore-log: ok 14 we should not have gotten an error
04-01 10:29:11.810 11399 11462 I jxcore-log: 
,04-01 10:29:11.820 11399 11462 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:11.820 11399 11462 I jxcore-log: 
,04-01 10:29:11.825 11399 11462 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:11.825 11399 11462 I jxcore-log: 
,04-01 10:29:11.840 11399 11462 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:11.840 11399 11462 I jxcore-log: 
,04-01 10:29:11.840 11399 11462 I jxcore-log: DEBUG createNativeListener: incoming socket close
04-01 10:29:11.840 11399 11462 I jxcore-log: 
,04-01 10:29:11.855 11399 11462 I jxcore-log: ok 15 socket shouldn't close until after incoming
04-01 10:29:11.855 11399 11462 I jxcore-log: 
,04-01 10:29:11.855 11399 11462 I jxcore-log: ok 16 incoming is cleaned up
04-01 10:29:11.855 11399 11462 I jxcore-log: 
,04-01 10:29:11.860 11399 11462 I jxcore-log: # teardown
04-01 10:29:11.860 11399 11462 I jxcore-log: 
,04-01 10:29:12.075 11399 11462 I jxcore-log: # setup
04-01 10:29:12.075 11399 11462 I jxcore-log: 
,04-01 10:29:12.180 11399 11462 I jxcore-log: # 7. native server - closing outgoing socket cleans associated mux stream
04-01 10:29:12.180 11399 11462 I jxcore-log: 
,04-01 10:29:12.350 11399 11462 I jxcore-log: DEBUG createNativeListener: creating native server
04-01 10:29:12.350 11399 11462 I jxcore-log: 
,04-01 10:29:12.360 11399 11462 I jxcore-log: DEBUG createNativeListener: listening 50712
04-01 10:29:12.360 11399 11462 I jxcore-log: 
,04-01 10:29:12.370 11399 11462 I jxcore-log: DEBUG createNativeListener: new incoming socket
04-01 10:29:12.370 11399 11462 I jxcore-log: 
,04-01 10:29:12.375 11399 11462 I jxcore-log: DEBUG createNativeListener: creating incoming mux
04-01 10:29:12.375 11399 11462 I jxcore-log: 
,04-01 10:29:12.380 11399 11462 I jxcore-log: DEBUG createNativeListener: new mux
04-01 10:29:12.380 11399 11462 I jxcore-log: 
,04-01 10:29:12.395 11399 11462 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:12.395 11399 11462 I jxcore-log: 
,04-01 10:29:12.400 11399 11462 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:12.400 11399 11462 I jxcore-log: 
,04-01 10:29:12.420 11399 11462 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:12.420 11399 11462 I jxcore-log: 
,04-01 10:29:12.435 11399 11462 I jxcore-log: ok 17 stream was closed
04-01 10:29:12.435 11399 11462 I jxcore-log: 
,04-01 10:29:12.435 11399 11462 I jxcore-log: ok 18 incoming should survive
04-01 10:29:12.435 11399 11462 I jxcore-log: 
,04-01 10:29:12.435 11399 11462 I jxcore-log: ok 19 mux should have no streams
04-01 10:29:12.435 11399 11462 I jxcore-log: 
,04-01 10:29:12.445 11399 11462 I jxcore-log: # teardown
04-01 10:29:12.445 11399 11462 I jxcore-log: 
,04-01 10:29:12.575 11399 11462 I jxcore-log: DEBUG createNativeListener: mux close
04-01 10:29:12.575 11399 11462 I jxcore-log: 
,04-01 10:29:12.585 11399 11462 I jxcore-log: # setup
04-01 10:29:12.585 11399 11462 I jxcore-log: 
,04-01 10:29:12.590 11399 11462 I jxcore-log: DEBUG createNativeListener: incoming socket close
04-01 10:29:12.590 11399 11462 I jxcore-log: 
,04-01 10:29:12.715 11399 11462 I jxcore-log: # 8. native server - closing the whole server cleans everything up
04-01 10:29:12.715 11399 11462 I jxcore-log: 
,04-01 10:29:13.005 11399 11462 I jxcore-log: DEBUG createNativeListener: creating native server
04-01 10:29:13.005 11399 11462 I jxcore-log: 
,04-01 10:29:13.010 11399 11462 I jxcore-log: DEBUG createNativeListener: listening 40793
04-01 10:29:13.010 11399 11462 I jxcore-log: 
,04-01 10:29:13.020 11399 11462 I jxcore-log: DEBUG createNativeListener: new incoming socket
04-01 10:29:13.020 11399 11462 I jxcore-log: 
,04-01 10:29:13.025 11399 11462 I jxcore-log: DEBUG createNativeListener: creating incoming mux
04-01 10:29:13.025 11399 11462 I jxcore-log: 
,04-01 10:29:13.025 11399 11462 I jxcore-log: DEBUG createNativeListener: new mux
04-01 10:29:13.025 11399 11462 I jxcore-log: 
,04-01 10:29:13.035 11399 11462 I jxcore-log: ok 20 we should not have gotten an error
04-01 10:29:13.035 11399 11462 I jxcore-log: 
,04-01 10:29:13.045 11399 11462 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:13.045 11399 11462 I jxcore-log: 
,04-01 10:29:13.050 11399 11462 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:13.050 11399 11462 I jxcore-log: 
,04-01 10:29:13.065 11399 11462 I jxcore-log: ok 21 Buffers are identical
04-01 10:29:13.065 11399 11462 I jxcore-log: 
,04-01 10:29:13.065 11399 11462 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:13.065 11399 11462 I jxcore-log: 
,04-01 10:29:13.070 11399 11462 I jxcore-log: DEBUG createNativeListener: mux close
04-01 10:29:13.070 11399 11462 I jxcore-log: 
,04-01 10:29:13.075 11399 11462 I jxcore-log: ok 22 native server is nulled out
04-01 10:29:13.075 11399 11462 I jxcore-log: 
,04-01 10:29:13.080 11399 11462 I jxcore-log: ok 23 native server should be closed
04-01 10:29:13.080 11399 11462 I jxcore-log: 
,04-01 10:29:13.080 11399 11462 I jxcore-log: ok 24 incoming has been removed
04-01 10:29:13.080 11399 11462 I jxcore-log: 
,04-01 10:29:13.080 11399 11462 I jxcore-log: ok 25 Incoming should be done
04-01 10:29:13.080 11399 11462 I jxcore-log: 
,04-01 10:29:13.085 11399 11462 I jxcore-log: ok 26 The mux object should be closed
04-01 10:29:13.085 11399 11462 I jxcore-log: 
,04-01 10:29:13.085 11399 11462 I jxcore-log: ok 27 The mux stream should be closed
04-01 10:29:13.085 11399 11462 I jxcore-log: 
,04-01 10:29:13.085 11399 11462 I jxcore-log: DEBUG createNativeListener: incoming socket close
04-01 10:29:13.085 11399 11462 I jxcore-log: 
,04-01 10:29:13.105 11399 11462 I jxcore-log: # teardown
04-01 10:29:13.105 11399 11462 I jxcore-log: 
,04-01 10:29:13.620  3403  4396 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:29:13.625  3403  4396 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:29:13.625  3403  4396 D BatteryService: online:4, current avg:29, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
,04-01 10:29:13.625  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,04-01 10:29:13.630  3403  3403 I MotionRecognitionService: Plugged
04-01 10:29:13.630  3403  3403 D MotionRecognitionService:   cableConnection= 1
04-01 10:29:13.630  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
04-01 10:29:13.630  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:29:13.635  3403  4396 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 13ms,
04-01 10:29:13.635  3403  4396 D BatteryService: stay LED for fully charged
,04-01 10:29:13.645  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
04-01 10:29:13.645  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,04-01 10:29:13.645  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate,
,04-01 10:29:13.665  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,04-01 10:29:13.665  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:29:13.675  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:29:13.675  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:29:13.675  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:29:13.675  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:29:13.875 11399 11462 I jxcore-log: # setup
04-01 10:29:13.875 11399 11462 I jxcore-log: 
,04-01 10:29:14.415  3403  6140 D SSRM:n  : SIOP:: AP = 270, PST = 267 (W:14), CUR = 29, LCD = 0
,04-01 10:29:15.555 11399 11462 I jxcore-log: # 9. native server - we can get a ton of connections and data through and still clean up the server completely
04-01 10:29:15.555 11399 11462 I jxcore-log: 
,04-01 10:29:19.285 11399 11462 I jxcore-log: DEBUG createNativeListener: creating native server
04-01 10:29:19.285 11399 11462 I jxcore-log: 
,04-01 10:29:19.295 11399 11462 I jxcore-log: DEBUG createNativeListener: listening 34797
04-01 10:29:19.295 11399 11462 I jxcore-log: 
,04-01 10:29:19.335 11399 11462 I jxcore-log: DEBUG createNativeListener: new incoming socket
04-01 10:29:19.335 11399 11462 I jxcore-log: 
,04-01 10:29:19.335 11399 11462 I jxcore-log: DEBUG createNativeListener: creating incoming mux
04-01 10:29:19.335 11399 11462 I jxcore-log: 
,04-01 10:29:19.340 11399 11462 I jxcore-log: DEBUG createNativeListener: new mux
04-01 10:29:19.340 11399 11462 I jxcore-log: 
,04-01 10:29:19.350 11399 11462 I jxcore-log: DEBUG createNativeListener: new incoming socket
04-01 10:29:19.350 11399 11462 I jxcore-log: 
,04-01 10:29:19.350 11399 11462 I jxcore-log: DEBUG createNativeListener: creating incoming mux
04-01 10:29:19.350 11399 11462 I jxcore-log: 
,04-01 10:29:19.355 11399 11462 I jxcore-log: DEBUG createNativeListener: new mux
04-01 10:29:19.355 11399 11462 I jxcore-log: 
,04-01 10:29:19.355 11399 11462 I jxcore-log: DEBUG createNativeListener: new incoming socket
04-01 10:29:19.355 11399 11462 I jxcore-log: 
,04-01 10:29:19.355 11399 11462 I jxcore-log: DEBUG createNativeListener: creating incoming mux
04-01 10:29:19.355 11399 11462 I jxcore-log: 
,04-01 10:29:19.360 11399 11462 I jxcore-log: DEBUG createNativeListener: new mux
04-01 10:29:19.360 11399 11462 I jxcore-log: 
,04-01 10:29:19.365 11399 11462 I jxcore-log: DEBUG createNativeListener: new incoming socket
04-01 10:29:19.365 11399 11462 I jxcore-log: 
,04-01 10:29:19.365 11399 11462 I jxcore-log: DEBUG createNativeListener: creating incoming mux
04-01 10:29:19.365 11399 11462 I jxcore-log: 
,04-01 10:29:19.365 11399 11462 I jxcore-log: DEBUG createNativeListener: new mux
04-01 10:29:19.365 11399 11462 I jxcore-log: 
,04-01 10:29:19.370 11399 11462 I jxcore-log: DEBUG createNativeListener: new incoming socket
04-01 10:29:19.370 11399 11462 I jxcore-log: 
,04-01 10:29:19.370 11399 11462 I jxcore-log: DEBUG createNativeListener: creating incoming mux
04-01 10:29:19.370 11399 11462 I jxcore-log: 
,04-01 10:29:19.375 11399 11462 I jxcore-log: DEBUG createNativeListener: new mux
04-01 10:29:19.375 11399 11462 I jxcore-log: 
,04-01 10:29:19.375 11399 11462 I jxcore-log: DEBUG createNativeListener: new incoming socket
04-01 10:29:19.375 11399 11462 I jxcore-log: 
,04-01 10:29:19.375 11399 11462 I jxcore-log: DEBUG createNativeListener: creating incoming mux
04-01 10:29:19.375 11399 11462 I jxcore-log: 
,04-01 10:29:19.380 11399 11462 I jxcore-log: DEBUG createNativeListener: new mux
04-01 10:29:19.380 11399 11462 I jxcore-log: 
,04-01 10:29:19.380 11399 11462 I jxcore-log: DEBUG createNativeListener: new incoming socket,
04-01 10:29:19.380 11399 11462 I jxcore-log: 
,04-01 10:29:19.385 11399 11462 I jxcore-log: DEBUG createNativeListener: creating incoming mux
04-01 10:29:19.385 11399 11462 I jxcore-log: 
,04-01 10:29:19.385 11399 11462 I jxcore-log: DEBUG createNativeListener: new mux
04-01 10:29:19.385 11399 11462 I jxcore-log: 
,04-01 10:29:19.390 11399 11462 I jxcore-log: DEBUG createNativeListener: new incoming socket
04-01 10:29:19.390 11399 11462 I jxcore-log: 
,04-01 10:29:19.390 11399 11462 I jxcore-log: DEBUG createNativeListener: creating incoming mux
04-01 10:29:19.390 11399 11462 I jxcore-log: 
,04-01 10:29:19.390 11399 11462 I jxcore-log: DEBUG createNativeListener: new mux
04-01 10:29:19.390 11399 11462 I jxcore-log: 
,04-01 10:29:19.395 11399 11462 I jxcore-log: DEBUG createNativeListener: new incoming socket
04-01 10:29:19.395 11399 11462 I jxcore-log: 
,04-01 10:29:19.395 11399 11462 I jxcore-log: DEBUG createNativeListener: creating incoming mux
04-01 10:29:19.395 11399 11462 I jxcore-log: 
,04-01 10:29:19.395 11399 11462 I jxcore-log: DEBUG createNativeListener: new mux
04-01 10:29:19.395 11399 11462 I jxcore-log: 
,04-01 10:29:19.400 11399 11462 I jxcore-log: DEBUG createNativeListener: new incoming socket
04-01 10:29:19.400 11399 11462 I jxcore-log: 
,04-01 10:29:19.400 11399 11462 I jxcore-log: DEBUG createNativeListener: creating incoming mux
04-01 10:29:19.400 11399 11462 I jxcore-log: 
,04-01 10:29:19.405 11399 11462 I jxcore-log: DEBUG createNativeListener: new mux
04-01 10:29:19.405 11399 11462 I jxcore-log: 
,04-01 10:29:19.520 11399 11462 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:19.520 11399 11462 I jxcore-log: 
,04-01 10:29:19.520 11399 11462 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:19.520 11399 11462 I jxcore-log: 
,04-01 10:29:19.525 11399 11462 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:19.525 11399 11462 I jxcore-log: 
,04-01 10:29:19.525 11399 11462 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:19.525 11399 11462 I jxcore-log: 
,04-01 10:29:19.525 11399 11462 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:19.525 11399 11462 I jxcore-log: 
,04-01 10:29:19.530 11399 11462 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:19.530 11399 11462 I jxcore-log: 
,04-01 10:29:19.530 11399 11462 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:19.530 11399 11462 I jxcore-log: 
,04-01 10:29:19.535 11399 11462 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:19.535 11399 11462 I jxcore-log: 
,04-01 10:29:19.535 11399 11462 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:19.535 11399 11462 I jxcore-log: 
,04-01 10:29:19.535 11399 11462 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:19.535 11399 11462 I jxcore-log: 
,04-01 10:29:19.535 11399 11462 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:19.535 11399 11462 I jxcore-log: 
,04-01 10:29:19.540 11399 11462 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:19.540 11399 11462 I jxcore-log: 
,04-01 10:29:19.540 11399 11462 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:19.540 11399 11462 I jxcore-log: 
,04-01 10:29:19.540 11399 11462 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:19.540 11399 11462 I jxcore-log: 
,04-01 10:29:19.545 11399 11462 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:19.545 11399 11462 I jxcore-log: 
,04-01 10:29:19.545 11399 11462 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:19.545 11399 11462 I jxcore-log: 
,04-01 10:29:19.545 11399 11462 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:19.545 11399 11462 I jxcore-log: 
,04-01 10:29:19.550 11399 11462 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:19.550 11399 11462 I jxcore-log: 
,04-01 10:29:19.550 11399 11462 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:19.550 11399 11462 I jxcore-log: 
,04-01 10:29:19.555 11399 11462 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:19.555 11399 11462 I jxcore-log: 
,04-01 10:29:19.555 11399 11462 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:19.555 11399 11462 I jxcore-log: 
,04-01 10:29:19.555 11399 11462 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:19.555 11399 11462 I jxcore-log: 
,04-01 10:29:19.560 11399 11462 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:19.560 11399 11462 I jxcore-log: 
,04-01 10:29:19.560 11399 11462 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:19.560 11399 11462 I jxcore-log: 
,04-01 10:29:19.560 11399 11462 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:19.560 11399 11462 I jxcore-log: 
,04-01 10:29:19.565 11399 11462 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:19.565 11399 11462 I jxcore-log: 
,04-01 10:29:19.565 11399 11462 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:19.565 11399 11462 I jxcore-log: 
,04-01 10:29:19.565 11399 11462 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:19.565 11399 11462 I jxcore-log: 
,04-01 10:29:19.565 11399 11462 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:19.565 11399 11462 I jxcore-log: 
,04-01 10:29:19.570 11399 11462 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:19.570 11399 11462 I jxcore-log: 
,04-01 10:29:19.570 11399 11462 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:19.570 11399 11462 I jxcore-log: 
,04-01 10:29:19.570 11399 11462 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:19.570 11399 11462 I jxcore-log: 
,04-01 10:29:19.575 11399 11462 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:19.575 11399 11462 I jxcore-log: 
,04-01 10:29:19.575 11399 11462 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:19.575 11399 11462 I jxcore-log: 
,04-01 10:29:19.575 11399 11462 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:19.575 11399 11462 I jxcore-log: 
,04-01 10:29:19.580 11399 11462 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:19.580 11399 11462 I jxcore-log: 
,04-01 10:29:19.580 11399 11462 I jxcore-log: DEBUG createNativeListener: new stream: 
,04-01 10:29:19.580 11399 11462 I jxcore-log: 
,04-01 10:29:19.580 11399 11462 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:19.580 11399 11462 I jxcore-log: 
,04-01 10:29:19.580 11399 11462 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:19.580 11399 11462 I jxcore-log: 
,04-01 10:29:19.585 11399 11462 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:19.585 11399 11462 I jxcore-log: 
,04-01 10:29:19.585 11399 11462 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:19.585 11399 11462 I jxcore-log: 
,04-01 10:29:19.590 11399 11462 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:19.590 11399 11462 I jxcore-log: 
,04-01 10:29:19.590 11399 11462 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:19.590 11399 11462 I jxcore-log: ,
,04-01 10:29:19.590 11399 11462 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:19.590 11399 11462 I jxcore-log: 
,04-01 10:29:19.590 11399 11462 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:19.590 11399 11462 I jxcore-log: 
,04-01 10:29:19.595 11399 11462 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:19.595 11399 11462 I jxcore-log: 
,04-01 10:29:19.600 11399 11462 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:19.600 11399 11462 I jxcore-log: 
,04-01 10:29:19.600 11399 11462 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:19.600 11399 11462 I jxcore-log: 
,04-01 10:29:19.605 11399 11462 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:19.605 11399 11462 I jxcore-log: ,
,04-01 10:29:19.605 11399 11462 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:19.605 11399 11462 I jxcore-log: 
,04-01 10:29:19.605 11399 11462 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:19.605 11399 11462 I jxcore-log: 
,04-01 10:29:19.610 11399 11462 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:19.610 11399 11462 I jxcore-log: 
,04-01 10:29:19.610 11399 11462 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:19.610 11399 11462 I jxcore-log: 
,04-01 10:29:19.610 11399 11462 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:19.610 11399 11462 I jxcore-log: 
,04-01 10:29:19.610 11399 11462 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:19.610 11399 11462 I jxcore-log: 
,04-01 10:29:19.615 11399 11462 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:19.615 11399 11462 I jxcore-log: 
,04-01 10:29:19.615 11399 11462 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:19.615 11399 11462 I jxcore-log: ,
,04-01 10:29:19.615 11399 11462 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:19.615 11399 11462 I jxcore-log: 
,04-01 10:29:19.615 11399 11462 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:19.615 11399 11462 I jxcore-log: 
,04-01 10:29:19.620 11399 11462 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:19.620 11399 11462 I jxcore-log: 
,04-01 10:29:19.620 11399 11462 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:19.620 11399 11462 I jxcore-log: 
,04-01 10:29:19.620 11399 11462 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:19.620 11399 11462 I jxcore-log: 
,04-01 10:29:19.620 11399 11462 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:19.620 11399 11462 I jxcore-log: 
,04-01 10:29:19.620 11399 11462 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:19.620 11399 11462 I jxcore-log: 
,04-01 10:29:19.625 11399 11462 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:19.625 11399 11462 I jxcore-log: 
,04-01 10:29:19.625 11399 11462 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:19.625 11399 11462 I jxcore-log: 
,04-01 10:29:19.625 11399 11462 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:19.625 11399 11462 I jxcore-log: 
,04-01 10:29:19.625 11399 11462 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:19.625 11399 11462 I jxcore-log: 
,04-01 10:29:19.630 11399 11462 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:19.630 11399 11462 I jxcore-log: 
,04-01 10:29:19.630 11399 11462 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:19.630 11399 11462 I jxcore-log: 
,04-01 10:29:19.630 11399 11462 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:19.630 11399 11462 I jxcore-log: 
,04-01 10:29:19.630 11399 11462 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:19.630 11399 11462 I jxcore-log: 
,04-01 10:29:19.630 11399 11462 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:19.630 11399 11462 I jxcore-log: 
04-01 10:29:19.635 11399 11462 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:19.635 11399 11462 I jxcore-log: 
04-01 10:29:19.635 11399 11462 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:19.635 11399 11462 I jxcore-log: 
,04-01 10:29:19.635 11399 11462 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:19.635 11399 11462 I jxcore-log: 
,04-01 10:29:19.635 11399 11462 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:19.635 11399 11462 I jxcore-log: 
,04-01 10:29:19.640 11399 11462 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:19.640 11399 11462 I jxcore-log: 
,04-01 10:29:19.640 11399 11462 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:19.640 11399 11462 I jxcore-log: 
,04-01 10:29:19.640 11399 11462 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:19.640 11399 11462 I jxcore-log: 
,04-01 10:29:19.700 11399 11462 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:19.700 11399 11462 I jxcore-log: 
,04-01 10:29:19.700 11399 11462 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:19.700 11399 11462 I jxcore-log: 
,04-01 10:29:19.700 11399 11462 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:19.700 11399 11462 I jxcore-log: 
,04-01 10:29:19.700 11399 11462 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:19.700 11399 11462 I jxcore-log: 
04-01 10:29:19.700 11399 11462 I jxcore-log: DEBUG createNativeListener: mux close
04-01 10:29:19.700 11399 11462 I jxcore-log: 
,04-01 10:29:19.705 11399 11462 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:19.705 11399 11462 I jxcore-log: 
,04-01 10:29:19.705 11399 11462 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:19.705 11399 11462 I jxcore-log: 
04-01 10:29:19.705 11399 11462 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:19.705 11399 11462 I jxcore-log: 
,04-01 10:29:19.705 11399 11462 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:19.705 11399 11462 I jxcore-log: 
04-01 10:29:19.705 11399 11462 I jxcore-log: DEBUG createNativeListener: mux close
04-01 10:29:19.705 11399 11462 I jxcore-log: 
,04-01 10:29:19.705 11399 11462 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:19.705 11399 11462 I jxcore-log: 
,04-01 10:29:19.710 11399 11462 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:19.710 11399 11462 I jxcore-log: 
,04-01 10:29:19.710 11399 11462 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:19.710 11399 11462 I jxcore-log: 
04-01 10:29:19.710 11399 11462 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:19.710 11399 11462 I jxcore-log: 
,04-01 10:29:19.710 11399 11462 I jxcore-log: DEBUG createNativeListener: mux close
04-01 10:29:19.710 11399 11462 I jxcore-log: 
,04-01 10:29:19.710 11399 11462 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:19.710 11399 11462 I jxcore-log: 
,04-01 10:29:19.710 11399 11462 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:19.710 11399 11462 I jxcore-log: 
04-01 10:29:19.710 11399 11462 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:19.710 11399 11462 I jxcore-log: 
,04-01 10:29:19.710 11399 11462 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:19.710 11399 11462 I jxcore-log: 
,04-01 10:29:19.715 11399 11462 I jxcore-log: DEBUG createNativeListener: mux close
04-01 10:29:19.715 11399 11462 I jxcore-log: 
04-01 10:29:19.715 11399 11462 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:19.715 11399 11462 I jxcore-log: 
,04-01 10:29:19.715 11399 11462 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:19.715 11399 11462 I jxcore-log: 
04-01 10:29:19.715 11399 11462 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:19.715 11399 11462 I jxcore-log: 
,04-01 10:29:19.715 11399 11462 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:19.715 11399 11462 I jxcore-log: 
,04-01 10:29:19.715 11399 11462 I jxcore-log: DEBUG createNativeListener: mux close
04-01 10:29:19.715 11399 11462 I jxcore-log: 
,04-01 10:29:19.715 11399 11462 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:19.715 11399 11462 I jxcore-log: 
04-01 10:29:19.715 11399 11462 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:19.715 11399 11462 I jxcore-log: 
,04-01 10:29:19.720 11399 11462 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:19.720 11399 11462 I jxcore-log: 
04-01 10:29:19.720 11399 11462 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:19.720 11399 11462 I jxcore-log: 
,04-01 10:29:19.720 11399 11462 I jxcore-log: DEBUG createNativeListener: mux close
04-01 10:29:19.720 11399 11462 I jxcore-log: 
,04-01 10:29:19.720 11399 11462 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:19.720 11399 11462 I jxcore-log: 
04-01 10:29:19.720 11399 11462 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:19.720 11399 11462 I jxcore-log: 
,04-01 10:29:19.720 11399 11462 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:19.720 11399 11462 I jxcore-log: 
,04-01 10:29:19.720 11399 11462 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:19.720 11399 11462 I jxcore-log: 
04-01 10:29:19.720 11399 11462 I jxcore-log: DEBUG createNativeListener: mux close
04-01 10:29:19.720 11399 11462 I jxcore-log: 
,04-01 10:29:19.720 11399 11462 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:19.720 11399 11462 I jxcore-log: 
04-01 10:29:19.720 11399 11462 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:19.720 11399 11462 I jxcore-log: 
,04-01 10:29:19.725 11399 11462 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:19.725 11399 11462 I jxcore-log: 
04-01 10:29:19.725 11399 11462 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:19.725 11399 11462 I jxcore-log: 
,04-01 10:29:19.725 11399 11462 I jxcore-log: DEBUG createNativeListener: mux close
04-01 10:29:19.725 11399 11462 I jxcore-log: 
04-01 10:29:19.725 11399 11462 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:19.725 11399 11462 I jxcore-log: 
,04-01 10:29:19.725 11399 11462 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:19.725 11399 11462 I jxcore-log: 
04-01 10:29:19.725 11399 11462 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:19.725 11399 11462 I jxcore-log: 
,04-01 10:29:19.725 11399 11462 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:19.725 11399 11462 I jxcore-log: 
04-01 10:29:19.725 11399 11462 I jxcore-log: DEBUG createNativeListener: mux close
04-01 10:29:19.725 11399 11462 I jxcore-log: 
,04-01 10:29:19.725 11399 11462 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:19.725 11399 11462 I jxcore-log: 
,04-01 10:29:19.730 11399 11462 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:19.730 11399 11462 I jxcore-log: 
04-01 10:29:19.730 11399 11462 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:19.730 11399 11462 I jxcore-log: 
,04-01 10:29:19.730 11399 11462 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:19.730 11399 11462 I jxcore-log: 
,04-01 10:29:19.730 11399 11462 I jxcore-log: DEBUG createNativeListener: mux close
04-01 10:29:19.730 11399 11462 I jxcore-log: 
,04-01 10:29:19.730 11399 11462 I jxcore-log: ok 28 native server is nulled out
04-01 10:29:19.730 11399 11462 I jxcore-log: 
,04-01 10:29:19.730 11399 11462 I jxcore-log: ok 29 native server should be closed
04-01 10:29:19.730 11399 11462 I jxcore-log: 
04-01 10:29:19.730 11399 11462 I jxcore-log: ok 30 incoming has been removed
04-01 10:29:19.730 11399 11462 I jxcore-log: 
,04-01 10:29:19.735 11399 11462 I jxcore-log: DEBUG createNativeListener: incoming socket close
04-01 10:29:19.735 11399 11462 I jxcore-log: 
04-01 10:29:19.735 11399 11462 I jxcore-log: DEBUG createNativeListener: incoming socket close
04-01 10:29:19.735 11399 11462 I jxcore-log: 
,04-01 10:29:19.735 11399 11462 I jxcore-log: DEBUG createNativeListener: incoming socket close
04-01 10:29:19.735 11399 11462 I jxcore-log: 
04-01 10:29:19.735 11399 11462 I jxcore-log: DEBUG createNativeListener: incoming socket close
04-01 10:29:19.735 11399 11462 I jxcore-log: 
04-01 10:29:19.735 11399 11462 I jxcore-log: DEBUG createNativeListener: incoming socket close
04-01 10:29:19.735 11399 11462 I jxcore-log: 
,04-01 10:29:19.735 11399 11462 I jxcore-log: DEBUG createNativeListener: incoming socket close
04-01 10:29:19.735 11399 11462 I jxcore-log: 
04-01 10:29:19.735 11399 11462 I jxcore-log: DEBUG createNativeListener: incoming socket close
04-01 10:29:19.735 11399 11462 I jxcore-log: 
04-01 10:29:19.735 11399 11462 I jxcore-log: DEBUG createNativeListener: incoming socket close
04-01 10:29:19.735 11399 11462 I jxcore-log: 
,04-01 10:29:19.735 11399 11462 I jxcore-log: DEBUG createNativeListener: incoming socket close
04-01 10:29:19.735 11399 11462 I jxcore-log: 
04-01 10:29:19.735 11399 11462 I jxcore-log: DEBUG createNativeListener: incoming socket close
04-01 10:29:19.735 11399 11462 I jxcore-log: 
,04-01 10:29:19.820 11399 11462 I jxcore-log: # teardown
04-01 10:29:19.820 11399 11462 I jxcore-log: 
,04-01 10:29:20.480  3403  3863 E Watchdog: !@Sync 7 [04-01 10:29:20.483]
,04-01 10:29:22.130 11399 11462 I jxcore-log: # setup
04-01 10:29:22.130 11399 11462 I jxcore-log: 
,04-01 10:29:23.760  3403  3649 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:29:23.760  3403  3649 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:29:23.760  3403  3649 D BatteryService: online:4, current avg:38, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:50
,04-01 10:29:23.765  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,04-01 10:29:23.770  3403  3649 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 11ms
04-01 10:29:23.770  3403  3649 D BatteryService: stay LED for fully charged,
,04-01 10:29:23.775  3403  3403 I MotionRecognitionService: Plugged
,04-01 10:29:23.775  3403  3403 D MotionRecognitionService:   cableConnection= 1,
04-01 10:29:23.775  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
,04-01 10:29:23.775  3403  3403 D MotionRecognitionService: skip setTransmitPower. ,
,04-01 10:29:23.790  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,04-01 10:29:23.790  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,04-01 10:29:23.790  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate,
,04-01 10:29:23.810  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,04-01 10:29:23.815  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:29:23.820  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:29:23.820  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:29:23.825  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:29:23.825  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:29:24.450  3403  6140 D SSRM:n  : SIOP:: AP = 260, PST = 267 (W:14), CUR = 38, LCD = 0
,04-01 10:29:24.875 11399 11462 I jxcore-log: # 10. native server - simulate mux failure, make sure everything is cleaned up
04-01 10:29:24.875 11399 11462 I jxcore-log: 
,04-01 10:29:28.170  3403  6173 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,04-01 10:29:28.800 11399 11462 I jxcore-log: DEBUG createNativeListener: creating native server
04-01 10:29:28.800 11399 11462 I jxcore-log: 
,04-01 10:29:28.805 11399 11462 I jxcore-log: DEBUG createNativeListener: listening 42460
04-01 10:29:28.805 11399 11462 I jxcore-log: 
,04-01 10:29:28.815 11399 11462 I jxcore-log: DEBUG createNativeListener: new incoming socket
04-01 10:29:28.815 11399 11462 I jxcore-log: 
,04-01 10:29:28.815 11399 11462 I jxcore-log: DEBUG createNativeListener: creating incoming mux
04-01 10:29:28.815 11399 11462 I jxcore-log: 
,04-01 10:29:28.820 11399 11462 I jxcore-log: DEBUG createNativeListener: new mux
04-01 10:29:28.820 11399 11462 I jxcore-log: 
,04-01 10:29:28.830 11399 11462 I jxcore-log: ok 31 we should not have gotten an error
04-01 10:29:28.830 11399 11462 I jxcore-log: 
,04-01 10:29:28.835 11399 11462 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:28.835 11399 11462 I jxcore-log: 
,04-01 10:29:28.840 11399 11462 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:28.840 11399 11462 I jxcore-log: 
,04-01 10:29:28.850 11399 11462 I jxcore-log: ok 32 Buffers are identical
04-01 10:29:28.850 11399 11462 I jxcore-log: 
,04-01 10:29:28.850 11399 11462 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:28.850 11399 11462 I jxcore-log: 
,04-01 10:29:28.850 11399 11462 I jxcore-log: DEBUG createNativeListener: mux close
04-01 10:29:28.850 11399 11462 I jxcore-log: 
,04-01 10:29:28.865 11399 11462 I jxcore-log: DEBUG createNativeListener: incoming socket close
04-01 10:29:28.865 11399 11462 I jxcore-log: 
,04-01 10:29:28.870 11399 11462 I jxcore-log: ok 33 server should be fine
04-01 10:29:28.870 11399 11462 I jxcore-log: 
,04-01 10:29:28.870 11399 11462 I jxcore-log: ok 34 server should be open
04-01 10:29:28.870 11399 11462 I jxcore-log: 
,04-01 10:29:28.870 11399 11462 I jxcore-log: ok 35 incoming has been removed
04-01 10:29:28.870 11399 11462 I jxcore-log: 
,04-01 10:29:28.870 11399 11462 I jxcore-log: ok 36 The mux object should be closed
04-01 10:29:28.870 11399 11462 I jxcore-log: 
,04-01 10:29:28.870 11399 11462 I jxcore-log: ok 37 The mux stream should be closed
04-01 10:29:28.870 11399 11462 I jxcore-log: 
,04-01 10:29:28.880 11399 11462 I jxcore-log: # teardown
04-01 10:29:28.880 11399 11462 I jxcore-log: 
,04-01 10:29:30.305 11399 11462 I jxcore-log: # setup
04-01 10:29:30.305 11399 11462 I jxcore-log: 
,04-01 10:29:33.905  3403  3432 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,04-01 10:29:33.905  3403  3432 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:29:33.905  3403  3432 D BatteryService: online:4, current avg:41, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:37
04-01 10:29:33.905  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,04-01 10:29:33.905  3403  3432 D BatteryService: stay LED for fully charged,
04-01 10:29:33.910  3403  3403 I MotionRecognitionService: Plugged
,04-01 10:29:33.910  3403  3403 D MotionRecognitionService:   cableConnection= 1
,04-01 10:29:33.910  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
04-01 10:29:33.910  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:29:33.915  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:29:33.915  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
04-01 10:29:33.915  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:29:33.930  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,04-01 10:29:33.930  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:29:33.940  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:29:33.940  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:29:33.940  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:29:33.945  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:29:34.485  3403  6140 D SSRM:n  : SIOP:: AP = 260, PST = 267 (W:14), CUR = 41, LCD = 0
,04-01 10:29:39.020 11399 11462 I jxcore-log: # 11. native server - timing out the incoming connection cleans everything up
04-01 10:29:39.020 11399 11462 I jxcore-log: 
,04-01 10:29:43.990  3403  3583 I PowerManagerService: [PWL] Off : 180s ago
,04-01 10:29:44.040  3403  3830 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:29:44.040  3403  3830 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:29:44.045  3403  3830 D BatteryService: online:4, current avg:39, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
,04-01 10:29:44.045  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
04-01 10:29:44.050  3403  3830 D BatteryService: stay LED for fully charged
,04-01 10:29:44.055  3403  3403 I MotionRecognitionService: Plugged
04-01 10:29:44.055  3403  3403 D MotionRecognitionService:   cableConnection= 1,
04-01 10:29:44.055  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,04-01 10:29:44.055  3403  3403 D MotionRecognitionService: skip setTransmitPower. ,
,04-01 10:29:44.065  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:29:44.065  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:29:44.065  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:29:44.075  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,04-01 10:29:44.075  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:29:44.090  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:29:44.090  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:29:44.090  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:29:44.090  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:29:44.515  3403  6140 D SSRM:n  : SIOP:: AP = 260, PST = 267 (W:16), CUR = 39, LCD = 0
,04-01 10:29:48.180  3403  6173 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,04-01 10:29:50.485  3403  3863 E Watchdog: !@Sync 8 [04-01 10:29:50.491]
,04-01 10:29:53.725  2891  4804 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,04-01 10:29:54.175  3403  4786 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,04-01 10:29:54.180  3403  4786 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:29:54.180  3403  4786 D BatteryService: online:4, current avg:37, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:52
04-01 10:29:54.185  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
04-01 10:29:54.185  3403  4786 D BatteryService: stay LED for fully charged
,04-01 10:29:54.190  3403  3403 I MotionRecognitionService: Plugged
,04-01 10:29:54.190  3403  3403 D MotionRecognitionService:   cableConnection= 1
04-01 10:29:54.190  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
04-01 10:29:54.190  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:29:54.195  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:29:54.195  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:29:54.195  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:29:54.205  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:29:54.210  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
04-01 10:29:54.210  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:29:54.225  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:29:54.225  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:29:54.225  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:29:54.545  3403  6140 D SSRM:n  : SIOP:: AP = 260, PST = 266 (W:16), CUR = 37, LCD = 0
,04-01 10:30:04.315  3403  4003 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:30:04.315  3403  4003 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:30:04.315  3403  4003 D BatteryService: online:4, current avg:35, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:28
,04-01 10:30:04.320  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
04-01 10:30:04.320  3403  4003 D BatteryService: stay LED for fully charged,
,04-01 10:30:04.330  3403  3403 I MotionRecognitionService: Plugged
04-01 10:30:04.330  3403  3403 D MotionRecognitionService:   cableConnection= 1,
,04-01 10:30:04.330  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,04-01 10:30:04.330  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:30:04.340  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:30:04.340  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:30:04.340  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:30:04.350  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
04-01 10:30:04.350  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:30:04.365  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:30:04.365  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:30:04.365  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:30:04.365  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:30:04.580  3403  6140 D SSRM:n  : SIOP:: AP = 260, PST = 266 (W:16), CUR = 35, LCD = 0
,04-01 10:30:08.185  3403  6173 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,04-01 10:30:14.455  3403  3434 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:30:14.455  3403  3434 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:30:14.455  3403  3434 D BatteryService: online:4, current avg:34, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,04-01 10:30:14.455  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,04-01 10:30:14.465  3403  3403 I MotionRecognitionService: Plugged
04-01 10:30:14.465  3403  3403 D MotionRecognitionService:   cableConnection= 1,
04-01 10:30:14.465  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
04-01 10:30:14.465  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
04-01 10:30:14.465  3403  3434 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 11ms
04-01 10:30:14.465  3403  3434 D BatteryService: stay LED for fully charged,
,04-01 10:30:14.475  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,04-01 10:30:14.475  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,04-01 10:30:14.475  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate,
,04-01 10:30:14.495  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
04-01 10:30:14.495  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:30:14.510  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:30:14.510  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:30:14.510  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:30:14.510  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:30:14.610  3403  6140 D SSRM:n  : SIOP:: AP = 250, PST = 266 (W:16), CUR = 34, LCD = 0
,04-01 10:30:20.495  3403  3863 E Watchdog: !@Sync 9 [04-01 10:30:20.498]
,04-01 10:30:24.590  3403  3850 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:30:24.595  3403  3850 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:30:24.595  3403  3850 D BatteryService: online:4, current avg:34, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:32
,04-01 10:30:24.595  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,04-01 10:30:24.605  3403  3403 I MotionRecognitionService: Plugged
04-01 10:30:24.605  3403  3403 D MotionRecognitionService:   cableConnection= 1
04-01 10:30:24.605  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
04-01 10:30:24.605  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:30:24.605  3403  3850 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 14ms,
04-01 10:30:24.605  3403  3850 D BatteryService: stay LED for fully charged
,04-01 10:30:24.615  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
04-01 10:30:24.615  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:30:24.615  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:30:24.640  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
04-01 10:30:24.640  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:30:24.645  3403  6140 D SSRM:n  : SIOP:: AP = 250, PST = 264 (W:18), CUR = 34, LCD = 0
,04-01 10:30:24.650  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:30:24.650  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:30:24.650  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:30:24.650  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:30:28.190  3403  6173 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,04-01 10:30:28.995  3403  3583 I PowerManagerService: [PWL] Off : 225s ago
,04-01 10:30:33.755 11399 11462 I jxcore-log: DEBUG createNativeListener: creating native server
04-01 10:30:33.755 11399 11462 I jxcore-log: 
,04-01 10:30:33.770 11399 11462 I jxcore-log: DEBUG createNativeListener: listening 51645
04-01 10:30:33.770 11399 11462 I jxcore-log: 
,04-01 10:30:33.780 11399 11462 I jxcore-log: DEBUG createNativeListener: new incoming socket
04-01 10:30:33.780 11399 11462 I jxcore-log: 
,04-01 10:30:33.780 11399 11462 I jxcore-log: DEBUG createNativeListener: creating incoming mux
04-01 10:30:33.780 11399 11462 I jxcore-log: 
,04-01 10:30:33.785 11399 11462 I jxcore-log: DEBUG createNativeListener: new mux
04-01 10:30:33.785 11399 11462 I jxcore-log: 
,04-01 10:30:33.795 11399 11462 I jxcore-log: ok 38 we should not have gotten an error
04-01 10:30:33.795 11399 11462 I jxcore-log: 
,04-01 10:30:33.800 11399 11462 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:30:33.800 11399 11462 I jxcore-log: 
,04-01 10:30:33.800 11399 11462 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:30:33.800 11399 11462 I jxcore-log: 
,04-01 10:30:33.825 11399 11462 I jxcore-log: ok 39 Buffers are identical
04-01 10:30:33.825 11399 11462 I jxcore-log: 
,04-01 10:30:33.830 11399 11462 I jxcore-log: DEBUG createNativeListener: incoming socket timeout
04-01 10:30:33.830 11399 11462 I jxcore-log: 
,04-01 10:30:33.830 11399 11462 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:30:33.830 11399 11462 I jxcore-log: 
,04-01 10:30:33.835 11399 11462 I jxcore-log: DEBUG createNativeListener: mux close
04-01 10:30:33.835 11399 11462 I jxcore-log: 
,04-01 10:30:33.840 11399 11462 I jxcore-log: DEBUG createNativeListener: incoming socket close
04-01 10:30:33.840 11399 11462 I jxcore-log: 
,04-01 10:30:33.840 11399 11462 I jxcore-log: ok 40 server should be fine
04-01 10:30:33.840 11399 11462 I jxcore-log: 
04-01 10:30:33.840 11399 11462 I jxcore-log: ok 41 server should be open
04-01 10:30:33.840 11399 11462 I jxcore-log: 
,04-01 10:30:33.840 11399 11462 I jxcore-log: ok 42 incoming has been removed
04-01 10:30:33.840 11399 11462 I jxcore-log: 
04-01 10:30:33.845 11399 11462 I jxcore-log: ok 43 The mux object should be closed
04-01 10:30:33.845 11399 11462 I jxcore-log: 
,04-01 10:30:33.845 11399 11462 I jxcore-log: ok 44 The mux stream should be closed
04-01 10:30:33.845 11399 11462 I jxcore-log: 
,04-01 10:30:33.855 11399 11462 I jxcore-log: # teardown
04-01 10:30:33.855 11399 11462 I jxcore-log: 
,04-01 10:30:34.675  3403  6140 D SSRM:n  : SIOP:: AP = 250, PST = 260 (W:18), CUR = 32, LCD = 0
,04-01 10:30:34.725  3403  4027 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:30:34.725  3403  4027 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:30:34.725  3403  4027 D BatteryService: online:4, current avg:32, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
04-01 10:30:34.725  3403  4027 D BatteryService: stay LED for fully charged
,04-01 10:30:34.725  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,04-01 10:30:34.730  3403  3403 I MotionRecognitionService: Plugged
04-01 10:30:34.730  3403  3403 D MotionRecognitionService:   cableConnection= 1
04-01 10:30:34.730  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
04-01 10:30:34.730  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:30:34.735  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:30:34.735  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
04-01 10:30:34.735  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:30:34.755  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
04-01 10:30:34.755  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:30:34.765  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:30:34.765  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:30:34.765  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:30:34.765  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:30:44.710  3403  6140 D SSRM:n  : SIOP:: AP = 250, PST = 259 (W:18), CUR = 32, LCD = 0
,04-01 10:30:44.840  3403  3851 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,04-01 10:30:44.840  3403  3851 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:30:44.840  3403  3851 D BatteryService: online:4, current avg:31, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
04-01 10:30:44.840  3403  3851 D BatteryService: stay LED for fully charged
04-01 10:30:44.840  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,04-01 10:30:44.845  3403  3403 I MotionRecognitionService: Plugged
04-01 10:30:44.845  3403  3403 D MotionRecognitionService:   cableConnection= 1
04-01 10:30:44.845  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
04-01 10:30:44.845  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:30:44.845  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:30:44.845  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:30:44.845  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:30:44.855  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
04-01 10:30:44.855  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:30:44.870  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:30:44.870  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:30:44.870  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:30:44.870  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:30:44.920  3403  3418 I art     : Background partial concurrent mark sweep GC freed 40830(3MB) AllocSpace objects, 96(3MB) LOS objects, 33% free, 29MB/44MB, paused 2.755ms total 226.715ms
,04-01 10:30:48.095  3403  3605 D TimaService: TIMA: TimaService scheduler is intialized. 
,04-01 10:30:48.100  3403  3604 D TimaService: TimaServiceHandler.handleMessage what =1
,04-01 10:30:48.100  3403  3605 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000,
,04-01 10:30:48.115  3403  3605 I TLC_TIMA_PKM_initialize: initializing...
,04-01 10:30:48.115  3403  3605 I TLC_TIMA_PKM_initialize: root = 0, root_strlen = 1
04-01 10:30:48.115  3403  3605 I TLC_TIMA_PKM_initialize: process = ffffffff00000000000000000000000a, process_strlen = 32
,04-01 10:30:48.120  3403  3605 I TZ: mc_tlc_communication: input max_sendmsg_size = 262196
,04-01 10:30:48.120  3403  3605 I TZ: mc_tlc_communication: input max_recvmsg_size = 262196
04-01 10:30:48.120  3403  3605 I TZ: mc_tlc_communication: root = 0, root_len = 1
,04-01 10:30:48.120  3403  3605 I TZ: mc_tlc_communication: process = ffffffff00000000000000000000000a, process_strlen = 32
,04-01 10:30:48.120  3403  3605 I TZ: mc_tlc_communication: aligned max_sendmsg_size = 262208
04-01 10:30:48.120  3403  3605 I TZ: mc_tlc_communication: aligned max_recvmsg_size = 262208
,04-01 10:30:48.120  3403  3605 I TZ: mc_tlc_communication: device_id = 0x0
04-01 10:30:48.120  3403  3605 I TZ: mc_tlc_communication: tlc_open() was called
04-01 10:30:48.120  3403  3605 I TZ: mc_tlc_communication: Opening MobiCore device
,04-01 10:30:48.130  3403  3605 I TZ: mc_tlc_communication: Allocating message buffer for TCI,
04-01 10:30:48.135  3403  3605 I TZ: mc_tlc_communication: Opening the session
,04-01 10:30:48.150  3403  3605 I TZ: mc_tlc_communication: tlc_open() succeeded
,04-01 10:30:48.160  3403  3605 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,04-01 10:30:48.195  3403  6173 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,04-01 10:30:50.500  3403  3863 E Watchdog: !@Sync 10 [04-01 10:30:50.506],
,04-01 10:30:53.020  3403  3605 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
04-01 10:30:53.020  3403  3605 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,04-01 10:30:53.035  3403  3605 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
04-01 10:30:53.040  3403  3605 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,04-01 10:30:53.725  2891  4804 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,04-01 10:30:54.745  3403  6140 D SSRM:n  : SIOP:: AP = 250, PST = 258 (W:18), CUR = 31, LCD = 0,
,04-01 10:30:54.985  3403  4002 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:30:54.985  3403  4002 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:30:54.985  3403  4002 D BatteryService: online:4, current avg:31, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
,04-01 10:30:54.985  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,04-01 10:30:54.995  3403  3403 I MotionRecognitionService: Plugged
04-01 10:30:54.995  3403  3403 D MotionRecognitionService:   cableConnection= 1,
04-01 10:30:54.995  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
04-01 10:30:54.995  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:30:55.000  3403  4002 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 13ms,
04-01 10:30:55.000  3403  4002 D BatteryService: stay LED for fully charged
,04-01 10:30:55.005  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
04-01 10:30:55.005  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:30:55.010  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:30:55.025  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,04-01 10:30:55.025  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:30:55.040  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:30:55.040  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:30:55.040  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:30:55.040  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:31:04.795  3403  6140 D SSRM:n  : SIOP:: AP = 250, PST = 257 (W:20), CUR = 31, LCD = 0
,04-01 10:31:05.125  3403  4407 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:31:05.125  3403  4407 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:31:05.125  3403  4407 D BatteryService: online:4, current avg:29, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:33
,04-01 10:31:05.130  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,04-01 10:31:05.135  3403  3403 I MotionRecognitionService: Plugged
04-01 10:31:05.135  3403  3403 D MotionRecognitionService:   cableConnection= 1,
04-01 10:31:05.135  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
04-01 10:31:05.135  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:31:05.140  3403  4407 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 14ms,
04-01 10:31:05.140  3403  4407 D BatteryService: stay LED for fully charged
,04-01 10:31:05.150  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,04-01 10:31:05.150  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,04-01 10:31:05.150  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate,
,04-01 10:31:05.170  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
04-01 10:31:05.170  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:31:05.180  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:31:05.185  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:31:05.185  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:31:05.185  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:31:08.195  3403  6173 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,04-01 10:31:14.830  3403  6140 D SSRM:n  : SIOP:: AP = 250, PST = 255 (W:20), CUR = 29, LCD = 0
,04-01 10:31:15.270  3403  4793 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:31:15.270  3403  4793 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:31:15.270  3403  4793 D BatteryService: online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:42
,04-01 10:31:15.275  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
04-01 10:31:15.275  3403  4793 D BatteryService: stay LED for fully charged,
,04-01 10:31:15.280  3403  3403 I MotionRecognitionService: Plugged
04-01 10:31:15.280  3403  3403 D MotionRecognitionService:   cableConnection= 1
04-01 10:31:15.280  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
04-01 10:31:15.280  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:31:15.290  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
04-01 10:31:15.290  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:31:15.290  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:31:15.305  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
04-01 10:31:15.305  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:31:15.320  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:31:15.320  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:31:15.320  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:31:15.320  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:31:18.995  3403  3583 I PowerManagerService: [PWL] Off : 275s ago
,04-01 10:31:20.515  3403  3863 E Watchdog: !@Sync 11 [04-01 10:31:20.519]
,04-01 10:31:24.860  3403  6140 D SSRM:n  : SIOP:: AP = 250, PST = 254 (W:20), CUR = 28, LCD = 0
,04-01 10:31:25.410  3403  4028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:31:25.410  3403  4028 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:31:25.410  3403  4028 D BatteryService: online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
,04-01 10:31:25.415  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
04-01 10:31:25.415  3403  4028 D BatteryService: stay LED for fully charged
,04-01 10:31:25.425  3403  3403 I MotionRecognitionService: Plugged,
04-01 10:31:25.425  3403  3403 D MotionRecognitionService:   cableConnection= 1
04-01 10:31:25.425  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
04-01 10:31:25.425  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:31:25.430  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,04-01 10:31:25.430  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:31:25.430  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:31:25.450  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
04-01 10:31:25.450  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:31:25.460  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:31:25.465  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:31:25.465  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:31:25.465  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:31:28.200  3403  6173 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,04-01 10:31:34.890  3403  6140 D SSRM:n  : SIOP:: AP = 250, PST = 253 (W:20), CUR = 26, LCD = 0
,04-01 10:31:35.555  3403  4737 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:31:35.555  3403  4737 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:31:35.555  3403  4737 D BatteryService: online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
,04-01 10:31:35.555  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,04-01 10:31:35.565  3403  3403 I MotionRecognitionService: Plugged
04-01 10:31:35.565  3403  3403 D MotionRecognitionService:   cableConnection= 1
04-01 10:31:35.565  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
04-01 10:31:35.565  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:31:35.565  3403  4737 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 11ms,
04-01 10:31:35.565  3403  4737 D BatteryService: stay LED for fully charged
,04-01 10:31:35.580  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
04-01 10:31:35.580  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:31:35.580  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:31:35.595  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
04-01 10:31:35.595  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:31:35.605  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:31:35.605  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:31:35.605  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:31:35.605  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:31:44.920  3403  6140 D SSRM:n  : SIOP:: AP = 250, PST = 253 (W:22), CUR = 27, LCD = 0
,04-01 10:31:45.695  3403  4396 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:31:45.695  3403  4396 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:31:45.695  3403  4396 D BatteryService: online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,04-01 10:31:45.695  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
04-01 10:31:45.695  3403  4396 D BatteryService: stay LED for fully charged
,04-01 10:31:45.705  3403  3403 I MotionRecognitionService: Plugged
04-01 10:31:45.705  3403  3403 D MotionRecognitionService:   cableConnection= 1
04-01 10:31:45.710  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
04-01 10:31:45.710  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:31:45.710  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:31:45.710  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
04-01 10:31:45.710  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate,
,04-01 10:31:45.720  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:31:45.725  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,04-01 10:31:45.725  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:31:45.740  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:31:45.740  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:31:45.740  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:31:48.210  3403  6173 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,04-01 10:31:50.525  3403  3863 E Watchdog: !@Sync 12 [04-01 10:31:50.528]
,04-01 10:31:53.725  2891  4804 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,04-01 10:31:54.950  3403  6140 D SSRM:n  : SIOP:: AP = 250, PST = 252 (W:22), CUR = 27, LCD = 0
,04-01 10:31:55.830  3403  3649 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:31:55.835  3403  3649 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:31:55.835  3403  3649 D BatteryService: online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,04-01 10:31:55.835  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,04-01 10:31:55.845  3403  3403 I MotionRecognitionService: Plugged
04-01 10:31:55.845  3403  3403 D MotionRecognitionService:   cableConnection= 1,
04-01 10:31:55.845  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
04-01 10:31:55.845  3403  3403 D MotionRecognitionService: skip setTransmitPower. ,
,04-01 10:31:55.850  3403  3649 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 17ms,
04-01 10:31:55.850  3403  3649 D BatteryService: stay LED for fully charged
,04-01 10:31:55.855  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:31:55.855  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:31:55.855  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:31:55.870  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,04-01 10:31:55.870  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:31:55.880  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:31:55.880  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:31:55.880  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:31:55.880  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:31:59.995  3403  3616 V AlarmManager: waitForAlarm result :8
04-01 10:31:59.995  3403  3616 V AlarmManager: No more alarm at this time.nowELAPSED=382196 batch.start=545840
,04-01 10:32:00.020  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,04-01 10:32:00.020  3724  3724 I PERF    : received broadcast android.intent.action.TIME_TICK
,04-01 10:32:00.025  3724  3724 D KeyguardUpdateMonitor: handleTimeUpdate
,04-01 10:32:00.025  3403  3616 V AlarmManager: waitForAlarm result :8
,04-01 10:32:00.025  3403  3616 V AlarmManager: No more alarm at this time.nowELAPSED=382228 batch.start=442197
,04-01 10:32:00.045  3724  3724 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,04-01 10:32:00.050  3724  3724 D SecKeyguardClockView: HomeTimezone(): 1
,04-01 10:32:00.060  3724  3724 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,04-01 10:32:00.060  3724  3724 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,04-01 10:32:00.075  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,04-01 10:32:00.110  3724  3724 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,04-01 10:32:00.110  3724  3724 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,04-01 10:32:00.115  3724  3724 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,04-01 10:32:00.115  3724  3724 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,04-01 10:32:00.120  3724  3724 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,04-01 10:32:00.125  3724  3724 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,04-01 10:32:00.140  3724  3724 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,04-01 10:32:04.975  3403  6140 D SSRM:n  : SIOP:: AP = 250, PST = 251 (W:22), CUR = 27, LCD = 0
,04-01 10:32:05.045  3403  3567 W ProcessCpuTracker: Skipping unknown process pid 11787
,04-01 10:32:05.970  3403  3434 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:32:05.970  3403  3434 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:32:05.970  3403  3434 D BatteryService: online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:39
,04-01 10:32:05.975  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
04-01 10:32:05.975  3403  3434 D BatteryService: stay LED for fully charged
,04-01 10:32:05.980  3403  3403 I MotionRecognitionService: Plugged,
04-01 10:32:05.985  3403  3403 D MotionRecognitionService:   cableConnection= 1
04-01 10:32:05.985  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
04-01 10:32:05.985  3403  3403 D MotionRecognitionService: skip setTransmitPower. ,
,04-01 10:32:05.990  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
04-01 10:32:05.990  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:32:05.990  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:32:06.010  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
04-01 10:32:06.010  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:32:06.020  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:32:06.020  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:32:06.020  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:32:06.020  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:32:08.215  3403  6173 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,04-01 10:32:14.000  3403  3583 I PowerManagerService: [PWL] Off : 330s ago
,04-01 10:32:15.005  3403  6140 D SSRM:n  : SIOP:: AP = 250, PST = 251 (W:22), CUR = 26, LCD = 0
,04-01 10:32:15.475 11165 11264 D AndroidHttpClient: [NALSECURITY] isMmsRequest() : CoreProtocolPNames.USER_AGENT = Dalvik/2.1.0 (Linux; U; Android 5.1.1; SM-N910C Build/LMY47X)
,04-01 10:32:15.480 11165 11264 D AndroidHttpClient: [NALSECURITY] checkMmsSendPermission() : isMmsRequest() = false method = GET
,04-01 10:32:15.480 11165 11264 I System.out: Thread-1613(ApacheHTTPLog):isSBSettingEnabled false
,04-01 10:32:15.480 11165 11264 I System.out: Thread-1613(ApacheHTTPLog):isShipBuild true
,04-01 10:32:15.480 11165 11264 I System.out: Thread-1613(ApacheHTTPLog):SMARTBONDING_ENABLED is false
04-01 10:32:15.480 11165 11264 I System.out: Thread-1613(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,04-01 10:32:15.490  2873  3464 D EnterpriseController: netId is 0
04-01 10:32:15.490  2873  3464 D Netd    : getNetworkForDns: using netid 502 for uid 10202
,04-01 10:32:16.110  3403  3830 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:32:16.110  3403  3830 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:32:16.110  3403  3830 D BatteryService: online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:29
,04-01 10:32:16.110  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
04-01 10:32:16.115  3403  3830 D BatteryService: stay LED for fully charged
,04-01 10:32:16.120  3403  3403 I MotionRecognitionService: Plugged
04-01 10:32:16.120  3403  3403 D MotionRecognitionService:   cableConnection= 1
04-01 10:32:16.120  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
04-01 10:32:16.120  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:32:16.130  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:32:16.130  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:32:16.135  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:32:16.140  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
04-01 10:32:16.145  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
04-01 10:32:16.145  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:32:16.145  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:32:16.145  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:32:16.145  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:32:17.050 11399 11462 I jxcore-log: # setup
04-01 10:32:17.050 11399 11462 I jxcore-log: 
,04-01 10:32:20.530  3403  3863 E Watchdog: !@Sync 13 [04-01 10:32:20.536]
,04-01 10:32:25.040  3403  6140 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:24), CUR = 25, LCD = 0
,04-01 10:32:26.245  3403  4407 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:32:26.245  3403  4407 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:32:26.245  3403  4407 D BatteryService: online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:34
,04-01 10:32:26.250  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
04-01 10:32:26.250  3403  4407 D BatteryService: stay LED for fully charged
,04-01 10:32:26.255  3403  3403 I MotionRecognitionService: Plugged
04-01 10:32:26.255  3403  3403 D MotionRecognitionService:   cableConnection= 1,
04-01 10:32:26.255  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
04-01 10:32:26.255  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:32:26.265  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
04-01 10:32:26.265  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:32:26.265  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:32:26.290  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,04-01 10:32:26.290  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:32:26.300  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:32:26.300  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:32:26.300  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:32:26.300  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:32:28.220  3403  6173 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,04-01 10:32:35.075  3403  6140 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:24), CUR = 25, LCD = 0
,04-01 10:32:36.385  3403  4786 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:32:36.385  3403  4786 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:32:36.385  3403  4786 D BatteryService: online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,04-01 10:32:36.390  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,04-01 10:32:36.395  3403  3403 I MotionRecognitionService: Plugged
,04-01 10:32:36.395  3403  3403 D MotionRecognitionService:   cableConnection= 1
04-01 10:32:36.395  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,04-01 10:32:36.395  3403  3403 D MotionRecognitionService: skip setTransmitPower. ,
04-01 10:32:36.400  3403  4786 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 15ms
,04-01 10:32:36.400  3403  4786 D BatteryService: stay LED for fully charged
,04-01 10:32:36.410  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,04-01 10:32:36.410  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,04-01 10:32:36.410  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate,
,04-01 10:32:36.435  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
04-01 10:32:36.435  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:32:36.445  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:32:36.445  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:32:36.445  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:32:36.445  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:32:45.105  3403  6140 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:24), CUR = 25, LCD = 0
,04-01 10:32:46.495  3403  3850 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,04-01 10:32:46.495  3403  3850 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:32:46.495  3403  3850 D BatteryService: online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:29
04-01 10:32:46.495  3403  3850 D BatteryService: stay LED for fully charged
04-01 10:32:46.495  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,04-01 10:32:46.495  3403  3403 I MotionRecognitionService: Plugged
04-01 10:32:46.495  3403  3403 D MotionRecognitionService:   cableConnection= 1
04-01 10:32:46.495  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
04-01 10:32:46.495  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:32:46.500  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:32:46.500  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:32:46.500  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:32:46.505  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:32:46.505  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
04-01 10:32:46.505  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:32:46.520  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:32:46.520  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:32:46.525  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:32:46.570 11165 11264 I System.out: Thread-1613 calls detatch()
,04-01 10:32:46.585 11165 11264 E GoogleConversionReporter: Error sending ping
04-01 10:32:46.585 11165 11264 E GoogleConversionReporter: javax.net.ssl.SSLHandshakeException: Connection closed by peer
04-01 10:32:46.585 11165 11264 E GoogleConversionReporter: 	at com.android.org.conscrypt.NativeCrypto.SSL_do_handshake(Native Method)
04-01 10:32:46.585 11165 11264 E GoogleConversionReporter: 	at com.android.org.conscrypt.OpenSSLSocketImpl.startHandshake(OpenSSLSocketImpl.java:347)
04-01 10:32:46.585 11165 11264 E GoogleConversionReporter: 	at android.net.SSLCertificateSocketFactory.verifyHostname(SSLCertificateSocketFactory.java:241)
04-01 10:32:46.585 11165 11264 E GoogleConversionReporter: 	at android.net.SSLCertificateSocketFactory.createSocket(SSLCertificateSocketFactory.java:494)
04-01 10:32:46.585 11165 11264 E GoogleConversionReporter: 	at org.apache.http.conn.ssl.SSLSocketFactory.createSocket(SSLSocketFactory.java:388)
04-01 10:32:46.585 11165 11264 E GoogleConversionReporter: 	at org.apache.http.impl.conn.DefaultClientConnectionOperator.openConnection(DefaultClientConnectionOperator.java:219)
04-01 10:32:46.585 11165 11264 E GoogleConversionReporter: 	at org.apache.http.impl.conn.AbstractPoolEntry.open(AbstractPoolEntry.java:172)
04-01 10:32:46.585 11165 11264 E GoogleConversionReporter: 	at org.apache.http.impl.conn.AbstractPooledConnAdapter.open(AbstractPooledConnAdapter.java:130)
04-01 10:32:46.585 11165 11264 E GoogleConversionReporter: 	at org.apache.http.impl.client.DefaultRequestDirector.executeOriginal(DefaultRequestDirector.java:1317)
04-01 10:32:46.585 11165 11264 E GoogleConversionReporter: 	at org.apache.http.impl.client.DefaultRequestDirector.execute(DefaultRequestDirector.java:707)
04-01 10:32:46.585 11165 11264 E GoogleConversionReporter: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:694)
04-01 10:32:46.585 11165 11264 E GoogleConversionReporter: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:520)
04-01 10:32:46.585 11165 11264 E GoogleConversionReporter: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:498)
04-01 10:32:46.585 11165 11264 E GoogleConversionReporter: 	at android.net.http.AndroidHttpClient.execute(AndroidHttpClient.java:335)
04-01 10:32:46.585 11165 11264 E GoogleConversionReporter: 	at afz.a(SourceFile:217)
04-01 10:32:46.585 11165 11264 E GoogleConversionReporter: 	at agc.run(SourceFile:173)
04-01 10:32:46.585 11165 11264 E GoogleConversionReporter: 	at java.lang.Thread.run(Thread.java:818)
,04-01 10:32:47.605 11165 11264 D AndroidHttpClient: [NALSECURITY] isMmsRequest() : CoreProtocolPNames.USER_AGENT = Dalvik/2.1.0 (Linux; U; Android 5.1.1; SM-N910C Build/LMY47X)
,04-01 10:32:47.610 11165 11264 D AndroidHttpClient: [NALSECURITY] checkMmsSendPermission() : isMmsRequest() = false method = GET
,04-01 10:32:47.615 11165 11264 I System.out: Thread-1613(ApacheHTTPLog):isSBSettingEnabled false
,04-01 10:32:47.620 11165 11264 I System.out: Thread-1613(ApacheHTTPLog):isShipBuild true
,04-01 10:32:47.625 11165 11264 I System.out: Thread-1613(ApacheHTTPLog):SMARTBONDING_ENABLED is false
,04-01 10:32:47.630 11165 11264 I System.out: Thread-1613(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,04-01 10:32:47.635  2873  3464 D EnterpriseController: netId is 0
04-01 10:32:47.635  2873  3464 D Netd    : getNetworkForDns: using netid 502 for uid 10202
,04-01 10:32:48.225  3403  6173 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,04-01 10:32:50.540  3403  3863 E Watchdog: !@Sync 14 [04-01 10:32:50.543]
,04-01 10:32:53.725  2891  4804 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,04-01 10:32:55.130  3403  6140 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:24), CUR = 24, LCD = 0
,04-01 10:32:56.635  3403  4793 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:32:56.635  3403  4793 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:32:56.635  3403  4793 D BatteryService: online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
,04-01 10:32:56.640  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,04-01 10:32:56.645  3403  3403 I MotionRecognitionService: Plugged
04-01 10:32:56.645  3403  3403 D MotionRecognitionService:   cableConnection= 1,
04-01 10:32:56.650  3403  4793 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 12ms
04-01 10:32:56.650  3403  4793 D BatteryService: stay LED for fully charged
,04-01 10:32:56.650  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
04-01 10:32:56.650  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:32:56.660  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,04-01 10:32:56.660  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,04-01 10:32:56.660  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate,
,04-01 10:32:56.680  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
04-01 10:32:56.680  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:32:56.690  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:32:56.695  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:32:56.695  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:32:56.695  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:32:59.995  3403  3616 V AlarmManager: waitForAlarm result :8
,04-01 10:33:05.160  3403  6140 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:26), CUR = 22, LCD = 0
,04-01 10:33:06.775  3403  4028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:33:06.775  3403  4028 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:33:06.775  3403  4028 D BatteryService: online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,04-01 10:33:06.775  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,04-01 10:33:06.785  3403  4028 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 12ms
04-01 10:33:06.785  3403  4028 D BatteryService: stay LED for fully charged
,04-01 10:33:06.790  3403  3403 I MotionRecognitionService: Plugged,
04-01 10:33:06.790  3403  3403 D MotionRecognitionService:   cableConnection= 1
,04-01 10:33:06.790  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
04-01 10:33:06.790  3403  3403 D MotionRecognitionService: skip setTransmitPower. ,
,04-01 10:33:06.800  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
04-01 10:33:06.800  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:33:06.800  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate,
,04-01 10:33:06.815  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
04-01 10:33:06.815  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:33:06.830  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:33:06.830  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:33:06.830  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:33:06.830  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:33:08.230  3403  6173 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,04-01 10:33:08.890 11165 11264 I System.out: Thread-1613 calls detatch()
,04-01 10:33:08.890 11165 11264 E GoogleConversionReporter: Error sending ping
04-01 10:33:08.890 11165 11264 E GoogleConversionReporter: javax.net.ssl.SSLHandshakeException: Connection closed by peer
04-01 10:33:08.890 11165 11264 E GoogleConversionReporter: 	at com.android.org.conscrypt.NativeCrypto.SSL_do_handshake(Native Method)
04-01 10:33:08.890 11165 11264 E GoogleConversionReporter: 	at com.android.org.conscrypt.OpenSSLSocketImpl.startHandshake(OpenSSLSocketImpl.java:347)
04-01 10:33:08.890 11165 11264 E GoogleConversionReporter: 	at android.net.SSLCertificateSocketFactory.verifyHostname(SSLCertificateSocketFactory.java:241)
04-01 10:33:08.890 11165 11264 E GoogleConversionReporter: 	at android.net.SSLCertificateSocketFactory.createSocket(SSLCertificateSocketFactory.java:494)
04-01 10:33:08.890 11165 11264 E GoogleConversionReporter: 	at org.apache.http.conn.ssl.SSLSocketFactory.createSocket(SSLSocketFactory.java:388)
04-01 10:33:08.890 11165 11264 E GoogleConversionReporter: 	at org.apache.http.impl.conn.DefaultClientConnectionOperator.openConnection(DefaultClientConnectionOperator.java:219)
04-01 10:33:08.890 11165 11264 E GoogleConversionReporter: 	at org.apache.http.impl.conn.AbstractPoolEntry.open(AbstractPoolEntry.java:172)
04-01 10:33:08.890 11165 11264 E GoogleConversionReporter: 	at org.apache.http.impl.conn.AbstractPooledConnAdapter.open(AbstractPooledConnAdapter.java:130)
04-01 10:33:08.890 11165 11264 E GoogleConversionReporter: 	at org.apache.http.impl.client.DefaultRequestDirector.executeOriginal(DefaultRequestDirector.java:1317)
04-01 10:33:08.890 11165 11264 E GoogleConversionReporter: 	at org.apache.http.impl.client.DefaultRequestDirector.execute(DefaultRequestDirector.java:707)
04-01 10:33:08.890 11165 11264 E GoogleConversionReporter: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:694)
04-01 10:33:08.890 11165 11264 E GoogleConversionReporter: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:520)
04-01 10:33:08.890 11165 11264 E GoogleConversionReporter: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:498)
04-01 10:33:08.890 11165 11264 E GoogleConversionReporter: 	at android.net.http.AndroidHttpClient.execute(AndroidHttpClient.java:335)
04-01 10:33:08.890 11165 11264 E GoogleConversionReporter: 	at afz.a(SourceFile:217)
04-01 10:33:08.890 11165 11264 E GoogleConversionReporter: 	at agc.run(SourceFile:173)
04-01 10:33:08.890 11165 11264 E GoogleConversionReporter: 	at java.lang.Thread.run(Thread.java:818)
,04-01 10:33:14.000  3403  3583 I PowerManagerService: [PWL] Off : 390s ago
,04-01 10:33:15.190  3403  6140 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:26), CUR = 22, LCD = 0
,04-01 10:33:16.915  3403  4002 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:33:16.915  3403  4002 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:33:16.915  3403  4002 D BatteryService: online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:21
,04-01 10:33:16.915  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
04-01 10:33:16.920  3403  4002 D BatteryService: stay LED for fully charged,
,04-01 10:33:16.930  3403  3403 I MotionRecognitionService: Plugged,
04-01 10:33:16.930  3403  3403 D MotionRecognitionService:   cableConnection= 1,
,04-01 10:33:16.930  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
04-01 10:33:16.930  3403  3403 D MotionRecognitionService: skip setTransmitPower. ,
,04-01 10:33:16.940  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,04-01 10:33:16.940  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,04-01 10:33:16.940  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate,
,04-01 10:33:16.965  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,04-01 10:33:16.965  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:33:16.975  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:33:16.975  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:33:16.975  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:33:16.975  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:33:20.545  3403  3863 E Watchdog: !@Sync 15 [04-01 10:33:20.550]
,04-01 10:33:25.225  3403  6140 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:26), CUR = 23, LCD = 0
,04-01 10:33:27.055  3403  3850 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:33:27.055  3403  3850 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:33:27.055  3403  3850 D BatteryService: online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:37
,04-01 10:33:27.060  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
04-01 10:33:27.060  3403  3850 D BatteryService: stay LED for fully charged,
,04-01 10:33:27.070  3403  3403 I MotionRecognitionService: Plugged
04-01 10:33:27.070  3403  3403 D MotionRecognitionService:   cableConnection= 1
04-01 10:33:27.070  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
04-01 10:33:27.070  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:33:27.075  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
04-01 10:33:27.075  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:33:27.075  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:33:27.095  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,04-01 10:33:27.095  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:33:27.110  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:33:27.110  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:33:27.110  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:33:27.110  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:33:28.235  3403  6173 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,04-01 10:33:35.255  3403  6140 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:26), CUR = 23, LCD = 0
,04-01 10:33:37.190  3403  4027 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:33:37.190  3403  4027 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:33:37.190  3403  4027 D BatteryService: online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:37
,04-01 10:33:37.195  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
04-01 10:33:37.195  3403  4027 D BatteryService: stay LED for fully charged
,04-01 10:33:37.200  3403  3403 I MotionRecognitionService: Plugged
04-01 10:33:37.200  3403  3403 D MotionRecognitionService:   cableConnection= 1
04-01 10:33:37.200  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,04-01 10:33:37.200  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:33:37.210  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
04-01 10:33:37.210  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:33:37.210  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:33:37.230  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,04-01 10:33:37.230  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:33:37.240  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:33:37.240  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:33:37.240  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:33:37.240  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:33:41.895  2906  2906 I bootchecker: bootchecker wake up!!
,04-01 10:33:45.290  3403  6140 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:28), CUR = 22, LCD = 0
,04-01 10:33:47.330  3403  4407 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:33:47.330  3403  4407 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:33:47.330  3403  4407 D BatteryService: online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
,04-01 10:33:47.335  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,04-01 10:33:47.345  3403  4407 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 11ms
04-01 10:33:47.345  3403  4407 D BatteryService: stay LED for fully charged,
,04-01 10:33:47.345  3403  3403 I MotionRecognitionService: Plugged
04-01 10:33:47.345  3403  3403 D MotionRecognitionService:   cableConnection= 1,
04-01 10:33:47.345  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,04-01 10:33:47.345  3403  3403 D MotionRecognitionService: skip setTransmitPower. ,
,04-01 10:33:47.360  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
04-01 10:33:47.360  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,04-01 10:33:47.360  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate,
,04-01 10:33:47.380  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,04-01 10:33:47.380  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:33:47.390  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:33:47.390  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:33:47.390  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:33:47.390  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:33:48.245  3403  6173 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,04-01 10:33:50.555  3403  3863 E Watchdog: !@Sync 16 [04-01 10:33:50.558]
,04-01 10:33:53.725  2891  4804 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,04-01 10:33:55.320  3403  6140 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:28), CUR = 22, LCD = 0
,04-01 10:33:57.470  3403  4786 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:33:57.470  3403  4786 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:33:57.470  3403  4786 D BatteryService: online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
,04-01 10:33:57.470  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,04-01 10:33:57.480  3403  3403 I MotionRecognitionService: Plugged
04-01 10:33:57.480  3403  3403 D MotionRecognitionService:   cableConnection= 1
04-01 10:33:57.480  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
04-01 10:33:57.480  3403  3403 D MotionRecognitionService: skip setTransmitPower. ,
,04-01 10:33:57.485  3403  4786 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 14ms,
04-01 10:33:57.485  3403  4786 D BatteryService: stay LED for fully charged,
04-01 10:33:57.490  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,04-01 10:33:57.490  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:33:57.490  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:33:57.510  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
04-01 10:33:57.510  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:33:57.520  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:33:57.520  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:33:57.525  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:33:57.525  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:34:05.345  3403  6140 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:28), CUR = 21, LCD = 0
,04-01 10:34:07.610  3403  3851 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:34:07.610  3403  3851 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:34:07.610  3403  3851 D BatteryService: online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:7
,04-01 10:34:07.615  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,04-01 10:34:07.620  3403  3851 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 10ms
04-01 10:34:07.620  3403  3851 D BatteryService: stay LED for fully charged,
,04-01 10:34:07.625  3403  3403 I MotionRecognitionService: Plugged,
04-01 10:34:07.625  3403  3403 D MotionRecognitionService:   cableConnection= 1,
04-01 10:34:07.625  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,04-01 10:34:07.625  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:34:07.635  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
04-01 10:34:07.635  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:34:07.635  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate,
,04-01 10:34:07.655  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
04-01 10:34:07.655  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:34:07.665  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:34:07.665  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:34:07.665  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:34:07.665  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:34:08.250  3403  6173 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,04-01 10:34:15.375  3403  6140 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:28), CUR = 20, LCD = 0
,04-01 10:34:17.750  3403  4737 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:34:17.750  3403  4737 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:34:17.750  3403  4737 D BatteryService: online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,04-01 10:34:17.750  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,04-01 10:34:17.760  3403  4737 D BatteryService: stay LED for fully charged
04-01 10:34:17.760  3403  3403 I MotionRecognitionService: Plugged,
,04-01 10:34:17.760  3403  3403 D MotionRecognitionService:   cableConnection= 1
,04-01 10:34:17.760  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
04-01 10:34:17.760  3403  3403 D MotionRecognitionService: skip setTransmitPower. ,
,04-01 10:34:17.775  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,04-01 10:34:17.775  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:34:17.775  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:34:17.795  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
04-01 10:34:17.795  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:34:17.805  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:34:17.805  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:34:17.805  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:34:17.805  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:34:19.000  3403  3583 I PowerManagerService: [PWL] Off : 455s ago
,04-01 10:34:20.560  3403  3863 E Watchdog: !@Sync 17 [04-01 10:34:20.565]
,04-01 10:34:25.400  3403  6140 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 21, LCD = 0
,04-01 10:34:27.890  3403  4396 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:34:27.890  3403  4396 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:34:27.890  3403  4396 D BatteryService: online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
,04-01 10:34:27.890  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
04-01 10:34:27.890  3403  4396 D BatteryService: stay LED for fully charged
,04-01 10:34:27.900  3403  3403 I MotionRecognitionService: Plugged,
,04-01 10:34:27.900  3403  3403 D MotionRecognitionService:   cableConnection= 1
04-01 10:34:27.900  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
04-01 10:34:27.900  3403  3403 D MotionRecognitionService: skip setTransmitPower. ,
,04-01 10:34:27.910  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,04-01 10:34:27.910  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:34:27.910  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:34:27.930  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,04-01 10:34:27.935  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:34:27.945  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:34:27.945  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:34:27.945  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:34:27.945  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:34:28.260  3403  6173 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,04-01 10:34:35.435  3403  6140 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 21, LCD = 0
,04-01 10:34:38.025  3403  3649 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:34:38.025  3403  3649 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:34:38.025  3403  3649 D BatteryService: online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
,04-01 10:34:38.030  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
04-01 10:34:38.030  3403  3649 D BatteryService: stay LED for fully charged
,04-01 10:34:38.035  3403  3403 I MotionRecognitionService: Plugged
04-01 10:34:38.035  3403  3403 D MotionRecognitionService:   cableConnection= 1
04-01 10:34:38.035  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
04-01 10:34:38.035  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:34:38.045  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
04-01 10:34:38.045  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,04-01 10:34:38.045  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:34:38.065  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,04-01 10:34:38.070  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:34:38.075  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:34:38.075  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:34:38.075  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:34:38.075  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:34:43.640  3403  3616 V AlarmManager: waitForAlarm result :4
,04-01 10:34:43.680  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
04-01 10:34:43.680  3724  3724 I PERF    : received broadcast android.intent.action.TIME_TICK
,04-01 10:34:43.685  3724  3724 D KeyguardUpdateMonitor: handleTimeUpdate
,04-01 10:34:43.700  3724  3724 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,04-01 10:34:43.705  3724  3724 D SecKeyguardClockView: HomeTimezone(): 1
,04-01 10:34:43.710  3724  3724 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,04-01 10:34:43.710  3724  3724 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,04-01 10:34:43.720  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,04-01 10:34:43.755  3724  3724 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,04-01 10:34:43.760  3724  3724 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,04-01 10:34:43.760  3724  3724 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,04-01 10:34:43.765  3724  3724 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,04-01 10:34:43.770  3724  3724 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,04-01 10:34:43.770  3724  3724 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,04-01 10:34:43.785  3724  3724 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,04-01 10:34:45.465  3403  6140 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 20, LCD = 0
,04-01 10:34:48.170  3403  4002 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,04-01 10:34:48.170  3403  4002 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
,04-01 10:34:48.170  3403  4002 D BatteryService: online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
04-01 10:34:48.170  3403  4002 D BatteryService: stay LED for fully charged
04-01 10:34:48.170  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,04-01 10:34:48.175  3403  3403 I MotionRecognitionService: Plugged
04-01 10:34:48.175  3403  3403 D MotionRecognitionService:   cableConnection= 1
04-01 10:34:48.175  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
04-01 10:34:48.175  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:34:48.185  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:34:48.185  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:34:48.185  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:34:48.190  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:34:48.195  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,04-01 10:34:48.195  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:34:48.210  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:34:48.210  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:34:48.210  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:34:48.265  3403  6173 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,04-01 10:34:50.570  3403  3863 E Watchdog: !@Sync 18 [04-01 10:34:50.572]
,04-01 10:34:53.725  2891  4804 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,04-01 10:34:55.485  3403  6140 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 21, LCD = 0
,04-01 10:34:58.305  3403  3830 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:34:58.305  3403  3830 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:34:58.305  3403  3830 D BatteryService: online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,04-01 10:34:58.310  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
04-01 10:34:58.310  3403  3830 D BatteryService: stay LED for fully charged
,04-01 10:34:58.320  3403  3403 I MotionRecognitionService: Plugged
04-01 10:34:58.320  3403  3403 D MotionRecognitionService:   cableConnection= 1
04-01 10:34:58.320  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
04-01 10:34:58.320  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:34:58.330  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
04-01 10:34:58.330  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:34:58.330  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:34:58.350  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,04-01 10:34:58.350  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:34:58.360  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:34:58.360  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:34:58.360  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:34:58.360  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:34:59.995  3403  3616 V AlarmManager: waitForAlarm result :8
,04-01 10:35:05.510  3403  6140 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 21, LCD = 0
,04-01 10:35:08.270  3403  6173 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,04-01 10:35:08.440  3403  3432 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:35:08.440  3403  3432 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:35:08.440  3403  3432 D BatteryService: online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
,04-01 10:35:08.445  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
04-01 10:35:08.445  3403  3432 D BatteryService: stay LED for fully charged
,04-01 10:35:08.455  3403  3403 I MotionRecognitionService: Plugged
04-01 10:35:08.455  3403  3403 D MotionRecognitionService:   cableConnection= 1
04-01 10:35:08.455  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
04-01 10:35:08.455  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:35:08.460  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
04-01 10:35:08.460  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:35:08.460  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate,
,04-01 10:35:08.480  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
04-01 10:35:08.480  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:35:08.490  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:35:08.490  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:35:08.490  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:35:08.490  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:35:15.540  3403  6140 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 18, LCD = 0
,04-01 10:35:18.610  3403  4028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:35:18.610  3403  4028 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:35:18.610  3403  4028 D BatteryService: online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,04-01 10:35:18.615  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,04-01 10:35:18.620  3403  3403 I MotionRecognitionService: Plugged
04-01 10:35:18.620  3403  3403 D MotionRecognitionService:   cableConnection= 1
04-01 10:35:18.620  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
,04-01 10:35:18.620  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:35:18.625  3403  4028 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 14ms,
,04-01 10:35:18.625  3403  4028 D BatteryService: stay LED for fully charged,
,04-01 10:35:18.635  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
04-01 10:35:18.635  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
04-01 10:35:18.635  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:35:18.650  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,04-01 10:35:18.650  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:35:18.665  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:35:18.665  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:35:18.665  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:35:18.670  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:35:20.575  3403  3863 E Watchdog: !@Sync 19 [04-01 10:35:20.580]
,04-01 10:35:25.565  3403  6140 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 18, LCD = 0
,04-01 10:35:28.275  3403  6173 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,04-01 10:35:28.750  3403  3434 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:35:28.750  3403  3434 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:35:28.750  3403  3434 D BatteryService: online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
,04-01 10:35:28.755  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
04-01 10:35:28.755  3403  3434 D BatteryService: stay LED for fully charged
,04-01 10:35:28.765  3403  3403 I MotionRecognitionService: Plugged,
04-01 10:35:28.765  3403  3403 D MotionRecognitionService:   cableConnection= 1
,04-01 10:35:28.765  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,04-01 10:35:28.765  3403  3403 D MotionRecognitionService: skip setTransmitPower. ,
,04-01 10:35:28.775  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:35:28.775  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:35:28.775  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:35:28.790  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
04-01 10:35:28.790  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:35:28.805  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:35:28.805  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:35:28.805  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:35:28.805  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:35:29.000  3403  3583 I PowerManagerService: [PWL] Off : 525s ago
,04-01 10:35:35.595  3403  6140 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 18, LCD = 0
,04-01 10:35:38.890  3403  4003 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:35:38.890  3403  4003 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:35:38.890  3403  4003 D BatteryService: online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:29
,04-01 10:35:38.895  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
04-01 10:35:38.895  3403  4003 D BatteryService: stay LED for fully charged,
,04-01 10:35:38.905  3403  3403 I MotionRecognitionService: Plugged
04-01 10:35:38.905  3403  3403 D MotionRecognitionService:   cableConnection= 1,
,04-01 10:35:38.905  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,04-01 10:35:38.905  3403  3403 D MotionRecognitionService: skip setTransmitPower. ,
,04-01 10:35:38.920  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:35:38.920  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:35:38.920  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:35:38.930  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
04-01 10:35:38.930  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:35:38.945  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:35:38.945  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:35:38.945  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:35:38.945  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:35:45.620  3403  6140 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 17, LCD = 0
,04-01 10:35:48.095  3403  3605 D TimaService: TIMA: TimaService scheduler is intialized. 
04-01 10:35:48.095  3403  3605 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,04-01 10:35:48.100  3403  3604 D TimaService: TimaServiceHandler.handleMessage what =1
,04-01 10:35:48.280  3403  6173 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,04-01 10:35:49.050  3403  4793 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:35:49.050  3403  4793 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:35:49.050  3403  4793 D BatteryService: online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
,04-01 10:35:49.050  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
04-01 10:35:49.055  3403  4793 D BatteryService: stay LED for fully charged
,04-01 10:35:49.060  3403  3403 I MotionRecognitionService: Plugged
04-01 10:35:49.060  3403  3403 D MotionRecognitionService:   cableConnection= 1,
04-01 10:35:49.060  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
04-01 10:35:49.060  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:35:49.070  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,04-01 10:35:49.070  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:35:49.070  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:35:49.090  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,04-01 10:35:49.090  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:35:49.105  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:35:49.105  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:35:49.105  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:35:49.105  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:35:50.585  3403  3863 E Watchdog: !@Sync 20 [04-01 10:35:50.587]
,04-01 10:35:50.620  3403  3605 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
04-01 10:35:50.620  3403  3605 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,04-01 10:35:50.635  3403  3605 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;,
04-01 10:35:50.635  3403  3605 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,04-01 10:35:53.725  2891  4804 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,04-01 10:35:53.805  3403  3581 I ActivityManager: setMaxStartingBackgroundTimer onfinish
04-01 10:35:53.805  3403  3581 I ActivityManager: MaxStartingBackground is set. ( current : 8 )
,04-01 10:35:55.650  3403  6140 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 16, LCD = 0
,04-01 10:35:59.190  3403  3850 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:35:59.190  3403  3850 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:35:59.190  3403  3850 D BatteryService: online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:32
,04-01 10:35:59.190  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
04-01 10:35:59.195  3403  3850 D BatteryService: stay LED for fully charged,
,04-01 10:35:59.200  3403  3403 I MotionRecognitionService: Plugged
04-01 10:35:59.200  3403  3403 D MotionRecognitionService:   cableConnection= 1,
04-01 10:35:59.200  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
04-01 10:35:59.200  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:35:59.210  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
04-01 10:35:59.210  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:35:59.210  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:35:59.230  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,04-01 10:35:59.230  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:35:59.240  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:35:59.240  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:35:59.240  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:35:59.240  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:36:05.685  3403  6140 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 18, LCD = 0
,04-01 10:36:08.290  3403  6173 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,04-01 10:36:09.325  3403  4027 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,04-01 10:36:09.330  3403  4027 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:36:09.330  3403  4027 D BatteryService: online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
04-01 10:36:09.330  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
04-01 10:36:09.335  3403  4027 D BatteryService: stay LED for fully charged
,04-01 10:36:09.340  3403  3403 I MotionRecognitionService: Plugged,
04-01 10:36:09.340  3403  3403 D MotionRecognitionService:   cableConnection= 1
04-01 10:36:09.340  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,04-01 10:36:09.340  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:36:09.350  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
04-01 10:36:09.350  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:36:09.350  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:36:09.370  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,04-01 10:36:09.370  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:36:09.380  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:36:09.380  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:36:09.380  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:36:09.380  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:36:09.755  3403  3432 I ActivityManager: Killing 10176:com.google.android.apps.docs/u0a101 (adj 15): emptyCount ##31
,04-01 10:36:15.715  3403  6140 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 19, LCD = 0
,04-01 10:36:19.465  3403  4737 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:36:19.465  3403  4737 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:36:19.465  3403  4737 D BatteryService: online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
,04-01 10:36:19.470  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
04-01 10:36:19.475  3403  4737 D BatteryService: stay LED for fully charged
,04-01 10:36:19.480  3403  3403 I MotionRecognitionService: Plugged
,04-01 10:36:19.480  3403  3403 D MotionRecognitionService:   cableConnection= 1
04-01 10:36:19.480  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
04-01 10:36:19.480  3403  3403 D MotionRecognitionService: skip setTransmitPower. ,
,04-01 10:36:19.490  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
04-01 10:36:19.490  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:36:19.495  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:36:19.505  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
04-01 10:36:19.505  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:36:19.520  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:36:19.520  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:36:19.520  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:36:19.520  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:36:20.590  3403  3863 E Watchdog: !@Sync 21 [04-01 10:36:20.596]
,04-01 10:36:25.740  3403  6140 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 18, LCD = 0
,04-01 10:36:29.610  3403  3851 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:36:29.610  3403  3851 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:36:29.610  3403  3851 D BatteryService: online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
,04-01 10:36:29.610  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,04-01 10:36:29.615  3403  3851 D BatteryService: stay LED for fully charged
04-01 10:36:29.620  3403  3403 I MotionRecognitionService: Plugged,
04-01 10:36:29.620  3403  3403 D MotionRecognitionService:   cableConnection= 1
04-01 10:36:29.620  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,04-01 10:36:29.620  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:36:29.630  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
04-01 10:36:29.630  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:36:29.630  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:36:29.650  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
04-01 10:36:29.650  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:36:29.660  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:36:29.660  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:36:29.660  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:36:29.660  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:36:35.765  3403  6140 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 17, LCD = 0
,04-01 10:36:39.745  3403  3649 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:36:39.745  3403  3649 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:36:39.745  3403  3649 D BatteryService: online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,04-01 10:36:39.750  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,04-01 10:36:39.755  3403  3403 I MotionRecognitionService: Plugged,
04-01 10:36:39.755  3403  3403 D MotionRecognitionService:   cableConnection= 1
,04-01 10:36:39.755  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
,04-01 10:36:39.755  3403  3403 D MotionRecognitionService: skip setTransmitPower. ,
04-01 10:36:39.760  3403  3649 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 12ms
,04-01 10:36:39.760  3403  3649 D BatteryService: stay LED for fully charged,
04-01 10:36:39.775  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
04-01 10:36:39.775  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,04-01 10:36:39.775  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate,
,04-01 10:36:39.795  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
04-01 10:36:39.795  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:36:39.805  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:36:39.805  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:36:39.805  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:36:39.805  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:36:44.005  3403  3583 I PowerManagerService: [PWL] Off : 600s ago
,04-01 10:36:45.795  3403  6140 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 18, LCD = 0
,04-01 10:36:49.890  3403  4396 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:36:49.890  3403  4396 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:36:49.890  3403  4396 D BatteryService: online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,04-01 10:36:49.890  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
04-01 10:36:49.890  3403  4396 D BatteryService: stay LED for fully charged
,04-01 10:36:49.900  3403  3403 I MotionRecognitionService: Plugged,
04-01 10:36:49.900  3403  3403 D MotionRecognitionService:   cableConnection= 1
,04-01 10:36:49.900  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
04-01 10:36:49.900  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:36:49.910  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,04-01 10:36:49.910  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,04-01 10:36:49.910  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:36:49.930  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
04-01 10:36:49.930  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:36:49.940  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:36:49.940  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:36:49.940  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:36:49.940  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:36:50.600  3403  3863 E Watchdog: !@Sync 22 [04-01 10:36:50.603]
,04-01 10:36:53.725  2891  4804 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,04-01 10:36:55.830  3403  6140 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 16, LCD = 0
,04-01 10:37:00.025  3403  3830 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:37:00.025  3403  3830 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:37:00.025  3403  3830 D BatteryService: online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,04-01 10:37:00.030  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
04-01 10:37:00.035  3403  3830 D BatteryService: stay LED for fully charged
,04-01 10:37:00.040  3403  3403 I MotionRecognitionService: Plugged,
04-01 10:37:00.040  3403  3403 D MotionRecognitionService:   cableConnection= 1,
04-01 10:37:00.040  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
,04-01 10:37:00.040  3403  3403 D MotionRecognitionService: skip setTransmitPower. ,
,04-01 10:37:00.050  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
04-01 10:37:00.050  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,04-01 10:37:00.050  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate,
,04-01 10:37:00.075  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
04-01 10:37:00.075  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:37:00.085  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:37:00.085  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:37:00.085  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:37:00.085  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:37:05.860  3403  6140 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 16, LCD = 0
,04-01 10:37:10.165  3403  3432 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:37:10.165  3403  3432 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:37:10.165  3403  3432 D BatteryService: online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
,04-01 10:37:10.170  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,04-01 10:37:10.175  3403  3432 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 10ms,
04-01 10:37:10.175  3403  3432 D BatteryService: stay LED for fully charged
,04-01 10:37:10.175  3403  3403 I MotionRecognitionService: Plugged
,04-01 10:37:10.175  3403  3403 D MotionRecognitionService:   cableConnection= 1,
,04-01 10:37:10.175  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
04-01 10:37:10.185  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
04-01 10:37:10.175  3403  3403 D MotionRecognitionService: skip setTransmitPower. ,
,04-01 10:37:10.190  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,04-01 10:37:10.190  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate,
,04-01 10:37:10.210  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
04-01 10:37:10.210  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:37:10.225  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:37:10.225  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:37:10.225  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:37:10.225  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:37:15.890  3403  6140 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 17, LCD = 0
,04-01 10:37:20.305  3403  3830 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:37:20.305  3403  3830 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:37:20.305  3403  3830 D BatteryService: online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
,04-01 10:37:20.305  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,04-01 10:37:20.315  3403  3830 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 10ms
04-01 10:37:20.315  3403  3830 D BatteryService: stay LED for fully charged
,04-01 10:37:20.320  3403  3403 I MotionRecognitionService: Plugged
,04-01 10:37:20.320  3403  3403 D MotionRecognitionService:   cableConnection= 1
,04-01 10:37:20.320  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
04-01 10:37:20.320  3403  3403 D MotionRecognitionService: skip setTransmitPower. ,
,04-01 10:37:20.330  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
04-01 10:37:20.330  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:37:20.330  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate,
,04-01 10:37:20.360  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
04-01 10:37:20.360  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:37:20.365  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:37:20.365  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:37:20.365  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:37:20.365  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:37:20.605  3403  3863 E Watchdog: !@Sync 23 [04-01 10:37:20.611]
,04-01 10:37:25.915  3403  6140 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 16, LCD = 0
,04-01 10:37:30.450  3403  3432 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:37:30.450  3403  3432 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:37:30.450  3403  3432 D BatteryService: online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
,04-01 10:37:30.455  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
04-01 10:37:30.460  3403  3432 D BatteryService: stay LED for fully charged
,04-01 10:37:30.465  3403  3403 I MotionRecognitionService: Plugged,
04-01 10:37:30.465  3403  3403 D MotionRecognitionService:   cableConnection= 1,
04-01 10:37:30.465  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,04-01 10:37:30.465  3403  3403 D MotionRecognitionService: skip setTransmitPower. ,
,04-01 10:37:30.475  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
04-01 10:37:30.475  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:37:30.475  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:37:30.490  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:37:30.495  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
04-01 10:37:30.495  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:37:30.510  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:37:30.510  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:37:30.510  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:37:35.945  3403  6140 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 16, LCD = 0
,04-01 10:37:40.590  3403  4028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:37:40.590  3403  4028 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:37:40.590  3403  4028 D BatteryService: online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-2
,04-01 10:37:40.590  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
04-01 10:37:40.595  3403  4028 D BatteryService: stay LED for fully charged
,04-01 10:37:40.600  3403  3403 I MotionRecognitionService: Plugged,
04-01 10:37:40.600  3403  3403 D MotionRecognitionService:   cableConnection= 1
04-01 10:37:40.600  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
,04-01 10:37:40.600  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:37:40.610  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
04-01 10:37:40.610  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:37:40.610  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate,
,04-01 10:37:40.620  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
04-01 10:37:40.620  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:37:40.635  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:37:40.635  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:37:40.635  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:37:40.635  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:37:45.980  3403  6140 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 16, LCD = 0
,04-01 10:37:50.615  3403  3863 E Watchdog: !@Sync 24 [04-01 10:37:50.620]
,04-01 10:37:50.725  3403  4396 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:37:50.725  3403  4396 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
,04-01 10:37:50.725  3403  4396 D BatteryService: online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,04-01 10:37:50.730  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
04-01 10:37:50.735  3403  4396 D BatteryService: stay LED for fully charged
,04-01 10:37:50.740  3403  3403 I MotionRecognitionService: Plugged
04-01 10:37:50.740  3403  3403 D MotionRecognitionService:   cableConnection= 1,
04-01 10:37:50.740  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
04-01 10:37:50.740  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:37:50.750  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
04-01 10:37:50.750  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:37:50.750  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:37:50.770  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,04-01 10:37:50.770  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:37:50.780  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:37:50.780  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:37:50.780  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:37:50.780  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:37:53.725  2891  4804 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,04-01 10:37:56.010  3403  6140 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 17, LCD = 0
,04-01 10:38:00.865  3403  3649 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,04-01 10:38:00.865  3403  3649 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:38:00.865  3403  3649 D BatteryService: online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,04-01 10:38:00.870  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,04-01 10:38:00.880  3403  3403 I MotionRecognitionService: Plugged
04-01 10:38:00.880  3403  3403 D MotionRecognitionService:   cableConnection= 1,
04-01 10:38:00.880  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
04-01 10:38:00.880  3403  3403 D MotionRecognitionService: skip setTransmitPower. ,
,04-01 10:38:00.880  3403  3649 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 13ms
04-01 10:38:00.880  3403  3649 D BatteryService: stay LED for fully charged
,04-01 10:38:00.890  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
04-01 10:38:00.890  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:38:00.890  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:38:00.915  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,04-01 10:38:00.915  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:38:00.925  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:38:00.925  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:38:00.925  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:38:00.925  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:38:04.005  3403  3583 I PowerManagerService: [PWL] Off : 680s ago
,04-01 10:38:06.040  3403  6140 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 15, LCD = 0
,04-01 10:38:11.005  3403  3432 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:38:11.005  3403  3432 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:38:11.005  3403  3432 D BatteryService: online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-3
,04-01 10:38:11.010  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
04-01 10:38:11.010  3403  3432 D BatteryService: stay LED for fully charged
,04-01 10:38:11.020  3403  3403 I MotionRecognitionService: Plugged,
04-01 10:38:11.020  3403  3403 D MotionRecognitionService:   cableConnection= 1
04-01 10:38:11.020  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
04-01 10:38:11.020  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:38:11.025  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
04-01 10:38:11.025  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:38:11.030  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:38:11.045  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,04-01 10:38:11.050  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:38:11.060  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:38:11.060  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:38:11.060  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:38:11.060  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:38:16.070  3403  6140 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 15, LCD = 0
,04-01 10:38:20.620  3403  3863 E Watchdog: !@Sync 25 [04-01 10:38:20.623]
,04-01 10:38:21.145  3403  4028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:38:21.145  3403  4028 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:38:21.145  3403  4028 D BatteryService: online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
,04-01 10:38:21.150  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
04-01 10:38:21.150  3403  4028 D BatteryService: stay LED for fully charged,
,04-01 10:38:21.160  3403  3403 I MotionRecognitionService: Plugged
04-01 10:38:21.160  3403  3403 D MotionRecognitionService:   cableConnection= 1,
04-01 10:38:21.160  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
04-01 10:38:21.160  3403  3403 D MotionRecognitionService: skip setTransmitPower. ,
,04-01 10:38:21.170  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
04-01 10:38:21.170  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:38:21.170  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:38:21.190  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,04-01 10:38:21.190  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:38:21.200  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:38:21.200  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:38:21.200  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:38:21.200  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:38:26.095  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 249 (W:30), CUR = 14, LCD = 0
,04-01 10:38:31.280  3403  3434 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:38:31.280  3403  3434 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:38:31.280  3403  3434 D BatteryService: online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:21
,04-01 10:38:31.280  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
04-01 10:38:31.285  3403  3434 D BatteryService: stay LED for fully charged
,04-01 10:38:31.290  3403  3403 I MotionRecognitionService: Plugged
,04-01 10:38:31.290  3403  3403 D MotionRecognitionService:   cableConnection= 1
04-01 10:38:31.290  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
04-01 10:38:31.290  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:38:31.300  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
04-01 10:38:31.300  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:38:31.300  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:38:31.320  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,04-01 10:38:31.320  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:38:31.335  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:38:31.335  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:38:31.335  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:38:31.335  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:38:36.125  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 249 (W:30), CUR = 15, LCD = 0
,04-01 10:38:41.420  3403  4003 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,04-01 10:38:41.420  3403  4003 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:38:41.420  3403  4003 D BatteryService: online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:4
,04-01 10:38:41.425  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,04-01 10:38:41.435  3403  3403 I MotionRecognitionService: Plugged
04-01 10:38:41.435  3403  3403 D MotionRecognitionService:   cableConnection= 1,
04-01 10:38:41.435  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,04-01 10:38:41.435  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:38:41.435  3403  4003 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 13ms,
,04-01 10:38:41.435  3403  4003 D BatteryService: stay LED for fully charged
04-01 10:38:41.445  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:38:41.445  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:38:41.445  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:38:41.470  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,04-01 10:38:41.470  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:38:41.480  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:38:41.480  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:38:41.480  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:38:41.480  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:38:46.155  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 249 (W:30), CUR = 15, LCD = 0
,04-01 10:38:50.625  3403  3863 E Watchdog: !@Sync 26 [04-01 10:38:50.630]
,04-01 10:38:51.565  3403  3432 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:38:51.565  3403  3432 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:38:51.565  3403  3432 D BatteryService: online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
,04-01 10:38:51.570  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,04-01 10:38:51.575  3403  3403 I MotionRecognitionService: Plugged
04-01 10:38:51.575  3403  3403 D MotionRecognitionService:   cableConnection= 1,
04-01 10:38:51.575  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
04-01 10:38:51.575  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:38:51.580  3403  3432 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 14ms,
04-01 10:38:51.580  3403  3432 D BatteryService: stay LED for fully charged
,04-01 10:38:51.590  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
04-01 10:38:51.590  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:38:51.590  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:38:51.605  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,04-01 10:38:51.610  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:38:51.620  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:38:51.620  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:38:51.620  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:38:51.620  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:38:53.685  3403  3616 V AlarmManager: waitForAlarm result :8
,04-01 10:38:53.725  2891  4804 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,04-01 10:38:56.185  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 248 (W:30), CUR = 14, LCD = 0
,04-01 10:39:01.705  3403  4028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:39:01.705  3403  4028 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:39:01.705  3403  4028 D BatteryService: online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:4
,04-01 10:39:01.710  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
04-01 10:39:01.710  3403  4028 D BatteryService: stay LED for fully charged,
,04-01 10:39:01.720  3403  3403 I MotionRecognitionService: Plugged
04-01 10:39:01.720  3403  3403 D MotionRecognitionService:   cableConnection= 1,
04-01 10:39:01.720  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
04-01 10:39:01.720  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:39:01.730  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
04-01 10:39:01.730  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:39:01.730  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:39:01.750  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,04-01 10:39:01.755  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:39:01.760  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:39:01.760  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:39:01.760  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:39:01.760  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:39:06.220  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 248 (W:30), CUR = 12, LCD = 0
,04-01 10:39:11.850  3403  3434 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:39:11.850  3403  3434 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:39:11.850  3403  3434 D BatteryService: online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:6
,04-01 10:39:11.850  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,04-01 10:39:11.855  3403  3434 D BatteryService: stay LED for fully charged
,04-01 10:39:11.865  3403  3403 I MotionRecognitionService: Plugged
04-01 10:39:11.865  3403  3403 D MotionRecognitionService:   cableConnection= 1
04-01 10:39:11.865  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
04-01 10:39:11.865  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:39:11.870  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:39:11.870  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:39:11.870  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:39:11.890  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,04-01 10:39:11.895  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:39:11.900  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:39:11.900  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:39:11.900  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:39:11.905  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:39:16.250  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 248 (W:30), CUR = 14, LCD = 0
,04-01 10:39:20.635  3403  3863 E Watchdog: !@Sync 27 [04-01 10:39:20.637]
,04-01 10:39:21.985  3403  4003 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:39:21.985  3403  4003 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:39:21.985  3403  4003 D BatteryService: online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
,04-01 10:39:21.990  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
04-01 10:39:21.990  3403  4003 D BatteryService: stay LED for fully charged
,04-01 10:39:22.000  3403  3403 I MotionRecognitionService: Plugged
04-01 10:39:22.000  3403  3403 D MotionRecognitionService:   cableConnection= 1
04-01 10:39:22.000  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
04-01 10:39:22.000  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:39:22.005  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:39:22.005  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:39:22.005  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:39:22.025  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,04-01 10:39:22.030  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:39:22.035  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:39:22.035  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:39:22.035  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:39:22.035  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:39:26.280  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 247 (W:30), CUR = 13, LCD = 0
,04-01 10:39:29.010  3403  3583 I PowerManagerService: [PWL] Off : 765s ago
,04-01 10:39:32.125  3403  4793 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:39:32.125  3403  4793 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:39:32.125  3403  4793 D BatteryService: online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:21
,04-01 10:39:32.130  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,04-01 10:39:32.135  3403  3403 I MotionRecognitionService: Plugged,
,04-01 10:39:32.140  3403  3403 D MotionRecognitionService:   cableConnection= 1
,04-01 10:39:32.140  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
,04-01 10:39:32.140  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:39:32.140  3403  4793 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 16ms
04-01 10:39:32.140  3403  4793 D BatteryService: stay LED for fully charged
,04-01 10:39:32.155  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
04-01 10:39:32.155  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:39:32.155  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:39:32.165  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
04-01 10:39:32.170  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:39:32.180  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:39:32.180  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:39:32.180  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:39:32.180  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:39:36.310  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 247 (W:30), CUR = 14, LCD = 0
,04-01 10:39:42.265  3403  3850 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:39:42.265  3403  3850 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:39:42.265  3403  3850 D BatteryService: online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
,04-01 10:39:42.270  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
04-01 10:39:42.270  3403  3850 D BatteryService: stay LED for fully charged
,04-01 10:39:42.280  3403  3403 I MotionRecognitionService: Plugged,
,04-01 10:39:42.280  3403  3403 D MotionRecognitionService:   cableConnection= 1
04-01 10:39:42.280  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,04-01 10:39:42.280  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:39:42.290  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:39:42.290  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:39:42.290  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:39:42.300  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
04-01 10:39:42.300  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:39:42.315  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:39:42.315  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:39:42.315  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:39:42.315  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:39:46.340  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 247 (W:30), CUR = 14, LCD = 0
,04-01 10:39:50.640  3403  3863 E Watchdog: !@Sync 28 [04-01 10:39:50.645]
,04-01 10:39:52.410  3403  4027 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,04-01 10:39:52.410  3403  4027 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:39:52.410  3403  4027 D BatteryService: online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
04-01 10:39:52.410  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,04-01 10:39:52.410  3403  4027 D BatteryService: stay LED for fully charged
,04-01 10:39:52.415  3403  3403 I MotionRecognitionService: Plugged
04-01 10:39:52.415  3403  3403 D MotionRecognitionService:   cableConnection= 1
04-01 10:39:52.415  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
,04-01 10:39:52.415  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:39:52.420  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:39:52.425  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:39:52.425  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:39:52.435  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
04-01 10:39:52.435  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:39:52.450  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:39:52.450  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:39:52.450  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:39:52.450  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:39:53.725  2891  4804 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,04-01 10:39:56.370  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 246 (W:30), CUR = 14, LCD = 0
,04-01 10:40:02.545  3403  4002 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,04-01 10:40:02.545  3403  4002 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:40:02.545  3403  4002 D BatteryService: online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
04-01 10:40:02.545  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
04-01 10:40:02.545  3403  4002 D BatteryService: stay LED for fully charged
,04-01 10:40:02.555  3403  3403 I MotionRecognitionService: Plugged,
,04-01 10:40:02.555  3403  3403 D MotionRecognitionService:   cableConnection= 1,
,04-01 10:40:02.555  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
,04-01 10:40:02.555  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:40:02.570  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,04-01 10:40:02.570  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,04-01 10:40:02.570  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate,
,04-01 10:40:02.595  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,04-01 10:40:02.595  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:40:02.605  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:40:02.605  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:40:02.605  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:40:02.605  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:40:06.400  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 246 (W:30), CUR = 13, LCD = 0
,04-01 10:40:12.685  3403  4786 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:40:12.685  3403  4786 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:40:12.685  3403  4786 D BatteryService: online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,04-01 10:40:12.685  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
04-01 10:40:12.685  3403  4786 D BatteryService: stay LED for fully charged
,04-01 10:40:12.695  3403  3403 I MotionRecognitionService: Plugged
04-01 10:40:12.695  3403  3403 D MotionRecognitionService:   cableConnection= 1
04-01 10:40:12.695  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
04-01 10:40:12.695  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:40:12.705  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
04-01 10:40:12.705  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:40:12.705  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:40:12.725  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,04-01 10:40:12.725  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:40:12.735  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:40:12.735  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:40:12.735  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:40:12.735  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:40:16.425  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 246 (W:30), CUR = 12, LCD = 0
,04-01 10:40:20.650  3403  3863 E Watchdog: !@Sync 29 [04-01 10:40:20.652]
,04-01 10:40:22.850  3403  4407 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:40:22.850  3403  4407 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:40:22.850  3403  4407 D BatteryService: online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
,04-01 10:40:22.855  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
04-01 10:40:22.855  3403  4407 D BatteryService: stay LED for fully charged
,04-01 10:40:22.865  3403  3403 I MotionRecognitionService: Plugged,
,04-01 10:40:22.865  3403  3403 D MotionRecognitionService:   cableConnection= 1
,04-01 10:40:22.865  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
,04-01 10:40:22.865  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:40:22.875  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:40:22.875  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:40:22.875  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:40:22.900  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
04-01 10:40:22.900  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:40:22.905  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:40:22.905  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:40:22.910  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:40:22.910  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:40:26.455  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 245 (W:30), CUR = 11, LCD = 0
,04-01 10:40:32.990  3403  4737 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:40:32.995  3403  4737 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:40:32.995  3403  4737 D BatteryService: online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
04-01 10:40:32.995  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
04-01 10:40:32.995  3403  4737 D BatteryService: stay LED for fully charged
,04-01 10:40:33.005  3403  3403 I MotionRecognitionService: Plugged,
04-01 10:40:33.005  3403  3403 D MotionRecognitionService:   cableConnection= 1
04-01 10:40:33.005  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
04-01 10:40:33.005  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:40:33.015  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:40:33.015  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:40:33.015  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:40:33.030  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:40:33.030  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
04-01 10:40:33.030  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:40:33.030  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:40:33.035  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:40:33.045  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:40:36.490  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 245 (W:30), CUR = 13, LCD = 0
,04-01 10:40:43.130  3403  4407 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:40:43.130  3403  4407 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:40:43.130  3403  4407 D BatteryService: online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
,04-01 10:40:43.135  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,04-01 10:40:43.145  3403  3403 I MotionRecognitionService: Plugged
04-01 10:40:43.145  3403  3403 D MotionRecognitionService:   cableConnection= 1,
04-01 10:40:43.145  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,04-01 10:40:43.145  3403  3403 D MotionRecognitionService: skip setTransmitPower. ,
,04-01 10:40:43.145  3403  4407 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 16ms
,04-01 10:40:43.145  3403  4407 D BatteryService: stay LED for fully charged,
04-01 10:40:43.160  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,04-01 10:40:43.160  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:40:43.160  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:40:43.175  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
04-01 10:40:43.175  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:40:43.190  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:40:43.190  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:40:43.190  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:40:43.190  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:40:46.515  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 245 (W:30), CUR = 12, LCD = 0
,04-01 10:40:48.095  3403  3605 D TimaService: TIMA: TimaService scheduler is intialized. 
04-01 10:40:48.095  3403  3605 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,04-01 10:40:48.100  3403  3604 D TimaService: TimaServiceHandler.handleMessage what =1,
,04-01 10:40:50.655  3403  3863 E Watchdog: !@Sync 30 [04-01 10:40:50.660]
,04-01 10:40:52.965  3403  3605 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
04-01 10:40:52.965  3403  3605 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,04-01 10:40:52.985  3403  3605 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
04-01 10:40:52.985  3403  3605 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,04-01 10:40:53.190  3403  3567 W ProcessCpuTracker: Skipping unknown process pid 12214
,04-01 10:40:53.255  3403  4737 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,04-01 10:40:53.255  3403  4737 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:40:53.255  3403  4737 D BatteryService: online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
04-01 10:40:53.255  3403  4737 D BatteryService: stay LED for fully charged
04-01 10:40:53.255  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,04-01 10:40:53.255  3403  3403 I MotionRecognitionService: Plugged
,04-01 10:40:53.255  3403  3403 D MotionRecognitionService:   cableConnection= 1
04-01 10:40:53.255  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
04-01 10:40:53.255  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:40:53.260  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
04-01 10:40:53.260  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:40:53.260  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:40:53.265  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:40:53.270  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,04-01 10:40:53.270  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:40:53.285  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:40:53.285  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:40:53.285  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:40:53.725  2891  4804 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,04-01 10:40:56.545  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 244 (W:30), CUR = 12, LCD = 0
,04-01 10:40:59.015  3403  3583 I PowerManagerService: [PWL] Off : 855s ago
,04-01 10:41:03.395  3403  3851 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:41:03.395  3403  3851 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:41:03.395  3403  3851 D BatteryService: online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,04-01 10:41:03.400  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
04-01 10:41:03.400  3403  3851 D BatteryService: stay LED for fully charged
,04-01 10:41:03.405  3403  3403 I MotionRecognitionService: Plugged,
,04-01 10:41:03.405  3403  3403 D MotionRecognitionService:   cableConnection= 1
04-01 10:41:03.405  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,04-01 10:41:03.405  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:41:03.420  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
04-01 10:41:03.425  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,04-01 10:41:03.425  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate,
,04-01 10:41:03.445  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
04-01 10:41:03.445  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:41:03.455  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:41:03.455  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:41:03.455  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:41:03.455  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:41:06.575  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 244 (W:30), CUR = 13, LCD = 0
,04-01 10:41:13.535  3403  3830 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,04-01 10:41:13.540  3403  3830 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:41:13.540  3403  3830 D BatteryService: online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
04-01 10:41:13.540  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
04-01 10:41:13.545  3403  3830 D BatteryService: stay LED for fully charged
,04-01 10:41:13.550  3403  3403 I MotionRecognitionService: Plugged,
04-01 10:41:13.550  3403  3403 D MotionRecognitionService:   cableConnection= 1,
04-01 10:41:13.550  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
,04-01 10:41:13.550  3403  3403 D MotionRecognitionService: skip setTransmitPower. ,
,04-01 10:41:13.560  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:41:13.560  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:41:13.560  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:41:13.575  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,04-01 10:41:13.580  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:41:13.590  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:41:13.590  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:41:13.590  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:41:13.590  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:41:16.605  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 244 (W:30), CUR = 12, LCD = 0
,04-01 10:41:20.670  3403  3863 E Watchdog: !@Sync 31 [04-01 10:41:20.672]
,04-01 10:41:23.675  3403  4396 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,04-01 10:41:23.680  3403  4396 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:41:23.680  3403  4396 D BatteryService: online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
,04-01 10:41:23.685  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,04-01 10:41:23.690  3403  3403 I MotionRecognitionService: Plugged
04-01 10:41:23.690  3403  3403 D MotionRecognitionService:   cableConnection= 1,
04-01 10:41:23.690  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
,04-01 10:41:23.690  3403  3403 D MotionRecognitionService: skip setTransmitPower. ,
04-01 10:41:23.695  3403  4396 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 19ms,
04-01 10:41:23.695  3403  4396 D BatteryService: stay LED for fully charged
,04-01 10:41:23.705  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
04-01 10:41:23.705  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:41:23.705  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate,
,04-01 10:41:23.715  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
04-01 10:41:23.715  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:41:23.730  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:41:23.730  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:41:23.730  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:41:23.730  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:41:26.635  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 243 (W:30), CUR = 12, LCD = 0
,04-01 10:41:33.815  3403  3649 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:41:33.815  3403  3649 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:41:33.815  3403  3649 D BatteryService: online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-7
,04-01 10:41:33.820  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,04-01 10:41:33.830  3403  3649 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 13ms
04-01 10:41:33.830  3403  3649 D BatteryService: stay LED for fully charged,
,04-01 10:41:33.835  3403  3403 I MotionRecognitionService: Plugged,
04-01 10:41:33.835  3403  3403 D MotionRecognitionService:   cableConnection= 1
,04-01 10:41:33.835  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
04-01 10:41:33.835  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:41:33.845  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:41:33.845  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:41:33.845  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:41:33.860  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
04-01 10:41:33.860  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:41:33.870  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:41:33.870  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:41:33.870  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:41:33.870  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:41:36.670  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 243 (W:30), CUR = 11, LCD = 0
,04-01 10:41:43.950  3403  3432 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:41:43.950  3403  3432 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:41:43.950  3403  3432 D BatteryService: online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:40
04-01 10:41:43.950  3403  3432 D BatteryService: stay LED for fully charged
,04-01 10:41:43.955  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,04-01 10:41:43.955  3403  3403 I MotionRecognitionService: Plugged
04-01 10:41:43.955  3403  3403 D MotionRecognitionService:   cableConnection= 1
04-01 10:41:43.960  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
04-01 10:41:43.960  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:41:43.965  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:41:43.965  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:41:43.965  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:41:43.970  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:41:43.970  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
04-01 10:41:43.970  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:41:43.985  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:41:43.985  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:41:43.985  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:41:46.695  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 243 (W:30), CUR = 12, LCD = 0
,04-01 10:41:50.675  3403  3863 E Watchdog: !@Sync 32 [04-01 10:41:50.680]
,04-01 10:41:53.725  2891  4804 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,04-01 10:41:54.095  3403  4028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:41:54.095  3403  4028 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:41:54.095  3403  4028 D BatteryService: online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,04-01 10:41:54.100  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
04-01 10:41:54.100  3403  4028 D BatteryService: stay LED for fully charged,
,04-01 10:41:54.110  3403  3403 I MotionRecognitionService: Plugged
04-01 10:41:54.110  3403  3403 D MotionRecognitionService:   cableConnection= 1
04-01 10:41:54.110  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
04-01 10:41:54.110  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:41:54.115  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:41:54.115  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:41:54.115  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:41:54.125  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,04-01 10:41:54.125  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:41:54.140  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:41:54.140  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:41:54.140  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:41:54.140  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:41:56.730  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 242 (W:30), CUR = 13, LCD = 0
,04-01 10:42:04.235  3403  3434 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:42:04.235  3403  3434 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:42:04.235  3403  3434 D BatteryService: online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
,04-01 10:42:04.235  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,04-01 10:42:04.245  3403  3403 I MotionRecognitionService: Plugged
04-01 10:42:04.245  3403  3403 D MotionRecognitionService:   cableConnection= 1,
,04-01 10:42:04.245  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
04-01 10:42:04.245  3403  3403 D MotionRecognitionService: skip setTransmitPower. ,
,04-01 10:42:04.250  3403  3434 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 15ms,
04-01 10:42:04.250  3403  3434 D BatteryService: stay LED for fully charged
,04-01 10:42:04.260  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,04-01 10:42:04.260  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,04-01 10:42:04.260  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate,
,04-01 10:42:04.280  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
04-01 10:42:04.280  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:42:04.290  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:42:04.290  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:42:04.290  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:42:04.290  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:42:06.760  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 242 (W:30), CUR = 12, LCD = 0
,04-01 10:42:14.370  3403  4003 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,04-01 10:42:14.375  3403  4003 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:42:14.375  3403  4003 D BatteryService: online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:4
04-01 10:42:14.375  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
04-01 10:42:14.380  3403  4003 D BatteryService: stay LED for fully charged
,04-01 10:42:14.385  3403  3403 I MotionRecognitionService: Plugged,
,04-01 10:42:14.385  3403  3403 D MotionRecognitionService:   cableConnection= 1
04-01 10:42:14.385  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
,04-01 10:42:14.385  3403  3403 D MotionRecognitionService: skip setTransmitPower. ,
,04-01 10:42:14.395  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
04-01 10:42:14.395  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
04-01 10:42:14.395  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate,
,04-01 10:42:14.420  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
04-01 10:42:14.420  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:42:14.430  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:42:14.430  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:42:14.430  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:42:14.430  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:42:16.785  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 242 (W:30), CUR = 11, LCD = 0
,04-01 10:42:20.685  3403  3863 E Watchdog: !@Sync 33 [04-01 10:42:20.688]
,04-01 10:42:24.515  3403  3434 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:42:24.515  3403  3434 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:42:24.515  3403  3434 D BatteryService: online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-1
,04-01 10:42:24.515  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,04-01 10:42:24.525  3403  3403 I MotionRecognitionService: Plugged
04-01 10:42:24.525  3403  3403 D MotionRecognitionService:   cableConnection= 1
04-01 10:42:24.525  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
04-01 10:42:24.525  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:42:24.525  3403  3434 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 13ms,
04-01 10:42:24.525  3403  3434 D BatteryService: stay LED for fully charged
,04-01 10:42:24.535  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
04-01 10:42:24.535  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:42:24.535  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:42:24.550  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
04-01 10:42:24.550  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:42:24.565  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:42:24.565  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:42:24.565  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:42:24.565  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:42:26.810  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 241 (W:30), CUR = 11, LCD = 0
,04-01 10:42:34.020  3403  3583 I PowerManagerService: [PWL] Off : 950s ago
,04-01 10:42:34.655  3403  4003 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:42:34.655  3403  4003 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:42:34.655  3403  4003 D BatteryService: online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
,04-01 10:42:34.655  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
04-01 10:42:34.660  3403  4003 D BatteryService: stay LED for fully charged
,04-01 10:42:34.665  3403  3403 I MotionRecognitionService: Plugged,
04-01 10:42:34.665  3403  3403 D MotionRecognitionService:   cableConnection= 1
,04-01 10:42:34.665  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
04-01 10:42:34.665  3403  3403 D MotionRecognitionService: skip setTransmitPower. ,
,04-01 10:42:34.675  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:42:34.675  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:42:34.675  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:42:34.695  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
04-01 10:42:34.695  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:42:34.710  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:42:34.710  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:42:34.710  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:42:34.710  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:42:36.840  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 241 (W:30), CUR = 11, LCD = 0
,04-01 10:42:44.795  3403  4793 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:42:44.795  3403  4793 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:42:44.795  3403  4793 D BatteryService: online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
,04-01 10:42:44.795  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
04-01 10:42:44.800  3403  4793 D BatteryService: stay LED for fully charged
,04-01 10:42:44.805  3403  3403 I MotionRecognitionService: Plugged
,04-01 10:42:44.805  3403  3403 D MotionRecognitionService:   cableConnection= 1
04-01 10:42:44.805  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
04-01 10:42:44.805  3403  3403 D MotionRecognitionService: skip setTransmitPower. ,
,04-01 10:42:44.815  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,04-01 10:42:44.815  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:42:44.815  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:42:44.840  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,04-01 10:42:44.840  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:42:44.850  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:42:44.850  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:42:44.850  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:42:44.850  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:42:46.865  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 241 (W:30), CUR = 10, LCD = 0
,04-01 10:42:50.690  3403  3863 E Watchdog: !@Sync 34 [04-01 10:42:50.695]
,04-01 10:42:53.725  2891  4804 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,04-01 10:42:54.935  3403  3850 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:42:54.935  3403  3850 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:42:54.935  3403  3850 D BatteryService: online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
,04-01 10:42:54.935  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,04-01 10:42:54.945  3403  3403 I MotionRecognitionService: Plugged
04-01 10:42:54.945  3403  3403 D MotionRecognitionService:   cableConnection= 1
04-01 10:42:54.945  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
04-01 10:42:54.945  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:42:54.945  3403  3850 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 12ms,
04-01 10:42:54.945  3403  3850 D BatteryService: stay LED for fully charged
,04-01 10:42:54.955  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
04-01 10:42:54.955  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:42:54.955  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:42:54.970  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
04-01 10:42:54.970  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:42:54.985  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:42:54.985  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:42:54.985  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:42:54.985  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:42:56.890  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 240 (W:30), CUR = 11, LCD = 0
,04-01 10:43:05.075  3403  4027 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:43:05.075  3403  4027 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:43:05.075  3403  4027 D BatteryService: online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:3
,04-01 10:43:05.075  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
04-01 10:43:05.075  3403  4027 D BatteryService: stay LED for fully charged
,04-01 10:43:05.085  3403  3403 I MotionRecognitionService: Plugged,
04-01 10:43:05.085  3403  3403 D MotionRecognitionService:   cableConnection= 1
,04-01 10:43:05.085  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
04-01 10:43:05.085  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:43:05.095  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
04-01 10:43:05.100  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:43:05.100  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:43:05.115  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,04-01 10:43:05.115  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:43:05.130  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:43:05.130  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:43:05.130  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:43:05.130  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:43:06.920  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 240 (W:30), CUR = 11, LCD = 0
,04-01 10:43:15.210  3403  4002 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:43:15.210  3403  4002 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:43:15.210  3403  4002 D BatteryService: online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
,04-01 10:43:15.210  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
04-01 10:43:15.210  3403  4002 D BatteryService: stay LED for fully charged
,04-01 10:43:15.220  3403  3403 I MotionRecognitionService: Plugged
04-01 10:43:15.220  3403  3403 D MotionRecognitionService:   cableConnection= 1,
04-01 10:43:15.220  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
04-01 10:43:15.220  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:43:15.230  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
04-01 10:43:15.230  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:43:15.230  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:43:15.245  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
04-01 10:43:15.250  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:43:15.260  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:43:15.260  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:43:15.260  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:43:15.260  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:43:16.950  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 240 (W:30), CUR = 10, LCD = 0
,04-01 10:43:20.700  3403  3863 E Watchdog: !@Sync 35 [04-01 10:43:20.703]
,04-01 10:43:25.350  3403  4786 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:43:25.350  3403  4786 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:43:25.350  3403  4786 D BatteryService: online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
04-01 10:43:25.350  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
04-01 10:43:25.355  3403  4786 D BatteryService: stay LED for fully charged
,04-01 10:43:25.360  3403  3403 I MotionRecognitionService: Plugged
04-01 10:43:25.360  3403  3403 D MotionRecognitionService:   cableConnection= 1
04-01 10:43:25.360  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
04-01 10:43:25.360  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:43:25.370  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
04-01 10:43:25.370  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:43:25.370  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:43:25.385  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
04-01 10:43:25.385  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:43:25.400  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:43:25.400  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:43:25.400  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:43:25.400  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:43:26.975  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 240 (W:30), CUR = 11, LCD = 0
,04-01 10:43:35.485  3403  4407 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:43:35.490  3403  4407 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:43:35.490  3403  4407 D BatteryService: online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-1
,04-01 10:43:35.490  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,04-01 10:43:35.500  3403  3403 I MotionRecognitionService: Plugged
04-01 10:43:35.500  3403  3403 D MotionRecognitionService:   cableConnection= 1
04-01 10:43:35.500  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
04-01 10:43:35.500  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:43:35.500  3403  4407 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 14ms,
04-01 10:43:35.500  3403  4407 D BatteryService: stay LED for fully charged
,04-01 10:43:35.510  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:43:35.510  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:43:35.510  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:43:35.520  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
04-01 10:43:35.520  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:43:35.535  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:43:35.535  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:43:35.535  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:43:35.535  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:43:37.020  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 240 (W:30), CUR = 12, LCD = 0
,04-01 10:43:45.625  3403  4737 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:43:45.625  3403  4737 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:43:45.625  3403  4737 D BatteryService: online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:2
,04-01 10:43:45.630  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
04-01 10:43:45.630  3403  4737 D BatteryService: stay LED for fully charged
,04-01 10:43:45.635  3403  3403 I MotionRecognitionService: Plugged
04-01 10:43:45.635  3403  3403 D MotionRecognitionService:   cableConnection= 1,
04-01 10:43:45.635  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
04-01 10:43:45.635  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:43:45.645  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
04-01 10:43:45.650  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:43:45.650  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:43:45.670  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,04-01 10:43:45.670  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:43:45.680  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:43:45.680  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:43:45.680  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:43:45.680  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:43:47.045  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 240 (W:30), CUR = 11, LCD = 0
,04-01 10:43:50.705  3403  3863 E Watchdog: !@Sync 36 [04-01 10:43:50.711]
,04-01 10:43:53.725  2891  4804 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,04-01 10:43:55.765  3403  3851 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:43:55.765  3403  3851 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:43:55.765  3403  3851 D BatteryService: online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
,04-01 10:43:55.765  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,04-01 10:43:55.775  3403  3403 I MotionRecognitionService: Plugged
04-01 10:43:55.775  3403  3403 D MotionRecognitionService:   cableConnection= 1
04-01 10:43:55.775  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
04-01 10:43:55.775  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:43:55.780  3403  3851 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 13ms,
04-01 10:43:55.780  3403  3851 D BatteryService: stay LED for fully charged
,04-01 10:43:55.785  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
04-01 10:43:55.785  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:43:55.785  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:43:55.810  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,04-01 10:43:55.810  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:43:55.815  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:43:55.820  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:43:55.820  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:43:55.820  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:43:57.075  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 240 (W:30), CUR = 11, LCD = 0
,04-01 10:44:05.900  3403  3830 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:44:05.900  3403  3830 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:44:05.900  3403  3830 D BatteryService: online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
,04-01 10:44:05.905  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,04-01 10:44:05.910  3403  3403 I MotionRecognitionService: Plugged
04-01 10:44:05.910  3403  3403 D MotionRecognitionService:   cableConnection= 1,
04-01 10:44:05.910  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
04-01 10:44:05.910  3403  3403 D MotionRecognitionService: skip setTransmitPower. ,
,04-01 10:44:05.915  3403  3830 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 14ms
,04-01 10:44:05.915  3403  3830 D BatteryService: stay LED for fully charged
,04-01 10:44:05.925  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
04-01 10:44:05.925  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:44:05.925  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:44:05.945  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
04-01 10:44:05.945  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:44:05.960  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:44:05.960  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:44:05.960  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:44:05.960  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:44:07.105  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 240 (W:30), CUR = 11, LCD = 0
,04-01 10:44:14.020  3403  3583 I PowerManagerService: [PWL] Off : 1050s ago
,04-01 10:44:16.040  3403  4396 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,04-01 10:44:16.040  3403  4396 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:44:16.040  3403  4396 D BatteryService: online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
04-01 10:44:16.040  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
04-01 10:44:16.045  3403  4396 D BatteryService: stay LED for fully charged
,04-01 10:44:16.050  3403  3403 I MotionRecognitionService: Plugged
04-01 10:44:16.050  3403  3403 D MotionRecognitionService:   cableConnection= 1
04-01 10:44:16.050  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
04-01 10:44:16.050  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:44:16.060  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
04-01 10:44:16.060  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:44:16.060  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:44:16.075  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
04-01 10:44:16.075  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:44:16.090  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:44:16.090  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:44:16.090  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:44:16.090  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:44:17.135  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 240 (W:30), CUR = 11, LCD = 0
,04-01 10:44:20.715  3403  3863 E Watchdog: !@Sync 37 [04-01 10:44:20.719]
,04-01 10:44:26.175  3403  3649 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:44:26.175  3403  3649 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:44:26.175  3403  3649 D BatteryService: online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
,04-01 10:44:26.180  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,04-01 10:44:26.185  3403  3403 I MotionRecognitionService: Plugged,
04-01 10:44:26.185  3403  3403 D MotionRecognitionService:   cableConnection= 1
04-01 10:44:26.185  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
,04-01 10:44:26.185  3403  3403 D MotionRecognitionService: skip setTransmitPower. ,
04-01 10:44:26.190  3403  3649 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 14ms,
,04-01 10:44:26.190  3403  3649 D BatteryService: stay LED for fully charged,
,04-01 10:44:26.200  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:44:26.200  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,04-01 10:44:26.200  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate,
,04-01 10:44:26.225  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
04-01 10:44:26.225  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:44:26.235  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:44:26.235  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:44:26.235  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:44:26.235  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:44:27.160  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 240 (W:30), CUR = 9, LCD = 0
,04-01 10:44:36.315  3403  3432 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:44:36.315  3403  3432 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:44:36.315  3403  3432 D BatteryService: online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
,04-01 10:44:36.320  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
04-01 10:44:36.320  3403  3432 D BatteryService: stay LED for fully charged
,04-01 10:44:36.330  3403  3403 I MotionRecognitionService: Plugged,
04-01 10:44:36.330  3403  3403 D MotionRecognitionService:   cableConnection= 1
04-01 10:44:36.330  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,04-01 10:44:36.330  3403  3403 D MotionRecognitionService: skip setTransmitPower. ,
,04-01 10:44:36.340  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
04-01 10:44:36.340  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:44:36.340  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate,
,04-01 10:44:36.360  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,04-01 10:44:36.365  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:44:36.370  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:44:36.375  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:44:36.375  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:44:36.375  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:44:37.190  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 240 (W:30), CUR = 9, LCD = 0
,04-01 10:44:46.455  3403  4028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:44:46.455  3403  4028 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:44:46.455  3403  4028 D BatteryService: online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,04-01 10:44:46.455  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,04-01 10:44:46.465  3403  3403 I MotionRecognitionService: Plugged
04-01 10:44:46.465  3403  3403 D MotionRecognitionService:   cableConnection= 1,
04-01 10:44:46.465  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
04-01 10:44:46.465  3403  3403 D MotionRecognitionService: skip setTransmitPower. ,
,04-01 10:44:46.470  3403  4028 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 16ms
04-01 10:44:46.470  3403  4028 D BatteryService: stay LED for fully charged
,04-01 10:44:46.480  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
04-01 10:44:46.480  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:44:46.480  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:44:46.500  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
04-01 10:44:46.500  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:44:46.510  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:44:46.510  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:44:46.510  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:44:46.510  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:44:47.215  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 240 (W:30), CUR = 10, LCD = 0
,04-01 10:44:50.720  3403  3863 E Watchdog: !@Sync 38 [04-01 10:44:50.726]
,04-01 10:44:53.725  2891  4804 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,04-01 10:44:56.585  3403  3434 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,04-01 10:44:56.590  3403  3434 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:44:56.590  3403  3434 D BatteryService: online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
04-01 10:44:56.590  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,04-01 10:44:56.600  3403  3403 I MotionRecognitionService: Plugged,
04-01 10:44:56.600  3403  3403 D MotionRecognitionService:   cableConnection= 1
04-01 10:44:56.600  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
04-01 10:44:56.600  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
04-01 10:44:56.600  3403  3434 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 16ms
,04-01 10:44:56.600  3403  3434 D BatteryService: stay LED for fully charged,
,04-01 10:44:56.610  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:44:56.615  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:44:56.615  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:44:56.630  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
04-01 10:44:56.630  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:44:56.640  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:44:56.640  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:44:56.640  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:44:56.640  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:44:57.245  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 240 (W:30), CUR = 9, LCD = 0
,04-01 10:45:06.725  3403  4003 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:45:06.725  3403  4003 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:45:06.725  3403  4003 D BatteryService: online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
,04-01 10:45:06.730  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
04-01 10:45:06.730  3403  4003 D BatteryService: stay LED for fully charged
,04-01 10:45:06.735  3403  3403 I MotionRecognitionService: Plugged,
04-01 10:45:06.735  3403  3403 D MotionRecognitionService:   cableConnection= 1
,04-01 10:45:06.735  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,04-01 10:45:06.735  3403  3403 D MotionRecognitionService: skip setTransmitPower. ,
,04-01 10:45:06.750  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
04-01 10:45:06.750  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,04-01 10:45:06.750  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate,
,04-01 10:45:06.765  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
04-01 10:45:06.765  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:45:06.780  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:45:06.780  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:45:06.780  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:45:06.780  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:45:07.270  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 240 (W:30), CUR = 10, LCD = 0
,04-01 10:45:16.865  3403  4793 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:45:16.865  3403  4793 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:45:16.865  3403  4793 D BatteryService: online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:2
,04-01 10:45:16.865  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
04-01 10:45:16.870  3403  4793 D BatteryService: stay LED for fully charged
,04-01 10:45:16.880  3403  3403 I MotionRecognitionService: Plugged
04-01 10:45:16.880  3403  3403 D MotionRecognitionService:   cableConnection= 1
04-01 10:45:16.880  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
04-01 10:45:16.880  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:45:16.890  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,04-01 10:45:16.890  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:45:16.890  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate,
,04-01 10:45:16.900  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,04-01 10:45:16.900  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:45:16.910  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:45:16.910  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:45:16.915  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:45:16.915  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:45:17.300  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 240 (W:30), CUR = 9, LCD = 0
,04-01 10:45:20.735  3403  3863 E Watchdog: !@Sync 39 [04-01 10:45:20.733]
,04-01 10:45:27.005  3403  4028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:45:27.005  3403  4028 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:45:27.005  3403  4028 D BatteryService: online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:6
,04-01 10:45:27.005  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
04-01 10:45:27.005  3403  4028 D BatteryService: stay LED for fully charged
,04-01 10:45:27.015  3403  3403 I MotionRecognitionService: Plugged,
,04-01 10:45:27.015  3403  3403 D MotionRecognitionService:   cableConnection= 1
,04-01 10:45:27.015  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
04-01 10:45:27.015  3403  3403 D MotionRecognitionService: skip setTransmitPower. ,
,04-01 10:45:27.025  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:45:27.025  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:45:27.025  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:45:27.040  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,04-01 10:45:27.040  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:45:27.050  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:45:27.050  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:45:27.050  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:45:27.055  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:45:27.335  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 240 (W:30), CUR = 9, LCD = 0
,04-01 10:45:37.140  3403  3434 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:45:37.145  3403  3434 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:45:37.145  3403  3434 D BatteryService: online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:2
,04-01 10:45:37.145  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,04-01 10:45:37.155  3403  3403 I MotionRecognitionService: Plugged
04-01 10:45:37.155  3403  3403 D MotionRecognitionService:   cableConnection= 1,
04-01 10:45:37.155  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,04-01 10:45:37.155  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:45:37.160  3403  3434 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 18ms,
04-01 10:45:37.160  3403  3434 D BatteryService: stay LED for fully charged,
,04-01 10:45:37.165  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,04-01 10:45:37.165  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:45:37.165  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate,
,04-01 10:45:37.180  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
04-01 10:45:37.180  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:45:37.195  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:45:37.195  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:45:37.195  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
04-01 10:45:37.195  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:45:37.360  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 240 (W:30), CUR = 9, LCD = 0
,04-01 10:45:47.280  3403  4737 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:45:47.280  3403  4737 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:45:47.280  3403  4737 D BatteryService: online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
,04-01 10:45:47.285  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,04-01 10:45:47.290  3403  3403 I MotionRecognitionService: Plugged
04-01 10:45:47.290  3403  3403 D MotionRecognitionService:   cableConnection= 1
,04-01 10:45:47.290  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,04-01 10:45:47.290  3403  3403 D MotionRecognitionService: skip setTransmitPower. ,
04-01 10:45:47.295  3403  4737 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 13ms,
04-01 10:45:47.295  3403  4737 D BatteryService: stay LED for fully charged
,04-01 10:45:47.305  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
04-01 10:45:47.305  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:45:47.305  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:45:47.325  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
04-01 10:45:47.325  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:45:47.335  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:45:47.335  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:45:47.335  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:45:47.335  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:45:47.370  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 240 (W:30), CUR = 9, LCD = 0
,04-01 10:45:48.095  3403  3605 D TimaService: TIMA: TimaService scheduler is intialized. 
04-01 10:45:48.095  3403  3605 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,04-01 10:45:48.100  3403  3604 D TimaService: TimaServiceHandler.handleMessage what =1
,04-01 10:45:48.740  3403  3566 I UsageStatsService: User[0] Flushing usage stats to disk
,04-01 10:45:50.635  3403  3605 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
04-01 10:45:50.635  3403  3605 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,04-01 10:45:50.655  3403  3605 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;,
,04-01 10:45:50.660  3403  3605 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,04-01 10:45:50.740  3403  3863 E Watchdog: !@Sync 40 [04-01 10:45:50.745]
,04-01 10:45:53.725  2891  4804 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,04-01 10:45:57.390  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 240 (W:30), CUR = 10, LCD = 0
,04-01 10:45:57.420  3403  3851 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:45:57.420  3403  3851 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:45:57.420  3403  3851 D BatteryService: online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
04-01 10:45:57.420  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
04-01 10:45:57.420  3403  3851 D BatteryService: stay LED for fully charged
,04-01 10:45:57.425  3403  3403 I MotionRecognitionService: Plugged
04-01 10:45:57.425  3403  3403 D MotionRecognitionService:   cableConnection= 1
04-01 10:45:57.425  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
04-01 10:45:57.425  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:45:57.430  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:45:57.430  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:45:57.430  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:45:57.445  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,04-01 10:45:57.445  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:45:57.455  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:45:57.455  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:45:57.455  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:45:57.455  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:45:59.020  3403  3583 I PowerManagerService: [PWL] Off : 1155s ago
,04-01 10:46:07.430  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 240 (W:30), CUR = 10, LCD = 0
,04-01 10:46:07.535  3403  3830 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,04-01 10:46:07.535  3403  3830 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:46:07.535  3403  3830 D BatteryService: online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
04-01 10:46:07.535  3403  3830 D BatteryService: stay LED for fully charged
04-01 10:46:07.540  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,04-01 10:46:07.540  3403  3403 I MotionRecognitionService: Plugged
04-01 10:46:07.540  3403  3403 D MotionRecognitionService:   cableConnection= 1
04-01 10:46:07.540  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
04-01 10:46:07.540  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:46:07.545  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:46:07.545  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:46:07.545  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:46:07.550  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,04-01 10:46:07.550  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:46:07.565  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:46:07.565  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:46:07.570  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:46:07.570  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:46:17.455  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 240 (W:30), CUR = 10, LCD = 0
,04-01 10:46:17.680  3403  4396 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:46:17.680  3403  4396 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:46:17.680  3403  4396 D BatteryService: online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:7
,04-01 10:46:17.685  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,04-01 10:46:17.690  3403  3403 I MotionRecognitionService: Plugged
04-01 10:46:17.690  3403  3403 D MotionRecognitionService:   cableConnection= 1
04-01 10:46:17.690  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
04-01 10:46:17.690  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
04-01 10:46:17.690  3403  4396 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 11ms
04-01 10:46:17.690  3403  4396 D BatteryService: stay LED for fully charged
,04-01 10:46:17.700  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
04-01 10:46:17.700  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:46:17.700  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:46:17.720  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
04-01 10:46:17.720  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:46:17.735  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:46:17.735  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:46:17.735  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:46:17.735  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:46:20.750  3403  3863 E Watchdog: !@Sync 41 [04-01 10:46:20.752]
,04-01 10:46:27.485  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 240 (W:30), CUR = 9, LCD = 0
,04-01 10:46:27.820  3403  3649 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:46:27.820  3403  3649 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:46:27.820  3403  3649 D BatteryService: online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
,04-01 10:46:27.825  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
04-01 10:46:27.825  3403  3649 D BatteryService: stay LED for fully charged
,04-01 10:46:27.835  3403  3403 I MotionRecognitionService: Plugged
,04-01 10:46:27.835  3403  3403 D MotionRecognitionService:   cableConnection= 1
04-01 10:46:27.835  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,04-01 10:46:27.835  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:46:27.845  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:46:27.845  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:46:27.845  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:46:27.855  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
04-01 10:46:27.855  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:46:27.870  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:46:27.870  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:46:27.870  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:46:27.870  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:46:37.510  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 240 (W:30), CUR = 9, LCD = 0
,04-01 10:46:37.955  3403  3432 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:46:37.955  3403  3432 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:46:37.955  3403  3432 D BatteryService: online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,04-01 10:46:37.960  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
04-01 10:46:37.960  3403  3432 D BatteryService: stay LED for fully charged
,04-01 10:46:37.970  3403  3403 I MotionRecognitionService: Plugged,
04-01 10:46:37.970  3403  3403 D MotionRecognitionService:   cableConnection= 1
04-01 10:46:37.970  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
04-01 10:46:37.970  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:46:37.975  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:46:37.975  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:46:37.975  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:46:37.985  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
04-01 10:46:37.985  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:46:38.000  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:46:38.000  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:46:38.000  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:46:38.000  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:46:47.540  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 240 (W:30), CUR = 10, LCD = 0,
,04-01 10:46:48.095  3403  4028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:46:48.095  3403  4028 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:46:48.095  3403  4028 D BatteryService: online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
,04-01 10:46:48.100  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,04-01 10:46:48.100  3403  4028 D BatteryService: stay LED for fully charged
,04-01 10:46:48.110  3403  3403 I MotionRecognitionService: Plugged,
,04-01 10:46:48.110  3403  3403 D MotionRecognitionService:   cableConnection= 1
,04-01 10:46:48.110  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
04-01 10:46:48.110  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:46:48.120  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,04-01 10:46:48.120  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:46:48.120  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:46:48.135  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,04-01 10:46:48.135  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:46:48.145  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:46:48.150  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:46:48.150  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:46:48.150  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:46:50.755  3403  3863 E Watchdog: !@Sync 42 [04-01 10:46:50.759]
,04-01 10:46:53.725  2891  4804 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,04-01 10:46:57.570  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 240 (W:30), CUR = 9, LCD = 0
,04-01 10:46:58.230  3403  3434 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:46:58.230  3403  3434 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:46:58.230  3403  3434 D BatteryService: online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-5
,04-01 10:46:58.235  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,04-01 10:46:58.245  3403  3403 I MotionRecognitionService: Plugged
04-01 10:46:58.245  3403  3403 D MotionRecognitionService:   cableConnection= 1,
,04-01 10:46:58.245  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
04-01 10:46:58.245  3403  3403 D MotionRecognitionService: skip setTransmitPower. ,
04-01 10:46:58.250  3403  3434 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 17ms,
,04-01 10:46:58.250  3403  3434 D BatteryService: stay LED for fully charged
,04-01 10:46:58.260  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:46:58.260  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,04-01 10:46:58.260  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:46:58.280  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
04-01 10:46:58.280  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:46:58.290  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:46:58.290  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:46:58.290  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:46:58.290  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:47:07.600  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 240 (W:30), CUR = 9, LCD = 0
,04-01 10:47:08.370  3403  4003 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:47:08.370  3403  4003 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:47:08.370  3403  4003 D BatteryService: online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
,04-01 10:47:08.370  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
04-01 10:47:08.375  3403  4003 D BatteryService: stay LED for fully charged
,04-01 10:47:08.380  3403  3403 I MotionRecognitionService: Plugged,
04-01 10:47:08.380  3403  3403 D MotionRecognitionService:   cableConnection= 1,
04-01 10:47:08.380  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
04-01 10:47:08.380  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:47:08.390  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
04-01 10:47:08.390  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:47:08.390  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate,
,04-01 10:47:08.410  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
04-01 10:47:08.410  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:47:08.420  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:47:08.420  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:47:08.420  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:47:08.420  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:47:17.625  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 240 (W:30), CUR = 10, LCD = 0
,04-01 10:47:18.510  3403  3434 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:47:18.510  3403  3434 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:47:18.510  3403  3434 D BatteryService: online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
,04-01 10:47:18.515  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,04-01 10:47:18.520  3403  3434 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 10ms
04-01 10:47:18.520  3403  3434 D BatteryService: stay LED for fully charged,
04-01 10:47:18.525  3403  3403 I MotionRecognitionService: Plugged,
04-01 10:47:18.525  3403  3403 D MotionRecognitionService:   cableConnection= 1,
04-01 10:47:18.525  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
04-01 10:47:18.525  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:47:18.535  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
04-01 10:47:18.535  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:47:18.535  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:47:18.555  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
04-01 10:47:18.555  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:47:18.565  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:47:18.565  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:47:18.565  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:47:18.565  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:47:20.760  3403  3863 E Watchdog: !@Sync 43 [04-01 10:47:20.766]
,04-01 10:47:27.650  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 240 (W:30), CUR = 11, LCD = 0
,04-01 10:47:28.650  3403  4003 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:47:28.650  3403  4003 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:47:28.650  3403  4003 D BatteryService: online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
,04-01 10:47:28.650  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,04-01 10:47:28.660  3403  4003 D BatteryService: stay LED for fully charged
,04-01 10:47:28.660  3403  3403 I MotionRecognitionService: Plugged
04-01 10:47:28.660  3403  3403 D MotionRecognitionService:   cableConnection= 1,
04-01 10:47:28.660  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
04-01 10:47:28.660  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:47:28.670  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
04-01 10:47:28.675  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:47:28.675  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:47:28.695  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
04-01 10:47:28.695  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:47:28.705  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:47:28.705  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:47:28.705  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:47:28.705  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:47:37.680  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 240 (W:30), CUR = 9, LCD = 0
,04-01 10:47:38.785  3403  4793 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:47:38.785  3403  4793 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:47:38.785  3403  4793 D BatteryService: online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:2
,04-01 10:47:38.785  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,04-01 10:47:38.795  3403  4793 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 10ms
04-01 10:47:38.795  3403  4793 D BatteryService: stay LED for fully charged,
04-01 10:47:38.795  3403  3403 I MotionRecognitionService: Plugged,
04-01 10:47:38.795  3403  3403 D MotionRecognitionService:   cableConnection= 1,
04-01 10:47:38.795  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
04-01 10:47:38.795  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:47:38.810  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
04-01 10:47:38.810  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:47:38.810  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:47:38.830  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,04-01 10:47:38.830  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:47:38.840  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:47:38.840  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:47:38.840  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:47:38.840  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:47:47.715  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 240 (W:30), CUR = 10, LCD = 0
,04-01 10:47:48.925  3403  4003 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:47:48.925  3403  4003 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:47:48.925  3403  4003 D BatteryService: online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-6
,04-01 10:47:48.925  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
04-01 10:47:48.925  3403  4003 D BatteryService: stay LED for fully charged
,04-01 10:47:48.935  3403  3403 I MotionRecognitionService: Plugged
04-01 10:47:48.935  3403  3403 D MotionRecognitionService:   cableConnection= 1,
04-01 10:47:48.935  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
04-01 10:47:48.935  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:47:48.945  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
04-01 10:47:48.945  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:47:48.945  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:47:48.965  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,04-01 10:47:48.965  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:47:48.975  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:47:48.975  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:47:48.975  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:47:48.975  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:47:49.020  3403  3583 I PowerManagerService: [PWL] Off : 1265s ago
,04-01 10:47:50.770  3403  3863 E Watchdog: !@Sync 44 [04-01 10:47:50.774]
,04-01 10:47:53.725  2891  4804 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,04-01 10:47:57.745  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 240 (W:30), CUR = 8, LCD = 0
,04-01 10:47:59.065  3403  4793 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:47:59.065  3403  4793 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:47:59.065  3403  4793 D BatteryService: online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
,04-01 10:47:59.065  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
04-01 10:47:59.070  3403  4793 D BatteryService: stay LED for fully charged,
,04-01 10:47:59.075  3403  3403 I MotionRecognitionService: Plugged
04-01 10:47:59.075  3403  3403 D MotionRecognitionService:   cableConnection= 1,
04-01 10:47:59.075  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
04-01 10:47:59.075  3403  3403 D MotionRecognitionService: skip setTransmitPower. ,
,04-01 10:47:59.090  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
04-01 10:47:59.090  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:47:59.090  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:47:59.105  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:47:59.105  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
04-01 10:47:59.105  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:47:59.120  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:47:59.120  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:47:59.125  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:48:07.775  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 240 (W:30), CUR = 9, LCD = 0
,04-01 10:48:09.200  3403  3850 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:48:09.205  3403  3850 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:48:09.205  3403  3850 D BatteryService: online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
,04-01 10:48:09.205  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,04-01 10:48:09.215  3403  3403 I MotionRecognitionService: Plugged
04-01 10:48:09.215  3403  3403 D MotionRecognitionService:   cableConnection= 1
04-01 10:48:09.215  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
04-01 10:48:09.215  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:48:09.215  3403  3850 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 14ms,
04-01 10:48:09.215  3403  3850 D BatteryService: stay LED for fully charged
,04-01 10:48:09.225  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:48:09.225  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:48:09.225  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:48:09.240  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
04-01 10:48:09.240  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:48:09.250  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:48:09.250  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:48:09.250  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:48:09.250  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:48:17.800  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 240 (W:30), CUR = 8, LCD = 0
,04-01 10:48:19.340  3403  4027 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:48:19.340  3403  4027 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:48:19.340  3403  4027 D BatteryService: online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
,04-01 10:48:19.340  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,04-01 10:48:19.350  3403  3403 I MotionRecognitionService: Plugged
04-01 10:48:19.350  3403  3403 D MotionRecognitionService:   cableConnection= 1,
,04-01 10:48:19.350  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
,04-01 10:48:19.350  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:48:19.355  3403  4027 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 15ms
,04-01 10:48:19.355  3403  4027 D BatteryService: stay LED for fully charged
,04-01 10:48:19.365  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,04-01 10:48:19.365  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:48:19.365  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:48:19.385  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
04-01 10:48:19.385  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:48:19.395  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:48:19.395  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:48:19.395  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:48:19.395  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:48:20.775  3403  3863 E Watchdog: !@Sync 45 [04-01 10:48:20.781],
,04-01 10:48:27.825  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 240 (W:30), CUR = 10, LCD = 0
,04-01 10:48:29.475  3403  4002 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,04-01 10:48:29.475  3403  4002 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:48:29.475  3403  4002 D BatteryService: online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:21
,04-01 10:48:29.480  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
04-01 10:48:29.485  3403  4002 D BatteryService: stay LED for fully charged,
,04-01 10:48:29.490  3403  3403 I MotionRecognitionService: Plugged,
04-01 10:48:29.490  3403  3403 D MotionRecognitionService:   cableConnection= 1,
,04-01 10:48:29.490  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
04-01 10:48:29.490  3403  3403 D MotionRecognitionService: skip setTransmitPower. ,
,04-01 10:48:29.500  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
04-01 10:48:29.500  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,04-01 10:48:29.505  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:48:29.525  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
04-01 10:48:29.525  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:48:29.535  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:48:29.535  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:48:29.535  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:48:29.535  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:48:37.850  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 240 (W:30), CUR = 9, LCD = 0
,04-01 10:48:39.615  3403  4786 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:48:39.615  3403  4786 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:48:39.615  3403  4786 D BatteryService: online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
,04-01 10:48:39.620  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,04-01 10:48:39.625  3403  3403 I MotionRecognitionService: Plugged,
04-01 10:48:39.625  3403  3403 D MotionRecognitionService:   cableConnection= 1
,04-01 10:48:39.625  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,04-01 10:48:39.625  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
04-01 10:48:39.625  3403  4786 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 11ms,
,04-01 10:48:39.625  3403  4786 D BatteryService: stay LED for fully charged,
04-01 10:48:39.640  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:48:39.640  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,04-01 10:48:39.640  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate,
,04-01 10:48:39.660  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
04-01 10:48:39.660  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:48:39.670  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:48:39.670  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:48:39.670  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:48:39.670  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:48:47.880  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 240 (W:30), CUR = 7, LCD = 0
,04-01 10:48:49.755  3403  4407 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:48:49.755  3403  4407 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:48:49.755  3403  4407 D BatteryService: online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:2
,04-01 10:48:49.755  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,04-01 10:48:49.765  3403  3403 I MotionRecognitionService: Plugged
04-01 10:48:49.765  3403  3403 D MotionRecognitionService:   cableConnection= 1
04-01 10:48:49.765  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
04-01 10:48:49.765  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:48:49.765  3403  4407 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 13ms,
04-01 10:48:49.765  3403  4407 D BatteryService: stay LED for fully charged,
,04-01 10:48:49.780  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,04-01 10:48:49.780  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:48:49.780  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:48:49.800  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,04-01 10:48:49.800  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:48:49.810  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:48:49.810  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:48:49.810  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:48:49.810  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:48:50.785  3403  3863 E Watchdog: !@Sync 46 [04-01 10:48:50.790]
,04-01 10:48:53.725  2891  4804 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,04-01 10:48:57.905  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 240 (W:30), CUR = 7, LCD = 0
,04-01 10:48:59.895  3403  4737 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:48:59.895  3403  4737 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:48:59.895  3403  4737 D BatteryService: online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
,04-01 10:48:59.895  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
04-01 10:48:59.895  3403  4737 D BatteryService: stay LED for fully charged
,04-01 10:48:59.905  3403  3403 I MotionRecognitionService: Plugged,
04-01 10:48:59.905  3403  3403 D MotionRecognitionService:   cableConnection= 1,
,04-01 10:48:59.905  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,04-01 10:48:59.905  3403  3403 D MotionRecognitionService: skip setTransmitPower. ,
,04-01 10:48:59.915  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,04-01 10:48:59.915  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:48:59.915  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:48:59.935  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
04-01 10:48:59.935  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:48:59.950  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:48:59.950  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:48:59.950  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:48:59.950  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:49:07.935  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 240 (W:30), CUR = 8, LCD = 0
,04-01 10:49:10.030  3403  3851 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:49:10.030  3403  3851 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:49:10.030  3403  3851 D BatteryService: online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
,04-01 10:49:10.030  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
04-01 10:49:10.030  3403  3851 D BatteryService: stay LED for fully charged
,04-01 10:49:10.040  3403  3403 I MotionRecognitionService: Plugged
04-01 10:49:10.040  3403  3403 D MotionRecognitionService:   cableConnection= 1,
04-01 10:49:10.040  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
,04-01 10:49:10.040  3403  3403 D MotionRecognitionService: skip setTransmitPower. ,
,04-01 10:49:10.050  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,04-01 10:49:10.050  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:49:10.050  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:49:10.075  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,04-01 10:49:10.075  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:49:10.085  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:49:10.085  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:49:10.085  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:49:10.085  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:49:17.965  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 240 (W:30), CUR = 7, LCD = 0
,04-01 10:49:20.165  3403  3830 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:49:20.165  3403  3830 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:49:20.165  3403  3830 D BatteryService: online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-11
,04-01 10:49:20.170  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
04-01 10:49:20.170  3403  3830 D BatteryService: stay LED for fully charged
,04-01 10:49:20.175  3403  3403 I MotionRecognitionService: Plugged
,04-01 10:49:20.175  3403  3403 D MotionRecognitionService:   cableConnection= 1
04-01 10:49:20.175  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,04-01 10:49:20.175  3403  3403 D MotionRecognitionService: skip setTransmitPower. ,
,04-01 10:49:20.190  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
04-01 10:49:20.190  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:49:20.190  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:49:20.210  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,04-01 10:49:20.210  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:49:20.220  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:49:20.220  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:49:20.220  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:49:20.220  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:49:20.795  3403  3863 E Watchdog: !@Sync 47 [04-01 10:49:20.799]
,04-01 10:49:27.995  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 240 (W:30), CUR = 7, LCD = 0
,04-01 10:49:30.300  3403  4396 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:49:30.305  3403  4396 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:49:30.305  3403  4396 D BatteryService: online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
,04-01 10:49:30.305  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
04-01 10:49:30.310  3403  4396 D BatteryService: stay LED for fully charged
,04-01 10:49:30.315  3403  3403 I MotionRecognitionService: Plugged
04-01 10:49:30.315  3403  3403 D MotionRecognitionService:   cableConnection= 1
04-01 10:49:30.315  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
04-01 10:49:30.315  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:49:30.325  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
04-01 10:49:30.325  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:49:30.325  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:49:30.345  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,04-01 10:49:30.345  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:49:30.355  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:49:30.355  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:49:30.355  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:49:30.355  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:49:38.025  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 240 (W:30), CUR = 7, LCD = 0
,04-01 10:49:40.445  3403  3649 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:49:40.445  3403  3649 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:49:40.445  3403  3649 D BatteryService: online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:7
,04-01 10:49:40.450  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
04-01 10:49:40.450  3403  3649 D BatteryService: stay LED for fully charged,
,04-01 10:49:40.455  3403  3403 I MotionRecognitionService: Plugged
04-01 10:49:40.455  3403  3403 D MotionRecognitionService:   cableConnection= 1,
04-01 10:49:40.455  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
04-01 10:49:40.455  3403  3403 D MotionRecognitionService: skip setTransmitPower. ,
,04-01 10:49:40.470  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
04-01 10:49:40.470  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:49:40.470  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:49:40.490  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,04-01 10:49:40.490  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:49:40.500  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:49:40.500  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:49:40.500  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:49:40.500  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:49:44.020  3403  3583 I PowerManagerService: [PWL] Off : 1380s ago
,04-01 10:49:48.050  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 240 (W:30), CUR = 9, LCD = 0
,04-01 10:49:50.580  3403  3432 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:49:50.580  3403  3432 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
,04-01 10:49:50.580  3403  3432 D BatteryService: online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-2
,04-01 10:49:50.585  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
04-01 10:49:50.585  3403  3432 D BatteryService: stay LED for fully charged
,04-01 10:49:50.595  3403  3403 I MotionRecognitionService: Plugged
04-01 10:49:50.595  3403  3403 D MotionRecognitionService:   cableConnection= 1,
04-01 10:49:50.595  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
04-01 10:49:50.595  3403  3403 D MotionRecognitionService: skip setTransmitPower. ,
,04-01 10:49:50.605  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
04-01 10:49:50.605  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:49:50.605  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate,
,04-01 10:49:50.625  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,04-01 10:49:50.630  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:49:50.635  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:49:50.635  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:49:50.635  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:49:50.635  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:49:50.805  3403  3863 E Watchdog: !@Sync 48 [04-01 10:49:50.807]
,04-01 10:49:53.725  2891  4804 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,04-01 10:49:58.075  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 240 (W:30), CUR = 7, LCD = 0
,04-01 10:50:00.720  3403  4028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:50:00.720  3403  4028 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:50:00.720  3403  4028 D BatteryService: online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:7
,04-01 10:50:00.725  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
04-01 10:50:00.725  3403  4028 D BatteryService: stay LED for fully charged
,04-01 10:50:00.735  3403  3403 I MotionRecognitionService: Plugged
04-01 10:50:00.735  3403  3403 D MotionRecognitionService:   cableConnection= 1
04-01 10:50:00.735  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,04-01 10:50:00.735  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:50:00.745  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
04-01 10:50:00.745  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:50:00.745  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:50:00.760  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,04-01 10:50:00.760  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:50:00.775  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:50:00.775  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:50:00.775  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:50:00.775  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:50:08.105  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 240 (W:30), CUR = 7, LCD = 0
,04-01 10:50:10.860  3403  3434 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:50:10.860  3403  3434 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:50:10.860  3403  3434 D BatteryService: online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
,04-01 10:50:10.860  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
04-01 10:50:10.865  3403  3434 D BatteryService: stay LED for fully charged
,04-01 10:50:10.870  3403  3403 I MotionRecognitionService: Plugged,
04-01 10:50:10.870  3403  3403 D MotionRecognitionService:   cableConnection= 1
04-01 10:50:10.870  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
,04-01 10:50:10.870  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:50:10.880  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
04-01 10:50:10.880  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:50:10.880  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:50:10.900  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
04-01 10:50:10.900  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:50:10.910  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:50:10.910  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:50:10.910  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:50:10.910  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:50:18.135  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 240 (W:30), CUR = 6, LCD = 0
,04-01 10:50:20.810  3403  3863 E Watchdog: !@Sync 49 [04-01 10:50:20.816]
,04-01 10:50:21.000  3403  4003 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:50:21.000  3403  4003 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:50:21.000  3403  4003 D BatteryService: online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
,04-01 10:50:21.000  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
04-01 10:50:21.005  3403  4003 D BatteryService: stay LED for fully charged
,04-01 10:50:21.010  3403  3403 I MotionRecognitionService: Plugged
04-01 10:50:21.010  3403  3403 D MotionRecognitionService:   cableConnection= 1,
04-01 10:50:21.010  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
04-01 10:50:21.010  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:50:21.020  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
04-01 10:50:21.020  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:50:21.020  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:50:21.040  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,04-01 10:50:21.040  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:50:21.050  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:50:21.050  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:50:21.050  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:50:21.050  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:50:28.170  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 240 (W:30), CUR = 8, LCD = 0
,04-01 10:50:31.135  3403  4793 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:50:31.135  3403  4793 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:50:31.135  3403  4793 D BatteryService: online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:7
,04-01 10:50:31.140  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
04-01 10:50:31.140  3403  4793 D BatteryService: stay LED for fully charged
,04-01 10:50:31.150  3403  3403 I MotionRecognitionService: Plugged,
04-01 10:50:31.150  3403  3403 D MotionRecognitionService:   cableConnection= 1
04-01 10:50:31.150  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,04-01 10:50:31.150  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:50:31.160  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,04-01 10:50:31.160  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
04-01 10:50:31.160  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:50:31.180  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,04-01 10:50:31.180  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:50:31.190  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:50:31.190  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:50:31.190  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:50:31.190  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:50:38.195  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 240 (W:30), CUR = 7, LCD = 0
,04-01 10:50:41.275  3403  3850 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:50:41.275  3403  3850 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:50:41.275  3403  3850 D BatteryService: online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-5
,04-01 10:50:41.275  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,04-01 10:50:41.285  3403  3403 I MotionRecognitionService: Plugged
04-01 10:50:41.285  3403  3403 D MotionRecognitionService:   cableConnection= 1,
04-01 10:50:41.285  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
04-01 10:50:41.285  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:50:41.285  3403  3850 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 12ms,
,04-01 10:50:41.285  3403  3850 D BatteryService: stay LED for fully charged,
,04-01 10:50:41.300  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
04-01 10:50:41.300  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,04-01 10:50:41.300  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate,
,04-01 10:50:41.325  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
04-01 10:50:41.325  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:50:41.335  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:50:41.335  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:50:41.335  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:50:41.335  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:50:48.095  3403  3605 D TimaService: TIMA: TimaService scheduler is intialized. 
04-01 10:50:48.095  3403  3605 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,04-01 10:50:48.100  3403  3604 D TimaService: TimaServiceHandler.handleMessage what =1,
,04-01 10:50:48.250  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 240 (W:30), CUR = 6, LCD = 0
,04-01 10:50:50.820  3403  3863 E Watchdog: !@Sync 50 [04-01 10:50:50.823]
,04-01 10:50:51.425  3403  4027 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:50:51.425  3403  4027 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
,04-01 10:50:51.425  3403  4027 D BatteryService: online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
04-01 10:50:51.425  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
04-01 10:50:51.430  3403  4027 D BatteryService: stay LED for fully charged
,04-01 10:50:51.440  3403  3403 I MotionRecognitionService: Plugged
04-01 10:50:51.440  3403  3403 D MotionRecognitionService:   cableConnection= 1
04-01 10:50:51.440  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,04-01 10:50:51.440  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:50:51.450  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,04-01 10:50:51.450  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:50:51.450  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate,
,04-01 10:50:51.475  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,04-01 10:50:51.475  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:50:51.485  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:50:51.485  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:50:51.485  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:50:51.485  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:50:52.940  3403  3605 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
04-01 10:50:52.940  3403  3605 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,04-01 10:50:52.960  3403  3605 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
04-01 10:50:52.960  3403  3605 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,04-01 10:50:53.725  2891  4804 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,04-01 10:50:58.280  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 240 (W:30), CUR = 7, LCD = 0
,04-01 10:51:01.565  3403  4002 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:51:01.565  3403  4002 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:51:01.565  3403  4002 D BatteryService: online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
,04-01 10:51:01.570  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,04-01 10:51:01.575  3403  3403 I MotionRecognitionService: Plugged
04-01 10:51:01.580  3403  3403 D MotionRecognitionService:   cableConnection= 1,
04-01 10:51:01.580  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
,04-01 10:51:01.580  3403  3403 D MotionRecognitionService: skip setTransmitPower. ,
04-01 10:51:01.580  3403  4002 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 15ms,
,04-01 10:51:01.580  3403  4002 D BatteryService: stay LED for fully charged
,04-01 10:51:01.590  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,04-01 10:51:01.590  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:51:01.595  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:51:01.615  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
04-01 10:51:01.615  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:51:01.625  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:51:01.625  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:51:01.625  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:51:01.625  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:51:08.310  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 240 (W:30), CUR = 7, LCD = 0
,04-01 10:51:11.705  3403  4786 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,04-01 10:51:11.705  3403  4786 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:51:11.705  3403  4786 D BatteryService: online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
,04-01 10:51:11.710  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
04-01 10:51:11.720  3403  3403 I MotionRecognitionService: Plugged
04-01 10:51:11.720  3403  3403 D MotionRecognitionService:   cableConnection= 1,
04-01 10:51:11.720  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
04-01 10:51:11.720  3403  3403 D MotionRecognitionService: skip setTransmitPower. ,
04-01 10:51:11.725  3403  4786 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 19ms,
04-01 10:51:11.725  3403  4786 D BatteryService: stay LED for fully charged,
,04-01 10:51:11.735  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,04-01 10:51:11.735  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,04-01 10:51:11.735  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:51:11.755  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
04-01 10:51:11.755  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:51:11.770  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:51:11.770  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:51:11.770  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:51:11.770  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:51:18.340  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 240 (W:30), CUR = 6, LCD = 0
,04-01 10:51:20.825  3403  3863 E Watchdog: !@Sync 51 [04-01 10:51:20.830]
,04-01 10:51:21.850  3403  4407 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:51:21.850  3403  4407 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:51:21.850  3403  4407 D BatteryService: online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-12
,04-01 10:51:21.855  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
04-01 10:51:21.855  3403  4407 D BatteryService: stay LED for fully charged,
,04-01 10:51:21.865  3403  3403 I MotionRecognitionService: Plugged
04-01 10:51:21.865  3403  3403 D MotionRecognitionService:   cableConnection= 1
04-01 10:51:21.865  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
04-01 10:51:21.865  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:51:21.870  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:51:21.870  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:51:21.870  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:51:21.890  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
04-01 10:51:21.890  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:51:21.900  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:51:21.900  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:51:21.900  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:51:21.900  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:51:28.365  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 240 (W:30), CUR = 6, LCD = 0
,04-01 10:51:31.990  3403  4737 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:51:31.990  3403  4737 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:51:31.990  3403  4737 D BatteryService: online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
,04-01 10:51:31.990  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,04-01 10:51:32.000  3403  3403 I MotionRecognitionService: Plugged
04-01 10:51:32.000  3403  3403 D MotionRecognitionService:   cableConnection= 1,
,04-01 10:51:32.000  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
04-01 10:51:32.000  3403  3403 D MotionRecognitionService: skip setTransmitPower. ,
,04-01 10:51:32.005  3403  4737 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 16ms,
,04-01 10:51:32.005  3403  4737 D BatteryService: stay LED for fully charged
,04-01 10:51:32.015  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:51:32.015  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:51:32.015  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:51:32.020  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:51:32.025  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,04-01 10:51:32.025  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:51:32.040  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:51:32.040  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:51:32.040  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:51:38.395  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 240 (W:30), CUR = 7, LCD = 0
,04-01 10:51:42.130  3403  3851 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:51:42.130  3403  3851 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:51:42.130  3403  3851 D BatteryService: online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-11
,04-01 10:51:42.130  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,04-01 10:51:42.145  3403  3403 I MotionRecognitionService: Plugged
04-01 10:51:42.145  3403  3403 D MotionRecognitionService:   cableConnection= 1
04-01 10:51:42.145  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
04-01 10:51:42.145  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:51:42.145  3403  3851 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 17ms,
04-01 10:51:42.145  3403  3851 D BatteryService: stay LED for fully charged
,04-01 10:51:42.155  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:51:42.155  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:51:42.155  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:51:42.165  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,04-01 10:51:42.170  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:51:42.180  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:51:42.180  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:51:42.180  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:51:42.180  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:51:44.025  3403  3583 I PowerManagerService: [PWL] Off : 1500s ago
,04-01 10:51:48.420  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 240 (W:30), CUR = 6, LCD = 0
,04-01 10:51:50.835  3403  3863 E Watchdog: !@Sync 52 [04-01 10:51:50.839]
,04-01 10:51:52.275  3403  3830 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:51:52.275  3403  3830 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:51:52.275  3403  3830 D BatteryService: online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:3
04-01 10:51:52.275  3403  3830 D BatteryService: stay LED for fully charged
04-01 10:51:52.275  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,04-01 10:51:52.280  3403  3403 I MotionRecognitionService: Plugged,
04-01 10:51:52.280  3403  3403 D MotionRecognitionService:   cableConnection= 1
04-01 10:51:52.280  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
04-01 10:51:52.280  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:51:52.290  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
04-01 10:51:52.290  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:51:52.290  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:51:52.300  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
04-01 10:51:52.305  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:51:52.315  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:51:52.315  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:51:52.315  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:51:52.315  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:51:53.725  2891  4804 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,04-01 10:51:58.445  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 240 (W:30), CUR = 7, LCD = 0
,04-01 10:52:02.415  3403  4407 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:52:02.415  3403  4407 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
,04-01 10:52:02.420  3403  4407 D BatteryService: online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:28
04-01 10:52:02.420  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
04-01 10:52:02.420  3403  4407 D BatteryService: stay LED for fully charged
,04-01 10:52:02.425  3403  3403 I MotionRecognitionService: Plugged
04-01 10:52:02.425  3403  3403 D MotionRecognitionService:   cableConnection= 1,
04-01 10:52:02.425  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,04-01 10:52:02.425  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:52:02.435  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
04-01 10:52:02.435  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:52:02.435  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:52:02.455  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,04-01 10:52:02.455  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:52:02.465  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:52:02.465  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:52:02.465  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:52:02.465  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:52:08.475  3403  6140 D SSRM:n  : SIOP:: AP = 240, PST = 240 (W:30), CUR = 8, LCD = 0
,04-01 10:52:12.555  3403  4737 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 10:52:12.555  3403  4737 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 10:52:12.555  3403  4737 D BatteryService: online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
,04-01 10:52:12.560  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
04-01 10:52:12.560  3403  4737 D BatteryService: stay LED for fully charged
,04-01 10:52:12.565  3403  3403 I MotionRecognitionService: Plugged
04-01 10:52:12.565  3403  3403 D MotionRecognitionService:   cableConnection= 1,
04-01 10:52:12.565  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
04-01 10:52:12.565  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
,04-01 10:52:12.575  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
04-01 10:52:12.580  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 10:52:12.580  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,04-01 10:52:12.600  5917  5917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,04-01 10:52:12.600  5917  6034 D HeadsetStateMachine: Disconnected process message: 10
,04-01 10:52:12.610  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 10:52:12.610  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 10:52:12.610  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 10:52:12.610  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,TIME-OUT KILL (timeout was 1400000ms),04-01 10:52:15.725 12676 12676 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
04-01 10:52:15.730 12676 12676 D AndroidRuntime: CheckJNI is OFF
04-01 10:52:15.730 12676 12676 D AndroidRuntime: readGMSProperty: start
04-01 10:52:15.730 12676 12676 D AndroidRuntime: readGMSProperty: already setted!!
04-01 10:52:15.730 12676 12676 D AndroidRuntime: propertySet: couldn't set property (it is from app)
04-01 10:52:15.730 12676 12676 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
04-01 10:52:15.730 12676 12676 D AndroidRuntime: readGMSProperty: end
04-01 10:52:15.730 12676 12676 D AndroidRuntime: addProductProperty: start
04-01 10:52:15.825 12676 12676 E AffinityControl: AffinityControl: registerfunction enter
04-01 10:52:15.855 12676 12676 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
04-01 10:52:15.865  3403  3432 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
04-01 10:52:15.865  3403  3432 D PackageManager: START PACKAGE DELETE: observer{522664056}
04-01 10:52:15.865  3403  3432 D PackageManager: pkg{<packageName>}
04-01 10:52:15.865  3403  3432 D PackageManager: user{0}
04-01 10:52:15.865  3403  3432 D PackageManager: caller{2000}
04-01 10:52:15.865  3403  3432 D PackageManager: flags{2}
04-01 10:52:15.865  3403  3432 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
04-01 10:52:15.865  3403  3432 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
04-01 10:52:15.865  3403  3589 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
04-01 10:52:15.865  3403  3432 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
04-01 10:52:15.865  3403  3432 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
04-01 10:52:15.865  3403  3589 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
04-01 10:52:15.865  3403  3589 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
04-01 10:52:15.865  3403  3589 D ApplicationPolicy: getApplicationUninstallationEnabled
04-01 10:52:15.865  3403  3589 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
04-01 10:52:15.870  3403  3589 D PackageManager: !@killApplicatoin: 10011, uninstall pkg
04-01 10:52:15.875  3403  3567 I ActivityManager: Force stopping com.test.thalitest appid=10011 user=-1: uninstall pkg
04-01 10:52:15.880  3403  3567 I ActivityManager: Killing 11399:com.test.thalitest/u0a11 (adj 0): stop com.test.thalitest cause uninstall pkg
04-01 10:52:15.905  3403  3567 I ActivityManager:   Force finishing activity 3 ActivityRecord{ef60afc u0 com.test.thalitest/.MainActivity t42}
04-01 10:52:15.905  3403  3567 W ActivityManager: mDVFSHelper.acquire()
04-01 10:52:15.990  3403  3589 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
04-01 10:52:15.995  3403  3589 W PackageSettings: Skipping PackageSetting{2b6efc1f com.example.hello/10691} due to missing metadata
04-01 10:52:16.015  3403  3589 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
04-01 10:52:16.020  3403  3567 D PowerManagerService: setKeyboardVisibility: false
04-01 10:52:16.025  3403  3567 I ActivityManager: Skip updateThumbnail for r=ActivityRecord{3bcf8a16 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t40}
04-01 10:52:16.035  3403  3589 I ActivityManager: Force stopping com.test.thalitest appid=10011 user=0: pkg removed
04-01 10:52:16.035  3403  3589 I ActivityManager:   Force finishing activity 3 ActivityRecord{ef60afc u0 com.test.thalitest/.MainActivity t42 f}
04-01 10:52:16.035  3403  3589 W ActivityManager: Duplicate finish request for ActivityRecord{ef60afc u0 com.test.thalitest/.MainActivity t42 f}
04-01 10:52:16.040  3403  3589 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
04-01 10:52:16.060  9200  9200 I art     : Explicit concurrent mark sweep GC freed 2670(151KB) AllocSpace objects, 0(0B) LOS objects, 69% free, 1770KB/5MB, paused 575us total 19.598ms
04-01 10:52:16.060  3403  3851 I WindowState: WIN DEATH: Window{3906a33a u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}
04-01 10:52:16.065  2859  3628 I SurfaceFlinger: id=15 Removed NainActivit (6/8)
04-01 10:52:16.065  2859  3081 I SurfaceFlinger: id=15 Removed NainActivit (-2/8)
04-01 10:52:16.065  3403  3851 D InputDispatcher: Focus left window: 11399
04-01 10:52:16.065  3403  3690 D TaskPersister: removeObsoleteFile: deleting file=42_task.xml
04-01 10:52:16.065  3403  3690 D TaskPersister: removeObsoleteFile: deleting file=42_task_thumbnail.png
04-01 10:52:16.070  3403  3851 D MultiWindowConverter: dismissGuide() : Before attaching the guide view, mForceDismissGuide : false
04-01 10:52:16.070  3403  3567 D InputDispatcher: Focused application released
04-01 10:52:16.070  2859  4727 I SurfaceFlinger: id=15 Removed NainActivit (-2/8)
04-01 10:52:16.075  6603  6603 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(433/onResume)] 
04-01 10:52:16.080  3403  3581 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3403 uid:1000
04-01 10:52:16.080  3403  3581 D PointerIcon: setMouseCustomIcon IconType is same.101
04-01 10:52:16.080  3403  3581 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3403 uid:1000
04-01 10:52:16.080  3403  3581 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
04-01 10:52:16.095  3919  3919 I art     : Explicit concurrent mark sweep GC freed 1697(88KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 474us total 48.173ms
04-01 10:52:16.100  6603  6603 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5412/IlIlllIlllllIlIllllI)] Get Postpone Count : 0
04-01 10:52:16.110  3403  3630 I InputReader: Reconfiguring input devices.  changes=0x00000010
04-01 10:52:16.115  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.PACKAGE_REMOVED
04-01 10:52:16.120  4012  4012 I art     : Explicit concurrent mark sweep GC freed 16149(929KB) AllocSpace objects, 9(1362KB) LOS objects, 12% free, 56MB/64MB, paused 381us total 65.479ms
04-01 10:52:16.120  4108  4108 I art     : Explicit concurrent mark sweep GC freed 15420(968KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/8MB, paused 536us total 68.559ms
04-01 10:52:16.120  4498  4498 E SamsungIME: mOCRHelper is null
04-01 10:52:16.125  4435  4825 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
04-01 10:52:16.125  6603  6603 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5134/lIIIIIIIlllllllIIlll)] Get Priority : 0
04-01 10:52:16.130 10818 10818 D LWLocationManager: getDeviceLocationId :  id = -100
04-01 10:52:16.130 10818 10818 D LocationWidgetApplication: getLastUiLocationId() : mLastUiLocationId = -100
04-01 10:52:16.130  6603  6603 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5434/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
04-01 10:52:16.135  6603  6603 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(443/onResume)] Postpone Count : 0
04-01 10:52:16.135  4685  4685 I art     : Explicit concurrent mark sweep GC freed 7542(502KB) AllocSpace objects, 5(80KB) LOS objects, 24% free, 8MB/11MB, paused 837us total 92.877ms
04-01 10:52:16.140  6603  6603 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5475/llIlIIIIlllIlllllIll)] Download Postpone status : 0
04-01 10:52:16.145  4685  4694 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@13e60b22)
04-01 10:52:16.150  3403  3651 D NtpTrustedTime: currentTimeMillis() cache hit
04-01 10:52:16.150  3403  3651 V NetworkStats: removeUidsLocked() for UIDs [10011]
04-01 10:52:16.150  3403  3651 V NetworkStats: performPollLocked(flags=0x3)
04-01 10:52:16.160  3403  3651 V NetworkStats: performPollLocked() took 7ms
04-01 10:52:16.160  3403  3651 D NtpTrustedTime: currentTimeMillis() cache hit
04-01 10:52:16.165  3403  3567 E ActivityManager: checkUser: useridlist=null, currentuser=0
04-01 10:52:16.165  3403  3567 E ActivityManager: checkUser: useridlist=null, currentuser=0
04-01 10:52:16.165  3403  3567 E ActivityManager: checkUser: useridlist=null, currentuser=0
04-01 10:52:16.165  3403  3567 E ActivityManager: checkUser: useridlist=null, currentuser=0
04-01 10:52:16.170  5356  5389 W ResourceType: For resource 0x7f020570, entry index(1392) is beyond type entryCount(787)
04-01 10:52:16.170  5356  5389 W ResourceType: Failure getting entry for 0x7f020570 (t=1 e=1392) (error -75)
04-01 10:52:16.175  4685  4694 W SQLiteConnectionPool: A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
04-01 10:52:16.180 12695 12695 E Zygote  : MountEmulatedStorage()
04-01 10:52:16.180 12695 12695 E Zygote  : v2
04-01 10:52:16.180 12695 12695 I libpersona: KNOX_SDCARD checking this for 10063
04-01 10:52:16.180 12695 12695 I libpersona: KNOX_SDCARD not a persona
04-01 10:52:16.185 12695 12695 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
04-01 10:52:16.185  3403  3567 I ActivityManager: Start proc 12695:com.samsung.android.app.vrsetupwizardstub/u0a63 for broadcast-3 com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver
04-01 10:52:16.185 12695 12695 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
04-01 10:52:16.190  6603  6603 I DBG_DM  : [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
04-01 10:52:16.190 12695 12695 E Zygote  : accessInfo : 0
04-01 10:52:16.190  6603  6603 I DBG_DM  : [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(327/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
04-01 10:52:16.190 12695 12695 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
04-01 10:52:16.205  6603  6603 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5134/lIIIIIIIlllllllIIlll)] Get Priority : 0
04-01 10:52:16.210  3980  3980 D RegisteredServicesCache: empty dynamic service
04-01 10:52:16.220  3403  4793 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
04-01 10:52:16.220  3403  4793 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
04-01 10:52:16.225 12695 12695 D TimaKeyStoreProvider: TimaSignature is unavailable
04-01 10:52:16.225 12695 12695 D ActivityThread: Added TimaKeyStore provider
04-01 10:52:16.225  6603  6603 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5412/IlIlllIlllllIlIllllI)] Get Postpone Count : 0
04-01 10:52:16.230  3403  3403 I art     : Explicit concurrent mark sweep GC freed 31532(2MB) AllocSpace objects, 45(720KB) LOS objects, 33% free, 29MB/44MB, paused 8.498ms total 186.507ms
04-01 10:52:16.230  3980  3980 D RegisteredComponentCache: Collect Tech packages for Knox
04-01 10:52:16.230  3403  3589 I art     : WaitForGcToComplete blocked for 167.509ms for cause Explicit
04-01 10:52:16.230  6603  6603 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5054/IIlllIlIIlIllIlllIll)] Get Force status : 0
04-01 10:52:16.235  6603  6603 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5434/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
04-01 10:52:16.235  6603  6603 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(537/llIIIIlllllIIllIIllI)] Check Force Install : false
04-01 10:52:16.235  6603  6603 I DBG_DM  : [llIIlIIlIllIllIlllII(337/IllIlIIIIlIIlIIIllIl)] 
04-01 10:52:16.240  6603  6603 I DBG_DM  : [llIIlIIlIllIllIlllII(343/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
04-01 10:52:16.240  3403  3649 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1eda6fb6 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{dcf34b7 12695:com.samsung.android.app.vrsetupwizardstub/u0a63}
04-01 10:52:16.240  3403  4027 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
04-01 10:52:16.240  3403  4027 D KnoxTimeoutHandler: postActiveUserChange for user 0
04-01 10:52:16.240  3403  4027 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
04-01 10:52:16.245  6603  6603 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(425/onPause)] 
04-01 10:52:16.250  2859  2859 I SurfaceFlinger: id=16 createSurf (1440x2560),1 flag=404, YUIInstallC
04-01 10:52:16.250  3403  4737 D MultiWindowConverter: dismissGuide() : Before attaching the guide view, mForceDismissGuide : false
04-01 10:52:16.255  3403  3579 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{10f7abb9 u0 d0 com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}
04-01 10:52:16.255  3403  4737 D InputDispatcher: Focus entered window: 6603
04-01 10:52:16.255  3403  3581 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3403 uid:1000
04-01 10:52:16.255  3403  3581 D PointerIcon: setMouseCustomIcon IconType is same.101
04-01 10:52:16.260  6603  6603 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
04-01 10:52:16.260  3403  3581 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3403 uid:1000
04-01 10:52:16.260  3403  3581 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
04-01 10:52:16.260  6603  9267 D mali_winsys: new_window_surface returns 0x3000,  [1440x2560]-format:1
04-01 10:52:16.260  3403  3434 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
04-01 10:52:16.265  3403  3434 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 11399 uid 10011
04-01 10:52:16.275  4498  4498 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
04-01 10:52:16.280  3403  3652 D NtpTrustedTime: currentTimeMillis() cache hit
04-01 10:52:16.280  3403  3652 D NtpTrustedTime: currentTimeMillis() cache hit
04-01 10:52:16.285 12695 12695 D VRSetupWizardStub/PackageIntentReceiver: onReceive()
04-01 10:52:16.285 12695 12695 D VRSetupWizardStub/PackageIntentReceiver: Action Package Remove
04-01 10:52:16.285 12695 12695 D VRSetupWizardStub/PackageIntentReceiver: packagename:com.test.thalitest
04-01 10:52:16.295  3403  3850 I ActivityManager: Killing 10485:com.facebook.system/u0a10 (adj 15): emptyCount ##31
04-01 10:52:16.295  3403  4027 D SecContentProvider2: query(), uri = 11 selection = getMyKnoxAdmin
04-01 10:52:16.295  3403  3850 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1eda6fb6 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{24eeccaa 7210:com.samsung.klmsagent/u0a21}
04-01 10:52:16.305  6603  6603 V ActivityThread: updateVisibility : ActivityRecord{2cd300e0 token=android.os.BinderProxy@346b9306 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
04-01 10:52:16.305  7210  7210 I KLMS-2.5.262: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Apr 01 10:52:16 GMT+02:00 2016
04-01 10:52:16.305  6603  6603 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@346b9306 time:1598508
04-01 10:52:16.305  3403  3581 W ActivityManager: mDVFSHelper.release()
04-01 10:52:16.305  3403  3581 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3bcf8a16 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t40} time:1598508
04-01 10:52:16.315  3403  3830 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
04-01 10:52:16.325  7210  7210 I KLMS-2.5.262: : KLMSAbstractReciever(): onReceive().END.
04-01 10:52:16.325  3403  4002 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=14, mSplitNum[1]=26, mSplitNum[2]=38, mBgSplitQueueNum=3 divideNum= 12 r.nextReceiver= 2 receivers.size=50
04-01 10:52:16.325  3403  4002 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
04-01 10:52:16.330  7210  7210 I KLMS-2.5.262: : KLMSIntentService(): onCreate()
04-01 10:52:16.330  7210  7210 I KLMS-2.5.262: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
04-01 10:52:16.330  7210  7210 I KLMS-2.5.262: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
04-01 10:52:16.330  7210 12713 I KLMS-2.5.262: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.service.KLMSIntentService (has extras) }
04-01 10:52:16.330  7210 12713 D KLMS-2.5.262: : KLMSIntentService(): PACKAGE_REMOVED
04-01 10:52:16.330  7210 12713 I KLMS-2.5.262: : Systemprocess(): listeningToPackageRemoved().START
04-01 10:52:16.330  7210 12713 I KLMS-2.5.262: : Systemprocess(): listeningToPackageRemoved().packageName: com.test.thalitest
04-01 10:52:16.330  7210 12713 I KLMS-2.5.262: : listeningToPackageRemovedforELM().START
04-01 10:52:16.330  7210 12713 I KLMS-2.5.262: : MDMBridge.getInstance()
04-01 10:52:16.330  7210 12713 I KLMS-2.5.262: : MDMBridge.getAllLicenseInfoFromSDK()
04-01 10:52:16.335  3403  4002 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1eda6fb6 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{38648739 6900:com.samsung.aasaservice/1000}
04-01 10:52:16.335  6900  6900 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
04-01 10:52:16.335  6900  6900 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
04-01 10:52:16.335  6900  6900 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:334)
04-01 10:52:16.335  6900  6900 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
04-01 10:52:16.335  6900  6900 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3509)
04-01 10:52:16.335  6900  6900 W System.err: 	at android.app.ActivityThread.access$1900(ActivityThread.java:197)
04-01 10:52:16.335  6900  6900 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1758)
04-01 10:52:16.335  6900  6900 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
04-01 10:52:16.335  6900  6900 W System.err: 	at android.os.Looper.loop(Looper.java:145)
04-01 10:52:16.335  6900  6900 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6872)
04-01 10:52:16.335  6900  6900 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
04-01 10:52:16.335  6900  6900 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
04-01 10:52:16.335  6900  6900 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
04-01 10:52:16.335  6900  6900 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
04-01 10:52:16.335  3403  3567 E ActivityManager: checkUser: useridlist=null, currentuser=0
04-01 10:52:16.335  7210 12713 I KLMS-2.5.262: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
04-01 10:52:16.335  3403  3567 E ActivityManager: checkUser: useridlist=null, currentuser=0
04-01 10:52:16.335  3403  3567 E ActivityManager: checkUser: useridlist=null, currentuser=0
04-01 10:52:16.335  3403  3567 E ActivityManager: checkUser: useridlist=null, currentuser=0
04-01 10:52:16.340  7210 12713 I KLMS-2.5.262: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
04-01 10:52:16.340  7210 12713 I KLMS-2.5.262: : MDMBridge.getAllLicenseInfoFromSDK()
04-01 10:52:16.340  7210 12713 E KLMS-2.5.262: : arr si null
04-01 10:52:16.350  7210 12713 D KLMS-2.5.262: : DataSource(): Fetched Data from data base count : 0
04-01 10:52:16.355  7210 12713 I KLMS-2.5.262: : listeningToPackageRemovedforELM().END
04-01 10:52:16.355  7210 12713 I KLMS-2.5.262: : Systemprocess(): listeningToPackageRemovedforKLM().START
04-01 10:52:16.355  7210 12713 I KLMS-2.5.262: : Systemprocess(): .pkgName: com.test.thalitest
04-01 10:52:16.370 12715 12715 E Zygote  : MountEmulatedStorage()
04-01 10:52:16.370 12715 12715 E Zygote  : v2
04-01 10:52:16.370 12715 12715 I libpersona: KNOX_SDCARD checking this for 10042
04-01 10:52:16.370 12715 12715 I libpersona: KNOX_SDCARD not a persona
04-01 10:52:16.370 12715 12715 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
04-01 10:52:16.370  3403  3567 I ActivityManager: Start proc 12715:com.samsung.android.sdk.samsunglink/u0a42 for broadcast-4 com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver
04-01 10:52:16.375 12715 12715 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
04-01 10:52:16.375 12715 12715 E Zygote  : accessInfo : 0
04-01 10:52:16.375 12715 12715 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
04-01 10:52:16.380  3403  3589 I art     : Explicit concurrent mark sweep GC freed 10834(975KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 29MB/44MB, paused 1.843ms total 150.048ms
04-01 10:52:16.385  3403  3567 V BroadcastQueue: [backgroundsplit_1] Process cur broadcast BroadcastRecord{1490ef2 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{33c58a4f 11104:com.samsung.android.sm/1000}
04-01 10:52:16.395  3403  3567 E ActivityManager: checkUser: useridlist=null, currentuser=0
04-01 10:52:16.395  3403  3567 E ActivityManager: checkUser: useridlist=null, currentuser=0
04-01 10:52:16.395  3403  3567 E ActivityManager: checkUser: useridlist=null, currentuser=0
04-01 10:52:16.395  3403  3567 E ActivityManager: checkUser: useridlist=null, currentuser=0
04-01 10:52:16.410 12730 12730 E Zygote  : MountEmulatedStorage()
04-01 10:52:16.410 12730 12730 E Zygote  : v2
04-01 10:52:16.410 12730 12730 I libpersona: KNOX_SDCARD checking this for 1000
04-01 10:52:16.410 12730 12730 I libpersona: KNOX_SDCARD not a persona
04-01 10:52:16.415 12715 12715 D TimaKeyStoreProvider: TimaSignature is unavailable
04-01 10:52:16.415 10818 12702 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
04-01 10:52:16.415 12715 12715 D ActivityThread: Added TimaKeyStore provider
04-01 10:52:16.415 12730 12730 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
04-01 10:52:16.415  3403  3567 I ActivityManager: Start proc 12730:com.sec.android.app.popupuireceiver/1000 for broadcast-4 com.sec.android.app.popupuireceiver/.PopupuiReceiver
04-01 10:52:16.420  3403  3589 D PackageManager: delete codoeFile: 
04-01 10:52:16.420  3403  3589 D PackageManager: Resopt: Clean up res: /data/app/com.test.thalitest-1/base.apk
04-01 10:52:16.425  3403  3589 D AASAuninstall: userId = 0, info.removedAppID = 10011, info.uid = 10011, packageName = com.test.thalitest
04-01 10:52:16.425 12730 12730 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
04-01 10:52:16.425  3403  3589 I AASA_removePackage: UID=10011 Target=com.test.thalitest
04-01 10:52:16.425 12730 12730 E Zygote  : accessInfo : 0
04-01 10:52:16.425  3403  3589 D PackageManager: result of delete: 1{522664056}
04-01 10:52:16.425 12730 12730 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
04-01 10:52:16.425  3403  3589 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
04-01 10:52:16.425  3403  3589 D PackageManager: userId{-1}
04-01 10:52:16.425  3403  3589 D PackageManager: andCode{true}
04-01 10:52:16.430 12676 12676 I art     : System.exit called, status: 0
04-01 10:52:16.430 12676 12676 I AndroidRuntime: VM exiting with result code 0.
04-01 10:52:16.430  3403  4786 V BroadcastQueue: [backgroundsplit_0] Process cur broadcast BroadcastRecord{2e81f5aa u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{11ab959b 12715:com.samsung.android.sdk.samsunglink/u0a42}
04-01 10:52:16.435  3403  4002 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1eda6fb6 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{43ac0ff 3403:system/1000}
04-01 10:52:16.445  9837 12745 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.test.thalitest
04-01 10:52:16.450  9837 12745 W System.err: remove failed: EACCES (Permission denied) : /storage/extSdCard/Android/data/com.test.thalitest
04-01 10:52:16.450  9837 12745 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.test.thalitest
04-01 10:52:16.450 12715 12715 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
04-01 10:52:16.450  9837 12745 W System.err: remove failed: EACCES (Permission denied) : /storage/extSdCard/Android/media/com.test.thalitest
04-01 10:52:16.450  9837 12745 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/obb/com.test.thalitest
04-01 10:52:16.450 12730 12730 D TimaKeyStoreProvider: TimaSignature is unavailable
04-01 10:52:16.450 12715 12715 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
04-01 10:52:16.450  9837 12745 W System.err: remove failed: EACCES (Permission denied) : /storage/extSdCard/Android/obb/com.test.thalitest
04-01 10:52:16.450 12730 12730 D ActivityThread: Added TimaKeyStore provider
04-01 10:52:16.455  3403  3403 D RCPManagerService: PackageReceiver onReceive()
04-01 10:52:16.455  3403  3403 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
04-01 10:52:16.455 11104 11104 I art     : Explicit concurrent mark sweep GC freed 150(20KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 1735KB/3MB, paused 392us total 43.220ms
04-01 10:52:16.455  3403  3403 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
04-01 10:52:16.455  3403  3403 I OTPFW   : PackageRemovalReceiver::onReceive Enter
04-01 10:52:16.455  3403  3403 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10011 container id = 0
04-01 10:52:16.455 10818 12702 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
04-01 10:52:16.455 10818 12702 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
04-01 10:52:16.455 10818 12702 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
04-01 10:52:16.455 10818 12702 W ResourcesManager: Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
04-01 10:52:16.460  7210 12713 D KLMS-2.5.262: : KLMSUtility(): IsPackageExistInDevice().mAppInfoList: 322
04-01 10:52:16.460  7210 12713 D KLMS-2.5.262: : KLMSSharedPreferences(): deleteNotificationAppList().pkgName: com.test.thalitest
04-01 10:52:16.460  7210 12713 I KLMS-2.5.262: : KLMSSharedPreferences(): getNotificationAppList(): null
04-01 10:52:16.460  7210 12713 I KLMS-2.5.262: : Systemprocess(): Notification App List is Null. Remove Notification.
04-01 10:52:16.460  3403  3403 I OTPFW   : ProvisionData::getAllEntries Enter
04-01 10:52:16.460  3403  3403 E OTPFW   : ProvisionData::getAllEntries Table is empty
04-01 10:52:16.460  3403  3434 V BroadcastQueue: [backgroundsplit_2] Process cur broadcast BroadcastRecord{28189798 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{28390bf1 12730:com.sec.android.app.popupuireceiver/1000}
04-01 10:52:16.465  3403  3403 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
04-01 10:52:16.465  3403  3403 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
04-01 10:52:16.465  7210 12713 D KLMS-2.5.262: : DataSource(): Fetched Data from data base count : 0
04-01 10:52:16.465  7210 12713 I KLMS-2.5.262: : Systemprocess(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
04-01 10:52:16.465  7210 12713 I KLMS-2.5.262: : Systemprocess(): listeningToPackageRemovedforKLM().END
04-01 10:52:16.465  7210 12713 I KLMS-2.5.262: : Systemprocess(): listeningToPackageRemoved().END
04-01 10:52:16.465  7210  7210 I KLMS-2.5.262: : KLMSIntentService(): onDestroy()
04-01 10:52:16.465  3403  3403 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
04-01 10:52:16.465  3403  3403 V EnterpriseBillingPolicy: uID is 10011
04-01 10:52:16.465  3403  3403 V EnterpriseBillingPolicy: Removed Packageuid is0
04-01 10:52:16.465  3403  3403 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
04-01 10:52:16.465  3403  3403 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
04-01 10:52:16.465  3403  3403 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
04-01 10:52:16.465  3403  3403 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
04-01 10:52:16.465  3403  3403 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
04-01 10:52:16.470  3403  3403 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
04-01 10:52:16.470  3403  3403 D SdpManagerService:  ActionReceiver::onReceive() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
04-01 10:52:16.470  3403  3403 D SdpManagerService: ACTION_PACKAGE_REMOVED Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) } DATA= package:com.test.thalitest UID 1000 userId 0
04-01 10:52:16.470  3403  3403 D SdpManagerService: ACTION_PACKAGE_REMOVED packageName:: com.test.thalitest
04-01 10:52:16.470  3403  4002 V BroadcastQueue: [backgroundsplit_1] Process cur broadcast BroadcastRecord{1490ef2 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{33c58a4f 11104:com.samsung.android.sm/1000}
04-01 10:52:16.475  3403  3403 D EnterprisePartitionManager: SND -> {secure_fs remove_enc_dir}
04-01 10:52:16.475  3403  3591 D EnterprisePartitionManager: RCV <-
04-01 10:52:16.475  3403  3403 D EnterprisePartitionManager: RMV <-
04-01 10:52:16.480  3403  4002 V BroadcastQueue: [backgroundsplit_1] Process cur broadcast BroadcastRecord{1490ef2 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{33c58a4f 11104:com.samsung.android.sm/1000}
04-01 10:52:16.480  3403  3403 E EnterprisePartitionManager: Failed to send commandcom.sec.knox.container.util.DaemonConnector$DaemonArgumentException: command 'secure_fs' failed with '500 3 Command not recognized'
04-01 10:52:16.480  3403  3403 W System.err: java.io.FileNotFoundException: /data/system/users/sdp_engine_list.xml: open failed: ENOENT (No such file or directory)
04-01 10:52:16.480  3403  3403 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
04-01 10:52:16.480  3403  3403 W System.err: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
04-01 10:52:16.480  3403  3403 W System.err: 	at com.android.server.SdpManagerService$SdpEngineDatabase$EngineListHandler.getEngineListLocked(SdpManagerService.java:1514)
04-01 10:52:16.480  3403  3403 W System.err: 	at com.android.server.SdpManagerService$SdpEngineDatabase$EngineListHandler.access$1100(SdpManagerService.java:1434)
04-01 10:52:16.480  3403  3403 W System.err: 	at com.android.server.SdpManagerService$SdpEngineDatabase.getEngineListLocked(SdpManagerService.java:1418)
04-01 10:52:16.480  3403  3403 W System.err: 	at com.android.server.SdpManagerService$SdpEngineDatabase.access$2200(SdpManagerService.java:1393)
04-01 10:52:16.480  3403  3403 W System.err: 	at com.android.server.SdpManagerService.handlePkgRemoved(SdpManagerService.java:2647)
04-01 10:52:16.480  3403  3403 W System.err: 	at com.android.server.SdpManagerService.access$2500(SdpManagerService.java:137)
04-01 10:52:16.480  3403  3403 W System.err: 	at com.android.server.SdpManagerService$ActionReceiver.onReceive(SdpManagerService.java:2719)
04-01 10:52:16.480  3403  3403 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:972)
04-01 10:52:16.480  3403  3403 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
04-01 10:52:16.480  3403  3403 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
04-01 10:52:16.480  3403  3403 W System.err: 	at android.os.Looper.loop(Looper.java:145)
04-01 10:52:16.480  3403  3403 W System.err: 	at com.android.server.SystemServer.run(SystemServer.java:469)
04-01 10:52:16.480  3403  3403 W System.err: 	at com.android.server.SystemServer.main(SystemServer.java:353)
04-01 10:52:16.480  3403  3403 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
04-01 10:52:16.480  3403  3403 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
04-01 10:52:16.480  3403  3403 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
04-01 10:52:16.480  3403  3403 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
04-01 10:52:16.480  3403  3403 W System.err: Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
04-01 10:52:16.480  3403  3403 W System.err: 	at libcore.io.Posix.open(Native Method)
04-01 10:52:16.480  3403  3403 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
04-01 10:52:16.480  3403  3403 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
04-01 10:52:16.480  3403  3403 W System.err: 	... 18 more
04-01 10:52:16.480  3403  3403 E SdpManagerService: failed to get engine list
04-01 10:52:16.485  3403  3403 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
04-01 10:52:16.485  3403  6140 D SSRM:bd : MSG_TYPE_APP_REMOVED::
04-01 10:52:16.485  3403  3403 V EnterpriseBillingPolicy: uID is 10011
04-01 10:52:16.485  3403  3403 V EnterpriseBillingPolicy: Removed Packageuid is0
04-01 10:52:16.485  3403  3403 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
04-01 10:52:16.485  3403  3403 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
04-01 10:52:16.485  3403  3403 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
04-01 10:52:16.485  3403  3403 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
04-01 10:52:16.485  3403  3403 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
04-01 10:52:16.485  3403  3403 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
04-01 10:52:16.485  3403  3403 D KnoxTimeoutHandler: handleActiveUserChange for user 0
04-01 10:52:16.485  3403  3403 E EnterpriseSharedDevicePolicy: isSharedDeviceEnabled
04-01 10:52:16.485  3403  3403 I EnterpriseSharedDevicePolicy: isSharedDeviceEnabled in Service
04-01 10:52:16.485  3403  3403 I EnterpriseSharedDevicePolicy: Get Result: -1
04-01 10:52:16.485  3403  3403 I EnterpriseSharedDevicePolicy: status: false
04-01 10:52:16.485  3403  3403 D PersonaManagerService: getPersonasForUser(): returning null!
04-01 10:52:16.485  3403  3403 I KnoxTimeoutHandler: Shared devices show user statefalse
04-01 10:52:16.485  3403  3403 V AlarmManagerEXT: com.test.thalitest(10011) is removed.
04-01 10:52:16.490  3724  3724 D PanelView: There is/are notification(s) 
04-01 10:52:16.490  3403  3403 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1eda6fb6 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{2dadbe2f 6209:com.sec.android.service.health/u0a19}
04-01 10:52:16.490  6209  6209 D com.sec.android.service.health.upgrade.UninstallReceiver: onReceive()
04-01 10:52:16.490  6209  6209 I com.sec.android.service.health.upgrade.UninstallReceiver: onReceive called  PACKAGE_REMOVED package:com.test.thalitest
04-01 10:52:16.490  6209  6209 D com.sec.android.service.health.upgrade.UninstallReceiver: onReceive() : package name is not s health. Return !!!
04-01 10:52:16.495  3403  3432 E ActivityManager: checkUser: useridlist=null, currentuser=0
04-01 10:52:16.495  3403  3432 E ActivityManager: checkUser: useridlist=null, currentuser=0
04-01 10:52:16.495  3403  3432 E ActivityManager: checkUser: useridlist=null, currentuser=0
04-01 10:52:16.495  3403  3432 E ActivityManager: checkUser: useridlist=null, currentuser=0
04-01 10:52:16.495 11104 12747 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
04-01 10:52:16.510 12730 12730 D PopupuiReceiver: onReceive() getAction : android.intent.action.PACKAGE_REMOVED
04-01 10:52:16.510  3403  3432 I ActivityManager: Start proc 12752:com.samsung.android.app.assistantmenu/1000 for broadcast-4 com.samsung.android.app.assistantmenu/.AssistantMenuReceiver
04-01 10:52:16.520 12752 12752 E Zygote  : MountEmulatedStorage()
04-01 10:52:16.520 12752 12752 I libpersona: KNOX_SDCARD checking this for 1000
04-01 10:52:16.520 12752 12752 E Zygote  : v2
04-01 10:52:16.520 12752 12752 I libpersona: KNOX_SDCARD not a persona
04-01 10:52:16.520 12752 12752 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
04-01 10:52:16.520  3403  3649 D SecContentProvider2: query(), uri = -1 selection = getSealedState
04-01 10:52:16.520 12752 12752 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
04-01 10:52:16.525  3403  4786 D SecContentProvider2: query(), uri = 15 selection = getSealedHideNotificationMessages
04-01 10:52:16.525 12730 12730 I PopupuiReceiver_KNOX: getSealedHideNotificationMessages : 0
04-01 10:52:16.525  3403  3850 D SecContentProvider2: query(), uri = 15 selection = getCheckCoverPopupState
04-01 10:52:16.525 12730 12730 I PopupuiReceiver_KNOX: getCheckCoverPopupState : false
04-01 10:52:16.525 12730 12730 D PopupuiReceiver: Action package removed
04-01 10:52:16.525 12752 12752 E Zygote  : accessInfo : 0
04-01 10:52:16.525 12752 12752 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
04-01 10:52:16.530  3403  3432 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1eda6fb6 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{19ccd75b 10818:com.sec.android.widgetapp.locationwidget/u0a22}
04-01 10:52:16.530 10818 10818 D LocationWidgetApplication: getLastUiLocationId() : mLastUiLocationId = -100
04-01 10:52:16.535 12715 12715 I SL_DEBUG: isLoggable:: isProductShip = 1
04-01 10:52:16.535 12715 12715 I SL_DEBUG: isLoggable:: SL_DEBUG_EXIST = false
04-01 10:52:16.540  4012  4012 D Launcher.Model: reloadBadges entered.
04-01 10:52:16.540 10930 10948 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
04-01 10:52:16.540 10930 10948 D BadgeProvider: sendNotify, [notify] : null
04-01 10:52:16.540 10930 10948 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
04-01 10:52:16.540 10930 10948 D BadgeProvider: update, [uri.query] : null
04-01 10:52:16.540 10930 10948 D BadgeProvider: update, [BadgeCount] : badgecount=0
04-01 10:52:16.540 10930 10948 D BadgeProvider: update, [UpdateCount] : 1
04-01 10:52:16.550  3403  3432 V BroadcastQueue: [backgroundsplit_2] Process cur broadcast BroadcastRecord{28189798 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{3d372561 10751:com.samsung.android.snote/u0a160}
04-01 10:52:16.550 12752 12752 D TimaKeyStoreProvider: TimaSignature is unavailable
04-01 10:52:16.555 12752 12752 D ActivityThread: Added TimaKeyStore provider
04-01 10:52:16.565  3403  4396 V BroadcastQueue: [backgroundsplit_1] Process cur broadcast BroadcastRecord{1490ef2 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{1bec4829 12752:com.samsung.android.app.assistantmenu/1000}
04-01 10:52:16.565 10930 10940 D BadgeProvider: query, [selection] : null
04-01 10:52:16.575  3403  3432 E ActivityManager: checkUser: useridlist=null, currentuser=0
04-01 10:52:16.575  3403  3432 E ActivityManager: checkUser: useridlist=null, currentuser=0
04-01 10:52:16.575  3403  3432 E ActivityManager: checkUser: useridlist=null, currentuser=0
04-01 10:52:16.575  3403  3432 E ActivityManager: checkUser: useridlist=null, currentuser=0
04-01 10:52:16.585 12770 12770 E Zygote  : MountEmulatedStorage()
04-01 10:52:16.585 12770 12770 E Zygote  : v2
04-01 10:52:16.590 12770 12770 I libpersona: KNOX_SDCARD checking this for 1000
04-01 10:52:16.590 12770 12770 I libpersona: KNOX_SDCARD not a persona
04-01 10:52:16.590 12770 12770 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
04-01 10:52:16.590  3403  3432 I ActivityManager: Start proc 12770:com.sec.pcw.device/1000 for broadcast-3 com.sec.pcw.device/.receiver.SYSTEMReceiver
04-01 10:52:16.590 12770 12770 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
04-01 10:52:16.595 12770 12770 E Zygote  : accessInfo : 0
04-01 10:52:16.595 12770 12770 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
04-01 10:52:16.595  3403  3432 E ActivityManager: checkUser: useridlist=null, currentuser=0
04-01 10:52:16.595  3403  3432 E ActivityManager: checkUser: useridlist=null, currentuser=0
04-01 10:52:16.595  3403  3432 E ActivityManager: checkUser: useridlist=null, currentuser=0
04-01 10:52:16.595  3403  3432 E ActivityManager: checkUser: useridlist=null, currentuser=0
04-01 10:52:16.605  3724  3724 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
04-01 10:52:16.615  3724  3724 D PanelView: There is/are notification(s) 
04-01 10:52:16.615  3724  3724 D PanelView: kidsfalse mQsExpansionEnabled:true
04-01 10:52:16.615 12770 12770 D TimaKeyStoreProvider: TimaSignature is unavailable
04-01 10:52:16.620 12785 12785 I libpersona: KNOX_SDCARD checking this for 10183
04-01 10:52:16.620 12770 12770 D ActivityThread: Added TimaKeyStore provider
04-01 10:52:16.620 12785 12785 I libpersona: KNOX_SDCARD not a persona
04-01 10:52:16.620 12785 12785 E Zygote  : MountEmulatedStorage()
04-01 10:52:16.620 12785 12785 E Zygote  : v2
04-01 10:52:16.620  3724  3724 D PanelView: There is/are notification(s) 
04-01 10:52:16.620  3724  3724 D PanelView: kidsfalse mQsExpansionEnabled:true
04-01 10:52:16.620 12785 12785 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
04-01 10:52:16.620  3403  3432 I ActivityManager: Start proc 12785:com.samsung.android.provider.shootingmodeprovider/u0a183 for broadcast-4 com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver
04-01 10:52:16.630 12785 12785 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
04-01 10:52:16.630 12785 12785 E Zygote  : accessInfo : 0
04-01 10:52:16.630 12785 12785 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
04-01 10:52:16.630  3403  3851 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1eda6fb6 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{261648dc 12770:com.sec.pcw.device/1000}
04-01 10:52:16.635 12752 12752 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2129 android.content.ContextWrapper.startService:534 android.content.ContextWrapper.startService:534 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3509 
04-01 10:52:16.635  3403  4793 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
04-01 10:52:16.645  3403  3432 E ActivityManager: checkUser: useridlist=null, currentuser=0
04-01 10:52:16.645  3403  3432 E ActivityManager: checkUser: useridlist=null, currentuser=0
04-01 10:52:16.645  3403  3432 E ActivityManager: checkUser: useridlist=null, currentuser=0
04-01 10:52:16.645  3403  3432 E ActivityManager: checkUser: useridlist=null, currentuser=0
04-01 10:52:16.660 12802 12802 E Zygote  : MountEmulatedStorage()
04-01 10:52:16.660 12802 12802 I libpersona: KNOX_SDCARD checking this for 1000
04-01 10:52:16.660 12802 12802 E Zygote  : v2
04-01 10:52:16.660 12802 12802 I libpersona: KNOX_SDCARD not a persona
04-01 10:52:16.660 12802 12802 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
04-01 10:52:16.665 11104 12749 E SQLiteLog: (10) unixWrite() File Descriptor : 35 gets errno : 9
04-01 10:52:16.665 12802 12802 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
04-01 10:52:16.665 12802 12802 E Zygote  : accessInfo : 0
04-01 10:52:16.665 12802 12802 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
04-01 10:52:16.670 12785 12785 D TimaKeyStoreProvider: TimaSignature is unavailable
04-01 10:52:16.670  3403  3432 I ActivityManager: Start proc 12802:com.sec.knox.bridge/1000 for broadcast-4 com.sec.knox.bridge/.PersonaShortcutReceiver
04-01 10:52:16.670 12785 12785 D ActivityThread: Added TimaKeyStore provider
04-01 10:52:16.680  3403  3432 I ActivityManager: Killing 10466:com.vlingo.midas/u0a34 (adj 15): emptyCount ##31
04-01 10:52:16.685  3724  3724 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
04-01 10:52:16.695  3403  3649 V BroadcastQueue: [backgroundsplit_2] Process cur broadcast BroadcastRecord{28189798 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{2e0c50ba 12785:com.samsung.android.provider.shootingmodeprovider/u0a183}
04-01 10:52:16.695 11104 12749 E SQLiteDatabase: Error inserting name=isDevelopVersion value=false
04-01 10:52:16.695 11104 12749 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
04-01 10:52:16.695 11104 12749 E SQLiteDatabase: #################################################################
04-01 10:52:16.695 11104 12749 E SQLiteDatabase: Error Code : 778 (SQLITE_IOERR_WRITE)
04-01 10:52:16.695 11104 12749 E SQLiteDatabase: Caused By : Disk I/O error occurred during 'write' operation.
04-01 10:52:16.695 11104 12749 E SQLiteDatabase: 	(disk I/O error (code 778))
04-01 10:52:16.695 11104 12749 E SQLiteDatabase: #################################################################
04-01 10:52:16.695 11104 12749 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
04-01 10:52:16.695 11104 12749 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
04-01 10:52:16.695 11104 12749 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
04-01 10:52:16.695 11104 12749 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
04-01 10:52:16.695 11104 12749 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
04-01 10:52:16.695 11104 12749 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
04-01 10:52:16.695 11104 12749 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
04-01 10:52:16.695 11104 12749 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
04-01 10:52:16.695 11104 12749 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:186)
04-01 10:52:16.695 11104 12749 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
04-01 10:52:16.695 11104 12749 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
04-01 10:52:16.695 11104 12749 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
04-01 10:52:16.695 11104 12749 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
04-01 10:52:16.695 11104 12749 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
04-01 10:52:16.695 11104 12749 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
04-01 10:52:16.695 11104 12749 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
04-01 10:52:16.695 11104 12749 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
04-01 10:52:16.695 11104 12749 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
04-01 10:52:16.695 11104 12749 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
04-01 10:52:16.695 12802 12802 D TimaKeyStoreProvider: TimaSignature is unavailable
04-01 10:52:16.695 12802 12802 D ActivityThread: Added TimaKeyStore provider
04-01 10:52:16.700  3403  4002 I ActivityManager: Killing 10414:com.sec.android.automotive.drivelink/u0a102 (adj 15): emptyCount ##31
04-01 10:52:16.710  3403  4027 V BroadcastQueue: [backgroundsplit_1] Process cur broadcast BroadcastRecord{1490ef2 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{5b33b6b 12802:com.sec.knox.bridge/1000}
04-01 10:52:16.710 12770 12770 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
04-01 10:52:16.710 12770 12770 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
04-01 10:52:16.710 12770 12770 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
04-01 10:52:16.710 11104 12749 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
04-01 10:52:16.710 11104 12749 E SQLiteLog: (6922) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
04-01 10:52:16.710 11104 12749 E SQLiteDatabase: Error inserting name=DBVersion value=2003
04-01 10:52:16.710 11104 12749 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 6922)
04-01 10:52:16.710 11104 12749 E SQLiteDatabase: #################################################################
04-01 10:52:16.710 11104 12749 E SQLiteDatabase: Error Code : 6922 (SQLITE_IOERR_LOCK_EBADF)
04-01 10:52:16.710 11104 12749 E SQLiteDatabase: Caused By : I/O error happened due to bad file descriptor. There is possibility the partition changed to read-only.
04-01 10:52:16.710 11104 12749 E SQLiteDatabase: 	(disk I/O error (code 6922))
04-01 10:52:16.710 11104 12749 E SQLiteDatabase: #################################################################
04-01 10:52:16.710 11104 12749 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
04-01 10:52:16.710 11104 12749 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
04-01 10:52:16.710 11104 12749 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
04-01 10:52:16.710 11104 12749 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
04-01 10:52:16.710 11104 12749 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
04-01 10:52:16.710 11104 12749 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
04-01 10:52:16.710 11104 12749 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
04-01 10:52:16.710 11104 12749 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
04-01 10:52:16.710 11104 12749 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:187)
04-01 10:52:16.710 11104 12749 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
04-01 10:52:16.710 11104 12749 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
04-01 10:52:16.710 11104 12749 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
04-01 10:52:16.710 11104 12749 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
04-01 10:52:16.710 11104 12749 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
04-01 10:52:16.710 11104 12749 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
04-01 10:52:16.710 11104 12749 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
04-01 10:52:16.710 11104 12749 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
04-01 10:52:16.710 11104 12749 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
04-01 10:52:16.710 11104 12749 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
04-01 10:52:16.710 12770 12770 E SQLiteLog: (28) failed to open "/data/data/com.sec.pcw.device/databases/value.db" with flag (131138) and mode_t (0) due to error (30)
04-01 10:52:16.710 11104 12749 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
04-01 10:52:16.710 11104 12749 E SQLiteLog: (6922) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
04-01 10:52:16.715 11104 12749 E SQLiteDatabase: Error inserting name=LPCSystemVersion value=1.0.0
04-01 10:52:16.715 11104 12749 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 6922)
04-01 10:52:16.715 11104 12749 E SQLiteDatabase: #################################################################
04-01 10:52:16.715 11104 12749 E SQLiteDatabase: Error Code : 6922 (SQLITE_IOERR_LOCK_EBADF)
04-01 10:52:16.715 11104 12749 E SQLiteDatabase: Caused By : I/O error happened due to bad file descriptor. There is possibility the partition changed to read-only.
04-01 10:52:16.715 11104 12749 E SQLiteDatabase: 	(disk I/O error (code 6922))
04-01 10:52:16.715 11104 12749 E SQLiteDatabase: #################################################################
04-01 10:52:16.715 11104 12749 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
04-01 10:52:16.715 11104 12749 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
04-01 10:52:16.715 11104 12749 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
04-01 10:52:16.715 11104 12749 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
04-01 10:52:16.715 11104 12749 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
04-01 10:52:16.715 11104 12749 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
04-01 10:52:16.715 11104 12749 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
04-01 10:52:16.715 11104 12749 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
04-01 10:52:16.715 11104 12749 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:188)
04-01 10:52:16.715 11104 12749 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
04-01 10:52:16.715 11104 12749 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
04-01 10:52:16.715 11104 12749 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
04-01 10:52:16.715 11104 12749 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
04-01 10:52:16.715 11104 12749 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
04-01 10:52:16.715 11104 12749 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
04-01 10:52:16.715 11104 12749 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
04-01 10:52:16.715 11104 12749 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
04-01 10:52:16.715 11104 12749 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
04-01 10:52:16.715 11104 12749 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)

```
